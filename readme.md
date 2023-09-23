
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

<ul>
    {% for item in site.data.nav[page.sidebar] %}
      <li><a href="{{ item.url }}">{{ item.title }}</a></li>
    {% endfor %}
</ul>


- [Campaign Wiki: HomePage](https://campaignwiki.org/)
> We give you the opportunity to create a wiki for your own roleplaying campaigns.

- [Obsidian Portal - Campaign websites for Dungeons and Dragons and other tabletop RPGs | Obsidian Portal](https://www.obsidianportal.com/)
> Obsidian Portal takes the pain out of managing your tabletop RPG

