# Sufriendo como Inge Vol.2
## Solución a los problemas
A continuación le doy solución a 6 problemas de programación, lastimosamente no son soluciones a problemas de mi vida.
### Vocal minúscula
Dado un número entero, determinar si ese número corresponde al código ASCII de una vocal minúscula.
```pseudocode
n:int
n = int(input("Ingrese un numero: "))
a=chr(n)
v= 'a'or 'e'or 'i' or 'o' or 'u'
if str(a) ==str(v):
     print ("es una vocal minúscula")
     print (chr(n))
else:
    print ("no es una vocal minúscula")
    print (chr(n))
```
### Cadena de Longitud 1
Dada una cadena de longitud 1, determine si el código ASCII de primera letra de la cadena es par o no.
```pseudocode
letra=input("ingresa una letra:")
a= ord(letra)
if a%2==0:
    print ("la letra pertenece a un número par")
else:
    print ("la letra no pertenece a un número par")
 ```
### Dígito o no?
Dado un carácter, construya un programa en Python para determinar si el carácter es un dígito o no.
```pseudocode
n:float
n=float(input("ingrese un carácter:"))
digitos='0' or '1' or '2' or '3' or '4' or '5' or '6' or '7' or '9'
if n==digitos:
    print ("el cáracter es un dígito")
else:
    print ("el cáracter no es un dígito")
   ``` 
### Número Real
Dado un número real x, construya un programa que permita determinar si el número es positivo, negativo o cero. Para cada caso de debe imprimir el texto que se especifica a continuación:
+ Positivo: "El número x es positivo"
+ Negativo: "El número x es negativo"
+ Cero (0): "El número x es el neutro para la suma"

```pseudocode
x:float
x=float(input("Ingresa un número real"))
if x<0:
 print("El número x es negativo")
elif x>=0:
 print ("El número x es positivo")
elif x==0:
 print ("El número x es el neutro para la suma")
 ```
### Círculo
Dado el centro y el radio de un círculo, determinar si un punto de R2 pertenece o no al interior del círculo.
```pseudocode
x:float
x=float(input("Ingrese coordenada x:"))
y:float
y=float(input("Ingrese coordenada y:"))
coordenadas:'x'and 'y'
R:float
R=float(input("Ingrese radio:"))
a:float
a=float(input("Ingrese coordenada a del centro:"))
b:float
b=float(input("Ingrese coordenada b del centro:"))
C:'a' and 'b'
if ((x-a)**2)+((y-b)**2)<=R**2:
    print("las coordenadas están dentro del círculo")
else:
    print("las coordenadas están fuera del círculo")
 ```
### Triángulo
Dadas tres longitudes positivas, determinar si con esas longitudes se puede construir un triángulo.
```pseudocode
a:float
a=float(input("Ingrese longitud a:"))
b:float
b=float(input("Ingrese longitud b:"))
c:float
c=float(input("Ingrese longitud c:"))
if a>0 and b>0 and c>0 and a+b>c and b+c>a and a+c>b:
    print ("puedes construir un triángulo")
else:
    print ("no puedes construir un triángulo")
 ```

