# Repositorio.

# 3 ejemplos de Listas

# Lista de materias.
materias = ["Matemáticas", "Programación", "Contabilidad"].

# Agregar una nueva materia.
materias.append("Inglés").

print(materias).

# Lista de jugadores.
jugadores = ["Carlos", "Luis", "Miguel", "Pedro"].

# Eliminar un jugador.
jugadores.remove("Miguel").

print(jugadores).

# Calificaciones de estudiantes
calificaciones = [85, 70, 95, 60, 90]

# Ordenar las calificaciones de menor a mayor
calificaciones.sort()

print(calificaciones)

# 3 ejemplos de Diccionarios

# Información de un estudiante
estudiante = {
    "nombre": "Carlos",
    "edad": 22,
    "carrera": "Contaduría"
}

# Obtener la carrera
carrera = estudiante.get("carrera")

print(carrera)

# Información de un producto
producto = {
    "nombre": "Laptop",
    "precio": 15000
}

# Actualizar información
producto.update({"precio": 13500, "stock": 10})

print(producto)

# Datos de un empleado
empleado = {
    "nombre": "Luis",
    "puesto": "Programador",
    "edad": 25
}

# Eliminar la edad
edad = empleado.pop("edad")

print(empleado)
print("Edad eliminada:", edad)