## METODO DEL TRAPRECIO

#### El método del trapecio es un método de integración numérica que sirve para aproximar el valor de una integral definida. Este método reemplaza la curva de la función por una línea recta entre dos puntos, formando un trapecio.
#### La idea principal es calcular el área del trapecio para aproximar el área bajo la curva.

CODIGO 1:
```python

def trapecio(fa, fb, a, b):
    resultado = ((b - a) / 2) * (fa + fb)
    return resultado
```
CODIGO 2:
```python

CODIGO 1:
```python

def trapecio(fa, fb, a, b):
    resultado = ((b - a) / 2) * (fa + fb)
    return resultado
```

```
CODIGO 3:
```python

a = 1
b = 3

fa = 2*a + 5
fb = 2*b + 5

resultado = ((b - a) / 2) * (fa + fb)

print("Resultado:", resultado)
```
CODIGO 4:
```python

import math

a = 0
b = 4

fa = math.sqrt(a + 1)
fb = math.sqrt(b + 1)

resultado = ((b - a) / 2) * (fa + fb)

print("Resultado:", resultado)
```
CODIGO 5:
```python

import math

a = 0
b = math.pi

fa = math.sin(a)
fb = math.sin(b)

resultado = ((b - a) / 2) * (fa + fb)

print("Resultado:", resultado)
```

