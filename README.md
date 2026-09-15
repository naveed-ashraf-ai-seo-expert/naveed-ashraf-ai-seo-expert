<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Naveed Ashraf — SEO Expert | AI SEO | Local SEO | GBP</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Bricolage+Grotesque:opsz,wght@12..96,400;12..96,600;12..96,800&family=Source+Serif+4:opsz,wght@8..60,400;8..60,600&display=swap" rel="stylesheet">
<style>
:root{
  --paper:#FBFAF7;
  --deep:#0C1B18;
  --ink:#14171C;
  --ink-soft:#585F68;
  --rule:#E3DFD7;
  --rule-dim:rgba(251,250,247,.16);
  --pin:#0B6B4F;
  --pin-lit:#22C48A;
  --pin-tint:#E7F1ED;
  --flag:#E0902C;
  --max:70rem;
}

*{box-sizing:border-box}
html{-webkit-text-size-adjust:100%;scroll-behavior:smooth}
body{
  margin:0;background:var(--paper);color:var(--ink);
  font-family:"Source Serif 4",Georgia,serif;
  font-size:1.125rem;line-height:1.68;font-optical-sizing:auto;
}
.wrap{max-width:var(--max);margin:0 auto;padding:0 1.6rem}
h1,h2,h3,.ui{font-family:"Bricolage Grotesque","Helvetica Neue",Arial,sans-serif}

/* ============ HERO ============ */
.hero{
  background:var(--deep);color:var(--paper);
  padding:4rem 0 5rem;position:relative;overflow:hidden;
}
.hero::after{
  content:"";position:absolute;inset:auto -20% -60% 40%;
  height:70%;background:radial-gradient(closest-side,rgba(34,196,138,.18),transparent);
  pointer-events:none;
}
.ident{
  display:flex;flex-wrap:wrap;align-items:baseline;gap:.5rem 1.1rem;
  padding-bottom:1.6rem;margin-bottom:3.2rem;
  border-bottom:1px solid var(--rule-dim);position:relative;z-index:1;
}
.ident .nm{
  font-family:"Bricolage Grotesque",Arial,sans-serif;
  font-weight:800;font-size:1.3rem;letter-spacing:-.02em;
}
.ident .rl{
  font-family:"Bricolage Grotesque",Arial,sans-serif;
  font-size:.92rem;color:#9FB3AC;font-weight:400;
}
.hero-grid{display:grid;grid-template-columns:1fr;gap:3.2rem;align-items:center;position:relative;z-index:1}
@media(min-width:58rem){.hero-grid{grid-template-columns:1.1fr .9fr;gap:4.5rem}}

h1{
  font-size:clamp(3rem,7.6vw,5.4rem);
  line-height:.98;letter-spacing:-.035em;font-weight:800;
  margin:0 0 1.5rem;text-wrap:balance;
}
.sub{
  font-size:clamp(1.2rem,2.3vw,1.45rem);
  color:#B9C9C3;margin:0 0 2.4rem;max-width:36ch;line-height:1.5;
}
.hero ul{
  list-style:none;margin:0 0 2.6rem;padding:0;
  display:grid;gap:.75rem;max-width:34rem;
}
.hero ul li{
  display:grid;grid-template-columns:1.4rem 1fr;gap:.75rem;align-items:start;
  font-family:"Bricolage Grotesque",Arial,sans-serif;
  font-size:1.05rem;color:#DCE7E3;line-height:1.45;
}
.hero ul li::before{
  content:"";width:.6rem;height:.6rem;margin-top:.5rem;border-radius:2px;
  background:var(--pin-lit);transform:rotate(45deg);
}
.cta{
  display:inline-block;font-family:"Bricolage Grotesque",Arial,sans-serif;
  font-weight:600;font-size:1.05rem;color:var(--deep);background:var(--pin-lit);
  padding:1rem 1.9rem;border-radius:2.5rem;text-decoration:none;
  transition:transform .18s ease,background .18s ease;
}
.cta:hover,.cta:focus-visible{background:#fff;transform:translateY(-2px)}
.cta-note{display:block;margin-top:1rem;font-size:.98rem;color:#8FA49E}

/* ============ MAP PACK ============ */
.pack{
  background:#fff;border-radius:16px;padding:.45rem;
  box-shadow:0 30px 70px -30px rgba(0,0,0,.6);color:var(--ink);
}
.pack-head{
  display:flex;align-items:center;gap:.6rem;padding:.85rem .95rem 1rem;
  border-bottom:1px solid var(--rule);
  font-family:"Bricolage Grotesque",Arial,sans-serif;font-size:.95rem;color:var(--ink-soft);
}
.dot{width:.6rem;height:.6rem;border-radius:50%;background:var(--rule);flex:none}
.row{
  display:grid;grid-template-columns:1.6rem 1fr auto;gap:.9rem;align-items:center;
  padding:1.05rem .95rem;border-bottom:1px solid var(--rule);
}
.row:last-child{border-bottom:0}
.rank{font-family:"Bricolage Grotesque",Arial,sans-serif;font-size:.9rem;color:var(--ink-soft);font-weight:600}
.name{font-family:"Bricolage Grotesque",Arial,sans-serif;font-weight:600;font-size:1.05rem;line-height:1.3;display:block}
.meta{font-size:.88rem;color:var(--ink-soft);line-height:1.45;display:block}
.stars{color:var(--flag);letter-spacing:.06em}
.row--you{background:var(--pin-tint);border-radius:11px}
.row--you .name{color:var(--pin)}
.tag{
  font-family:"Bricolage Grotesque",Arial,sans-serif;font-size:.74rem;font-weight:600;
  color:var(--pin);border:1px solid var(--pin);border-radius:1rem;padding:.15rem .6rem;white-space:nowrap;
}
@media(prefers-reduced-motion:no-preference){
  .row--you{animation:climb 1.6s cubic-bezier(.16,.84,.34,1) .55s both}
  @keyframes climb{0%{transform:translateY(134px);opacity:.2}60%,100%{transform:translateY(0);opacity:1}}
  .row--drop{animation:settle 1.6s cubic-bezier(.16,.84,.34,1) .55s both}
  @keyframes settle{0%{transform:translateY(-67px)}60%,100%{transform:translateY(0)}}
}

/* ============ BANDS ============ */
.band{padding:5.5rem 0;border-top:1px solid var(--rule)}
h2{
  font-size:clamp(2.1rem,4.6vw,3.1rem);letter-spacing:-.028em;line-height:1.08;
  font-weight:800;margin:0 0 .8rem;max-width:20ch;
}
.lede{color:var(--ink-soft);margin:0 0 3.4rem;max-width:56ch;font-size:1.2rem}

.svc{
  display:grid;grid-template-columns:1fr;gap:.9rem;
  padding:2.4rem 0;border-top:1px solid var(--rule);
}
.svc:last-of-type{border-bottom:1px solid var(--rule)}
@media(min-width:48rem){.svc{grid-template-columns:17rem 1fr;gap:3rem;align-items:start}}
.svc h3{margin:0;font-size:1.5rem;font-weight:800;letter-spacing:-.022em;line-height:1.18}
.svc p{margin:0 0 1rem;color:var(--ink-soft);max-width:62ch}
.svc ul{list-style:none;margin:0;padding:0;display:grid;gap:.5rem}
.svc ul li{
  display:grid;grid-template-columns:1.1rem 1fr;gap:.7rem;align-items:start;
  font-family:"Bricolage Grotesque",Arial,sans-serif;font-size:1rem;line-height:1.45;
}
.svc ul li::before{
  content:"";width:.45rem;height:.45rem;margin-top:.52rem;border-radius:50%;background:var(--flag);
}

/* ============ STEPS ============ */
ol.steps{list-style:none;counter-reset:s;margin:0;padding:0}
ol.steps li{
  counter-increment:s;display:grid;grid-template-columns:3rem 1fr;gap:1.4rem;
  padding:1.8rem 0;border-top:1px solid var(--rule);
}
ol.steps li:last-child{border-bottom:1px solid var(--rule)}
ol.steps li::before{
  content:counter(s);font-family:"Bricolage Grotesque",Arial,sans-serif;
  font-weight:800;font-size:2rem;color:var(--flag);line-height:1.05;
}
ol.steps h3{margin:0 0 .3rem;font-size:1.3rem;font-weight:600;letter-spacing:-.015em}
ol.steps p{margin:0;color:var(--ink-soft);max-width:58ch}

/* ============ CLOSE ============ */
.close{background:var(--deep);color:var(--paper);padding:5.5rem 0}
.close h2{color:var(--paper)}
.close p{max-width:52ch;color:#B9C9C3;margin:0 0 2.4rem;font-size:1.2rem}
footer{
  background:var(--deep);color:#7F948E;border-top:1px solid var(--rule-dim);
  font-family:"Bricolage Grotesque",Arial,sans-serif;font-size:.95rem;padding:1.8rem 0 2.6rem;
}
a:focus-visible,.cta:focus-visible{outline:2px solid var(--pin-lit);outline-offset:3px}
</style>
</head>
<body>

<header class="hero">
  <div class="wrap">
    <div class="ident">
      <span class="nm">Naveed Ashraf</span>
      <span class="rl">SEO Expert · AI SEO · AEO/GEO · Local SEO · GBP · Technical &amp; On-Page SEO</span>
    </div>

    <div class="hero-grid">
      <div>
        <h1>Three businesses show up on the map. Yours should be one.</h1>
        <p class="sub">Local search, Google Business Profile and AI visibility for businesses that live on phone calls.</p>

        <ul>
          <li>Rank in the Google Maps 3-pack for the searches that bring calls</li>
          <li>Google Business Profile rebuilt, cleaned and kept current</li>
          <li>Cited in ChatGPT and Google AI Overviews, not just blue links</li>
          <li>Technical and on-page work implemented, never just recommended</li>
        </ul>

        <a class="cta" href="#start">Get a free profile check</a>
        <span class="cta-note">Send a URL and a city. Honest read back within 24 hours.</span>
      </div>

      <div class="pack" role="img" aria-label="A Google Maps local pack with your business ranked first.">
        <div class="pack-head"><span class="dot"></span> plumber near me</div>
        <div class="row row--you">
          <span class="rank">1</span>
          <span><span class="name">Your business</span><span class="meta"><span class="stars">★★★★★</span> 94 reviews · Open now</span></span>
          <span class="tag">Map pack</span>
        </div>
        <div class="row row--drop">
          <span class="rank">2</span>
          <span><span class="name">Competitor A</span><span class="meta">★★★★☆ 52 reviews · Closes 5pm</span></span>
        </div>
        <div class="row row--drop">
          <span class="rank">3</span>
          <span><span class="name">Competitor B</span><span class="meta">★★★★☆ 38 reviews · Closed</span></span>
        </div>
      </div>
    </div>
  </div>
</header>

<section class="band">
  <div class="wrap">
    <h2>What actually moves local rankings</h2>
    <p class="lede">Most businesses don't lose customers to a better competitor. They lose them to one Google trusts more. These are the signals that decide it.</p>

    <div class="svc">
      <h3>Google Business Profile</h3>
      <div>
        <p>Set up the way Google reads it, not the way the form suggests. Half-configured profiles are the most common reason a strong business sits below a weaker one.</p>
        <ul>
          <li>Primary and secondary category selection</li>
          <li>Full services list, attributes and description</li>
          <li>Posts, photos and Q&amp;A kept active</li>
          <li>Suspension recovery and reinstatement</li>
        </ul>
      </div>
    </div>

    <div class="svc">
      <h3>Citations &amp; NAP</h3>
      <div>
        <p>Your name, address and phone matched across every directory, down to whether it reads Street or St. Mismatches split the signals that should point at one business.</p>
        <ul>
          <li>Citation audit across existing directories</li>
          <li>Duplicate listing detection and removal</li>
          <li>Manual submissions on top DA and niche sites</li>
          <li>Live URLs reported for every listing</li>
        </ul>
      </div>
    </div>

    <div class="svc">
      <h3>Technical &amp; On-Page</h3>
      <div>
        <p>Service and location pages built around what people actually search, on a site that loads before the visitor gives up.</p>
        <ul>
          <li>Crawlability, indexing, canonicals and sitemaps</li>
          <li>Titles, meta, headings and internal linking</li>
          <li>Schema markup and structured data</li>
          <li>Core Web Vitals and page speed</li>
        </ul>
      </div>
    </div>

    <div class="svc">
      <h3>AI Search (AEO/GEO)</h3>
      <div>
        <p>Customers now ask ChatGPT and Google's AI Overviews who to hire. If your data is thin or inconsistent, the answer names someone else.</p>
        <ul>
          <li>Entity SEO and knowledge graph alignment</li>
          <li>Structured data built for machine parsing</li>
          <li>llms.txt and AI crawler accessibility</li>
          <li>Content structured to be quoted, not skimmed</li>
        </ul>
      </div>
    </div>
  </div>
</section>

<section class="band">
  <div class="wrap">
    <h2>How the work runs</h2>
    <p class="lede">Foundation first, then authority. In that order, because citations built on a broken profile don't count for much.</p>
    <ol class="steps">
      <li><div><h3>Audit</h3><p>Your profile, site, competitors and where you currently sit on the map for the searches that bring calls.</p></div></li>
      <li><div><h3>Fix the foundation</h3><p>Profile rebuild, NAP cleanup, duplicate removal, technical and on-page issues cleared before anything is added on top.</p></div></li>
      <li><div><h3>Build authority</h3><p>Citations on directories that matter, local links, review velocity and content that earns relevance in your city.</p></div></li>
      <li><div><h3>Track and adjust</h3><p>Rankings, calls and direction requests in Search Console and GA4, reported in plain language every month.</p></div></li>
    </ol>
  </div>
</section>

<section class="close" id="start">
  <div class="wrap">
    <h2>Start with the free check</h2>
    <p>Send your website, your city and your main services. You'll get the three things holding your rankings back and what I'd fix first. No charge, and no obligation afterwards.</p>
    <a class="cta" href="mailto:hello@example.com">Send your details</a>
  </div>
</section>

<footer>
  <div class="wrap">Naveed Ashraf · SEO Expert · AI SEO · AEO/GEO · Local SEO · GBP · Technical &amp; On-Page SEO</div>
</footer>

</body>
</html>
