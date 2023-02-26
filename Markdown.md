## Encabezados:
  Para los encabezados se usan **#**, pueden ir del 1 al 6 siendo el 1 el más grande y el 6 el más pequeño, ejemplo:

# Encabezado con \#
## Encabezado con \##
### Encabezado con \###

## Negritas y cursivas:

  Para negritas se usa el \**  y para cursivas \_, estos símbolos deben ir al inicio y al fin de cada texto a formatear
  
  Ejemplo de **texto en negritas**, aqu literalmente se escribe:  "Ejemplo de \*\*texto en negritas\*\*"
    
  Ejemplo de _texto en cursiva_, aquí´literalmente se escribe "Ejemplo de \_texto en cursiva\_"
    
## Enlaces:
  
   Para poner enlaces se hay que cerrar el texro en corchetes \[ \] y luego encerrar el enlace en paréntesis \( \)
   
   Ejemplo un enlace a github:
   
   enlace a [Github](www.github.com/RobertoASF)

## Enlaces por Referencia:
   
   El otro tipo de enlace es el llamado un enlace referencia. Como el nombre implica, el enlace es una referencia a otro lugar en el documento.
   
   Ejemplo un enlace a github:
   
   Enlace a [mi GitHub][github] se escribe: "Enlace a \[mi GitHub\]\[github\]
   \[github\]: www.github.com/RobertoASF"
   
   [github]: www.github.com/RobertoASF
   
## Imágenes:
 
### enlace en línea a una imagen:
  Para enlazar imágenes de esta forma primero se pone un símbolo de exclamación \( \! \), encierre el texto entre corchetes \( \[ \] \), y después se encierra el enlace entre paréntesis \( \( \) \)
   
   Ejemplo para poner una imágen de mi avatar:

   ![avatar](https://avatars.githubusercontent.com/u/63380708?s=40&v=4) Para esto se escribe: "\!\[avatar\]\(https://avatars.githubusercontent.com/u/63380708?s=40&v=4)"

## imágenes incluidas como referencia:
   para enlazar imágenes de esta forma primero se comienza con el simbolo de expclamación, luego entre corchetes el tecto y leugo dentro de otros corchetes la etiqueta de la imágen, la cual deberá ser definida al final:
   
   Ejemplo para poner una imágen por referencia:
             
  ![mi avatar][imagen]
  
  [imagen]: https://avatars.githubusercontent.com/u/63380708?s=40&v=4 
  Para esto se escribe: "\!\[mi avatar\]\[imagen\]
             
  \[imagen\]: https://avatars.githubusercontent.com/u/63380708?s=40&v=4"
             
  ## Citas:
   
  Para incluir una cita hay que agregar un símbolo \> antes del comienzo de ésta, en caso que se quiera citar un texto de más de un párrafo se puede añadir este símbolo al comienzo de cada párrafo, incluso a las líneas en blanco se le puede agrgar el símbolo \>
  
  Ejemplo:
  
  >"El que tenga miedo a morir que no nazca"
             
   para citar este texto tenemos que escribir:   \>"El que tenga miedo a morir que no nazca"
             
   ## Listas:
    
   Para crear una lista hay que añadir un \* a cada elemento 
   
   Ejemplo:
     
* elemento1
* elemento2
* elemento3
