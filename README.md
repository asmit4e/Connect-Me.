<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Social Media Contact Icons</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #fff;
      text-align: center;
      padding: 40px;
    }

    .social-icons {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(120px, 1fr));
      gap: 30px;
      max-width: 800px;
      margin: auto;
    }

    .icon-box {
      display: flex;
      flex-direction: column;
      align-items: center;
    }

    .icon-box a {
      text-decoration: none;
      color: #5a00a2;
      font-weight: bold;
      margin-top: 10px;
      display: flex;
      align-items: center;
      gap: 5px;
    }

    .icon {
      font-size: 50px;
      width: 80px;
      height: 80px;
      line-height: 80px;
      border-radius: 50%;
      color: white;
      display: flex;
      align-items: center;
      justify-content: center;
      transition: transform 0.3s ease;
    }

    .icon:hover {
      transform: scale(1.1);
    }

    /* Individual platform colors */
    .linkedin    { background: #0A66C2; }
    .twitter     { background: #1DA1F2; }
    .whatsapp    { background: #25D366; }
    .telegram    { background: #0088cc; }
    .facebook    { background: #1877F2; }
    .instagram   { background: radial-gradient(circle at 30% 107%, #fdf497 0%, #fdf497 5%, #fd5949 45%, #d6249f 60%, #285AEB 90%); }
    .person      { background: #34a853; }
    .like        { background: #ccc; color: #555; }
  </style>
</head>
<body>

  <div class="social-icons">

    <div class="icon-box">
      <div class="icon linkedin"><i class="fab fa-linkedin-in"></i></div>
      <a href="https://www.linkedin.com/in/asmit-singh-795b97287" target="_blank"><i class="fa-solid fa-hand"></i> click dude</a>
    </div>

    <div class="icon-box">
      <div class="icon twitter"><i class="fab fa-twitter"></i></div>
      <a href="https://x.com/sasmit959" target="_blank"><i class="fa-solid fa-hand"></i> click dude</a>
    </div>

    <div class="icon-box">
      <div class="icon whatsapp"><i class="fab fa-whatsapp"></i></div>
      <a href="https://wa.me/918004413591" target="_blank"><i class="fa-solid fa-hand"></i> click dude</a>
    </div>

    <div class="icon-box">
      <div class="icon telegram"><i class="fab fa-telegram-plane"></i></div>
      <a href="https://t.me/asmit_4e" target="_blank"><i class="fa-solid fa-hand"></i> click dude</a>
    </div>

    <div class="icon-box">
      <div class="icon like"><i class="fas fa-thumbs-up"></i></div>
      <a href="#"><i class="fa-solid fa-hand"></i> click dude</a>
    </div>

    <div class="icon-box">
      <div class="icon facebook"><i class="fab fa-facebook-f"></i></div>
      <a href="https://www.facebook.com/profile.php?id=61553400024153" target="_blank"><i class="fa-solid fa-hand"></i> click dude</a>
    </div>

    <div class="icon-box">
      <div class="icon instagram"><i class="fab fa-instagram"></i></div>
      <a href="https://www.instagram.com/__jay_4e" target="_blank"><i class="fa-solid fa-hand"></i> click dude</a>
    </div>

    <div class="icon-box">
      <div class="icon person"><i class="fas fa-user"></i></div>
      <a href="#"><i class="fa-solid fa-hand"></i> click dude</a>
    </div>

  </div>

</body>
</html>
