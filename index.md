---
layout: default
title: Consumer Notebook - Insider Tips For Consumers
---

<div id="home">
    <div class="posts">
    {% for post in site.posts %}
        <div class="post">
            <a href="{{ post.url }}"><h2>{{ post.title }}</h2></a>
            <div class="attribution">
                <span class="author">By {{ post.author }}</span> | 
                <span class="date">{{ post.date | date_to_string }}</span>
            </div>
        </div>
    {% endfor %}
    </div>

</div>
