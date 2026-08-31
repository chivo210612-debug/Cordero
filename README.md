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

# 3 ejemplos de Conjuntos

# Números registrados
numeros = {1, 2, 3, 4}

# Agregar un nuevo número
numeros.add(5)

print(numeros)

# Estudiantes que practican diferentes deportes
futbol = {"Carlos", "Luis", "Pedro"}
basquetbol = {"Pedro", "Miguel", "Juan"}

# Obtener todos los estudiantes
todos = futbol.union(basquetbol)

print(todos)

# Estudiantes inscritos en diferentes actividades
programacion = {"Carlos", "Luis", "Pedro", "Miguel"}
futbol = {"Pedro", "Miguel", "Juan"}

# Encontrar estudiantes que están en ambas actividades
comunes = programacion.intersection(futbol)

print(comunes)

# 3 ejemplos de Tuplas

# Calificaciones obtenidas
calificaciones = (90, 80, 90, 70, 90, 85)

# Contar cuántas veces aparece 90
cantidad = calificaciones.count(90)

print("El 90 aparece:", cantidad, "veces")

# Días de la semana
dias = ("Lunes", "Martes", "Miércoles", "Jueves", "Viernes")

# Buscar la posición de "Miércoles"
posicion = dias.index("Miércoles")

print("Miércoles está en la posición:", posicion)

# Datos de un producto
producto = ("Laptop", 15000, 10)

# Desempaquetar la tupla
nombre, precio, stock = producto

print("Producto:", nombre)
print("Precio:", precio)
print("Stock:", stock)