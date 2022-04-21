# RETOS
## REALIZAR LOS SIGUIENTES RETOS CON SU ALGORITMO Y DIAGRAMA DE FLUJO CORRESPONDIENTE CADA UNO 

* Programa que pida un número y diga si es positivo o negativo
* Programa que solicite se ingrese una letra y sólo permita introducir los caracteres s y n.

1.- Inicio
2.- declarar(letra)char
3.- mostrar("ingresa una letra")
4.- asignar(letra)
5.- Sí, letra == "n" || letra == "s" entoces
6.- mostrar "ACEPTADO" 
7.- sino
8.- mostrar "INCORRECTO"
9.- fin si.
10.-fin

* Un programa que pida una letra y detecte si es una vocal. 

1.- Inicio
2.- Declarar(letra)char
3.- Mostrar(ingrese una letra)
4.- Asignar(letra)
5.- Sí, letra == "a" || letra == "e" || letra == "i"|| letra == "o" || letra == "u"
6.- Mostrar "ACEPTADO."
7.- sino
8.- Mostrar "INCORRECTO."
9.- Finsi
10.- Fin

* Programa que pida 3 números y los muestre en pantalla de menor a mayor.  

Inicio
Declarar num1, num2, num3.
Mostrar(Ingresar numeros aleatorios)
Asignar(numero 1)
Asignar(numero 2)
Asignar(numero 3)

Sí, num1<num2 y num2<num3
        Sí, num2<num3
 Mostrar num1,num2,num3
 Sino.
 Mostrar num1,num3,num2
   sino             
    Sí, num2<num1 y num2<num3
        Sí, num1<num3
 Mostrar num2,num1,num3
 sino
 mostrar num2,num3,num1
     sino           
     Sí, num3<num2 y num3<num1
        Sí, num2<num1
  Mostrar num3,num2,num1
  sino
  Mostrar num3,num1,num2
  Finsi
                 FIN

* De un programa que pida un número del 1 al 12 y diga el nombre del mes correspondiente.

INICIO
Declarar(dia)int
Mostrar("ingresa un número")
Asignar(Día)
Caso(día)
        1-mostrar("enero")
        2-mostrar("febrero")
        3-mostrar("marzo")
        4-mostrar("abril")
        5-mostrar("mayo")
        6-mostrar("junio")
        7-mostrar("julio")
        8-mostrar("agosto")
        9-mostrar("septiembre")
        10-mostrar("octubre")
        11-mostrar("noviembre")
        12-mostrar("diciembre")
        < 12 mostrar ("error")
      fincaso
Fin

![mes drawio](https://user-images.githubusercontent.com/103066188/164532574-1b5be2a2-6757-4978-a2cc-da36d44bc443.png)


* De un programa que permita al usuario elegir un candidato por el cual votar. Las posibilidades son: candidato A por el partido rojo, candidato B por el partido verde, candidato C por el partido azul. Según el candidato elegido (A, B ó C) se le debe imprimir el mensaje “Usted ha votado por el partido [color que corresponda al candidato elegido]”. Si el usuario ingresa una opción que no corresponde a ninguno de los candidatos disponibles, indicar “Opción errónea”.
* Para un programa que almacene la cadena de caracteres para una contraseña y email, pregunte al usuario por la contraseña y email e imprima por pantalla si la contraseña y el email introducidos por el usuario coincide con los guardadados en las variables.
