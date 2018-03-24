---
layout: page
title: "Joplin: Crear un Checklist dentro de una Nota"
date: 2018-03-24 11:35 
tags: [blog, checklist, notas, joplin]
categories: notas
comments: true
---
#### Publicado por Angel



![joplin](http://telegra.ph/file/0fbd8a60e0370f0859e4a.jpg)  

Joplin es una aplicación que ha despertado mucho interés entre los oyentes. Su privacidad al poder utilizar una nube privada como Nextcloud, cifrar notas, sencillez de uso, gestión y búsqueda de las notas, creación y exportación en Markdown, la hacen una aplicación muy a tener en cuenta.

Aún así quedan muchos detalles por pulir, como la creación de Checklist dentro de una nota. 
Aunque está disponible en  la documentación de la app, deseariamos que fuera mucho mas sencillas de crear, pero recordar que tal como comenté, es una aplicación que está en constante actualización. Prueba de ello, es que ayer llegó para Android la nueva actualización con la completa traducción de la app al castellano, así como el poder etiquetar todas nuestras notas.

Para aquellos que quieran crear un Checklist dentro de una Nota, copiar esta Demo en cualquier Nota de Joplin.   

```
- [X] uno
- [X] dos
- [ ]  
- [ ] 
- [ ]  
- [ ] 
- [ ]  
- [ ]  
```  


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
