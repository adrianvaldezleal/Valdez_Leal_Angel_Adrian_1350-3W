#5-practica 2 2o parcial
print(" ")
print("Valdez Leal Angel Adrian-1350-3W")
print(" ")
import math

#función para calcular el área de un círculo
def calcular_area_circulo(radio):
    return math.pi * (radio ** 2)

#función para calcular el volumen de un cilindro
def calcular_volumen_cilindro(radio, altura):
    area_base = calcular_area_circulo(radio)  # Utiliza la función anterior
    return area_base * altura

#se solicita al usuario ingresar el radio y la altura
radio = float(input("Introduce el radio del círculo: "))
altura = float(input("Introduce la altura del cilindro: "))

#se calcula y muestra el área del círculo
area = calcular_area_circulo(radio)
print(f"El área del círculo es: {area:.2f}")

#se calcula y muestra el volumen del cilindro
volumen = calcular_volumen_cilindro(radio, altura)
print(f"El volumen del cilindro es: {volumen:.2f}")

![image](https://github.com/user-attachments/assets/c8acf4e6-f2e8-4d24-aa35-fabdb2a74ccd)
![image](https://github.com/user-attachments/assets/538cc061-4770-4520-bded-efd11871d95b)

