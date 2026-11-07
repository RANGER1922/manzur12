<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Hotel Manzur | Hospedaje en Ixtepec, Oaxaca</title>
<meta name="description" content="Hotel Manzur en Ciudad Ixtepec, Oaxaca. Habitaciones con aire acondicionado, restaurante, alberca y recepción las 24 horas.">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,500;0,600;1,500&family=Poiret+One&display=swap" rel="stylesheet">
<style>
:root{
  color-scheme: light dark;
  --bg:#EEF0EB; --fg:#14201F; --panel:#E2E7E0; --muted:#4A5755; --gold:#85652A; --line:#C3CBC2;
  --ink:#0C1B1C; --ivory:#EAE3D0; --gilt:#C9A867;
  --display:"Poiret One","Didot","Georgia",serif; --body:"Cormorant Garamond","Georgia","Times New Roman",serif;
  box-sizing:border-box; padding-top:env(safe-area-inset-top,0px); padding-bottom:env(safe-area-inset-bottom,0px);
}
@media (prefers-color-scheme: dark){
  :root:not([data-theme="light"]){--bg:#0A1516;--fg:#E8E2D2;--panel:#102021;--muted:#A6B0AB;--gold:#C9A867;--line:#24393A}
}
:root[data-theme="dark"]{--bg:#0A1516;--fg:#E8E2D2;--panel:#102021;--muted:#A6B0AB;--gold:#C9A867;--line:#24393A}
*,*::before,*::after{box-sizing:border-box}
html{scroll-behavior:smooth;scroll-padding-top:4.5rem}
body{margin:0;background:var(--bg);color:var(--fg);font:500 1.25rem/1.6 var(--body);-webkit-font-smoothing:antialiased}
a{color:inherit}
:focus-visible{outline:2px solid var(--gilt);outline-offset:4px}
.wrap{width:min(1100px,100% - 3rem);margin-inline:auto}

.top{position:sticky;top:0;z-index:20;background:var(--ink);color:var(--ivory);padding-top:env(safe-area-inset-top,0px);border-bottom:1px solid rgba(201,168,103,.35)}
.top .wrap{display:flex;align-items:center;justify-content:space-between;gap:1.5rem;min-height:3.75rem}
.brand{font:400 1.5rem var(--display);text-decoration:none;letter-spacing:.04em}
.top nav{display:flex;gap:2rem;font-size:1.1rem}
.top nav a{text-decoration:none;opacity:.85}
.top nav a:hover{opacity:1;color:var(--gilt)}
.call{color:var(--gilt);text-decoration:none;border:1px solid var(--gilt);padding:.35rem 1.1rem;font-size:1.05rem}
.call:hover{background:var(--gilt);color:var(--ink)}
@media (max-width:760px){.top nav{display:none}}

/* hero */
.hero{position:relative;overflow:hidden;background:linear-gradient(180deg,#0C1B1C 0%,#08100F 100%);color:var(--ivory);min-height:min(82vh,720px);display:flex;align-items:center}
.fan{position:absolute;right:-8%;bottom:0;width:min(88vw,760px);aspect-ratio:2/1;border-radius:999px 999px 0 0;
  background:repeating-conic-gradient(from -90deg at 50% 100%,var(--gilt) 0 .5deg,transparent .5deg 5deg);
  -webkit-mask-image:radial-gradient(circle at 50% 100%,#000 12%,transparent 70%);mask-image:radial-gradient(circle at 50% 100%,#000 12%,transparent 70%);
  opacity:.5;animation:rise 1.8s cubic-bezier(.2,.7,.2,1) both}
@keyframes rise{from{opacity:0;transform:translateY(18%)}}
.hero .wrap{position:relative;padding:clamp(3rem,9vw,6rem) 0}
.hero h1{font:400 clamp(3.5rem,13vw,8.5rem)/.95 var(--display);margin:0;letter-spacing:.01em}
.hero .rule{width:6rem;height:1px;background:var(--gilt);margin:2rem 0 1.5rem}
.hero p{margin:0;max-width:30ch;font-size:clamp(1.4rem,3vw,1.9rem);font-style:italic;line-height:1.35}
.hero .where{margin-top:1.5rem;font-size:1.1rem;color:var(--gilt);font-style:normal}

/* reservación */
.book{background:var(--panel);border-bottom:1px solid var(--line)}
.book form{display:grid;grid-template-columns:repeat(3,1fr) auto;gap:1.25rem;padding:1.5rem 0;align-items:end}
.book label{display:grid;gap:.3rem;font-size:1.05rem;color:var(--muted)}
.book input,.book select{font:500 1.1rem var(--body);color:var(--fg);background:transparent;border:0;border-bottom:1px solid var(--fg);border-radius:0;padding:.45rem 0;min-height:2.75rem;width:100%}
.btn{font:600 1.1rem var(--body);background:var(--ink);color:var(--gilt);border:1px solid var(--gilt);padding:.7rem 1.6rem;min-height:2.75rem;cursor:pointer;text-decoration:none;display:inline-flex;align-items:center;justify-content:center}
.btn:hover{background:var(--gilt);color:var(--ink)}
@media (max-width:760px){.book form{grid-template-columns:1fr 1fr}.book .btn{grid-column:1/-1}}

section{padding:clamp(3.5rem,9vw,6.5rem) 0}
h2{font:400 clamp(2.2rem,5vw,3.4rem)/1.05 var(--display);margin:0 0 1.25rem;text-wrap:balance}
.lead{max-width:44ch;color:var(--muted);margin:0 0 3rem;font-size:1.35rem}

/* servicios */
.serv{display:grid;grid-template-columns:repeat(2,1fr);gap:0 4rem}
.serv article{padding:1.75rem 0;border-top:1px solid var(--gold)}
.serv h3{font:600 1.6rem/1.2 var(--body);margin:0 0 .4rem;font-style:italic}
.serv p{margin:0;color:var(--muted)}
@media (max-width:720px){.serv{grid-template-columns:1fr}}

/* galería con arcos */
.arches{display:grid;grid-template-columns:repeat(3,1fr);gap:1.5rem;align-items:end}
.arch{aspect-ratio:3/4;border:1px solid var(--gold);border-radius:999px 999px 0 0;display:grid;place-items:end center;text-align:center;padding:2rem 1.25rem;color:var(--muted);font-style:italic;font-size:1.1rem;
  background:repeating-linear-gradient(90deg,transparent 0 14px,color-mix(in srgb,var(--gold) 14%,transparent) 14px 15px)}
.arch:nth-child(2){aspect-ratio:3/4.6}
@media (max-width:720px){.arches{grid-template-columns:1fr 1fr}.arch:nth-child(2){aspect-ratio:3/4}.arch:last-child{grid-column:1/-1;aspect-ratio:2/1}}

/* opiniones */
.score{display:flex;align-items:baseline;gap:1.25rem;flex-wrap:wrap}
.score strong{font:400 clamp(4rem,12vw,7rem)/1 var(--display);color:var(--gold)}
.pull{font-size:clamp(1.6rem,3.6vw,2.3rem);line-height:1.3;font-style:italic;max-width:30ch;margin:1.5rem 0 0}
.minor{display:grid;grid-template-columns:1fr 1fr;gap:2rem;margin-top:2.5rem;max-width:760px;color:var(--muted)}
.minor p{margin:0;padding-top:1rem;border-top:1px solid var(--line)}
@media (max-width:640px){.minor{grid-template-columns:1fr}}

/* contacto */
.contact{background:var(--ink);color:var(--ivory)}
.contact .cols{display:grid;grid-template-columns:1fr 1fr;gap:3rem}
.contact dl{margin:0;display:grid;gap:1.5rem}
.contact dt{color:var(--gilt);font-style:italic;font-size:1.1rem}
.contact dd{margin:0}
.contact a{text-underline-offset:5px}
@media (max-width:720px){.contact .cols{grid-template-columns:1fr}}
footer{padding:1.5rem 0;font-size:1rem;color:var(--muted)}

@media (prefers-reduced-motion: reduce){.fan{animation:none}html{scroll-behavior:auto}}
</style>
</head>
<body>

<header class="top">
  <div class="wrap">
    <a class="brand" href="#inicio">Hotel Manzur</a>
    <nav aria-label="Principal">
      <a href="#servicios">Servicios</a>
      <a href="#galeria">Galería</a>
      <a href="#opiniones">Opiniones</a>
      <a href="#contacto">Contacto</a>
    </nav>
    <a class="call" href="tel:+529716882931">Llamar</a>
  </div>
</header>

<main id="inicio">
  <div class="hero">
    <div class="fan" aria-hidden="true"></div>
    <div class="wrap">
      <h1>Hotel<br>Manzur</h1>
      <div class="rule"></div>
      <p>Una estancia con la elegancia del cine de oro mexicano.</p>
      <p class="where">Av. 16 de Septiembre 110, Ciudad Ixtepec, Oaxaca</p>
    </div>
  </div>

  <div class="book">
    <div class="wrap">
      <form id="reserva" aria-label="Solicitar reservación">
        <label>Llegada <input type="date" id="llegada" required></label>
        <label>Salida <input type="date" id="salida" required></label>
        <label>Huéspedes
          <select id="huespedes">
            <option>1 persona</option><option selected>2 personas</option><option>3 personas</option><option>4 personas</option><option>5 o más</option>
          </select>
        </label>
        <button class="btn" type="submit">Solicitar por WhatsApp</button>
      </form>
    </div>
  </div>

  <section id="servicios">
    <div class="wrap">
      <h2>Su estancia, sin prisas</h2>
      <p class="lead">Un hotel pensado para dormir bien, comer en casa y descansar junto a la alberca, ya sea una noche de paso o una semana en el Istmo.</p>
      <div class="serv">
        <article><h3>Habitaciones</h3><p>Camas cómodas, aire acondicionado y agua caliente. Hay opciones en planta baja.</p></article>
        <article><h3>Desayuno</h3><p>Desayuno de cortesía para huéspedes, servido en el restaurante del hotel.</p></article>
        <article><h3>Restaurante</h3><p>Cocina a precios accesibles en un salón decorado con el cine de oro como tema. Abierto también al público.</p></article>
        <article><h3>Alberca</h3><p>Un patio con alberca para refrescarse después de un día de viaje.</p></article>
        <article><h3>Recepción</h3><p>Atención las 24 horas, ideal si llega tarde por carretera o en autobús.</p></article>
        <article><h3>Ubicación</h3><p>En la avenida principal de Ixtepec, a pasos del centro y del parque.</p></article>
      </div>
    </div>
  </section>

  <section id="galeria" style="background:var(--panel)">
    <div class="wrap">
      <h2>El hotel</h2>
      <p class="lead">Las fotografías reales del hotel van en estos arcos.</p>
      <div class="arches">
        <div class="arch">Lobby y decoración</div>
        <div class="arch">Habitación</div>
        <div class="arch">Alberca y restaurante</div>
      </div>
    </div>
  </section>

  <section id="opiniones">
    <div class="wrap">
      <h2>Opiniones</h2>
      <div class="score"><strong>4.6</strong><span>de 5 en Google, con más de 1,100 opiniones</span></div>
      <p class="pull">Los huéspedes destacan la temática del cine de oro, el trato amable y la comodidad de las habitaciones.</p>
      <div class="minor">
        <p>Viajeros en bicicleta agradecen la atención del dueño y la habitación espaciosa.</p>
        <p>Quienes solo comieron aquí elogian la comida y el ambiente junto a la alberca.</p>
      </div>
    </div>
  </section>

  <section class="contact" id="contacto">
    <div class="wrap">
      <h2>Reservaciones</h2>
      <div class="cols">
        <dl>
          <div><dt>Teléfono</dt><dd><a href="tel:+529716882931">+52 971 688 2931</a></dd></div>
          <div><dt>Dirección</dt><dd>Av. 16 de Septiembre 110, Col. Moderna, 70110 Ciudad Ixtepec, Oaxaca</dd></div>
          <div><dt>Recepción</dt><dd>Abierta las 24 horas, todos los días</dd></div>
        </dl>
        <div>
          <p>Llámenos y le ayudamos con indicaciones y disponibilidad.</p>
          <a class="btn" href="https://www.google.com/maps/search/?api=1&query=Hotel+Manzur+Ixtepec+Oaxaca" target="_blank" rel="noopener">Ver en Google Maps</a>
        </div>
      </div>
    </div>
  </section>
</main>

<footer>
  <div class="wrap">Prototipo de página web para Hotel Manzur. Textos y fotos por confirmar con el hotel.</div>
</footer>

<script>
(function(){
  var hoy=new Date(), pad=function(n){return String(n).padStart(2,"0")};
  var iso=function(d){return d.getFullYear()+"-"+pad(d.getMonth()+1)+"-"+pad(d.getDate())};
  var ll=document.getElementById("llegada"), sa=document.getElementById("salida");
  ll.min=iso(hoy); sa.min=iso(hoy);
  ll.addEventListener("change",function(){ sa.min=ll.value||iso(hoy); if(sa.value&&sa.value<ll.value){sa.value=ll.value;} });
  document.getElementById("reserva").addEventListener("submit",function(e){
    e.preventDefault();
    var h=document.getElementById("huespedes").value;
    var msg="Hola, quisiera reservar en Hotel Manzur. Llegada: "+ll.value+". Salida: "+sa.value+". Huéspedes: "+h+".";
    window.open("https://wa.me/529716882931?text="+encodeURIComponent(msg),"_blank","noopener");
  });
})();
</script>
</body>
</html>
