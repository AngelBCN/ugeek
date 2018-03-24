---
layout: page
title: "ORGMODE: Focus Mode"
date: 2018-03-24 15:30 
tags: [blog, emacs, focusmode, orgmode]
categories: notas
comments: true
---
#### Publicado por Angel



![focusmode](https://github.com/larstvei/Focus/raw/master/demo-light.gif)

  
Si queremos centrar nuestra atención cuando estamos escribiendo en emacs con Org Mode, podemos instalar Focus Mode.  

![fucusmode](https://github.com/larstvei/Focus/raw/master/demo-dark.gif)

  
### INSTALAR  
```
M-x package-install RET focus RET
```  

### ACTIVAR  
Para activar, escribir:
```
M-x focus-mode
```  

### ACTIVAR READ ONLY  
```
M-x focus-read-only-mode
```  

La cantidad de opacidad, podemos personalizarlo configurando el focus-dimness  

[Fuente](https://github.com/larstvei/Focus)


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
