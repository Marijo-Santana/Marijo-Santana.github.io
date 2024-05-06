<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <table>
        <tr>
            <td><button onclick="act0()">Actividad 0 </button></td>
            <td><button onclick="act1()">Actividad 1</button></td>
            <td><button onclick="act2()">Actividad 2</button></td>
        </tr>
        <tr>
            <td><button onclick="act3()">Actividad 3</button></td>
            <td><button onclick="act4()">Actividad 4</button></td>
            <td><button onclick="act5()">Actividad 5</button></td>
        </tr>
        <tr>
            <td><button onclick="act6()">Actividad 6</button></td>
            <td><button onclick="act7()">Actividad 7</button></td>
            <td><button onclick="act8()">Actividad 8</button></td>
        </tr>
        <tr>
            <td><button onclick="act9()">Actividad 9</button></td>
            <td><button onclick="act10()">Actividad 10</button></td>
            <td><button onclick="act11()">Actividad 11</button></td>
        </tr>
        <p id="demo"></p>
    </table>
   
    <script>
        function act0(){
            document.getElementById("demo").innerHTML="<a href=P0_1P3.html>Ejercicio 0</a>";
        }
        function act1(){
            document.getElementById("demo").innerHTML="<a href=P0_2P3.html>Ejercicio 1</a>";
        }
        function act2(){
            document.getElementById("demo").innerHTML="<a href=P1P3.html>Ejercicio 2</a>";
        }
        function act3(){
            document.getElementById("demo").innerHTML="<a href=P2_1P3.html>Ejercicio 3</a>";
        }
        function act4(){
            document.getElementById("demo").innerHTML="<a href=P2_2P3.html>Ejercicio 4</a>";
        }
        function act5(){
            document.getElementById("demo").innerHTML="<a href=P3_1P3.html>Ejercicio 5</a>";
        }
        function act6(){
            document.getElementById("demo").innerHTML="<a href=P3_2P3.html>Ejercicio 6</a>";
        }
        function act7(){
            document.getElementById("demo").innerHTML="<a href=Arreglos.html>Ejercicio 7</a>";
        }
        function act8(){
            document.getElementById("demo").innerHTML="<a href=P8_1P3.html>Ejercicio 8</a>";
        }
        function act9(){
            document.getElementById("demo").innerHTML="<a href=P8_2P3.html>Ejercicio 9</a>";
        }
        function act10(){
            document.getElementById("demo").innerHTML="<a href=P8_3P3.html>Ejercicio 10</a>";
        }
        function act11(){
            document.getElementById("demo").innerHTML="<a href=P9P3.html>Ejercicio 11</a>";
        }
    </script>
</body>
</html>
