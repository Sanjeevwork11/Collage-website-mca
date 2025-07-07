<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>My College</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      scroll-behavior: smooth;
    }

    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
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

    nav ul {
      list-style: none;
      display: flex;
    }

    nav ul li {
      margin-left: 20px;
    }

    nav ul li a {
      color: white;
      text-decoration: none;
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
    }

    .gallery img {
      width: 200px;
      height: auto;
      border-radius: 8px;
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
      <h1>My College</h1>
      <nav>
        <ul>
          <li><a href="#home">Home</a></li>
          <li><a href="#about">About</a></li>
          <li><a href="#courses">Courses</a></li>
          <li><a href="#gallery">Gallery</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <section id="home">
    <h2>Welcome to My College</h2>
    <p>Your future starts here!</p>
  </section>

  <section id="about">
    <h2>About Us</h2>
    <p>My College is a premier institution offering quality education for over 25 years.</p>
  </section>

  <section id="courses">
    <h2>Our Courses</h2>
    <ul>
      <li>Bachelor of Computer Applications (BCA)</li>
      <li>Bachelor of Business Administration (BBA)</li>
      <li>Bachelor of Commerce (B.Com)</li>
    </ul>
  </section>

  <section id="gallery">
    <h2>Gallery</h2>
    <div class="gallery">
      <img src="https://via.placeholder.com/200" alt="College 1" />
      <img src="https://via.placeholder.com/200" alt="College 2" />
      <img src="https://via.placeholder.com/200" alt="College 3" />
    </div>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <p>Email: info@mycollege.com</p>
    <p>Phone: +91 12345 67890</p>
  </section>

  <footer>
    <p>© 2025 My College. All rights reserved.</p>
  </footer>
</body>
</html>
