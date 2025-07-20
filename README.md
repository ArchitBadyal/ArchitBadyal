
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


<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>CSS Woman in Bikini</title>
  <style>
    body {
      background: #87ceeb; /* sky background */
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
    }
    .woman {
      position: relative;
      width: 60px;
    }
    .head {
      width: 40px;
      height: 40px;
      background: #f1c27d;
      border-radius: 50%;
      margin: 0 auto;
    }
    .body {
      position: relative;
      width: 20px;
      height: 80px;
      background: #f1c27d;
      margin: 0 auto;
    }
    .bikini-top {
      position: absolute;
      top: 0;
      left: -10px;
      width: 40px;
      height: 20px;
      background: red;
      border-top-left-radius: 20px;
      border-top-right-radius: 20px;
    }
    .bikini-bottom {
      position: absolute;
      bottom: 0;
      left: -10px;
      width: 40px;
      height: 20px;
      background: red;
      border-bottom-left-radius: 20px;
      border-bottom-right-radius: 20px;
    }
    .legs {
      display: flex;
      justify-content: space-between;
      margin-top: 2px;
    }
    .leg {
      width: 10px;
      height: 60px;
      background: #f1c27d;
    }
    .arms {
      position: absolute;
      top: 20px;
      left: -30px;
      width: 120px;
      display: flex;
      justify-content: space-between;
    }
    .arm {
      width: 10px;
      height: 50px;
      background: #f1c27d;
    }
  </style>
</head>
<body>
  <div class="woman">
    <div class="head"></div>
    <div class="arms">
      <div class="arm"></div>
      <div class="arm"></div>
    </div>
    <div class="body">
      <div class="bikini-top"></div>
      <div class="bikini-bottom"></div>
    </div>
    <div class="legs">
      <div class="leg"></div>
      <div class="leg"></div>
    </div>
  </div>
</body>
</html>
