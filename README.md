# Chinnistudio.
Welcome to Chinni Digital Studio Wedpage
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Chinni Studio</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: Arial, sans-serif;
      background-color: #f0f8ff;
      color: #003366;
    }
    header {
      background-color: #003366;
      color: white;
      padding: 1rem;
      text-align: center;
    }
    .slideshow {
      max-width: 100%;
      height: 300px;
      overflow: hidden;
      position: relative;
    }
    .slides {
      display: flex;
      width: 300%;
      animation: slide 9s infinite;
    }
    .slides div {
      position: relative;
      width: 100%;
    }
    .slides img {
      width: 100%;
      height: 300px;
      object-fit: cover;
    }
    .slides h2 {
      position: absolute;
      bottom: 20px;
      left: 20px;
      color: white;
      background: rgba(0, 0, 0, 0.5);
      padding: 10px;
      border-radius: 6px;
    }
    @keyframes slide {
      0% { transform: translateX(0); }
      33% { transform: translateX(-100%); }
      66% { transform: translateX(-200%); }
      100% { transform: translateX(0); }
    }
    .info {
      padding: 1.5rem;
      text-align: center;
    }
    .info img {
      width: 200px;
      height: 200px;
      border-radius: 50%;
      border: 4px solid #003366;
      object-fit: cover;
      margin-bottom: 1rem;
    }
    .services {
      background-color: #e0f0ff;
      padding: 2rem;
      text-align: center;
    }
    .services h2 {
      margin-bottom: 1rem;
    }
    .services ul {
      list-style: none;
      padding: 0;
    }
    .services ul li {
      margin: 0.5rem 0;
      font-size: 1.1rem;
    }
    .map {
      padding: 2rem;
      text-align: center;
    }
    .map iframe {
      border-radius: 12px;
    }
    .gallery {
      text-align: center;
      padding: 2rem;
    }
    .gallery img {
      max-width: 300px;
      margin: 10px;
      border-radius: 10px;
    }
    footer {
      background-color: #003366;
      color: white;
      padding: 1rem;
      text-align: center;
    }
    a {
      color: #ffcc00;
      text-decoration: none;
    }
  </style>
</head>
<body>
  <header>
    <h1>Chinni Studio</h1>
  </header>

  <!-- Slideshow with Text -->
  <div class="slideshow">
    <div class="slides">
      <div>
        <img src="https://via.placeholder.com/1200x300?text=Slide+1" alt="Slide 1">
        <h2>Welcome to Chinni Studio</h2>
      </div>
      <div>
        <img src="https://via.placeholder.com/1200x300?text=Slide+2" alt="Slide 2">
        <h2>We Capture Your Memories</h2>
      </div>
      <div>
        <img src="https://via.placeholder.com/1200x300?text=Slide+3" alt="Slide 3">
        <h2>One Stop for Digital Services</h2>
      </div>
    </div>
  </div>

  <div class="info">
    <img src="owner.jpg" alt="Studio Owner Photo">
    <p><strong>Phone:</strong> 9440150947, 9705754907, 9121174999</p>
    <p><strong>Email:</strong> chinni244740@gmail.com</p>
    <p><a href="https://youtube.com/@126chinnidigitalstudio?feature=shared" target="_blank">Visit Our YouTube Channel</a></p>
  </div>

  <div class="services">
    <h2>Our Services</h2>
    <ul>
      <li>Aadhaar Card Download</li>
      <li>PAN Card Download</li>
      <li>Photo Shoots</li>
      <li>Wedding Shoots</li>
      <li>Album Designing</li>
      <li>Xerox Services</li>
    </ul>
  </div>

  <div class="gallery">
    <h2>Studio Highlights</h2>
    <img src="https://images.unsplash.com/photo-1553062407-98eeb64c6a62?auto=format&fit=crop&w=800&q=80" alt="AI Studio Image 1">
    <img src="https://images.unsplash.com/photo-1518770660439-4636190af475?auto=format&fit=crop&w=800&q=80" alt="AI Studio Image 2">
    <img src="https://images.unsplash.com/photo-1504198453319-5ce911bafcde?auto=format&fit=crop&w=800&q=80" alt="AI Studio Image 3">
  </div>

  <div class="map">
    <h2>Find Us</h2>
    <iframe 
      src="https://www.google.com/maps?q=8qf8P8HGj8F8wbXu7&output=embed" 
      width="90%" 
      height="300" 
      style="border:0;" 
      allowfullscreen="" 
      loading="lazy">
    </iframe>
  </div>

  <footer>
    &copy; 2025 Chinni Studio. All Rights Reserved.
  </footer>
</body>
</html>
