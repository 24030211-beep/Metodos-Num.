# 4.Acumulación de errores en bucles
#### Sucede cuando una operación decimal se repite muchas veces dentro de un ciclo. Cada pequeño error de aproximación se va sumando hasta producir una diferencia mayor al final.


## Codigo 1:
```python
a = 1.0000001
b = 1.0000000
print(a - b)
```


## Codigo 2:
```python
x = 1000000.001
y = 1000000.000
print(x - y)
```


## Codigo 3:
```python
a = 5.5555556
b = 5.5555555
print(a - b)
```


## Codigo 4:
```python
x = 99999.9999
y = 99999.9998
print(x - y)
```


## Codigo 5:
```python
p = 2.00000001
q = 2.00000000
print(p - q)
```
