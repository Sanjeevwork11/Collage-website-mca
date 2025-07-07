<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Image Enhanced Webpage</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
      margin: 0;
      padding: 0;
    }

    header {
      background: #333;
      color: #fff;
      padding: 20px 0;
      position: sticky;
      top: 0;
      z-index: 1000;
    }

    .container {
      width: 90%;
      margin: auto;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    .logo img {
      height: 50px;
    }

    nav ul {
      list-style: none;
      display: flex;
      padding: 0;
      margin: 0;
    }

    nav ul li {
      margin-left: 20px;
    }

    nav ul li a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }

    .hero {
      background: url('https://via.placeholder.com/1200x400?text=Welcome+Banner') no-repeat center center/cover;
      height: 400px;
      display: flex;
      justify-content: center;
      align-items: center;
      color: white;
      text-align: center;
      font-size: 2.5rem;
      font-weight: bold;
    }

    section {
      padding: 60px 20px;
      background: #f4f4f4;
      border-bottom: 1px solid #ccc;
    }

    section:nth-child(even) {
      background: #eaeaea;
    }

    .gallery {
      display: flex;
      gap: 20px;
      flex-wrap: wrap;
      justify-content: center;
    }

    .gallery-item {
      position: relative;
      width: 200px;
    }

    .gallery img {
      width: 100%;
      height: auto;
      border-radius: 8px;
      transition: transform 0.3s ease;
    }

    .gallery img:hover {
      transform: scale(1.05);
    }

    .gallery-item span {
      display: block;
      text-align: center;
      margin-top: 8px;
      font-weight: bold;
    }

    footer {
      background: #333;
      color: #fff;
      text-align: center;
      padding: 20px;
    }

    h2 {
      margin-bottom: 10px;
    }

    ul {
      margin-left: 20px;
    }
  </style>
</head>
<body>

  <header>
    <div class="container">
      <div class="logo">
        <img src="https://via.placeholder.com/100x50?text=Logo" alt="Logo">
      </div>
      <nav>
        <ul>
          <li><a href="#">Home</a></li>
          <li><a href="#">Gallery</a></li>
          <li><a href="#">About</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <div class="hero">
    Welcome to Our Website!
  </div>

  <section>
    <h2>Gallery</h2>
    <div class="gallery">
      <div class="gallery-item">
        <img src="https://via.placeholder.com/200x150?text=Nature" alt="Nature">
        <span>Nature</span>
      </div>
      <div class="gallery-item">
        <img src="https://via.placeholder.com/200x150?text=City" alt="City">
        <span>City</span>
      </div>
      <div class="gallery-item">
        <img src="https://via.placeholder.com/200x150?text=Adventure" alt="Adventure">
        <span>Adventure</span>
      </div>
      <div class="gallery-item">
        <img src="https://via.placeholder.com/200x150?text=Wildlife" alt="Wildlife">
        <span>Wildlife</span>
      </div>
    </div>
  </section>

  <footer>
    &copy; 2025 Your Website. All rights reserved.
  </footer>

</body>
</html>
