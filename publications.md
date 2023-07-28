---
layout: default
---

# Bibtex

{% include_relative bibtex-include.md %}

# Publications

{% for item in site.data.publications.papers %}
{% if item.id %}<a name="{{ item.id }}"></a>{% endif %}
{% for cauthor in item.author %}{{ cauthor.name}}{% if forloop.last == false %}, {% endif %}{% endfor %}.
{% if item.pdf %}<a href="{{ item.pdf | relative_url }}">{{ item.title }}</a>{% else %}{{ item.title }}{% endif %}.
{{ item.publication-title }}{% if item.type == "journal" and item.volume %} {{ item.volume }}{% if item.issue %} ({{ item.issue }}){% endif %}{% endif %}{% if item.pages %}: {{ item.pages }}{% endif %}. ({{ item.year }}){% if item.awards %}<span class="awards">{% if item.awards.url %}<a href="{{ item.awards.url }}">{% endif %}{% for award in item.awards.awards %}<br/><b>{{ award }}</b>{% endfor %}{% if item.awards.url %}</a>{% endif %}</span>{% endif %}<br />
<span class="gray">
{% if item.pdf %}[ <a class="dgray" href="{{ item.pdf | relative_url }}">PDF</a> ]{% endif %} {% if item.doi %}&ensp;[ <a class="dgray" href="http://dx.doi.org/{{ item.doi }}">DOI</a> ]{% endif %} {% if item.preprint %}&ensp;[ <a class="dgray" href="{{ item.preprint | relative_url }}">Preprint</a> ]{% endif %} {% if item.extended %}&ensp;[ <a class="dgray" href="{{ item.extended | relative_url }}">Extended Version</a> ]{% endif %} {% if item.arxiv %}&ensp;[ <a class="dgray" href="{{ item.arxiv}}">Arxiv</a> ]{% endif %} {% if item.bibtex %}&ensp;[ <a class="dgray" href="{{ item.bibtex | relative_url }}">Bibtex</a> ]{% endif %} {% if item.artifact %}&ensp;[ <a class="dgray" href="{{ item.artifact }}">Artifact</a> ]{% endif %} {% if item.talk %}&ensp;[ <a class="dgray" href="{{ item.talk }}">Talk</a> ]{% endif %} {% if item.talk %}&ensp;[ <a class="dgray" href="{{ item.errata }}">Errata</a> ]{% endif %}
</span>
{% endfor %}
