---
layout: default
title: "Clément Herman"
description: "Clément Herman — Postdoctoral Scholar at Caltech. Behavioral & experimental economics, political economy. Research on collective (group) search, stopping rules, and decision-making."
permalink: /
---

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Fraunces:opsz,wght@9..144,500;9..144,600;9..144,700&family=Inter:wght@400;500;600&display=swap" rel="stylesheet">

<style>
  :root{
    --accent:#111;             /* button text/icon */
    --accent-bg:#f1f1f1;       /* button background */
    --accent-bg-hover:#e7e7e7; /* hover */
    --ring:#8ab4f8;            /* focus ring */
    --abstract-bg:#fafafa;     /* abstract panel bg */
    --font-heading: "Fraunces", Georgia, serif;
    --font-body: "Inter", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
  }

  body {
    font-family: var(--font-body);
    font-size: 16px;
    line-height: 1.6;
    color: #1a1a1a;
  }

  h1, h2, h3 {
    font-family: var(--font-heading);
    font-weight: 600;
    letter-spacing: -0.01em;
  }

  h1 { font-weight: 700; }

  .container { display:flex; flex-wrap:wrap; max-width:1000px; margin:0 auto; }
  .sidebar { flex:1 1 30%; padding:20px; background-color:#f5f5f5; min-width:200px; box-sizing:border-box; text-align:center; }
  .sidebar img { border-radius:50%; width:240px; height:240px; object-fit:cover; margin-bottom:15px; }
  .sidebar a { display:block; margin:8px 0; text-decoration:none; font-family: var(--font-body); }
  .main-content { flex:1 1 70%; padding:20px; box-sizing:border-box; }
  .project { margin-bottom:40px; }

  /* ---------- Tabs ---------- */
  .tabs {
    display:flex; gap:4px;
    border-bottom:1px solid #e2e2e2;
    margin:0 0 24px;
  }
  .tabs a {
    padding:8px 16px;
    text-decoration:none;
    color:#666;
    font-weight:500;
    border-bottom:2px solid transparent;
    margin-bottom:-1px;
  }
  .tabs a:hover { color:#111; }
  .tabs a[aria-selected="true"] { color:#111; font-weight:600; border-bottom-color:#111; }
  .tabs a:focus-visible { outline:3px solid var(--ring); outline-offset:2px; border-radius:4px; }

  /* Override any theme styling so the tab content lines up with the heading */
  .main-content .tab-panel {
    float:none; width:auto; max-width:none;
    margin:0; padding:0;
    text-align:left;
  }

  /* Only hide inactive tabs once the script has run; without JS everything shows. */
  .js .tab-panel:not(.active) { display:none; }

  /* ---------- Home tab research teaser ---------- */
  .teaser { list-style:none; padding:0; margin:0 0 16px; }
  .teaser li { margin-bottom:14px; }
  .teaser .title { font-family: var(--font-heading); font-weight:600; font-size:17px; }
  .teaser .meta { display:block; color:#666; font-size:14px; }
  .more-link { font-weight:600; text-decoration:none; }

  /* ---------- Abstract toggle button ---------- */
  .abstract-toggle{
    --pad-y: 6px; --pad-x: 12px; --radius: 999px;
    display:inline-flex; align-items:center; gap:8px;
    padding: var(--pad-y) var(--pad-x);
    border:1px solid #ddd; border-radius: var(--radius);
    background: var(--accent-bg);
    color: var(--accent); font-weight:600; letter-spacing:.2px;
    font-family: var(--font-body);
    font-size: 14px;
    cursor:pointer; user-select:none;
    transition: background .15s ease, transform .06s ease;
  }
  .abstract-toggle:hover{ background: var(--accent-bg-hover); }
  .abstract-toggle:active{ transform: translateY(1px); }
  .abstract-toggle:focus-visible{
    outline: 3px solid var(--ring);
    outline-offset: 2px;
  }
  .abstract-toggle svg{ width:14px; height:14px; transition: transform .2s ease; }
  .abstract-toggle[aria-expanded="true"] svg{ transform: rotate(180deg); }

  /* ---------- Abstract panel with smooth expand ---------- */
  .abstract[hidden]{
    display:block;               /* keep flow for transition */
    max-height:0;
    padding:0;
    overflow:hidden;
    border-color: transparent;
  }
  .abstract{
    display:block;
    background: var(--abstract-bg);
    border:1px solid #eee;
    border-radius:12px;
    margin-top:10px;
    padding:12px 14px;
    line-height:1.55;
    font-family: var(--font-body);
    transition: max-height .25s ease, padding .2s ease, border-color .2s ease;
    max-height: 1000px;          /* sufficiently large */
  }

  @media (prefers-reduced-motion: reduce){
    .abstract{ transition:none; }
    .abstract-toggle svg{ transition:none; }
  }
</style>

<div class="container">

  <div class="sidebar">
    <img src="me.jpg" alt="Portrait of Clément Herman" loading="lazy" width="140" height="140">
    <a href="https://drive.google.com/file/d/1TrC1MCd6kxQlAt9jsvOpUZAS79TmcFaq/view?usp=share_link" target="_blank" rel="noopener">📄 CV</a>
    <a href="mailto:cherman@princeton.edu">✉️ cherman@princeton.edu</a>
    <a href="https://scholar.google.com/citations?user=9imfc4YAAAAJ" target="_blank" rel="me noopener">🎓 Google Scholar</a>
    <a href="https://bsky.app/profile/clemherm.bsky.social" target="_blank" rel="me noopener">🌐 Bluesky</a>
  </div>

  <div class="main-content">
    <h1>Clément Herman — <br> Postdoctoral Scholar in Economics</h1>

    <!-- To add a tab: add a link here (href="#name") and a matching <div id="name" class="tab-panel"> below. -->
    <div class="tabs" role="tablist" aria-label="Sections">
      <a href="#home" role="tab" aria-controls="home">Home</a>
      <a href="#research" role="tab" aria-controls="research">Research</a>
    </div>

    <!-- ================= HOME TAB ================= -->
    <div id="home" class="tab-panel" role="tabpanel">
      <h2>About me</h2>
      <p>
        I am a postdoctoral scholar at <b>Caltech</b>. I received my Ph.D. in Economics from
        Princeton University. My research spans
        <strong>behavioral and experimental economics</strong> and <strong>political economy</strong>.
        <br><br>
        During my Ph.D., I served as Lab Manager for the <a href="https://pexl.lab.run" target="_blank" rel="noopener">Princeton Experimental Laboratory for the Social Sciences (PExL)</a> in 2023–2024.
      </p>

      <h2>Working Papers</h2>
      <ul class="teaser">
        <li>
          <a class="title" href="https://drive.google.com/file/d/1y5wnjRmn4bTxqYAMbl-4sAGgy0OrtrPL/view?usp=share_link" target="_blank" rel="noopener">Searching Alone or Together? Evidence from the Lab</a>
          <span class="meta">Revise &amp; Resubmit (second round) at <em>Quantitative Economics</em></span>
        </li>
        <li>
          <a class="title" href="https://drive.google.com/file/d/1IHxUsEYY6GrKq6VCnENFPaqMZ7Wx2E0E/view?usp=share_link" target="_blank" rel="noopener">Communicating with Data-Generating Processes: An Experimental Analysis</a>
          <span class="meta">With Agata Farina · Draft available</span>
        </li>
      </ul>
      <a class="more-link" href="#research">All papers, works in progress and abstracts →</a>
    </div>

    <!-- ================= RESEARCH TAB ================= -->
    <div id="research" class="tab-panel" role="tabpanel">
      <h2>Working Papers</h2>

      <div class="project">
        <h3>
          <a href="https://drive.google.com/file/d/1y5wnjRmn4bTxqYAMbl-4sAGgy0OrtrPL/view?usp=share_link"
             target="_blank" rel="noopener">
            Searching Alone or Together? Evidence from the Lab
          </a>
        </h3>
        <em>Revise & Resubmit (second round) at Quantitative Economics</em><br>

        <button type="button"
                class="abstract-toggle"
                aria-expanded="false"
                aria-controls="abs-groups"
                onclick="toggleAbstract('abs-groups', this)">
          <svg viewBox="0 0 24 24" aria-hidden="true"><path d="M12 15.5a1 1 0 0 1-.71-.29l-6-6a1 1 0 1 1 1.42-1.42L12 12.38l5.29-4.59a1 1 0 1 1 1.42 1.42l-6 6a1 1 0 0 1-.71.29z"/></svg>
          <span>Show abstract</span>
        </button>

        <div class="abstract" id="abs-groups" hidden>
          <p>Groups, not just individuals, carry out search over candidates, products, and projects, yet standard approaches treat search as an individual activity. In laboratory experiments, we study groups that sequentially sample alternatives, varying stopping-decision rules and the alignment of group members' preferences, and compare them to individuals under identical conditions. Individuals undersearch, whereas groups systematically examine more alternatives, especially under stricter stopping rules. With aligned preferences, longer group search improves outcomes by raising reservation thresholds and smoothing variability in strategies, thereby increasing the rejection of low-value alternatives. With misaligned preferences, it has detrimental effects: high-value alternatives are rejected more often because agreement is harder to reach, even though participants lower their standards. The paper thus identifies sequential exploration (rather than deliberation or information aggregation) as a novel mechanism explaining why groups outperform or underperform individuals, and challenges modeling group search as if a single “unitary” decision maker were at work.</p>
        </div>
      </div>


      <div class="project">
        <h3>
          <a href="https://drive.google.com/file/d/1IHxUsEYY6GrKq6VCnENFPaqMZ7Wx2E0E/view?usp=share_link"
             target="_blank" rel="noopener">
            Communicating with Data-Generating Processes: An Experimental Analysis
          </a>
        </h3>
        <p>
          <strong>With:</strong>
          <a href="https://www.agatafarina.com" target="_blank" rel="noopener">Agata Farina</a>
        </p>
        <em>Draft available!</em><br>

        <button type="button"
                class="abstract-toggle"
                aria-expanded="false"
                aria-controls="abs-dgp"
                onclick="toggleAbstract('abs-dgp', this)">
          <svg viewBox="0 0 24 24" aria-hidden="true"><path d="M12 15.5a1 1 0 0 1-.71-.29l-6-6a1 1 0 1 1 1.42-1.42L12 12.38l5.29-4.59a1 1 0 1 1 1.42 1.42l-6 6a1 1 0 0 1-.71.29z"/></svg>
          <span>Show abstract</span>
        </button>

        <div class="abstract" id="abs-dgp" hidden>
          <p>In many applications, agents can influence how data are generated but cannot manipulate the data themselves. For example, students choose which classes to take but cannot alter their grades, and firms decide on internal accounting practices but cannot change the resulting financial statements. This paper experimentally studies information transmission when data are generated through an unobservable, strategically chosen process. We focus on settings where an informed sender—such as a student or a firm—privately selects a data-generating process (DGP)—a portfolio of classes or an accounting practice—to shape the beliefs of an uninformed receiver, such as an employer or an investor. Across treatments, we vary which DGPs are feasible and whether some come at a cost. These variations span different levels of information verifiability and allow us to capture, within a unified framework, the core insights of disclosure, cheap-talk, and signaling models. Our findings reveal three main patterns. First, while senders select their DGPs strategically in line with theoretical predictions, receivers often fail to account for this strategic selection. Second, introducing differential costs across feasible DGPs mitigates this "DGP selection neglect." Third, while receivers’ biases are robust across environments, their consequences vary: information transmission falters most when the evidence receivers observe is highly sensitive to the sender’s DGP choices. Finally, increasing transparency about the selected DGP—a policy often advocated in practice—does not, in general, improve information transmission.</p>
        </div>
      </div>


      <h2 id="in-progress">In Progress</h2>

      <div class="project">
        <h3>Where to Search and When to Stop: A Lab Study</h3>
        <p>
          <strong>With:</strong>
          <a href="https://sites.google.com/view/lizzeri" target="_blank" rel="noopener">Alessandro Lizzeri</a>,
          <a href="https://www.lyariv.com" target="_blank" rel="noopener">Leeat Yariv</a>
        </p>
        <em>In preparation</em><br>

        <button type="button"
                class="abstract-toggle"
                aria-expanded="false"
                aria-controls="abs-where"
                onclick="toggleAbstract('abs-where', this)">
          <svg viewBox="0 0 24 24" aria-hidden="true"><path d="M12 15.5a1 1 0 0 1-.71-.29l-6-6a1 1 0 1 1 1.42-1.42L12 12.38l5.29-4.59a1 1 0 1 1 1.42 1.42l-6 6a1 1 0 0 1-.71.29z"/></svg>
          <span>Show abstract</span>
        </button>

        <div class="abstract" id="abs-where" hidden>
          <p>In many real-life situations—such as searching for jobs, houses, or spouses—individuals must explore heterogeneous options sequentially before making a choice. This paper investigates how individuals search and when they stop searching in environments with heterogeneous alternatives. Drawing on Weitzman’s (1979) optimal search theory, we design a large-scale experiment that systematically explores a broad universe of search problems, in which participants face sequential search tasks involving costly inspections of alternatives (boxes) with varying reward distributions and search costs. While participants generally follow the direction of optimal search—favoring alternatives with higher expected value, lower cost, or greater variance—we document systematic deviations. These include pervasive undersearching, negative responses to variance in approximately one-third of participants, and menu-dependent behavior that violates the index-based predictions of Weitzman’s rule. Using structural modeling, we identify distinct behavioral types. We also show that specific combinations of box characteristics give rise to different search patterns, with more complex menus triggering greater departures from optimal behavior. Our findings highlight both the power and the limits of classical search theory in explaining actual search behavior.</p>
        </div>
      </div>


      <div class="project">
        <h3>Small Datasets as Mental Models</h3>
        <em>Slides available upon request</em><br>

        <button type="button"
                class="abstract-toggle"
                aria-expanded="false"
                aria-controls="abs-model"
                onclick="toggleAbstract('abs-model', this)">
          <svg viewBox="0 0 24 24" aria-hidden="true"><path d="M12 15.5a1 1 0 0 1-.71-.29l-6-6a1 1 0 1 1 1.42-1.42L12 12.38l5.29-4.59a1 1 0 1 1 1.42 1.42l-6 6a1 1 0 0 1-.71.29z"/></svg>
          <span>Show abstract</span>
        </button>

        <div class="abstract" id="abs-model" hidden>
          <p>How do people form beliefs about environments too rich to hold in memory? This paper develops and tests a framework in which decision-makers reduce large datasets to a small set of representative "cases"—a mental model—from which beliefs are then formed. In a lab experiment, participants view datasets of 12 items with 3 attributes each, construct 1–3 "guessing aids" summarizing what they observed, and later use only these aids to predict a hidden attribute value for unseen items. Comparing behavior to an optimal clustering (k-medians) benchmark, case selection largely tracks coverage as clustering predicts, but participants over-rely on literally observed and duplicated cases. Predictions track the nearest retained case, but moderates away from distant or extreme values. These deviations do not overturn the clustering benchmark's qualitative predictions about which datasets and statistics are well versus poorly recovered—they exacerbate them, producing worse accuracy for noisy datasets, outliers, extreme values, and higher-order statistical relationships like conditional correlations.</p>
        </div>
      </div>
    </div>

  </div>
</div>

<script>
/* ---------- Tabs: show one section at a time, driven by the URL hash ---------- */
(function(){
  document.documentElement.classList.add('js');
  const tabs = Array.from(document.querySelectorAll('.tabs a'));
  const panels = Array.from(document.querySelectorAll('.tab-panel'));
  const ids = panels.map(p => p.id);

  function show(id, scroll){
    if(!ids.includes(id)) id = ids[0];
    panels.forEach(p => p.classList.toggle('active', p.id === id));
    tabs.forEach(t => t.setAttribute('aria-selected', String(t.getAttribute('href') === '#' + id)));
    if(scroll) window.scrollTo({ top: 0 });
  }

  // Any link to #home / #research (tabs or in-page links) switches tabs
  // without jumping the page down to the section.
  document.addEventListener('click', function(e){
    const a = e.target.closest('a[href^="#"]');
    if(!a) return;
    const id = a.getAttribute('href').slice(1);
    if(!ids.includes(id)) return;
    e.preventDefault();
    history.pushState(null, '', '#' + id);
    show(id, true);
  });

  window.addEventListener('popstate', () => show(location.hash.slice(1), false));
  show(location.hash.slice(1), false);
})();

/* ---------- Abstract toggles ---------- */
function toggleAbstract(id, btn){
  const panel = document.getElementById(id);
  const expanded = btn.getAttribute('aria-expanded') === 'true';
  btn.setAttribute('aria-expanded', String(!expanded));
  const label = btn.querySelector('span');
  if(label) label.textContent = expanded ? 'Show abstract' : 'Hide abstract';

  if(expanded){
    // closing
    panel.style.maxHeight = panel.scrollHeight + 'px';
    requestAnimationFrame(()=>{
      panel.setAttribute('hidden','');
      panel.style.maxHeight = null;
    });
  } else {
    // opening
    panel.removeAttribute('hidden');
    const target = panel.scrollHeight;
    panel.style.maxHeight = '0px';
    requestAnimationFrame(()=>{
      panel.style.maxHeight = target + 'px';
      panel.addEventListener('transitionend', function tidy(e){
        if(e.propertyName === 'max-height'){
          panel.style.maxHeight = null;
          panel.removeEventListener('transitionend', tidy);
        }
      });
    });
  }
}
</script>

<!-- =================== -->
<!-- Minimal JSON-LD SEO -->
<!-- =================== -->
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "Person",
  "name": "Clément Herman",
  "jobTitle": "Postdoctoral Scholar in Economics",
  "affiliation": {
    "@type": "CollegeOrUniversity",
    "name": "California Institute of Technology"
  },
  "alumniOf": {
    "@type": "CollegeOrUniversity",
    "name": "Princeton University"
  },
  "email": "mailto:cherman@princeton.edu",
  "url": "https://clement-herman.com",
  "sameAs": [
    "https://bsky.app/profile/clemherm.bsky.social",
    "https://scholar.google.com/citations?user=9imfc4YAAAAJ"
  ]
}
</script>

<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "ScholarlyArticle",
  "name": "Searching Alone or Together? Evidence from the Lab",
  "author": {
    "@type": "Person",
    "name": "Clément Herman"
  },
  "inLanguage": "en",
  "datePublished": "2025",
  "url": "https://drive.google.com/file/d/1y5wnjRmn4bTxqYAMbl-4sAGgy0OrtrPL/view?usp=share_link",
  "isAccessibleForFree": true
}
</script>
