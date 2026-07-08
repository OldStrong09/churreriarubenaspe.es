[index.html](https://github.com/user-attachments/files/29807522/churreria-ruben-aspe.html)# churreriarubenaspe.es
Pagina Web de Churreria Ruben Aspe
[<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Churrería Rubén Aspe | Porras artesanales desde 2021</title>
<meta name="description" content="Churrería Rubén, en Aspe (Alicante). Porras con aire por dentro, chocolate a la taza, café y tostadas. Abiertos todos los días de 6:00 a 12:00.">
<meta property="og:title" content="Churrería Rubén Aspe | Porras con aire por dentro">
<meta property="og:description" content="Porras artesanales, chocolate a la taza y tostadas en Aspe (Alicante). Abiertos todos los días de 6:00 a 12:00.">
<meta property="og:type" content="restaurant.menu">
<meta property="og:locale" content="es_ES">
<link rel="icon" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 100 100'%3E%3Ccircle cx='50' cy='50' r='46' fill='%232B1A10'/%3E%3Ccircle cx='50' cy='50' r='30' fill='%23D9A441'/%3E%3Ccircle cx='50' cy='50' r='16' fill='%23F7ECD8'/%3E%3C/svg%3E">
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "Bakery",
  "name": "Churrería Rubén Aspe",
  "@id": "https://churreriarubenaspe.com",
  "url": "https://churreriarubenaspe.com",
  "telephone": "+34665692896",
  "priceRange": "€",
  "address": {
    "@type": "PostalAddress",
    "streetAddress": "Av. Pintor Pastor Calpena, 2",
    "addressLocality": "Aspe",
    "addressRegion": "Alicante",
    "postalCode": "03680",
    "addressCountry": "ES"
  },
  "openingHoursSpecification": [{
    "@type": "OpeningHoursSpecification",
    "dayOfWeek": ["Monday","Tuesday","Wednesday","Thursday","Friday","Saturday","Sunday"],
    "opens": "06:00",
    "closes": "12:00"
  }],
  "servesCuisine": "Churrería",
  "sameAs": [
    "https://www.instagram.com/aspe_churreriaruben/",
    "https://www.tiktok.com/@elchurrerodeaspe"
  ]
}
</script>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Ultra&family=Space+Mono:wght@400;700&family=Karla:wght@400;500;600;700&display=swap" rel="stylesheet">
<style>
  :root{
    --ink:#2B1A10;
    --ink-soft:#40291A;
    --cream:#F7ECD8;
    --cream-soft:#FBF5EA;
    --gold:#D9A441;
    --gold-deep:#B5822C;
    --copper:#B5482A;
    --steam:#CEDAD6;
  }

  *{box-sizing:border-box; margin:0; padding:0;}

  html{scroll-behavior:smooth;}

  body{
    font-family:'Karla', sans-serif;
    background:var(--cream-soft);
    color:var(--ink);
    line-height:1.6;
    overflow-x:hidden;
  }

  h1,h2,h3{
    font-family:'Ultra', serif;
    font-weight:400;
    line-height:1.15;
    letter-spacing:0.5px;
  }

  .mono{
    font-family:'Space Mono', monospace;
  }

  a{color:inherit; text-decoration:none;}
  img,svg{display:block; max-width:100%;}

  .wrap{
    max-width:1120px;
    margin:0 auto;
    padding:0 32px;
  }

  /* ---------- HEADER ---------- */
  header{
    position:sticky;
    top:0;
    z-index:100;
    background:rgba(43,26,16,0.92);
    backdrop-filter:blur(6px);
    color:var(--cream);
  }
  header .wrap{
    display:flex;
    align-items:center;
    justify-content:space-between;
    padding-top:18px;
    padding-bottom:18px;
  }
  .brand{
    font-family:'Space Mono', monospace;
    font-weight:700;
    font-size:15px;
    letter-spacing:1.5px;
    text-transform:uppercase;
  }
  .brand span{color:var(--gold);}
  nav{display:flex; gap:28px; align-items:center;}
  nav a{
    font-size:14px;
    letter-spacing:0.3px;
    opacity:0.85;
    transition:opacity 0.2s;
  }
  nav a:hover{opacity:1;}
  .nav-cta{
    background:var(--gold);
    color:var(--ink);
    padding:9px 18px;
    border-radius:100px;
    font-weight:700;
    font-size:13px;
  }
  .nav-links{display:flex; gap:24px;}
  @media (max-width:720px){
    .nav-links{display:none;}
  }

  /* ---------- HERO ---------- */
  .hero{
    background:var(--ink);
    color:var(--cream);
    position:relative;
    overflow:hidden;
    padding:96px 0 70px;
  }
  .hero .wrap{
    display:grid;
    grid-template-columns:1.15fr 0.85fr;
    gap:48px;
    align-items:center;
  }
  @media (max-width:860px){
    .hero .wrap{grid-template-columns:1fr; text-align:left;}
  }
  .eyebrow{
    font-family:'Space Mono', monospace;
    font-size:13px;
    letter-spacing:2px;
    text-transform:uppercase;
    color:var(--gold);
    margin-bottom:18px;
    display:flex;
    align-items:center;
    gap:10px;
  }
  .eyebrow::before{
    content:'';
    width:26px; height:1px;
    background:var(--gold);
    display:inline-block;
  }
  .hero h1{
    font-size:clamp(42px, 6vw, 76px);
    color:var(--cream);
    margin-bottom:22px;
  }
  .hero h1 em{
    font-style:normal;
    color:var(--gold);
  }
  .hero p.lead{
    font-size:18px;
    max-width:460px;
    color:var(--steam);
    margin-bottom:34px;
  }
  .cta-row{display:flex; gap:14px; flex-wrap:wrap;}
  .btn{
    display:inline-flex;
    align-items:center;
    gap:8px;
    padding:14px 26px;
    border-radius:100px;
    font-weight:700;
    font-size:15px;
    transition:transform 0.2s ease, box-shadow 0.2s ease;
  }
  .btn-primary{
    background:var(--gold);
    color:var(--ink);
  }
  .btn-primary:hover{transform:translateY(-2px); box-shadow:0 8px 20px rgba(217,164,65,0.35);}
  .btn-outline{
    border:1.5px solid var(--steam);
    color:var(--cream);
  }
  .btn-outline:hover{border-color:var(--gold); color:var(--gold);}

  /* Porra illustration */
  .porra-art{
    position:relative;
    display:flex;
    justify-content:center;
  }
  .gauge-badge{
    position:absolute;
    bottom:-14px;
    left:50%;
    transform:translateX(-50%);
    background:var(--ink-soft);
    border:1px solid var(--gold-deep);
    border-radius:100px;
    padding:8px 18px;
    font-family:'Space Mono', monospace;
    font-size:12.5px;
    color:var(--gold);
    letter-spacing:0.5px;
    white-space:nowrap;
  }

  /* ---------- BUBBLE DIVIDER ---------- */
  .bubble-divider{
    background:var(--ink);
    padding-bottom:6px;
  }
  .bubble-divider svg{width:100%; height:32px;}

  /* ---------- STORY ---------- */
  .story{
    background:var(--cream-soft);
    padding:100px 0;
  }
  .section-head{
    margin-bottom:56px;
    max-width:640px;
  }
  .section-head .eyebrow{color:var(--copper);}
  .section-head .eyebrow::before{background:var(--copper);}
  .section-head h2{
    font-size:clamp(30px,4vw,44px);
    color:var(--ink);
  }
  .timeline{
    display:grid;
    grid-template-columns:1fr 1fr;
    gap:40px;
  }
  @media (max-width:760px){
    .timeline{grid-template-columns:1fr;}
  }
  .tl-item{
    border-top:2px solid var(--gold-deep);
    padding-top:22px;
    position:relative;
  }
  .tl-year{
    font-family:'Space Mono', monospace;
    font-size:14px;
    color:var(--copper);
    font-weight:700;
    letter-spacing:1px;
    margin-bottom:10px;
    display:block;
  }
  .tl-item h3{
    font-size:24px;
    margin-bottom:12px;
    color:var(--ink);
  }
  .tl-item p{
    font-size:15.5px;
    color:var(--ink-soft);
    max-width:420px;
  }

  /* ---------- MENU ---------- */
  .menu{
    background:var(--ink);
    color:var(--cream);
    padding:100px 0;
  }
  .menu .section-head .eyebrow{color:var(--gold);}
  .menu .section-head .eyebrow::before{background:var(--gold);}
  .menu .section-head h2{color:var(--cream);}
  .menu-cols{
    display:grid;
    grid-template-columns:1fr 1fr;
    gap:60px;
  }
  @media (max-width:760px){
    .menu-cols{grid-template-columns:1fr; gap:48px;}
  }
  .menu-col-title{
    font-family:'Space Mono', monospace;
    text-transform:uppercase;
    letter-spacing:2px;
    font-size:13px;
    color:var(--gold);
    margin-bottom:22px;
    padding-bottom:12px;
    border-bottom:1px solid var(--ink-soft);
  }
  .menu-item{
    display:flex;
    justify-content:space-between;
    align-items:baseline;
    gap:16px;
    padding:16px 0;
    border-bottom:1px dashed rgba(247,236,216,0.15);
  }
  .menu-item:last-child{border-bottom:none;}
  .menu-item h4{
    font-size:17px;
    font-weight:600;
    color:var(--cream);
  }
  .menu-item p{
    font-size:13.5px;
    color:var(--steam);
    margin-top:4px;
  }

  /* ---------- HOURS / LOCATION ---------- */
  .hours{
    background:var(--copper);
    color:var(--cream);
    padding:80px 0;
  }
  .hours .wrap{
    display:grid;
    grid-template-columns:1fr 1fr;
    gap:40px;
    align-items:center;
  }
  @media (max-width:760px){
    .hours .wrap{grid-template-columns:1fr;}
  }
  .big-hours{
    font-family:'Ultra', serif;
    font-size:clamp(48px,7vw,88px);
    line-height:1;
  }
  .hours-sub{
    font-family:'Space Mono', monospace;
    font-size:14px;
    letter-spacing:1px;
    text-transform:uppercase;
    margin-top:12px;
    opacity:0.9;
  }
  .hours-detail p{
    font-size:15.5px;
    margin-bottom:10px;
  }
  .hours-detail .addr{
    font-weight:700;
    font-size:17px;
    margin-bottom:14px;
  }
  .hours .btn-outline{border-color:rgba(247,236,216,0.5);}
  .hours .btn-outline:hover{border-color:var(--cream); color:var(--cream);}

  /* ---------- CONTACT ---------- */
  .contact{
    background:var(--cream-soft);
    padding:100px 0;
  }
  .contact-cards{
    display:grid;
    grid-template-columns:1fr 1fr;
    gap:24px;
  }
  @media (max-width:760px){
    .contact-cards{grid-template-columns:1fr;}
  }
  .card{
    background:var(--cream);
    border:1px solid #E7D9BE;
    border-radius:18px;
    padding:32px;
  }
  .card h3{
    font-size:21px;
    margin-bottom:10px;
    color:var(--ink);
  }
  .card p{
    font-size:15px;
    color:var(--ink-soft);
    margin-bottom:22px;
  }
  .card .btn-primary{width:100%; justify-content:center;}

  /* ---------- FOOTER ---------- */
  footer{
    background:var(--ink);
    color:var(--steam);
    padding:44px 0;
    font-size:14px;
  }
  footer .wrap{
    display:flex;
    justify-content:space-between;
    flex-wrap:wrap;
    gap:16px;
  }
  footer a:hover{color:var(--gold);}

  /* ---------- FLOATING WHATSAPP ---------- */
  .float-wa{
    position:fixed;
    bottom:24px;
    right:24px;
    background:var(--gold);
    color:var(--ink);
    width:58px;
    height:58px;
    border-radius:50%;
    display:flex;
    align-items:center;
    justify-content:center;
    box-shadow:0 10px 24px rgba(0,0,0,0.25);
    z-index:200;
    transition:transform 0.2s;
  }
  .float-wa:hover{transform:scale(1.08);}

  @media (prefers-reduced-motion: reduce){
    html{scroll-behavior:auto;}
    *{transition:none !important; animation:none !important;}
  }
</style>
</head>
<body>

<header>
  <div class="wrap">
    <div class="brand">Churrería <span>Rubén</span> · Aspe</div>
    <nav>
      <div class="nav-links">
        <a href="#historia">Historia</a>
        <a href="#menu">Menú</a>
        <a href="#horario">Horario</a>
        <a href="#resenas">Reseñas</a>
      </div>
      <a class="nav-cta" href="https://wa.me/34665692896?text=Hola%2C%20quer%C3%ADa%20hacer%20un%20pedido%20de%20porras" target="_blank" rel="noopener">WhatsApp</a>
    </nav>
  </div>
</header>

<section class="hero">
  <div class="wrap">
    <div>
      <div class="eyebrow">Aspe · Alicante · desde 2021</div>
      <h1>Porras con<br><em>aire por dentro.</em></h1>
      <p class="lead">Hechas al punto exacto de temperatura del aceite, cada mañana desde las 6:00. Ligeras por dentro, doradas y crujientes por fuera.</p>
      <div class="cta-row">
        <a class="btn btn-primary" href="https://wa.me/34665692896?text=Hola%2C%20quer%C3%ADa%20hacer%20un%20pedido%20de%20porras" target="_blank" rel="noopener">Pedir por WhatsApp</a>
        <a class="btn btn-outline" href="#horario">Ver horario y ubicación</a>
      </div>
    </div>
    <div class="porra-art">
      <svg viewBox="0 0 260 260" width="260" height="260">
        <circle cx="130" cy="130" r="118" fill="none" stroke="#40291A" stroke-width="1"/>
        <!-- porra ring cross-section -->
        <path d="M130 40 C190 40 232 78 232 130 C232 182 190 220 130 220 C70 220 28 182 28 130 C28 78 70 40 130 40 Z"
              fill="#B5822C" stroke="#2B1A10" stroke-width="3"/>
        <path d="M130 78 C164 78 190 100 190 130 C190 160 164 182 130 182 C96 182 70 160 70 130 C70 100 96 78 130 78 Z"
              fill="#F7ECD8"/>
        <!-- crust texture lines -->
        <path d="M60 90 Q130 60 200 90" fill="none" stroke="#8C5A1F" stroke-width="2.5" opacity="0.55"/>
        <path d="M50 150 Q130 190 210 150" fill="none" stroke="#8C5A1F" stroke-width="2.5" opacity="0.45"/>
        <!-- air pockets -->
        <circle cx="108" cy="115" r="9" fill="#EAD9B4"/>
        <circle cx="145" cy="105" r="6" fill="#EAD9B4"/>
        <circle cx="122" cy="145" r="7" fill="#EAD9B4"/>
        <circle cx="155" cy="140" r="10" fill="#EAD9B4"/>
        <circle cx="98" cy="150" r="5" fill="#EAD9B4"/>
      </svg>
      <div class="gauge-badge mono">◉ 190°C — el punto exacto</div>
    </div>
  </div>
</section>

<div class="bubble-divider">
  <svg viewBox="0 0 1200 32" preserveAspectRatio="none">
    <circle cx="20" cy="16" r="4" fill="#D9A441"/>
    <circle cx="70" cy="10" r="3" fill="#D9A441" opacity="0.6"/>
    <circle cx="140" cy="22" r="5" fill="#D9A441"/>
    <circle cx="210" cy="8" r="2.5" fill="#D9A441" opacity="0.5"/>
    <circle cx="280" cy="18" r="4" fill="#D9A441"/>
    <circle cx="350" cy="12" r="3" fill="#D9A441" opacity="0.6"/>
    <circle cx="420" cy="24" r="5" fill="#D9A441"/>
    <circle cx="490" cy="9" r="2.5" fill="#D9A441" opacity="0.5"/>
    <circle cx="560" cy="17" r="4" fill="#D9A441"/>
    <circle cx="630" cy="11" r="3" fill="#D9A441" opacity="0.6"/>
    <circle cx="700" cy="21" r="5" fill="#D9A441"/>
    <circle cx="770" cy="8" r="2.5" fill="#D9A441" opacity="0.5"/>
    <circle cx="840" cy="18" r="4" fill="#D9A441"/>
    <circle cx="910" cy="12" r="3" fill="#D9A441" opacity="0.6"/>
    <circle cx="980" cy="23" r="5" fill="#D9A441"/>
    <circle cx="1050" cy="9" r="2.5" fill="#D9A441" opacity="0.5"/>
    <circle cx="1120" cy="17" r="4" fill="#D9A441"/>
    <circle cx="1180" cy="11" r="3" fill="#D9A441" opacity="0.6"/>
  </svg>
</div>

<section class="story" id="historia">
  <div class="wrap">
    <div class="section-head">
      <div class="eyebrow">Nuestra historia</div>
      <h2>Una receta que viene de familia.</h2>
    </div>
    <div class="timeline">
      <div class="tl-item">
        <span class="tl-year mono">NOVELDA</span>
        <h3>Más de 26 años de tradición</h3>
        <p>Todo empezó con mis padres, en Novelda (Capellán Margall, 77), donde siguen haciendo porras cada día con el mismo cuidado desde hace más de 26 años.</p>
      </div>
      <div class="tl-item">
        <span class="tl-year mono">ASPE, 2021</span>
        <h3>5 años trayendo esa tradición a Aspe</h3>
        <p>Con su ayuda, montamos Churrería Rubén en Aspe para seguir haciendo las cosas igual: con el punto exacto de aceite y sin prisa.</p>
      </div>
    </div>
  </div>
</section>

<section class="menu" id="menu">
  <div class="wrap">
    <div class="section-head">
      <div class="eyebrow">Para desayunar</div>
      <h2>Dulce o salado, como más te apetezca.</h2>
    </div>
    <div class="menu-cols">
      <div>
        <div class="menu-col-title">Dulce</div>
        <div class="menu-item">
          <div>
            <h4>Porras</h4>
            <p>Con aire por dentro, doradas y crujientes por fuera.</p>
          </div>
        </div>
        <div class="menu-item">
          <div>
            <h4>Chocolate a la taza</h4>
            <p>Espeso, para mojar sin prisa.</p>
          </div>
        </div>
        <div class="menu-item">
          <div>
            <h4>Café</h4>
            <p>Recién hecho, como acompañamiento perfecto.</p>
          </div>
        </div>
      </div>
      <div>
        <div class="menu-col-title">Salado</div>
        <div class="menu-item">
          <div>
            <h4>Tostada de jamón serrano</h4>
          </div>
        </div>
        <div class="menu-item">
          <div>
            <h4>Tostada de jamón york y tomate</h4>
          </div>
        </div>
        <div class="menu-item">
          <div>
            <h4>Tostada de atún</h4>
          </div>
        </div>
        <div class="menu-item">
          <div>
            <h4>Tostada de mantequilla</h4>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<section class="hours" id="horario">
  <div class="wrap">
    <div>
      <div class="big-hours">6:00–12:00</div>
      <div class="hours-sub mono">Todos los días, sin excepción</div>
    </div>
    <div class="hours-detail">
      <p class="addr">Av. Pintor Pastor Calpena, 2 · 03680 Aspe (Alicante)</p>
      <p>Para tomar en el local o para llevar.</p>
      <p>665 69 28 96</p>
      <div class="cta-row" style="margin-top:18px;">
        <a class="btn btn-outline" href="https://www.google.com/maps/search/?api=1&query=Churrer%C3%ADa+Rub%C3%A9n+Aspe" target="_blank" rel="noopener">Cómo llegar</a>
      </div>
    </div>
  </div>
  <div class="wrap" style="margin-top:44px;">
    <iframe
      src="https://www.google.com/maps?q=Churrer%C3%ADa+Rub%C3%A9n+Aspe,+Av.+Pintor+Pastor+Calpena,+2,+03680+Aspe,+Alicante&output=embed"
      width="100%" height="280" style="border:0; border-radius:14px;" loading="lazy"
      referrerpolicy="no-referrer-when-downgrade" title="Mapa Churrería Rubén Aspe">
    </iframe>
  </div>
</section>

<section class="story" id="resenas" style="padding-top:80px; padding-bottom:80px;">
  <div class="wrap">
    <div class="section-head">
      <div class="eyebrow">Lo que dicen en Google</div>
      <h2>4,6 sobre 5, con clientes que repiten cada semana.</h2>
    </div>
    <div class="timeline">
      <div class="tl-item">
        <span class="tl-year mono">★★★★★</span>
        <h3>Rapidez y buen trato</h3>
        <p>Varios clientes destacan lo bien atendidos que se sienten desde el primer día, con un ambiente cercano y familiar en cada visita.</p>
      </div>
      <div class="tl-item">
        <span class="tl-year mono">★★★★★</span>
        <h3>Porras recién hechas</h3>
        <p>Se repite mucho la misma idea: las porras salen calientes y en el punto justo, y el chocolate acompaña perfecto para mojar sin prisa.</p>
      </div>
    </div>
  </div>
</section>

<section class="contact" id="contacto">
  <div class="wrap">
    <div class="section-head">
      <div class="eyebrow">Encárganos lo tuyo</div>
      <h2>Habla con nosotros directamente.</h2>
    </div>
    <div class="contact-cards">
      <div class="card">
        <h3>Pedido del día</h3>
        <p>Porras, chocolate, tostadas... para llevar o para tomar aquí mismo.</p>
        <a class="btn btn-primary" href="https://wa.me/34665692896?text=Hola%2C%20quer%C3%ADa%20hacer%20un%20pedido%20de%20porras" target="_blank" rel="noopener">Escribir por WhatsApp</a>
      </div>
      <div class="card">
        <h3>Encargos y eventos</h3>
        <p>Bandejas para comuniones, desayunos de empresa o cualquier celebración.</p>
        <a class="btn btn-primary" href="https://wa.me/34665692896?text=Hola%2C%20quer%C3%ADa%20informaci%C3%B3n%20para%20encargar%20una%20bandeja%20para%20un%20evento" target="_blank" rel="noopener">Consultar encargo</a>
      </div>
    </div>
  </div>
</section>

<footer>
  <div class="wrap">
    <div>© 2026 Churrería Rubén · Aspe, Alicante</div>
    <div style="display:flex; gap:20px;">
      <a href="https://www.instagram.com/aspe_churreriaruben/" target="_blank" rel="noopener">Instagram</a>
      <a href="https://www.tiktok.com/@elchurrerodeaspe" target="_blank" rel="noopener">TikTok</a>
    </div>
  </div>
</footer>

<a class="float-wa" href="https://wa.me/34665692896?text=Hola%2C%20quer%C3%ADa%20hacer%20un%20pedido%20de%20porras" target="_blank" rel="noopener" aria-label="Escribir por WhatsApp">
  <svg width="28" height="28" viewBox="0 0 24 24" fill="none">
    <path d="M17.6 6.32A7.85 7.85 0 0 0 12.05 4C7.6 4 4 7.6 4 12.05c0 1.42.37 2.8 1.08 4.02L4 20l4.05-1.06a8.02 8.02 0 0 0 3.99 1.02h.01c4.45 0 8.05-3.6 8.05-8.05 0-2.15-.84-4.17-2.5-5.59Zm-5.55 12.4h-.01a6.7 6.7 0 0 1-3.4-.93l-.24-.14-2.4.63.64-2.34-.16-.24a6.68 6.68 0 0 1-1.02-3.55c0-3.7 3.01-6.71 6.72-6.71 1.8 0 3.48.7 4.75 1.97a6.67 6.67 0 0 1 1.97 4.75c0 3.71-3.01 6.56-6.85 6.56Zm3.68-4.96c-.2-.1-1.18-.58-1.36-.65-.18-.07-.32-.1-.45.1-.13.2-.51.65-.63.78-.12.13-.23.15-.43.05-.2-.1-.86-.32-1.63-1.01-.6-.54-1.01-1.2-1.13-1.4-.12-.2-.01-.31.09-.4.09-.1.2-.24.3-.36.1-.12.13-.2.2-.34.06-.13.03-.25-.02-.35-.05-.1-.45-1.08-.61-1.48-.16-.38-.33-.33-.45-.34-.12 0-.25-.01-.38-.01-.13 0-.35.05-.53.25-.18.2-.7.68-.7 1.66 0 .98.72 1.93.82 2.06.1.13 1.4 2.14 3.4 3 .48.2.85.33 1.14.42.48.15.91.13 1.25.08.38-.06 1.18-.48 1.35-.95.17-.47.17-.87.12-.95-.05-.09-.18-.14-.38-.24Z" fill="#2B1A10"/>
  </svg>
</a>

</body>
</html>
Uploading churreria-ruben-aspe.html…]()

