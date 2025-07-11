---
title: Projects
description: What I'm doing
permalink: /projects/
layout: page
comments: false
---

Below are the current projects I'm currently working on, with a short description.

### Tournicator
*Better version of Tournify.*  

<div>
    {%- for post in site.tags["tournicator"] -%}
    <article class="post-item" id="results-container">
        <span class="post-item-date">{{ post.date | date: "%b %d, %Y" }}</span>
        <h3 class="post-item-title">
        <a href="{{ post.url }}">{{ post.title | escape }}</a>
        </h3> 
    </article>
    {%- endfor -%}  
</div>

### Fantasy Jupiler Pro League Engine  
*Training an AI model to predict the number of points scored by a player in the FJPL. With the goal to win some epic prizes.*  

<div>
    {%- for post in site.tags["fjpl"] -%}
    <article class="post-item" id="results-container">
        <span class="post-item-date">{{ post.date | date: "%b %d, %Y" }}</span>
        <h3 class="post-item-title">
            <a href="{{ post.url }}">{{ post.title | escape }}</a>
        </h3> 
    </article>
    {%- endfor -%}
</div>