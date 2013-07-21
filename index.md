---
layout: page
title: Home

---
{% include JB/setup %}


<div class="container">
  <h3><q><em>"Technology does not drive change...it enables change"</em></q></h3>
  <h4><em>Unknown</em></h4>
</div>
<br>
<!-- <h1>Test</h1> -->

<!-- <div class="contact">
  <p>
    <a href="http://github.com/Hjack/">github.com/Hjack</a><br />
    <a href="http://twitter.com/HakimuJ/">twitter.com/HakimuJ</a><br />
    <a href="http://www.linkedin.com/pub/hakimu-jackson/51/3a6/a08">LinkedIn</a><br />
  </p>
</div> -->

<!-- Read [Jekyll Quick Start](http://jekyllbootstrap.com/usage/jekyll-quick-start.html)

Complete usage and documentation available at: [Jekyll Bootstrap](http://jekyllbootstrap.com)

## Update Author Attributes

In `_config.yml` remember to specify your own data:
    
    title : My Blog =)
    
    author :
      name : Name Lastname
      email : blah@email.test
      github : username
      twitter : username

The theme should reference these variables whenever needed.
    
## Sample Posts

This blog contains sample posts which help stage pages and blog data.
When you don't need the samples anymore just delete the `_posts/core-samples` folder.

    $ rm -rf _posts/core-samples -->

Blog Posts...

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

<!-- ## To-Do

This theme is still unfinished. If you'd like to be added as a contributor, [please fork](http://github.com/plusjade/jekyll-bootstrap)!
We need to clean up the themes, make theme usage guides with theme-specific markup examples.
 -->

