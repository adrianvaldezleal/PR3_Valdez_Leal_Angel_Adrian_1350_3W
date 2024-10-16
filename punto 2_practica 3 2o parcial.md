#2_practica 3 2o parcial
print(" ")
print("Valdez Leal Angel Adrian-1350-3W")
print(" ")

#aqui se solicitara al usuario su informacion
nombre = input("Cuál es tu nombre? ")
edad = input("Cuántos años tienes? ")
direccion = input("Cuál es tu dirección? ")
telefono = input("Cuál es tu número de teléfono? ")

#aqui se gurdara la informacion de usuario en diccionario
usuario = {
"nombre": nombre, #se almacena el nombre del usuario
"edad": edad, #se almacena la edad del usuario
"direccion": direccion, #se almacena la direccion del usuario
"telefono": telefono #se almacena el telefono del usuario
}

#aqui se desplegara el mensaje
print(f"{usuario['nombre']} tiene {usuario['edad']} años, vive en {usuario['direccion']} y su número de teléfono es {usuario['telefono']}.")

![image](https://github.com/user-attachments/assets/d877d0b9-234e-435f-8af8-4e9ea9fc5f22)
![image](https://github.com/user-attachments/assets/02e1f603-0d39-4a42-8a7c-6a1aba1997da)

