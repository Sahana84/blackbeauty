---
layout: home
author_profile: true
---


<div> 
    <img src="{{ "/images/BlackBeauty.jpg" | absolute_url }}" alt="github octocat" style="width:37%;" >    
</div>

# Black Beauty

---



### Title: Black Beauty, Young Folks' Edition

### Author: Anna Sewell

### Release Date: March 31, 2004 

### Language: English

	{% for lesson in site.pages %}
	{% if lesson.nav == true %}- [{{ lesson.title }}]({{ lesson.url | absolute_url }}){% endif %}
	{% endfor %}
	</div>

