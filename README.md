## Un-nuevo-reto-5
Ahora tenemos un nuevo reto : el número cinco de la clase, el cual consiste en:

**1.** Dado un número entero, determinar si ese número corresponde al código ASCII de una vocal minúscula.

```python
# determinar si un numero entero pertenece al codigo ASCII de una vocal minuscula
x : int

if chr(x) == "a" or chr(x) == "e" or chr(x) == "i" or chr(x) == "o" or chr(x) == "u":
    print("el numero " + str(x) + " corresponde al codigo ASCII de una vocal minuscula")
else:
    print("el numero " + str(x) + " no corresponde al codigo ASCII de una vocal minuscula")
```
**2.** Dada una cadena de longitud 1, determine si el código ASCII de primera letra de la cadena es par o no.

```python
# determinar si la primera letra corresponde a un numero par en ASCII
cadena : str # ingresar cadena de longitud 1

if ord(cadena[0]) % 2 == 0: 
    print("el código ASCII de la primera letra corresponde a un número par")
else:
    print("el código ASCII de la primera letra no corresponde a un número par")

if ord(cadena[0]) % 2 == 0: 
    print("el código ASCII de la primera letra corresponde a un número par")
else:
    print("el código ASCII de la primera letra no corresponde a un número par")
```

**3.** Dado un carácter, construya un programa en Python para determinar si el carácter es un dígito o no.

```python
# determinar si el carácfer es un dígito o no
x : int or str
x = input("ingrese un carácter: ")

caracter_x = ord(x)

if caracter_x >= 48 and caracter_x <= 57:
    print(str(x) + " sí es un dígito")
else:
    print(str(x) + " no es un dígito")
```

**4.** Dado un número real x, construya un programa que permita determinar si el número es positivo, negativo o cero. Para cada caso de debe imprimir el texto que se especifica a continuación:

Positivo: "El número x es positivo"
Negativo: "El número x es negativo"
Cero (0): "El número x es el neutro para la suma"

```python
# indicar si el número es negativo, positivo o cero
x : float

if x < 0:
    print("el número x es negativo")
elif x > 0:
    print("el número x es positivo")
else:
    print("el número x es el neutro para la suma")
```

**5.** Dado el centro y el radio de un círculo, determinar si un punto de R2 pertenece o no al interior del círculo.

```python
# determinar si un punto de R2 pertenece o no al círculo
center_x : float
center_y : float
radio: float
a : float
b : float


c = (center_x - a)**2 + (center_y - b)**2
r = radio**2

if c == r:
    print("el punto " + str(a) + ',' + str(b) + " pertenece al interior círculo")
else:
    print("el punto " + str(a) + ',' + str(b) + " no pertenece al interior círculo")
```

**6.** Dadas tres longitudes positivas, determinar si con esas longitudes se puede construir un triángulo.

```python
# determinar si con tres longitudes positivas se puede construir un triángulo
a : float
b : float
c : float

if (a + b) > c and (a + c) > b and (c + b) > a:
    print("sí se puede construir un triángulo")
else:
    print("no se puede construir un triángulo")
```

Así terminamos de solucionar este challenge. :smiley:
