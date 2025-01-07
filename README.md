<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Pork Tuah</title>
  <style>
    /* General Body Styling */
    body {
      margin: 0;
      padding: 0;
      font-family: Arial, sans-serif;
      background-color: #ffffff;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      min-height: 100vh;
      overflow: hidden;
    }

    /* Background styling */
    body::before {
      content: "Pork Tuah Pork Tuah Pork Tuah Pork Tuah Pork Tuah Pork Tuah";
      position: absolute;
      top: -50%;
      left: -50%;
      right: -50%;
      bottom: -50%;
      transform: rotate(-45deg);
      font-size: 50px;
      font-weight: bold;
      color: rgba(0, 0, 0, 0.1);
      white-space: nowrap;
      z-index: -1;
    }

    /* Styling for the rotating image */
    .iphone {
      width: 200px;
      animation: ring 2s infinite ease-in-out;
    }

    @keyframes ring {
      0%, 100% {
        transform: rotate(-5deg);
      }
      50% {
        transform: rotate(5deg);
      }
    }

    /* Links Section */
    .links {
      margin-top: 20px;
      text-align: center;
    }

    .links a {
      display: inline-block;
      margin: 10px;
      font-size: 18px;
      text-decoration: none;
      color: #333;
      padding: 10px 15px;
      border: 2px solid #333;
      border-radius: 5px;
      transition: all 0.3s ease;
    }

    .links a:hover {
      background-color: #333;
      color: white;
    }

    /* Logo styling */
    .link-container {
      display: flex;
      align-items: center;
      justify-content: center;
      margin-bottom: 5px;
    }

    .logo {
      width: 20px;
      height: auto;
      margin-right: 10px;
    }
  </style>
</head>
<body>
  <!-- Rotating iPhone Image -->
  <img src="iphone.png" alt="iPhone" class="iphone">

  <!-- Links Section -->
  <div class="links">
    <div class="link-container">
      <img src="pump-logo.png" alt="Pump.fun Logo" class="logo">
      <a href="https://pump.fun" target="_blank">Pump.fun</a>
    </div>
    <div class="link-container">
      <img src="x-logo.png" alt="X Logo" class="logo">
      <a href="https://twitter.com" target="_blank">X Account</a>
    </div>
    <div class="link-container">
      <img src="telegram-logo.png" alt="Telegram Logo" class="logo">
      <a href="https://telegram.org" target="_blank">Telegram</a>
    </div>
  </div>
</body>
</html>
