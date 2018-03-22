---
layout: post
title: "Instala un servidor de mensajeria tipo Whatsapp o Telegram y de Software
  Libre con XMPP/Jabber "
date: 2017-03-16
image: img/ugeek.png
podcast_link: https://ia601607.us.archive.org/17/items/ugeekpodcast_gmail_XMPP/XMPP.mp3
tags: [podcast]
categories: podcast
comments: true
---
#### Publicado por Angel

Suscribete al Blog :  [RSS del Blog](http://feeds.feedburner.com/uGeekBlog) |

Suscribete al Podcast :  [RSS](http://feeds.feedburner.com/ugeek) , [ITunes](https://itunes.apple.com/us/podcast/ugeek/id1201421866?mt=2) , [ivoox](https://www.ivoox.com/podcast-ugeek_sq_f1383493_1.html)

<audio controls>
  <source src="https://ia601607.us.archive.org/17/items/ugeekpodcast_gmail_XMPP/XMPP.mp3" type="audio/mpeg">
Your browser does not support the audio element.
</audio>
<!-- ---------------------------------------------------Pon aquí el audio-------------------------------------------------------- -->


<div class="separator" style="clear: both; text-align: center;"><a href="https://1.bp.blogspot.com/-LsBoYZadruY/WMmi82z79RI/AAAAAAAAAz0/bux6yXlG4XE-YLJE3a3BGGq4QqW32OCsACLcB/s1600/xmpp.jpg" imageanchor="1" style="margin-left: 1em; margin-right: 1em;"><img border="0" height="320" src="https://1.bp.blogspot.com/-LsBoYZadruY/WMmi82z79RI/AAAAAAAAAz0/bux6yXlG4XE-YLJE3a3BGGq4QqW32OCsACLcB/s320/xmpp.jpg" width="320" /></a></div>Vamos a instalar un servidor de mensajería instantánea, donde los mensajes, llamadas... No pasaran por servidores ajenos, sino que pasará por nuestro servidor en nuestra red local o desde cualquier parte utilizando nuestra <a href="http://ugeekpodcast.blogspot.com.es/2017/03/027-instala-una-vpn-openvpn-en-ubuntu-o.html">OpenVpn</a>.<br /><br />Para instalar este servicio es muy simple ya que el servidor esta en los repositorios tanto de Raspbian en Raspberry Pi como en Ubuntu.<br /><br />Introducimos en la terminal:<br /><br /><span style="background-color: yellow;">sudo apt-get install ejabberd</span><br /><br />Una vez instalado escribimos la siguiente linea en la terminal y editamos tanto el nombre de servidor, nombre de administrador y contraseña.<br /><br />Yo en mi caso puse:<br /><br />Servidor: localhost<br />Administrador: admin<br />Contraseña: password<br /><br /><span style="background-color: yellow;">sudo dpkg-reconfigure ejabberd</span><br /><br />Una vez configurado, escribimos en nuestro navegador:<br /><br /><span style="background-color: yellow;">http://ip:5280/admin</span><br /><br />Para acceder al la web de administración, nos pedirá el usuario y contraseña.<br />En mi caso como os había dicho antes, seria:<br /><br />Nombre de usuario: admin@localhost<br />Contraseña: password<br /><br />Se abrirá la web de administración. Ahora para crear los usuarios, entraremos en:<br /><br />Virtualhost / localhost / users &gt; creamos el nombre del usuario y contraseña<br /><br /><br /><br />Ahora solo nos queda utilizar la aplicación de mensajería que mas os guste y cumpla con el protocolo XMPP o Jabber.<br /><br />Yo en <span style="font-size: small;"><a href="https://f-droid.org/repository/browse/?fdfilter=xmpp&amp;fdid=eu.siacs.conversations">Conversations</a>, que podemos descargar gratuitamente desde los repositorios de <a href="https://f-droid.org/">F-Droid</a> y <a href="http://www.astrachat.com/">AstraChat,</a> Que funciona tanto en Android como IPhone y ademas incluye llamadas Voip.</span><br /><br /><span style="font-size: small;">Recordar que no unicamente hay aplicaciones para móvil, sino también para PC. </span><br /><br /><br /><br />Únete al canal el Telegram en:<br />https://telegram.me/uGeek<br /><br /><br /><br />



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
