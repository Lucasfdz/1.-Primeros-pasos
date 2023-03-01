# 1.-Primeros-pasos
# Para irme familiarizando con GITHUB y repasar funciones básias de Python, decido subir este código sencillo de compronación de una lista.

dia = input("¿Qué día de la semana puedes venir")
hora = int(input("¿A qué hora vas a pasarte? - indicado en números enteros"))
listadias = ["Lunes", "Martes", "Miercoles", "Jueves"]
listahoras = [9,10,11,12,13,14]

if dia in listadias and hora in listahoras:
    print("Perfecto, te esperamos a esa hora")
else:
    print("Nuestro horario esde 9:00 a 14:00 de Lunes a Jueves")
