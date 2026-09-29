---
title: Equipment
nav:
  order: 2
  tooltip: Our equipment, datasets, and more
---

# {% include icon.html icon="fa-solid fa-wrench" %}Equipment

Check out our equipment below!

{% include tags.html tags="publication, resource, website" %}

{% include search-info.html %}

{% include section.html %}

## Featured

{% include list.html component="card" data="equipment" filter="group == 'featured'" %}

{% include section.html %}

## More

{% include list.html component="card" data="equipment" filter="!group" style="small" %}
