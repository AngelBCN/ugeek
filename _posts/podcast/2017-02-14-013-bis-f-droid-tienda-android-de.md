---
layout: post
title: "bis F-Droid Tienda Android de aplicaciones de Software Libre y Actualizar
  las Noticias en Nextcloud."
date: 2017-02-14
image: img/ugeek.png
podcast_link: https://ia801604.us.archive.org/21/items/013FDroidAplicacionesDeSoftwareLibre/%23013%20F-Droid%20Aplicaciones%20de%20Software%20Libre.mp3
tags: [podcast]
categories: podcast
comments: true
---
#### Publicado por Angel

Suscribete al Blog :  [RSS del Blog](http://feeds.feedburner.com/uGeekBlog) |

Suscribete al Podcast :  [RSS](http://feeds.feedburner.com/ugeek) , [ITunes](https://itunes.apple.com/us/podcast/ugeek/id1201421866?mt=2) , [ivoox](https://www.ivoox.com/podcast-ugeek_sq_f1383493_1.html)

<audio controls>
  <source src="https://ia801604.us.archive.org/21/items/013FDroidAplicacionesDeSoftwareLibre/%23013%20F-Droid%20Aplicaciones%20de%20Software%20Libre.mp3" type="audio/mpeg">
Your browser does not support the audio element.
</audio>
<!-- ---------------------------------------------------Pon aquí el audio-------------------------------------------------------- -->


<div class="separator" style="clear: both; text-align: center;"><a href="https://3.bp.blogspot.com/-qaRvyg-WypQ/WKIVq3fzPiI/AAAAAAAAAdM/428Faox9zjAfeLXLd9gQ4DhWE9WmIptegCEw/s1600/CAP4.jpg" imageanchor="1" style="margin-left: 1em; margin-right: 1em;"><img border="0" height="168" src="https://3.bp.blogspot.com/-qaRvyg-WypQ/WKIVq3fzPiI/AAAAAAAAAdM/428Faox9zjAfeLXLd9gQ4DhWE9WmIptegCEw/s320/CAP4.jpg" width="320" /></a></div><a href="https://f-droid.org/">https://f-droid.org/</a><br /><br />Para hacer que se actualice Nextcloud cada 15 minutos:<br /><br />&gt;&gt; sudo crontab -u www-data -e<br /><br />Copiamos al final del archivo:<br /><br />&gt;&gt; */15 * * * * php -f /var/www/html/nextcloud/cron.php<br /><br /><br />



<!-- TAGS Y COMENTARIOS -->

Tags: {% assign sorted_tags = page.tags | sort %} {% for tag in sorted_tags %} , <span class="tag"><a href="/search#{{ tag }}">{{ tag }}</a></span> {% endfor %},



{% if page.comments %}
<div id="disqus_thread"></div>
<script>

/**
*  RECOMMENDED CONFIGURATION VARIABLES: EDIT AND UNCOMMENT THE SECTION BELOW TO INSERT DYNAMIC VALUES FROM YOUR PLATFORM OR CMS.
*  LEARN WHY DEFINING THESE VARIABLES IS IMPORTANT: https://disqus.com/admin/universalcode/#configuration-variables*/
/*
var disqus_config = function () {
this.page.url = PAGE_URL;  // Replace PAGE_URL with your page's canonical URL variable
this.page.identifier = PAGE_IDENTIFIER; // Replace PAGE_IDENTIFIER with your page's unique identifier variable
};
*/
(function() { // DON'T EDIT BELOW THIS LINE
var d = document, s = d.createElement('script');
s.src = 'https://https-angelbcn-github-io-ugeek.disqus.com/embed.js';
s.setAttribute('data-timestamp', +new Date());
(d.head || d.body).appendChild(s);
})();
</script>
<noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript>


{% endif %}
