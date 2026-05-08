# Interpolación segmentaria
#### Es un método que consiste en dividir un conjunto de datos en varios intervalos pequeños y realizar una interpolación independiente en cada uno de ellos. En lugar de usar una sola ecuación para todos los puntos, se construyen diferentes funciones entre pares o grupos de puntos consecutivos. Esto permite obtener aproximaciones más precisas y evitar errores grandes que pueden aparecer cuando se usa un único polinomio para muchos datos.La forma más común es la interpolación lineal segmentaria, donde cada segmento se representa con una recta entre dos puntos consecutivos. Su fórmula es:

![Imagen](cap2.PNG)

#### donde (xi,yi) y (xi+1,yi+1) son los puntos conocidos del segmento que se está utilizando.Este tipo de interpolación se usa mucho en análisis numérico, gráficas por computadora, procesamiento de datos y simulaciones, ya que permite trabajar con muchos puntos de manera más estable y sencilla.
