
---
title: Home
sidebar: nav
---
Summary:

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>


<h2>{{ site.data.samplelist.docs_list_title }}</h2>
<ul>
    {% for item in site.data.nav[page.sidebar] %}
      <li><a href="{{ item.url }}">{{ item.title }}</a></li>
    {% endfor %}
</ul>


