def datos_nicolas():
    print("Mi nombre es Nicolás y tengo 19 años.")

# Menú principal
print("MENÚ")
print("1. Mostrar datos de Nicolás")
print("2. Salir")

op = input("Elige una opción: ")

if op == "1":
    datos_nicolas()
elif op == "2":
    print("Saliendo del programa...")
else:
    print("Opción no válida.")
