<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Beautiful Website</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;500;700&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: "Roboto", sans-serif;
      margin: 0;
      padding: 0;
      background-color: #ffffff;
    }
    
    header {
      height: 100px;
      background-color: #000000;
      color: #ffffff;
      text-align: center;
    }
    
    nav {
      display: flex;
      justify-content: space-around;
      margin: 20px 0;
    }
    
    nav a {
      color: #ffffff;
      font-size: 20px;
      text-decoration: none;
    }
    
    main {
      margin: 20px 0;
    }
    
    .container {
      max-width: 1200px;
      margin: 0 auto;
    }
    
    .image {
      width: 100%;
      height: 100%;
    }
    
    .text {
      text-align: center;
    }
    
    .button {
      display: block;
      margin: 20px auto;
      width: 100px;
      height: 40px;
      background-color: #000000;
      color: #ffffff;
      font-size: 20px;
      text-decoration: none;
      border-radius: 5px;
    }
  </style>
</head>
<body>
  <header>
    <h1>My Beautiful Website</h1>
  </header>
  <nav>
    <a href="#">Home</a>
    <a href="#">About</a>
    <a href="#">Contact</a>
  </nav>
  <main>
    <div class="container">
      <img src="https://source.unsplash.com/random" class="image">
      <div class="text">
        <p>This is the main content of my website.</p>
        <p>I can write about anything I want here.</p>
        <p>I can also add images, videos, and other media.</p>
      </div>
      <a href="#">Learn more</a>
    </div>
  </main>
</body>
</html>
