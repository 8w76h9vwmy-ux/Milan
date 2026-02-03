# Milan
Will you be my valentine 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Will You Be My Valentine?</title>

  <style>
    body {
      margin: 0;
      height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      background: linear-gradient(135deg, #ff758c, #ff7eb3);
      font-family: 'Arial', sans-serif;
      text-align: center;
      color: white;
    }

    .card {
      background: rgba(255, 255, 255, 0.15);
      padding: 30px 25px;
      border-radius: 20px;
      backdrop-filter: blur(10px);
      max-width: 320px;
      width: 90%;
    }

    h1 {
      font-size: 1.8rem;
      margin-bottom: 10px;
    }

    p {
      font-size: 1.1rem;
      margin-bottom: 25px;
    }

    .buttons {
      display: flex;
      justify-content: center;
      gap: 15px;
    }

    button {
      padding: 12px 20px;
      border: none;
      border-radius: 25px;
      font-size: 1rem;
      cursor: pointer;
      transition: transform 0.2s;
    }

    button:hover {
      transform: scale(1.05);
    }

    .yes {
      background: #ff4d6d;
      color: white;
    }

    .no {
      background: white;
      color: #ff4d6d;
    }
  </style>
</head>
<body>

  <div class="card">
    <h1>Hey beb ❤️</h1>
    <p>Will you be my Valentine?</p>

    <div class="buttons">
      <button class="yes" onclick="yesClicked()">Yes 💖</button>
      <button class="no" onclick="noClicked()">No 😢</button>
    </div>
  </div>

  <script>
    function yesClicked() {
      document.body.innerHTML = `
        <div style="
          height:100vh;
          display:flex;
          flex-direction:column;
          align-items:center;
          justify-content:center;
          background:linear-gradient(135deg,#ff758c,#ff7eb3);
          color:white;
          font-family:Arial;
          text-align:center;">
          <h1>Yayyy 🥰</h1>
          <p>You just made my day, beb 💘</p>
        </div>
      `;
    }

    function noClicked() {
      alert("Think again beb 😌💞");
    }
  </script>

</body>
</html>
