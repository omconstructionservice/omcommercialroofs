<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Free Quote | O&M Commercial Roofing</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #ffffff;
      color: #000000;
    }
    header, footer {
      background-color: #c40000;
      color: white;
      text-align: center;
      padding: 20px;
    }
    nav {
      background-color: #c40000;
      padding: 10px 0;
      text-align: center;
    }
    nav a {
      color: white;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
    }
    .content {
      padding: 40px;
      max-width: 600px;
      margin: 0 auto;
    }
    .content h1 {
      color: #c40000;
      text-align: center;
    }
    form label {
      display: block;
      margin-bottom: 10px;
      font-weight: bold;
    }
    form input, form textarea {
      width: 100%;
      padding: 10px;
      margin-bottom: 20px;
      border: 1px solid #ccc;
      border-radius: 4px;
    }
    form button {
      background-color: #c40000;
      color: white;
      padding: 15px 30px;
      border: none;
      border-radius: 4px;
      cursor: pointer;
      font-size: 16px;
    }
  </style>
</head>
<body>
  <header>
    <h1>O&M Commercial Roofing</h1>
  </header>

  <nav>
    <a href="index.html">Home</a>
    <a href="about.html">About</a>
    <a href="services.html">Services</a>
    <a href="projects.html">Projects</a>
    <a href="quote.html">Free Quote</a>
    <a href="contact.html">Contact</a>
  </nav>

  <section class="content">
    <h1>Request a Free Quote</h1>
    <form action="https://formspree.io/f/yourformid" method="POST">
      <label for="name">Name</label>
      <input type="text" id="name" name="name" required>

      <label for="email">Email</label>
      <input type="email" id="email" name="email" required>

      <label for="phone">Phone</label>
      <input type="tel" id="phone" name="phone" required>

      <label for="message">Tell us about your project</label>
      <textarea id="message" name="message" rows="5" required></textarea>

      <input type="hidden" name="_subject" value="New Quote Request from O&M Website">
      <input type="hidden" name="_next" value="https://omcommercialroofs.com/thank-you.html">
      <button type="submit">Submit</button>
    </form>
  </section>

  <footer>
    <p>Contact us at omconstructionservice@gmail.com | 713-234-7518</p>
    <p>Serving Houston and surrounding areas</p>
  </footer>
</body>
</html>

