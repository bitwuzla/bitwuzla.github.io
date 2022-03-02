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
- [{{ item.event }}]({{ item.event_url }}):&nbsp; {{ item.gold}} gold medals
  ([details]({{ item.details | relative_url }}))
{% endfor %}
{% endfor %}



