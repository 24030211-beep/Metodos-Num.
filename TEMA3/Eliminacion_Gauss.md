# 1.Eliminación Gaussiana
#### Es un método para resolver sistemas de ecuaciones lineales. Consiste en transformar la matriz del sistema en una matriz triangular superior y después encontrar los valores con sustitución hacia atrás.
# Codigo Principal:
```python
A = [
    [2.0, 1.0, 5.0],
    [4.0, -6.0, -2.0]
]

# Paso 1: Hacer cero debajo del primer pivote
factor = A[1][0] / A[0][0]

A[1][0] = A[1][0] - factor * A[0][0]
A[1][1] = A[1][1] - factor * A[0][1]
A[1][2] = A[1][2] - factor * A[0][2]

print("Matriz triangular:")
print(A[0])
print(A[1])

# Paso 2: Sustitución hacia atrás
y = A[1][2] / A[1][1]
x = (A[0][2] - A[0][1] * y) / A[0][0]

print("Valor de x:", x)
print("Valor de y:", y)
```
#### (Ejercicios):
##### Solo cambia la matriz A y usa el mismo código.

## Codigo 1:

```python
A = [
    [1.0, 1.0, 5.0],
    [1.0, -1.0, 1.0]
]
```
## Resultado 1:
#### x = 3.0       y = 2.0


## Codigo 2:

```python
A = [
    [2.0, 1.0, 7.0],
    [1.0, 1.0, 4.0]
]
```
## Resultado 2:
#### x = 3.0        y = 1.0


## Codigo 3:

```python
A = [
    [3.0, 1.0, 10.0],
    [1.0, -1.0, 2.0]
]
```
## Resultado 3:
#### x = 3.0        y = 1.0


## Codigo 4:

```python
A = [
    [1.0, 2.0, 8.0],
    [3.0, 1.0, 9.0]
]
```
## Resultado 4:
#### x = 2.0        y = 3.0


## Codigo 5:

```python
A = [
    [2.0, 3.0, 13.0],
    [1.0, 1.0, 5.0]
]
```
## Resultado 5:
#### x = 2.0         y = 3.0
