---
layout: page
title: "Resilio en Ubuntu, Raspbian, Antergos y derivadas"
date: 2017-05-14 19:00:00
tags: [blog, resilio, nube, raspberry, ubuntu, antergos]
categories: aplicaciones
comments: true
---
#### Publicado por Angel

![resilio](/img/post/resilio.png)

Ya aprendimos a instalar Syncthing, ahora toca hacer lo propio con la opción privativa Resilio.

## Ubuntu, Raspbian y dereivadas de debian


1- Añadimos los repositorios:   
```
echo "deb https://linux-packages.resilio.com/resilio-sync/deb resilio-sync non-free" | sudo tee /etc/apt/sources.list.d/resilio-sync.list
```   

2- Actualizamos el repositorio:
```
sudo apt update
```

3- Instalamos Resilio

```
sudo apt-get install resilio-sync
```

Ahora escribimos **localhost:8888** y entraremos en la interfaz web de resilio.

### Otras instrucciones:

_systemctl stop resilio-sync_  
_systemctl start resilio-sync_  
_systemctl restart resilio-sync_  
_systemctl status resilio-sync_  


## Antergos y derivadas de Arch
1- Instalar resilio:   

```
yaourt -S rslsync

```   


2- Iniciamos resilio con:  
```
rslsync
```

Ahora escribimos **localhost:8888** y entraremos en la interfaz web de resilio.




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
