<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Dra. Marcella Maia | Harmonização Facial</title>
<meta name="description" content="Dra. Marcella Maia — Cirurgiã-Dentista e residente em Harmonização Facial. Bioestimulador de colágeno, Botox, preenchimento facial, microagulhamento, peptídeos e fios de PDO.">

<meta property="og:title" content="Dra. Marcella Maia | Harmonização Facial">
<meta property="og:description" content="Cirurgiã-Dentista e residente em Harmonização Facial. Realce sua beleza, preserve sua essência.">
<meta property="og:type" content="website">
<meta property="og:image" content="about.jpeg">
<meta name="robots" content="index, follow">
<link rel="canonical" href="https://dramarcellamaia.com.br/">

<link rel="icon" href="m-glyph.png" type="image/png">

<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "Dentist",
  "name": "Dra. Marcella Maia",
  "image": "about.jpeg",
  "description": "Cirurgiã-Dentista, CRO-TO 1729, residente em Harmonização Facial. Bioestimulador de colágeno, Botox, preenchimento facial, microagulhamento, peptídeos e fios de PDO.",
  "telephone": "+5563984636750",
  "email": "marcellacalaca@gmail.com",
  "sameAs": ["https://instagram.com/dramarcellamaiaa"],
  "medicalSpecialty": "Harmonização Facial"
}
</script>

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,300;0,400;0,500;0,600;1,400&family=Manrope:wght@300;400;500;600;700&display=swap" rel="stylesheet">

<style>
:root{
  --bordo:#5A1F2B;
  --rose-burnt:#B86D6B;
  --rose-light:#E9A09D;
  --off-white:#FAF9F7;
  --graphite:#252124;
  --line: rgba(37,33,36,0.14);
  --line-on-bordo: rgba(250,249,247,0.22);
  --serif: 'Cormorant Garamond', serif;
  --sans: 'Manrope', sans-serif;
  --ease: cubic-bezier(.22,.61,.36,1);
}

*{box-sizing:border-box;}
html{scroll-behavior:smooth;}
body{
  margin:0;
  background:var(--off-white);
  color:var(--graphite);
  font-family:var(--sans);
  font-weight:400;
  -webkit-font-smoothing:antialiased;
  overflow-x:hidden;
}
img{max-width:100%;display:block;}
a{color:inherit;text-decoration:none;}
button{font-family:inherit;cursor:pointer;background:none;border:none;color:inherit;}

::selection{background:var(--rose-light);color:var(--bordo);}

@media (prefers-reduced-motion: reduce){
  *{animation-duration:0.001ms !important; animation-iteration-count:1 !important; transition-duration:0.001ms !important; scroll-behavior:auto !important;}
}

:focus-visible{outline:2px solid var(--bordo); outline-offset:3px;}

.wrap{
  max-width:1280px;
  margin:0 auto;
  padding:0 6vw;
}
@media (max-width:640px){ .wrap{padding:0 24px;} }

.eyebrow{
  font-family:var(--sans);
  font-size:12.5px;
  letter-spacing:0.14em;
  color:var(--rose-burnt);
  font-weight:600;
}

h1,h2,h3,h4{
  font-family:var(--serif);
  font-weight:500;
  margin:0;
  color:var(--bordo);
  letter-spacing:0.002em;
}

.serif-italic{font-style:italic; font-weight:400;}

p{line-height:1.7; margin:0;}

.btn{
  display:inline-flex;
  align-items:center;
  gap:10px;
  font-family:var(--sans);
  font-size:13.5px;
  font-weight:600;
  letter-spacing:0.05em;
  padding:16px 30px;
  border-radius:2px;
  transition:all .45s var(--ease);
  white-space:nowrap;
}
.btn-primary{
  background:var(--bordo);
  color:var(--off-white);
}
.btn-primary:hover{
  background:#431720;
  gap:16px;
}
.btn-outline{
  border:1px solid var(--graphite);
  color:var(--graphite);
}
.btn-outline:hover{
  border-color:var(--bordo);
  color:var(--bordo);
  gap:16px;
}
.btn-arrow{transition:transform .45s var(--ease);}
.btn-primary:hover .btn-arrow, .btn-outline:hover .btn-arrow{transform:translateX(3px);}

/* ================= CURSOR ================= */
#cursor-dot{
  position:fixed;
  width:26px;height:26px;
  border-radius:50%;
  border:1px solid rgba(90,31,43,0.35);
  pointer-events:none;
  z-index:9999;
  transform:translate(-50%,-50%);
  transition:width .3s var(--ease), height .3s var(--ease), border-color .3s var(--ease), opacity .3s;
  mix-blend-mode:multiply;
  opacity:0;
}
#cursor-dot.active{opacity:1;}
#cursor-dot.hovering{
  width:56px;height:56px;
  background:rgba(184,109,107,0.14);
  border-color:rgba(184,109,107,0.4);
}

/* ================= NAVBAR ================= */
header{
  position:fixed;
  top:0; left:0; right:0;
  z-index:1000;
  padding:26px 0;
  transition:all .5s var(--ease);
}
header .wrap{
  display:flex;
  align-items:center;
  justify-content:space-between;
}
header.scrolled{
  padding:16px 0;
  background:rgba(250,249,247,0.86);
  backdrop-filter:blur(14px);
  -webkit-backdrop-filter:blur(14px);
  box-shadow:0 1px 0 var(--line);
}
.nav-logo{
  position:relative;
  display:block;
  height:40px;
  width:190px;
}
.nav-logo img{
  position:absolute;
  left:0; top:50%;
  transform:translateY(-50%);
  height:52px;
  width:auto;
  transition:opacity .5s var(--ease);
}
.nav-logo .logo-white{opacity:1;}
.nav-logo .logo-color{opacity:0;}
header.scrolled .nav-logo .logo-white{opacity:0;}
header.scrolled .nav-logo .logo-color{opacity:1;}
@media (max-width:400px){
  .nav-logo{width:150px; height:34px;}
  .nav-logo img{height:42px;}
}

nav.nav-links{
  display:flex;
  align-items:center;
  gap:38px;
}
.nav-links a:not(.btn){
  font-size:13px;
  letter-spacing:0.03em;
  color:var(--off-white);
  position:relative;
  padding-bottom:4px;
  transition:color .5s var(--ease);
}
header.scrolled .nav-links a:not(.btn){color:var(--graphite);}
.nav-links a:not(.btn)::after{
  content:'';
  position:absolute;
  left:0;right:100%;bottom:0;
  height:1px;
  background:currentColor;
  transition:right .35s var(--ease);
}
.nav-links a:not(.btn):hover::after{right:0;}

.nav-cta{
  border:1px solid var(--off-white);
  color:var(--off-white) !important;
  padding:11px 22px;
  font-size:11.5px;
}
header.scrolled .nav-cta{
  border-color:var(--bordo);
  background:var(--bordo);
  color:var(--off-white) !important;
}
.nav-cta:hover{background:var(--off-white); color:var(--bordo) !important;}
header.scrolled .nav-cta:hover{background:#431720; color:var(--off-white) !important;}

#menu-toggle{display:none;}
.hamburger{
  display:none;
  flex-direction:column;
  gap:6px;
  width:28px;
  z-index:1200;
}
.hamburger span{
  height:1px;
  background:var(--off-white);
  transition:all .4s var(--ease);
}
header.scrolled .hamburger span{background:var(--bordo);}
body.menu-open .hamburger span{background:var(--bordo) !important;}

@media (max-width:920px){
  nav.nav-links{
    position:fixed;
    inset:0;
    background:var(--off-white);
    flex-direction:column;
    justify-content:center;
    align-items:flex-start;
    padding:0 40px;
    gap:26px;
    transform:translateX(100%);
    transition:transform .55s var(--ease);
  }
  nav.nav-links a:not(.btn){color:var(--bordo) !important; font-family:var(--serif); font-size:28px;}
  body.menu-open nav.nav-links{transform:translateX(0);}
  .nav-cta{border-color:var(--bordo); color:var(--bordo) !important; margin-top:10px;}
  .hamburger{display:flex;}
}

/* ================= HERO ================= */
.hero{
  position:relative;
  min-height:100vh;
  display:grid;
  grid-template-columns:1.05fr 0.95fr;
  align-items:stretch;
  background:var(--bordo);
  overflow:hidden;
}
.hero-copy{
  position:relative;
  z-index:3;
  display:flex;
  flex-direction:column;
  justify-content:center;
  padding:160px 5vw 90px 6vw;
  color:var(--off-white);
}
.hero-eyebrow{
  font-size:12.5px;
  letter-spacing:0.16em;
  color:var(--rose-light);
  font-weight:600;
  margin-bottom:26px;
  opacity:0;
}
.hero-name{
  font-family:var(--serif);
  font-size:clamp(38px, 5.4vw, 70px);
  line-height:1.02;
  color:var(--off-white);
  letter-spacing:0.005em;
  max-width:640px;
  opacity:0;
}
.hero-role{
  font-family:var(--sans);
  font-size:14px;
  letter-spacing:0.03em;
  color:var(--rose-light);
  margin-top:20px;
  padding-top:20px;
  border-top:1px solid var(--line-on-bordo);
  max-width:420px;
  opacity:0;
}
.hero-desc{
  font-size:15.5px;
  line-height:1.85;
  color:rgba(250,249,247,0.78);
  max-width:400px;
  margin-top:32px;
  opacity:0;
}
.hero-ctas{
  display:flex;
  align-items:center;
  gap:20px;
  margin-top:48px;
  flex-wrap:wrap;
  opacity:0;
}
.hero-ctas .btn-outline{
  border-color:rgba(250,249,247,0.5);
  color:var(--off-white);
}
.hero-ctas .btn-outline:hover{
  border-color:var(--off-white);
  color:var(--off-white);
}
.hero-ctas .btn-primary{background:var(--rose-light); color:var(--bordo);}
.hero-ctas .btn-primary:hover{background:var(--off-white);}

.hero-media{
  position:relative;
  overflow:hidden;
}
.hero-media-inner{
  position:absolute;
  inset:0;
  transform:scale(1.12);
}
.hero-media img{
  width:100%;height:100%;
  object-fit:cover;
  object-position:top center;
  filter:saturate(0.92) contrast(1.02);
}
.hero-media::before{
  content:'';
  position:absolute;
  inset:0;
  background:linear-gradient(100deg, var(--bordo) 0%, rgba(90,31,43,0.15) 22%, rgba(90,31,43,0) 46%);
  z-index:2;
}
.hero-media::after{
  content:'';
  position:absolute;
  left:0; top:0; bottom:0; width:1px;
  background:var(--line-on-bordo);
}
.hero-glyph{
  position:absolute;
  bottom:-6%;
  left:-8%;
  width:34%;
  opacity:0.07;
  filter:brightness(0) invert(1);
  z-index:1;
  pointer-events:none;
}
.hero-caption{
  position:absolute;
  right:34px;
  bottom:34px;
  z-index:3;
  color:var(--off-white);
  font-size:11px;
  letter-spacing:0.1em;
  writing-mode:vertical-rl;
  opacity:0.55;
}
.scroll-cue{
  position:absolute;
  left:6vw;
  bottom:38px;
  z-index:3;
  display:flex;
  align-items:center;
  gap:12px;
  color:rgba(250,249,247,0.55);
  font-size:11px;
  letter-spacing:0.12em;
}
.scroll-cue .line{width:34px;height:1px;background:currentColor;position:relative;overflow:hidden;}
.scroll-cue .line::after{
  content:'';
  position:absolute;left:-100%;top:0;bottom:0;width:100%;
  background:var(--off-white);
  animation:scrollcue 2.6s ease-in-out infinite;
}
@keyframes scrollcue{
  0%{left:-100%;} 50%{left:0;} 100%{left:100%;}
}

@media (max-width:920px){
  .hero{grid-template-columns:1fr; min-height:auto;}
  .hero-media{height:56vh; order:1;}
  .hero-copy{padding:132px 24px 60px; order:2;}
  .hero-media::before{background:linear-gradient(180deg, rgba(90,31,43,0) 55%, var(--bordo) 100%);}
  .hero-media::after{display:none;}
  .hero-caption{display:none;}
  .scroll-cue{display:none;}
}

/* ================= SECTION HELPERS ================= */
section{position:relative;}
.section-pad{padding:130px 0;}
@media (max-width:768px){.section-pad{padding:88px 0;}}

.reveal{
  opacity:0;
  transform:translateY(22px);
  transition:opacity 1s var(--ease), transform 1s var(--ease);
}
.reveal.in{opacity:1; transform:translateY(0);}
.reveal-delay-1{transition-delay:.1s;}
.reveal-delay-2{transition-delay:.2s;}
.reveal-delay-3{transition-delay:.3s;}

.kicker{
  display:flex;
  align-items:center;
  gap:14px;
  margin-bottom:22px;
}
.kicker .num{
  font-family:var(--serif);
  font-style:italic;
  color:var(--rose-burnt);
  font-size:15px;
}
.kicker .rule{width:40px;height:1px;background:var(--rose-burnt);}
.kicker .label{font-size:12px;letter-spacing:0.12em;color:var(--graphite);opacity:0.6;font-weight:600;}

/* ================= POSITIONING ================= */
.positioning{background:var(--off-white);}
.positioning-grid{
  display:grid;
  grid-template-columns:1fr 1fr;
  gap:60px;
  align-items:end;
}
.positioning h2{
  font-size:clamp(34px, 4.4vw, 58px);
  line-height:1.12;
}
.positioning .support{
  padding-bottom:6px;
}
.positioning .support p{
  font-size:16.5px;
  color:var(--graphite);
  max-width:420px;
  margin-bottom:28px;
}
@media (max-width:860px){
  .positioning-grid{grid-template-columns:1fr; gap:34px;}
}

/* ================= ABOUT ================= */
.about{background:var(--off-white);}
.about-grid{
  display:grid;
  grid-template-columns:0.85fr 1.15fr;
  gap:0 70px;
  align-items:center;
}
.about-media{
  position:relative;
}
.about-media img{
  width:100%;
  aspect-ratio:4/5;
  object-fit:cover;
  object-position:top;
}
.about-media-frame{
  position:absolute;
  top:24px; left:24px;
  right:-24px; bottom:-24px;
  border:1px solid var(--rose-burnt);
  z-index:-1;
}
.about-media-accent{
  position:absolute;
  width:44%;
  top:-13%;
  right:-15%;
  aspect-ratio:4/5;
  border:6px solid var(--off-white);
  box-shadow:0 20px 50px rgba(37,33,36,0.18);
  z-index:2;
}
.about-media-accent img{width:100%; height:100%; object-fit:cover; object-position:top;}
@media (max-width:860px){
  .about-media-accent{width:34%; right:-6%; top:-8%;}
}
.about-copy .credential{
  font-size:14px;
  color:var(--rose-burnt);
  letter-spacing:0.02em;
  margin-top:18px;
  margin-bottom:34px;
  line-height:1.9;
}
.about-copy h2{
  font-size:clamp(30px,3.6vw,46px);
  line-height:1.15;
  margin-bottom:26px;
}
.about-copy p{
  font-size:16px;
  color:var(--graphite);
  max-width:480px;
  margin-bottom:18px;
}
.about-values{
  display:flex;
  gap:38px;
  margin-top:40px;
  padding-top:34px;
  border-top:1px solid var(--line);
  flex-wrap:wrap;
}
.about-values .item{max-width:190px;}
.about-values .item .lbl{
  font-family:var(--serif);
  font-style:italic;
  color:var(--bordo);
  font-size:19px;
  margin-bottom:6px;
  display:block;
}
.about-values .item p{font-size:13.5px; color:var(--graphite); opacity:0.75;}

@media (max-width:860px){
  .about-grid{grid-template-columns:1fr; gap:50px 0;}
  .about-media-frame{display:none;}
}

/* ================= PRESENÇA (GALERIA) ================= */
.presence{background:var(--off-white);}
.presence-head{max-width:560px; margin-bottom:60px;}
.presence-head h2{font-size:clamp(30px,3.8vw,48px); line-height:1.15;}
.presence-head p{margin-top:18px; font-size:15px; color:var(--graphite); opacity:0.75; max-width:440px;}
.presence-grid{
  display:grid;
  grid-template-columns:1.15fr 0.85fr 0.85fr;
  grid-template-rows:auto auto;
  gap:18px;
}
.presence-grid figure{margin:0; overflow:hidden; position:relative;}
.presence-grid img{width:100%; height:100%; object-fit:cover; object-position:top; display:block; transition:transform .8s var(--ease);}
.presence-grid figure:hover img{transform:scale(1.045);}
.p-tall{grid-row:span 2; aspect-ratio:3/4.3;}
.p-short{aspect-ratio:1/1;}
@media (max-width:860px){
  .presence-grid{grid-template-columns:1fr 1fr; grid-template-rows:auto;}
  .p-tall{grid-row:span 2; aspect-ratio:3/4;}
  .p-short{aspect-ratio:1/1;}
}
@media (max-width:560px){
  .presence-grid{grid-template-columns:1fr;}
  .p-tall{grid-row:auto; aspect-ratio:4/5;}
  .p-short{aspect-ratio:4/5;}
}

/* ================= PROCEDURES ================= */
.procedures{background:var(--bordo); color:var(--off-white);}
.procedures .kicker .label{color:var(--rose-light); opacity:0.9;}
.procedures .kicker .rule{background:var(--rose-light);}
.procedures .kicker .num{color:var(--rose-light);}
.procedures-head{
  display:flex;
  justify-content:space-between;
  align-items:flex-end;
  gap:40px;
  margin-bottom:70px;
}
.procedures-head h2{
  color:var(--off-white);
  font-size:clamp(32px,4vw,50px);
  max-width:560px;
  line-height:1.12;
}
.procedures-head p{
  color:rgba(250,249,247,0.65);
  max-width:280px;
  font-size:14.5px;
  padding-bottom:6px;
}
.proc-layout{
  display:grid;
  grid-template-columns:1.2fr 0.8fr;
  gap:60px;
  align-items:start;
}
.proc-list{border-top:1px solid var(--line-on-bordo);}
.proc-item{
  border-bottom:1px solid var(--line-on-bordo);
  padding:30px 0;
  cursor:pointer;
  transition:padding .4s var(--ease);
}
.proc-item-top{
  display:flex;
  align-items:baseline;
  gap:26px;
}
.proc-item .idx{
  font-family:var(--serif);
  font-style:italic;
  font-size:16px;
  color:var(--rose-light);
  min-width:28px;
}
.proc-item h3{
  color:var(--off-white);
  font-size:clamp(22px,2.6vw,32px);
  font-weight:400;
  transition:color .35s var(--ease), transform .35s var(--ease);
  flex:1;
}
.proc-item .plus{
  font-size:20px;
  color:var(--rose-light);
  transition:transform .4s var(--ease);
  font-weight:300;
}
.proc-item.active .plus{transform:rotate(45deg);}
.proc-item.active h3, .proc-item:hover h3{
  color:var(--rose-light);
  transform:translateX(8px);
}
.proc-item-body{
  max-height:0;
  overflow:hidden;
  transition:max-height .5s var(--ease), opacity .5s var(--ease), margin .5s var(--ease);
  opacity:0;
  margin-left:54px;
}
.proc-item.active .proc-item-body{
  max-height:120px;
  opacity:1;
  margin-top:14px;
}
.proc-item-body p{
  color:rgba(250,249,247,0.68);
  font-size:14.5px;
  max-width:460px;
}
.proc-media{
  position:sticky;
  top:120px;
  aspect-ratio:3/4;
  overflow:hidden;
  border:1px solid var(--line-on-bordo);
}
.proc-media img{
  width:100%;height:100%;object-fit:cover;object-position:top;
  transition:filter .6s var(--ease), transform 8s linear;
  filter:saturate(0.85) brightness(0.96);
}
.proc-media::after{
  content:'';
  position:absolute; inset:0;
  background:var(--tint, rgba(90,31,43,0));
  mix-blend-mode:multiply;
  transition:background .5s var(--ease);
}
.proc-media-label{
  position:absolute;
  left:20px; bottom:20px;
  color:var(--off-white);
  font-family:var(--serif);
  font-style:italic;
  font-size:20px;
  z-index:2;
  transition:opacity .4s var(--ease);
}

@media (max-width:900px){
  .proc-layout{grid-template-columns:1fr;}
  .proc-media{position:relative; top:0; aspect-ratio:4/5; order:-1; margin-bottom:20px;}
  .procedures-head{flex-direction:column; align-items:flex-start; gap:16px;}
}

/* ================= APPROACH ================= */
.approach{background:var(--off-white);}
.approach-head{max-width:620px; margin-bottom:80px;}
.approach-head h2{font-size:clamp(32px,4vw,50px); line-height:1.15;}
.pillars{
  display:grid;
  grid-template-columns:repeat(3,1fr);
  gap:0;
  border-top:1px solid var(--line);
}
.pillar{
  padding:44px 34px 10px 0;
  border-right:1px solid var(--line);
}
.pillar:last-child{border-right:none;}
.pillar .num{
  font-family:var(--serif);
  font-size:15px;
  color:var(--rose-burnt);
  letter-spacing:0.05em;
}
.pillar h3{
  font-size:26px;
  margin:22px 0 14px;
  color:var(--bordo);
}
.pillar p{font-size:14.5px; color:var(--graphite); opacity:0.78; max-width:230px;}
@media (max-width:760px){
  .pillars{grid-template-columns:1fr;}
  .pillar{border-right:none; border-bottom:1px solid var(--line); padding:34px 0;}
}

/* ================= RESULTS ================= */
.results{background:var(--off-white);}
.results-head{
  display:flex;
  justify-content:space-between;
  align-items:flex-end;
  gap:30px;
  margin-bottom:56px;
  flex-wrap:wrap;
}
.results-head h2{font-size:clamp(32px,4vw,50px);}
.results-grid{
  display:grid;
  grid-template-columns:repeat(3,1fr);
  gap:22px;
}
.result-slot{
  position:relative;
  aspect-ratio:3/4;
  background:linear-gradient(160deg, #F1EBE7, #F7F2EF);
  border:1px dashed var(--line);
  display:flex;
  flex-direction:column;
  align-items:center;
  justify-content:center;
  gap:14px;
  text-align:center;
  padding:20px;
}
.result-slot .ico{
  width:34px; height:34px;
  border:1px solid var(--rose-burnt);
  border-radius:50%;
  display:flex; align-items:center; justify-content:center;
  color:var(--rose-burnt);
  font-size:15px;
}
.result-slot span{
  font-size:12px;
  letter-spacing:0.05em;
  color:var(--graphite);
  opacity:0.55;
  max-width:150px;
}
.results-note{
  margin-top:30px;
  font-size:12.5px;
  color:var(--graphite);
  opacity:0.55;
  font-style:italic;
  max-width:520px;
}
.result-photo{
  position:relative;
  aspect-ratio:3/4;
  overflow:hidden;
  border:1px solid var(--line);
}
.result-photo img{
  width:100%; height:100%;
  object-fit:cover;
  object-position:center;
  display:block;
  transition:transform .7s var(--ease);
}
.result-photo:hover img{transform:scale(1.035);}
@media (max-width:760px){.results-grid{grid-template-columns:repeat(2,1fr);}}

/* ================= EXPERIENCE JOURNEY ================= */
.journey{background:var(--bordo); color:var(--off-white);}
.journey .kicker .label{color:var(--rose-light);}
.journey .kicker .rule{background:var(--rose-light);}
.journey .kicker .num{color:var(--rose-light);}
.journey-head h2{color:var(--off-white); font-size:clamp(32px,4vw,50px); max-width:560px; margin-bottom:70px; line-height:1.15;}
.journey-steps{
  display:grid;
  grid-template-columns:repeat(4,1fr);
  gap:0;
}
.jstep{
  padding:0 26px 0 0;
  border-left:1px solid var(--line-on-bordo);
  padding-left:26px;
}
.jstep .num{font-family:var(--serif); font-style:italic; font-size:36px; color:var(--rose-light);}
.jstep h3{color:var(--off-white); font-size:20px; font-weight:500; margin:18px 0 12px;}
.jstep p{font-size:13.5px; color:rgba(250,249,247,0.65);}
@media (max-width:880px){
  .journey-steps{grid-template-columns:1fr 1fr; row-gap:40px;}
}
@media (max-width:540px){
  .journey-steps{grid-template-columns:1fr; row-gap:36px;}
}

/* ================= IMPACT STATEMENT ================= */
.impact{
  background:var(--off-white);
  padding:180px 0;
  display:flex;
  align-items:center;
  justify-content:center;
  text-align:center;
}
.impact h2{
  font-size:clamp(32px, 6.4vw, 84px);
  line-height:1.12;
  max-width:1000px;
  color:var(--bordo);
}
.impact .accent{color:var(--rose-burnt);}
@media (max-width:640px){.impact{padding:120px 0;}}

/* ================= FAQ ================= */
.faq{background:var(--off-white);}
.faq-layout{
  display:grid;
  grid-template-columns:0.7fr 1.3fr;
  gap:60px;
}
.faq-side h2{font-size:clamp(30px,3.6vw,44px); line-height:1.15; max-width:340px;}
.faq-side p{margin-top:20px; color:var(--graphite); opacity:0.7; font-size:14.5px; max-width:300px;}
.faq-list{border-top:1px solid var(--line);}
.faq-item{border-bottom:1px solid var(--line);}
.faq-q{
  width:100%;
  text-align:left;
  display:flex;
  justify-content:space-between;
  align-items:center;
  gap:20px;
  padding:26px 0;
  font-family:var(--serif);
  font-size:19px;
  color:var(--bordo);
}
.faq-q .sign{font-size:20px; color:var(--rose-burnt); font-weight:300; transition:transform .4s var(--ease); flex-shrink:0;}
.faq-item.open .faq-q .sign{transform:rotate(45deg);}
.faq-a{
  max-height:0;
  overflow:hidden;
  transition:max-height .5s var(--ease), padding .5s var(--ease);
}
.faq-item.open .faq-a{max-height:200px; padding-bottom:26px;}
.faq-a p{font-size:15px; color:var(--graphite); opacity:0.78; max-width:560px;}
@media (max-width:860px){.faq-layout{grid-template-columns:1fr; gap:36px;}}

/* ================= INSTAGRAM ================= */
.instagram{background:var(--off-white);}
.insta-head{
  display:flex;
  justify-content:space-between;
  align-items:flex-end;
  gap:30px;
  margin-bottom:44px;
  flex-wrap:wrap;
}
.insta-head h2{font-size:clamp(30px,3.6vw,46px);}
.insta-head .handle{color:var(--rose-burnt); font-family:var(--serif); font-style:italic; font-size:19px;}
.insta-grid{
  display:grid;
  grid-template-columns:repeat(6,1fr);
  gap:10px;
}
.insta-tile{
  position:relative;
  aspect-ratio:1;
  display:block;
  overflow:hidden;
  transition:transform .5s var(--ease);
}
.insta-tile img{
  width:100%;height:100%;
  object-fit:cover;
  object-position:top;
  transition:transform .7s var(--ease), filter .5s var(--ease);
}
.insta-tile:hover{transform:translateY(-4px);}
.insta-tile:hover img{transform:scale(1.06); filter:brightness(0.6);}
.insta-hover{
  position:absolute; inset:0;
  display:flex; align-items:center; justify-content:center;
  color:var(--off-white);
  opacity:0;
  transition:opacity .4s var(--ease);
}
.insta-tile:hover .insta-hover{opacity:1;}
.insta-hover svg{width:24px;height:24px;}
@media (max-width:760px){.insta-grid{grid-template-columns:repeat(3,1fr);}}

/* ================= FINAL CTA ================= */
.final-cta{
  background:var(--bordo);
  color:var(--off-white);
  padding:150px 0;
  text-align:center;
  position:relative;
  overflow:hidden;
}
.final-cta h2{
  color:var(--off-white);
  font-size:clamp(34px,5.2vw,64px);
  line-height:1.1;
}
.final-cta p{
  color:rgba(250,249,247,0.72);
  max-width:460px;
  margin:26px auto 44px;
  font-size:15.5px;
}
.final-cta .btn-primary{background:var(--rose-light); color:var(--bordo);}
.final-cta .btn-primary:hover{background:var(--off-white);}
.final-glyph{
  position:absolute;
  top:50%; left:50%;
  width:900px;
  transform:translate(-50%,-50%);
  opacity:0.05;
  filter:brightness(0) invert(1);
  pointer-events:none;
}

/* ================= FOOTER ================= */
footer{background:var(--graphite); color:rgba(250,249,247,0.75); padding:80px 0 30px;}
.footer-grid{
  display:grid;
  grid-template-columns:1.3fr 1fr 1fr;
  gap:50px;
  padding-bottom:56px;
  border-bottom:1px solid rgba(250,249,247,0.12);
}
.footer-brand .flogo{width:170px; margin-bottom:22px;}
.footer-brand p{font-size:13.5px; line-height:1.8; opacity:0.55; max-width:260px; margin-top:18px;}
.footer h4{
  color:var(--off-white);
  font-family:var(--sans);
  font-size:12px;
  letter-spacing:0.1em;
  font-weight:700;
  opacity:0.55;
  margin-bottom:22px;
}
.footer ul{list-style:none; margin:0; padding:0; display:flex; flex-direction:column; gap:12px;}
.footer ul li a{font-size:14px; opacity:0.75; transition:opacity .3s;}
.footer ul li a:hover{opacity:1; color:var(--rose-light);}
.footer-bottom{
  padding-top:26px;
  display:flex;
  justify-content:space-between;
  align-items:center;
  flex-wrap:wrap;
  gap:14px;
  font-size:12px;
  opacity:0.45;
}
.footer-disclaimer{
  font-size:12px;
  opacity:0.5;
  font-style:italic;
  max-width:640px;
  margin-top:10px;
}
@media (max-width:760px){
  .footer-grid{grid-template-columns:1fr; gap:36px;}
}

/* ================= WHATSAPP FLOATING ================= */
.wa-float{
  position:fixed;
  right:26px;
  bottom:26px;
  z-index:900;
  display:flex;
  align-items:center;
  gap:10px;
  background:var(--bordo);
  color:var(--off-white);
  padding:15px 18px;
  border-radius:40px;
  box-shadow:0 10px 30px rgba(90,31,43,0.35);
  font-size:13px;
  font-weight:600;
  letter-spacing:0.02em;
  transition:transform .4s var(--ease), background .4s var(--ease), padding .4s var(--ease);
}
.wa-float span{max-width:140px; overflow:hidden; white-space:nowrap;}
.wa-float:hover{transform:translateY(-3px); background:#431720;}
.wa-float svg{width:20px;height:20px; flex-shrink:0;}
@media (max-width:560px){
  .wa-float{right:16px; bottom:16px; padding:14px;}
  .wa-float span{display:none;}
}
</style>
</head>
<body>

<div id="cursor-dot"></div>

<!-- ================= HEADER ================= -->
<header id="site-header">
  <div class="wrap">
    <a href="#top" class="nav-logo" aria-label="Dra. Marcella Maia — início">
      <img src="logo-white.png" class="logo-white" alt="Dra. Marcella Maia, Cirurgiã-Dentista">
      <img src="logo-color.png" class="logo-color" alt="">
    </a>
    <input type="checkbox" id="menu-toggle">
    <nav class="nav-links" id="nav-links">
      <a href="#top" class="nav-link">Início</a>
      <a href="#sobre" class="nav-link">Sobre</a>
      <a href="#procedimentos" class="nav-link">Procedimentos</a>
      <a href="#resultados" class="nav-link">Resultados</a>
      <a href="#duvidas" class="nav-link">Dúvidas</a>
      <a href="#contato" class="nav-link">Contato</a>
      <a href="https://wa.me/5563984636750?text=Ol%C3%A1%2C%20Dra.%20Marcella%21%20Gostaria%20de%20agendar%20uma%20avalia%C3%A7%C3%A3o." class="btn nav-cta" target="_blank" rel="noopener">Agendar avaliação</a>
    </nav>
    <button class="hamburger" id="hamburger" aria-label="Abrir menu" aria-expanded="false">
      <span></span><span></span><span></span>
    </button>
  </div>
</header>

<!-- ================= HERO ================= -->
<section class="hero" id="top">
  <div class="hero-copy">
    <span class="hero-eyebrow" data-hero>Harmonização Facial · Porto Nacional</span>
    <h1 class="hero-name" data-hero>Realce sua beleza.<br>Preserve sua essência.</h1>
    <p class="hero-role" data-hero>Dra. Marcella Maia — Cirurgiã-Dentista, CRO-TO 1729, residente em Harmonização Facial.</p>
    <p class="hero-desc" data-hero>Um olhar clínico dedicado à individualidade de cada rosto — equilíbrio, proporção e naturalidade, sem abrir mão do que torna você única.</p>
    <div class="hero-ctas" data-hero>
      <a href="https://wa.me/5563984636750?text=Ol%C3%A1%2C%20Dra.%20Marcella%21%20Gostaria%20de%20agendar%20uma%20avalia%C3%A7%C3%A3o." class="btn btn-primary" target="_blank" rel="noopener">Agendar avaliação <span class="btn-arrow">→</span></a>
      <a href="#procedimentos" class="btn btn-outline">Conhecer meu trabalho</a>
    </div>
  </div>
  <div class="hero-media">
    <div class="hero-media-inner">
      <img src="hero.jpeg" alt="Dra. Marcella Maia, cirurgiã-dentista e residente em Harmonização Facial">
    </div>
    <img src="m-glyph.png" class="hero-glyph" alt="" aria-hidden="true">
  </div>
  <span class="hero-caption">DRA. MARCELLA MAIA — CRO-TO 1729</span>
  <div class="scroll-cue"><span class="line"></span> ROLAR</div>
</section>

<!-- ================= POSITIONING ================= -->
<section class="positioning section-pad">
  <div class="wrap positioning-grid">
    <h2 class="reveal">Beleza não é transformar.<br><span class="serif-italic" style="color:var(--rose-burnt)">É revelar.</span></h2>
    <div class="support reveal reveal-delay-1">
      <p>A harmonização facial deve respeitar a individualidade, as proporções e as características únicas de cada pessoa — um cuidado que valoriza, nunca substitui, quem você já é.</p>
    </div>
  </div>
</section>

<!-- ================= SOBRE ================= -->
<section class="about section-pad" id="sobre">
  <div class="wrap about-grid">
    <div class="about-media reveal">
      <div class="about-media-frame"></div>
      <img src="about.jpeg" alt="Retrato da Dra. Marcella Maia">
      <div class="about-media-accent">
        <img src="lace-portrait2.jpeg" alt="Dra. Marcella Maia">
      </div>
    </div>
    <div class="about-copy">
      <div class="kicker reveal">
        <span class="num">02</span><span class="rule"></span><span class="label">SOBRE</span>
      </div>
      <h2 class="reveal">Conheça a Dra.<br>Marcella Maia</h2>
      <p class="credential reveal reveal-delay-1">Cirurgiã-Dentista · CRO-TO 1729 · Residente em Harmonização Facial</p>
      <p class="reveal reveal-delay-1">Cada atendimento começa por um princípio simples: ouvir. Compreender as proporções, a expressão e a história de cada rosto antes de propor qualquer procedimento.</p>
      <p class="reveal reveal-delay-2">O planejamento é individualizado, com atenção aos detalhes e respeito ao tempo de cada paciente — sempre em busca do equilíbrio entre cuidado técnico e naturalidade.</p>
      <div class="about-values reveal reveal-delay-3">
        <div class="item"><span class="lbl">Individualizado</span><p>Cada plano de cuidado é pensado a partir das características únicas do paciente.</p></div>
        <div class="item"><span class="lbl">Natural</span><p>Valorização da beleza própria, sem descaracterizar traços e expressões.</p></div>
        <div class="item"><span class="lbl">Detalhista</span><p>Atenção clínica dedicada a cada etapa do procedimento.</p></div>
      </div>
    </div>
  </div>
</section>

<!-- ================= PRESENÇA (GALERIA) ================= -->
<section class="presence section-pad">
  <div class="wrap">
    <div class="kicker reveal">
      <span class="num">03</span><span class="rule"></span><span class="label">PRESENÇA</span>
    </div>
    <div class="presence-head">
      <h2 class="reveal">Um cuidado presente em cada detalhe.</h2>
      <p class="reveal reveal-delay-1">Da avaliação ao acompanhamento, a mesma atenção dedicada em cada etapa.</p>
    </div>
    <div class="presence-grid reveal reveal-delay-1">
      <figure class="p-tall">
        <img src="lace-chair.jpeg" alt="Dra. Marcella Maia">
      </figure>
      <figure class="p-short">
        <img src="ipad-sitting.jpeg" alt="Dra. Marcella Maia">
      </figure>
      <figure class="p-tall">
        <img src="radiesse-full.jpeg" alt="Dra. Marcella Maia">
      </figure>
      <figure class="p-short">
        <img src="pink-portrait1.jpeg" alt="Dra. Marcella Maia">
      </figure>
    </div>
  </div>
</section>

<!-- ================= PROCEDIMENTOS ================= -->
<section class="procedures section-pad" id="procedimentos">
  <div class="wrap">
    <div class="kicker reveal">
      <span class="num">04</span><span class="rule"></span><span class="label">PROCEDIMENTOS</span>
    </div>
    <div class="procedures-head">
      <h2 class="reveal">Precisão, cuidado e naturalidade em cada detalhe.</h2>
      <p class="reveal reveal-delay-1">Toque em cada procedimento para conhecer mais.</p>
    </div>
    <div class="proc-layout">
      <div class="proc-list reveal">
        <div class="proc-item active" data-tint="rgba(90,31,43,0.28)" data-label="Bioestimulador" data-img="pennova.jpeg">
          <div class="proc-item-top">
            <span class="idx">01</span>
            <h3>Bioestimulador de Colágeno</h3>
            <span class="plus">+</span>
          </div>
          <div class="proc-item-body"><p>Procedimento voltado ao estímulo de colágeno e à melhora da qualidade e firmeza da pele.</p></div>
        </div>
        <div class="proc-item" data-tint="rgba(184,109,107,0.32)" data-label="Botox" data-img="syringes-lace.jpeg">
          <div class="proc-item-top">
            <span class="idx">02</span>
            <h3>Botox</h3>
            <span class="plus">+</span>
          </div>
          <div class="proc-item-body"><p>Procedimento utilizado para suavizar linhas de expressão e proporcionar uma aparência mais descansada.</p></div>
        </div>
        <div class="proc-item" data-tint="rgba(233,160,157,0.34)" data-label="Preenchimento" data-img="radiesse-bust.jpeg">
          <div class="proc-item-top">
            <span class="idx">03</span>
            <h3>Preenchimento Facial</h3>
            <span class="plus">+</span>
          </div>
          <div class="proc-item-body"><p>Técnica utilizada para harmonizar proporções e valorizar contornos faciais.</p></div>
        </div>
        <div class="proc-item" data-tint="rgba(90,31,43,0.22)" data-label="Microagulhamento" data-img="lace-portrait1.jpeg">
          <div class="proc-item-top">
            <span class="idx">04</span>
            <h3>Microagulhamento</h3>
            <span class="plus">+</span>
          </div>
          <div class="proc-item-body"><p>Procedimento voltado à renovação e melhora da qualidade da pele.</p></div>
        </div>
        <div class="proc-item" data-tint="rgba(184,109,107,0.24)" data-label="Peptídeos" data-img="office-2.jpeg">
          <div class="proc-item-top">
            <span class="idx">05</span>
            <h3>Peptídeos</h3>
            <span class="plus">+</span>
          </div>
          <div class="proc-item-body"><p>Tratamentos voltados ao cuidado e à qualidade da pele.</p></div>
        </div>
        <div class="proc-item" data-tint="rgba(90,31,43,0.3)" data-label="Fios de PDO" data-img="procedures.jpeg">
          <div class="proc-item-top">
            <span class="idx">06</span>
            <h3>Fios de PDO</h3>
            <span class="plus">+</span>
          </div>
          <div class="proc-item-body"><p>Técnica utilizada para estímulo de colágeno e melhora do suporte e contorno facial.</p></div>
        </div>
      </div>
      <div class="proc-media reveal reveal-delay-2">
        <img src="pennova.jpeg" alt="Dra. Marcella Maia em atendimento" id="proc-img">
        <span class="proc-media-label" id="proc-label">Bioestimulador</span>
      </div>
    </div>
  </div>
</section>

<!-- ================= ABORDAGEM ================= -->
<section class="approach section-pad">
  <div class="wrap">
    <div class="kicker reveal">
      <span class="num">05</span><span class="rule"></span><span class="label">ABORDAGEM</span>
    </div>
    <div class="approach-head">
      <h2 class="reveal">Harmonização com propósito.</h2>
    </div>
    <div class="pillars reveal">
      <div class="pillar">
        <span class="num">01</span>
        <h3>Individualidade</h3>
        <p>Cada rosto possui características únicas.</p>
      </div>
      <div class="pillar">
        <span class="num">02</span>
        <h3>Equilíbrio</h3>
        <p>Proporções e contornos devem conversar entre si.</p>
      </div>
      <div class="pillar">
        <span class="num">03</span>
        <h3>Naturalidade</h3>
        <p>O objetivo é valorizar sem descaracterizar.</p>
      </div>
    </div>
  </div>
</section>

<!-- ================= RESULTADOS ================= -->
<section class="results section-pad" id="resultados">
  <div class="wrap">
    <div class="kicker reveal">
      <span class="num">06</span><span class="rule"></span><span class="label">RESULTADOS</span>
    </div>
    <div class="results-head">
      <h2 class="reveal">Resultados</h2>
    </div>
    <div class="results-grid reveal reveal-delay-1">
      <figure class="result-photo">
        <img src="result-1.jpeg" alt="Resultado de preenchimento labial — antes e depois">
      </figure>
      <figure class="result-photo">
        <img src="result-2.jpeg" alt="Resultado de harmonização facial — antes e depois">
      </figure>
      <figure class="result-photo">
        <img src="result-3.jpeg" alt="Resultado de preenchimento labial — antes e depois">
      </figure>
    </div>
    <p class="results-note reveal reveal-delay-2">Os resultados podem variar de acordo com as características individuais de cada paciente.</p>
  </div>
</section>

<!-- ================= JORNADA ================= -->
<section class="journey section-pad">
  <div class="wrap">
    <div class="kicker reveal">
      <span class="num">07</span><span class="rule"></span><span class="label">ATENDIMENTO</span>
    </div>
    <div class="journey-head">
      <h2 class="reveal">Um cuidado pensado para você.</h2>
    </div>
    <div class="journey-steps reveal reveal-delay-1">
      <div class="jstep">
        <span class="num">01</span>
        <h3>Avaliação</h3>
        <p>Entendimento das necessidades e objetivos individuais.</p>
      </div>
      <div class="jstep">
        <span class="num">02</span>
        <h3>Planejamento</h3>
        <p>Definição da abordagem mais adequada para cada caso.</p>
      </div>
      <div class="jstep">
        <span class="num">03</span>
        <h3>Procedimento</h3>
        <p>Realização com cuidado, precisão e atenção aos detalhes.</p>
      </div>
      <div class="jstep">
        <span class="num">04</span>
        <h3>Acompanhamento</h3>
        <p>Orientações e acompanhamento conforme a necessidade.</p>
      </div>
    </div>
  </div>
</section>

<!-- ================= IMPACT ================= -->
<section class="impact">
  <h2 class="reveal">Sua beleza não precisa ser reinventada.<br>Ela precisa ser <span class="accent serif-italic">valorizada</span>.</h2>
</section>

<!-- ================= FAQ ================= -->
<section class="faq section-pad" id="duvidas">
  <div class="wrap faq-layout">
    <div class="faq-side reveal">
      <div class="kicker">
        <span class="num">08</span><span class="rule"></span><span class="label">DÚVIDAS</span>
      </div>
      <h2>Perguntas frequentes</h2>
      <p>Reunimos as dúvidas mais comuns sobre avaliação e procedimentos.</p>
    </div>
    <div class="faq-list reveal reveal-delay-1">
      <div class="faq-item open">
        <button class="faq-q"><span>Como funciona a avaliação?</span><span class="sign">+</span></button>
        <div class="faq-a"><p>A avaliação é o primeiro passo: um momento de escuta para entender suas necessidades e objetivos antes de qualquer indicação.</p></div>
      </div>
      <div class="faq-item">
        <button class="faq-q"><span>Qual procedimento é indicado para mim?</span><span class="sign">+</span></button>
        <div class="faq-a"><p>A indicação é sempre individualizada e definida durante a avaliação, de acordo com as características e objetivos de cada paciente.</p></div>
      </div>
      <div class="faq-item">
        <button class="faq-q"><span>Os procedimentos são personalizados?</span><span class="sign">+</span></button>
        <div class="faq-a"><p>Sim. Cada plano de tratamento é construído a partir das proporções e da individualidade de cada rosto.</p></div>
      </div>
      <div class="faq-item">
        <button class="faq-q"><span>Como funciona o preenchimento facial?</span><span class="sign">+</span></button>
        <div class="faq-a"><p>É uma técnica utilizada para harmonizar proporções e valorizar contornos faciais, sempre com planejamento individualizado.</p></div>
      </div>
      <div class="faq-item">
        <button class="faq-q"><span>Para que serve o Botox?</span><span class="sign">+</span></button>
        <div class="faq-a"><p>É utilizado para suavizar linhas de expressão e proporcionar uma aparência mais descansada.</p></div>
      </div>
      <div class="faq-item">
        <button class="faq-q"><span>Para que serve o bioestimulador de colágeno?</span><span class="sign">+</span></button>
        <div class="faq-a"><p>Estimula a produção de colágeno, contribuindo para a melhora da qualidade e firmeza da pele.</p></div>
      </div>
      <div class="faq-item">
        <button class="faq-q"><span>Posso combinar procedimentos?</span><span class="sign">+</span></button>
        <div class="faq-a"><p>A combinação de procedimentos é avaliada individualmente durante a consulta, conforme a indicação para cada caso.</p></div>
      </div>
      <div class="faq-item">
        <button class="faq-q"><span>Como funciona o agendamento?</span><span class="sign">+</span></button>
        <div class="faq-a"><p>O agendamento é feito diretamente pelo WhatsApp — basta tocar em "Agendar avaliação" em qualquer parte do site.</p></div>
      </div>
    </div>
  </div>
</section>

<!-- ================= INSTAGRAM ================= -->
<section class="instagram section-pad" id="instagram">
  <div class="wrap">
    <div class="kicker reveal">
      <span class="num">09</span><span class="rule"></span><span class="label">INSTAGRAM</span>
    </div>
    <div class="insta-head">
      <h2 class="reveal">Acompanhe meu trabalho</h2>
      <a href="https://instagram.com/dramarcellamaiaa" target="_blank" rel="noopener" class="handle reveal">@dramarcellamaiaa</a>
    </div>
    <div class="insta-grid reveal reveal-delay-1">
      <a class="insta-tile" href="https://instagram.com/dramarcellamaiaa" target="_blank" rel="noopener" aria-label="Ver no Instagram">
        <img src="office-1.jpeg" alt="Dra. Marcella Maia no Instagram">
        <span class="insta-hover"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.4"><rect x="3" y="3" width="18" height="18" rx="5"/><circle cx="12" cy="12" r="4"/><circle cx="17.2" cy="6.8" r="0.6" fill="currentColor"/></svg></span>
      </a>
      <a class="insta-tile" href="https://instagram.com/dramarcellamaiaa" target="_blank" rel="noopener" aria-label="Ver no Instagram">
        <img src="ipad-standing.jpeg" alt="Dra. Marcella Maia no Instagram">
        <span class="insta-hover"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.4"><rect x="3" y="3" width="18" height="18" rx="5"/><circle cx="12" cy="12" r="4"/><circle cx="17.2" cy="6.8" r="0.6" fill="currentColor"/></svg></span>
      </a>
      <a class="insta-tile" href="https://instagram.com/dramarcellamaiaa" target="_blank" rel="noopener" aria-label="Ver no Instagram">
        <img src="pink-chair2.jpeg" alt="Dra. Marcella Maia no Instagram">
        <span class="insta-hover"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.4"><rect x="3" y="3" width="18" height="18" rx="5"/><circle cx="12" cy="12" r="4"/><circle cx="17.2" cy="6.8" r="0.6" fill="currentColor"/></svg></span>
      </a>
      <a class="insta-tile" href="https://instagram.com/dramarcellamaiaa" target="_blank" rel="noopener" aria-label="Ver no Instagram">
        <img src="pink-portrait2.jpeg" alt="Dra. Marcella Maia no Instagram">
        <span class="insta-hover"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.4"><rect x="3" y="3" width="18" height="18" rx="5"/><circle cx="12" cy="12" r="4"/><circle cx="17.2" cy="6.8" r="0.6" fill="currentColor"/></svg></span>
      </a>
      <a class="insta-tile" href="https://instagram.com/dramarcellamaiaa" target="_blank" rel="noopener" aria-label="Ver no Instagram">
        <img src="lace-chair.jpeg" alt="Dra. Marcella Maia no Instagram">
        <span class="insta-hover"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.4"><rect x="3" y="3" width="18" height="18" rx="5"/><circle cx="12" cy="12" r="4"/><circle cx="17.2" cy="6.8" r="0.6" fill="currentColor"/></svg></span>
      </a>
      <a class="insta-tile" href="https://instagram.com/dramarcellamaiaa" target="_blank" rel="noopener" aria-label="Ver no Instagram">
        <img src="pink-portrait1.jpeg" alt="Dra. Marcella Maia no Instagram">
        <span class="insta-hover"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.4"><rect x="3" y="3" width="18" height="18" rx="5"/><circle cx="12" cy="12" r="4"/><circle cx="17.2" cy="6.8" r="0.6" fill="currentColor"/></svg></span>
      </a>
    </div>
  </div>
</section>

<!-- ================= CTA FINAL ================= -->
<section class="final-cta" id="contato">
  <img src="m-glyph.png" class="final-glyph" alt="" aria-hidden="true">
  <div class="wrap">
    <h2 class="reveal">Seu rosto. Sua essência.<br>Seu melhor detalhe.</h2>
    <p class="reveal reveal-delay-1">Agende uma avaliação e descubra uma abordagem personalizada para valorizar sua beleza.</p>
    <a href="https://wa.me/5563984636750?text=Ol%C3%A1%2C%20Dra.%20Marcella%21%20Gostaria%20de%20agendar%20uma%20avalia%C3%A7%C3%A3o." class="btn btn-primary reveal reveal-delay-2" target="_blank" rel="noopener">Agendar avaliação <span class="btn-arrow">→</span></a>
  </div>
</section>

<!-- ================= FOOTER ================= -->
<footer>
  <div class="wrap">
    <div class="footer-grid">
      <div class="footer-brand">
        <img src="logo-white.png" class="flogo" alt="Dra. Marcella Maia">
        <p>Cirurgiã-Dentista · CRO-TO 1729 · Residente em Harmonização Facial.</p>
      </div>
      <div class="footer">
        <h4>PROCEDIMENTOS</h4>
        <ul>
          <li><a href="#procedimentos">Bioestimulador de colágeno</a></li>
          <li><a href="#procedimentos">Botox</a></li>
          <li><a href="#procedimentos">Preenchimento facial</a></li>
          <li><a href="#procedimentos">Microagulhamento</a></li>
          <li><a href="#procedimentos">Peptídeos</a></li>
          <li><a href="#procedimentos">Fios de PDO</a></li>
        </ul>
      </div>
      <div class="footer">
        <h4>CONTATO</h4>
        <ul>
          <li><a href="https://wa.me/5563984636750">(63) 98463-6750</a></li>
          <li><a href="mailto:marcellacalaca@gmail.com">marcellacalaca@gmail.com</a></li>
          <li><a href="https://instagram.com/dramarcellamaiaa" target="_blank" rel="noopener">@dramarcellamaiaa</a></li>
        </ul>
      </div>
    </div>
    <div class="footer-bottom">
      <span>© <span id="year"></span> Dra. Marcella Maia. Todos os direitos reservados.</span>
    </div>
    <p class="footer-disclaimer">Os resultados dos procedimentos podem variar de acordo com as características individuais de cada paciente.</p>
  </div>
</footer>

<!-- WHATSAPP FLUTUANTE -->
<a href="https://wa.me/5563984636750?text=Ol%C3%A1%2C%20Dra.%20Marcella%21%20Gostaria%20de%20agendar%20uma%20avalia%C3%A7%C3%A3o." class="wa-float" target="_blank" rel="noopener" aria-label="Agendar avaliação pelo WhatsApp">
  <svg viewBox="0 0 24 24" fill="currentColor"><path d="M17.6 6.32A7.85 7.85 0 0 0 12.05 4a7.94 7.94 0 0 0-6.9 11.9L4 20l4.2-1.1a7.9 7.9 0 0 0 3.85 1h.01A7.94 7.94 0 0 0 20 12a7.9 7.9 0 0 0-2.4-5.68zm-5.55 12.2h-.01a6.6 6.6 0 0 1-3.36-.92l-.24-.14-2.5.65.67-2.44-.16-.25a6.6 6.6 0 1 1 5.6 3.1zm3.6-4.94c-.2-.1-1.17-.58-1.35-.64-.18-.07-.31-.1-.44.1-.13.2-.5.64-.62.77-.11.13-.23.15-.42.05a5.4 5.4 0 0 1-1.6-.98 6 6 0 0 1-1.1-1.37c-.12-.2 0-.3.09-.4.09-.1.2-.24.3-.36.1-.12.13-.2.2-.33.07-.13.03-.25-.02-.35-.05-.1-.44-1.06-.6-1.45-.16-.38-.32-.33-.44-.34h-.38c-.13 0-.34.05-.52.25-.18.2-.68.66-.68 1.6s.7 1.86.79 1.99c.1.13 1.37 2.1 3.33 2.94.46.2.83.32 1.11.4.47.15.9.13 1.24.08.38-.06 1.17-.48 1.34-.94.16-.46.16-.85.11-.94-.05-.09-.18-.14-.38-.24z"/></svg>
  <span>Agendar avaliação</span>
</a>

<script>
document.getElementById('year').textContent = new Date().getFullYear();

/* Header scroll state */
const header = document.getElementById('site-header');
const onScroll = () => {
  header.classList.toggle('scrolled', window.scrollY > 40);
};
onScroll();
window.addEventListener('scroll', onScroll, {passive:true});

/* Mobile menu */
const hamburger = document.getElementById('hamburger');
hamburger.addEventListener('click', () => {
  const open = document.body.classList.toggle('menu-open');
  hamburger.setAttribute('aria-expanded', open);
});
document.querySelectorAll('.nav-link').forEach(a => a.addEventListener('click', () => {
  document.body.classList.remove('menu-open');
}));

/* Hero entrance sequence */
window.addEventListener('DOMContentLoaded', () => {
  const els = document.querySelectorAll('[data-hero]');
  els.forEach((el, i) => {
    setTimeout(() => {
      el.style.transition = 'opacity 1.1s cubic-bezier(.22,.61,.36,1), transform 1.1s cubic-bezier(.22,.61,.36,1)';
      el.style.transform = 'translateY(0)';
      el.style.opacity = '1';
    }, 260 + i * 160);
    el.style.transform = 'translateY(16px)';
  });
});

/* Scroll reveal */
const revealEls = document.querySelectorAll('.reveal');
const io = new IntersectionObserver((entries) => {
  entries.forEach(entry => {
    if (entry.isIntersecting) {
      entry.target.classList.add('in');
      io.unobserve(entry.target);
    }
  });
}, {threshold:0.15, rootMargin:'0px 0px -60px 0px'});
revealEls.forEach(el => io.observe(el));

/* Procedures interactive list */
const procItems = document.querySelectorAll('.proc-item');
const procImg = document.getElementById('proc-img');
const procLabel = document.getElementById('proc-label');
const procMedia = document.querySelector('.proc-media');
function swapProcImage(item){
  procMedia.style.setProperty('--tint', item.dataset.tint);
  procImg.style.opacity = 0;
  procLabel.style.opacity = 0;
  setTimeout(() => {
    if (item.dataset.img) procImg.src = item.dataset.img;
    procLabel.textContent = item.dataset.label;
    procImg.style.opacity = 1;
    procLabel.style.opacity = 1;
  }, 220);
}
procImg.style.transition = 'opacity .3s var(--ease)';
procItems.forEach(item => {
  item.addEventListener('click', () => {
    const alreadyActive = item.classList.contains('active');
    procItems.forEach(i => i.classList.remove('active'));
    if (!alreadyActive) {
      item.classList.add('active');
      swapProcImage(item);
    }
  });
  item.addEventListener('mouseenter', () => {
    if (window.matchMedia('(hover:hover)').matches){
      swapProcImage(item);
    }
  });
});

/* FAQ accordion */
document.querySelectorAll('.faq-q').forEach(btn => {
  btn.addEventListener('click', () => {
    const item = btn.closest('.faq-item');
    const wasOpen = item.classList.contains('open');
    document.querySelectorAll('.faq-item').forEach(i => i.classList.remove('open'));
    if (!wasOpen) item.classList.add('open');
  });
});

/* Custom cursor - desktop only */
if (window.matchMedia('(hover:hover) and (pointer:fine)').matches) {
  const dot = document.getElementById('cursor-dot');
  let mx=0,my=0,dx=0,dy=0;
  window.addEventListener('mousemove', (e) => {
    mx = e.clientX; my = e.clientY;
    dot.classList.add('active');
  });
  const raf = () => {
    dx += (mx-dx)*0.18; dy += (my-dy)*0.18;
    dot.style.left = dx+'px'; dot.style.top = dy+'px';
    requestAnimationFrame(raf);
  };
  raf();
  document.querySelectorAll('a, button, .proc-item').forEach(el => {
    el.addEventListener('mouseenter', () => dot.classList.add('hovering'));
    el.addEventListener('mouseleave', () => dot.classList.remove('hovering'));
  });
  document.addEventListener('mouseleave', () => dot.classList.remove('active'));
}
</script>
</body>
</html>
