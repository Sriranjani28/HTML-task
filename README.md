# HTML-task

# AIM:
  To create a Webpage with Internal Navigation.

# CODE:
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Internal Navigation Example</title>
  <style>
    html {
      scroll-behavior: smooth;
    }

    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f3e8ff;
    }

    nav {
      background-color: #7b2cbf; /* Deep violet */
      padding: 15px;
      position: sticky;
      top: 0;
    }

    nav a {
      color: white;
      margin-right: 20px;
      text-decoration: none;
      font-weight: bold;
    }

    section {
      padding: 50px;
      margin: 20px;
      border-radius: 10px;
      background-color: #e0bbff; /* Light violet */
    }

    h2 {
      color: #5a189a; /* Darker violet for headings */
    }
  </style>
</head>
<body>

  <!-- Navigation bar -->
  <nav>
    <a href="#home">Home</a>
    <a href="#about">About Us</a>
    <a href="#services">Services</a>
    <a href="#contact">Contact</a>
  </nav>

  <!-- Sections -->
  <div id="home">
    <section>
      <h2>Home</h2>
      <p>Welcome to FutureTech Solutions. We specialize in innovative technology services for businesses of all sizes.</p>
    </section>
  </div>

  <div id="about">
    <section>
      <h2>About Us</h2>
      <p>We are passionate about delivering quality software, AI solutions, and IT services to help businesses grow.</p>
    </section>
  </div>

  <div id="services">
    <section>
      <h2>Our Services</h2>
      <ul>
        <li>Web & App Development</li>
        <li>Artificial Intelligence</li>
        <li>Cloud Services</li>
        <li>Cybersecurity</li>
      </ul>
    </section>
  </div>

  <div id="contact">
    <section>
      <h2>Contact Us</h2>
      <p>Email: contact@futuretech.com<br>Phone: +91-98765-43210</p>
    </section>
  </div>

</body>
</html>
```
# OUTPUT:

![WhatsApp Image 2025-07-01 at 12 13 14_1b47b4ac](https://github.com/user-attachments/assets/0c045e63-a0a2-4d01-aea1-b9da1dee53ae)
