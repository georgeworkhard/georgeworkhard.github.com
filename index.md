---
layout: page
title: George Huang
tagline: tech, travelling
---
{% include JB/setup %}


<img src="./assets/themes/imgs/1627385056.jpg" style="zoom:20%" alt="photos"/>


SDE focusing on backend development.
I write articles in tech, travelling, life etc. 
- I use this page to practice concise, persuative writing. 
- I use this page to remind myself to study, summerize and recap various tech topics so that I can keep learning.
- I use this page to post my travelling experience


## Recent Posts

Here's the "recent posts list".

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## Coming-soon

Planning to write in articles related to these topics in the near future.

