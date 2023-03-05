# Sufriendo como Inge Vol.2
## Solución a los problemas
A continuación le doy solución a 6 problemas de programación, lastimosamente no son soluciones a problemas de mi vida. 
### Vocal minúscula
Dado un número entero, determinar si ese número corresponde al código ASCII de una vocal minúscula.
![image](https://user-images.githubusercontent.com/124603892/222986405-b9308778-2653-4837-8616-ed77f59434a9.png)

```python
n: Int
n = int(input("lngrese un numero: "))
a = chr(n)
v = 'a' or 'e' or 'i' or 'o' or 'u'
if str(a) == str(v) :
  print ("es una vocal minuscula")
  print (chr(n))
else:
  print ("no es una vocal minuscula")
  print (chr(n))
```
### Cadena de Longitud 1
Dada una cadena de longitud 1, determine si el código ASCII de primera letra de la cadena es par o no.
![image](https://user-images.githubusercontent.com/124603892/222986455-1cc241f3-39bf-4c6e-9137-ee58aafaf718.png)
### Dígito o no?
Dado un carácter, construya un programa en Python para determinar si el carácter es un dígito o no.
![image](https://user-images.githubusercontent.com/124603892/222986593-065a4dff-be2a-45e8-9931-1911abcb5b99.png)
### Número Real
Dado un número real x, construya un programa que permita determinar si el número es positivo, negativo o cero. Para cada caso de debe imprimir el texto que se especifica a continuación:
+ Positivo: "El número x es positivo"
+ Negativo: "El número x es negativo"
+ Cero (0): "El número x es el neutro para la suma"

![image](https://user-images.githubusercontent.com/124603892/222986896-f6cdb6d9-6537-42ca-89cb-4b08408c226f.png)
### Círculo
Dado el centro y el radio de un círculo, determinar si un punto de R2 pertenece o no al interior del círculo.
![image](https://user-images.githubusercontent.com/124603892/222986979-c1d30cd8-7037-4511-973e-67ebc77cdc9b.png)
### Triángulo
Dadas tres longitudes positivas, determinar si con esas longitudes se puede construir un triángulo.
![image](https://user-images.githubusercontent.com/124603892/222987014-3c504e12-39eb-46b3-bfea-5fb0fc8e9eb9.png)


