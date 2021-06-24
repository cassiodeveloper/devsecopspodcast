---
layout: default
title: Episódios
---
<div class = "episodes">

<h2> Episódios </h2>
<ul>
{% for post in site.posts %}    
    {% if post.type == "main" %}
        <li>
            <a href="{{ post.url }}"> {{ post.title }} </a>
        </li>
    {% endif %}

{% endfor %}
</ul>

<h2> Episódios extras </h2>
<ul>
{% for post in site.posts %}    
    {% if post.type == "extra" %}
        <li>
            <a href="{{ post.url }}"> {{ post.title }} </a>
        </li>
    {% endif %}

{% endfor %}
</ul>
</div> 