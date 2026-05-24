<!DOCTYPE html>
<html lang="en-GB">
<head>
  <meta charset="UTF-8">
  <title>Gallery | Jotham Jeremiah Okure</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <!-- Navigation menu -->
  <nav>
    <ul>
      <li><a href="index.html">Home</a></li>
      <li><a href="gallery.html">Gallery</a></li>
      <li><a href="about.html">About</a></li>
      <li><a href="contact.html">Contact</a></li>
    </ul>
  </nav>

  <h1>Gallery</h1>

  <!-- Gallery section for Papa -->
  <h2 id="papa">Papa (Father)</h2>
  <div class="gallery">
    <img src="images/papa1.jpg" alt="Jotham Jeremiah with father" onclick="openLightbox(this)">
    <!-- Repeat for more Papa photos if available -->
    <!-- <img src="images/papa2.jpg" alt="Jotham Jeremiah with father" onclick="openLightbox(this)"> -->
  </div>

  <!-- Gallery section for Jeremiah -->
  <h2 id="jeremiah">Jeremiah</h2>
  <div class="gallery">
    <img src="images/jeremiah.jpg" alt="Jeremiah Okure smiling" onclick="openLightbox(this)">
    <!-- Add more Jeremiah photos here -->
  </div>

  <!-- Gallery section for Mum & Jeremiah -->
  <h2 id="mum">Mum & Jeremiah</h2>
  <div class="gallery">
    <img src="images/mum_jeremiah.jpg" alt="Jeremiah Okure with mother" onclick="openLightbox(this)">
    <!-- Add more Mum & Jeremiah photos here -->
  </div>

  <!-- Lightbox modal (same as in index.html) -->
  <div id="lightbox" onclick="closeLightbox()">
    <span class="close">&times;</span>
    <img class="lightbox-content" id="lightbox-img">
    <div id="caption"></div>
  </div>

  <script src="script.js"></script>
</body>
</html>
