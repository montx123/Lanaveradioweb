<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>La Nave Radio Web</title>
  <style>
    body {
      background-color: #121212;
      color: #fff;
      font-family: 'Arial', sans-serif;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      height: 100vh;
      margin: 0;
    }
    h1 {
      margin-bottom: 20px;
      font-size: 2rem;
      color: #00ffe1;
    }
    img {
      max-width: 250px;
      margin-bottom: 20px;
    }
    audio {
      width: 90%;
      max-width: 400px;
      border: 2px solid #00ffe1;
      border-radius: 8px;
      background-color: #1e1e1e;
      padding: 10px;
    }
  </style>
</head>
<body>
  <!-- Logo agregado -->
<img src="la_nave_logo.png" alt="Logo La Nave Radio Web">

  <h1>Escuchanos en vivo</h1>
  <audio controls autoplay>
    <source src="https://stream.zeno.fm/utaaqemlboovv" type="audio/mpeg">
    Tu navegador no soporta audio en línea.
  </audio>
</body>
</html>
