# Online-Blood-donation-system-
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Online Blood Donation System</title>
  <style>
    /* Basic Reset */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
      color: #333;
      background: #f4f4f4;
    }

    /* Header Styling */
    header {
      background: #b71c1c;
      color: #fff;
      padding: 20px;
      text-align: center;
    }

    /* Navigation Menu */
    nav {
      background: #d32f2f;
    }

    nav ul {
      list-style: none;
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
    }

    nav ul li {
      margin: 10px;
    }

    nav ul li a {
      color: #fff;
      text-decoration: none;
      padding: 10px 15px;
      display: block;
      transition: background 0.3s ease;
    }

    nav ul li a:hover {
      background: #c62828;
    }

    /* Main Container */
    .container {
      max-width: 1200px;
      margin: auto;
      padding: 20px;
    }

    /* Section Styling */
    section {
      margin-bottom: 20px;
      padding: 20px;
      background: #ffffff;
      border-radius: 5px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
    }

    section h2 {
      margin-bottom: 10px;
      color: #b71c1c;
    }

    /* Footer Styling */
    footer {
      background: #b71c1c;
      color: #fff;
      text-align: center;
      padding: 15px;
    }

    /* Responsive Design */
    @media (max-width: 768px) {
      nav ul {
        flex-direction: column;
        align-items: center;
      }
    }
  </style>
</head>
<body>
  <!-- Header Section -->
  <header>
    <h1>Online Blood Donation System</h1>
    <p>Donate Blood, Save Lives!</p>
  </header>

  <!-- Navigation Menu -->
  <nav>
    <ul>
      <li><a href="#home">Home</a></li>
      <li><a href="#about">About</a></li>
      <li><a href="#donor">Donor Registration</a></li>
      <li><a href="#services">Services</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>

  <!-- Main Content -->
  <div class="container">
    <!-- Home Section -->
    <section id="home">
      <h2>Home</h2>
      <p>Welcome to the **Online Blood Donation System**. Donate blood and save lives!</p>
    </section>

    <!-- About Section -->
    <section id="about">
      <h2>About Us</h2>
      <p>We aim to connect blood donors with those in need. Join us and make a difference in someone's life.</p>
    </section>

    <!-- Donor Registration Section -->
    <section id="donor">
      <h2>Donor Registration</h2>
      <p>Become a donor and help save lives.</p>
      <button onclick="alert('Registration Page Coming Soon!')">Register Now</button>
    </section>

    <!-- Services Section -->
    <section id="services">
      <h2>Our Services</h2>
      <p>We provide blood donation services, donor management, and emergency blood request systems.</p>
    </section>

    <!-- Contact Section -->
    <section id="contact">
      <h2>Contact Us</h2>
      <p>Email: blooddonation@support.com</p>
      <p>Phone: +123 456 7890</p>
    </section>
  </div>

  <!-- Footer Section -->
  <footer>
    <p>&copy; 2025 Online Blood Donation System. All rights reserved.</p>
  </footer>
</body>
</html>
