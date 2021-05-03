---
layout: default
---
# SMT Competitions

{% for competition in site.data.competitions.competitions %}
<h2>
  <a id="smtcomp{{ competition.year }}" href="{{ competition.url }}" target="_blank">
    SMT Competition {{ competition.year }}
  </a>
</h2>
**Competing Version:** &nbsp;{% if competition.version %} {{ competition.version }} ([submitted binary]({{ competition.binary }})){% else %}[submitted binary]({{ competition.binary }}){% endif %}
<br/>
**System Description**: &nbsp;[{{ competition.sysdesc-title }}]({{ competition.sysdesc-url }})

### Divisions Entered
{% for track in competition.entered %}
- <span class="orange">{{ track.track }}:</span> &nbsp;{{ track.divisions }}
{% endfor %}

### Division Awards
{% for track in competition.tracks-awards %}
<b>{{ track.track }}</b>
<ul class="awards">
{% for award in track.divisions %}
  <li class="awards"><span class="orange">{{ award.place }}<sup>{% if award.place == 1 %}st{% elsif award.place == 2 %}nd{% else %}rd{% endif %}</sup></span> place in division <a href="{{ award.url }}">{{ award.division }}</a></li>
{% endfor %}
</ul>
{% endfor %}

### Competition-Wide Awards
{% for award in competition.competition-awards %}
<b>{{ award.award }}</b>
<ul class="awards">
{% for award in award.tracks %}
  <li class="awards"><span class="orange">{{ award.place }}<sup>{% if award.place == 1 %}st{% elsif award.place == 2 %}nd{% else %}rd{% endif %}</sup></span> place ({% if award.place == 1 %}gold{% elsif award.place == 2 %}silver{% else %}bronze{% endif %}) in the <a href="{{ award.url }}">{{ award.track }}</a></li>
{% endfor %}
</ul>

{% endfor %}

{% endfor %}
