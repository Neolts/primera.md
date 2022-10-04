### 1 Notas de clase ###
x= 10
print(x":",id(x)

y=10
print(y,":",id(y))

*Ambos estan guardados o localizados en la misma direccion de memoria.
//////////////////////////////////////////////////////////////////////

### 2 Notas de clase ###

*hints: Asignar un dato tentativo de una variable.
Ejemplo:
x=10 
print(x,":",id(x))

*El que el codigo sea dinamico tiene consecuencias en el codigo.

*def: Se usa para definir una funcion,debe esa definida antes de usarse.
Ejemplo:

def mensaje(x):
print("Dentro de la funcion",x,id(x)) 

%%"Hola mundo"
%%int("Fuera de la funcion",x,id(x))

%%mensaje(x)

**Ambos tienen la misma direccion.

**Scope: El espacio donde una variable tiene predeterminado valor.
++Codigo
def mensaje (x):
print("Dentro de la funcion",x,id(x))
if__name__="__main__":
mensaje("Hola mundo")

def saludo (sal:str,nombre:str)
print(sal,nombre)

if__name__=="__main__":
saludos("Buenos dias","Alex")

////

def calcula(nombre:str,años:int):
edad=2022-años
print:("Hola",nombre,"tienes",edad,"años")
if__name__=="__main__":
calcula("Alex",1971)

*imprime: Hola Alex tienes 51 años

////

def calcular_edad(a_actual:int,a_nacimiento:int)

def saludo(nombre:str,edad:int):
print("Hola",nombre,"tienes",edad,"años")

if __name__=="__main__"
saludo("Alex";calcular_edad(2022,2003))

edad=calcular_edad(2022,2003)
saludo("fer",edad)

*Crear utileria.py:
def mensaje(msg:str):
print(msg)

mensaje("Hola ICI")

import utilerias as util
*importar una utileria con un alias diferente

////

*Codigos de actividades

suma.py
def suma(n:int,a:int):
n=n+a
return n

resta.py
def resta(n:int,a:int):
n=n-a
return n

multip.py
def multi(n:int,a:int):
n=n*a
return n

divi.py
def div(n:int,a:int):
n=n/a
return n

cuad.py
def sqr(n:int,a:int):
n=n*n
return n

////

*Interpolacion de cadenas
lista= ["uno","dos","tres","tres"]
msg_numeros=f"numeros;(tupla_numeros)
print(msg_numeros)    
**imprime: Numeros('uno','dos','tres','tres')

dos= f"Numero:(dict,numeros("1"))
print(dos)
**imprime: Numero: 1

def mensaje(name:str,a_actual:int,a_nac:int)->str;
return f"Hola(name) tienes (a_actual-a_nac)"
print(mensaje("Alex",2022,1995))
**imprime: Hola Alex tienes 27


/////////////////////////////////////////////////////////////////////



