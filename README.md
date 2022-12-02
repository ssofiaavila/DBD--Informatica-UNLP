# DBD--Informatica-UNLP
Prácticas y material de diseño de bases de datos, cursada 2do semestre 2022- Facultad de informática UNLP

## Prácticas ##
* [Enunciados + explicaciones](https://github.com/ssofiaavila/DBD--Informatica-UNLP/tree/main/Pr%C3%A1cticas/Enunciados%20%2B%20explicaciones)
* [Práctica 1](https://github.com/ssofiaavila/DBD--Informatica-UNLP/blob/main/Pr%C3%A1cticas/Pr%C3%A1ctica%201.pdf)
* <details>
  <summary> Práctica 2 </summary>
  
  * [Primera parte- modelos conceptuales y lógicos](https://github.com/ssofiaavila/DBD--Informatica-UNLP/blob/main/Pr%C3%A1cticas/Pr%C3%A1ctica%202-%20Primera%20parte%2C%20conceptual%20y%20l%C3%B3gico.pdf)
  * [Primera parte- modelos físicos](https://github.com/ssofiaavila/DBD--Informatica-UNLP/blob/main/Pr%C3%A1cticas/Pr%C3%A1ctica%202-%20Primera%20parte%2C%20f%C3%ADsico.pdf)
  * [Segunda parte](https://github.com/ssofiaavila/DBD--Informatica-UNLP/blob/main/Pr%C3%A1cticas/Pr%C3%A1ctica%202-%20Segunda%20parte.pdf)
  
  </details>
* [Práctica 3](https://github.com/ssofiaavila/DBD--Informatica-UNLP/blob/main/Pr%C3%A1cticas/Pr%C3%A1ctica%203.pdf)

---
## Probar álgebra relacional ##
1) Crear datos para las tablas con [Mockaroo](https://www.mockaroo.com/) y guardarlos como .csv
2) En [relaX](https://dbis-uibk.github.io/relax/landing) en la parte de "Editor de grupos" declarar el nombre del grupo/ base de datos ```group: ejemplo``` y cada tabla se va a declarar de la siguiente manera  
 
~~~ 
    nombreDeTabla= {  
    dato1: tipoDeDato, dato2: tipoDeDato 
    /* salto a la proxima linea y pego los datos de cada .csv correspondiente a esa tabla, excepto los nombres para cada columna 
    } 
~~~

  [Acá un ejemplo más claro :zap: ](https://github.com/ssofiaavila/DBD--Informatica-UNLP/blob/main/Pr%C3%A1cticas/Schemas%20para%20%C3%A1lgebra%20relacional/ejercicio1.txt)
  
  [__ALGUNAS BASES DE DATOS QUE HICE PARA LA PRÁCTICA 3__](https://github.com/ssofiaavila/DBD--Informatica-UNLP/tree/main/Pr%C3%A1cticas/Schemas%20para%20%C3%A1lgebra%20relacional). Lo único que hay que hacer es en la parte de ```Editor de grupos``` pegar el archivo ```.txt```
  
  __ACLARACIONES PARA SU IMPLEMENTACIÓN__
  * Los __datos declarados en relaX tienen que ser de tipo ```number``` o ```string```__. Los otros no supe cómo hacerlos funcionar por lo tanto a la hora de generar datos en Mockaroo declarar los datos de la tabla como ```number```, ```name```, ```sequence of characters```. En caso de que un dato tenga más de dos palabras, agregarle ```' '``` porque si no relaX lo toma como dos filas distintas. O sea,
    ```QuilmesOeste``` bien
    ```Quilmes Oeste``` mal, tendría que ser ```'Quilmes Oeste'```
  * __Mockaroo permite usar claves foráneas__, tutorial [acá](https://www.youtube.com/watch?v=S_oYFGhZSkQ&ab_channel=Mockaroo)
  * __relaX no permite más de 28 tuplas__

---
## Material ##
* [Teorías](https://github.com/ssofiaavila/DBD--Informatica-UNLP/tree/main/Teor%C3%ADas)


