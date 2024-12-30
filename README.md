# IBM-project
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Infinite Destination</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <!-- Hero Section -->
  <header class="hero-section">
    <div class="hero-overlay">
      <div class="content">
        <h1 class="fade-in">Start Your Journey Today</h1>
        <p class="fade-in">Explore the world's most breathtaking destinations. Your adventure begins now.</p>
        <button class="cta-button" id="ctaButton">Discover More</button>
      </div>
    </div>
  </header>

  <!-- Transparent Navbar -->
  <nav class="navbar">
    <div class="logo">Infinite Destination</div>
    <ul>
      <li><a href="#destinations">Destinations</a></li>
      <li><a href="#packages">Travel Packages</a></li>
      <li><a href="#about">About Us</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>

  <!-- Destinations Section -->
  <section id="destinations" class="destinations-section">
    <h2 class="section-title">Top Destinations</h2>
    <div class="destination-cards">
      <div class="destination-card">
        <img src="" alt="Paris" class="destination-image">
        <div class="destination-info">
          <h3>Paris</h3>
          <p>Explore the city of love, culture, and history.</p>
        </div>
      </div>
      <div class="destination-card">
        <img src="jezael-melgoza-layMbSJ3YOE-unsplash.jpg" alt="Tokyo" class="destination-image">
        <div class="destination-info">
          <h3>Tokyo</h3>
          <p>Immerse yourself in the vibrant culture of Japan's capital.</p>
        </div>
      </div>
      <div class="destination-card">
        <img src="leonard-cotte-R5scocnOOdM-unsplash.jpg" alt="Maldives" class="destination-image">
        <div class="destination-info">
          <h3>Maldives</h3>
          <p>Relax on the tropical paradise of white-sand beaches and clear blue waters.</p>
        </div>
      </div>
      <div class="destination-card">
        <img src="syd-sujuaan-AjtAJ-FK0Aw-unsplash.jpg" alt="New York" class="destination-image">
        <div class="destination-info">
          <h3>New York</h3>
          <p>Experience the energy and excitement of the Big Apple.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Travel Packages Section -->
  <section id="packages" class="packages-section">
    <h2 class="section-title">Our Travel Packages</h2>
    <div class="package-cards">
      <div class="package-card">
        <img src="michelle-woodson-howell-ed3K-b6XLnQ-unsplash.jpg" alt="Luxury Travel" class="package-image">
        <div class="package-info">
          <h3>Luxury Travel</h3>
          <p>Indulge in luxury accommodations and exclusive experiences.</p>
        </div>
      </div>
      <div class="package-card">
        <img src="vincentiu-solomon-R86bzJSneuw-unsplash.jpg" alt="Adventure Tours" class="package-image">
        <div class="package-info">
          <h3>Adventure Tours</h3>
          <p>Explore rugged landscapes and thrilling adventures.</p>
        </div>
      </div>
      <div class="package-card">
        <img src="nikola-tasic-Ju88Q5SRRzo-unsplash.jpg" alt="Honeymoon" class="package-image">
        <div class="package-info">
          <h3>Honeymoon Escapes</h3>
          <p>Spend your honeymoon in the most romantic destinations.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Booking Section -->
  <section id="booking" class="booking-section">
    <h2 class="section-title">Book Your Adventure</h2>
    <form action="#" class="booking-form">
      <label for="destination">Choose Destination</label>
      <select id="destination" name="destination">
        <option value="paris">Paris</option>
        <option value="tokyo">Tokyo</option>
        <option value="maldives">Maldives</option>
        <option value="newyork">New York</option>
      </select>

      <label for="travel-dates">Travel Dates</label>
      <input type="date" id="travel-dates" name="travel-dates">

      <label for="people">Number of People</label>
      <input type="number" id="people" name="people" min="1" value="1">

      <button type="submit" class="cta-button">Book Now</button>
    </form>
  </section>

  <footer class="footer">
    <p>© 2024 Infinite Destination. All Rights Reserved.</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>
