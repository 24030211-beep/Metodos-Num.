## Regla de Simpson

#### La regla de Simpson es un método de integración numérica más preciso que el método del trapecio. En lugar de aproximar la curva con una línea recta, Simpson usa una parábola que pasa por tres puntos de la función: punto inicial, punto medio. punto final

## CODIGO PRINCIPAL

``` Python

def simpson(fa, fm, fb, a, b):
    resultado = ((b - a) / 6) * (fa + 4*fm + fb)
    return resultado

```

## CODIGO 1:

``` Python

def simpson(fa, fm, fb, a, b):
    resultado = ((b - a) / 6) * (fa + 4*fm + fb)
    return resultado

```
### Resultado: 6.000
## CODIGO 1:

``` Python

def simpson(fa, fm, fb, a, b):
    resultado = ((b - a) / 6) * (fa + 4*fm + fb)
    return resultado

```
### Resultado:17.333
## CODIGO 1:

``` Python

a = 0
b = 2
m = (a + b) / 2

fa = a**3 + 1
fm = m**3 + 1
fb = b**3 + 1

resultado = ((b - a) / 6) * (fa + 4*fm + fb)

print("Resultado:", resultado)

```
### Resultado:
## CODIGO 2:

``` Python

a = 1
b = 5
m = (a + b) / 2

fa = a**2 - 2*a
fm = m**2 - 2*m
fb = b**2 - 2*b

resultado = ((b - a) / 6) * (fa + 4*fm + fb)

print("Resultado:", resultado)

```
### Resultado:
## CODIGO 3:

``` Python

a = 1
b = 5
m = (a + b) / 2

fa = a**2 - 2*a
fm = m**2 - 2*m
fb = b**2 - 2*b

resultado = ((b - a) / 6) * (fa + 4*fm + fb)

print("Resultado:", resultado)
```
### Resultado: 0
## CODIGO 4:

``` Python

a = 1
b = 4
m = (a + b) / 2

fa = 1/a
fm = 1/m
fb = 1/b

resultado = ((b - a) / 6) * (fa + 4*fm + fb)

print("Resultado:", resultado)

print("Resultado:", resultado)
```
### Resultado: 1.425
## CODIGO 5:

``` Python

import math

a = 0
b = 3
m = (a + b) / 2

fa = math.exp(a)
fm = math.exp(m)
fb = math.exp(b)

resultado = ((b - a) / 6) * (fa + 4*fm + fb)

print("Resultado:", resultado)
```
### Resultado: 19,835
