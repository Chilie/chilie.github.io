---
layout: page
title: About me 
cv-zh: 'cv-zh.html'
cv-en: 'cv-en.html'
---

This is a static page. It could be an 'about page' if you'd like.

我2018年7月从[北京大学数学科学学院](http://www.math.pku.edu.cn "北大数院")博士毕业，没有找到合适的工作，现在在[北京计算科学研究中心](http://www.csrc.ac.cn)做博士后研究

现在主要做相位恢复的相关研究工作，关心非凸优化算法的应用

你可以在[知乎](http://www.zhihu.com)上找到我

下面是我的
{% if page.cv-zh %} <a href='{{ site.baseurl }}{{ page.cv-zh }}'> 中文简历 </a> {% endif %}

下面是我的[英文简历]
{% if page.cv-en %} <a href='{{ site.baseurl }}{{ page.cv-en }}'> 英文简历 </a> {% endif %}

