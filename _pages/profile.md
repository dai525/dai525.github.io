---
layout: archive
title: "Profile"
permalink: /profile/
author_profile: false
---

{% include base_path %}

## 基本情報

**氏名: 知念大樹**  
所属: 筑波大学 理工情報生命学術院 物理学学位プログラム 博士前期課程2年 / 筑波大学 計算科学研究センター  
指導教員：大須賀 健 教授  

〒305-8577 つくば市天王台1-1-1  
E-mail: daiki[at]ccs.tsukuba.ac.jp

## 学歴

- **2021年3月** 沖縄県立普天間高等学校 卒業
- **2021年4月** 琉球大学 理学部 物質地球科学科 物理系 入学
- **2025年3月** 琉球大学 理学部 物質地球科学科 物理系 卒業
- **2025年4月** 筑波大学大学院 数理物質科学研究群 博士前期課程 入学
- **2027年3月** 筑波大学大学院 数理物質科学研究群 博士前期課程 修了見込み

## Publications

<ul>
{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}
</ul>

## Talks

<ul>
{% for post in site.talks reversed %}
  {% include archive-single-talk-cv.html %}
{% endfor %}
</ul>