<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Clarity Concierge</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Inter', sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f8f8f8;
      color: #333;
    }
    header {
      background-color: #ffffff;
      padding: 1.5rem 1rem;
      text-align: center;
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.05);
    }
    header img {
      height: 50px;
      margin-bottom: 0.5rem;
    }
    header h1 {
      margin: 0.2rem 0;
      color: #1a202c;
    }
    nav {
      margin-top: 1rem;
    }
    nav a {
      margin: 0 0.75rem;
      text-decoration: none;
      color: #007b7f;
      font-weight: 600;
    }
    section {
      max-width: 800px;
      margin: 2rem auto;
      padding: 1rem;
      background-color: #ffffff;
      border-radius: 8px;
      box-shadow: 0 2px 10px rgba(0,0,0,0.05);
    }
    h2 {
      color: #007b7f;
    }
    form {
      display: flex;
      flex-direction: column;
    }
    form input, form textarea {
      margin-bottom: 1rem;
      padding: 0.75rem;
      border: 1px solid #ccc;
      border-radius: 4px;
      font-size: 1rem;
    }
    form button {
      background-color: #007b7f;
      color: white;
      padding: 0.75rem;
      border: none;
      border-radius: 4px;
      font-size: 1rem;
      cursor: pointer;
    }
    form button:hover {
      background-color: #005f61;
    }
    footer {
      text-align: center;
      padding: 2rem;
      font-size: 0.9rem;
      color: #666;
    }
    @media (max-width: 600px) {
      header, nav, section {
        padding: 1rem;
      }
      nav a {
        display: block;
        margin: 0.5rem 0;
      }
    }
  </style>
</head>
<body>
  <header>
    <img src="https://via.placeholder.com/150x50?text=Clarity+Logo" alt="Clarity Concierge Logo" />
    <h1>Clarity Concierge</h1>
    <p>Reliable. Personalized. Discreet Lifestyle Management.</p>
    <nav>
      <a href="#about">About</a>
      <a href="#services">Services</a>
      <a href="#pricing">Pricing</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section id="about">
    <h2>About Us</h2>
    <p>At Clarity Concierge, we simplify and enhance the lives of busy professionals, families, and businesses by offering tailored concierge services. Whether it’s managing errands or planning events, we’re here to help you live with ease and focus on what matters most.</p>
  </section>

  <section id="services">
    <h2>Our Services</h2>
    <ul>
      <li>Personal errands (shopping, deliveries)</li>
      <li>Appointment scheduling</li>
      <li>Travel planning and booking</li>
      <li>Event planning and coordination</li>
      <li>Home management services</li>
      <li>Corporate concierge support</li>
    </ul>
  </section>

  <section id="pricing">
    <h2>Plans & Pricing</h2>
    <p>We offer flexible packages to suit your needs:</p>
    <ul>
      <li>Basic Plan: $50/month - up to 5 tasks</li>
      <li>Premium Plan: $150/month - unlimited support</li>
      <li>One-time tasks: from $10/task</li>
    </ul>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <form action="mailto:info@clarityconcierge.com" method="post" enctype="text/plain">
      <input type="text" name="name" placeholder="Your Name" required />
      <input type="email" name="email" placeholder="Your Email" required />
      <textarea name="message" rows="5" placeholder="Your Message" required></textarea>
      <button type="submit">Send Message</button>
    </form>
    <p>Or reach out via WhatsApp or Calendly.</p>
  </section>

  <footer>
    <p>&copy; 2025 Clarity Concierge. All rights reserved.</p>
  </footer>
</body>
</html>
