# Condicionales `if` en Python

Los condicionales permiten **tomar decisiones** en el programa. Con `if` se evalúa una condición y, según el resultado, se ejecuta o no un bloque de código.

## 1. `if`
Ejecuta el bloque solo si la condición es **verdadera**.

```python
x = 10
if x > 5:
    print("x es mayor que 5")
```

## 2. `if - else`
Permite elegir entre **dos caminos**.

```python
x = 3
if x > 5:
    print("x es mayor que 5")
else:
    print("x es menor o igual que 5")
```

## 3. `if - elif - else`
Permite evaluar **múltiples condiciones** en orden.

```python
x = 7
if x < 5:
    print("x es menor que 5")
elif x == 5:
    print("x es igual a 5")
else:
    print("x es mayor que 5")
```

**Resumen**

| Forma               | Uso principal                            |
|---------------------|------------------------------------------|
| `if`                | Ejecutar código si la condición es true  |
| `if - else`         | Elegir entre dos opciones                |
| `if - elif - else`  | Evaluar varias condiciones en secuencia  |
