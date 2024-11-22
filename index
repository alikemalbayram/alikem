<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Araba İbresi Animasyonu</title>
  <style>
    body {
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
      background: #1e272e;
      color: white;
      font-family: Arial, sans-serif;
    }

    .gauge {
      position: relative;
      width: 200px;
      height: 100px;
      border: 10px solid #fff;
      border-bottom: none;
      border-radius: 100px 100px 0 0;
      overflow: hidden;
    }

    .gauge:before {
      content: '';
      position: absolute;
      top: 90px;
      left: 90px;
      width: 20px;
      height: 20px;
      background: #fff;
      border-radius: 50%;
      z-index: 10;
    }

    .needle {
      position: absolute;
      width: 6px;
      height: 100px;
      background: red;
      top: 50%;
      left: 50%;
      transform-origin: bottom center;
      transform: rotate(-90deg);
      animation: move-needle 2s infinite alternate ease-in-out;
    }

    @keyframes move-needle {
      0% {
        transform: rotate(-90deg);
      }
      100% {
        transform: rotate(90deg);
      }
    }

    .ticks {
      position: absolute;
      width: 100%;
      height: 100%;
      top: 0;
      left: 0;
      display: flex;
      justify-content: space-around;
      align-items: center;
    }

    .tick {
      position: absolute;
      width: 2px;
      height: 20px;
      background: #fff;
      transform-origin: bottom center;
    }

    .tick:nth-child(1) { transform: rotate(-90deg) translateX(-100px); }
    .tick:nth-child(2) { transform: rotate(-45deg) translateX(-100px); }
    .tick:nth-child(3) { transform: rotate(0deg) translateX(-100px); }
    .tick:nth-child(4) { transform: rotate(45deg) translateX(-100px); }
    .tick:nth-child(5) { transform: rotate(90deg) translateX(-100px); }
  </style>
</head>
<body>
  <div class="gauge">
    <div class="needle"></div>
    <div class="ticks">
      <div class="tick"></div>
      <div class="tick"></div>
      <div class="tick"></div>
      <div class="tick"></div>
      <div class="tick"></div>
    </div>
  </div>
</body>
</html>
