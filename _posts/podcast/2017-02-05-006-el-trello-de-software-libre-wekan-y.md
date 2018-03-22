---
layout: post
title: "El Trello de Software Libre Wekan y Kanboard para Raspberry Pi. El sistema
  Kanban en tu servidor."
date: 2017-02-05
image: img/ugeek.png
podcast_link: https://ia601900.us.archive.org/18/items/ElTrelloDeSoftwareLibreWekan/El_Trello_de_software_libre_Wekan.mp3
tags: [podcast]
categories: podcast
comments: true
---
#### Publicado por Angel

Suscribete al Blog :  [RSS del Blog](http://feeds.feedburner.com/uGeekBlog) |

Suscribete al Podcast :  [RSS](http://feeds.feedburner.com/ugeek) , [ITunes](https://itunes.apple.com/us/podcast/ugeek/id1201421866?mt=2) , [ivoox](https://www.ivoox.com/podcast-ugeek_sq_f1383493_1.html)

<audio controls>
  <source src="https://ia601900.us.archive.org/18/items/ElTrelloDeSoftwareLibreWekan/El_Trello_de_software_libre_Wekan.mp3" type="audio/mpeg">
Your browser does not support the audio element.
</audio>
<!-- ---------------------------------------------------Pon aquí el audio-------------------------------------------------------- -->


Hoy os traigo un par de aplicaciones para desarrollar vosotros el sistema Kanban y no tener que usar necesariamente aplicaciones como Trello. Como sabéis, si instaláis estas aplicaciones en vuestro servidor o raspberry Pi, tendréis vosotros vuestra información y no en servidores ajenos. <br /><br />Sistema Kanban. <a href="https://es.wikipedia.org/wiki/Kanban">https://es.wikipedia.org/wiki/Kanban</a><br /><br /><div class="separator" style="clear: both; text-align: center;"><a href="https://wekan.io/" style="margin-left: 1em; margin-right: 1em;"><img alt="Resultado de imagen de wekan" class="irc_mi iOXvv5bMLA2c-pQOPx8XEepE" height="207" src="https://wekan.io/static/screenshot.jpeg" style="margin-top: 13px;" width="400" />&nbsp;</a></div><div class="separator" style="clear: both; text-align: center;"><br /></div><div class="separator" style="clear: both; text-align: left;"><a href="https://wekan.io/">https://wekan.io/</a></div><h4><b>Wekan</b> </h4>Para instalar en ubuntu:&nbsp; sudo snap install wekan-ondra<br /><br />Para poder acceder a Wekan desde vuestro navegador, tenéis que poner vuestra ip:8080 <br /><br /><br /><br /><br /><br /><b>kanboard </b><br /><br />Kanboard la podremos instalar en nuestra Raspberri Pi ya que es una aplicación muy liviana y que apenas consume recursos.<br /><b> </b><br /><br /><br /><br /><br /><br /><div class="separator" style="clear: both; text-align: center;"><a href="https://2.bp.blogspot.com/-0gyOTYRqksA/WJdywcPc5wI/AAAAAAAAATk/tMqP1noqUDk0lAM7pKg2ROZqXk73SD7fgCLcB/s1600/edee9450049a28c2a21fc73d2069f8b1_medium.png" imageanchor="1" style="margin-left: 1em; margin-right: 1em;"><img border="0" height="187" src="https://2.bp.blogspot.com/-0gyOTYRqksA/WJdywcPc5wI/AAAAAAAAATk/tMqP1noqUDk0lAM7pKg2ROZqXk73SD7fgCLcB/s400/edee9450049a28c2a21fc73d2069f8b1_medium.png" width="400" /></a></div>Una vez descomprimido el archivo en la carpeta donde tiene acceso vuestro servidor web, para acceder debereis poner el nombre de usuario y contraseña por defecto:<br /><br />usuario: admin<br />contraseña: admin<br /><br /><br /><br /><a href="https://kanboard.net/"><cite class="_Rm">https://kanboard.net/</cite></a><b> </b><br /><br /><br /><br />



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
