# 4.Acumulación de errores en bucles
#### Sucede cuando una operación decimal se repite muchas veces dentro de un ciclo. Cada pequeño error de aproximación se va sumando hasta producir una diferencia mayor al final.


## Codigo 1:
```python
suma = 0
for i in range(10):
    suma += 0.1
print(suma)
```
```python
Resultado: 0.9999999999999999
```


## Codigo 2:
```python
x = 1
for i in range(20):
    x *= 1.1
print(x)
```
```python
Resultado: 6.72749994932561
```


## Codigo 3:
```python
total = 0
for i in range(100):
    total += 0.01
print(total
```
```python
Resultado: 1.0000000000000007
```


## Codigo 4:
```python
n = 0
for i in range(7):
    n += 0.2
print(n)

```
```python
Resultado: 1.4
```


## Codigo 5:
```python
valor = 5
for i in range(50):
    valor -= 0.1
print(valor)
```
```python
Resultado: 1.0269562977782698e-15
```
