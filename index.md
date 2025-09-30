---
layout: default
title: Clément Herman
---

<style>
  body {
  font-family: "Courier New", Courier, monospace;
}
  .container {
    display: flex;
    flex-wrap: wrap;
    max-width: 1000px;
    margin: 0 auto;
  }
  .sidebar {
    flex: 1 1 30%;
    padding: 20px;
    background-color: #f5f5f5;
    min-width: 200px;
    box-sizing: border-box;
    text-align: center;
  }
  .sidebar img {
    border-radius: 50%;
    width: 140px;
    height: 140px;
    object-fit: cover;
    margin-bottom: 15px;
  }
  .sidebar a {
    display: block;
    margin: 8px 0;
    text-decoration: none;
  }

  .main-content {
    flex: 1 1 70%;
    padding: 20px;
    box-sizing: border-box;
  }

  h1 {
    margin-top: 0;
  }

  .abstract {
    display: none;
    margin-top: 5px;
  }

  button {
    margin-top: 5px;
  }

  .project {
  margin-bottom: 40px;
}
</style>

<div class="container">

  <div class="sidebar">
    <img src="photo_clement.jpg" alt="Photo de Clément Herman">
    <a href="https://drive.google.com/file/d/1TrC1MCd6kxQlAt9jsvOpUZAS79TmcFaq/view?usp=share_link" target="_blank">📄 CV</a>
    <a href="mailto:cherman@princeton.edu">✉️ cherman@princeton.edu</a>
    <a href="https://bsky.app/profile/clemherm.bsky.social" target="_blank">🌐 Bluesky</a>
  </div>

  <div class="main-content">
    <h1>Welcome to Clément Herman's Website!</h1>

    <h2>About me</h2>
    <p>
      I am a Ph.D. candidate in Economics at Princeton University. I am a microeconomist with research interests in Behavioral Economics, Experimental Economics, and Political Economy.
    </p>

    <h2>Research</h2>

<div class="project">
  <h3><a href="https://drive.google.com/file/d/1y5wnjRmn4bTxqYAMbl-4sAGgy0OrtrPL/view?usp=share_link" target="_blank">How Do Groups Search? Experimental Evidence</a></h3>
  <em>Working Paper, 2025 · Submitted</em><br>
  <button onclick="toggleAbstract('abs1')">Abstract</button>
  <div class="abstract" id="abs1">
    <p>Searching for a suitable alternative—whether in research teams, hiring committees, or households—is often a collective process, combining the trade-offs of individual search with the challenges of group decision-making. We study collective search in laboratory experiments, where groups of participants sequentially sample alternatives. We vary the stopping-decision rule and the alignment of group members’ preferences, and compare group behavior to that of individuals under otherwise identical conditions. Several patterns emerge. While individuals tend to undersearch, groups examine more alternatives, particularly when unanimity is required to stop. When preferences are aligned, group search generates beneficial effects: participants raise their standards, and low-value alternatives are more likely to be rejected. When preferences are misaligned, however, group search generates detrimental effects: high-value alternatives are often rejected, and participants adopt lower standards. These findings reveal a new channel, the sequential exploration of alternatives, through which groups can outperform or underperform individual decision-making.</p>
  </div>
</div>

<div class="project">
  <h3>Where to Search and When to Stop: A Lab Study</h3>
  <p>
    <strong>With:</strong> 
    <a href="https://sites.google.com/view/lizzeri" target="_blank" rel="noopener noreferrer">
      Alessandro Lizzeri
    </a>, 
    <a href="https://www.lyariv.com" target="_blank" rel="noopener noreferrer">
      Leeat Yariv
    </a>
  </p>
  <em>In preparation</em>
</div>




<div class="project">
  <h3>
    Communicating with Data-Generating Processes: An Experimental Analysis (Agata's JMP!)
  </h3>
  <p>
    <strong>With:</strong> 
    <a href="https://www.agatafarina.com" target="_blank" rel="noopener noreferrer">
      Agata Farina
    </a>
  </p>
  <em>In preparation</em>
</div>



  </div>
</div>

<script>
function toggleAbstract(id) {
  var x = document.getElementById(id);
  if (x.style.display === "none" || x.style.display === "") {
    x.style.display = "block";
  } else {
    x.style.display = "none";
  }
}
</script>
