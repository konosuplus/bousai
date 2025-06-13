---
layout: default
title: 鴻巣市避難所マップ
permalink: /shelters/
---

# 鴻巣市 避難所マップ　索引

<img src="/shelters/map/fullmap.avif" alt="鴻巣市全体マップ" />

## 地区ごとの避難所を見る

<div class="area-buttons">
  {% for area in site.data.areas %}
    <a href="/shelters/{{ area.slug }}/" class="area-btn" style="background-color: {{ area.color }};">
      {{ area.name }}
    </a>
  {% endfor %}
</div>
