# https-anonymous-khabib.vercel.app
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>The Anonymous Khabib</title>
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@600&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Courier New', monospace;
      background: url('https://files.catbox.moe/lmo594.jpg') no-repeat center center fixed;
      background-size: cover;
      color: #00ff00;
    }

    .container {
      max-width: 600px;
      margin: 100px auto;
      background: rgba(0, 0, 0, 0.8);
      padding: 30px;
      border-radius: 15px;
      box-shadow: 0 0 10px #00ff00;
    }

    h1 {
      text-align: center;
      font-size: 30px;
      color: #ff00ff;
      text-shadow: 0 0 8px #00ffff;
      font-family: 'Orbitron', sans-serif;
    }

    label {
      display: block;
      margin-top: 15px;
    }

    input, textarea {
      width: 100%;
      padding: 10px;
      margin-top: 5px;
      background: #111;
      color: #0f0;
      border: 1px solid #0f0;
      border-radius: 5px;
    }

    .btn {
      display: block;
      width: 100%;
      margin-top: 20px;
      padding: 10px;
      background: #00ff00;
      color: black;
      font-weight: bold;
      border: none;
      border-radius: 5px;
      text-align: center;
      text-decoration: none;
      font-family: 'Orbitron', sans-serif;
    }

    footer {
      text-align: center;
      margin-top: 50px;
      color: #ccc;
      font-size: 18px;
      font-family: 'Orbitron', sans-serif;
      text-shadow: 0 0 8px #0ff;
    }

    .email-link {
      font-size: 22px;
      color: #00ffff;
      font-weight: bold;
      text-decoration: none;
    }

    .footer-note {
      display: block;
      font-size: 26px;
      margin-top: 10px;
      color: #ff00ff;
      text-shadow: 0 0 10px #00ff00;
      font-weight: bold;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>The Anonymous Khabib</h1>
    <h2><form action="https://wa.me/254748950572" target="_blank"></h2>
      <label for="name">Your Name</label>
      <input type="text" id="name" placeholder="Enter your name" required>

      <label for="service">Service Interested In</label>
      <input type="text" id="service" placeholder="e.g., Website, App, etc." required>

      <label for="message">Tell us your issues or suggestions</label>
      <textarea id="message" rows="4" placeholder="Your message..."></textarea>

      <button class="btn" type="submit">Send via WhatsApp</button>
    </form>
  </div>

  <footer>
    Contact: <h2><a href="mailto:merabjoy@gmail.com" class="email-link">merabjoy@gmail.com</a></h2>
    <h3><span class="footer-note">Mera-B SYSTEM</span></h3>
  </footer>
</body>
</html>

