---
layout: post
title: "Adiós Blogger, Hola GitHub!"
date: 2017-05-04
author: Angel
categories: podcast
image: /img/ugeek.png
podcast_link: https://ia801502.us.archive.org/5/items/051.AdisBloggerHolaGithub/051.%20Adi%C3%B3s%20Blogger,%20Hola%20Github%20.mp3
tags: [podcast, github, jekyll, blogger, blog]
categories: podcast
comments: true
---
#### Publicado por Angel

Suscribete al Blog :  [RSS del Blog](http://feeds.feedburner.com/uGeekBlog) |

Suscribete al Podcast :  [RSS](http://feeds.feedburner.com/ugeek) , [ITunes](https://itunes.apple.com/us/podcast/ugeek/id1201421866?mt=2) , [ivoox](https://www.ivoox.com/podcast-ugeek_sq_f1383493_1.html)

<audio controls>
  <source src="https://ia801502.us.archive.org/5/items/051.AdisBloggerHolaGithub/051.%20Adi%C3%B3s%20Blogger,%20Hola%20Github%20.mp3" type="audio/mpeg">
Your browser does not support the audio element.
</audio>
<!-- ---------------------------------------------------Pon aquí el audio-------------------------------------------------------- -->

![Jekyll](/img/post/jekyll-github.png)
Desconexión en 3, 2, 1... Desde ayer a las 23:00 horas, hice el cambio de Blogger a GitHub.  

En el podcast os explico las diferentes secciones que tendrá el nuevo Blog en GitHub con Jekyll y en cierto modo, os muestro una alternativa a las habituales, para crear vuestro propio Blog o incluso, como yo, adjuntar vuestro podcast.  

La verdad es que haber creado el Blog mediante Jekyll, es una doble satisfacción, porque al margen de poder hacer un Fork de otro o ser un blog totalmente estatico, es muy personalizable y lo configuras 100% a tu gusto.     

Os animo a crear el vuestro. En próximos podcast y posts os explicaré como hacer un Fork, una réplica exacta, pero que pasará a ser vuestra. Una forma, sin ser programador, de disfrutar a nuestra manera del Software Libre.  

[uGeek](https://ugeek.github.io/)  

[post del podcast](https://ugeek.github.io/051-Adios-Blogger-Hola-GitHub/)  

<!-- -------------------------------------Aquí abajo los comentarios -------------------------------------------  -->
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
