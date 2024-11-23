<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Animated Intro</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      background-color: #f0f0f0;
      margin: 0;
    }

    .text-container {
      font-size: 24px;
      font-weight: bold;
      color: #333;
      overflow: hidden;
      height: 30px; /* ارتفاع السطر */
    }

    .text {
      display: block;
      animation: slide 12s infinite;
      line-height: 30px; /* تساوي ارتفاع السطر */
    }

    @keyframes slide {
      0%, 20% {
        transform: translateY(0);
      }
      25%, 45% {
        transform: translateY(-30px);
      }
      50%, 70% {
        transform: translateY(-60px);
      }
      75%, 100% {
        transform: translateY(-90px);
      }
    }
  </style>
</head>
<body>
  <div class="text-container">
    <div class="text">
      Hi, I'm Shady!<br>
      I’m a Computer Science student at Modern Academy.<br>
      Skilled in C++, Python, and JavaScript.<br>
      Member of the MACPC Community. 😊<br>
    </div>
  </div>
</body>
</html>
