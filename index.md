---
title: Home
---

<div> 
    <img src="{{ "/images/octocat.jpg" | absolute_url }}" alt="github octocat" style="width:25%;" >    
</div>

# This is a test-blog to create static website with Jekyll and GitHub Pages 

With [GitHub pages](https://pages.github.com/) and [Jekyll](https://jekyllrb.com/) you can quickly create and publish a website for free! 
It is an ideal solution for creating a simple project or personal site to highlight your academic work. 

<div class="toc" markdown="1">
## Contents:

{% for lesson in site.pages %}
{% if lesson.nav == true %}- [{{ lesson.title }}]({{ lesson.url | absolute_url }}){% endif %}
{% endfor %}
</div>
