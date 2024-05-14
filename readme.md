# fernando Castro metodologias semana 6
'use strict';
//Agregamos las variables respectivas 
let clave=3214;
let num;
let contador = 0;
do{
    num =(Number(prompt("Digitar Clave")));
    contador++;
}
while (num != clave && contador<5)
    if(contador == 5 && num != clave)
        {
            alert("CLave Incorrecta")
            alert("Tarjeta Bloqueada")
        }else
        {
            alert("Clave correcta")
            alert("Operacion Exitosa")
        }

