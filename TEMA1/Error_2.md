# 2.Pérdida de precisión por magnitud
#### Sucede cuando se realizan operaciones entre números muy grandes y números muy pequeños. Debido a la forma en que Python guarda los decimales (float), el número pequeño puede no influir en el resultado o perderse parcialmente.


## Codigo 1:

```python
x = 10000000000000000.0 + 1
print(x)
```
```python
Resultado: 10000000000000000.0
```


## Codigo 2:

```python
x = 1e16 + 0.5
print(x)
```
```python
Resultado: 10000000000000000.0
```

## Codigo 3:

```python
x = 9999999999999999.0 + 2
print(x)
```
```python
Resultado: 10000000000000000.0
```

## Codigo 4:

```python
x = 1e20 + 3
print(x)
```
```python
Resultado: 1e+20
```


## Codigo 5:

```python
x = 5000000000000000.0 + 0.1
print(x)
```

```python
 Resultado: 5000000000000000.0
```
