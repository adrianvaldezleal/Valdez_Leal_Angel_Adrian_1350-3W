#3-practica 2 2o parcial
print(" ")
print("Valdez Leal Angel Adrian-1350-3W")
print(" ")

#aqui se hace una funcion para calcular la factorial de un numero
def my_factorial(n):
    resultado = 1
    for i in range(2, n + 1):
        resultado *= i
    return resultado

#aqui se solicita al usuario ingresar un número entero positivo
numero = int(input("Introduce un número entero positivo: "))
resultado = my_factorial(numero)
#aqui se imprime la factorial del numero
print("El factorial es:",resultado)

![image](https://github.com/user-attachments/assets/44ff9b9c-61f7-4f44-ba99-4394429e0bc4)
![image](https://github.com/user-attachments/assets/c3af3efe-225f-490b-93bd-68c888fa936a)

