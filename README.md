
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Sudeep Eco Solutions</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #4CAF50;
      color: white;
      padding: 1rem;
      text-align: center;
    }
    nav {
      background-color: #333;
      overflow: hidden;
    }
    nav a {
      float: left;
      color: white;
      padding: 14px 16px;
      text-decoration: none;
      display: block;
    }
    nav a:hover {
      background-color: #575757;
    }
    section {
      padding: 20px;
    }
    .contact-form input, .contact-form textarea {
      width: 100%;
      padding: 10px;
      margin: 6px 0;
      box-sizing: border-box;
    }
    .contact-form button {
      padding: 10px 20px;
      background-color: #4CAF50;
      color: white;
      border: none;
      cursor: pointer;
    }
    .contact-form button:hover {
      background-color: #45a049;
    }
    .info-box {
      background: #f0f0f0;
      padding: 10px;
      border-radius: 8px;
      margin-top: 20px;
    }
  </style>
</head>
<body>

<header>
  <h1>Welcome to Sudeep Eco Solutions</h1>
</header>

<nav>
  <a href="#home">Home</a>
  <a href="#about">About</a>
  <a href="#contact">Contact</a>
</nav>

<section id="home">
  <h2>Home</h2>
  <p>This is my plastic recycling startup website.</p>
  <p>We help people recycle plastic and earn rewards while saving the planet.</p>
</section>

<section id="about">
  <h2>About Us</h2>
  <p><strong>Sudeep Eco Solutions</strong> is based in <b>India</b>. We connect people who want to sell plastic waste with trusted recycling companies.</p>
  <p>We aim to reduce pollution and help citizens earn from recycling. Let's build a cleaner future together!</p>
</section>

<section id="contact">
  <h2>Contact Us</h2>
  <form class="contact-form" action="https://formsubmit.co/sudeepsudeep808080@gmail.com" method="POST">
    <input type="hidden" name="_captcha" value="false">
    <label for="name">Name</label>
    <input type="text" id="name" name="name" required placeholder="Your name">

    <label for="email">Email</label>
    <input type="email" id="email" name="email" required placeholder="Your email">

    <label for="message">Message</label>
    <textarea id="message" name="message" rows="5" required placeholder="Write your message here..."></textarea>

    <button type="submit">Send Message</button>
  </form>

  <div class="info-box">
    <p>📧 Email: <a href="mailto:sudeepsudeep808080@gmail.com">sudeepsudeep808080@gmail.com</a></p>
    <p>📞 Phone: <a href="tel:+919632763054">9632763054</a></p>
    <p>📍 Location: India</p>
  </div>
</section>

</body>
</html>
