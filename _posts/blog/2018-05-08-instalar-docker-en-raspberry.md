---
layout: page
title: "Instalar Docker y Portainer en Raspbian"
date: 2018-05-08
tags: [blog, docker, raspberry, portainer]
categories: servidor
comments: true
---
![docker](https://i.imgur.com/9DMx0DS.png)
#### Publicado por Angel


## Instalación de Docker en Raspbian.


### Instala primero algunos paquetes que necesitamos
```
sudo apt install apt-transport-https ca-certificates curl gnupg2 software-properties-common
```  

### Obtener la clave de firma Docker para paquetes
```
sudo curl -fsSL https://download.docker.com/linux/$(. /etc/os-release; echo "$ID")/gpg | sudo apt-key add -
```  

### Añadimos los repositorios oficiales
```
sudo echo "deb [arch=armhf] https://download.docker.com/linux/$(. /etc/os-release; echo "$ID") \
     $(lsb_release -cs) stable" | \
    sudo tee /etc/apt/sources.list.d/docker.list
```  

### Instalamos Docker
```
sudo apt update
sudo apt install docker-ce
```  

### Iniciamos Docker y lo habilitamos para que se inicie al reiniciar
```
sudo systemctl enable docker
sudo systemctl start docker
```  

## Portainer
Para gestionar los Dockers de modo gráfico, vamos a instalar **Portainer**.  

### Instalación
```
sudo docker run -d --name=Portainer --restart=always -p 9000:9000 -v /var/run/docker.sock:/var/run/docker.sock portainer/portainer
```  

- Nos conectamos a nuestra ip, puerto 9000. http://nuestra_ip:9000
- Ponemos la contraseña de administrador
- Seleccionamos la opción local y pulsamos "Connect"


**Ya podemos instalar Dockers**



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
