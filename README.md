<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Ooha Poloju | Software Engineer, Distributed Systems & Real-Time Data</title>
<meta name="description" content="Software engineer with nearly 6 years across banking and healthcare. Kafka, Spark, Java, Spring Boot, Azure and AWS. Cut transaction reporting latency from 15 minutes to under 2 seconds at Citibank.">
<meta property="og:title" content="Ooha Poloju | Software Engineer">
<meta property="og:description" content="Backend systems that move data in seconds, not minutes.">
<meta property="og:type" content="website">
<link rel="icon" href="data:image/svg+xml,<svg xmlns=%22http://www.w3.org/2000/svg%22 viewBox=%220 0 100 100%22><rect width=%22100%22 height=%22100%22 rx=%2222%22 fill=%22%232447f5%22/><text x=%2250%22 y=%2272%22 font-size=%2262%22 font-family=%22sans-serif%22 font-weight=%22700%22 text-anchor=%22middle%22 fill=%22white%22>O</text></svg>">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Bricolage+Grotesque:opsz,wght@12..96,500;12..96,700;12..96,800&family=IBM+Plex+Sans:wght@400;500;600&display=swap" rel="stylesheet">
<script type="application/ld+json">
{"@context":"https://schema.org","@type":"Person","name":"Ooha Poloju","jobTitle":"Software Engineer","address":{"@type":"PostalAddress","addressLocality":"Dallas","addressRegion":"TX"},"email":"mailto:polojuooha03@gmail.com","sameAs":["https://linkedin.com/in/ooha-poloju-3b7b42435","https://github.com/Oohapoloju"],"alumniOf":"Harrisburg University of Science and Technology"}
</script>
<style>
:root{
  --paper:#eef2f7; --panel:#ffffff; --ink:#14202e; --muted:#51606f; --line:#cfd8e3;
  --blue:#2447f5; --amber:#c97a00; --amber-bg:#fff1d6; --blue-bg:#e4e9ff;
  --display:"Bricolage Grotesque","Segoe UI",system-ui,sans-serif;
  --body:"IBM Plex Sans","Segoe UI",system-ui,sans-serif;
}
@media (prefers-color-scheme:dark){
  :root:not([data-theme="light"]){--paper:#0f1722;--panel:#162231;--ink:#e8eef6;--muted:#9fb0c3;--line:#2a3a4d;--blue:#7d95ff;--amber:#ffb340;--amber-bg:#3a2a0c;--blue-bg:#1b2750}
}
:root[data-theme="dark"]{--paper:#0f1722;--panel:#162231;--ink:#e8eef6;--muted:#9fb0c3;--line:#2a3a4d;--blue:#7d95ff;--amber:#ffb340;--amber-bg:#3a2a0c;--blue-bg:#1b2750}
*{box-sizing:border-box}
html{scroll-behavior:smooth;scroll-padding-top:4.5rem}
body{margin:0;background:var(--paper);color:var(--ink);font:400 1.0625rem/1.65 var(--body)}
a{color:inherit}
:focus-visible{outline:3px solid var(--blue);outline-offset:3px;border-radius:4px}
.wrap{max-width:68rem;margin:0 auto;padding:0 1.5rem}
header.nav{position:sticky;top:0;z-index:5;background:color-mix(in srgb,var(--paper) 88%,transparent);backdrop-filter:blur(8px);border-bottom:1px solid var(--line)}
.nav .wrap{display:flex;align-items:center;justify-content:space-between;gap:1rem;height:3.5rem}
.nav b{font:700 1.1rem var(--display)}
.nav nav{display:flex;gap:1.25rem;align-items:center;font-size:.95rem}
.nav nav a{text-decoration:none;color:var(--muted)}
.nav nav a:hover{color:var(--ink)}
#theme{border:1px solid var(--line);background:var(--panel);color:var(--ink);border-radius:999px;padding:.25rem .75rem;font:500 .85rem var(--body);cursor:pointer}
@media(max-width:640px){.nav nav a.hide-s{display:none}}

/* hero */
.hero{padding:4.5rem 0 3rem}
h1{font:800 clamp(2.8rem,8vw,6rem)/.95 var(--display);letter-spacing:-.035em;margin:0 0 1.25rem}
.lead{font:500 clamp(1.35rem,3vw,2rem)/1.25 var(--display);max-width:30ch;margin:0 0 1rem;letter-spacing:-.01em}
.sub{max-width:56ch;color:var(--muted);margin:0 0 1.75rem}
.cta{display:flex;flex-wrap:wrap;gap:.75rem}
.btn{display:inline-block;padding:.7rem 1.2rem;border-radius:.6rem;font-weight:600;text-decoration:none;border:1.5px solid var(--ink)}
.btn.primary{background:var(--blue);border-color:var(--blue);color:#fff}
[data-theme="dark"] .btn.primary{color:#0f1722}
@media (prefers-color-scheme:dark){:root:not([data-theme="light"]) .btn.primary{color:#0f1722}}
.btn:hover{transform:translateY(-1px)}

/* live pipeline */
.pipe{margin-top:3rem;background:var(--panel);border:1px solid var(--line);border-radius:1rem;padding:1.25rem 1.25rem 1rem}
.pipe h2{font:700 1rem var(--display);margin:0 0 .15rem}
.pipe p.cap{margin:0 0 1rem;color:var(--muted);font-size:.9rem}
.lane{display:grid;grid-template-columns:11rem 1fr 9rem;gap:1rem;align-items:center;padding:.6rem 0;border-top:1px solid var(--line)}
.lane .name{font-weight:600;font-size:.95rem;line-height:1.3}
.lane .name small{display:block;font-weight:400;color:var(--muted)}
.track{position:relative;height:2.2rem;border-radius:.5rem;background:var(--paper);overflow:hidden}
.dot{position:absolute;top:50%;left:0;width:.8rem;height:.8rem;margin-top:-.4rem;border-radius:50%}
.stream .dot{background:var(--blue)}
.batch .dot{background:var(--amber)}
.read{font:700 1.15rem var(--display);text-align:right;font-variant-numeric:tabular-nums}
.read small{display:block;font:400 .75rem var(--body);color:var(--muted)}
.batch .read{color:var(--amber)} .stream .read{color:var(--blue)}
@media(max-width:700px){.lane{grid-template-columns:1fr}.read{text-align:left}}

/* sections */
section{padding:3.5rem 0;border-top:1px solid var(--line)}
h2.t{font:700 clamp(1.8rem,4vw,2.6rem)/1.1 var(--display);letter-spacing:-.02em;margin:0 0 2rem}
.facts{display:grid;grid-template-columns:repeat(auto-fit,minmax(11rem,1fr));gap:1.5rem 2rem;margin:0;padding:0;list-style:none}
.facts b{display:block;font:800 2.1rem/1.1 var(--display);letter-spacing:-.02em;color:var(--blue)}
.facts span{color:var(--muted);font-size:.95rem}

.job{display:grid;grid-template-columns:13rem 1fr;gap:1rem 2.5rem;padding:0 0 2.75rem;margin-bottom:2.75rem;border-bottom:1px dashed var(--line)}
.job:last-child{border-bottom:0;margin-bottom:0;padding-bottom:0}
.job .meta{color:var(--muted);font-size:.95rem}
.job .meta b{display:block;color:var(--ink);font:700 1.15rem var(--display)}
.job h3{font:700 1.3rem var(--display);margin:0 0 .75rem}
.job ul{margin:0 0 1rem;padding-left:1.1rem;max-width:68ch}
.job li{margin-bottom:.5rem}
.job li::marker{color:var(--blue)}
.stack{font-size:.9rem;color:var(--muted)}
.stack b{color:var(--ink)}
@media(max-width:760px){.job{grid-template-columns:1fr}}

.skills{display:grid;grid-template-columns:repeat(auto-fit,minmax(16rem,1fr));gap:1.75rem 2.5rem}
.skills h3{font:700 1rem var(--display);margin:0 0 .5rem}
.chips{display:flex;flex-wrap:wrap;gap:.4rem;margin:0;padding:0;list-style:none}
.chips li{background:var(--blue-bg);color:var(--ink);padding:.15rem .65rem;border-radius:999px;font-size:.88rem}
.two{display:grid;grid-template-columns:repeat(auto-fit,minmax(18rem,1fr));gap:2.5rem}
.two h3{font:700 1.2rem var(--display);margin:0 0 .5rem}
.certs{list-style:none;margin:0;padding:0}
.certs li{padding:.55rem 0;border-bottom:1px solid var(--line)}
.certs li span{color:var(--muted);font-size:.9rem}
.contact p{max-width:48ch;color:var(--muted)}
.contact .big{font:700 clamp(1.4rem,4vw,2.4rem) var(--display);word-break:break-all;color:var(--blue);text-decoration:none;border-bottom:3px solid var(--amber)}
.links{display:flex;gap:1.5rem;flex-wrap:wrap;margin-top:1.5rem}
footer{padding:2rem 0;color:var(--muted);font-size:.9rem;border-top:1px solid var(--line)}

/* one orchestrated load moment */
@media (prefers-reduced-motion:no-preference){
  h1,.lead,.sub,.cta,.pipe{animation:rise .7s cubic-bezier(.2,.7,.2,1) both}
  .lead{animation-delay:.08s}.sub{animation-delay:.16s}.cta{animation-delay:.24s}.pipe{animation-delay:.34s}
  @keyframes rise{from{opacity:0;transform:translateY(14px)}to{opacity:1;transform:none}}
}
</style>
</head>
<body>
<header class="nav">
  <div class="wrap">
    <b>Ooha Poloju</b>
    <nav aria-label="Primary">
      <a href="#impact" class="hide-s">Impact</a>
      <a href="#experience">Experience</a>
      <a href="#skills" class="hide-s">Skills</a>
      <a href="#contact">Contact</a>
      <button id="theme" type="button" aria-label="Toggle light and dark theme">Theme</button>
    </nav>
  </div>
</header>

<main>
<div class="wrap hero">
  <h1>Ooha Poloju</h1>
  <p class="lead">I build backend systems that move data in seconds, not minutes.</p>
  <p class="sub">Software engineer with nearly six years across banking and healthcare. I work on event-driven services, streaming pipelines and cloud platforms with Java, Kafka, Spark, Azure and AWS. Based in Dallas, Texas.</p>
  <div class="cta">
    <a class="btn primary" href="#experience">See my work</a>
    <a class="btn" href="mailto:polojuooha03@gmail.com">Email me</a>
    <a class="btn" href="resume.pdf">Download resume</a>
  </div>

  <div class="pipe" aria-labelledby="pipe-h">
    <h2 id="pipe-h">The Citibank change, in miniature</h2>
    <p class="cap">Same events, two designs. Time is sped up for this demo. Real result: transaction reporting went from 15 minutes to under 2 seconds.</p>
    <div class="lane batch">
      <div class="name">Legacy batch jobs<small>Hadoop, runs on a schedule</small></div>
      <div class="track" id="batchTrack" aria-hidden="true"></div>
      <div class="read"><span id="batchWait">0.0 s</span><small>oldest event waiting</small></div>
    </div>
    <div class="lane stream">
      <div class="name">Streaming service<small>Kafka on Azure</small></div>
      <div class="track" id="streamTrack" aria-hidden="true"></div>
      <div class="read"><span id="streamLat">1.4 s</span><small>delivery time</small></div>
    </div>
  </div>
</div>

<section id="impact"><div class="wrap">
  <h2 class="t">Results I can point to</h2>
  <ul class="facts">
    <li><b>15 min to under 2 s</b><span>Transaction reporting latency at Citibank after replacing 8 Hadoop batch jobs with Kafka streaming</span></li>
    <li><b>99.95%</b><span>Uptime across 5M+ daily transaction events</span></li>
    <li><b>2M+ requests/day</b><span>Served by Spring Boot APIs at p99 under 150 ms</span></li>
    <li><b>100M+ claims</b><span>Healthcare claims reprocessed in Spark, nightly runtime cut from 8 to 3 hours</span></li>
    <li><b>40%</b><span>Lower pipeline latency using AWS Step Functions at CIE</span></li>
  </ul>
</div></section>

<section id="experience"><div class="wrap">
  <h2 class="t">Experience</h2>

  <article class="job">
    <div class="meta"><b>Citibank</b>Dallas, Texas<br>Aug 2024 to present</div>
    <div>
      <h3>Software Engineer</h3>
      <ul>
        <li>Replaced 8 legacy Hadoop batch jobs with Kafka streaming services on Azure, cutting transaction reporting latency from 15 minutes to under 2 seconds.</li>
        <li>Designed event-driven microservices on Kafka and AKS that sustain 99.95% uptime across 5M+ daily transaction events.</li>
        <li>Built RESTful APIs in Java and Spring Boot for 12 risk and regulatory reporting applications, serving 2M+ requests a day at p99 under 150 ms.</li>
        <li>Added Redis caching to Hibernate data-access layers over PostgreSQL, cutting average query time by 45%.</li>
        <li>Secured service-to-service calls with OAuth2/JWT and Azure Key Vault. Two internal audits closed with zero critical findings.</li>
        <li>Built Azure Monitor and Grafana alerting that cut incident detection time by 40%, and moved releases from biweekly to daily with Jenkins quality gates.</li>
      </ul>
      <p class="stack"><b>Stack:</b> Java, Spring Boot, Kafka, AKS, Redis, PostgreSQL, Hibernate, Azure Key Vault, Grafana, Jenkins</p>
    </div>
  </article>

  <article class="job">
    <div class="meta"><b>CIE</b>Harrisburg, Pennsylvania<br>Sep 2023 to May 2024</div>
    <div>
      <h3>Software Engineer</h3>
      <ul>
        <li>Built serverless Python services on AWS Lambda that process 50M+ IoT events a day.</li>
        <li>Orchestrated event-driven workflows with Step Functions, cutting processing latency by 40%.</li>
        <li>Deployed real-time anomaly detection models on SageMaker that flag anomalies within 5 seconds.</li>
        <li>Designed GraphQL APIs now used by 9 internal and partner systems.</li>
        <li>Tuned Redshift queries and indexing, taking dashboard load times from 30 seconds to 4. CloudWatch alerting cut mean time to resolution by 30%.</li>
      </ul>
      <p class="stack"><b>Stack:</b> Python, AWS Lambda, Step Functions, SageMaker, GraphQL, Redshift, CloudWatch</p>
    </div>
  </article>

  <article class="job">
    <div class="meta"><b>Ascension Health</b>Hyderabad, India<br>Jan 2021 to Jul 2023</div>
    <div>
      <h3>Junior Software Engineer</h3>
      <ul>
        <li>Built Python ETL integrations that load 1M+ HL7/FHIR messages a day from 40+ facilities into Snowflake.</li>
        <li>Re-engineered batch processing of 100M+ healthcare claims in Spark, cutting nightly runtime from 8 hours to 3.</li>
        <li>Streamed device and claims data through Kafka with latency under 5 seconds.</li>
        <li>Partitioned and tuned 10TB+ of healthcare data in PySpark, cutting query runtime by 50%.</li>
        <li>Automated claims reconciliation with Airflow, removing 10+ hours of manual work every week.</li>
        <li>Onboarded 3 new engineers and led code reviews for a team of 8.</li>
      </ul>
      <p class="stack"><b>Stack:</b> Python, Spark, PySpark, Kafka, Airflow, Snowflake, HL7, FHIR</p>
    </div>
  </article>
</div></section>

<section id="skills"><div class="wrap">
  <h2 class="t">Skills</h2>
  <div class="skills">
    <div><h3>Languages</h3><ul class="chips"><li>Java</li><li>Python</li><li>SQL</li><li>Shell</li></ul></div>
    <div><h3>Backend</h3><ul class="chips"><li>Spring Boot</li><li>Hibernate/JPA</li><li>REST</li><li>GraphQL</li><li>Microservices</li></ul></div>
    <div><h3>Streaming and data</h3><ul class="chips"><li>Kafka</li><li>Kinesis</li><li>Spark</li><li>PySpark</li><li>Airflow</li></ul></div>
    <div><h3>Cloud</h3><ul class="chips"><li>Azure AKS</li><li>Azure Functions</li><li>Key Vault</li><li>AWS Lambda</li><li>Step Functions</li><li>SageMaker</li><li>EKS</li></ul></div>
    <div><h3>Databases</h3><ul class="chips"><li>PostgreSQL</li><li>SQL Server</li><li>Snowflake</li><li>Redshift</li></ul></div>
    <div><h3>DevOps and testing</h3><ul class="chips"><li>Jenkins</li><li>CI/CD</li><li>Docker</li><li>Kubernetes</li><li>JUnit</li><li>pytest</li></ul></div>
    <div><h3>Monitoring</h3><ul class="chips"><li>Azure Monitor</li><li>CloudWatch</li><li>Grafana</li></ul></div>
    <div><h3>Healthcare data</h3><ul class="chips"><li>HL7</li><li>FHIR</li><li>EDI 837/835</li></ul></div>
  </div>
</div></section>

<section id="education"><div class="wrap two">
  <div>
    <h2 class="t">Education</h2>
    <h3>Master of Science in Computer Science</h3>
    <p>Harrisburg University of Science and Technology, Harrisburg, Pennsylvania<br><span style="color:var(--muted)">Aug 2023 to May 2025 · GPA 3.5/4.0</span></p>
  </div>
  <div>
    <h2 class="t">Certifications</h2>
    <ul class="certs">
      <li>AWS Certified Solutions Architect, Associate <span>· 2025</span></li>
      <li>AWS Certified Developer, Associate</li>
      <li>AWS Certified Cloud Practitioner</li>
      <li>Mastering Spring Framework, Coursera <span>· 2025</span></li>
    </ul>
  </div>
</div></section>

<section id="contact" class="contact"><div class="wrap">
  <h2 class="t">Let’s talk</h2>
  <p>I’m looking for senior roles in distributed systems and real-time data. The fastest way to reach me is email.</p>
  <a class="big" href="mailto:polojuooha03@gmail.com">polojuooha03@gmail.com</a>
  <div class="links">
    <a href="https://linkedin.com/in/ooha-poloju-3b7b42435" rel="noopener">LinkedIn</a>
    <a href="https://github.com/Oohapoloju" rel="noopener">GitHub</a>
    <a href="resume.pdf">Resume (PDF)</a>
  </div>
</div></section>
</main>

<footer><div class="wrap">© <span id="yr">2026</span> Ooha Poloju. Dallas, Texas.</div></footer>

<script>
(function(){
  document.getElementById('yr').textContent=new Date().getFullYear();

  // theme toggle (remembered when storage is available)
  var root=document.documentElement,btn=document.getElementById('theme');
  try{var s=localStorage.getItem('theme');if(s)root.setAttribute('data-theme',s)}catch(e){}
  btn.addEventListener('click',function(){
    var dark=root.getAttribute('data-theme')?root.getAttribute('data-theme')==='dark':matchMedia('(prefers-color-scheme:dark)').matches;
    var next=dark?'light':'dark';root.setAttribute('data-theme',next);
    try{localStorage.setItem('theme',next)}catch(e){}
  });

  // pipeline demo
  if(matchMedia('(prefers-reduced-motion:reduce)').matches)return;
  var bt=document.getElementById('batchTrack'),st=document.getElementById('streamTrack');
  var bw=document.getElementById('batchWait'),sl=document.getElementById('streamLat');
  var TRAVEL=1400,FLUSH=7000,TICK=650;
  var waiting=[],first=null,last=Date.now();

  function mk(track){var d=document.createElement('span');d.className='dot';track.appendChild(d);return d}
  function fly(d,from){
    d.style.left=from;
    requestAnimationFrame(function(){requestAnimationFrame(function(){
      d.style.transition='left '+TRAVEL+'ms linear';d.style.left='calc(100% - .8rem)';
    })});
    setTimeout(function(){d.remove()},TRAVEL+100);
  }
  function tick(){
    if(document.hidden)return;
    fly(mk(st),'0');
    var d=mk(bt);var x=Math.min(waiting.length,38)*2.4+1;
    d.style.left=x+'%';waiting.push(d);if(!first)first=Date.now();
  }
  function flush(){
    waiting.forEach(function(d){
      var from=d.style.left;
      requestAnimationFrame(function(){d.style.transition='left '+TRAVEL+'ms linear';d.style.left='calc(100% - .8rem)'});
      setTimeout(function(){d.remove()},TRAVEL+100);
    });
    waiting=[];first=null;
  }
  setInterval(tick,TICK);
  setInterval(flush,FLUSH);
  setInterval(function(){bw.textContent=first?((Date.now()-first)/1000).toFixed(1)+' s':'0.0 s'},100);
  sl.textContent=(TRAVEL/1000).toFixed(1)+' s';
})();
</script>
</body>
</html>
