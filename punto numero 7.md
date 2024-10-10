#7-practica 2 2o parcial
print(" ")
print("Valdez Leal Angel Adrian-1350-3W")
print(" ")

#se realiza una funcion para calcular la longitud de una palabra
def longitud_de_palabra(s):
    #aqui se eliminan los espacios al inicio y al final del string
    s = s.strip()
    #se divide el string en palabras usando espacios como separador
    palabras = s.split()
    #se verifica la longitud de la última palabra
    return len(palabras[-1]) if palabras else 0

#se imprime la longitud de la palabra
texto =  " popocatepetl "
print("la longiutd de la palabra es:",longitud_de_palabra(texto))

![image](https://github.com/user-attachments/assets/c08f9afb-6adc-454f-b68e-927a57fc65bd)
![image](https://github.com/user-attachments/assets/e8b195b6-0e30-4f80-805b-090a02bb0ba8)
