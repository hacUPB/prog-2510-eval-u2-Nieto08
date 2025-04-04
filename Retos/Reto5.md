**Reto 5**
---
pseudocódigo

    01. INICIO 
    02. escrbir pago_hora, horas_trabajadas
    03. Leer pago_hora, horas_trabajadas
    04. si horas_trabajas>50 o horas_trabajadas<0
    05.       escribir("Hable con recursos humanos")
    06. si no
    07.     si horas_trabajadas<=40
    08.        pago= horas_trabajadas * pago_horas
    09.     si no 
    10.        pago= 40 * pago_horas         # 40 son las horas base 
    11.        horas_extra= horas_trabajadas - 40 
    12.        si horas_extra<=5 
    13.           pago+= (horas_extra * pago_ horas * 2)
    14.        si no 
    15.           pago+= (5 * pago_ horas * 2)  # pagar rango(40,45)
    16.           pago+= ((horas_extra-5) * pago_horas * 3) #pagar rango (46,50)
    17.        fin del si
    18.     fin del si
    19. fin del si
    20. escribir "su pago es de {pago}"
    21. FIN
---