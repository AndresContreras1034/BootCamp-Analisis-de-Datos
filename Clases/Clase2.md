
# Conceptos Básicos de Python

Python es un lenguaje de programación fácil de aprender y muy usado para análisis de datos, desarrollo web, automatización y más.  
En este documento se explican los conceptos básicos con ejemplos.

---

## 1. Asignación de Variables

En Python, se asigna un valor a una variable usando el signo `=`.  
Ejemplo:

```python
x = 10          # Asigna 10 a la variable x
nombre = "Ana"  # Asigna "Ana" a la variable nombre
pi = 3.14       # Asigna 3.14 a la variable pi
```

> Nota: No es necesario declarar el tipo de variable; Python lo infiere automáticamente.

---

## 2. Tipos de Datos

Python tiene varios tipos de datos básicos:

- **Enteros** (`int`): Números sin decimales.
- **Decimales** (`float`): Números con decimales.
- **Texto** (`str`): Cadenas de caracteres.
- **Booleanos** (`bool`): Verdadero o falso (`True` / `False`).

Ejemplos:

```python
edad = 25            # int
altura = 1.75        # float
nombre = "Pedro"     # str
es_estudiante = True # bool
```

---

## 3. Concatenación de Cadenas

Se pueden unir cadenas usando el operador `+`:

```python
nombre = "Ana"
apellido = "Gomez"
nombre_completo = nombre + " " + apellido
print(nombre_completo)  # Ana Gomez
```

También se pueden usar **f-strings** para insertar variables dentro de texto:

```python
edad = 25
print(f"Hola, tengo {edad} años")  # Hola, tengo 25 años
```

---

## 4. Operadores Básicos

Python tiene varios operadores:

### Aritméticos
```python
x = 5
y = 2
print(x + y)  # 7
print(x - y)  # 3
print(x * y)  # 10
print(x / y)  # 2.5
print(x // y) # 2 (división entera)
print(x % y)  # 1 (módulo)
print(x ** y) # 25 (potencia)
```

### Comparación
```python
print(x == y)  # False
print(x != y)  # True
print(x > y)   # True
print(x < y)   # False
print(x >= y)  # True
print(x <= y)  # False
```

### Lógicos
```python
a = True
b = False
print(a and b) # False
print(a or b)  # True
print(not a)   # False
```

---

## 5. Entrada y Salida

### Mostrar en pantalla
```python
print("Hola Mundo")
nombre = "Ana"
print("Hola", nombre)
```

### Pedir datos al usuario
```python
nombre = input("Ingresa tu nombre: ")
edad = int(input("Ingresa tu edad: "))  # Convierte la entrada a entero
print(f"Hola {nombre}, tienes {edad} años")
```

---

## 6. Comentarios

Los comentarios se usan para explicar el código y no se ejecutan:

```python
# Esto es un comentario de una línea

"""
Esto es un comentario
de varias líneas
"""
```

---

## 7. Listas

Las listas son colecciones de elementos ordenados:

```python
frutas = ["manzana", "banana", "cereza"]
print(frutas[0])   # manzana
frutas.append("naranja")  # Agregar elemento
print(len(frutas)) # 4
```

---

## 8. Condicionales

Python usa `if`, `elif` y `else`:

```python
edad = 18
if edad >= 18:
    print("Eres mayor de edad")
else:
    print("Eres menor de edad")
```

---

## 9. Bucles

### Bucle `for`
```python
for i in range(5):
    print(i)  # 0 1 2 3 4
```

### Bucle `while`
```python
x = 0
while x < 5:
    print(x)
    x += 1
```

---

## 10. Funciones

Se definen con `def` y pueden recibir parámetros:

```python
def saludar(nombre):
    print(f"Hola {nombre}")

saludar("Ana")  # Hola Ana
```

---

## 11. Diccionarios

Colecciones de pares clave-valor:

```python
persona = {"nombre": "Ana", "edad": 25}
print(persona["nombre"])  # Ana
persona["altura"] = 1.75
```

---

## 12. Operadores de Asignación

Combinan operación y asignación:

```python
x = 5
x += 2  # x = x + 2 => 7
x -= 3  # x = x - 3 => 4
x *= 2  # x = x * 2 => 8
x /= 4  # x = x / 4 => 2.0
```

---

## 13. Otros Conceptos Básicos

- **None**: Representa la ausencia de valor.
- **type()**: Muestra el tipo de dato de una variable.
- **isinstance()**: Verifica si una variable es de cierto tipo.

```python
x = None
print(type(x))           # <class 'NoneType'>
print(isinstance(5, int)) # True
```

---

Este bloque de Markdown cubre **todos los conceptos básicos de Python**, combinando explicación, ejemplos de código y notas, listo para usar como guía de estudio.
```
