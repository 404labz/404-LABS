# 404-LABS
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>404 LABS — Coming Soon</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      background-color: #000;
      color: #fff;
      font-family: 'Courier New', monospace;
      height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      overflow: hidden;
    }
    video {
      max-width: 300px;
      margin-bottom: 30px;
    }
    h1 {
      font-size: 1.2rem;
      letter-spacing: 0.4rem;
      color: #aaa;
      text-align: center;
      animation: flicker 2s infinite;
    }
    @keyframes flicker {
      0%, 100% { opacity: 1; }
      50% { opacity: 0.5; }
    }
  </style>
</head>
<body>
  <!-- Replace logo.mp4 with your actual video file name -->
  <video src="logo.mp4" autoplay loop muted playsinline></video>
  <h1>COMING SOON</h1>
</body>
</html>
