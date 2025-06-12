Chinni digital studio 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Chinni Studio</title>
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }
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
      background: rgba(0,0,0,0.5);
      padding: 10px;
      border-radius: 8px;
    }
    @keyframes slide {
      0% { transform: translateX(0); }
      33% { transform: translateX(-100%); }
      66% { transform: translateX(-200%); }
      100% { transform: translateX(0); }
    }
    .info {
      padding: 2rem;
      text-align: center;
    }
    .chat-button {
      display: inline-block;
      margin-top: 1rem;
      background-color: #25D366;
      color: white;
      padding: 10px 20px;
      text-decoration: none;
      font-weight: bold;
      border-radius: 30px;
      box-shadow: 0 4px 6px rgba(0,0,0,0.1);
      transition: background-color 0.3s ease;
    }
    .chat-button:hover {
      background-color: #1ebc59;
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
    .gallery {
      text-align: center;
      padding: 2rem;
    }
    .gallery img {
      max-width: 300px;
      margin: 10px;
      border-radius: 10px;
    }
    .map {
      padding: 2rem;
      text-align: center;
    }
    .map iframe {
      width: 90%;
      height: 300px;
      border: 0;
      border-radius: 12px;
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

  <!-- Slideshow -->
  <div class="slideshow">
    <div class="slides">
      <div>
        <img src="https://via.placeholder.com/1200x300?text=Chinni+Studio" alt="Slide 1">
        <h2>Welcome to Chinni Studio</h2>
      </div>
      <div>
        <img src="https://via.placeholder.com/1200x300?text=Capturing+Memories" alt="Slide 2">
        <h2>Capturing Beautiful Memories</h2>
      </div>
      <div>
        <img src="https://via.placeholder.com/1200x300?text=Digital+Solutions" alt="Slide 3">
        <h2>Complete Digital Solutions</h2>
      </div>
    </div>
  </div>

  <!-- Info Section -->
  <div class="info">
    <p><strong>Phone:</strong> 9440150947, 9705754907, 9121174999</p>
    <p><strong>Email:</strong> chinni244740@gmail.com</p>
    <p><a href="https://youtube.com/@126chinnidigitalstudio?feature=shared" target="_blank">🎥 Visit Our YouTube Channel</a></p>
    <p><a href="https://drive.google.com/drive/folders/1Pbt73J2oPudANCZiuCqXs__RZ0pGUqeF" target="_blank">📁 Access Our Google Drive</a></p>
    <p><a href="https://wa.me/919440150947" target="_blank" class="chat-button">💬 Chat with Us on WhatsApp</a></p>
  </div>

  <!-- Services -->
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

  <!-- Gallery -->
  <div class="gallery">
    <h2>Photography Showcase</h2>
    <img src="https://oaidalleapiprodscus.blob.core.windows.net/private/org-eZkFWV8PrqQWaIhziCM1jRTM/user-0NwGrzccM8hrfp3K8z5MuKug/img-yUq4g0kFIfscvKmhbcNOku9o.png?st=2024-06-12T12%3A00%3A00Z&se=2025-06-12T12%3A00%3A00Z&sp=r&sv=2021-08-06&sr=b&sig=wJ8twA2Z%2FD2SmnVmM9%2FqzWnILmH41aVO9rZBg%2Bv7agM%3D" alt="Photography AI Image">
  </div>

  <!-- Map Section -->
  <div class="map">
    <h2>Visit Us</h2>
    <iframe src="https://www.google.com/maps?q=Eluru&output=embed"></iframe>
  </div>

  <footer>
    &copy; 2025 Chinni Studio. All Rights Reserved.
  </footer>
</body>
</html>
