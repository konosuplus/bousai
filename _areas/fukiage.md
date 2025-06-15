---
layout: area
title: 吹上地区の避難所
slug: fukiage
---

{% assign this_slug = page.slug %}
{% assign this_area = site.data.areas | where: "slug", this_slug | first %}

<div style="background-color: {{ this_area.color }};">
  <strong><p style="color: white; padding-left: 0.4em;">{{ this_area.name }}</p></strong>
</div>

<img src="/shelters/map/11_fukiage1.avif" alt="吹上地区北部マップ" />
<img src="/shelters/map/12_fukiage2.avif" alt="吹上地区南部マップ" />

<div style="background-color: {{ this_area.color }};">
  <strong><p style="color: white; padding-left: 0.4em;">{{ this_area.name }}地区 避難所一覧</p></strong>
</div>

coming soon ....
