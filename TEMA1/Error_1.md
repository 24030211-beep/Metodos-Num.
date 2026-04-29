# 1.ERROR DE REDONDEO
#### El error de redondeo ocurre cuando un número decimal se aproxima porque la computadora solo guarda cierta cantidad de cifras. 
#### Esto puede causar pequeñas diferencias en los resultados.


## Codigo 1 (División con decimal infinito):

```python
numero = 10 / 3

print("Resultado:", numero)
print("El número tiene infinitos decimales")
print("Python lo aproxima.")

```
```python
Resultado: 3.3333333333333335
```

## Codigo 2 (Suma de decimales):

```python
resultado = 0.1 + 0.2

print("Resultado:", resultado)
print("No aparece exactamente 0.3")
print("Se muestra aproximado.")

```
```python
Resultado: 0.30000000000000004
```

## Codigo 3 (Multiplicación decimal):

```python
resultado = 1.1 * 3

print("Resultado:", resultado)
print("Puede mostrar decimales extras")
print("por redondeo interno."))

```
```python
Resultado:3.3000000000000003
```

## Codigo 4 ( Raíz cuadrada):

```python
resultado = 2 ** 0.5

print("Resultado:", resultado)
print("La raíz es irracional")
print("Python la aproxima.")

```
```python
Resultado: 1.4142135623730951
```

## Codigo 5 (Suma repetida):

```python
suma = 0

for i in range(10):
    suma = suma + 0.1

print("Resultado:", suma)
print("Debería ser 1")
print("Pero puede salir aproximado.")
```
```python
Resultado:  0.9999999999999999
```

