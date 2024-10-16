#practica 3 2o parcial
print(" ")
print("Valdez Leal Angel Adrian-1350-3W")
print(" ")
#aqui se va a guardar una variable en el diccionario
divisas = {'Euro': '€', 'Dollar': '$', '¥': 'Yen'}

#aqui se le pedira al usuario ingresar una divisa
entrada = input("Ingresa el nombre de una divisa (Euro, Dollar, Yen): ")

#aqui se mostrara un símbolo o un mensaje si la divisa no está en el diccionario
if entrada in divisas:
    print(f"El símbolo de {entrada} es: {divisas[entrada]}") #si la divisa esta en el diccionario se imprime 
else:
    print("La divisa no está en el diccionario.") #se mostrara un mensaje de error si la divisa no esta


![image](https://github.com/user-attachments/assets/f797015b-4e9f-49f9-a052-96bb580c7468)
![image](https://github.com/user-attachments/assets/555674cf-4bb5-4819-a4e2-a6bc9b84b053)
