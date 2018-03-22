---
layout: post
title: "Mumble, VoIP de Software Libre. Nextcloud, Wallabag y kdenlive"
date: 2017-03-21
image: img/ugeek.png
podcast_link: https://ia601609.us.archive.org/0/items/030Mumble/%23030%20Mumble.mp3
tags: [podcast]
categories: podcast
comments: true
---
#### Publicado por Angel

Suscribete al Blog :  [RSS del Blog](http://feeds.feedburner.com/uGeekBlog) |

Suscribete al Podcast :  [RSS](http://feeds.feedburner.com/ugeek) , [ITunes](https://itunes.apple.com/us/podcast/ugeek/id1201421866?mt=2) , [ivoox](https://www.ivoox.com/podcast-ugeek_sq_f1383493_1.html)

<audio controls>
  <source src="https://ia601609.us.archive.org/0/items/030Mumble/%23030%20Mumble.mp3" type="audio/mpeg">
Your browser does not support the audio element.
</audio>
<!-- ---------------------------------------------------Pon aquí el audio-------------------------------------------------------- -->


Llega <a href="https://kdenlive.org/">kdenlive</a> para Windows.<br /><br />Hacia donde va el desarrollo de Wallabag.<br /><br />Nextcloud la nube por excelencia de Software Libre.<br /><br />Instalemos un servidor de Mumble para tener conversaciones grupales via VoIP.<br /><br />Para instalar el servidor en Ubuntu y Raspberry Pi.<br /><br /><span style="background-color: yellow;">sudo apt-get install mumble-server</span><br /><br />Editamos el archivo, para poner la contraseña:<br /><br /><span style="background-color: yellow;">sudo nano /etc/mumble-server.ini</span><br /><br />Buscamos la linea:<br /><span style="background-color: yellow;"><br /></span><span style="background-color: yellow;"># Password to join server<br />serverpassword=aquivamicontraseña</span><br /><br />Por último iniciamos el servicio poniendo esta linea acabado en start o stop, para pararlo.<br /><br /><br /><br /><br /><br /><br /><br /><span style="background-color: yellow;">sudo /etc/init.d/mumble-server start</span><br /><br />Podéis instalar Plumble, que es la app Android, desde <a href="https://f-droid.org/repository/browse/?fdfilter=plumble&amp;fdid=com.morlunk.mumbleclient">F-Droid</a> o desde el canal de <a href="https://t.me/uGeek/51">uGeek</a>



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
