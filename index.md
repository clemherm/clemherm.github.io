---
layout: default
title: "Clément Herman"
description: "Clément Herman — PhD candidate at Princeton. Behavioral & experimental economics, political economy. Research on collective (group) search, stopping rules, and decision-making."
permalink: /
---

<style>
  body { font-family: "Courier New", Courier, monospace; }
  .container {
    display: flex; flex-wrap: wrap; max-width: 1000px; margin: 0 auto;
  }
  .sidebar {
    flex: 1 1 30%; padding: 20px; background-color: #f5f5f5;
    min-width: 200px; box-sizing: border-box; text-align: center;
  }
  .sidebar img {
    border-radius: 50%; width: 240px; height: 240px; object-fit: cover;
    margin-bottom: 15px;
  }
  .sidebar a { display: block; margin: 8px 0; text-decoration: none; }
  .main-content { flex: 1 1 70%; padding: 20px; box-sizing: border-box; }
  h1 { margin-top: 0; }
  .abstract { display: none; margin-top: 5px; }
  button { margin-top: 5px; }
  .project { margin-bottom: 40px; }
  .nav { margin: 10px 0 20px; }
  .nav a { margin-right: 12px; }
</style>

<div class="container">

  <div class="sidebar">
    <!-- SEO: add descriptive alt and lazy-load -->
    <img src="photo_clement_edit.png" alt="Portrait of Clément Herman" loading="lazy" width="140" height="140">
    <!-- SEO: add rel=noopener and rel=me for profile -->
    <a href="https://drive.google.com/file/d/1TrC1MCd6kxQlAt9jsvOpUZAS79TmcFaq/view?usp=share_link" target="_blank" rel="noopener">📄 CV</a>
    <a href="mailto:cherman@princeton.edu">✉️ cherman@princeton.edu</a>
    <a href="https://bsky.app/profile/clemherm.bsky.social" target="_blank" rel="me noopener">🌐 Bluesky</a>

    <!-- Optional: quick internal nav -->
    <div class="nav" aria-label="Section navigation">
      <a href="#about">About</a>
      <a href="#research">Research</a>
      <a href="#contact">Contact</a>
    </div>
  </div>

  <div class="main-content">
    <!-- SEO: put main keywords in H1 -->
    <h1>Clément Herman — PhD Candidate in Economics</h1>

    <h2 id="about">About me</h2>
    <p>
      I am a Ph.D. candidate in Economics at Princeton University. My research spans
      <strong>behavioral and experimental economics</strong> and <strong>political economy</strong>.
<br> <br>
      I served as Lab Manager for the <a href="https://pexl.lab.run" target="_blank" rel="noopener">Princeton Experimental Laboratory for the Social Sciences (PExL)</a> in 2023–2024.
Since 2024, I have been supported by the <a href="https://gradschool.princeton.edu/financial-support/fellowships/princeton-fellowships/prize-fellowship-social-sciences" target="_blank" rel="noopener">Prize Fellow in the Social Sciences</a> at Princeton University.
    </p>

    <h2 id="research">Research</h2>

    <div class="project">
      <h3>
        <a href="https://drive.google.com/file/d/1y5wnjRmn4bTxqYAMbl-4sAGgy0OrtrPL/view?usp=share_link"
           target="_blank" rel="noopener">
          How Do Groups Search? Experimental Evidence
        </a>
      </h3>
      <em>Working Paper, 2025 · Submitted</em><br>
      <!-- Accessibility: button controls & aria-expanded -->
      <button type="button" aria-expanded="false" aria-controls="abs1" onclick="toggleAbstract('abs1', this)">
        Abstract
      </button>
      <div class="abstract" id="abs1">
        <p>Searching for a suitable alternative—whether in research teams, hiring committees, or households—is often a collective process, combining the trade-offs of individual search with the challenges of group decision-making. We study collective search in laboratory experiments, where groups of participants sequentially sample alternatives. We vary the stopping-decision rule and the alignment of group members’ preferences, and compare group behavior to that of individuals under otherwise identical conditions. Several patterns emerge. While individuals tend to undersearch, groups examine more alternatives, particularly when unanimity is required to stop. When preferences are aligned, group search generates beneficial effects: participants raise their standards, and low-value alternatives are more likely to be rejected. When preferences are misaligned, however, group search generates detrimental effects: high-value alternatives are often rejected, and participants adopt lower standards. These findings reveal a new channel, the sequential exploration of alternatives, through which groups can outperform or underperform individual decision-making.</p>
      </div>
    </div>

    <div class="project">
      <h3>Where to Search and When to Stop: A Lab Study</h3>
      <p>
        <strong>With:</strong>
        <a href="https://sites.google.com/view/lizzeri" target="_blank" rel="noopener">Alessandro Lizzeri</a>,
        <a href="https://www.lyariv.com" target="_blank" rel="noopener">Leeat Yariv</a>
      </p>
      <em>In preparation</em>
    </div>

    <div class="project">
      <h3>Communicating with Data-Generating Processes: An Experimental Analysis (Agata's JMP!)</h3>
      <p>
        <strong>With:</strong>
        <a href="https://www.agatafarina.com" target="_blank" rel="noopener">Agata Farina</a>
      </p>
      <em>In preparation</em>
    </div>
  </div>
</div>

<script>
function toggleAbstract(id, btn) {
  var x = document.getElementById(id);
  var isHidden = (x.style.display === "none" || x.style.display === "");
  x.style.display = isHidden ? "block" : "none";
  if (btn) btn.setAttribute("aria-expanded", isHidden ? "true" : "false");
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

<!-- Example article schema for the working paper; duplicate & adjust for others if you like -->
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
