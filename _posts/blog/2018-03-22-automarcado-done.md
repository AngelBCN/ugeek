---
layout: page
title: "OrgMode: Automarcado DONE al Realizar un Grupo de Tareas"
date: 2018-03-22 9:30
tags: [blog, emacs, checklist, orgmode]
categories: emacs
comments: true
---
#### Publicado por Angel



![]()  

Cuando tenemos que realizar una tarea muy grande, un modo para motivarse a realizar esta, es dividirla en subtareas.   
Gracias al Org Mode y sus sistema jerárquico de tareas, es posible hacerlo, pero por defecto no permite que una vez realizadas todas las subtareas, marcar la tarea global automáticamente con el **DONE**.  

Para poder realizar esto, añadiremos en nuestro .emacs o init.el:  
```
(defun org-summary-todo (n-done n-not-done)
  "Switch entry to DONE when all subentries are done, to TODO otherwise."
  (let (org-log-done org-log-states)   ; turn off logging
    (org-todo (if (= n-not-done 0) "DONE" "TODO"))))

(add-hook 'org-after-todo-statistics-hook 'org-summary-todo)
```  


El modo de representar la tarea y subtareas, seria de la siguiente manera:  
```
* TODO tarea[0/2]
** TODO uno
** TODO dos[1/2]
*** TODO uno de dos
*** DONE dos de deos
```  
Una vez todas las subtareas estén realizada y marcada con **DONE**, ahora si la tarea principal cambiará automáticamente a **DONE**.  

[rss de OrgMode y Emacs](https://ugeek.github.io/emacs)

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
