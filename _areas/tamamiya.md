---
layout: area
title: 田間宮地区の避難所
slug: tamamiya
---

{% assign this_slug = page.slug %}
{% assign this_area = site.data.areas | where: "slug", this_slug | first %}

<div style="background-color: {{ this_area.color }};">
  <strong><p style="color: white; padding-left: 0.4em;">{{ this_area.name }}</p></strong>
</div>

<img src="/shelters/map/6_tamamiya.avif" alt="田間宮マップ" />

<div style="background-color: {{ this_area.color }};">
  <strong><p style="color: white; padding-left: 0.4em;">{{ this_area.name }}地区 避難所一覧</p></strong>
</div>

coming soon ....
