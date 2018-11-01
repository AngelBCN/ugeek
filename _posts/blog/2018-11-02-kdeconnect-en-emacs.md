---
layout: page
title: "Kde Connect en Emacs"
date: 2018-11-02
tags: [blog, emacs, kdeconnect]
categories: emacs
comments: true
---

Por culpa del [Podcast de atareao.es](https://www.atareao.es/podcast/integrando-android-con-ubuntu/), he estado probando Kde Connect y la verdad es que ha pasado a ser una aplicación imprescindible en mi día a día. Tal como explica en su Podcast, existe la posibilidad de utilizarla con Emacs y como podéis imaginar, no me he podido resistir a probarla. Os explico como utilizarla:


Teniendo los repositorios de Melpa:
1.  Instalación: **M-x package-install RET kdeconnect**
2.  Listamos los dispositivos de nuestra red local: **M-x kdeconnect-list-devices**
3.  Buscamos los búfer anteriores para copiar los *id* de nuestros dispositivos (C-x Izquierda)
4.  Introducimos el *id* de nuestro dispositivo: **M-x kdeconnect-select-active-device RET id**
5.  Hacemos un *ping* para comprobar que se ha conectado correctamente: **M-x kdeconnect-ping**


**YA ESTA!!!**

Ahora si copiamos un texto en el portapapeles de nuestro Emacs, podremos pegarlo en el otro dispositivo gracias a Kde Connect.


Vamos a enviar un texto desde Emacs al otro dispositivo **M-x kdeconnect-ping-msg RET Texto**


Os dejo el resto de funciones para que juguéis y el repositorio donde está toda la información:


<span class="underline">Resto de Funciones disponibles</span>

<table border="2" cellspacing="0" cellpadding="6" rules="groups" frame="hsides">


<colgroup>
<col  class="org-left" />

<col  class="org-left" />
</colgroup>
<thead>
<tr>
<th scope="col" class="org-left">Función</th>
<th scope="col" class="org-left">Descripción</th>
</tr>
</thead>

<tbody>
<tr>
<td class="org-left">kdeconnect-get-active-device</td>
<td class="org-left">Mostrar el dispositivo activo</td>
</tr>


<tr>
<td class="org-left">kdeconnect-list-devices</td>
<td class="org-left">Muestra todos los dispositivos visibles, incluso los no disponibles.</td>
</tr>


<tr>
<td class="org-left">kdeconnect-ping</td>
<td class="org-left">Enviar una notificación al dispositivo activo.</td>
</tr>


<tr>
<td class="org-left">kdeconnect-ping-msg</td>
<td class="org-left">Envía una notificación con un mensaje personalizado al dispositivo activo</td>
</tr>


<tr>
<td class="org-left">kdeconnect-refresh</td>
<td class="org-left">Escanee la red y actualice las conexiones disponibles</td>
</tr>


<tr>
<td class="org-left">kdeconnect-ring</td>
<td class="org-left">Hacer que suene el dispositivo activo (útil para encontrarlo)</td>
</tr>


<tr>
<td class="org-left">kdeconnect-select-active-device</td>
<td class="org-left">Seleccione el dispositivo activo de kdeconnect-devices</td>
</tr>


<tr>
<td class="org-left">kdeconnect-enviar-archivo</td>
<td class="org-left">Enviar el archivo seleccionado al dispositivo activo</td>
</tr>


<tr>
<td class="org-left">kdeconnect-enviar-sms</td>
<td class="org-left">Enviar un SMS al destino especificado</td>
</tr>
</tbody>
</table>

[Repositorio de GitHub](https://github.com/carldotac/kdeconnect.el)



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

