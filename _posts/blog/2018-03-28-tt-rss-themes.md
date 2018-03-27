---
layout: page
title: "Cambiar el Tema de Tiny Tiny RSS al estilo Feedly"
date: 2018-03-28 1:15 
tags: [blog, tt-rss, feedly, tema]
categories: servidor
comments: true
---
#### Publicado por Angel



![tt-rss](https://camo.githubusercontent.com/851194fd738e02496073a5c7e4ca3d1f5d38c8e0/68747470733a2f2f7261772e6769746875622e636f6d2f6c657669746f2f74742d7273732d666565646c792d7468656d652f6d61737465722f666565646c792d73637265656e73686f74732f666565646c792d657870616e6461626c652e706e673f313330383236)  

Te gusta Tiny Tiny RSS, pero si eres de los que sigue tus Feeds favoritos a través de la versión de pc, quizás no te guste mucho la estética Google Reader que trae por defecto.

En este post voy a explicarte cómo dejar Tiny Tiny RSS al más puro estilo Feedly y gracias a este post podrás personalizarlo como quieras.

- Descargamos este archivo:  
```
wget https://github.com/levito/tt-rss-feedly-theme/archive/master.zip
```  
- Descomprimimos:
```
unzip master.zip
```  
- Entramos en la nueva carpeta creada:
```
cd tt-rss-feedly-theme-master
```  
- Copiamos en la ruta de nuestro tt-rss:
```
cp feedly.css feedly-night.css [ruta de nuestro tt-rss]/themes
cp -r feedly/ [ruta de nuestro tt-rss]/themes
```  

Ahora entramos en preferencias, y en temas seleccionamos **feedly-theme**.

Este proceso es el mismo para cambiar cualquier tema. Os dejo el link de este tema y otros más.

+ [tt-rss-feedly-theme](https://github.com/levito/tt-rss-feedly-theme)
+ [Mas Temas de tt-rss](https://git.tt-rss.org/git/tt-rss/wiki/Themes)
<!-- -------------------------------------Aquí abajo los comentarios -------------------------------------------  -->
---
Cuando 
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
