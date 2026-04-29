# 5. Desbordamiento Silecioso 
#### Sucede cuando un número supera el límite máximo que puede almacenar el tipo de dato float. En muchos casos Python no marca error, sino que muestra inf, que significa infinito.


## Codigo 1:

``` python
x = 1e308 * 10
print(x)
```
```python
Resultado: inf
```


## Codigo 2:

``` python
y = 10.0 ** 400
print(y)
```
```python
Resultado: inf
```


## Codigo 3:

``` python
a = float("1e309")
print(a)
```
```python
Resultado: inf
```


## Codigo 4:

``` python
n = 9e307 * 9e10
print(n)
```
```python
Resultado: inf
```

## Codigo 5:

``` python
x = 1e300
x *= 1e50
print(x)
```
`````python
Resultado: inf
```
