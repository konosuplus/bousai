---

layout: area
title: 鴻巣地区の避難所
slug: konosu

---

{% assign this_slug = page.slug %}
{% assign this_area = site.data.areas | where: "slug", this_slug | first %}

<div style="background-color: {{ this_area.color }};">
  <strong>{{ this_area.name }}</strong>
</div>

<img src="/shelters/map/3_konosu1.avif" alt="鴻巣地区北部マップ" />
<img src="/shelters/map/4_konosu2.avif" alt="鴻巣地区南部マップ" />

## 鴻巣地区避難所一覧

- 鴻巣小学校
- 鴻巣中学校
- 市民体育館
