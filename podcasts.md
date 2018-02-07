
<div id="inputbox" style="display: none;"><select id="select-podcast">
	<option value="Todos">Todos</option>
	<option value="Mosqueteroweb tecnologia, Linux, Chromebooks">Mosqueteroweb tecnologia, Linux, Chromebooks</option>
	<option value="mixx.io, tecnologĂ­a y negocios">mixx.io, tecnologĂ­a y negocios</option>
	<option value="DekNet">DekNet</option>
	<option value="Radiogeek">Radiogeek</option>
	<option value="NASeros Podcast">NASeros Podcast</option>
	<option value="Linux Express, de Podcast Linux.">Linux Express, de Podcast Linux.</option>
	<option value="Podcast de Eduardo Collado">Podcast de Eduardo Collado</option>
	<option value="Code Time">Code Time</option>
	<option value="Web Reactiva">Web Reactiva</option>
	<option value="Vacía tu bandeja">Vacía tu bandeja</option>
	<option value="La Tecnología para todos">La Tecnología para todos</option>
	<option value="La Hora Maker">La Hora Maker</option>
	<option value="Tomando Un Café">Tomando Un Café</option>
	<option value="Bitácora de Ciberseguridad">Bitácora de Ciberseguridad</option>
	<option value="Astronomía y algo más">Astronomía y algo más</option>
	<option value="Bateria2x100">Bateria2x100</option>
	<option value="Coffee Break: Señal y Ruido">Coffee Break: Señal y Ruido</option>
	<option value="reflex podcast">reflex podcast</option>
	<option value="uGeek - Tecnología, Android, Linux, Servidores y mucho más...">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</option>
	<option value="Podcast Linux">Podcast Linux</option>
	<option value="eDucando Geek">eDucando Geek</option>
	<option value="NOlegaltech Radio">NOlegaltech Radio</option>
	<option value="Programar es una mierda">Programar es una mierda</option>
	<option value="República Web">República Web</option>
	<option value="Podcast – ForoMóviles">Podcast – ForoMóviles</option>
	<option value="EntreDevYOps Podcast">EntreDevYOps Podcast</option>
	<option value="Compilando Podcast">Compilando Podcast</option>
	<option value="Podcast WINTABLET.INFO">Podcast WINTABLET.INFO</option>
	<option value="Podcast dmanuelalonso">Podcast dmanuelalonso</option>
	<option value="Salmorejo Geek">Salmorejo Geek</option>
	<option value="Code on the rocks">Code on the rocks</option>
	<option value="mixx.io, tecnología y negocios">mixx.io, tecnología y negocios</option>
	<option value="deployando.me">deployando.me</option>
	<option value="Vacia Tu Bandeja">Vacia Tu Bandeja</option>
	<option value="Cultura NAS">Cultura NAS</option>
	<option value="Aprendiendo GTD podcast productividad">Aprendiendo GTD podcast productividad</option>
	<option value="NeoSiteLinux Podcast">NeoSiteLinux Podcast</option>
	<option value="RetroActivo Podcast">RetroActivo Podcast</option>
	<option value="WeCodeSign Podcast">WeCodeSign Podcast</option>
	<option value="Ubuntu y otras hierbas">Ubuntu y otras hierbas</option>
	<option value="Maratón Linuxero">Maratón Linuxero</option>
	<option value="Droid Talks">Droid Talks</option>
	<option value="Podcast de KDE España">Podcast de KDE España</option>
	<option value="Procrastinación y Café">Procrastinación y Café</option>
	<option value="We.Developers">We.Developers</option>
	<option value="DaboBlog Podcast">DaboBlog Podcast</option>
	<option value="Odaiba Net (Podcast) - www.poderato.com/odaibanet">Odaiba Net (Podcast) - www.poderato.com/odaibanet</option>
</select>
</div>
<div id="for-speed" style="display: none;">
    <select id="select-speed">
        <option value="0.8">0.8x</option>
        <option value="1.0">1.0x</option>
        <option value="1.2">1.2x</option>
        <option value="1.4">1.4x</option>
        <option value="1.6">1.6x</option>
        <option value="1.8">1.8x</option>
        <option value="2.0">2.0x</option>
    </select>
</div>
<div class="panel" id="panelplayer" style="height: 70px;">
    <div id="player">
        <a href="#" id="left" onclick="return false" title="Anterior">
            <span class="control-icon previous-icon" aria-hidden="true"></span>
        </a>
        <a href="#" id="play-pause" onclick="return false" title="Reproducir">
            <span class="control-icon play-icon" aria-hidden="true"></span>
        </a>
        <a href="#" id="right" onclick="return false" title="Siguiente">
            <span class="control-icon next-icon" aria-hidden="true"></span>
        </a>
        <audio id="audio" preload="auto" tabindex="0" src="">
            <source src="">
        </audio>
    </div>
    <div id="playing">
        <span id="media-info">
            <span id="podcast"></span>
            <span id="duration"></span>
        </span>
        <span id="track"></span>
        <progress id="progressbar" max="100" value=""></progress>
    </div>
    <div id="controls" style="float: left;">
        <!--
        <a href="#" id="volume" onclick="return false" title="Volumen">
            <span class="control-icon volume-icon" aria-hidden="true"></span>
        </a>
        <a href="#" id="random" onclick="return false" title="Volumen">
            <span class="control-icon norandom-icon" aria-hidden="true"></span>
        </a>
        -->
        <a href="#" id="search" onclick="return false" title="Filtrar">
            <span class="control-icon search-icon" aria-hidden="true"></span>
        </a>
        <a href='#' id="speed" onclick="return false" title="Velocidad">
            <span id="speed-value" aria-hidden="true">1.0x</span>
        </a>
        <!--
        <a href="#" id="download" onclick="return false" title="Descargar">
            <span class="control-icon download-icon" aria-hidden="true"></span>
        </a>
        -->
    </div>
</div>

<div class="panel">
    <ul id="playlist">
        <li class="active">
	<span id="item-0">
		<a href="#" data-media="http://www.ivoox.com/tu-biblioteca-nube-hazte-profesor-de_mf_23607219_feed_1.mp3" title="Tu Biblioteca en la Nube. Hazte profesor de FP">
			<span class="isplaying"></span>
			<span class="logo mosqueterowebtecnologialinuxchromebooks"></span>
			<span class="podcast">Mosqueteroweb tecnologia, Linux, Chromebooks</span>
			<span class="track">Tu Biblioteca en la Nube. Hazte profesor de FP</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1">
		<a href="#" data-media="https://cuonda.com/mixxio/rumbo-al-cinturon-de-asteroides/534845.mp3" title="Rumbo al cinturĂłn de asteroides">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologăaynegocios"></span>
			<span class="podcast">mixx.io, tecnologĂ­a y negocios</span>
			<span class="track">Rumbo al cinturĂłn de asteroides</span>
		</a>
	</span>
</li>
<li>
	<span id="item-2">
		<a href="#" data-media="http://api.spreaker.com/download/episode/13988738/starman_y_1_000_seguidores.mp3" title="Starman y 1.000 seguidores">
			<span class="isplaying"></span>
			<span class="logo deknet"></span>
			<span class="podcast">DekNet</span>
			<span class="track">Starman y 1.000 seguidores</span>
		</a>
	</span>
</li>
<li>
	<span id="item-3">
		<a href="#" data-media="http://www.ivoox.com/radiogeek-resumen-diario-dia-6-febrero_mf_23596875_feed_1.mp3" title="#Radiogeek - Resumen diario día 6 de febrero 2018 #Podcast">
			<span class="isplaying"></span>
			<span class="logo radiogeek"></span>
			<span class="podcast">Radiogeek</span>
			<span class="track">#Radiogeek - Resumen diario día 6 de febrero 2018 #Podcast</span>
		</a>
	</span>
</li>
<li>
	<span id="item-4">
		<a href="#" data-media="https://www.ivoox.com/38-como-funciona-internet-se-interconectan_mf_23590389_feed_1.mp3" title="38 - ¿Cómo funciona internet y se interconectan las redes a nivel mundial?">
			<span class="isplaying"></span>
			<span class="logo naserospodcast"></span>
			<span class="podcast">NASeros Podcast</span>
			<span class="track">38 - ¿Cómo funciona internet y se interconectan las redes a nivel mundial?</span>
		</a>
	</span>
</li>
<li>
	<span id="item-5">
		<a href="#" data-media="https://gitlab.com/podcastlinux/podcastlinux.gitlab.io/raw/master/Linux-Express/34linuxexpress.mp3" title="#34 Linux Express">
			<span class="isplaying"></span>
			<span class="logo linuxexpressdepodcastlinux"></span>
			<span class="podcast">Linux Express, de Podcast Linux.</span>
			<span class="track">#34 Linux Express</span>
		</a>
	</span>
</li>
<li>
	<span id="item-6">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2018/02/podcast-110-coliad.mp3" title="Podcast #110: Codiad, tu propio IDE online">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #110: Codiad, tu propio IDE online</span>
		</a>
	</span>
</li>
<li>
	<span id="item-7">
		<a href="#" data-media="http://www.ivoox.com/code-time-100-los-problemas-del-infierno-de_mf_23581268_feed_1.mp3" title="Code Time (100): Los problemas del infierno de las dependencias">
			<span class="isplaying"></span>
			<span class="logo codetime"></span>
			<span class="podcast">Code Time</span>
			<span class="track">Code Time (100): Los problemas del infierno de las dependencias</span>
		</a>
	</span>
</li>
<li>
	<span id="item-8">
		<a href="#" data-media="http://api.spreaker.com/download/episode/13978143/webreactiva_podcast_21.mp3" title="WR 21: Gestión de equipos y desarrollo de software con Israel Alcázar">
			<span class="isplaying"></span>
			<span class="logo webreactiva"></span>
			<span class="podcast">Web Reactiva</span>
			<span class="track">WR 21: Gestión de equipos y desarrollo de software con Israel Alcázar</span>
		</a>
	</span>
</li>
<li>
	<span id="item-9">
		<a href="#" data-media="https://cuonda.com/mixxio/heavy-heavy-super-heavy/532000.mp3" title="Heavy, heavy, super heavy">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologăaynegocios"></span>
			<span class="podcast">mixx.io, tecnologĂ­a y negocios</span>
			<span class="track">Heavy, heavy, super heavy</span>
		</a>
	</span>
</li>
<li>
	<span id="item-10">
		<a href="#" data-media="http://feedproxy.google.com/~r/Vaciatubandeja/~5/4mxgOwvXiS0/6642655.mp3" title="17: Simplifica aplicaciones | Un poco de Minimalismo">
			<span class="isplaying"></span>
			<span class="logo vacíatubandeja"></span>
			<span class="podcast">Vacía tu bandeja</span>
			<span class="track">17: Simplifica aplicaciones | Un poco de Minimalismo</span>
		</a>
	</span>
</li>
<li>
	<span id="item-11">
		<a href="#" data-media="http://api.spreaker.com/download/episode/13973919/podcast127.mp3" title="#127. Memoria de Arduino y alimentación ESP8266">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">#127. Memoria de Arduino y alimentación ESP8266</span>
		</a>
	</span>
</li>
<li>
	<span id="item-12">
		<a href="#" data-media="http://www.ivoox.com/anecdotas-giordanicas-6-como-comenzo-code-time_mf_23569001_feed_1.mp3" title="Anécdotas Giordánicas (6): ¿Cómo comenzó Code Time?">
			<span class="isplaying"></span>
			<span class="logo codetime"></span>
			<span class="podcast">Code Time</span>
			<span class="track">Anécdotas Giordánicas (6): ¿Cómo comenzó Code Time?</span>
		</a>
	</span>
</li>
<li>
	<span id="item-13">
		<a href="#" data-media="http://www.ivoox.com/radiogeek-resumen-diario-dia-5-febrero_mf_23567657_feed_1.mp3" title="#Radiogeek - Resumen diario día 5 de febrero 2018 #Podcast">
			<span class="isplaying"></span>
			<span class="logo radiogeek"></span>
			<span class="podcast">Radiogeek</span>
			<span class="track">#Radiogeek - Resumen diario día 5 de febrero 2018 #Podcast</span>
		</a>
	</span>
</li>
<li>
	<span id="item-14">
		<a href="#" data-media="http://traffic.libsyn.com/cesargarciasaez/LHM143.mp3" title="LHM143 en directo – Preguntas y Proyectos con David Cuartielles (Enero 2018)">
			<span class="isplaying"></span>
			<span class="logo lahoramaker"></span>
			<span class="podcast">La Hora Maker</span>
			<span class="track">LHM143 en directo – Preguntas y Proyectos con David Cuartielles (Enero 2018)</span>
		</a>
	</span>
</li>
<li>
	<span id="item-15">
		<a href="#" data-media="https://anchor.fm/s/18c0860/podcast/play/125487/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fanchor-data%2Fstationexports%2Fpodcasts%2F5-Comando-5-Usos-para-Git-246a8c672fee1.m4a" title="5 Comando 5 Usos para Git">
			<span class="isplaying"></span>
			<span class="logo tomandouncafé"></span>
			<span class="podcast">Tomando Un Café</span>
			<span class="track">5 Comando 5 Usos para Git</span>
		</a>
	</span>
</li>
<li>
	<span id="item-16">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2018/02/podcast-109-pcs-sincronizados.mp3" title="Podcast #109: Mantener dos PCs totalmente sincronizados con linux">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #109: Mantener dos PCs totalmente sincronizados con linux</span>
		</a>
	</span>
</li>
<li>
	<span id="item-17">
		<a href="#" data-media="http://tracking.feedpress.it/link/15407/8174279/BCS022-Bitcoin-ETEPolitica-BitaCiber.mp3" title="BCS022 – Bitcoin, con ETEPolitica y BitaCiber">
			<span class="isplaying"></span>
			<span class="logo bitácoradeciberseguridad"></span>
			<span class="podcast">Bitácora de Ciberseguridad</span>
			<span class="track">BCS022 – Bitcoin, con ETEPolitica y BitaCiber</span>
		</a>
	</span>
</li>
<li>
	<span id="item-18">
		<a href="#" data-media="https://cuonda.com/mixxio/guerras-musicales-de-ayer-y-hoy/529148.mp3" title="Guerras musicales de ayer y hoy">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologăaynegocios"></span>
			<span class="podcast">mixx.io, tecnologĂ­a y negocios</span>
			<span class="track">Guerras musicales de ayer y hoy</span>
		</a>
	</span>
</li>
<li>
	<span id="item-19">
		<a href="#" data-media="http://api.spreaker.com/download/episode/13970313/lametric_time_take_2.mp3" title="LaMetric Time, take 2">
			<span class="isplaying"></span>
			<span class="logo deknet"></span>
			<span class="podcast">DekNet</span>
			<span class="track">LaMetric Time, take 2</span>
		</a>
	</span>
</li>
<li>
	<span id="item-20">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2018/02/podcast-108-for-y-awk-en-bash.mp3" title="Podcast #108: for y awk en bash">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #108: for y awk en bash</span>
		</a>
	</span>
</li>
<li>
	<span id="item-21">
		<a href="#" data-media="http://www.ivoox.com/radiogeek-match-com-expertos-relaciones-amorosas-entrevista_mf_23542495_feed_1.mp3" title="#Radiogeek - Match.com expertos en relaciones amorosas, entrevista a Directivo">
			<span class="isplaying"></span>
			<span class="logo radiogeek"></span>
			<span class="podcast">Radiogeek</span>
			<span class="track">#Radiogeek - Match.com expertos en relaciones amorosas, entrevista a Directivo</span>
		</a>
	</span>
</li>
<li>
	<span id="item-22">
		<a href="#" data-media="https://cuonda.com/mixxio/kernel-el-exito-de-oneplus/527477.mp3" title="Kernel: El ĂŠxito de OnePlus">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologăaynegocios"></span>
			<span class="podcast">mixx.io, tecnologĂ­a y negocios</span>
			<span class="track">Kernel: El ĂŠxito de OnePlus</span>
		</a>
	</span>
</li>
<li>
	<span id="item-23">
		<a href="#" data-media="http://feedproxy.google.com/~r/Vaciatubandeja/~5/nrqSX5BrfiM/6639181.mp3" title="6: Identifica bien tus Bandejas de Entrada">
			<span class="isplaying"></span>
			<span class="logo vacíatubandeja"></span>
			<span class="podcast">Vacía tu bandeja</span>
			<span class="track">6: Identifica bien tus Bandejas de Entrada</span>
		</a>
	</span>
</li>
<li>
	<span id="item-24">
		<a href="#" data-media="http://feedproxy.google.com/~r/Vaciatubandeja/~5/qJ1RPBPfpiM/6639178.mp3" title="5: Bullet Journal | Vista semanal y Areas de responsabilidad">
			<span class="isplaying"></span>
			<span class="logo vacíatubandeja"></span>
			<span class="podcast">Vacía tu bandeja</span>
			<span class="track">5: Bullet Journal | Vista semanal y Areas de responsabilidad</span>
		</a>
	</span>
</li>
<li>
	<span id="item-25">
		<a href="#" data-media="http://feedproxy.google.com/~r/Vaciatubandeja/~5/VLkDjpYZUwQ/6639176.mp3" title="4: Cómo crear un hábito nuevo">
			<span class="isplaying"></span>
			<span class="logo vacíatubandeja"></span>
			<span class="podcast">Vacía tu bandeja</span>
			<span class="track">4: Cómo crear un hábito nuevo</span>
		</a>
	</span>
</li>
<li>
	<span id="item-26">
		<a href="#" data-media="http://feedproxy.google.com/~r/Vaciatubandeja/~5/Vcm8mmXt0hU/6639171.mp3" title="3: El funcionamiento del hábito">
			<span class="isplaying"></span>
			<span class="logo vacíatubandeja"></span>
			<span class="podcast">Vacía tu bandeja</span>
			<span class="track">3: El funcionamiento del hábito</span>
		</a>
	</span>
</li>
<li>
	<span id="item-27">
		<a href="#" data-media="http://feedproxy.google.com/~r/Vaciatubandeja/~5/QrR3Zgg74gc/6639170.mp3" title="2: Cómo empezar a ser organizado">
			<span class="isplaying"></span>
			<span class="logo vacíatubandeja"></span>
			<span class="podcast">Vacía tu bandeja</span>
			<span class="track">2: Cómo empezar a ser organizado</span>
		</a>
	</span>
</li>
<li>
	<span id="item-28">
		<a href="#" data-media="http://feedproxy.google.com/~r/Vaciatubandeja/~5/h54KdQK_KDY/6639165.mp3" title="1: Organízate con Bullet Journal">
			<span class="isplaying"></span>
			<span class="logo vacíatubandeja"></span>
			<span class="podcast">Vacía tu bandeja</span>
			<span class="track">1: Organízate con Bullet Journal</span>
		</a>
	</span>
</li>
<li>
	<span id="item-29">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/Ep117.mp3" title="Moléculas en el espacio y AstroQuímica [Ep.117]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Moléculas en el espacio y AstroQuímica [Ep.117]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-30">
		<a href="#" data-media="http://traffic.libsyn.com/cesargarciasaez/LHM142.mp3" title="LHM142 – Escornabot, los robots educativos libres con Pablo Rubio">
			<span class="isplaying"></span>
			<span class="logo lahoramaker"></span>
			<span class="podcast">La Hora Maker</span>
			<span class="track">LHM142 – Escornabot, los robots educativos libres con Pablo Rubio</span>
		</a>
	</span>
</li>
<li>
	<span id="item-31">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/8146752/Bat2x100_177.m4a" title="#177 – Ya estamos a viernes !">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#177 – Ya estamos a viernes !</span>
		</a>
	</span>
</li>
<li>
	<span id="item-32">
		<a href="#" data-media="https://cuonda.com/mixxio/encuentra-la-x/520512.mp3" title="Encuentra la X">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologăaynegocios"></span>
			<span class="podcast">mixx.io, tecnologĂ­a y negocios</span>
			<span class="track">Encuentra la X</span>
		</a>
	</span>
</li>
<li>
	<span id="item-33">
		<a href="#" data-media="http://ar.ivoox.com/es/radiogeek-resumen-diario-dia-1-febrero_mf_23506451_feed_1.mp3" title="#Radiogeek - Resumen diario día 1 de febrero 2018 #Podcast">
			<span class="isplaying"></span>
			<span class="logo radiogeek"></span>
			<span class="podcast">Radiogeek</span>
			<span class="track">#Radiogeek - Resumen diario día 1 de febrero 2018 #Podcast</span>
		</a>
	</span>
</li>
<li>
	<span id="item-34">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2018/01/podcast-107-kanboard.mp3" title="Podcast #107: KanBoard, como Trello, pero tú tienes los datos">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #107: KanBoard, como Trello, pero tú tienes los datos</span>
		</a>
	</span>
</li>
<li>
	<span id="item-35">
		<a href="#" data-media="http://www.ivoox.com/ep148-la-ciencia-del-codice-secreto-voynich_mf_23502664_feed_1.mp3" title="Ep148: La Ciencia del Códice Secreto de Voynich; Materia Oscura de la Vía Láctea; El Preocupante Fallo del Ariane 5">
			<span class="isplaying"></span>
			<span class="logo coffeebreakseñalyruido"></span>
			<span class="podcast">Coffee Break: Señal y Ruido</span>
			<span class="track">Ep148: La Ciencia del Códice Secreto de Voynich; Materia Oscura de la Vía Láctea; El Preocupante Fallo del Ariane 5</span>
		</a>
	</span>
</li>
<li>
	<span id="item-36">
		<a href="#" data-media="http://www.ivoox.com/30-la-chica-no-queria-aprender-fotografia_mf_23491325_feed_1.mp3" title="#30 La chica que no quería aprender fotografía">
			<span class="isplaying"></span>
			<span class="logo reflexpodcast"></span>
			<span class="podcast">reflex podcast</span>
			<span class="track">#30 La chica que no quería aprender fotografía</span>
		</a>
	</span>
</li>
<li>
	<span id="item-37">
		<a href="#" data-media="https://cuonda.com/mixxio/facebook-es-una-maquina-de-hacer-dinero/518315.mp3" title="Facebook es una mĂĄquina de hacer dinero">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologăaynegocios"></span>
			<span class="podcast">mixx.io, tecnologĂ­a y negocios</span>
			<span class="track">Facebook es una mĂĄquina de hacer dinero</span>
		</a>
	</span>
</li>
<li>
	<span id="item-38">
		<a href="#" data-media="http://tracking.feedpress.it/link/15407/8130676/BCS021-Meltdown-y-Spectre.mp3" title="BCS021 – Meltdown y Spectre">
			<span class="isplaying"></span>
			<span class="logo bitácoradeciberseguridad"></span>
			<span class="podcast">Bitácora de Ciberseguridad</span>
			<span class="track">BCS021 – Meltdown y Spectre</span>
		</a>
	</span>
</li>
<li>
	<span id="item-39">
		<a href="#" data-media="http://api.spreaker.com/download/episode/13937391/mensajeria_para_las_masas_signal_para_el_resto.mp3" title="Mensajeria para las masas, Signal para el resto">
			<span class="isplaying"></span>
			<span class="logo deknet"></span>
			<span class="podcast">DekNet</span>
			<span class="track">Mensajeria para las masas, Signal para el resto</span>
		</a>
	</span>
</li>
<li>
	<span id="item-40">
		<a href="#" data-media="https://ia601502.us.archive.org/10/items/090.screen/090.screen.mp3" title="090. Screen y la Terminal">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">090. Screen y la Terminal</span>
		</a>
	</span>
</li>
<li>
	<span id="item-41">
		<a href="#" data-media="http://www.ivoox.com/radiogeek-resumen-diario-dia-31-enero_mf_23484079_feed_1.mp3" title="#Radiogeek - Resumen diario día 31 de enero 2018 #Podcast">
			<span class="isplaying"></span>
			<span class="logo radiogeek"></span>
			<span class="podcast">Radiogeek</span>
			<span class="track">#Radiogeek - Resumen diario día 31 de enero 2018 #Podcast</span>
		</a>
	</span>
</li>
<li>
	<span id="item-42">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2018/01/podcast-106-tuneles-ssh.mp3" title="Podcast #106: Túneles ssh">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #106: Túneles ssh</span>
		</a>
	</span>
</li>
<li>
	<span id="item-43">
		<a href="#" data-media="http://www.ivoox.com/44-linux-connexion-vant_mf_23463564_feed_1.mp3" title="#44 Linux Connexion con Vant">
			<span class="isplaying"></span>
			<span class="logo podcastlinux"></span>
			<span class="podcast">Podcast Linux</span>
			<span class="track">#44 Linux Connexion con Vant</span>
		</a>
	</span>
</li>
<li>
	<span id="item-44">
		<a href="#" data-media="https://cuonda.com/mixxio/apple-pisa-el-freno-con-ios/518314.mp3" title="Apple pisa el freno con iOS">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologăaynegocios"></span>
			<span class="podcast">mixx.io, tecnologĂ­a y negocios</span>
			<span class="track">Apple pisa el freno con iOS</span>
		</a>
	</span>
</li>
<li>
	<span id="item-45">
		<a href="#" data-media="http://www.ivoox.com/radiogeek-resumen-diario-dia-30-enero_mf_23459991_feed_1.mp3" title="#Radiogeek - Resumen diario día 30 de enero 2018 #Podcast">
			<span class="isplaying"></span>
			<span class="logo radiogeek"></span>
			<span class="podcast">Radiogeek</span>
			<span class="track">#Radiogeek - Resumen diario día 30 de enero 2018 #Podcast</span>
		</a>
	</span>
</li>
<li>
	<span id="item-46">
		<a href="#" data-media="https://anchor.fm/s/18c0860/podcast/play/119407/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fanchor-data%2Fstationexports%2Fpodcasts%2Fcurso-de-programaci-n-9b58c02bdc9fd.m4a" title="curso de programación">
			<span class="isplaying"></span>
			<span class="logo tomandouncafé"></span>
			<span class="podcast">Tomando Un Café</span>
			<span class="track">curso de programación</span>
		</a>
	</span>
</li>
<li>
	<span id="item-47">
		<a href="#" data-media="https://archive.org/download/44CrearPuntoDeAccesoConPc/44-crear-punto-de-acceso-con-pc.mp3" title="#44 Cómo crear un punto de acceso WiFi con un PC">
			<span class="isplaying"></span>
			<span class="logo educandogeek"></span>
			<span class="podcast">eDucando Geek</span>
			<span class="track">#44 Cómo crear un punto de acceso WiFi con un PC</span>
		</a>
	</span>
</li>
<li>
	<span id="item-48">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2018/01/podcast-105-formacion-con-jose-jimenez.mp3" title="Podcast #105: Formación con José Jiménez">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #105: Formación con José Jiménez</span>
		</a>
	</span>
</li>
<li>
	<span id="item-49">
		<a href="#" data-media="http://api.spreaker.com/download/episode/13926337/imported_1517330552.mp3" title="Micro Podcast ZUNGLE">
			<span class="isplaying"></span>
			<span class="logo deknet"></span>
			<span class="podcast">DekNet</span>
			<span class="track">Micro Podcast ZUNGLE</span>
		</a>
	</span>
</li>
<li>
	<span id="item-50">
		<a href="#" data-media="http://ia600808.us.archive.org/9/items/NolegaltechRadio/007NolegaltechRadio-laPropiedadDelCdigo.mp3" title="#007-Propiedad del código">
			<span class="isplaying"></span>
			<span class="logo nolegaltechradio"></span>
			<span class="podcast">NOlegaltech Radio</span>
			<span class="track">#007-Propiedad del código</span>
		</a>
	</span>
</li>
<li>
	<span id="item-51">
		<a href="#" data-media="http://api.spreaker.com/download/episode/13923627/webreactiva_podcast_20.mp3" title="WR 20: Sitios estáticos y datos dinámicos con Gatsby">
			<span class="isplaying"></span>
			<span class="logo webreactiva"></span>
			<span class="podcast">Web Reactiva</span>
			<span class="track">WR 20: Sitios estáticos y datos dinámicos con Gatsby</span>
		</a>
	</span>
</li>
<li>
	<span id="item-52">
		<a href="#" data-media="https://www.ivoox.com/code-time-99-que-es-infierno-de_mf_23434569_feed_1.mp3" title="Code Time (99): ¿Qué es el infierno de las dependencias? + Importante anuncio">
			<span class="isplaying"></span>
			<span class="logo codetime"></span>
			<span class="podcast">Code Time</span>
			<span class="track">Code Time (99): ¿Qué es el infierno de las dependencias? + Importante anuncio</span>
		</a>
	</span>
</li>
<li>
	<span id="item-53">
		<a href="#" data-media="https://cuonda.com/mixxio/lanzando-cosas-al-espacio/518313.mp3" title="Lanzando cosas al espacio">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologăaynegocios"></span>
			<span class="podcast">mixx.io, tecnologĂ­a y negocios</span>
			<span class="track">Lanzando cosas al espacio</span>
		</a>
	</span>
</li>
<li>
	<span id="item-54">
		<a href="#" data-media="http://api.spreaker.com/download/episode/13916892/podcast126.mp3" title="#126 ¿Arduino y ESP se unen? Proyectos que salvan vidas y muchas cosas más">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">#126 ¿Arduino y ESP se unen? Proyectos que salvan vidas y muchas cosas más</span>
		</a>
	</span>
</li>
<li>
	<span id="item-55">
		<a href="#" data-media="http://www.ivoox.com/radiogeek-resumen-diario-dia-29-enero_mf_23431052_feed_1.mp3" title="#Radiogeek - Resumen diario día 29 de enero 2018 #Podcast">
			<span class="isplaying"></span>
			<span class="logo radiogeek"></span>
			<span class="podcast">Radiogeek</span>
			<span class="track">#Radiogeek - Resumen diario día 29 de enero 2018 #Podcast</span>
		</a>
	</span>
</li>
<li>
	<span id="item-56">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2018/01/podcast-104-zammad.mp3" title="Podcast #104: Zammad, gestión de tickets">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #104: Zammad, gestión de tickets</span>
		</a>
	</span>
</li>
<li>
	<span id="item-57">
		<a href="#" data-media="http://api.spreaker.com/download/episode/13914226/paranoia_contable.mp3" title="Paranoia contable">
			<span class="isplaying"></span>
			<span class="logo deknet"></span>
			<span class="podcast">DekNet</span>
			<span class="track">Paranoia contable</span>
		</a>
	</span>
</li>
<li>
	<span id="item-58">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/5a6ec6639e91b02b750c99cb.mp3" title="Camarero, hay un bot en mi sopa">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologăaynegocios"></span>
			<span class="podcast">mixx.io, tecnologĂ­a y negocios</span>
			<span class="track">Camarero, hay un bot en mi sopa</span>
		</a>
	</span>
</li>
<li>
	<span id="item-59">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/Ep116.mp3" title="El Futuro de la NASA en Astrofísica [Ep.116]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">El Futuro de la NASA en Astrofísica [Ep.116]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-60">
		<a href="#" data-media="http://www.ivoox.com/radiogeek-como-definir-tu-proximo-estudio-con_mf_23409767_feed_1.mp3" title="#Radiogeek - ¿Como definir tu próximo estudio? con un test vocacional en línea">
			<span class="isplaying"></span>
			<span class="logo radiogeek"></span>
			<span class="podcast">Radiogeek</span>
			<span class="track">#Radiogeek - ¿Como definir tu próximo estudio? con un test vocacional en línea</span>
		</a>
	</span>
</li>
<li>
	<span id="item-61">
		<a href="#" data-media="https://www.ivoox.com/episodio-19-lecciones-aprendidas_mf_23408968_feed_1.mp3" title="Episodio 19 - Lecciones aprendidas">
			<span class="isplaying"></span>
			<span class="logo programaresunamierda"></span>
			<span class="podcast">Programar es una mierda</span>
			<span class="track">Episodio 19 - Lecciones aprendidas</span>
		</a>
	</span>
</li>
<li>
	<span id="item-62">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2018/01/podcast-103-spanning-tree-casero.mp3" title="Podcast #103: Spanning tree casero con dos mikrotiks">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #103: Spanning tree casero con dos mikrotiks</span>
		</a>
	</span>
</li>
<li>
	<span id="item-63">
		<a href="#" data-media="http://www.ivoox.com/romper-monopolios-internet-va-a_mf_23407196_feed_1.mp3" title="Romper con los monopolios de internet va a ser duro | Episodio 65">
			<span class="isplaying"></span>
			<span class="logo repúblicaweb"></span>
			<span class="podcast">República Web</span>
			<span class="track">Romper con los monopolios de internet va a ser duro | Episodio 65</span>
		</a>
	</span>
</li>
<li>
	<span id="item-64">
		<a href="#" data-media="http://api.spreaker.com/download/episode/13906770/internet_del_valor_la_internet_vital.mp3" title="Internet del valor, la Internet vital">
			<span class="isplaying"></span>
			<span class="logo deknet"></span>
			<span class="podcast">DekNet</span>
			<span class="track">Internet del valor, la Internet vital</span>
		</a>
	</span>
</li>
<li>
	<span id="item-65">
		<a href="#" data-media="http://mundipad.es/capitulos-podcast-bemoob/098-foromoviles-podcast.mp3" title="ForoMoviles Podcast 098: Presente, pasado y futuro de los móviles">
			<span class="isplaying"></span>
			<span class="logo podcastforomóviles"></span>
			<span class="podcast">Podcast – ForoMóviles</span>
			<span class="track">ForoMoviles Podcast 098: Presente, pasado y futuro de los móviles</span>
		</a>
	</span>
</li>
<li>
	<span id="item-66">
		<a href="#" data-media="http://podcast.edyo.es/podcast/edyo-pildora2.mp3" title="EDyO píldora 2 - Migrando la web a Hugo.">
			<span class="isplaying"></span>
			<span class="logo entredevyopspodcast"></span>
			<span class="podcast">EntreDevYOps Podcast</span>
			<span class="track">EDyO píldora 2 - Migrando la web a Hugo.</span>
		</a>
	</span>
</li>
<li>
	<span id="item-67">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/5a6cca219e91b02b750c60e6.mp3" title="Kernel: NiĂąos, Mentiras y Cintas de VĂ­deo (Audio corregido)">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologăaynegocios"></span>
			<span class="podcast">mixx.io, tecnologĂ­a y negocios</span>
			<span class="track">Kernel: NiĂąos, Mentiras y Cintas de VĂ­deo (Audio corregido)</span>
		</a>
	</span>
</li>
<li>
	<span id="item-68">
		<a href="#" data-media="http://compilando.audio/wp-content/uploads/2018/01/podcast21.mp3" title="Especial Mesa Redonda : Estado actual del software libre y GNU/Linux, terminado 2017 y comenzando 2018.">
			<span class="isplaying"></span>
			<span class="logo compilandopodcast"></span>
			<span class="podcast">Compilando Podcast</span>
			<span class="track">Especial Mesa Redonda : Estado actual del software libre y GNU/Linux, terminado 2017 y comenzando 2018.</span>
		</a>
	</span>
</li>
<li>
	<span id="item-69">
		<a href="#" data-media="https://ia801509.us.archive.org/21/items/089TelegramStreaming/089-Telegram-streaming.mp3" title="089. Telegram: Audio y Vídeo en Streaming">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">089. Telegram: Audio y Vídeo en Streaming</span>
		</a>
	</span>
</li>
<li>
	<span id="item-70">
		<a href="#" data-media="http://www.ivoox.com/xiaomi-problemas-chromebooks-nuevos-tablets-baterias-qc_mf_23378217_feed_1.mp3" title="Xiaomi y problemas. Chromebooks nuevos. Tablets. Baterías QC">
			<span class="isplaying"></span>
			<span class="logo mosqueterowebtecnologialinuxchromebooks"></span>
			<span class="podcast">Mosqueteroweb tecnologia, Linux, Chromebooks</span>
			<span class="track">Xiaomi y problemas. Chromebooks nuevos. Tablets. Baterías QC</span>
		</a>
	</span>
</li>
<li>
	<span id="item-71">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/5a6ad2139e91b02b750c20ea.mp3" title="Lanzallamas y pantuflas">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologăaynegocios"></span>
			<span class="podcast">mixx.io, tecnologĂ­a y negocios</span>
			<span class="track">Lanzallamas y pantuflas</span>
		</a>
	</span>
</li>
<li>
	<span id="item-72">
		<a href="#" data-media="http://www.ivoox.com/producto-ideal-cap-84_mf_23370703_feed_1.mp3" title="El producto ideal - Cap 84">
			<span class="isplaying"></span>
			<span class="logo podcastwintabletinfo"></span>
			<span class="podcast">Podcast WINTABLET.INFO</span>
			<span class="track">El producto ideal - Cap 84</span>
		</a>
	</span>
</li>
<li>
	<span id="item-73">
		<a href="#" data-media="http://ar.ivoox.com/es/radiogeek-resumen-diario-dia-25-enero_mf_23369340_feed_1.mp3" title="#Radiogeek - Resumen diario día 25 de enero 2018 #Podcast">
			<span class="isplaying"></span>
			<span class="logo radiogeek"></span>
			<span class="podcast">Radiogeek</span>
			<span class="track">#Radiogeek - Resumen diario día 25 de enero 2018 #Podcast</span>
		</a>
	</span>
</li>
<li>
	<span id="item-74">
		<a href="#" data-media="https://anchor.fm/s/18c0860/podcast/play/114184/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fanchor-data%2Fstationexports%2Fpodcasts%2FRadicale-y-Baikal-5283c3ebd11fa.m4a" title="Radicale y Baikal">
			<span class="isplaying"></span>
			<span class="logo tomandouncafé"></span>
			<span class="podcast">Tomando Un Café</span>
			<span class="track">Radicale y Baikal</span>
		</a>
	</span>
</li>
<li>
	<span id="item-75">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2018/01/podcast-102-ssh.mp3" title="Podcast #102: SSH">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #102: SSH</span>
		</a>
	</span>
</li>
<li>
	<span id="item-76">
		<a href="#" data-media="http://www.ivoox.com/ep147-piramides-trono-hierro-meteorito-hipatia-pinturas_mf_23361703_feed_1.mp3" title="Ep147: Pirámides: Trono de hierro, meteorito Hipatia, pinturas egipcias, la Tabby “Hipster”, Geoingeniería, NASA cerrada">
			<span class="isplaying"></span>
			<span class="logo coffeebreakseñalyruido"></span>
			<span class="podcast">Coffee Break: Señal y Ruido</span>
			<span class="track">Ep147: Pirámides: Trono de hierro, meteorito Hipatia, pinturas egipcias, la Tabby “Hipster”, Geoingeniería, NASA cerrada</span>
		</a>
	</span>
</li>
<li>
	<span id="item-77">
		<a href="#" data-media="http://api.spreaker.com/download/episode/13885382/sistemas_de_alarma_menos_es_mucho_m_s.mp3" title="Sistemas de alarma: Menos, es mucho más">
			<span class="isplaying"></span>
			<span class="logo deknet"></span>
			<span class="podcast">DekNet</span>
			<span class="track">Sistemas de alarma: Menos, es mucho más</span>
		</a>
	</span>
</li>
<li>
	<span id="item-78">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/5a69838ddb5e932b6f32ec81.mp3" title="Multas, sanciones y otras cosas del amor">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologăaynegocios"></span>
			<span class="podcast">mixx.io, tecnologĂ­a y negocios</span>
			<span class="track">Multas, sanciones y otras cosas del amor</span>
		</a>
	</span>
</li>
<li>
	<span id="item-79">
		<a href="#" data-media="https://ia601502.us.archive.org/32/items/88Telegramx/88-telegramx.mp3" title="088. Telegram X">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">088. Telegram X</span>
		</a>
	</span>
</li>
<li>
	<span id="item-80">
		<a href="#" data-media="http://www.ivoox.com/me-compro-nas-o-monto-servidor_mf_23349931_feed_1.mp3" title="¿Me compro un NAS o monto un servidor? Virtualizacion en servidores">
			<span class="isplaying"></span>
			<span class="logo naserospodcast"></span>
			<span class="podcast">NASeros Podcast</span>
			<span class="track">¿Me compro un NAS o monto un servidor? Virtualizacion en servidores</span>
		</a>
	</span>
</li>
<li>
	<span id="item-81">
		<a href="#" data-media="http://www.ivoox.com/radiogeek-resumen-diario-dia-24-enero_mf_23347879_feed_1.mp3" title="#Radiogeek - Resumen diario día 24 de enero 2018 #Podcast">
			<span class="isplaying"></span>
			<span class="logo radiogeek"></span>
			<span class="podcast">Radiogeek</span>
			<span class="track">#Radiogeek - Resumen diario día 24 de enero 2018 #Podcast</span>
		</a>
	</span>
</li>
<li>
	<span id="item-82">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2018/01/podcast-101-metarouters-mikrotik.mp3" title="Podcast #101: Metarouters de Mikrotik">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #101: Metarouters de Mikrotik</span>
		</a>
	</span>
</li>
<li>
	<span id="item-83">
		<a href="#" data-media="http://www.ivoox.com/29-youtube-creadores-emosido-enganado_mf_23340586_feed_1.mp3" title="#29 Youtube, los creadores emosido engañado">
			<span class="isplaying"></span>
			<span class="logo reflexpodcast"></span>
			<span class="podcast">reflex podcast</span>
			<span class="track">#29 Youtube, los creadores emosido engañado</span>
		</a>
	</span>
</li>
<li>
	<span id="item-84">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/5a682a609e91b02b750bdc9f.mp3" title="El HomePod no es un home run">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologăaynegocios"></span>
			<span class="podcast">mixx.io, tecnologĂ­a y negocios</span>
			<span class="track">El HomePod no es un home run</span>
		</a>
	</span>
</li>
<li>
	<span id="item-85">
		<a href="#" data-media="http://ar.ivoox.com/es/radiogeek-resumen-diario-dia-23-enero_mf_23321703_feed_1.mp3" title="#Radiogeek - Resumen diario día 23 de enero 2018 #Podcast">
			<span class="isplaying"></span>
			<span class="logo radiogeek"></span>
			<span class="podcast">Radiogeek</span>
			<span class="track">#Radiogeek - Resumen diario día 23 de enero 2018 #Podcast</span>
		</a>
	</span>
</li>
<li>
	<span id="item-86">
		<a href="#" data-media="https://gitlab.com/podcastlinux/podcastlinux.gitlab.io/raw/master/Linux-Express/33linuxexpress.mp3" title="#33 Linux Express">
			<span class="isplaying"></span>
			<span class="logo linuxexpressdepodcastlinux"></span>
			<span class="podcast">Linux Express, de Podcast Linux.</span>
			<span class="track">#33 Linux Express</span>
		</a>
	</span>
</li>
<li>
	<span id="item-87">
		<a href="#" data-media="https://archive.org/download/43PlexEnRaspberrypi/43-plex-en-raspberrypi.mp3" title="#43 Plex Media Server en mi Raspberry Pi 3 y otros servicios que uso">
			<span class="isplaying"></span>
			<span class="logo educandogeek"></span>
			<span class="podcast">eDucando Geek</span>
			<span class="track">#43 Plex Media Server en mi Raspberry Pi 3 y otros servicios que uso</span>
		</a>
	</span>
</li>
<li>
	<span id="item-88">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2018/01/podcast-100-communities.mp3" title="Podcast #100: Communities de BGP">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #100: Communities de BGP</span>
		</a>
	</span>
</li>
<li>
	<span id="item-89">
		<a href="#" data-media="http://www.ivoox.com/28-1-adios-adobe-lightroom-audio-bueno_mf_23312484_feed_1.mp3" title="#28.1 Adiós adobe Lightroom (audio bueno)">
			<span class="isplaying"></span>
			<span class="logo reflexpodcast"></span>
			<span class="podcast">reflex podcast</span>
			<span class="track">#28.1 Adiós adobe Lightroom (audio bueno)</span>
		</a>
	</span>
</li>
<li>
	<span id="item-90">
		<a href="#" data-media="https://gitlab.com/uGeek/podcasts/raw/master/audios/087-arrancar-raspberry-por-usb.mp3" title="087. Arrancar Raspberry desde USB">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">087. Arrancar Raspberry desde USB</span>
		</a>
	</span>
</li>
<li>
	<span id="item-91">
		<a href="#" data-media="http://api.spreaker.com/download/episode/13870033/webreactiva_podcast_19.mp3" title="WR 19: Microframeworks, microservicios y la corrala de vecinos">
			<span class="isplaying"></span>
			<span class="logo webreactiva"></span>
			<span class="podcast">Web Reactiva</span>
			<span class="track">WR 19: Microframeworks, microservicios y la corrala de vecinos</span>
		</a>
	</span>
</li>
<li>
	<span id="item-92">
		<a href="#" data-media="https://www.ivoox.com/anecdotas-giordanicas-5-como-perdi-2tb-informacion_mf_23298812_feed_1.mp3" title="Anécdotas Giordánicas (5) ¿Cómo perdí 2TB de información y los recuperé? PT 1">
			<span class="isplaying"></span>
			<span class="logo codetime"></span>
			<span class="podcast">Code Time</span>
			<span class="track">Anécdotas Giordánicas (5) ¿Cómo perdí 2TB de información y los recuperé? PT 1</span>
		</a>
	</span>
</li>
<li>
	<span id="item-93">
		<a href="#" data-media="https://www.ivoox.com/anecdotas-giordanicas-5-como-perdi-2tb-informacion_mf_23298811_feed_1.mp3" title="Anécdotas Giordánicas (5) ¿Cómo perdí 2TB de información y los recuperé? PT 2">
			<span class="isplaying"></span>
			<span class="logo codetime"></span>
			<span class="podcast">Code Time</span>
			<span class="track">Anécdotas Giordánicas (5) ¿Cómo perdí 2TB de información y los recuperé? PT 2</span>
		</a>
	</span>
</li>
<li>
	<span id="item-94">
		<a href="#" data-media="https://www.ivoox.com/anecdotas-giordanicas-5-como-perdi-2tb-informacion_mf_23298810_feed_1.mp3" title="Anécdotas Giordánicas (5) ¿Cómo perdí 2TB de información y los recuperé? PT 3">
			<span class="isplaying"></span>
			<span class="logo codetime"></span>
			<span class="podcast">Code Time</span>
			<span class="track">Anécdotas Giordánicas (5) ¿Cómo perdí 2TB de información y los recuperé? PT 3</span>
		</a>
	</span>
</li>
<li>
	<span id="item-95">
		<a href="#" data-media="https://cuonda.com/mixxio/dame-mi-dinero-facebook/518305.mp3" title="Dame mi dinero, Facebook!">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologăaynegocios"></span>
			<span class="podcast">mixx.io, tecnologĂ­a y negocios</span>
			<span class="track">Dame mi dinero, Facebook!</span>
		</a>
	</span>
</li>
<li>
	<span id="item-96">
		<a href="#" data-media="http://api.spreaker.com/download/episode/13860226/podcast125.mp3" title="#125 ¿Por dónde empezar con Arduino? y sistema de riego con SigFox y LoRa">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">#125 ¿Por dónde empezar con Arduino? y sistema de riego con SigFox y LoRa</span>
		</a>
	</span>
</li>
<li>
	<span id="item-97">
		<a href="#" data-media="http://www.ivoox.com/radiogeek-resumen-diario-dia-22-enero_mf_23294533_feed_1.mp3" title="#Radiogeek - Resumen diario día 22 de enero 2018 #Podcast">
			<span class="isplaying"></span>
			<span class="logo radiogeek"></span>
			<span class="podcast">Radiogeek</span>
			<span class="track">#Radiogeek - Resumen diario día 22 de enero 2018 #Podcast</span>
		</a>
	</span>
</li>
<li>
	<span id="item-98">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/8070529/Bat2x100_176.m4a" title="#176 – In reply to Macjosan & Dekkar">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#176 – In reply to Macjosan & Dekkar</span>
		</a>
	</span>
</li>
<li>
	<span id="item-99">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2018/01/podcast-99-monitorizacion-otros-campos.mp3" title="Podcast #99: Usar herramientas de monitorización en otros campos">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #99: Usar herramientas de monitorización en otros campos</span>
		</a>
	</span>
</li>
<li>
	<span id="item-100">
		<a href="#" data-media="http://ia600808.us.archive.org/9/items/NolegaltechRadio/Especial-tendencias2018.mp3" title="Especial-Tendencias 2018, jugamos a ser futurólogos">
			<span class="isplaying"></span>
			<span class="logo nolegaltechradio"></span>
			<span class="podcast">NOlegaltech Radio</span>
			<span class="track">Especial-Tendencias 2018, jugamos a ser futurólogos</span>
		</a>
	</span>
</li>
<li>
	<span id="item-101">
		<a href="#" data-media="http://api.spreaker.com/download/episode/13860188/podcast_en_defensa_de_los_oyentes.mp3" title="PODCAST: En defensa de los oyentes">
			<span class="isplaying"></span>
			<span class="logo deknet"></span>
			<span class="podcast">DekNet</span>
			<span class="track">PODCAST: En defensa de los oyentes</span>
		</a>
	</span>
</li>
<li>
	<span id="item-102">
		<a href="#" data-media="http://api.spreaker.com/download/episode/13860158/cap37_por_que_xiaomi.mp3" title="cap37 - Por qué Xiaomi">
			<span class="isplaying"></span>
			<span class="logo podcastdmanuelalonso"></span>
			<span class="podcast">Podcast dmanuelalonso</span>
			<span class="track">cap37 - Por qué Xiaomi</span>
		</a>
	</span>
</li>
<li>
	<span id="item-103">
		<a href="#" data-media="http://traffic.libsyn.com/cesargarciasaez/LHM141.mp3" title="LHM141 – Novedades tecnológicas en CES 2018 – Impresión 3D, robótica y startups de hardware">
			<span class="isplaying"></span>
			<span class="logo lahoramaker"></span>
			<span class="podcast">La Hora Maker</span>
			<span class="track">LHM141 – Novedades tecnológicas en CES 2018 – Impresión 3D, robótica y startups de hardware</span>
		</a>
	</span>
</li>
<li>
	<span id="item-104">
		<a href="#" data-media="https://cuonda.com/mixxio/llegan-las-tiendas-sin-cajeros-de-amazon/518304.mp3" title="Llegan las tiendas sin cajeros de Amazon">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologăaynegocios"></span>
			<span class="podcast">mixx.io, tecnologĂ­a y negocios</span>
			<span class="track">Llegan las tiendas sin cajeros de Amazon</span>
		</a>
	</span>
</li>
<li>
	<span id="item-105">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2018/01/podcast-98-spanning-tree.mp3" title="Podcast #98: Spanning Tree">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #98: Spanning Tree</span>
		</a>
	</span>
</li>
<li>
	<span id="item-106">
		<a href="#" data-media="http://www.ivoox.com/vendi-mi-alma-al-diablo-servicios-google_mf_23271678_feed_1.mp3" title="Vendí mi alma al Diablo. Servicios de Google">
			<span class="isplaying"></span>
			<span class="logo mosqueterowebtecnologialinuxchromebooks"></span>
			<span class="podcast">Mosqueteroweb tecnologia, Linux, Chromebooks</span>
			<span class="track">Vendí mi alma al Diablo. Servicios de Google</span>
		</a>
	</span>
</li>
<li>
	<span id="item-107">
		<a href="#" data-media="http://www.ivoox.com/27-es-tim-cook-peor-producto-de_mf_23267211_feed_1.mp3" title="#27 ¿Es Tim Cook el peor producto de Apple?">
			<span class="isplaying"></span>
			<span class="logo reflexpodcast"></span>
			<span class="podcast">reflex podcast</span>
			<span class="track">#27 ¿Es Tim Cook el peor producto de Apple?</span>
		</a>
	</span>
</li>
<li>
	<span id="item-108">
		<a href="#" data-media="http://www.ivoox.com/mas-alla-burbuja-bitcoin_mf_23262916_feed_1.mp3" title="Más allá de la burbuja de Bitcoin | Episodio 64">
			<span class="isplaying"></span>
			<span class="logo repúblicaweb"></span>
			<span class="podcast">República Web</span>
			<span class="track">Más allá de la burbuja de Bitcoin | Episodio 64</span>
		</a>
	</span>
</li>
<li>
	<span id="item-109">
		<a href="#" data-media="http://traffic.libsyn.com/cesargarciasaez/LHM126.mp3" title="LHM126 – Internet de las Cosas y el futuro del trabajo – Presentación Informe COTEC">
			<span class="isplaying"></span>
			<span class="logo lahoramaker"></span>
			<span class="podcast">La Hora Maker</span>
			<span class="track">LHM126 – Internet de las Cosas y el futuro del trabajo – Presentación Informe COTEC</span>
		</a>
	</span>
</li>
<li>
	<span id="item-110">
		<a href="#" data-media="http://api.spreaker.com/download/episode/13842337/la_luz_de_la_seguridad.mp3" title="La luz de la seguridad">
			<span class="isplaying"></span>
			<span class="logo deknet"></span>
			<span class="podcast">DekNet</span>
			<span class="track">La luz de la seguridad</span>
		</a>
	</span>
</li>
<li>
	<span id="item-111">
		<a href="#" data-media="http://www.ivoox.com/mosqueteroweb-podcast-se-hace-pago_mf_23240402_feed_1.mp3" title="Mosqueteroweb Podcast se hace de pago">
			<span class="isplaying"></span>
			<span class="logo mosqueterowebtecnologialinuxchromebooks"></span>
			<span class="podcast">Mosqueteroweb tecnologia, Linux, Chromebooks</span>
			<span class="track">Mosqueteroweb Podcast se hace de pago</span>
		</a>
	</span>
</li>
<li>
	<span id="item-112">
		<a href="#" data-media="https://www.ivoox.com/por-he-estado-ausente-todo-este-tiempo_mf_23237220_feed_1.mp3" title="¿Por qué he estado ausente todo este tiempo?">
			<span class="isplaying"></span>
			<span class="logo codetime"></span>
			<span class="podcast">Code Time</span>
			<span class="track">¿Por qué he estado ausente todo este tiempo?</span>
		</a>
	</span>
</li>
<li>
	<span id="item-113">
		<a href="#" data-media="https://cuonda.com/mixxio/twitch-va-a-por-el-contenido-de-youtube/518297.mp3" title="Twitch va a por el contenido de YouTube">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologăaynegocios"></span>
			<span class="podcast">mixx.io, tecnologĂ­a y negocios</span>
			<span class="track">Twitch va a por el contenido de YouTube</span>
		</a>
	</span>
</li>
<li>
	<span id="item-114">
		<a href="#" data-media="https://www.ivoox.com/code-time-celebra-su-segundo-aniversario_mf_23235012_feed_1.mp3" title="Code Time celebra su segundo aniversario">
			<span class="isplaying"></span>
			<span class="logo codetime"></span>
			<span class="podcast">Code Time</span>
			<span class="track">Code Time celebra su segundo aniversario</span>
		</a>
	</span>
</li>
<li>
	<span id="item-115">
		<a href="#" data-media="http://www.ivoox.com/radiogeek-resumen-diario-dia-18-enero_mf_23233887_feed_1.mp3" title="#Radiogeek - Resumen diario día 18 de enero 2018 #Podcast">
			<span class="isplaying"></span>
			<span class="logo radiogeek"></span>
			<span class="podcast">Radiogeek</span>
			<span class="track">#Radiogeek - Resumen diario día 18 de enero 2018 #Podcast</span>
		</a>
	</span>
</li>
<li>
	<span id="item-116">
		<a href="#" data-media="http://www.ivoox.com/episodio-18-agile-manifesto_mf_23232577_feed_1.mp3" title="Episodio 18 - Agile Manifesto">
			<span class="isplaying"></span>
			<span class="logo programaresunamierda"></span>
			<span class="podcast">Programar es una mierda</span>
			<span class="track">Episodio 18 - Agile Manifesto</span>
		</a>
	</span>
</li>
<li>
	<span id="item-117">
		<a href="#" data-media="https://www.ivoox.com/episodio-18-agile-manifesto_mf_23232577_feed_1.mp3" title="Episodio 18 - Agile Manifesto">
			<span class="isplaying"></span>
			<span class="logo programaresunamierda"></span>
			<span class="podcast">Programar es una mierda</span>
			<span class="track">Episodio 18 - Agile Manifesto</span>
		</a>
	</span>
</li>
<li>
	<span id="item-118">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2018/01/podcast-97-asistencia-a-usuario-remoto.mp3" title="Podcast #97: Asistencia al usuario final en remoto">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #97: Asistencia al usuario final en remoto</span>
		</a>
	</span>
</li>
<li>
	<span id="item-119">
		<a href="#" data-media="http://www.ivoox.com/169-youtube-se-pone-duro_mf_23231924_feed_1.mp3" title="#169 Youtube se pone duro">
			<span class="isplaying"></span>
			<span class="logo salmorejogeek"></span>
			<span class="podcast">Salmorejo Geek</span>
			<span class="track">#169 Youtube se pone duro</span>
		</a>
	</span>
</li>
<li>
	<span id="item-120">
		<a href="#" data-media="http://www.ivoox.com/26-cambio-paradigma_mf_23230834_feed_1.mp3" title="#26 Cambio de Paradigma">
			<span class="isplaying"></span>
			<span class="logo reflexpodcast"></span>
			<span class="podcast">reflex podcast</span>
			<span class="track">#26 Cambio de Paradigma</span>
		</a>
	</span>
</li>
<li>
	<span id="item-121">
		<a href="#" data-media="http://www.ivoox.com/ep146-hielo-marte-dinosaurios-ano-jurasico_mf_23230781_feed_1.mp3" title="Ep146: Hielo en Marte; Dinosaurios y Año Jurásico; Hongos que Comen Radiación">
			<span class="isplaying"></span>
			<span class="logo coffeebreakseñalyruido"></span>
			<span class="podcast">Coffee Break: Señal y Ruido</span>
			<span class="track">Ep146: Hielo en Marte; Dinosaurios y Año Jurásico; Hongos que Comen Radiación</span>
		</a>
	</span>
</li>
<li>
	<span id="item-122">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/8056532/Bat2x100_175.m4a" title="#175 – MaCnífica Experiencia">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#175 – MaCnífica Experiencia</span>
		</a>
	</span>
</li>
<li>
	<span id="item-123">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/5a605a639e91b02b750b5ee0.mp3" title="MontaĂąas de dinero">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologăaynegocios"></span>
			<span class="podcast">mixx.io, tecnologĂ­a y negocios</span>
			<span class="track">MontaĂąas de dinero</span>
		</a>
	</span>
</li>
<li>
	<span id="item-124">
		<a href="#" data-media="http://api.spreaker.com/download/episode/13827799/lametric_time.mp3" title="LaMetric Time: Mucho más que un reloj">
			<span class="isplaying"></span>
			<span class="logo deknet"></span>
			<span class="podcast">DekNet</span>
			<span class="track">LaMetric Time: Mucho más que un reloj</span>
		</a>
	</span>
</li>
<li>
	<span id="item-125">
		<a href="#" data-media="http://www.ivoox.com/radiogeek-resumen-diario-dia-17-enero_mf_23214689_feed_1.mp3" title="#Radiogeek - Resumen diario día 17 de enero 2017 #Podcast">
			<span class="isplaying"></span>
			<span class="logo radiogeek"></span>
			<span class="podcast">Radiogeek</span>
			<span class="track">#Radiogeek - Resumen diario día 17 de enero 2017 #Podcast</span>
		</a>
	</span>
</li>
<li>
	<span id="item-126">
		<a href="#" data-media="https://anchor.fm/s/18c0860/podcast/download/101176/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fanchor-data%2Fstationexports%2Fpodcasts%2FPatrones-de-dise-o--0256531c08388.m4a" title="Patrones de diseño.">
			<span class="isplaying"></span>
			<span class="logo tomandouncafé"></span>
			<span class="podcast">Tomando Un Café</span>
			<span class="track">Patrones de diseño.</span>
		</a>
	</span>
</li>
<li>
	<span id="item-127">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2018/01/podcast-96-conceptos-tcp-udp.mp3" title="Podcast #96: Conceptos básicos de conexiones TCP y UDP">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #96: Conceptos básicos de conexiones TCP y UDP</span>
		</a>
	</span>
</li>
<li>
	<span id="item-128">
		<a href="#" data-media="http://api.spreaker.com/download/episode/13825099/recap_2017_noticias_tech.mp3" title="Recap 2017 - Noticias Tech">
			<span class="isplaying"></span>
			<span class="logo codeontherocks"></span>
			<span class="podcast">Code on the rocks</span>
			<span class="track">Recap 2017 - Noticias Tech</span>
		</a>
	</span>
</li>
<li>
	<span id="item-129">
		<a href="#" data-media="http://www.ivoox.com/canal-telegram-chromebooks-rifa-encuesta_mf_23200318_feed_1.mp3" title="Canal de Telegram, Chromebooks, Rifa y Encuesta">
			<span class="isplaying"></span>
			<span class="logo mosqueterowebtecnologialinuxchromebooks"></span>
			<span class="podcast">Mosqueteroweb tecnologia, Linux, Chromebooks</span>
			<span class="track">Canal de Telegram, Chromebooks, Rifa y Encuesta</span>
		</a>
	</span>
</li>
<li>
	<span id="item-130">
		<a href="#" data-media="http://www.ivoox.com/43-especial-ultramoove-vant_mf_23194601_feed_1.mp3" title="#43 Especial UltraMoove de Vant">
			<span class="isplaying"></span>
			<span class="logo podcastlinux"></span>
			<span class="podcast">Podcast Linux</span>
			<span class="track">#43 Especial UltraMoove de Vant</span>
		</a>
	</span>
</li>
<li>
	<span id="item-131">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/5a5f05879e91b02b750b35c0.mp3" title="Mensajero del futuro">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Mensajero del futuro</span>
		</a>
	</span>
</li>
<li>
	<span id="item-132">
		<a href="#" data-media="https://gitlab.com/uGeek/podcasts/raw/master/audios/086-recalbox.m4a" title="086. Recalbox. Consola de Juegos Retro+Kodi">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">086. Recalbox. Consola de Juegos Retro+Kodi</span>
		</a>
	</span>
</li>
<li>
	<span id="item-133">
		<a href="#" data-media="https://deployando.me/podcast-download/196/25-yo-y-la-infraestructura-inmutable.mp3" title="25 – Yo y la infraestructura inmutable">
			<span class="isplaying"></span>
			<span class="logo deployandome"></span>
			<span class="podcast">deployando.me</span>
			<span class="track">25 – Yo y la infraestructura inmutable</span>
		</a>
	</span>
</li>
<li>
	<span id="item-134">
		<a href="#" data-media="http://www.ivoox.com/radiogeek-resumen-diario-dia-16-enero_mf_23188642_feed_1.mp3" title="#Radiogeek - Resumen diario día 16 de enero 2017 #Podcast">
			<span class="isplaying"></span>
			<span class="logo radiogeek"></span>
			<span class="podcast">Radiogeek</span>
			<span class="track">#Radiogeek - Resumen diario día 16 de enero 2017 #Podcast</span>
		</a>
	</span>
</li>
<li>
	<span id="item-135">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2018/01/podcast-95-alta-disponibilidad-en-proxmox.mp3" title="Podcast #95: Alta disponibilidad en Cluster de Proxmox con Ceph">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #95: Alta disponibilidad en Cluster de Proxmox con Ceph</span>
		</a>
	</span>
</li>
<li>
	<span id="item-136">
		<a href="#" data-media="http://compilando.audio/wp-content/uploads/2018/01/podcast20.mp3" title="Podcast 20 – EterTICs GNU/Linux con Javier Obregón y Meltdwon and Spectre con Alejandro López (Slimbook)">
			<span class="isplaying"></span>
			<span class="logo compilandopodcast"></span>
			<span class="podcast">Compilando Podcast</span>
			<span class="track">Podcast 20 – EterTICs GNU/Linux con Javier Obregón y Meltdwon and Spectre con Alejandro López (Slimbook)</span>
		</a>
	</span>
</li>
<li>
	<span id="item-137">
		<a href="#" data-media="http://feedproxy.google.com/~r/Vaciatubandeja/~5/13QOSzROdJU/6622238.mp3" title="16: Descubre tus hábitos básicos y comienza el cambio">
			<span class="isplaying"></span>
			<span class="logo vacíatubandeja"></span>
			<span class="podcast">Vacía tu bandeja</span>
			<span class="track">16: Descubre tus hábitos básicos y comienza el cambio</span>
		</a>
	</span>
</li>
<li>
	<span id="item-138">
		<a href="#" data-media="http://api.spreaker.com/download/episode/13814441/webreactiva_podcast_18.mp3" title="WR 18: ¡Mamá, quiero ser freelance!">
			<span class="isplaying"></span>
			<span class="logo webreactiva"></span>
			<span class="podcast">Web Reactiva</span>
			<span class="track">WR 18: ¡Mamá, quiero ser freelance!</span>
		</a>
	</span>
</li>
<li>
	<span id="item-139">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/5a5d9f609e91b02b750af483.mp3" title="Facebook: los nuevos Illuminati">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Facebook: los nuevos Illuminati</span>
		</a>
	</span>
</li>
<li>
	<span id="item-140">
		<a href="#" data-media="http://www.ivoox.com/radiogeek-resumen-diario-dia-15-enero_mf_23164425_feed_1.mp3" title="#Radiogeek - Resumen diario día 15 de enero 2017 #Podcast">
			<span class="isplaying"></span>
			<span class="logo radiogeek"></span>
			<span class="podcast">Radiogeek</span>
			<span class="track">#Radiogeek - Resumen diario día 15 de enero 2017 #Podcast</span>
		</a>
	</span>
</li>
<li>
	<span id="item-141">
		<a href="#" data-media="http://feedproxy.google.com/~r/Vaciatubandeja/~5/wcKWJJDTkWY/16-Descubre%20tus%20habitos%20basicos%20y%20comienza%20el%20cambio.mp3" title="#16-Descubre tus hábitos básicos y comienza el cambio">
			<span class="isplaying"></span>
			<span class="logo vaciatubandeja"></span>
			<span class="podcast">Vacia Tu Bandeja</span>
			<span class="track">#16-Descubre tus hábitos básicos y comienza el cambio</span>
		</a>
	</span>
</li>
<li>
	<span id="item-142">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2018/01/podcast-94-alta-disponibilidad.mp3" title="Podcast #94: Proyecto alta disponibilidad con Javier Alonso">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #94: Proyecto alta disponibilidad con Javier Alonso</span>
		</a>
	</span>
</li>
<li>
	<span id="item-143">
		<a href="#" data-media="http://www.ivoox.com/36-el-futuro-tecnologia-retos-de_mf_23150374_feed_1.mp3" title="36. El futuro de la tecnología. Retos de la tecnología para los próximos años">
			<span class="isplaying"></span>
			<span class="logo naserospodcast"></span>
			<span class="podcast">NASeros Podcast</span>
			<span class="track">36. El futuro de la tecnología. Retos de la tecnología para los próximos años</span>
		</a>
	</span>
</li>
<li>
	<span id="item-144">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/5a5c6efd9e91b02b750ac06e.mp3" title="Kernel: Asistentes, no mayordomos">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Kernel: Asistentes, no mayordomos</span>
		</a>
	</span>
</li>
<li>
	<span id="item-145">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2018/01/podcast-93-freshrss-y-easyrss.mp3" title="Podcast #93: FreshRSS y EasyRSS">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #93: FreshRSS y EasyRSS</span>
		</a>
	</span>
</li>
<li>
	<span id="item-146">
		<a href="#" data-media="http://api.spreaker.com/download/episode/13794737/ipad_nas_postpc.mp3" title="iPAD + NAS = PostPC">
			<span class="isplaying"></span>
			<span class="logo deknet"></span>
			<span class="podcast">DekNet</span>
			<span class="track">iPAD + NAS = PostPC</span>
		</a>
	</span>
</li>
<li>
	<span id="item-147">
		<a href="#" data-media="https://cuonda.com/api/external.mp3/http://tapewrite.com/REST/feed/@alexbarredo/5a5aaef89e91b02b750a8b09.mp3" title="Bonus: Hablando de Newsletters en KFund">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Bonus: Hablando de Newsletters en KFund</span>
		</a>
	</span>
</li>
<li>
	<span id="item-148">
		<a href="#" data-media="http://podcast.edyo.es/podcast/edyo-35.mp3" title="EDyO 35 - Git y GitHub, to commit or not to commit">
			<span class="isplaying"></span>
			<span class="logo entredevyopspodcast"></span>
			<span class="podcast">EntreDevYOps Podcast</span>
			<span class="track">EDyO 35 - Git y GitHub, to commit or not to commit</span>
		</a>
	</span>
</li>
<li>
	<span id="item-149">
		<a href="#" data-media="http://tracking.feedpress.it/link/14730/8044376/CN_Programa_030b.mp3" title="#CN030 – No hay pipas en Japón">
			<span class="isplaying"></span>
			<span class="logo culturanas"></span>
			<span class="podcast">Cultura NAS</span>
			<span class="track">#CN030 – No hay pipas en Japón</span>
		</a>
	</span>
</li>
<li>
	<span id="item-150">
		<a href="#" data-media="http://api.spreaker.com/download/episode/13760580/control_de_teclados.mp3" title="Control de teclados">
			<span class="isplaying"></span>
			<span class="logo deknet"></span>
			<span class="podcast">DekNet</span>
			<span class="track">Control de teclados</span>
		</a>
	</span>
</li>
<li>
	<span id="item-151">
		<a href="#" data-media="http://www.ivoox.com/25-lo-mal-lo-hacen-algunas-marcas_mf_23116627_feed_1.mp3" title="#25 Lo mal que lo hacen algunas marcas.">
			<span class="isplaying"></span>
			<span class="logo reflexpodcast"></span>
			<span class="podcast">reflex podcast</span>
			<span class="track">#25 Lo mal que lo hacen algunas marcas.</span>
		</a>
	</span>
</li>
<li>
	<span id="item-152">
		<a href="#" data-media="http://www.ivoox.com/meltdown-spectre-cap-83_mf_23109815_feed_1.mp3" title="Meltdown y Spectre - Cap 83">
			<span class="isplaying"></span>
			<span class="logo podcastwintabletinfo"></span>
			<span class="podcast">Podcast WINTABLET.INFO</span>
			<span class="track">Meltdown y Spectre - Cap 83</span>
		</a>
	</span>
</li>
<li>
	<span id="item-153">
		<a href="#" data-media="http://traffic.libsyn.com/cesargarciasaez/LHM140.mp3" title="LHM140 – Robótica educativa de competición con Nerea de la Riva Iriepa">
			<span class="isplaying"></span>
			<span class="logo lahoramaker"></span>
			<span class="podcast">La Hora Maker</span>
			<span class="track">LHM140 – Robótica educativa de competición con Nerea de la Riva Iriepa</span>
		</a>
	</span>
</li>
<li>
	<span id="item-154">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/5a585a4e9e91b02b750a548a.mp3" title="Facebook cambia: más amigos, menos noticias">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Facebook cambia: más amigos, menos noticias</span>
		</a>
	</span>
</li>
<li>
	<span id="item-155">
		<a href="#" data-media="http://www.ivoox.com/radiogeek-el-proximo-google-pixel-no-tendria_mf_23105199_feed_1.mp3" title="#Radiogeek - El próximo Google Pixel no tendría parlantes">
			<span class="isplaying"></span>
			<span class="logo radiogeek"></span>
			<span class="podcast">Radiogeek</span>
			<span class="track">#Radiogeek - El próximo Google Pixel no tendría parlantes</span>
		</a>
	</span>
</li>
<li>
	<span id="item-156">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2018/01/podcast-92-preparar-servidor-docker-ce.mp3" title="Podcast #92: Preparar servidor público para Docker-ce">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #92: Preparar servidor público para Docker-ce</span>
		</a>
	</span>
</li>
<li>
	<span id="item-157">
		<a href="#" data-media="http://www.ivoox.com/ep145-star-wars-sin-spoilers-incertidumbres-fisica_mf_23101397_feed_1.mp3" title="Ep145: Star Wars sin Spoilers; Incertidumbres en Física; Temperatura y Calor; #CienciaEnElParlamento">
			<span class="isplaying"></span>
			<span class="logo coffeebreakseñalyruido"></span>
			<span class="podcast">Coffee Break: Señal y Ruido</span>
			<span class="track">Ep145: Star Wars sin Spoilers; Incertidumbres en Física; Temperatura y Calor; #CienciaEnElParlamento</span>
		</a>
	</span>
</li>
<li>
	<span id="item-158">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/8022504/Bat2x100_174.m4a" title="#174 – IPhone nuevo, vida nueva">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#174 – IPhone nuevo, vida nueva</span>
		</a>
	</span>
</li>
<li>
	<span id="item-159">
		<a href="#" data-media="https://anchor.fm/s/18c0860/podcast/download/94860/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fanchor-data%2Fstationexports%2Fpodcasts%2F-C-mo-aprender-a-programar--e5eb7d8f15b01.m4a" title="¿Cómo aprender a programar?">
			<span class="isplaying"></span>
			<span class="logo tomandouncafé"></span>
			<span class="podcast">Tomando Un Café</span>
			<span class="track">¿Cómo aprender a programar?</span>
		</a>
	</span>
</li>
<li>
	<span id="item-160">
		<a href="#" data-media="https://www.ivoox.com/anecdotas-giordanicas-4-las-locuras-armar-un_mf_23088644_feed_1.mp3" title="Anécdotas Giordánicas (4): ¿Las locuras de armar un curso completo de Swift 4?">
			<span class="isplaying"></span>
			<span class="logo codetime"></span>
			<span class="podcast">Code Time</span>
			<span class="track">Anécdotas Giordánicas (4): ¿Las locuras de armar un curso completo de Swift 4?</span>
		</a>
	</span>
</li>
<li>
	<span id="item-161">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/5a570ead9e91b02b750a2cbe.mp3" title="Apple se vuelve a dejar las llaves puestas por fuera">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Apple se vuelve a dejar las llaves puestas por fuera</span>
		</a>
	</span>
</li>
<li>
	<span id="item-162">
		<a href="#" data-media="http://www.ivoox.com/radiogeek-todo-sobre-ces2018-primera-parte_mf_23087253_feed_1.mp3" title="#Radiogeek - Todo sobre el #CES2018 Primera parte">
			<span class="isplaying"></span>
			<span class="logo radiogeek"></span>
			<span class="podcast">Radiogeek</span>
			<span class="track">#Radiogeek - Todo sobre el #CES2018 Primera parte</span>
		</a>
	</span>
</li>
<li>
	<span id="item-163">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2018/01/podcast-91-bucar-una-maquina.mp3" title="Podcast #91: Buscar una máquina en la red">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #91: Buscar una máquina en la red</span>
		</a>
	</span>
</li>
<li>
	<span id="item-164">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/5a55b2ef9e91b02b750a0011.mp3" title="El control parental eres tú">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">El control parental eres tú</span>
		</a>
	</span>
</li>
<li>
	<span id="item-165">
		<a href="#" data-media="http://api.spreaker.com/download/episode/13760420/videovigilancia_menos_es_m_s.mp3" title="Videovigilancia: Menos es más">
			<span class="isplaying"></span>
			<span class="logo deknet"></span>
			<span class="podcast">DekNet</span>
			<span class="track">Videovigilancia: Menos es más</span>
		</a>
	</span>
</li>
<li>
	<span id="item-166">
		<a href="#" data-media="https://deployando.me/podcast-download/194/24-infraestructura-inmutable.mp3" title="24 – Infraestructura inmutable">
			<span class="isplaying"></span>
			<span class="logo deployandome"></span>
			<span class="podcast">deployando.me</span>
			<span class="track">24 – Infraestructura inmutable</span>
		</a>
	</span>
</li>
<li>
	<span id="item-167">
		<a href="#" data-media="https://gitlab.com/podcastlinux/podcastlinux.gitlab.io/raw/master/Linux-Express/32linuxexpress.mp3" title="#32 Linux Express">
			<span class="isplaying"></span>
			<span class="logo linuxexpressdepodcastlinux"></span>
			<span class="podcast">Linux Express, de Podcast Linux.</span>
			<span class="track">#32 Linux Express</span>
		</a>
	</span>
</li>
<li>
	<span id="item-168">
		<a href="#" data-media="https://archive.org/download/42ArranqueUsbRaspberrypi3/42-arranque-usb-raspberrypi3.mp3" title="#42 Arrancar Raspberry Pi 3 desde memoria USB - Elección de disco duro">
			<span class="isplaying"></span>
			<span class="logo educandogeek"></span>
			<span class="podcast">eDucando Geek</span>
			<span class="track">#42 Arrancar Raspberry Pi 3 desde memoria USB - Elección de disco duro</span>
		</a>
	</span>
</li>
<li>
	<span id="item-169">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2018/01/podcast-90-netinstall-en-mikrotik.mp3" title="Podcast #90: Netinstall en Mikrotik">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #90: Netinstall en Mikrotik</span>
		</a>
	</span>
</li>
<li>
	<span id="item-170">
		<a href="#" data-media="https://cuonda.com/api/external.mp3/http://tapewrite.com/REST/feed/@alexbarredo/5a54b3a49e91b02b7509d6a6.mp3" title="Traiciones, rendiciones y presentaciones">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Traiciones, rendiciones y presentaciones</span>
		</a>
	</span>
</li>
<li>
	<span id="item-171">
		<a href="#" data-media="http://api.spreaker.com/download/episode/13749618/webreactiva_podcast_17.mp3" title="WR 17: Programar en Kotlin con Borja Quevedo">
			<span class="isplaying"></span>
			<span class="logo webreactiva"></span>
			<span class="podcast">Web Reactiva</span>
			<span class="track">WR 17: Programar en Kotlin con Borja Quevedo</span>
		</a>
	</span>
</li>
<li>
	<span id="item-172">
		<a href="#" data-media="https://www.ivoox.com/script-time-el-error-borrar-codigo_mf_23037181_feed_1.mp3" title="Script Time: El error de borrar el código &quot;inútil&quot;">
			<span class="isplaying"></span>
			<span class="logo codetime"></span>
			<span class="podcast">Code Time</span>
			<span class="track">Script Time: El error de borrar el código &quot;inútil&quot;</span>
		</a>
	</span>
</li>
<li>
	<span id="item-173">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2018/01/podcast-89-streaming-gratis.mp3" title="Podcast #89: Streaming de audio gratis con icecast">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #89: Streaming de audio gratis con icecast</span>
		</a>
	</span>
</li>
<li>
	<span id="item-174">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/5a53153c9e91b02b7509a0a6.mp3" title="¿Quién quiere ir a Las Vegas?">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">¿Quién quiere ir a Las Vegas?</span>
		</a>
	</span>
</li>
<li>
	<span id="item-175">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2018/01/podcast-88-ceph-en-proxmox.mp3" title="Podcast #88: Ceph en Proxmox">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #88: Ceph en Proxmox</span>
		</a>
	</span>
</li>
<li>
	<span id="item-176">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/5a5259cc9e91b02b75097892.mp3" title="Kernel: Google no sabe hacer amigos, con Axel Marazzi @amarazzi">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Kernel: Google no sabe hacer amigos, con Axel Marazzi @amarazzi</span>
		</a>
	</span>
</li>
<li>
	<span id="item-177">
		<a href="#" data-media="http://www.ivoox.com/026-ensenando-gtd-jose-miguel-bolivar_mf_23011301_feed_1.mp3" title="026 - Enseñando GTD con José Miguel Bolívar">
			<span class="isplaying"></span>
			<span class="logo aprendiendogtdpodcastproductividad"></span>
			<span class="podcast">Aprendiendo GTD podcast productividad</span>
			<span class="track">026 - Enseñando GTD con José Miguel Bolívar</span>
		</a>
	</span>
</li>
<li>
	<span id="item-178">
		<a href="#" data-media="http://api.spreaker.com/download/episode/13740156/offtopic_blade_runner_2049.mp3" title="OFFTOPIC: Blade Runner 2049">
			<span class="isplaying"></span>
			<span class="logo deknet"></span>
			<span class="podcast">DekNet</span>
			<span class="track">OFFTOPIC: Blade Runner 2049</span>
		</a>
	</span>
</li>
<li>
	<span id="item-179">
		<a href="#" data-media="http://api.spreaker.com/download/episode/13734341/meltdown_attack_teoria_y_practica.mp3" title="Meltdown Attack: Teoria y practica">
			<span class="isplaying"></span>
			<span class="logo deknet"></span>
			<span class="podcast">DekNet</span>
			<span class="track">Meltdown Attack: Teoria y practica</span>
		</a>
	</span>
</li>
<li>
	<span id="item-180">
		<a href="#" data-media="http://www.ivoox.com/35-redes-wifi-mesh-bajo-coste-aimesh_mf_22997059_feed_1.mp3" title="35. Redes WIFI mesh de bajo coste. AiMesh de Asus">
			<span class="isplaying"></span>
			<span class="logo naserospodcast"></span>
			<span class="podcast">NASeros Podcast</span>
			<span class="track">35. Redes WIFI mesh de bajo coste. AiMesh de Asus</span>
		</a>
	</span>
</li>
<li>
	<span id="item-181">
		<a href="#" data-media="http://ar.ivoox.com/es/neositelinux-podcast-2018-1-el-intel-gate_mf_22998056_feed_1.mp3" title="NeoSiteLinux Podcast 2018 - #1 - El Intel-Gate">
			<span class="isplaying"></span>
			<span class="logo neositelinuxpodcast"></span>
			<span class="podcast">NeoSiteLinux Podcast</span>
			<span class="track">NeoSiteLinux Podcast 2018 - #1 - El Intel-Gate</span>
		</a>
	</span>
</li>
<li>
	<span id="item-182">
		<a href="#" data-media="https://anchor.fm/s/18c0860/podcast/download/89483/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fanchor-data%2Fstationexports%2Fpodcasts%2FTypora-7150195fadbf4.m4a" title="Typora">
			<span class="isplaying"></span>
			<span class="logo tomandouncafé"></span>
			<span class="podcast">Tomando Un Café</span>
			<span class="track">Typora</span>
		</a>
	</span>
</li>
<li>
	<span id="item-183">
		<a href="#" data-media="http://ia800808.us.archive.org/9/items/NolegaltechRadio/006Nolegaltechradio-seguridadInformtica.mp3" title="#006-Seguridad informática">
			<span class="isplaying"></span>
			<span class="logo nolegaltechradio"></span>
			<span class="podcast">NOlegaltech Radio</span>
			<span class="track">#006-Seguridad informática</span>
		</a>
	</span>
</li>
<li>
	<span id="item-184">
		<a href="#" data-media="http://www.ivoox.com/ep144-premios-senal-ruido-2017-estrella-de_mf_22977866_feed_1.mp3" title="Ep144: Premios Señal y Ruido 2017; Estrella de Tabby; Vulnerabilidad Informática">
			<span class="isplaying"></span>
			<span class="logo coffeebreakseñalyruido"></span>
			<span class="podcast">Coffee Break: Señal y Ruido</span>
			<span class="track">Ep144: Premios Señal y Ruido 2017; Estrella de Tabby; Vulnerabilidad Informática</span>
		</a>
	</span>
</li>
<li>
	<span id="item-185">
		<a href="#" data-media="http://api.spreaker.com/download/episode/13723753/meldown.mp3" title="Meltdown Attack: Que listo es Calisto">
			<span class="isplaying"></span>
			<span class="logo deknet"></span>
			<span class="podcast">DekNet</span>
			<span class="track">Meltdown Attack: Que listo es Calisto</span>
		</a>
	</span>
</li>
<li>
	<span id="item-186">
		<a href="#" data-media="http://www.ivoox.com/episodio-17-seguridad-web_mf_22972571_feed_1.mp3" title="Episodio 17 - Seguridad Web">
			<span class="isplaying"></span>
			<span class="logo programaresunamierda"></span>
			<span class="podcast">Programar es una mierda</span>
			<span class="track">Episodio 17 - Seguridad Web</span>
		</a>
	</span>
</li>
<li>
	<span id="item-187">
		<a href="#" data-media="https://www.ivoox.com/episodio-17-seguridad-web_mf_22972571_feed_1.mp3" title="Episodio 17 - Seguridad Web">
			<span class="isplaying"></span>
			<span class="logo programaresunamierda"></span>
			<span class="podcast">Programar es una mierda</span>
			<span class="track">Episodio 17 - Seguridad Web</span>
		</a>
	</span>
</li>
<li>
	<span id="item-188">
		<a href="#" data-media="http://www.ivoox.com/sesion-oyentes-1-estructura-buenas-practicas_mf_22971998_feed_1.mp3" title="Sesión oyentes #1 - ¿Estructura y buenas prácticas con frameworks?">
			<span class="isplaying"></span>
			<span class="logo programaresunamierda"></span>
			<span class="podcast">Programar es una mierda</span>
			<span class="track">Sesión oyentes #1 - ¿Estructura y buenas prácticas con frameworks?</span>
		</a>
	</span>
</li>
<li>
	<span id="item-189">
		<a href="#" data-media="https://www.ivoox.com/sesion-oyentes-1-estructura-buenas-practicas_mf_22971998_feed_1.mp3" title="Sesión oyentes #1 - ¿Estructura y buenas prácticas con frameworks?">
			<span class="isplaying"></span>
			<span class="logo programaresunamierda"></span>
			<span class="podcast">Programar es una mierda</span>
			<span class="track">Sesión oyentes #1 - ¿Estructura y buenas prácticas con frameworks?</span>
		</a>
	</span>
</li>
<li>
	<span id="item-190">
		<a href="#" data-media="https://www.ivoox.com/anecdotas-giordanicas-3-como-creamos-server-distribuido_mf_22967229_feed_1.mp3" title="Anécdotas Giordánicas (3): ¿Cómo creamos un server distribuido?">
			<span class="isplaying"></span>
			<span class="logo codetime"></span>
			<span class="podcast">Code Time</span>
			<span class="track">Anécdotas Giordánicas (3): ¿Cómo creamos un server distribuido?</span>
		</a>
	</span>
</li>
<li>
	<span id="item-191">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/7939203/Bat2x100_173.m4a" title="#173 – Ya vienen los Reyes !">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#173 – Ya vienen los Reyes !</span>
		</a>
	</span>
</li>
<li>
	<span id="item-192">
		<a href="#" data-media="http://www.ivoox.com/42-linux-connexion-alvaro-nova_mf_22945301_feed_1.mp3" title="#42 Linux Connexion con Alvaro Nova">
			<span class="isplaying"></span>
			<span class="logo podcastlinux"></span>
			<span class="podcast">Podcast Linux</span>
			<span class="track">#42 Linux Connexion con Alvaro Nova</span>
		</a>
	</span>
</li>
<li>
	<span id="item-193">
		<a href="#" data-media="http://ia600808.us.archive.org/9/items/NolegaltechRadio/005Nolegaltechradio-usoDeSoftwareSinLicencia.mp3" title="#005-Uso de software sin licencia">
			<span class="isplaying"></span>
			<span class="logo nolegaltechradio"></span>
			<span class="podcast">NOlegaltech Radio</span>
			<span class="track">#005-Uso de software sin licencia</span>
		</a>
	</span>
</li>
<li>
	<span id="item-194">
		<a href="#" data-media="http://www.ivoox.com/168-movistar-wordpress-yo-mismo-laura_mf_22937474_feed_1.mp3" title="#168 Movistar, WordPress, yo mismo y Laura">
			<span class="isplaying"></span>
			<span class="logo salmorejogeek"></span>
			<span class="podcast">Salmorejo Geek</span>
			<span class="track">#168 Movistar, WordPress, yo mismo y Laura</span>
		</a>
	</span>
</li>
<li>
	<span id="item-195">
		<a href="#" data-media="http://api.spreaker.com/download/episode/13710136/webreactiva_podcast_16.mp3" title="WR 16: Lo que me gustaría aprender en 2018">
			<span class="isplaying"></span>
			<span class="logo webreactiva"></span>
			<span class="podcast">Web Reactiva</span>
			<span class="track">WR 16: Lo que me gustaría aprender en 2018</span>
		</a>
	</span>
</li>
<li>
	<span id="item-196">
		<a href="#" data-media="http://api.spreaker.com/download/episode/13708507/cap36_macbook_pro_y_linux_es_un_problema.mp3" title="cap36 - MacBook Pro y linux es un problema">
			<span class="isplaying"></span>
			<span class="logo podcastdmanuelalonso"></span>
			<span class="podcast">Podcast dmanuelalonso</span>
			<span class="track">cap36 - MacBook Pro y linux es un problema</span>
		</a>
	</span>
</li>
<li>
	<span id="item-197">
		<a href="#" data-media="http://tracking.feedpress.it/link/15407/7921440/BCS020-Hacks-2017.mp3" title="BCS020 – Hacks 2017">
			<span class="isplaying"></span>
			<span class="logo bitácoradeciberseguridad"></span>
			<span class="podcast">Bitácora de Ciberseguridad</span>
			<span class="track">BCS020 – Hacks 2017</span>
		</a>
	</span>
</li>
<li>
	<span id="item-198">
		<a href="#" data-media="http://www.ivoox.com/feliz-ano-nuevo-les-deseamos-desde-infosertec_mf_22912155_feed_1.mp3" title="Feliz Año nuevo! les deseamos desde Infosertec!!!">
			<span class="isplaying"></span>
			<span class="logo radiogeek"></span>
			<span class="podcast">Radiogeek</span>
			<span class="track">Feliz Año nuevo! les deseamos desde Infosertec!!!</span>
		</a>
	</span>
</li>
<li>
	<span id="item-199">
		<a href="#" data-media="https://www.ivoox.com/anecdotas-giordanicas-2-las-modificaciones-mi-equipo_mf_22911298_feed_1.mp3" title="Anécdotas Giordánicas (2): Las modificaciones de mi equipo de trabajo">
			<span class="isplaying"></span>
			<span class="logo codetime"></span>
			<span class="podcast">Code Time</span>
			<span class="track">Anécdotas Giordánicas (2): Las modificaciones de mi equipo de trabajo</span>
		</a>
	</span>
</li>
<li>
	<span id="item-200">
		<a href="#" data-media="http://traffic.libsyn.com/cesargarciasaez/LHM139.mp3" title="LHM139 – 7 tendencias maker para 2018">
			<span class="isplaying"></span>
			<span class="logo lahoramaker"></span>
			<span class="podcast">La Hora Maker</span>
			<span class="track">LHM139 – 7 tendencias maker para 2018</span>
		</a>
	</span>
</li>
<li>
	<span id="item-201">
		<a href="#" data-media="http://api.spreaker.com/download/episode/13690306/deknet_dekkar_feliz_2018.mp3" title="Feliz 2018 desde la red DekNet">
			<span class="isplaying"></span>
			<span class="logo deknet"></span>
			<span class="podcast">DekNet</span>
			<span class="track">Feliz 2018 desde la red DekNet</span>
		</a>
	</span>
</li>
<li>
	<span id="item-202">
		<a href="#" data-media="https://archive.org/download/41CierreDel2017/41-cierre-del-2017.mp3" title="#41 Cerrando el año 2017">
			<span class="isplaying"></span>
			<span class="logo educandogeek"></span>
			<span class="podcast">eDucando Geek</span>
			<span class="track">#41 Cerrando el año 2017</span>
		</a>
	</span>
</li>
<li>
	<span id="item-203">
		<a href="#" data-media="http://www.ivoox.com/mi-2017-resumen-del-ano_mf_22904192_feed_1.mp3" title="Mi 2017 . Resumen del año">
			<span class="isplaying"></span>
			<span class="logo mosqueterowebtecnologialinuxchromebooks"></span>
			<span class="podcast">Mosqueteroweb tecnologia, Linux, Chromebooks</span>
			<span class="track">Mi 2017 . Resumen del año</span>
		</a>
	</span>
</li>
<li>
	<span id="item-204">
		<a href="#" data-media="https://www.ivoox.com/34-evolucion-naseros-3-master-class_mf_22902555_feed_1.mp3" title="34. Evolución de NASeros y 3ª Master Class de NAS">
			<span class="isplaying"></span>
			<span class="logo naserospodcast"></span>
			<span class="podcast">NASeros Podcast</span>
			<span class="track">34. Evolución de NASeros y 3ª Master Class de NAS</span>
		</a>
	</span>
</li>
<li>
	<span id="item-205">
		<a href="#" data-media="http://www.ivoox.com/retroactivo-podcast-especial-misterio_mf_22899119_feed_1.mp3" title="RetroActivo Podcast: Especial Misterio">
			<span class="isplaying"></span>
			<span class="logo retroactivopodcast"></span>
			<span class="podcast">RetroActivo Podcast</span>
			<span class="track">RetroActivo Podcast: Especial Misterio</span>
		</a>
	</span>
</li>
<li>
	<span id="item-206">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/5a46455f9e91b02b75090fa9.mp3" title="Kernel: Cómo convertirse en un pro de los esports, con @Alvaro845">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Kernel: Cómo convertirse en un pro de los esports, con @Alvaro845</span>
		</a>
	</span>
</li>
<li>
	<span id="item-207">
		<a href="#" data-media="http://www.ivoox.com/radiogeek-ultimo-podcast-del-ano_mf_22884246_feed_1.mp3" title="#Radiogeek - Ultimo #Podcast del año!">
			<span class="isplaying"></span>
			<span class="logo radiogeek"></span>
			<span class="podcast">Radiogeek</span>
			<span class="track">#Radiogeek - Ultimo #Podcast del año!</span>
		</a>
	</span>
</li>
<li>
	<span id="item-208">
		<a href="#" data-media="https://ar.ivoox.com/es/ep143-estrella-belen-materia-oscura-polemica_mf_22880075_feed_1.mp3" title="Ep143: Estrella de Belén; Materia Oscura y Polémica 'No LIGO MACHO'; Astronomía Amateur; El Puente de Magallanes">
			<span class="isplaying"></span>
			<span class="logo coffeebreakseñalyruido"></span>
			<span class="podcast">Coffee Break: Señal y Ruido</span>
			<span class="track">Ep143: Estrella de Belén; Materia Oscura y Polémica 'No LIGO MACHO'; Astronomía Amateur; El Puente de Magallanes</span>
		</a>
	</span>
</li>
<li>
	<span id="item-209">
		<a href="#" data-media="http://api.spreaker.com/download/episode/13679752/offtopic_bobos_tecnologicos.mp3" title="OFFTOPIC: Bobos tecnologicos">
			<span class="isplaying"></span>
			<span class="logo deknet"></span>
			<span class="podcast">DekNet</span>
			<span class="track">OFFTOPIC: Bobos tecnologicos</span>
		</a>
	</span>
</li>
<li>
	<span id="item-210">
		<a href="#" data-media="http://www.ivoox.com/radiogeek-samsung-mobile-care-disponible-espana_mf_22869798_feed_1.mp3" title="#Radiogeek - Samsung Mobile Care disponible en España">
			<span class="isplaying"></span>
			<span class="logo radiogeek"></span>
			<span class="podcast">Radiogeek</span>
			<span class="track">#Radiogeek - Samsung Mobile Care disponible en España</span>
		</a>
	</span>
</li>
<li>
	<span id="item-211">
		<a href="#" data-media="http://www.ivoox.com/episodio-especial-1_mf_22861909_feed_1.mp3" title="Episodio especial #1">
			<span class="isplaying"></span>
			<span class="logo programaresunamierda"></span>
			<span class="podcast">Programar es una mierda</span>
			<span class="track">Episodio especial #1</span>
		</a>
	</span>
</li>
<li>
	<span id="item-212">
		<a href="#" data-media="https://www.ivoox.com/episodio-especial-1_mf_22861909_feed_1.mp3" title="Episodio especial #1">
			<span class="isplaying"></span>
			<span class="logo programaresunamierda"></span>
			<span class="podcast">Programar es una mierda</span>
			<span class="track">Episodio especial #1</span>
		</a>
	</span>
</li>
<li>
	<span id="item-213">
		<a href="#" data-media="http://www.ivoox.com/radiogeek-que-dispositivos-quedaran-sin-whatsapp-en_mf_22851527_feed_1.mp3" title="#Radiogeek - Que dispositivos quedaran sin WhatsApp en enero de 2018">
			<span class="isplaying"></span>
			<span class="logo radiogeek"></span>
			<span class="podcast">Radiogeek</span>
			<span class="track">#Radiogeek - Que dispositivos quedaran sin WhatsApp en enero de 2018</span>
		</a>
	</span>
</li>
<li>
	<span id="item-214">
		<a href="#" data-media="https://gitlab.com/podcastlinux/podcastlinux.gitlab.io/raw/master/Linux-Express/31linuxexpress.mp3" title="#31 Linux Express">
			<span class="isplaying"></span>
			<span class="logo linuxexpressdepodcastlinux"></span>
			<span class="podcast">Linux Express, de Podcast Linux.</span>
			<span class="track">#31 Linux Express</span>
		</a>
	</span>
</li>
<li>
	<span id="item-215">
		<a href="#" data-media="http://feedproxy.google.com/~r/WecodesignPodcast/~5/_uCDPDZw7Rg/WeCodeSign%202x14%20-%20Polymer.mp3" title="2x14 - Polymer">
			<span class="isplaying"></span>
			<span class="logo wecodesignpodcast"></span>
			<span class="podcast">WeCodeSign Podcast</span>
			<span class="track">2x14 - Polymer</span>
		</a>
	</span>
</li>
<li>
	<span id="item-216">
		<a href="#" data-media="http://feedproxy.google.com/~r/Vaciatubandeja/~5/De-gslK6bsk/6622239.mp3" title="15: Fin de año | Revisa tus proyectos y objetivos">
			<span class="isplaying"></span>
			<span class="logo vacíatubandeja"></span>
			<span class="podcast">Vacía tu bandeja</span>
			<span class="track">15: Fin de año | Revisa tus proyectos y objetivos</span>
		</a>
	</span>
</li>
<li>
	<span id="item-217">
		<a href="#" data-media="http://api.spreaker.com/download/episode/13658913/webreactiva_podcast_15.mp3" title="WR 15: El aguinaldo navideño">
			<span class="isplaying"></span>
			<span class="logo webreactiva"></span>
			<span class="podcast">Web Reactiva</span>
			<span class="track">WR 15: El aguinaldo navideño</span>
		</a>
	</span>
</li>
<li>
	<span id="item-218">
		<a href="#" data-media="http://www.ivoox.com/radiogeek-especial-peliculas-series-diciembre-2017_mf_22835179_feed_1.mp3" title="#Radiogeek - Especial películas y series Diciembre 2017">
			<span class="isplaying"></span>
			<span class="logo radiogeek"></span>
			<span class="podcast">Radiogeek</span>
			<span class="track">#Radiogeek - Especial películas y series Diciembre 2017</span>
		</a>
	</span>
</li>
<li>
	<span id="item-219">
		<a href="#" data-media="http://feedproxy.google.com/~r/Vaciatubandeja/~5/lqYS17qvjaY/15-Fin%20de%20a%C3%B1o-Revisa%20tus%20proyectos%20y%20objetivos.mp3" title="#15-Fin de año: Revisa tus proyectos y objetivos">
			<span class="isplaying"></span>
			<span class="logo vaciatubandeja"></span>
			<span class="podcast">Vacia Tu Bandeja</span>
			<span class="track">#15-Fin de año: Revisa tus proyectos y objetivos</span>
		</a>
	</span>
</li>
<li>
	<span id="item-220">
		<a href="#" data-media="http://www.ivoox.com/24-podcast-navidad-donde-os-digo-lo_mf_22830890_feed_1.mp3" title="#24 Podcast de navidad donde os digo lo mas importante que podeis comprar.">
			<span class="isplaying"></span>
			<span class="logo reflexpodcast"></span>
			<span class="podcast">reflex podcast</span>
			<span class="track">#24 Podcast de navidad donde os digo lo mas importante que podeis comprar.</span>
		</a>
	</span>
</li>
<li>
	<span id="item-221">
		<a href="#" data-media="http://www.ivoox.com/anecdotas-giordanicas-1-las-locuras-armar-el_mf_22826721_feed_1.mp3" title="Anécdotas Giordánicas (1): ¿Las locuras de armar el curso de desarrollo de aplicaciones para iOS 11?">
			<span class="isplaying"></span>
			<span class="logo codetime"></span>
			<span class="podcast">Code Time</span>
			<span class="track">Anécdotas Giordánicas (1): ¿Las locuras de armar el curso de desarrollo de aplicaciones para iOS 11?</span>
		</a>
	</span>
</li>
<li>
	<span id="item-222">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/Ep115.mp3" title="Física espacial, anillos de radiación y auroras boreales [Ep.115]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Física espacial, anillos de radiación y auroras boreales [Ep.115]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-223">
		<a href="#" data-media="http://www.ivoox.com/feliz-navidad-les-deseamos-desde-infosertec_mf_22824853_feed_1.mp3" title="Feliz Navidad! les deseamos desde Infosertec!!!">
			<span class="isplaying"></span>
			<span class="logo radiogeek"></span>
			<span class="podcast">Radiogeek</span>
			<span class="track">Feliz Navidad! les deseamos desde Infosertec!!!</span>
		</a>
	</span>
</li>
<li>
	<span id="item-224">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/7832485/Bat2x100_172.m4a" title="#172 – Feliz Navidad !! 🎄">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#172 – Feliz Navidad !! 🎄</span>
		</a>
	</span>
</li>
<li>
	<span id="item-225">
		<a href="#" data-media="https://ar.ivoox.com/es/bonus-audio-navidad-historia-astronomia-una_mf_22820853_feed_1.mp3" title="Bonus Audio. Navidad: Historia y Astronomía de una Tradición Ancestral">
			<span class="isplaying"></span>
			<span class="logo coffeebreakseñalyruido"></span>
			<span class="podcast">Coffee Break: Señal y Ruido</span>
			<span class="track">Bonus Audio. Navidad: Historia y Astronomía de una Tradición Ancestral</span>
		</a>
	</span>
</li>
<li>
	<span id="item-226">
		<a href="#" data-media="http://api.spreaker.com/download/episode/13660843/feliz_navidad_20172.mp3" title="Feliz Navidad 2017">
			<span class="isplaying"></span>
			<span class="logo deknet"></span>
			<span class="podcast">DekNet</span>
			<span class="track">Feliz Navidad 2017</span>
		</a>
	</span>
</li>
<li>
	<span id="item-227">
		<a href="#" data-media="https://anchor.fm/s/18c0860/podcast/download/79704/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fanchor-data%2Fstationexports%2Fpodcasts%2FFormaci-n-Inform-tica-7bb270f4b21fd.m4a" title="Formación Informática">
			<span class="isplaying"></span>
			<span class="logo tomandouncafé"></span>
			<span class="podcast">Tomando Un Café</span>
			<span class="track">Formación Informática</span>
		</a>
	</span>
</li>
<li>
	<span id="item-228">
		<a href="#" data-media="http://traffic.libsyn.com/cesargarciasaez/LHM138.mp3" title="LHM138 – Preguntas y Proyectos con David Cuartielles (Diciembre 2017)">
			<span class="isplaying"></span>
			<span class="logo lahoramaker"></span>
			<span class="podcast">La Hora Maker</span>
			<span class="track">LHM138 – Preguntas y Proyectos con David Cuartielles (Diciembre 2017)</span>
		</a>
	</span>
</li>
<li>
	<span id="item-229">
		<a href="#" data-media="http://compilando.audio/wp-content/uploads/2017/12/podcast19.mp3" title="Podcast 19 – Ciberseguridad con Yaiza Rubio y Ubucon 2018 en Gijón">
			<span class="isplaying"></span>
			<span class="logo compilandopodcast"></span>
			<span class="podcast">Compilando Podcast</span>
			<span class="track">Podcast 19 – Ciberseguridad con Yaiza Rubio y Ubucon 2018 en Gijón</span>
		</a>
	</span>
</li>
<li>
	<span id="item-230">
		<a href="#" data-media="http://www.ivoox.com/linux-mint-18-3-como-actualizar_mf_22801021_feed_1.mp3" title="Linux Mint 18.3 ¿cómo actualizar?">
			<span class="isplaying"></span>
			<span class="logo mosqueterowebtecnologialinuxchromebooks"></span>
			<span class="podcast">Mosqueteroweb tecnologia, Linux, Chromebooks</span>
			<span class="track">Linux Mint 18.3 ¿cómo actualizar?</span>
		</a>
	</span>
</li>
<li>
	<span id="item-231">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/5a3cad079e91b02b75088d30.mp3" title="Fin de la â€˜supervisiÃ³n adultaâ€™ en Google">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Fin de la â€˜supervisiÃ³n adultaâ€™ en Google</span>
		</a>
	</span>
</li>
<li>
	<span id="item-232">
		<a href="#" data-media="http://www.ivoox.com/radiogeek-el-gobierno-argentina-aprobo-la_mf_22791929_feed_1.mp3" title="#Radiogeek - El Gobierno de Argentina aprobó la fusión de Telecom-Cablevision">
			<span class="isplaying"></span>
			<span class="logo radiogeek"></span>
			<span class="podcast">Radiogeek</span>
			<span class="track">#Radiogeek - El Gobierno de Argentina aprobó la fusión de Telecom-Cablevision</span>
		</a>
	</span>
</li>
<li>
	<span id="item-233">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/12/podcast-87-private-vlans.mp3" title="Podcast #87: Private Vlans">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #87: Private Vlans</span>
		</a>
	</span>
</li>
<li>
	<span id="item-234">
		<a href="#" data-media="http://www.ivoox.com/167-flasheando-android-one-xiaomi-mi_mf_22788031_feed_1.mp3" title="#167 Flasheando Android ONE en un Xiaomi Mi 5X vía TWRP">
			<span class="isplaying"></span>
			<span class="logo salmorejogeek"></span>
			<span class="podcast">Salmorejo Geek</span>
			<span class="track">#167 Flasheando Android ONE en un Xiaomi Mi 5X vía TWRP</span>
		</a>
	</span>
</li>
<li>
	<span id="item-235">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/5a3bf0e19e91b02b75085fd1.mp3" title="Las máquinas de pensar, con ALMO (@davilagrau)">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Las máquinas de pensar, con ALMO (@davilagrau)</span>
		</a>
	</span>
</li>
<li>
	<span id="item-236">
		<a href="#" data-media="http://www.ivoox.com/fire-tv-apps-amazon-prime-video_mf_22782774_feed_1.mp3" title="Fire TV, apps y Amazon Prime Vídeo">
			<span class="isplaying"></span>
			<span class="logo mosqueterowebtecnologialinuxchromebooks"></span>
			<span class="podcast">Mosqueteroweb tecnologia, Linux, Chromebooks</span>
			<span class="track">Fire TV, apps y Amazon Prime Vídeo</span>
		</a>
	</span>
</li>
<li>
	<span id="item-237">
		<a href="#" data-media="https://ar.ivoox.com/es/ep142-excitonium-magnetismo-agujeros-negros-lucy-patroclus_mf_22779651_feed_1.mp3" title="Ep142: Excitonium; Magnetismo en Agujeros Negros; Lucy, Patroclus y Meonetius; El Quásar más Lejano">
			<span class="isplaying"></span>
			<span class="logo coffeebreakseñalyruido"></span>
			<span class="podcast">Coffee Break: Señal y Ruido</span>
			<span class="track">Ep142: Excitonium; Magnetismo en Agujeros Negros; Lucy, Patroclus y Meonetius; El Quásar más Lejano</span>
		</a>
	</span>
</li>
<li>
	<span id="item-238">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/5a3b86b29e91b02b75084738.mp3" title="Apple unificará desarrollo de apps para iOS y macOS">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Apple unificará desarrollo de apps para iOS y macOS</span>
		</a>
	</span>
</li>
<li>
	<span id="item-239">
		<a href="#" data-media="http://www.ivoox.com/radiogeek-apple-lo-confirma-iphones_mf_22772769_feed_1.mp3" title="#Radiogeek - Apple lo confirma que los iPhones se hace más lento con los años">
			<span class="isplaying"></span>
			<span class="logo radiogeek"></span>
			<span class="podcast">Radiogeek</span>
			<span class="track">#Radiogeek - Apple lo confirma que los iPhones se hace más lento con los años</span>
		</a>
	</span>
</li>
<li>
	<span id="item-240">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/12/podcast-86-portainer-remoto.mp3" title="Podcast #86: Portainer y docker remoto">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #86: Portainer y docker remoto</span>
		</a>
	</span>
</li>
<li>
	<span id="item-241">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/7792665/Bat2x100_171.m4a" title="#171 – Podcast 24horas tarde…">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#171 – Podcast 24horas tarde…</span>
		</a>
	</span>
</li>
<li>
	<span id="item-242">
		<a href="#" data-media="http://20313.mc.tritondigital.com/WHOOSHKAA_2289/media-session/a53e91c0-a0ea-4cb1-a8b3-3b528cbf917d/podcasts/podcast_2486/podcast_media/ed4c51-2-aplicaciones-y-reproductor-de-podcast.mp3" title="084. Rerproductor de Podcast y 2 App de Oferta">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">084. Rerproductor de Podcast y 2 App de Oferta</span>
		</a>
	</span>
</li>
<li>
	<span id="item-243">
		<a href="#" data-media="http://podcast.edyo.es/podcast/edyo-34.mp3" title="EDyO 34 - Blockchain, no sólo criptomonedas">
			<span class="isplaying"></span>
			<span class="logo entredevyopspodcast"></span>
			<span class="podcast">EntreDevYOps Podcast</span>
			<span class="track">EDyO 34 - Blockchain, no sólo criptomonedas</span>
		</a>
	</span>
</li>
<li>
	<span id="item-244">
		<a href="#" data-media="http://www.ivoox.com/41-gaming-gnu-linux_mf_22751215_feed_1.mp3" title="#41 Gaming y GNU/Linux">
			<span class="isplaying"></span>
			<span class="logo podcastlinux"></span>
			<span class="podcast">Podcast Linux</span>
			<span class="track">#41 Gaming y GNU/Linux</span>
		</a>
	</span>
</li>
<li>
	<span id="item-245">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/5a3a0c249e91b02b75081860.mp3" title="El éxito silencioso de los AirPods">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">El éxito silencioso de los AirPods</span>
		</a>
	</span>
</li>
<li>
	<span id="item-246">
		<a href="#" data-media="http://api.spreaker.com/download/episode/13631690/mirando_la_mirilla.mp3" title="Mirando la mirilla">
			<span class="isplaying"></span>
			<span class="logo deknet"></span>
			<span class="podcast">DekNet</span>
			<span class="track">Mirando la mirilla</span>
		</a>
	</span>
</li>
<li>
	<span id="item-247">
		<a href="#" data-media="http://www.ivoox.com/episodio-16-kotlin_mf_22744381_feed_1.mp3" title="Episodio 16 - Kotlin">
			<span class="isplaying"></span>
			<span class="logo programaresunamierda"></span>
			<span class="podcast">Programar es una mierda</span>
			<span class="track">Episodio 16 - Kotlin</span>
		</a>
	</span>
</li>
<li>
	<span id="item-248">
		<a href="#" data-media="https://www.ivoox.com/episodio-16-kotlin_mf_22744381_feed_1.mp3" title="Episodio 16 - Kotlin">
			<span class="isplaying"></span>
			<span class="logo programaresunamierda"></span>
			<span class="podcast">Programar es una mierda</span>
			<span class="track">Episodio 16 - Kotlin</span>
		</a>
	</span>
</li>
<li>
	<span id="item-249">
		<a href="#" data-media="http://www.ivoox.com/radiogeek-hoy-dos-filtraciones-oficiales-del-galaxy_mf_22744060_feed_1.mp3" title="#Radiogeek - Hoy dos filtraciones oficiales del Galaxy S9 y Nokia 9">
			<span class="isplaying"></span>
			<span class="logo radiogeek"></span>
			<span class="podcast">Radiogeek</span>
			<span class="track">#Radiogeek - Hoy dos filtraciones oficiales del Galaxy S9 y Nokia 9</span>
		</a>
	</span>
</li>
<li>
	<span id="item-250">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/12/podcast-85-cluster-de-proxmox.mp3" title="Podcast #85: Cluster con Proxmox">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #85: Cluster con Proxmox</span>
		</a>
	</span>
</li>
<li>
	<span id="item-251">
		<a href="#" data-media="http://api.spreaker.com/download/episode/13627323/webreactiva_podcast_14.mp3" title="WR 14: Blockchain explicado como si se entendiera">
			<span class="isplaying"></span>
			<span class="logo webreactiva"></span>
			<span class="podcast">Web Reactiva</span>
			<span class="track">WR 14: Blockchain explicado como si se entendiera</span>
		</a>
	</span>
</li>
<li>
	<span id="item-252">
		<a href="#" data-media="http://www.ivoox.com/code-time-97-tipos-degradacion-del-software_mf_22725691_feed_1.mp3" title="Code Time (97): Tipos de degradación del Software">
			<span class="isplaying"></span>
			<span class="logo codetime"></span>
			<span class="podcast">Code Time</span>
			<span class="track">Code Time (97): Tipos de degradación del Software</span>
		</a>
	</span>
</li>
<li>
	<span id="item-253">
		<a href="#" data-media="http://www.ivoox.com/code-time-98-especial-navidad-fin_mf_22725690_feed_1.mp3" title="Code Time (98) Especial de Navidad y fin de año 2017">
			<span class="isplaying"></span>
			<span class="logo codetime"></span>
			<span class="podcast">Code Time</span>
			<span class="track">Code Time (98) Especial de Navidad y fin de año 2017</span>
		</a>
	</span>
</li>
<li>
	<span id="item-254">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/5a38ba769e91b02b7507e9aa.mp3" title="El rendimiento de los iPhone cae con el tiempo">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">El rendimiento de los iPhone cae con el tiempo</span>
		</a>
	</span>
</li>
<li>
	<span id="item-255">
		<a href="#" data-media="http://www.ivoox.com/radiogeek-al-fin-chrome-va-bloquear-los_mf_22723812_feed_1.mp3" title="#Radiogeek - Al fin Chrome va bloquear los pop-up de vídeos molestos">
			<span class="isplaying"></span>
			<span class="logo radiogeek"></span>
			<span class="podcast">Radiogeek</span>
			<span class="track">#Radiogeek - Al fin Chrome va bloquear los pop-up de vídeos molestos</span>
		</a>
	</span>
</li>
<li>
	<span id="item-256">
		<a href="#" data-media="https://anchor.fm/s/18c0860/podcast/download/77224/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fanchor-data%2Fstationexports%2Fpodcasts%2FRouter-Xiaomi-R1D-7ec45adbb6111.m4a" title="Router Xiaomi R1D">
			<span class="isplaying"></span>
			<span class="logo tomandouncafé"></span>
			<span class="podcast">Tomando Un Café</span>
			<span class="track">Router Xiaomi R1D</span>
		</a>
	</span>
</li>
<li>
	<span id="item-257">
		<a href="#" data-media="http://www.ivoox.com/software-time-0-mis-principios-ciencias-de_mf_22722049_feed_1.mp3" title="Software Time (0): Mis principios en ciencias de la computación">
			<span class="isplaying"></span>
			<span class="logo codetime"></span>
			<span class="podcast">Code Time</span>
			<span class="track">Software Time (0): Mis principios en ciencias de la computación</span>
		</a>
	</span>
</li>
<li>
	<span id="item-258">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/12/podcast-84-paqueteria-snap.mp3" title="Podcast #84: Paquetería snap">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #84: Paquetería snap</span>
		</a>
	</span>
</li>
<li>
	<span id="item-259">
		<a href="#" data-media="http://www.ivoox.com/025-preguntas-respuestas-productividad_mf_22711163_feed_1.mp3" title="025 - Preguntas y respuestas de productividad">
			<span class="isplaying"></span>
			<span class="logo aprendiendogtdpodcastproductividad"></span>
			<span class="podcast">Aprendiendo GTD podcast productividad</span>
			<span class="track">025 - Preguntas y respuestas de productividad</span>
		</a>
	</span>
</li>
<li>
	<span id="item-260">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/5a376b6b9e91b02b7507c079.mp3" title="La solución para que Facebook no te ponga triste es usar mejor Facebook, dice Facebook">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">La solución para que Facebook no te ponga triste es usar mejor Facebook, dice Facebook</span>
		</a>
	</span>
</li>
<li>
	<span id="item-261">
		<a href="#" data-media="http://www.ivoox.com/33-master-class-sobre-nas-2-parte-raid_mf_22700286_feed_1.mp3" title="33. Master Class sobre NAS (2ª parte). RAID de discos">
			<span class="isplaying"></span>
			<span class="logo naserospodcast"></span>
			<span class="podcast">NASeros Podcast</span>
			<span class="track">33. Master Class sobre NAS (2ª parte). RAID de discos</span>
		</a>
	</span>
</li>
<li>
	<span id="item-262">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/12/podcast-83-conexion-ipv6-por-tunelbroker.mp3" title="Podcast #83: Conexión IPv6 por túnel broker">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #83: Conexión IPv6 por túnel broker</span>
		</a>
	</span>
</li>
<li>
	<span id="item-263">
		<a href="#" data-media="http://mundipad.es/capitulos-podcast-bemoob/097-foromoviles-podcast.mp3" title="ForoMoviles Podcast 097: Microsoft, Android TV…">
			<span class="isplaying"></span>
			<span class="logo podcastforomóviles"></span>
			<span class="podcast">Podcast – ForoMóviles</span>
			<span class="track">ForoMoviles Podcast 097: Microsoft, Android TV…</span>
		</a>
	</span>
</li>
<li>
	<span id="item-264">
		<a href="#" data-media="http://api.spreaker.com/download/episode/13561921/podcast_carpetas.mp3" title="PODCAST: Carpetas, un valor añadido">
			<span class="isplaying"></span>
			<span class="logo deknet"></span>
			<span class="podcast">DekNet</span>
			<span class="track">PODCAST: Carpetas, un valor añadido</span>
		</a>
	</span>
</li>
<li>
	<span id="item-265">
		<a href="#" data-media="http://www.ivoox.com/linux-android-otras-noticias_mf_22680412_feed_1.mp3" title="Linux, Android y otras noticias">
			<span class="isplaying"></span>
			<span class="logo mosqueterowebtecnologialinuxchromebooks"></span>
			<span class="podcast">Mosqueteroweb tecnologia, Linux, Chromebooks</span>
			<span class="track">Linux, Android y otras noticias</span>
		</a>
	</span>
</li>
<li>
	<span id="item-266">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/7736243/Bat2x100_170.m4a" title="#170 – Píldoras de información.">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#170 – Píldoras de información.</span>
		</a>
	</span>
</li>
<li>
	<span id="item-267">
		<a href="#" data-media="http://www.ivoox.com/166-linux-con-todos-respetos_mf_22668853_feed_1.mp3" title="#166 Linux: Con Todos Respetos">
			<span class="isplaying"></span>
			<span class="logo salmorejogeek"></span>
			<span class="podcast">Salmorejo Geek</span>
			<span class="track">#166 Linux: Con Todos Respetos</span>
		</a>
	</span>
</li>
<li>
	<span id="item-268">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/5a33ac0d9e91b02b75077fb3.mp3" title="O los gigantes tecnológicos empiezan a entenderse, o les hacemos entenderse">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">O los gigantes tecnológicos empiezan a entenderse, o les hacemos entenderse</span>
		</a>
	</span>
</li>
<li>
	<span id="item-269">
		<a href="#" data-media="https://ia601500.us.archive.org/0/items/NasVsServidorLinux/Nas%20vs%20Servidor%20Linux.mp3" title="083. Nas vs Servidor Linux">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">083. Nas vs Servidor Linux</span>
		</a>
	</span>
</li>
<li>
	<span id="item-270">
		<a href="#" data-media="http://www.ivoox.com/arqueologia-informatica-cap-82_mf_22664371_feed_1.mp3" title="Arqueología Informática - Cap 82">
			<span class="isplaying"></span>
			<span class="logo podcastwintabletinfo"></span>
			<span class="podcast">Podcast WINTABLET.INFO</span>
			<span class="track">Arqueología Informática - Cap 82</span>
		</a>
	</span>
</li>
<li>
	<span id="item-271">
		<a href="#" data-media="http://api.spreaker.com/download/episode/13589179/podcast124.mp3" title="#124 Dispositivo del IoT con SigFox y Arduino">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">#124 Dispositivo del IoT con SigFox y Arduino</span>
		</a>
	</span>
</li>
<li>
	<span id="item-272">
		<a href="#" data-media="http://www.ivoox.com/radiogeek-estados-unidos-termina-neutralidad_mf_22664227_feed_1.mp3" title="#Radiogeek - Estados unidos termina con la neutralidad en la red">
			<span class="isplaying"></span>
			<span class="logo radiogeek"></span>
			<span class="podcast">Radiogeek</span>
			<span class="track">#Radiogeek - Estados unidos termina con la neutralidad en la red</span>
		</a>
	</span>
</li>
<li>
	<span id="item-273">
		<a href="#" data-media="https://anchor.fm/s/18c0860/podcast/download/75202/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fanchor-data%2Fstationexports%2Fpodcasts%2FProgramadores-b73f798e01edd.m4a" title="Programadores">
			<span class="isplaying"></span>
			<span class="logo tomandouncafé"></span>
			<span class="podcast">Tomando Un Café</span>
			<span class="track">Programadores</span>
		</a>
	</span>
</li>
<li>
	<span id="item-274">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/12/podcast-82-instalacion-mikrotik.mp3" title="Podcast #82: Instalación mikrotik de cliente">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #82: Instalación mikrotik de cliente</span>
		</a>
	</span>
</li>
<li>
	<span id="item-275">
		<a href="#" data-media="https://ar.ivoox.com/es/ep141-asteroide-interestelar-oumuamua-habitabilidad-galactica-galactoscuroplanismo-marte_mf_22657184_feed_1.mp3" title="Ep141: Asteroide Interestelar 'Oumuamua; Habitabilidad Galáctica; Galactoscuroplanismo; Marte; Ojos y Telescopios">
			<span class="isplaying"></span>
			<span class="logo coffeebreakseñalyruido"></span>
			<span class="podcast">Coffee Break: Señal y Ruido</span>
			<span class="track">Ep141: Asteroide Interestelar 'Oumuamua; Habitabilidad Galáctica; Galactoscuroplanismo; Marte; Ojos y Telescopios</span>
		</a>
	</span>
</li>
<li>
	<span id="item-276">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/5a32ac5e9e91b02b750750b4.mp3" title="Kernel: Conociendo a Sundar Pichai, con Rosa Jiménez Cano">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Kernel: Conociendo a Sundar Pichai, con Rosa Jiménez Cano</span>
		</a>
	</span>
</li>
<li>
	<span id="item-277">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/5a321d8a9e91b02b750730c0.mp3" title="Giros de 180 grados en Facebook, Patreon y iTunes Music">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Giros de 180 grados en Facebook, Patreon y iTunes Music</span>
		</a>
	</span>
</li>
<li>
	<span id="item-278">
		<a href="#" data-media="http://www.ivoox.com/radiogeek-google-lanza-maps-go-para-android_mf_22643422_feed_1.mp3" title="#Radiogeek - Google lanza Maps Go para Android">
			<span class="isplaying"></span>
			<span class="logo radiogeek"></span>
			<span class="podcast">Radiogeek</span>
			<span class="track">#Radiogeek - Google lanza Maps Go para Android</span>
		</a>
	</span>
</li>
<li>
	<span id="item-279">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/12/podcast-81-transitos-y-peering.mp3" title="Podcast #81: Tránsitos y peering">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #81: Tránsitos y peering</span>
		</a>
	</span>
</li>
<li>
	<span id="item-280">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/5a30d1ae9e91b02b750704f4.mp3" title="Facebook cambia su estructura fiscal">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Facebook cambia su estructura fiscal</span>
		</a>
	</span>
</li>
<li>
	<span id="item-281">
		<a href="#" data-media="http://www.ivoox.com/radiogeek-en-local-starbucks-de_mf_22616725_feed_1.mp3" title="#Radiogeek - En un local de Starbucks de Buenos Aires usan la red Wifi para minar Bitcoins">
			<span class="isplaying"></span>
			<span class="logo radiogeek"></span>
			<span class="podcast">Radiogeek</span>
			<span class="track">#Radiogeek - En un local de Starbucks de Buenos Aires usan la red Wifi para minar Bitcoins</span>
		</a>
	</span>
</li>
<li>
	<span id="item-282">
		<a href="#" data-media="https://gitlab.com/podcastlinux/podcastlinux.gitlab.io/raw/master/Linux-Express/30linuxexpress.mp3" title="#30 Linux Express">
			<span class="isplaying"></span>
			<span class="logo linuxexpressdepodcastlinux"></span>
			<span class="podcast">Linux Express, de Podcast Linux.</span>
			<span class="track">#30 Linux Express</span>
		</a>
	</span>
</li>
<li>
	<span id="item-283">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/12/podcast-80-listas-de-spam.mp3" title="Podcast #80: Listas de Spam">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #80: Listas de Spam</span>
		</a>
	</span>
</li>
<li>
	<span id="item-284">
		<a href="#" data-media="http://feedproxy.google.com/~r/WecodesignPodcast/~5/2FBnmpGpvXA/WeCodeSign%202x13%20-%20Proyectos%20Sostenibles.mp3" title="2x13 - Proyectos Sostenibles">
			<span class="isplaying"></span>
			<span class="logo wecodesignpodcast"></span>
			<span class="podcast">WeCodeSign Podcast</span>
			<span class="track">2x13 - Proyectos Sostenibles</span>
		</a>
	</span>
</li>
<li>
	<span id="item-285">
		<a href="#" data-media="https://anchor.fm/s/18c0860/podcast/download/73685/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fanchor-data%2Fstationexports%2Fpodcasts%2FReflexi-n-sobre-Software-Libre-e441b001260f9.m4a" title="Reflexión sobre Software Libre">
			<span class="isplaying"></span>
			<span class="logo tomandouncafé"></span>
			<span class="podcast">Tomando Un Café</span>
			<span class="track">Reflexión sobre Software Libre</span>
		</a>
	</span>
</li>
<li>
	<span id="item-286">
		<a href="#" data-media="http://feedproxy.google.com/~r/Vaciatubandeja/~5/TCSxrOELpFY/6622240.mp3" title="14: Bullet Journal | Adáptalo a los principios del GTD">
			<span class="isplaying"></span>
			<span class="logo vacíatubandeja"></span>
			<span class="podcast">Vacía tu bandeja</span>
			<span class="track">14: Bullet Journal | Adáptalo a los principios del GTD</span>
		</a>
	</span>
</li>
<li>
	<span id="item-287">
		<a href="#" data-media="http://api.spreaker.com/download/episode/13565951/webreactiva_podcast_13.mp3" title="WR 13: Así creamos nuestro primer chatbot">
			<span class="isplaying"></span>
			<span class="logo webreactiva"></span>
			<span class="podcast">Web Reactiva</span>
			<span class="track">WR 13: Así creamos nuestro primer chatbot</span>
		</a>
	</span>
</li>
<li>
	<span id="item-288">
		<a href="#" data-media="http://www.ivoox.com/code-time-96-causas-tipos-degradacion_mf_22594788_feed_1.mp3" title="Code Time (96): Causas y tipos de degradación del Software">
			<span class="isplaying"></span>
			<span class="logo codetime"></span>
			<span class="podcast">Code Time</span>
			<span class="track">Code Time (96): Causas y tipos de degradación del Software</span>
		</a>
	</span>
</li>
<li>
	<span id="item-289">
		<a href="#" data-media="http://www.ivoox.com/32-master-class-sobre-nas-1-parte_mf_22593315_feed_1.mp3" title="32. Master Class sobre NAS (1ª parte)">
			<span class="isplaying"></span>
			<span class="logo naserospodcast"></span>
			<span class="podcast">NASeros Podcast</span>
			<span class="track">32. Master Class sobre NAS (1ª parte)</span>
		</a>
	</span>
</li>
<li>
	<span id="item-290">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/5a2f826f9e91b02b7506dbc1.mp3" title="Apple hace cambios inteligentes en la App Store">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Apple hace cambios inteligentes en la App Store</span>
		</a>
	</span>
</li>
<li>
	<span id="item-291">
		<a href="#" data-media="http://api.spreaker.com/download/episode/13548323/2017_12_10_01_19_28.mp3" title="La basura de las ovejas">
			<span class="isplaying"></span>
			<span class="logo deknet"></span>
			<span class="podcast">DekNet</span>
			<span class="track">La basura de las ovejas</span>
		</a>
	</span>
</li>
<li>
	<span id="item-292">
		<a href="#" data-media="https://anchor.fm/s/18c0860/podcast/download/73159/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fanchor-data%2Fstationexports%2Fpodcasts%2FSmartGit-3e87d9cacfb3a.m4a" title="SmartGit">
			<span class="isplaying"></span>
			<span class="logo tomandouncafé"></span>
			<span class="podcast">Tomando Un Café</span>
			<span class="track">SmartGit</span>
		</a>
	</span>
</li>
<li>
	<span id="item-293">
		<a href="#" data-media="http://www.ivoox.com/radiogeek-lg-seria-fabricante-las_mf_22590318_feed_1.mp3" title="#Radiogeek - LG seria el fabricante de las próximas pantallas del iPhone X">
			<span class="isplaying"></span>
			<span class="logo radiogeek"></span>
			<span class="podcast">Radiogeek</span>
			<span class="track">#Radiogeek - LG seria el fabricante de las próximas pantallas del iPhone X</span>
		</a>
	</span>
</li>
<li>
	<span id="item-294">
		<a href="#" data-media="http://feedproxy.google.com/~r/Vaciatubandeja/~5/KidifVae9DQ/14-Bullet%20Journal-%20Adaptalo%20a%20los%20principios%20del%20GTD.mp3" title="#14-Bullet Journal: Adáptalo a los principios del GTD">
			<span class="isplaying"></span>
			<span class="logo vaciatubandeja"></span>
			<span class="podcast">Vacia Tu Bandeja</span>
			<span class="track">#14-Bullet Journal: Adáptalo a los principios del GTD</span>
		</a>
	</span>
</li>
<li>
	<span id="item-295">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/12/podcast-79-ebtables.mp3" title="Podcast #79: ebtables">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #79: ebtables</span>
		</a>
	</span>
</li>
<li>
	<span id="item-296">
		<a href="#" data-media="https://ia601504.us.archive.org/25/items/SlimbookOneEl3En1/SlimbookOne_El_3_en_1.mp3" title="082. Slimbook One. El 3 en 1">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">082. Slimbook One. El 3 en 1</span>
		</a>
	</span>
</li>
<li>
	<span id="item-297">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/5a2e2ca09e91b02b7506b052.mp3" title="Vuelve Jony Ive a Appleâ€¦ Â¿se habÃ­a ido?">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Vuelve Jony Ive a Appleâ€¦ Â¿se habÃ­a ido?</span>
		</a>
	</span>
</li>
<li>
	<span id="item-298">
		<a href="#" data-media="https://anchor.fm/s/18c0860/podcast/download/72594/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fanchor-data%2Fstationexports%2Fpodcasts%2FSmartGit-7884acb9eeb5e.m4a" title="SmartGit">
			<span class="isplaying"></span>
			<span class="logo tomandouncafé"></span>
			<span class="podcast">Tomando Un Café</span>
			<span class="track">SmartGit</span>
		</a>
	</span>
</li>
<li>
	<span id="item-299">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/12/podcast-78-policy-routing-en-mikrotik.mp3" title="Podcast #78: Policy Routing en Mikrotik">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #78: Policy Routing en Mikrotik</span>
		</a>
	</span>
</li>
<li>
	<span id="item-300">
		<a href="#" data-media="http://www.ivoox.com/radiogeek-especial-bitcoin-podcast_mf_22567872_feed_1.mp3" title="#Radiogeek - Especial Bitcoin - #Podcast">
			<span class="isplaying"></span>
			<span class="logo radiogeek"></span>
			<span class="podcast">Radiogeek</span>
			<span class="track">#Radiogeek - Especial Bitcoin - #Podcast</span>
		</a>
	</span>
</li>
<li>
	<span id="item-301">
		<a href="#" data-media="http://www.ivoox.com/episodio-15-pruebas_mf_22565205_feed_1.mp3" title="Episodio 15 - Pruebas">
			<span class="isplaying"></span>
			<span class="logo programaresunamierda"></span>
			<span class="podcast">Programar es una mierda</span>
			<span class="track">Episodio 15 - Pruebas</span>
		</a>
	</span>
</li>
<li>
	<span id="item-302">
		<a href="#" data-media="https://www.ivoox.com/episodio-15-pruebas_mf_22565205_feed_1.mp3" title="Episodio 15 - Pruebas">
			<span class="isplaying"></span>
			<span class="logo programaresunamierda"></span>
			<span class="podcast">Programar es una mierda</span>
			<span class="track">Episodio 15 - Pruebas</span>
		</a>
	</span>
</li>
<li>
	<span id="item-303">
		<a href="#" data-media="https://www.ivoox.com/s02e03-distros-derivadas-entrevista-unav-linux-on_mf_22563701_feed_1.mp3" title="S02E03 Distros derivadas, entrevista uNav y Linux on Galaxy">
			<span class="isplaying"></span>
			<span class="logo ubuntuyotrashierbas"></span>
			<span class="podcast">Ubuntu y otras hierbas</span>
			<span class="track">S02E03 Distros derivadas, entrevista uNav y Linux on Galaxy</span>
		</a>
	</span>
</li>
<li>
	<span id="item-304">
		<a href="#" data-media="http://api.spreaker.com/download/episode/13542388/borrando_el_rastro_en_twitter.mp3" title="Borrando el rastro en Twitter">
			<span class="isplaying"></span>
			<span class="logo deknet"></span>
			<span class="podcast">DekNet</span>
			<span class="track">Borrando el rastro en Twitter</span>
		</a>
	</span>
</li>
<li>
	<span id="item-305">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/Ep114.mp3" title="Descubren el Quásar más lejano del universo [Ep.114]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Descubren el Quásar más lejano del universo [Ep.114]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-306">
		<a href="#" data-media="http://api.spreaker.com/download/episode/13531952/cuentochino.mp3" title="Un cuento chino">
			<span class="isplaying"></span>
			<span class="logo deknet"></span>
			<span class="podcast">DekNet</span>
			<span class="track">Un cuento chino</span>
		</a>
	</span>
</li>
<li>
	<span id="item-307">
		<a href="#" data-media="http://www.ivoox.com/23-super-luna-rally-madrid_mf_22548729_feed_1.mp3" title="#23 Súper luna + Rally de Madrid">
			<span class="isplaying"></span>
			<span class="logo reflexpodcast"></span>
			<span class="podcast">reflex podcast</span>
			<span class="track">#23 Súper luna + Rally de Madrid</span>
		</a>
	</span>
</li>
<li>
	<span id="item-308">
		<a href="#" data-media="http://www.ivoox.com/radiogeek-cafe-amigos-geeks_mf_22534965_feed_1.mp3" title="#Radiogeek - Cafe con amigos geeks">
			<span class="isplaying"></span>
			<span class="logo radiogeek"></span>
			<span class="podcast">Radiogeek</span>
			<span class="track">#Radiogeek - Cafe con amigos geeks</span>
		</a>
	</span>
</li>
<li>
	<span id="item-309">
		<a href="#" data-media="http://www.ivoox.com/chromebooks-netbooks-revival_mf_22531698_feed_1.mp3" title="Chromebooks. Netbooks revival">
			<span class="isplaying"></span>
			<span class="logo mosqueterowebtecnologialinuxchromebooks"></span>
			<span class="podcast">Mosqueteroweb tecnologia, Linux, Chromebooks</span>
			<span class="track">Chromebooks. Netbooks revival</span>
		</a>
	</span>
</li>
<li>
	<span id="item-310">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/12/podcast-77-opendns.mp3" title="Podcast #77: OpenDNS">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #77: OpenDNS</span>
		</a>
	</span>
</li>
<li>
	<span id="item-311">
		<a href="#" data-media="https://ar.ivoox.com/es/ep140-colapso-del-vacio-fin-del-universo-minimo_mf_22530768_feed_1.mp3" title="Ep140:Colapso del Vacío y Fin del Universo; Mínimo Solar; Voyager Reactivado; ExperimentoLuna; Principio de Equivalencia">
			<span class="isplaying"></span>
			<span class="logo coffeebreakseñalyruido"></span>
			<span class="podcast">Coffee Break: Señal y Ruido</span>
			<span class="track">Ep140:Colapso del Vacío y Fin del Universo; Mínimo Solar; Voyager Reactivado; ExperimentoLuna; Principio de Equivalencia</span>
		</a>
	</span>
</li>
<li>
	<span id="item-312">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/5a29582f9e91b02b75064b86.mp3" title="Kernel: Cromos, cofres y casinos. La realidad de los juegos móviles con Félix Palazuelos">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Kernel: Cromos, cofres y casinos. La realidad de los juegos móviles con Félix Palazuelos</span>
		</a>
	</span>
</li>
<li>
	<span id="item-313">
		<a href="#" data-media="http://podcast.edyo.es/podcast/edyo-33.mp3" title="EDyO 33 - Hablamos sobre CI/CD">
			<span class="isplaying"></span>
			<span class="logo entredevyopspodcast"></span>
			<span class="podcast">EntreDevYOps Podcast</span>
			<span class="track">EDyO 33 - Hablamos sobre CI/CD</span>
		</a>
	</span>
</li>
<li>
	<span id="item-314">
		<a href="#" data-media="http://api.spreaker.com/download/episode/13526313/viajeros_estelares.mp3" title="OFFTOPIC: Viajeros Estelares">
			<span class="isplaying"></span>
			<span class="logo deknet"></span>
			<span class="podcast">DekNet</span>
			<span class="track">OFFTOPIC: Viajeros Estelares</span>
		</a>
	</span>
</li>
<li>
	<span id="item-315">
		<a href="#" data-media="http://www.ivoox.com/radiogeek-el-fundador-vine-esta-trabajando_mf_22515020_feed_1.mp3" title="#Radiogeek - El Fundador de Vine esta trabajando en Vine 2">
			<span class="isplaying"></span>
			<span class="logo radiogeek"></span>
			<span class="podcast">Radiogeek</span>
			<span class="track">#Radiogeek - El Fundador de Vine esta trabajando en Vine 2</span>
		</a>
	</span>
</li>
<li>
	<span id="item-316">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/12/podcast-76-analizar-trafico-en-mikrotik.mp3" title="Podcast #76: Analizar tráfico en Mikrotik">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #76: Analizar tráfico en Mikrotik</span>
		</a>
	</span>
</li>
<li>
	<span id="item-317">
		<a href="#" data-media="http://www.ivoox.com/40-linux-connexion-aleix-pol_mf_22492088_feed_1.mp3" title="#40 Linux Connexion con Aleix Pol">
			<span class="isplaying"></span>
			<span class="logo podcastlinux"></span>
			<span class="podcast">Podcast Linux</span>
			<span class="track">#40 Linux Connexion con Aleix Pol</span>
		</a>
	</span>
</li>
<li>
	<span id="item-318">
		<a href="#" data-media="http://www.ivoox.com/radiogeek-samsung-lanza-memorias-512-gb_mf_22487853_feed_1.mp3" title="#Radiogeek - Samsung lanza memorias de 512 GB, las que podrían ser usadas en el S9">
			<span class="isplaying"></span>
			<span class="logo radiogeek"></span>
			<span class="podcast">Radiogeek</span>
			<span class="track">#Radiogeek - Samsung lanza memorias de 512 GB, las que podrían ser usadas en el S9</span>
		</a>
	</span>
</li>
<li>
	<span id="item-319">
		<a href="#" data-media="https://anchor.fm/s/18c0860/podcast/download/69917/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fanchor-data%2Fstationexports%2Fpodcasts%2FTelegram-para-podcast-464eeff27265b.m4a" title="Telegram para podcast">
			<span class="isplaying"></span>
			<span class="logo tomandouncafé"></span>
			<span class="podcast">Tomando Un Café</span>
			<span class="track">Telegram para podcast</span>
		</a>
	</span>
</li>
<li>
	<span id="item-320">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/12/especial-plataformas-de-podcasting-con-ivan-patxi.mp3" title="Especial: Plataformas de podcasting con Iván Patxi">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Especial: Plataformas de podcasting con Iván Patxi</span>
		</a>
	</span>
</li>
<li>
	<span id="item-321">
		<a href="#" data-media="http://compilando.audio/wp-content/uploads/2017/12/podcast18.mp3" title="Podcast 18 – Desarrollo de Debian con Laura Arjona y Firefox Quantum">
			<span class="isplaying"></span>
			<span class="logo compilandopodcast"></span>
			<span class="podcast">Compilando Podcast</span>
			<span class="track">Podcast 18 – Desarrollo de Debian con Laura Arjona y Firefox Quantum</span>
		</a>
	</span>
</li>
<li>
	<span id="item-322">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/7627716/Bat2x100_169.m4a" title="#169 – Recomendaciones  varias (interesante creo)">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#169 – Recomendaciones  varias (interesante creo)</span>
		</a>
	</span>
</li>
<li>
	<span id="item-323">
		<a href="#" data-media="http://api.spreaker.com/download/episode/13511346/webreactiva_podcast_12b.mp3" title="WR 12: Marketing online y desarrollo web con Óscar Martín">
			<span class="isplaying"></span>
			<span class="logo webreactiva"></span>
			<span class="podcast">Web Reactiva</span>
			<span class="track">WR 12: Marketing online y desarrollo web con Óscar Martín</span>
		</a>
	</span>
</li>
<li>
	<span id="item-324">
		<a href="#" data-media="http://www.ivoox.com/code-time-95-la-degradacion-del-software_mf_22452388_feed_1.mp3" title="Code Time (95): La degradación del Software">
			<span class="isplaying"></span>
			<span class="logo codetime"></span>
			<span class="podcast">Code Time</span>
			<span class="track">Code Time (95): La degradación del Software</span>
		</a>
	</span>
</li>
<li>
	<span id="item-325">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/5a26301d9e91b02b750603ae.mp3" title="Dejad que los niños se acerquen a Facebook">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Dejad que los niños se acerquen a Facebook</span>
		</a>
	</span>
</li>
<li>
	<span id="item-326">
		<a href="#" data-media="http://www.ivoox.com/radiogeek-samsung-revolucionaria-mercado-las_mf_22447288_feed_1.mp3" title="#Radiogeek - Samsung revolucionaria el mercado de las baterías con el Grafeno">
			<span class="isplaying"></span>
			<span class="logo radiogeek"></span>
			<span class="podcast">Radiogeek</span>
			<span class="track">#Radiogeek - Samsung revolucionaria el mercado de las baterías con el Grafeno</span>
		</a>
	</span>
</li>
<li>
	<span id="item-327">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/12/podcast-75-multiples-gateways-multiples-interfaces.mp3" title="Podcast #75: Multiples gateways con múltiples interfaces">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #75: Multiples gateways con múltiples interfaces</span>
		</a>
	</span>
</li>
<li>
	<span id="item-328">
		<a href="#" data-media="http://api.spreaker.com/download/episode/13504143/jakers.mp3" title="Jakers de escaparate">
			<span class="isplaying"></span>
			<span class="logo deknet"></span>
			<span class="podcast">DekNet</span>
			<span class="track">Jakers de escaparate</span>
		</a>
	</span>
</li>
<li>
	<span id="item-329">
		<a href="#" data-media="http://tracking.feedpress.it/link/15407/7611398/BCS019-Plataforma-Life-ciberacoso-y-suicidio.mp3" title="BCS019 – Plataforma Life! Ciberacoso y suicidio">
			<span class="isplaying"></span>
			<span class="logo bitácoradeciberseguridad"></span>
			<span class="podcast">Bitácora de Ciberseguridad</span>
			<span class="track">BCS019 – Plataforma Life! Ciberacoso y suicidio</span>
		</a>
	</span>
</li>
<li>
	<span id="item-330">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/5a24f6319e91b02b7505da56.mp3" title="Wall Street se lanza a por el Bitcoin">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Wall Street se lanza a por el Bitcoin</span>
		</a>
	</span>
</li>
<li>
	<span id="item-331">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/12/podcast-74-varias-ips-mala-idea-constante.mp3" title="Podcast #74: Varias IPs en el mismo interfaz es mala idea">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #74: Varias IPs en el mismo interfaz es mala idea</span>
		</a>
	</span>
</li>
<li>
	<span id="item-332">
		<a href="#" data-media="http://www.ivoox.com/165-asi-lo-hacemos-apacoestrada77-aecollado-ayoyo308_mf_22424042_feed_1.mp3" title="#165 Asi? lo hacemos (@pacoestrada77 @ecollado @yoyo308)">
			<span class="isplaying"></span>
			<span class="logo salmorejogeek"></span>
			<span class="podcast">Salmorejo Geek</span>
			<span class="track">#165 Asi? lo hacemos (@pacoestrada77 @ecollado @yoyo308)</span>
		</a>
	</span>
</li>
<li>
	<span id="item-333">
		<a href="#" data-media="https://anchor.fm/s/106db04/podcast/download/68109/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fanchor-data%2Fstationexports%2Fpodcasts%2FRecomendaciones-Y-Pr-ximo-Ep---4dadac040f951.m4a" title="081. Recomendaciones y Próximos Podcast">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">081. Recomendaciones y Próximos Podcast</span>
		</a>
	</span>
</li>
<li>
	<span id="item-334">
		<a href="#" data-media="https://anchor.fm/s/18c0860/podcast/download/68248/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fanchor-data%2Fstationexports%2Fpodcasts%2FHerramientas-para-terminal-12d2778854d9c.m4a" title="Herramientas para terminal">
			<span class="isplaying"></span>
			<span class="logo tomandouncafé"></span>
			<span class="podcast">Tomando Un Café</span>
			<span class="track">Herramientas para terminal</span>
		</a>
	</span>
</li>
<li>
	<span id="item-335">
		<a href="#" data-media="https://archive.org/download/ArielCorgatelli/ArielCorgatelli.ogg" title="#04 Maratón Linuxero 3D: Ariel Corgatelli">
			<span class="isplaying"></span>
			<span class="logo maratónlinuxero"></span>
			<span class="podcast">Maratón Linuxero</span>
			<span class="track">#04 Maratón Linuxero 3D: Ariel Corgatelli</span>
		</a>
	</span>
</li>
<li>
	<span id="item-336">
		<a href="#" data-media="https://archive.org/download/MaratonLinuxero3D/MaratonLinuxero3D.ogg" title="#03 Maratón Linuxero 3D: Maratón Linuxero">
			<span class="isplaying"></span>
			<span class="logo maratónlinuxero"></span>
			<span class="podcast">Maratón Linuxero</span>
			<span class="track">#03 Maratón Linuxero 3D: Maratón Linuxero</span>
		</a>
	</span>
</li>
<li>
	<span id="item-337">
		<a href="#" data-media="https://archive.org/download/GabrielCoronado/GabrielCoronado.ogg" title="#02 Maratón Linuxero 3D: Gabriel Coronado">
			<span class="isplaying"></span>
			<span class="logo maratónlinuxero"></span>
			<span class="podcast">Maratón Linuxero</span>
			<span class="track">#02 Maratón Linuxero 3D: Gabriel Coronado</span>
		</a>
	</span>
</li>
<li>
	<span id="item-338">
		<a href="#" data-media="https://archive.org/download/RailsGirlsVe/RailGirlsVe.ogg" title="#01 Maratón Linuxero 3D: Rails Girls Venezuela">
			<span class="isplaying"></span>
			<span class="logo maratónlinuxero"></span>
			<span class="podcast">Maratón Linuxero</span>
			<span class="track">#01 Maratón Linuxero 3D: Rails Girls Venezuela</span>
		</a>
	</span>
</li>
<li>
	<span id="item-339">
		<a href="#" data-media="http://mundipad.es/capitulos-podcast-bemoob/096-foromoviles-podcast.mp3" title="ForoMoviles Podcast 096: Youtube y trabajar haciendo vídeos">
			<span class="isplaying"></span>
			<span class="logo podcastforomóviles"></span>
			<span class="podcast">Podcast – ForoMóviles</span>
			<span class="track">ForoMoviles Podcast 096: Youtube y trabajar haciendo vídeos</span>
		</a>
	</span>
</li>
<li>
	<span id="item-340">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/Ep113.mp3" title="Física o Astronomía, plasmas y algo más [Ep.113]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Física o Astronomía, plasmas y algo más [Ep.113]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-341">
		<a href="#" data-media="http://api.spreaker.com/download/episode/13488362/sin_alternativas.mp3" title="Sin alternativas">
			<span class="isplaying"></span>
			<span class="logo deknet"></span>
			<span class="podcast">DekNet</span>
			<span class="track">Sin alternativas</span>
		</a>
	</span>
</li>
<li>
	<span id="item-342">
		<a href="#" data-media="http://www.ivoox.com/radiogeek-el-google-pixel-tiene-menos-amigos_mf_22406601_feed_1.mp3" title="#Radiogeek - El Google Pixel tiene menos amigos que Trump">
			<span class="isplaying"></span>
			<span class="logo radiogeek"></span>
			<span class="podcast">Radiogeek</span>
			<span class="track">#Radiogeek - El Google Pixel tiene menos amigos que Trump</span>
		</a>
	</span>
</li>
<li>
	<span id="item-343">
		<a href="#" data-media="http://www.ivoox.com/episodio-14-http-2_mf_22405717_feed_1.mp3" title="Episodio 14 - HTTP/2">
			<span class="isplaying"></span>
			<span class="logo programaresunamierda"></span>
			<span class="podcast">Programar es una mierda</span>
			<span class="track">Episodio 14 - HTTP/2</span>
		</a>
	</span>
</li>
<li>
	<span id="item-344">
		<a href="#" data-media="https://www.ivoox.com/episodio-14-http-2_mf_22405717_feed_1.mp3" title="Episodio 14 - HTTP/2">
			<span class="isplaying"></span>
			<span class="logo programaresunamierda"></span>
			<span class="podcast">Programar es una mierda</span>
			<span class="track">Episodio 14 - HTTP/2</span>
		</a>
	</span>
</li>
<li>
	<span id="item-345">
		<a href="#" data-media="http://www.ivoox.com/164-guiller-pedro-sanchez-yo-charleta-de_mf_22404222_feed_1.mp3" title="#164 Guiller, Pedro Sanchez y Yo: Charleta de Norte a Sur">
			<span class="isplaying"></span>
			<span class="logo salmorejogeek"></span>
			<span class="podcast">Salmorejo Geek</span>
			<span class="track">#164 Guiller, Pedro Sanchez y Yo: Charleta de Norte a Sur</span>
		</a>
	</span>
</li>
<li>
	<span id="item-346">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/5a2135229e91b02b7505a11c.mp3" title="General Motors revela sus planes de coches autónomos">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">General Motors revela sus planes de coches autónomos</span>
		</a>
	</span>
</li>
<li>
	<span id="item-347">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/11/especial-maraton-entrevista-jfebles.mp3" title="Especial: Entrevista a Juan Febles del Maratón Linuxero">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Especial: Entrevista a Juan Febles del Maratón Linuxero</span>
		</a>
	</span>
</li>
<li>
	<span id="item-348">
		<a href="#" data-media="http://www.ivoox.com/telecomunicaciones-cap-81_mf_22388287_feed_1.mp3" title="Telecomunicaciones - Cap 81">
			<span class="isplaying"></span>
			<span class="logo podcastwintabletinfo"></span>
			<span class="podcast">Podcast WINTABLET.INFO</span>
			<span class="track">Telecomunicaciones - Cap 81</span>
		</a>
	</span>
</li>
<li>
	<span id="item-349">
		<a href="#" data-media="https://anchor.fm/s/18c0860/podcast/download/66332/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fanchor-data%2Fstationexports%2Fpodcasts%2F5-Usos-para-un-canal-Telegram-8c30358c68ab1.m4a" title="5 Usos para un canal Telegram">
			<span class="isplaying"></span>
			<span class="logo tomandouncafé"></span>
			<span class="podcast">Tomando Un Café</span>
			<span class="track">5 Usos para un canal Telegram</span>
		</a>
	</span>
</li>
<li>
	<span id="item-350">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/11/podcast-73-migracion-correo.mp3" title="Podcast #73: Migración de servidor de correo">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #73: Migración de servidor de correo</span>
		</a>
	</span>
</li>
<li>
	<span id="item-351">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/7573563/Bat2x100_168.m4a" title="#168 – RSS Radio la mejor app para podcasts ?">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#168 – RSS Radio la mejor app para podcasts ?</span>
		</a>
	</span>
</li>
<li>
	<span id="item-352">
		<a href="#" data-media="https://ar.ivoox.com/es/ep139-especial-fisica-particulas-ii-simetrias-en_mf_22379719_feed_1.mp3" title="Ep139: Especial Física de Partículas II. Simetrías en Física y Leyes de Conservación; Campos Cuánticos; El Spin">
			<span class="isplaying"></span>
			<span class="logo coffeebreakseñalyruido"></span>
			<span class="podcast">Coffee Break: Señal y Ruido</span>
			<span class="track">Ep139: Especial Física de Partículas II. Simetrías en Física y Leyes de Conservación; Campos Cuánticos; El Spin</span>
		</a>
	</span>
</li>
<li>
	<span id="item-353">
		<a href="#" data-media="http://tracking.feedpress.it/link/14730/7570442/CN_Programa_029.mp3" title="#CN029 – Dieciocho preguntas y otros menesteres">
			<span class="isplaying"></span>
			<span class="logo culturanas"></span>
			<span class="podcast">Cultura NAS</span>
			<span class="track">#CN029 – Dieciocho preguntas y otros menesteres</span>
		</a>
	</span>
</li>
<li>
	<span id="item-354">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/5a1fa9b19e91b02b75057640.mp3" title="Un gran bug menos, muchos pequeños bugs que siguen">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Un gran bug menos, muchos pequeños bugs que siguen</span>
		</a>
	</span>
</li>
<li>
	<span id="item-355">
		<a href="#" data-media="http://api.spreaker.com/download/episode/13468209/deknet_20171130_0032.mp3" title="Tim Cook, chapuza sin limites">
			<span class="isplaying"></span>
			<span class="logo deknet"></span>
			<span class="podcast">DekNet</span>
			<span class="track">Tim Cook, chapuza sin limites</span>
		</a>
	</span>
</li>
<li>
	<span id="item-356">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/11/podcast-72-el-neogicio-del-dns.mp3" title="Podcast #72: El negocio del DNS">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #72: El negocio del DNS</span>
		</a>
	</span>
</li>
<li>
	<span id="item-357">
		<a href="#" data-media="http://www.ivoox.com/episodio-13-evolucion-java_mf_22358349_feed_1.mp3" title="Episodio 13 - Evolución de Java">
			<span class="isplaying"></span>
			<span class="logo programaresunamierda"></span>
			<span class="podcast">Programar es una mierda</span>
			<span class="track">Episodio 13 - Evolución de Java</span>
		</a>
	</span>
</li>
<li>
	<span id="item-358">
		<a href="#" data-media="https://www.ivoox.com/episodio-13-evolucion-java_mf_22358349_feed_1.mp3" title="Episodio 13 - Evolución de Java">
			<span class="isplaying"></span>
			<span class="logo programaresunamierda"></span>
			<span class="podcast">Programar es una mierda</span>
			<span class="track">Episodio 13 - Evolución de Java</span>
		</a>
	</span>
</li>
<li>
	<span id="item-359">
		<a href="#" data-media="https://anchor.fm/s/18c0860/podcast/download/65479/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fanchor-data%2Fstationexports%2Fpodcasts%2FMicr-fonos-d4811cf8e39e1.m4a" title="Micrófonos">
			<span class="isplaying"></span>
			<span class="logo tomandouncafé"></span>
			<span class="podcast">Tomando Un Café</span>
			<span class="track">Micrófonos</span>
		</a>
	</span>
</li>
<li>
	<span id="item-360">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/5a1e7a439e91b02b750550df.mp3" title="Apple inventa el 0-factor auth">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Apple inventa el 0-factor auth</span>
		</a>
	</span>
</li>
<li>
	<span id="item-361">
		<a href="#" data-media="http://api.spreaker.com/download/episode/13460368/podcast_123.mp3" title="#123 Cómo crear tu propia PCB con Gustavo Reynaga">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">#123 Cómo crear tu propia PCB con Gustavo Reynaga</span>
		</a>
	</span>
</li>
<li>
	<span id="item-362">
		<a href="#" data-media="https://anchor.fm/s/18c0860/podcast/download/64856/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fanchor-data%2Fstationexports%2Fpodcasts%2FTomando-Un-Caf--06-552664f583be5.m4a" title="Tomando Un Café 06">
			<span class="isplaying"></span>
			<span class="logo tomandouncafé"></span>
			<span class="podcast">Tomando Un Café</span>
			<span class="track">Tomando Un Café 06</span>
		</a>
	</span>
</li>
<li>
	<span id="item-363">
		<a href="#" data-media="https://gitlab.com/podcastlinux/podcastlinux.gitlab.io/raw/master/Linux-Express/29linuxexpress.mp3" title="#29 Linux Express">
			<span class="isplaying"></span>
			<span class="logo linuxexpressdepodcastlinux"></span>
			<span class="podcast">Linux Express, de Podcast Linux.</span>
			<span class="track">#29 Linux Express</span>
		</a>
	</span>
</li>
<li>
	<span id="item-364">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/11/podcast-71-lacp.mp3" title="Podcast #71: LACP">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #71: LACP</span>
		</a>
	</span>
</li>
<li>
	<span id="item-365">
		<a href="#" data-media="http://feedproxy.google.com/~r/WecodesignPodcast/~5/M_PCX-RHV4Q/WeCodeSign%202x12%20-%20El%20Valor%20del%20Disen%CC%83o.mp3" title="2x12 - El valor del diseño">
			<span class="isplaying"></span>
			<span class="logo wecodesignpodcast"></span>
			<span class="podcast">WeCodeSign Podcast</span>
			<span class="track">2x12 - El valor del diseño</span>
		</a>
	</span>
</li>
<li>
	<span id="item-366">
		<a href="#" data-media="http://api.spreaker.com/download/episode/13454096/webreactiva_podcast_11.mp3" title="WR 11: Alternativas a WordPress. ¿Hay alguien ahí fuera?">
			<span class="isplaying"></span>
			<span class="logo webreactiva"></span>
			<span class="podcast">Web Reactiva</span>
			<span class="track">WR 11: Alternativas a WordPress. ¿Hay alguien ahí fuera?</span>
		</a>
	</span>
</li>
<li>
	<span id="item-367">
		<a href="#" data-media="http://www.ivoox.com/code-time-94-es-recomendable-usar-interface-builder_mf_22317236_feed_1.mp3" title="Code Time (94) ¿Es recomendable usar Interface Builder? Pt 3">
			<span class="isplaying"></span>
			<span class="logo codetime"></span>
			<span class="podcast">Code Time</span>
			<span class="track">Code Time (94) ¿Es recomendable usar Interface Builder? Pt 3</span>
		</a>
	</span>
</li>
<li>
	<span id="item-368">
		<a href="#" data-media="http://ia601503.us.archive.org/30/items/NolegaltechRadio/004-nolegaltechradio-githubLegal.mp3" title="#004-Github legal">
			<span class="isplaying"></span>
			<span class="logo nolegaltechradio"></span>
			<span class="podcast">NOlegaltech Radio</span>
			<span class="track">#004-Github legal</span>
		</a>
	</span>
</li>
<li>
	<span id="item-369">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/5a1d08d59e91b02b750524e0.mp3" title="Los elfos subcontratados de Papa Noel">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Los elfos subcontratados de Papa Noel</span>
		</a>
	</span>
</li>
<li>
	<span id="item-370">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/11/podcast-70-mi-web-no-tiene-candado-verde.mp3" title="Podcast #70: He instalado un certificado y mi web no muestra el candado verde">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #70: He instalado un certificado y mi web no muestra el candado verde</span>
		</a>
	</span>
</li>
<li>
	<span id="item-371">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/7539793/Bat2x100_167.m4a" title="#167 – Empieza la Navidad">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#167 – Empieza la Navidad</span>
		</a>
	</span>
</li>
<li>
	<span id="item-372">
		<a href="#" data-media="http://api.spreaker.com/download/episode/13441900/el_mito_de_la_juventud.mp3" title="El mito de la juventud = expertos en tecnología">
			<span class="isplaying"></span>
			<span class="logo deknet"></span>
			<span class="podcast">DekNet</span>
			<span class="track">El mito de la juventud = expertos en tecnología</span>
		</a>
	</span>
</li>
<li>
	<span id="item-373">
		<a href="#" data-media="http://www.ivoox.com/neositelinux-podcast-2017-8-ultimo-episodio_mf_22303078_feed_1.mp3" title="NeoSiteLinux Podcast 2017 - #8 - Ultimo episodio de la temporada">
			<span class="isplaying"></span>
			<span class="logo neositelinuxpodcast"></span>
			<span class="podcast">NeoSiteLinux Podcast</span>
			<span class="track">NeoSiteLinux Podcast 2017 - #8 - Ultimo episodio de la temporada</span>
		</a>
	</span>
</li>
<li>
	<span id="item-374">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/5a1bbb0b9e91b02b7504fa81.mp3" title="Hablemos de estadísticas: Facebook, Spotify y Pokémon Go">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Hablemos de estadísticas: Facebook, Spotify y Pokémon Go</span>
		</a>
	</span>
</li>
<li>
	<span id="item-375">
		<a href="#" data-media="http://www.ivoox.com/31-neutralidad-red-las-grandes-tecnologicas_mf_22291805_feed_1.mp3" title="31. Neutralidad de la red. Las grandes tecnológicas están matando internet y la innovación">
			<span class="isplaying"></span>
			<span class="logo naserospodcast"></span>
			<span class="podcast">NASeros Podcast</span>
			<span class="track">31. Neutralidad de la red. Las grandes tecnológicas están matando internet y la innovación</span>
		</a>
	</span>
</li>
<li>
	<span id="item-376">
		<a href="#" data-media="http://tracking.feedpress.it/link/16349/7528976/DT_E10.mp3" title="#10 Tiendas online">
			<span class="isplaying"></span>
			<span class="logo droidtalks"></span>
			<span class="podcast">Droid Talks</span>
			<span class="track">#10 Tiendas online</span>
		</a>
	</span>
</li>
<li>
	<span id="item-377">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/11/podcast-69-monitorizar-carga-web-desde-un-terminal.mp3" title="Podcast #69: Monitorizar carga de una web desde un terminal">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #69: Monitorizar carga de una web desde un terminal</span>
		</a>
	</span>
</li>
<li>
	<span id="item-378">
		<a href="#" data-media="http://www.ivoox.com/163-paypal-al-mover-dinero-no-te-emociones_mf_22283488_feed_1.mp3" title="#163 Paypal: Al mover dinero no te emociones, ojo con las comisiones">
			<span class="isplaying"></span>
			<span class="logo salmorejogeek"></span>
			<span class="podcast">Salmorejo Geek</span>
			<span class="track">#163 Paypal: Al mover dinero no te emociones, ojo con las comisiones</span>
		</a>
	</span>
</li>
<li>
	<span id="item-379">
		<a href="#" data-media="https://www.ivoox.com/s02e02-material-educativo-cuota-6-91-firefox-57_mf_22280032_feed_1.mp3" title="S02E02 Material educativo, cuota 6,91% y Firefox 57">
			<span class="isplaying"></span>
			<span class="logo ubuntuyotrashierbas"></span>
			<span class="podcast">Ubuntu y otras hierbas</span>
			<span class="track">S02E02 Material educativo, cuota 6,91% y Firefox 57</span>
		</a>
	</span>
</li>
<li>
	<span id="item-380">
		<a href="#" data-media="http://api.spreaker.com/download/episode/13424190/linustorvalds.mp3" title="Linus Torvalds contra la industria de la inseguridad">
			<span class="isplaying"></span>
			<span class="logo deknet"></span>
			<span class="podcast">DekNet</span>
			<span class="track">Linus Torvalds contra la industria de la inseguridad</span>
		</a>
	</span>
</li>
<li>
	<span id="item-381">
		<a href="#" data-media="http://traffic.libsyn.com/cesargarciasaez/LHM135.mp3" title="LHM135 – Preguntas y Proyectos con David Cuartielles (Noviembre 2017)">
			<span class="isplaying"></span>
			<span class="logo lahoramaker"></span>
			<span class="podcast">La Hora Maker</span>
			<span class="track">LHM135 – Preguntas y Proyectos con David Cuartielles (Noviembre 2017)</span>
		</a>
	</span>
</li>
<li>
	<span id="item-382">
		<a href="#" data-media="http://mundipad.es/capitulos-podcast-bemoob/095-foromoviles-podcast.mp3" title="ForoMoviles Podcast 095: Especial Black Friday">
			<span class="isplaying"></span>
			<span class="logo podcastforomóviles"></span>
			<span class="podcast">Podcast – ForoMóviles</span>
			<span class="track">ForoMoviles Podcast 095: Especial Black Friday</span>
		</a>
	</span>
</li>
<li>
	<span id="item-383">
		<a href="#" data-media="http://podcast.edyo.es/podcast/edyo-32.mp3" title="EDyO 32 - Infraestructura como código (IaC)">
			<span class="isplaying"></span>
			<span class="logo entredevyopspodcast"></span>
			<span class="podcast">EntreDevYOps Podcast</span>
			<span class="track">EDyO 32 - Infraestructura como código (IaC)</span>
		</a>
	</span>
</li>
<li>
	<span id="item-384">
		<a href="#" data-media="https://anchor.fm/s/18c0860/podcast/download/62427/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fanchor-data%2Fstationexports%2Fpodcasts%2FOrganizando-cables-2f2fdf7bc3321.m4a" title="Organizando cables">
			<span class="isplaying"></span>
			<span class="logo tomandouncafé"></span>
			<span class="podcast">Tomando Un Café</span>
			<span class="track">Organizando cables</span>
		</a>
	</span>
</li>
<li>
	<span id="item-385">
		<a href="#" data-media="http://www.ivoox.com/retroactivo-podcast-70-3dfx_mf_22270214_feed_1.mp3" title="RetroActivo Podcast #70: 3Dfx">
			<span class="isplaying"></span>
			<span class="logo retroactivopodcast"></span>
			<span class="podcast">RetroActivo Podcast</span>
			<span class="track">RetroActivo Podcast #70: 3Dfx</span>
		</a>
	</span>
</li>
<li>
	<span id="item-386">
		<a href="#" data-media="http://traffic.libsyn.com/cesargarciasaez/LHM134.mp3" title="LHM134 – Consejos para lanzar tu crowdfunding maker con Victor Barahona">
			<span class="isplaying"></span>
			<span class="logo lahoramaker"></span>
			<span class="podcast">La Hora Maker</span>
			<span class="track">LHM134 – Consejos para lanzar tu crowdfunding maker con Victor Barahona</span>
		</a>
	</span>
</li>
<li>
	<span id="item-387">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/7504383/Bat2x100_166.m4a" title="#166 – Viernes Negro y sorpresita….">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#166 – Viernes Negro y sorpresita….</span>
		</a>
	</span>
</li>
<li>
	<span id="item-388">
		<a href="#" data-media="http://www.ivoox.com/retroactivo-69-id-software-parte-ii_mf_22256980_feed_1.mp3" title="RetroActivo #69: Id Software - Parte II">
			<span class="isplaying"></span>
			<span class="logo retroactivopodcast"></span>
			<span class="podcast">RetroActivo Podcast</span>
			<span class="track">RetroActivo #69: Id Software - Parte II</span>
		</a>
	</span>
</li>
<li>
	<span id="item-389">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/5a17c5279e91b02b7504b0d3.mp3" title="El capitalismo sociópata de Silicon Valley">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">El capitalismo sociópata de Silicon Valley</span>
		</a>
	</span>
</li>
<li>
	<span id="item-390">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/11/podcast-68-sobre-dominios.mp3" title="Podcast #68: Sobre dominios">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #68: Sobre dominios</span>
		</a>
	</span>
</li>
<li>
	<span id="item-391">
		<a href="#" data-media="https://ar.ivoox.com/es/ep138-especial-inteligencia-artificial-redes-neuronales-la-singularidad_mf_22246089_feed_1.mp3" title="Ep138: Especial Inteligencia Artificial: Redes Neuronales; La Singularidad; Posthumanismo">
			<span class="isplaying"></span>
			<span class="logo coffeebreakseñalyruido"></span>
			<span class="podcast">Coffee Break: Señal y Ruido</span>
			<span class="track">Ep138: Especial Inteligencia Artificial: Redes Neuronales; La Singularidad; Posthumanismo</span>
		</a>
	</span>
</li>
<li>
	<span id="item-392">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/5a16ba889e91b02b75048aa5.mp3" title="Esto no es serio, YouTube">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Esto no es serio, YouTube</span>
		</a>
	</span>
</li>
<li>
	<span id="item-393">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/7493809/Bat2x100_165.m4a" title="#165 – Noticias varias ! (Ofertas Black Friday)">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#165 – Noticias varias ! (Ofertas Black Friday)</span>
		</a>
	</span>
</li>
<li>
	<span id="item-394">
		<a href="#" data-media="http://www.ivoox.com/code-time-93-es-recomendable-usar-interface-builder_mf_22240778_feed_1.mp3" title="Code Time (93) ¿Es recomendable usar Interface Builder? Pt 2">
			<span class="isplaying"></span>
			<span class="logo codetime"></span>
			<span class="podcast">Code Time</span>
			<span class="track">Code Time (93) ¿Es recomendable usar Interface Builder? Pt 2</span>
		</a>
	</span>
</li>
<li>
	<span id="item-395">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/11/podcast-67-impresspages.mp3" title="Podcast #67: ImpressPages">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #67: ImpressPages</span>
		</a>
	</span>
</li>
<li>
	<span id="item-396">
		<a href="#" data-media="http://www.ivoox.com/39-gnu-linux-moviles_mf_22214993_feed_1.mp3" title="#39 GNU/Linux y Móviles">
			<span class="isplaying"></span>
			<span class="logo podcastlinux"></span>
			<span class="podcast">Podcast Linux</span>
			<span class="track">#39 GNU/Linux y Móviles</span>
		</a>
	</span>
</li>
<li>
	<span id="item-397">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/5a1528029e91b02b75045999.mp3" title="Espionajes, evasiones y estudiantes trabajando horas extra">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Espionajes, evasiones y estudiantes trabajando horas extra</span>
		</a>
	</span>
</li>
<li>
	<span id="item-398">
		<a href="#" data-media="https://deployando.me/podcast-download/191/23-rancheros.mp3" title="23 – RancherOS">
			<span class="isplaying"></span>
			<span class="logo deployandome"></span>
			<span class="podcast">deployando.me</span>
			<span class="track">23 – RancherOS</span>
		</a>
	</span>
</li>
<li>
	<span id="item-399">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/11/podcast-66-medicion-del-ancho-de-banda.mp3" title="Podcast #66: Medición del ancho de banda">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #66: Medición del ancho de banda</span>
		</a>
	</span>
</li>
<li>
	<span id="item-400">
		<a href="#" data-media="https://anchor.fm/s/18c0860/podcast/download/60964/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fanchor-data%2Fstationexports%2Fpodcasts%2FRaspberry-ea912a99ca103.m4a" title="Raspberry">
			<span class="isplaying"></span>
			<span class="logo tomandouncafé"></span>
			<span class="podcast">Tomando Un Café</span>
			<span class="track">Raspberry</span>
		</a>
	</span>
</li>
<li>
	<span id="item-401">
		<a href="#" data-media="http://feedproxy.google.com/~r/Vaciatubandeja/~5/GZTKQ6dADR8/6622241.mp3" title="13: Aprendizaje | ¿Sabes en que fase estás?">
			<span class="isplaying"></span>
			<span class="logo vacíatubandeja"></span>
			<span class="podcast">Vacía tu bandeja</span>
			<span class="track">13: Aprendizaje | ¿Sabes en que fase estás?</span>
		</a>
	</span>
</li>
<li>
	<span id="item-402">
		<a href="#" data-media="https://anchor.fm/s/18c0860/podcast/download/60780/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fanchor-data%2Fstationexports%2Fpodcasts%2F21-nov--2017-2944addd0e63f.m4a" title="21 nov. 2017">
			<span class="isplaying"></span>
			<span class="logo tomandouncafé"></span>
			<span class="podcast">Tomando Un Café</span>
			<span class="track">21 nov. 2017</span>
		</a>
	</span>
</li>
<li>
	<span id="item-403">
		<a href="#" data-media="https://anchor.fm/s/18c0860/podcast/download/60775/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fanchor-data%2Fstationexports%2Fpodcasts%2F21-nov--2017-de2c55fe8c78b.m4a" title="DietPi">
			<span class="isplaying"></span>
			<span class="logo tomandouncafé"></span>
			<span class="podcast">Tomando Un Café</span>
			<span class="track">DietPi</span>
		</a>
	</span>
</li>
<li>
	<span id="item-404">
		<a href="#" data-media="http://api.spreaker.com/download/episode/13383382/webreactiva_podcast_10.mp3" title="WR 10: Los mejores podcast de programación y tecnología (o casi)">
			<span class="isplaying"></span>
			<span class="logo webreactiva"></span>
			<span class="podcast">Web Reactiva</span>
			<span class="track">WR 10: Los mejores podcast de programación y tecnología (o casi)</span>
		</a>
	</span>
</li>
<li>
	<span id="item-405">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/7473115/Bat2x100_164.m4a" title="#164 – Bundles, Black Friday & Gestores Contraseñas (otra vez)">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#164 – Bundles, Black Friday & Gestores Contraseñas (otra vez)</span>
		</a>
	</span>
</li>
<li>
	<span id="item-406">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/11/podcast-65-tiendas-online-autogestionadas.mp3" title="Podcast #65: Tiendas online autogestionadas">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #65: Tiendas online autogestionadas</span>
		</a>
	</span>
</li>
<li>
	<span id="item-407">
		<a href="#" data-media="http://www.ivoox.com/script-time-crear-programas-sin-saber-programacion_mf_22186414_feed_1.mp3" title="Script Time: Crear programas sin saber programación">
			<span class="isplaying"></span>
			<span class="logo codetime"></span>
			<span class="podcast">Code Time</span>
			<span class="track">Script Time: Crear programas sin saber programación</span>
		</a>
	</span>
</li>
<li>
	<span id="item-408">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/5a138f2e6df7fd2b59f036b3.mp3" title="Uber se acerca a su Objetivo Final (â„¢)">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Uber se acerca a su Objetivo Final (â„¢)</span>
		</a>
	</span>
</li>
<li>
	<span id="item-409">
		<a href="#" data-media="http://feedproxy.google.com/~r/Vaciatubandeja/~5/MdE9PF5EHUg/13-Aprendizaje-En%20que%20fase%20estas.mp3" title="#13-Aprendizaje: ¿Sabes en que fase estás?">
			<span class="isplaying"></span>
			<span class="logo vaciatubandeja"></span>
			<span class="podcast">Vacia Tu Bandeja</span>
			<span class="track">#13-Aprendizaje: ¿Sabes en que fase estás?</span>
		</a>
	</span>
</li>
<li>
	<span id="item-410">
		<a href="#" data-media="http://api.spreaker.com/download/episode/13378854/macos_divertido_2.mp3" title="MacOS geek y AC/DC">
			<span class="isplaying"></span>
			<span class="logo deknet"></span>
			<span class="podcast">DekNet</span>
			<span class="track">MacOS geek y AC/DC</span>
		</a>
	</span>
</li>
<li>
	<span id="item-411">
		<a href="#" data-media="https://anchor.fm/s/18c0860/podcast/download/60316/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fanchor-data%2Fstationexports%2Fpodcasts%2FTomando-un-caf--03-64d0e7d0c93c.m4a" title="Lista de deseo para Telegram">
			<span class="isplaying"></span>
			<span class="logo tomandouncafé"></span>
			<span class="podcast">Tomando Un Café</span>
			<span class="track">Lista de deseo para Telegram</span>
		</a>
	</span>
</li>
<li>
	<span id="item-412">
		<a href="#" data-media="http://compilando.audio/wp-content/uploads/2017/11/podcast17.mp3" title="Podcast 17 – Robótica libre con Obijuan y Cumpleaños de Android">
			<span class="isplaying"></span>
			<span class="logo compilandopodcast"></span>
			<span class="podcast">Compilando Podcast</span>
			<span class="track">Podcast 17 – Robótica libre con Obijuan y Cumpleaños de Android</span>
		</a>
	</span>
</li>
<li>
	<span id="item-413">
		<a href="#" data-media="http://api.spreaker.com/download/episode/13374247/cap35_dispositivo_u_nico_respuesto_a_converso72.mp3" title="cap35 - Dispositivo único, respuesta a @converso72">
			<span class="isplaying"></span>
			<span class="logo podcastdmanuelalonso"></span>
			<span class="podcast">Podcast dmanuelalonso</span>
			<span class="track">cap35 - Dispositivo único, respuesta a @converso72</span>
		</a>
	</span>
</li>
<li>
	<span id="item-414">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/5a12a23f6df7fd2b59f019f5.mp3" title="Los sueños rotos del libro electrónico">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Los sueños rotos del libro electrónico</span>
		</a>
	</span>
</li>
<li>
	<span id="item-415">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/11/podcast-64-migracion-a-firefox-quantum.mp3" title="Podcast #64: Migración a Firefox Quantum">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #64: Migración a Firefox Quantum</span>
		</a>
	</span>
</li>
<li>
	<span id="item-416">
		<a href="#" data-media="https://anchor.fm/s/18c0860/podcast/download/59733/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fanchor-data%2Fstationexports%2Fpodcasts%2FReflexi-n-sobre-Telegram-f07297e0fee5.m4a" title="Reflexión sobre Telegram">
			<span class="isplaying"></span>
			<span class="logo tomandouncafé"></span>
			<span class="podcast">Tomando Un Café</span>
			<span class="track">Reflexión sobre Telegram</span>
		</a>
	</span>
</li>
<li>
	<span id="item-417">
		<a href="#" data-media="http://www.ivoox.com/intel-amd-windows-linux-android_mf_22160116_feed_1.mp3" title="Intel y Amd. Windows y Linux en Android. Chromebooks">
			<span class="isplaying"></span>
			<span class="logo mosqueterowebtecnologialinuxchromebooks"></span>
			<span class="podcast">Mosqueteroweb tecnologia, Linux, Chromebooks</span>
			<span class="track">Intel y Amd. Windows y Linux en Android. Chromebooks</span>
		</a>
	</span>
</li>
<li>
	<span id="item-418">
		<a href="#" data-media="https://archive.org/download/40ElPodcastHerramientaDidacticaEnElAula/40-el-podcast-herramienta-didactica-en-el-aula.mp3" title="#40 El Podcast como herramienta didáctica en el aula de Educación Primaria">
			<span class="isplaying"></span>
			<span class="logo educandogeek"></span>
			<span class="podcast">eDucando Geek</span>
			<span class="track">#40 El Podcast como herramienta didáctica en el aula de Educación Primaria</span>
		</a>
	</span>
</li>
<li>
	<span id="item-419">
		<a href="#" data-media="http://traffic.libsyn.com/cesargarciasaez/LHM130.mp3" title="LHM130 – Cómo crear comunidad – Comentarios a la entrevista a Cole de Luis del Valle">
			<span class="isplaying"></span>
			<span class="logo lahoramaker"></span>
			<span class="podcast">La Hora Maker</span>
			<span class="track">LHM130 – Cómo crear comunidad – Comentarios a la entrevista a Cole de Luis del Valle</span>
		</a>
	</span>
</li>
<li>
	<span id="item-420">
		<a href="#" data-media="http://www.ivoox.com/mintablet-medios-pago-round-2-con_mf_22148114_feed_1.mp3" title="mintablet - Medios de pago Round 2 (con Treki23)">
			<span class="isplaying"></span>
			<span class="logo podcastwintabletinfo"></span>
			<span class="podcast">Podcast WINTABLET.INFO</span>
			<span class="track">mintablet - Medios de pago Round 2 (con Treki23)</span>
		</a>
	</span>
</li>
<li>
	<span id="item-421">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/7430026/Bat2x100_163.m4a" title="#163 – 2FA / 2FV – Generando inseguridad, sin querer !">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#163 – 2FA / 2FV – Generando inseguridad, sin querer !</span>
		</a>
	</span>
</li>
<li>
	<span id="item-422">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/5a0eb0576df7fd2b59efc91a.mp3" title="Un One More Thing bien hecho">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Un One More Thing bien hecho</span>
		</a>
	</span>
</li>
<li>
	<span id="item-423">
		<a href="#" data-media="http://www.ivoox.com/black-friday-cap-80_mf_22125364_feed_1.mp3" title="Black Friday - Cap 80">
			<span class="isplaying"></span>
			<span class="logo podcastwintabletinfo"></span>
			<span class="podcast">Podcast WINTABLET.INFO</span>
			<span class="track">Black Friday - Cap 80</span>
		</a>
	</span>
</li>
<li>
	<span id="item-424">
		<a href="#" data-media="https://ar.ivoox.com/es/ep137-la-nueva-exotierra-ross-128b-cosmologia-exotica_mf_22120374_feed_1.mp3" title="Ep137: La Nueva Exotierra Ross 128b; Cosmología Exótica; Grupos Matemáticos; La Supernova que No Cesa">
			<span class="isplaying"></span>
			<span class="logo coffeebreakseñalyruido"></span>
			<span class="podcast">Coffee Break: Señal y Ruido</span>
			<span class="track">Ep137: La Nueva Exotierra Ross 128b; Cosmología Exótica; Grupos Matemáticos; La Supernova que No Cesa</span>
		</a>
	</span>
</li>
<li>
	<span id="item-425">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/5a0dce3d6df7fd2b59efab2a.mp3" title="Kernel: Google tiene mucho poder, ¿es hora de romper?">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Kernel: Google tiene mucho poder, ¿es hora de romper?</span>
		</a>
	</span>
</li>
<li>
	<span id="item-426">
		<a href="#" data-media="http://traffic.libsyn.com/cesargarciasaez/LHM128.mp3" title="LHM128 – Las cinco disfunciones de un equipo">
			<span class="isplaying"></span>
			<span class="logo lahoramaker"></span>
			<span class="podcast">La Hora Maker</span>
			<span class="track">LHM128 – Las cinco disfunciones de un equipo</span>
		</a>
	</span>
</li>
<li>
	<span id="item-427">
		<a href="#" data-media="http://www.ivoox.com/episodio-12-la-comunidad-open-source-sakai_mf_22114250_feed_1.mp3" title="Episodio 12 - La comunidad open source Sakai">
			<span class="isplaying"></span>
			<span class="logo programaresunamierda"></span>
			<span class="podcast">Programar es una mierda</span>
			<span class="track">Episodio 12 - La comunidad open source Sakai</span>
		</a>
	</span>
</li>
<li>
	<span id="item-428">
		<a href="#" data-media="https://www.ivoox.com/episodio-12-la-comunidad-open-source-sakai_mf_22114250_feed_1.mp3" title="Episodio 12 - La comunidad open source Sakai">
			<span class="isplaying"></span>
			<span class="logo programaresunamierda"></span>
			<span class="podcast">Programar es una mierda</span>
			<span class="track">Episodio 12 - La comunidad open source Sakai</span>
		</a>
	</span>
</li>
<li>
	<span id="item-429">
		<a href="#" data-media="http://www.ivoox.com/cesta-tecnologica-sorteo-recaudacion-benefica_mf_22109813_feed_1.mp3" title="Cesta Tecnologica Sorteo y recaudación benéfica">
			<span class="isplaying"></span>
			<span class="logo mosqueterowebtecnologialinuxchromebooks"></span>
			<span class="podcast">Mosqueteroweb tecnologia, Linux, Chromebooks</span>
			<span class="track">Cesta Tecnologica Sorteo y recaudación benéfica</span>
		</a>
	</span>
</li>
<li>
	<span id="item-430">
		<a href="#" data-media="http://www.ivoox.com/024-los-niveles-altitud-gtd_mf_22094466_feed_1.mp3" title="024 - Los niveles de altitud en GTD">
			<span class="isplaying"></span>
			<span class="logo aprendiendogtdpodcastproductividad"></span>
			<span class="podcast">Aprendiendo GTD podcast productividad</span>
			<span class="track">024 - Los niveles de altitud en GTD</span>
		</a>
	</span>
</li>
<li>
	<span id="item-431">
		<a href="#" data-media="http://traffic.libsyn.com/cesargarciasaez/LHM127.mp3" title="LHM127 – TechShop, la gran cadena de espacios de fabricación digital, cierra sus puertas">
			<span class="isplaying"></span>
			<span class="logo lahoramaker"></span>
			<span class="podcast">La Hora Maker</span>
			<span class="track">LHM127 – TechShop, la gran cadena de espacios de fabricación digital, cierra sus puertas</span>
		</a>
	</span>
</li>
<li>
	<span id="item-432">
		<a href="#" data-media="http://www.ivoox.com/04x02-novedades-plasma-mobile-purism_mf_22090356_feed_1.mp3" title="04x02 Novedades de Plasma Mobile y Purism">
			<span class="isplaying"></span>
			<span class="logo podcastdekdeespaña"></span>
			<span class="podcast">Podcast de KDE España</span>
			<span class="track">04x02 Novedades de Plasma Mobile y Purism</span>
		</a>
	</span>
</li>
<li>
	<span id="item-433">
		<a href="#" data-media="http://www.ivoox.com/04x01-desmontando-kde-05-maraton-linuxero_mf_22090166_feed_1.mp3" title="04x01 Desmontando KDE - 05 Maraton linuxero">
			<span class="isplaying"></span>
			<span class="logo podcastdekdeespaña"></span>
			<span class="podcast">Podcast de KDE España</span>
			<span class="track">04x01 Desmontando KDE - 05 Maraton linuxero</span>
		</a>
	</span>
</li>
<li>
	<span id="item-434">
		<a href="#" data-media="http://api.spreaker.com/download/episode/13329246/cap34_android_vs_iphone.mp3" title="cap34 - Android vs iPhone">
			<span class="isplaying"></span>
			<span class="logo podcastdmanuelalonso"></span>
			<span class="podcast">Podcast dmanuelalonso</span>
			<span class="track">cap34 - Android vs iPhone</span>
		</a>
	</span>
</li>
<li>
	<span id="item-435">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/5a0be47e6df7fd2b59ef8fdc.mp3" title="Las 'sorpresas' de Facebook: opiáceos, Trump, Brexit...">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Las 'sorpresas' de Facebook: opiáceos, Trump, Brexit...</span>
		</a>
	</span>
</li>
<li>
	<span id="item-436">
		<a href="#" data-media="https://gitlab.com/podcastlinux/podcastlinux.gitlab.io/raw/master/Linux-Express/28linuxexpress.mp3" title="#28 Linux Express">
			<span class="isplaying"></span>
			<span class="logo linuxexpressdepodcastlinux"></span>
			<span class="podcast">Linux Express, de Podcast Linux.</span>
			<span class="track">#28 Linux Express</span>
		</a>
	</span>
</li>
<li>
	<span id="item-437">
		<a href="#" data-media="http://feedproxy.google.com/~r/WecodesignPodcast/~5/3f9QrycBo9E/WeCodeSign%202x11%20-%20El%20ecosistema%20de%20React.mp3" title="2x11 - El ecosistema de React">
			<span class="isplaying"></span>
			<span class="logo wecodesignpodcast"></span>
			<span class="podcast">WeCodeSign Podcast</span>
			<span class="track">2x11 - El ecosistema de React</span>
		</a>
	</span>
</li>
<li>
	<span id="item-438">
		<a href="#" data-media="http://api.spreaker.com/download/episode/13319600/webreactiva_podcast_09.mp3" title="WR 9: Contenido enriquecido HTML5 con H5P">
			<span class="isplaying"></span>
			<span class="logo webreactiva"></span>
			<span class="podcast">Web Reactiva</span>
			<span class="track">WR 9: Contenido enriquecido HTML5 con H5P</span>
		</a>
	</span>
</li>
<li>
	<span id="item-439">
		<a href="#" data-media="http://www.ivoox.com/code-time-92-es-recomendable-usar-interface-builder_mf_22053295_feed_1.mp3" title="Code Time (92) ¿Es recomendable usar Interface Builder?">
			<span class="isplaying"></span>
			<span class="logo codetime"></span>
			<span class="podcast">Code Time</span>
			<span class="track">Code Time (92) ¿Es recomendable usar Interface Builder?</span>
		</a>
	</span>
</li>
<li>
	<span id="item-440">
		<a href="#" data-media="http://www.ivoox.com/30-tipos-formatos-discos-ssd-m2_mf_22051973_feed_1.mp3" title="30. Tipos y formatos de discos SSD M2, PCIe y NVMe">
			<span class="isplaying"></span>
			<span class="logo naserospodcast"></span>
			<span class="podcast">NASeros Podcast</span>
			<span class="track">30. Tipos y formatos de discos SSD M2, PCIe y NVMe</span>
		</a>
	</span>
</li>
<li>
	<span id="item-441">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/5a0a93b26df7fd2b59ef78da.mp3" title="Reddit saldrá a bolsa">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Reddit saldrá a bolsa</span>
		</a>
	</span>
</li>
<li>
	<span id="item-442">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/11/podcast-63-autogestion-de-la-informacion.mp3" title="Podcast #63: Autogestión de la información">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #63: Autogestión de la información</span>
		</a>
	</span>
</li>
<li>
	<span id="item-443">
		<a href="#" data-media="http://api.spreaker.com/download/episode/13317462/deknet_20171114_0330.mp3" title="BotNet Mirai, ¿otra trola de la inseguridad?">
			<span class="isplaying"></span>
			<span class="logo deknet"></span>
			<span class="podcast">DekNet</span>
			<span class="track">BotNet Mirai, ¿otra trola de la inseguridad?</span>
		</a>
	</span>
</li>
<li>
	<span id="item-444">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/Ep112.mp3" title="Mega-Terremotos, Volcanes y Cambio Climático [Ep.112]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Mega-Terremotos, Volcanes y Cambio Climático [Ep.112]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-445">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/5a0945cb6df7fd2b59ef636e.mp3" title="Escuchando podcasts a velocidades inhumanas">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Escuchando podcasts a velocidades inhumanas</span>
		</a>
	</span>
</li>
<li>
	<span id="item-446">
		<a href="#" data-media="http://www.ivoox.com/visualizacion-datos-gnu-linux-como-hacer-figuras_mf_22026855_feed_1.mp3" title="Visualización de Datos en GNU/Linux. Cómo hacer figuras profesionales">
			<span class="isplaying"></span>
			<span class="logo procrastinaciónycafé"></span>
			<span class="podcast">Procrastinación y Café</span>
			<span class="track">Visualización de Datos en GNU/Linux. Cómo hacer figuras profesionales</span>
		</a>
	</span>
</li>
<li>
	<span id="item-447">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/11/podcast-62-seguridad-en-aplicaciones-web.mp3" title="Podcast #62: Seguridad en Aplicaciones Web con Sergio R. Solís">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #62: Seguridad en Aplicaciones Web con Sergio R. Solís</span>
		</a>
	</span>
</li>
<li>
	<span id="item-448">
		<a href="#" data-media="http://traffic.libsyn.com/cesargarciasaez/LHM124.mp3" title="LHM124 – Proyectos juveniles con tecnologías libres en OSHWDEM 2017">
			<span class="isplaying"></span>
			<span class="logo lahoramaker"></span>
			<span class="podcast">La Hora Maker</span>
			<span class="track">LHM124 – Proyectos juveniles con tecnologías libres en OSHWDEM 2017</span>
		</a>
	</span>
</li>
<li>
	<span id="item-449">
		<a href="#" data-media="http://traffic.libsyn.com/cesargarciasaez/LHM123.mp3" title="LHM123 – ¿Cuál es la importancia de las tecnologías libres? Exploramos esta cuestión preguntando a los expositores de OSHWDEM 2017">
			<span class="isplaying"></span>
			<span class="logo lahoramaker"></span>
			<span class="podcast">La Hora Maker</span>
			<span class="track">LHM123 – ¿Cuál es la importancia de las tecnologías libres? Exploramos esta cuestión preguntando a los expositores de OSHWDEM 2017</span>
		</a>
	</span>
</li>
<li>
	<span id="item-450">
		<a href="#" data-media="http://compilando.audio/wp-content/uploads/2017/11/podcast16.mp3" title="Podcast 16 – Resumen LibreCon 2017 y Crossover NoLegalTech Radio">
			<span class="isplaying"></span>
			<span class="logo compilandopodcast"></span>
			<span class="podcast">Compilando Podcast</span>
			<span class="track">Podcast 16 – Resumen LibreCon 2017 y Crossover NoLegalTech Radio</span>
		</a>
	</span>
</li>
<li>
	<span id="item-451">
		<a href="#" data-media="http://api.spreaker.com/download/episode/13299546/oshwdem_directo_gustavo_reynaga.mp3" title="#OSHWDem directo Gustavo Reynaga">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">#OSHWDem directo Gustavo Reynaga</span>
		</a>
	</span>
</li>
<li>
	<span id="item-452">
		<a href="#" data-media="http://api.spreaker.com/download/episode/13298641/oshwdem_en_directo.mp3" title="#OSHWDem en directo">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">#OSHWDem en directo</span>
		</a>
	</span>
</li>
<li>
	<span id="item-453">
		<a href="#" data-media="http://ia801503.us.archive.org/30/items/NolegaltechRadio/CrossoverEntrecompilanpodcastYNolegatechRadio.mp3" title="Crossover entre @CompilanPodcast y NOlegatech Radio">
			<span class="isplaying"></span>
			<span class="logo nolegaltechradio"></span>
			<span class="podcast">NOlegaltech Radio</span>
			<span class="track">Crossover entre @CompilanPodcast y NOlegatech Radio</span>
		</a>
	</span>
</li>
<li>
	<span id="item-454">
		<a href="#" data-media="http://www.ivoox.com/off-topic-acoso-abuso-sexual-banalizacion_mf_22006102_feed_1.mp3" title="Off topic: Acoso y abuso sexual. Banalización">
			<span class="isplaying"></span>
			<span class="logo mosqueterowebtecnologialinuxchromebooks"></span>
			<span class="podcast">Mosqueteroweb tecnologia, Linux, Chromebooks</span>
			<span class="track">Off topic: Acoso y abuso sexual. Banalización</span>
		</a>
	</span>
</li>
<li>
	<span id="item-455">
		<a href="#" data-media="http://traffic.libsyn.com/cesargarciasaez/LHM122.mp3" title="LHM122 – Cómo acelerar tus proyectos de hardware con Ethan Haigh de HAX">
			<span class="isplaying"></span>
			<span class="logo lahoramaker"></span>
			<span class="podcast">La Hora Maker</span>
			<span class="track">LHM122 – Cómo acelerar tus proyectos de hardware con Ethan Haigh de HAX</span>
		</a>
	</span>
</li>
<li>
	<span id="item-456">
		<a href="#" data-media="http://www.ivoox.com/neositelinux-podcast-2017-7-volviendo-a_mf_22001159_feed_1.mp3" title="NeoSiteLinux Podcast 2017 - #7 - Volviendo a las raíces">
			<span class="isplaying"></span>
			<span class="logo neositelinuxpodcast"></span>
			<span class="podcast">NeoSiteLinux Podcast</span>
			<span class="track">NeoSiteLinux Podcast 2017 - #7 - Volviendo a las raíces</span>
		</a>
	</span>
</li>
<li>
	<span id="item-457">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/5a0588e66df7fd2b59ef47e7.mp3" title="Verificaciones e inversiones">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Verificaciones e inversiones</span>
		</a>
	</span>
</li>
<li>
	<span id="item-458">
		<a href="#" data-media="http://www.ivoox.com/22-sony-a7r-iii-adobe-cc-2018_mf_21992804_feed_1.mp3" title="#22 Sony A7r III y adobe CC 2018">
			<span class="isplaying"></span>
			<span class="logo reflexpodcast"></span>
			<span class="podcast">reflex podcast</span>
			<span class="track">#22 Sony A7r III y adobe CC 2018</span>
		</a>
	</span>
</li>
<li>
	<span id="item-459">
		<a href="#" data-media="https://ar.ivoox.com/es/ep136-piramides-rayos-cosmicos-antimateria-violaciones_mf_21983348_feed_1.mp3" title="Ep136: Pirámides y Rayos Cósmicos; Antimateria y Violaciones de Simetría; Inteligencia Artificial; Encélado; Proxima Cen">
			<span class="isplaying"></span>
			<span class="logo coffeebreakseñalyruido"></span>
			<span class="podcast">Coffee Break: Señal y Ruido</span>
			<span class="track">Ep136: Pirámides y Rayos Cósmicos; Antimateria y Violaciones de Simetría; Inteligencia Artificial; Encélado; Proxima Cen</span>
		</a>
	</span>
</li>
<li>
	<span id="item-460">
		<a href="#" data-media="https://ia601506.us.archive.org/0/items/80.HRecorderPro_201711/80.H-Recorder-pro.m4a" title="080. Grabadora de Audio en Oferta">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">080. Grabadora de Audio en Oferta</span>
		</a>
	</span>
</li>
<li>
	<span id="item-461">
		<a href="#" data-media="http://www.ivoox.com/162-disponible-opcion-donaciones-para-proyectos-salmorejo_mf_21982463_feed_1.mp3" title="#162 Disponible opción donaciones para los proyectos Salmorejo Geek y Killall Radio">
			<span class="isplaying"></span>
			<span class="logo salmorejogeek"></span>
			<span class="podcast">Salmorejo Geek</span>
			<span class="track">#162 Disponible opción donaciones para los proyectos Salmorejo Geek y Killall Radio</span>
		</a>
	</span>
</li>
<li>
	<span id="item-462">
		<a href="#" data-media="http://api.spreaker.com/download/episode/13273900/imported_1510146904.mp3" title="140 + 140 = 0">
			<span class="isplaying"></span>
			<span class="logo deknet"></span>
			<span class="podcast">DekNet</span>
			<span class="track">140 + 140 = 0</span>
		</a>
	</span>
</li>
<li>
	<span id="item-463">
		<a href="#" data-media="http://www.ivoox.com/38-linux-connexion-wikimedia-espana_mf_21944072_feed_1.mp3" title="#38 Linux Connexion con Wikimedia España">
			<span class="isplaying"></span>
			<span class="logo podcastlinux"></span>
			<span class="podcast">Podcast Linux</span>
			<span class="track">#38 Linux Connexion con Wikimedia España</span>
		</a>
	</span>
</li>
<li>
	<span id="item-464">
		<a href="#" data-media="http://api.spreaker.com/download/episode/13268551/podcast122.mp3" title="#122 Curso de Arduino desde cero">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">#122 Curso de Arduino desde cero</span>
		</a>
	</span>
</li>
<li>
	<span id="item-465">
		<a href="#" data-media="https://deployando.me/podcast-download/181/22-asciinema.mp3" title="22 – asciinema">
			<span class="isplaying"></span>
			<span class="logo deployandome"></span>
			<span class="podcast">deployando.me</span>
			<span class="track">22 – asciinema</span>
		</a>
	</span>
</li>
<li>
	<span id="item-466">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/5a0275c26df7fd2b59ef25b1.mp3" title="Si es que al final... vivimos en el futuro">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Si es que al final... vivimos en el futuro</span>
		</a>
	</span>
</li>
<li>
	<span id="item-467">
		<a href="#" data-media="http://tracking.feedpress.it/link/14730/7427247/CN_Programa_028.mp3" title="#CN028 – Madrid NAS Events 2017">
			<span class="isplaying"></span>
			<span class="logo culturanas"></span>
			<span class="podcast">Cultura NAS</span>
			<span class="track">#CN028 – Madrid NAS Events 2017</span>
		</a>
	</span>
</li>
<li>
	<span id="item-468">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/Ep111_mixdown.mp3" title="Variables cataclísmicas, sistemas binarios y Observatorio Gimini [Ep.111]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Variables cataclísmicas, sistemas binarios y Observatorio Gimini [Ep.111]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-469">
		<a href="#" data-media="http://feedproxy.google.com/~r/Vaciatubandeja/~5/8ctQI5skS9E/6622242.mp3" title="12: yUML | Crea Diagramas a partir de texto plano">
			<span class="isplaying"></span>
			<span class="logo vacíatubandeja"></span>
			<span class="podcast">Vacía tu bandeja</span>
			<span class="track">12: yUML | Crea Diagramas a partir de texto plano</span>
		</a>
	</span>
</li>
<li>
	<span id="item-470">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/7327708/Bat2x100_162.m4a" title="#162 – Sigo viviendo con retraso…">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#162 – Sigo viviendo con retraso…</span>
		</a>
	</span>
</li>
<li>
	<span id="item-471">
		<a href="#" data-media="http://api.spreaker.com/download/episode/13264718/webreactiva_podcast_08.mp3" title="WR 8: El programador mató a la startup">
			<span class="isplaying"></span>
			<span class="logo webreactiva"></span>
			<span class="podcast">Web Reactiva</span>
			<span class="track">WR 8: El programador mató a la startup</span>
		</a>
	</span>
</li>
<li>
	<span id="item-472">
		<a href="#" data-media="http://www.ivoox.com/code-time-91-por-deberia-usar-linux_mf_21917171_feed_1.mp3" title="Code Time (91): ¿Por qué debería usar Linux?">
			<span class="isplaying"></span>
			<span class="logo codetime"></span>
			<span class="podcast">Code Time</span>
			<span class="track">Code Time (91): ¿Por qué debería usar Linux?</span>
		</a>
	</span>
</li>
<li>
	<span id="item-473">
		<a href="#" data-media="http://www.ivoox.com/code-time-91-por-deberia-usar-linux_mf_21917170_feed_1.mp3" title="Code Time (91): ¿Por qué debería usar Linux? PT 2">
			<span class="isplaying"></span>
			<span class="logo codetime"></span>
			<span class="podcast">Code Time</span>
			<span class="track">Code Time (91): ¿Por qué debería usar Linux? PT 2</span>
		</a>
	</span>
</li>
<li>
	<span id="item-474">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/5a0163326df7fd2b59ef1337.mp3" title="El perturbador mundo de YouTube Kids">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">El perturbador mundo de YouTube Kids</span>
		</a>
	</span>
</li>
<li>
	<span id="item-475">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/11/podcast-61-gestion-contenedores-con-portainer.mp3" title="Podcast #61: Gestión de contenedores Docker con portainer">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #61: Gestión de contenedores Docker con portainer</span>
		</a>
	</span>
</li>
<li>
	<span id="item-476">
		<a href="#" data-media="http://feedproxy.google.com/~r/Vaciatubandeja/~5/RDvyf9JuOtY/12%20-%20yUML-Crea%20diagramas%20a%20partir%20de%20texto%20plano.mp3" title="#12-yUML: Crea Diagramas a partir de texto plano">
			<span class="isplaying"></span>
			<span class="logo vaciatubandeja"></span>
			<span class="podcast">Vacia Tu Bandeja</span>
			<span class="track">#12-yUML: Crea Diagramas a partir de texto plano</span>
		</a>
	</span>
</li>
<li>
	<span id="item-477">
		<a href="#" data-media="http://traffic.libsyn.com/cesargarciasaez/LHM118.mp3" title="LHM118 – Una mudanza de ciencia ficción">
			<span class="isplaying"></span>
			<span class="logo lahoramaker"></span>
			<span class="podcast">La Hora Maker</span>
			<span class="track">LHM118 – Una mudanza de ciencia ficción</span>
		</a>
	</span>
</li>
<li>
	<span id="item-478">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/5a00449e6df7fd2b59eefd7e.mp3" title="Unicornios sin control">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Unicornios sin control</span>
		</a>
	</span>
</li>
<li>
	<span id="item-479">
		<a href="#" data-media="http://tracking.feedpress.it/link/15407/7314665/BCS018-WiFi-phishing-conejos.mp3" title="BCS018 – WiFi, phishing, conejos y otras mancias">
			<span class="isplaying"></span>
			<span class="logo bitácoradeciberseguridad"></span>
			<span class="podcast">Bitácora de Ciberseguridad</span>
			<span class="track">BCS018 – WiFi, phishing, conejos y otras mancias</span>
		</a>
	</span>
</li>
<li>
	<span id="item-480">
		<a href="#" data-media="http://www.ivoox.com/w10-da-miedito-noche-halloween_mf_21890831_feed_1.mp3" title="w10 da miedito en la noche de Halloween">
			<span class="isplaying"></span>
			<span class="logo mosqueterowebtecnologialinuxchromebooks"></span>
			<span class="podcast">Mosqueteroweb tecnologia, Linux, Chromebooks</span>
			<span class="track">w10 da miedito en la noche de Halloween</span>
		</a>
	</span>
</li>
<li>
	<span id="item-481">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/11/podcast-60-primer-aniversario-del-podcast.mp3" title="Podcast #60: Primer aniversario del podcast">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #60: Primer aniversario del podcast</span>
		</a>
	</span>
</li>
<li>
	<span id="item-482">
		<a href="#" data-media="http://www.ivoox.com/161-como-partner-youtube-soy-os_mf_21887997_feed_1.mp3" title="#161 Como partner de Youtube que soy os debo una explicación">
			<span class="isplaying"></span>
			<span class="logo salmorejogeek"></span>
			<span class="podcast">Salmorejo Geek</span>
			<span class="track">#161 Como partner de Youtube que soy os debo una explicación</span>
		</a>
	</span>
</li>
<li>
	<span id="item-483">
		<a href="#" data-media="http://api.spreaker.com/download/episode/13249434/deknet_20171105_1412.mp3" title="La encriptación ha llegado y muchos no se han enterado">
			<span class="isplaying"></span>
			<span class="logo deknet"></span>
			<span class="podcast">DekNet</span>
			<span class="track">La encriptación ha llegado y muchos no se han enterado</span>
		</a>
	</span>
</li>
<li>
	<span id="item-484">
		<a href="#" data-media="https://www.ivoox.com/s02e01-ubuntu-17-10-distros-100-libres_mf_21884774_feed_1.mp3" title="S02E01 Ubuntu 17.10 y distros 100% libres">
			<span class="isplaying"></span>
			<span class="logo ubuntuyotrashierbas"></span>
			<span class="podcast">Ubuntu y otras hierbas</span>
			<span class="track">S02E01 Ubuntu 17.10 y distros 100% libres</span>
		</a>
	</span>
</li>
<li>
	<span id="item-485">
		<a href="#" data-media="http://traffic.libsyn.com/cesargarciasaez/LHM117.mp3" title="LHM117 – Crea eventos más activos para makers">
			<span class="isplaying"></span>
			<span class="logo lahoramaker"></span>
			<span class="podcast">La Hora Maker</span>
			<span class="track">LHM117 – Crea eventos más activos para makers</span>
		</a>
	</span>
</li>
<li>
	<span id="item-486">
		<a href="#" data-media="http://traffic.libsyn.com/cesargarciasaez/LHM116.mp3" title="LHM116 – Resumen de proyectos y actividades en Madrid Mini Maker Faire 2017">
			<span class="isplaying"></span>
			<span class="logo lahoramaker"></span>
			<span class="podcast">La Hora Maker</span>
			<span class="track">LHM116 – Resumen de proyectos y actividades en Madrid Mini Maker Faire 2017</span>
		</a>
	</span>
</li>
<li>
	<span id="item-487">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/59fdfbf86df7fd2b59eee5a3.mp3" title="Kernel: iPhone X vs Pixel 2 XL, con Paolo Ã�lvarez">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Kernel: iPhone X vs Pixel 2 XL, con Paolo Ã�lvarez</span>
		</a>
	</span>
</li>
<li>
	<span id="item-488">
		<a href="#" data-media="http://mundipad.es/capitulos-podcast-bemoob/094-foromoviles-podcast.mp3" title="ForoMoviles Podcast 094: Deja disfrutar a los demás">
			<span class="isplaying"></span>
			<span class="logo podcastforomóviles"></span>
			<span class="podcast">Podcast – ForoMóviles</span>
			<span class="track">ForoMoviles Podcast 094: Deja disfrutar a los demás</span>
		</a>
	</span>
</li>
<li>
	<span id="item-489">
		<a href="#" data-media="http://www.ivoox.com/episodio-11-introspeccion-ii_mf_21874493_feed_1.mp3" title="Episodio 11 - Introspección II">
			<span class="isplaying"></span>
			<span class="logo programaresunamierda"></span>
			<span class="podcast">Programar es una mierda</span>
			<span class="track">Episodio 11 - Introspección II</span>
		</a>
	</span>
</li>
<li>
	<span id="item-490">
		<a href="#" data-media="https://www.ivoox.com/episodio-11-introspeccion-ii_mf_21874493_feed_1.mp3" title="Episodio 11 - Introspección II">
			<span class="isplaying"></span>
			<span class="logo programaresunamierda"></span>
			<span class="podcast">Programar es una mierda</span>
			<span class="track">Episodio 11 - Introspección II</span>
		</a>
	</span>
</li>
<li>
	<span id="item-491">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/59fc7f466df7fd2b59eecabd.mp3" title="El trimestre de los 100 millones">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">El trimestre de los 100 millones</span>
		</a>
	</span>
</li>
<li>
	<span id="item-492">
		<a href="#" data-media="http://www.ivoox.com/despotricando-ando-2017-cap-79_mf_21852380_feed_1.mp3" title="Despotricando ando 2017 - Cap 79">
			<span class="isplaying"></span>
			<span class="logo podcastwintabletinfo"></span>
			<span class="podcast">Podcast WINTABLET.INFO</span>
			<span class="track">Despotricando ando 2017 - Cap 79</span>
		</a>
	</span>
</li>
<li>
	<span id="item-493">
		<a href="#" data-media="https://ar.ivoox.com/es/ep135-el-despertar-tabby_mf_21846225_feed_1.mp3" title="Ep135: El Despertar de Tabby">
			<span class="isplaying"></span>
			<span class="logo coffeebreakseñalyruido"></span>
			<span class="podcast">Coffee Break: Señal y Ruido</span>
			<span class="track">Ep135: El Despertar de Tabby</span>
		</a>
	</span>
</li>
<li>
	<span id="item-494">
		<a href="#" data-media="http://traffic.libsyn.com/cesargarciasaez/LHM114.mp3" title="LHM114 – ¿Para qué sirve asistir a una Maker Faire?">
			<span class="isplaying"></span>
			<span class="logo lahoramaker"></span>
			<span class="podcast">La Hora Maker</span>
			<span class="track">LHM114 – ¿Para qué sirve asistir a una Maker Faire?</span>
		</a>
	</span>
</li>
<li>
	<span id="item-495">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/59faae866df7fd2b59eea961.mp3" title="Cómo el iPhone X ha dominado la semana">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Cómo el iPhone X ha dominado la semana</span>
		</a>
	</span>
</li>
<li>
	<span id="item-496">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/10/podcast-59-victor-de-la-nuez.mp3" title="Podcast #59: Víctor de la Nuez de Wifi Canarias">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #59: Víctor de la Nuez de Wifi Canarias</span>
		</a>
	</span>
</li>
<li>
	<span id="item-497">
		<a href="#" data-media="http://traffic.libsyn.com/cesargarciasaez/LHM113.mp3" title="LHM113 – Programación Madrid Mini Maker Faire 2017 y arranque NaPodPoMo!">
			<span class="isplaying"></span>
			<span class="logo lahoramaker"></span>
			<span class="podcast">La Hora Maker</span>
			<span class="track">LHM113 – Programación Madrid Mini Maker Faire 2017 y arranque NaPodPoMo!</span>
		</a>
	</span>
</li>
<li>
	<span id="item-498">
		<a href="#" data-media="http://api.spreaker.com/download/episode/13219884/deknet_20171101_1900.mp3" title="Las nubes se evaporan">
			<span class="isplaying"></span>
			<span class="logo deknet"></span>
			<span class="podcast">DekNet</span>
			<span class="track">Las nubes se evaporan</span>
		</a>
	</span>
</li>
<li>
	<span id="item-499">
		<a href="#" data-media="http://www.ivoox.com/023-gestion-del-correo-electronico_mf_21822168_feed_1.mp3" title="023 - Gestión del correo electrónico">
			<span class="isplaying"></span>
			<span class="logo aprendiendogtdpodcastproductividad"></span>
			<span class="podcast">Aprendiendo GTD podcast productividad</span>
			<span class="track">023 - Gestión del correo electrónico</span>
		</a>
	</span>
</li>
<li>
	<span id="item-500">
		<a href="#" data-media="http://api.spreaker.com/download/episode/13217419/synology_da_la_nota.mp3" title="REPOST: Synology da la nota">
			<span class="isplaying"></span>
			<span class="logo deknet"></span>
			<span class="podcast">DekNet</span>
			<span class="track">REPOST: Synology da la nota</span>
		</a>
	</span>
</li>
<li>
	<span id="item-501">
		<a href="#" data-media="https://deployando.me/podcast-download/179/21-ceph-storage.mp3" title="21 – Ceph Storage">
			<span class="isplaying"></span>
			<span class="logo deployandome"></span>
			<span class="podcast">deployando.me</span>
			<span class="track">21 – Ceph Storage</span>
		</a>
	</span>
</li>
<li>
	<span id="item-502">
		<a href="#" data-media="https://gitlab.com/podcastlinux/podcastlinux.gitlab.io/raw/master/Linux-Express/27linuxexpress.mp3" title="#27 Linux Express">
			<span class="isplaying"></span>
			<span class="logo linuxexpressdepodcastlinux"></span>
			<span class="podcast">Linux Express, de Podcast Linux.</span>
			<span class="track">#27 Linux Express</span>
		</a>
	</span>
</li>
<li>
	<span id="item-503">
		<a href="#" data-media="http://ia801503.us.archive.org/30/items/NolegaltechRadio/003-NOlegaltechRadio.mp3" title="#003-Distribuciones del mal, no todas son libres de verdad">
			<span class="isplaying"></span>
			<span class="logo nolegaltechradio"></span>
			<span class="podcast">NOlegaltech Radio</span>
			<span class="track">#003-Distribuciones del mal, no todas son libres de verdad</span>
		</a>
	</span>
</li>
<li>
	<span id="item-504">
		<a href="#" data-media="http://feedproxy.google.com/~r/WecodesignPodcast/~5/b4nWnu1Urzk/WeCodeSign+2x10+-+La+W3C.mp3" title="2x10 - La W3C">
			<span class="isplaying"></span>
			<span class="logo wecodesignpodcast"></span>
			<span class="podcast">WeCodeSign Podcast</span>
			<span class="track">2x10 - La W3C</span>
		</a>
	</span>
</li>
<li>
	<span id="item-505">
		<a href="#" data-media="http://api.spreaker.com/download/episode/13210675/webreactiva_podcast_07.mp3" title="WR 7: Open Source CRM. Gestiona tus clientes con software libre gratuito">
			<span class="isplaying"></span>
			<span class="logo webreactiva"></span>
			<span class="podcast">Web Reactiva</span>
			<span class="track">WR 7: Open Source CRM. Gestiona tus clientes con software libre gratuito</span>
		</a>
	</span>
</li>
<li>
	<span id="item-506">
		<a href="#" data-media="http://www.ivoox.com/code-time-90-jornadas-ciencias-la_mf_21784302_feed_1.mp3" title="Code Time (90): Jornadas en ciencias de la computación 2017">
			<span class="isplaying"></span>
			<span class="logo codetime"></span>
			<span class="podcast">Code Time</span>
			<span class="track">Code Time (90): Jornadas en ciencias de la computación 2017</span>
		</a>
	</span>
</li>
<li>
	<span id="item-507">
		<a href="#" data-media="http://podcast.edyo.es/podcast/edyo-31.mp3" title="EDyO 31 - La tecnología detrás del CERN">
			<span class="isplaying"></span>
			<span class="logo entredevyopspodcast"></span>
			<span class="podcast">EntreDevYOps Podcast</span>
			<span class="track">EDyO 31 - La tecnología detrás del CERN</span>
		</a>
	</span>
</li>
<li>
	<span id="item-508">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/59f6c7986df7fd2b59ee7ba0.mp3" title="El iMac Pro se deja ver y tocar">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">El iMac Pro se deja ver y tocar</span>
		</a>
	</span>
</li>
<li>
	<span id="item-509">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/Ep110_mixdown.mp3" title="¿Cómo medimos el tiempo? Pulsares y Ondas Gravitacionales [Ep.110]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">¿Cómo medimos el tiempo? Pulsares y Ondas Gravitacionales [Ep.110]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-510">
		<a href="#" data-media="http://www.ivoox.com/script-time-por-es-util-aprender-ensamblador_mf_21746581_feed_1.mp3" title="Script Time: ¿Por qué es útil aprender ensamblador?">
			<span class="isplaying"></span>
			<span class="logo codetime"></span>
			<span class="podcast">Code Time</span>
			<span class="track">Script Time: ¿Por qué es útil aprender ensamblador?</span>
		</a>
	</span>
</li>
<li>
	<span id="item-511">
		<a href="#" data-media="http://www.ivoox.com/160-linux-mint-abandona-kde-corebird-1-7-mini_mf_21746395_feed_1.mp3" title="#160 Linux Mint abandona KDE, Corebird 1.7, mini Podcast personal en Telegram">
			<span class="isplaying"></span>
			<span class="logo salmorejogeek"></span>
			<span class="podcast">Salmorejo Geek</span>
			<span class="track">#160 Linux Mint abandona KDE, Corebird 1.7, mini Podcast personal en Telegram</span>
		</a>
	</span>
</li>
<li>
	<span id="item-512">
		<a href="#" data-media="https://archive.org/download/39ContestandoALazarusWorld/39-contestando-a-lazarus-world.mp3" title="#39 El fracaso escolar en España">
			<span class="isplaying"></span>
			<span class="logo educandogeek"></span>
			<span class="podcast">eDucando Geek</span>
			<span class="track">#39 El fracaso escolar en España</span>
		</a>
	</span>
</li>
<li>
	<span id="item-513">
		<a href="#" data-media="https://anchor.fm/s/106db04/podcast/download/47948/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fanchor-data%2Fstationexports%2Fpodcasts%2FComo-enlazo-audios-a-Anchor-b378f648f54ec.m4a" title="079. Novedades Anchor y como enlazo mis Audios">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">079. Novedades Anchor y como enlazo mis Audios</span>
		</a>
	</span>
</li>
<li>
	<span id="item-514">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/10/podcast-58-rip.mp3" title="Podcast #58: RIP">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #58: RIP</span>
		</a>
	</span>
</li>
<li>
	<span id="item-515">
		<a href="#" data-media="http://traffic.libsyn.com/cesargarciasaez/LHM112.mp3" title="LHM 112 en directo – Preguntas y proyectos con David Cuartielles (Octubre 2017)">
			<span class="isplaying"></span>
			<span class="logo lahoramaker"></span>
			<span class="podcast">La Hora Maker</span>
			<span class="track">LHM 112 en directo – Preguntas y proyectos con David Cuartielles (Octubre 2017)</span>
		</a>
	</span>
</li>
<li>
	<span id="item-516">
		<a href="#" data-media="http://www.ivoox.com/neositelinux-podcast-2017-6-11-pasos_mf_21727900_feed_1.mp3" title="NeoSiteLinux Podcast 2017 - #6 - 11 Pasos para armar tu Podcast">
			<span class="isplaying"></span>
			<span class="logo neositelinuxpodcast"></span>
			<span class="podcast">NeoSiteLinux Podcast</span>
			<span class="track">NeoSiteLinux Podcast 2017 - #6 - 11 Pasos para armar tu Podcast</span>
		</a>
	</span>
</li>
<li>
	<span id="item-517">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/59f3538f6df7fd2b59ee4c6d.mp3" title="Vuelven las colas a las Apple Store">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Vuelven las colas a las Apple Store</span>
		</a>
	</span>
</li>
<li>
	<span id="item-518">
		<a href="#" data-media="https://ar.ivoox.com/es/ep134-cosmologia-ondas-gravitacionales-energia-oscura-teorias_mf_21711480_feed_1.mp3" title="Ep134: Cosmología; Ondas Gravitacionales, Energía Oscura y Teorías Alternativas; El Futuro del Sol; ¿Exoasteroide?">
			<span class="isplaying"></span>
			<span class="logo coffeebreakseñalyruido"></span>
			<span class="podcast">Coffee Break: Señal y Ruido</span>
			<span class="track">Ep134: Cosmología; Ondas Gravitacionales, Energía Oscura y Teorías Alternativas; El Futuro del Sol; ¿Exoasteroide?</span>
		</a>
	</span>
</li>
<li>
	<span id="item-519">
		<a href="#" data-media="https://anchor.fm/s/106db04/podcast/download/47146/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fanchor-data%2Fstationexports%2Fpodcasts%2FAplicaci-n-De-Podcast-Gratis--23f7b134c5844.m4a" title="078. Aplicación Gratis de Podcast y Música Streaming">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">078. Aplicación Gratis de Podcast y Música Streaming</span>
		</a>
	</span>
</li>
<li>
	<span id="item-520">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/59f20e096df7fd2b59ee3278.mp3" title="Kernel: ¿Android 'Where'? con Pedro Moya">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Kernel: ¿Android 'Where'? con Pedro Moya</span>
		</a>
	</span>
</li>
<li>
	<span id="item-521">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/59f134716df7fd2b59ee1e79.mp3" title="Casi que prefiero un dron entrando por la ventana">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Casi que prefiero un dron entrando por la ventana</span>
		</a>
	</span>
</li>
<li>
	<span id="item-522">
		<a href="#" data-media="https://anchor.fm/s/106db04/podcast/download/46801/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fanchor-data%2Fstationexports%2Fpodcasts%2FEsExplorer-Y-Otros-Exploradore-1a73fb172fa59.m4a" title="077.Android: Es Explorer y varios exploradores de Carpetas">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">077.Android: Es Explorer y varios exploradores de Carpetas</span>
		</a>
	</span>
</li>
<li>
	<span id="item-523">
		<a href="#" data-media="http://www.ivoox.com/37-cultura-libre_mf_21673527_feed_1.mp3" title="#37 Cultura Libre">
			<span class="isplaying"></span>
			<span class="logo podcastlinux"></span>
			<span class="podcast">Podcast Linux</span>
			<span class="track">#37 Cultura Libre</span>
		</a>
	</span>
</li>
<li>
	<span id="item-524">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/59f040e59e91b02b75013ecf.mp3" title="Smartphones sin puertos de carga">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Smartphones sin puertos de carga</span>
		</a>
	</span>
</li>
<li>
	<span id="item-525">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/10/podcast-57-jitsi.mp3" title="Podcast #57: Jitsi">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #57: Jitsi</span>
		</a>
	</span>
</li>
<li>
	<span id="item-526">
		<a href="#" data-media="http://feedproxy.google.com/~r/Vaciatubandeja/~5/NJhtLl-ARLE/6622243.mp3" title="11: Correo | Cómo redactar un buen Asunto">
			<span class="isplaying"></span>
			<span class="logo vacíatubandeja"></span>
			<span class="podcast">Vacía tu bandeja</span>
			<span class="track">11: Correo | Cómo redactar un buen Asunto</span>
		</a>
	</span>
</li>
<li>
	<span id="item-527">
		<a href="#" data-media="http://api.spreaker.com/download/episode/13111917/wr_6_como_explicar_proyectos_tecnolo_gicos_a_tu_jefe_o_cliente.mp3" title="WR 6: Cómo explicar proyectos tecnológicos a tu jefe o cliente">
			<span class="isplaying"></span>
			<span class="logo webreactiva"></span>
			<span class="podcast">Web Reactiva</span>
			<span class="track">WR 6: Cómo explicar proyectos tecnológicos a tu jefe o cliente</span>
		</a>
	</span>
</li>
<li>
	<span id="item-528">
		<a href="#" data-media="http://www.ivoox.com/code-time-89-que-estudian-ciencias-de_mf_21641563_feed_1.mp3" title="Code Time (89): ¿Qué estudian las ciencias de la computación?">
			<span class="isplaying"></span>
			<span class="logo codetime"></span>
			<span class="podcast">Code Time</span>
			<span class="track">Code Time (89): ¿Qué estudian las ciencias de la computación?</span>
		</a>
	</span>
</li>
<li>
	<span id="item-529">
		<a href="#" data-media="http://api.spreaker.com/download/episode/13110404/podcast121.mp3" title="#121 Historia del movimiento Maker en España con @Colepower">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">#121 Historia del movimiento Maker en España con @Colepower</span>
		</a>
	</span>
</li>
<li>
	<span id="item-530">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/10/podcast-56-internet-y-la-aguja-hipotermica.mp3" title="Podcast #56: Internet y la aguja hipodérmica">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #56: Internet y la aguja hipodérmica</span>
		</a>
	</span>
</li>
<li>
	<span id="item-531">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/59ee97329e91b02b750113e5.mp3" title="Hablando de Schadenfreude">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Hablando de Schadenfreude</span>
		</a>
	</span>
</li>
<li>
	<span id="item-532">
		<a href="#" data-media="http://feedproxy.google.com/~r/Vaciatubandeja/~5/33ZkQxHR6T0/11-Correo%20-%20Como%20redactar%20un%20buen%20Asunto.mp3" title="#11-Correo: Cómo redactar un buen Asunto">
			<span class="isplaying"></span>
			<span class="logo vaciatubandeja"></span>
			<span class="podcast">Vacia Tu Bandeja</span>
			<span class="track">#11-Correo: Cómo redactar un buen Asunto</span>
		</a>
	</span>
</li>
<li>
	<span id="item-533">
		<a href="#" data-media="http://podcast.edyo.es/podcast/edyo-30.mp3" title="EDyO 30 - Cómo nos mantenemos al día.">
			<span class="isplaying"></span>
			<span class="logo entredevyopspodcast"></span>
			<span class="podcast">EntreDevYOps Podcast</span>
			<span class="track">EDyO 30 - Cómo nos mantenemos al día.</span>
		</a>
	</span>
</li>
<li>
	<span id="item-534">
		<a href="#" data-media="http://tracking.feedpress.it/link/16349/7172038/DT9.mp3" title="#9 Retroinformática con Jojo073">
			<span class="isplaying"></span>
			<span class="logo droidtalks"></span>
			<span class="podcast">Droid Talks</span>
			<span class="track">#9 Retroinformática con Jojo073</span>
		</a>
	</span>
</li>
<li>
	<span id="item-535">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/59ed5a219e91b02b7500efa8.mp3" title="Explore Feed y el 30% injusto">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Explore Feed y el 30% injusto</span>
		</a>
	</span>
</li>
<li>
	<span id="item-536">
		<a href="#" data-media="http://www.ivoox.com/episodio-10-web-components_mf_21609756_feed_1.mp3" title="Episodio 10 - Web components">
			<span class="isplaying"></span>
			<span class="logo programaresunamierda"></span>
			<span class="podcast">Programar es una mierda</span>
			<span class="track">Episodio 10 - Web components</span>
		</a>
	</span>
</li>
<li>
	<span id="item-537">
		<a href="#" data-media="https://www.ivoox.com/episodio-10-web-components_mf_21609756_feed_1.mp3" title="Episodio 10 - Web components">
			<span class="isplaying"></span>
			<span class="logo programaresunamierda"></span>
			<span class="podcast">Programar es una mierda</span>
			<span class="track">Episodio 10 - Web components</span>
		</a>
	</span>
</li>
<li>
	<span id="item-538">
		<a href="#" data-media="http://www.ivoox.com/159-2-distros-linux-1-swap-solucion-inicio_mf_21604893_feed_1.mp3" title="#159 2 distros Linux 1 Swap: Solución inicio lento (extra ACPI Error)">
			<span class="isplaying"></span>
			<span class="logo salmorejogeek"></span>
			<span class="podcast">Salmorejo Geek</span>
			<span class="track">#159 2 distros Linux 1 Swap: Solución inicio lento (extra ACPI Error)</span>
		</a>
	</span>
</li>
<li>
	<span id="item-539">
		<a href="#" data-media="http://mundipad.es/capitulos-podcast-bemoob/093-foromoviles-podcast.mp3" title="ForoMoviles Podcast 093: Huawei Mate 10, convergencia…">
			<span class="isplaying"></span>
			<span class="logo podcastforomóviles"></span>
			<span class="podcast">Podcast – ForoMóviles</span>
			<span class="track">ForoMoviles Podcast 093: Huawei Mate 10, convergencia…</span>
		</a>
	</span>
</li>
<li>
	<span id="item-540">
		<a href="#" data-media="https://archive.org/download/38CorreccionesACap37Y36/38-correcciones-a-cap-37-y-36.mp3" title="#38 Telegram lo hizo primero - Simyo - Correcciones">
			<span class="isplaying"></span>
			<span class="logo educandogeek"></span>
			<span class="podcast">eDucando Geek</span>
			<span class="track">#38 Telegram lo hizo primero - Simyo - Correcciones</span>
		</a>
	</span>
</li>
<li>
	<span id="item-541">
		<a href="#" data-media="http://www.ivoox.com/21-adobe-me-toca-lo-ladrillos_mf_21585096_feed_1.mp3" title="#21 Adobe me toca lo Ladrillos">
			<span class="isplaying"></span>
			<span class="logo reflexpodcast"></span>
			<span class="podcast">reflex podcast</span>
			<span class="track">#21 Adobe me toca lo Ladrillos</span>
		</a>
	</span>
</li>
<li>
	<span id="item-542">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/10/podcast-55-centros-de-datos-tomas-ledo.mp3" title="Podcast #55: Centros de Datos con Tomás Ledo">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #55: Centros de Datos con Tomás Ledo</span>
		</a>
	</span>
</li>
<li>
	<span id="item-543">
		<a href="#" data-media="http://www.ivoox.com/158-un-truco-telegram-para-ser-mas-productivo_mf_21575863_feed_1.mp3" title="#158 Un truco Telegram para ser más productivo">
			<span class="isplaying"></span>
			<span class="logo salmorejogeek"></span>
			<span class="podcast">Salmorejo Geek</span>
			<span class="track">#158 Un truco Telegram para ser más productivo</span>
		</a>
	</span>
</li>
<li>
	<span id="item-544">
		<a href="#" data-media="http://www.ivoox.com/realidad-virtual-aumentada-cap-78_mf_21573460_feed_1.mp3" title="Realidad virtual y aumentada - Cap 78">
			<span class="isplaying"></span>
			<span class="logo podcastwintabletinfo"></span>
			<span class="podcast">Podcast WINTABLET.INFO</span>
			<span class="track">Realidad virtual y aumentada - Cap 78</span>
		</a>
	</span>
</li>
<li>
	<span id="item-545">
		<a href="#" data-media="https://ar.ivoox.com/es/ep133-primera-onda-gravitacional-deteccion-multifrecuencia-fusion_mf_21564078_feed_1.mp3" title="Ep133: Primera onda gravitacional con detección multifrecuencia: fusión estrellas de neutrones; Homenaje a H. Leavitt">
			<span class="isplaying"></span>
			<span class="logo coffeebreakseñalyruido"></span>
			<span class="podcast">Coffee Break: Señal y Ruido</span>
			<span class="track">Ep133: Primera onda gravitacional con detección multifrecuencia: fusión estrellas de neutrones; Homenaje a H. Leavitt</span>
		</a>
	</span>
</li>
<li>
	<span id="item-546">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/59e919209e91b02b7500a513.mp3" title="Kernel: Las tarifas de datos ilimitadas, con Miguel Ã�ngel Uriondo">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Kernel: Las tarifas de datos ilimitadas, con Miguel Ã�ngel Uriondo</span>
		</a>
	</span>
</li>
<li>
	<span id="item-547">
		<a href="#" data-media="http://traffic.libsyn.com/cesargarciasaez/LHM111.mp3" title="LHM 111 – Fablab Valencia Océano Naranja – Un espacio donde dejar volar la imaginación">
			<span class="isplaying"></span>
			<span class="logo lahoramaker"></span>
			<span class="podcast">La Hora Maker</span>
			<span class="track">LHM 111 – Fablab Valencia Océano Naranja – Un espacio donde dejar volar la imaginación</span>
		</a>
	</span>
</li>
<li>
	<span id="item-548">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/59e8591e9e91b02b750079c3.mp3" title="Pagar mil euros por una pantalla así">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Pagar mil euros por una pantalla así</span>
		</a>
	</span>
</li>
<li>
	<span id="item-549">
		<a href="#" data-media="https://archive.org/download/37WhatsappUbicacionEnTiempoReal/37-whatsapp-ubicacion-en-tiempo-real.mp3" title="#37 WhatsApp Ubicación en tiempo real">
			<span class="isplaying"></span>
			<span class="logo educandogeek"></span>
			<span class="podcast">eDucando Geek</span>
			<span class="track">#37 WhatsApp Ubicación en tiempo real</span>
		</a>
	</span>
</li>
<li>
	<span id="item-550">
		<a href="#" data-media="http://api.spreaker.com/download/episode/13070392/s2e10_con_msanjuan_y_los_codingstones_toma_2.mp3" title="S2E10 con @msanjuan y los @CodingStones, toma 2">
			<span class="isplaying"></span>
			<span class="logo codeontherocks"></span>
			<span class="podcast">Code on the rocks</span>
			<span class="track">S2E10 con @msanjuan y los @CodingStones, toma 2</span>
		</a>
	</span>
</li>
<li>
	<span id="item-551">
		<a href="#" data-media="http://www.ivoox.com/29-conceptos-basicos-redes-vulnerabilidad-wifi_mf_21526247_feed_1.mp3" title="29. Conceptos básicos de redes y vulnerabilidad WIFI WPA2 KRACK">
			<span class="isplaying"></span>
			<span class="logo naserospodcast"></span>
			<span class="podcast">NASeros Podcast</span>
			<span class="track">29. Conceptos básicos de redes y vulnerabilidad WIFI WPA2 KRACK</span>
		</a>
	</span>
</li>
<li>
	<span id="item-552">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/59e724f99e91b02b75004e6f.mp3" title="La diversidad en un 'cupcake'">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">La diversidad en un 'cupcake'</span>
		</a>
	</span>
</li>
<li>
	<span id="item-553">
		<a href="#" data-media="https://gitlab.com/podcastlinux/podcastlinux.gitlab.io/raw/master/Linux-Express/%2326%20Podcast%20Linux%20Express.mp3" title="#26 Linux Express">
			<span class="isplaying"></span>
			<span class="logo linuxexpressdepodcastlinux"></span>
			<span class="podcast">Linux Express, de Podcast Linux.</span>
			<span class="track">#26 Linux Express</span>
		</a>
	</span>
</li>
<li>
	<span id="item-554">
		<a href="#" data-media="http://feedproxy.google.com/~r/WecodesignPodcast/~5/6C3gzwIYqBk/WeCodeSign%202x09%20-%20Sindrome%20del%20Impostor.mp3" title="2x09 - El Síndrome del Impostor">
			<span class="isplaying"></span>
			<span class="logo wecodesignpodcast"></span>
			<span class="podcast">WeCodeSign Podcast</span>
			<span class="track">2x09 - El Síndrome del Impostor</span>
		</a>
	</span>
</li>
<li>
	<span id="item-555">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/59e6041f9e91b02b75002946.mp3" title="El día después">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">El día después</span>
		</a>
	</span>
</li>
<li>
	<span id="item-556">
		<a href="#" data-media="http://api.spreaker.com/download/episode/13058124/webreactiva_podcast_05b.mp3" title="WR 5: La historia de los pequeños objetos y la web de componentes">
			<span class="isplaying"></span>
			<span class="logo webreactiva"></span>
			<span class="podcast">Web Reactiva</span>
			<span class="track">WR 5: La historia de los pequeños objetos y la web de componentes</span>
		</a>
	</span>
</li>
<li>
	<span id="item-557">
		<a href="#" data-media="http://www.ivoox.com/code-time-88-los-aportes-ciencias_mf_21494722_feed_1.mp3" title="Code Time (88): Los aportes de la ciencias de la computación a la historia">
			<span class="isplaying"></span>
			<span class="logo codetime"></span>
			<span class="podcast">Code Time</span>
			<span class="track">Code Time (88): Los aportes de la ciencias de la computación a la historia</span>
		</a>
	</span>
</li>
<li>
	<span id="item-558">
		<a href="#" data-media="http://ia801503.us.archive.org/30/items/NolegaltechRadio/Especial-MaratonLinuxero1-1.mp3" title="Especial - Maratón Linuxero 1.1">
			<span class="isplaying"></span>
			<span class="logo nolegaltechradio"></span>
			<span class="podcast">NOlegaltech Radio</span>
			<span class="track">Especial - Maratón Linuxero 1.1</span>
		</a>
	</span>
</li>
<li>
	<span id="item-559">
		<a href="#" data-media="http://www.ivoox.com/hacen-mas-infelices-smartphones-a-nuevas_mf_21471262_feed_1.mp3" title="¿Hacen más infelices los smartphones a las nuevas generaciones? | Episodio 63">
			<span class="isplaying"></span>
			<span class="logo repúblicaweb"></span>
			<span class="podcast">República Web</span>
			<span class="track">¿Hacen más infelices los smartphones a las nuevas generaciones? | Episodio 63</span>
		</a>
	</span>
</li>
<li>
	<span id="item-560">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/59e44dc19e91b02b75fff96f.mp3" title="¡Lunes negro!">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">¡Lunes negro!</span>
		</a>
	</span>
</li>
<li>
	<span id="item-561">
		<a href="#" data-media="http://compilando.audio/wp-content/uploads/2017/10/podcast15.mp3" title="Podcast 15 – Desarrollo de Gnome, Red Hat y Fedora . Librecon 2017.">
			<span class="isplaying"></span>
			<span class="logo compilandopodcast"></span>
			<span class="podcast">Compilando Podcast</span>
			<span class="track">Podcast 15 – Desarrollo de Gnome, Red Hat y Fedora . Librecon 2017.</span>
		</a>
	</span>
</li>
<li>
	<span id="item-562">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/10/podcast-54-hablamos-de-dominios-con-jorge-campanillas.mp3" title="Podcast #54: Hablamos de dominios con Jorge Campanillas">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #54: Hablamos de dominios con Jorge Campanillas</span>
		</a>
	</span>
</li>
<li>
	<span id="item-563">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/Ep109.mp3" title="Buscando la Luna de los Ewoks y Ciencia en Redes Sociales [Ep.109]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Buscando la Luna de los Ewoks y Ciencia en Redes Sociales [Ep.109]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-564">
		<a href="#" data-media="https://archive.org/download/Maraton11NoLegalTech/Marat%C3%B3n11-NoLegalTech.ogg" title="#03 Maratón Linuxero 1.1: NOLegalTech Radio">
			<span class="isplaying"></span>
			<span class="logo maratónlinuxero"></span>
			<span class="podcast">Maratón Linuxero</span>
			<span class="track">#03 Maratón Linuxero 1.1: NOLegalTech Radio</span>
		</a>
	</span>
</li>
<li>
	<span id="item-565">
		<a href="#" data-media="https://archive.org/download/Maraton11Etertics/Marat%C3%B3n11-Etertics.ogg" title="#02 Maratón Linuxero 1.1: Etertics">
			<span class="isplaying"></span>
			<span class="logo maratónlinuxero"></span>
			<span class="podcast">Maratón Linuxero</span>
			<span class="track">#02 Maratón Linuxero 1.1: Etertics</span>
		</a>
	</span>
</li>
<li>
	<span id="item-566">
		<a href="#" data-media="https://archive.org/download/Maraton11MaratonLinuxero/Marat%C3%B3n11-Marat%C3%B3nLinuxero.ogg" title="#01 Maratón Linuxero 1.1: Proyecto Maratón Linuxero">
			<span class="isplaying"></span>
			<span class="logo maratónlinuxero"></span>
			<span class="podcast">Maratón Linuxero</span>
			<span class="track">#01 Maratón Linuxero 1.1: Proyecto Maratón Linuxero</span>
		</a>
	</span>
</li>
<li>
	<span id="item-567">
		<a href="#" data-media="http://www.ivoox.com/157-victorhck-in-the-free-world-gnu-linux-software_mf_21456955_feed_1.mp3" title="#157 Victorhck in The Free World: GNU/Linux, Software Libre, openSUSE y Gatos">
			<span class="isplaying"></span>
			<span class="logo salmorejogeek"></span>
			<span class="podcast">Salmorejo Geek</span>
			<span class="track">#157 Victorhck in The Free World: GNU/Linux, Software Libre, openSUSE y Gatos</span>
		</a>
	</span>
</li>
<li>
	<span id="item-568">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/59e09e409e91b02b75ffac7b.mp3" title="Muy Samsungs y mucho Samsungs">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Muy Samsungs y mucho Samsungs</span>
		</a>
	</span>
</li>
<li>
	<span id="item-569">
		<a href="#" data-media="https://ar.ivoox.com/es/ep132-detectada-materia-perdida-escudo-planetario-para_mf_21425272_feed_1.mp3" title="Ep132: Detectada la Materia Perdida; Escudo Planetario para la Tierra; Supernova 1987; Los Anillos de Haumea">
			<span class="isplaying"></span>
			<span class="logo coffeebreakseñalyruido"></span>
			<span class="podcast">Coffee Break: Señal y Ruido</span>
			<span class="track">Ep132: Detectada la Materia Perdida; Escudo Planetario para la Tierra; Supernova 1987; Los Anillos de Haumea</span>
		</a>
	</span>
</li>
<li>
	<span id="item-570">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/7066757/Bat2x100_161.m4a" title="#161 – Por fin …  Sigo vivo !">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#161 – Por fin …  Sigo vivo !</span>
		</a>
	</span>
</li>
<li>
	<span id="item-571">
		<a href="#" data-media="http://www.ivoox.com/022-productividad-sergio-pantiga_mf_21418719_feed_1.mp3" title="022 - Productividad con Sergio Pantiga">
			<span class="isplaying"></span>
			<span class="logo aprendiendogtdpodcastproductividad"></span>
			<span class="podcast">Aprendiendo GTD podcast productividad</span>
			<span class="track">022 - Productividad con Sergio Pantiga</span>
		</a>
	</span>
</li>
<li>
	<span id="item-572">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/59df7a1c9e91b02b75ff85cc.mp3" title="Kernel: la crisis de YouTube, con Juan Castromil">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Kernel: la crisis de YouTube, con Juan Castromil</span>
		</a>
	</span>
</li>
<li>
	<span id="item-573">
		<a href="#" data-media="http://traffic.libsyn.com/cesargarciasaez/LHM110.mp3" title="LHM 110 – Cómo imprimir en 3D a lo grande con Gianluca Pugliese de WASP Madrid">
			<span class="isplaying"></span>
			<span class="logo lahoramaker"></span>
			<span class="podcast">La Hora Maker</span>
			<span class="track">LHM 110 – Cómo imprimir en 3D a lo grande con Gianluca Pugliese de WASP Madrid</span>
		</a>
	</span>
</li>
<li>
	<span id="item-574">
		<a href="#" data-media="https://archive.org/download/36Miband2Simyo/36-miband2-simyo.mp3" title="#36 Mi Band 2 y Simyo">
			<span class="isplaying"></span>
			<span class="logo educandogeek"></span>
			<span class="podcast">eDucando Geek</span>
			<span class="track">#36 Mi Band 2 y Simyo</span>
		</a>
	</span>
</li>
<li>
	<span id="item-575">
		<a href="#" data-media="http://www.ivoox.com/36-linux-connexion-atareao_mf_21387751_feed_1.mp3" title="#36 Linux Connexion con Atareao">
			<span class="isplaying"></span>
			<span class="logo podcastlinux"></span>
			<span class="podcast">Podcast Linux</span>
			<span class="track">#36 Linux Connexion con Atareao</span>
		</a>
	</span>
</li>
<li>
	<span id="item-576">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/59ddd3ae9e91b02b75ff5e11.mp3" title="Tic, TAC, tic, TAC, tic, TAC">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Tic, TAC, tic, TAC, tic, TAC</span>
		</a>
	</span>
</li>
<li>
	<span id="item-577">
		<a href="#" data-media="http://api.spreaker.com/download/episode/13006362/podcast120.mp3" title="#120 Haz tus propios wearables con Arduino LilyPad y Flora">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">#120 Haz tus propios wearables con Arduino LilyPad y Flora</span>
		</a>
	</span>
</li>
<li>
	<span id="item-578">
		<a href="#" data-media="http://api.spreaker.com/download/episode/13002280/webreactiva_podcast_04.mp3" title="WR 4: Stripe, el gran salto de los pagos online">
			<span class="isplaying"></span>
			<span class="logo webreactiva"></span>
			<span class="podcast">Web Reactiva</span>
			<span class="track">WR 4: Stripe, el gran salto de los pagos online</span>
		</a>
	</span>
</li>
<li>
	<span id="item-579">
		<a href="#" data-media="http://www.ivoox.com/code-time-87-que-son-ciencias-de_mf_21360640_feed_1.mp3" title="Code Time (87): ¿Qué son las ciencias de la computación?">
			<span class="isplaying"></span>
			<span class="logo codetime"></span>
			<span class="podcast">Code Time</span>
			<span class="track">Code Time (87): ¿Qué son las ciencias de la computación?</span>
		</a>
	</span>
</li>
<li>
	<span id="item-580">
		<a href="#" data-media="http://feedproxy.google.com/~r/Vaciatubandeja/~5/uCJqPzKEP0A/6622244.mp3" title="10: Cómo conseguir las metas que te propones">
			<span class="isplaying"></span>
			<span class="logo vacíatubandeja"></span>
			<span class="podcast">Vacía tu bandeja</span>
			<span class="track">10: Cómo conseguir las metas que te propones</span>
		</a>
	</span>
</li>
<li>
	<span id="item-581">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/59dab2569e91b02b75ff31e7.mp3" title="Seis años sin Steve Jobs">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Seis años sin Steve Jobs</span>
		</a>
	</span>
</li>
<li>
	<span id="item-582">
		<a href="#" data-media="http://feedproxy.google.com/~r/Vaciatubandeja/~5/xV7_uChntEY/10-Como%20conseguir%20las%20metas%20que%20te%20propones.mp3" title="#10-Cómo conseguir las metas que te propones">
			<span class="isplaying"></span>
			<span class="logo vaciatubandeja"></span>
			<span class="podcast">Vacia Tu Bandeja</span>
			<span class="track">#10-Cómo conseguir las metas que te propones</span>
		</a>
	</span>
</li>
<li>
	<span id="item-583">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/Ep108.mp3" title="Astronomía e Informática: Inteligencia Artificial, Machine Learning y Big Data [Ep.108]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Astronomía e Informática: Inteligencia Artificial, Machine Learning y Big Data [Ep.108]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-584">
		<a href="#" data-media="http://www.ivoox.com/episodio-9-serverless-faas_mf_21332282_feed_1.mp3" title="Episodio 9 - Serverless FaaS">
			<span class="isplaying"></span>
			<span class="logo programaresunamierda"></span>
			<span class="podcast">Programar es una mierda</span>
			<span class="track">Episodio 9 - Serverless FaaS</span>
		</a>
	</span>
</li>
<li>
	<span id="item-585">
		<a href="#" data-media="https://www.ivoox.com/episodio-9-serverless-faas_mf_21332282_feed_1.mp3" title="Episodio 9 - Serverless FaaS">
			<span class="isplaying"></span>
			<span class="logo programaresunamierda"></span>
			<span class="podcast">Programar es una mierda</span>
			<span class="track">Episodio 9 - Serverless FaaS</span>
		</a>
	</span>
</li>
<li>
	<span id="item-586">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/10/podcast-53-bgp.mp3" title="Podcast #53: BGP">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #53: BGP</span>
		</a>
	</span>
</li>
<li>
	<span id="item-587">
		<a href="#" data-media="http://www.ivoox.com/script-time-las-preguntas-comentarios-los_mf_21325697_feed_1.mp3" title="Script Time: Las preguntas y comentarios en los foros">
			<span class="isplaying"></span>
			<span class="logo codetime"></span>
			<span class="podcast">Code Time</span>
			<span class="track">Script Time: Las preguntas y comentarios en los foros</span>
		</a>
	</span>
</li>
<li>
	<span id="item-588">
		<a href="#" data-media="http://www.ivoox.com/156-mi-hdd-1tb-ha-muerto-y_mf_21322964_feed_1.mp3" title="#156 Mi HDD de 1TB ha muerto y se ha llevado parte de mí">
			<span class="isplaying"></span>
			<span class="logo salmorejogeek"></span>
			<span class="podcast">Salmorejo Geek</span>
			<span class="track">#156 Mi HDD de 1TB ha muerto y se ha llevado parte de mí</span>
		</a>
	</span>
</li>
<li>
	<span id="item-589">
		<a href="#" data-media="http://mundipad.es/capitulos-podcast-bemoob/092-foromoviles-podcast.mp3" title="ForoMoviles Podcast 092: Google Pixel 2, Xiaomi Mi A1…">
			<span class="isplaying"></span>
			<span class="logo podcastforomóviles"></span>
			<span class="podcast">Podcast – ForoMóviles</span>
			<span class="track">ForoMoviles Podcast 092: Google Pixel 2, Xiaomi Mi A1…</span>
		</a>
	</span>
</li>
<li>
	<span id="item-590">
		<a href="#" data-media="http://www.ivoox.com/155-ojo-la-scarlett-2i2-2nd-gen-firmware_mf_21315385_feed_1.mp3" title="#155 OJO: La Scarlett 2i2 2nd gen firmware 1116 no funciona en Linux">
			<span class="isplaying"></span>
			<span class="logo salmorejogeek"></span>
			<span class="podcast">Salmorejo Geek</span>
			<span class="track">#155 OJO: La Scarlett 2i2 2nd gen firmware 1116 no funciona en Linux</span>
		</a>
	</span>
</li>
<li>
	<span id="item-591">
		<a href="#" data-media="http://www.ivoox.com/w10-update-creators-google-ia-iphone-mas_mf_21303021_feed_1.mp3" title="W10 Update Creators, Google, IA, Iphone y mas">
			<span class="isplaying"></span>
			<span class="logo mosqueterowebtecnologialinuxchromebooks"></span>
			<span class="podcast">Mosqueteroweb tecnologia, Linux, Chromebooks</span>
			<span class="track">W10 Update Creators, Google, IA, Iphone y mas</span>
		</a>
	</span>
</li>
<li>
	<span id="item-592">
		<a href="#" data-media="http://tracking.feedpress.it/link/15407/7007533/BCS017-TIC-y-Educacion.mp3" title="BCS017 – TIC y Educación">
			<span class="isplaying"></span>
			<span class="logo bitácoradeciberseguridad"></span>
			<span class="podcast">Bitácora de Ciberseguridad</span>
			<span class="track">BCS017 – TIC y Educación</span>
		</a>
	</span>
</li>
<li>
	<span id="item-593">
		<a href="#" data-media="http://www.ivoox.com/novedades-google-oct-2017-cap-77_mf_21297828_feed_1.mp3" title="Novedades Google Oct 2017 - Cap 77">
			<span class="isplaying"></span>
			<span class="logo podcastwintabletinfo"></span>
			<span class="podcast">Podcast WINTABLET.INFO</span>
			<span class="track">Novedades Google Oct 2017 - Cap 77</span>
		</a>
	</span>
</li>
<li>
	<span id="item-594">
		<a href="#" data-media="https://ar.ivoox.com/es/ep131-los-nobel-rumores-tmt-ligo-virgo-suenos_mf_21294286_feed_1.mp3" title="Ep131: Los NOBEL; Rumores: TMT y LIGO/VIRGO; Sueños de Medusas">
			<span class="isplaying"></span>
			<span class="logo coffeebreakseñalyruido"></span>
			<span class="podcast">Coffee Break: Señal y Ruido</span>
			<span class="track">Ep131: Los NOBEL; Rumores: TMT y LIGO/VIRGO; Sueños de Medusas</span>
		</a>
	</span>
</li>
<li>
	<span id="item-595">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/59d5a9f8db5e932b6f31b269.mp3" title="Kernel: Pixelados, con Paolo Ã�lvarez">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Kernel: Pixelados, con Paolo Ã�lvarez</span>
		</a>
	</span>
</li>
<li>
	<span id="item-596">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/59d59a2edb5e932b6f31ab6a.mp3" title="Di no a DxO">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Di no a DxO</span>
		</a>
	</span>
</li>
<li>
	<span id="item-597">
		<a href="#" data-media="http://www.ivoox.com/28-fin-neutralidad-red_mf_21275754_feed_1.mp3" title="28. Fin de la neutralidad de la red. Los datos, el petróleo del siglo XXI.">
			<span class="isplaying"></span>
			<span class="logo naserospodcast"></span>
			<span class="podcast">NASeros Podcast</span>
			<span class="track">28. Fin de la neutralidad de la red. Los datos, el petróleo del siglo XXI.</span>
		</a>
	</span>
</li>
<li>
	<span id="item-598">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/59d4780f9e91b02b75febbdd.mp3" title="Los hilos de Seúl">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Los hilos de Seúl</span>
		</a>
	</span>
</li>
<li>
	<span id="item-599">
		<a href="#" data-media="https://gitlab.com/podcastlinux/podcastlinux.gitlab.io/raw/master/Linux-Express/%2325%20Podcast%20Linux%20Express.mp3" title="#25 Linux Express">
			<span class="isplaying"></span>
			<span class="logo linuxexpressdepodcastlinux"></span>
			<span class="podcast">Linux Express, de Podcast Linux.</span>
			<span class="track">#25 Linux Express</span>
		</a>
	</span>
</li>
<li>
	<span id="item-600">
		<a href="#" data-media="http://www.ivoox.com/migrando-a-gnu-linux-programas-hay-ahi-dentro_mf_21245514_feed_1.mp3" title="Migrando a GNU/Linux, que programas hay ahí dentro">
			<span class="isplaying"></span>
			<span class="logo procrastinaciónycafé"></span>
			<span class="podcast">Procrastinación y Café</span>
			<span class="track">Migrando a GNU/Linux, que programas hay ahí dentro</span>
		</a>
	</span>
</li>
<li>
	<span id="item-601">
		<a href="#" data-media="http://feedproxy.google.com/~r/WecodesignPodcast/~5/wx8yUQDkuao/WeCodeSign%202x08%20-%20Progressive%20Web%20Apps.mp3" title="2x08 - Progressive Web Apps">
			<span class="isplaying"></span>
			<span class="logo wecodesignpodcast"></span>
			<span class="podcast">WeCodeSign Podcast</span>
			<span class="track">2x08 - Progressive Web Apps</span>
		</a>
	</span>
</li>
<li>
	<span id="item-602">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/59d38bc29e91b02b75fe9e4f.mp3" title="Wow, Waymo!">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Wow, Waymo!</span>
		</a>
	</span>
</li>
<li>
	<span id="item-603">
		<a href="#" data-media="http://www.ivoox.com/script-code-time-86-todos-seran_mf_21226539_feed_1.mp3" title="Script / Code Time (86) : ¿Todos serán programadores en el futuro?">
			<span class="isplaying"></span>
			<span class="logo codetime"></span>
			<span class="podcast">Code Time</span>
			<span class="track">Script / Code Time (86) : ¿Todos serán programadores en el futuro?</span>
		</a>
	</span>
</li>
<li>
	<span id="item-604">
		<a href="#" data-media="http://ia801503.us.archive.org/30/items/NolegaltechRadio/002-NOlegaltechRadio.mp3" title="#002-Posibilidades de negocio en software libre">
			<span class="isplaying"></span>
			<span class="logo nolegaltechradio"></span>
			<span class="podcast">NOlegaltech Radio</span>
			<span class="track">#002-Posibilidades de negocio en software libre</span>
		</a>
	</span>
</li>
<li>
	<span id="item-605">
		<a href="#" data-media="http://api.spreaker.com/download/episode/12939362/webreactiva_podcast_03.mp3" title="WR 3: Programador, pon un git en tu vida">
			<span class="isplaying"></span>
			<span class="logo webreactiva"></span>
			<span class="podcast">Web Reactiva</span>
			<span class="track">WR 3: Programador, pon un git en tu vida</span>
		</a>
	</span>
</li>
<li>
	<span id="item-606">
		<a href="#" data-media="http://www.ivoox.com/retroactivo-podcast-68-id-software_mf_21213717_feed_1.mp3" title="RetroActivo Podcast #68: Id Software">
			<span class="isplaying"></span>
			<span class="logo retroactivopodcast"></span>
			<span class="podcast">RetroActivo Podcast</span>
			<span class="track">RetroActivo Podcast #68: Id Software</span>
		</a>
	</span>
</li>
<li>
	<span id="item-607">
		<a href="#" data-media="http://www.ivoox.com/154-killall-radio-team-international-podcast-day_mf_21210309_feed_1.mp3" title="#154 Killall Radio Team International Podcast Day">
			<span class="isplaying"></span>
			<span class="logo salmorejogeek"></span>
			<span class="podcast">Salmorejo Geek</span>
			<span class="track">#154 Killall Radio Team International Podcast Day</span>
		</a>
	</span>
</li>
<li>
	<span id="item-608">
		<a href="#" data-media="http://www.ivoox.com/neositelinux-podcast-2017-5-celebrando-el_mf_21209635_feed_1.mp3" title="NeoSiteLinux Podcast 2017 - #5 - Celebrando el #InternationalPodcastDay junto a grandes referentes">
			<span class="isplaying"></span>
			<span class="logo neositelinuxpodcast"></span>
			<span class="podcast">NeoSiteLinux Podcast</span>
			<span class="track">NeoSiteLinux Podcast 2017 - #5 - Celebrando el #InternationalPodcastDay junto a grandes referentes</span>
		</a>
	</span>
</li>
<li>
	<span id="item-609">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/59d1c8de9e91b02b75fe6f60.mp3" title="Llego tarde, me voy en cohete al trabajo">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Llego tarde, me voy en cohete al trabajo</span>
		</a>
	</span>
</li>
<li>
	<span id="item-610">
		<a href="#" data-media="http://www.ivoox.com/153-eugenia-bahit-el-dinero-no-es-un_mf_21189920_feed_1.mp3" title="#153 Eugenia Bahit: El dinero no es un incentivo, necesito otros retos">
			<span class="isplaying"></span>
			<span class="logo salmorejogeek"></span>
			<span class="podcast">Salmorejo Geek</span>
			<span class="track">#153 Eugenia Bahit: El dinero no es un incentivo, necesito otros retos</span>
		</a>
	</span>
</li>
<li>
	<span id="item-611">
		<a href="#" data-media="https://archive.org/download/35Ifttt/35-ifttt.mp3" title="#35 IFTTT">
			<span class="isplaying"></span>
			<span class="logo educandogeek"></span>
			<span class="podcast">eDucando Geek</span>
			<span class="track">#35 IFTTT</span>
		</a>
	</span>
</li>
<li>
	<span id="item-612">
		<a href="#" data-media="http://www.ivoox.com/021-10-leyes-productividad_mf_21188972_feed_1.mp3" title="021 - 10 Leyes de la productividad">
			<span class="isplaying"></span>
			<span class="logo aprendiendogtdpodcastproductividad"></span>
			<span class="podcast">Aprendiendo GTD podcast productividad</span>
			<span class="track">021 - 10 Leyes de la productividad</span>
		</a>
	</span>
</li>
<li>
	<span id="item-613">
		<a href="#" data-media="http://www.ivoox.com/neositelinux-podcast-2017-4-sourceforge-union_mf_21177077_feed_1.mp3" title="NeoSiteLinux Podcast 2017 - #4 - SourceForge, Union Podcastera, Podcast en iTunes y Adios 32Bits en Ubuntu">
			<span class="isplaying"></span>
			<span class="logo neositelinuxpodcast"></span>
			<span class="podcast">NeoSiteLinux Podcast</span>
			<span class="track">NeoSiteLinux Podcast 2017 - #4 - SourceForge, Union Podcastera, Podcast en iTunes y Adios 32Bits en Ubuntu</span>
		</a>
	</span>
</li>
<li>
	<span id="item-614">
		<a href="#" data-media="https://ar.ivoox.com/es/ep130-ligo-virgo-alimentacion-farmaciencia-vs-homeopatia-huracanes-y_mf_21163214_feed_1.mp3" title="Ep130: LIGO+VIRGO; Alimentación; Farmaciencia vs Homeopatía; Huracanes y conspiranoias; Asteroide-cometa doble">
			<span class="isplaying"></span>
			<span class="logo coffeebreakseñalyruido"></span>
			<span class="podcast">Coffee Break: Señal y Ruido</span>
			<span class="track">Ep130: LIGO+VIRGO; Alimentación; Farmaciencia vs Homeopatía; Huracanes y conspiranoias; Asteroide-cometa doble</span>
		</a>
	</span>
</li>
<li>
	<span id="item-615">
		<a href="#" data-media="http://api.spreaker.com/download/episode/12915617/podcast_119.mp3" title="#119 Sensor de corriente alterna para medir consumos con Arduino">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">#119 Sensor de corriente alterna para medir consumos con Arduino</span>
		</a>
	</span>
</li>
<li>
	<span id="item-616">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/59cd9c539e91b02b75fe3e31.mp3" title="Elon Musk dice cosas">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Elon Musk dice cosas</span>
		</a>
	</span>
</li>
<li>
	<span id="item-617">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/09/podcast-52-por-que-el-correo-no-llega.mp3" title="Podcast #52: Por qué el correo no llega">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #52: Por qué el correo no llega</span>
		</a>
	</span>
</li>
<li>
	<span id="item-618">
		<a href="#" data-media="http://tracking.feedpress.it/link/14730/7427248/CN_Programa_027.mp3" title="#CN027 – Los mata bien muertos">
			<span class="isplaying"></span>
			<span class="logo culturanas"></span>
			<span class="podcast">Cultura NAS</span>
			<span class="track">#CN027 – Los mata bien muertos</span>
		</a>
	</span>
</li>
<li>
	<span id="item-619">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/59ccb4b99e91b02b75fe1dbe.mp3" title="El Windows de las casas">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">El Windows de las casas</span>
		</a>
	</span>
</li>
<li>
	<span id="item-620">
		<a href="#" data-media="http://www.ivoox.com/152-rim-la-chica-sono-ser_mf_21136402_feed_1.mp3" title="#152 RIM: La chica que soñó con ser linuxera (un año después)">
			<span class="isplaying"></span>
			<span class="logo salmorejogeek"></span>
			<span class="podcast">Salmorejo Geek</span>
			<span class="track">#152 RIM: La chica que soñó con ser linuxera (un año después)</span>
		</a>
	</span>
</li>
<li>
	<span id="item-621">
		<a href="#" data-media="http://www.ivoox.com/35-formatos-libres_mf_21117524_feed_1.mp3" title="#35 Formatos Libres">
			<span class="isplaying"></span>
			<span class="logo podcastlinux"></span>
			<span class="podcast">Podcast Linux</span>
			<span class="track">#35 Formatos Libres</span>
		</a>
	</span>
</li>
<li>
	<span id="item-622">
		<a href="#" data-media="http://www.ivoox.com/151-extra-crossover-eduardo-yoyo-septiembre-2017_mf_21108291_feed_1.mp3" title="#151 Extra: Crossover Eduardo y Yoyo Septiembre 2017">
			<span class="isplaying"></span>
			<span class="logo salmorejogeek"></span>
			<span class="podcast">Salmorejo Geek</span>
			<span class="track">#151 Extra: Crossover Eduardo y Yoyo Septiembre 2017</span>
		</a>
	</span>
</li>
<li>
	<span id="item-623">
		<a href="#" data-media="http://feedproxy.google.com/~r/WecodesignPodcast/~5/BXI0lD8L2oc/WCD-Mini-11-Novedades.mp3" title="Mini 11 - Novedades">
			<span class="isplaying"></span>
			<span class="logo wecodesignpodcast"></span>
			<span class="podcast">WeCodeSign Podcast</span>
			<span class="track">Mini 11 - Novedades</span>
		</a>
	</span>
</li>
<li>
	<span id="item-624">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/09/crossover-yoyo-eduardo-sep-2017.mp3" title="Extra: Crossover Yoyo y Eduardo Septiembre 2017">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Extra: Crossover Yoyo y Eduardo Septiembre 2017</span>
		</a>
	</span>
</li>
<li>
	<span id="item-625">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/59c9c1f09e91b02b75fde423.mp3" title="Ya ni Bill Gates">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Ya ni Bill Gates</span>
		</a>
	</span>
</li>
<li>
	<span id="item-626">
		<a href="#" data-media="http://podcast.edyo.es/podcast/edyo-pildora1.mp3" title="EDyO píldora 1 - Analizando la seguridad del web del referendum catalán.">
			<span class="isplaying"></span>
			<span class="logo entredevyopspodcast"></span>
			<span class="podcast">EntreDevYOps Podcast</span>
			<span class="track">EDyO píldora 1 - Analizando la seguridad del web del referendum catalán.</span>
		</a>
	</span>
</li>
<li>
	<span id="item-627">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/59c865999e91b02b75fdbf12.mp3" title="Colas, correas y conductores">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Colas, correas y conductores</span>
		</a>
	</span>
</li>
<li>
	<span id="item-628">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/Ep107_mixdown.mp3" title="Reconexión Magnética, Anillos de radiación, física de plasmas y Satélite Chileno [Ep.107]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Reconexión Magnética, Anillos de radiación, física de plasmas y Satélite Chileno [Ep.107]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-629">
		<a href="#" data-media="http://www.ivoox.com/episodio-8-introspeccion-i_mf_21060983_feed_1.mp3" title="Episodio 8 - Introspección I">
			<span class="isplaying"></span>
			<span class="logo programaresunamierda"></span>
			<span class="podcast">Programar es una mierda</span>
			<span class="track">Episodio 8 - Introspección I</span>
		</a>
	</span>
</li>
<li>
	<span id="item-630">
		<a href="#" data-media="https://www.ivoox.com/episodio-8-introspeccion-i_mf_21060983_feed_1.mp3" title="Episodio 8 - Introspección I">
			<span class="isplaying"></span>
			<span class="logo programaresunamierda"></span>
			<span class="podcast">Programar es una mierda</span>
			<span class="track">Episodio 8 - Introspección I</span>
		</a>
	</span>
</li>
<li>
	<span id="item-631">
		<a href="#" data-media="http://compilando.audio/wp-content/uploads/2017/09/podcast14.mp3" title="Podcast 14 – Ordenadores con GNU/Linux preinstalado (Pcubuntu, Vant, Slimbook)">
			<span class="isplaying"></span>
			<span class="logo compilandopodcast"></span>
			<span class="podcast">Compilando Podcast</span>
			<span class="track">Podcast 14 – Ordenadores con GNU/Linux preinstalado (Pcubuntu, Vant, Slimbook)</span>
		</a>
	</span>
</li>
<li>
	<span id="item-632">
		<a href="#" data-media="http://traffic.libsyn.com/cesargarciasaez/LHM109.mp3" title="LHM 109 – Cómo apropiarse de la tecnología con Susan Klimczak">
			<span class="isplaying"></span>
			<span class="logo lahoramaker"></span>
			<span class="podcast">La Hora Maker</span>
			<span class="track">LHM 109 – Cómo apropiarse de la tecnología con Susan Klimczak</span>
		</a>
	</span>
</li>
<li>
	<span id="item-633">
		<a href="#" data-media="http://www.ivoox.com/150-salmorejo-geek-finalista-8-edicion_mf_21046283_feed_1.mp3" title="#150 Salmorejo Geek finalista en la 8ª edición de los Premios de la Asociación Podcast de España">
			<span class="isplaying"></span>
			<span class="logo salmorejogeek"></span>
			<span class="podcast">Salmorejo Geek</span>
			<span class="track">#150 Salmorejo Geek finalista en la 8ª edición de los Premios de la Asociación Podcast de España</span>
		</a>
	</span>
</li>
<li>
	<span id="item-634">
		<a href="#" data-media="http://api.spreaker.com/download/episode/12868016/deknet_20170923_0656.mp3" title="Manipulación, clickbait y otras hierbas">
			<span class="isplaying"></span>
			<span class="logo deknet"></span>
			<span class="podcast">DekNet</span>
			<span class="track">Manipulación, clickbait y otras hierbas</span>
		</a>
	</span>
</li>
<li>
	<span id="item-635">
		<a href="#" data-media="http://www.ivoox.com/seguridad-acceso-cap-76_mf_21028418_feed_1.mp3" title="Seguridad de acceso - Cap 76">
			<span class="isplaying"></span>
			<span class="logo podcastwintabletinfo"></span>
			<span class="podcast">Podcast WINTABLET.INFO</span>
			<span class="track">Seguridad de acceso - Cap 76</span>
		</a>
	</span>
</li>
<li>
	<span id="item-636">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/59c4a6f39e91b02b75fd93a3.mp3" title="La mitad de HTC">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">La mitad de HTC</span>
		</a>
	</span>
</li>
<li>
	<span id="item-637">
		<a href="#" data-media="https://ar.ivoox.com/es/ep129-naukas-ig-nobel-homininos-huellas-europeas-adios_mf_21019434_feed_1.mp3" title="Ep129: Naukas; Ig-Nobel; Homininos y huellas Europeas; Adiós Cassini - hola New Horizons y OSIRIS-REX; TRAPPIST-1">
			<span class="isplaying"></span>
			<span class="logo coffeebreakseñalyruido"></span>
			<span class="podcast">Coffee Break: Señal y Ruido</span>
			<span class="track">Ep129: Naukas; Ig-Nobel; Homininos y huellas Europeas; Adiós Cassini - hola New Horizons y OSIRIS-REX; TRAPPIST-1</span>
		</a>
	</span>
</li>
<li>
	<span id="item-638">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/59c30f1d9e91b02b75fd6d5c.mp3" title="Una pinza para el iPhone 8">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Una pinza para el iPhone 8</span>
		</a>
	</span>
</li>
<li>
	<span id="item-639">
		<a href="#" data-media="http://www.ivoox.com/post-keynote-iphone-sep-2017-crossover-con_mf_20989432_feed_1.mp3" title="Post Keynote iPhone Sep 2017 - Crossover con Treki23">
			<span class="isplaying"></span>
			<span class="logo podcastwintabletinfo"></span>
			<span class="podcast">Podcast WINTABLET.INFO</span>
			<span class="track">Post Keynote iPhone Sep 2017 - Crossover con Treki23</span>
		</a>
	</span>
</li>
<li>
	<span id="item-640">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/59c233639e91b02b75fd4f6c.mp3" title="Otra vez todo filtrado">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Otra vez todo filtrado</span>
		</a>
	</span>
</li>
<li>
	<span id="item-641">
		<a href="#" data-media="http://api.spreaker.com/download/episode/12840752/webreactiva_podcast_02.mp3" title="WR 2: La trampa de las plantillas premium">
			<span class="isplaying"></span>
			<span class="logo webreactiva"></span>
			<span class="podcast">Web Reactiva</span>
			<span class="track">WR 2: La trampa de las plantillas premium</span>
		</a>
	</span>
</li>
<li>
	<span id="item-642">
		<a href="#" data-media="https://gitlab.com/podcastlinux/podcastlinux.gitlab.io/raw/master/Linux-Express/%2324%20Podcast%20Linux%20Express.mp3" title="#24 Linux Express">
			<span class="isplaying"></span>
			<span class="logo linuxexpressdepodcastlinux"></span>
			<span class="podcast">Linux Express, de Podcast Linux.</span>
			<span class="track">#24 Linux Express</span>
		</a>
	</span>
</li>
<li>
	<span id="item-643">
		<a href="#" data-media="http://feedproxy.google.com/~r/WecodesignPodcast/~5/es2DXLwk-qo/WeCodeSign%202x07%20-%20La%20Web%20Abierta.mp3" title="2x07 - La Web Abierta">
			<span class="isplaying"></span>
			<span class="logo wecodesignpodcast"></span>
			<span class="podcast">WeCodeSign Podcast</span>
			<span class="track">2x07 - La Web Abierta</span>
		</a>
	</span>
</li>
<li>
	<span id="item-644">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/09/podcast-51-microweber.mp3" title="Podcast #51: MicroWeber">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #51: MicroWeber</span>
		</a>
	</span>
</li>
<li>
	<span id="item-645">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/6840493/Bat2x100_160.m4a" title="#160 – FingBox">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#160 – FingBox</span>
		</a>
	</span>
</li>
<li>
	<span id="item-646">
		<a href="#" data-media="http://podcast.edyo.es/podcast/edyo-29.mp3" title="Edyo 29 - Herramientas del día a día">
			<span class="isplaying"></span>
			<span class="logo entredevyopspodcast"></span>
			<span class="podcast">EntreDevYOps Podcast</span>
			<span class="track">Edyo 29 - Herramientas del día a día</span>
		</a>
	</span>
</li>
<li>
	<span id="item-647">
		<a href="#" data-media="http://www.ivoox.com/nikon-850-iphone-x-la-ruina_mf_20954469_feed_1.mp3" title="Nikon 850 + iphone X La ruina....">
			<span class="isplaying"></span>
			<span class="logo reflexpodcast"></span>
			<span class="podcast">reflex podcast</span>
			<span class="track">Nikon 850 + iphone X La ruina....</span>
		</a>
	</span>
</li>
<li>
	<span id="item-648">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/59c0e3ce9e91b02b75fd2bc7.mp3" title="¿Es suficiente la privacidad diferencial?">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">¿Es suficiente la privacidad diferencial?</span>
		</a>
	</span>
</li>
<li>
	<span id="item-649">
		<a href="#" data-media="http://ia601503.us.archive.org/30/items/NolegaltechRadio/001-NOlegaltechRadio.mp3" title="#001-Software libre y código abierto">
			<span class="isplaying"></span>
			<span class="logo nolegaltechradio"></span>
			<span class="podcast">NOlegaltech Radio</span>
			<span class="track">#001-Software libre y código abierto</span>
		</a>
	</span>
</li>
<li>
	<span id="item-650">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/59bf7a3c9e91b02b75fd0732.mp3" title="No me pongas banners, ponme a minar">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">No me pongas banners, ponme a minar</span>
		</a>
	</span>
</li>
<li>
	<span id="item-651">
		<a href="#" data-media="http://tracking.feedpress.it/link/16349/6823920/DT8-ecollado.mp3" title="#08 La fibra oscura con Eduardo Collado">
			<span class="isplaying"></span>
			<span class="logo droidtalks"></span>
			<span class="podcast">Droid Talks</span>
			<span class="track">#08 La fibra oscura con Eduardo Collado</span>
		</a>
	</span>
</li>
<li>
	<span id="item-652">
		<a href="#" data-media="http://www.ivoox.com/un-novato-ubucon-europea-paris_mf_20922438_feed_1.mp3" title="Un novato en la UbuCon Europea de París 2017">
			<span class="isplaying"></span>
			<span class="logo procrastinaciónycafé"></span>
			<span class="podcast">Procrastinación y Café</span>
			<span class="track">Un novato en la UbuCon Europea de París 2017</span>
		</a>
	</span>
</li>
<li>
	<span id="item-653">
		<a href="#" data-media="http://mundipad.es/capitulos-podcast-bemoob/091-foromoviles-podcast.mp3" title="ForoMoviles Podcast 091: iPhone X, Galaxy Note 8, Xiaomi Mi MIX 2…">
			<span class="isplaying"></span>
			<span class="logo podcastforomóviles"></span>
			<span class="podcast">Podcast – ForoMóviles</span>
			<span class="track">ForoMoviles Podcast 091: iPhone X, Galaxy Note 8, Xiaomi Mi MIX 2…</span>
		</a>
	</span>
</li>
<li>
	<span id="item-654">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/Ep106.mp3" title="¿Qué diablos es la Luz? Óptica, mecánica cuántica y física no-lineal [Ep.106]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">¿Qué diablos es la Luz? Óptica, mecánica cuántica y física no-lineal [Ep.106]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-655">
		<a href="#" data-media="http://www.ivoox.com/149-demasiado-telegram-usar-responsabilidad_mf_20904631_feed_1.mp3" title="#149 Demasiado Telegram, usar con responsabilidad">
			<span class="isplaying"></span>
			<span class="logo salmorejogeek"></span>
			<span class="podcast">Salmorejo Geek</span>
			<span class="track">#149 Demasiado Telegram, usar con responsabilidad</span>
		</a>
	</span>
</li>
<li>
	<span id="item-656">
		<a href="#" data-media="http://www.ivoox.com/episodio-7-codelearn-opennebula_mf_20898883_feed_1.mp3" title="Episodio 7 - Codelearn y OpenNebula">
			<span class="isplaying"></span>
			<span class="logo programaresunamierda"></span>
			<span class="podcast">Programar es una mierda</span>
			<span class="track">Episodio 7 - Codelearn y OpenNebula</span>
		</a>
	</span>
</li>
<li>
	<span id="item-657">
		<a href="#" data-media="https://www.ivoox.com/episodio-7-codelearn-opennebula_mf_20898883_feed_1.mp3" title="Episodio 7 - Codelearn y OpenNebula">
			<span class="isplaying"></span>
			<span class="logo programaresunamierda"></span>
			<span class="podcast">Programar es una mierda</span>
			<span class="track">Episodio 7 - Codelearn y OpenNebula</span>
		</a>
	</span>
</li>
<li>
	<span id="item-658">
		<a href="#" data-media="http://www.ivoox.com/020-entornos-productivos_mf_20895650_feed_1.mp3" title="020 - Entornos Productivos">
			<span class="isplaying"></span>
			<span class="logo aprendiendogtdpodcastproductividad"></span>
			<span class="podcast">Aprendiendo GTD podcast productividad</span>
			<span class="track">020 - Entornos Productivos</span>
		</a>
	</span>
</li>
<li>
	<span id="item-659">
		<a href="#" data-media="http://traffic.libsyn.com/cesargarciasaez/LHM108.mp3" title="LHM 108 en directo – Preguntas y proyectos con David Cuartielles (Septiembre 2017)">
			<span class="isplaying"></span>
			<span class="logo lahoramaker"></span>
			<span class="podcast">La Hora Maker</span>
			<span class="track">LHM 108 en directo – Preguntas y proyectos con David Cuartielles (Septiembre 2017)</span>
		</a>
	</span>
</li>
<li>
	<span id="item-660">
		<a href="#" data-media="https://ar.ivoox.com/es/ep128-ciencia-fantasia-agujeros-negros-fulguraciones-solares_mf_20885774_feed_1.mp3" title="Ep128: Ciencia en Fantasía; Agujeros Negros; Fulguraciones Solares; Terremotos y Luces en el Cielo; Astronautas Gemelos">
			<span class="isplaying"></span>
			<span class="logo coffeebreakseñalyruido"></span>
			<span class="podcast">Coffee Break: Señal y Ruido</span>
			<span class="track">Ep128: Ciencia en Fantasía; Agujeros Negros; Fulguraciones Solares; Terremotos y Luces en el Cielo; Astronautas Gemelos</span>
		</a>
	</span>
</li>
<li>
	<span id="item-661">
		<a href="#" data-media="http://traffic.libsyn.com/cesargarciasaez/LHM107.mp3" title="LHM 107 – Qué es la programación creativa con Marta Verde">
			<span class="isplaying"></span>
			<span class="logo lahoramaker"></span>
			<span class="podcast">La Hora Maker</span>
			<span class="track">LHM 107 – Qué es la programación creativa con Marta Verde</span>
		</a>
	</span>
</li>
<li>
	<span id="item-662">
		<a href="#" data-media="http://www.ivoox.com/neositelinux-podcast-2017-3-crossover-con_mf_20862667_feed_1.mp3" title="NeoSiteLinux Podcast 2017 - #3 - Crossover con 'A golpes de click' - Manjaro y su portatil">
			<span class="isplaying"></span>
			<span class="logo neositelinuxpodcast"></span>
			<span class="podcast">NeoSiteLinux Podcast</span>
			<span class="track">NeoSiteLinux Podcast 2017 - #3 - Crossover con 'A golpes de click' - Manjaro y su portatil</span>
		</a>
	</span>
</li>
<li>
	<span id="item-663">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/6777127/Bat2x100_159.m4a" title="#159 – Sorteo !">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#159 – Sorteo !</span>
		</a>
	</span>
</li>
<li>
	<span id="item-664">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/59b9114f9e91b02b75fcc280.mp3" title="República Independiente de watchOS">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">República Independiente de watchOS</span>
		</a>
	</span>
</li>
<li>
	<span id="item-665">
		<a href="#" data-media="https://deployando.me/podcast-download/174/20-mosh.mp3" title="20 – mosh">
			<span class="isplaying"></span>
			<span class="logo deployandome"></span>
			<span class="podcast">deployando.me</span>
			<span class="track">20 – mosh</span>
		</a>
	</span>
</li>
<li>
	<span id="item-666">
		<a href="#" data-media="http://api.spreaker.com/download/episode/12778503/webreactiva_podcast_1.mp3" title="WR 1: Un programador, una oportunidad aprovechada y pasión por el salmón">
			<span class="isplaying"></span>
			<span class="logo webreactiva"></span>
			<span class="podcast">Web Reactiva</span>
			<span class="track">WR 1: Un programador, una oportunidad aprovechada y pasión por el salmón</span>
		</a>
	</span>
</li>
<li>
	<span id="item-667">
		<a href="#" data-media="https://www.ivoox.com/s01extra02-desde-ubucon-europe-entrevistas-alan-pope-martin_mf_20826073_feed_1.mp3" title="S01Extra02 Desde Ubucon Europe: Entrevistas (Alan Pope, Martin Wimpress, Rudy y Miguel) & LexNET">
			<span class="isplaying"></span>
			<span class="logo ubuntuyotrashierbas"></span>
			<span class="podcast">Ubuntu y otras hierbas</span>
			<span class="track">S01Extra02 Desde Ubucon Europe: Entrevistas (Alan Pope, Martin Wimpress, Rudy y Miguel) & LexNET</span>
		</a>
	</span>
</li>
<li>
	<span id="item-668">
		<a href="#" data-media="http://feedproxy.google.com/~r/WecodesignPodcast/~5/1hHJDXKar8o/WeCodeSign%20Mini%2010%20-%20Empresas%20Unicornio.mp3" title="Mini 10 - Empresas unicornio">
			<span class="isplaying"></span>
			<span class="logo wecodesignpodcast"></span>
			<span class="podcast">WeCodeSign Podcast</span>
			<span class="track">Mini 10 - Empresas unicornio</span>
		</a>
	</span>
</li>
<li>
	<span id="item-669">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/6765725/Bat2x100_158.m4a" title="#158 – Volvemos ya no ? Empezamos !!">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#158 – Volvemos ya no ? Empezamos !!</span>
		</a>
	</span>
</li>
<li>
	<span id="item-670">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/59b779889e91b02b75fc97c5.mp3" title="Ofo que te cofo">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Ofo que te cofo</span>
		</a>
	</span>
</li>
<li>
	<span id="item-671">
		<a href="#" data-media="http://api.spreaker.com/download/episode/12777977/podcast118.mp3" title="#118. Medir la temperatura en líquidos con Arduino">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">#118. Medir la temperatura en líquidos con Arduino</span>
		</a>
	</span>
</li>
<li>
	<span id="item-672">
		<a href="#" data-media="http://www.ivoox.com/emacs-editor-texto-vida_mf_20808274_feed_1.mp3" title="Emacs, el editor de texto de una vida en Linux">
			<span class="isplaying"></span>
			<span class="logo procrastinaciónycafé"></span>
			<span class="podcast">Procrastinación y Café</span>
			<span class="track">Emacs, el editor de texto de una vida en Linux</span>
		</a>
	</span>
</li>
<li>
	<span id="item-673">
		<a href="#" data-media="http://www.ivoox.com/34-directo-maraton-linuxero_mf_20794227_feed_1.mp3" title="#34 Directo Maratón Linuxero">
			<span class="isplaying"></span>
			<span class="logo podcastlinux"></span>
			<span class="podcast">Podcast Linux</span>
			<span class="track">#34 Directo Maratón Linuxero</span>
		</a>
	</span>
</li>
<li>
	<span id="item-674">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/59b629ee9e91b02b75fc78b3.mp3" title="Una filtración no es un spoiler...">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Una filtración no es un spoiler...</span>
		</a>
	</span>
</li>
<li>
	<span id="item-675">
		<a href="#" data-media="http://feedproxy.google.com/~r/Vaciatubandeja/~5/Knb_2NL-Tfw/6622245.mp3" title="9: Elimina el desorden Visual | Un poco de minimalismo">
			<span class="isplaying"></span>
			<span class="logo vacíatubandeja"></span>
			<span class="podcast">Vacía tu bandeja</span>
			<span class="track">9: Elimina el desorden Visual | Un poco de minimalismo</span>
		</a>
	</span>
</li>
<li>
	<span id="item-676">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/09/podcast-50-sandstorm.mp3" title="Podcast #50: Sandstorm">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #50: Sandstorm</span>
		</a>
	</span>
</li>
<li>
	<span id="item-677">
		<a href="#" data-media="http://traffic.libsyn.com/cesargarciasaez/LHM106.mp3" title="LHM 106 – Exploramos la nube y gran avance de los eventos del otoño">
			<span class="isplaying"></span>
			<span class="logo lahoramaker"></span>
			<span class="podcast">La Hora Maker</span>
			<span class="track">LHM 106 – Exploramos la nube y gran avance de los eventos del otoño</span>
		</a>
	</span>
</li>
<li>
	<span id="item-678">
		<a href="#" data-media="http://feedproxy.google.com/~r/Vaciatubandeja/~5/wHXO1CeBYXU/09%20Elimina%20el%20desorden%20visual.mp3" title="#09-Elimina el desorden Visual | Un poco de minimalismo">
			<span class="isplaying"></span>
			<span class="logo vaciatubandeja"></span>
			<span class="podcast">Vacia Tu Bandeja</span>
			<span class="track">#09-Elimina el desorden Visual | Un poco de minimalismo</span>
		</a>
	</span>
</li>
<li>
	<span id="item-679">
		<a href="#" data-media="http://www.ivoox.com/blackview-a7-smartphone-sorprendente_mf_20776730_feed_1.mp3" title="Blackview A7. Smartphone sorprendente">
			<span class="isplaying"></span>
			<span class="logo mosqueterowebtecnologialinuxchromebooks"></span>
			<span class="podcast">Mosqueteroweb tecnologia, Linux, Chromebooks</span>
			<span class="track">Blackview A7. Smartphone sorprendente</span>
		</a>
	</span>
</li>
<li>
	<span id="item-680">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/09/podcast-49-youphptube-tu-propio-you-tube.mp3" title="Podcast #49: YouPHPTube, tu propio You Tube">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #49: YouPHPTube, tu propio You Tube</span>
		</a>
	</span>
</li>
<li>
	<span id="item-681">
		<a href="#" data-media="http://compilando.audio/wp-content/uploads/2017/09/Podcast13-MaratonLinuxero.mp3" title="Podcast 13 – Maratón Linuxero">
			<span class="isplaying"></span>
			<span class="logo compilandopodcast"></span>
			<span class="podcast">Compilando Podcast</span>
			<span class="track">Podcast 13 – Maratón Linuxero</span>
		</a>
	</span>
</li>
<li>
	<span id="item-682">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/09/podcast-48-escritorio-en-la-nube-con-x2go.mp3" title="Podcast #48: Escritorio en la nube con x2Go">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #48: Escritorio en la nube con x2Go</span>
		</a>
	</span>
</li>
<li>
	<span id="item-683">
		<a href="#" data-media="http://www.ivoox.com/neositelinux-podcast-2017-2-resaca-del-maraton_mf_20759935_feed_1.mp3" title="NeoSiteLinux Podcast 2017 - #2 Resaca del Maratón Linuxero">
			<span class="isplaying"></span>
			<span class="logo neositelinuxpodcast"></span>
			<span class="podcast">NeoSiteLinux Podcast</span>
			<span class="track">NeoSiteLinux Podcast 2017 - #2 Resaca del Maratón Linuxero</span>
		</a>
	</span>
</li>
<li>
	<span id="item-684">
		<a href="#" data-media="http://www.ivoox.com/aplicaciones-gadgets-del-verano-cap-75_mf_20754525_feed_1.mp3" title="Aplicaciones y gadgets del verano - Cap 75">
			<span class="isplaying"></span>
			<span class="logo podcastwintabletinfo"></span>
			<span class="podcast">Podcast WINTABLET.INFO</span>
			<span class="track">Aplicaciones y gadgets del verano - Cap 75</span>
		</a>
	</span>
</li>
<li>
	<span id="item-685">
		<a href="#" data-media="https://archive.org/download/34LinktreePlusdede/34-linktree-plusdede.mp3" title="#34 Linktree y Plusdede">
			<span class="isplaying"></span>
			<span class="logo educandogeek"></span>
			<span class="podcast">eDucando Geek</span>
			<span class="track">#34 Linktree y Plusdede</span>
		</a>
	</span>
</li>
<li>
	<span id="item-686">
		<a href="#" data-media="https://ar.ivoox.com/es/ep127-babilonia-estrella-tabby-fast-radio-bursts_mf_20747354_feed_1.mp3" title="Ep127: Babilonia; Estrella de Tabby; Fast Radio Bursts">
			<span class="isplaying"></span>
			<span class="logo coffeebreakseñalyruido"></span>
			<span class="podcast">Coffee Break: Señal y Ruido</span>
			<span class="track">Ep127: Babilonia; Estrella de Tabby; Fast Radio Bursts</span>
		</a>
	</span>
</li>
<li>
	<span id="item-687">
		<a href="#" data-media="http://api.spreaker.com/download/episode/12739776/s2e09_rrhh_y_recruiters_con_justyna_adam_y_lordmccord.mp3" title="S2E09 RRHH y recruiters con @Justyna_Adam y @LordMcCord">
			<span class="isplaying"></span>
			<span class="logo codeontherocks"></span>
			<span class="podcast">Code on the rocks</span>
			<span class="track">S2E09 RRHH y recruiters con @Justyna_Adam y @LordMcCord</span>
		</a>
	</span>
</li>
<li>
	<span id="item-688">
		<a href="#" data-media="https://gitlab.com/podcastlinux/podcastlinux.gitlab.io/raw/master/Linux-Express/%2323%20Podcast%20Linux%20Express.mp3" title="#23 Linux Express">
			<span class="isplaying"></span>
			<span class="logo linuxexpressdepodcastlinux"></span>
			<span class="podcast">Linux Express, de Podcast Linux.</span>
			<span class="track">#23 Linux Express</span>
		</a>
	</span>
</li>
<li>
	<span id="item-689">
		<a href="#" data-media="http://feedproxy.google.com/~r/WecodesignPodcast/~5/RMjcnA7PPNk/WeCodeSign%202x06%20-%20Accesibilidad%20Pra%CC%81ctica.mp3" title="2x06 - Accesibilidad Práctica">
			<span class="isplaying"></span>
			<span class="logo wecodesignpodcast"></span>
			<span class="podcast">WeCodeSign Podcast</span>
			<span class="track">2x06 - Accesibilidad Práctica</span>
		</a>
	</span>
</li>
<li>
	<span id="item-690">
		<a href="#" data-media="http://www.ivoox.com/jugando-gnu-linux-emision-maraton-linuxero_mf_20696395_feed_1.mp3" title="Jugando en GNU/Linux - Emisión Maratón Linuxero">
			<span class="isplaying"></span>
			<span class="logo neositelinuxpodcast"></span>
			<span class="podcast">NeoSiteLinux Podcast</span>
			<span class="track">Jugando en GNU/Linux - Emisión Maratón Linuxero</span>
		</a>
	</span>
</li>
<li>
	<span id="item-691">
		<a href="#" data-media="http://tracking.feedpress.it/link/15407/6688337/BCS016-Neutralidad-de-la-Red.mp3" title="BCS016 – Neutralidad de la Red">
			<span class="isplaying"></span>
			<span class="logo bitácoradeciberseguridad"></span>
			<span class="podcast">Bitácora de Ciberseguridad</span>
			<span class="track">BCS016 – Neutralidad de la Red</span>
		</a>
	</span>
</li>
<li>
	<span id="item-692">
		<a href="#" data-media="https://ia601500.us.archive.org/19/items/076.UnServidorEnMiCasaMaratnLinuxero/076.%20Un%20Servidor%20en%20mi%20Casa%20-%20Marat%C3%B3n%20Linuxero.mp3" title="076. Un Servidor en mi Casa - Podcast del Maratón Linuxero 2017">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">076. Un Servidor en mi Casa - Podcast del Maratón Linuxero 2017</span>
		</a>
	</span>
</li>
<li>
	<span id="item-693">
		<a href="#" data-media="http://www.ivoox.com/servidor-casero-ugeek-maraton-linuxero-3-9-17_mf_20680980_feed_1.mp3" title="Servidor Casero con ugeek en Maraton Linuxero 3/9/17">
			<span class="isplaying"></span>
			<span class="logo mosqueterowebtecnologialinuxchromebooks"></span>
			<span class="podcast">Mosqueteroweb tecnologia, Linux, Chromebooks</span>
			<span class="track">Servidor Casero con ugeek en Maraton Linuxero 3/9/17</span>
		</a>
	</span>
</li>
<li>
	<span id="item-694">
		<a href="#" data-media="http://www.ivoox.com/episodio-6-graphql-falcor_mf_20680974_feed_1.mp3" title="Episodio 6 - GraphQL y Falcor">
			<span class="isplaying"></span>
			<span class="logo programaresunamierda"></span>
			<span class="podcast">Programar es una mierda</span>
			<span class="track">Episodio 6 - GraphQL y Falcor</span>
		</a>
	</span>
</li>
<li>
	<span id="item-695">
		<a href="#" data-media="https://www.ivoox.com/episodio-6-graphql-falcor_mf_20680974_feed_1.mp3" title="Episodio 6 - GraphQL y Falcor">
			<span class="isplaying"></span>
			<span class="logo programaresunamierda"></span>
			<span class="podcast">Programar es una mierda</span>
			<span class="track">Episodio 6 - GraphQL y Falcor</span>
		</a>
	</span>
</li>
<li>
	<span id="item-696">
		<a href="#" data-media="https://www.ivoox.com/s01extra01-maraton-linuxero-ubucon-europea-drm-en_mf_20679885_feed_1.mp3" title="S01Extra01 Maratón Linuxero. Ubucon Europea y DRM en HTML5">
			<span class="isplaying"></span>
			<span class="logo ubuntuyotrashierbas"></span>
			<span class="podcast">Ubuntu y otras hierbas</span>
			<span class="track">S01Extra01 Maratón Linuxero. Ubucon Europea y DRM en HTML5</span>
		</a>
	</span>
</li>
<li>
	<span id="item-697">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/09/podcast-47-directo-maraton-linuxero.mp3" title="Podcast #47: Mi intervención en el Maratón Linuxero">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #47: Mi intervención en el Maratón Linuxero</span>
		</a>
	</span>
</li>
<li>
	<span id="item-698">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/Ep105Bonus.mp3" title="El arte de capturar el universo, homenaje a Daniel Verschatse [Ep.Bonus]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">El arte de capturar el universo, homenaje a Daniel Verschatse [Ep.Bonus]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-699">
		<a href="#" data-media="https://archive.org/download/MaratonLinuxero9CompilandoPodcast/Marat%C3%B3n%20Linuxero%209%20Compilando%20Podcast.ogg" title="#09 Maratón Linuxero I: Compilando Podcast">
			<span class="isplaying"></span>
			<span class="logo maratónlinuxero"></span>
			<span class="podcast">Maratón Linuxero</span>
			<span class="track">#09 Maratón Linuxero I: Compilando Podcast</span>
		</a>
	</span>
</li>
<li>
	<span id="item-700">
		<a href="#" data-media="https://archive.org/download/MaratonLinuxero8Jugando/Marat%C3%B3n%20Linuxero%208%20Jugandoen%20GNULinux.ogg" title="#08 Maratón Linuxero I: Jugando en GNU/Linux">
			<span class="isplaying"></span>
			<span class="logo maratónlinuxero"></span>
			<span class="podcast">Maratón Linuxero</span>
			<span class="track">#08 Maratón Linuxero I: Jugando en GNU/Linux</span>
		</a>
	</span>
</li>
<li>
	<span id="item-701">
		<a href="#" data-media="https://archive.org/download/MaratonLinuxero7UgeekYMosqueteroWeb/Marat%C3%B3n%20Linuxero%207%20Ugeek%20y%20Mosquetero%20Web.ogg" title="#07 Maratón Linuxero I: uGeek y Mosquetero Web">
			<span class="isplaying"></span>
			<span class="logo maratónlinuxero"></span>
			<span class="podcast">Maratón Linuxero</span>
			<span class="track">#07 Maratón Linuxero I: uGeek y Mosquetero Web</span>
		</a>
	</span>
</li>
<li>
	<span id="item-702">
		<a href="#" data-media="https://archive.org/download/MaratonLinuxero6UbuntuYOtrasHierbas/Marat%C3%B3n%20Linuxero%206%20Ubuntu%20y%20otras%20hierbas.ogg" title="#06 Maratón Linuxero I: Ubuntu y otras hierbas">
			<span class="isplaying"></span>
			<span class="logo maratónlinuxero"></span>
			<span class="podcast">Maratón Linuxero</span>
			<span class="track">#06 Maratón Linuxero I: Ubuntu y otras hierbas</span>
		</a>
	</span>
</li>
<li>
	<span id="item-703">
		<a href="#" data-media="https://archive.org/download/MaratonLinuxero5KDEEspana/Marat%C3%B3n%20Linuxero%205%20KDE%20Espa%C3%B1a.ogg" title="#05 Maratón Linuxero I: KDE España">
			<span class="isplaying"></span>
			<span class="logo maratónlinuxero"></span>
			<span class="podcast">Maratón Linuxero</span>
			<span class="track">#05 Maratón Linuxero I: KDE España</span>
		</a>
	</span>
</li>
<li>
	<span id="item-704">
		<a href="#" data-media="https://archive.org/download/MaratonLinuxero4Audio/Marat%C3%B3n%20Linuxero%204%20Audio.ogg" title="#04 Maratón Linuxero I: Audio y Música en GNU/Linux">
			<span class="isplaying"></span>
			<span class="logo maratónlinuxero"></span>
			<span class="podcast">Maratón Linuxero</span>
			<span class="track">#04 Maratón Linuxero I: Audio y Música en GNU/Linux</span>
		</a>
	</span>
</li>
<li>
	<span id="item-705">
		<a href="#" data-media="https://archive.org/download/MaratonLinuxero3SalmorejoGeek/Marat%C3%B3n%20Linuxero%203%20Salmorejo%20Geek.ogg" title="#03 Maratón Linuxero I: Salmorejo Geek">
			<span class="isplaying"></span>
			<span class="logo maratónlinuxero"></span>
			<span class="podcast">Maratón Linuxero</span>
			<span class="track">#03 Maratón Linuxero I: Salmorejo Geek</span>
		</a>
	</span>
</li>
<li>
	<span id="item-706">
		<a href="#" data-media="https://archive.org/download/MaratonLinuxero2EduardoCollado/Marat%C3%B3n%20Linuxero%202%20Eduardo%20Collado.ogg" title="#02 Maratón Linuxero I: Eduardo Collado">
			<span class="isplaying"></span>
			<span class="logo maratónlinuxero"></span>
			<span class="podcast">Maratón Linuxero</span>
			<span class="track">#02 Maratón Linuxero I: Eduardo Collado</span>
		</a>
	</span>
</li>
<li>
	<span id="item-707">
		<a href="#" data-media="https://archive.org/download/MaratonLinuxero1PodcastLinux/Marat%C3%B3n%20Linuxero%201%20PodcastLinux.ogg" title="#01 Maratón Linuxero I: Podcast Linux">
			<span class="isplaying"></span>
			<span class="logo maratónlinuxero"></span>
			<span class="podcast">Maratón Linuxero</span>
			<span class="track">#01 Maratón Linuxero I: Podcast Linux</span>
		</a>
	</span>
</li>
<li>
	<span id="item-708">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/Ep105.mp3" title="De la Tierra al Cielo, el arte de la fotografía nocturna [Ep.105]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">De la Tierra al Cielo, el arte de la fotografía nocturna [Ep.105]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-709">
		<a href="#" data-media="https://ia601508.us.archive.org/22/items/075.RespuestaDePreguntasYMaraton/075.%20Respuesta%20de%20Preguntas%20y%20Maraton.mp3" title="075. Respuestas a Preguntas de los Oyentes y Maratón Linuxero">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">075. Respuestas a Preguntas de los Oyentes y Maratón Linuxero</span>
		</a>
	</span>
</li>
<li>
	<span id="item-710">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/09/podcast-46-mejorar-apariencia-gnu-social.mp3" title="Podcast #46: Mejorar la imagen de GNU Social con Qvitter">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #46: Mejorar la imagen de GNU Social con Qvitter</span>
		</a>
	</span>
</li>
<li>
	<span id="item-711">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/59a933636df7fd2b59ebc184.mp3" title="Xiaomi tira el guante a Apple (¡Nota importante sobre el podcast!)">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Xiaomi tira el guante a Apple (¡Nota importante sobre el podcast!)</span>
		</a>
	</span>
</li>
<li>
	<span id="item-712">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/08/podcast-45-instalacion-gnu-social.mp3" title="Podcast #45: Instalación de GNUSocial">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #45: Instalación de GNUSocial</span>
		</a>
	</span>
</li>
<li>
	<span id="item-713">
		<a href="#" data-media="https://ar.ivoox.com/es/ep126-juego-tronos-tensiones-cosmologicas-dark_mf_20622026_feed_1.mp3" title="Ep126: Juego de Tronos; Tensiones Cosmológicas y Dark Energy Survey; Teorías Alternativas; Rotación en el Universo">
			<span class="isplaying"></span>
			<span class="logo coffeebreakseñalyruido"></span>
			<span class="podcast">Coffee Break: Señal y Ruido</span>
			<span class="track">Ep126: Juego de Tronos; Tensiones Cosmológicas y Dark Energy Survey; Teorías Alternativas; Rotación en el Universo</span>
		</a>
	</span>
</li>
<li>
	<span id="item-714">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/59a7f0306df7fd2b59ebb125.mp3" title="Desde Berlín con calor">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Desde Berlín con calor</span>
		</a>
	</span>
</li>
<li>
	<span id="item-715">
		<a href="#" data-media="https://archive.org/download/33Freedompop4gLogitechmk270Carbocage/33-freedompop4g-logitechmk270-carbocage.mp3" title="#33 FreedomPop 4G - Teclado - Carbocaje">
			<span class="isplaying"></span>
			<span class="logo educandogeek"></span>
			<span class="podcast">eDucando Geek</span>
			<span class="track">#33 FreedomPop 4G - Teclado - Carbocaje</span>
		</a>
	</span>
</li>
<li>
	<span id="item-716">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/59a68a029e91b02b75fbb604.mp3" title="Can I get an ARCore? Do you want more?">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Can I get an ARCore? Do you want more?</span>
		</a>
	</span>
</li>
<li>
	<span id="item-717">
		<a href="#" data-media="https://ia601507.us.archive.org/20/items/074.NotasYFeed/074.%20Notas%20y%20Feed.mp3" title="074. Me explicáis como tomáis vuestras Notas. Y Que es uGeekRadio">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">074. Me explicáis como tomáis vuestras Notas. Y Que es uGeekRadio</span>
		</a>
	</span>
</li>
<li>
	<span id="item-718">
		<a href="#" data-media="http://www.ivoox.com/33-1-directo-podcast-linux_mf_20569029_feed_1.mp3" title="#33 1º Directo Podcast Linux">
			<span class="isplaying"></span>
			<span class="logo podcastlinux"></span>
			<span class="podcast">Podcast Linux</span>
			<span class="track">#33 1º Directo Podcast Linux</span>
		</a>
	</span>
</li>
<li>
	<span id="item-719">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/59a6230a9e91b02b75fba0bf.mp3" title="Programadores ciegos y un gran otoño para los smartphones">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Programadores ciegos y un gran otoño para los smartphones</span>
		</a>
	</span>
</li>
<li>
	<span id="item-720">
		<a href="#" data-media="http://www.ivoox.com/019-los-contextos-gtd_mf_20554370_feed_1.mp3" title="019 - Los contextos en GTD">
			<span class="isplaying"></span>
			<span class="logo aprendiendogtdpodcastproductividad"></span>
			<span class="podcast">Aprendiendo GTD podcast productividad</span>
			<span class="track">019 - Los contextos en GTD</span>
		</a>
	</span>
</li>
<li>
	<span id="item-721">
		<a href="#" data-media="http://www.ivoox.com/informe-mozilla-sobre-salud-internet_mf_20544648_feed_1.mp3" title="El informe Mozilla sobre la salud de internet | Episodio 62">
			<span class="isplaying"></span>
			<span class="logo repúblicaweb"></span>
			<span class="podcast">República Web</span>
			<span class="track">El informe Mozilla sobre la salud de internet | Episodio 62</span>
		</a>
	</span>
</li>
<li>
	<span id="item-722">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/6602296/Bat2x100_157.m4a" title="#157 – Un podcast raro">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#157 – Un podcast raro</span>
		</a>
	</span>
</li>
<li>
	<span id="item-723">
		<a href="#" data-media="http://www.ivoox.com/retroactivo-67-la-consola-atari-jaguar_mf_20539380_feed_1.mp3" title="RetroActivo #67: La consola Atari Jaguar">
			<span class="isplaying"></span>
			<span class="logo retroactivopodcast"></span>
			<span class="podcast">RetroActivo Podcast</span>
			<span class="track">RetroActivo #67: La consola Atari Jaguar</span>
		</a>
	</span>
</li>
<li>
	<span id="item-724">
		<a href="#" data-media="https://archive.org/download/04UltimoEnsayo/%2304UltimoEnsayo.ogg" title="#04 Último ensayo del Maratón Linuxero">
			<span class="isplaying"></span>
			<span class="logo maratónlinuxero"></span>
			<span class="podcast">Maratón Linuxero</span>
			<span class="track">#04 Último ensayo del Maratón Linuxero</span>
		</a>
	</span>
</li>
<li>
	<span id="item-725">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/08/podcast-44-la-red-en-gnu-linux.mp3" title="Podcast #44: Redes en GNU/Linux">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #44: Redes en GNU/Linux</span>
		</a>
	</span>
</li>
<li>
	<span id="item-726">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/Ep104.mp3" title="¿Encontraremos vida en otros planetas? [Ep.104]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">¿Encontraremos vida en otros planetas? [Ep.104]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-727">
		<a href="#" data-media="http://tracking.feedpress.it/link/15407/6582468/BCS015-Primer-Aniversario.mp3" title="BCS015 – Primer Aniversario de Bitácora de Ciberseguridad">
			<span class="isplaying"></span>
			<span class="logo bitácoradeciberseguridad"></span>
			<span class="podcast">Bitácora de Ciberseguridad</span>
			<span class="track">BCS015 – Primer Aniversario de Bitácora de Ciberseguridad</span>
		</a>
	</span>
</li>
<li>
	<span id="item-728">
		<a href="#" data-media="http://api.spreaker.com/download/episode/12644162/cap33_review_linux_macbook_pro.mp3" title="cap33 - Review Linux MacBook Pro 2008">
			<span class="isplaying"></span>
			<span class="logo podcastdmanuelalonso"></span>
			<span class="podcast">Podcast dmanuelalonso</span>
			<span class="track">cap33 - Review Linux MacBook Pro 2008</span>
		</a>
	</span>
</li>
<li>
	<span id="item-729">
		<a href="#" data-media="http://traffic.libsyn.com/cesargarciasaez/LHM105.mp3" title="LHM 105 – Emprendiendo con la impresion 3D de la mano de Diego Trapero">
			<span class="isplaying"></span>
			<span class="logo lahoramaker"></span>
			<span class="podcast">La Hora Maker</span>
			<span class="track">LHM 105 – Emprendiendo con la impresion 3D de la mano de Diego Trapero</span>
		</a>
	</span>
</li>
<li>
	<span id="item-730">
		<a href="#" data-media="http://podcast.edyo.es/podcast/edyo-28.mp3" title="Edyo 28 - La tecnología detrás de Entredevyops">
			<span class="isplaying"></span>
			<span class="logo entredevyopspodcast"></span>
			<span class="podcast">EntreDevYOps Podcast</span>
			<span class="track">Edyo 28 - La tecnología detrás de Entredevyops</span>
		</a>
	</span>
</li>
<li>
	<span id="item-731">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/599d92ab6df7fd2b59eb7657.mp3" title="Apple pilla el coche por los cuernos">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Apple pilla el coche por los cuernos</span>
		</a>
	</span>
</li>
<li>
	<span id="item-732">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/599b8dc19e91b02b75fb2b4c.mp3" title="Android O va a tardar, pero...">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Android O va a tardar, pero...</span>
		</a>
	</span>
</li>
<li>
	<span id="item-733">
		<a href="#" data-media="http://compilando.audio/wp-content/uploads/2017/08/podcast12.mp3" title="Podcast 12 – Empleo y Negocio en software libre con Carlos Rodriguez (Librebit-AGASOL) y Maratón Linuxero.">
			<span class="isplaying"></span>
			<span class="logo compilandopodcast"></span>
			<span class="podcast">Compilando Podcast</span>
			<span class="track">Podcast 12 – Empleo y Negocio en software libre con Carlos Rodriguez (Librebit-AGASOL) y Maratón Linuxero.</span>
		</a>
	</span>
</li>
<li>
	<span id="item-734">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/599a3b079e91b02b75fb0968.mp3" title="Tempus fugit et augebitur scientia">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Tempus fugit et augebitur scientia</span>
		</a>
	</span>
</li>
<li>
	<span id="item-735">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/08/podcast-43-pfsense.mp3" title="Podcast #43: PfSense">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #43: PfSense</span>
		</a>
	</span>
</li>
<li>
	<span id="item-736">
		<a href="#" data-media="http://feedproxy.google.com/~r/Vaciatubandeja/~5/0966D3nKlGM/08-Bullet%20Journal%20-%20Chronodex.%20Gestiona%20tu%20tiempo%20de%20forma%20visual.mp3" title="#08-Bullet Journal | Chronodex: Gestiona tu tiempo de forma visual">
			<span class="isplaying"></span>
			<span class="logo vaciatubandeja"></span>
			<span class="podcast">Vacia Tu Bandeja</span>
			<span class="track">#08-Bullet Journal | Chronodex: Gestiona tu tiempo de forma visual</span>
		</a>
	</span>
</li>
<li>
	<span id="item-737">
		<a href="#" data-media="http://www.podtrac.com/pts/redirect.mp3/www.wedevelopers.com/podcast/wedevelopers048.mp3" title="We.Developers 048 – Drupal">
			<span class="isplaying"></span>
			<span class="logo wedevelopers"></span>
			<span class="podcast">We.Developers</span>
			<span class="track">We.Developers 048 – Drupal</span>
		</a>
	</span>
</li>
<li>
	<span id="item-738">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/08/podcast-42-routers-en-gnu-linux.mp3" title="Podcast #42: Routers sobre GNU/Linux">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #42: Routers sobre GNU/Linux</span>
		</a>
	</span>
</li>
<li>
	<span id="item-739">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/5997b6c79e91b02b75fad7ec.mp3" title="Cine en tu casa sí, pero a qué precio">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Cine en tu casa sí, pero a qué precio</span>
		</a>
	</span>
</li>
<li>
	<span id="item-740">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/6530215/Bat2x100_156.m4a" title="#156 – Atentado en Barcelona y algo de tecnología.">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#156 – Atentado en Barcelona y algo de tecnología.</span>
		</a>
	</span>
</li>
<li>
	<span id="item-741">
		<a href="#" data-media="http://www.ivoox.com/19-de-verdad-crees-hay-necesidad-de_mf_20399669_feed_1.mp3" title="#19 ¿De verdad crees que hay necesidad de dar ese testimonio gráfico?">
			<span class="isplaying"></span>
			<span class="logo reflexpodcast"></span>
			<span class="podcast">reflex podcast</span>
			<span class="track">#19 ¿De verdad crees que hay necesidad de dar ese testimonio gráfico?</span>
		</a>
	</span>
</li>
<li>
	<span id="item-742">
		<a href="#" data-media="http://api.spreaker.com/download/episode/12597463/deknet_20170817_1826_2.mp3" title="DekNet 2017">
			<span class="isplaying"></span>
			<span class="logo deknet"></span>
			<span class="podcast">DekNet</span>
			<span class="track">DekNet 2017</span>
		</a>
	</span>
</li>
<li>
	<span id="item-743">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/Ep103.mp3" title="Eclipse 21 de Agosto EEUU – Todo lo que debes saber [Ep.103]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Eclipse 21 de Agosto EEUU – Todo lo que debes saber [Ep.103]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-744">
		<a href="#" data-media="http://api.spreaker.com/download/episode/12594904/cap32_linux_en_el_macbookpro.mp3" title="cap32 - Linux en el Macbook Pro">
			<span class="isplaying"></span>
			<span class="logo podcastdmanuelalonso"></span>
			<span class="podcast">Podcast dmanuelalonso</span>
			<span class="track">cap32 - Linux en el Macbook Pro</span>
		</a>
	</span>
</li>
<li>
	<span id="item-745">
		<a href="#" data-media="http://traffic.libsyn.com/cesargarciasaez/LHM104.mp3" title="LHM 104 – Milena Orlandini nos acerca al espacio desde Tinkerers Lab">
			<span class="isplaying"></span>
			<span class="logo lahoramaker"></span>
			<span class="podcast">La Hora Maker</span>
			<span class="track">LHM 104 – Milena Orlandini nos acerca al espacio desde Tinkerers Lab</span>
		</a>
	</span>
</li>
<li>
	<span id="item-746">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/599505a39e91b02b75faa82e.mp3" title="Azafatos para el coche autónomo">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Azafatos para el coche autónomo</span>
		</a>
	</span>
</li>
<li>
	<span id="item-747">
		<a href="#" data-media="http://www.ivoox.com/poder-conversacion-era_mf_20371319_feed_1.mp3" title="El poder de la conversación en la era digital | Episodio 61">
			<span class="isplaying"></span>
			<span class="logo repúblicaweb"></span>
			<span class="podcast">República Web</span>
			<span class="track">El poder de la conversación en la era digital | Episodio 61</span>
		</a>
	</span>
</li>
<li>
	<span id="item-748">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/6510774/Bat2x100_155.m4a" title="#155 – Vacaciones tecnológicas.">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#155 – Vacaciones tecnológicas.</span>
		</a>
	</span>
</li>
<li>
	<span id="item-749">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/5993f94e9e91b02b75fa8803.mp3" title="Mis datos son míos, ¿o no?">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Mis datos son míos, ¿o no?</span>
		</a>
	</span>
</li>
<li>
	<span id="item-750">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/5992d03d9e91b02b75fa64c4.mp3" title="Te receto un Apple Watch">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Te receto un Apple Watch</span>
		</a>
	</span>
</li>
<li>
	<span id="item-751">
		<a href="#" data-media="http://ia801503.us.archive.org/30/items/NolegaltechRadio/000-NOlegaltechRadio.mp3" title="#000-Presentación del podcast">
			<span class="isplaying"></span>
			<span class="logo nolegaltechradio"></span>
			<span class="podcast">NOlegaltech Radio</span>
			<span class="track">#000-Presentación del podcast</span>
		</a>
	</span>
</li>
<li>
	<span id="item-752">
		<a href="#" data-media="http://www.ivoox.com/32-linux-connexion-reciclanet_mf_20316104_feed_1.mp3" title="#32 Linux Connexion con Reciclanet">
			<span class="isplaying"></span>
			<span class="logo podcastlinux"></span>
			<span class="podcast">Podcast Linux</span>
			<span class="track">#32 Linux Connexion con Reciclanet</span>
		</a>
	</span>
</li>
<li>
	<span id="item-753">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/6490695/Bat2x100_154.m4a" title="#154 – Crossover con … Tecnologistas !">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#154 – Crossover con … Tecnologistas !</span>
		</a>
	</span>
</li>
<li>
	<span id="item-754">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/599254ef9e91b02b75fa5388.mp3" title="are we humans... or are we dota-2-player-bots?">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">are we humans... or are we dota-2-player-bots?</span>
		</a>
	</span>
</li>
<li>
	<span id="item-755">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/08/podcast-41-maraton-grabacion-y-transmision.mp3" title="Podcast #41: Maratón Linuxsero, grabación de podcast y transmisión en vídeo">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #41: Maratón Linuxsero, grabación de podcast y transmisión en vídeo</span>
		</a>
	</span>
</li>
<li>
	<span id="item-756">
		<a href="#" data-media="http://api.spreaker.com/download/episode/12564683/cap31_aplicaciones_en_linux_y_brave.mp3" title="cap31 - Aplicaciones en Linux y Brave">
			<span class="isplaying"></span>
			<span class="logo podcastdmanuelalonso"></span>
			<span class="podcast">Podcast dmanuelalonso</span>
			<span class="track">cap31 - Aplicaciones en Linux y Brave</span>
		</a>
	</span>
</li>
<li>
	<span id="item-757">
		<a href="#" data-media="http://traffic.libsyn.com/cesargarciasaez/LHM103.mp3" title="LHM 103 en directo – Preguntas y proyectos con David Cuartielles (Agosto 2017)">
			<span class="isplaying"></span>
			<span class="logo lahoramaker"></span>
			<span class="podcast">La Hora Maker</span>
			<span class="track">LHM 103 en directo – Preguntas y proyectos con David Cuartielles (Agosto 2017)</span>
		</a>
	</span>
</li>
<li>
	<span id="item-758">
		<a href="#" data-media="https://archive.org/download/03NovedadesEnElMaratnLinuxero/%2303%20Novedades%20en%20el%20Marat%C3%B3n%20Linuxero.ogg" title="#03 Novedades en el Maratón Linuxero">
			<span class="isplaying"></span>
			<span class="logo maratónlinuxero"></span>
			<span class="podcast">Maratón Linuxero</span>
			<span class="track">#03 Novedades en el Maratón Linuxero</span>
		</a>
	</span>
</li>
<li>
	<span id="item-759">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/Ep102.mp3" title="El tamaño del universo, ¿cómo lo llegamos a conocer? [Ep.102]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">El tamaño del universo, ¿cómo lo llegamos a conocer? [Ep.102]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-760">
		<a href="#" data-media="http://www.ivoox.com/neositelinux-podcast-2017-1-un-poco-de_mf_20294550_feed_1.mp3" title="NeoSiteLinux Podcast 2017 - #1 Un poco de todo">
			<span class="isplaying"></span>
			<span class="logo neositelinuxpodcast"></span>
			<span class="podcast">NeoSiteLinux Podcast</span>
			<span class="track">NeoSiteLinux Podcast 2017 - #1 Un poco de todo</span>
		</a>
	</span>
</li>
<li>
	<span id="item-761">
		<a href="#" data-media="https://archive.org/download/32Raspi3BujoAnchor/32-raspi3-bujo-anchor.mp3" title="#32 Montando un servidor con una Raspberry Pi 3 - Bullet Journal, un sistema de organización personal analógico - Leyendo Voy, mi nuevo podcast de libros y lectura en Anchor">
			<span class="isplaying"></span>
			<span class="logo educandogeek"></span>
			<span class="podcast">eDucando Geek</span>
			<span class="track">#32 Montando un servidor con una Raspberry Pi 3 - Bullet Journal, un sistema de organización personal analógico - Leyendo Voy, mi nuevo podcast de libros y lectura en Anchor</span>
		</a>
	</span>
</li>
<li>
	<span id="item-762">
		<a href="#" data-media="http://www.ivoox.com/algo-polemica-editores-texto-fundamentales_mf_20275692_feed_1.mp3" title="Algo de polémica y editores de texto fundamentales en GNU/Linux">
			<span class="isplaying"></span>
			<span class="logo procrastinaciónycafé"></span>
			<span class="podcast">Procrastinación y Café</span>
			<span class="track">Algo de polémica y editores de texto fundamentales en GNU/Linux</span>
		</a>
	</span>
</li>
<li>
	<span id="item-763">
		<a href="#" data-media="http://traffic.libsyn.com/cesargarciasaez/LHM102.mp3" title="LHM 102 – Descubre el arte digital con Varvara Guljajeva y Mar Canet">
			<span class="isplaying"></span>
			<span class="logo lahoramaker"></span>
			<span class="podcast">La Hora Maker</span>
			<span class="track">LHM 102 – Descubre el arte digital con Varvara Guljajeva y Mar Canet</span>
		</a>
	</span>
</li>
<li>
	<span id="item-764">
		<a href="#" data-media="http://www.ivoox.com/instalacion-nuevo-disco-hibrido-sshd-tests-en_mf_20255876_feed_1.mp3" title="Instalación nuevo disco híbrido SSHD y tests en Linux">
			<span class="isplaying"></span>
			<span class="logo mosqueterowebtecnologialinuxchromebooks"></span>
			<span class="podcast">Mosqueteroweb tecnologia, Linux, Chromebooks</span>
			<span class="track">Instalación nuevo disco híbrido SSHD y tests en Linux</span>
		</a>
	</span>
</li>
<li>
	<span id="item-765">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/598a95f69e91b02b75f9ff98.mp3" title="El riesgo de abandonar Netflix">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">El riesgo de abandonar Netflix</span>
		</a>
	</span>
</li>
<li>
	<span id="item-766">
		<a href="#" data-media="https://deployando.me/podcast-download/171/administradores-de-configuracion-02.mp3" title="19 – Administradores de Configuración 02">
			<span class="isplaying"></span>
			<span class="logo deployandome"></span>
			<span class="podcast">deployando.me</span>
			<span class="track">19 – Administradores de Configuración 02</span>
		</a>
	</span>
</li>
<li>
	<span id="item-767">
		<a href="#" data-media="http://www.ivoox.com/mintablet-tablet-o-convertible-windows_mf_20239255_feed_1.mp3" title="minTablet - Tablet o Convertible Windows">
			<span class="isplaying"></span>
			<span class="logo podcastwintabletinfo"></span>
			<span class="podcast">Podcast WINTABLET.INFO</span>
			<span class="track">minTablet - Tablet o Convertible Windows</span>
		</a>
	</span>
</li>
<li>
	<span id="item-768">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/598a8fcd9e91b02b75f9f859.mp3" title="Walkie Talkies mágicos">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Walkie Talkies mágicos</span>
		</a>
	</span>
</li>
<li>
	<span id="item-769">
		<a href="#" data-media="http://api.spreaker.com/download/episode/12530934/cap_30_mis_dispositivos_y_vuelta_al_podcast.mp3" title="cap 30 - Mis dispositivos y vuelta al podcast">
			<span class="isplaying"></span>
			<span class="logo podcastdmanuelalonso"></span>
			<span class="podcast">Podcast dmanuelalonso</span>
			<span class="track">cap 30 - Mis dispositivos y vuelta al podcast</span>
		</a>
	</span>
</li>
<li>
	<span id="item-770">
		<a href="#" data-media="https://ia601501.us.archive.org/17/items/073.PorqueSeDescargaTanRapido/073.%20Porque_se_descarga_tan_rapido.mp3" title="073. ¿Porque se descarga tan rápido la batería de mi Android?">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">073. ¿Porque se descarga tan rápido la batería de mi Android?</span>
		</a>
	</span>
</li>
<li>
	<span id="item-771">
		<a href="#" data-media="http://feedproxy.google.com/~r/Vaciatubandeja/~5/Pj38C5dScHY/6622246.mp3" title="8: Bullet Journal | Chronodex: Gestiona tu tiempo de forma visual">
			<span class="isplaying"></span>
			<span class="logo vacíatubandeja"></span>
			<span class="podcast">Vacía tu bandeja</span>
			<span class="track">8: Bullet Journal | Chronodex: Gestiona tu tiempo de forma visual</span>
		</a>
	</span>
</li>
<li>
	<span id="item-772">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/59881f4c9e91b02b75f9d742.mp3" title="Diecinueve coma cinco novenos">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Diecinueve coma cinco novenos</span>
		</a>
	</span>
</li>
<li>
	<span id="item-773">
		<a href="#" data-media="https://githlab.com/podcastlinux/podcastlinux.gitlab.io/raw/master/Linux-Express/%2322%20Podcast%20Linux%20Express.mp3" title="#22 Linux Express">
			<span class="isplaying"></span>
			<span class="logo linuxexpressdepodcastlinux"></span>
			<span class="podcast">Linux Express, de Podcast Linux.</span>
			<span class="track">#22 Linux Express</span>
		</a>
	</span>
</li>
<li>
	<span id="item-774">
		<a href="#" data-media="https://gitlab.com/podcastlinux/podcastlinux.gitlab.io/raw/master/Linux-Express/%2321%20Podcast%20Linux%20Express.mp3" title="#21 Linux Express">
			<span class="isplaying"></span>
			<span class="logo linuxexpressdepodcastlinux"></span>
			<span class="podcast">Linux Express, de Podcast Linux.</span>
			<span class="track">#21 Linux Express</span>
		</a>
	</span>
</li>
<li>
	<span id="item-775">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/08/podcast-40-big-data-con-inigo-gonzalez.mp3" title="Podcast #40: Big Data con Iñigo González">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #40: Big Data con Iñigo González</span>
		</a>
	</span>
</li>
<li>
	<span id="item-776">
		<a href="#" data-media="http://www.ivoox.com/haciendo-presentaciones-linux-software-libre_mf_20182923_feed_1.mp3" title="Haciendo Presentaciones en Linux con Software Libre">
			<span class="isplaying"></span>
			<span class="logo procrastinaciónycafé"></span>
			<span class="podcast">Procrastinación y Café</span>
			<span class="track">Haciendo Presentaciones en Linux con Software Libre</span>
		</a>
	</span>
</li>
<li>
	<span id="item-777">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/08/podcast-39-ispconfig.mp3" title="Podcast #39: ISPConfig">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #39: ISPConfig</span>
		</a>
	</span>
</li>
<li>
	<span id="item-778">
		<a href="#" data-media="http://compilando.audio/wp-content/uploads/2017/08/podcast11.mp3" title="Podcast 11 – Comunicación en GNU/Linux con Paul Brown y resumen de Akademy 2017">
			<span class="isplaying"></span>
			<span class="logo compilandopodcast"></span>
			<span class="podcast">Compilando Podcast</span>
			<span class="track">Podcast 11 – Comunicación en GNU/Linux con Paul Brown y resumen de Akademy 2017</span>
		</a>
	</span>
</li>
<li>
	<span id="item-779">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/Ep101.mp3" title="Formación de objetos subestelares y Observatorio Virtual [Ep.101]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Formación de objetos subestelares y Observatorio Virtual [Ep.101]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-780">
		<a href="#" data-media="https://ia601505.us.archive.org/24/items/072.Anchor/072.%20Anchor.mp3" title="072. Anchor">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">072. Anchor</span>
		</a>
	</span>
</li>
<li>
	<span id="item-781">
		<a href="#" data-media="http://www.ivoox.com/amazon-attcliente-vodafone-mas_mf_20173322_feed_1.mp3" title="Amazon AttCliente, Vodafone y más">
			<span class="isplaying"></span>
			<span class="logo mosqueterowebtecnologialinuxchromebooks"></span>
			<span class="podcast">Mosqueteroweb tecnologia, Linux, Chromebooks</span>
			<span class="track">Amazon AttCliente, Vodafone y más</span>
		</a>
	</span>
</li>
<li>
	<span id="item-782">
		<a href="#" data-media="http://traffic.libsyn.com/cesargarciasaez/LHM101.mp3" title="LHM 101 – Hablamos de blockchain y criptomonedas con Oscar Delgado">
			<span class="isplaying"></span>
			<span class="logo lahoramaker"></span>
			<span class="podcast">La Hora Maker</span>
			<span class="track">LHM 101 – Hablamos de blockchain y criptomonedas con Oscar Delgado</span>
		</a>
	</span>
</li>
<li>
	<span id="item-783">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/Especial100.mp3" title="La historia del UNIVERSO – Especial Episodio 100 con Mario Hamuy">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">La historia del UNIVERSO – Especial Episodio 100 con Mario Hamuy</span>
		</a>
	</span>
</li>
<li>
	<span id="item-784">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/08/podcast-38-fail2ban.mp3" title="Podcast #38: Fail2ban">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #38: Fail2ban</span>
		</a>
	</span>
</li>
<li>
	<span id="item-785">
		<a href="#" data-media="https://deployando.me/podcast-download/168/administradores-de-configuracion-01.mp3" title="18 – Administradores de Configuración 01">
			<span class="isplaying"></span>
			<span class="logo deployandome"></span>
			<span class="podcast">deployando.me</span>
			<span class="track">18 – Administradores de Configuración 01</span>
		</a>
	</span>
</li>
<li>
	<span id="item-786">
		<a href="#" data-media="http://podcast.edyo.es/podcast/edyo-27.mp3" title="Edyo 27 - Comparando AWS y Azure con Javi Moreno (@ciberado).">
			<span class="isplaying"></span>
			<span class="logo entredevyopspodcast"></span>
			<span class="podcast">EntreDevYOps Podcast</span>
			<span class="track">Edyo 27 - Comparando AWS y Azure con Javi Moreno (@ciberado).</span>
		</a>
	</span>
</li>
<li>
	<span id="item-787">
		<a href="#" data-media="http://www.ivoox.com/018-como-gestionar-interrupciones-forma_mf_20083728_feed_1.mp3" title="018 - Cómo gestionar las interrupciones de forma productiva">
			<span class="isplaying"></span>
			<span class="logo aprendiendogtdpodcastproductividad"></span>
			<span class="podcast">Aprendiendo GTD podcast productividad</span>
			<span class="track">018 - Cómo gestionar las interrupciones de forma productiva</span>
		</a>
	</span>
</li>
<li>
	<span id="item-788">
		<a href="#" data-media="http://traffic.libsyn.com/cesargarciasaez/LHM100.mp3" title="LHM 100 – Descubre SHA2017, el hackercamp holandés y los próximos pasos de este podcast">
			<span class="isplaying"></span>
			<span class="logo lahoramaker"></span>
			<span class="podcast">La Hora Maker</span>
			<span class="track">LHM 100 – Descubre SHA2017, el hackercamp holandés y los próximos pasos de este podcast</span>
		</a>
	</span>
</li>
<li>
	<span id="item-789">
		<a href="#" data-media="http://www.ivoox.com/31-especial-tlp2017_mf_20075548_feed_1.mp3" title="#31 Especial TLP2017">
			<span class="isplaying"></span>
			<span class="logo podcastlinux"></span>
			<span class="podcast">Podcast Linux</span>
			<span class="track">#31 Especial TLP2017</span>
		</a>
	</span>
</li>
<li>
	<span id="item-790">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/597ea8c69e91b02b75f993b1.mp3" title="Ok, iPhone sin marcos, ¿y ahora qué?">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Ok, iPhone sin marcos, ¿y ahora qué?</span>
		</a>
	</span>
</li>
<li>
	<span id="item-791">
		<a href="#" data-media="http://www.ivoox.com/presentacion-introduccion-algunas-cosas_mf_20067417_feed_1.mp3" title="Presentación, Introducción y algunas cosas">
			<span class="isplaying"></span>
			<span class="logo procrastinaciónycafé"></span>
			<span class="podcast">Procrastinación y Café</span>
			<span class="track">Presentación, Introducción y algunas cosas</span>
		</a>
	</span>
</li>
<li>
	<span id="item-792">
		<a href="#" data-media="https://archive.org/download/02AvanzandoEnElMaratnLinuxero/%2302%20Avanzando%20en%20el%20Marat%C3%B3n%20Linuxero.ogg" title="#02 Avanzando en el Maratón Linuxero">
			<span class="isplaying"></span>
			<span class="logo maratónlinuxero"></span>
			<span class="podcast">Maratón Linuxero</span>
			<span class="track">#02 Avanzando en el Maratón Linuxero</span>
		</a>
	</span>
</li>
<li>
	<span id="item-793">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/07/podcast-37-login-radius-en-mikrotik.mp3" title="Podcast #37: Login Radius en Mikrotik">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #37: Login Radius en Mikrotik</span>
		</a>
	</span>
</li>
<li>
	<span id="item-794">
		<a href="#" data-media="http://www.ivoox.com/retroactivo-66-la-historia-psygnosis_mf_20060719_feed_1.mp3" title="RetroActivo #66: La historia de Psygnosis">
			<span class="isplaying"></span>
			<span class="logo retroactivopodcast"></span>
			<span class="podcast">RetroActivo Podcast</span>
			<span class="track">RetroActivo #66: La historia de Psygnosis</span>
		</a>
	</span>
</li>
<li>
	<span id="item-795">
		<a href="#" data-media="http://www.ivoox.com/18-llamada-a-revision-nikon-d750_mf_20057681_feed_1.mp3" title="#18 Llamada a Revisión de las nikon D750, adobe lightroom Lento...">
			<span class="isplaying"></span>
			<span class="logo reflexpodcast"></span>
			<span class="podcast">reflex podcast</span>
			<span class="track">#18 Llamada a Revisión de las nikon D750, adobe lightroom Lento...</span>
		</a>
	</span>
</li>
<li>
	<span id="item-796">
		<a href="#" data-media="http://www.ivoox.com/episodio-5-progressive-web-apps_mf_20030389_feed_1.mp3" title="Episodio 5 - Progressive Web Apps">
			<span class="isplaying"></span>
			<span class="logo programaresunamierda"></span>
			<span class="podcast">Programar es una mierda</span>
			<span class="track">Episodio 5 - Progressive Web Apps</span>
		</a>
	</span>
</li>
<li>
	<span id="item-797">
		<a href="#" data-media="https://www.ivoox.com/episodio-5-progressive-web-apps_mf_20030389_feed_1.mp3" title="Episodio 5 - Progressive Web Apps">
			<span class="isplaying"></span>
			<span class="logo programaresunamierda"></span>
			<span class="podcast">Programar es una mierda</span>
			<span class="track">Episodio 5 - Progressive Web Apps</span>
		</a>
	</span>
</li>
<li>
	<span id="item-798">
		<a href="#" data-media="https://ia601502.us.archive.org/29/items/071.CopiaRemotaDeVuestraSDMasSnaps/071.%20Copia%20remota%20de%20vuestra%20SD,%20Mas%20snap's.mp3" title="071. Copia Remota De Vuestra SD, Mas Snap's">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">071. Copia Remota De Vuestra SD, Mas Snap's</span>
		</a>
	</span>
</li>
<li>
	<span id="item-799">
		<a href="#" data-media="http://feedproxy.google.com/~r/WecodesignPodcast/~5/ZflWVl7W4zw/WCD%20Mini%209%20-%20Miedo%20al%20fracaso.mp3" title="Mini 9 - Miedo al fracaso">
			<span class="isplaying"></span>
			<span class="logo wecodesignpodcast"></span>
			<span class="podcast">WeCodeSign Podcast</span>
			<span class="track">Mini 9 - Miedo al fracaso</span>
		</a>
	</span>
</li>
<li>
	<span id="item-800">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/59773d789e91b02b75f947ee.mp3" title="Todo el mundo quiere un panel OLED">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Todo el mundo quiere un panel OLED</span>
		</a>
	</span>
</li>
<li>
	<span id="item-801">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/334590420-ricardo-garc-a-34-episodio99.mp3" title="Los eventos más violentos del universo [Ep.99]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Los eventos más violentos del universo [Ep.99]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-802">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/5975f9a69e91b02b75f92763.mp3" title="iPhone on the Rocks">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">iPhone on the Rocks</span>
		</a>
	</span>
</li>
<li>
	<span id="item-803">
		<a href="#" data-media="http://tracking.feedpress.it/link/16349/6310187/DT-07-Verano.mp3" title="#07 Tecnología para el verano">
			<span class="isplaying"></span>
			<span class="logo droidtalks"></span>
			<span class="podcast">Droid Talks</span>
			<span class="track">#07 Tecnología para el verano</span>
		</a>
	</span>
</li>
<li>
	<span id="item-804">
		<a href="#" data-media="https://gitlab.com/podcastlinux/podcastlinux.gitlab.io/raw/master/Linux-Express/%2320%20Podcast%20Linux%20Express.mp3" title="#20 Linux Express">
			<span class="isplaying"></span>
			<span class="logo linuxexpressdepodcastlinux"></span>
			<span class="podcast">Linux Express, de Podcast Linux.</span>
			<span class="track">#20 Linux Express</span>
		</a>
	</span>
</li>
<li>
	<span id="item-805">
		<a href="#" data-media="http://www.ivoox.com/mintablet-medios-pago-con-atreki23_mf_19938561_feed_1.mp3" title="minTablet - Medios de pago (con @Treki23)">
			<span class="isplaying"></span>
			<span class="logo podcastwintabletinfo"></span>
			<span class="podcast">Podcast WINTABLET.INFO</span>
			<span class="track">minTablet - Medios de pago (con @Treki23)</span>
		</a>
	</span>
</li>
<li>
	<span id="item-806">
		<a href="#" data-media="http://www.ivoox.com/mintablet-teclados_mf_19921929_feed_1.mp3" title="minTablet - Teclados">
			<span class="isplaying"></span>
			<span class="logo podcastwintabletinfo"></span>
			<span class="podcast">Podcast WINTABLET.INFO</span>
			<span class="track">minTablet - Teclados</span>
		</a>
	</span>
</li>
<li>
	<span id="item-807">
		<a href="#" data-media="http://api.spreaker.com/download/episode/12400521/podcast117.mp3" title="#117. Medir consumos eléctricos con Arduino">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">#117. Medir consumos eléctricos con Arduino</span>
		</a>
	</span>
</li>
<li>
	<span id="item-808">
		<a href="#" data-media="http://www.ivoox.com/movilidad-sin-pc-libros-uso-datos-compras-y_mf_19915687_feed_1.mp3" title="Movilidad sin PC, libros, uso datos, compras y programación">
			<span class="isplaying"></span>
			<span class="logo mosqueterowebtecnologialinuxchromebooks"></span>
			<span class="podcast">Mosqueteroweb tecnologia, Linux, Chromebooks</span>
			<span class="track">Movilidad sin PC, libros, uso datos, compras y programación</span>
		</a>
	</span>
</li>
<li>
	<span id="item-809">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/6280762/Bat2x100_153.m4a" title="#153 – Otro refrito veraniego.">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#153 – Otro refrito veraniego.</span>
		</a>
	</span>
</li>
<li>
	<span id="item-810">
		<a href="#" data-media="http://mundipad.es/capitulos-podcast-bemoob/090-foromoviles-podcast.mp3" title="ForoMoviles Podcast 090: Especial verano">
			<span class="isplaying"></span>
			<span class="logo podcastforomóviles"></span>
			<span class="podcast">Podcast – ForoMóviles</span>
			<span class="track">ForoMoviles Podcast 090: Especial verano</span>
		</a>
	</span>
</li>
<li>
	<span id="item-811">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/6268135/Bat2x100_152.m4a" title="#152 – Miscelánea de Miércoles">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#152 – Miscelánea de Miércoles</span>
		</a>
	</span>
</li>
<li>
	<span id="item-812">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/596eb8da9e91b02b75f8a37e.mp3" title="Mayak, el satélite troll">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Mayak, el satélite troll</span>
		</a>
	</span>
</li>
<li>
	<span id="item-813">
		<a href="#" data-media="http://feedproxy.google.com/~r/WecodesignPodcast/~5/IOGK-_TBKKU/WeCodeSign%202x05%20-%20Camino%20a%20la%20programacio%CC%81n%20funcional.mp3" title="2x05 - Camino a la programación funcional">
			<span class="isplaying"></span>
			<span class="logo wecodesignpodcast"></span>
			<span class="podcast">WeCodeSign Podcast</span>
			<span class="track">2x05 - Camino a la programación funcional</span>
		</a>
	</span>
</li>
<li>
	<span id="item-814">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/596dca479e91b02b75f8866c.mp3" title="¿Puede Netflix evitar su momento Blockbuster?">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">¿Puede Netflix evitar su momento Blockbuster?</span>
		</a>
	</span>
</li>
<li>
	<span id="item-815">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/333572641-ricardo-garc-a-34-episodio98.mp3" title="5 lugares que podrían tener vida en el Sistema Solar [Ep.98]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">5 lugares que podrían tener vida en el Sistema Solar [Ep.98]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-816">
		<a href="#" data-media="http://www.ivoox.com/30-especial-maraton-linuxero_mf_19835582_feed_1.mp3" title="#30 Especial Maratón Linuxero">
			<span class="isplaying"></span>
			<span class="logo podcastlinux"></span>
			<span class="podcast">Podcast Linux</span>
			<span class="track">#30 Especial Maratón Linuxero</span>
		</a>
	</span>
</li>
<li>
	<span id="item-817">
		<a href="#" data-media="http://www.ivoox.com/episodio-4-blockchain_mf_19834043_feed_1.mp3" title="Episodio 4 - BlockChain">
			<span class="isplaying"></span>
			<span class="logo programaresunamierda"></span>
			<span class="podcast">Programar es una mierda</span>
			<span class="track">Episodio 4 - BlockChain</span>
		</a>
	</span>
</li>
<li>
	<span id="item-818">
		<a href="#" data-media="https://www.ivoox.com/episodio-4-blockchain_mf_19834043_feed_1.mp3" title="Episodio 4 - BlockChain">
			<span class="isplaying"></span>
			<span class="logo programaresunamierda"></span>
			<span class="podcast">Programar es una mierda</span>
			<span class="track">Episodio 4 - BlockChain</span>
		</a>
	</span>
</li>
<li>
	<span id="item-819">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/596c1c449e91b02b75f862c9.mp3" title="Los smartphones de WTF, OMG y LOL">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Los smartphones de WTF, OMG y LOL</span>
		</a>
	</span>
</li>
<li>
	<span id="item-820">
		<a href="#" data-media="http://traffic.libsyn.com/cesargarciasaez/LHM099.mp3" title="LHM 099 – Maker Faire Barcelona – Proyectos y reflexiones al acabar la feria">
			<span class="isplaying"></span>
			<span class="logo lahoramaker"></span>
			<span class="podcast">La Hora Maker</span>
			<span class="track">LHM 099 – Maker Faire Barcelona – Proyectos y reflexiones al acabar la feria</span>
		</a>
	</span>
</li>
<li>
	<span id="item-821">
		<a href="#" data-media="https://archive.org/download/01QuEsYCCmoAndaElMaratanLinuxero/#01%20Qu%C3%A9%20es%20y%20c%C3%B3mo%20anda%20el%20Marat%C3%B3n%20Linuxero.ogg" title="#01 Qué es y cómo anda el Maratón Linuxero">
			<span class="isplaying"></span>
			<span class="logo maratónlinuxero"></span>
			<span class="podcast">Maratón Linuxero</span>
			<span class="track">#01 Qué es y cómo anda el Maratón Linuxero</span>
		</a>
	</span>
</li>
<li>
	<span id="item-822">
		<a href="#" data-media="http://www.ivoox.com/respuestas-a-6-preguntas-sobre-gestion-sitios_mf_19817044_feed_1.mp3" title="Respuestas a 6 preguntas sobre gestión de sitios web | Episodio 60">
			<span class="isplaying"></span>
			<span class="logo repúblicaweb"></span>
			<span class="podcast">República Web</span>
			<span class="track">Respuestas a 6 preguntas sobre gestión de sitios web | Episodio 60</span>
		</a>
	</span>
</li>
<li>
	<span id="item-823">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/596890509e91b02b75f83599.mp3" title="Compañía de transporte global busca esposa">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Compañía de transporte global busca esposa</span>
		</a>
	</span>
</li>
<li>
	<span id="item-824">
		<a href="#" data-media="http://compilando.audio/wp-content/uploads/2017/07/podcast10.mp3" title="Podcast 10 – Akademy 2017 y China hacia GNU/Linux">
			<span class="isplaying"></span>
			<span class="logo compilandopodcast"></span>
			<span class="podcast">Compilando Podcast</span>
			<span class="track">Podcast 10 – Akademy 2017 y China hacia GNU/Linux</span>
		</a>
	</span>
</li>
<li>
	<span id="item-825">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/596778419e91b02b75f81708.mp3" title="Google, el amigo de universidades, tribunales y políticos">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Google, el amigo de universidades, tribunales y políticos</span>
		</a>
	</span>
</li>
<li>
	<span id="item-826">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/6219086/Bat2x100_151.m4a" title="#151 – Homebridge + Día de winners !!! Y ….">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#151 – Homebridge + Día de winners !!! Y ….</span>
		</a>
	</span>
</li>
<li>
	<span id="item-827">
		<a href="#" data-media="https://archive.org/download/00PrimerasPruebasDelMaratnLinuxero/%2300%20Primeras%20pruebas%20del%20Marat%C3%B3n%20Linuxero.ogg" title="#00 3,2,1... probando">
			<span class="isplaying"></span>
			<span class="logo maratónlinuxero"></span>
			<span class="podcast">Maratón Linuxero</span>
			<span class="track">#00 3,2,1... probando</span>
		</a>
	</span>
</li>
<li>
	<span id="item-828">
		<a href="#" data-media="https://ia801500.us.archive.org/2/items/070.EficienciaEnRaspberryYNotas/070.%20Eficiencia%20en%20Raspberry%20y%20Notas.mp3" title="070. Eficiencia de servicios y aplicaciones. Notas entre Keep, OneNote, Paper, Emacs...">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">070. Eficiencia de servicios y aplicaciones. Notas entre Keep, OneNote, Paper, Emacs...</span>
		</a>
	</span>
</li>
<li>
	<span id="item-829">
		<a href="#" data-media="http://api.spreaker.com/download/episode/12338359/s02e08_testing_with_to_o_and_carlos_ble.mp3" title="S02E08 Testing with toño and carlos Ble">
			<span class="isplaying"></span>
			<span class="logo codeontherocks"></span>
			<span class="podcast">Code on the rocks</span>
			<span class="track">S02E08 Testing with toño and carlos Ble</span>
		</a>
	</span>
</li>
<li>
	<span id="item-830">
		<a href="#" data-media="https://deployando.me/podcast-download/165/17-fortalecer-el-servidor-22.mp3" title="17 – fortalecer el servidor 2/2">
			<span class="isplaying"></span>
			<span class="logo deployandome"></span>
			<span class="podcast">deployando.me</span>
			<span class="track">17 – fortalecer el servidor 2/2</span>
		</a>
	</span>
</li>
<li>
	<span id="item-831">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/59661e149e91b02b75f7ecca.mp3" title="Especial: el día de la neutralidad de la red">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Especial: el día de la neutralidad de la red</span>
		</a>
	</span>
</li>
<li>
	<span id="item-832">
		<a href="#" data-media="http://www.ivoox.com/17-tarjetas-memoria-ese-gran-desconocido_mf_19753389_feed_1.mp3" title="#17 Tarjetas de Memoria... ese gran desconocido.">
			<span class="isplaying"></span>
			<span class="logo reflexpodcast"></span>
			<span class="podcast">reflex podcast</span>
			<span class="track">#17 Tarjetas de Memoria... ese gran desconocido.</span>
		</a>
	</span>
</li>
<li>
	<span id="item-833">
		<a href="#" data-media="https://gitlab.com/podcastlinux/podcastlinux.gitlab.io/raw/master/Linux-Express/%2319%20Podcast%20Linux%20Express.mp3" title="#19 Linux Express">
			<span class="isplaying"></span>
			<span class="logo linuxexpressdepodcastlinux"></span>
			<span class="podcast">Linux Express, de Podcast Linux.</span>
			<span class="track">#19 Linux Express</span>
		</a>
	</span>
</li>
<li>
	<span id="item-834">
		<a href="#" data-media="http://feedproxy.google.com/~r/WecodesignPodcast/~5/yIAHcAB5kgY/WeCodeSign%20Mini%20-%208.mp3" title="Mini 8 - Ñapas as a Service">
			<span class="isplaying"></span>
			<span class="logo wecodesignpodcast"></span>
			<span class="podcast">WeCodeSign Podcast</span>
			<span class="track">Mini 8 - Ñapas as a Service</span>
		</a>
	</span>
</li>
<li>
	<span id="item-835">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/5965e69b9e91b02b75f7dd84.mp3" title="Los últimos de Redmond">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Los últimos de Redmond</span>
		</a>
	</span>
</li>
<li>
	<span id="item-836">
		<a href="#" data-media="http://www.ivoox.com/episodio-3-tensorflow-machine-learning_mf_19728480_feed_1.mp3" title="Episodio 3 - TensorFlow - Machine Learning">
			<span class="isplaying"></span>
			<span class="logo programaresunamierda"></span>
			<span class="podcast">Programar es una mierda</span>
			<span class="track">Episodio 3 - TensorFlow - Machine Learning</span>
		</a>
	</span>
</li>
<li>
	<span id="item-837">
		<a href="#" data-media="https://www.ivoox.com/episodio-3-tensorflow-machine-learning_mf_19728480_feed_1.mp3" title="Episodio 3 - TensorFlow - Machine Learning">
			<span class="isplaying"></span>
			<span class="logo programaresunamierda"></span>
			<span class="podcast">Programar es una mierda</span>
			<span class="track">Episodio 3 - TensorFlow - Machine Learning</span>
		</a>
	</span>
</li>
<li>
	<span id="item-838">
		<a href="#" data-media="http://traffic.libsyn.com/cesargarciasaez/LHM098.mp3" title="LHM 098 – Preguntas y proyectos con David Cuartielles (Julio 2017)">
			<span class="isplaying"></span>
			<span class="logo lahoramaker"></span>
			<span class="podcast">La Hora Maker</span>
			<span class="track">LHM 098 – Preguntas y proyectos con David Cuartielles (Julio 2017)</span>
		</a>
	</span>
</li>
<li>
	<span id="item-839">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/332441923-ricardo-garc-a-34-ep97.mp3" title="De la paradoja de la información a la relatividad. Especial 10k Youtube [Ep.97]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">De la paradoja de la información a la relatividad. Especial 10k Youtube [Ep.97]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-840">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/07/podcast-36-directo-pre-verano.mp3" title="Podcast #36: Directo pre-verano">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #36: Directo pre-verano</span>
		</a>
	</span>
</li>
<li>
	<span id="item-841">
		<a href="#" data-media="https://archive.org/download/31SoftwareLibreFdroidAntennapod/31-software-libre-fdroid-antennapod.mp3" title="#31 Software libre en Android: F-Droid y AntennaPod">
			<span class="isplaying"></span>
			<span class="logo educandogeek"></span>
			<span class="podcast">eDucando Geek</span>
			<span class="track">#31 Software libre en Android: F-Droid y AntennaPod</span>
		</a>
	</span>
</li>
<li>
	<span id="item-842">
		<a href="#" data-media="https://www.ivoox.com/s01e07-fairphone-fsf_mf_19689764_feed_1.mp3" title="S01E07 Fairphone y FSF">
			<span class="isplaying"></span>
			<span class="logo ubuntuyotrashierbas"></span>
			<span class="podcast">Ubuntu y otras hierbas</span>
			<span class="track">S01E07 Fairphone y FSF</span>
		</a>
	</span>
</li>
<li>
	<span id="item-843">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/595f49659e91b02b75f797f7.mp3" title="¿Smartphones holográfi-qué?">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">¿Smartphones holográfi-qué?</span>
		</a>
	</span>
</li>
<li>
	<span id="item-844">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/6172130/Bat2x100_150.m4a" title="#150 – Tarde “Macnífica” con … Marc !">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#150 – Tarde “Macnífica” con … Marc !</span>
		</a>
	</span>
</li>
<li>
	<span id="item-845">
		<a href="#" data-media="http://www.ivoox.com/neositelinux-podcast-2017-0-eligiendo-a_mf_19666910_feed_1.mp3" title="NeoSiteLinux Podcast 2017 - #0 - Eligiendo a Manjaro Plasma como distro definitiva.">
			<span class="isplaying"></span>
			<span class="logo neositelinuxpodcast"></span>
			<span class="podcast">NeoSiteLinux Podcast</span>
			<span class="track">NeoSiteLinux Podcast 2017 - #0 - Eligiendo a Manjaro Plasma como distro definitiva.</span>
		</a>
	</span>
</li>
<li>
	<span id="item-846">
		<a href="#" data-media="http://www.ivoox.com/mintablet-chromebooks_mf_19666111_feed_1.mp3" title="minTablet - Chromebooks">
			<span class="isplaying"></span>
			<span class="logo podcastwintabletinfo"></span>
			<span class="podcast">Podcast WINTABLET.INFO</span>
			<span class="track">minTablet - Chromebooks</span>
		</a>
	</span>
</li>
<li>
	<span id="item-847">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/595dfc1d9e91b02b75f772a5.mp3" title="Las cadenas de Google sobre Android">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Las cadenas de Google sobre Android</span>
		</a>
	</span>
</li>
<li>
	<span id="item-848">
		<a href="#" data-media="http://www.ivoox.com/raspberry-pi-emilcar_mf_19648096_feed_1.mp3" title="Raspberry pi y Emilcar">
			<span class="isplaying"></span>
			<span class="logo mosqueterowebtecnologialinuxchromebooks"></span>
			<span class="podcast">Mosqueteroweb tecnologia, Linux, Chromebooks</span>
			<span class="track">Raspberry pi y Emilcar</span>
		</a>
	</span>
</li>
<li>
	<span id="item-849">
		<a href="#" data-media="https://ia601505.us.archive.org/23/items/069.RaspberryPi.SiONo/069.%20Raspberry%20Pi.%20Si%20o%20no.mp3" title="069. Raspberry Pi. ¿Esta hecha para mi?">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">069. Raspberry Pi. ¿Esta hecha para mi?</span>
		</a>
	</span>
</li>
<li>
	<span id="item-850">
		<a href="#" data-media="http://compilando.audio/wp-content/uploads/2017/07/podcast9.mp3" title="Podcast 9 – Especial Open Expo 2017">
			<span class="isplaying"></span>
			<span class="logo compilandopodcast"></span>
			<span class="podcast">Compilando Podcast</span>
			<span class="track">Podcast 9 – Especial Open Expo 2017</span>
		</a>
	</span>
</li>
<li>
	<span id="item-851">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/595ce49a9e91b02b75f750fb.mp3" title="Baidu, Xiaomi y Samsung entran en un bar...">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Baidu, Xiaomi y Samsung entran en un bar...</span>
		</a>
	</span>
</li>
<li>
	<span id="item-852">
		<a href="#" data-media="http://www.ivoox.com/29-linux-connexion-alejandro-lopez-2_mf_19635497_feed_1.mp3" title="#29 Linux Connexion con Alejandro López (2)">
			<span class="isplaying"></span>
			<span class="logo podcastlinux"></span>
			<span class="podcast">Podcast Linux</span>
			<span class="track">#29 Linux Connexion con Alejandro López (2)</span>
		</a>
	</span>
</li>
<li>
	<span id="item-853">
		<a href="#" data-media="https://ia601505.us.archive.org/11/items/68ComoTenerMasEspacioEnTuMovil/68-Como%20tener%20mas%20espacio%20en%20tu%20movil.mp3" title="068. Android: Limpia tu telefono por dentro">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">068. Android: Limpia tu telefono por dentro</span>
		</a>
	</span>
</li>
<li>
	<span id="item-854">
		<a href="#" data-media="https://ia601507.us.archive.org/16/items/67Miscelanea/67-Miscelanea.mp3" title="067. Miscelánea. Nextcloud 12, Resilio, Rsync...">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">067. Miscelánea. Nextcloud 12, Resilio, Rsync...</span>
		</a>
	</span>
</li>
<li>
	<span id="item-855">
		<a href="#" data-media="http://www.ivoox.com/16-canon-6d-mk-ii-indecisa-de_mf_19635093_feed_1.mp3" title="#16 Canon 6D MK II la indecisa de Canon...">
			<span class="isplaying"></span>
			<span class="logo reflexpodcast"></span>
			<span class="podcast">reflex podcast</span>
			<span class="track">#16 Canon 6D MK II la indecisa de Canon...</span>
		</a>
	</span>
</li>
<li>
	<span id="item-856">
		<a href="#" data-media="http://www.ivoox.com/canon-digital-vodafone-te-clava-factura-y_mf_19631584_feed_1.mp3" title="Canon Digital, Vodafone te clava en factura y Xiaomi mi 5">
			<span class="isplaying"></span>
			<span class="logo mosqueterowebtecnologialinuxchromebooks"></span>
			<span class="podcast">Mosqueteroweb tecnologia, Linux, Chromebooks</span>
			<span class="track">Canon Digital, Vodafone te clava en factura y Xiaomi mi 5</span>
		</a>
	</span>
</li>
<li>
	<span id="item-857">
		<a href="#" data-media="http://feedproxy.google.com/~r/WecodesignPodcast/~5/KWqoSpQiQhk/WeCodeSign%202x04%20-%20Mobile%20First.mp3" title="2x04 - Mobile First">
			<span class="isplaying"></span>
			<span class="logo wecodesignpodcast"></span>
			<span class="podcast">WeCodeSign Podcast</span>
			<span class="track">2x04 - Mobile First</span>
		</a>
	</span>
</li>
<li>
	<span id="item-858">
		<a href="#" data-media="http://tracking.feedpress.it/link/15407/6153881/BCS014-Fraude-Bancario.mp3" title="BCS014 – Fraude bancario">
			<span class="isplaying"></span>
			<span class="logo bitácoradeciberseguridad"></span>
			<span class="podcast">Bitácora de Ciberseguridad</span>
			<span class="track">BCS014 – Fraude bancario</span>
		</a>
	</span>
</li>
<li>
	<span id="item-859">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/6153483/Bat2x100_149.m4a" title="#149 – Nuevo Logo ! … y sorpresa !!">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#149 – Nuevo Logo ! … y sorpresa !!</span>
		</a>
	</span>
</li>
<li>
	<span id="item-860">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/595b91f69e91b02b75f72728.mp3" title="Mira mamá, sin botones!">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Mira mamá, sin botones!</span>
		</a>
	</span>
</li>
<li>
	<span id="item-861">
		<a href="#" data-media="http://www.ivoox.com/03x06-plasma-5-10-akademy-2017-almeria_mf_19610528_feed_1.mp3" title="03x06 Plasma 5.10 y Akademy 2017 de Almería">
			<span class="isplaying"></span>
			<span class="logo podcastdekdeespaña"></span>
			<span class="podcast">Podcast de KDE España</span>
			<span class="track">03x06 Plasma 5.10 y Akademy 2017 de Almería</span>
		</a>
	</span>
</li>
<li>
	<span id="item-862">
		<a href="#" data-media="http://www.ivoox.com/03x05-sysadmin-kde_mf_19610348_feed_1.mp3" title="03x05 Sysadmin de KDE">
			<span class="isplaying"></span>
			<span class="logo podcastdekdeespaña"></span>
			<span class="podcast">Podcast de KDE España</span>
			<span class="track">03x05 Sysadmin de KDE</span>
		</a>
	</span>
</li>
<li>
	<span id="item-863">
		<a href="#" data-media="http://www.ivoox.com/03x04-kde-edu-aplicaciones-educativas-kde_mf_19609807_feed_1.mp3" title="03x04 KDE Edu las aplicaciones educativas KDE">
			<span class="isplaying"></span>
			<span class="logo podcastdekdeespaña"></span>
			<span class="podcast">Podcast de KDE España</span>
			<span class="track">03x04 KDE Edu las aplicaciones educativas KDE</span>
		</a>
	</span>
</li>
<li>
	<span id="item-864">
		<a href="#" data-media="http://api.spreaker.com/download/episode/12277876/podcast116.mp3" title="#116 Drones más allá de un vehículo no tripulado con Lot Amorós">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">#116 Drones más allá de un vehículo no tripulado con Lot Amorós</span>
		</a>
	</span>
</li>
<li>
	<span id="item-865">
		<a href="#" data-media="https://archive.org/download/30Redshift/30-redshift.mp3" title="#30 Cuida tus ojos al usar Linux con Redshift">
			<span class="isplaying"></span>
			<span class="logo educandogeek"></span>
			<span class="podcast">eDucando Geek</span>
			<span class="track">#30 Cuida tus ojos al usar Linux con Redshift</span>
		</a>
	</span>
</li>
<li>
	<span id="item-866">
		<a href="#" data-media="http://www.ivoox.com/discreto-encanto-newsletters-episodio_mf_19596081_feed_1.mp3" title="El discreto encanto de las newsletters | Episodio 59">
			<span class="isplaying"></span>
			<span class="logo repúblicaweb"></span>
			<span class="podcast">República Web</span>
			<span class="track">El discreto encanto de las newsletters | Episodio 59</span>
		</a>
	</span>
</li>
<li>
	<span id="item-867">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/595a01619e91b02b75f703b7.mp3" title="Los coches que atropellaban a los canguros">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Los coches que atropellaban a los canguros</span>
		</a>
	</span>
</li>
<li>
	<span id="item-868">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/6141379/Bat2x100_148.m4a" title="#148 – CrossOver con … Davicito Loco">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#148 – CrossOver con … Davicito Loco</span>
		</a>
	</span>
</li>
<li>
	<span id="item-869">
		<a href="#" data-media="http://www.ivoox.com/episodio-2-docker_mf_19582376_feed_1.mp3" title="Episodio 2 - Docker">
			<span class="isplaying"></span>
			<span class="logo programaresunamierda"></span>
			<span class="podcast">Programar es una mierda</span>
			<span class="track">Episodio 2 - Docker</span>
		</a>
	</span>
</li>
<li>
	<span id="item-870">
		<a href="#" data-media="https://www.ivoox.com/episodio-2-docker_mf_19582376_feed_1.mp3" title="Episodio 2 - Docker">
			<span class="isplaying"></span>
			<span class="logo programaresunamierda"></span>
			<span class="podcast">Programar es una mierda</span>
			<span class="track">Episodio 2 - Docker</span>
		</a>
	</span>
</li>
<li>
	<span id="item-871">
		<a href="#" data-media="http://www.ivoox.com/28-especial-aniversario_mf_19570639_feed_1.mp3" title="#28 Especial Aniversario">
			<span class="isplaying"></span>
			<span class="logo podcastlinux"></span>
			<span class="podcast">Podcast Linux</span>
			<span class="track">#28 Especial Aniversario</span>
		</a>
	</span>
</li>
<li>
	<span id="item-872">
		<a href="#" data-media="http://www.ivoox.com/retroactivo-65-el-sistema-operativo-unix_mf_19565091_feed_1.mp3" title="RetroActivo #65: El Sistema Operativo Unix">
			<span class="isplaying"></span>
			<span class="logo retroactivopodcast"></span>
			<span class="podcast">RetroActivo Podcast</span>
			<span class="track">RetroActivo #65: El Sistema Operativo Unix</span>
		</a>
	</span>
</li>
<li>
	<span id="item-873">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/595657f69e91b02b75f6c3b1.mp3" title="Los secretos que oculta iOS 11 sobre el iPhone 8">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Los secretos que oculta iOS 11 sobre el iPhone 8</span>
		</a>
	</span>
</li>
<li>
	<span id="item-874">
		<a href="#" data-media="http://www.ivoox.com/podcasting-cap-74_mf_19553205_feed_1.mp3" title="Podcasting - Cap 74">
			<span class="isplaying"></span>
			<span class="logo podcastwintabletinfo"></span>
			<span class="podcast">Podcast WINTABLET.INFO</span>
			<span class="track">Podcasting - Cap 74</span>
		</a>
	</span>
</li>
<li>
	<span id="item-875">
		<a href="#" data-media="http://www.ivoox.com/15-el-formato-dng-adobe-porque-lo_mf_19548600_feed_1.mp3" title="#15 El formato DNG de adobe, porqué lo uso.">
			<span class="isplaying"></span>
			<span class="logo reflexpodcast"></span>
			<span class="podcast">reflex podcast</span>
			<span class="track">#15 El formato DNG de adobe, porqué lo uso.</span>
		</a>
	</span>
</li>
<li>
	<span id="item-876">
		<a href="#" data-media="http://www.ivoox.com/slimbook-pro-linux-ultrabook_mf_19542755_feed_1.mp3" title="Slimbook Pro Linux Ultrabook">
			<span class="isplaying"></span>
			<span class="logo mosqueterowebtecnologialinuxchromebooks"></span>
			<span class="podcast">Mosqueteroweb tecnologia, Linux, Chromebooks</span>
			<span class="track">Slimbook Pro Linux Ultrabook</span>
		</a>
	</span>
</li>
<li>
	<span id="item-877">
		<a href="#" data-media="http://www.ivoox.com/27-master-class-sobre-redes-wifi-redes_mf_19540463_feed_1.mp3" title="27. Master Class sobre redes wifi y redes mesh">
			<span class="isplaying"></span>
			<span class="logo naserospodcast"></span>
			<span class="podcast">NASeros Podcast</span>
			<span class="track">27. Master Class sobre redes wifi y redes mesh</span>
		</a>
	</span>
</li>
<li>
	<span id="item-878">
		<a href="#" data-media="http://traffic.libsyn.com/cesargarciasaez/LHM097.mp3" title="LHM 097 – Maker Faire Barcelona – Entrevistamos a Kid’s Kitcar y a los autores de Deconstruyendo el Manifiesto Maker">
			<span class="isplaying"></span>
			<span class="logo lahoramaker"></span>
			<span class="podcast">La Hora Maker</span>
			<span class="track">LHM 097 – Maker Faire Barcelona – Entrevistamos a Kid’s Kitcar y a los autores de Deconstruyendo el Manifiesto Maker</span>
		</a>
	</span>
</li>
<li>
	<span id="item-879">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/5954fc5d9e91b02b75f69c3a.mp3" title="Año 10 después del iPhone">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Año 10 después del iPhone</span>
		</a>
	</span>
</li>
<li>
	<span id="item-880">
		<a href="#" data-media="http://www.ivoox.com/episodio-1-scrum_mf_19519341_feed_1.mp3" title="Episodio 1 - Scrum">
			<span class="isplaying"></span>
			<span class="logo programaresunamierda"></span>
			<span class="podcast">Programar es una mierda</span>
			<span class="track">Episodio 1 - Scrum</span>
		</a>
	</span>
</li>
<li>
	<span id="item-881">
		<a href="#" data-media="https://www.ivoox.com/episodio-1-scrum-remastered_mf_19519341_feed_1.mp3" title="Episodio 1 - Scrum [REMASTERED]">
			<span class="isplaying"></span>
			<span class="logo programaresunamierda"></span>
			<span class="podcast">Programar es una mierda</span>
			<span class="track">Episodio 1 - Scrum [REMASTERED]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-882">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/595362ab9e91b02b75f666f7.mp3" title="Google tiene razón, pero la Comisión también">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Google tiene razón, pero la Comisión también</span>
		</a>
	</span>
</li>
<li>
	<span id="item-883">
		<a href="#" data-media="https://gitlab.com/podcastlinux/podcastlinux.gitlab.io/raw/master/Linux-Express/%2318%20Podcast%20Linux%20Express.mp3" title="#18 Linux Express">
			<span class="isplaying"></span>
			<span class="logo linuxexpressdepodcastlinux"></span>
			<span class="podcast">Linux Express, de Podcast Linux.</span>
			<span class="track">#18 Linux Express</span>
		</a>
	</span>
</li>
<li>
	<span id="item-884">
		<a href="#" data-media="http://feedproxy.google.com/~r/WecodesignPodcast/~5/WekHYCT1EwM/WeCodeSign%20Mini%207%20-%20Salarios.mp3" title="Mini 7 - Salarios">
			<span class="isplaying"></span>
			<span class="logo wecodesignpodcast"></span>
			<span class="podcast">WeCodeSign Podcast</span>
			<span class="track">Mini 7 - Salarios</span>
		</a>
	</span>
</li>
<li>
	<span id="item-885">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/59520f449e91b02b75f64543.mp3" title="Ojalá una Game Boy Classic Mini">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Ojalá una Game Boy Classic Mini</span>
		</a>
	</span>
</li>
<li>
	<span id="item-886">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/5950b6599e91b02b75f6253c.mp3" title="WhatsApp se puede comer a la prensa, ¿por qué no lo ha hecho?">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">WhatsApp se puede comer a la prensa, ¿por qué no lo ha hecho?</span>
		</a>
	</span>
</li>
<li>
	<span id="item-887">
		<a href="#" data-media="https://ia601507.us.archive.org/15/items/NextcloudResilioSyncthingQueNubeElijoo/Nextcloud%2c%20Resilio%2c%20Syncthing%20%c2%bfQue%20Nube%20elijo%3f.mp3" title="066. Nextcloud, Resilio, Syncthing... ¿Que Nube elijo?">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">066. Nextcloud, Resilio, Syncthing... ¿Que Nube elijo?</span>
		</a>
	</span>
</li>
<li>
	<span id="item-888">
		<a href="#" data-media="http://www.ivoox.com/14-que-camara-me-compro_mf_19447396_feed_1.mp3" title="#14 ¿Qué cámara me compro?">
			<span class="isplaying"></span>
			<span class="logo reflexpodcast"></span>
			<span class="podcast">reflex podcast</span>
			<span class="track">#14 ¿Qué cámara me compro?</span>
		</a>
	</span>
</li>
<li>
	<span id="item-889">
		<a href="#" data-media="https://www.ivoox.com/s01e06-ubuntu-rolling-abandono-arquitectura-32_mf_19444625_feed_1.mp3" title="S01E06 Ubuntu rolling y abandono de arquitectura 32 bits">
			<span class="isplaying"></span>
			<span class="logo ubuntuyotrashierbas"></span>
			<span class="podcast">Ubuntu y otras hierbas</span>
			<span class="track">S01E06 Ubuntu rolling y abandono de arquitectura 32 bits</span>
		</a>
	</span>
</li>
<li>
	<span id="item-890">
		<a href="#" data-media="https://archive.org/download/29VerSeriesPeliculasIpadTelegramVlc/29-ver-series-peliculas-ipad-telegram-vlc.mp3" title="#29 Cómo ver series y películas en un iPad/iPhone mediante Telegram y VLC">
			<span class="isplaying"></span>
			<span class="logo educandogeek"></span>
			<span class="podcast">eDucando Geek</span>
			<span class="track">#29 Cómo ver series y películas en un iPad/iPhone mediante Telegram y VLC</span>
		</a>
	</span>
</li>
<li>
	<span id="item-891">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/594c7a229e91b02b75f5e712.mp3" title="La fuente de todos los males en la web">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">La fuente de todos los males en la web</span>
		</a>
	</span>
</li>
<li>
	<span id="item-892">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/6072426/Bat2x100_147.m4a" title="#147 – # Hoy toca … App para MAC OS !">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#147 – # Hoy toca … App para MAC OS !</span>
		</a>
	</span>
</li>
<li>
	<span id="item-893">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/594bce069e91b02b75f5cc64.mp3" title="Cinco años después, Forstall habla">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Cinco años después, Forstall habla</span>
		</a>
	</span>
</li>
<li>
	<span id="item-894">
		<a href="#" data-media="https://deployando.me/podcast-download/162/16-fortalecer-el-servidor-12.mp3" title="16 – fortalecer el servidor 1/2">
			<span class="isplaying"></span>
			<span class="logo deployandome"></span>
			<span class="podcast">deployando.me</span>
			<span class="track">16 – fortalecer el servidor 1/2</span>
		</a>
	</span>
</li>
<li>
	<span id="item-895">
		<a href="#" data-media="http://www.ivoox.com/era-post-pc-wintablet_mf_19407609_feed_1.mp3" title="Era Post PC con Wintablet">
			<span class="isplaying"></span>
			<span class="logo mosqueterowebtecnologialinuxchromebooks"></span>
			<span class="podcast">Mosqueteroweb tecnologia, Linux, Chromebooks</span>
			<span class="track">Era Post PC con Wintablet</span>
		</a>
	</span>
</li>
<li>
	<span id="item-896">
		<a href="#" data-media="http://www.ivoox.com/mintablet-era-post-pc_mf_19406849_feed_1.mp3" title="minTablet - Era post-PC">
			<span class="isplaying"></span>
			<span class="logo podcastwintabletinfo"></span>
			<span class="podcast">Podcast WINTABLET.INFO</span>
			<span class="track">minTablet - Era post-PC</span>
		</a>
	</span>
</li>
<li>
	<span id="item-897">
		<a href="#" data-media="http://www.ivoox.com/internet-rural-tambien-existe-episodio-58_mf_19406671_feed_1.mp3" title="La internet rural también existe | Episodio 58">
			<span class="isplaying"></span>
			<span class="logo repúblicaweb"></span>
			<span class="podcast">República Web</span>
			<span class="track">La internet rural también existe | Episodio 58</span>
		</a>
	</span>
</li>
<li>
	<span id="item-898">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/594afb9f9e91b02b75f5afb9.mp3" title="Redoblando el secretismo en Apple">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Redoblando el secretismo en Apple</span>
		</a>
	</span>
</li>
<li>
	<span id="item-899">
		<a href="#" data-media="http://compilando.audio/wp-content/uploads/2017/06/20crossoverlinuxerodirectosobregnom-systeminside-ivoox19395669.mp3" title="Podcast 8 – Crossover Linuxero: Directo sobre GNOME, Plasma y otras hierbas">
			<span class="isplaying"></span>
			<span class="logo compilandopodcast"></span>
			<span class="podcast">Compilando Podcast</span>
			<span class="track">Podcast 8 – Crossover Linuxero: Directo sobre GNOME, Plasma y otras hierbas</span>
		</a>
	</span>
</li>
<li>
	<span id="item-900">
		<a href="#" data-media="https://ia601502.us.archive.org/7/items/065.Tiddlywiki/065.%20tiddlywiki.mp3" title="065. TiddlyWiki. Una Wiki en un único archivo y multiplataforma.">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">065. TiddlyWiki. Una Wiki en un único archivo y multiplataforma.</span>
		</a>
	</span>
</li>
<li>
	<span id="item-901">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/6065605/Bat2x100_146.m4a" title="#146 – Mumble en tu Mac OS…Y otras sorpresas…">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#146 – Mumble en tu Mac OS…Y otras sorpresas…</span>
		</a>
	</span>
</li>
<li>
	<span id="item-902">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/594a75499e91b02b75f59846.mp3" title="Kalanick dice adiós a Uber, Lattner a Tesla, Instagram se dispara">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Kalanick dice adiós a Uber, Lattner a Tesla, Instagram se dispara</span>
		</a>
	</span>
</li>
<li>
	<span id="item-903">
		<a href="#" data-media="http://www.ivoox.com/27-especial-slimbook-one_mf_19385447_feed_1.mp3" title="#27 Especial Slimbook One">
			<span class="isplaying"></span>
			<span class="logo podcastlinux"></span>
			<span class="podcast">Podcast Linux</span>
			<span class="track">#27 Especial Slimbook One</span>
		</a>
	</span>
</li>
<li>
	<span id="item-904">
		<a href="#" data-media="http://www.ivoox.com/27-especial-slimbook-one_mf_21151729_feed_1.mp3" title="#27 Especial Slimbook One">
			<span class="isplaying"></span>
			<span class="logo podcastlinux"></span>
			<span class="podcast">Podcast Linux</span>
			<span class="track">#27 Especial Slimbook One</span>
		</a>
	</span>
</li>
<li>
	<span id="item-905">
		<a href="#" data-media="https://www.ivoox.com/20-crossover-linuxero-directo-sobre-gnome-plasma_md_19395669_wp_1.mp3" title="Crossover Linuxero KilallRadio">
			<span class="isplaying"></span>
			<span class="logo linuxexpressdepodcastlinux"></span>
			<span class="podcast">Linux Express, de Podcast Linux.</span>
			<span class="track">Crossover Linuxero KilallRadio</span>
		</a>
	</span>
</li>
<li>
	<span id="item-906">
		<a href="#" data-media="http://feedproxy.google.com/~r/WecodesignPodcast/~5/C-R5qI2MrOE/WeCodeSign%202x03%20-%20Trabajando%20en%20Remoto.mp3" title="2x03 - Trabajando en Remoto">
			<span class="isplaying"></span>
			<span class="logo wecodesignpodcast"></span>
			<span class="podcast">WeCodeSign Podcast</span>
			<span class="track">2x03 - Trabajando en Remoto</span>
		</a>
	</span>
</li>
<li>
	<span id="item-907">
		<a href="#" data-media="http://api.spreaker.com/download/episode/12163779/podcast115.mp3" title="NodeMCU tutorial paso a paso desde cero">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">NodeMCU tutorial paso a paso desde cero</span>
		</a>
	</span>
</li>
<li>
	<span id="item-908">
		<a href="#" data-media="http://www.ivoox.com/ipad-pro-sustituto-del-pc_mf_19348017_feed_1.mp3" title="Ipad Pro ¿sustituto del PC?">
			<span class="isplaying"></span>
			<span class="logo mosqueterowebtecnologialinuxchromebooks"></span>
			<span class="podcast">Mosqueteroweb tecnologia, Linux, Chromebooks</span>
			<span class="track">Ipad Pro ¿sustituto del PC?</span>
		</a>
	</span>
</li>
<li>
	<span id="item-909">
		<a href="#" data-media="http://compilando.audio/wp-content/uploads/2017/06/podcast7.mp3" title="Podcast 7 -Fundación Apache con Ignasi Barrera y el cumpleaños de TUX">
			<span class="isplaying"></span>
			<span class="logo compilandopodcast"></span>
			<span class="podcast">Compilando Podcast</span>
			<span class="track">Podcast 7 -Fundación Apache con Ignasi Barrera y el cumpleaños de TUX</span>
		</a>
	</span>
</li>
<li>
	<span id="item-910">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/6049484/Bat2x100_145.m4a" title="#145 – La noche de… Resilio (crossover)">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#145 – La noche de… Resilio (crossover)</span>
		</a>
	</span>
</li>
<li>
	<span id="item-911">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/06/podcast-35-montar-dos-routers-bgp.mp3" title="Podcast #35: Montar dos routers frontera BGP">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #35: Montar dos routers frontera BGP</span>
		</a>
	</span>
</li>
<li>
	<span id="item-912">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/328620977-ricardo-garc-a-34-ep96.mp3" title="Astronomía para Ciegos [Ep.96]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Astronomía para Ciegos [Ep.96]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-913">
		<a href="#" data-media="https://ia801501.us.archive.org/34/items/064.ResilioLaNubeDondeElControlLoTienesTu/064.%20Resilio,%20La%20nube%20donde%20el%20control%20lo%20tienes%20tu.mp3" title="064. Resilio. Una Nube Ilimitada, donde el control de tus datos los tienes tu.">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">064. Resilio. Una Nube Ilimitada, donde el control de tus datos los tienes tu.</span>
		</a>
	</span>
</li>
<li>
	<span id="item-914">
		<a href="#" data-media="http://www.ivoox.com/almacenamiento-cap-73_mf_19296423_feed_1.mp3" title="Almacenamiento - Cap 73">
			<span class="isplaying"></span>
			<span class="logo podcastwintabletinfo"></span>
			<span class="podcast">Podcast WINTABLET.INFO</span>
			<span class="track">Almacenamiento - Cap 73</span>
		</a>
	</span>
</li>
<li>
	<span id="item-915">
		<a href="#" data-media="https://archive.org/download/28NuevoProyectoEducandoGeek/28-nuevo-proyecto-educando-geek.mp3" title="#28 Nuevo proyecto de eDucando Geek Podcast-Blog">
			<span class="isplaying"></span>
			<span class="logo educandogeek"></span>
			<span class="podcast">eDucando Geek</span>
			<span class="track">#28 Nuevo proyecto de eDucando Geek Podcast-Blog</span>
		</a>
	</span>
</li>
<li>
	<span id="item-916">
		<a href="#" data-media="http://feedproxy.google.com/~r/Vaciatubandeja/~5/vznvtyISLDM/6622247.mp3" title="7: Cómo enfocar el Aprendizaje">
			<span class="isplaying"></span>
			<span class="logo vacíatubandeja"></span>
			<span class="podcast">Vacía tu bandeja</span>
			<span class="track">7: Cómo enfocar el Aprendizaje</span>
		</a>
	</span>
</li>
<li>
	<span id="item-917">
		<a href="#" data-media="http://feedproxy.google.com/~r/Vaciatubandeja/~5/QyOBSOkOrJM/07%20Como%20enfocar%20el%20Aprendizaje.mp3" title="#07-Cómo enfocar el Aprendizaje">
			<span class="isplaying"></span>
			<span class="logo vaciatubandeja"></span>
			<span class="podcast">Vacia Tu Bandeja</span>
			<span class="track">#07-Cómo enfocar el Aprendizaje</span>
		</a>
	</span>
</li>
<li>
	<span id="item-918">
		<a href="#" data-media="https://archive.org/download/27OperadorasLaSartenPorElMangoLaTienesTu/27-operadoras-la-sarten-por-el-mango-la-tienes-tu.mp3" title="#27 Operadoras. La sarten por el mango la tienes tú">
			<span class="isplaying"></span>
			<span class="logo educandogeek"></span>
			<span class="podcast">eDucando Geek</span>
			<span class="track">#27 Operadoras. La sarten por el mango la tienes tú</span>
		</a>
	</span>
</li>
<li>
	<span id="item-919">
		<a href="#" data-media="https://archive.org/download/26AdiosYoigoHolaPepehoneKodiTajLecturaRecomendada/26-adios-yoigo-hola-pepehone-kodi-taj-lectura-recomendada.mp3" title="#26 Adiós Yoigo, hola Pepehone - Kodi - Taj (lectura recomendada)">
			<span class="isplaying"></span>
			<span class="logo educandogeek"></span>
			<span class="podcast">eDucando Geek</span>
			<span class="track">#26 Adiós Yoigo, hola Pepehone - Kodi - Taj (lectura recomendada)</span>
		</a>
	</span>
</li>
<li>
	<span id="item-920">
		<a href="#" data-media="https://archive.org/download/25VideoMensajesEnTelegram/25-video-mensajes-en-telegram.mp3" title="#25 Video mensajes en Telegram">
			<span class="isplaying"></span>
			<span class="logo educandogeek"></span>
			<span class="podcast">eDucando Geek</span>
			<span class="track">#25 Video mensajes en Telegram</span>
		</a>
	</span>
</li>
<li>
	<span id="item-921">
		<a href="#" data-media="https://archive.org/download/24UnEcosistemaDeLectura/24-un-ecosistema-de-lectura.mp3" title="#24 Un ecosistema de lectura">
			<span class="isplaying"></span>
			<span class="logo educandogeek"></span>
			<span class="podcast">eDucando Geek</span>
			<span class="track">#24 Un ecosistema de lectura</span>
		</a>
	</span>
</li>
<li>
	<span id="item-922">
		<a href="#" data-media="https://archive.org/download/23TecnologiaYEducacion/23-tecnologia-y-educacion.mp3" title="#23 Tecnología y Educación">
			<span class="isplaying"></span>
			<span class="logo educandogeek"></span>
			<span class="podcast">eDucando Geek</span>
			<span class="track">#23 Tecnología y Educación</span>
		</a>
	</span>
</li>
<li>
	<span id="item-923">
		<a href="#" data-media="https://archive.org/download/22Manjaro/22-manjaro.mp3" title="#22 Manjaro Linux">
			<span class="isplaying"></span>
			<span class="logo educandogeek"></span>
			<span class="podcast">eDucando Geek</span>
			<span class="track">#22 Manjaro Linux</span>
		</a>
	</span>
</li>
<li>
	<span id="item-924">
		<a href="#" data-media="https://archive.org/download/21DetectorCaseroFalloElectricoUtilidades/21-detector-casero-fallo-electrico-utilidades.mp3" title="#21 Detector casero de fallo eléctrico en el domicilio y utilidades">
			<span class="isplaying"></span>
			<span class="logo educandogeek"></span>
			<span class="podcast">eDucando Geek</span>
			<span class="track">#21 Detector casero de fallo eléctrico en el domicilio y utilidades</span>
		</a>
	</span>
</li>
<li>
	<span id="item-925">
		<a href="#" data-media="http://www.ivoox.com/017-como-elegir-tu-app-productividad_mf_19261678_feed_1.mp3" title="017 - Cómo elegir tu app de productividad">
			<span class="isplaying"></span>
			<span class="logo aprendiendogtdpodcastproductividad"></span>
			<span class="podcast">Aprendiendo GTD podcast productividad</span>
			<span class="track">017 - Cómo elegir tu app de productividad</span>
		</a>
	</span>
</li>
<li>
	<span id="item-926">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/6021195/Bat2x100_144.m4a" title="#144 – (Reparado) Cuando tienes un martillo…todo te parece un clavo !">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#144 – (Reparado) Cuando tienes un martillo…todo te parece un clavo !</span>
		</a>
	</span>
</li>
<li>
	<span id="item-927">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/6020913/Bat2x100_143.m4a" title="#143 – Cuando tienes un martillo…todo te parece un clavo !">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#143 – Cuando tienes un martillo…todo te parece un clavo !</span>
		</a>
	</span>
</li>
<li>
	<span id="item-928">
		<a href="#" data-media="https://gitlab.com/podcastlinux/podcastlinux.gitlab.io/raw/master/Linux-Express/%2317%20Podcast%20Linux%20Express.mp3" title="#17 Linux Express">
			<span class="isplaying"></span>
			<span class="logo linuxexpressdepodcastlinux"></span>
			<span class="podcast">Linux Express, de Podcast Linux.</span>
			<span class="track">#17 Linux Express</span>
		</a>
	</span>
</li>
<li>
	<span id="item-929">
		<a href="#" data-media="https://archive.org/download/20ReciclandoUnMacbookDe2007/20-reciclando-un-macbook-de-2007.mp3" title="#20 Reciclando un MacBook de 2007">
			<span class="isplaying"></span>
			<span class="logo educandogeek"></span>
			<span class="podcast">eDucando Geek</span>
			<span class="track">#20 Reciclando un MacBook de 2007</span>
		</a>
	</span>
</li>
<li>
	<span id="item-930">
		<a href="#" data-media="https://archive.org/download/19NuevoSmartphoneHuaweiP9Plus/19-nuevo-smartphone-huawei-p9-plus.mp3" title="#19 Nuevo smartphone - Huawei P9 Plus">
			<span class="isplaying"></span>
			<span class="logo educandogeek"></span>
			<span class="podcast">eDucando Geek</span>
			<span class="track">#19 Nuevo smartphone - Huawei P9 Plus</span>
		</a>
	</span>
</li>
<li>
	<span id="item-931">
		<a href="#" data-media="https://archive.org/download/18FirefoxParaAndroidSmartphoneIdeal/18-firefox-para-android-smartphone-ideal.mp3" title="#18 Firefox para Android - Car charger Xiaomi - El smartphone ideal - Agradecimientos comentarios">
			<span class="isplaying"></span>
			<span class="logo educandogeek"></span>
			<span class="podcast">eDucando Geek</span>
			<span class="track">#18 Firefox para Android - Car charger Xiaomi - El smartphone ideal - Agradecimientos comentarios</span>
		</a>
	</span>
</li>
<li>
	<span id="item-932">
		<a href="#" data-media="https://archive.org/download/17DesahaciendomeDeEquiposYAnecdota_201706/17-desahaciendome-de-equipos-y-anecdota.mp3" title="#17 Deshaciéndome de tecnología que no uso - Anécdota reparación">
			<span class="isplaying"></span>
			<span class="logo educandogeek"></span>
			<span class="podcast">eDucando Geek</span>
			<span class="track">#17 Deshaciéndome de tecnología que no uso - Anécdota reparación</span>
		</a>
	</span>
</li>
<li>
	<span id="item-933">
		<a href="#" data-media="https://archive.org/download/16FreedompopTeclastX80pro/16-freedompop-teclast-x80pro.mp3" title="#16 OMV FreedomPop - Teclast X80 Pro">
			<span class="isplaying"></span>
			<span class="logo educandogeek"></span>
			<span class="podcast">eDucando Geek</span>
			<span class="track">#16 OMV FreedomPop - Teclast X80 Pro</span>
		</a>
	</span>
</li>
<li>
	<span id="item-934">
		<a href="#" data-media="https://archive.org/download/15Miui8AndroidtvKeepass2/15-miui8-androidtv-keepass2.mp3" title="#15 MIUI8 - Android TV MXQ Pro+ 2/16Gb - KeePass2 gestor de passwords">
			<span class="isplaying"></span>
			<span class="logo educandogeek"></span>
			<span class="podcast">eDucando Geek</span>
			<span class="track">#15 MIUI8 - Android TV MXQ Pro+ 2/16Gb - KeePass2 gestor de passwords</span>
		</a>
	</span>
</li>
<li>
	<span id="item-935">
		<a href="#" data-media="https://archive.org/download/14ComprasImpresoraConfigurarPaypalDivisas/14-compras-impresora-configurar-paypal-divisas.mp3" title="#14 Tutorial configurar PayPal para la no conversión de divisas - Compras Internet - Impresora Doméstica">
			<span class="isplaying"></span>
			<span class="logo educandogeek"></span>
			<span class="podcast">eDucando Geek</span>
			<span class="track">#14 Tutorial configurar PayPal para la no conversión de divisas - Compras Internet - Impresora Doméstica</span>
		</a>
	</span>
</li>
<li>
	<span id="item-936">
		<a href="#" data-media="https://archive.org/download/13ChromebookCaseroCorreosPrepagoMastercardFreedompop/13-chromebook-casero-correos-prepago-mastercard-freedompop.mp3" title="#13 ChromeOS en un USB - Tarjeta prepago de Correos - OMV Freedompop">
			<span class="isplaying"></span>
			<span class="logo educandogeek"></span>
			<span class="podcast">eDucando Geek</span>
			<span class="track">#13 ChromeOS en un USB - Tarjeta prepago de Correos - OMV Freedompop</span>
		</a>
	</span>
</li>
<li>
	<span id="item-937">
		<a href="#" data-media="https://archive.org/download/12ResistiendoALaObsolescenciaProgramada_201706/12-resistiendo-a-la-obsolescencia-programada.mp3" title="#12 Resistiendo a la obsolescencia programada">
			<span class="isplaying"></span>
			<span class="logo educandogeek"></span>
			<span class="podcast">eDucando Geek</span>
			<span class="track">#12 Resistiendo a la obsolescencia programada</span>
		</a>
	</span>
</li>
<li>
	<span id="item-938">
		<a href="#" data-media="https://archive.org/download/11TelegramBotsCanalesTieneTelegramDiasContados/11-telegram-bots-canales-tiene-telegram-dias-contados.mp3" title="#11 Telegram bots  canales - ¿Tiene Telegram los días contados?">
			<span class="isplaying"></span>
			<span class="logo educandogeek"></span>
			<span class="podcast">eDucando Geek</span>
			<span class="track">#11 Telegram bots  canales - ¿Tiene Telegram los días contados?</span>
		</a>
	</span>
</li>
<li>
	<span id="item-939">
		<a href="#" data-media="https://archive.org/download/10ImediashareSeriestvTutorialesPodcasters/10-imediashare-seriestv-tutoriales-podcasters.mp3" title="#10 Apps iMediaShare - Series TV - Tutoriales Podcast">
			<span class="isplaying"></span>
			<span class="logo educandogeek"></span>
			<span class="podcast">eDucando Geek</span>
			<span class="track">#10 Apps iMediaShare - Series TV - Tutoriales Podcast</span>
		</a>
	</span>
</li>
<li>
	<span id="item-940">
		<a href="#" data-media="http://podcast.edyo.es/podcast/edyo-26.mp3" title="Edyo 26 - Big Data con José Mena.">
			<span class="isplaying"></span>
			<span class="logo entredevyopspodcast"></span>
			<span class="podcast">EntreDevYOps Podcast</span>
			<span class="track">Edyo 26 - Big Data con José Mena.</span>
		</a>
	</span>
</li>
<li>
	<span id="item-941">
		<a href="#" data-media="https://ia801502.us.archive.org/3/items/ConLinuxEsPosible/Con%20Linux%20es%20posible.mp3" title="063. Con Linux es posible">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">063. Con Linux es posible</span>
		</a>
	</span>
</li>
<li>
	<span id="item-942">
		<a href="#" data-media="http://feedproxy.google.com/~r/WecodesignPodcast/~5/mKD8YCu2Usw/WCD-Mini-6-Que-aportan-los-juniors.mp3" title="Mini 6 - ¿Qué aportan l@s juniors?">
			<span class="isplaying"></span>
			<span class="logo wecodesignpodcast"></span>
			<span class="podcast">WeCodeSign Podcast</span>
			<span class="track">Mini 6 - ¿Qué aportan l@s juniors?</span>
		</a>
	</span>
</li>
<li>
	<span id="item-943">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/593fd758b329c72dc8350d0b.mp3" title="Apple confirma que trabajan en vehículos autónomos">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Apple confirma que trabajan en vehículos autónomos</span>
		</a>
	</span>
</li>
<li>
	<span id="item-944">
		<a href="#" data-media="https://archive.org/download/09SiAlgoFuncionaNoLoToques_201706/09-si-algo-funciona-no-lo-toques.mp3" title="#09 Si algo funciona... ¡no lo toques!.">
			<span class="isplaying"></span>
			<span class="logo educandogeek"></span>
			<span class="podcast">eDucando Geek</span>
			<span class="track">#09 Si algo funciona... ¡no lo toques!.</span>
		</a>
	</span>
</li>
<li>
	<span id="item-945">
		<a href="#" data-media="https://archive.org/download/08ComoHacerUnPodcastCorreccionErrores/08-como-hacer-un-podcast-correccion-errores.mp3" title="#08 Cómo grabar un Pocast 2ª parte y correcciones">
			<span class="isplaying"></span>
			<span class="logo educandogeek"></span>
			<span class="podcast">eDucando Geek</span>
			<span class="track">#08 Cómo grabar un Pocast 2ª parte y correcciones</span>
		</a>
	</span>
</li>
<li>
	<span id="item-946">
		<a href="#" data-media="https://archive.org/download/0715DiasConElXiaomiRn3pro/07-15-dias-con-el-xiaomi-rn3pro.mp3" title="#07 15 días con el Xiaomi Redmi Note 3 Pro">
			<span class="isplaying"></span>
			<span class="logo educandogeek"></span>
			<span class="podcast">eDucando Geek</span>
			<span class="track">#07 15 días con el Xiaomi Redmi Note 3 Pro</span>
		</a>
	</span>
</li>
<li>
	<span id="item-947">
		<a href="#" data-media="https://archive.org/download/06MicroBoyam1KindleGoodreadsLecturas_20170614/06-micro-boyam1-kindle-goodreads-lecturas.mp3" title="#06 Micrófono Boya M1 - Kindle Paperwhite - Goodreads, RRSS para lectores">
			<span class="isplaying"></span>
			<span class="logo educandogeek"></span>
			<span class="podcast">eDucando Geek</span>
			<span class="track">#06 Micrófono Boya M1 - Kindle Paperwhite - Goodreads, RRSS para lectores</span>
		</a>
	</span>
</li>
<li>
	<span id="item-948">
		<a href="#" data-media="https://archive.org/download/05ComoHacerUnPodcastPorQueGrabarUnPodcast/05-como-hacer-un-podcast-por-que-grabar-un-podcast.mp3" title="#05 Cómo grabar un podcast y por qué he decidido hacer el mío">
			<span class="isplaying"></span>
			<span class="logo educandogeek"></span>
			<span class="podcast">eDucando Geek</span>
			<span class="track">#05 Cómo grabar un podcast y por qué he decidido hacer el mío</span>
		</a>
	</span>
</li>
<li>
	<span id="item-949">
		<a href="#" data-media="https://archive.org/download/04PrimeraTomaDeContatctoXiaomiRn3pro_201706/04-primera-toma-de-contatcto-xiaomi-rn3pro.mp3" title="#04 Mis primeras impresiones con el Xiaomi Redmi Note 3 Pro">
			<span class="isplaying"></span>
			<span class="logo educandogeek"></span>
			<span class="podcast">eDucando Geek</span>
			<span class="track">#04 Mis primeras impresiones con el Xiaomi Redmi Note 3 Pro</span>
		</a>
	</span>
</li>
<li>
	<span id="item-950">
		<a href="#" data-media="https://archive.org/download/03YoigoCapaLosTorrentsVacunacionInfantil/03-yoigo-capa-los-torrents-vacunacion-infantil.mp3" title="#03 Yoigo capa las descargas por Torrent - Vacunación">
			<span class="isplaying"></span>
			<span class="logo educandogeek"></span>
			<span class="podcast">eDucando Geek</span>
			<span class="track">#03 Yoigo capa las descargas por Torrent - Vacunación</span>
		</a>
	</span>
</li>
<li>
	<span id="item-951">
		<a href="#" data-media="https://archive.org/download/02EsperandoElXiaomiRedmiNote3Pro_20170614/02-esperando-el-xiaomi-redmi-note-3-pro.mp3" title="#02 Esperando el Xiaomi Redmi Note 3 Pro">
			<span class="isplaying"></span>
			<span class="logo educandogeek"></span>
			<span class="podcast">eDucando Geek</span>
			<span class="track">#02 Esperando el Xiaomi Redmi Note 3 Pro</span>
		</a>
	</span>
</li>
<li>
	<span id="item-952">
		<a href="#" data-media="http://www.ivoox.com/13-ex12-1-samyang-35mm-f-2-8-para-nikon_mf_19217822_feed_1.mp3" title="#13 (ex12+1) Samyang 35mm f 2,8 para nikon, Amazon nos da una de arena... resaca WWDC">
			<span class="isplaying"></span>
			<span class="logo reflexpodcast"></span>
			<span class="podcast">reflex podcast</span>
			<span class="track">#13 (ex12+1) Samyang 35mm f 2,8 para nikon, Amazon nos da una de arena... resaca WWDC</span>
		</a>
	</span>
</li>
<li>
	<span id="item-953">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/593e9530b329c72dc834e856.mp3" title="El informe de Uber, Xbox One X, Kitty Hawk">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">El informe de Uber, Xbox One X, Kitty Hawk</span>
		</a>
	</span>
</li>
<li>
	<span id="item-954">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/6006587/Bat2x100_142.m4a" title="#142 – NAS huérfano busca propietario !">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#142 – NAS huérfano busca propietario !</span>
		</a>
	</span>
</li>
<li>
	<span id="item-955">
		<a href="#" data-media="http://traffic.libsyn.com/cesargarciasaez/LHM096.mp3" title="LHM 096 en directo – Preguntas y proyectos con David Cuartielles (Junio 2017)">
			<span class="isplaying"></span>
			<span class="logo lahoramaker"></span>
			<span class="podcast">La Hora Maker</span>
			<span class="track">LHM 096 en directo – Preguntas y proyectos con David Cuartielles (Junio 2017)</span>
		</a>
	</span>
</li>
<li>
	<span id="item-956">
		<a href="#" data-media="https://archive.org/download/01EpisodioPiloto_20170614/01-episodio-piloto.mp3" title="#01 Capítulo piloto">
			<span class="isplaying"></span>
			<span class="logo educandogeek"></span>
			<span class="podcast">eDucando Geek</span>
			<span class="track">#01 Capítulo piloto</span>
		</a>
	</span>
</li>
<li>
	<span id="item-957">
		<a href="#" data-media="https://www.ivoox.com/s01e05-comprar-pcs-ubuntu-desbandada-desarrolladores-canonical_mf_19187730_feed_1.mp3" title="S01E05 Comprar PCs con Ubuntu, desbandada desarrolladores Canonical y Chrome ha ganado ¿qué puede hacer Mozilla?">
			<span class="isplaying"></span>
			<span class="logo ubuntuyotrashierbas"></span>
			<span class="podcast">Ubuntu y otras hierbas</span>
			<span class="track">S01E05 Comprar PCs con Ubuntu, desbandada desarrolladores Canonical y Chrome ha ganado ¿qué puede hacer Mozilla?</span>
		</a>
	</span>
</li>
<li>
	<span id="item-958">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/06/podcast-34-servicio-de-correo.mp3" title="Podcast #34: Servicio de correo">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #34: Servicio de correo</span>
		</a>
	</span>
</li>
<li>
	<span id="item-959">
		<a href="#" data-media="https://ia801505.us.archive.org/28/items/062.DomoticaConMiRasperry./062.%20Domotica%20con%20mi%20Rasperry..mp3" title="062. Domótica con mi Raspberry Pi. Usemos el GPIO">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">062. Domótica con mi Raspberry Pi. Usemos el GPIO</span>
		</a>
	</span>
</li>
<li>
	<span id="item-960">
		<a href="#" data-media="http://tracking.feedpress.it/link/15407/5994820/BCS013-Privacidad-en-Redes-Sociales.mp3" title="BCS013 – Privacidad en Redes Sociales">
			<span class="isplaying"></span>
			<span class="logo bitácoradeciberseguridad"></span>
			<span class="podcast">Bitácora de Ciberseguridad</span>
			<span class="track">BCS013 – Privacidad en Redes Sociales</span>
		</a>
	</span>
</li>
<li>
	<span id="item-961">
		<a href="#" data-media="https://deployando.me/podcast-download/159/15-copiando-bloques.mp3" title="15 – copiando bloques">
			<span class="isplaying"></span>
			<span class="logo deployandome"></span>
			<span class="podcast">deployando.me</span>
			<span class="track">15 – copiando bloques</span>
		</a>
	</span>
</li>
<li>
	<span id="item-962">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/5939178bb329c72dc834a83f.mp3" title="Mortadelo y Filemon, directivos de Uber">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Mortadelo y Filemon, directivos de Uber</span>
		</a>
	</span>
</li>
<li>
	<span id="item-963">
		<a href="#" data-media="http://www.ivoox.com/mintablet-android-auto_mf_19147130_feed_1.mp3" title="mintablet - Android Auto">
			<span class="isplaying"></span>
			<span class="logo podcastwintabletinfo"></span>
			<span class="podcast">Podcast WINTABLET.INFO</span>
			<span class="track">mintablet - Android Auto</span>
		</a>
	</span>
</li>
<li>
	<span id="item-964">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/5981666/Bat2x100_141.m4a" title="#141 – Miscelánea de miércoles.">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#141 – Miscelánea de miércoles.</span>
		</a>
	</span>
</li>
<li>
	<span id="item-965">
		<a href="#" data-media="http://www.ivoox.com/26-linux-connexion-ugeek_mf_19127057_feed_1.mp3" title="#26 Linux Connexion con Ugeek">
			<span class="isplaying"></span>
			<span class="logo podcastlinux"></span>
			<span class="podcast">Podcast Linux</span>
			<span class="track">#26 Linux Connexion con Ugeek</span>
		</a>
	</span>
</li>
<li>
	<span id="item-966">
		<a href="#" data-media="http://traffic.libsyn.com/cesargarciasaez/LHM095.mp3" title="LHM 095 – Visitamos ITmakES Village, la muestra de proyectos maker italoespañola">
			<span class="isplaying"></span>
			<span class="logo lahoramaker"></span>
			<span class="podcast">La Hora Maker</span>
			<span class="track">LHM 095 – Visitamos ITmakES Village, la muestra de proyectos maker italoespañola</span>
		</a>
	</span>
</li>
<li>
	<span id="item-967">
		<a href="#" data-media="http://tracking.feedpress.it/link/14730/7427249/CN_Programa_026.mp3" title="#CN026 – Synology Workshop Barcelona con Manuel Jordán">
			<span class="isplaying"></span>
			<span class="logo culturanas"></span>
			<span class="podcast">Cultura NAS</span>
			<span class="track">#CN026 – Synology Workshop Barcelona con Manuel Jordán</span>
		</a>
	</span>
</li>
<li>
	<span id="item-968">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/5937b328b329c72dc8348688.mp3" title="Detalles del OnePlus 5 y Tesla Model Y">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Detalles del OnePlus 5 y Tesla Model Y</span>
		</a>
	</span>
</li>
<li>
	<span id="item-969">
		<a href="#" data-media="http://www.ivoox.com/especial-wwdc-2017-crossover-treki23-wintablet_mf_19126331_feed_1.mp3" title="Especial WWDC 2017 - Crossover Treki23 y Wintablet">
			<span class="isplaying"></span>
			<span class="logo podcastwintabletinfo"></span>
			<span class="podcast">Podcast WINTABLET.INFO</span>
			<span class="track">Especial WWDC 2017 - Crossover Treki23 y Wintablet</span>
		</a>
	</span>
</li>
<li>
	<span id="item-970">
		<a href="#" data-media="http://feedproxy.google.com/~r/WecodesignPodcast/~5/bZ7XxdyRpsE/WeCodeSign%202x02%20-%20Toma%20de%20Requisitos.mp3" title="2x02 - Toma de Requisitos">
			<span class="isplaying"></span>
			<span class="logo wecodesignpodcast"></span>
			<span class="podcast">WeCodeSign Podcast</span>
			<span class="track">2x02 - Toma de Requisitos</span>
		</a>
	</span>
</li>
<li>
	<span id="item-971">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/59364ca2b329c72dc83463ef.mp3" title="¿HomePod?">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">¿HomePod?</span>
		</a>
	</span>
</li>
<li>
	<span id="item-972">
		<a href="#" data-media="http://api.spreaker.com/download/episode/12044042/podcast114.mp3" title="114. Sigfox, Arduino MKRFOX1200 y un medidor de radiación UV">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">114. Sigfox, Arduino MKRFOX1200 y un medidor de radiación UV</span>
		</a>
	</span>
</li>
<li>
	<span id="item-973">
		<a href="#" data-media="http://tracking.feedpress.it/link/16349/5966777/DT-06-Obijuan.mp3" title="#06 Mundo Maker con @Obijuan_cube">
			<span class="isplaying"></span>
			<span class="logo droidtalks"></span>
			<span class="podcast">Droid Talks</span>
			<span class="track">#06 Mundo Maker con @Obijuan_cube</span>
		</a>
	</span>
</li>
<li>
	<span id="item-974">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/59355b83b329c72dc83451d1.mp3" title="Bingo del WWDC de Apple">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Bingo del WWDC de Apple</span>
		</a>
	</span>
</li>
<li>
	<span id="item-975">
		<a href="#" data-media="https://www.ivoox.com/s01e04-software-libre-educacion_mf_19068060_feed_1.mp3" title="S01E04 Software libre en la educación">
			<span class="isplaying"></span>
			<span class="logo ubuntuyotrashierbas"></span>
			<span class="podcast">Ubuntu y otras hierbas</span>
			<span class="track">S01E04 Software libre en la educación</span>
		</a>
	</span>
</li>
<li>
	<span id="item-976">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/325930904-ricardo-garc-a-34-polvo-cosmico-que-gira-ep95.mp3" title="Polvo Cósmico que gira [Ep.95]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Polvo Cósmico que gira [Ep.95]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-977">
		<a href="#" data-media="https://www.ivoox.com/s01e03-seguridad-privacidad_mf_19058066_feed_1.mp3" title="S01E03 Seguridad y privacidad">
			<span class="isplaying"></span>
			<span class="logo ubuntuyotrashierbas"></span>
			<span class="podcast">Ubuntu y otras hierbas</span>
			<span class="track">S01E03 Seguridad y privacidad</span>
		</a>
	</span>
</li>
<li>
	<span id="item-978">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/06/podcast-33-virtualizacion-personal.mp3" title="Podcast #33: Virtualiación personal con VMWare Workstation y Virtualbox">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #33: Virtualiación personal con VMWare Workstation y Virtualbox</span>
		</a>
	</span>
</li>
<li>
	<span id="item-979">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/06/podcast-32-especial-openexpo.mp3" title="Podcast #32: Especial OpenExpo 2017">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #32: Especial OpenExpo 2017</span>
		</a>
	</span>
</li>
<li>
	<span id="item-980">
		<a href="#" data-media="https://ia601502.us.archive.org/23/items/DockerEnMenosDe10Min/Docker%20en%20menos%20de%2010%20min.mp3" title="061. Docker en 10 minutos">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">061. Docker en 10 minutos</span>
		</a>
	</span>
</li>
<li>
	<span id="item-981">
		<a href="#" data-media="http://podcast.edyo.es/podcast/edyo-25.mp3" title="Edyo 25 - Cómo organizar con éxito un evento como PyData Barcelona 2017.">
			<span class="isplaying"></span>
			<span class="logo entredevyopspodcast"></span>
			<span class="podcast">EntreDevYOps Podcast</span>
			<span class="track">Edyo 25 - Cómo organizar con éxito un evento como PyData Barcelona 2017.</span>
		</a>
	</span>
</li>
<li>
	<span id="item-982">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/5955001/Bat2x100_140.m4a" title="#140 – Sorteo  y más contenido …con sorpresa!">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#140 – Sorteo  y más contenido …con sorpresa!</span>
		</a>
	</span>
</li>
<li>
	<span id="item-983">
		<a href="#" data-media="http://www.ivoox.com/avance-tecnologico-tercera-edad_mf_19037235_feed_1.mp3" title="El avance tecnológico y la tercera edad - Cap 72">
			<span class="isplaying"></span>
			<span class="logo podcastwintabletinfo"></span>
			<span class="podcast">Podcast WINTABLET.INFO</span>
			<span class="track">El avance tecnológico y la tercera edad - Cap 72</span>
		</a>
	</span>
</li>
<li>
	<span id="item-984">
		<a href="#" data-media="http://tracking.feedpress.it/link/14730/7427250/CN_Programa_025.mp3" title="#CN025 – Especial preguntas (atrasadas) de oyentes">
			<span class="isplaying"></span>
			<span class="logo culturanas"></span>
			<span class="podcast">Cultura NAS</span>
			<span class="track">#CN025 – Especial preguntas (atrasadas) de oyentes</span>
		</a>
	</span>
</li>
<li>
	<span id="item-985">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/5930ccb7b329c72dc833f861.mp3" title="Brave, el navegador valiente">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Brave, el navegador valiente</span>
		</a>
	</span>
</li>
<li>
	<span id="item-986">
		<a href="#" data-media="https://ia601504.us.archive.org/9/items/TerminalAlias/Terminal%20alias.mp3" title="060. La Terminal mas fácil con alias">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">060. La Terminal mas fácil con alias</span>
		</a>
	</span>
</li>
<li>
	<span id="item-987">
		<a href="#" data-media="http://www.ivoox.com/12-nuevas-opticas-angulares-nikon-poco_mf_19016957_feed_1.mp3" title="#12 Nuevas ópticas angulares Nikon y un poco de HDR">
			<span class="isplaying"></span>
			<span class="logo reflexpodcast"></span>
			<span class="podcast">reflex podcast</span>
			<span class="track">#12 Nuevas ópticas angulares Nikon y un poco de HDR</span>
		</a>
	</span>
</li>
<li>
	<span id="item-988">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/592ec8091cb1bc5a7af04eba.mp3" title="Decepción Esencial">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Decepción Esencial</span>
		</a>
	</span>
</li>
<li>
	<span id="item-989">
		<a href="#" data-media="https://gitlab.com/podcastlinux/podcastlinux.gitlab.io/raw/master/Linux-Express/%2316%20Podcast%20Linux%20Express.mp3" title="#16 Linux Express">
			<span class="isplaying"></span>
			<span class="logo linuxexpressdepodcastlinux"></span>
			<span class="podcast">Linux Express, de Podcast Linux.</span>
			<span class="track">#16 Linux Express</span>
		</a>
	</span>
</li>
<li>
	<span id="item-990">
		<a href="#" data-media="http://feedproxy.google.com/~r/WecodesignPodcast/~5/Cbr5mrFy83g/WeCodeSign-Mini-5.mp3" title="Mini 5 - ¿Sómos proactivos?">
			<span class="isplaying"></span>
			<span class="logo wecodesignpodcast"></span>
			<span class="podcast">WeCodeSign Podcast</span>
			<span class="track">Mini 5 - ¿Sómos proactivos?</span>
		</a>
	</span>
</li>
<li>
	<span id="item-991">
		<a href="#" data-media="http://traffic.libsyn.com/cesargarciasaez/LHM094.mp3" title="LHM 094 – Fablab Festival abre la temporada de actividades maker del verano">
			<span class="isplaying"></span>
			<span class="logo lahoramaker"></span>
			<span class="podcast">La Hora Maker</span>
			<span class="track">LHM 094 – Fablab Festival abre la temporada de actividades maker del verano</span>
		</a>
	</span>
</li>
<li>
	<span id="item-992">
		<a href="#" data-media="http://www.ivoox.com/26-cuando-es-recomendable-cambiar-router_mf_18945263_feed_1.mp3" title="26. ¿Cuándo es recomendable cambiar de router?">
			<span class="isplaying"></span>
			<span class="logo naserospodcast"></span>
			<span class="podcast">NASeros Podcast</span>
			<span class="track">26. ¿Cuándo es recomendable cambiar de router?</span>
		</a>
	</span>
</li>
<li>
	<span id="item-993">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/5923403/Bat2x100_139.m4a" title="#139 – Miscelánea… De lunes !">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#139 – Miscelánea… De lunes !</span>
		</a>
	</span>
</li>
<li>
	<span id="item-994">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/05/podcast-31-migracion-a-kde-neon.mp3" title="Podcast #31: Migración a KDE Neón 5.9">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #31: Migración a KDE Neón 5.9</span>
		</a>
	</span>
</li>
<li>
	<span id="item-995">
		<a href="#" data-media="http://compilando.audio/wp-content/uploads/2017/05/podcast6.mp3" title="Podcast 6 – openSuse y KDE con Antonio Larrosa . OpenExpo2017">
			<span class="isplaying"></span>
			<span class="logo compilandopodcast"></span>
			<span class="podcast">Compilando Podcast</span>
			<span class="track">Podcast 6 – openSuse y KDE con Antonio Larrosa . OpenExpo2017</span>
		</a>
	</span>
</li>
<li>
	<span id="item-996">
		<a href="#" data-media="http://www.ivoox.com/retroactivo-podcast-64-la-wonderswan_mf_18926581_feed_1.mp3" title="RetroActivo Podcast #64: La WonderSwan">
			<span class="isplaying"></span>
			<span class="logo retroactivopodcast"></span>
			<span class="podcast">RetroActivo Podcast</span>
			<span class="track">RetroActivo Podcast #64: La WonderSwan</span>
		</a>
	</span>
</li>
<li>
	<span id="item-997">
		<a href="#" data-media="http://www.ivoox.com/11-cosas-sony-miscelanea-varia_mf_18903284_feed_1.mp3" title="#11 Cosas de Sony y miscelanea varia">
			<span class="isplaying"></span>
			<span class="logo reflexpodcast"></span>
			<span class="podcast">reflex podcast</span>
			<span class="track">#11 Cosas de Sony y miscelanea varia</span>
		</a>
	</span>
</li>
<li>
	<span id="item-998">
		<a href="#" data-media="https://ia801505.us.archive.org/21/items/059.2AplicacinesParaTomarNotas/059.%202%20Aplicaci%C3%B3nes%20para%20tomar%20Notas.mp3" title="059. 2 Aplicaciones de Notas alternativas que utilizo">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">059. 2 Aplicaciones de Notas alternativas que utilizo</span>
		</a>
	</span>
</li>
<li>
	<span id="item-999">
		<a href="#" data-media="https://ia601502.us.archive.org/10/items/058.Android.AppCloneMultipleAccounts/058.%20Android.%20App%20clone%20-%20Multiple%20Accounts.m4a" title="058. Android: Multicuentas. Gestion de Servicios Raspberry Pi">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">058. Android: Multicuentas. Gestion de Servicios Raspberry Pi</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1000">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/05/podcast-30-instalacion-freepbx.mp3" title="Podcast #30: Instalación de FreePBX">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #30: Instalación de FreePBX</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1001">
		<a href="#" data-media="http://feedproxy.google.com/~r/WecodesignPodcast/~5/C3TotpUgxyQ/WeCodeSign%202x01%20-%20Adalab.mp3" title="2x01 - Adalab">
			<span class="isplaying"></span>
			<span class="logo wecodesignpodcast"></span>
			<span class="podcast">WeCodeSign Podcast</span>
			<span class="track">2x01 - Adalab</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1002">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/592455423344500e15b2516f.mp3" title="Guerra de tabletas que quieren ser portátil">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Guerra de tabletas que quieren ser portátil</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1003">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/59241fec3344500e15b23f78.mp3" title="Comprar los coches por su ordenador, no por su motor">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Comprar los coches por su ordenador, no por su motor</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1004">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/324048026-ricardo-garc-a-34-ep94.mp3" title="Buscando señales de vida extraterrestre en exoplanetas [Ep.94]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Buscando señales de vida extraterrestre en exoplanetas [Ep.94]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1005">
		<a href="#" data-media="http://api.spreaker.com/download/episode/11930794/podcast113.mp3" title="#113 Aprender Arduino con Enrique Crespo (@jecrespom)">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">#113 Aprender Arduino con Enrique Crespo (@jecrespom)</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1006">
		<a href="#" data-media="http://podcast.edyo.es/podcast/edyo-24.mp3" title="Edyo 24 - Especial Wannacry.">
			<span class="isplaying"></span>
			<span class="logo entredevyopspodcast"></span>
			<span class="podcast">EntreDevYOps Podcast</span>
			<span class="track">Edyo 24 - Especial Wannacry.</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1007">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/5882630/Bat2x100_138.m4a" title="#138 – Executar Workflows de forma “automática”">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#138 – Executar Workflows de forma “automática”</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1008">
		<a href="#" data-media="http://www.ivoox.com/25-conexiones-remotas-como-puede-afectarnos-la_mf_18813411_feed_1.mp3" title="25. Conexiones remotas y cómo puede afectarnos la llegada IPv6">
			<span class="isplaying"></span>
			<span class="logo naserospodcast"></span>
			<span class="podcast">NASeros Podcast</span>
			<span class="track">25. Conexiones remotas y cómo puede afectarnos la llegada IPv6</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1009">
		<a href="#" data-media="https://www.ivoox.com/s01e02-gnome3-ubports_mf_18807244_feed_1.mp3" title="S01E02 GNOME3 y UBPorts">
			<span class="isplaying"></span>
			<span class="logo ubuntuyotrashierbas"></span>
			<span class="podcast">Ubuntu y otras hierbas</span>
			<span class="track">S01E02 GNOME3 y UBPorts</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1010">
		<a href="#" data-media="https://gitlab.com/podcastlinux/podcastlinux.gitlab.io/raw/master/Linux-Express/%2315%20Podcast%20Linux%20Express.mp3" title="#15 Linux Express ¿Mp3 o Ogg? y 2">
			<span class="isplaying"></span>
			<span class="logo linuxexpressdepodcastlinux"></span>
			<span class="podcast">Linux Express, de Podcast Linux.</span>
			<span class="track">#15 Linux Express ¿Mp3 o Ogg? y 2</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1011">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/05/podcast-29-calidad-de-servicio-en-linux.mp3" title="Podcast #29: Calidad de servicio en GNU/Linux">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #29: Calidad de servicio en GNU/Linux</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1012">
		<a href="#" data-media="http://mundipad.es/capitulos-podcast-bemoob/089-foromoviles-podcast.mp3" title="ForoMoviles Podcast 089: Google I/O 2017, root y más">
			<span class="isplaying"></span>
			<span class="logo podcastforomóviles"></span>
			<span class="podcast">Podcast – ForoMóviles</span>
			<span class="track">ForoMoviles Podcast 089: Google I/O 2017, root y más</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1013">
		<a href="#" data-media="https://gitlab.com/podcastlinux/podcastlinux.gitlab.io/raw/master/Linux-Express/%2314%20Podcast%20Linux%20Express.mp3" title="#14 Linux Express ¿Mp3 o Ogg?">
			<span class="isplaying"></span>
			<span class="logo linuxexpressdepodcastlinux"></span>
			<span class="podcast">Linux Express, de Podcast Linux.</span>
			<span class="track">#14 Linux Express ¿Mp3 o Ogg?</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1014">
		<a href="#" data-media="https://ia801500.us.archive.org/13/items/057.MulticuentaTelegramWire/057.%20Multicuenta%20telegram,%20wire.mp3" title="057. Multicuenta de Telegram en tu PC de escritorio y Wire">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">057. Multicuenta de Telegram en tu PC de escritorio y Wire</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1015">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/5858522/Bat2x100_137.m4a" title="#137 – Apps y un WorkFlow muy muy guapo !">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#137 – Apps y un WorkFlow muy muy guapo !</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1016">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/591d35b73344500e15b1ddb3.mp3" title="Buen comienzo del Google IO 2017">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Buen comienzo del Google IO 2017</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1017">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/5853048/Bat2x100_136.m4a" title="#136 – 1 año de podcasting">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#136 – 1 año de podcasting</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1018">
		<a href="#" data-media="http://traffic.libsyn.com/cesargarciasaez/LHM093.mp3" title="LHM 093 – Cómo impedir que se infecten los equipos de tu makespace con el virus WannaCry">
			<span class="isplaying"></span>
			<span class="logo lahoramaker"></span>
			<span class="podcast">La Hora Maker</span>
			<span class="track">LHM 093 – Cómo impedir que se infecten los equipos de tu makespace con el virus WannaCry</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1019">
		<a href="#" data-media="https://ia801503.us.archive.org/12/items/056.VideoderYLlamadasTelegram/056.%20Videoder%20y%20llamadas%20Telegram.mp3" title="056. Android: Videoder y llamadas de Telegram">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">056. Android: Videoder y llamadas de Telegram</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1020">
		<a href="#" data-media="https://ia801506.us.archive.org/9/items/055.M4aAplicacionesDePodcastYNuevoMicro/055.%20M4a,%20aplicaciones%20de%20Podcast%20y%20nuevo%20micro.mp3" title="055. Nuevos Cambios...">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">055. Nuevos Cambios...</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1021">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/591bb356be432b0407404cb8.mp3" title="El objetivo final de Uber, Waymo, Lyft, Tesla, etc.">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">El objetivo final de Uber, Waymo, Lyft, Tesla, etc.</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1022">
		<a href="#" data-media="https://gitlab.com/podcastlinux/podcastlinux.gitlab.io/raw/master/Linux-Express/%2313%20Podcast%20Linux%20Express.mp3" title="#13 Linux Express">
			<span class="isplaying"></span>
			<span class="logo linuxexpressdepodcastlinux"></span>
			<span class="podcast">Linux Express, de Podcast Linux.</span>
			<span class="track">#13 Linux Express</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1023">
		<a href="#" data-media="http://www.ivoox.com/10-seguridad-fotografica-para-guardar-nuestras-fotos_mf_18727432_feed_1.mp3" title="#10 Seguridad Fotográfica para guardar nuestras fotos.">
			<span class="isplaying"></span>
			<span class="logo reflexpodcast"></span>
			<span class="podcast">reflex podcast</span>
			<span class="track">#10 Seguridad Fotográfica para guardar nuestras fotos.</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1024">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/591bb162be432b0407404655.mp3" title="El problema de Project Treble en Android">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">El problema de Project Treble en Android</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1025">
		<a href="#" data-media="http://feedproxy.google.com/~r/WecodesignPodcast/~5/Yac3gi0kwyU/WeCodeSign%20Mini%204%20-%20Un%20an%CC%83o%20de%20WeCodeSign.mp3" title="Mini 4 - Un año de WeCodeSign">
			<span class="isplaying"></span>
			<span class="logo wecodesignpodcast"></span>
			<span class="podcast">WeCodeSign Podcast</span>
			<span class="track">Mini 4 - Un año de WeCodeSign</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1026">
		<a href="#" data-media="http://www.ivoox.com/espana-reserva-ciberguerrera-occidente-episodio_mf_18703671_feed_1.mp3" title="España, la reserva ciberguerrera de Occidente | Episodio 57">
			<span class="isplaying"></span>
			<span class="logo repúblicaweb"></span>
			<span class="podcast">República Web</span>
			<span class="track">España, la reserva ciberguerrera de Occidente | Episodio 57</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1027">
		<a href="#" data-media="http://podcast.edyo.es/podcast/edyo-23.mp3" title="Edyo 23 - Vulnerabilidad de Wordpress, generadores de contenido estáticos y Amazon Drive.">
			<span class="isplaying"></span>
			<span class="logo entredevyopspodcast"></span>
			<span class="podcast">EntreDevYOps Podcast</span>
			<span class="track">Edyo 23 - Vulnerabilidad de Wordpress, generadores de contenido estáticos y Amazon Drive.</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1028">
		<a href="#" data-media="http://www.ivoox.com/24-que-es-ransomware-crossover-adekkar_mf_18675963_feed_1.mp3" title="24. ¿Qué es un ransomware? Crossover con @Dekkar y @bateria2x100">
			<span class="isplaying"></span>
			<span class="logo naserospodcast"></span>
			<span class="podcast">NASeros Podcast</span>
			<span class="track">24. ¿Qué es un ransomware? Crossover con @Dekkar y @bateria2x100</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1029">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/5834676/Bat2x100_135.mp3" title="#135 – # Ransomware_WannaCry @Dekkar @macjosan Must listen !">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#135 – # Ransomware_WannaCry @Dekkar @macjosan Must listen !</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1030">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/322584990-ricardo-garc-a-34-ep93.mp3" title="Cómo el universo llegó a ser como lo conocemos [Ep.93]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Cómo el universo llegó a ser como lo conocemos [Ep.93]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1031">
		<a href="#" data-media="http://tracking.feedpress.it/link/15407/5834148/BCS-012-Ransomware-WannaCry.mp3" title="Ransomware WannaCry, con Securizando">
			<span class="isplaying"></span>
			<span class="logo bitácoradeciberseguridad"></span>
			<span class="podcast">Bitácora de Ciberseguridad</span>
			<span class="track">Ransomware WannaCry, con Securizando</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1032">
		<a href="#" data-media="http://compilando.audio/wp-content/uploads/2017/05/podcast5.mp3" title="Podcast 5 – Radios Libres. Microsoft y su “amor” por GNU/Linux.">
			<span class="isplaying"></span>
			<span class="logo compilandopodcast"></span>
			<span class="podcast">Compilando Podcast</span>
			<span class="track">Podcast 5 – Radios Libres. Microsoft y su “amor” por GNU/Linux.</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1033">
		<a href="#" data-media="http://mundipad.es/capitulos-podcast-bemoob/088-foromoviles-podcast.mp3" title="ForoMoviles Podcast 088: Ransomware, Treble, LG G6…">
			<span class="isplaying"></span>
			<span class="logo podcastforomóviles"></span>
			<span class="podcast">Podcast – ForoMóviles</span>
			<span class="track">ForoMoviles Podcast 088: Ransomware, Treble, LG G6…</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1034">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/5826921/Bat2x100_134.mp3" title="#134 – Charla con …. @Patuflinx !">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#134 – Charla con …. @Patuflinx !</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1035">
		<a href="#" data-media="http://www.ivoox.com/9-fotografiar-fauna-pajaros_mf_18653942_feed_1.mp3" title="#9 Fotografiar fauna ( Pájaros)">
			<span class="isplaying"></span>
			<span class="logo reflexpodcast"></span>
			<span class="podcast">reflex podcast</span>
			<span class="track">#9 Fotografiar fauna ( Pájaros)</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1036">
		<a href="#" data-media="https://ia601507.us.archive.org/31/items/054.TelefnicaEstaSiendoAtacada/054.%20Telef%C3%B3nica%20esta%20siendo%20atacada!%20.mp3" title="054. Telefónica esta siendo Atacada!!!">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">054. Telefónica esta siendo Atacada!!!</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1037">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/05/podcast-28-ipv6-segunda-parte.mp3" title="Podcast #28: IPv6 (segunda parte)">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #28: IPv6 (segunda parte)</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1038">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/5913d338cce049e0751d871b.mp3" title="Necesitamos un Snapchat fuerte">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Necesitamos un Snapchat fuerte</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1039">
		<a href="#" data-media="http://feedproxy.google.com/~r/Vaciatubandeja/~5/gKM4otPERmA/06%20Identifica%20bien%20tus%20bandejas%20de%20entrada.mp3" title="#06-Identifica bien tus Bandejas de Entrada">
			<span class="isplaying"></span>
			<span class="logo vaciatubandeja"></span>
			<span class="podcast">Vacia Tu Bandeja</span>
			<span class="track">#06-Identifica bien tus Bandejas de Entrada</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1040">
		<a href="#" data-media="http://api.spreaker.com/download/episode/11835110/s02e07_a_todo_datas_con_pantojacoder_soygema_y_javisantana.mp3" title="S02E07 A Todo Datas!  con @pantojacoder @SoyGema y @javisantana">
			<span class="isplaying"></span>
			<span class="logo codeontherocks"></span>
			<span class="podcast">Code on the rocks</span>
			<span class="track">S02E07 A Todo Datas!  con @pantojacoder @SoyGema y @javisantana</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1041">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/591323a6cce049e0751d6668.mp3" title="YouTube va bien, los youtubers no tanto (Audio corregido)">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">YouTube va bien, los youtubers no tanto (Audio corregido)</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1042">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/5812783/Bat2x100_133.mp3" title="#133 – # Crossover de Seguridad con Andreu Adrover">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#133 – # Crossover de Seguridad con Andreu Adrover</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1043">
		<a href="#" data-media="http://www.ivoox.com/24-linux-connexion-davidochobits_mf_18604559_feed_1.mp3" title="#24 Linux Connexion con DavidOchoBits">
			<span class="isplaying"></span>
			<span class="logo podcastlinux"></span>
			<span class="podcast">Podcast Linux</span>
			<span class="track">#24 Linux Connexion con DavidOchoBits</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1044">
		<a href="#" data-media="http://www.ivoox.com/mark-zuckerberg-for-president-episodio-56_mf_18596853_feed_1.mp3" title="Mark Zuckerberg for President | Episodio 56">
			<span class="isplaying"></span>
			<span class="logo repúblicaweb"></span>
			<span class="podcast">República Web</span>
			<span class="track">Mark Zuckerberg for President | Episodio 56</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1045">
		<a href="#" data-media="https://ia601502.us.archive.org/7/items/053.Synapse/053.%20Synapse%20.mp3" title="053. Synapse">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">053. Synapse</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1046">
		<a href="#" data-media="http://feedproxy.google.com/~r/WecodesignPodcast/~5/i7ecFfN9_R4/WeCodeSign%201x27%20-%20Paradigmas%20de%20Interaccio%CC%81n.mp3" title="27 - Paradigmas de Interacción">
			<span class="isplaying"></span>
			<span class="logo wecodesignpodcast"></span>
			<span class="podcast">WeCodeSign Podcast</span>
			<span class="track">27 - Paradigmas de Interacción</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1047">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/5911a033b1c92f596b80c823.mp3" title="La guerra por tu salón">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">La guerra por tu salón</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1048">
		<a href="#" data-media="http://traffic.libsyn.com/cesargarciasaez/LHM092.mp3" title="LHM 092 – Valentín Muro comparte sus aprendizajes tras grabar un documental explorando qué ocurre en los espacios maker por el mundo">
			<span class="isplaying"></span>
			<span class="logo lahoramaker"></span>
			<span class="podcast">La Hora Maker</span>
			<span class="track">LHM 092 – Valentín Muro comparte sus aprendizajes tras grabar un documental explorando qué ocurre en los espacios maker por el mundo</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1049">
		<a href="#" data-media="http://api.spreaker.com/download/episode/11823013/podcast112.mp3" title="#112 4 formas de geolocalizar Arduino, GPS, GSM, LPWAN y WiFi">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">#112 4 formas de geolocalizar Arduino, GPS, GSM, LPWAN y WiFi</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1050">
		<a href="#" data-media="http://tracking.feedpress.it/link/15407/5799695/BCS-011-Panico-en-el-hospital.mp3" title="BCS011 – Pánico en el Hospital">
			<span class="isplaying"></span>
			<span class="logo bitácoradeciberseguridad"></span>
			<span class="podcast">Bitácora de Ciberseguridad</span>
			<span class="track">BCS011 – Pánico en el Hospital</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1051">
		<a href="#" data-media="http://tracking.feedpress.it/link/16349/5799233/DT5-Licencias.mp3" title="#5 Licencias">
			<span class="isplaying"></span>
			<span class="logo droidtalks"></span>
			<span class="podcast">Droid Talks</span>
			<span class="track">#5 Licencias</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1052">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/590ff7e2b9e256b6214a38ba.mp3" title="Estamos atrapados entre Stallman y Zuckerberg">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Estamos atrapados entre Stallman y Zuckerberg</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1053">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/5794178/Bat2x100_132.mp3" title="#132 – Jekill o WordPress">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#132 – Jekill o WordPress</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1054">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/05/podcast-27-ipv6-primera-parte.mp3" title="Podcast #27: IPv6 (primera parte)">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #27: IPv6 (primera parte)</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1055">
		<a href="#" data-media="https://ia601506.us.archive.org/33/items/JekyllOWordpress/Jekyll%20o%20Wordpress.mp3" title="052. ¿Jekyll o WordPress?">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">052. ¿Jekyll o WordPress?</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1056">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/5788411/Bat2x100_131.mp3" title="#131 – Worflow Avanzado (VIII)">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#131 – Worflow Avanzado (VIII)</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1057">
		<a href="#" data-media="http://traffic.libsyn.com/cesargarciasaez/LHM091.mp3" title="LHM 091 – Preguntas y proyectos con David Cuartielles edición Mayo 2017">
			<span class="isplaying"></span>
			<span class="logo lahoramaker"></span>
			<span class="podcast">La Hora Maker</span>
			<span class="track">LHM 091 – Preguntas y proyectos con David Cuartielles edición Mayo 2017</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1058">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/590c1471725a19ff42b63370.mp3" title="El iPad estaba destinado a mucho más">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">El iPad estaba destinado a mucho más</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1059">
		<a href="#" data-media="http://tracking.feedpress.it/link/14730/7427251/CN_Programa_024.mp3" title="#CN024 – Los 1001 usos de un NAS by Sergio Navas de @isenacode">
			<span class="isplaying"></span>
			<span class="logo culturanas"></span>
			<span class="podcast">Cultura NAS</span>
			<span class="track">#CN024 – Los 1001 usos de un NAS by Sergio Navas de @isenacode</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1060">
		<a href="#" data-media="https://ia801502.us.archive.org/5/items/051.AdisBloggerHolaGithub/051.%20Adi%C3%B3s%20Blogger,%20Hola%20Github%20.mp3" title="051. Adiós Blogger, Hola GitHub!">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">051. Adiós Blogger, Hola GitHub!</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1061">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/590a5b8c725a19ff42b60594.mp3" title="Windows 10 S: esta película ya la he visto">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Windows 10 S: esta película ya la he visto</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1062">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/5778335/Bat2x100_130.mp3" title="#130 – Worflow Avanzado (VII)">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#130 – Worflow Avanzado (VII)</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1063">
		<a href="#" data-media="http://traffic.libsyn.com/cesargarciasaez/LHM090.mp3" title="LHM 090 – Gerard Rubio nos explica como ha evolucionado Kniterate, su tejedora de escritorio en el último año">
			<span class="isplaying"></span>
			<span class="logo lahoramaker"></span>
			<span class="podcast">La Hora Maker</span>
			<span class="track">LHM 090 – Gerard Rubio nos explica como ha evolucionado Kniterate, su tejedora de escritorio en el último año</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1064">
		<a href="#" data-media="https://deployando.me/podcast-download/153/14-vagrant-workflow-vagrant-03.mp3" title="14 – vagrant workflow (vagrant 03)">
			<span class="isplaying"></span>
			<span class="logo deployandome"></span>
			<span class="podcast">deployando.me</span>
			<span class="track">14 – vagrant workflow (vagrant 03)</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1065">
		<a href="#" data-media="https://gitlab.com/podcastlinux/podcastlinux.gitlab.io/raw/master/Linux-Express/%2312%20Podcast%20Linux%20Express.mp3" title="#12 Linux Express">
			<span class="isplaying"></span>
			<span class="logo linuxexpressdepodcastlinux"></span>
			<span class="podcast">Linux Express, de Podcast Linux.</span>
			<span class="track">#12 Linux Express</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1066">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/5773304/Bat2x100_129.mp3" title="#129 – WorkFlow Avanzado (VI)">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#129 – WorkFlow Avanzado (VI)</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1067">
		<a href="#" data-media="http://feedproxy.google.com/~r/WecodesignPodcast/~5/yd4wGQdscTk/WeCodeSign%20Mini%20-%203.mp3" title="Mini 3">
			<span class="isplaying"></span>
			<span class="logo wecodesignpodcast"></span>
			<span class="podcast">WeCodeSign Podcast</span>
			<span class="track">Mini 3</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1068">
		<a href="#" data-media="http://www.ivoox.com/016-mejora-tu-productividad-matriz_mf_18449310_feed_1.mp3" title="016 - Mejora tu productividad con la matriz de Eisenhower">
			<span class="isplaying"></span>
			<span class="logo aprendiendogtdpodcastproductividad"></span>
			<span class="podcast">Aprendiendo GTD podcast productividad</span>
			<span class="track">016 - Mejora tu productividad con la matriz de Eisenhower</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1069">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/5909ebeb21b2e3ec468912a4.mp3" title="Los smartwatch no son un fracaso, pero yo no me voy a comprar uno">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Los smartwatch no son un fracaso, pero yo no me voy a comprar uno</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1070">
		<a href="#" data-media="http://www.ivoox.com/llego-momento-poner-vpn-en_mf_18435521_feed_1.mp3" title="Llegó el momento de poner una VPN en tu vida | Episodio 55">
			<span class="isplaying"></span>
			<span class="logo repúblicaweb"></span>
			<span class="podcast">República Web</span>
			<span class="track">Llegó el momento de poner una VPN en tu vida | Episodio 55</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1071">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/05/podcast-26-odoo-y-transformacion.mp3" title="Podcast #26: Odoo y transformación digital">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #26: Odoo y transformación digital</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1072">
		<a href="#" data-media="https://ia801505.us.archive.org/9/items/050.QueAndoHaciendo/050.%20Que%20ando%20haciendo.mp3" title="050. Que ando haciendo, nuevas publicaciones y más...">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">050. Que ando haciendo, nuevas publicaciones y más...</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1073">
		<a href="#" data-media="http://www.ivoox.com/retroactivo-podcast-63-nobuo-uematsu_mf_18420168_feed_1.mp3" title="RetroActivo Podcast #63: Nobuo Uematsu">
			<span class="isplaying"></span>
			<span class="logo retroactivopodcast"></span>
			<span class="podcast">RetroActivo Podcast</span>
			<span class="track">RetroActivo Podcast #63: Nobuo Uematsu</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1074">
		<a href="#" data-media="http://traffic.libsyn.com/cesargarciasaez/LHM089.mp3" title="LHM 089 – Visitamos RetroMadrid, una de las ferias más importantes de informática retro">
			<span class="isplaying"></span>
			<span class="logo lahoramaker"></span>
			<span class="podcast">La Hora Maker</span>
			<span class="track">LHM 089 – Visitamos RetroMadrid, una de las ferias más importantes de informática retro</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1075">
		<a href="#" data-media="https://ia601503.us.archive.org/0/items/049.Syncthing/049.%20Syncthing.mp3" title="049. Instalando Syncthing en Ubuntu, Antergos y Raspberry Pi">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">049. Instalando Syncthing en Ubuntu, Antergos y Raspberry Pi</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1076">
		<a href="#" data-media="http://www.ivoox.com/8-la-profundidad-campo-noticias-fotograficas_mf_18410232_feed_1.mp3" title="#8 La profundidad de campo + noticias fotograficas">
			<span class="isplaying"></span>
			<span class="logo reflexpodcast"></span>
			<span class="podcast">reflex podcast</span>
			<span class="track">#8 La profundidad de campo + noticias fotograficas</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1077">
		<a href="#" data-media="http://compilando.audio/wp-content/uploads/2017/04/podcast4.mp3" title="Podcast 4 – Jon “maddog” Hall , Open South Code y Linux y Tapas">
			<span class="isplaying"></span>
			<span class="logo compilandopodcast"></span>
			<span class="podcast">Compilando Podcast</span>
			<span class="track">Podcast 4 – Jon “maddog” Hall , Open South Code y Linux y Tapas</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1078">
		<a href="#" data-media="http://podcast.edyo.es/podcast/edyo-22.mp3" title="Edyo 22 - Orchestrate 2017, PyData 2017, Caída s3, Vulnerabilidad de CloudFlare y Vault7.">
			<span class="isplaying"></span>
			<span class="logo entredevyopspodcast"></span>
			<span class="podcast">EntreDevYOps Podcast</span>
			<span class="track">Edyo 22 - Orchestrate 2017, PyData 2017, Caída s3, Vulnerabilidad de CloudFlare y Vault7.</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1079">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/5752088/Bat2x100_128.mp3" title="#128 – Encuentro entre dos amigos !">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#128 – Encuentro entre dos amigos !</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1080">
		<a href="#" data-media="https://ia601503.us.archive.org/28/items/EncuentroDeAmiguetes/Encuentro%20de%20amiguetes.mp3" title="048. Encuentro de amiguetes">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">048. Encuentro de amiguetes</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1081">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/5901f652340bf95e3a2764c1.mp3" title="¿Por qué Apple no lanza un iPhone barato?">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">¿Por qué Apple no lanza un iPhone barato?</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1082">
		<a href="#" data-media="http://www.ivoox.com/s01e01-ubuntu-mata-unity-movil_mf_18361665_feed_1.mp3" title="S01E01 Ubuntu mata Unity y el móvil">
			<span class="isplaying"></span>
			<span class="logo ubuntuyotrashierbas"></span>
			<span class="podcast">Ubuntu y otras hierbas</span>
			<span class="track">S01E01 Ubuntu mata Unity y el móvil</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1083">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/5900adfe8c40475974440377.mp3" title="Facebook sale de Guatemala">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Facebook sale de Guatemala</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1084">
		<a href="#" data-media="http://www.ivoox.com/23-la-terminal_mf_18347303_feed_1.mp3" title="#23 La Terminal">
			<span class="isplaying"></span>
			<span class="logo podcastlinux"></span>
			<span class="podcast">Podcast Linux</span>
			<span class="track">#23 La Terminal</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1085">
		<a href="#" data-media="http://www.ivoox.com/23-la-terminal_mf_21151730_feed_1.mp3" title="#23 La Terminal">
			<span class="isplaying"></span>
			<span class="logo podcastlinux"></span>
			<span class="podcast">Podcast Linux</span>
			<span class="track">#23 La Terminal</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1086">
		<a href="#" data-media="https://ia801500.us.archive.org/21/items/SeEstropeaLaSDDeMiRasberry/Se%20estropea%20la%20SD%20de%20mi%20rasberry.mp3" title="047. Se quemó la SD. Comparación de consumos entre PC, NAS-Microserver, Raspberry Pi">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">047. Se quemó la SD. Comparación de consumos entre PC, NAS-Microserver, Raspberry Pi</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1087">
		<a href="#" data-media="http://feedproxy.google.com/~r/WecodesignPodcast/~5/8Yjzv3PkLKM/WeCodeSign%201x26%20-%20Design%20Systems.mp3" title="26 - Design Systems">
			<span class="isplaying"></span>
			<span class="logo wecodesignpodcast"></span>
			<span class="podcast">WeCodeSign Podcast</span>
			<span class="track">26 - Design Systems</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1088">
		<a href="#" data-media="http://traffic.libsyn.com/cesargarciasaez/LHM088.mp3" title="LHM 088 – Retos y oportunidades para los Makespaces en bibliotecas">
			<span class="isplaying"></span>
			<span class="logo lahoramaker"></span>
			<span class="podcast">La Hora Maker</span>
			<span class="track">LHM 088 – Retos y oportunidades para los Makespaces en bibliotecas</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1089">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/5731739/Bat2x100_127.mp3" title="#127 – Worflow Avanzado (V)">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#127 – Worflow Avanzado (V)</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1090">
		<a href="#" data-media="http://api.spreaker.com/download/episode/11711889/podcast_111.mp3" title="#111 Lean Startup y el movimiento Maker con Néstor Guerra">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">#111 Lean Startup y el movimiento Maker con Néstor Guerra</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1091">
		<a href="#" data-media="http://feedproxy.google.com/~r/Vaciatubandeja/~5/KbK_OfgFiV4/05%20BuJo-Vista%20semanal-Areas.mp3" title="#05-Bullet Journal: Vista semanal y Areas de responsabilidad">
			<span class="isplaying"></span>
			<span class="logo vaciatubandeja"></span>
			<span class="podcast">Vacia Tu Bandeja</span>
			<span class="track">#05-Bullet Journal: Vista semanal y Areas de responsabilidad</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1092">
		<a href="#" data-media="http://www.ivoox.com/web-mercadona-es-mierda-y_mf_18309734_feed_1.mp3" title="La web de Mercadona es una mierda ¿y ahora qué? | Episodio 54">
			<span class="isplaying"></span>
			<span class="logo repúblicaweb"></span>
			<span class="podcast">República Web</span>
			<span class="track">La web de Mercadona es una mierda ¿y ahora qué? | Episodio 54</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1093">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/58fe12338c4047597443e0a9.mp3" title="El yin y el yang de Uber">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">El yin y el yang de Uber</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1094">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/5723135/Bat2x100_126.mp3" title="#126 – Especial Leo Rearte">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#126 – Especial Leo Rearte</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1095">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/04/podcast-25-introduccion-a-docker.mp3" title="Podcast #25: Introducción a Docker">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #25: Introducción a Docker</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1096">
		<a href="#" data-media="http://www.ivoox.com/7-efecto-moire-filtro-paso-bajo-y_mf_18288898_feed_1.mp3" title="#7 Efecto Moiré, filtro de paso bajo y comparaciones injustas">
			<span class="isplaying"></span>
			<span class="logo reflexpodcast"></span>
			<span class="podcast">reflex podcast</span>
			<span class="track">#7 Efecto Moiré, filtro de paso bajo y comparaciones injustas</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1097">
		<a href="#" data-media="https://ia601509.us.archive.org/6/items/046SyncthingResilioYDukto/%23046%20Syncthing%2c%20Resilio%20y%20Dukto%20.mp3" title="046. Sincronización de carpetas entre dispositivos. Syncthing, Resilio y Dukto">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">046. Sincronización de carpetas entre dispositivos. Syncthing, Resilio y Dukto</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1098">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/58f904ac8c40475974439a8b.mp3" title="¿Quieres escuchar primero la noticia mala o la peor?">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">¿Quieres escuchar primero la noticia mala o la peor?</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1099">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/5702435/Bat2x100_125.mp3" title="#125 – WorkFlow Avanzado (IV)">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#125 – WorkFlow Avanzado (IV)</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1100">
		<a href="#" data-media="http://www.ivoox.com/podcast-6-sony-a9-camara-mas-brutal_mf_18243408_feed_1.mp3" title="podcast #6 Sony A9 la cámara mas brutal y sin sentido de Sony ( audio resubido)">
			<span class="isplaying"></span>
			<span class="logo reflexpodcast"></span>
			<span class="podcast">reflex podcast</span>
			<span class="track">podcast #6 Sony A9 la cámara mas brutal y sin sentido de Sony ( audio resubido)</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1101">
		<a href="#" data-media="http://www.ivoox.com/sony-a9-la-sinsentido-sony_mf_18242421_feed_1.mp3" title="Sony A9 (La sinsentido de Sony)">
			<span class="isplaying"></span>
			<span class="logo reflexpodcast"></span>
			<span class="podcast">reflex podcast</span>
			<span class="track">Sony A9 (La sinsentido de Sony)</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1102">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/58f790638c40475974437eb4.mp3" title="Sálvanos, Evan Spiegel">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Sálvanos, Evan Spiegel</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1103">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/5697573/Bat2x100_124.mp3" title="#124 – WorkFlow Avanzado (III)">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#124 – WorkFlow Avanzado (III)</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1104">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/5696878/Bat2x100_123.mp3" title="#123 – Hazel con Eden Exposito">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#123 – Hazel con Eden Exposito</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1105">
		<a href="#" data-media="https://gitlab.com/podcastlinux/podcastlinux.gitlab.io/raw/master/Linux-Express/%2311%20Podcast%20Linux%20Express.mp3" title="#11 Linux Express">
			<span class="isplaying"></span>
			<span class="logo linuxexpressdepodcastlinux"></span>
			<span class="podcast">Linux Express, de Podcast Linux.</span>
			<span class="track">#11 Linux Express</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1106">
		<a href="#" data-media="http://feedproxy.google.com/~r/WecodesignPodcast/~5/WJwaTkHIhRo/WeCodeSign%20Mini%20-%202.mp3" title="Mini 2">
			<span class="isplaying"></span>
			<span class="logo wecodesignpodcast"></span>
			<span class="podcast">WeCodeSign Podcast</span>
			<span class="track">Mini 2</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1107">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/58f650058c4047597443645a.mp3" title="Después del recogimiento religioso">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Después del recogimiento religioso</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1108">
		<a href="#" data-media="http://traffic.libsyn.com/cesargarciasaez/LHM087.mp3" title="LHM 087 – Cómo elegir una cortadora láser para tu colegio (o makespace)">
			<span class="isplaying"></span>
			<span class="logo lahoramaker"></span>
			<span class="podcast">La Hora Maker</span>
			<span class="track">LHM 087 – Cómo elegir una cortadora láser para tu colegio (o makespace)</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1109">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/5691499/Bat2x100_122.mp3" title="#122 – WorkFlow Avanzado (II)">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#122 – WorkFlow Avanzado (II)</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1110">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/5691501/Bat2x100_121.mp3" title="#121 – WorkFlow Avanzado (I)">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#121 – WorkFlow Avanzado (I)</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1111">
		<a href="#" data-media="http://www.ivoox.com/015-productividad-mapas-mentales_mf_18193206_feed_1.mp3" title="015 - Productividad con mapas mentales">
			<span class="isplaying"></span>
			<span class="logo aprendiendogtdpodcastproductividad"></span>
			<span class="podcast">Aprendiendo GTD podcast productividad</span>
			<span class="track">015 - Productividad con mapas mentales</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1112">
		<a href="#" data-media="http://www.ivoox.com/repaso-al-libro-resilient-web-design-jeremy_mf_18190405_feed_1.mp3" title="Repaso al libro Resilient Web Design de Jeremy Keith | Episodio 53">
			<span class="isplaying"></span>
			<span class="logo repúblicaweb"></span>
			<span class="podcast">República Web</span>
			<span class="track">Repaso al libro Resilient Web Design de Jeremy Keith | Episodio 53</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1113">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/04/podcast-24-sobre-vlans.mp3" title="Podcast #24: Sobre Vlans">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #24: Sobre Vlans</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1114">
		<a href="#" data-media="http://www.ivoox.com/03x02-kirigami-interfaz-kde-para-creacion_mf_18154054_feed_1.mp3" title="03x02 Kirigami, la interfaz KDE para la creación de aplicaciones móviles">
			<span class="isplaying"></span>
			<span class="logo podcastdekdeespaña"></span>
			<span class="podcast">Podcast de KDE España</span>
			<span class="track">03x02 Kirigami, la interfaz KDE para la creación de aplicaciones móviles</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1115">
		<a href="#" data-media="http://www.ivoox.com/03x03-como-contribuir-a-tu-aplicacion-de_mf_18154028_feed_1.mp3" title="03x03 Cómo contribuir a que tu aplicación de Software Libre funcione correctamente">
			<span class="isplaying"></span>
			<span class="logo podcastdekdeespaña"></span>
			<span class="podcast">Podcast de KDE España</span>
			<span class="track">03x03 Cómo contribuir a que tu aplicación de Software Libre funcione correctamente</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1116">
		<a href="#" data-media="http://www.ivoox.com/03x01-portatiles-linux-kde-slimbook_mf_18145444_feed_1.mp3" title="03x01 Portátiles con Linux - KDE Slimbook">
			<span class="isplaying"></span>
			<span class="logo podcastdekdeespaña"></span>
			<span class="podcast">Podcast de KDE España</span>
			<span class="track">03x01 Portátiles con Linux - KDE Slimbook</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1117">
		<a href="#" data-media="http://traffic.libsyn.com/cesargarciasaez/LHM086.mp3" title="LHM 086 – Celebramos con Alex Posada el lanzamiento de los primeros Oval, instrumentos de percusión electrónicos">
			<span class="isplaying"></span>
			<span class="logo lahoramaker"></span>
			<span class="podcast">La Hora Maker</span>
			<span class="track">LHM 086 – Celebramos con Alex Posada el lanzamiento de los primeros Oval, instrumentos de percusión electrónicos</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1118">
		<a href="#" data-media="http://www.ivoox.com/22-linux-connexion-osl-la_mf_18133189_feed_1.mp3" title="#22 Linux Connexion con la OSL de la Universidad de La Laguna">
			<span class="isplaying"></span>
			<span class="logo podcastlinux"></span>
			<span class="podcast">Podcast Linux</span>
			<span class="track">#22 Linux Connexion con la OSL de la Universidad de La Laguna</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1119">
		<a href="#" data-media="https://ia801505.us.archive.org/27/items/045CrossoverConSalmorejoGeek/%23045%20Crossover%20con%20Salmorejo%20Geek.mp3" title="045. Crossover con Salmorejo Geek, donde hablamos de Mastodon, Ubuntu, Telegram y mucho mas...">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">045. Crossover con Salmorejo Geek, donde hablamos de Mastodon, Ubuntu, Telegram y mucho mas...</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1120">
		<a href="#" data-media="http://feedproxy.google.com/~r/WecodesignPodcast/~5/l7rwtRX031g/WeCodeSign%201x25%20-%20PostCSS.mp3" title="25 - PostCSS">
			<span class="isplaying"></span>
			<span class="logo wecodesignpodcast"></span>
			<span class="podcast">WeCodeSign Podcast</span>
			<span class="track">25 - PostCSS</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1121">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/58ed053694b8213d74e9d81c.mp3" title="La diversidad en Silicon Valley">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">La diversidad en Silicon Valley</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1122">
		<a href="#" data-media="http://api.spreaker.com/download/episode/11602454/podcast110.mp3" title="#110 Coches autónomos, el estado del arte con Alex Barredo">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">#110 Coches autónomos, el estado del arte con Alex Barredo</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1123">
		<a href="#" data-media="https://ia801504.us.archive.org/22/items/044WebDeJekyllEnGithub/%23044%20Web%20de%20Jekyll%20en%20Github.mp3" title="044. La web de Jekyll en GitHub, va tomando forma">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">044. La web de Jekyll en GitHub, va tomando forma</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1124">
		<a href="#" data-media="http://feedproxy.google.com/~r/Vaciatubandeja/~5/4oWZBbaGff4/04%20Como%20crear%20un%20habito%20nuevo.mp3" title="#04-Cómo crear un hábito nuevo">
			<span class="isplaying"></span>
			<span class="logo vaciatubandeja"></span>
			<span class="podcast">Vacia Tu Bandeja</span>
			<span class="track">#04-Cómo crear un hábito nuevo</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1125">
		<a href="#" data-media="http://tracking.feedpress.it/link/16349/5651011/DT4-Nuestras-Apps.mp3" title="#04 Nuestras Apps favoritas">
			<span class="isplaying"></span>
			<span class="logo droidtalks"></span>
			<span class="podcast">Droid Talks</span>
			<span class="track">#04 Nuestras Apps favoritas</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1126">
		<a href="#" data-media="http://tracking.feedpress.it/link/15407/5650768/BCS-010-Glosario-de-malware.mp3" title="BCS010 – Glosario de Malware">
			<span class="isplaying"></span>
			<span class="logo bitácoradeciberseguridad"></span>
			<span class="podcast">Bitácora de Ciberseguridad</span>
			<span class="track">BCS010 – Glosario de Malware</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1127">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/58eb0770ea27426e5c394879.mp3" title="Decir que son 'fake news' no soluciona las 'fake news'">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Decir que son 'fake news' no soluciona las 'fake news'</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1128">
		<a href="#" data-media="https://ia601509.us.archive.org/23/items/043BotDeTelegramDeIFTTT/%23043%20Bot%20de%20Telegram%20de%20IFTTT.mp3" title="043. Bot de Telegram IFTTT">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">043. Bot de Telegram IFTTT</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1129">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/316887466-ricardo-garc-a-34-episodio92.mp3" title="¿Por qué la materia tiene MASA? [Ep.92]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">¿Por qué la materia tiene MASA? [Ep.92]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1130">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/04/podcast-23-calcular-mascaras-de-red.mp3" title="Podcast #23: Calcular máscaras de red">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #23: Calcular máscaras de red</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1131">
		<a href="#" data-media="https://ia601502.us.archive.org/25/items/042ElAtareaoVisitaElCrossoverDeLaSemana/%23042%20El%20Atareao%20visita%20el%20Crossover%20de%20la%20Semana.mp3" title="042. El Atareao visita el Crossover de la Semana">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">042. El Atareao visita el Crossover de la Semana</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1132">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/58e6d96eea27426e5c38ec9f.mp3" title="El nuevo rumbo de Twitter">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">El nuevo rumbo de Twitter</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1133">
		<a href="#" data-media="https://compilando.audio/wp-content/uploads/2017/04/Podcast_3.mp3" title="Podcast 3 – Entrevista con ” el atareao” y el nuevo rumbo de Ubuntu">
			<span class="isplaying"></span>
			<span class="logo compilandopodcast"></span>
			<span class="podcast">Compilando Podcast</span>
			<span class="track">Podcast 3 – Entrevista con ” el atareao” y el nuevo rumbo de Ubuntu</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1134">
		<a href="#" data-media="https://ia801502.us.archive.org/1/items/041UbuntuYElAdiosAUnity/%23041%20Ubuntu%20y%20el%20adi%c3%b3s%20a%20Unity.mp3" title="041. Ubuntu y el adios de Unity">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">041. Ubuntu y el adios de Unity</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1135">
		<a href="#" data-media="https://ia801504.us.archive.org/29/items/40AntergosOCNewsDeNextcloudYJekyll/%2340%20Antergos%2c%20OCNews%20de%20Nextcloud%20y%20Jekyll%20.mp3" title="040. Antergos, Ocnews De Nextcloud Y Jekyll">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">040. Antergos, Ocnews De Nextcloud Y Jekyll</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1136">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/58e4ff173983178b7a176c12.mp3" title="Hard to Say I'm Sorry, Chicago feat. Tim Cook">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Hard to Say I'm Sorry, Chicago feat. Tim Cook</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1137">
		<a href="#" data-media="https://gitlab.com/podcastlinux/podcastlinux.gitlab.io/raw/master/Linux-Express/%2310%20Podcast%20Linux%20Express.mp3" title="#10 Linux Express">
			<span class="isplaying"></span>
			<span class="logo linuxexpressdepodcastlinux"></span>
			<span class="podcast">Linux Express, de Podcast Linux.</span>
			<span class="track">#10 Linux Express</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1138">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/5622479/Bat2x100_120.mp3" title="#120 – Download Station y sorpresa.(must listen)">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#120 – Download Station y sorpresa.(must listen)</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1139">
		<a href="#" data-media="http://feedproxy.google.com/~r/WecodesignPodcast/~5/6JhUuxsSEM8/WeCodeSign%20Mini%20-%201.mp3" title="Mini 1">
			<span class="isplaying"></span>
			<span class="logo wecodesignpodcast"></span>
			<span class="podcast">WeCodeSign Podcast</span>
			<span class="track">Mini 1</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1140">
		<a href="#" data-media="http://traffic.libsyn.com/cesargarciasaez/LHM085.mp3" title="LHM 085 – Descubre los proyectos seleccionados para Fab Linkage y sus primeros resultados">
			<span class="isplaying"></span>
			<span class="logo lahoramaker"></span>
			<span class="podcast">La Hora Maker</span>
			<span class="track">LHM 085 – Descubre los proyectos seleccionados para Fab Linkage y sus primeros resultados</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1141">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/58e31a343983178b7a174c49.mp3" title="El muro tecnológico de Apple">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">El muro tecnológico de Apple</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1142">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/04/podcast-22-iptables-en-gnu-linux.mp3" title="Podcast #22: NAT en GNU/Linux">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #22: NAT en GNU/Linux</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1143">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/58e2552b8aaaef4c12bd2c7c.mp3" title="Cambios de aires para Oculus y Twitter">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Cambios de aires para Oculus y Twitter</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1144">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/5609387/Bat2x100_119.mp3" title="#119 – In reply to @uGeekPodcast">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#119 – In reply to @uGeekPodcast</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1145">
		<a href="#" data-media="https://ia601508.us.archive.org/2/items/039TelegramNotes/%23039%20Telegram%2c%20Notes.mp3" title="039. Aplicación Notes de Nextcloud y crea tus bots de Telegram">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">039. Aplicación Notes de Nextcloud y crea tus bots de Telegram</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1146">
		<a href="#" data-media="https://compilando.audio/wp-content/uploads/2017/04/CompilandoPodcast2.mp3" title="Podcast 2 – Especial Servidores Privados">
			<span class="isplaying"></span>
			<span class="logo compilandopodcast"></span>
			<span class="podcast">Compilando Podcast</span>
			<span class="track">Podcast 2 – Especial Servidores Privados</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1147">
		<a href="#" data-media="https://compilando.audio/wp-content/uploads/2017/04/podcast_1.mp3" title="Podcast 1- Ian Murdock, Debian y el proyecto QSL">
			<span class="isplaying"></span>
			<span class="logo compilandopodcast"></span>
			<span class="podcast">Compilando Podcast</span>
			<span class="track">Podcast 1- Ian Murdock, Debian y el proyecto QSL</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1148">
		<a href="#" data-media="https://archive.org/download/PODCAST0_201704/PODCAST_0.mp3" title="Podcast 0 – Edición de presentación. Stallman y el síndrome Mi Pueblex.">
			<span class="isplaying"></span>
			<span class="logo compilandopodcast"></span>
			<span class="podcast">Compilando Podcast</span>
			<span class="track">Podcast 0 – Edición de presentación. Stallman y el síndrome Mi Pueblex.</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1149">
		<a href="#" data-media="https://ia601506.us.archive.org/26/items/38CrossoverConMosqueteroWeb/%23%2038%20Crossover%20con%20MosqueteroWeb.mp3" title="038. Crossover con MosqueteroWeb. Masterclass de FreeNas, Docker y virtualización mediante Proxmox y Esxi.">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">038. Crossover con MosqueteroWeb. Masterclass de FreeNas, Docker y virtualización mediante Proxmox y Esxi.</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1150">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/58dd89547846c693057437df.mp3" title="Esto no es una review del Galaxy S8">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Esto no es una review del Galaxy S8</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1151">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/5594853/Bat2x100_118.mp3" title="#118 – Podcast in itinere…">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#118 – Podcast in itinere…</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1152">
		<a href="#" data-media="http://www.ivoox.com/014-la-regla-dos-minutos_mf_17859531_feed_1.mp3" title="014 - La regla de los dos minutos">
			<span class="isplaying"></span>
			<span class="logo aprendiendogtdpodcastproductividad"></span>
			<span class="podcast">Aprendiendo GTD podcast productividad</span>
			<span class="track">014 - La regla de los dos minutos</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1153">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/5592352/Bat2x100_117.mp3" title="#117 – Podcast con uGeekPodcast hablando de Servidores NAS y Linux">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#117 – Podcast con uGeekPodcast hablando de Servidores NAS y Linux</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1154">
		<a href="#" data-media="http://traffic.libsyn.com/cesargarciasaez/LHM084.mp3" title="LHM 084 – Preguntas y proyectos con David Cuartielles – Marzo 2017">
			<span class="isplaying"></span>
			<span class="logo lahoramaker"></span>
			<span class="podcast">La Hora Maker</span>
			<span class="track">LHM 084 – Preguntas y proyectos con David Cuartielles – Marzo 2017</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1155">
		<a href="#" data-media="https://ia801503.us.archive.org/18/items/037LlamadasDeTelegram/%23037%20Llamadas%20de%20Telegram.mp3" title="037. Llamadas de Telegram ya estan aquí. Y 3 bots que os encantaran">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">037. Llamadas de Telegram ya estan aquí. Y 3 bots que os encantaran</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1156">
		<a href="#" data-media="https://ia601509.us.archive.org/25/items/036PodcastConFrank/%23036%20podcast%20con%20Frank.mp3" title="036. Podcast con Frank de Batería2x100, Servidores Linux y NAS, lo mismo pero  diferente">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">036. Podcast con Frank de Batería2x100, Servidores Linux y NAS, lo mismo pero  diferente</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1157">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/03/podcast-21-lets-encrypt.mp3" title="Podcast #21: Let’s Encrypt">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #21: Let’s Encrypt</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1158">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/58dbcbf67846c6930574047d.mp3" title="Las inversiones necesarias de Tencent">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Las inversiones necesarias de Tencent</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1159">
		<a href="#" data-media="http://www.ivoox.com/21-gnu-linux-universidad_mf_17834272_feed_1.mp3" title="#21 GNU/Linux en la Universidad">
			<span class="isplaying"></span>
			<span class="logo podcastlinux"></span>
			<span class="podcast">Podcast Linux</span>
			<span class="track">#21 GNU/Linux en la Universidad</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1160">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/03/podcast-20-como-ganar-dinero-con-el-podcast.mp3" title="Podcast #20: Cómo ganar dinero con el podcast">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #20: Cómo ganar dinero con el podcast</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1161">
		<a href="#" data-media="http://feedproxy.google.com/~r/WecodesignPodcast/~5/o2KqiN2Ltx0/WeCodeSign%201x24%20-%20CSS%20Grid%20Layout.mp3" title="24 - CSS Grid Layout">
			<span class="isplaying"></span>
			<span class="logo wecodesignpodcast"></span>
			<span class="podcast">WeCodeSign Podcast</span>
			<span class="track">24 - CSS Grid Layout</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1162">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/58da72fa5028d022439dce9f.mp3" title="En búsqueda del smartphone 'esencial'">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">En búsqueda del smartphone 'esencial'</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1163">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/5581612/Bat2x100_116.mp3" title="#116 – PushBullet/ PushOver, Workflows y Bots…">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#116 – PushBullet/ PushOver, Workflows y Bots…</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1164">
		<a href="#" data-media="http://tracking.feedpress.it/link/14730/7427252/CN_Programa_023.mp3" title="#CN023 – IoT, IFTTT y Thunderbolt 3 con Pedro Barranquero">
			<span class="isplaying"></span>
			<span class="logo culturanas"></span>
			<span class="podcast">Cultura NAS</span>
			<span class="track">#CN023 – IoT, IFTTT y Thunderbolt 3 con Pedro Barranquero</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1165">
		<a href="#" data-media="http://api.spreaker.com/download/episode/11495348/podcast109.mp3" title="#109 Cómo crear un prototipo con Arduino, el proceso paso a paso">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">#109 Cómo crear un prototipo con Arduino, el proceso paso a paso</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1166">
		<a href="#" data-media="https://ia601501.us.archive.org/10/items/035MiG8/%23035%20Mi%20G8.mp3" title="035. Mi HP ProLiant MicroServer Gen8">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">035. Mi HP ProLiant MicroServer Gen8</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1167">
		<a href="#" data-media="https://ia801500.us.archive.org/9/items/034BotDeTelegramSustitutoAShazam/%23034%20Bot%20de%20Telegram%20sustituto%20a%20Shazam.mp3" title="034. Bots de Telegram Sustitutos a Shazam y busqueda de articulos dentro del bot de Pocket">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">034. Bots de Telegram Sustitutos a Shazam y busqueda de articulos dentro del bot de Pocket</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1168">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/58d8f9075028d022439da36d.mp3" title="Yo tenía que haber nacido youtuber">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Yo tenía que haber nacido youtuber</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1169">
		<a href="#" data-media="http://feedproxy.google.com/~r/Vaciatubandeja/~5/THIxi2C7AkQ/03%20Funcionamiento%20del%20habito.mp3" title="#03-El funcionamiento del hábito">
			<span class="isplaying"></span>
			<span class="logo vaciatubandeja"></span>
			<span class="podcast">Vacia Tu Bandeja</span>
			<span class="track">#03-El funcionamiento del hábito</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1170">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/03/podcast-19-openvpn.mp3" title="Podcast #19: OpenVPN">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #19: OpenVPN</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1171">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/58d546c75028d022439d384e.mp3" title="Toma mi dinero Twitter, por favor">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Toma mi dinero Twitter, por favor</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1172">
		<a href="#" data-media="https://ia601500.us.archive.org/4/items/033BotDePocketParaTelegram/%23033%20Bot%20de%20Pocket%20para%20Telegram.mp3" title="033. Bots en Telegram. Bot de Pocket">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">033. Bots en Telegram. Bot de Pocket</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1173">
		<a href="#" data-media="https://ia601606.us.archive.org/30/items/032MiscelaneaDeViernes/%23032%20Miscel%C3%A1nea%20de%20Viernes.mp3" title="032. Miscelánea de Viernes">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">032. Miscelánea de Viernes</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1174">
		<a href="#" data-media="http://www.ivoox.com/apuesta-facebook-codigo-abierto_mf_17727865_feed_1.mp3" title="La apuesta de Facebook por el código abierto | Episodio 52">
			<span class="isplaying"></span>
			<span class="logo repúblicaweb"></span>
			<span class="podcast">República Web</span>
			<span class="track">La apuesta de Facebook por el código abierto | Episodio 52</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1175">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/58d3eacf5028d022439d0cd5.mp3" title="Navidad en Apple, sinsentidos en Medium y caos en YouTube">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Navidad en Apple, sinsentidos en Medium y caos en YouTube</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1176">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/5552178/Bat2x100_115.mp3" title="#115 – MisceláNASnea de miércoles !">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#115 – MisceláNASnea de miércoles !</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1177">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/58d298ae5028d022439cf3d1.mp3" title="iPhones rojos, ¿Android cojos?">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">iPhones rojos, ¿Android cojos?</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1178">
		<a href="#" data-media="https://ia601606.us.archive.org/14/items/031Keepass.ComoGestionoMisContrasenas/%23031%20Keepass.%20Como%20gestiono%20mis%20contrase%C3%B1as.mp3" title="031. Keepass, como gestiono mis contraseñas">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">031. Keepass, como gestiono mis contraseñas</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1179">
		<a href="#" data-media="https://gitlab.com/podcastlinux/podcastlinux.gitlab.io/raw/master/Linux-Express/%2309%20Podcast%20Linux%20Express.mp3" title="#09 Linux Express">
			<span class="isplaying"></span>
			<span class="logo linuxexpressdepodcastlinux"></span>
			<span class="podcast">Linux Express, de Podcast Linux.</span>
			<span class="track">#09 Linux Express</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1180">
		<a href="#" data-media="https://ia601609.us.archive.org/0/items/030Mumble/%23030%20Mumble.mp3" title="030. Mumble, VoIP de Software Libre. Nextcloud, Wallabag y kdenlive">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">030. Mumble, VoIP de Software Libre. Nextcloud, Wallabag y kdenlive</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1181">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/5541236/Bat2x100_114.mp3" title="#114 – Apps de IOS – Edén Exposito (II)">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#114 – Apps de IOS – Edén Exposito (II)</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1182">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/03/podcast-18-herramientas-simples-y-utiles-para-un-adminsitrador-de-red.mp3" title="Podcast #18: Herramientas simples y útiles para un adminsitrador de red">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #18: Herramientas simples y útiles para un adminsitrador de red</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1183">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/5527711/Bat2x100_113.mp3" title="#113 – VierNAS de Podcast variado…">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#113 – VierNAS de Podcast variado…</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1184">
		<a href="#" data-media="http://traffic.libsyn.com/cesargarciasaez/LHM083.mp3" title="LHM 083 – Sistemas de control de acceso para espacios maker de código abierto – CarontePass y Jarvis">
			<span class="isplaying"></span>
			<span class="logo lahoramaker"></span>
			<span class="podcast">La Hora Maker</span>
			<span class="track">LHM 083 – Sistemas de control de acceso para espacios maker de código abierto – CarontePass y Jarvis</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1185">
		<a href="#" data-media="http://www.ivoox.com/013-bullet-journal-metodo-productividad_mf_17600758_feed_1.mp3" title="013 - Bullet Journal, un método de productividad analógico">
			<span class="isplaying"></span>
			<span class="logo aprendiendogtdpodcastproductividad"></span>
			<span class="podcast">Aprendiendo GTD podcast productividad</span>
			<span class="track">013 - Bullet Journal, un método de productividad analógico</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1186">
		<a href="#" data-media="https://ia601608.us.archive.org/28/items/029MiscelneaDeViernes/%23029%20Miscel%C3%A1nea%20de%20viernes.mp3" title="029. Miscelánea de Viernes.">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">029. Miscelánea de Viernes.</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1187">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/58cab24f5028d022439c6b1c.mp3" title="La medicina correcta">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">La medicina correcta</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1188">
		<a href="#" data-media="https://ia601607.us.archive.org/17/items/ugeekpodcast_gmail_XMPP/XMPP.mp3" title="028. Instala un servidor de mensajeria tipo Whatsapp o Telegram y de Software Libre con XMPP/Jabber">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">028. Instala un servidor de mensajeria tipo Whatsapp o Telegram y de Software Libre con XMPP/Jabber</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1189">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/58c96a975028d022439c46ed.mp3" title="Cómo luchar contra el contenido falsificado">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Cómo luchar contra el contenido falsificado</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1190">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/5512078/Bat2x100_112.mp3" title="#112 – Se acabó la paciencia… “must listen”">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#112 – Se acabó la paciencia… “must listen”</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1191">
		<a href="#" data-media="http://www.ivoox.com/20-linux-connexion-david-montalva-lliurex_mf_17557164_feed_1.mp3" title="#20 Linux Connexion con David Montalva (Lliurex)">
			<span class="isplaying"></span>
			<span class="logo podcastlinux"></span>
			<span class="podcast">Podcast Linux</span>
			<span class="track">#20 Linux Connexion con David Montalva (Lliurex)</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1192">
		<a href="#" data-media="http://feedproxy.google.com/~r/WecodesignPodcast/~5/pHUCTKgl4wQ/WeCodeSign%201x23%20-%20De%20educadora%20a%20Front-end.mp3" title="23 - De educadora a Front-end">
			<span class="isplaying"></span>
			<span class="logo wecodesignpodcast"></span>
			<span class="podcast">WeCodeSign Podcast</span>
			<span class="track">23 - De educadora a Front-end</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1193">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/58c810785028d022439c1d57.mp3" title="La 'conspiración' de Nintendo">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">La 'conspiración' de Nintendo</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1194">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/5506780/Bat2x100_111.mp3" title="#111 – Ombi & Daisy Disk">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#111 – Ombi & Daisy Disk</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1195">
		<a href="#" data-media="http://traffic.libsyn.com/cesargarciasaez/LHM082.mp3" title="LHM 082 – Crowdfunding maker, qué ha pasado en estos últimos 4 años">
			<span class="isplaying"></span>
			<span class="logo lahoramaker"></span>
			<span class="podcast">La Hora Maker</span>
			<span class="track">LHM 082 – Crowdfunding maker, qué ha pasado en estos últimos 4 años</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1196">
		<a href="#" data-media="http://api.spreaker.com/download/episode/11382955/podcast108.mp3" title="#108 David Cuartielles cofundador de Arduino y del Open Hardware">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">#108 David Cuartielles cofundador de Arduino y del Open Hardware</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1197">
		<a href="#" data-media="https://ia601606.us.archive.org/3/items/027InstalaTuVpnEnUbuntuORaspberryPi/%23027%20instala%20tu%20vpn%20en%20Ubuntu%20o%20Raspberry%20Pi.mp3" title="027. Instala una VPN (OpenVpn) en Ubuntu o Raspberry Pi con PiVpn">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">027. Instala una VPN (OpenVpn) en Ubuntu o Raspberry Pi con PiVpn</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1198">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/58c6d4c55028d022439c00c5.mp3" title="El gran salto autónomo de Intel">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">El gran salto autónomo de Intel</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1199">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/312139283-ricardo-garc-a-34-episodio91.mp3" title="Trappist-1 y la búsqueda de exoplanetas [Ep91]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Trappist-1 y la búsqueda de exoplanetas [Ep91]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1200">
		<a href="#" data-media="http://tracking.feedpress.it/link/16349/5498722/DT3-Asistentes-Virtuales.mp3" title="#03 Asistentes Virtuales">
			<span class="isplaying"></span>
			<span class="logo droidtalks"></span>
			<span class="podcast">Droid Talks</span>
			<span class="track">#03 Asistentes Virtuales</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1201">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/03/podcast-17-sistemas-de-monitorizacion-de-sistemas-y-red.mp3" title="Podcast #17: Sistemas de monitorización de sistemas y red">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #17: Sistemas de monitorización de sistemas y red</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1202">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/5491860/Bat2x100_110.mp3" title="#110 – Podcast con uGeekPodcast, Hablamos de como gestionamos nuestras Fotos, actualidad y Regalo final">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#110 – Podcast con uGeekPodcast, Hablamos de como gestionamos nuestras Fotos, actualidad y Regalo final</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1203">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/03/podcast-16-directo-11-marzo-2017.mp3" title="Podcast #16: Directo 11 de Marzo 2017">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #16: Directo 11 de Marzo 2017</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1204">
		<a href="#" data-media="https://ia601606.us.archive.org/25/items/026PodcastConFrankDeBatera2x100/%23026%20Podcast%20con%20Frank%20de%20Bater%C3%ADa2x100.mp3" title="026. Podcast con Frank de Batería2x100, Hablamos de como gestionamos nuestras Fotos, actualidad y sorteo del libro del año">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">026. Podcast con Frank de Batería2x100, Hablamos de como gestionamos nuestras Fotos, actualidad y sorteo del libro del año</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1205">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/58c2cf6d5028d022439bc826.mp3" title="Lo que nos espera en las nubes">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Lo que nos espera en las nubes</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1206">
		<a href="#" data-media="http://traffic.libsyn.com/cesargarciasaez/LHM081.mp3" title="LHM 081 – Descubre los proyectos de Luis del Valle de la Tecnología para Todos">
			<span class="isplaying"></span>
			<span class="logo lahoramaker"></span>
			<span class="podcast">La Hora Maker</span>
			<span class="track">LHM 081 – Descubre los proyectos de Luis del Valle de la Tecnología para Todos</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1207">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/5481956/Bat2x100_109.mp3" title="#109 – Miscelánea Jueves Noche">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#109 – Miscelánea Jueves Noche</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1208">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/58c1963e5028d022439bb19c.mp3" title="Tormenta coreana">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Tormenta coreana</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1209">
		<a href="#" data-media="http://www.ivoox.com/competencia-a-clic-distancia_mf_17440102_feed_1.mp3" title="La competencia a un clic de distancia | Episodio 51">
			<span class="isplaying"></span>
			<span class="logo repúblicaweb"></span>
			<span class="podcast">República Web</span>
			<span class="track">La competencia a un clic de distancia | Episodio 51</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1210">
		<a href="#" data-media="http://feedproxy.google.com/~r/Vaciatubandeja/~5/aIAJtbYUCjg/02-Como%20empezar%20a%20ser%20organizado.mp3" title="#02-Cómo empezar a ser organizado">
			<span class="isplaying"></span>
			<span class="logo vaciatubandeja"></span>
			<span class="podcast">Vacia Tu Bandeja</span>
			<span class="track">#02-Cómo empezar a ser organizado</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1211">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/58c026d05028d022439b8e0d.mp3" title="Construye tu propio kit de espía">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Construye tu propio kit de espía</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1212">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/5473528/Bat2x100_108.mp3" title="#108 – Especial Seguridad III Y Sorpresa">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#108 – Especial Seguridad III Y Sorpresa</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1213">
		<a href="#" data-media="https://ia601600.us.archive.org/16/items/025MtodoMMsCompletoQueParaRecopilarNotasOrgMode/%23025%20M%C3%A9todo%20m%C3%A1s%20completo%20que%20para%20recopilar%20notas%2C%20org%20mode.mp3" title="025. Metodo mas completo para recopilar notas, org Mode">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">025. Metodo mas completo para recopilar notas, org Mode</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1214">
		<a href="#" data-media="https://gitlab.com/podcastlinux/podcastlinux.gitlab.io/raw/master/Linux-Express/%2308%20Podcast%20Linux%20Express.mp3" title="#08 Linux Express">
			<span class="isplaying"></span>
			<span class="logo linuxexpressdepodcastlinux"></span>
			<span class="podcast">Linux Express, de Podcast Linux.</span>
			<span class="track">#08 Linux Express</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1215">
		<a href="#" data-media="http://traffic.libsyn.com/cesargarciasaez/LHM080.mp3" title="LHM 080 – Homenaje a Ana Abril, fundadora de Imprimaker">
			<span class="isplaying"></span>
			<span class="logo lahoramaker"></span>
			<span class="podcast">La Hora Maker</span>
			<span class="track">LHM 080 – Homenaje a Ana Abril, fundadora de Imprimaker</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1216">
		<a href="#" data-media="http://api.spreaker.com/download/episode/11331804/s02e06_medias_en_tech_con_alba_roza_y_jaimenovoa.mp3" title="S02E06 Medias en Tech con @Alba_Roza y @jaimenovoa">
			<span class="isplaying"></span>
			<span class="logo codeontherocks"></span>
			<span class="podcast">Code on the rocks</span>
			<span class="track">S02E06 Medias en Tech con @Alba_Roza y @jaimenovoa</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1217">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/5467633/Bat2x100_107.mp3" title="#107 – Piper NV Y Alguna Cosa Más!">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#107 – Piper NV Y Alguna Cosa Más!</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1218">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/58becf53fc28f80643d71379.mp3" title="Twitch vs Twitter">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Twitch vs Twitter</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1219">
		<a href="#" data-media="https://ia601605.us.archive.org/10/items/024ConectateRemotamenteATuRaspberryPiCondataplicity/%23024%20Conectate%20remotamente%20a%20tu%20Raspberry%20Pi%20con%20%22dataplicity%22%20.mp3" title="024. Conectate remotamente a tu Raspberry Pi con 'dataplicity'">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">024. Conectate remotamente a tu Raspberry Pi con 'dataplicity'</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1220">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/58bd83b6239d394e71ba6b2f.mp3" title="La primera gran cruzada anti contenido falsificado">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">La primera gran cruzada anti contenido falsificado</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1221">
		<a href="#" data-media="http://tracking.feedpress.it/link/15407/5460185/BCS-009-Entrevista-Yolanda-Corral.mp3" title="BCS009 – Entrevista a Yolanda Corral">
			<span class="isplaying"></span>
			<span class="logo bitácoradeciberseguridad"></span>
			<span class="podcast">Bitácora de Ciberseguridad</span>
			<span class="track">BCS009 – Entrevista a Yolanda Corral</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1222">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/5458016/Bat2x100_106.mp3" title="#106 – Comentarios Sobre Mi Router Asus Ac-68U">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#106 – Comentarios Sobre Mi Router Asus Ac-68U</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1223">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/03/podcast-15-mumble.mp3" title="Podcast #15: Mumble, tu mesa de reuniones virtual">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #15: Mumble, tu mesa de reuniones virtual</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1224">
		<a href="#" data-media="http://www.ivoox.com/012-workflow-automatizaciones-ios_mf_17357158_feed_1.mp3" title="012 - Workflow - Automatizaciones en iOS">
			<span class="isplaying"></span>
			<span class="logo aprendiendogtdpodcastproductividad"></span>
			<span class="podcast">Aprendiendo GTD podcast productividad</span>
			<span class="track">012 - Workflow - Automatizaciones en iOS</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1225">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/310717344-ricardo-garc-a-34-episodio90.mp3" title="Fotografiar paisajes con estrellas + libro gratis [Ep.90]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Fotografiar paisajes con estrellas + libro gratis [Ep.90]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1226">
		<a href="#" data-media="https://ia801609.us.archive.org/20/items/EntrevistaADosDesarrolladoresDeSoftwareLibreDeIgalia/Entrevista%20a%20dos%20desarrolladores%20de%20Software%20Libre%20de%20Igalia.mp3" title="023. Entrevista a Chema y Juan, dos desarrolladores de Software Libre de Igalia.com en el #mwc17">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">023. Entrevista a Chema y Juan, dos desarrolladores de Software Libre de Igalia.com en el #mwc17</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1227">
		<a href="#" data-media="http://tracking.feedpress.it/link/14730/7427253/CN_Programa_022.mp3" title="#CN022 – El libro «Servidores NAS en tu vida digital»">
			<span class="isplaying"></span>
			<span class="logo culturanas"></span>
			<span class="podcast">Cultura NAS</span>
			<span class="track">#CN022 – El libro «Servidores NAS en tu vida digital»</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1228">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/58b83b8f239d394e71ba2917.mp3" title="Twitter lo ha hecho muy bien!">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Twitter lo ha hecho muy bien!</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1229">
		<a href="#" data-media="https://ia601600.us.archive.org/33/items/EntrevistaConArturoSuarezDirectivoDelCloudDeCanonicalUbuntu/Entrevista%20con%20Arturo%20Suarez,%20Directivo%20del%20Cloud%20de%20Canonical%20Ubuntu.mp3" title="022. Entrevista con Arturo Suarez, DIrectivo del Cloud de Canonical Ubuntu">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">022. Entrevista con Arturo Suarez, DIrectivo del Cloud de Canonical Ubuntu</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1230">
		<a href="#" data-media="http://www.ivoox.com/conquistar-libertad-ayuda-internet_mf_17304188_feed_1.mp3" title="Conquistar la libertad con la ayuda de internet, el caso del MCRC | Episodio 50">
			<span class="isplaying"></span>
			<span class="logo repúblicaweb"></span>
			<span class="podcast">República Web</span>
			<span class="track">Conquistar la libertad con la ayuda de internet, el caso del MCRC | Episodio 50</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1231">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/58b6eb84239d394e71ba0a8c.mp3" title="YouTube TV esâ€¦ Â¿mÃ¡s de lo mismo?">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">YouTube TV esâ€¦ Â¿mÃ¡s de lo mismo?</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1232">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/5437584/Bat2x100_105.mp3" title="#105 – Trucos y agradecimientos.La Impresora de Tickets">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#105 – Trucos y agradecimientos.La Impresora de Tickets</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1233">
		<a href="#" data-media="http://www.ivoox.com/19-gnu-linux-escuela_mf_17289281_feed_1.mp3" title="#19 GNU/Linux en la escuela">
			<span class="isplaying"></span>
			<span class="logo podcastlinux"></span>
			<span class="podcast">Podcast Linux</span>
			<span class="track">#19 GNU/Linux en la escuela</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1234">
		<a href="#" data-media="http://traffic.libsyn.com/cesargarciasaez/LHM079.mp3" title="LHM 079 – Respuestas sobre el futuro de La Hora Maker">
			<span class="isplaying"></span>
			<span class="logo lahoramaker"></span>
			<span class="podcast">La Hora Maker</span>
			<span class="track">LHM 079 – Respuestas sobre el futuro de La Hora Maker</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1235">
		<a href="#" data-media="http://feedproxy.google.com/~r/WecodesignPodcast/~5/PByItXwv47I/WeCodeSign%201x22%20-%20La%20importancia%20del%20disen%CC%83o%20en%20la%20web.mp3" title="22 - La importancia del diseño en la web">
			<span class="isplaying"></span>
			<span class="logo wecodesignpodcast"></span>
			<span class="podcast">WeCodeSign Podcast</span>
			<span class="track">22 - La importancia del diseño en la web</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1236">
		<a href="#" data-media="http://api.spreaker.com/download/episode/11234908/podcast107.mp3" title="#107 Aplicaciones del IoT usos prácticos en el mundo real">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">#107 Aplicaciones del IoT usos prácticos en el mundo real</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1237">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/02/podcast-14-radio-o-podcast.mp3" title="Podcast #14: Radio o Podcast, no elijas puedes tener las dos">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #14: Radio o Podcast, no elijas puedes tener las dos</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1238">
		<a href="#" data-media="https://ia801606.us.archive.org/21/items/021UbuntuEnMobileWorldCongress/%23021%20ubuntu%20en%20Mobile%20World%20Congress%20.mp3" title="021. Ubuntu en el Mobile World Congress">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">021. Ubuntu en el Mobile World Congress</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1239">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/58b422b5239d394e71b9e92e.mp3" title="Morralla World Congress">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Morralla World Congress</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1240">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/5422049/Bat2x100_104.mp3" title="#104 – Los Clásicos Básicos Con Edén Expósito.">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#104 – Los Clásicos Básicos Con Edén Expósito.</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1241">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/02/podcast-13-ospf-multiarea.mp3" title="Podcast #13: OSPF Multiárea">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #13: OSPF Multiárea</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1242">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/5411239/Bat2x100_103.mp3" title="#103 – Notas, mediaWiki, dokuWiki…una Charla De Viernes.">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#103 – Notas, mediaWiki, dokuWiki…una Charla De Viernes.</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1243">
		<a href="#" data-media="https://ia601601.us.archive.org/7/items/20PodcastConFrankDeBatera2x100HablamosDeComoGestionamosNuestraNotas/%2320%20Podcast%20con%20Frank%20de%20Bater%c3%ada2x100%2c%20Hablamos%20de%20como%20gestionamos%20nuestra%20notas%20.mp3" title="020. Podcast con Frank de Batería2x100, Hablamos de como gestionamos nuestra notas y mucho mas...">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">020. Podcast con Frank de Batería2x100, Hablamos de como gestionamos nuestra notas y mucho mas...</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1244">
		<a href="#" data-media="http://api.spreaker.com/download/episode/11085669/cap29_piratear_no_es_gratis_mejor_linux.mp3" title="cap29 - piratear no es gratis, mejor linux">
			<span class="isplaying"></span>
			<span class="logo podcastdmanuelalonso"></span>
			<span class="podcast">Podcast dmanuelalonso</span>
			<span class="track">cap29 - piratear no es gratis, mejor linux</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1245">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/58b03ad5239d394e71b9c1f2.mp3" title="Uber: la telenovela">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Uber: la telenovela</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1246">
		<a href="#" data-media="http://podcast.edyo.es/podcast/edyo-21.mp3" title="Edyo 21 - Debate sobre el incidente en Gitlab">
			<span class="isplaying"></span>
			<span class="logo entredevyopspodcast"></span>
			<span class="podcast">EntreDevYOps Podcast</span>
			<span class="track">Edyo 21 - Debate sobre el incidente en Gitlab</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1247">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/58aebfa8239d394e71b9b5cf.mp3" title="AMD pone a Intel contra las cuerdas">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">AMD pone a Intel contra las cuerdas</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1248">
		<a href="#" data-media="http://www.ivoox.com/como-identificar-a-buen-profesional-web_mf_17174416_feed_1.mp3" title="Como identificar a buen profesional de la web | Episodio 49">
			<span class="isplaying"></span>
			<span class="logo repúblicaweb"></span>
			<span class="podcast">República Web</span>
			<span class="track">Como identificar a buen profesional de la web | Episodio 49</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1249">
		<a href="#" data-media="https://ia601603.us.archive.org/6/items/019DokuwikiNuevaFormaDeTomarMisNotas/%23019%20Dokuwiki%2c%20nueva%20forma%20de%20tomar%20mis%20notas%20.mp3" title="019. Dokuwiki, nueva forma de tomar mis notas. Monta tu wiki con DokuWiki o MediaWiki.">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">019. Dokuwiki, nueva forma de tomar mis notas. Monta tu wiki con DokuWiki o MediaWiki.</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1250">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/5394883/Bat2x100_102.mp3" title="#102 – La Dimensión Desconocida…">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#102 – La Dimensión Desconocida…</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1251">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/5391684/Bat2x100_101.mp3" title="#101 – ASUS AC-68U Y Mitrastar HGU 2541 De Movistar.">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#101 – ASUS AC-68U Y Mitrastar HGU 2541 De Movistar.</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1252">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/58ad7899239d394e71b9a983.mp3" title="Los directos">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Los directos</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1253">
		<a href="#" data-media="https://gitlab.com/podcastlinux/podcastlinux.gitlab.io/raw/master/Linux-Express/%2307%20Podcast%20Linux%20Express.mp3" title="#07 Linux Express">
			<span class="isplaying"></span>
			<span class="logo linuxexpressdepodcastlinux"></span>
			<span class="podcast">Linux Express, de Podcast Linux.</span>
			<span class="track">#07 Linux Express</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1254">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/58abe90f7820e1a268b3c0a8.mp3" title="WhatsApp ha cambiado para siempre">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">WhatsApp ha cambiado para siempre</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1255">
		<a href="#" data-media="https://ia601604.us.archive.org/24/items/018WallabagElPocketOInstapaper/%23018_Wallabag%2c_el_Pocket_o_Instapaper.mp3" title="018. Como montar Wallabag, el Pocket o Instapaper de software libre y lo mejor de todo, en tu servidor">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">018. Como montar Wallabag, el Pocket o Instapaper de software libre y lo mejor de todo, en tu servidor</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1256">
		<a href="#" data-media="http://feedproxy.google.com/~r/Vaciatubandeja/~5/HnGBGpZGsKs/Vtb01_Se_analogico_en_un_mundo_digital_con_Bullet_Journal.mp3" title="#01-Organízate con Bullet Journal">
			<span class="isplaying"></span>
			<span class="logo vaciatubandeja"></span>
			<span class="podcast">Vacia Tu Bandeja</span>
			<span class="track">#01-Organízate con Bullet Journal</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1257">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/5365429/Bat2x100_100.mp3" title="#100 – Homenaje a…Seguridad IOS (2) Y Docker">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#100 – Homenaje a…Seguridad IOS (2) Y Docker</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1258">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/58aae94f7820e1a268b3b3e4.mp3" title="La cultura interna de Uber sigue siendo rancia">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">La cultura interna de Uber sigue siendo rancia</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1259">
		<a href="#" data-media="http://tracking.feedpress.it/link/16349/5359024/DT-02-El-futuro.mp3" title="#02 El futuro ya está aquí">
			<span class="isplaying"></span>
			<span class="logo droidtalks"></span>
			<span class="podcast">Droid Talks</span>
			<span class="track">#02 El futuro ya está aquí</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1260">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/5340600/Bat2x100_99.mp3" title="#99 – Podcast Con Angel De uGeekPodcast Hablando De Plex, Nextcloud">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#99 – Podcast Con Angel De uGeekPodcast Hablando De Plex, Nextcloud</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1261">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/02/podcast-12-atencion-al-cliente-y-migrar-una-web.mp3" title="Podcast #12: Atención al cliente y migrar una web">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #12: Atención al cliente y migrar una web</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1262">
		<a href="#" data-media="https://ia801300.us.archive.org/34/items/017PodcastConFrankDeBateria2x100HablandoDePlexNextcloud.../%23017%20Podcast%20con%20Frank%20de%20Bateria2x100%2c%20hablando%20de%20Plex%2c%20Nextcloud....mp3" title="017. Podcast con Frank de Bateria2x100, hablando de Plex, Nextcloud...">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">017. Podcast con Frank de Bateria2x100, hablando de Plex, Nextcloud...</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1263">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/5332154/Bat2x100_98.mp3" title="#98 – Homenaje a … Especial Seguridad (I)">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#98 – Homenaje a … Especial Seguridad (I)</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1264">
		<a href="#" data-media="https://ia801603.us.archive.org/24/items/016QueEsUnServidor/%23016%20Que%20es%20un%20servidor.mp3" title="016. Que es un Servidor (dudas oyentes), servidor web, ...">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">016. Que es un Servidor (dudas oyentes), servidor web, ...</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1265">
		<a href="#" data-media="http://www.ivoox.com/lo-supone-ser-buen-ciudadano-de_mf_17043958_feed_1.mp3" title="Lo que supone ser un buen ciudadano de internet | Episodio 48">
			<span class="isplaying"></span>
			<span class="logo repúblicaweb"></span>
			<span class="podcast">República Web</span>
			<span class="track">Lo que supone ser un buen ciudadano de internet | Episodio 48</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1266">
		<a href="#" data-media="https://ia801603.us.archive.org/20/items/015AlmacenamientoTheNextcloud/%23015_almacenamiento_the_nextcloud.mp3" title="015. Como ampliar el almacenamiento de Nextcloud, combinar con nubes publicas y hacer copias de mis fotos.">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">015. Como ampliar el almacenamiento de Nextcloud, combinar con nubes publicas y hacer copias de mis fotos.</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1267">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/5318680/Bat2x100_97.mp3" title="#97 – Homenaje A… (1/3)">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#97 – Homenaje A… (1/3)</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1268">
		<a href="#" data-media="https://ia601602.us.archive.org/11/items/NotasEnNextcloud/Notas%20en%20nextcloud.mp3" title="014. Notas en Nextcloud y Markdown">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">014. Notas en Nextcloud y Markdown</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1269">
		<a href="#" data-media="http://feedproxy.google.com/~r/WecodesignPodcast/~5/XjyQucVe-W4/WeCodeSign%201x21%20-%20El%20presente%20y%20futuro%20del%20UX.mp3" title="21 - El presente y futuro del UX">
			<span class="isplaying"></span>
			<span class="logo wecodesignpodcast"></span>
			<span class="podcast">WeCodeSign Podcast</span>
			<span class="track">21 - El presente y futuro del UX</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1270">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/5315184/Bat2x100_96.mp3" title="#96 – Audio Whatsapp a Mp3.">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#96 – Audio Whatsapp a Mp3.</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1271">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/58a2e7954bb9e7460537dcf4.mp3" title="¿Cargadores? A donde vamos no necesitamos cargadores">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">¿Cargadores? A donde vamos no necesitamos cargadores</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1272">
		<a href="#" data-media="http://api.spreaker.com/download/episode/10772602/podcast106.mp3" title="#106 BricoGeek, la tienda Maker de Frikis para Frikis">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">#106 BricoGeek, la tienda Maker de Frikis para Frikis</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1273">
		<a href="#" data-media="https://ia801601.us.archive.org/21/items/013NewsYFreshRSS.GestorDeNoticiasRSS/%23013%20News%20y%20Fresh%20RSS.%20Gestor%20de%20Noticias%20RSS.mp3" title="013. News y FreshRSS. Gestor de Noticias RSS.">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">013. News y FreshRSS. Gestor de Noticias RSS.</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1274">
		<a href="#" data-media="https://ia801604.us.archive.org/21/items/013FDroidAplicacionesDeSoftwareLibre/%23013%20F-Droid%20Aplicaciones%20de%20Software%20Libre.mp3" title="013. bis F-Droid Tienda Android de aplicaciones de Software Libre y Actualizar las Noticias en Nextcloud.">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">013. bis F-Droid Tienda Android de aplicaciones de Software Libre y Actualizar las Noticias en Nextcloud.</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1275">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/58a159461c19b23f0a752485.mp3" title="Todo es vídeo ahora o qué">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Todo es vídeo ahora o qué</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1276">
		<a href="#" data-media="https://ia801601.us.archive.org/24/items/012CmoActualizarNextcloudY/%23012_c%c3%b3mo_actualizar_Nextcloud_y.mp3" title="012. Como actualizar Nextcloud y salir del modo de 'mantenimiento'">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">012. Como actualizar Nextcloud y salir del modo de 'mantenimiento'</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1277">
		<a href="#" data-media="http://tracking.feedpress.it/link/14730/7427254/CN_Programa_021.mp3" title="#CN021 – Los 1001 usos de un NAS by @patuflinx">
			<span class="isplaying"></span>
			<span class="logo culturanas"></span>
			<span class="podcast">Cultura NAS</span>
			<span class="track">#CN021 – Los 1001 usos de un NAS by @patuflinx</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1278">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/307212164-ricardo-garc-a-34-galaxias-inusuales-y-la-quimica-del-espacio-interestelar-ep89.mp3" title="Galaxias inusuales y la química del espacio interestelar [Ep.89]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Galaxias inusuales y la química del espacio interestelar [Ep.89]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1279">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/02/podcast-11-ospf-en-un-area.mp3" title="Podcast #11: OSPF en un único área">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #11: OSPF en un único área</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1280">
		<a href="#" data-media="https://ia801602.us.archive.org/16/items/011PodcastConFrankDeBateria2x100/%23011%20Podcast%20con%20Frank%20de%20Bateria2x100.mp3" title="011. Podcast con Frank de Bateria2x100, hablando un poco de todo...">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">011. Podcast con Frank de Bateria2x100, hablando un poco de todo...</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1281">
		<a href="#" data-media="http://www.ivoox.com/reinvencion-instagram-es-copiar-bien_mf_16943611_feed_1.mp3" title="La reinvención de Instagram es copiar bien | Episodio 47">
			<span class="isplaying"></span>
			<span class="logo repúblicaweb"></span>
			<span class="podcast">República Web</span>
			<span class="track">La reinvención de Instagram es copiar bien | Episodio 47</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1282">
		<a href="#" data-media="https://ia601603.us.archive.org/9/items/010ElSistemaOperativoDeBolsillo/%23010%20El%20Sistema%20Operativo%20de%20bolsillo.mp3" title="010. CloudReady el Chromium OS de bolsillo">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">010. CloudReady el Chromium OS de bolsillo</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1283">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/5291600/Bat2x100_95.mp3" title="#95 – Apunte DS Note">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#95 – Apunte DS Note</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1284">
		<a href="#" data-media="http://www.ivoox.com/011-tecnicas-productividad-pomodoro-mapas_mf_16923506_feed_1.mp3" title="011 - Técnicas de productividad: Pomodoro + Mapas mentales">
			<span class="isplaying"></span>
			<span class="logo aprendiendogtdpodcastproductividad"></span>
			<span class="podcast">Aprendiendo GTD podcast productividad</span>
			<span class="track">011 - Técnicas de productividad: Pomodoro + Mapas mentales</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1285">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/5290201/Bat2x100_94.mp3" title="#94 – DS NOTE, espectacular.">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#94 – DS NOTE, espectacular.</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1286">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/589bebf1f7f6f2e82daf0663.mp3" title="Android Wear 2: Electric Boogaloo">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Android Wear 2: Electric Boogaloo</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1287">
		<a href="#" data-media="https://ia601602.us.archive.org/11/items/ComoCrearTuPodcastYTotalmenteGtatis/Como%20crear%20tu%20podcast%20y%20totalmente%20gtatis.mp3" title="009. Crea tu podcast en 3 simples pasos y totalmente gratis">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">009. Crea tu podcast en 3 simples pasos y totalmente gratis</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1288">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/5281613/Bat2x100_93.mp3" title="#93 – Life360,Piper Y #SaferInternetDay">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#93 – Life360,Piper Y #SaferInternetDay</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1289">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/5278089/Bat2x100_92.mp3" title="#92 – Miscelánea De Miércoles">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#92 – Miscelánea De Miércoles</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1290">
		<a href="#" data-media="https://ia801900.us.archive.org/13/items/008ComoGestionoMisNotas/%23008%20Como%20gestiono%20mis%20notas.mp3" title="008. Como gestiono mis Notas">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">008. Como gestiono mis Notas</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1291">
		<a href="#" data-media="https://gitlab.com/podcastlinux/podcastlinux.gitlab.io/raw/master/Linux-Express/%2306%20Podcast%20Linux%20Express.mp3" title="#06 Linux Express">
			<span class="isplaying"></span>
			<span class="logo linuxexpressdepodcastlinux"></span>
			<span class="podcast">Linux Express, de Podcast Linux.</span>
			<span class="track">#06 Linux Express</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1292">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/58999f10f7f6f2e82daefd7e.mp3" title="El despegue de los VTOL">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">El despegue de los VTOL</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1293">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/5272972/Bat2x100_91.mp3" title="#91 – Charla con @angel_bcn, podcaster de uGeek">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#91 – Charla con @angel_bcn, podcaster de uGeek</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1294">
		<a href="#" data-media="hhttps://ia601902.us.archive.org/28/items/007LinuxEsUnaAlternativaReal/%23007%20Linux%20es%20una%20alternativa%20real.mp3" title="007. Linux es una alternativa real">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">007. Linux es una alternativa real</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1295">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/5897e41af7f6f2e82daef58f.mp3" title="¿Qué está pasando con el Apple Watch?">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">¿Qué está pasando con el Apple Watch?</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1296">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/5266091/Bat2x100_90.mp3" title="#90 – Prueba De Feed">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#90 – Prueba De Feed</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1297">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/5266093/Bat2x100_89.mp3" title="#89 – Ransomware & Dropbox">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#89 – Ransomware & Dropbox</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1298">
		<a href="#" data-media="https://ia601900.us.archive.org/18/items/ElTrelloDeSoftwareLibreWekan/El_Trello_de_software_libre_Wekan.mp3" title="006. El Trello de Software Libre Wekan y Kanboard para Raspberry Pi. El sistema Kanban en tu servidor.">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">006. El Trello de Software Libre Wekan y Kanboard para Raspberry Pi. El sistema Kanban en tu servidor.</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1299">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/5259020/Bat2x100_88.mp3" title="#88 – RCLONE & MULTCLOUD.">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#88 – RCLONE & MULTCLOUD.</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1300">
		<a href="#" data-media="http://www.ivoox.com/burbuja-wordpress-episodio-46_mf_16816098_feed_1.mp3" title="La burbuja de WordPress | Episodio 46">
			<span class="isplaying"></span>
			<span class="logo repúblicaweb"></span>
			<span class="podcast">República Web</span>
			<span class="track">La burbuja de WordPress | Episodio 46</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1301">
		<a href="#" data-media="http://tracking.feedpress.it/link/15407/5256088/BCS-008-Asegurando-el-router-Primeros-pasos.mp3" title="BCS008 – Asegurando el router, primeros pasos">
			<span class="isplaying"></span>
			<span class="logo bitácoradeciberseguridad"></span>
			<span class="podcast">Bitácora de Ciberseguridad</span>
			<span class="track">BCS008 – Asegurando el router, primeros pasos</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1302">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/589440cef7f6f2e82daee51f.mp3" title="Todos los hombres del presidente">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Todos los hombres del presidente</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1303">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/5254374/Bat2x100_87.mp3" title="#87 – Siempre Estuvo Allí Y Yo Sin Saberlo (DS NOTE)">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#87 – Siempre Estuvo Allí Y Yo Sin Saberlo (DS NOTE)</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1304">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/02/podcast-10-dns-y-arp.mp3" title="Podcast #10: Cómo funciona el DNS">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #10: Cómo funciona el DNS</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1305">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/5892dac4f7f6f2e82daedd0d.mp3" title="Facebook se baña en dinero">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Facebook se baña en dinero</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1306">
		<a href="#" data-media="https://ia601603.us.archive.org/9/items/005PaperDeDropbox/%23005%20Paper%20de%20Dropbox.mp3" title="005. Paper de Dropbox">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">005. Paper de Dropbox</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1307">
		<a href="#" data-media="http://api.spreaker.com/download/episode/10458114/cap28_smtube_youtube_en_linux.mp3" title="cap28 - SMTUBE -  Youtube en linux">
			<span class="isplaying"></span>
			<span class="logo podcastdmanuelalonso"></span>
			<span class="podcast">Podcast dmanuelalonso</span>
			<span class="track">cap28 - SMTUBE -  Youtube en linux</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1308">
		<a href="#" data-media="http://www.ivoox.com/17-linux-connexion-alexandre-filgueira_mf_16768269_feed_1.mp3" title="#17 Linux Connexion con Alexandre Filgueira">
			<span class="isplaying"></span>
			<span class="logo podcastlinux"></span>
			<span class="podcast">Podcast Linux</span>
			<span class="track">#17 Linux Connexion con Alexandre Filgueira</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1309">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/58916369f7f6f2e82daed2f9.mp3" title="Las dos Apple">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Las dos Apple</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1310">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/01/podcast-9-streaming-con-icecat2-mp3.mp3" title="Podcast #9: Streaming con Icecast 2">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #9: Streaming con Icecast 2</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1311">
		<a href="#" data-media="https://ia601903.us.archive.org/19/items/004ServidorLinuxVsQNapSynology/%23004%20Servidor%20Linux%20Vs%20QNap-Synology.mp3" title="004. Servidor Linux Vs QNAP-Synology">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">004. Servidor Linux Vs QNAP-Synology</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1312">
		<a href="#" data-media="http://feedproxy.google.com/~r/WecodesignPodcast/~5/JlCzC-TQ6wE/WeCodeSign%201x20%20-%20La%20importancia%20del%20Open%20Source.mp3" title="20 - La importancia del Open Source">
			<span class="isplaying"></span>
			<span class="logo wecodesignpodcast"></span>
			<span class="podcast">WeCodeSign Podcast</span>
			<span class="track">20 - La importancia del Open Source</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1313">
		<a href="#" data-media="http://api.spreaker.com/download/episode/10446110/podcast105.mp3" title="#105 Guía cómo configurar un ESP01, el módulo WiFi basado en ESP8266">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">#105 Guía cómo configurar un ESP01, el módulo WiFi basado en ESP8266</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1314">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/588fff4cf7f6f2e82daecd3d.mp3" title="Snapchat mal y Fitbit peor">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Snapchat mal y Fitbit peor</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1315">
		<a href="#" data-media="https://ia601903.us.archive.org/4/items/003Nextcloud/%23003%20Nextcloud.mp3" title="003. Nextcloud. Instalar tu Nube en menos de 2 minutos.">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">003. Nextcloud. Instalar tu Nube en menos de 2 minutos.</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1316">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/305269395-ricardo-garc-a-34-episodio88.mp3" title="Megaproyectos de Radioastronomía, un desafío tecnológico [Ep.88]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Megaproyectos de Radioastronomía, un desafío tecnológico [Ep.88]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1317">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/5234570/Bat2x100_86.mp3" title="#86 – No Somos Usuarios Corrientes">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#86 – No Somos Usuarios Corrientes</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1318">
		<a href="#" data-media="http://www.ivoox.com/retroactivo-podcast-62-nintendo-64_mf_16715022_feed_1.mp3" title="RetroActivo Podcast #62: Nintendo 64">
			<span class="isplaying"></span>
			<span class="logo retroactivopodcast"></span>
			<span class="podcast">RetroActivo Podcast</span>
			<span class="track">RetroActivo Podcast #62: Nintendo 64</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1319">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/588eff71f7f6f2e82daec415.mp3" title="Qué bien se vive en Silicon Valley">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Qué bien se vive en Silicon Valley</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1320">
		<a href="#" data-media="https://ia801904.us.archive.org/20/items/DeQueVaEstoDeUGeek/De%20que%20va%20esto%20de%20uGeek%3f.mp3" title="002. 'De qué va esto de uGeek?'">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">002. 'De qué va esto de uGeek?'</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1321">
		<a href="#" data-media="http://www.ivoox.com/mantenerse-al-dia-profesionalmente-tecnologia_mf_16700113_feed_1.mp3" title="Mantenerse al día profesionalmente con la tecnología | Episodio 45">
			<span class="isplaying"></span>
			<span class="logo repúblicaweb"></span>
			<span class="podcast">República Web</span>
			<span class="track">Mantenerse al día profesionalmente con la tecnología | Episodio 45</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1322">
		<a href="#" data-media="http://api.spreaker.com/download/episode/10393938/cap27_linux_en_casa.mp3" title="cap27 - Linux en casa">
			<span class="isplaying"></span>
			<span class="logo podcastdmanuelalonso"></span>
			<span class="podcast">Podcast dmanuelalonso</span>
			<span class="track">cap27 - Linux en casa</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1323">
		<a href="#" data-media="https://ia801602.us.archive.org/21/items/HolaMundo_201701/Hola%20Mundo.mp3" title="001. Hola Mundo">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">001. Hola Mundo</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1324">
		<a href="#" data-media="http://tracking.feedpress.it/link/14730/7427255/CN_Programa_Sorteo.mp3" title="Llamada telefónica">
			<span class="isplaying"></span>
			<span class="logo culturanas"></span>
			<span class="podcast">Cultura NAS</span>
			<span class="track">Llamada telefónica</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1325">
		<a href="#" data-media="https://gitlab.com/podcastlinux/podcastlinux.gitlab.io/raw/master/Linux-Express/%2305%20Podcast%20Linux%20Express.mp3" title="#05 Linux Express">
			<span class="isplaying"></span>
			<span class="logo linuxexpressdepodcastlinux"></span>
			<span class="podcast">Linux Express, de Podcast Linux.</span>
			<span class="track">#05 Linux Express</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1326">
		<a href="#" data-media="http://www.ivoox.com/guia-para-analizar-sitio-web-15_mf_16617887_feed_1.mp3" title="Guía para analizar un sitio web en 15 minutos | Episodio 44">
			<span class="isplaying"></span>
			<span class="logo repúblicaweb"></span>
			<span class="podcast">República Web</span>
			<span class="track">Guía para analizar un sitio web en 15 minutos | Episodio 44</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1327">
		<a href="#" data-media="http://tracking.feedpress.it/link/16349/5197671/DT-_01_Netiqueta.mp3" title="#01 Netiqueta">
			<span class="isplaying"></span>
			<span class="logo droidtalks"></span>
			<span class="podcast">Droid Talks</span>
			<span class="track">#01 Netiqueta</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1328">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/5194885/Bat2x100_85.mp3" title="#85 – Un Capítulo Muy Muy Interesante.">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#85 – Un Capítulo Muy Muy Interesante.</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1329">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/5186279/Bat2x100_84.mp3" title="#84 – Así Me Gestiono Yo & Menubar Stats 2">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#84 – Así Me Gestiono Yo & Menubar Stats 2</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1330">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/303900849-ricardo-garc-a-34-episodio87.mp3" title="El misterio de la masa del neutrino [Ep.87]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">El misterio de la masa del neutrino [Ep.87]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1331">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/01/podcast-8-el-viaje-de-cargar-una-web.mp3" title="Podcast #8: El viaje de cargar una web">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #8: El viaje de cargar una web</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1332">
		<a href="#" data-media="http://tracking.feedpress.it/link/14730/7427256/CN_Programa_020.mp3" title="#CN020 – Cómo mejorar la velocidad de transferencia del NAS en tu red LAN">
			<span class="isplaying"></span>
			<span class="logo culturanas"></span>
			<span class="podcast">Cultura NAS</span>
			<span class="track">#CN020 – Cómo mejorar la velocidad de transferencia del NAS en tu red LAN</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1333">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/5167120/Bat2x100_83.mp3" title="#83 – Variado De Miércoles">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#83 – Variado De Miércoles</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1334">
		<a href="#" data-media="http://www.ivoox.com/16-antergos_mf_16451726_feed_1.mp3" title="#16 Antergos">
			<span class="isplaying"></span>
			<span class="logo podcastlinux"></span>
			<span class="podcast">Podcast Linux</span>
			<span class="track">#16 Antergos</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1335">
		<a href="#" data-media="http://feedproxy.google.com/~r/WecodesignPodcast/~5/EVhOE1OUy_U/WeCodeSign%201x19%20-%20Reclutando%20Talento.mp3" title="19 - Reclutando Talento">
			<span class="isplaying"></span>
			<span class="logo wecodesignpodcast"></span>
			<span class="podcast">WeCodeSign Podcast</span>
			<span class="track">19 - Reclutando Talento</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1336">
		<a href="#" data-media="http://api.spreaker.com/download/episode/10323357/podcast104.mp3" title="#104 Electrónica para todos con RincónIngenieril">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">#104 Electrónica para todos con RincónIngenieril</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1337">
		<a href="#" data-media="http://www.ivoox.com/trump-twitter-extrana-pareja-episodio_mf_16373040_feed_1.mp3" title="Trump y Twitter, una extraña pareja | Episodio 43">
			<span class="isplaying"></span>
			<span class="logo repúblicaweb"></span>
			<span class="podcast">República Web</span>
			<span class="track">Trump y Twitter, una extraña pareja | Episodio 43</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1338">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/587c45c9f7f6f2e82dae86b7.mp3" title="Semana judicial de alto riesgo para Samsung y Facebook">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Semana judicial de alto riesgo para Samsung y Facebook</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1339">
		<a href="#" data-media="https://gitlab.com/uGeek/podcasts/raw/master/audios/085-nextcloud-talks.m4a" title="085. Nextcloud Talk y Script para Instalar Nextcloud">
			<span class="isplaying"></span>
			<span class="logo ugeektecnologíaandroidlinuxservidoresymuchomás"></span>
			<span class="podcast">uGeek - Tecnología, Android, Linux, Servidores y mucho más...</span>
			<span class="track">085. Nextcloud Talk y Script para Instalar Nextcloud</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1340">
		<a href="#" data-media="http://www.ivoox.com/02x07-flatpak-snappy_mf_16315062_feed_1.mp3" title="02x07 Flatpak y Snappy">
			<span class="isplaying"></span>
			<span class="logo podcastdekdeespaña"></span>
			<span class="podcast">Podcast de KDE España</span>
			<span class="track">02x07 Flatpak y Snappy</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1341">
		<a href="#" data-media="http://www.ivoox.com/02x06-presente-futuro-plasma-5_mf_16313378_feed_1.mp3" title="02x06 Presente y futuro de Plasma 5">
			<span class="isplaying"></span>
			<span class="logo podcastdekdeespaña"></span>
			<span class="podcast">Podcast de KDE España</span>
			<span class="track">02x06 Presente y futuro de Plasma 5</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1342">
		<a href="#" data-media="http://www.ivoox.com/02x05-20-anos-kde_mf_16312432_feed_1.mp3" title="02x05 20 años de KDE">
			<span class="isplaying"></span>
			<span class="logo podcastdekdeespaña"></span>
			<span class="podcast">Podcast de KDE España</span>
			<span class="track">02x05 20 años de KDE</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1343">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/5143176/Bat2x100_82.mp3" title="#82 – Amerigo(App IOS) Y Wallabag Por Fin Ok!">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#82 – Amerigo(App IOS) Y Wallabag Por Fin Ok!</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1344">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/302741478-ricardo-garc-a-34-episodio86.mp3" title="Cómo hacer turismo astronómico y científico en Chile [Ep.86]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Cómo hacer turismo astronómico y científico en Chile [Ep.86]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1345">
		<a href="#" data-media="https://gitlab.com/podcastlinux/podcastlinux.gitlab.io/raw/master/Linux-Express/%2304%20Podcast%20Linux%20Express.mp3" title="#04 Linux Express">
			<span class="isplaying"></span>
			<span class="logo linuxexpressdepodcastlinux"></span>
			<span class="podcast">Linux Express, de Podcast Linux.</span>
			<span class="track">#04 Linux Express</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1346">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/58770232f7f6f2e82dae730b.mp3" title="Fitbit se asoma al abismo">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Fitbit se asoma al abismo</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1347">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/5122681/Bat2x100_81.mp3" title="#81 – Otro Podcast Nocturno.">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#81 – Otro Podcast Nocturno.</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1348">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/5876602bf7f6f2e82dae6ec1.mp3" title="Los ingenieros más brillantes quieren cambiar el mundo">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Los ingenieros más brillantes quieren cambiar el mundo</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1349">
		<a href="#" data-media="http://www.ivoox.com/jovenes-necesidad-aprender-a_mf_16071709_feed_1.mp3" title="Los jóvenes y la necesidad de aprender a programar | Episodio 42">
			<span class="isplaying"></span>
			<span class="logo repúblicaweb"></span>
			<span class="podcast">República Web</span>
			<span class="track">Los jóvenes y la necesidad de aprender a programar | Episodio 42</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1350">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/587489dcf7f6f2e82dae64c5.mp3" title="â€˜cuales son las noticias mÃ¡s relevantes de hoy altaba respuestasâ€™">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">â€˜cuales son las noticias mÃ¡s relevantes de hoy altaba respuestasâ€™</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1351">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2017/01/podcast-7-cableado.mp3" title="Podcast #7: Cableado en un Centro de Datos">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #7: Cableado en un Centro de Datos</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1352">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/301404910-ricardo-garc-a-34-episodio85.mp3" title="Binarias de Rayos X, viajar a un agujero negro, supernovas y pulsares [Ep.85]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Binarias de Rayos X, viajar a un agujero negro, supernovas y pulsares [Ep.85]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1353">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/5097843/Bat2x100_80.mp3" title="#80 – Podcast Verpertino.3 Reflexiones Post Navideñas">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#80 – Podcast Verpertino.3 Reflexiones Post Navideñas</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1354">
		<a href="#" data-media="http://www.ivoox.com/15-linux-connexion-jen0f0nte_mf_15880251_feed_1.mp3" title="#15 Linux Connexion con Jen0f0nte">
			<span class="isplaying"></span>
			<span class="logo podcastlinux"></span>
			<span class="podcast">Podcast Linux</span>
			<span class="track">#15 Linux Connexion con Jen0f0nte</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1355">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/5084487/Bat2x100_79.mp3" title="#79 – Variado De Reyes !">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#79 – Variado De Reyes !</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1356">
		<a href="#" data-media="http://tracking.feedpress.it/link/15407/5080157/BCS-007-Hacks-2016.mp3" title="BCS007 – Hacks de 2016">
			<span class="isplaying"></span>
			<span class="logo bitácoradeciberseguridad"></span>
			<span class="podcast">Bitácora de Ciberseguridad</span>
			<span class="track">BCS007 – Hacks de 2016</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1357">
		<a href="#" data-media="http://feedproxy.google.com/~r/WecodesignPodcast/~5/c1fGTm5or_E/WeCodeSign%201x18%20-%20Metodologias%20de%20Trabajo.mp3" title="18 - Metodologías de Trabajo">
			<span class="isplaying"></span>
			<span class="logo wecodesignpodcast"></span>
			<span class="podcast">WeCodeSign Podcast</span>
			<span class="track">18 - Metodologías de Trabajo</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1358">
		<a href="#" data-media="http://www.ivoox.com/como-conseguir-google-te-contrate-episodio_mf_15743773_feed_1.mp3" title="Como conseguir que Google te contrate - Episodio 41">
			<span class="isplaying"></span>
			<span class="logo repúblicaweb"></span>
			<span class="podcast">República Web</span>
			<span class="track">Como conseguir que Google te contrate - Episodio 41</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1359">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/586b27bc48f89f4719955eac.mp3" title="Cuidado que viene el CES 2017">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Cuidado que viene el CES 2017</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1360">
		<a href="#" data-media="http://api.spreaker.com/download/episode/10226310/cap26_miui_semanal_o_estable.mp3" title="cap26 - Xiaomi: MIUI Semanal o Estable">
			<span class="isplaying"></span>
			<span class="logo podcastdmanuelalonso"></span>
			<span class="podcast">Podcast dmanuelalonso</span>
			<span class="track">cap26 - Xiaomi: MIUI Semanal o Estable</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1361">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/5067810/Bat2x100_78.mp3" title="#78 – +Wallabag Y Piper NV">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#78 – +Wallabag Y Piper NV</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1362">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/5064109/Bat2x100_77.mp3" title="#77 – Feliz 2017  ! Resilio Y Wallabag Y Alguna Cosa Más.">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#77 – Feliz 2017  ! Resilio Y Wallabag Y Alguna Cosa Más.</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1363">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2016/12/podcast-6-almacenamiento.mp3" title="Podcast #6: Almacenamiento">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #6: Almacenamiento</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1364">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/300376184-ricardo-garc-a-34-episodio84.mp3" title="Ondas Gravitacionales, Próxima B, Marte, SuperLuna y más. Resumen científico 2016 [Ep.84]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Ondas Gravitacionales, Próxima B, Marte, SuperLuna y más. Resumen científico 2016 [Ep.84]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1365">
		<a href="#" data-media="https://gitlab.com/podcastlinux/podcastlinux.gitlab.io/raw/master/Linux-Express/%2303%20Podcast%20Linux%20Express.mp3" title="#03 Linux Express">
			<span class="isplaying"></span>
			<span class="logo linuxexpressdepodcastlinux"></span>
			<span class="podcast">Linux Express, de Podcast Linux.</span>
			<span class="track">#03 Linux Express</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1366">
		<a href="#" data-media="http://api.spreaker.com/download/episode/10197320/s02e05_especial_navidad_invitamos_a_papa_noel.mp3" title="S02E05 Especial Navidad - Invitamos a Papa Noel!">
			<span class="isplaying"></span>
			<span class="logo codeontherocks"></span>
			<span class="podcast">Code on the rocks</span>
			<span class="track">S02E05 Especial Navidad - Invitamos a Papa Noel!</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1367">
		<a href="#" data-media="http://www.ivoox.com/amazon-alexa-inteligencia-artificial-auge-de_mf_15470896_feed_1.mp3" title="Amazon Alexa, inteligencia artificial y el auge de la voz como interfaz | Episodio 40">
			<span class="isplaying"></span>
			<span class="logo repúblicaweb"></span>
			<span class="podcast">República Web</span>
			<span class="track">Amazon Alexa, inteligencia artificial y el auge de la voz como interfaz | Episodio 40</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1368">
		<a href="#" data-media="http://api.spreaker.com/download/episode/10187746/podcast103.mp3" title="#103. Cultura Maker e IoT con Cesar García de La Hora Maker">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">#103. Cultura Maker e IoT con Cesar García de La Hora Maker</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1369">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/5029972/Bat2x100_76.mp3" title="#76 – 25 Dciembre !">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#76 – 25 Dciembre !</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1370">
		<a href="#" data-media="http://www.ivoox.com/14-especial-slimbook-katana_mf_15380402_feed_1.mp3" title="#14 Especial Slimbook Katana">
			<span class="isplaying"></span>
			<span class="logo podcastlinux"></span>
			<span class="podcast">Podcast Linux</span>
			<span class="track">#14 Especial Slimbook Katana</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1371">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/299383074-ricardo-garc-a-34-episodio83.mp3" title="¿Qué ocurrió antes del Big Bang? Cuerdas, agujeros negros y múltiples dimensiones [Ep.83]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">¿Qué ocurrió antes del Big Bang? Cuerdas, agujeros negros y múltiples dimensiones [Ep.83]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1372">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/585cd0c436a187b42377b17f.mp3" title="La realidad tras las demandas de Nokia">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">La realidad tras las demandas de Nokia</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1373">
		<a href="#" data-media="http://tracking.feedpress.it/link/14730/7427257/CN_Programa_019.mp3" title="#CN019 – Hablamos sobre todas las novedades del Synology Event 2017">
			<span class="isplaying"></span>
			<span class="logo culturanas"></span>
			<span class="podcast">Cultura NAS</span>
			<span class="track">#CN019 – Hablamos sobre todas las novedades del Synology Event 2017</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1374">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/5015085/Bat2x100_75.mp3" title="#75 – Disculpas / Telegram IFTTT">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#75 – Disculpas / Telegram IFTTT</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1375">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/5011944/Bat2x100_74.mp3" title="#74 – Variado De Miércoles">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#74 – Variado De Miércoles</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1376">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/585a280a36a187b42377a127.mp3" title="Los Mac se van apagando en Apple">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Los Mac se van apagando en Apple</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1377">
		<a href="#" data-media="http://feedproxy.google.com/~r/WecodesignPodcast/~5/HV64oiyylKI/WeCodeSign%201x17%20-%20SVG.mp3" title="17 - SVG">
			<span class="isplaying"></span>
			<span class="logo wecodesignpodcast"></span>
			<span class="podcast">WeCodeSign Podcast</span>
			<span class="track">17 - SVG</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1378">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2016/12/podcast-5-cloud-centros-de-datos.mp3" title="Podcast #5: Introducción al Cloud y servicios de Centros de Datos">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #5: Introducción al Cloud y servicios de Centros de Datos</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1379">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/5858d271683610846bbfc1f1.mp3" title="Zuckerberg sigue siendo un hacker">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Zuckerberg sigue siendo un hacker</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1380">
		<a href="#" data-media="http://www.ivoox.com/netflix-big-data-futuro-del-entretenimiento_mf_15164654_feed_1.mp3" title="Netflix, big data y el futuro del entretenimiento | Episodio 39">
			<span class="isplaying"></span>
			<span class="logo repúblicaweb"></span>
			<span class="podcast">República Web</span>
			<span class="track">Netflix, big data y el futuro del entretenimiento | Episodio 39</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1381">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/5857a639c9b0ca9d6b577718.mp3" title="El día del Apple-amiento">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">El día del Apple-amiento</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1382">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/4985759/Bat2x100_73.mp3" title="#73 – Especial Navidad ’16. V1.0">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#73 – Especial Navidad ’16. V1.0</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1383">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/4982891/Bat2x100_72.mp3" title="#72 – Plexpy Y Los Bloqueos De Las Cuentas en Amazon Cloud Drive">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#72 – Plexpy Y Los Bloqueos De Las Cuentas en Amazon Cloud Drive</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1384">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/4978702/Bat2x100_71.mp3" title="#71 – Notición + Podcasting Nocturno.">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#71 – Notición + Podcasting Nocturno.</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1385">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/4978611/Bat2x100_70.mp3" title="#70 – Amazon Pantry Y Mis Menesteres Navideños.">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#70 – Amazon Pantry Y Mis Menesteres Navideños.</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1386">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/4976671/Bat2x100_69.mp3" title="#69 – PLEX PHOTO Y PLEX MUSIC">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#69 – PLEX PHOTO Y PLEX MUSIC</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1387">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/58523fecdbf90bd83f5009b3.mp3" title="La foto de la vergüenza">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">La foto de la vergüenza</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1388">
		<a href="#" data-media="https://gitlab.com/podcastlinux/podcastlinux.gitlab.io/raw/master/Linux-Express/%2302%20Podcast%20Linux%20Express.mp3" title="#02 Linux Express">
			<span class="isplaying"></span>
			<span class="logo linuxexpressdepodcastlinux"></span>
			<span class="podcast">Linux Express, de Podcast Linux.</span>
			<span class="track">#02 Linux Express</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1389">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/4968838/Bat2x100_68.mp3" title="#68 – Amazon Go, Netflix Y La Inteligencia Artificial">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#68 – Amazon Go, Netflix Y La Inteligencia Artificial</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1390">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/5850d57adbf90bd83f4ff98f.mp3" title="Apple te lo da y Apple te lo quita">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Apple te lo da y Apple te lo quita</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1391">
		<a href="#" data-media="http://www.ivoox.com/7-errores-clasicos-a-evitar-tu-pagina_mf_14949043_feed_1.mp3" title="7 errores clásicos a evitar en tu página web | Episodio 38">
			<span class="isplaying"></span>
			<span class="logo repúblicaweb"></span>
			<span class="podcast">República Web</span>
			<span class="track">7 errores clásicos a evitar en tu página web | Episodio 38</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1392">
		<a href="#" data-media="http://www.ivoox.com/010-preguntas-respuestas-productividad_mf_14936160_feed_1.mp3" title="010 - Preguntas y respuestas de productividad">
			<span class="isplaying"></span>
			<span class="logo aprendiendogtdpodcastproductividad"></span>
			<span class="podcast">Aprendiendo GTD podcast productividad</span>
			<span class="track">010 - Preguntas y respuestas de productividad</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1393">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/4962010/Bat2x100_67.mp3" title="#67 – PLEX : Sincronización Y Nubes.">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#67 – PLEX : Sincronización Y Nubes.</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1394">
		<a href="#" data-media="http://api.spreaker.com/download/episode/10094908/podcast102.mp3" title="#102. Luces árbol de Navidad NeoPixel con Arduino, hazlo tu mismo">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">#102. Luces árbol de Navidad NeoPixel con Arduino, hazlo tu mismo</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1395">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/584f8106dbf90bd83f4fef2b.mp3" title="Realidad aumentada para tu iPhone">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Realidad aumentada para tu iPhone</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1396">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/4955048/Bat2x100_66.mp3" title="#66 – Termostatos">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#66 – Termostatos</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1397">
		<a href="#" data-media="http://www.ivoox.com/13-ciberseguridad-basica-gnu-linux_mf_14880771_feed_1.mp3" title="#13 Ciberseguridad Básica en GNU/Linux">
			<span class="isplaying"></span>
			<span class="logo podcastlinux"></span>
			<span class="podcast">Podcast Linux</span>
			<span class="track">#13 Ciberseguridad Básica en GNU/Linux</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1398">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/584e2aa8dbf90bd83f4fe664.mp3" title="Reunión de pastores en Nueva York">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Reunión de pastores en Nueva York</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1399">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/584df5e8dbf90bd83f4fe4a0.mp3" title="'Pero a mí es que me gusta conducir'">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">'Pero a mí es que me gusta conducir'</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1400">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/297457715-ricardo-garc-a-34-ep82.mp3" title="Materia oscura, vida extraterrestre, conquista espacial y más [Ep.82]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Materia oscura, vida extraterrestre, conquista espacial y más [Ep.82]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1401">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/4948930/Bat2x100_65.mp3" title="#65 – Reflexiones Sábado Noche">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#65 – Reflexiones Sábado Noche</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1402">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2016/12/podcast-4-ssl-spam-postventa-de-apple.mp3" title="Podcast #4: SSL, spam y postventa de Apple">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #4: SSL, spam y postventa de Apple</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1403">
		<a href="#" data-media="http://api.spreaker.com/download/episode/10070579/cap25_por_uso_manjaro_linux_mf_14791474_feed_1.mp3" title="cap25 - Por qué uso manjaro linux">
			<span class="isplaying"></span>
			<span class="logo podcastdmanuelalonso"></span>
			<span class="podcast">Podcast dmanuelalonso</span>
			<span class="track">cap25 - Por qué uso manjaro linux</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1404">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/584a365ddbf90bd83f4fd973.mp3" title="Dejemos a Google ser Google">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Dejemos a Google ser Google</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1405">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/5848e34df56d3fc825156794.mp3" title="El avance más importante en el mercado de PC desde el iPad">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">El avance más importante en el mercado de PC desde el iPad</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1406">
		<a href="#" data-media="http://tracking.feedpress.it/link/15407/4921432/BCS-006-Raul-en-el-Cronovisor.mp3" title="BCS006 – Raúl en El Cronovisor">
			<span class="isplaying"></span>
			<span class="logo bitácoradeciberseguridad"></span>
			<span class="podcast">Bitácora de Ciberseguridad</span>
			<span class="track">BCS006 – Raúl en El Cronovisor</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1407">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/58478e35f56d3fc8251560a3.mp3" title="Samsung es una empresa complicada">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Samsung es una empresa complicada</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1408">
		<a href="#" data-media="http://www.ivoox.com/acceso-a-internet-como-derecho-humano_mf_14666574_feed_1.mp3" title="El acceso a internet como derecho humano | Episodio 37">
			<span class="isplaying"></span>
			<span class="logo repúblicaweb"></span>
			<span class="podcast">República Web</span>
			<span class="track">El acceso a internet como derecho humano | Episodio 37</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1409">
		<a href="#" data-media="http://feedproxy.google.com/~r/WecodesignPodcast/~5/rtScRZRWElE/WeCodeSign%201x16%20-%20Buenas%20pra%CC%81cticas%20CSS.mp3" title="16 - Buenas prácticas CSS">
			<span class="isplaying"></span>
			<span class="logo wecodesignpodcast"></span>
			<span class="podcast">WeCodeSign Podcast</span>
			<span class="track">16 - Buenas prácticas CSS</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1410">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/584629eff56d3fc825155baf.mp3" title="El coche de Apple no es como te lo imaginas">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">El coche de Apple no es como te lo imaginas</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1411">
		<a href="#" data-media="http://www.ivoox.com/retroactivo-podcast-61-sierra-on-line_mf_14593861_feed_1.mp3" title="RetroActivo Podcast #61: Sierra On-Line">
			<span class="isplaying"></span>
			<span class="logo retroactivopodcast"></span>
			<span class="podcast">RetroActivo Podcast</span>
			<span class="track">RetroActivo Podcast #61: Sierra On-Line</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1412">
		<a href="#" data-media="https://gitlab.com/podcastlinux/podcastlinux.gitlab.io/raw/master/Linux-Express/%2301%20Podcast%20Linux%20Express.mp3" title="#01 Linux Express">
			<span class="isplaying"></span>
			<span class="logo linuxexpressdepodcastlinux"></span>
			<span class="podcast">Linux Express, de Podcast Linux.</span>
			<span class="track">#01 Linux Express</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1413">
		<a href="#" data-media="http://api.spreaker.com/download/episode/10029497/cap24_las_baterias_mf_14509323_feed_1.mp3" title="cap24 - Las baterías">
			<span class="isplaying"></span>
			<span class="logo podcastdmanuelalonso"></span>
			<span class="podcast">Podcast dmanuelalonso</span>
			<span class="track">cap24 - Las baterías</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1414">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/4894112/Bat2x100_64.mp3" title="#64 – Empieza La Navidad !">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#64 – Empieza La Navidad !</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1415">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/584172d1f56d3fc8251550ba.mp3" title="Twitter nos ha vuelto a fallar">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Twitter nos ha vuelto a fallar</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1416">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/584098c4f56d3fc825154a44.mp3" title="El camión de Amazon demuestra lo inteligente que es Jeff Bezos">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">El camión de Amazon demuestra lo inteligente que es Jeff Bezos</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1417">
		<a href="#" data-media="http://api.spreaker.com/download/episode/10015027/s02e04_jvm_y_otras_movidas.mp3" title="S02E04 JVM y otras movidas">
			<span class="isplaying"></span>
			<span class="logo codeontherocks"></span>
			<span class="podcast">Code on the rocks</span>
			<span class="track">S02E04 JVM y otras movidas</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1418">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/4886356/Bat2x100_63.mp3" title="#63 – ApplePay !! Y Muchas Noticias….">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#63 – ApplePay !! Y Muchas Noticias….</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1419">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2016/12/podcast-3-como-crear-un-podcast.mp3" title="Podcast #3: Cómo crear un podcast">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #3: Cómo crear un podcast</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1420">
		<a href="#" data-media="http://www.ivoox.com/10-normas-wikipedia-para-editar-en_mf_14309652_feed_1.mp3" title="Las 10 normas de Wikipedia para editar en la web | Episodio 36">
			<span class="isplaying"></span>
			<span class="logo repúblicaweb"></span>
			<span class="podcast">República Web</span>
			<span class="track">Las 10 normas de Wikipedia para editar en la web | Episodio 36</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1421">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/4877236/Bat2x100_62.mp3" title="#62 – Mi Experiencia Con UBER en Miami !">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#62 – Mi Experiencia Con UBER en Miami !</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1422">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/583f7d14f56d3fc825154923.mp3" title="Todo el mundo quiere un coche autónomo">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Todo el mundo quiere un coche autónomo</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1423">
		<a href="#" data-media="http://api.spreaker.com/download/episode/9999312/cap23_xiaomi_bloquea_sus_moviles_mf_14253378_feed_1.mp3" title="cap23 - Xiaomi bloquea sus móviles">
			<span class="isplaying"></span>
			<span class="logo podcastdmanuelalonso"></span>
			<span class="podcast">Podcast dmanuelalonso</span>
			<span class="track">cap23 - Xiaomi bloquea sus móviles</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1424">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/583d927ef56d3fc82515469d.mp3" title="El día más importante para Uber y Samsung">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">El día más importante para Uber y Samsung</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1425">
		<a href="#" data-media="http://tracking.feedpress.it/link/14730/7427258/CN_Programa_018.mp3" title="#CN018 – Nos vigilan las 24h">
			<span class="isplaying"></span>
			<span class="logo culturanas"></span>
			<span class="podcast">Cultura NAS</span>
			<span class="track">#CN018 – Nos vigilan las 24h</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1426">
		<a href="#" data-media="http://podcast.edyo.es/podcast/edyo-20.mp3" title="Edyo 20 - Entrevista a David Monreal">
			<span class="isplaying"></span>
			<span class="logo entredevyopspodcast"></span>
			<span class="podcast">EntreDevYOps Podcast</span>
			<span class="track">Edyo 20 - Entrevista a David Monreal</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1427">
		<a href="#" data-media="http://api.spreaker.com/download/episode/9991973/podcast101.mp3" title="101. Proyectos IoT con Arduino, las plataformas más importantes">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">101. Proyectos IoT con Arduino, las plataformas más importantes</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1428">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/583c23bef56d3fc82515451c.mp3" title="Google inventa un idioma sin querer">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Google inventa un idioma sin querer</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1429">
		<a href="#" data-media="http://www.ivoox.com/12-linux-connexion-alejandro-lopez-slimbook_mf_14164009_feed_1.mp3" title="#12 Linux Connexion con Alejandro López ( Slimbook )">
			<span class="isplaying"></span>
			<span class="logo podcastlinux"></span>
			<span class="podcast">Podcast Linux</span>
			<span class="track">#12 Linux Connexion con Alejandro López ( Slimbook )</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1430">
		<a href="#" data-media="http://tapewrite.com/REST/feed/@alexbarredo/583edaaaf56d3fc82515486d.mp3" title="Google vs Google">
			<span class="isplaying"></span>
			<span class="logo mixxiotecnologíaynegocios"></span>
			<span class="podcast">mixx.io, tecnología y negocios</span>
			<span class="track">Google vs Google</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1431">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/294883320-ricardo-garc-a-34-episodio81.mp3" title="El gran desafío para encontrar otras Tierras [Ep.81]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">El gran desafío para encontrar otras Tierras [Ep.81]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1432">
		<a href="#" data-media="http://www.podtrac.com/pts/redirect.mp3/www.wedevelopers.com/podcast/wedevelopers047.mp3" title="We.Developers 047 – SAP">
			<span class="isplaying"></span>
			<span class="logo wedevelopers"></span>
			<span class="podcast">We.Developers</span>
			<span class="track">We.Developers 047 – SAP</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1433">
		<a href="#" data-media="http://api.spreaker.com/download/episode/9963304/cap22_microsoft_office_vs_libreoffice_mf_13986412_feed_1.mp3" title="cap22 - Microsoft Office VS. LibreOffice">
			<span class="isplaying"></span>
			<span class="logo podcastdmanuelalonso"></span>
			<span class="podcast">Podcast dmanuelalonso</span>
			<span class="track">cap22 - Microsoft Office VS. LibreOffice</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1434">
		<a href="#" data-media="http://www.ivoox.com/batalla-del-comercio-local-internet_mf_13869779_feed_1.mp3" title="La batalla del comercio local con internet | Episodio 35">
			<span class="isplaying"></span>
			<span class="logo repúblicaweb"></span>
			<span class="podcast">República Web</span>
			<span class="track">La batalla del comercio local con internet | Episodio 35</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1435">
		<a href="#" data-media="http://feedproxy.google.com/~r/WecodesignPodcast/~5/FY-VkIJe5a0/WeCodeSign%201x15%20-%20Herramientas%20del%20Frontend.mp3" title="15 - Herramientas del Frontend">
			<span class="isplaying"></span>
			<span class="logo wecodesignpodcast"></span>
			<span class="podcast">WeCodeSign Podcast</span>
			<span class="track">15 - Herramientas del Frontend</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1436">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2016/12/podcast-2-crud-en-rails-formularios-dinamicos.mp3" title="Podcast #2: Git, CRUD en Rails y Formularios dinámicos en HTML con JavaScript">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #2: Git, CRUD en Rails y Formularios dinámicos en HTML con JavaScript</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1437">
		<a href="#" data-media="http://www.ivoox.com/es-economia-atencion-estupido_mf_13768768_feed_1.mp3" title="¡Es la economía de la atención, estúpido! | Episodio 34">
			<span class="isplaying"></span>
			<span class="logo repúblicaweb"></span>
			<span class="podcast">República Web</span>
			<span class="track">¡Es la economía de la atención, estúpido! | Episodio 34</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1438">
		<a href="#" data-media="http://www.ivoox.com/009-hacer-tareas-nuestro-sistema_mf_13765048_feed_1.mp3" title="009 - Hacer las tareas de nuestro sistema GTD">
			<span class="isplaying"></span>
			<span class="logo aprendiendogtdpodcastproductividad"></span>
			<span class="podcast">Aprendiendo GTD podcast productividad</span>
			<span class="track">009 - Hacer las tareas de nuestro sistema GTD</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1439">
		<a href="#" data-media="http://www.ivoox.com/11-linux-connexion-gabriel-viso-pitando-net-podcast_mf_13759097_feed_1.mp3" title="#11 Linux Connexion con Gabriel Viso (Pitando.net). Podcast Linux">
			<span class="isplaying"></span>
			<span class="logo podcastlinux"></span>
			<span class="podcast">Podcast Linux</span>
			<span class="track">#11 Linux Connexion con Gabriel Viso (Pitando.net). Podcast Linux</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1440">
		<a href="#" data-media="http://api.spreaker.com/download/episode/9877168/podcast100.mp3" title="100. Trabajar como Freelance emprendedor, la historia de Luis del Valle">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">100. Trabajar como Freelance emprendedor, la historia de Luis del Valle</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1441">
		<a href="#" data-media="http://tracking.feedpress.it/link/15407/4789459/BCS-005-HoneyCON16.mp3" title="BCS005 – HoneyCON16">
			<span class="isplaying"></span>
			<span class="logo bitácoradeciberseguridad"></span>
			<span class="podcast">Bitácora de Ciberseguridad</span>
			<span class="track">BCS005 – HoneyCON16</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1442">
		<a href="#" data-media="http://www.podtrac.com/pts/redirect.mp3/www.wedevelopers.com/podcast/wedevelopers046.mp3" title="We.Developers 046 – Docker">
			<span class="isplaying"></span>
			<span class="logo wedevelopers"></span>
			<span class="podcast">We.Developers</span>
			<span class="track">We.Developers 046 – Docker</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1443">
		<a href="#" data-media="http://api.spreaker.com/download/episode/9859247/cap21_uso_mac_linux_windows_android_y_mf_13724757_feed_1.mp3" title="cap21 - Uso Mac, Linux, Windows, Android y Xiaomi">
			<span class="isplaying"></span>
			<span class="logo podcastdmanuelalonso"></span>
			<span class="podcast">Podcast dmanuelalonso</span>
			<span class="track">cap21 - Uso Mac, Linux, Windows, Android y Xiaomi</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1444">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/4776794/Bat2x100_61.mp3" title="#61 – AyudaAlba Y Desvirtualizando Podcasters.">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#61 – AyudaAlba Y Desvirtualizando Podcasters.</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1445">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2016/12/podcast-1-presentacion-rails-lynda.mp3" title="Podcast #1: Presentación, Rails y Lynda.com">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #1: Presentación, Rails y Lynda.com</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1446">
		<a href="#" data-media="http://www.ivoox.com/sms-marketing-para-pymes-comercios-episodio_mf_13684707_feed_1.mp3" title="SMS Marketing para pymes y comercios | Episodio 33">
			<span class="isplaying"></span>
			<span class="logo repúblicaweb"></span>
			<span class="podcast">República Web</span>
			<span class="track">SMS Marketing para pymes y comercios | Episodio 33</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1447">
		<a href="#" data-media="http://tracking.feedpress.it/link/14730/7427259/CN_Programa_017.mp3" title="#CN017 – Hablamos sobre el QNAP World Tour 2016">
			<span class="isplaying"></span>
			<span class="logo culturanas"></span>
			<span class="podcast">Cultura NAS</span>
			<span class="track">#CN017 – Hablamos sobre el QNAP World Tour 2016</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1448">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/292191021-ricardo-garc-a-34-episodio80.mp3" title="Astronomía desde el espacio. Misiones, exoplanetas, datos, satélites y ESA [Ep.80]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Astronomía desde el espacio. Misiones, exoplanetas, datos, satélites y ESA [Ep.80]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1449">
		<a href="#" data-media="http://feedproxy.google.com/~r/WecodesignPodcast/~5/eLAOfrZNJDU/WeCodeSign%201x14%20-%20Accesibilidad%20Web.mp3" title="14 - Accesibilidad Web">
			<span class="isplaying"></span>
			<span class="logo wecodesignpodcast"></span>
			<span class="podcast">WeCodeSign Podcast</span>
			<span class="track">14 - Accesibilidad Web</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1450">
		<a href="#" data-media="http://api.spreaker.com/download/episode/9858784/cap20_la_mejor_rom_xiaomi_mf_13662154_feed_1.mp3" title="cap20 - La mejor ROM de Xiaomi">
			<span class="isplaying"></span>
			<span class="logo podcastdmanuelalonso"></span>
			<span class="podcast">Podcast dmanuelalonso</span>
			<span class="track">cap20 - La mejor ROM de Xiaomi</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1451">
		<a href="#" data-media="http://www.ivoox.com/008-evaluacion-nuestro-sistema-gtd_mf_13660172_feed_1.mp3" title="008 - Evaluación de nuestro sistema GTD">
			<span class="isplaying"></span>
			<span class="logo aprendiendogtdpodcastproductividad"></span>
			<span class="podcast">Aprendiendo GTD podcast productividad</span>
			<span class="track">008 - Evaluación de nuestro sistema GTD</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1452">
		<a href="#" data-media="https://media.blubrry.com/eduardocollado/www.eduardocollado.com/wp-content/uploads/2016/12/podcast-0.mp3" title="Podcast #0: Presentación">
			<span class="isplaying"></span>
			<span class="logo podcastdeeduardocollado"></span>
			<span class="podcast">Podcast de Eduardo Collado</span>
			<span class="track">Podcast #0: Presentación</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1453">
		<a href="#" data-media="http://tracking.feedpress.it/link/15407/4789460/Episodio-004-Ley-de-Proteccion-de-Datos-Parte-2.mp3" title="BCS004 – Ley de Protección de Datos (Parte 2)">
			<span class="isplaying"></span>
			<span class="logo bitácoradeciberseguridad"></span>
			<span class="podcast">Bitácora de Ciberseguridad</span>
			<span class="track">BCS004 – Ley de Protección de Datos (Parte 2)</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1454">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/4739234/Bat2x100_60.mp3" title="#60 – Descuentos en Amazon Con COINC Y Un Par De Cosas Más.">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#60 – Descuentos en Amazon Con COINC Y Un Par De Cosas Más.</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1455">
		<a href="#" data-media="http://www.ivoox.com/no-disparen-al-community-manager-episodio-32_mf_13602744_feed_1.mp3" title="No disparen al community manager | Episodio 32">
			<span class="isplaying"></span>
			<span class="logo repúblicaweb"></span>
			<span class="podcast">República Web</span>
			<span class="track">No disparen al community manager | Episodio 32</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1456">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/4733251/Bat2x100_59.mp3" title="#59 – Suscripciones Con Movistar Y Más Cosillas.">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#59 – Suscripciones Con Movistar Y Más Cosillas.</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1457">
		<a href="#" data-media="http://api.spreaker.com/download/episode/9773815/s02e03_el_futuro_del_software.mp3" title="S02E03 El futuro del software">
			<span class="isplaying"></span>
			<span class="logo codeontherocks"></span>
			<span class="podcast">Code on the rocks</span>
			<span class="track">S02E03 El futuro del software</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1458">
		<a href="#" data-media="http://api.spreaker.com/download/episode/9769921/podcast99.mp3" title="99. Arquitectura IoT, prototipando los dispositivos del futuro">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">99. Arquitectura IoT, prototipando los dispositivos del futuro</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1459">
		<a href="#" data-media="http://www.ivoox.com/retroactivo-podcast-60-nasa-human-computers_mf_13540817_feed_1.mp3" title="RetroActivo Podcast #60: NASA Human Computers">
			<span class="isplaying"></span>
			<span class="logo retroactivopodcast"></span>
			<span class="podcast">RetroActivo Podcast</span>
			<span class="track">RetroActivo Podcast #60: NASA Human Computers</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1460">
		<a href="#" data-media="http://www.ivoox.com/recuerdos-presente-interminable-internet_mf_13531885_feed_1.mp3" title="Los recuerdos en el presente interminable de internet | Episodio 31">
			<span class="isplaying"></span>
			<span class="logo repúblicaweb"></span>
			<span class="podcast">República Web</span>
			<span class="track">Los recuerdos en el presente interminable de internet | Episodio 31</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1461">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/4712043/Bat2x100_58.mp3" title="#58 – Podcast Tardío …">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#58 – Podcast Tardío …</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1462">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/290008960-ricardo-garc-a-34-episodio79.mp3" title="La forma de nuestro universo y vientos galácticos [Ep.79]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">La forma de nuestro universo y vientos galácticos [Ep.79]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1463">
		<a href="#" data-media="http://feedproxy.google.com/~r/WecodesignPodcast/~5/4M5fzVCh9aE/WeCodeSign%201x13%20-%20El%20ecosistema%20Frontend.mp3" title="13 - El ecosistema frontend">
			<span class="isplaying"></span>
			<span class="logo wecodesignpodcast"></span>
			<span class="podcast">WeCodeSign Podcast</span>
			<span class="track">13 - El ecosistema frontend</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1464">
		<a href="#" data-media="http://api.spreaker.com/download/episode/9715839/podcast98.mp3" title="98. 5 proyectos con Arduino para iniciarse en el mundo Maker">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">98. 5 proyectos con Arduino para iniciarse en el mundo Maker</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1465">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/4685064/Bat2x100_57.mp3" title="#57 – Thermo (Withings)">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#57 – Thermo (Withings)</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1466">
		<a href="#" data-media="http://www.ivoox.com/23-que-es-como-se-prepara-para_mf_13435849_feed_1.mp3" title="23. Qué es, cómo se prepara y para qué sirve un ataque DDoS. Qué ocurrió realmente este viernes">
			<span class="isplaying"></span>
			<span class="logo naserospodcast"></span>
			<span class="podcast">NASeros Podcast</span>
			<span class="track">23. Qué es, cómo se prepara y para qué sirve un ataque DDoS. Qué ocurrió realmente este viernes</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1467">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/4682146/Bat2x100_56.mp3" title="#56 – Mokacam">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#56 – Mokacam</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1468">
		<a href="#" data-media="http://www.ivoox.com/amor-tiempos-del-emoji-episodio_mf_13430552_feed_1.mp3" title="El amor en tiempos del emoji | Episodio 30">
			<span class="isplaying"></span>
			<span class="logo repúblicaweb"></span>
			<span class="podcast">República Web</span>
			<span class="track">El amor en tiempos del emoji | Episodio 30</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1469">
		<a href="#" data-media="http://www.ivoox.com/22-vpns-pago-plex-cloud-agregacion_mf_13404579_feed_1.mp3" title="22. VPNs de pago, Plex Cloud y Agregación de enlaces o LACP">
			<span class="isplaying"></span>
			<span class="logo naserospodcast"></span>
			<span class="podcast">NASeros Podcast</span>
			<span class="track">22. VPNs de pago, Plex Cloud y Agregación de enlaces o LACP</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1470">
		<a href="#" data-media="http://tracking.feedpress.it/link/14730/7427260/CN_Programa_016.mp3" title="#CN016 – La virtualización para todos los públicos">
			<span class="isplaying"></span>
			<span class="logo culturanas"></span>
			<span class="podcast">Cultura NAS</span>
			<span class="track">#CN016 – La virtualización para todos los públicos</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1471">
		<a href="#" data-media="http://podcast.edyo.es/podcast/edyo-19.mp3" title="Edyo 19 - Serverless">
			<span class="isplaying"></span>
			<span class="logo entredevyopspodcast"></span>
			<span class="podcast">EntreDevYOps Podcast</span>
			<span class="track">Edyo 19 - Serverless</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1472">
		<a href="#" data-media="http://api.spreaker.com/download/episode/9662020/podcast97.mp3" title="97. Obijuan, que el software libre te acompañe">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">97. Obijuan, que el software libre te acompañe</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1473">
		<a href="#" data-media="http://www.ivoox.com/internet-como-arma-decisiva-para-ganar-elecciones_mf_13340446_feed_1.mp3" title="Internet como arma decisiva para ganar elecciones | Episodio 29">
			<span class="isplaying"></span>
			<span class="logo repúblicaweb"></span>
			<span class="podcast">República Web</span>
			<span class="track">Internet como arma decisiva para ganar elecciones | Episodio 29</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1474">
		<a href="#" data-media="http://www.ivoox.com/21-tipos-sistemas-seguridad-podemos-tener_mf_13321458_feed_1.mp3" title="21. Tipos de sistemas seguridad que podemos tener">
			<span class="isplaying"></span>
			<span class="logo naserospodcast"></span>
			<span class="podcast">NASeros Podcast</span>
			<span class="track">21. Tipos de sistemas seguridad que podemos tener</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1475">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/4626880/Bat2x100_55.mp3" title="#55 – Ya Estoy De Vuelta">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#55 – Ya Estoy De Vuelta</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1476">
		<a href="#" data-media="http://www.ivoox.com/007-como-organizar-tareas-proyectos-en_mf_13288081_feed_1.mp3" title="007 - Cómo organizar tareas y proyectos en GTD">
			<span class="isplaying"></span>
			<span class="logo aprendiendogtdpodcastproductividad"></span>
			<span class="podcast">Aprendiendo GTD podcast productividad</span>
			<span class="track">007 - Cómo organizar tareas y proyectos en GTD</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1477">
		<a href="#" data-media="http://www.podtrac.com/pts/redirect.mp3/www.wedevelopers.com/podcast/wedevelopers045.mp3" title="We.Developers 045 – Inteligencia Artificial con Amstrad CPC">
			<span class="isplaying"></span>
			<span class="logo wedevelopers"></span>
			<span class="podcast">We.Developers</span>
			<span class="track">We.Developers 045 – Inteligencia Artificial con Amstrad CPC</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1478">
		<a href="#" data-media="http://tracking.feedpress.it/link/15407/4789461/BCS-003-Ley-Proteccion-Datos-1.mp3" title="BCS003 – Ley de Protección de Datos (Parte 1)">
			<span class="isplaying"></span>
			<span class="logo bitácoradeciberseguridad"></span>
			<span class="podcast">Bitácora de Ciberseguridad</span>
			<span class="track">BCS003 – Ley de Protección de Datos (Parte 1)</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1479">
		<a href="#" data-media="http://www.ivoox.com/02x04-akademy-2016-berlin_mf_13282347_feed_1.mp3" title="02x04 Akademy 2016 en Berlín">
			<span class="isplaying"></span>
			<span class="logo podcastdekdeespaña"></span>
			<span class="podcast">Podcast de KDE España</span>
			<span class="track">02x04 Akademy 2016 en Berlín</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1480">
		<a href="#" data-media="http://feedproxy.google.com/~r/WecodesignPodcast/~5/A4tcpF8KTMY/WeCodeSign%201x11%20-%20Tipografi%CC%81a%20Web.mp3" title="12 - Tipografía Web">
			<span class="isplaying"></span>
			<span class="logo wecodesignpodcast"></span>
			<span class="podcast">WeCodeSign Podcast</span>
			<span class="track">12 - Tipografía Web</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1481">
		<a href="#" data-media="http://www.ivoox.com/09-especial-lenovo-thinkpad-x220_mf_13265714_feed_1.mp3" title="#09 Especial Lenovo ThinkPad X220">
			<span class="isplaying"></span>
			<span class="logo podcastlinux"></span>
			<span class="podcast">Podcast Linux</span>
			<span class="track">#09 Especial Lenovo ThinkPad X220</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1482">
		<a href="#" data-media="http://api.spreaker.com/download/episode/9612398/podcast96.mp3" title="96. Programación con Arduino, el paradigma de la computación física">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">96. Programación con Arduino, el paradigma de la computación física</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1483">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/287030480-ricardo-garc-a-34-episodio78.mp3" title="¿Encontraremos vida en Marte? Todo acerca de ExoMars [Ep.78]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">¿Encontraremos vida en Marte? Todo acerca de ExoMars [Ep.78]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1484">
		<a href="#" data-media="http://www.ivoox.com/google-amp-futuro-web_mf_13255058_feed_1.mp3" title="Google AMP y el futuro de la web móvil | Episodio 28">
			<span class="isplaying"></span>
			<span class="logo repúblicaweb"></span>
			<span class="podcast">República Web</span>
			<span class="track">Google AMP y el futuro de la web móvil | Episodio 28</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1485">
		<a href="#" data-media="http://www.ivoox.com/revolucion-blockchain-episodio-27_mf_13188425_feed_1.mp3" title="La revolución Blockchain | Episodio 27">
			<span class="isplaying"></span>
			<span class="logo repúblicaweb"></span>
			<span class="podcast">República Web</span>
			<span class="track">La revolución Blockchain | Episodio 27</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1486">
		<a href="#" data-media="http://api.spreaker.com/download/episode/9559392/podcast95.mp3" title="95. Staticboards, fabricar electrónica para Arduino made in Spain">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">95. Staticboards, fabricar electrónica para Arduino made in Spain</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1487">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/285605782-ricardo-garc-a-34-episodio77.mp3" title="Todo lo que necesitas saber para hacer fotografía astronómica [Ep.77]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Todo lo que necesitas saber para hacer fotografía astronómica [Ep.77]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1488">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/4535017/Bat2x100_54.mp3" title="#54 – PLEX Cloud">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#54 – PLEX Cloud</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1489">
		<a href="#" data-media="http://tracking.feedpress.it/link/14730/7427583/CN_Programa_015.mp3" title="#CN015 – Adrián Groba, responsable de ventas en QNAP España">
			<span class="isplaying"></span>
			<span class="logo culturanas"></span>
			<span class="podcast">Cultura NAS</span>
			<span class="track">#CN015 – Adrián Groba, responsable de ventas en QNAP España</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1490">
		<a href="#" data-media="http://www.ivoox.com/08-sabores-a-montones_mf_13103580_feed_1.mp3" title="#08 Sabores a montones">
			<span class="isplaying"></span>
			<span class="logo podcastlinux"></span>
			<span class="podcast">Podcast Linux</span>
			<span class="track">#08 Sabores a montones</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1491">
		<a href="#" data-media="http://www.ivoox.com/turbulenta-relacion-industria-musical-con_mf_13094832_feed_1.mp3" title="La turbulenta relación de la industria musical con internet | Episodio 26">
			<span class="isplaying"></span>
			<span class="logo repúblicaweb"></span>
			<span class="podcast">República Web</span>
			<span class="track">La turbulenta relación de la industria musical con internet | Episodio 26</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1492">
		<a href="#" data-media="http://api.spreaker.com/download/episode/9505597/s02e02_women_in_tech.mp3" title="S02E02 Women in tech">
			<span class="isplaying"></span>
			<span class="logo codeontherocks"></span>
			<span class="podcast">Code on the rocks</span>
			<span class="track">S02E02 Women in tech</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1493">
		<a href="#" data-media="http://www.ivoox.com/006-procesar-tareas-proyectos-gtd_mf_13088788_feed_1.mp3" title="006 - Procesar tareas y proyectos en GTD">
			<span class="isplaying"></span>
			<span class="logo aprendiendogtdpodcastproductividad"></span>
			<span class="podcast">Aprendiendo GTD podcast productividad</span>
			<span class="track">006 - Procesar tareas y proyectos en GTD</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1494">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/4517572/Bat2x100_53.mp3" title="#53 – Amazon Cloud Drive Y Plex Unidos !!">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#53 – Amazon Cloud Drive Y Plex Unidos !!</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1495">
		<a href="#" data-media="http://feedproxy.google.com/~r/WecodesignPodcast/~5/SI6IvJ6IGYA/WeCodeSign%201x11%20-%20Web%20Audio.mp3" title="11 - Web Audio">
			<span class="isplaying"></span>
			<span class="logo wecodesignpodcast"></span>
			<span class="podcast">WeCodeSign Podcast</span>
			<span class="track">11 - Web Audio</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1496">
		<a href="#" data-media="http://api.spreaker.com/download/episode/9495173/podcast94.mp3" title="94. Por qué usar las interrupciones en Arduino, todo lo que necesitas saber">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">94. Por qué usar las interrupciones en Arduino, todo lo que necesitas saber</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1497">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/284601453-ricardo-garc-a-34-episodio76.mp3" title="Galaxias activas y agujeros negros supermasivos [Ep.76]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Galaxias activas y agujeros negros supermasivos [Ep.76]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1498">
		<a href="#" data-media="http://podcast.edyo.es/podcast/edyo-18.mp3" title="Edyo 18 - Entrevista a Xavi Soler">
			<span class="isplaying"></span>
			<span class="logo entredevyopspodcast"></span>
			<span class="podcast">EntreDevYOps Podcast</span>
			<span class="track">Edyo 18 - Entrevista a Xavi Soler</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1499">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/4488618/Bat2x100_52.mp3" title="#52 – Sorteo ! & iDoctusPed">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#52 – Sorteo ! & iDoctusPed</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1500">
		<a href="#" data-media="http://tracking.feedpress.it/link/15407/4789215/BCS-002-Haz-copias-de-seguridad-ya.mp3" title="#002 – Haz copias de seguridad ¡YA!">
			<span class="isplaying"></span>
			<span class="logo bitácoradeciberseguridad"></span>
			<span class="podcast">Bitácora de Ciberseguridad</span>
			<span class="track">#002 – Haz copias de seguridad ¡YA!</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1501">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/4466370/Bat2x100_51.mp3" title="#51 – LightX">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#51 – LightX</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1502">
		<a href="#" data-media="http://api.spreaker.com/download/episode/9444186/podcast_93.mp3" title="93. ESP8266 todo lo que necesitas saber del módulo WiFi para Arduino">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">93. ESP8266 todo lo que necesitas saber del módulo WiFi para Arduino</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1503">
		<a href="#" data-media="http://www.ivoox.com/bloqueadores-anuncios-heroes-o-villanos-episodio_mf_12956610_feed_1.mp3" title="Bloqueadores de anuncios ¿héroes o villanos? | Episodio 25">
			<span class="isplaying"></span>
			<span class="logo repúblicaweb"></span>
			<span class="podcast">República Web</span>
			<span class="track">Bloqueadores de anuncios ¿héroes o villanos? | Episodio 25</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1504">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/4433408/Bat2x100_50.mp3" title="#50 – In Reply to JM & David">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#50 – In Reply to JM & David</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1505">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/283257177-ricardo-garc-a-34-episodio75.mp3" title="Nebulosas planetarias, el futuro de nuestro Sol [Ep.75]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Nebulosas planetarias, el futuro de nuestro Sol [Ep.75]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1506">
		<a href="#" data-media="http://www.ivoox.com/07-linux-connexion-huezo-grupo-telegram_mf_12912418_feed_1.mp3" title="#07 Linux Connexion con Huezo (Grupo Telegram GNU-Linux)">
			<span class="isplaying"></span>
			<span class="logo podcastlinux"></span>
			<span class="podcast">Podcast Linux</span>
			<span class="track">#07 Linux Connexion con Huezo (Grupo Telegram GNU-Linux)</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1507">
		<a href="#" data-media="http://www.ivoox.com/07-linux-connexion-huezo-grupo-telegram-gnu-linux_mf_13383404_feed_1.mp3" title="#07 Linux Connexion con Huezo (Grupo Telegram GNU/Linux) Podcast Linux">
			<span class="isplaying"></span>
			<span class="logo podcastlinux"></span>
			<span class="podcast">Podcast Linux</span>
			<span class="track">#07 Linux Connexion con Huezo (Grupo Telegram GNU/Linux) Podcast Linux</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1508">
		<a href="#" data-media="http://tracking.feedpress.it/link/14730/7427584/CN_Programa_014.mp3" title="#CN014 – Aumenta la seguridad en tu NAS">
			<span class="isplaying"></span>
			<span class="logo culturanas"></span>
			<span class="podcast">Cultura NAS</span>
			<span class="track">#CN014 – Aumenta la seguridad en tu NAS</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1509">
		<a href="#" data-media="http://feedproxy.google.com/~r/WecodesignPodcast/~5/HA-xFQoZRBo/WeCodeSign%201x10%20-%20Disen%CC%83o%20de%20Interaccio%CC%81n.mp3" title="10 - Diseño de Interacción">
			<span class="isplaying"></span>
			<span class="logo wecodesignpodcast"></span>
			<span class="podcast">WeCodeSign Podcast</span>
			<span class="track">10 - Diseño de Interacción</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1510">
		<a href="#" data-media="http://api.spreaker.com/download/episode/9396831/podcast_92.mp3" title="92. Crear un vehículo autónomo con sensores de ultrasonidos y Arduino">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">92. Crear un vehículo autónomo con sensores de ultrasonidos y Arduino</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1511">
		<a href="#" data-media="http://www.ivoox.com/censura-facebook-episodio-24_mf_12869686_feed_1.mp3" title="La censura en Facebook | Episodio 24">
			<span class="isplaying"></span>
			<span class="logo repúblicaweb"></span>
			<span class="podcast">República Web</span>
			<span class="track">La censura en Facebook | Episodio 24</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1512">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/4388666/Bat2x100_49.mp3" title="#49 – Subsmarine Y Ajuste Del Consumo De Datos.">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#49 – Subsmarine Y Ajuste Del Consumo De Datos.</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1513">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/282256390-ricardo-garc-a-34-episodio74.mp3" title="¿Cómo se forman las estrellas supermasivas? [Ep.74]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">¿Cómo se forman las estrellas supermasivas? [Ep.74]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1514">
		<a href="#" data-media="http://www.ivoox.com/retroactivo-59-historia-tamagotchi-akiyoshi-hongo-tres_mf_12834236_feed_1.mp3" title="RetroActivo #59: Historia de Tamagotchi, Akiyoshi Hongo, tres personas en una">
			<span class="isplaying"></span>
			<span class="logo retroactivopodcast"></span>
			<span class="podcast">RetroActivo Podcast</span>
			<span class="track">RetroActivo #59: Historia de Tamagotchi, Akiyoshi Hongo, tres personas en una</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1515">
		<a href="#" data-media="http://api.spreaker.com/download/episode/9342197/podcast91.mp3" title="91. Motor Shield, arrancando motores del e-tiesto">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">91. Motor Shield, arrancando motores del e-tiesto</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1516">
		<a href="#" data-media="http://www.ivoox.com/fundamentos-para-aprender-diseno-web-episodio_mf_12787049_feed_1.mp3" title="Los fundamentos para aprender diseño web | Episodio 23">
			<span class="isplaying"></span>
			<span class="logo repúblicaweb"></span>
			<span class="podcast">República Web</span>
			<span class="track">Los fundamentos para aprender diseño web | Episodio 23</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1517">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/4339884/Bat2x100_48.mp3" title="#48 – Miscelánea De NAS Y Corrección HYper BackUp Con Amazon Cloud Drive">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#48 – Miscelánea De NAS Y Corrección HYper BackUp Con Amazon Cloud Drive</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1518">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/281346521-ricardo-garc-a-34-episodio73.mp3" title="Próxima b ¿será un planeta similar a la Tierra? [Ep.73]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Próxima b ¿será un planeta similar a la Tierra? [Ep.73]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1519">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/4324745/Bat2x100_47.mp3" title="#47 – Gestores De Datos en IOS">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#47 – Gestores De Datos en IOS</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1520">
		<a href="#" data-media="http://tracking.feedpress.it/link/15407/4307034/ep001-hackeo-muerte-y-resurreccion-de-histocast.mp3" title="#001 – Hackeo, muerte y resurrección de Histocast.com">
			<span class="isplaying"></span>
			<span class="logo bitácoradeciberseguridad"></span>
			<span class="podcast">Bitácora de Ciberseguridad</span>
			<span class="track">#001 – Hackeo, muerte y resurrección de Histocast.com</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1521">
		<a href="#" data-media="http://www.ivoox.com/crisis-obesidad-web_mf_12738677_feed_1.mp3" title="La crisis de obesidad en la web | Episodio 22">
			<span class="isplaying"></span>
			<span class="logo repúblicaweb"></span>
			<span class="podcast">República Web</span>
			<span class="track">La crisis de obesidad en la web | Episodio 22</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1522">
		<a href="#" data-media="http://www.ivoox.com/06-conlinuxsisepuede_mf_12737297_feed_1.mp3" title="#06 #ConLinuxSíSePuede">
			<span class="isplaying"></span>
			<span class="logo podcastlinux"></span>
			<span class="podcast">Podcast Linux</span>
			<span class="track">#06 #ConLinuxSíSePuede</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1523">
		<a href="#" data-media="http://www.ivoox.com/06-conlinuxsisepuede-podcast-linux_mf_13383405_feed_1.mp3" title="#06 #ConLinuxSíSePuede. Podcast Linux">
			<span class="isplaying"></span>
			<span class="logo podcastlinux"></span>
			<span class="podcast">Podcast Linux</span>
			<span class="track">#06 #ConLinuxSíSePuede. Podcast Linux</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1524">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/4301188/Bat2x100_46.mp3" title="#46 – Amazon Cloud Drive">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#46 – Amazon Cloud Drive</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1525">
		<a href="#" data-media="http://api.spreaker.com/download/episode/9304610/s02e01_part_2_virtual_reality_con_diegobez_serhidal.mp3" title="S02E01 Part 2 Virtual Reality con @Diegobez @serhidal">
			<span class="isplaying"></span>
			<span class="logo codeontherocks"></span>
			<span class="podcast">Code on the rocks</span>
			<span class="track">S02E01 Part 2 Virtual Reality con @Diegobez @serhidal</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1526">
		<a href="#" data-media="http://api.spreaker.com/download/episode/9304307/s02e01_virtual_reality_con_diegobez_serhidal.mp3" title="S02E01 Virtual Reality con @Diegobez @serhidal">
			<span class="isplaying"></span>
			<span class="logo codeontherocks"></span>
			<span class="podcast">Code on the rocks</span>
			<span class="track">S02E01 Virtual Reality con @Diegobez @serhidal</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1527">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/4292872/Bat2x100_45.mp3" title="#45 – Malware De Nuevo en Transmission Y Un Reply to Retrotech Podcast">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#45 – Malware De Nuevo en Transmission Y Un Reply to Retrotech Podcast</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1528">
		<a href="#" data-media="http://feedproxy.google.com/~r/WecodesignPodcast/~5/_tGu0jsY4PU/WeCodeSign%201x09%20-%20El%20estado%20actual%20de%20Angular%20y%20Polymer.mp3" title="9 - El estado actual de Angular y Polymer">
			<span class="isplaying"></span>
			<span class="logo wecodesignpodcast"></span>
			<span class="podcast">WeCodeSign Podcast</span>
			<span class="track">9 - El estado actual de Angular y Polymer</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1529">
		<a href="#" data-media="http://api.spreaker.com/download/episode/9293727/podcast90.mp3" title="90. Tiesto inteligente con Arduino, proyecto paso a paso">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">90. Tiesto inteligente con Arduino, proyecto paso a paso</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1530">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/280156762-ricardo-garc-a-34-episodio72.mp3" title="Midiendo la energía y materia oscura del universo [Ep.72]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Midiendo la energía y materia oscura del universo [Ep.72]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1531">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/4242490/Bat2x100_44.mp3" title="#44 – Cosas Varias Y Protector Ultrafino iPhone">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#44 – Cosas Varias Y Protector Ultrafino iPhone</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1532">
		<a href="#" data-media="http://tracking.feedpress.it/link/15407/4242122/000-Piloto-BitacoraDeCiberseguridad.mp3" title="#000 – Piloto de Bitácora de Ciberseguridad">
			<span class="isplaying"></span>
			<span class="logo bitácoradeciberseguridad"></span>
			<span class="podcast">Bitácora de Ciberseguridad</span>
			<span class="track">#000 – Piloto de Bitácora de Ciberseguridad</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1533">
		<a href="#" data-media="http://tracking.feedpress.it/link/14730/7427585/CN_Programa_013.mp3" title="#CN013 – Especial preguntas (fin de) verano">
			<span class="isplaying"></span>
			<span class="logo culturanas"></span>
			<span class="podcast">Cultura NAS</span>
			<span class="track">#CN013 – Especial preguntas (fin de) verano</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1534">
		<a href="#" data-media="http://www.ivoox.com/aumenta-tu-visibilidad-seo-local-episodio_mf_12651810_feed_1.mp3" title="Aumenta tu visibilidad con SEO Local | Episodio 21">
			<span class="isplaying"></span>
			<span class="logo repúblicaweb"></span>
			<span class="podcast">República Web</span>
			<span class="track">Aumenta tu visibilidad con SEO Local | Episodio 21</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1535">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/4221979/Bat2x100_43.mp3" title="#43 – Series Y Aprender a Pronunciar Vitaminización.">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#43 – Series Y Aprender a Pronunciar Vitaminización.</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1536">
		<a href="#" data-media="http://api.spreaker.com/download/episode/9243968/podcast89.mp3" title="89. Eliminar el ruido en Arduino, controlando la señal">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">89. Eliminar el ruido en Arduino, controlando la señal</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1537">
		<a href="#" data-media="http://tracking.feedpress.it/link/15407/4203934/PROMO_NUEVOS_PROGRAMAS_AVPODCAST.mp3" title="En breve en este feed…ciberseguridad para ti">
			<span class="isplaying"></span>
			<span class="logo bitácoradeciberseguridad"></span>
			<span class="podcast">Bitácora de Ciberseguridad</span>
			<span class="track">En breve en este feed…ciberseguridad para ti</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1538">
		<a href="#" data-media="http://www.ivoox.com/10-consejos-para-tu-presencia-profesional-la_mf_12608209_feed_1.mp3" title="10 consejos para tu presencia profesional en la web | Episodio 20">
			<span class="isplaying"></span>
			<span class="logo repúblicaweb"></span>
			<span class="podcast">República Web</span>
			<span class="track">10 consejos para tu presencia profesional en la web | Episodio 20</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1539">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/279089831-ricardo-garc-a-34-episodio71.mp3" title="De los eventos más violentos del Cosmos al universo frío [Ep.71]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">De los eventos más violentos del Cosmos al universo frío [Ep.71]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1540">
		<a href="#" data-media="http://www.ivoox.com/05-linux-connexion-yoyo-fernandez_mf_12593330_feed_1.mp3" title="#05 Linux Connexion con Yoyo Fernández">
			<span class="isplaying"></span>
			<span class="logo podcastlinux"></span>
			<span class="podcast">Podcast Linux</span>
			<span class="track">#05 Linux Connexion con Yoyo Fernández</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1541">
		<a href="#" data-media="http://www.ivoox.com/05-linux-connexion-yoyo-fernandez_mf_13383406_feed_1.mp3" title="#05 Linux Connexion con Yoyo Fernández">
			<span class="isplaying"></span>
			<span class="logo podcastlinux"></span>
			<span class="podcast">Podcast Linux</span>
			<span class="track">#05 Linux Connexion con Yoyo Fernández</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1542">
		<a href="#" data-media="http://feedproxy.google.com/~r/WecodesignPodcast/~5/IMK5K4d-T8g/WeCodeSign%201x08%20-%20Trabajando%20con%20diferentes%20CMS.mp3" title="8 - Trabajando con diferentes CMS">
			<span class="isplaying"></span>
			<span class="logo wecodesignpodcast"></span>
			<span class="podcast">WeCodeSign Podcast</span>
			<span class="track">8 - Trabajando con diferentes CMS</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1543">
		<a href="#" data-media="http://www.ivoox.com/google-rankbrain-su-influencia-seo_mf_12550225_feed_1.mp3" title="Google RankBrain y su influencia en el SEO | Episodio 19">
			<span class="isplaying"></span>
			<span class="logo repúblicaweb"></span>
			<span class="podcast">República Web</span>
			<span class="track">Google RankBrain y su influencia en el SEO | Episodio 19</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1544">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/4140888/Bat2x100_42.mp3" title="#42 – Screens, VNC, TeamViewe, Parallels Access…cuál Usáis Vosotros ??">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#42 – Screens, VNC, TeamViewe, Parallels Access…cuál Usáis Vosotros ??</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1545">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/278127130-ricardo-garc-a-34-episodio70.mp3" title="Exoplanetas ¿encontraremos vida en otro lugar? [Ep.70]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Exoplanetas ¿encontraremos vida en otro lugar? [Ep.70]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1546">
		<a href="#" data-media="http://www.ivoox.com/04-amor-distro-madre_mf_12520959_feed_1.mp3" title="#04 Amor de (Distro) madre">
			<span class="isplaying"></span>
			<span class="logo podcastlinux"></span>
			<span class="podcast">Podcast Linux</span>
			<span class="track">#04 Amor de (Distro) madre</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1547">
		<a href="#" data-media="http://www.ivoox.com/04-amor-distro-madre-podcast-linux_mf_13383407_feed_1.mp3" title="#04 Amor de Distro Madre. Podcast Linux">
			<span class="isplaying"></span>
			<span class="logo podcastlinux"></span>
			<span class="podcast">Podcast Linux</span>
			<span class="track">#04 Amor de Distro Madre. Podcast Linux</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1548">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/4122468/Bat2x100_41.mp3" title="#41 – Pocket Casts Y Sus Filtros.">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#41 – Pocket Casts Y Sus Filtros.</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1549">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/4121849/Bat2x100_40.mp3" title="#40 – Mi Nuevo Mouse Y RoomScan Pro">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#40 – Mi Nuevo Mouse Y RoomScan Pro</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1550">
		<a href="#" data-media="http://www.ivoox.com/nuevas-profesiones-puede-traer-web_mf_12499579_feed_1.mp3" title="Nuevas profesiones que puede traer la web | Episodio 18">
			<span class="isplaying"></span>
			<span class="logo repúblicaweb"></span>
			<span class="podcast">República Web</span>
			<span class="track">Nuevas profesiones que puede traer la web | Episodio 18</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1551">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/4084831/Bat2x100_39.mp3" title="#39 – Suscripciones ?? Seguro ?? & VidLib">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#39 – Suscripciones ?? Seguro ?? & VidLib</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1552">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/277091072-ricardo-garc-a-34-episodio-69-como-crecen-los-agujeros-negros-supermasivos-halos-de-materia-oscura-y-simulaciones.mp3" title="Agujeros negros supermasivos, Halos de Materia Oscura y simulaciones en cosmología [Ep.69]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Agujeros negros supermasivos, Halos de Materia Oscura y simulaciones en cosmología [Ep.69]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1553">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/4068203/Bat2x100_38.mp3" title="#38 – Mix De Cosillas(Droplr, Here,Vivino)">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#38 – Mix De Cosillas(Droplr, Here,Vivino)</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1554">
		<a href="#" data-media="http://www.ivoox.com/resenas-comentarios-otras-mentiras-web_mf_12435906_feed_1.mp3" title="Reseñas, comentarios y otras mentiras de la web | Episodio 17">
			<span class="isplaying"></span>
			<span class="logo repúblicaweb"></span>
			<span class="podcast">República Web</span>
			<span class="track">Reseñas, comentarios y otras mentiras de la web | Episodio 17</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1555">
		<a href="#" data-media="http://www.ivoox.com/005-recopilar-informacion-gtd_mf_12424970_feed_1.mp3" title="005 - Recopilar información en GTD">
			<span class="isplaying"></span>
			<span class="logo aprendiendogtdpodcastproductividad"></span>
			<span class="podcast">Aprendiendo GTD podcast productividad</span>
			<span class="track">005 - Recopilar información en GTD</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1556">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/4052759/Bat2x100_37.mp3" title="#37 – Un 10 Para Movistar en Twitter">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#37 – Un 10 Para Movistar en Twitter</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1557">
		<a href="#" data-media="http://feedproxy.google.com/~r/WecodesignPodcast/~5/VSh_qGnr6_Q/WeCodeSign%20Podcast.%20Episodio%201x07%20-%20Exportando%20talento.mp3" title="7 - Exportando talento">
			<span class="isplaying"></span>
			<span class="logo wecodesignpodcast"></span>
			<span class="podcast">WeCodeSign Podcast</span>
			<span class="track">7 - Exportando talento</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1558">
		<a href="#" data-media="http://www.ivoox.com/retroactivo-podcast-58-c-lenguaje-programacion_mf_12394507_feed_1.mp3" title="RetroActivo Podcast #58: C, el lenguaje de programación">
			<span class="isplaying"></span>
			<span class="logo retroactivopodcast"></span>
			<span class="podcast">RetroActivo Podcast</span>
			<span class="track">RetroActivo Podcast #58: C, el lenguaje de programación</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1559">
		<a href="#" data-media="http://www.ivoox.com/de-vive-whatsapp-episodio-16_mf_12392569_feed_1.mp3" title="¿De qué vive WhatsApp? | Episodio 16">
			<span class="isplaying"></span>
			<span class="logo repúblicaweb"></span>
			<span class="podcast">República Web</span>
			<span class="track">¿De qué vive WhatsApp? | Episodio 16</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1560">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/276119818-ricardo-garc-a-34-episodio68.mp3" title="Astrología para hablar de ciencia [Ep.68]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Astrología para hablar de ciencia [Ep.68]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1561">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/4052760/Bat2x100_36.mp3" title="#36 – Plex : Content Rating & IFTTT">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#36 – Plex : Content Rating & IFTTT</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1562">
		<a href="#" data-media="http://www.ivoox.com/entrevista-francisco-presencia-picnic-css-y_mf_12375913_feed_1.mp3" title="Entrevista con Francisco Presencia de Picnic CSS y Makers UPV | Episodio 15">
			<span class="isplaying"></span>
			<span class="logo repúblicaweb"></span>
			<span class="podcast">República Web</span>
			<span class="track">Entrevista con Francisco Presencia de Picnic CSS y Makers UPV | Episodio 15</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1563">
		<a href="#" data-media="http://www.ivoox.com/03-y-no-estaba-muerto-no-no_mf_12374536_feed_1.mp3" title="#03 Y no estaba muerto, no no">
			<span class="isplaying"></span>
			<span class="logo podcastlinux"></span>
			<span class="podcast">Podcast Linux</span>
			<span class="track">#03 Y no estaba muerto, no no</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1564">
		<a href="#" data-media="http://www.ivoox.com/03-y-no-estaba-muerto-no-no-podcast_mf_13383408_feed_1.mp3" title="#03 Y no estaba muerto, no, no. Podcast Linux">
			<span class="isplaying"></span>
			<span class="logo podcastlinux"></span>
			<span class="podcast">Podcast Linux</span>
			<span class="track">#03 Y no estaba muerto, no, no. Podcast Linux</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1565">
		<a href="#" data-media="http://www.ivoox.com/02x03-plasma-distintas-distribuciones_mf_12362858_feed_1.mp3" title="02x03 Plasma en las distintas distribuciones">
			<span class="isplaying"></span>
			<span class="logo podcastdekdeespaña"></span>
			<span class="podcast">Podcast de KDE España</span>
			<span class="track">02x03 Plasma en las distintas distribuciones</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1566">
		<a href="#" data-media="http://tracking.feedpress.it/link/14730/7427586/CN_Programa_012.mp3" title="#CN012 – ¿Cómo organizamos la información en nuestro NAS?">
			<span class="isplaying"></span>
			<span class="logo culturanas"></span>
			<span class="podcast">Cultura NAS</span>
			<span class="track">#CN012 – ¿Cómo organizamos la información en nuestro NAS?</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1567">
		<a href="#" data-media="http://api.spreaker.com/download/episode/9062389/podcast88.mp3" title="88. Servidor web Low Cost con Raspberry Pi">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">88. Servidor web Low Cost con Raspberry Pi</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1568">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/4052761/Bat2x100_35.mp3" title="#35 – Reflexión">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#35 – Reflexión</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1569">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/275025949-ricardo-garc-a-34-episodio67.mp3" title="Misterio de la Corona Solar, plasma que flota y mujeres en astronomía [Ep.67]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Misterio de la Corona Solar, plasma que flota y mujeres en astronomía [Ep.67]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1570">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/4052762/Bat2x100_34.mp3" title="#34 – Downie & Eliminar Ficheros en Plex & DSPhoto Para Apple TV">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#34 – Downie & Eliminar Ficheros en Plex & DSPhoto Para Apple TV</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1571">
		<a href="#" data-media="http://www.ivoox.com/004-los-cinco-pasos-del-gtd_mf_12304304_feed_1.mp3" title="004 - Los cinco pasos del GTD">
			<span class="isplaying"></span>
			<span class="logo aprendiendogtdpodcastproductividad"></span>
			<span class="podcast">Aprendiendo GTD podcast productividad</span>
			<span class="track">004 - Los cinco pasos del GTD</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1572">
		<a href="#" data-media="http://www.ivoox.com/entrevista-a-pierpaolo-palazzo-fotografo-google-maps_mf_12302261_feed_1.mp3" title="Entrevista a Pierpaolo Palazzo Fotógrafo de Google Maps Business | Episodio 14">
			<span class="isplaying"></span>
			<span class="logo repúblicaweb"></span>
			<span class="podcast">República Web</span>
			<span class="track">Entrevista a Pierpaolo Palazzo Fotógrafo de Google Maps Business | Episodio 14</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1573">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/4052763/Bat2x100_33.mp3" title="#33 – Movistar… Y Orasis">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#33 – Movistar… Y Orasis</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1574">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/4052764/Bat2x100_32.mp3" title="#32 –  Eltima Software : CloudMounter & Más Sobre GPS">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#32 –  Eltima Software : CloudMounter & Más Sobre GPS</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1575">
		<a href="#" data-media="http://feedproxy.google.com/~r/WecodesignPodcast/~5/7gHZ0goj3As/WeCodeSign%20Podcast.%20Episodio%201x06%20-%20Primeros%20pasos%20como%20Front-end%20Designer.mp3" title="6 - Primeros pasos como Front-end Designer">
			<span class="isplaying"></span>
			<span class="logo wecodesignpodcast"></span>
			<span class="podcast">WeCodeSign Podcast</span>
			<span class="track">6 - Primeros pasos como Front-end Designer</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1576">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/4052765/Bat2x100_31.mp3" title="#31 – Plex Home Theater Y GPS iPhone">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#31 – Plex Home Theater Y GPS iPhone</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1577">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/274004776-ricardo-garc-a-34-episodio66.mp3" title="Terraformación, Meteorito Marciano, vulcanismo y Ciencias Planetarias [Ep.66]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Terraformación, Meteorito Marciano, vulcanismo y Ciencias Planetarias [Ep.66]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1578">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/4052766/Bat2x100_30.mp3" title="#30 Adiós a Spreaker Y Desavenencias Con Parallels">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#30 Adiós a Spreaker Y Desavenencias Con Parallels</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1579">
		<a href="#" data-media="http://www.ivoox.com/entrevista-a-jordi-alcaniz-naranjasecologicas-com-episodio_mf_12219106_feed_1.mp3" title="Entrevista a Jordi Alcañiz de naranjasecologicas.com | Episodio 13">
			<span class="isplaying"></span>
			<span class="logo repúblicaweb"></span>
			<span class="podcast">República Web</span>
			<span class="track">Entrevista a Jordi Alcañiz de naranjasecologicas.com | Episodio 13</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1580">
		<a href="#" data-media="http://www.ivoox.com/02-un-pinguino-mi-usb_mf_12218805_feed_1.mp3" title="#02 Un pingüino en mi USB">
			<span class="isplaying"></span>
			<span class="logo podcastlinux"></span>
			<span class="podcast">Podcast Linux</span>
			<span class="track">#02 Un pingüino en mi USB</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1581">
		<a href="#" data-media="http://www.ivoox.com/02-un-pinguino-mi-usb-podcast-linux_mf_13383409_feed_1.mp3" title="#02 Un pingüino en mi USB Podcast Linux">
			<span class="isplaying"></span>
			<span class="logo podcastlinux"></span>
			<span class="podcast">Podcast Linux</span>
			<span class="track">#02 Un pingüino en mi USB Podcast Linux</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1582">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/4052767/Bat2x100_29.mp3" title="#29 Trickster y WaltR2">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#29 Trickster y WaltR2</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1583">
		<a href="#" data-media="http://api.spreaker.com/download/episode/8966066/podcast87.mp3" title="87. Vídeo con Raspberry Pi, crea tu sistema de vigilancia">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">87. Vídeo con Raspberry Pi, crea tu sistema de vigilancia</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1584">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/4052768/Bat2x100_28.mp3" title="#28 Burstio, Prisma e Instaflash Pro">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#28 Burstio, Prisma e Instaflash Pro</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1585">
		<a href="#" data-media="http://www.ivoox.com/02x02-kde-android_mf_12171095_feed_1.mp3" title="02x02 KDE en Android">
			<span class="isplaying"></span>
			<span class="logo podcastdekdeespaña"></span>
			<span class="podcast">Podcast de KDE España</span>
			<span class="track">02x02 KDE en Android</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1586">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/272915490-ricardo-garc-a-34-episodio65.mp3" title="¿Materia oscura o materia perdida? [Ep.65]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">¿Materia oscura o materia perdida? [Ep.65]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1587">
		<a href="#" data-media="http://www.ivoox.com/02x01-plasma-mobile_mf_12170139_feed_1.mp3" title="02x01 Plasma Mobile">
			<span class="isplaying"></span>
			<span class="logo podcastdekdeespaña"></span>
			<span class="podcast">Podcast de KDE España</span>
			<span class="track">02x01 Plasma Mobile</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1588">
		<a href="#" data-media="http://www.ivoox.com/internet-no-es-respuesta-episodio-12_mf_12167912_feed_1.mp3" title="Internet no es la respuesta | Episodio 12">
			<span class="isplaying"></span>
			<span class="logo repúblicaweb"></span>
			<span class="podcast">República Web</span>
			<span class="track">Internet no es la respuesta | Episodio 12</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1589">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/4052769/Bat2x100_27.mp3" title="#27 Más sobre Parking Door">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#27 Más sobre Parking Door</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1590">
		<a href="#" data-media="http://feedproxy.google.com/~r/WecodesignPodcast/~5/4tyG7l1je_s/WeCodeSign%20Podcast.%20Episodio%201x05%20-%20UX%20y%20UI.mp3" title="5 - UX y UI">
			<span class="isplaying"></span>
			<span class="logo wecodesignpodcast"></span>
			<span class="podcast">WeCodeSign Podcast</span>
			<span class="track">5 - UX y UI</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1591">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/4052770/Bat2x100_26.mp3" title="#26 Amazon Cloud Drive">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#26 Amazon Cloud Drive</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1592">
		<a href="#" data-media="http://www.ivoox.com/influencia-del-color-diseno-web_mf_12121937_feed_1.mp3" title="La influencia del color en el diseño web | Episodio 11">
			<span class="isplaying"></span>
			<span class="logo repúblicaweb"></span>
			<span class="podcast">República Web</span>
			<span class="track">La influencia del color en el diseño web | Episodio 11</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1593">
		<a href="#" data-media="http://tracking.feedpress.it/link/14730/7427587/CN_Programa_011.mp3" title="#CN011 – Manuel Jordán, Synology Product Manager para España">
			<span class="isplaying"></span>
			<span class="logo culturanas"></span>
			<span class="podcast">Cultura NAS</span>
			<span class="track">#CN011 – Manuel Jordán, Synology Product Manager para España</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1594">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/4052771/Bat2x100_25.mp3" title="#25 Multimedia Para Mayores Y PlexPy">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#25 Multimedia Para Mayores Y PlexPy</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1595">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/271849399-ricardo-garc-a-34-episodio64.mp3" title="Simular universos para entender la energía oscura [Ep.64]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Simular universos para entender la energía oscura [Ep.64]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1596">
		<a href="#" data-media="http://www.ivoox.com/003-entrevista-a-javier-cristobal-acrjstobal_mf_12088444_feed_1.mp3" title="003 - Entrevista a Javier Cristobal @crjstobal">
			<span class="isplaying"></span>
			<span class="logo aprendiendogtdpodcastproductividad"></span>
			<span class="podcast">Aprendiendo GTD podcast productividad</span>
			<span class="track">003 - Entrevista a Javier Cristobal @crjstobal</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1597">
		<a href="#" data-media="http://www.ivoox.com/01-antecedentes_mf_12085902_feed_1.mp3" title="#01 Antecedentes">
			<span class="isplaying"></span>
			<span class="logo podcastlinux"></span>
			<span class="podcast">Podcast Linux</span>
			<span class="track">#01 Antecedentes</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1598">
		<a href="#" data-media="http://www.ivoox.com/secreto-para-conseguir-exito-la_mf_12070170_feed_1.mp3" title="El secreto para conseguir el éxito en la web | Episodio 10">
			<span class="isplaying"></span>
			<span class="logo repúblicaweb"></span>
			<span class="podcast">República Web</span>
			<span class="track">El secreto para conseguir el éxito en la web | Episodio 10</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1599">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/4052772/Bat2x100_24.mp3" title="#24 KickStarter –  LightPack2 – Macnificos y podcasts">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#24 KickStarter –  LightPack2 – Macnificos y podcasts</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1600">
		<a href="#" data-media="http://www.ivoox.com/00-promo-podcast-linux_mf_12048502_feed_1.mp3" title="#00 Promo Podcast Linux">
			<span class="isplaying"></span>
			<span class="logo podcastlinux"></span>
			<span class="podcast">Podcast Linux</span>
			<span class="track">#00 Promo Podcast Linux</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1601">
		<a href="#" data-media="http://www.ivoox.com/00-promo-podcast-linux_mf_13383411_feed_1.mp3" title="#00 Promo Podcast Linux">
			<span class="isplaying"></span>
			<span class="logo podcastlinux"></span>
			<span class="podcast">Podcast Linux</span>
			<span class="track">#00 Promo Podcast Linux</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1602">
		<a href="#" data-media="http://api.spreaker.com/download/episode/8869489/podcast86.mp3" title="86. Sensor Kinect, inteligencia artificial al alcance de todos">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">86. Sensor Kinect, inteligencia artificial al alcance de todos</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1603">
		<a href="#" data-media="http://www.ivoox.com/video-online-se-apodera-web_mf_12042652_feed_1.mp3" title="El vídeo online se apodera de la web | Episodio 9">
			<span class="isplaying"></span>
			<span class="logo repúblicaweb"></span>
			<span class="podcast">República Web</span>
			<span class="track">El vídeo online se apodera de la web | Episodio 9</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1604">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/4052773/Bat2x100_23.mp3" title="#23 Mi primera semana con el iPad mini">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#23 Mi primera semana con el iPad mini</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1605">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/270944261-ricardo-garc-a-34-episodio63.mp3" title="Atmósfera Solar y medición distancias [Ep.63]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Atmósfera Solar y medición distancias [Ep.63]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1606">
		<a href="#" data-media="http://www.ivoox.com/jovenes-hablan-sobre-redes-sociales-y_mf_12007264_feed_1.mp3" title="Las jóvenes hablan sobre las redes sociales y el uso de internet | Episodio 8">
			<span class="isplaying"></span>
			<span class="logo repúblicaweb"></span>
			<span class="podcast">República Web</span>
			<span class="track">Las jóvenes hablan sobre las redes sociales y el uso de internet | Episodio 8</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1607">
		<a href="#" data-media="http://podcast.edyo.es/podcast/edyo-17.mp3" title="Edyo 17 - ChatOps">
			<span class="isplaying"></span>
			<span class="logo entredevyopspodcast"></span>
			<span class="podcast">EntreDevYOps Podcast</span>
			<span class="track">Edyo 17 - ChatOps</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1608">
		<a href="#" data-media="http://feedproxy.google.com/~r/WecodesignPodcast/~5/B050J0BBd74/We%20Code%20Sign%20Podcast.%20Episodio%201x04%20-%20SEO%20y%20SEM.mp3" title="4 - SEO y SEM">
			<span class="isplaying"></span>
			<span class="logo wecodesignpodcast"></span>
			<span class="podcast">WeCodeSign Podcast</span>
			<span class="track">4 - SEO y SEM</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1609">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/4052774/Bat2x100_22.mp3" title="#22 Tulotero y CloudConverter">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#22 Tulotero y CloudConverter</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1610">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/4052775/Bat2x100_21.mp3" title="#21 Nuevo Router Movistar">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#21 Nuevo Router Movistar</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1611">
		<a href="#" data-media="http://api.spreaker.com/download/episode/8810866/podcast85.mp3" title="85. Trabajar de programador, las claves">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">85. Trabajar de programador, las claves</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1612">
		<a href="#" data-media="http://www.ivoox.com/podcasts-son-cutres-eso-es-muy_mf_11947433_feed_1.mp3" title="Los podcasts son cutres y eso es muy bueno para la web | Episodio 7">
			<span class="isplaying"></span>
			<span class="logo repúblicaweb"></span>
			<span class="podcast">República Web</span>
			<span class="track">Los podcasts son cutres y eso es muy bueno para la web | Episodio 7</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1613">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/4052776/Bat2x100_20.mp3" title="#20 IndieGoGo & KickStarter">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#20 IndieGoGo & KickStarter</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1614">
		<a href="#" data-media="http://tracking.feedpress.it/link/14730/3651015/Programa_010.mp3" title="#CN010 – Mac & NAS con Carlos Burges">
			<span class="isplaying"></span>
			<span class="logo culturanas"></span>
			<span class="podcast">Cultura NAS</span>
			<span class="track">#CN010 – Mac & NAS con Carlos Burges</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1615">
		<a href="#" data-media="http://www.ivoox.com/retos-oportunidades-del-comercio-electronico-para-pymes_mf_11912845_feed_1.mp3" title="Retos y oportunidades del comercio electrónico para PYMES | Episodio 6">
			<span class="isplaying"></span>
			<span class="logo repúblicaweb"></span>
			<span class="podcast">República Web</span>
			<span class="track">Retos y oportunidades del comercio electrónico para PYMES | Episodio 6</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1616">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/4052777/Bat2x100_19.mp3" title="#19 File Manager Pro">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#19 File Manager Pro</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1617">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/4052778/Bat2x100_18.mp3" title="#18 Gestión De Tareas">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#18 Gestión De Tareas</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1618">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/268949201-ricardo-garc-a-34-episodio62.mp3" title="¿Cómo llegar al conocimiento astronómico? [Ep.62]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">¿Cómo llegar al conocimiento astronómico? [Ep.62]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1619">
		<a href="#" data-media="http://api.spreaker.com/download/episode/8756170/podcast84.mp3" title="84. Creación de Software, así lo hago yo">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">84. Creación de Software, así lo hago yo</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1620">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/4052779/Bat2x100_17.mp3" title="#17 WWDC">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#17 WWDC</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1621">
		<a href="#" data-media="http://www.ivoox.com/002-que-es-gtd_mf_11864093_feed_1.mp3" title="002 - ¿Qué es el GTD?">
			<span class="isplaying"></span>
			<span class="logo aprendiendogtdpodcastproductividad"></span>
			<span class="podcast">Aprendiendo GTD podcast productividad</span>
			<span class="track">002 - ¿Qué es el GTD?</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1622">
		<a href="#" data-media="http://www.ivoox.com/comercio-electronico-wordpress-a-traves-woocommerce_mf_11856333_feed_1.mp3" title="Comercio electrónico con WordPress a través de WooCommerce | Episodio 5">
			<span class="isplaying"></span>
			<span class="logo repúblicaweb"></span>
			<span class="podcast">República Web</span>
			<span class="track">Comercio electrónico con WordPress a través de WooCommerce | Episodio 5</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1623">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/4052780/Bat2x100_16.mp3" title="#16 WeSmartPark">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#16 WeSmartPark</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1624">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/4052781/Bat2x100_15.mp3" title="#15 ParkingDoor & Montar Unidades NAS">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#15 ParkingDoor & Montar Unidades NAS</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1625">
		<a href="#" data-media="http://feedproxy.google.com/~r/WecodesignPodcast/~5/etCnL5uKZ8E/WeCodeSign%20Podcast.%20-%20Episodio%201x03%20-%20Formacio%CC%81n%20online.mp3" title="3 - Formación online">
			<span class="isplaying"></span>
			<span class="logo wecodesignpodcast"></span>
			<span class="podcast">WeCodeSign Podcast</span>
			<span class="track">3 - Formación online</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1626">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/4052782/Bat2x100_14.mp3" title="#14 Más Hazel !">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#14 Más Hazel !</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1627">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/4052783/Bat2x100_13.mp3" title="#13 Soporte Targus">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#13 Soporte Targus</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1628">
		<a href="#" data-media="http://api.spreaker.com/download/episode/8700539/podcast83.mp3" title="83. Escoger el mejor sensor de temperatura para Arduino">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">83. Escoger el mejor sensor de temperatura para Arduino</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1629">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/267692294-ricardo-garc-a-34-episodio61.mp3" title="Buscando a Tatooine y al misterioso planeta nueve [Ep.61]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Buscando a Tatooine y al misterioso planeta nueve [Ep.61]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1630">
		<a href="#" data-media="http://www.ivoox.com/estan-muertas-paginas-webs-episodio-4_mf_11777902_feed_1.mp3" title="¿Están muertas las páginas webs? | Episodio 4">
			<span class="isplaying"></span>
			<span class="logo repúblicaweb"></span>
			<span class="podcast">República Web</span>
			<span class="track">¿Están muertas las páginas webs? | Episodio 4</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1631">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/4052784/Bat2x100_12.mp3" title="#12 Wallapop & iPad mini 64 GB">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#12 Wallapop & iPad mini 64 GB</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1632">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/4052785/Bat2x100_11.mp3" title="#11 Interact (IOS)">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#11 Interact (IOS)</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1633">
		<a href="#" data-media="http://tracking.feedpress.it/link/14730/7427588/Programa_009.mp3" title="#CN009 – Todo sobre caché SSD en tu NAS">
			<span class="isplaying"></span>
			<span class="logo culturanas"></span>
			<span class="podcast">Cultura NAS</span>
			<span class="track">#CN009 – Todo sobre caché SSD en tu NAS</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1634">
		<a href="#" data-media="http://api.spreaker.com/download/episode/8662825/sorteo_campus.mp3" title="Sorteo del Arduino MKR1000 y novedades">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">Sorteo del Arduino MKR1000 y novedades</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1635">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/4052786/Bat2x100_10.mp3" title="#10 Dropcopy y Copied">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#10 Dropcopy y Copied</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1636">
		<a href="#" data-media="http://www.ivoox.com/consejos-para-tu-empresa-este-redes_mf_11711345_feed_1.mp3" title="Consejos para que tu empresa esté en redes sociales | Episodio 3">
			<span class="isplaying"></span>
			<span class="logo repúblicaweb"></span>
			<span class="podcast">República Web</span>
			<span class="track">Consejos para que tu empresa esté en redes sociales | Episodio 3</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1637">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/4052787/Bat2x100_09.mp3" title="#9 Backup y Redundancia (NAS) Crashplan">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#9 Backup y Redundancia (NAS) Crashplan</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1638">
		<a href="#" data-media="http://api.spreaker.com/download/episode/8642216/podcast82.mp3" title="82. Arduino MKR1000 y el protocolo I2C">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">82. Arduino MKR1000 y el protocolo I2C</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1639">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/4052788/Bat2x100_08.mp3" title="#8 Flujo de trabajo multimedia….Y Hazel !">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#8 Flujo de trabajo multimedia….Y Hazel !</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1640">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/4052789/Bat2x100_07.mp3" title="#7 iMazing y PopClip">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#7 iMazing y PopClip</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1641">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/4052790/Bat2x100_06.mp3" title="#6 Plato combinado (NAS/IOS/MAC OSX)">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#6 Plato combinado (NAS/IOS/MAC OSX)</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1642">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/4052791/Bat2x100_05.mp3" title="#5 Screenshot (MAC OS) y flujo en fotos (NAS)">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#5 Screenshot (MAC OS) y flujo en fotos (NAS)</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1643">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/266415057-ricardo-garc-a-34-episodio60.mp3" title="SKA, ondas gravitacionales y búsqueda de vida inteligente [Ep.60]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">SKA, ondas gravitacionales y búsqueda de vida inteligente [Ep.60]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1644">
		<a href="#" data-media="http://www.ivoox.com/fanboy-podcast-09-gluk-video-esa-gran-desconocida_mf_11677844_feed_1.mp3" title="Fanboy Podcast #09: Gluk Video Esa Gran Desconocida">
			<span class="isplaying"></span>
			<span class="logo retroactivopodcast"></span>
			<span class="podcast">RetroActivo Podcast</span>
			<span class="track">Fanboy Podcast #09: Gluk Video Esa Gran Desconocida</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1645">
		<a href="#" data-media="http://www.ivoox.com/para-mi-web-escojo-plantilla-o-un_mf_11676872_feed_1.mp3" title="¿Para mi web escojo una plantilla o un desarrollo a medida? | Episodio 2">
			<span class="isplaying"></span>
			<span class="logo repúblicaweb"></span>
			<span class="podcast">República Web</span>
			<span class="track">¿Para mi web escojo una plantilla o un desarrollo a medida? | Episodio 2</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1646">
		<a href="#" data-media="http://feedproxy.google.com/~r/WecodesignPodcast/~5/eJE-2eMyuvA/WeCodeSign%20-%20Episodio%201x02-%20Formacio%CC%81n%20de%20la%20universidad%20a%20los%20Bootcamps.mp3" title="2 - Bootcamps con Gonzalo Manrique">
			<span class="isplaying"></span>
			<span class="logo wecodesignpodcast"></span>
			<span class="podcast">WeCodeSign Podcast</span>
			<span class="track">2 - Bootcamps con Gonzalo Manrique</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1647">
		<a href="#" data-media="http://tracking.feedpress.it/link/14730/7427589/Programa_008.mp3" title="#CN008 – Especial preguntas de oyentes">
			<span class="isplaying"></span>
			<span class="logo culturanas"></span>
			<span class="podcast">Cultura NAS</span>
			<span class="track">#CN008 – Especial preguntas de oyentes</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1648">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/265527433-ricardo-garc-a-34-episodio59.mp3" title="El desafío de comunicar ciencia [Ep.59]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">El desafío de comunicar ciencia [Ep.59]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1649">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/4052792/Bat2x100_04.mp3" title="#4 TimePage (IOS)">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#4 TimePage (IOS)</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1650">
		<a href="#" data-media="http://api.spreaker.com/download/episode/8582396/podcast81.mp3" title="81. Visión artificial, OpenCV y Phyton">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">81. Visión artificial, OpenCV y Phyton</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1651">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/4052793/Bat2x100_03.mp3" title="#3 HashPhotos ! (IOS)">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#3 HashPhotos ! (IOS)</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1652">
		<a href="#" data-media="http://www.ivoox.com/mejorar-conversion-pagina-web_mf_11613802_feed_1.mp3" title="Mejorar la conversión de una página web | Episodio 1">
			<span class="isplaying"></span>
			<span class="logo repúblicaweb"></span>
			<span class="podcast">República Web</span>
			<span class="track">Mejorar la conversión de una página web | Episodio 1</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1653">
		<a href="#" data-media="http://tracking.feedpress.it/link/14730/7427590/Programa_007.mp3" title="#CN007 – Los NAS en la educación con Rubén Brenes">
			<span class="isplaying"></span>
			<span class="logo culturanas"></span>
			<span class="podcast">Cultura NAS</span>
			<span class="track">#CN007 – Los NAS en la educación con Rubén Brenes</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1654">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/4052794/Bat2x100_02.mp3" title="#2 Drop Zone 3 & Expandrive & Insync">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#2 Drop Zone 3 & Expandrive & Insync</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1655">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/4052795/Bat2x100_01.mp3" title="#1 Airserver y Remote Buddy">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">#1 Airserver y Remote Buddy</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1656">
		<a href="#" data-media="http://www.ivoox.com/20-cual-es-mejor-reproductor-multimedia-cual-es_mf_11569876_feed_1.mp3" title="20. ¿Cual es el mejor reproductor multimedia?¿Cual es el mejor hardware para Plex o Kodi?">
			<span class="isplaying"></span>
			<span class="logo naserospodcast"></span>
			<span class="podcast">NASeros Podcast</span>
			<span class="track">20. ¿Cual es el mejor reproductor multimedia?¿Cual es el mejor hardware para Plex o Kodi?</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1657">
		<a href="#" data-media="http://www.ivoox.com/lo-me-gustaria-haber-sabido-al-empezar_mf_11558104_feed_1.mp3" title="Lo que me gustaría haber sabido al empezar con internet | Episodio 0">
			<span class="isplaying"></span>
			<span class="logo repúblicaweb"></span>
			<span class="podcast">República Web</span>
			<span class="track">Lo que me gustaría haber sabido al empezar con internet | Episodio 0</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1658">
		<a href="#" data-media="http://tracking.feedpress.it/link/15283/4052796/Bat2x100_00.mp3" title="Hola a tod@s !">
			<span class="isplaying"></span>
			<span class="logo bateria2x100"></span>
			<span class="podcast">Bateria2x100</span>
			<span class="track">Hola a tod@s !</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1659">
		<a href="#" data-media="http://api.spreaker.com/download/episode/8521336/podcast80.mp3" title="80. Processing, el lenguaje para gráficos">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">80. Processing, el lenguaje para gráficos</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1660">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/263804453-ricardo-garc-a-34-episodio58.mp3" title="Introducción a la astronomía amateur [Ep.58]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Introducción a la astronomía amateur [Ep.58]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1661">
		<a href="#" data-media="http://feedproxy.google.com/~r/WecodesignPodcast/~5/fOoftR2lUZ8/WeCodeSign%20Podcast%20-%20Episodio%201x01.mp3" title="1 - Formación clásica con Edu Fierro">
			<span class="isplaying"></span>
			<span class="logo wecodesignpodcast"></span>
			<span class="podcast">WeCodeSign Podcast</span>
			<span class="track">1 - Formación clásica con Edu Fierro</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1662">
		<a href="#" data-media="http://api.spreaker.com/download/episode/8457793/podcast79.mp3" title="79. Pensamiento computacional con Tic and Bot">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">79. Pensamiento computacional con Tic and Bot</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1663">
		<a href="#" data-media="http://www.ivoox.com/001-presentacion-aprendiendo-gtd_mf_11450474_feed_1.mp3" title="001 - Presentación de Aprendiendo GTD">
			<span class="isplaying"></span>
			<span class="logo aprendiendogtdpodcastproductividad"></span>
			<span class="podcast">Aprendiendo GTD podcast productividad</span>
			<span class="track">001 - Presentación de Aprendiendo GTD</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1664">
		<a href="#" data-media="http://tracking.feedpress.it/link/14730/7427591/Programa_006.mp3" title="#CN006 – Hablemos de RADIUS">
			<span class="isplaying"></span>
			<span class="logo culturanas"></span>
			<span class="podcast">Cultura NAS</span>
			<span class="track">#CN006 – Hablemos de RADIUS</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1665">
		<a href="#" data-media="http://api.spreaker.com/download/episode/8395572/podcast78.mp3" title="78. Automatización del hogar con Arduino">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">78. Automatización del hogar con Arduino</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1666">
		<a href="#" data-media="http://api.spreaker.com/download/episode/8389942/promo01.mp3" title="Promo La Tecnología para todos">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">Promo La Tecnología para todos</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1667">
		<a href="#" data-media="http://api.spreaker.com/download/episode/8341197/podcast77.mp3" title="77. Aplicación web con Arduino MKR1000">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">77. Aplicación web con Arduino MKR1000</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1668">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/260727667-ricardo-garc-a-34-episodio57.mp3" title="La violenta muerte de estrellas supermasivas [Ep.57]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">La violenta muerte de estrellas supermasivas [Ep.57]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1669">
		<a href="#" data-media="http://www.ivoox.com/charla-flisol-2016-linux-who-gabriel-desimone_mf_11285768_feed_1.mp3" title="[Charla FLISOL 2016] Linux who? - Gabriel Desimone">
			<span class="isplaying"></span>
			<span class="logo neositelinuxpodcast"></span>
			<span class="podcast">NeoSiteLinux Podcast</span>
			<span class="track">[Charla FLISOL 2016] Linux who? - Gabriel Desimone</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1670">
		<a href="#" data-media="http://www.ivoox.com/charla-flisol-2016-vigilancia-electronica-christian-maran_mf_11285705_feed_1.mp3" title="[Charla FLISOL 2016] Vigilancia electronica - Christian Maran">
			<span class="isplaying"></span>
			<span class="logo neositelinuxpodcast"></span>
			<span class="podcast">NeoSiteLinux Podcast</span>
			<span class="track">[Charla FLISOL 2016] Vigilancia electronica - Christian Maran</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1671">
		<a href="#" data-media="http://www.ivoox.com/charla-flisol-2016-ransomware-la-quintaesencia-del-formato_mf_11285588_feed_1.mp3" title="[Charla FLISOL 2016] Ransomware: La quintaesencia del formato propietario - Carlos Pantelides">
			<span class="isplaying"></span>
			<span class="logo neositelinuxpodcast"></span>
			<span class="podcast">NeoSiteLinux Podcast</span>
			<span class="track">[Charla FLISOL 2016] Ransomware: La quintaesencia del formato propietario - Carlos Pantelides</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1672">
		<a href="#" data-media="http://tracking.feedpress.it/link/14730/7427592/Programa_005.mp3" title="#CN005 – Tu Web en Tu servidor NAS">
			<span class="isplaying"></span>
			<span class="logo culturanas"></span>
			<span class="podcast">Cultura NAS</span>
			<span class="track">#CN005 – Tu Web en Tu servidor NAS</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1673">
		<a href="#" data-media="http://api.spreaker.com/download/episode/8285708/podcast76.mp3" title="76. Arduino MKR1000, llega la revolución del IoT">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">76. Arduino MKR1000, llega la revolución del IoT</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1674">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/259254568-ricardo-garc-a-34-episodio56.mp3" title="Agujeros negros supermasivos en galaxias lejanas [Ep.56]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Agujeros negros supermasivos en galaxias lejanas [Ep.56]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1675">
		<a href="#" data-media="http://api.spreaker.com/download/episode/8231670/podcast75.mp3" title="75. Arduino Day y el protocolo de comunicaciones Firmata">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">75. Arduino Day y el protocolo de comunicaciones Firmata</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1676">
		<a href="#" data-media="http://tracking.feedpress.it/link/14730/7427593/Programa_004.mp3" title="#CN004 – Lo virtual si es privado… mejor!">
			<span class="isplaying"></span>
			<span class="logo culturanas"></span>
			<span class="podcast">Cultura NAS</span>
			<span class="track">#CN004 – Lo virtual si es privado… mejor!</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1677">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/257333861-ricardo-garc-a-34-episodio55.mp3" title="Desde el gran atractor hasta los universos burbujas y más [Ep.55]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Desde el gran atractor hasta los universos burbujas y más [Ep.55]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1678">
		<a href="#" data-media="http://www.ivoox.com/19-hablemos-seguridad-informatica_mf_11041040_feed_1.mp3" title="19. Hablemos de seguridad informática">
			<span class="isplaying"></span>
			<span class="logo naserospodcast"></span>
			<span class="podcast">NASeros Podcast</span>
			<span class="track">19. Hablemos de seguridad informática</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1679">
		<a href="#" data-media="http://api.spreaker.com/download/episode/8172535/podcast74.mp3" title="74. Programación y educación">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">74. Programación y educación</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1680">
		<a href="#" data-media="http://www.ivoox.com/18-prepara-router-nas-casero-gran-potencia_mf_11001326_feed_1.mp3" title="18. Prepara un Router-NAS casero de gran potencia">
			<span class="isplaying"></span>
			<span class="logo naserospodcast"></span>
			<span class="podcast">NASeros Podcast</span>
			<span class="track">18. Prepara un Router-NAS casero de gran potencia</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1681">
		<a href="#" data-media="http://www.ivoox.com/retroactivo-podcast-57-kazuhiko-nishi-padre-del-sistema_mf_10997757_feed_1.mp3" title="RetroActivo Podcast #57: Kazuhiko Nishi (padre del sistema MSX)">
			<span class="isplaying"></span>
			<span class="logo retroactivopodcast"></span>
			<span class="podcast">RetroActivo Podcast</span>
			<span class="track">RetroActivo Podcast #57: Kazuhiko Nishi (padre del sistema MSX)</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1682">
		<a href="#" data-media="http://www.ivoox.com/retroactivo-podcast-56-next-siguiente-trabajo-de_mf_10997623_feed_1.mp3" title="RetroActivo Podcast #56: NeXT, el siguiente trabajo de Steve Jobs">
			<span class="isplaying"></span>
			<span class="logo retroactivopodcast"></span>
			<span class="podcast">RetroActivo Podcast</span>
			<span class="track">RetroActivo Podcast #56: NeXT, el siguiente trabajo de Steve Jobs</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1683">
		<a href="#" data-media="http://www.ivoox.com/retroactivo-podcast-55-la-historia-super_mf_10992630_feed_1.mp3" title="RetroActivo Podcast #55: La historia de la Super Nintendo">
			<span class="isplaying"></span>
			<span class="logo retroactivopodcast"></span>
			<span class="podcast">RetroActivo Podcast</span>
			<span class="track">RetroActivo Podcast #55: La historia de la Super Nintendo</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1684">
		<a href="#" data-media="http://www.ivoox.com/retroactivo-podcast-54-ada-lovelace-primera-persona-considerada_mf_10992553_feed_1.mp3" title="RetroActivo Podcast #54: Ada Lovelace, primera persona considerada programador">
			<span class="isplaying"></span>
			<span class="logo retroactivopodcast"></span>
			<span class="podcast">RetroActivo Podcast</span>
			<span class="track">RetroActivo Podcast #54: Ada Lovelace, primera persona considerada programador</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1685">
		<a href="#" data-media="http://www.ivoox.com/17-nuevos-productos-cebit2016-dudas-oyentes_mf_10952034_feed_1.mp3" title="17. Nuevos productos, CeBIT2016 y dudas de oyentes">
			<span class="isplaying"></span>
			<span class="logo naserospodcast"></span>
			<span class="podcast">NASeros Podcast</span>
			<span class="track">17. Nuevos productos, CeBIT2016 y dudas de oyentes</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1686">
		<a href="#" data-media="http://api.spreaker.com/download/episode/8117605/podcast73.mp3" title="73. Motor paso a paso con Arduino">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">73. Motor paso a paso con Arduino</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1687">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/255062660-ricardo-garc-a-34-episodio54.mp3" title="Cuásares, agujeros negros gigantes que brillan y dilatación temporal [Ep.54]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Cuásares, agujeros negros gigantes que brillan y dilatación temporal [Ep.54]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1688">
		<a href="#" data-media="http://podcast.edyo.es/podcast/edyo-16.mp3" title="Edyo 16 - Noticias, Bluemix y Github">
			<span class="isplaying"></span>
			<span class="logo entredevyopspodcast"></span>
			<span class="podcast">EntreDevYOps Podcast</span>
			<span class="track">Edyo 16 - Noticias, Bluemix y Github</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1689">
		<a href="#" data-media="http://www.ivoox.com/16-multimedia-video-4k-nueva-colaboracion-con_mf_10878639_feed_1.mp3" title="16. Multimedia y vídeo 4K. Nueva colaboración con Applelianos.">
			<span class="isplaying"></span>
			<span class="logo naserospodcast"></span>
			<span class="podcast">NASeros Podcast</span>
			<span class="track">16. Multimedia y vídeo 4K. Nueva colaboración con Applelianos.</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1690">
		<a href="#" data-media="http://api.spreaker.com/download/episode/8060680/podcast72.mp3" title="72. Aniversario de La tecnología para todos">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">72. Aniversario de La tecnología para todos</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1691">
		<a href="#" data-media="http://www.ivoox.com/neositelinux-podcast-1-ano-2016_mf_10873941_feed_1.mp3" title="NeoSiteLinux Podcast #1 - Año 2016">
			<span class="isplaying"></span>
			<span class="logo neositelinuxpodcast"></span>
			<span class="podcast">NeoSiteLinux Podcast</span>
			<span class="track">NeoSiteLinux Podcast #1 - Año 2016</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1692">
		<a href="#" data-media="http://www.ivoox.com/fanboy-podcast-08-sega-model-2_mf_10824386_feed_1.mp3" title="Fanboy Podcast #08: Sega Model 2">
			<span class="isplaying"></span>
			<span class="logo retroactivopodcast"></span>
			<span class="podcast">RetroActivo Podcast</span>
			<span class="track">Fanboy Podcast #08: Sega Model 2</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1693">
		<a href="#" data-media="http://api.spreaker.com/download/episode/7998543/podcast71.mp3" title="71. Financia tu proyecto tecnológico con Crowdfunding">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">71. Financia tu proyecto tecnológico con Crowdfunding</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1694">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/251439767-ricardo-garc-a-34-episodio53.mp3" title="El telescopio más grande del planeta, ELT [Ep.53]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">El telescopio más grande del planeta, ELT [Ep.53]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1695">
		<a href="#" data-media="http://tracking.feedpress.it/link/14730/7427594/Programa_003.mp3" title="#CN003 – Torrentes de pasión">
			<span class="isplaying"></span>
			<span class="logo culturanas"></span>
			<span class="podcast">Cultura NAS</span>
			<span class="track">#CN003 – Torrentes de pasión</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1696">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/250857522-ricardo-garc-a-34-episodio52.mp3" title="¿Qué le pasará a la Tierra cuando se acabe el Sol? [Ep.52]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">¿Qué le pasará a la Tierra cuando se acabe el Sol? [Ep.52]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1697">
		<a href="#" data-media="http://www.ivoox.com/15-que-dispositivo-o-reproductor-streaming-elijo_mf_10710919_feed_1.mp3" title="15. ¿Qué dispositivo o reproductor de streaming elijo?">
			<span class="isplaying"></span>
			<span class="logo naserospodcast"></span>
			<span class="podcast">NASeros Podcast</span>
			<span class="track">15. ¿Qué dispositivo o reproductor de streaming elijo?</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1698">
		<a href="#" data-media="http://api.spreaker.com/download/episode/7942545/podcast70.mp3" title="70. Herramientas para Makers, conviértete en un profesional">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">70. Herramientas para Makers, conviértete en un profesional</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1699">
		<a href="#" data-media="http://api.spreaker.com/download/episode/7891875/podcast69.mp3" title="69. Aumentar salidas digitales en Arduino">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">69. Aumentar salidas digitales en Arduino</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1700">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/249185058-ricardo-garc-a-34-episodio51.mp3" title="ALMA, grandes descubrimientos, historia y medición de distancias cósmicas [Ep.51]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">ALMA, grandes descubrimientos, historia y medición de distancias cósmicas [Ep.51]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1701">
		<a href="#" data-media="http://tracking.feedpress.it/link/14730/7427595/Programa_002.mp3" title="#CN002 – Copiándonos">
			<span class="isplaying"></span>
			<span class="logo culturanas"></span>
			<span class="podcast">Cultura NAS</span>
			<span class="track">#CN002 – Copiándonos</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1702">
		<a href="#" data-media="http://api.spreaker.com/download/episode/7840768/podcast68.mp3" title="68. Arduino basado en la web">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">68. Arduino basado en la web</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1703">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/248066918-ricardo-garc-a-34-episodio50.mp3" title="Computación, divulgación, dibujos aliens y superluna [Ep.50]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Computación, divulgación, dibujos aliens y superluna [Ep.50]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1704">
		<a href="#" data-media="http://api.spreaker.com/download/episode/7790295/podcast67.mp3" title="67. Big data y visión artificial">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">67. Big data y visión artificial</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1705">
		<a href="#" data-media="http://tracking.feedpress.it/link/14730/7427596/Programa_001.mp3" title="#CN001 – Pon un Servidor NAS en tu vida">
			<span class="isplaying"></span>
			<span class="logo culturanas"></span>
			<span class="podcast">Cultura NAS</span>
			<span class="track">#CN001 – Pon un Servidor NAS en tu vida</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1706">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/246630974-ricardo-garc-a-34-episodio49.mp3" title="Instrumentación astronómica made in Chile [Ep.49]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Instrumentación astronómica made in Chile [Ep.49]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1707">
		<a href="#" data-media="http://api.spreaker.com/download/episode/7738563/podcast66.mp3" title="66. La vida del microcontrolador">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">66. La vida del microcontrolador</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1708">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/245593855-ricardo-garc-a-34-episodio48.mp3" title="Del vacío a los 5 pilares fundamentales de la física [Ep.48]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Del vacío a los 5 pilares fundamentales de la física [Ep.48]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1709">
		<a href="#" data-media="http://api.spreaker.com/download/episode/7686379/podcast65.mp3" title="65. Sistemas de comunicación inalámbricas">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">65. Sistemas de comunicación inalámbricas</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1710">
		<a href="#" data-media="http://tracking.feedpress.it/link/14730/7427597/Programa_000.mp3" title="#CN000 – Presentación del podcast Cultura NAS">
			<span class="isplaying"></span>
			<span class="logo culturanas"></span>
			<span class="podcast">Cultura NAS</span>
			<span class="track">#CN000 – Presentación del podcast Cultura NAS</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1711">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/244347691-ricardo-garc-a-34-episodio47.mp3" title="Expansión Acelerada, Podcasting y nuevo canal de Youtube Astrovlog [Ep.47]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Expansión Acelerada, Podcasting y nuevo canal de Youtube Astrovlog [Ep.47]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1712">
		<a href="#" data-media="http://api.spreaker.com/download/episode/7633821/podcast64.mp3" title="64. Proyectos curiosos con Arduino">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">64. Proyectos curiosos con Arduino</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1713">
		<a href="#" data-media="http://api.spreaker.com/download/episode/7583852/podcast63.mp3" title="63. Programación visual con Arduino, Scratch y Snap!">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">63. Programación visual con Arduino, Scratch y Snap!</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1714">
		<a href="#" data-media="http://api.spreaker.com/download/episode/7535262/podcast62.mp3" title="62. Domótica y edificios inteligentes">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">62. Domótica y edificios inteligentes</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1715">
		<a href="#" data-media="http://www.podtrac.com/pts/redirect.mp3/www.wedevelopers.com/podcast/wedevelopers044.mp3" title="We.Developers 044 – Trabajo en Remoto">
			<span class="isplaying"></span>
			<span class="logo wedevelopers"></span>
			<span class="podcast">We.Developers</span>
			<span class="track">We.Developers 044 – Trabajo en Remoto</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1716">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/239754371-ricardo-garc-a-34-episodio46.mp3" title="Universo no térmico, agujeros negros y supernovas [Ep.46]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Universo no térmico, agujeros negros y supernovas [Ep.46]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1717">
		<a href="#" data-media="http://api.spreaker.com/download/episode/7447958/podcast61.mp3" title="61. Arduino y los dispositivos del IoT">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">61. Arduino y los dispositivos del IoT</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1718">
		<a href="#" data-media="http://www.podtrac.com/pts/redirect.mp3/www.wedevelopers.com/podcast/wedevelopers043.mp3" title="We.Developers 043 – PHP">
			<span class="isplaying"></span>
			<span class="logo wedevelopers"></span>
			<span class="podcast">We.Developers</span>
			<span class="track">We.Developers 043 – PHP</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1719">
		<a href="#" data-media="http://api.spreaker.com/download/episode/7408228/podcast60.mp3" title="60. Raspberry Pi en modo didáctico con Pitando Podcast">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">60. Raspberry Pi en modo didáctico con Pitando Podcast</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1720">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/238185292-ricardo-garc-a-34-episodio45.mp3" title="Explosiones y actividad solar, Amenaza para la Tierra [Ep.45]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Explosiones y actividad solar, Amenaza para la Tierra [Ep.45]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1721">
		<a href="#" data-media="http://api.spreaker.com/download/episode/7363692/podcast59.mp3" title="59. Qué son los servicios web">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">59. Qué son los servicios web</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1722">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/237447935-ricardo-garc-a-34-episodio44.mp3" title="Astrobiología, buscando vida en mundos lejanos [Ep.44]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Astrobiología, buscando vida en mundos lejanos [Ep.44]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1723">
		<a href="#" data-media="http://podcast.edyo.es/podcast/edyo-15.mp3" title="Edyo 15 - Eventos y noticias de Diciembre">
			<span class="isplaying"></span>
			<span class="logo entredevyopspodcast"></span>
			<span class="podcast">EntreDevYOps Podcast</span>
			<span class="track">Edyo 15 - Eventos y noticias de Diciembre</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1724">
		<a href="#" data-media="http://api.spreaker.com/download/episode/7312952/podcast58.mp3" title="58. Cómo destruir Arduino">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">58. Cómo destruir Arduino</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1725">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/237409966-ricardo-garc-a-34-episodio43.mp3" title="Estrellas de neutrones y magnéticas, Astrofísica al límite [Ep.43]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Estrellas de neutrones y magnéticas, Astrofísica al límite [Ep.43]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1726">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/237433248-ricardo-garc-a-34-episodio42.mp3" title="Cúmulos de Galaxias, la clave para entender la Materia Oscura [Ep.42]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Cúmulos de Galaxias, la clave para entender la Materia Oscura [Ep.42]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1727">
		<a href="#" data-media="http://api.spreaker.com/download/episode/7267120/podcast57.mp3" title="57. Kit de supervivencia Arduino">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">57. Kit de supervivencia Arduino</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1728">
		<a href="#" data-media="http://api.spreaker.com/download/episode/7219757/podcast56.mp3" title="56. De la idea al producto, fases de creación del software">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">56. De la idea al producto, fases de creación del software</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1729">
		<a href="#" data-media="http://api.spreaker.com/download/episode/7172296/podcast55.mp3" title="55. Isabel Cabezas, Evangelista Técnico de Microsoft">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">55. Isabel Cabezas, Evangelista Técnico de Microsoft</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1730">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/237445132-ricardo-garc-a-34-episodio41.mp3" title="Enanas Marrones ¿estrellas fallidas o superplanetas? [Ep.41]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Enanas Marrones ¿estrellas fallidas o superplanetas? [Ep.41]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1731">
		<a href="#" data-media="http://api.spreaker.com/download/episode/7115805/podcast54.mp3" title="54. Web, móvil y desktop, un IDE para gobernarlos a todos">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">54. Web, móvil y desktop, un IDE para gobernarlos a todos</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1732">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/237450447-ricardo-garc-a-34-episodio40.mp3" title="Astronomía y Ciencia Ficción, haciendo las grandes preguntas [Ep.40]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Astronomía y Ciencia Ficción, haciendo las grandes preguntas [Ep.40]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1733">
		<a href="#" data-media="http://api.spreaker.com/download/episode/7029030/podcast53.mp3" title="53. Resultados de la encuesta y ganador del sorteo">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">53. Resultados de la encuesta y ganador del sorteo</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1734">
		<a href="#" data-media="http://api.spreaker.com/download/episode/6913772/podcast52.mp3" title="52. Bower, gestor de paquetes para el desarrollo web">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">52. Bower, gestor de paquetes para el desarrollo web</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1735">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/237455739-ricardo-garc-a-34-episodio39.mp3" title="Materia oscura y Galaxias en la Historia del Universo [Ep.39]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Materia oscura y Galaxias en la Historia del Universo [Ep.39]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1736">
		<a href="#" data-media="http://www.podtrac.com/pts/redirect.mp3/www.wedevelopers.com/podcast/wedevelopers042.mp3" title="We.Developers 042 – Swift">
			<span class="isplaying"></span>
			<span class="logo wedevelopers"></span>
			<span class="podcast">We.Developers</span>
			<span class="track">We.Developers 042 – Swift</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1737">
		<a href="#" data-media="http://api.spreaker.com/download/episode/6871482/podcast51.mp3" title="51. Qué es Bootstrap">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">51. Qué es Bootstrap</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1738">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/237456387-ricardo-garc-a-34-episodio38.mp3" title="Cómo comprar un telescopio y no morir en el intento [Ep.38]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Cómo comprar un telescopio y no morir en el intento [Ep.38]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1739">
		<a href="#" data-media="http://api.spreaker.com/download/episode/6822692/podcast50.mp3" title="50. Sonar con Visual Studio y Arduino">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">50. Sonar con Visual Studio y Arduino</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1740">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/237457020-ricardo-garc-a-34-episodio37.mp3" title="Agujeros negros supermasivos en la historia del universo [Ep.37]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Agujeros negros supermasivos en la historia del universo [Ep.37]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1741">
		<a href="#" data-media="http://www.ivoox.com/01x07-akademy-es-2015_mf_8799280_feed_1.mp3" title="01x07 Akademy-es 2015">
			<span class="isplaying"></span>
			<span class="logo podcastdekdeespaña"></span>
			<span class="podcast">Podcast de KDE España</span>
			<span class="track">01x07 Akademy-es 2015</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1742">
		<a href="#" data-media="http://api.spreaker.com/download/episode/6744906/podcast49.mp3" title="49. Ultrasonidos y servos con Arduino">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">49. Ultrasonidos y servos con Arduino</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1743">
		<a href="#" data-media="http://www.ivoox.com/01x06-aplicaciones-kde_mf_8783145_feed_1.mp3" title="01X06 Aplicaciones KDE">
			<span class="isplaying"></span>
			<span class="logo podcastdekdeespaña"></span>
			<span class="podcast">Podcast de KDE España</span>
			<span class="track">01X06 Aplicaciones KDE</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1744">
		<a href="#" data-media="http://podcast.edyo.es/podcast/edyo-14.mp3" title="Edyo 14 - Eventos, Entrevista post EuroPython y Python San Sebastián">
			<span class="isplaying"></span>
			<span class="logo entredevyopspodcast"></span>
			<span class="podcast">EntreDevYOps Podcast</span>
			<span class="track">Edyo 14 - Eventos, Entrevista post EuroPython y Python San Sebastián</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1745">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/237457337-ricardo-garc-a-34-episodio36.mp3" title="Relatividad, viajes en el tiempo y múltiples dimensiones [Ep.36]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Relatividad, viajes en el tiempo y múltiples dimensiones [Ep.36]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1746">
		<a href="#" data-media="http://www.ivoox.com/01x05-blogs-sobre-kde-software-libre-en_mf_8765003_feed_1.mp3" title="01x05 Blogs sobre KDE y Software Libre en general">
			<span class="isplaying"></span>
			<span class="logo podcastdekdeespaña"></span>
			<span class="podcast">Podcast de KDE España</span>
			<span class="track">01x05 Blogs sobre KDE y Software Libre en general</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1747">
		<a href="#" data-media="http://www.ivoox.com/01x04-como-iniciar-proyectos-kde_mf_8751812_feed_1.mp3" title="01x04 Como iniciar proyectos KDE">
			<span class="isplaying"></span>
			<span class="logo podcastdekdeespaña"></span>
			<span class="podcast">Podcast de KDE España</span>
			<span class="track">01x04 Como iniciar proyectos KDE</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1748">
		<a href="#" data-media="http://www.ivoox.com/01x03-los-eventos-comunidad-kde_mf_8750923_feed_1.mp3" title="01x03 Los eventos de la Comunidad KDE">
			<span class="isplaying"></span>
			<span class="logo podcastdekdeespaña"></span>
			<span class="podcast">Podcast de KDE España</span>
			<span class="track">01x03 Los eventos de la Comunidad KDE</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1749">
		<a href="#" data-media="http://api.spreaker.com/download/episode/6696817/podcast48.mp3" title="48. Sensor de  temperatura en Arduino">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">48. Sensor de  temperatura en Arduino</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1750">
		<a href="#" data-media="http://www.podtrac.com/pts/redirect.mp3/www.wedevelopers.com/podcast/wedevelopers041.mp3" title="We.Developers 041 – Realidad Virtual">
			<span class="isplaying"></span>
			<span class="logo wedevelopers"></span>
			<span class="podcast">We.Developers</span>
			<span class="track">We.Developers 041 – Realidad Virtual</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1751">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/237464941-ricardo-garc-a-34-episodio35.mp3" title="Cuántica, humor científico y la partícula de Dios en el CERN [Ep.35]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Cuántica, humor científico y la partícula de Dios en el CERN [Ep.35]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1752">
		<a href="#" data-media="http://api.spreaker.com/download/episode/6655920/podcast47.mp3" title="47. Raspberry Pi como servidor web">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">47. Raspberry Pi como servidor web</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1753">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/237466197-ricardo-garc-a-34-episodio34.mp3" title="TMT, el desafío de construir un telescopio de 30 metros en Hawaii [Ep.34]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">TMT, el desafío de construir un telescopio de 30 metros en Hawaii [Ep.34]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1754">
		<a href="#" data-media="http://api.spreaker.com/download/episode/6621714/podcast46.mp3" title="46. Experiencias de un programador con D. Freniche">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">46. Experiencias de un programador con D. Freniche</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1755">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/237466061-ricardo-garc-a-34-episodio33.mp3" title="Nueva pieza en el puzzle de la historia del universo [Ep.33]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Nueva pieza en el puzzle de la historia del universo [Ep.33]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1756">
		<a href="#" data-media="http://api.spreaker.com/download/episode/6590148/podcast45.mp3" title="45. Aprender a programar">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">45. Aprender a programar</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1757">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/237466708-ricardo-garc-a-34-episodio32.mp3" title="Preguntas de los oyentes del podcast [Ep.32]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Preguntas de los oyentes del podcast [Ep.32]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1758">
		<a href="#" data-media="http://www.podtrac.com/pts/redirect.mp3/www.wedevelopers.com/podcast/wedevelopers040.mp3" title="We.Developers 040 – Como ser desarrollador (y no morir en el intento)">
			<span class="isplaying"></span>
			<span class="logo wedevelopers"></span>
			<span class="podcast">We.Developers</span>
			<span class="track">We.Developers 040 – Como ser desarrollador (y no morir en el intento)</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1759">
		<a href="#" data-media="http://api.spreaker.com/download/episode/6568642/podcast44.mp3" title="44. Tratamiento de imágenes con JavaScript">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">44. Tratamiento de imágenes con JavaScript</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1760">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/237871524-ricardo-garc-a-34-episodio31.mp3" title="Plasmas cósmicos, tormentas solares y auroras [Ep.31]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Plasmas cósmicos, tormentas solares y auroras [Ep.31]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1761">
		<a href="#" data-media="http://api.spreaker.com/download/episode/9858780/cap19_garantia_asus_parte_ii_mf_7660188_feed_1.mp3" title="cap19 - Garantia ASUS parte II">
			<span class="isplaying"></span>
			<span class="logo podcastdmanuelalonso"></span>
			<span class="podcast">Podcast dmanuelalonso</span>
			<span class="track">cap19 - Garantia ASUS parte II</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1762">
		<a href="#" data-media="http://api.spreaker.com/download/episode/6535240/podcast43.mp3" title="43. Introducción a jQuery (Parte 2)">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">43. Introducción a jQuery (Parte 2)</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1763">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/237872576-ricardo-garc-a-34-episodio30.mp3" title="Cómo funciona la NASA y Telescopios Espaciales [Ep.30]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Cómo funciona la NASA y Telescopios Espaciales [Ep.30]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1764">
		<a href="#" data-media="http://api.spreaker.com/download/episode/6505114/podcast42.mp3" title="42. Introducción a jQuery (parte 1)">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">42. Introducción a jQuery (parte 1)</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1765">
		<a href="#" data-media="http://podcast.edyo.es/podcast/edyo-13.mp3" title="Edyo 13 - Eventos, Noticias y Varios">
			<span class="isplaying"></span>
			<span class="logo entredevyopspodcast"></span>
			<span class="podcast">EntreDevYOps Podcast</span>
			<span class="track">Edyo 13 - Eventos, Noticias y Varios</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1766">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/237874221-ricardo-garc-a-34-episodio29.mp3" title="Colores en las imágenes astronómicas [Ep.29]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Colores en las imágenes astronómicas [Ep.29]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1767">
		<a href="#" data-media="http://api.spreaker.com/download/episode/9858783/cap18_garantia_asus_parte_i_mf_6611177_feed_1.mp3" title="cap18 - Garantia ASUS parte I">
			<span class="isplaying"></span>
			<span class="logo podcastdmanuelalonso"></span>
			<span class="podcast">Podcast dmanuelalonso</span>
			<span class="track">cap18 - Garantia ASUS parte I</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1768">
		<a href="#" data-media="http://api.spreaker.com/download/episode/6477001/podcast41.mp3" title="41. Dudas sobre podcasting">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">41. Dudas sobre podcasting</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1769">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/237874220-ricardo-garc-a-34-episodio28.mp3" title="El inicio del universo con Inflación Cósmica [Ep.28]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">El inicio del universo con Inflación Cósmica [Ep.28]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1770">
		<a href="#" data-media="http://api.spreaker.com/download/episode/6448265/podcast40.mp3" title="40. Raspberry Pi como centro multimedia">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">40. Raspberry Pi como centro multimedia</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1771">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/237873488-ricardo-garc-a-34-episodio27.mp3" title="Galaxias gigantes, universo a gran escala y Materia Oscura [Ep.27]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Galaxias gigantes, universo a gran escala y Materia Oscura [Ep.27]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1772">
		<a href="#" data-media="http://www.ivoox.com/neositelinux-podcast-3-ano-2015-el_mf_5609071_feed_1.mp3" title="NeoSiteLinux Podcast #3 - Año 2015 - El script milagroso y Windows 10">
			<span class="isplaying"></span>
			<span class="logo neositelinuxpodcast"></span>
			<span class="podcast">NeoSiteLinux Podcast</span>
			<span class="track">NeoSiteLinux Podcast #3 - Año 2015 - El script milagroso y Windows 10</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1773">
		<a href="#" data-media="http://api.spreaker.com/download/episode/6422391/podcast39.mp3" title="39. Windows 10 para Raspberry Pi">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">39. Windows 10 para Raspberry Pi</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1774">
		<a href="#" data-media="http://api.spreaker.com/download/episode/9858852/cap_17_xiaomi_mi_note_vs_sistemas_mf_5444409_feed_1.mp3" title="cap 17 - Xiaomi Mi Note vs Sistemas">
			<span class="isplaying"></span>
			<span class="logo podcastdmanuelalonso"></span>
			<span class="podcast">Podcast dmanuelalonso</span>
			<span class="track">cap 17 - Xiaomi Mi Note vs Sistemas</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1775">
		<a href="#" data-media="http://api.spreaker.com/download/episode/6407093/podcast38.mp3" title="38. Visual Studio 2015, bienvenido">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">38. Visual Studio 2015, bienvenido</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1776">
		<a href="#" data-media="http://www.ivoox.com/neositelinux-podcast-2-ano-2015-a_mf_5320133_feed_1.mp3" title="NeoSiteLinux Podcast #2 - Año 2015 - A veces hay que decir No">
			<span class="isplaying"></span>
			<span class="logo neositelinuxpodcast"></span>
			<span class="podcast">NeoSiteLinux Podcast</span>
			<span class="track">NeoSiteLinux Podcast #2 - Año 2015 - A veces hay que decir No</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1777">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/237873842-ricardo-garc-a-34-episodio26.mp3" title="Astropartículas y Materia oscura [Ep.26]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Astropartículas y Materia oscura [Ep.26]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1778">
		<a href="#" data-media="http://api.spreaker.com/download/episode/6390000/podcast37.mp3" title="37. Raspberry Pi como servidor">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">37. Raspberry Pi como servidor</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1779">
		<a href="#" data-media="http://api.spreaker.com/download/episode/6375873/podcast36.mp3" title="36. Cómo elegir el entorno de desarrollo">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">36. Cómo elegir el entorno de desarrollo</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1780">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/237874121-ricardo-garc-a-34-episodio25.mp3" title="Aceleradores de partículas, física nuclear y mecánica cuántica [Ep.25]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Aceleradores de partículas, física nuclear y mecánica cuántica [Ep.25]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1781">
		<a href="#" data-media="http://api.spreaker.com/download/episode/6358147/podcast35.mp3" title="35.Conceptos básicos electrónica Arduino">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">35.Conceptos básicos electrónica Arduino</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1782">
		<a href="#" data-media="http://api.spreaker.com/download/episode/6344443/podcast34.mp3" title="34. Ranking de frameworks de JavaScript">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">34. Ranking de frameworks de JavaScript</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1783">
		<a href="#" data-media="http://www.podtrac.com/pts/redirect.mp3/www.wedevelopers.com/podcast/wedevelopers039.mp3" title="We.Developers 039 – WWDC 2015">
			<span class="isplaying"></span>
			<span class="logo wedevelopers"></span>
			<span class="podcast">We.Developers</span>
			<span class="track">We.Developers 039 – WWDC 2015</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1784">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/241680616-ricardo-garc-a-34-episodio24.mp3" title="El inicio del universo sin un Big Bang [Ep.24]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">El inicio del universo sin un Big Bang [Ep.24]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1785">
		<a href="#" data-media="http://api.spreaker.com/download/episode/6327734/podcast33.mp3" title="33. Tipos de datos básicos en Arduino">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">33. Tipos de datos básicos en Arduino</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1786">
		<a href="#" data-media="http://api.spreaker.com/download/episode/6314258/podcast32.mp3" title="32. Desarrollo web con JavaScript">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">32. Desarrollo web con JavaScript</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1787">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/241680445-ricardo-garc-a-34-episodio23.mp3" title="Las fallas del Modelo Estándar y el Neutrino [Ep.23]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Las fallas del Modelo Estándar y el Neutrino [Ep.23]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1788">
		<a href="#" data-media="http://api.spreaker.com/download/episode/6297337/podcast31.mp3" title="31. API de Arduino">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">31. API de Arduino</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1789">
		<a href="#" data-media="http://api.spreaker.com/download/episode/6283178/capitulo30.mp3" title="30. Introducción a Raspberry Pi">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">30. Introducción a Raspberry Pi</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1790">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/241680213-ricardo-garc-a-34-episodio22.mp3" title="Exploración de Marte, desde Maven a Misiones Tripuladas [Ep.22]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Exploración de Marte, desde Maven a Misiones Tripuladas [Ep.22]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1791">
		<a href="#" data-media="http://api.spreaker.com/download/episode/6265460/capitulo29.mp3" title="29. Desarrollo web con CSS3">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">29. Desarrollo web con CSS3</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1792">
		<a href="#" data-media="http://api.spreaker.com/download/episode/6251180/capitulo28.mp3" title="28. Entorno de desarrollo de Arduino">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">28. Entorno de desarrollo de Arduino</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1793">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/241679854-ricardo-garc-a-34-episodio21.mp3" title="Sexo, Astronomía y Divulgación [Ep.21]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Sexo, Astronomía y Divulgación [Ep.21]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1794">
		<a href="#" data-media="http://api.spreaker.com/download/episode/6233711/capitulo27.mp3" title="27. Desarrollo web con HTML5">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">27. Desarrollo web con HTML5</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1795">
		<a href="#" data-media="http://api.spreaker.com/download/episode/6227289/mi_band_podcast.mp3" title="cap16 -Xiaomi Mi Band con @Nosoyunmuggle">
			<span class="isplaying"></span>
			<span class="logo podcastdmanuelalonso"></span>
			<span class="podcast">Podcast dmanuelalonso</span>
			<span class="track">cap16 -Xiaomi Mi Band con @Nosoyunmuggle</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1796">
		<a href="#" data-media="http://api.spreaker.com/download/episode/9245088/210551524_codeontherocks_code_on_the_rocks_06_london_edition.mp3" title="S01E06 London Edition">
			<span class="isplaying"></span>
			<span class="logo codeontherocks"></span>
			<span class="podcast">Code on the rocks</span>
			<span class="track">S01E06 London Edition</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1797">
		<a href="#" data-media="http://api.spreaker.com/download/episode/6218231/capitulo26.mp3" title="26. Arduino entradas y salidas">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">26. Arduino entradas y salidas</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1798">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/241680160-ricardo-garc-a-34-episodio20.mp3" title="OVNIS ¿naves extraterrestres o fenómenos anómalos? [Ep.20]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">OVNIS ¿naves extraterrestres o fenómenos anómalos? [Ep.20]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1799">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/241679380-ricardo-garc-a-34-episodio19.mp3" title="Estudiando el nacimiento de Estrellas [Ep.19]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Estudiando el nacimiento de Estrellas [Ep.19]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1800">
		<a href="#" data-media="http://api.spreaker.com/download/episode/6199870/capitulo25.mp3" title="25. Proyecto Arduino y desarrollo web">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">25. Proyecto Arduino y desarrollo web</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1801">
		<a href="#" data-media="http://api.spreaker.com/download/episode/6185070/podcast24.mp3" title="24. Ciberseguridad con Josep Albors de E">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">24. Ciberseguridad con Josep Albors de E</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1802">
		<a href="#" data-media="http://api.spreaker.com/download/episode/6166362/capitulo23.mp3" title="23. Charla con El Guille parte 2">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">23. Charla con El Guille parte 2</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1803">
		<a href="#" data-media="http://api.spreaker.com/download/episode/6151569/capitulo22.mp3" title="22. Charla con El Guille parte 1">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">22. Charla con El Guille parte 1</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1804">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/241679578-ricardo-garc-a-34-episodio18.mp3" title="Exoplanetas ¿Estamos solos en el universo? [Ep.18]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Exoplanetas ¿Estamos solos en el universo? [Ep.18]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1805">
		<a href="#" data-media="http://api.spreaker.com/download/episode/6131735/podcast21.mp3" title="21. Introducción al Arduino">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">21. Introducción al Arduino</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1806">
		<a href="#" data-media="http://api.spreaker.com/download/episode/6117666/capitulo20.mp3" title="20. Crear aplicaciones con WPF">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">20. Crear aplicaciones con WPF</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1807">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/241679153-ricardo-garc-a-34-episodio17.mp3" title="Pulsares y Estrellas de Neutrones [Ep.17]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Pulsares y Estrellas de Neutrones [Ep.17]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1808">
		<a href="#" data-media="http://api.spreaker.com/download/episode/6099522/capitulo19.mp3" title="19. Patrón Modelo Vista Controlador">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">19. Patrón Modelo Vista Controlador</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1809">
		<a href="#" data-media="http://api.spreaker.com/download/episode/6090959/capitulo18.mp3" title="18. Realidad aumentada">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">18. Realidad aumentada</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1810">
		<a href="#" data-media="http://www.podtrac.com/pts/redirect.mp3/www.wedevelopers.com/podcast/wedevelopers038.mp3" title="We.Developers 038 – JavaScript ES6">
			<span class="isplaying"></span>
			<span class="logo wedevelopers"></span>
			<span class="podcast">We.Developers</span>
			<span class="track">We.Developers 038 – JavaScript ES6</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1811">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/241679165-ricardo-garc-a-34-episodio16.mp3" title="Agujeros Negros, Agujeros de gusano y Materia Fantasma [Ep.16]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Agujeros Negros, Agujeros de gusano y Materia Fantasma [Ep.16]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1812">
		<a href="#" data-media="http://api.spreaker.com/download/episode/6066610/podcast17.mp3" title="17. Whatsapp en entorno web">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">17. Whatsapp en entorno web</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1813">
		<a href="#" data-media="http://api.spreaker.com/download/episode/6052770/podcast16.mp3" title="16. Alerta virus CryptoLocker">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">16. Alerta virus CryptoLocker</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1814">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/241679604-ricardo-garc-a-34-episodio15.mp3" title="El eslabón perdido, dinosaurios y fósiles [Ep.15]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">El eslabón perdido, dinosaurios y fósiles [Ep.15]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1815">
		<a href="#" data-media="http://api.spreaker.com/download/episode/6035013/podcast15.mp3" title="15. Cómo funciona un sitio web">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">15. Cómo funciona un sitio web</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1816">
		<a href="#" data-media="http://api.spreaker.com/download/episode/6019448/podcast14.mp3" title="14.Qué es un podcast y cómo podemos crea">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">14.Qué es un podcast y cómo podemos crea</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1817">
		<a href="#" data-media="http://www.ivoox.com/neositelinux-podcast-1-ano-2015_mf_4438604_feed_1.mp3" title="NeoSiteLinux Podcast #1 - Año 2015">
			<span class="isplaying"></span>
			<span class="logo neositelinuxpodcast"></span>
			<span class="podcast">NeoSiteLinux Podcast</span>
			<span class="track">NeoSiteLinux Podcast #1 - Año 2015</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1818">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/241679786-ricardo-garc-a-34-episodio14.mp3" title="Relatividad General, en búsqueda de la Teoría del Todo [Ep.14]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Relatividad General, en búsqueda de la Teoría del Todo [Ep.14]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1819">
		<a href="#" data-media="http://api.spreaker.com/download/episode/6001587/podcast13.mp3" title="13. Megapíxeles: una verdad a medias">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">13. Megapíxeles: una verdad a medias</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1820">
		<a href="#" data-media="http://api.spreaker.com/download/episode/5986608/podcast12.mp3" title="12. Navegador Chrome de Google">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">12. Navegador Chrome de Google</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1821">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/241679950-ricardo-garc-a-34-episodio13.mp3" title="Las Rezagadas Azules, unas misteriosas estrellas  [Ep.13]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Las Rezagadas Azules, unas misteriosas estrellas  [Ep.13]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1822">
		<a href="#" data-media="http://api.spreaker.com/download/episode/5964839/podcast11.mp3" title="11. El Internet de las cosas">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">11. El Internet de las cosas</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1823">
		<a href="#" data-media="http://api.spreaker.com/download/episode/5952287/podcast10.mp3" title="10. Como afecta el Big Data a nuestras v">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">10. Como afecta el Big Data a nuestras v</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1824">
		<a href="#" data-media="http://api.spreaker.com/download/episode/5938385/podcast09.mp3" title="9. Desarrollar aplicaciones con Visual S">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">9. Desarrollar aplicaciones con Visual S</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1825">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/241680167-ricardo-garc-a-34-episodio12.mp3" title="Guía Básica de Observación del Cielo [Ep.12]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Guía Básica de Observación del Cielo [Ep.12]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1826">
		<a href="#" data-media="http://api.spreaker.com/download/episode/5928158/podcast08.mp3" title="8. Una herramienta indispensable, Google">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">8. Una herramienta indispensable, Google</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1827">
		<a href="#" data-media="http://api.spreaker.com/download/episode/5916092/podcast07.mp3" title="7. Android Studio para desarrollar aplic">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">7. Android Studio para desarrollar aplic</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1828">
		<a href="#" data-media="http://podcast.edyo.es/podcast/edyo-12.mp3" title="Edyo 12 - Entrevista EuroPython 2015">
			<span class="isplaying"></span>
			<span class="logo entredevyopspodcast"></span>
			<span class="podcast">EntreDevYOps Podcast</span>
			<span class="track">Edyo 12 - Entrevista EuroPython 2015</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1829">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/241680361-ricardo-garc-a-34-episodio11.mp3" title="¿Qué le pasó a Plutón? Lunas, asteroides, vida y misiones [Ep.11]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">¿Qué le pasó a Plutón? Lunas, asteroides, vida y misiones [Ep.11]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1830">
		<a href="#" data-media="http://api.spreaker.com/download/episode/5896346/podcast06.mp3" title="6. Batiburrillo tecnológico">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">6. Batiburrillo tecnológico</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1831">
		<a href="#" data-media="http://api.spreaker.com/download/episode/5880922/podcast05.mp3" title="5. Montar un servidor web en casa">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">5. Montar un servidor web en casa</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1832">
		<a href="#" data-media="http://api.spreaker.com/download/episode/5867578/podcast04.mp3" title="4. El desfragmentador de disco duro">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">4. El desfragmentador de disco duro</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1833">
		<a href="#" data-media="http://api.spreaker.com/download/episode/5852051/podcast03.mp3" title="3. Iniciarse en la programación">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">3. Iniciarse en la programación</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1834">
		<a href="#" data-media="http://api.spreaker.com/download/episode/5834311/podcast02.mp3" title="2. Qué es un driver">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">2. Qué es un driver</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1835">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/241680609-ricardo-garc-a-34-episodio10.mp3" title="Grandes Proyectos astronómicos en Chile [Ep.10]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Grandes Proyectos astronómicos en Chile [Ep.10]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1836">
		<a href="#" data-media="http://api.spreaker.com/download/episode/5819108/capitulo01.mp3" title="1. Comenzamos La Tecnología Para Todos">
			<span class="isplaying"></span>
			<span class="logo latecnologíaparatodos"></span>
			<span class="podcast">La Tecnología para todos</span>
			<span class="track">1. Comenzamos La Tecnología Para Todos</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1837">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/241680750-ricardo-garc-a-34-episodio9.mp3" title="Cómo se trabajan los datos en Astronomía [Ep.9]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Cómo se trabajan los datos en Astronomía [Ep.9]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1838">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/241680878-ricardo-garc-a-34-episodio8.mp3" title="Energía Oscura y Expansión Acelerada [Ep.8]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Energía Oscura y Expansión Acelerada [Ep.8]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1839">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/248203815-ricardo-garc-a-34-episodio7.mp3" title="La historia del gran astrofotógrafo Daniel Verschatse [Ep.7]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">La historia del gran astrofotógrafo Daniel Verschatse [Ep.7]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1840">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/248212886-ricardo-garc-a-34-episodio6.mp3" title="Un técnico computacional en un Mega Observatorio [Ep.6]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Un técnico computacional en un Mega Observatorio [Ep.6]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1841">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/Ep05.mp3" title="Creando un mapa 3D de la Vía Láctea [Ep.05]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Creando un mapa 3D de la Vía Láctea [Ep.05]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1842">
		<a href="#" data-media="http://podcast.edyo.es/podcast/edyo-11.mp3" title="Edyo 11 - Cursos SCRUM, GHOST y FOSDEM">
			<span class="isplaying"></span>
			<span class="logo entredevyopspodcast"></span>
			<span class="podcast">EntreDevYOps Podcast</span>
			<span class="track">Edyo 11 - Cursos SCRUM, GHOST y FOSDEM</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1843">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/Ep04.mp3" title="Expansión acelerada del universo, la última gran revolución astronómica [Ep.4]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Expansión acelerada del universo, la última gran revolución astronómica [Ep.4]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1844">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/Ep03.mp3" title="Astrofotografía. Cómo obtener una impresionante imagen astronómica [Ep.3]">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Astrofotografía. Cómo obtener una impresionante imagen astronómica [Ep.3]</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1845">
		<a href="#" data-media="http://podcast.edyo.es/podcast/edyo-10.mp3" title="Edyo 10 - Eventos, EuroPython y FOSDEM">
			<span class="isplaying"></span>
			<span class="logo entredevyopspodcast"></span>
			<span class="podcast">EntreDevYOps Podcast</span>
			<span class="track">Edyo 10 - Eventos, EuroPython y FOSDEM</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1846">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/02._Carrera_espacial2.mp3" title="Episodio 2: Carrera Espacial. ¿Llegó el hombre a la Luna? y la disputa actual por colonizar Marte">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Episodio 2: Carrera Espacial. ¿Llegó el hombre a la Luna? y la disputa actual por colonizar Marte</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1847">
		<a href="#" data-media="http://traffic.libsyn.com/astroetal/01._Piloto.mp3" title="Episodio 1: De la Vía Láctea a Cómo se estudia astronomía">
			<span class="isplaying"></span>
			<span class="logo astronomíayalgomás"></span>
			<span class="podcast">Astronomía y algo más</span>
			<span class="track">Episodio 1: De la Vía Láctea a Cómo se estudia astronomía</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1848">
		<a href="#" data-media="http://podcast.edyo.es/podcast/edyo-9.mp3" title="Edyo 9 - Conferencias y Microservicios">
			<span class="isplaying"></span>
			<span class="logo entredevyopspodcast"></span>
			<span class="podcast">EntreDevYOps Podcast</span>
			<span class="track">Edyo 9 - Conferencias y Microservicios</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1849">
		<a href="#" data-media="http://www.podtrac.com/pts/redirect.mp3/www.wedevelopers.com/podcast/wedevelopers037.mp3" title="We.Developers 037 – .NET Open Source">
			<span class="isplaying"></span>
			<span class="logo wedevelopers"></span>
			<span class="podcast">We.Developers</span>
			<span class="track">We.Developers 037 – .NET Open Source</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1850">
		<a href="#" data-media="http://api.spreaker.com/download/episode/9245085/177781603_codeontherocks_code_on_the_rocks_05.mp3" title="S01E05:  'Diseñame esta cabecera, 17 versiones'">
			<span class="isplaying"></span>
			<span class="logo codeontherocks"></span>
			<span class="podcast">Code on the rocks</span>
			<span class="track">S01E05:  'Diseñame esta cabecera, 17 versiones'</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1851">
		<a href="#" data-media="http://podcast.edyo.es/podcast/edyo-8.mp3" title="Edyo 8 - Debatimos sobre Shellshock, Heartbleed y Poodle">
			<span class="isplaying"></span>
			<span class="logo entredevyopspodcast"></span>
			<span class="podcast">EntreDevYOps Podcast</span>
			<span class="track">Edyo 8 - Debatimos sobre Shellshock, Heartbleed y Poodle</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1852">
		<a href="#" data-media="http://www.podtrac.com/pts/redirect.mp3/www.wedevelopers.com/podcast/wedevelopers036.mp3" title="We.Developers 036 – Google App Engine">
			<span class="isplaying"></span>
			<span class="logo wedevelopers"></span>
			<span class="podcast">We.Developers</span>
			<span class="track">We.Developers 036 – Google App Engine</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1853">
		<a href="#" data-media="http://podcast.edyo.es/podcast/edyo-7.mp3" title="Edyo 7 - Entrevista a Josep Pla">
			<span class="isplaying"></span>
			<span class="logo entredevyopspodcast"></span>
			<span class="podcast">EntreDevYOps Podcast</span>
			<span class="track">Edyo 7 - Entrevista a Josep Pla</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1854">
		<a href="#" data-media="http://api.spreaker.com/download/episode/9245086/172073180_codeontherocks_code_on_the_rocks_04_a_nosotros_el_efecto_gowex_nos_hizo_mucho_dano.mp3" title="S01E04: 'A nosotros el efecto GOWEX nos hizo mucho daño.'">
			<span class="isplaying"></span>
			<span class="logo codeontherocks"></span>
			<span class="podcast">Code on the rocks</span>
			<span class="track">S01E04: 'A nosotros el efecto GOWEX nos hizo mucho daño.'</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1855">
		<a href="#" data-media="http://www.podtrac.com/pts/redirect.mp3/www.wedevelopers.com/podcast/wedevelopers035.mp3" title="We.Developers 035 – Procesadores Móviles 2014">
			<span class="isplaying"></span>
			<span class="logo wedevelopers"></span>
			<span class="podcast">We.Developers</span>
			<span class="track">We.Developers 035 – Procesadores Móviles 2014</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1856">
		<a href="#" data-media="http://podcast.edyo.es/podcast/edyo-6.mp3" title="Edyo 6 - Entrevista a David Poblador">
			<span class="isplaying"></span>
			<span class="logo entredevyopspodcast"></span>
			<span class="podcast">EntreDevYOps Podcast</span>
			<span class="track">Edyo 6 - Entrevista a David Poblador</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1857">
		<a href="#" data-media="http://api.spreaker.com/download/episode/9245087/163961963_codeontherocks_code_on_the_rocks_03.mp3" title="S01E03: 'En atlassian no tenemos maquina de cafe'">
			<span class="isplaying"></span>
			<span class="logo codeontherocks"></span>
			<span class="podcast">Code on the rocks</span>
			<span class="track">S01E03: 'En atlassian no tenemos maquina de cafe'</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1858">
		<a href="#" data-media="http://podcast.edyo.es/podcast/edyo-5.mp3" title="Edyo 5 - Entrevista a Daniel Aresté">
			<span class="isplaying"></span>
			<span class="logo entredevyopspodcast"></span>
			<span class="podcast">EntreDevYOps Podcast</span>
			<span class="track">Edyo 5 - Entrevista a Daniel Aresté</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1859">
		<a href="#" data-media="http://api.spreaker.com/download/episode/9303224/158952908_codeontherocks_code_on_the_rocks_02.mp3" title="S01E02: Vivir y trabajar al extranjero">
			<span class="isplaying"></span>
			<span class="logo codeontherocks"></span>
			<span class="podcast">Code on the rocks</span>
			<span class="track">S01E02: Vivir y trabajar al extranjero</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1860">
		<a href="#" data-media="http://podcast.edyo.es/podcast/edyo-4.mp3" title="Edyo 4 - Heartbleed">
			<span class="isplaying"></span>
			<span class="logo entredevyopspodcast"></span>
			<span class="podcast">EntreDevYOps Podcast</span>
			<span class="track">Edyo 4 - Heartbleed</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1861">
		<a href="#" data-media="http://www.podtrac.com/pts/redirect.mp3/www.wedevelopers.com/podcast/wedevelopers034.mp3" title="We.Developers 034 – RabbitMQ">
			<span class="isplaying"></span>
			<span class="logo wedevelopers"></span>
			<span class="podcast">We.Developers</span>
			<span class="track">We.Developers 034 – RabbitMQ</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1862">
		<a href="#" data-media="http://www.podtrac.com/pts/redirect.mp3/www.wedevelopers.com/podcast/wedevelopers033.mp3" title="We.Developers 033 – Novedades WWDC 2014">
			<span class="isplaying"></span>
			<span class="logo wedevelopers"></span>
			<span class="podcast">We.Developers</span>
			<span class="track">We.Developers 033 – Novedades WWDC 2014</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1863">
		<a href="#" data-media="http://api.spreaker.com/download/episode/9303222/154836180_codeontherocks_code_on_the_rocks_01.mp3" title="S01E01: Testing, TDD y contar billetes">
			<span class="isplaying"></span>
			<span class="logo codeontherocks"></span>
			<span class="podcast">Code on the rocks</span>
			<span class="track">S01E01: Testing, TDD y contar billetes</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1864">
		<a href="#" data-media="http://www.podtrac.com/pts/redirect.mp3/www.wedevelopers.com/podcast/wedevelopers032.mp3" title="We.Developers 032 – Redis">
			<span class="isplaying"></span>
			<span class="logo wedevelopers"></span>
			<span class="podcast">We.Developers</span>
			<span class="track">We.Developers 032 – Redis</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1865">
		<a href="#" data-media="http://podcast.edyo.es/podcast/edyo-3.mp3" title="Edyo 3 - Entrevista a Jasiek, QA en Ebay">
			<span class="isplaying"></span>
			<span class="logo entredevyopspodcast"></span>
			<span class="podcast">EntreDevYOps Podcast</span>
			<span class="track">Edyo 3 - Entrevista a Jasiek, QA en Ebay</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1866">
		<a href="#" data-media="http://www.podtrac.com/pts/redirect.mp3/www.wedevelopers.com/podcast/wedevelopers031.mp3" title="We.Developers 031 – Erlang">
			<span class="isplaying"></span>
			<span class="logo wedevelopers"></span>
			<span class="podcast">We.Developers</span>
			<span class="track">We.Developers 031 – Erlang</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1867">
		<a href="#" data-media="http://www.podtrac.com/pts/redirect.mp3/www.wedevelopers.com/podcast/wedevelopers030.mp3" title="We.Developers 030 – Betabeers">
			<span class="isplaying"></span>
			<span class="logo wedevelopers"></span>
			<span class="podcast">We.Developers</span>
			<span class="track">We.Developers 030 – Betabeers</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1868">
		<a href="#" data-media="http://podcast.edyo.es/podcast/edyo-2.mp3" title="Edyo 2 - Creando una cultura de DevOps">
			<span class="isplaying"></span>
			<span class="logo entredevyopspodcast"></span>
			<span class="podcast">EntreDevYOps Podcast</span>
			<span class="track">Edyo 2 - Creando una cultura de DevOps</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1869">
		<a href="#" data-media="http://www.podtrac.com/pts/redirect.mp3/www.wedevelopers.com/podcast/wedevelopers029.mp3" title="We.Developers 029 – Backbeam">
			<span class="isplaying"></span>
			<span class="logo wedevelopers"></span>
			<span class="podcast">We.Developers</span>
			<span class="track">We.Developers 029 – Backbeam</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1870">
		<a href="#" data-media="http://www.podtrac.com/pts/redirect.mp3/www.wedevelopers.com/podcast/wedevelopers028.mp3" title="We.Developers 028 – Javascript">
			<span class="isplaying"></span>
			<span class="logo wedevelopers"></span>
			<span class="podcast">We.Developers</span>
			<span class="track">We.Developers 028 – Javascript</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1871">
		<a href="#" data-media="http://www.podtrac.com/pts/redirect.mp3/www.wedevelopers.com/podcast/wedevelopers027.mp3" title="We.Developers 027 – El Capital Contraataca">
			<span class="isplaying"></span>
			<span class="logo wedevelopers"></span>
			<span class="podcast">We.Developers</span>
			<span class="track">We.Developers 027 – El Capital Contraataca</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1872">
		<a href="#" data-media="http://www.ivoox.com/daboblog-podcast-kernel-panic-n-43-hacking-y_mf_2803627_feed_1.mp3" title="DaboBlog Podcast. 'Kernel Panic' nº 43. Hacking y GNU / Linux con Yago Jesús">
			<span class="isplaying"></span>
			<span class="logo daboblogpodcast"></span>
			<span class="podcast">DaboBlog Podcast</span>
			<span class="track">DaboBlog Podcast. 'Kernel Panic' nº 43. Hacking y GNU / Linux con Yago Jesús</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1873">
		<a href="#" data-media="http://www.podtrac.com/pts/redirect.mp3/www.wedevelopers.com/podcast/wedevelopers026.mp3" title="We.Developers 026 – Accesibilidad Web">
			<span class="isplaying"></span>
			<span class="logo wedevelopers"></span>
			<span class="podcast">We.Developers</span>
			<span class="track">We.Developers 026 – Accesibilidad Web</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1874">
		<a href="#" data-media="http://podcast.edyo.es/podcast/edyo-1.mp3" title="Edyo 1 - Primer commit">
			<span class="isplaying"></span>
			<span class="logo entredevyopspodcast"></span>
			<span class="podcast">EntreDevYOps Podcast</span>
			<span class="track">Edyo 1 - Primer commit</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1875">
		<a href="#" data-media="http://www.podtrac.com/pts/redirect.mp3/www.wedevelopers.com/podcast/wedevelopers025.mp3" title="We.Developers 025 – Developing for iOS and Android">
			<span class="isplaying"></span>
			<span class="logo wedevelopers"></span>
			<span class="podcast">We.Developers</span>
			<span class="track">We.Developers 025 – Developing for iOS and Android</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1876">
		<a href="#" data-media="http://www.ivoox.com/daboblog-podcast-kernel-panic-n-42-gnu_mf_2674894_feed_1.mp3" title="DaboBlog Podcast. 'Kernel Panic' nº 42. GNU / Linux y Software Libre">
			<span class="isplaying"></span>
			<span class="logo daboblogpodcast"></span>
			<span class="podcast">DaboBlog Podcast</span>
			<span class="track">DaboBlog Podcast. 'Kernel Panic' nº 42. GNU / Linux y Software Libre</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1877">
		<a href="#" data-media="http://www.podtrac.com/pts/redirect.mp3/www.wedevelopers.com/podcast/wedevelopers024.mp3" title="We.Developers 024 – Core Data">
			<span class="isplaying"></span>
			<span class="logo wedevelopers"></span>
			<span class="podcast">We.Developers</span>
			<span class="track">We.Developers 024 – Core Data</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1878">
		<a href="#" data-media="http://www.ivoox.com/daboblog-podcast-kernel-panic-n-41_mf_2579206_feed_1.mp3" title="DaboBlog Podcast. 'Kernel Panic' nº 41.">
			<span class="isplaying"></span>
			<span class="logo daboblogpodcast"></span>
			<span class="podcast">DaboBlog Podcast</span>
			<span class="track">DaboBlog Podcast. 'Kernel Panic' nº 41.</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1879">
		<a href="#" data-media="http://www.ivoox.com/daboblog-podcast-kernel-panic-n-40_mf_2522120_feed_1.mp3" title="DaboBlog Podcast. 'Kernel Panic' nº 40.">
			<span class="isplaying"></span>
			<span class="logo daboblogpodcast"></span>
			<span class="podcast">DaboBlog Podcast</span>
			<span class="track">DaboBlog Podcast. 'Kernel Panic' nº 40.</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1880">
		<a href="#" data-media="http://www.podtrac.com/pts/redirect.mp3/www.wedevelopers.com/podcast/wedevelopers023.mp3" title="We.Developers 023 – Go">
			<span class="isplaying"></span>
			<span class="logo wedevelopers"></span>
			<span class="podcast">We.Developers</span>
			<span class="track">We.Developers 023 – Go</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1881">
		<a href="#" data-media="http://www.podtrac.com/pts/redirect.mp3/www.wedevelopers.com/podcast/wedevelopers022.mp3" title="We.Developers 022 – NSSpain">
			<span class="isplaying"></span>
			<span class="logo wedevelopers"></span>
			<span class="podcast">We.Developers</span>
			<span class="track">We.Developers 022 – NSSpain</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1882">
		<a href="#" data-media="http://www.podtrac.com/pts/redirect.mp3/www.wedevelopers.com/podcast/wedevelopers021.mp3" title="We.Developers 021 – Emprender en España">
			<span class="isplaying"></span>
			<span class="logo wedevelopers"></span>
			<span class="podcast">We.Developers</span>
			<span class="track">We.Developers 021 – Emprender en España</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1883">
		<a href="#" data-media="http://www.podtrac.com/pts/redirect.mp3/www.wedevelopers.com/podcast/wedevelopers020.mp3" title="We.Developers 020 – Windows Phone 8">
			<span class="isplaying"></span>
			<span class="logo wedevelopers"></span>
			<span class="podcast">We.Developers</span>
			<span class="track">We.Developers 020 – Windows Phone 8</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1884">
		<a href="#" data-media="http://www.podtrac.com/pts/redirect.mp3/www.wedevelopers.com/podcast/wedevelopers019.mp3" title="We.Developers 019 – COBOL">
			<span class="isplaying"></span>
			<span class="logo wedevelopers"></span>
			<span class="podcast">We.Developers</span>
			<span class="track">We.Developers 019 – COBOL</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1885">
		<a href="#" data-media="http://www.podtrac.com/pts/redirect.mp3/www.wedevelopers.com/podcast/wedevelopers018.mp3" title="We.Developers 018 – Procesadores Móviles 2013">
			<span class="isplaying"></span>
			<span class="logo wedevelopers"></span>
			<span class="podcast">We.Developers</span>
			<span class="track">We.Developers 018 – Procesadores Móviles 2013</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1886">
		<a href="#" data-media="http://www.podtrac.com/pts/redirect.mp3/www.wedevelopers.com/podcast/wedevelopers017.mp3" title="We.Developers 017 – De cero a la App Store">
			<span class="isplaying"></span>
			<span class="logo wedevelopers"></span>
			<span class="podcast">We.Developers</span>
			<span class="track">We.Developers 017 – De cero a la App Store</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1887">
		<a href="#" data-media="http://www.podtrac.com/pts/redirect.mp3/www.wedevelopers.com/podcast/wedevelopers016.mp3" title="We.Developers 016 – Cocos2D">
			<span class="isplaying"></span>
			<span class="logo wedevelopers"></span>
			<span class="podcast">We.Developers</span>
			<span class="track">We.Developers 016 – Cocos2D</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1888">
		<a href="#" data-media="http://www.podtrac.com/pts/redirect.mp3/www.wedevelopers.com/podcast/wedevelopers015.mp3" title="We.Developers 015 – RealBasic">
			<span class="isplaying"></span>
			<span class="logo wedevelopers"></span>
			<span class="podcast">We.Developers</span>
			<span class="track">We.Developers 015 – RealBasic</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1889">
		<a href="#" data-media="http://www.ivoox.com/daboblog-podcast-especial-lanzamiento-eninternet-es-por-forat_mf_1768991_feed_1.mp3" title="DaboBlog Podcast. Especial lanzamiento 'eninternet.es' (por Forat)">
			<span class="isplaying"></span>
			<span class="logo daboblogpodcast"></span>
			<span class="podcast">DaboBlog Podcast</span>
			<span class="track">DaboBlog Podcast. Especial lanzamiento 'eninternet.es' (por Forat)</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1890">
		<a href="#" data-media="http://www.ivoox.com/daboblog-podcast-feliz-2013_mf_1679594_feed_1.mp3" title="DaboBlog Podcast. Feliz 2013 !!!">
			<span class="isplaying"></span>
			<span class="logo daboblogpodcast"></span>
			<span class="podcast">DaboBlog Podcast</span>
			<span class="track">DaboBlog Podcast. Feliz 2013 !!!</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1891">
		<a href="#" data-media="http://www.podtrac.com/pts/redirect.mp3/www.wedevelopers.com/podcast/wedevelopers014.mp3" title="We.Developers 014 – Arduino">
			<span class="isplaying"></span>
			<span class="logo wedevelopers"></span>
			<span class="podcast">We.Developers</span>
			<span class="track">We.Developers 014 – Arduino</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1892">
		<a href="#" data-media="http://www.ivoox.com/daboblog-podcast-n-39-kernel-panic-manzanas-traigo_mf_1667417_feed_1.mp3" title="DaboBlog Podcast nº39. 'Kernel Panic' y 'Manzanas Traigo'.">
			<span class="isplaying"></span>
			<span class="logo daboblogpodcast"></span>
			<span class="podcast">DaboBlog Podcast</span>
			<span class="track">DaboBlog Podcast nº39. 'Kernel Panic' y 'Manzanas Traigo'.</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1893">
		<a href="#" data-media="http://www.podtrac.com/pts/redirect.mp3/www.wedevelopers.com/podcast/wedevelopers013.mp3" title="We.Developers 013 – Compiladores">
			<span class="isplaying"></span>
			<span class="logo wedevelopers"></span>
			<span class="podcast">We.Developers</span>
			<span class="track">We.Developers 013 – Compiladores</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1894">
		<a href="#" data-media="http://www.podtrac.com/pts/redirect.mp3/www.wedevelopers.com/podcast/wedevelopers012.mp3" title="We.Developers 012 – Metodologías Ágiles">
			<span class="isplaying"></span>
			<span class="logo wedevelopers"></span>
			<span class="podcast">We.Developers</span>
			<span class="track">We.Developers 012 – Metodologías Ágiles</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1895">
		<a href="#" data-media="http://www.podtrac.com/pts/redirect.mp3/www.wedevelopers.com/podcast/wedevelopers011.mp3" title="We.Developers 011 – Diseño y Desarrollo">
			<span class="isplaying"></span>
			<span class="logo wedevelopers"></span>
			<span class="podcast">We.Developers</span>
			<span class="track">We.Developers 011 – Diseño y Desarrollo</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1896">
		<a href="#" data-media="http://www.ivoox.com/daboblog-podcast-n-38-kernel-panic-manzanas-traigo_mf_1562229_feed_1.mp3" title="DaboBlog Podcast nº38. 'Kernel Panic' y 'Manzanas Traigo'.">
			<span class="isplaying"></span>
			<span class="logo daboblogpodcast"></span>
			<span class="podcast">DaboBlog Podcast</span>
			<span class="track">DaboBlog Podcast nº38. 'Kernel Panic' y 'Manzanas Traigo'.</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1897">
		<a href="#" data-media="http://www.ivoox.com/daboblog-podcast-n-37-kernel-panic-manzanas-traigo_mf_1522771_feed_1.mp3" title="DaboBlog Podcast nº37. 'Kernel Panic' y 'Manzanas Traigo'.">
			<span class="isplaying"></span>
			<span class="logo daboblogpodcast"></span>
			<span class="podcast">DaboBlog Podcast</span>
			<span class="track">DaboBlog Podcast nº37. 'Kernel Panic' y 'Manzanas Traigo'.</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1898">
		<a href="#" data-media="http://www.podtrac.com/pts/redirect.mp3/www.wedevelopers.com/podcast/wedevelopers010.mp3" title="We.Developers 010 – Optimización Web">
			<span class="isplaying"></span>
			<span class="logo wedevelopers"></span>
			<span class="podcast">We.Developers</span>
			<span class="track">We.Developers 010 – Optimización Web</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1899">
		<a href="#" data-media="http://www.ivoox.com/daboblog-podcast-kernel-panic-especial-fluxbox_mf_1367785_feed_1.mp3" title="DaboBlog Podcast. 'Kernel Panic' especial Fluxbox">
			<span class="isplaying"></span>
			<span class="logo daboblogpodcast"></span>
			<span class="podcast">DaboBlog Podcast</span>
			<span class="track">DaboBlog Podcast. 'Kernel Panic' especial Fluxbox</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1900">
		<a href="#" data-media="http://www.podtrac.com/pts/redirect.mp3/www.wedevelopers.com/podcast/wedevelopers009.mp3" title="We.Developers 009 – Accesibilidad">
			<span class="isplaying"></span>
			<span class="logo wedevelopers"></span>
			<span class="podcast">We.Developers</span>
			<span class="track">We.Developers 009 – Accesibilidad</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1901">
		<a href="#" data-media="http://www.podtrac.com/pts/redirect.mp3/www.wedevelopers.com/podcast/wedevelopers008.mp3" title="We.Developers 008 – Experiencias WWDC">
			<span class="isplaying"></span>
			<span class="logo wedevelopers"></span>
			<span class="podcast">We.Developers</span>
			<span class="track">We.Developers 008 – Experiencias WWDC</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1902">
		<a href="#" data-media="http://www.podtrac.com/pts/redirect.mp3/www.wedevelopers.com/podcast/wedevelopers007.mp3" title="We.Developers 007 – Python & Django">
			<span class="isplaying"></span>
			<span class="logo wedevelopers"></span>
			<span class="podcast">We.Developers</span>
			<span class="track">We.Developers 007 – Python & Django</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1903">
		<a href="#" data-media="http://www.ivoox.com/daboblog-podcast-n-36-manzanas-traigo-wwdc_mf_1291005_feed_1.mp3" title="DaboBlog Podcast nº36. (Manzanas Traigo WWDC)">
			<span class="isplaying"></span>
			<span class="logo daboblogpodcast"></span>
			<span class="podcast">DaboBlog Podcast</span>
			<span class="track">DaboBlog Podcast nº36. (Manzanas Traigo WWDC)</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1904">
		<a href="#" data-media="http://www.podtrac.com/pts/redirect.mp3/www.wedevelopers.com/podcast/wedevelopers006.mp3" title="We.Developers 006 – BlackBerry 10">
			<span class="isplaying"></span>
			<span class="logo wedevelopers"></span>
			<span class="podcast">We.Developers</span>
			<span class="track">We.Developers 006 – BlackBerry 10</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1905">
		<a href="#" data-media="http://www.ivoox.com/daboblog-podcast-n-36-kernel-panic-prox-manzanas_mf_1265188_feed_1.mp3" title="DaboBlog Podcast nº36. 'Kernel Panic' (Próx 'Manzanas)">
			<span class="isplaying"></span>
			<span class="logo daboblogpodcast"></span>
			<span class="podcast">DaboBlog Podcast</span>
			<span class="track">DaboBlog Podcast nº36. 'Kernel Panic' (Próx 'Manzanas)</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1906">
		<a href="#" data-media="http://www.podtrac.com/pts/redirect.mp3/www.wedevelopers.com/podcast/wedevelopers005.mp3" title="We.Developers 005 – Desarrollo de Videojuegos">
			<span class="isplaying"></span>
			<span class="logo wedevelopers"></span>
			<span class="podcast">We.Developers</span>
			<span class="track">We.Developers 005 – Desarrollo de Videojuegos</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1907">
		<a href="#" data-media="http://www.ivoox.com/daboblog-podcast-n-35-kernel-panic-manzanas-traigo_mf_1147254_feed_1.mp3" title="DaboBlog Podcast nº35. 'Kernel Panic' y 'Manzanas Traigo'.">
			<span class="isplaying"></span>
			<span class="logo daboblogpodcast"></span>
			<span class="podcast">DaboBlog Podcast</span>
			<span class="track">DaboBlog Podcast nº35. 'Kernel Panic' y 'Manzanas Traigo'.</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1908">
		<a href="#" data-media="http://www.podtrac.com/pts/redirect.mp3/www.wedevelopers.com/podcast/wedevelopers004.mp3" title="We.Developers 004 – Big Nerd Ranch">
			<span class="isplaying"></span>
			<span class="logo wedevelopers"></span>
			<span class="podcast">We.Developers</span>
			<span class="track">We.Developers 004 – Big Nerd Ranch</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1909">
		<a href="#" data-media="http://www.podtrac.com/pts/redirect.mp3/www.wedevelopers.com/podcast/wedevelopers003.mp3" title="We.Developers 003 – Los mundos de Java">
			<span class="isplaying"></span>
			<span class="logo wedevelopers"></span>
			<span class="podcast">We.Developers</span>
			<span class="track">We.Developers 003 – Los mundos de Java</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1910">
		<a href="#" data-media="http://www.podtrac.com/pts/redirect.mp3/www.wedevelopers.com/podcast/wedevelopers002.mp3" title="We.Developers 002 – Arquitecturas de Procesadores Móviles">
			<span class="isplaying"></span>
			<span class="logo wedevelopers"></span>
			<span class="podcast">We.Developers</span>
			<span class="track">We.Developers 002 – Arquitecturas de Procesadores Móviles</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1911">
		<a href="#" data-media="http://www.ivoox.com/daboblog-podcast-especial-fin-ano-2011_mf_972013_feed_1.mp3" title="DaboBlog Podcast. Especial fin de año 2011">
			<span class="isplaying"></span>
			<span class="logo daboblogpodcast"></span>
			<span class="podcast">DaboBlog Podcast</span>
			<span class="track">DaboBlog Podcast. Especial fin de año 2011</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1912">
		<a href="#" data-media="http://www.ivoox.com/daboblog-podcast-n-34-kernel-panic-manzanas-traigo_mf_961747_feed_1.mp3" title="DaboBlog Podcast nº34. 'Kernel Panic' y 'Manzanas Traigo'.">
			<span class="isplaying"></span>
			<span class="logo daboblogpodcast"></span>
			<span class="podcast">DaboBlog Podcast</span>
			<span class="track">DaboBlog Podcast nº34. 'Kernel Panic' y 'Manzanas Traigo'.</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1913">
		<a href="#" data-media="http://www.podtrac.com/pts/redirect.mp3/www.wedevelopers.com/podcast/wedevelopers001.mp3" title="We.Developers 001 – webOS & Enyo">
			<span class="isplaying"></span>
			<span class="logo wedevelopers"></span>
			<span class="podcast">We.Developers</span>
			<span class="track">We.Developers 001 – webOS & Enyo</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1914">
		<a href="#" data-media="http://www.podtrac.com/pts/redirect.mp3/wedevelopers.com/podcast/wedevelopers000.mp3" title="We.Developers 000 – JMP #FFFF0">
			<span class="isplaying"></span>
			<span class="logo wedevelopers"></span>
			<span class="podcast">We.Developers</span>
			<span class="track">We.Developers 000 – JMP #FFFF0</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1915">
		<a href="#" data-media="http://www.ivoox.com/daboblog-podcast-n-33-kernel-panic-manzanas-traigo_mf_898481_feed_1.mp3" title="DaboBlog Podcast nº33. 'Kernel Panic' y 'Manzanas Traigo'.">
			<span class="isplaying"></span>
			<span class="logo daboblogpodcast"></span>
			<span class="podcast">DaboBlog Podcast</span>
			<span class="track">DaboBlog Podcast nº33. 'Kernel Panic' y 'Manzanas Traigo'.</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1916">
		<a href="#" data-media="http://www.ivoox.com/daboblog-podcast-n-32-kernel-panic-manzanas-traigo_mf_828844_feed_1.mp3" title="DaboBlog Podcast nº32. 'Kernel Panic' y 'Manzanas Traigo'.">
			<span class="isplaying"></span>
			<span class="logo daboblogpodcast"></span>
			<span class="podcast">DaboBlog Podcast</span>
			<span class="track">DaboBlog Podcast nº32. 'Kernel Panic' y 'Manzanas Traigo'.</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1917">
		<a href="#" data-media="http://www.ivoox.com/daboblog-podcast-n-31-kernel-panic-manzanas-traigo_mf_799855_feed_1.mp3" title="DaboBlog Podcast nº31. 'Kernel Panic' y 'Manzanas Traigo'.">
			<span class="isplaying"></span>
			<span class="logo daboblogpodcast"></span>
			<span class="podcast">DaboBlog Podcast</span>
			<span class="track">DaboBlog Podcast nº31. 'Kernel Panic' y 'Manzanas Traigo'.</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1918">
		<a href="#" data-media="http://www.ivoox.com/daboblog-podcast-n-30-kernel-panic-manzanas-traigo_mf_764549_feed_1.mp3" title="DaboBlog Podcast nº30. 'Kernel Panic' y 'Manzanas Traigo'.">
			<span class="isplaying"></span>
			<span class="logo daboblogpodcast"></span>
			<span class="podcast">DaboBlog Podcast</span>
			<span class="track">DaboBlog Podcast nº30. 'Kernel Panic' y 'Manzanas Traigo'.</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1919">
		<a href="#" data-media="http://www.ivoox.com/daboblog-podcast-n-29-kernel-panic-manzanas-traigo_mf_729491_feed_1.mp3" title="DaboBlog Podcast nº29. 'Kernel Panic' y 'Manzanas Traigo'">
			<span class="isplaying"></span>
			<span class="logo daboblogpodcast"></span>
			<span class="podcast">DaboBlog Podcast</span>
			<span class="track">DaboBlog Podcast nº29. 'Kernel Panic' y 'Manzanas Traigo'</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1920">
		<a href="#" data-media="http://feedproxy.google.com/~r/OdaibaNet/~5/Z4VutroILog/mp3.mp3" title="on172 regresando">
			<span class="isplaying"></span>
			<span class="logo odaibanetpodcastwwwpoderatocomodaibanet"></span>
			<span class="podcast">Odaiba Net (Podcast) - www.poderato.com/odaibanet</span>
			<span class="track">on172 regresando</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1921">
		<a href="#" data-media="http://feedproxy.google.com/~r/OdaibaNet/~5/Yx9D7XZPURU/mp3.mp3" title="Episode 171 - ON171 entrevista oesopen, cuide su privacidad">
			<span class="isplaying"></span>
			<span class="logo odaibanetpodcastwwwpoderatocomodaibanet"></span>
			<span class="podcast">Odaiba Net (Podcast) - www.poderato.com/odaibanet</span>
			<span class="track">Episode 171 - ON171 entrevista oesopen, cuide su privacidad</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1922">
		<a href="#" data-media="http://feedproxy.google.com/~r/OdaibaNet/~5/CrTA3sSVxxo/mp3.mp3" title="Episode 170 - ON 170 todos usan linux, hasta los que se portan mal">
			<span class="isplaying"></span>
			<span class="logo odaibanetpodcastwwwpoderatocomodaibanet"></span>
			<span class="podcast">Odaiba Net (Podcast) - www.poderato.com/odaibanet</span>
			<span class="track">Episode 170 - ON 170 todos usan linux, hasta los que se portan mal</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1923">
		<a href="#" data-media="http://feedproxy.google.com/~r/OdaibaNet/~5/0n4j5Agx0GI/mp3.mp3" title="Episode 169 - ON 169 ya en 2011, pymes, asesorías, huerfanos">
			<span class="isplaying"></span>
			<span class="logo odaibanetpodcastwwwpoderatocomodaibanet"></span>
			<span class="podcast">Odaiba Net (Podcast) - www.poderato.com/odaibanet</span>
			<span class="track">Episode 169 - ON 169 ya en 2011, pymes, asesorías, huerfanos</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1924">
		<a href="#" data-media="http://feedproxy.google.com/~r/OdaibaNet/~5/nT1a8Lg2KWs/mp3.mp3" title="Episode 168 - ON 168 Felices fiestas, nos vemos en el 2011">
			<span class="isplaying"></span>
			<span class="logo odaibanetpodcastwwwpoderatocomodaibanet"></span>
			<span class="podcast">Odaiba Net (Podcast) - www.poderato.com/odaibanet</span>
			<span class="track">Episode 168 - ON 168 Felices fiestas, nos vemos en el 2011</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1925">
		<a href="#" data-media="http://feedproxy.google.com/~r/OdaibaNet/~5/IpzvEu263pM/mp3.mp3" title="Episode 167 - ON 167 Noticias de Emergencia.">
			<span class="isplaying"></span>
			<span class="logo odaibanetpodcastwwwpoderatocomodaibanet"></span>
			<span class="podcast">Odaiba Net (Podcast) - www.poderato.com/odaibanet</span>
			<span class="track">Episode 167 - ON 167 Noticias de Emergencia.</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1926">
		<a href="#" data-media="http://feedproxy.google.com/~r/OdaibaNet/~5/QlJaHvaleLM/mp3.mp3" title="Episode 166 - ON 166 Ubuntudf, software, correo.">
			<span class="isplaying"></span>
			<span class="logo odaibanetpodcastwwwpoderatocomodaibanet"></span>
			<span class="podcast">Odaiba Net (Podcast) - www.poderato.com/odaibanet</span>
			<span class="track">Episode 166 - ON 166 Ubuntudf, software, correo.</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1927">
		<a href="#" data-media="http://feedproxy.google.com/~r/OdaibaNet/~5/MK8mWHzhttM/mp3.mp3" title="Episode 165 - ON 165 somos tan vulnerables.">
			<span class="isplaying"></span>
			<span class="logo odaibanetpodcastwwwpoderatocomodaibanet"></span>
			<span class="podcast">Odaiba Net (Podcast) - www.poderato.com/odaibanet</span>
			<span class="track">Episode 165 - ON 165 somos tan vulnerables.</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1928">
		<a href="#" data-media="http://feedproxy.google.com/~r/OdaibaNet/~5/iRIC9WmK1T8/mp3.mp3" title="4ce6bf9679793">
			<span class="isplaying"></span>
			<span class="logo odaibanetpodcastwwwpoderatocomodaibanet"></span>
			<span class="podcast">Odaiba Net (Podcast) - www.poderato.com/odaibanet</span>
			<span class="track">4ce6bf9679793</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1929">
		<a href="#" data-media="http://feedproxy.google.com/~r/OdaibaNet/~5/AZctbQvSCSo/mp3.mp3" title="Episode 163 - ON 163 Linux en la ciencia, programe usted SL, niños Debian">
			<span class="isplaying"></span>
			<span class="logo odaibanetpodcastwwwpoderatocomodaibanet"></span>
			<span class="podcast">Odaiba Net (Podcast) - www.poderato.com/odaibanet</span>
			<span class="track">Episode 163 - ON 163 Linux en la ciencia, programe usted SL, niños Debian</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1930">
		<a href="#" data-media="http://feedproxy.google.com/~r/OdaibaNet/~5/NZETlU2bfGI/mp3.mp3" title="ON162 embellece tu Ubuntu 10.10, radio comercial agoniza">
			<span class="isplaying"></span>
			<span class="logo odaibanetpodcastwwwpoderatocomodaibanet"></span>
			<span class="podcast">Odaiba Net (Podcast) - www.poderato.com/odaibanet</span>
			<span class="track">ON162 embellece tu Ubuntu 10.10, radio comercial agoniza</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1931">
		<a href="#" data-media="http://feedproxy.google.com/~r/OdaibaNet/~5/1LM3ePJOu80/mp3.mp3" title="Episode 161 - ON 161 habladuri­as corporativas, entrevista 2 con Allen Zapien.">
			<span class="isplaying"></span>
			<span class="logo odaibanetpodcastwwwpoderatocomodaibanet"></span>
			<span class="podcast">Odaiba Net (Podcast) - www.poderato.com/odaibanet</span>
			<span class="track">Episode 161 - ON 161 habladuri­as corporativas, entrevista 2 con Allen Zapien.</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1932">
		<a href="#" data-media="http://feedproxy.google.com/~r/OdaibaNet/~5/1r5wOOdLkPU/mp3.mp3" title="4cac7d21b34ee">
			<span class="isplaying"></span>
			<span class="logo odaibanetpodcastwwwpoderatocomodaibanet"></span>
			<span class="podcast">Odaiba Net (Podcast) - www.poderato.com/odaibanet</span>
			<span class="track">4cac7d21b34ee</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1933">
		<a href="#" data-media="http://feedproxy.google.com/~r/OdaibaNet/~5/cEji1guQWew/mp3.mp3" title="Episode 159 - ON 159 defendiendo el uso del SL">
			<span class="isplaying"></span>
			<span class="logo odaibanetpodcastwwwpoderatocomodaibanet"></span>
			<span class="podcast">Odaiba Net (Podcast) - www.poderato.com/odaibanet</span>
			<span class="track">Episode 159 - ON 159 defendiendo el uso del SL</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1934">
		<a href="#" data-media="http://feedproxy.google.com/~r/OdaibaNet/~5/tuB-Ppuu1iE/mp3.mp3" title="4c8faaca035e2">
			<span class="isplaying"></span>
			<span class="logo odaibanetpodcastwwwpoderatocomodaibanet"></span>
			<span class="podcast">Odaiba Net (Podcast) - www.poderato.com/odaibanet</span>
			<span class="track">4c8faaca035e2</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1935">
		<a href="#" data-media="http://feedproxy.google.com/~r/OdaibaNet/~5/FZV7xoXZjXY/mp3.mp3" title="4c812d51dff58">
			<span class="isplaying"></span>
			<span class="logo odaibanetpodcastwwwpoderatocomodaibanet"></span>
			<span class="podcast">Odaiba Net (Podcast) - www.poderato.com/odaibanet</span>
			<span class="track">4c812d51dff58</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1936">
		<a href="#" data-media="http://feedproxy.google.com/~r/OdaibaNet/~5/pqnVtXUgTE0/mp3.mp3" title="ON 156 Nuevo Inkscape, fin del 5to aniversario">
			<span class="isplaying"></span>
			<span class="logo odaibanetpodcastwwwpoderatocomodaibanet"></span>
			<span class="podcast">Odaiba Net (Podcast) - www.poderato.com/odaibanet</span>
			<span class="track">ON 156 Nuevo Inkscape, fin del 5to aniversario</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1937">
		<a href="#" data-media="http://feedproxy.google.com/~r/OdaibaNet/~5/c7i1sBWW4f4/mp3.mp3" title="Episode 155 - ON 155 Integradores gandallas, plática con Armando Muciño">
			<span class="isplaying"></span>
			<span class="logo odaibanetpodcastwwwpoderatocomodaibanet"></span>
			<span class="podcast">Odaiba Net (Podcast) - www.poderato.com/odaibanet</span>
			<span class="track">Episode 155 - ON 155 Integradores gandallas, plática con Armando Muciño</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1938">
		<a href="#" data-media="http://feedproxy.google.com/~r/OdaibaNet/~5/js5ucKHk8mE/mp3.mp3" title="Episode 154 - ON 154 Plática con Allen Zapien, parte 1">
			<span class="isplaying"></span>
			<span class="logo odaibanetpodcastwwwpoderatocomodaibanet"></span>
			<span class="podcast">Odaiba Net (Podcast) - www.poderato.com/odaibanet</span>
			<span class="track">Episode 154 - ON 154 Plática con Allen Zapien, parte 1</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1939">
		<a href="#" data-media="http://feedproxy.google.com/~r/OdaibaNet/~5/bMxSxXN5nEU/mp3.mp3" title="Episode 153 - ON 153 GPL gana demanda, antología de LiveCDs">
			<span class="isplaying"></span>
			<span class="logo odaibanetpodcastwwwpoderatocomodaibanet"></span>
			<span class="podcast">Odaiba Net (Podcast) - www.poderato.com/odaibanet</span>
			<span class="track">Episode 153 - ON 153 GPL gana demanda, antología de LiveCDs</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1940">
		<a href="#" data-media="http://feedproxy.google.com/~r/OdaibaNet/~5/6rwdTY1Uhlc/mp3.mp3" title="Episode 152 - ON 152 nubes, FF4beta, Nokia N900">
			<span class="isplaying"></span>
			<span class="logo odaibanetpodcastwwwpoderatocomodaibanet"></span>
			<span class="podcast">Odaiba Net (Podcast) - www.poderato.com/odaibanet</span>
			<span class="track">Episode 152 - ON 152 nubes, FF4beta, Nokia N900</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1941">
		<a href="#" data-media="http://feedproxy.google.com/~r/OdaibaNet/~5/64WU61qpSxc/mp3.mp3" title="ON 151 - Software para Empresas">
			<span class="isplaying"></span>
			<span class="logo odaibanetpodcastwwwpoderatocomodaibanet"></span>
			<span class="podcast">Odaiba Net (Podcast) - www.poderato.com/odaibanet</span>
			<span class="track">ON 151 - Software para Empresas</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1942">
		<a href="#" data-media="http://feedproxy.google.com/~r/OdaibaNet/~5/NvOsD4wmRFU/mp3.mp3" title="ON 150 expresate, con videos, screencast, audio">
			<span class="isplaying"></span>
			<span class="logo odaibanetpodcastwwwpoderatocomodaibanet"></span>
			<span class="podcast">Odaiba Net (Podcast) - www.poderato.com/odaibanet</span>
			<span class="track">ON 150 expresate, con videos, screencast, audio</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1943">
		<a href="#" data-media="http://feedproxy.google.com/~r/OdaibaNet/~5/KSGZds8hSb0/mp3.mp3" title="ON 149 Vulnerabilidad irreal ('Unreal' vulnerabilty)">
			<span class="isplaying"></span>
			<span class="logo odaibanetpodcastwwwpoderatocomodaibanet"></span>
			<span class="podcast">Odaiba Net (Podcast) - www.poderato.com/odaibanet</span>
			<span class="track">ON 149 Vulnerabilidad irreal ('Unreal' vulnerabilty)</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1944">
		<a href="#" data-media="http://feedproxy.google.com/~r/OdaibaNet/~5/X3DL4INNkqA/mp3.mp3" title="ON 148 recuperando la lomita">
			<span class="isplaying"></span>
			<span class="logo odaibanetpodcastwwwpoderatocomodaibanet"></span>
			<span class="podcast">Odaiba Net (Podcast) - www.poderato.com/odaibanet</span>
			<span class="track">ON 148 recuperando la lomita</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1945">
		<a href="#" data-media="http://feedproxy.google.com/~r/OdaibaNet/~5/VUbN2PdP_VA/mp3.mp3" title="ON 147 correo de mis amigos">
			<span class="isplaying"></span>
			<span class="logo odaibanetpodcastwwwpoderatocomodaibanet"></span>
			<span class="podcast">Odaiba Net (Podcast) - www.poderato.com/odaibanet</span>
			<span class="track">ON 147 correo de mis amigos</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1946">
		<a href="#" data-media="http://feedproxy.google.com/~r/OdaibaNet/~5/uEF9NIG2d_s/mp3.mp3" title="ON 146 ¿radio-ON? fácil su propia estación con software libre.">
			<span class="isplaying"></span>
			<span class="logo odaibanetpodcastwwwpoderatocomodaibanet"></span>
			<span class="podcast">Odaiba Net (Podcast) - www.poderato.com/odaibanet</span>
			<span class="track">ON 146 ¿radio-ON? fácil su propia estación con software libre.</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1947">
		<a href="#" data-media="http://feedproxy.google.com/~r/OdaibaNet/~5/6vhOPJBWbd4/mp3.mp3" title="ON 145 diseñando el futuro">
			<span class="isplaying"></span>
			<span class="logo odaibanetpodcastwwwpoderatocomodaibanet"></span>
			<span class="podcast">Odaiba Net (Podcast) - www.poderato.com/odaibanet</span>
			<span class="track">ON 145 diseñando el futuro</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1948">
		<a href="#" data-media="http://feedproxy.google.com/~r/OdaibaNet/~5/2uYFRUd3k80/mp3.mp3" title="ON 144 Twitísimo">
			<span class="isplaying"></span>
			<span class="logo odaibanetpodcastwwwpoderatocomodaibanet"></span>
			<span class="podcast">Odaiba Net (Podcast) - www.poderato.com/odaibanet</span>
			<span class="track">ON 144 Twitísimo</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1949">
		<a href="#" data-media="http://feedproxy.google.com/~r/OdaibaNet/~5/bRSmd3xNRec/mp3.mp3" title="ON 143 organizado, apretujado, corporatizado">
			<span class="isplaying"></span>
			<span class="logo odaibanetpodcastwwwpoderatocomodaibanet"></span>
			<span class="podcast">Odaiba Net (Podcast) - www.poderato.com/odaibanet</span>
			<span class="track">ON 143 organizado, apretujado, corporatizado</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1950">
		<a href="#" data-media="http://feedproxy.google.com/~r/OdaibaNet/~5/EZrdFPMBRtI/mp3.mp3" title="ON 142 nuevo horario, masoquistas, sea legal – use linux">
			<span class="isplaying"></span>
			<span class="logo odaibanetpodcastwwwpoderatocomodaibanet"></span>
			<span class="podcast">Odaiba Net (Podcast) - www.poderato.com/odaibanet</span>
			<span class="track">ON 142 nuevo horario, masoquistas, sea legal – use linux</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1951">
		<a href="#" data-media="http://feedproxy.google.com/~r/OdaibaNet/~5/Y3Jr6tvoQ1k/mp3.mp3" title="ON 141 Hadrones bajo GNU/Linux, ¡seamos libres! ¿chicas TUX?">
			<span class="isplaying"></span>
			<span class="logo odaibanetpodcastwwwpoderatocomodaibanet"></span>
			<span class="podcast">Odaiba Net (Podcast) - www.poderato.com/odaibanet</span>
			<span class="track">ON 141 Hadrones bajo GNU/Linux, ¡seamos libres! ¿chicas TUX?</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1952">
		<a href="#" data-media="http://feedproxy.google.com/~r/OdaibaNet/~5/0JDpxky_5Uc/mp3.mp3" title="ON140 Zen, Tron, Iron">
			<span class="isplaying"></span>
			<span class="logo odaibanetpodcastwwwpoderatocomodaibanet"></span>
			<span class="podcast">Odaiba Net (Podcast) - www.poderato.com/odaibanet</span>
			<span class="track">ON140 Zen, Tron, Iron</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1953">
		<a href="#" data-media="http://feedproxy.google.com/~r/OdaibaNet/~5/tjX9xkcHcEw/mp3.mp3" title="ON 139 Dialogo VoIP con Ebert">
			<span class="isplaying"></span>
			<span class="logo odaibanetpodcastwwwpoderatocomodaibanet"></span>
			<span class="podcast">Odaiba Net (Podcast) - www.poderato.com/odaibanet</span>
			<span class="track">ON 139 Dialogo VoIP con Ebert</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1954">
		<a href="#" data-media="http://feedproxy.google.com/~r/OdaibaNet/~5/uGYLTQc-n2o/mp3.mp3" title="ON 138 ¿criminales nosotros?, ¿queremos flash? seamos albañiles">
			<span class="isplaying"></span>
			<span class="logo odaibanetpodcastwwwpoderatocomodaibanet"></span>
			<span class="podcast">Odaiba Net (Podcast) - www.poderato.com/odaibanet</span>
			<span class="track">ON 138 ¿criminales nosotros?, ¿queremos flash? seamos albañiles</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1955">
		<a href="#" data-media="http://feedproxy.google.com/~r/OdaibaNet/~5/FUQeKeI4pt8/mp3.mp3" title="ON136 testiomonio de éxito con software libre">
			<span class="isplaying"></span>
			<span class="logo odaibanetpodcastwwwpoderatocomodaibanet"></span>
			<span class="podcast">Odaiba Net (Podcast) - www.poderato.com/odaibanet</span>
			<span class="track">ON136 testiomonio de éxito con software libre</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1956">
		<a href="#" data-media="http://feedproxy.google.com/~r/OdaibaNet/~5/igzVYbKPpAU/mp3.mp3" title="ON 135 haciendo las cosas, producir TV en linux">
			<span class="isplaying"></span>
			<span class="logo odaibanetpodcastwwwpoderatocomodaibanet"></span>
			<span class="podcast">Odaiba Net (Podcast) - www.poderato.com/odaibanet</span>
			<span class="track">ON 135 haciendo las cosas, producir TV en linux</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1957">
		<a href="#" data-media="http://feedproxy.google.com/~r/OdaibaNet/~5/ktLRR_u-Vqk/mp3.mp3" title="ON 134 el fin de la red IPv4 cantada, FLAC a mp3, minitube">
			<span class="isplaying"></span>
			<span class="logo odaibanetpodcastwwwpoderatocomodaibanet"></span>
			<span class="podcast">Odaiba Net (Podcast) - www.poderato.com/odaibanet</span>
			<span class="track">ON 134 el fin de la red IPv4 cantada, FLAC a mp3, minitube</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1958">
		<a href="#" data-media="http://feedproxy.google.com/~r/OdaibaNet/~5/u2NzIY3eg-A/mp3.mp3" title="ON 133 ¿Como seria la vida sin Windows?">
			<span class="isplaying"></span>
			<span class="logo odaibanetpodcastwwwpoderatocomodaibanet"></span>
			<span class="podcast">Odaiba Net (Podcast) - www.poderato.com/odaibanet</span>
			<span class="track">ON 133 ¿Como seria la vida sin Windows?</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1959">
		<a href="#" data-media="http://feedproxy.google.com/~r/OdaibaNet/~5/tNmUGTt7vag/mp3.mp3" title="ON 132 audiocorreo, linux vs mac, Avatar y su infoporn">
			<span class="isplaying"></span>
			<span class="logo odaibanetpodcastwwwpoderatocomodaibanet"></span>
			<span class="podcast">Odaiba Net (Podcast) - www.poderato.com/odaibanet</span>
			<span class="track">ON 132 audiocorreo, linux vs mac, Avatar y su infoporn</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1960">
		<a href="#" data-media="http://feedproxy.google.com/~r/OdaibaNet/~5/9z7ijgCqfOE/mp3.mp3" title="ON 131 de archivos, wallpapers, medios, ipods, y HD, sin ir al 'CES'">
			<span class="isplaying"></span>
			<span class="logo odaibanetpodcastwwwpoderatocomodaibanet"></span>
			<span class="podcast">Odaiba Net (Podcast) - www.poderato.com/odaibanet</span>
			<span class="track">ON 131 de archivos, wallpapers, medios, ipods, y HD, sin ir al 'CES'</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1961">
		<a href="#" data-media="http://feedproxy.google.com/~r/OdaibaNet/~5/aj-ZBYWVmM8/mp3.mp3" title="ON 130 ¿2010? y yo que no acabe con el 2009">
			<span class="isplaying"></span>
			<span class="logo odaibanetpodcastwwwpoderatocomodaibanet"></span>
			<span class="podcast">Odaiba Net (Podcast) - www.poderato.com/odaibanet</span>
			<span class="track">ON 130 ¿2010? y yo que no acabe con el 2009</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1962">
		<a href="#" data-media="http://feedproxy.google.com/~r/OdaibaNet/~5/Y5EnGfO8mqY/mp3.mp3" title="on129 Gente honesta">
			<span class="isplaying"></span>
			<span class="logo odaibanetpodcastwwwpoderatocomodaibanet"></span>
			<span class="podcast">Odaiba Net (Podcast) - www.poderato.com/odaibanet</span>
			<span class="track">on129 Gente honesta</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1963">
		<a href="#" data-media="http://feedproxy.google.com/~r/OdaibaNet/~5/uSF-8g-dT0s/mp3.mp3" title="ON 128 nuevo flash, chrome, lubuntu, pegotes">
			<span class="isplaying"></span>
			<span class="logo odaibanetpodcastwwwpoderatocomodaibanet"></span>
			<span class="podcast">Odaiba Net (Podcast) - www.poderato.com/odaibanet</span>
			<span class="track">ON 128 nuevo flash, chrome, lubuntu, pegotes</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1964">
		<a href="#" data-media="http://feedproxy.google.com/~r/OdaibaNet/~5/STh0Nr0LEfs/mp3.mp3" title="ON 118 CODIGO, unos lo abren, otros no.">
			<span class="isplaying"></span>
			<span class="logo odaibanetpodcastwwwpoderatocomodaibanet"></span>
			<span class="podcast">Odaiba Net (Podcast) - www.poderato.com/odaibanet</span>
			<span class="track">ON 118 CODIGO, unos lo abren, otros no.</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1965">
		<a href="#" data-media="http://feedproxy.google.com/~r/OdaibaNet/~5/Y8O5DMCnovQ/mp3.mp3" title="ON 116 Ligue chicas geek, Google Wave, Linux en la Casa Blanca">
			<span class="isplaying"></span>
			<span class="logo odaibanetpodcastwwwpoderatocomodaibanet"></span>
			<span class="podcast">Odaiba Net (Podcast) - www.poderato.com/odaibanet</span>
			<span class="track">ON 116 Ligue chicas geek, Google Wave, Linux en la Casa Blanca</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1966">
		<a href="#" data-media="http://feedproxy.google.com/~r/OdaibaNet/~5/_noB7rUS4VU/mp3.mp3" title="ON 114 elige tu distribución, sube fotos, apaga el monitor">
			<span class="isplaying"></span>
			<span class="logo odaibanetpodcastwwwpoderatocomodaibanet"></span>
			<span class="podcast">Odaiba Net (Podcast) - www.poderato.com/odaibanet</span>
			<span class="track">ON 114 elige tu distribución, sube fotos, apaga el monitor</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1967">
		<a href="#" data-media="http://feedproxy.google.com/~r/OdaibaNet/~5/OnSbiLnTNBE/mp3.mp3" title="ON 112 'la nube' es borrascosa, Linux en mas Gobiernos del mundo.">
			<span class="isplaying"></span>
			<span class="logo odaibanetpodcastwwwpoderatocomodaibanet"></span>
			<span class="podcast">Odaiba Net (Podcast) - www.poderato.com/odaibanet</span>
			<span class="track">ON 112 'la nube' es borrascosa, Linux en mas Gobiernos del mundo.</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1968">
		<a href="#" data-media="http://feedproxy.google.com/~r/OdaibaNet/~5/m8e0KeArk-8/mp3.mp3" title="ON111 Juegos, Mediateca, Escritorios, Tips en Linux">
			<span class="isplaying"></span>
			<span class="logo odaibanetpodcastwwwpoderatocomodaibanet"></span>
			<span class="podcast">Odaiba Net (Podcast) - www.poderato.com/odaibanet</span>
			<span class="track">ON111 Juegos, Mediateca, Escritorios, Tips en Linux</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1969">
		<a href="#" data-media="http://feedproxy.google.com/~r/OdaibaNet/~5/hd0lH3QHGyw/mp3.mp3" title="ON110 Mitin para hackear, el hacker no es malo, los medios lo pintan asi">
			<span class="isplaying"></span>
			<span class="logo odaibanetpodcastwwwpoderatocomodaibanet"></span>
			<span class="podcast">Odaiba Net (Podcast) - www.poderato.com/odaibanet</span>
			<span class="track">ON110 Mitin para hackear, el hacker no es malo, los medios lo pintan asi</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1970">
		<a href="#" data-media="http://feedproxy.google.com/~r/OdaibaNet/~5/1XBd_s5vNBo/mp3.mp3" title="ON 109 competencia desleal, abusos a licencia GNU-LGPL de FFMPEG">
			<span class="isplaying"></span>
			<span class="logo odaibanetpodcastwwwpoderatocomodaibanet"></span>
			<span class="podcast">Odaiba Net (Podcast) - www.poderato.com/odaibanet</span>
			<span class="track">ON 109 competencia desleal, abusos a licencia GNU-LGPL de FFMPEG</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1971">
		<a href="#" data-media="http://feedproxy.google.com/~r/OdaibaNet/~5/_ZjrYQmuIDo/mp3.mp3" title="ON 108 inocentes maquinas, dia de la libertad en el software">
			<span class="isplaying"></span>
			<span class="logo odaibanetpodcastwwwpoderatocomodaibanet"></span>
			<span class="podcast">Odaiba Net (Podcast) - www.poderato.com/odaibanet</span>
			<span class="track">ON 108 inocentes maquinas, dia de la libertad en el software</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1972">
		<a href="#" data-media="http://feedproxy.google.com/~r/OdaibaNet/~5/JUbOecNZ0m4/mp3.mp3" title="ON 107 mapa de gurús, hardware bajo linux">
			<span class="isplaying"></span>
			<span class="logo odaibanetpodcastwwwpoderatocomodaibanet"></span>
			<span class="podcast">Odaiba Net (Podcast) - www.poderato.com/odaibanet</span>
			<span class="track">ON 107 mapa de gurús, hardware bajo linux</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1973">
		<a href="#" data-media="http://feedproxy.google.com/~r/OdaibaNet/~5/qo9dzbh2jHo/mp3.mp3" title="ON 106 Correo de oyentes">
			<span class="isplaying"></span>
			<span class="logo odaibanetpodcastwwwpoderatocomodaibanet"></span>
			<span class="podcast">Odaiba Net (Podcast) - www.poderato.com/odaibanet</span>
			<span class="track">ON 106 Correo de oyentes</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1974">
		<a href="#" data-media="http://feedproxy.google.com/~r/OdaibaNet/~5/XI7bHQLKTwQ/mp3.mp3" title="ON 105 Yoo no me preocupo, 5 distros para netbooks">
			<span class="isplaying"></span>
			<span class="logo odaibanetpodcastwwwpoderatocomodaibanet"></span>
			<span class="podcast">Odaiba Net (Podcast) - www.poderato.com/odaibanet</span>
			<span class="track">ON 105 Yoo no me preocupo, 5 distros para netbooks</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1975">
		<a href="#" data-media="http://feedproxy.google.com/~r/OdaibaNet/~5/mBbyx8g-_y0/mp3.mp3" title="ON 104 ACABANDO CON NEÓFITOS">
			<span class="isplaying"></span>
			<span class="logo odaibanetpodcastwwwpoderatocomodaibanet"></span>
			<span class="podcast">Odaiba Net (Podcast) - www.poderato.com/odaibanet</span>
			<span class="track">ON 104 ACABANDO CON NEÓFITOS</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1976">
		<a href="#" data-media="http://feedproxy.google.com/~r/OdaibaNet/~5/CPGbFF6ZMFc/mp3.mp3" title="ON 103 PYME LIBRE, cifrado de archivos, correo de oyentes">
			<span class="isplaying"></span>
			<span class="logo odaibanetpodcastwwwpoderatocomodaibanet"></span>
			<span class="podcast">Odaiba Net (Podcast) - www.poderato.com/odaibanet</span>
			<span class="track">ON 103 PYME LIBRE, cifrado de archivos, correo de oyentes</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1977">
		<a href="#" data-media="http://feedproxy.google.com/~r/OdaibaNet/~5/R-JRFC5m4jo/mp3.mp3" title="ON 102 Linux para PYME, créditos TUX">
			<span class="isplaying"></span>
			<span class="logo odaibanetpodcastwwwpoderatocomodaibanet"></span>
			<span class="podcast">Odaiba Net (Podcast) - www.poderato.com/odaibanet</span>
			<span class="track">ON 102 Linux para PYME, créditos TUX</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1978">
		<a href="#" data-media="http://feedproxy.google.com/~r/OdaibaNet/~5/6Leuiy93_To/mp3.mp3" title="ON 101 regreso de vacaciones">
			<span class="isplaying"></span>
			<span class="logo odaibanetpodcastwwwpoderatocomodaibanet"></span>
			<span class="podcast">Odaiba Net (Podcast) - www.poderato.com/odaibanet</span>
			<span class="track">ON 101 regreso de vacaciones</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1979">
		<a href="#" data-media="http://feedproxy.google.com/~r/OdaibaNet/~5/iq-Zqhr6xPE/mp3.mp3" title="ON 100 un logro, antesala para lo que vendrá">
			<span class="isplaying"></span>
			<span class="logo odaibanetpodcastwwwpoderatocomodaibanet"></span>
			<span class="podcast">Odaiba Net (Podcast) - www.poderato.com/odaibanet</span>
			<span class="track">ON 100 un logro, antesala para lo que vendrá</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1980">
		<a href="#" data-media="http://feedproxy.google.com/~r/OdaibaNet/~5/dFg9Uhxhv84/mp3.mp3" title="ON 99 Correo de oyentes">
			<span class="isplaying"></span>
			<span class="logo odaibanetpodcastwwwpoderatocomodaibanet"></span>
			<span class="podcast">Odaiba Net (Podcast) - www.poderato.com/odaibanet</span>
			<span class="track">ON 99 Correo de oyentes</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1981">
		<a href="#" data-media="http://feedproxy.google.com/~r/OdaibaNet/~5/CmwDTWCWkMc/mp3.mp3" title="ON 98 Internet Satelital">
			<span class="isplaying"></span>
			<span class="logo odaibanetpodcastwwwpoderatocomodaibanet"></span>
			<span class="podcast">Odaiba Net (Podcast) - www.poderato.com/odaibanet</span>
			<span class="track">ON 98 Internet Satelital</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1982">
		<a href="#" data-media="http://feedproxy.google.com/~r/OdaibaNet/~5/AAUaZO47GRY/mp3.mp3" title="ON 97 Buscando la iluminación, de la que ilumina y también espiritual">
			<span class="isplaying"></span>
			<span class="logo odaibanetpodcastwwwpoderatocomodaibanet"></span>
			<span class="podcast">Odaiba Net (Podcast) - www.poderato.com/odaibanet</span>
			<span class="track">ON 97 Buscando la iluminación, de la que ilumina y también espiritual</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1983">
		<a href="#" data-media="http://feedproxy.google.com/~r/OdaibaNet/~5/KVrj0esPXG0/mp3.mp3" title="ON 96 Correo de oyentes y un amable reclamo">
			<span class="isplaying"></span>
			<span class="logo odaibanetpodcastwwwpoderatocomodaibanet"></span>
			<span class="podcast">Odaiba Net (Podcast) - www.poderato.com/odaibanet</span>
			<span class="track">ON 96 Correo de oyentes y un amable reclamo</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1984">
		<a href="#" data-media="http://feedproxy.google.com/~r/OdaibaNet/~5/-YfWkFjbfZc/mp3.mp3" title="ON 95 Ubuntu 9.04 nos gusta mucho.">
			<span class="isplaying"></span>
			<span class="logo odaibanetpodcastwwwpoderatocomodaibanet"></span>
			<span class="podcast">Odaiba Net (Podcast) - www.poderato.com/odaibanet</span>
			<span class="track">ON 95 Ubuntu 9.04 nos gusta mucho.</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1985">
		<a href="#" data-media="http://feedproxy.google.com/~r/OdaibaNet/~5/bdrszL6ytVU/mp3.mp3" title="ON 94 mi centro espacial personal, vuelve la relledona, Nokia E71 y 5800">
			<span class="isplaying"></span>
			<span class="logo odaibanetpodcastwwwpoderatocomodaibanet"></span>
			<span class="podcast">Odaiba Net (Podcast) - www.poderato.com/odaibanet</span>
			<span class="track">ON 94 mi centro espacial personal, vuelve la relledona, Nokia E71 y 5800</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1986">
		<a href="#" data-media="http://feedproxy.google.com/~r/OdaibaNet/~5/Z21fd2F8W9Y/mp3.mp3" title="ON 93 Protegiendonos de los 'otros' virus, quitate las pilas">
			<span class="isplaying"></span>
			<span class="logo odaibanetpodcastwwwpoderatocomodaibanet"></span>
			<span class="podcast">Odaiba Net (Podcast) - www.poderato.com/odaibanet</span>
			<span class="track">ON 93 Protegiendonos de los 'otros' virus, quitate las pilas</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1987">
		<a href="#" data-media="http://feedproxy.google.com/~r/OdaibaNet/~5/sEl2LXk5grM/mp3.mp3" title="ON 92 Virus ineficiente, Tecnologia ineficiente">
			<span class="isplaying"></span>
			<span class="logo odaibanetpodcastwwwpoderatocomodaibanet"></span>
			<span class="podcast">Odaiba Net (Podcast) - www.poderato.com/odaibanet</span>
			<span class="track">ON 92 Virus ineficiente, Tecnologia ineficiente</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1988">
		<a href="#" data-media="http://feedproxy.google.com/~r/OdaibaNet/~5/YYdP0vPhTvI/mp3.mp3" title="Contingencia Viral">
			<span class="isplaying"></span>
			<span class="logo odaibanetpodcastwwwpoderatocomodaibanet"></span>
			<span class="podcast">Odaiba Net (Podcast) - www.poderato.com/odaibanet</span>
			<span class="track">Contingencia Viral</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1989">
		<a href="#" data-media="http://feedproxy.google.com/~r/OdaibaNet/~5/IpEygRuBQiQ/mp3.mp3" title="ON 91 Venus y Luna, Otro caso de éxito usando Linux">
			<span class="isplaying"></span>
			<span class="logo odaibanetpodcastwwwpoderatocomodaibanet"></span>
			<span class="podcast">Odaiba Net (Podcast) - www.poderato.com/odaibanet</span>
			<span class="track">ON 91 Venus y Luna, Otro caso de éxito usando Linux</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1990">
		<a href="#" data-media="http://feedproxy.google.com/~r/OdaibaNet/~5/-Ds26oWlEJw/mp3.mp3" title="ON 90">
			<span class="isplaying"></span>
			<span class="logo odaibanetpodcastwwwpoderatocomodaibanet"></span>
			<span class="podcast">Odaiba Net (Podcast) - www.poderato.com/odaibanet</span>
			<span class="track">ON 90</span>
		</a>
	</span>
</li>
<li>
	<span id="item-1991">
		<a href="#" data-media="http://feedproxy.google.com/~r/OdaibaNet/~5/m57IpNeHOaQ/mp3.mp3" title="ON 89 semana de reflexión, y Alta Definición">
			<span class="isplaying"></span>
			<span class="logo odaibanetpodcastwwwpoderatocomodaibanet"></span>
			<span class="podcast">Odaiba Net (Podcast) - www.poderato.com/odaibanet</span>
			<span class="track">ON 89 semana de reflexión, y Alta Definición</span>
		</a>
	</span>
</li>


    </ul>
</div>
<link rel="stylesheet" type="text/css" href="https://ugeek.github.io/podcasts.css" />
<script type="text/javascript" src="https://code.jquery.com/jquery-3.2.1.min.js"></script>
<script type="text/javascript" src="https://ugeek.github.io/podcasts.js"></script>
