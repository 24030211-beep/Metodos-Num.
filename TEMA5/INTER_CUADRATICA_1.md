# Interpolación cuadratica
#### Es un método matemático que se utiliza para estimar valores desconocidos utilizando una función de segundo grado, es decir, una parábola. Este tipo de interpolación se aplica cuando se tienen tres puntos conocidos y se desea obtener una aproximación más precisa que la interpolación lineal. La idea principal es encontrar una ecuación cuadrática que pase exactamente por los tres puntos dados y usarla para calcular valores intermedios dentro del intervalo.
![Imagen](Captura_!.PNG)

### Codigo principal
```python

def interpolacion_cuadratica(x0, y0, x1, y1, x2, y2, x):

    L0 = ((x - x1)*(x - x2)) / ((x0 - x1)*(x0 - x2))
    L1 = ((x - x0)*(x - x2)) / ((x1 - x0)*(x1 - x2))
    L2 = ((x - x0)*(x - x1)) / ((x2 - x0)*(x2 - x1))

    resultado = y0*L0 + y1*L1 + y2*L2

    return resultado
```
### CODIGO 1:
```python

x0 = 1
y0 = 2

x1 = 2
y1 = 3

x2 = 3
y2 = 5

x = 2.5

L0 = ((x - x1)*(x - x2)) / ((x0 - x1)*(x0 - x2))
L1 = ((x - x0)*(x - x2)) / ((x1 - x0)*(x1 - x2))
L2 = ((x - x0)*(x - x1)) / ((x2 - x0)*(x2 - x1))

resultado = y0*L0 + y1*L1 + y2*L2

```
### Resultado: 4.000
### CODIGO 2:
```python

x0 = 0
y0 = 1

x1 = 1
y1 = 3

x2 = 2
y2 = 2

x = 1.5

L0 = ((x - x1)*(x - x2)) / ((x0 - x1)*(x0 - x2))
L1 = ((x - x0)*(x - x2)) / ((x1 - x0)*(x1 - x2))
L2 = ((x - x0)*(x - x1)) / ((x2 - x0)*(x2 - x1))

resultado = y0*L0 + y1*L1 + y2*L2

print("Resultado:", resultado)
```
### Resultado: 2.875
### CODIGO 3:
```python
x0 = 2
y0 = 4

x1 = 4
y1 = 8

x2 = 6
y2 = 7

x = 5

L0 = ((x - x1)*(x - x2)) / ((x0 - x1)*(x0 - x2))
L1 = ((x - x0)*(x - x2)) / ((x1 - x0)*(x1 - x2))
L2 = ((x - x0)*(x - x1)) / ((x2 - x0)*(x2 - x1))

resultado = y0*L0 + y1*L1 + y2*L2

print("Resultado:", resultado)
```
### Resultado:8.000

### CODIGO 4:
```python
x0 = 1
y0 = 5

x1 = 3
y1 = 6

x2 = 5
y2 = 10

x = 4

L0 = ((x - x1)*(x - x2)) / ((x0 - x1)*(x0 - x2))
L1 = ((x - x0)*(x - x2)) / ((x1 - x0)*(x1 - x2))
L2 = ((x - x0)*(x - x1)) / ((x2 - x0)*(x2 - x1))

resultado = y0*L0 + y1*L1 + y2*L2

print("Resultado:", resultado)

```
### Resultado:7.875

### CODIGO 5:
```python
x0 = 10
y0 = 100

x1 = 20
y1 = 400

x2 = 30
y2 = 900

x = 25

L0 = ((x - x1)*(x - x2)) / ((x0 - x1)*(x0 - x2))
L1 = ((x - x0)*(x - x2)) / ((x1 - x0)*(x1 - x2))
L2 = ((x - x0)*(x - x1)) / ((x2 - x0)*(x2 - x1))

resultado = y0*L0 + y1*L1 + y2*L2

print("Resultado:", resultado)

```
### Resultado:625.000

