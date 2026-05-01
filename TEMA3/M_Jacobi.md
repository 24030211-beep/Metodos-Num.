# Método de Jacobi
#### El método de Jacobi también es iterativo para resolver sistemas lineales. La diferencia es que en cada iteración usa únicamente los valores anteriores y actualiza al final.

# Codigo Principal:
```python
# Sistema:
# 4x + y = 9
# x + 3y = 8

x = 0
y = 0

for i in range(5):

    x_anterior = x
    y_anterior = y

    nuevo_x = (9 - y_anterior) / 4
    nuevo_y = (8 - x_anterior) / 3

    x = nuevo_x
    y = nuevo_y

    print("Iteracion", i + 1)
    print("x =", x)
    print("y =", y)
```
#### (Ejercicios):
##### Solo cambia nuevo_x y nuevo_y

## Codigo 1:

```python
nuevo_x = (10 - y_anterior) / 5
nuevo_y = (12 - x_anterior) / 4
```
## Resultado 1:
#### x ≈ 1.5750
#### y ≈ 2.6000


## Codigo 2:

```python
nuevo_x = (7 - y_anterior) / 2
nuevo_y = (6 - x_anterior) / 3

```
## Resultado 2:
#### x ≈ 2.1944
#### y ≈ 1.2778


## Codigo 3:

```python
nuevo_x = (15 - y_anterior) / 6
nuevo_y = (9 - x_anterior) / 2

```
## Resultado 3:
#### x ≈ 2.1667
#### y ≈ 3.4167


## Codigo 4:

```python
nuevo_x = (20 - y_anterior) / 8
nuevo_y = (10 - x_anterior) / 3

```
## Resultado 4:
#### x ≈ 2.1250
#### y ≈ 2.6250


## Codigo 5:

```python
nuevo_x = (18 - y_anterior) / 7
nuevo_y = (11 - x_anterior) / 4

```
## Resultado 5:
#### x ≈ 2.1071
#### y ≈ 2.2321
