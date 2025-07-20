<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>CSS Car</title>
  <style>
    .car {
      position: relative;
      width: 200px;
      height: 60px;
      background: blue;
      border-radius: 10px; b
      margin: 100px auto;
    }

    .car-top {
      position: absolute;
      top: -30px;
      left: 40px;
      width: 120px;
      height: 30px;
      background: blue;
      border-radius: 5px;
    }

    .window {
      position: absolute;
      top: -25px;
      left: 50px;
      width: 40px;
      height: 20px;
      background: lightblue;
      border-radius: 3px;
    }

    .window2 {
      position: absolute;
      top: -25px;
      left: 110px;
      width: 40px;
      height: 20px;
      background: lightblue;
      border-radius: 3px;
    }

    .wheel {
      position: absolute;
      bottom: -20px;
      width: 40px;
      height: 40px;
      background: black;
      border-radius: 50%;
    }

    .wheel.left {
      left: 20px;
    }

    .wheel.right {
      right: 20px;
    }
  </style>
</head>
<body>
  <div class="car">
    <div class="car-top"></div>
    <div class="window"></div>
    <div class="window2"></div>
    <div class="wheel left"></div>
    <div class="wheel right"></div>
  </div>
</body>
</html>
