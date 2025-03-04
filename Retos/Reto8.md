**Reto 8**
01. INICIO
02. Escribir “¿desea agregar un artículo?” 
03. Leer pregunta
04. art=0
05. total=0
06. Mientras pregunta = = 1
07. Leer precio
08. art+= 1  
09. Si precio>=200 
10.	   desc= 0.15
11.	   total+= (precio*desc)
12. Si 100<=precio<=199
13.	   desc= 0.12
14.	   total+= precio*desc
15. si no
16.	   desc= 0.10
17.	   total+= precio*desc
18. escriba f”el articulo número {art} cuesta {precio} y tiene un descuento de {desc}”
19. fin si
20. fin del mientras 
21. escríbame f“el total es de {total}” 
22. FIN