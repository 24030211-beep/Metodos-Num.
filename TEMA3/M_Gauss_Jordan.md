# Método de Gauss-Jordan 
#### Se utiliza para resolver sistemas de ecuaciones lineales. Consiste en transformar la matriz aumentada del sistema hasta obtener una matriz identidad en la parte izquierda, dejando directamente los valores de las incógnitas en la última columna.

# Codigo Principal:
```python
# Sistema:
# x + y = 6
# 2x + 3y = 14

A = [
    [1.0, 1.0, 6.0],
    [2.0, 3.0, 14.0]
]

# Paso 1: Hacer cero debajo del pivote
factor = A[1][0]

A[1][0] = A[1][0] - factor * A[0][0]
A[1][1] = A[1][1] - factor * A[0][1]
A[1][2] = A[1][2] - factor * A[0][2]

# Paso 2: Convertir pivote en 1
divisor = A[1][1]

A[1][1] = A[1][1] / divisor
A[1][2] = A[1][2] / divisor

# Paso 3: Hacer cero arriba del pivote
factor = A[0][1]

A[0][1] = A[0][1] - factor * A[1][1]
A[0][2] = A[0][2] - factor * A[1][2]

print("x =", A[0][2])
print("y =", A[1][2])
```
#### (Ejercicios):

## Codigo 1:

```python
A = [
    [1.0, 1.0, 5.0],
    [2.0, 1.0, 8.0]
]
```
## Resultado 1:
#### x = 3.0       y =2.0 


## Codigo 2:

```python
A = [
    [1.0, 1.0, 4.0],
    [3.0, 1.0, 8.0]
]

```
## Resultado 2:
#### x =2.0         y = 2.0


## Codigo 3:

```python

A = [
    [1.0, 2.0, 7.0],
    [2.0, 1.0, 8.0]
]
```
## Resultado 3:
#### x = 3.0       y = 2.0


## Codigo 4:

```python
A = [
    [1.0, 3.0, 10.0],
    [2.0, 1.0, 8.0]
]

```
## Resultado 4:
#### x =2.8        y = 2.4


## Codigo 5:

```python
A = [
    [2.0, 1.0, 9.0],
    [1.0, 2.0, 12.0]
]

```
## Resultado 5:
#### x =2.0         y =5.0
