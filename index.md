---
layout: page
title: Justyna Wardzińska - Blog
tagline: Supporting tagline
---
{% include JB/setup %}

Szybki początek: [Jekyll Quick Start](http://jekyllbootstrap.com/usage/jekyll-quick-start.html)

Dokumentacja: [Jekyll Bootstrap](http://jekyllbootstrap.com)

## Plik konfiguracyjny

W pliku `_config.yml` zmieniłam przykładowe dane na swoje 
Poniżej pokazane jest jakie dane były uprzednio
    
    title : My Blog =)
    
    author :
      name : Name Lastname
      email : blah@email.test
      github : username
      twitter : username



    
## Sample Posts

This blog contains sample posts which help stage pages and blog data.
When you don't need the samples anymore just delete the `_posts/core-samples` folder.

    $ rm -rf _posts/core-samples

Here's a sample "posts list".

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## To-Do
Spersonalizować bloga.

Pozbyć się nadwyżkowych linków w zakładce pages i posts


