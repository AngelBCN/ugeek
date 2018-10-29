---
layout: page
title: "Con Emacs, también podemos editar Markdown"
date: 2018-10-29
tags: [blog, emacs, markdown]
categories: emacs
comments: true
---

He hablado de como crear tus archivos Org Mode mediante Emacs, pero&#x2026; ¿Realmente vale la pena invertir tiempo en aprender los atajos de teclado y el funcionamiento de Emacs?.
Por supuesto que Sí!!! Y es que Emacs no solo funciona con Org Mode, sino que con cualquier sintaxis o cosa que se os ocurra.  
Hoy vamos a utilizar Emacs como editor de Markdown.
Voy a dividir el post en 2 partes, resaltado de sintaxis y previsulización del documento que estamos editando con refresco instantáneo. 


## Resaltado de Sintaxis

Para que Emacs resalte la sintaxis de Markdown, necesitamos instalar un paquete que encontraremos en [Melpa](https://melpa.org), [markdown-mode](https://github.com/jrblevin/markdown-mode).  

Instalación:  
```
M-x package-install RET markdown-mode RET
```


## Previsualización del documento

Para previsualizar el documento, instalaremos el paquete también de [Melpa](https://melpa.org), [Flymd](https://github.com/mola-T/flymd).

Instalación:  
```
M-x package-install RET flymd RET
```

Ahora si queremos previsualizar el documento, solo tenemos que introducir en Emacs:  
```
M-x flymd-flyit
```

Esto, nos lanzará un archivo temporal ya abrirá nuestro navegador web, para previsualizar el documento.
Por defecto se refresca en tiempo real y que podemos deshabilitar




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

