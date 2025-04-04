**Reto 8**
---
pseudocódigo

    01. INICIO
    02. Escribir n
    03. Leer n
    04. art=0 
    05. total=0
    06. Mientras n>0
    07.     escribir precio
    08.     art+= 1  
    09.     Si precio>=200 
    10.	        desc= 15
    11.	        total+= (precio*(desc/100))
    12.     Si precio>= 100
    13.	        desc= 12
    14.	        total+= (precio*(desc/100))
    15.     si no
    16.	        desc= 10
    17.	        total+= (precio*(desc/100))
    18.     fin del si
    19.     escribir "el articulo {art} cuesta {precio} y tiene un descuento de {desc}%"
    20.fin del mientras 
    21.escribir “el total es de {total}” 
    22.FIN
---