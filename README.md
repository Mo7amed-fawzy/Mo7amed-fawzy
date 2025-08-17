<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Skills Portfolio</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css" rel="stylesheet">
  <style>
    body {
      background: #121212;
      color: #fff;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }
    .section-title {
      font-size: 2rem;
      font-weight: bold;
      margin-bottom: 20px;
      text-transform: uppercase;
      color: #f39c12;
    }
    .card {
      background: #1e1e1e;
      border: none;
      border-radius: 15px;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }
    .card:hover {
      transform: translateY(-10px);
      box-shadow: 0 10px 25px rgba(243, 156, 18, 0.4);
    }
    .icon {
      font-size: 2.5rem;
      color: #f39c12;
      margin-bottom: 10px;
    }
    .contact-icons a {
      font-size: 2rem;
      margin: 0 15px;
      color: #f39c12;
      transition: color 0.3s ease;
    }
    .contact-icons a:hover {
      color: #fff;
    }
  </style>
</head>
<body>

  <div class="container py-5">

    <!-- Frontend Section -->
    <h2 class="section-title">Frontend</h2>
    <div class="row g-4">
      <div class="col-md-3 text-center">
        <div class="card p-3">
          <i class="fab fa-html5 icon"></i>
          <h5>HTML5</h5>
        </div>
      </div>
      <div class="col-md-3 text-center">
        <div class="card p-3">
          <i class="fab fa-css3-alt icon"></i>
          <h5>CSS3</h5>
        </div>
      </div>
      <div class="col-md-3 text-center">
        <div class="card p-3">
          <i class="fab fa-js icon"></i>
          <h5>JavaScript</h5>
        </div>
      </div>
      <div class="col-md-3 text-center">
        <div class="card p-3">
          <i class="fab fa-bootstrap icon"></i>
          <h5>Bootstrap</h5>
        </div>
      </div>
    </div>

    <!-- Backend Section -->
    <h2 class="section-title mt-5">Backend</h2>
    <div class="row g-4">
      <div class="col-md-3 text-center">
        <div class="card p-3">
          <i class="fab fa-node-js icon"></i>
          <h5>Node.js</h5>
        </div>
      </div>
      <div class="col-md-3 text-center">
        <div class="card p-3">
          <i class="fa-solid fa-server icon"></i>
          <h5>Express.js</h5>
        </div>
      </div>
      <div class="col-md-3 text-center">
        <div class="card p-3">
          <i class="fa-solid fa-rotate-right icon"></i>
          <h5>Nodemon</h5>
        </div>
      </div>
      <div class="col-md-3 text-center">
        <div class="card p-3">
          <i class="fas fa-database icon"></i>
          <h5>MongoDB</h5>
        </div>
      </div>
      <div class="col-md-3 text-center">
        <div class="card p-3">
          <i class="fab fa-google icon"></i>
          <h5>Firebase</h5>
        </div>
      </div>
      <div class="col-md-3 text-center">
        <div class="card p-3">
          <i class="fas fa-cloud icon"></i>
          <h5>Supabase</h5>
        </div>
      </div>
    </div>

    <!-- Flutter Section -->
    <h2 class="section-title mt-5">Flutter</h2>
    <div class="row g-4">
      <div class="col-md-3 text-center">
        <div class="card p-3">
          <i class="fab fa-dart icon"></i>
          <h5>Dart</h5>
        </div>
      </div>
      <div class="col-md-3 text-center">
        <div class="card p-3">
          <i class="fa-brands fa-android icon"></i>
          <h5>Flutter</h5>
        </div>
      </div>
      <div class="col-md-3 text-center">
        <div class="card p-3">
          <i class="fas fa-plug icon"></i>
          <h5>API</h5>
        </div>
      </div>
      <div class="col-md-3 text-center">
        <div class="card p-3">
          <i class="fas fa-layer-group icon"></i>
          <h5>State Management</h5>
        </div>
      </div>
      <div class="col-md-3 text-center">
        <div class="card p-3">
          <i class="fas fa-mobile-alt icon"></i>
          <h5>Responsive UI</h5>
        </div>
      </div>
      <div class="col-md-3 text-center">
        <div class="card p-3">
          <i class="fas fa-database icon"></i>
          <h5>Local Storage</h5>
        </div>
      </div>
      <div class="col-md-3 text-center">
        <div class="card p-3">
          <i class="fas fa-archway icon"></i>
          <h5>Clean Arch</h5>
        </div>
      </div>
      <div class="col-md-3 text-center">
        <div class="card p-3">
          <i class="fas fa-project-diagram icon"></i>
          <h5>MVVM</h5>
        </div>
      </div>
    </div>

    <!-- Tools Section -->
    <h2 class="section-title mt-5">Tools</h2>
    <div class="row g-4">
      <div class="col-md-3 text-center">
        <div class="card p-3">
          <i class="fab fa-github icon"></i>
          <h5>GitHub</h5>
        </div>
      </div>
      <div class="col-md-3 text-center">
        <div class="card p-3">
          <i class="fab fa-figma icon"></i>
          <h5>Figma</h5>
        </div>
      </div>
      <div class="col-md-3 text-center">
        <div class="card p-3">
          <i class="fab fa-xing icon"></i>
          <h5>Adobe XD</h5>
        </div>
      </div>
    </div>

    <!-- Contact Section -->
    <h2 class="section-title mt-5">Contact With Me</h2>
    <div class="contact-icons text-center">
      <a href="https://wa.me/201234567890" target="_blank"><i class="fab fa-whatsapp"></i></a>
      <a href="https://facebook.com/yourusername" target="_blank"><i class="fab fa-facebook"></i></a>
      <a href="https://discord.gg/yourserver" target="_blank"><i class="fab fa-discord"></i></a>
    </div>

  </div>
</body>
</html>
