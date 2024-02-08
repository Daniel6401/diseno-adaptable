# diseno-adaptable
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Proyecto Peliculas</title>
    <style>
        body{
            padding: 0px;
            margin: 0;
            font-family: 'Times New Roman', Times, serif;
            background-color: aliceblue;

        }
        header{
                text-align: center;
                container: cabeza;
                background-color: rgb(136, 128, 117);
        }
        div {
            background-color: rgb(200, 210, 210);
            border: 1px solid #ddd;
            padding: 15px;
            margin: 10px;
            display: inline-block;
            width: 600px;
            text-align: center;
            }
            div image {
                border-radius: 50px;
                margin-bottom: 5px;
                height: auto;
            }
            header {padding: 10px 0;}
            @media (max-width:600px) { div{ width: 90%;
            margin: 10px auto;}
          }

    </style>
</head>
<body>
    <header>
        <h1>Peliculas Animadas</h1>
        <button style="margin: 5%;" class="Menu"> Menu</button>
    </header>
    <div>
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQb0niU5_-nJcGruRTitqp6LWLeP5Av8LnPWcJ4eUz8avZ9zpXb">
        <strong><p>Pelicula 1</p></strong>
        <p>Descripcion del Producto 1</p>
        <p>$19,99</p>
        <a href="#">Comprar</a>
    </div>

</body>
</html>
