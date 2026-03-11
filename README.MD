print("Sistema Parqueadero Autos Colombia")

usuarios = []

def registrar_usuario():
    nombre = input("Nombre: ")
    documento = input("Documento: ")
    
    usuario = {
        "nombre": nombre,
        "documento": documento
    }
    
    usuarios.append(usuario)
    print("Usuario registrado")

while True:
    print("\n1. Registrar usuario")
    print("2. Salir")
    
    opcion = input("Seleccione opción: ")
    
    if opcion == "1":
        registrar_usuario()
    elif opcion == "2":
        print("Saliendo del sistema...")
    break
