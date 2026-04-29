# 3.Comparación directa con ==
#### Sucede cuando se comparan números decimales usando ==. Aunque dos valores parezcan iguales al mostrarse en pantalla, internamente pueden tener pequeñas diferencias y la comparación resulta falsa.


## Codigo 1:
``` python
print(0.1 + 0.2 == 0.3)
````
``` python
Resultado: False
````

## Codigo 2:
``` python
x = 0.3
y = 0.1 + 0.2
print(x == y)
````
``` python
Resultado: False
````


## Codigo 3:
``` python
print(1.1 + 2.2 == 3.3)
````
``` python
Resultado: False
````

## Codigo 4:
``` python
a = 0.15 + 0.15
print(a == 0.3)
````
``` python
Resultado: True
````

## Codigo 5:
``` python
x = sum([0.1, 0.1, 0.1])
print(x == 0.3)
````

``` python
Resultado: False
````
