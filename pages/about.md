---
layout: page
title: About
description: 打码改变世界
keywords: Jing Wang, 王晶
comments: true
menu: 关于
permalink: /about/
---

我是王晶，测试道路上的小透明。

仰慕「测试之美」。

理论纸上谈，测试靠实践。

## 联系

{% for website in site.data.social %}
* {{ website.sitename }}：[@{{ website.name }}]({{ website.url }})
{% endfor %}

## Skill Keywords

{% for category in site.data.skills %}
### {{ category.name }}
<div class="btn-inline">
{% for keyword in category.keywords %}
<button class="btn btn-outline" type="button">{{ keyword }}</button>
{% endfor %}
</div>
{% endfor %}
