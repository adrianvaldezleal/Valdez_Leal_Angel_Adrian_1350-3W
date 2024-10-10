#6-practica 2 2o parcial
print(" ")
print("Valdez Leal Angel Adrian-1350-3W")
print(" ")

#aqui se hace una funcion para verificar la validez del email
def verificar_my_email(email):
    return '@' in email  #la direcion es valida si contiene (@)

#se le solicita al usuario ingresar su email
email = input("introduce tu dirección de email: ")

#aqui se verifica si la direccion email es válida
if verificar_my_email(email):
    print("La dirección de email es válida.")
else:
    print("La dirección de email no es válida.")

![image](https://github.com/user-attachments/assets/ce52ab4d-76d6-47e6-aa0a-dfbe9d783362)
![image](https://github.com/user-attachments/assets/050749f7-eba9-4212-a48a-391f10c02e78)
