---
layout: default
title: "Clément Herman"
description: "Clément Herman — PhD candidate at Princeton. Behavioral & experimental economics, political economy. Research on collective (group) search, stopping rules, and decision-making."
permalink: /
---

<style>
  :root{
    --accent:#111;             /* button text/icon */
    --accent-bg:#f1f1f1;       /* button background */
    --accent-bg-hover:#e7e7e7; /* hover */
    --ring:#8ab4f8;            /* focus ring */
    --abstract-bg:#fafafa;     /* abstract panel bg */
  }

  body { font-family: "Courier New", Courier, monospace; }
  .container { display:flex; flex-wrap:wrap; max-width:1000px; margin:0 auto; }
  .sidebar { flex:1 1 30%; padding:20px; background-color:#f5f5f5; min-width:200px; box-sizing:border-box; text-align:center; }
  .sidebar img { border-radius:50%; width:240px; height:240px; object-fit:cover; margin-bottom:15px; }
  .sidebar a { display:block; margin:8px 0; text-decoration:none; }
  .main-content { flex:1 1 70%; padding:20px; box-sizing:border-box; }
  h1 { margin-top:0; }
  .project { margin-bottom:40px; }
  .nav { margin:10px 0 20px; }
  .nav a { margin-right:12px; }

  /* ---------- Abstract toggle button ---------- */
  .abstract-toggle{
    --pad-y: 6px; --pad-x: 12px; --radius: 999px;
    display:inline-flex; align-items:center; gap:8px;
    padding: var(--pad-y) var(--pad-x);
    border:1px solid #ddd; border-radius: var(--radius);
    background: var(--accent-bg);
    color: var(--accent); font-weight:600; letter-spacing:.2px;
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
    line-height:1.45;
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
    <img src="photo_clement_edit.png" alt="Portrait of Clément Herman" loading="lazy" width="140" height="140">
    <a href="https://drive.google.com/file/d/1TrC1MCd6kxQlAt9jsvOpUZAS79TmcFaq/view?usp=share_link" target="_blank" rel="noopener">📄 CV</a>
    <a href="mailto:cherman@princeton.edu">✉️ cherman@princeton.edu</a>
    <a href="https://bsky.app/profile/clemherm.bsky.social" target="_blank" rel="me noopener">🌐 Bluesky</a>

    <div class="nav" aria-label="Section navigation">
      <a href="#about">About</a>
      <a href="#research">Research</a>
    </div>
  </div>

  <div class="main-content">
    <h1>Clément Herman — <br> PhD Candidate in Economics</h1>

    <h2 id="about">About me</h2>
    <p>
      I am a Ph.D. candidate in Economics at Princeton University. My research spans
      <strong>behavioral and experimental economics</strong> and <strong>political economy</strong>.
      <br><br>
      I served as Lab Manager for the <a href="https://pexl.lab.run" target="_blank" rel="noopener">Princeton Experimental Laboratory for the Social Sciences (PExL)</a> in 2023–2024.
      Since 2024, I have been supported by the <a href="https://gradschool.princeton.edu/financial-support/fellowships/princeton-fellowships/prize-fellowship-social-sciences" target="_blank" rel="noopener">Prize Fellowship in the Social Sciences</a> at Princeton University.
    </p>

    <h2 id="research">Research</h2>

    <div class="project">
      <h3>
        <a href="https://drive.google.com/file/d/1y5wnjRmn4bTxqYAMbl-4sAGgy0OrtrPL/view?usp=share_link"
           target="_blank" rel="noopener">
          Searching Alone or Together? Evidence from the Lab
        </a>
      </h3>
      <em>Working Paper, 2025 · Submitted</em><br>

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
      <h3>        <a href="https://drive.google.com/file/d/1IHxUsEYY6GrKq6VCnENFPaqMZ7Wx2E0E/view?usp=share_link"
           target="_blank" rel="noopener">
          Communicating with Data-Generating Processes: An Experimental Analysis
        </a> (Agata's JMP!)
      
      
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

  </div>
</div>

<script>
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
  "jobTitle": "PhD Candidate in Economics",
  "affiliation": {
    "@type": "CollegeOrUniversity",
    "name": "Princeton University"
  },
  "email": "mailto:cherman@princeton.edu",
  "url": "https://clement-herman.com",
  "sameAs": [
    "https://bsky.app/profile/clemherm.bsky.social",
    "https://scholar.google.com/scholar?q=Cl%C3%A9ment+Herman"
  ]
}
</script>

<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "ScholarlyArticle",
  "name": "How Do Groups Search? Experimental Evidence",
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
