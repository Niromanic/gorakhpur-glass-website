# gorakhpur-glass-website<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Get a Quote - Gorakhpur Glass and Arts</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background-color: #f4f4f4;
    }
    header {
      background-color: #003b46;
      color: white;
      text-align: center;
      padding: 1rem;
    }
    nav {
      background: #07575b;
      text-align: center;
      padding: 0.5rem;
    }
    nav a {
      color: white;
      margin: 0 1rem;
      text-decoration: none;
    }
    main {
      max-width: 800px;
      margin: 2rem auto;
      background: white;
      padding: 2rem;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    label {
      display: block;
      margin-top: 1rem;
      font-weight: bold;
    }
    input, select, textarea {
      width: 100%;
      padding: 0.5rem;
      margin-top: 0.5rem;
      border: 1px solid #ccc;
      border-radius: 4px;
    }
    button {
      margin-top: 1.5rem;
      padding: 0.75rem 1.5rem;
      background-color: #003b46;
      color: white;
      border: none;
      border-radius: 4px;
      cursor: pointer;
    }
    button:hover {
      background-color: #07575b;
    }
    footer {
      background: #003b46;
      color: white;
      text-align: center;
      padding: 1rem;
      margin-top: 2rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>Gorakhpur Glass and Arts</h1>
    <p>Request a Custom Quote</p>
  </header>

  <nav>
    <a href="index.html">Home</a>
    <a href="about.html">About Us</a>
    <a href="services.html">Services</a>
    <a href="contact.html">Contact</a>
  </nav>

  <main>
    <h2>Get a Quote</h2>
    <form action="#" method="post" enctype="multipart/form-data">
      <label for="name">Full Name</label>
      <input type="text" id="name" name="name" required>

      <label for="email">Email Address</label>
      <input type="email" id="email" name="email" required>

      <label for="phone">Phone Number</label>
      <input type="tel" id="phone" name="phone" required>

      <label for="service">Select Service</label>
      <select id="service" name="service" required>
        <option value="">-- Choose a service --</option>
        <option value="float-glass">Float Glass</option>
        <option value="acid-work">Acid Work</option>
        <option value="glass-designing">Glass Designing</option>
        <option value="mirror-work">Mirror Work</option>
        <option value="custom">Custom Design</option>
      </select>

      <label for="message">Describe Your Requirements</label>
      <textarea id="message" name="message" rows="5" required></textarea>

      <label for="file">Upload a Design or Reference (optional)</label>
      <input type="file" id="file" name="file">

      <button type="submit">Submit Request</button>
    </form>
  </main>

  <footer>
    <p>&copy; 2025 Gorakhpur Glass and Arts. All rights reserved.</p>
  </footer>
</body>
</html>
