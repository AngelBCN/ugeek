---
layout: post
title: "La Nube más Segura Dentro y Fuera de tu Red Local"
date: 2018-04-26 5:40
author: Angel
categories: podcast
image: /img/ugeek.png
podcast_link: https://ia601500.us.archive.org/33/items/syncthing/syncthing.mp3
tags: [podcast, android, syncthing, vpn]
comments: true
---
#### Publicado por Angel

[https://ugeek.github.io/](https://ugeek.github.io/)

Suscribete al Blog :  [RSS del Blog](http://feeds.feedburner.com/uGeekBlog) |

Suscribete al Podcast :  [RSS](http://feeds.feedburner.com/ugeek) , [ITunes](https://itunes.apple.com/us/podcast/ugeek/id1201421866?mt=2) , [ivoox](https://www.ivoox.com/podcast-ugeek_sq_f1383493_1.html)  

Suscribete a uGeekRadio : [Feed](http://feeds.feedburner.com/uGeekRadio)  



<br>

<!-- ------------------------------------- url del podcast -------------------------------------------  -->
<audio controls>
  <source src="https://ia601500.us.archive.org/33/items/syncthing/syncthing.mp3">
Your browser does not support the audio element.
</audio>

<!-- -------------------------------------Imagen -------------------------------------------  -->



![syncthing](http://telegra.ph/file/5dc8a4d812d3b65e8d4b9.jpg)


<!-- -------------------------------------Descripción del podcast -------------------------------------------  -->



<!-- -------------------------------------Aquí abajo los Comentarios -------------------------------------------  -->

Introducir tu ip escribiendo **tcp://tu_ip:22000**. 22000 es el puerto de escucha de Syncthing por defecto.  

Podemos cambiar el puerto.  

![foto](http://telegra.ph/file/b0f2741fd9b3512ee49b6.jpg)


### Arranque y Paro  

Sustituye el usuario **pi** por tu usuario.  

```
# Habilitar
sudo systemctl enable syncthing@pi.service

# Iniciar Syncthing
sudo systemctl start syncthing@pi.service

# Detener Syncthing
sudo systemctl stop syncthing@pi.service

# Comprobar si el servicio esta activo o no
systemctl status syncthing@pi.service
```



### Arranque al Inicio  

```
sudo nano /etc/rc.local 
```

Antes de EXIT, ponemos para que inicie syncthing así:  

```
sudo systemctl start syncthing@pi.service
exit 0
```

  
---

[Canal en Telegram](https://t.me/uGeek)  

[Grupo en Telegram](https://t.me/uGeekPodcast)  

[uGeekPodcast en Twitter](https://twitter.com/ugeekpodcast)  


Escucha más Podcast en el Reproductor de la web [►Play](https://ugeek.github.io/podcasts/)  


Tags: {% assign sorted_tags = page.tags | sort %} {% for tag in sorted_tags %} , <span class="tag"><a href="/tag#{{ tag }}">{{ tag }}</a></span> {% endfor %},


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

<script id="dsq-count-scr" src="//https-angelbcn-github-io-ugeek.disqus.com/count.js" async></script>