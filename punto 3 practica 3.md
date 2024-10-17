#3-practica 3 2o parcial
print(" ")
print("Valdez Leal Angel Angel-1350-3W")
print(" ")

#aqui se hara un diccionario con frutas y sus precios
precios_frutas = {
    'manzana': 3,
    'plátano': 2.5,
    'naranja': 4,
    'fresa': 5,
    'uva': 6
}

#aqui se le pregunta al usuario por la fruta y la cantidad de kilo
fruta = input("Introduce el nombre de la fruta: ").lower()
kilos = float(input("Introduce el número de kilos: "))

#se verificar si la fruta está en el diccionario
if fruta in precios_frutas:
    precio_total = precios_frutas[fruta] * kilos
    print(f"El precio de {kilos} kilos de {fruta} es: ${precio_total:.2f}")
else:
    print("Lo siento, esa fruta no está en nuestro diccionario.")

![image](https://github.com/user-attachments/assets/9b95e0fa-151a-49c1-a2d5-0949f7ecd5c1)
![image](https://github.com/user-attachments/assets/a2c0678f-dd45-480e-8aa3-eab0f2d805d3)
