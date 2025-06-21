<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>KNHMA - Future Innovations</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: #0f2027;
      color: #fff;
      display: flex;
      flex-direction: column;
      align-items: center;
      padding: 40px;
    }

    h1 {
      font-size: 3em;
      margin-bottom: 0.3em;
    }

    p {
      font-size: 1.2em;
      margin-bottom: 2em;
      max-width: 700px;
      text-align: center;
    }

    .projects {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
    }

    .card {
      background-color: #203a43;
      border-radius: 10px;
      padding: 20px;
      width: 250px;
      text-align: center;
      transition: 0.3s;
    }

    .card:hover {
      background-color: #2c5364;
    }

    .card a {
      color: #00e676;
      text-decoration: none;
      font-weight: bold;
      display: block;
      margin-top: 10px;
    }
  </style>
</head>
<body>
  <h1>Welcome to KNHMA</h1>
  <p>We are building cutting-edge innovations that aim to impact the world. Below are our current and future projects:</p>

  <div class="projects">
    <div class="card">
      <h3>ViBreath</h3>
      <p>Vitamin analysis through breath sensors</p>
      <a href="vibreath/index.html">Explore</a>
    </div>

    <div class="card">
      <h3>Phobianicotine</h3>
      <p>Genetically engineered bacteria to reduce nicotine</p>
      <a href="phobianicotine/index.html">Explore</a>
    </div>

    <div class="card">
      <h3>CellSpy</h3>
      <p>Reprogramming cancer cells via stealth cell therapy</p>
      <a href="cellspy/index.html">Explore</a>
    </div>

    <div class="card">
      <h3>CarbonBlock</h3>
      <p>CO emission blocker for factories</p>
      <a href="carbonblock/index.html">Explore</a>
    </div>

    <div class="card">
      <h3>RadShield</h3>
      <p>Drone to mitigate nuclear radiation leakage</p>
      <a href="radshield/index.html">Explore</a>
    </div>
  </div>
</body>
</html>