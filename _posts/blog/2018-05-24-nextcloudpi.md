---
layout: page
title: "NextcloudPi. Nextcloud en Raspbian con Docker"
date: 2018-05-24
tags: [blog, docker, raspberry, portainer]
categories: servidor
comments: true
---
#### Publicado por Angel

## Descargar Imagen y Crear Contenedor NextcloudPi  

Tal como [os prometí en el podcast](https://ugeek.github.io/docker-en-que-ando-liado/), entro más al detalle con la instalación del Docker oficial de Nextcloud para Raspberry. [NextcloudPi](https://ownyourbits.com/nextcloudpi/).  

Si tenemos un servidor como apache2, vamos a detener el servicio para no utilizar el puerto 80, que éste utiliza por defecto.  

Tendrás que modificar en este comando el usuario **pi** por tu usuario y la ip **192.168.1.100** por la ip local de tu raspberry.  

```
sudo docker run -d -p 4443:4443 -p 443:443 -p 80:80 -v /home/pi/docker/nextcloudplus/:/data --name nextcloudpi ownyourbits/nextcloudplus-armhf 192.168.1.100
```  


## Iniciar Nextcloud
Una vez montado, nos conectaremos a nuestra ip:443. Nos aparecerá una web con el usuario ncp y dos contraseñas creadas de forma aleatoria.  

Guardamos las 2 contraseñas y le damos a **Activar** en la parte inferior.  

Una contraseña será para la web de administración de **NextcloudPi** por el puerto 4443 y la otra contraseña será para el servicio **Nextcloud** por el puerto 80 o 443.  

## Crear Certificado

Si no tenemos una ip pública estática, recomiendo el utilizar un servicio como [Duck DNS](https://www.duckdns.org/).  

Ahora vamos a ip::4443 y vamos a crear el certificado en el apartado: Let's Encrypt.  

Abriremos los puertos 443 y 80 de nuestro Router, dirigiendo el tráfico a la ip local de nuestra Raspberry y clicaremos **Ejecutar**.  

De forma automática, nos generará el certificado por 3 meses.  

[NextcloudPi](https://ownyourbits.com/nextcloudpi/)


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
