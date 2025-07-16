<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Botones Centrados</title>
  <style>
    body, html {
      height: 100%;
      margin: 0;
    }

    .centered-container {
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100%;
    }

    .button-group {
      display: flex;
      flex-direction: column;
      gap: 15px; /* Espacio entre botones */
    }

    button {
      padding: 15px 30px;
      font-size: 18px;
      cursor: pointer;
    }
  </style>
</head>
<body>
  <div class="centered-container">
    <div class="button-group">
      <button>Zona negra</button>
      <button>Zona gris</button>
      <button>Cubierta</button>
    </div>
  </div>
</body>
</html>
