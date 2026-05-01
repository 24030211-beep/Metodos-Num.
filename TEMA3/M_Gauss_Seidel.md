# Método de Gauss-Seidel
#### El método de Gauss-Seidel es un método iterativo para resolver sistemas de ecuaciones lineales. Parte de valores iniciales y va mejorando la solución en cada iteración usando inmediatamente los valores nuevos calculados.

# Codigo Principal:
```python
# Sistema:
# 4x + y = 9
# x + 3y = 8

x = 0
y = 0

for i in range(5):

    x = (9 - y) / 4
    y = (8 - x) / 3

    print("Iteracion", i + 1)
    print("x =", x)
    print("y =", y)
```
#### (Ejercicios):
###### Solo cambia las fórmulas dentro del for

## Codigo 1:

```python
x = (10 - y) / 5
y = (12 - x) / 4
```
## Resultado 1:
#### x ≈ 1.5781
#### y ≈ 2.6055 


## Codigo 2:

```python
x = (7 - y) / 2
y = (6 - x) / 3

```
## Resultado 2:
#### x ≈ 2.2006
#### y ≈ 1.2665

## Codigo 3:

```python
x = (15 - y) / 6
y = (9 - x) / 2

```
## Resultado 3:
#### x ≈ 2.1813
#### y ≈ 3.4093


## Codigo 4:

```python
x = (20 - y) / 8
y = (10 - x) / 3

```
## Resultado 4:
#### x ≈ 2.1277
#### y ≈ 2.6241


## Codigo 5:

```python
x = (18 - y) / 7
y = (11 - x) / 4

```
## Resultado 5:
#### x ≈ 2.1034
#### y ≈ 2.2241
