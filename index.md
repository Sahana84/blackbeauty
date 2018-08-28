

<div> 
    <img src="{{ "/images/BlackBeauty.jpg" | absolute_url }}" alt="github octocat" style="width:37%;" >    
</div>
<div>
 <html>
   <head>
	<!-- Load JQuery -->
	<script type="text/javascript" src="http://code.jquery.com/jquery-latest.min.js"></script>
	<!-- Load jquery.cookie plugin (optional) -->
	<script type="text/javascript" src="/navgoco/src/jquery.cookie.js"></script>
	<!-- Load jquery.navgoco plugin js and css files -->
	<script type="text/javascript" src="/navgoco/src/jquery.navgoco.js"></script>
	<link rel="stylesheet" href="/navgoco/src/jquery.navgoco.css" type="text/css" media="screen" />
  </head>
     <body>
         <script type="text/javascript">
	$(document).ready(function() {
		$('.nav').navgoco();
	});
</script>
         <ul class="nav">
	<li><a href="#">1. Menu</a>
		<ul>
			<li><a href="#">1.1 Submenu</a></li>
			<li><a href="#">1.2 Submenu</a></li>
			<li><a href="#">1.3 Submenu</a></li>
		</ul>
	</li>
<!-- etc... -->
</ul>
     </body>
 </html>
</div>

# Black Beauty

---



### Title: Black Beauty, Young Folks' Edition

### Author: Anna Sewell

### Release Date: March 31, 2004 

### Language: English




<div class="toc" markdown="1">
## Contents:

{% for lesson in site.pages %}
{% if lesson.nav == true %}- [{{ lesson.title }}]({{ lesson.url | absolute_url }}){% endif %}
{% endfor %}
</div>

