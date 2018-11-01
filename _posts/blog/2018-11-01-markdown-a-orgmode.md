---
layout: page
title: "Convertir de Markdown a Org Mode gracias a Pandoc"
date: 2018-11-01
tags: [blog, emacs, markdown, orgmode, pandoc]
categories: emacs
comments: true
---

Vamos a convertir nuestros archivos Markdown a Org Mode gracias a [Pandoc](https://pandoc.org/).
Para ello, primero necesitamos instalar Pandoc en nuestro Ubuntu:

```
sudo apt install pandoc
```

Ahora tenemos 2 posibilidades, transformar únicamente un archivo .md a .org, o aprovechando la magnífica gestión de los archivos Org Mode, convertir todos los archivos Markdown de una carpeta a un único archivo Org Mode.

1) Markdown a Org Mode.
Ejecutamos este comando en la terminal.

```
pandoc -f markdown -t org -o nuevo_archivo.org archivo_a_convertir.md
```

2) Muchos archivos Markdown a un único Org Mode.

Vamos a la carpeta donde están todos los **Markdown** que queremos convertir y **Llamamos a find vía Pandoc:**

```
find . -name \*.md -type f -exec pandoc  -f markdown -t org -o {}.org {} \;
```

Recordar verificar que la conversión se ha hecho correctamente.



#### Publicado por Angel 
<!-- -------------------------------------Aquí abajo los comentarios -------------------------------------------  -->
---


[Suscribete al Blog](https://ugeek.github.io/blog)

[Suscribete al Podcast](https://ugeek.github.io/podcast)

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

