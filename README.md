programacion-aplicada-a-la-web
==============================
<!DOCTYPE html>
<!--
To change this license header, choose License Headers in Project Properties.
To change this template file, choose Tools | Templates
and open the template in the editor.
-->
<html>
    <head>
        <title>TODO supply a title</title>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width">
    
        
    </head>
    <body >
      
            <div>   <h4> INGRESE NUMEROS PARA VERIFICAR SI SON PRIMOS:</h4> 
                <input type="text" onchange="esPrimo()" 
                       style="background-color : #E6E6FA;text-align:center" size="7" name="numero3"/> 
                <input type="button" id="generar" value="generar" onclick="esPrimo"/>
            </div><br><br><br>
     
        <h4>INGRESE VALORES HEXADECIMAL:</h4>
        <input type="text"  id="txthexa" value="" /><br><br>
          <h4>INGRESE NUMERO DE CEDULA:</h4>
        <input type="text"  id="txtcedula" value="" /><br><br>
        <input type="button" id="enviar" value="generar" onclick="validacion(n)" />
      
     <br><br> 
    </body>
    

   
</html>
