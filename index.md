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

  .project {
  margin-bottom: 40px;
}
</style>

<div class="container">

  <div class="sidebar">
    <img src="photo_clement.jpg" alt="Photo de Clément Herman">
    <a href="https://drive.google.com/file/d/1Gekom_rW1KhPX_Iw3T6jO6h6VYKndLcB/view?usp=share_link" target="_blank">📄 CV</a>
    <a href="mailto:cherman@princeton.edu">✉️ cherman@princeton.edu</a>
    <a href="https://bsky.app/profile/clemherm.bsky.social" target="_blank">🌐 Bluesky</a>
  </div>

  <div class="main-content">
    <h1>Clément Herman</h1>

    <h2>About me</h2>
    <p>
      I am a Ph.D. candidate in Economics at Princeton University. I am a microeconomist with research interests in Behavioral Economics, Experimental Economics, and Political Economy.
    </p>

    <h2>Research</h2>

<div class="project">
  <h3><a href="https://drive.google.com/file/d/1y5wnjRmn4bTxqYAMbl-4sAGgy0OrtrPL/view?usp=share_link" target="_blank">How Do Groups Search? An Experimental Study</a></h3>
  <em>Working Paper, 2025 · Submitted</em><br>
  <button onclick="toggleAbstract('abs1')">Abstract</button>
  <div class="abstract" id="abs1">
    <p>…abstract text…</p>
  </div>
</div>

<div class="project">
  <h3>Where to Search and When to Stop: A Lab Study</h3>
  <p><strong>With:</strong> Alessandro Lizzeri, Leeat Yariv</p>
  <em>In preparation</em>
</div>



<div class="project">
  <h3></h3>
  <p><strong>With:</strong> Alessandro Lizzeri, Leeat Yariv</p>
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
