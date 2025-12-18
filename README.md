<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Rhoda's First Build</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f4f7fb;
      margin: 0;
      padding: 20px;
      color: #333;
    }
    h1 {
      color: #2c3e50;
    }
    h2 {
      color: #34495e;
    }
    a {
      color: #1e88e5;
      text-decoration: none;
      font-weight: bold;
    }
    a:hover {
      text-decoration: underline;
    }
    .card {
      background: white;
      padding: 20px;
      border-radius: 12px;
      max-width: 700px;
      box-shadow: 0 10px 25px rgba(0,0,0,0.1);
    }
    button {
      padding: 10px 16px;
      border: none;
      border-radius: 8px;
      background: #1e88e5;
      color: white;
      cursor: pointer;
      margin-top: 10px;
    }
    button:hover {
      background: #1565c0;
    }
  </style>
</head>
<body>
  <div class="card">
  <h1>Welcome to My First Website 🌱</h1>  <p>
    Hi, my name is Rhoda. I am learning coding step by step and building my own path.
  </p>  <h2>My Inspirations</h2>
  <ul>
    <li>Discipline</li>
    <li>Consistency</li>
    <li>Curiosity</li>
  </ul>  <h2>Link I Built</h2>
  <p>
    <a href="https://www.instagram.com/vib.escake">Visit vib.escake</a>
  </p>  <h2>My Goals</h2>
  <p>
    I want to grow in academics, coding, and confidence — in my own way.
  </p>
  <button onclick="showMessage()">Click Me</button>
  <p id="message"></p>  <script>
    function showMessage() {
      document.getElementById('message').innerText = "You just interacted with your first website, Rhoda 🌱";
    }
  </script>  </div>
</body>
</html>
