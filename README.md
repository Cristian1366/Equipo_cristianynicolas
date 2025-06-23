programa
while True:
print("\n--- MENÚ PRINCIPAL ---")
print("1. Función de integrante 1")
print("2. Función de integrante 2")
print("3. Función de integrante 3")
print("0. Salir")
op = input("Seleccione opción: ")
if op == "0":
print("Programa finalizado.")
break
elif op == "1":
pass # Aquí se llamará a la función del integrante 1
elif op == "2":
pass # Aquí se llamará a la función del integrante 2
elif op == "3":
pass # Aquí se llamará a la función del integrante 3
else:
print(" Opción inválida.")









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
