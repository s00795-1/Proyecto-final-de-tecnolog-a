<!DOCTYPE html>
<html lang="es">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>IRTRA SMART GUARD</title>

    <style>

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, Helvetica, sans-serif;
        }

        body {
            min-height: 100vh;
            background: linear-gradient(135deg, #0b3d2e, #087f5b, #f4b942);
            display: flex;
            justify-content: center;
            align-items: center;
            color: white;
        }

        .contenedor {
            width: 90%;
            max-width: 1000px;
            text-align: center;
        }

        h1 {
            font-size: 45px;
            margin-bottom: 10px;
            text-shadow: 2px 2px 5px rgba(0,0,0,0.4);
        }

        .subtitulo {
            font-size: 18px;
            margin-bottom: 40px;
        }

        .tarjeta {
            background: rgba(255, 255, 255, 0.95);
            color: #222;
            width: 350px;
            margin: auto;
            padding: 35px;
            border-radius: 20px;
            box-shadow: 0 15px 35px rgba(0,0,0,0.3);
            transition: all 0.3s ease;
            cursor: pointer;
            text-decoration: none;
            display: block;
        }

        .tarjeta:hover {
            transform: translateY(-12px) scale(1.03);
            box-shadow: 0 25px 45px rgba(0,0,0,0.4);
        }

        .icono {
            font-size: 60px;
            margin-bottom: 20px;
        }

        .tarjeta h2 {
            color: #087f5b;
            margin-bottom: 15px;
        }

        .tarjeta p {
            font-size: 16px;
            line-height: 1.6;
            margin-bottom: 25px;
        }

        .boton {
            display: inline-block;
            background: #f4b942;
            color: #222;
            padding: 12px 25px;
            border-radius: 30px;
            font-weight: bold;
            transition: 0.3s;
        }

        .tarjeta:hover .boton {
            background: #087f5b;
            color: white;
        }

        footer {
            margin-top: 40px;
            font-size: 14px;
            opacity: 0.9;
        }

    </style>
</head>

<body>

    <div class="contenedor">

        <h1>IRTRA SMART GUARD</h1>

        <p class="subtitulo">
            Proyecto final de tecnología
        </p>

        <!-- TARJETA INTERACTIVA -->
        <a 
            class="tarjeta"
            href="https://github.com/s00795-1/Proyecto-final-de-tecnolog-a/blob/main/Investigaci%C3%B3n%20IRTRA%20SMART%20GUARD.docx"
            target="_blank"
        >

            <div class="icono">📄</div>

            <h2>Investigación del proyecto</h2>

            <p>
                Esta es la investigación realizada por el equipo
                sobre nuestra propuesta de circuito para el IRTRA.
            </p>

            <span class="boton">
                Ver investigación →
            </span>

        </a>

        <footer>
            Proyecto Final de Tecnología · IRTRA SMART GUARD
        </footer>

    </div>

</body>

</html>
