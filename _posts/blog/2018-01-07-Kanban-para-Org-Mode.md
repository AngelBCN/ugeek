---
layout: page
title: "Kanban para Org Mode"
date: 2018-01-07 21:00
tags: [blog, emacs, kanban, orgmode]
categories: emacs
comments: true
---
#### Publicado por Angel


Kanban para Org Mode
====================
![](https://telegra.ph/file/e257f19333ed6f9370d87.png)  
10 Meses utilizando Org Mode + Emacs y cada vez va a ser mas difícil el
dejar este método para gestionar mis tareas y tomar notas.

Hace unos 2 meses, gestionando mi listas de tareas en mi Org Mode, eché
de menos el poder implementar el método Kanban y poder ver mis tareas
de una forma más gráfica.

Tuve el comentario en un grupo reducido de Telegram, donde esta Daniel
Primo, que compartió conmigo esta joya que ha encontrado.

[![asciicast](https://asciinema.org/a/4gijw6gs9jlcf5dxnlj0f12bh.png)](https://asciinema.org/a/4gijw6gs9jlcf5dxnlj0f12bh)  

Christian Köstlin, inspirado en el artículo [Emacs, org-mode, Kanban,
Pomodoro… Oh
my…](https://agilesoc.com/2011/08/08/emacs-org-mode-kanban-pomodoro-oh-my/),
creo un paquete que no esta disponible en ningún repositorio pero que
podemos instalar de modo manual, para obtener un Panel dinámico Kanban,
dentro de nuestro Org Mode. Lo mejor de todo, es que no sólo podremos
ver estas tareas gráficamente, sino que también cambiar el estado de las
mismas.

Instalación
-----------

Instalaremos previamente **dash**, una librería avanzada para trabajar con tablas, si no la tenemos instalada  
```
M-x package-install RET dash RET
```    

*Recuerda que M-x=(Alt+x) y RET=Intro*

Descargaremos el archivo con la terminal  
```
wget https://raw.githubusercontent.com/ugeek/emacs-config/master/org-kanban.el
```  

<!-- -->

También podemos hacerlo desde el Explorador web  
[org-kanban.el](https://raw.githubusercontent.com/ugeek/emacs-config/master/org-kanban.el)

<!-- -->

Cargamos en Emacs el org-kanban.el que hemos descargado  
```
M-x load-file RET ruta_del_archivo RET
```    

Gestión en nuestro Org Mode
---------------------------

Nuestro archivo .org, debe tener en la cabecera del documento, los estados de las tareas. Yo he decidido añadir más estados y personalizarlo en Castellano  
```
#+TODO: PENDIENTE(t) | SIGuIENTE(s) | PROCESO(p) | ESPERA(e) | REALIZADO(d)
```  


![](https://telegra.ph/file/d7fdb99dd61e1b2a0317a.png)  

A diferencia del ejemplo de Christian Köstlin, sitúo mi panel Kanban
al inicio, seguido de mis tareas, pudiendo ver el resumen del estado de
estas de un modo más rápido.

Para generar el Panel Kanban, escribiremos este código:

```
#+BEGIN: kanban                                                                                                                           
#+END:                                                                                                                                    
```

Situando el cursor sobre **\#+BEGIN: kanban** pulsamos C-c C-c y nos
generará de forma automática el panel kanban

Ahora situándonos sobre una tarea en el panel, podremos cambiar su
estado:

Estado Siguiente  
```
M-x org-kanban/next
```  

Estado Anterior  
```
M-x org-kanban/prev
```  

Estado Siguiente o Anterior  
```
M-x org-kanban/shift
```  

Por defecto cambiará al estado siguiente, pero pulsando las teclas **j**
o **k**, podremos cambiar al estado que deseemos.

-   j = Anterior
-   k = Siguiente

También sobre la tarea en el panel, si tecleamos **C-c C-o**, nos
llevará hasta donde está la entrada de esta tarea y ver si está
compuesta de subtareas.

Nota: Recordar que el panel es estático, así que si cambiamos el estado de la taréa fuera del panel, deberemos actualizarlo desde el panel con (C-c C-c).

No se que opináis vosotros, pero para mi esto es alucinante. Tener todo
en un único archivo de texto en Modo Org, de tan poco tamaño.

[Repositorio original org-kanban de Christian
Köstlin](https://github.com/gizmomogwai/org-kanban)


<!-- -------------------------------------Aquí abajo los comentarios -------------------------------------------  -->
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
