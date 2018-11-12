---
layout: page
title: "Antergos. Comandos para terminal y derivadas de Arch Linux"
date: 2017-05-01
tags: [antergos, blog, terminal]
categories: blog
comments: true
---
#### Publicado por Angel

Los que venimos de Ubuntu, tenemos problemas al pasar a una dervada de Arch, porque no conocemos bien las instrucciones para actualizar el Sistema Operativo, instalar y demás...

Aquí iré añadiendo periodicamente comandos para ir conociendolos.

## pacman
Pacman es el sistema de paquetes de Arch oficial, supervisado por ellos.

* Actualizar el Sistema Operativo y repositorios  
**sudo pacman -Syyuu**

* Buscar en los repositorios (usaremos de ejem: gimp)    
**sudo pacman -Ss gimp**

* Instalar aplicaciones    
**sudo pacman -S gimp**

## yaourt  
Las aplicaciones que no esten en los repositorios oficiales de Arch, estan en AUR. AUR (Arch User Repository) es el lugar donde la comunidad de Arch Linux puede subir los PKGBUILD de las aplicaciones, bibliotecas, etc.,

Para instalar desde Aur utilizaremos **yaourt**.

* Actualizar los repositorios  
**yaourt -Syu**  

* Buscar en yaourt (usaremos de ejem: utext)  
**yaourt -Ss utext**  

* Instalar aplicaciones que no encontremos en Pacman (como utext)   
**yaourt -S utext**  


---

### Guía de comandos básicos de Pacman
Fuente : [sobrebits.com](https://sobrebits.com/guia-de-comandos-basicos-de-pacman-en-archlinux-y-derivadas/)
* Instalar paquetes  
**pacman -S “paquete”** #Instala un paquete.  
**pacman -Sy “paquete”** #Sincroniza repositorios e instala el paquete.  

* Actualizar paquetes  
**pacman -Sy** #Sincroniza repositorios.  
**pacman -Syy** #Fuerza la sincronización de repositorios incluso para paquetes que parecen actualizados.  
**pacman -Syu** #Sincroniza repositorios y actualiza paquetes.  
**pacman -Syyu** #Fuerza sincronización y actualiza paquetes.  
**pacman -Su** #Actualiza paquetes sin sincronizar repositorios.  

* Buscar paquetes  
**pacman -Ss “paquete”** #Busca un paquete.    
**pacman -Si “paquete”** #Muestra información detallada de un paquete.  
**pacman -Sg “grupo”** #Lista los paquetes que pertenecen a un grupo.  
**pacman -Qs “paquete”** #Busca un paquete YA instalado.  
**pacman -Qi “paquete”** #Muestra información detallada de un paquete YA instalado.  
**pacman -Qdt** #Muestra paquetes huerfanos.  

* Eliminar paquetes  
**pacman -R “paquete”** #Borra paquete sin sus dependencias.  
**pacman -Rs “paquete”** #Borra paquete y sus dependencias no utilizadas.  

---
## Aplicaciones Imprescindibles

Navegador Chrome  
**yaourt -S google-chrome**

Editor de video   
**sudo pacman -S openshot**

Notas de Nextcloud  
**yaourt -S qownnotes**

Descarga videos de youtube  
**sudo pacman -S clipgrab**

Hacer capturas de pantalla  
**yaourt -S shutter**

Convertir audios de m4a a MP3  
**sudo pacman -S soundconverter**

Editor de Fotografía  
**sudo pacman -S gimp**

Instalar Inkscape  
**sudo pacman -S inkscape**

Transmission  
**sudo pacman -S transmission-gtk**

Skype  
**sudo pacman -S skype**


<!-- TAGS Y COMENTARIOS -->

Tags: {% assign sorted_tags = page.tags | sort %} {% for tag in sorted_tags %} , <span class="tag"><a href="/search#{{ tag }}">{{ tag }}</a></span> {% endfor %},



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
