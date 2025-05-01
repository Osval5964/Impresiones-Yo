# Impresiones-Yo
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Impresiones Y.O.</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: Arial, sans-serif;
      background: url('moto.jpg') no-repeat center center fixed;
      background-size: cover;
    }

    .contenedor {
      background: url('madera.jpg') repeat;
      background-size: cover;
      max-width: 700px;
      margin: 80px auto;
      padding: 40px;
      border-radius: 16px;
      box-shadow: 0 0 25px rgba(0, 0, 0, 0.6);
      color: #fff;
      text-align: center;
    }

    h1 {
      font-size: 36px;
      color: #fff;
      text-shadow: 1px 1px 4px #000;
      margin-bottom: 20px;
    }

    .item {
      font-size: 24px;
      margin: 15px 0;
      color: #ffddcc;
      text-shadow: 1px 1px 2px #000;
    }

    .item span {
      color: #fff;
      font-weight: bold;
    }

    @media (max-width: 768px) {
      .contenedor {
        margin: 40px 20px;
        padding: 20px;
      }

      h1 {
        font-size: 28px;
      }

      .item {
        font-size: 20px;
      }
    }
  </style>
</head>
<body>
  <div class="contenedor">
    <h1>IMPRESIONES Y.O.</h1>
    <div class="item"><span>Hoja de texto:</span> $15</div>
    <div class="item"><span>Doble cara:</span> $20</div>
    <div class="item"><span>Fotos – hoja entera:</span> $60</div>
    <div class="item"><span>Fotos – media hoja:</span> $30</div>
    <div class="item"><span>Fotos – ¼ de hoja:</span> $15</div>
    <div class="item"><span>Fotocopias de documentos:</span> $20</div>
    <div class="item"><span>Plastificado de documentos:</span> $60</div>
  </div>
</body>
</html>
