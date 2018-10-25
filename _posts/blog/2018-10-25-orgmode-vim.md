---
layout: page
title: "Org Mode en Vim. Como Instalar el Plugin de Org Mode Mediante Vundle en Vim"
date: 2018-10-25
tags: [blog, emacs, orgmode, vim, vundle]
categories: emacs
comments: true
---
Yo soy de la opinión que el mejor modo de utilizar Org Mode es mediante Emacs. Aun así, para aquellos que se resisten inicialmente y conocen los atajos de teclado de Vim, os muestro paso a paso como Instalar el Plugin.   
Tomo de Ejemplo este Plugin, pero si veis cualquier otro que os guste, siguiendo los mismos pasos, también podréis instalarlo.


## Configurar Plugins

1.  Creamos la carpeta para alojar Vundle y clonamos el repositorio de GitHub:

Creamos la carpeta **bundle**, donde irán las carpetas de los plugins:
`mkdir ~/.vim/bundle`

Clonamos el repositorio de GitHub, en la ruta que especificamos a continuación:
`git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim`

1.  Añadimos las siguientes líneas en el archivo de configuración de Vim (.vimrc):
    Los comentarios van con comillas delante **"**

`vim ~/.vimrc`

Pegamos este contenido: 

    set nocompatible              " be iMproved, required
    filetype off                  " required
    
    " set the runtime path to include Vundle and initialize
    set rtp+=~/.vim/bundle/Vundle.vim
    call vundle#begin()
    " alternatively, pass a path where Vundle should install plugins
    "call vundle#begin('~/some/path/here')
    
    " let Vundle manage Vundle, required
    Plugin 'VundleVim/Vundle.vim'
    
    " The following are examples of different formats supported.
    " Keep Plugin commands between vundle#begin/end.
    " plugin on GitHub repo
    " Plugin 'tpope/vim-fugitive'
    " plugin from http://vim-scripts.org/vim/scripts.html
    " Plugin 'L9'
    " Git plugin not hosted on GitHub
    " Plugin 'git://git.wincent.com/command-t.git'
    " git repos on your local machine (i.e. when working on your own plugin)
    " Plugin 'file:///home/gmarik/path/to/plugin'
    " The sparkup vim script is in a subdirectory of this repo called vim.
    " Pass the path to set the runtimepath properly.
    " Plugin 'rstacruz/sparkup', {'rtp': 'vim/'}
    " Avoid a name conflict with L9
    " Plugin 'user/L9', {'name': 'newL9'}
    
    " All of your Plugins must be added before the following line
    call vundle#end()            " required
    filetype plugin indent on    " required
    " To ignore plugin indent changes, instead use:
    "filetype plugin on
    "
    " Brief help
    " :PluginList       - lists configured plugins
    " :PluginInstall    - installs plugins; append `!` to update or just :PluginUpdate
    " :PluginSearch foo - searches for foo; append `!` to refresh local cache
    " :PluginClean      - confirms removal of unused plugins; append `!` to auto-approve removal
    "
    " see :h vundle for more details or wiki for FAQ
    " Put your non-Plugin stuff after this line



## Instalar Plugins con Vundle

Para instalar el módulo con Vundle, añadimos la ruta del Plugin, en este caso la ruta de GitHub, al archivo .vimrc, después de **Plugin 'VundleVim/Vundle.vim'**.

1.  Copiamos **Plugin 'jceb/vim-orgmode'**, en el archivo de configuración de Vim **.vimrc** despues de Plugin 'VundleVim/Vundle.vim'

    Plugin 'VundleVim/Vundle.vim'
    Plugin 'jceb/vim-orgmode'

2.  Instalamos el Plugins o Plugins, si hubiéramos añadido mas de uno, con el siguiente comando

`vim +PluginInstall`

**Nota:** También lo podríamos hacer entrando en Vim y escribiendo **:PluginInstall**

3.  Veremos como se abre Vim y comenzaran a descargarse el Plugin o Plugins que hayamos añadido en el archivo de configuración.

**Nota:** Podemos consultar donde esta el módulo, introduciendo en Vim **:h vundle**.


## Desinstalar Plugins

Para desinstalar los Plugins y eliminar las carpetas de los mismos:

1.  Borramos del archivo **.vimrc** los Plugins a desinstalar
2.  Ejecutamos el siguiente comando, que a diferencia del anterior en el ejemplo de instalación, podriamos añadir **+qall**, que significa que una vez ejecutado, saldrá de Vim 

`vim +PluginClean +qall`



## Listar los Plugins Instalados

Entramos a Vim y ejecutamos **:PluginList**


Espero que os haya gustado. A disfrutar con el Org Mode y Vim. Y si te gusta mucho, utiliza también Emacs. :P


#### Publicado por Angel 
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

