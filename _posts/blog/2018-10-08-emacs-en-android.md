---
layout: page
title: "Emacs en Android"
date: 2018-10-09
tags: [blog, emacs, android, termux]
categories: emacs
comments: true
---

Podemos utilizar Emacs en Android gracias a Termux a través de la Terminal. La novedad es que desde hace mas o menos un mes, hay un nuevo paquete x11 para Termux llamado emacs-x. Gracias a la combinación de 3 aplicaciones, [Termux](https://play.google.com/store/apps/details?id=com.termux), [Hacker's keyboard](https://play.google.com/store/apps/details?id=org.pocketworkstation.pckeyboard) y [XServer XSDL](https://play.google.com/store/apps/details?id=x.org.server), podremos utilizar Emacs también de forma gráfica.

![Emacs para Android](https://i.imgur.com/fRNI5Uv.png)

Esto abre la posibilidad de utilizar Emacs tanto en tablets, Android Tv... del mismo modo como lo haríamos en un PC.


Escribimos en Termux:

```
pkg upgrade,
pkg install x11-repo
pkg install emacs-x
```

Ahora Iniciaremos XServer XSDL:
```
export DISPLAY=:0
```

Recordar que al iniciar XServer XSDL, podremos configurar la posición vertical de la pantalla, teclado, etc...

Iniciamos Emacs:
```
emacs
```

Si nos vamos a la aplicación de XServer XSDL y esperamos unos segundos, aparecerá Emacs en modo gráfico.


Fuente : https://www.reddit.com/r/emacs/comments/9m76ak/termux_package_emacsx/

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
