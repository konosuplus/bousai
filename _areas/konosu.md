---
layout: area
title: 鴻巣地区の避難所
slug: konosu
---

{% assign this_slug = page.slug %}
{% assign this_area = site.data.areas | where: "slug", this_slug | first %}

<div style="background-color: {{ this_area.color }};">
  <strong><p style="color: white; padding-left: 0.4em;">{{ this_area.name }}</p></strong>
</div>

<img src="/shelters/map/3_konosu1.avif" alt="鴻巣地区北部マップ" />
<img src="/shelters/map/4_konosu2.avif" alt="鴻巣地区南部マップ" />

<div style="background-color: {{ this_area.color }};">
  <strong><p style="color: white; padding-left: 0.4em;">{{ this_area.name }}地区 避難所一覧</p></strong>
</div>

coming soon ....
