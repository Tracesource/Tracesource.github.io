---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


<span class='anchor' id='about-me'></span>

 <!--这里引入的顺序就是主页显示各个模块的顺序-->

{% include_relative components/intro.md %}
{% include_relative components/news.md %}
{% include_relative components/pub.md %}
{% include_relative components/honors.md %}
{% include_relative components/edu.md %}