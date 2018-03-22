---
layout: post
title: "Instala una VPN (OpenVpn) en Ubuntu o Raspberry Pi con PiVpn"
date: 2017-03-14
image: img/ugeek.png
podcast_link: https://ia601606.us.archive.org/3/items/027InstalaTuVpnEnUbuntuORaspberryPi/%23027%20instala%20tu%20vpn%20en%20Ubuntu%20o%20Raspberry%20Pi.mp3
tags: [podcast]
categories: podcast
comments: true
---
#### Publicado por Angel

Suscribete al Blog :  [RSS del Blog](http://feeds.feedburner.com/uGeekBlog) |

Suscribete al Podcast :  [RSS](http://feeds.feedburner.com/ugeek) , [ITunes](https://itunes.apple.com/us/podcast/ugeek/id1201421866?mt=2) , [ivoox](https://www.ivoox.com/podcast-ugeek_sq_f1383493_1.html)

<audio controls>
  <source src="https://ia601606.us.archive.org/3/items/027InstalaTuVpnEnUbuntuORaspberryPi/%23027%20instala%20tu%20vpn%20en%20Ubuntu%20o%20Raspberry%20Pi.mp3" type="audio/mpeg">
Your browser does not support the audio element.
</audio>
<!-- ---------------------------------------------------Pon aquí el audio-------------------------------------------------------- -->


<div class="separator" style="clear: both; text-align: left;"><a href="https://2.bp.blogspot.com/-2uqeovra9ys/WMb0IWdSt7I/AAAAAAAAAzk/IpAD5V3cmCoFtY2zSJYPlFDj19SB_7TbwCLcB/s1600/pivpn_logo.png" imageanchor="1" style="margin-left: 1em; margin-right: 1em;"><img border="0" src="https://2.bp.blogspot.com/-2uqeovra9ys/WMb0IWdSt7I/AAAAAAAAAzk/IpAD5V3cmCoFtY2zSJYPlFDj19SB_7TbwCLcB/s1600/pivpn_logo.png" /></a></div><span style="font-size: small;">He probado tanto en Raspberry Pi con Raspbian como en Ubuntu 16.04 y funciona perfectamente.</span><br /><span style="font-size: small;"><br /></span><span style="font-size: small;">Con este método, en unos 10 minutos tienes montada una OpenVpn totalmente funcional.</span><br /><span style="font-size: small;"><br /></span><span style="font-size: small;">Primero instalaremos el servidor introduciendo este comandos en la terminal:</span><br /><br /><span style="font-size: large;">&nbsp;<span style="background-color: yellow;"><br /></span></span><br /><pre><span style="font-family: Arial,Helvetica,sans-serif;"><span style="background-color: yellow;"><span style="font-size: large;">curl -L https://install.pivpn.io <span class="pl-k">|</span> bash</span></span></span></pre><br /><br /><br /><span style="font-size: small;">Tendremos que configurar una ip estática, osea una ip fija dentro de nuestra red local, para que nuestro router siempre se redirija a nuestro servidor OpenVpn (Raspberry Pi).</span><br /><br /><span style="font-size: small;">Esto podremos hacerlo desde nuestra Raspberry o incluso hay routers, donde podremos otorgar una ip fija en función de la MAC del dispositivo.</span><br /><br /><span style="font-size: small;">Por defecto el puerto para una OpenVpn seria el 1194, pero recomiendo el cambiarlo desde el router o en el momento de la instalación, que nos pregunta que puerto queremos utilizar. Si nos olvidamos, con el certificado que se genera al crear un usuario, podremos configurar el puerto, ya que queda perfectamente visible si lo abrimos con un editor de texto.</span><br /><br /><span style="font-size: small;">Vamos a crear el certificado:&nbsp;</span><br /><span style="font-size: small;">&nbsp;</span><br /><span style="font-size: small;"><span style="font-size: large;"><span style="background-color: yellow;">sudo pivpn add</span></span></span><br /><br /><span style="font-size: small;">Nos pedirá el nombre de usuario, ponemos el nombre que deseemos.</span><br /><br /><span style="font-size: small;">Después la contraseña. </span><br /><br /><span style="font-size: small;">Esto creará un certificado que se guardará en: /home/pi/ovpns/</span><br /><span style="font-size: small;"><br /></span><span style="font-size: small;">Copiamos este certificado en nuestro móvil y lo importamos <a href="https://play.google.com/store/apps/details?id=net.openvpn.openvpn&amp;hl=es_419">con la app de openvpn.&nbsp;</a></span><br /><span style="font-size: small;"><br /></span><span style="font-size: small;">La app nos pedirá nuestro usuario y contraseña y.... listo, ya se habrá conectado a nuestra vpn.</span><br /><span style="font-size: small;"><br /></span><span style="font-size: small;">Recordar que en el momento de instalación, deberemos poner nuestra ip <a href="http://www.cualesmiip.com/">(http://www.cualesmiip.com/) </a>exterior, la que nos otorga nuestra compañia de telefonía.</span><br /><span style="font-size: small;">Si no lo hemos hecho antes o nuestra ip cambia, podemos editarlo desde el certificado con el editor de texto como antes he comentado.</span>



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
