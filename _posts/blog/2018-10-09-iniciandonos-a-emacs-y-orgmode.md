---
layout: page
title: "Iniciándonos a Emacs y Org Mode de un modo sencillo"
date: 2018-10-09
tags: [blog, emacs, orgmode]
categories: emacs
comments: true
---
Emacs parece complicado, pero nada de eso.

Como una imagen vale mas que mil palabras, os dejo este vídeo de youtube donde vereis como es el Org Mode.

<html>
    <iframe width="560" height="315" src="https://www.youtube.com/embed/bzZ09dAbLEE" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
    </html>

También os dejo estos dos Pdf's que os será de mucha ayuda para entender el Org Mode dentro de Emacs:

- [Guía Org Mode traducida por http://www.davidam.com/](http://www.davidam.com/docu/orgguide.es.pdf)
- [Guía Org Mode Resumida](https://orgmode.org/orgcard.pdf)


Ejemplo básico de sintaxis en Org Mode:

```
#+TITLE: Título de Nuestro Org
#+AUTHOR: Angel
#+DATE: 2018
#+LANGUAGE: es
#+SEQ_TODO: TODO(t) NEXT(n) WAIT(w) | CANCELLED (c) DONE(d)
#+TAGS: NOTAS (n) TAREAS (t)

Estructura del Org Mode:
* Primer nivel de Título
** Segundo nivel
*** Tercer nivel

Ejemplo de estructura de Tareas:
**** TODO A Tarea pendiente, Alta prioridad (A)
**** DONE B Esta tarea estaría realizada, Prioridad (B)

# Una línea de comentario. No se exporta esta línea.

Los párrafos están separados por al menos una línea de vacío.

Ejemplos de Enlaces. Atajo para crear el enlace: C-c C-l
[[https://ugeek.github.io/][Descripción del Enlace]]
https://ugeek.github.io/    enlace sin una descripción.

Marcado de palabras, frases...
*bold* ==> Negrita
~code~ ==> Código
+strike+ ==> Tachar
/italic/ ==> Cursiva
=verbatim= ==> Código
_underline_ ==> Subrallado

Bloque de código:
#+BEGIN_SRC bash
sudo apt update
sudo apt upgrade
#+END_SRC

Listas:
- En primer elemento de una lista.
- En segundo elemento.
  - Subpunto
      1. pregunta.
          2. Otro elemento.
	  - [ ] Artículo aún no se ha hecho.
	  - [X] artículo que se ha hecho.


Incluir una imagen:
archivo:ugeek_photo.jpg
```
Fuentes de la sintaxis:
- https://karl-voit.at/2017/09/23/orgmode-as-markup-only/
- https://nickhigham.wordpress.com/2017/11/02/org-mode-syntax-cheat-sheet/
- https://github.com/fniessen/refcard-org-mode

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
