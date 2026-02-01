# Lamar-website
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Lamar | Personal Website</title>

  <style>
    body {
      margin: 0;
      font-family: Arial, Helvetica, sans-serif;
      background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
      color: white;
      min-height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
    }

    .container {
      max-width: 700px;
      padding: 40px;
      background: rgba(255, 255, 255, 0.08);
      border-radius: 16px;
      backdrop-filter: blur(10px);
      box-shadow: 0 20px 40px rgba(0,0,0,0.3);
      text-align: center;
    }

    h1 {
      font-size: 2.5rem;
      margin-bottom: 10px;
    }

    h2 {
      font-weight: normal;
      opacity: 0.9;
      margin-bottom: 30px;
    }

    p {
      line-height: 1.7;
      font-size: 1.05rem;
      opacity: 0.95;
    }

    .buttons {
      margin-top: 30px;
    }

    a {
      display: inline-block;
      margin: 10px;
      padding: 12px 24px;
      border-radius: 30px;
      text-decoration: none;
      color: white;
      border: 1px solid rgba(255,255,255,0.5);
      transition: all 0.3s ease;
    }

    a:hover {
      background: white;
      color: #203a43;
    }

    footer {
      margin-top: 40px;
      font-size: 0.85rem;
      opacity: 0.7;
    }
  </style>
</head>
<body>

  <div class="container">
    <h1>Hi, Iâm Lamar</h1>
    <h2>Welcome to my space on the internet</h2>

    <p>
      This is my personal website.  
      A simple place where I share who I am, what Iâm building,
      and what Iâm interested in.
    </p>

    <p>
      I enjoy learning, creativity, and exploring ideas that sit
      between logic and imagination.
    </p>

    <div class="buttons">
      <a href="#">Contact Me</a>
      <a href="#">My Work</a>
    </div>

    <footer>
      Â© 2026 Lamar. All rights reserved.
    </footer>
  </div>

</body>
</html>
