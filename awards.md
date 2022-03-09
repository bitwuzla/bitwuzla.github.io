---
layout: default
---

# Awards

{% assign years = site.data.awards.awards | map: "year" | uniq | sort | reverse %}
{% for year in years %}
{% assign yearStr = year | append: "" %}
{% assign yearInt = year | plus: 0 %}
{% assign entries = site.data.awards.awards | where_exp: "e","e.year == year" %}
{% for item in entries %}
- [{{ item.event }}]({{ item.event_url }})
  ([details]({{ item.details | relative_url }}))
  - <b>entered:</b> {{ item.entered.divisions }} divisions
  - <b>overall:</b> {{ item.gold.divisions | plus: item.gold.competition-wide }} gold medals
  - <b>division awards:</b> {{ item.gold.divisions }} gold medals (out of {{ item.entered.awards }})
  {% if item.gold.competition-wide %}- <b>competition-wide awards:</b> {{ item.gold.competition-wide }} gold medals{% endif %}
{% endfor %}
{% endfor %}



