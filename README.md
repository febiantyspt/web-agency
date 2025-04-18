<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Creative Design Agency</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }

    header {
      padding: 20px;
      font-size: 24px;
      font-weight: bold;
    }

    .orange { color: orange; }
    .dot { color: orange; }
    .gray { color: gray; }

    .hero {
      padding: 20px;
    }

    .hero h2 {
      font-size: 36px;
    }

    .highlight {
      color: blueviolet;
    }

    .features {
      display: flex;
      justify-content: center;
      gap: 40px;
      padding: 40px;
      flex-wrap: wrap;
    }

    .feature {
      display: flex;
      flex-direction: row;
      align-items: flex-start;
      width: 600px;
      gap: 20px;
    }

    .feature img {
      width: 250px;
      height: auto;
    }

    footer {
      text-align: center;
      padding: 20px;
      background-color: #f0f0f0;
    }

    footer a {
      text-decoration: none;
      color: salmon;
      font-weight: bold;
    }
  </style>
</head>
<body>

  <header>
    <span class="orange">dev</span><span class="dot">.</span><span class="gray">com</span>
  </header>

  <section class="hero">
    <h2>We are a <span class="highlight">Creative</span> Design Agency</h2>
  </section>

  <section class="features">
    <div class="feature">
      <img src="c:\Users\ideap\Downloads\beauty.jpeg" alt="Beauty">
      <div>
        <h3>Beauty</h3>
        <p>We strive to create the most beautiful websites for all your needs. Working closely with you to design and develop an amazing website for your business.</p>
      </div>
    </div>

    <div class="feature">
      <img src="c:\Users\ideap\Downloads\construction.jpeg" alt="Construction">
      <div>
        <h3>Construction</h3>
        <p>Built by our team of professional developers, we ensure the most rigorous and modern websites. Built from scratch using HTML and CSS. Only the best for you.</p>
      </div>
    </div>
  </section>

  <footer>
    <a href="#">Create. Develop. Design.</a>
  </footer>

</body>
</html>
