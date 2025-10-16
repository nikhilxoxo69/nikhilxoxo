# nikhilxoxo
Nikhilxoxo is a live photography portfolio showcasing the world through my lens. From raw street moments to breathtaking landscapes, this space captures real-time emotion, light, and perspective — all set against a sleek black backdrop that lets every image tell its own story.
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Nikhilxoxo | Live Photography</title>
  <style>
    body {
      background-color: black;
      color: white;
      font-family: 'Poppins', sans-serif;
      margin: 0;
      padding: 0;
      text-align: center;
    }

    header {
      padding: 40px 20px;
      font-size: 2.5rem;
      font-weight: 600;
      letter-spacing: 2px;
      text-transform: uppercase;
    }

    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 15px;
      padding: 20px;
    }

    .gallery img {
      width: 100%;
      height: 300px;
      object-fit: cover;
      border-radius: 10px;
      transition: transform 0.3s ease;
    }

    .gallery img:hover {
      transform: scale(1.05);
    }

    footer {
      padding: 30px;
      font-size: 0.9rem;
      color: gray;
    }
  </style>
</head>
<body>
  <header>Nikhilxoxo Photography</header>

  <div class="gallery">
    <img src="https://source.unsplash.com/random/800x600?nature" alt="Nature photo">
    <img src="https://source.unsplash.com/random/800x601?city" alt="City photo">
    <img src="https://source.unsplash.com/random/800x602?portrait" alt="Portrait photo">
    <img src="https://source.unsplash.com/random/800x603?travel" alt="Travel photo">
    <img src="https://source.unsplash.com/random/800x604?night" alt="Night photo">
    <img src="https://source.unsplash.com/random/800x605?street" alt="Street photo">
  </div>

  <footer>
    © 2025 Nikhilxoxo | All rights reserved.
  </footer>
</body>
</html>
