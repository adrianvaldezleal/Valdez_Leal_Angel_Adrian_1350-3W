#4-practica 2 2o parcial
print(" ")
print("Valdez Leal Angel Adrian-1350-3W")
print(" ")

#aqui se hace una funcion para calcular el total de la factura de IVA
def calcular_total_factura(cantidad_sin_iva, porcentaje_iva=21):
    #se calcula el IVA
    iva = cantidad_sin_iva * (porcentaje_iva / 100)
    #se calcula el total
    total = cantidad_sin_iva + iva
    return total

#aqui se le pide al usario ingresar la cantidad sin IVA
cantidad = float(input("Introduce la cantidad sin IVA: "))
#aqui se calcula el total de la factura usando el IVA por defecto 21%
total_factura = calcular_total_factura(cantidad)
#se imprime el resultado
print("El total de la factura es:", total_factura)

![image](https://github.com/user-attachments/assets/d60d1d10-1b43-4ebc-8561-d0abd809c969)
![image](https://github.com/user-attachments/assets/b7d74f19-87cd-42ee-a657-95d29c74b9c5)
