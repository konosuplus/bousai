---
layout: area
title: 笠原地区の避難所
slug: kasahara
---

{% assign this_slug = page.slug %}
{% assign this_area = site.data.areas | where: "slug", this_slug | first %}

<div style="background-color: {{ this_area.color }};">
  <strong><p style="color: white; padding-left: 0.4em;">{{ this_area.name }}</p></strong>
</div>

<img src="/shelters/map/8_kasahara.avif" alt="笠原地区マップ" />

<div style="background-color: {{ this_area.color }};">
  <strong><p style="color: white; padding-left: 0.4em;">{{ this_area.name }}地区 避難所一覧</p></strong>
</div>

coming soon ....
