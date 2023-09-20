# Reto_4_a_un_paso_de_hakehar_la_nasa

## Punto 1

Dado un número entero, determinar si ese número corresponde al código ASCII de una vocal minúscula.

- Para resolver este punto, es vital tener presente a que digitos del código ASCCI pertenecen su respestiva vocal minúscula, averiguando en internet encontre los siguientes códigos:

    97 = a
    101 = e
    105 = i
    111 = o
    117= u

Ya teniendo presente esto, se estructura un comando que le permita al usuario saber el número que ingrese del código ASCII pertenece a alguna vocal minúscula, o en caso contaririo, enfatizar que no, El comando seria el siguiente

```

#Iniciar porque todos los inicios tienen un inicio xd
n: int
n=int(input("Ingrese un numerito, rey/reina:"))

#Iniciamos lo bueno >:)
if n == 97:
    print ("Le cuento mor, su numerito SI hace parte de una vocal minúscula en condigo ASCII. Es la vocal a")
elif n == 101:
    print("Le cuento mor, su numerito SI hace parte de una vocal minúscula en condigo ASCII. Es la vocal e")
elif n == 105:
    print("Le cuento mor, su numerito SI hace parte de una vocal minúscula en condigo ASCII. Es la vocal i")
elif n == 111:
    print("Le cuento mor, su numerito SI hace parte de una vocal minúscula en condigo ASCII. Es la vocal o")
elif n == 117:
    print("Le cuento mor, su numerito SI hace parte de una vocal minúscula en condigo ASCII. Es la vocal u")
else:
    print("F mor, tu numerito no hace parte de una vocal minúscula en codigo ASCII")

# Y breves

```
```
Ejemplito ahi de chill:

Ingrese un numerito, rey/reina: 
n: 2
F mor, tu numerito no hace parte de una vocal minúscula en codigo ASCII
```


## Punto 2

Dada una cadena de longitud 1, determine si el código ASCII de primera letra de la cadena es par o no.

Para resolver esto, se le pide al usuario que ingrese cualquier caracter sabiendo de antemano que en primera instancia da igual a 1. Despues de eso toca colocar los condicionales de % y ord (ya que es el que nos permite traducirse en el un código ASCII para asi tener presente si nuestra primera letra es par o no

```


palabra : str
palabra = input("Ingrese un solo caracter unicamente: ")
codigo_ascii = ord(palabra)

if codigo_ascii % 2 == 0:
    print("El código ASCII del caracter ingresado es par")
    print(codigo_ascii)
else:
    print("el código ASCII del caracter ingresado es impar")
    print(codigo_ascii)

```


## Punto 3

Dado un carácter, construya un programa en Python para determinar si el carácter es un dígito o no.

```
print("Vamo a ve si el caracter que colocas es digito o nel")
n: float
n: str
n=float(input("Ingrese unicamente un solo caracter, el que quieras bebe: "))

if (n>=0 and n<=9):
    print("El caracter que colocaste es un dígito")
else:
    n:str == print("El caracter que colocaste NO es un dígito")

```


