## Método de la Cuadratura Gaussiana

#### La cuadratura gaussiana es un método avanzado de integración numérica que busca obtener resultados muy precisos usando puntos especiales llamados nodos gaussianos. A diferencia del trapecio y Simpson, este método no divide el área en figuras geométricas, sino que utiliza puntos estratégicamente elegidos para minimizar el error.

## CODIGO PRINCIPAL
``` python
import math

x1 = -1 / math.sqrt(3)
x2 = 1 / math.sqrt(3)

resultado = f(x1) + f(x2)
```

## CODIGO 1:
``` python
import math

x1 = -1 / math.sqrt(3)
x2 = 1 / math.sqrt(3)

f1 = x1**2 + 2
f2 = x2**2 + 2

resultado = f1 + f2

print("Resultado:", resultado)
```
### Resultado:  4.666
## CODIGO 2:
``` python
import math

x1 = -1 / math.sqrt(3)
x2 = 1 / math.sqrt(3)

f1 = x1**3 + x1
f2 = x2**3 + x2

resultado = f1 + f2

print("Resultado:", resultado)

resultado = f(x1) + f(x2)
```
### Resultado: 0
## CODIGO 3:
``` python
import math

x1 = -1 / math.sqrt(3)
x2 = 1 / math.sqrt(3)

f1 = math.exp(x1)
f2 = math.exp(x2)

resultado = f1 + f2

print("Resultado:", resultado)
```
### Resultado: 2.342
## CODIGO 4:
``` python
import math

x1 = -1 / math.sqrt(3)
x2 = 1 / math.sqrt(3)

f1 = math.sqrt(1 + x1)
f2 = math.sqrt(1 + x2)

resultado = f1 + f2

print("Resultado:", resultado)
```
### Resultado: 1.906
## CODIGO 5:
``` python
import math

x1 = -1 / math.sqrt(3)
x2 = 1 / math.sqrt(3)

f1 = math.cos(x1)
f2 = math.cos(x2)

resultado = f1 + f2

print("Resultado:", resultado)
```
### Resultado: 1.674
