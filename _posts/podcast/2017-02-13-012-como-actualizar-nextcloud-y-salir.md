---
layout: post
title: 'Como actualizar Nextcloud y salir del modo de "mantenimiento"'
date: 2017-02-13
image: img/ugeek.png
podcast_link: https://ia801601.us.archive.org/24/items/012CmoActualizarNextcloudY/%23012_c%c3%b3mo_actualizar_Nextcloud_y.mp3
tags: [podcast]
categories: podcast
comments: true
---
#### Publicado por Angel

Suscribete al Blog :  [RSS del Blog](http://feeds.feedburner.com/uGeekBlog) |

Suscribete al Podcast :  [RSS](http://feeds.feedburner.com/ugeek) , [ITunes](https://itunes.apple.com/us/podcast/ugeek/id1201421866?mt=2) , [ivoox](https://www.ivoox.com/podcast-ugeek_sq_f1383493_1.html)

<audio controls>
  <source src="https://ia801601.us.archive.org/24/items/012CmoActualizarNextcloudY/%23012_c%c3%b3mo_actualizar_Nextcloud_y.mp3" type="audio/mpeg">
Your browser does not support the audio element.
</audio>
<!-- ---------------------------------------------------Pon aquí el audio-------------------------------------------------------- -->


Cuando actualizamos Nextcloud puede salirnos una pantalla donde se indica que estamos en modo mantenimiento. Para solucionar este problema, nos conectamos con la terminal y escribimos estas dos lineas:<br /><br /><div class="separator" style="clear: both; text-align: center;"><a href="https://3.bp.blogspot.com/-CZjfjHdkegs/WKHt-ysImMI/AAAAAAAAAcY/bragPoyP1pg_zt-RJM0mrLb20qM-Pd5zwCLcB/s1600/cap.png" imageanchor="1" style="margin-left: 1em; margin-right: 1em;"><img border="0" height="400" src="https://3.bp.blogspot.com/-CZjfjHdkegs/WKHt-ysImMI/AAAAAAAAAcY/bragPoyP1pg_zt-RJM0mrLb20qM-Pd5zwCLcB/s400/cap.png" width="400" /></a></div><br /><br /><br />&gt;&gt; sudo -u root php occ maintenance:mode —off<br /><br />&gt;&gt; sudo -u www-data php occ maintenance:mode --off<br /><br />Y a disfrutar de nuevo de Nextcloud.<br /><br /><br />Suscribiros a los podcast de la comunidad Linux:<br /><br /><br /><br /><div class="separator" style="clear: both; text-align: center;"><a href="https://2.bp.blogspot.com/-6ywvBbppeZE/WKHuw_f7elI/AAAAAAAAAcc/PeulofwMvaEBqXZRZDcuvLwCBw--RVZ4QCLcB/s1600/CAP4.jpg" imageanchor="1" style="margin-left: 1em; margin-right: 1em;"><img border="0" height="320" src="https://2.bp.blogspot.com/-6ywvBbppeZE/WKHuw_f7elI/AAAAAAAAAcc/PeulofwMvaEBqXZRZDcuvLwCBw--RVZ4QCLcB/s320/CAP4.jpg" width="320" /></a></div><a href="http://www.ivoox.com/feed_fg_f1297890_filtro_1.xml">&nbsp;http://www.ivoox.com/feed_fg_f1297890_filtro_1.xml</a><br /><br /><div style="text-align: center;"><a href="https://4.bp.blogspot.com/-cyCSHxc_v7A/WKHuyz12MNI/AAAAAAAAAcg/lAyRui5h8748f3_Wlc3gvAgf3fxt1mNkQCLcB/s1600/txt.jpg" imageanchor="1" style="margin-left: 1em; margin-right: 1em;"><img border="0" height="320" src="https://4.bp.blogspot.com/-cyCSHxc_v7A/WKHuyz12MNI/AAAAAAAAAcg/lAyRui5h8748f3_Wlc3gvAgf3fxt1mNkQCLcB/s320/txt.jpg" width="320" /></a>&nbsp; </div><br /><a href="http://www.ivoox.com/salmorejo-geek_fg_f1206500_filtro_1.xml">http://www.ivoox.com/salmorejo-geek_fg_f1206500_filtro_1.xml&nbsp;</a><br /><br /><br />Podcasts actuales sobre GNU/Linux:<br />@salmorejogeek @system_inside @CompilanPodcast @KDE_Blog @birrasybits @uGeekPodcast ...<br />Alguno más? <br /><br /><br />Podéis encontrarme en Twitter como: @uGeekPodcast<br /><br />



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
