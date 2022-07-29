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
{{ item.publication-title }}{% if item.type == "journal" and item.volume %} {{ item.volume }}{% if item.issue %} ({{ item.issue }}){% endif %}{% endif %}{% if item.pages %}: {{ item.pages }}{% endif %}. ({{ item.year }})<br />
<span class="gray">
{% if item.pdf %}[ <a class="orange" href="{{ item.pdf | relative_url }}">PDF</a> ]{% endif %} {% if item.doi %}&ensp;[ <a class="orange" href="http://dx.doi.org/{{ item.doi }}">DOI</a> ]{% endif %} {% if item.preprint %}&ensp;[ <a class="orange" href="{{ item.preprint | relative_url }}">Preprint</a> ]{% endif %} {% if item.extended %}&ensp;[ <a class="orange" href="{{ item.extended | relative_url }}">Extended Version</a> ]{% endif %} {% if item.arxiv %}&ensp;[ <a class="orange" href="{{ item.arxiv}}">Arxiv</a> ]{% endif %} {% if item.bibtex %}&ensp;[ <a class="orange" href="{{ item.bibtex | relative_url }}">Bibtex</a> ]{% endif %} {% if item.artifact %}&ensp;[ <a class="orange" href="{{ item.artifact }}">Artifact</a> ]{% endif %} {% if item.talk %}&ensp;[ <a class="orange" href="{{ item.talk }}">Talk</a> ]{% endif %} {% if item.talk %}&ensp;[ <a class="gray" href="{{ item.errata }}">Errata</a> ]{% endif %}
</span>
{% endfor %}
