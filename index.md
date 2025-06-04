---
layout: default
title: Clément Herman
---

<style>
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
</style>

<div class="container">

  <div class="sidebar">
    <img src="photo_clement.jpeg" alt="Photo de Clément Herman">
    <a href="https://drive.google.com/file/d/1Gekom_rW1KhPX_Iw3T6jO6h6VYKndLcB/view?usp=share_link" target="_blank">📄 CV</a>
    <a href="mailto:cherman@princeton.edu">✉️ cherman@princeton.edu</a>
    <a href="https://bsky.app/profile/clemherm.bsky.social" target="_blank">🌐 Bluesky</a>
  </div>

  <div class="main-content">
    <h1>Clément Herman</h1>

    <h2>About me</h2>
    <p>
      I am a Ph.D. candidate in Economics at Princeton University. My research explores how institutional structures and group dynamics shape decision-making in information-rich environments, with a focus on political economy and behavioral economics.
    </p>

    <h2>Research</h2>

    <h3><a href="https://drive.google.com/file/d/1y5wnjRmn4bTxqYAMbl-4sAGgy0OrtrPL/view?usp=share_link" target="_blank">How Do Groups Search? An Experimental Study</a></h3>
    <em>Working Paper, 2025 · Submitted</em><br>
    <button onclick="toggleAbstract('abs1')">Abstract</button>
    <div class="abstract" id="abs1">
      <p>
        We study how group structure and preference alignment shape collective search behavior in sequential decision tasks.
        Groups perform better than individuals when preferences are aligned and stopping requires unanimity, but underperform in misaligned contexts. Our results disentangle behavioral and aggregation effects.
      </p>
    </div>

    <h3>Project Title 2</h3>
    <em>In preparation</em>

    <h3>Project Title 3</h3>
    <em>In preparation</em>

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
