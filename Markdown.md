# Índice

* [Encabezados](#encabezados)
* [Énfasis](#énfasis)
* [Enlaces](#enlaces)
  * [Enlaces simples](#enlaces-simples)
  * [Enlaces por Referencia](#enlaces-por-referencia)
* [Imágenes](imágenes)
  * [Enlace en línea a una imagen](enlace-en-línea-a-una-imagen)
  * [Imágenes incluidas como referencia](Imágenes-incluidas-como-referencia)
* [Citas](citas)
* [Códigos](códigos)
* [Listas](listas)
  * [Listas no ordenadas](Listas-no-ordenadas)
  * [Listas ordenadas](Listas-ordenadas)
* [Párrafos](párrafos)


## Encabezados

Para los encabezados se usan **#**, pueden ir del 1 al 6 siendo el 1 el más grande y el 6 el más pequeño, ejemplo:

# Encabezado con \#
## Encabezado con \##
### Encabezado con \###

## Énfasis

  Para negritas se usa el (\**), para cursivas (\_), y para tachado se usa (\~~). Estos símbolos deben ir al inicio y al fin de cada texto a formatear
  
  - `Ejemplo de **texto en negritas**` --> Ejemplo de **texto en negritas**
   
  - `Ejemplo de _texto en cursiva_` --> Ejemplo de _texto en cursiva_

  - `Ejemplo de ~~texto tachado~~` --> Ejemplo de ~~texto tachado~~
  
## Enlaces:

### Enlaces simples

   Para poner enlaces se hay que cerrar el texro en corchetes \[ \] y luego encerrar el enlace en paréntesis \( \)
   
   Ejemplo un enlace a github:
   `enlace a [Github](www.github.com/RobertoASF)` --> enlace a [Github](www.github.com/RobertoASF)

### Enlaces por referencia
   
   El otro tipo de enlace es el llamado un enlace referencia. Como el nombre indica, el enlace es una referencia a otro lugar en el documento. El formato para usar estos enlaces es el siguiente:

   ```
Enlace a [Mi GitHub][enlace].

[enlace]: www.github.com/RobertoASF
   ```
esto se veria así

> Enlace a [Mi GitHub][enlace].
>
>[enlace]: www.github.com/RobertoASF
   

## Imágenes:
 
### Enlace en línea a una imagen:

Para enlazar imágenes de esta forma primero se pone un símbolo de exclamación \( \! \), encierre el texto entre corchetes \( \[ \] \), y después se encierra el enlace entre paréntesis \(  \)
   
Ejemplo para poner una imágen de mi avatar:
`![avatar](https://avatars.githubusercontent.com/u/63380708?s=40&v=4)` --> ![avatar](https://avatars.githubusercontent.com/u/63380708?s=40&v=4) 

### Imágenes incluidas como referencia:
   para enlazar imágenes de esta forma primero se comienza con el simbolo de expclamación, luego entre corchetes el tecto y leugo dentro de otros corchetes la etiqueta de la imágen, la cual deberá ser definida al final:
   
   Ejemplo para poner una imágen por referencia:
   ```
   ![mi avatar][imagen]
  
  [imagen]: https://avatars.githubusercontent.com/u/63380708?s=40&v=4 
   ```
   El resultado es esto es:
   
  ![mi avatar][imagen]
  
  [imagen]: https://avatars.githubusercontent.com/u/63380708?s=40&v=4 
 
## Citas:
   
Para incluir una cita hay que agregar un símbolo \> antes del comienzo de ésta, en caso que se quiera citar un texto de más de un párrafo se puede añadir este símbolo al comienzo de cada párrafo, incluso a las líneas en blanco se le puede agrgar el símbolo \>
  
Ejemplo:
  
`>"El que tenga miedo a morir que no nazca"`
  
>"El que tenga miedo a morir que no nazca"
               
## Códigos
   
Puede agregar código utilizando los siguientes símbolos:

- `código en línea`: escriba el código entre acentos graves (`).
- ```
  código en bloque
  ```
 : Se escribe el código entre tres acentos graves para crear un bloque de código.

Por ejemplo:

- `print("Hola mundo")`
- ```
  if x > 0:
      print("x es positivo")
  ```
      
## Listas:
    
### Listas no ordenadas:
   
Para crear una lista hay que añadir un \* \- o \+ a cada elemento indistintamente
   
Ejemplo:
     
* elemento1
* elemento2
* elemento3

### Listas ordenadas:
  
  Para crear una lista ordenada se debe anteceder el texto de el numero segudido de un un punto
  
  Ejemplo:
  
  1. Primer elemento    <--`1. Primer elemento`
  2. Segundo elemento   <--`2. Segundo elemento`
  3. Tercer elemento    <--`3. Tercer elemento`
  
 ### Listas anidadas:
 
 Si se requiere tener listas dentro de algún elemento de una listas estas se pueden anidar añadiendo dos espacio a los elemenentos que están dentro de otros.
 
 Ejemplo:
 
 - Elemento1
 - Elemento2
   - Sub-elemento1
   - Sub-eleemnto2
     - otro elemento
     - otro elemento 
   - Sub-elemento3
   - Sub-elemento4
 - Elemento3
 - Elemento4
  
## Párrafos

Para que un texto separado por líneas se ninterprete como aprte del mismo párrafo hay que agregaar **dos espacios** justo después del final de la línea que predcede a la continuación del párrafo

Ejemplo:

En este texto  
se agregaron dos espacios  
al final de las palabras  
"texto" y "esapcios"
