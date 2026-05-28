# Interpolación segmentaria
#### Es un método que consiste en dividir un conjunto de datos en varios intervalos pequeños y realizar una interpolación independiente en cada uno de ellos. En lugar de usar una sola ecuación para todos los puntos, se construyen diferentes funciones entre pares o grupos de puntos consecutivos. Esto permite obtener aproximaciones más precisas y evitar errores grandes que pueden aparecer cuando se usa un único polinomio para muchos datos.La forma más común es la interpolación lineal segmentaria, donde cada segmento se representa con una recta entre dos puntos consecutivos. Su fórmula es:

![Imagen](cap2.PNG)

#### donde (xi,yi) y (xi+1,yi+1) son los puntos conocidos del segmento que se está utilizando.Este tipo de interpolación se usa mucho en análisis numérico, gráficas por computadora, procesamiento de datos y simulaciones, ya que permite trabajar con muchos puntos de manera más estable y sencilla.

### Codigo Principal
```python
def interpolacion_segmentaria(x0, y0, x1, y1, x):

    resultado = y0 + ((x - x0)*(y1 - y0)) / (x1 - x0)

    return resultado
```
### CODIGO 1:
```python
x0 = 20
y0 = 125

x1 = 40
y1 = 95

x = 30

resultado = y0 + ((x - x0)*(y1 - y0)) / (x1 - x0)

print("Resultado:", resultado)
```
### Resultado: 110.000

### CODIGO 2:
```python
x0 = 0
y0 = 10

x1 = 5
y1 = 20

x = 3

resultado = y0 + ((x - x0)*(y1 - y0)) / (x1 - x0)

print("Resultado:", resultado)
```
### Resultado: 16.000

### CODIGO 3:
```python
x0 = 2
y0 = 8

x1 = 6
y1 = 20

x = 4

resultado = y0 + ((x - x0)*(y1 - y0)) / (x1 - x0)

print("Resultado:", resultado)
```
### Resultado: 14.000


### CODIGO 4:
```python
x0 = 1
y0 = 5

x1 = 4
y1 = 17

x = 2

resultado = y0 + ((x - x0)*(y1 - y0)) / (x1 - x0)

print("Resultado:", resultado)
```
### Resultado: 9.000


### CODIGO 5:
```python
x0 = 50
y0 = 60

x1 = 80
y1 = 30

x = 70

resultado = y0 + ((x - x0)*(y1 - y0)) / (x1 - x0)

print("Resultado:", resultado)
```
### Resultado: 40.000

