# My-portfolio-test-claude
free portfolio test website
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Your Brand Name | Cinematic Wedding Photography, Delhi</title>
<meta name="description" content="Cinematic storytelling for premium weddings. Wedding and editorial photography based in Delhi.">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,300;0,500;1,300&family=Jost:wght@300;400&display=swap" rel="stylesheet">
<style>
:root{
  --plum:#1d1519; --wine:#3a1f2b; --dusk:#5a3a3f; --stone:#e8e0d8; --brass:#b89b72;
  --serif:"Cormorant Garamond",Georgia,serif; --sans:"Jost",system-ui,sans-serif;
}
*{box-sizing:border-box;margin:0;padding:0}
html{scroll-behavior:smooth}
body{background:var(--plum);color:var(--stone);font-family:var(--sans);font-weight:300;line-height:1.7;font-size:1.05rem}
a{color:inherit}
:focus-visible{outline:2px solid var(--brass);outline-offset:4px}
.wrap{max-width:1100px;margin:0 auto;padding:0 1.5rem}

header{position:absolute;top:0;left:0;right:0;z-index:2}
nav{display:flex;justify-content:space-between;align-items:center;padding:1.6rem 0}
.logo{font-family:var(--serif);font-size:1.4rem;font-weight:500;text-decoration:none;letter-spacing:.02em}
nav ul{display:flex;gap:1.8rem;list-style:none}
nav ul a{text-decoration:none;font-size:.95rem}
nav ul a:hover{color:var(--brass)}

.hero{min-height:100svh;display:flex;align-items:center;background:radial-gradient(120% 90% at 70% 20%,var(--dusk) 0%,var(--wine) 40%,var(--plum) 80%)}
.hero h1{font-family:var(--serif);font-weight:300;font-size:clamp(2.8rem,8vw,6.5rem);line-height:1.02;max-width:12ch;animation:rise 1.4s ease both}
.hero p{margin-top:1.6rem;max-width:34ch;color:#cfc4ba}
.hero a.cta{display:inline-block;margin-top:2.2rem;padding:.85rem 2rem;border:1px solid var(--brass);text-decoration:none}
.hero a.cta:hover{background:var(--brass);color:var(--plum)}
@keyframes rise{from{opacity:0;transform:translateY(24px)}to{opacity:1;transform:none}}

section{padding:6rem 0}
h2{font-family:var(--serif);font-weight:300;font-size:clamp(2rem,4.5vw,3.2rem);line-height:1.15;margin-bottom:2.5rem}

.story{margin-bottom:4rem}
.frame{position:relative;aspect-ratio:2.39/1;overflow:hidden;background:linear-gradient(120deg,var(--wine),var(--dusk) 55%,#7a5a4e)}
.story:nth-child(even) .frame{background:linear-gradient(240deg,#2b2a33,#4a3a4a 55%,#6d5560)}
.frame img{position:absolute;inset:0;width:100%;height:100%;object-fit:cover}
.story h3{font-family:var(--serif);font-weight:500;font-size:1.7rem;margin-top:1rem}
.story p{color:#b9aea5}

.about{display:grid;grid-template-columns:1fr 1fr;gap:3rem;align-items:start}
.about .portrait{aspect-ratio:4/5;background:linear-gradient(160deg,var(--dusk),var(--wine));position:relative;overflow:hidden}
.about .portrait img{position:absolute;inset:0;width:100%;height:100%;object-fit:cover}
.about p+p{margin-top:1.1rem}

.contact{background:var(--wine);text-align:center}
.contact h2{margin-bottom:1.2rem}
.contact p{max-width:44ch;margin:0 auto 2rem;color:#d7ccc3}
.contact .mail{font-family:var(--serif);font-size:clamp(1.5rem,4vw,2.4rem);text-decoration:none;border-bottom:1px solid var(--brass)}
.contact .social{margin-top:2rem}
.contact .social a{margin:0 1rem}

footer{padding:2rem 0;text-align:center;font-size:.9rem;color:#8f847b}

@media(max-width:720px){
  nav ul{gap:1.1rem}
  .about{grid-template-columns:1fr}
  section{padding:4rem 0}
  .frame{aspect-ratio:16/9}
}
@media(prefers-reduced-motion:reduce){
  html{scroll-behavior:auto}
  .hero h1{animation:none}
}
</style>
</head>
<body>

<header>
  <div class="wrap">
    <nav>
      <a class="logo" href="#top">Your Brand Name</a>
      <ul>
        <li><a href="#work">Work</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </div>
</header>

<main id="top">
  <div class="hero">
    <div class="wrap">
      <h1>Cinematic storytelling for premium weddings.</h1>
      <p>Wedding and editorial photography, based in Delhi.</p>
      <a class="cta" href="#contact">Check your date</a>
    </div>
  </div>

  <section id="work">
    <div class="wrap">
      <h2>Selected weddings</h2>

      <!-- To add a wedding: copy one <article>, put your photo in the images folder, and change the file name below. -->
      <article class="story">
        <div class="frame"><img src="images/wedding-1.jpg" alt="Wedding ceremony, Udaipur" loading="lazy" onerror="this.remove()"></div>
        <h3>Aanya &amp; Kabir</h3>
        <p>Udaipur, three days by the lake.</p>
      </article>

      <article class="story">
        <div class="frame"><img src="images/wedding-2.jpg" alt="Wedding portrait, Delhi" loading="lazy" onerror="this.remove()"></div>
        <h3>Meher &amp; Arjun</h3>
        <p>Delhi, a winter wedding at a heritage farmhouse.</p>
      </article>

      <article class="story">
        <div class="frame"><img src="images/wedding-3.jpg" alt="Wedding farewell, Jaipur" loading="lazy" onerror="this.remove()"></div>
        <h3>Sara &amp; Dev</h3>
        <p>Jaipur, a palace wedding and a slow farewell.</p>
      </article>

      <article class="story">
        <div class="frame"><img src="images/wedding-4.jpg" alt="Destination wedding, Goa" loading="lazy" onerror="this.remove()"></div>
        <h3>Ira &amp; Neil</h3>
        <p>Goa, an evening ceremony on the beach.</p>
      </article>
    </div>
  </section>

  <section id="about">
    <div class="wrap about">
      <div class="portrait"><img src="images/portrait.jpg" alt="Photographer portrait" loading="lazy" onerror="this.remove()"></div>
      <div>
        <h2>Hi, I'm Vipin.</h2>
        <p>I photograph weddings the way a film is shot: with patience, natural light, and attention to the quiet moments between the big ones.</p>
        <p>My work is documentary at its heart and cinematic in how it looks. You get a gallery that feels like your day, not a checklist of poses.</p>
        <p>I take a limited number of weddings each season so every couple gets my full attention.</p>
      </div>
    </div>
  </section>

  <section id="contact" class="contact">
    <div class="wrap">
      <h2>Tell me about your wedding.</h2>
      <p>Send your date, your city, and a few lines about the celebration. I reply within two days.</p>
      <a class="mail" href="mailto:hello@yourdomain.com">hello@yourdomain.com</a>
      <div class="social">
        <a href="https://instagram.com/yourhandle" rel="noopener">Instagram</a>
        <a href="https://wa.me/910000000000" rel="noopener">WhatsApp</a>
      </div>
    </div>
  </section>
</main>

<footer>
  <div class="wrap">&copy; 2026 Your Brand Name. Delhi.</div>
</footer>

</body>
</html>
