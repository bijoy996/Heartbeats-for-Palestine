# Heartbeats-for-Palestine
Help Gaza
<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Heartbeats for Palestine</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f5f5f5;
      color: #222;
    }
    header {
      background: linear-gradient(to right, #006400, #1e90ff);
      color: white;
      padding: 40px 20px;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2.5rem;
    }
    .content {
      padding: 30px 20px;
      text-align: center;
    }
    .content p {
      font-size: 1.2rem;
      max-width: 600px;
      margin: 0 auto 30px;
    }
    .qr-section img {
      width: 200px;
      height: 200px;
      border: 5px solid #1e90ff;
      border-radius: 16px;
    }
    .donate-btn {
      background-color: #1e90ff;
      color: white;
      padding: 14px 28px;
      font-size: 1rem;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      margin-top: 20px;
      transition: background-color 0.3s ease;
    }
    .donate-btn:hover {
      background-color: #006400;
    }
    footer {
      background: #222;
      color: #ccc;
      text-align: center;
      padding: 20px;
      font-size: 0.9rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>Heartbeats for Palestine</h1>
    <p>Stand with Gaza. Every heartbeat matters. Every donation helps.</p>
  </header>  <section class="content">
    <p>Scan the QR code below to donate securely. Your generosity fuels hope and healing.</p>
    <div class="qr-section">
      <img src="qr-code.png" alt="Donate QR Code">
    </div>
    <button class="donate-btn" onclick="alert('Please scan the QR code above using your mobile banking app.')"><button class="donate-btn">Donate Now</button>
    &copy; 2025 Heartbeats for Palestine. All rights reserved.
  </footer>
</body>
</html>
