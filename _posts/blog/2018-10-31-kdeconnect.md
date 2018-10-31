---
layout: page
title: "Kde Connect en Ubuntu, Debian, Lubuntu, Mint... y derivadas"
date: 2018-10-31
tags: [blog, kdeconnect, android, ubuntu, i3]
categories: android
comments: true
---

He instalado Kde Connect en Lubuntu y Mint con el escritorio i3. Os detallo como instalarlo paso a paso.  

Hasta el paso 3, ya estaría listo gracias a kdeconnect-cli mediante interfaz gráfica. Pero si te animas con la terminal, llega hasta el final del post.  

Recordaros que Kde Connect está tanto en Google Play como en F-Droid para Android.  

1) Instalamos en nuestro Ubuntu  

```
sudo apt install kdeconnect
```  

Si tienes una versión superior a Ubuntu 16.04, incator-kdeconnect posiblemente estará disponible, en caso contrario, el equipo de webupd8team nos lo pone fácil.  
Instala esto:  

```
sudo add-apt-repository ppa:webupd8team/indicator-kdeconnect
sudo apt update
sudo apt install kdeconnect indicator-kdeconnect
```  

2) Instalamos la app en nuestro movil, tablet...  

3) Buscará dentro de nuestra red local los dispositivos con Kde Connect. Empareja tu dispositivo y... Ya está!! Si quieres seguir con la terminal, sigue leyendo.  

4) Vamos ha hacer el emparejamiento desde la Terminal. El comando kdeconnect-cli --help nos mostrará todos los comandos disponibles.  

5) Vamos a listar dispositivos disponibles en nuestra red local desde la terminal  

```
kdeconnect-cli -l
```  

La terminal nos mostrará todos los dispositivos disponibles, en mi caso, mi Xiaomi A1:  

```
    angel@angel /usr/lib/kde4 $ kdeconnect-cli -l
        - Xiami A1: 35826fca13f58Gsu (reachable)
	    1 device found  
```  

6) Vinculamos PC a mi Xiaomi A1 con nuestro:  

```
kdeconnect-cli -d 35826fca13f58Gsu --pair  
```  

7) En tu movil, tablet Android, recibirás una solicitud para vincularlo.  

8) Ya está condectado Kde Connect!!!  

Si tienes i3 y quieres que se inicie Kde Connect por defecto, escribe estas líneas en tu archivo de configuración:  

```
# Autostart kdeconnect
exec --no-startup-id /usr/bin/indicator-kdeconnect
```






#### Publicado por Angel 
<!-- -------------------------------------Aquí abajo los comentarios -------------------------------------------  -->
---
Cuando 
[Canal en Telegram](https://t.me/uGeek)  

[Grupo en Telegram](https://t.me/uGeekPodcast)  

[uGeekPodcast en Twitter](https://twitter.com/ugeekpodcast)  

[YouTube](https://www.youtube.com/channel/UCVmGqdwOeswJ55IFmsYNlww)  

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

