**Reto10**
---
pseudocódigo

    01. INICIO 
    02. escribir x
    03. leer x
    04. mientras x<=0
    05.    escribir x
    06. fin del mientras
    07. factorial=1*2*3
    08. expo= 3 
    09. senx = x
    10. cnt = 1
    11. para x desde 1 hasta x-1
    12.     si cnt%2 diferente de 0
    13.         senx-= (x^expo)/factorial
    14.     si no
    15.         senx+=(x^expo)/factorial
    16.     fin del si
    17.     factorial*= (expo + 1)*(expo+2) 
    18.     expo+=2 
    19.     cnt += 1 
    20. fin del para
    21. FIN   
--- 