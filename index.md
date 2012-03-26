---
layout: page
title: eWork!
tagline: Trustworthy, Digital Work Opportunities!
---
{% include JB/setup %}

## Sample Posts
<div class="row">
<div class="span4">
This blog contains sample posts which help stage pages and blog data.
</div>
<div class="span5 offset3">
When you don't need the samples anymore just delete the `_posts/core-samples` folder.

    $ rm -rf _posts/core-samples
</div>
</div>
Here's a sample "posts list".

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## To-Do

This theme is still unfinished. If you'd like to be added as a contributor, [please fork](http://github.com/plusjade/jekyll-bootstrap)!
We need to clean up the themes, make theme usage guides with theme-specific markup examples.


