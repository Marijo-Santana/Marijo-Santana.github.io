<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu JS</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Dancing+Script:wght@400..700&family=Licorice&family=Pacifico&display=swap" rel="stylesheet">
    <style>
        header
        {
            background-color: rgb(46, 80, 230);
            font-family: 'Times New Roman', Times, serif;
            text-align: center;
            color: white;
            border: 10px solid rgb(23, 0, 128);
            font-size: 30px;
        }
        body{
            background-color: rgb(88, 124, 243);
        }
        .letra {
        font-family: "Licorice", cursive;
        font-weight: 400;
        font-style: normal;
        letter-spacing: 3px;
        }
        .menu{
        background-color: rgb(32, 177, 182);
        width: 70px;
        height: auto;
        border-radius: 3px 3px 3px 3px;
        border: solid 2px rgb(3, 133, 156);
        margin-left: 10px;
        position: fixed;
        }
        </style>
</head>
<body>
    <header class="letra">
        <h1>Actividades Java Script</h1>
    </header>

    <div class="menu">
        <br>
        <a href="https://portafolioprograwebmjsm.000webhostapp.com/Programas%20HTML/Portafolio.html">Portafolio unidad 1</a>
        <br>
        <br>
        <a href="https://portafolioprograwebmjsm.000webhostapp.com/Programas%20CSS/Portafolio%20segundo%20parcial.html">Portafolio unidad 2</a>
        <br>
        <br>
    </div>
    <center>

    
    <table>
        <tr>
            <td><button onclick="act0()">Actividad 0 </button></td>
            <td><button onclick="act1()">Actividad 1</button></td>
            <td><button onclick="act2()">Actividad 2</button></td>
            <td><button onclick="act3()">Actividad 3</button></td>
            <td><button onclick="act4()">Actividad 4</button></td>
            <td><button onclick="act5()">Actividad 5</button></td>
            <td><button onclick="act6()">Actividad 6</button></td>
            <td><button onclick="act7()">Actividad 7</button></td>
        </tr>
        <p id="demo1"></p> 
        </table>     
        <br>
        <br>
        <br>
        <table>      
        <tr>
            <td><button onclick="act8()">Actividad 8</button></td>
            <td><button onclick="act9()">Actividad 9</button></td>
            <td><button onclick="act10()">Actividad 10</button></td>
            <td><button onclick="act11()">Actividad 11</button></td>
        </tr>
        <p id="demo1"></p>
        </table>
        
    
   </center>
    <script>
        function act0(){
            document.getElementById("demo1").innerHTML="<a href=P0_1P3.html>Ejercicio 0</a>";
        }
        function act1(){
            document.getElementById("demo1").innerHTML="<a href=P0_2P3.html>Ejercicio 1</a>";
        }
        function act2(){
            document.getElementById("demo1").innerHTML="<a href=P1P3.html>Ejercicio 2</a>";
        }
        function act3(){
            document.getElementById("demo1").innerHTML="<a href=P2_1P3.html>Ejercicio 3</a>";
        }
        function act4(){
            document.getElementById("demo1").innerHTML="<a href=P2_2P3.html>Ejercicio 4</a>";
        }
        function act5(){
            document.getElementById("demo1").innerHTML="<a href=P3_1P3.html>Ejercicio 5</a>";
        }
        function act6(){
            document.getElementById("demo1").innerHTML="<a href=P3_2P3.html>Ejercicio 6</a>";
        }
        function act7(){
            document.getElementById("demo1").innerHTML="<a href=Arreglos.html>Ejercicio 7</a>";
        }
        function act8(){
            document.getElementById("demo1").innerHTML="<a href=P8_1P3.html>Ejercicio 8</a>";
        }
        function act9(){
            document.getElementById("demo1").innerHTML="<a href=P8_2P3.html>Ejercicio 9</a>";
        }
        function act10(){
            document.getElementById("demo1").innerHTML="<a href=P8_3P3.html>Ejercicio 10</a>";
        }
        function act11(){
            document.getElementById("demo1").innerHTML="<a href=P9P3.html>Ejercicio 11</a>";
        }
        
    </script>
</body>
</html>
