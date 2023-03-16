# Taller 1 🦖
<details><summary>Logo</summary><p>
<div align='center'>
<figure> <img src="https://i.postimg.cc/zB4xj8YL/324036197-911982026745761-7248675058037719255-n.jpg" alt="" width="400" height="auto"/></br>
<figcaption><b></b></figcaption></figure>
</div>
</p></details><br>
Que hay de nuevo prograsaurio, ya sabes que quedamos pocos de nosotros pero mientras existamos realizaremos repos a la vieja escuela prehistorica asi que empecemos. 

Como todo programador prehistorico empecemos con un chiste:
<details><summary>Preparense para el super chiste...</summary><p>
<div align='center'>
<figure> <img src="https://i.postimg.cc/QCNB9WHh/FSk-Xm9-HWUAEav-Cf.jpg" alt="" width="400" height="auto"/></br>
<figcaption><b></b></figcaption></figure>
</div>
</p></details><br>

## Punto 1
Realice el quiz Python Beginner Quiz (20 preguntas) y adjunte pantallazo con el resultado (mínimo 90% bien).

##### Prograsauria Industrial (Gabriella Ballesteros)
[![Captura-de-pantalla-2023-03-14-222021.png](https://i.postimg.cc/yWCkWScY/Captura-de-pantalla-2023-03-14-222021.png)](https://postimg.cc/LgvHb5xr)

##### Prograsaurio Electrico (Santiago Linares)
[![Captura-de-pantalla-2023-03-14-221934.png](https://i.postimg.cc/mDrMGMNv/Captura-de-pantalla-2023-03-14-221934.png)](https://postimg.cc/VS35qJhg)

##### Prograsaurio Quimico (Santiago Guaqueta)
[![Captura-de-pantalla-2023-03-14-161556.png](https://i.postimg.cc/8PnP1YGy/Captura-de-pantalla-2023-03-14-161556.png)](https://postimg.cc/GHG1KqHY)

## Punto 2
Realice un programa que lea tres números reales y determine cuál es el mayor.

Se soluciono de la siguiente manera como pide tres numero colocamos 3 variables en este caso x,y,z  como nos pidio reales deben ser flotantes despues ponemos nuestras condiciones para que se cumpla lo que se pidio. Por ultimo despues de haber programado todo probamos el codigo y listo. Pico y pala meu

``` python
#Ejercicio 2
# Colocamos nuestras variables
x=float(input("primer numero ="))
y=float(input("segundo numero ="))
z=float(input("tercer numero ="))
print("el numero mayor es:")
# Colocamos nuestros condicionales necesarios
if x>y and x>z:
    print ( x )
elif y>x and y>z :
    print ( y )
else :
    print (z)
```
[![Captura-de-pantalla-2023-03-14-163201.png](https://i.postimg.cc/HxWf8p4b/Captura-de-pantalla-2023-03-14-163201.png)](https://postimg.cc/bGM6Kf5v)

## Punto 3

Realice un programa que lea un número enteros y determine si es par o impar.

Primero que todo definimos nuestra variable n, como entero, luego generamos un input para que el usuario digite el numero que quiera evaluar, utilizando un condicional, determinamos que si el coeficiente es igual a 0, cuando dividimos en 2 el número, este número es par y si no, no lo es, esto exeptuando el número 2. Y finalmente imprimimos el resultado dado

``` python 
## Realice un programa que lea un número enteros y determine si es par o impar.
n:int
n= int(input("ingrese el número"))
if n % 2 == 0 or n==2:
   print("el número es par")
else:
   print("el número es impar")
```
[![Captura-de-pantalla-2023-03-15-172149.png](https://i.postimg.cc/YS2HYft4/Captura-de-pantalla-2023-03-15-172149.png)](https://postimg.cc/BjzkGFLs)

## Punto 4

Realice un programa que lea dos números reales y determine si el primero es múltiplo del segundo.

Colocamos tres variables que deben ser flotantes debido a que nos dice reales excepto la variable n que es x%y ya explicamos porque, después colocamos nuestras condiciones sabemos que un número es múltiplo o no si el residuo de su división da 0 por esta razón colocamos que la variable n=x%y ya que en el condicional debería ir que es múltiplo si n==0 despues ya probamos el codigo y listo. Pico y pala meu.
``` python 
#Ejercicio 4
# Colocamos las variables
x=int(input("primer numero ="))
y=int(input("segundo numero ="))
n = x % y
# Colocamos los condicionales necesarios
if n == 0 :
    print ("el numero ", x , "es multiplo de " , y ) 
else :
    print ("el numero ", x , "No es multiplo de " , y)
```
[![Captura-de-pantalla-2023-03-14-165324.png](https://i.postimg.cc/8zNQgBJy/Captura-de-pantalla-2023-03-14-165324.png)](https://postimg.cc/dLHS8C9d)

[![Diagrama-sin-t-tulo-drawio.png](https://i.postimg.cc/XvYRpjgd/Diagrama-sin-t-tulo-drawio.png)](https://postimg.cc/hXNyYq6t)

## Punto 5

Realice un programa que lea tres números reales y determine si la suma de los dos primeros es mayor, menor o igual que el tercer número.

Para esto definimos 3 variables como flotantes y generamos el input para digitar los tres numero, y haciendo uso de los condicionales,  evaluamos que si, la primera variable mas la segunda es mayos que la tercera, imprimios que la suma es mayor que el tercer número, por otro lado si la suma entre las dos primeras es menor que el tercer numero, imprimimos que la suma es menor, y finalmente si las suma de los numero es igual al tercero, imprimimos el texto que nos diga que es igual

``` python 
a:float
b:float
c:float
a= float(input("Ingrese el primer número"))
b= float(input("Ingrese el segundo número"))
c= float(input("ingrese el tercer número"))
if a+b>c:
  print("el resultado entre la suma de "+str(a)+" y "+str(b)+" es mayor que " +str(c))
elif a+b<c:
  print("el resultado entre la suma de "+str(a)+" y "+str(b)+" es menor que " +str(c))
elif a+b==c:
  print("el resultado entre la suma de "+str(a)+" y "+str(b)+" es igual que " +str(c))
```
[![Captura-de-pantalla-2023-03-15-172531.png](https://i.postimg.cc/rs1nf3Jq/Captura-de-pantalla-2023-03-15-172531.png)](https://postimg.cc/ZvqxRf2Q)
## Punto 6

Escriba un programa que solicite al usuario una letra y determine si es una vocal o una consonante

Colocamos nuestra variable x que pida al lector que ponga una letra después ponemos nuestras condiciones en la cual decimos que si x es una vocal osea a e i o u,para eso utilizamos if x==”a” as con todos y para decir que puede ser cualquiera se utiliza or. Por ultimo despues de poner nuestro if y elif y colocar que queremos que imprima lo probamos y listo. Pico y pala meu
``` python
#Ejercicio 6
# Colocamos nuestra variable
x=input("Escriba una letra=")

x=x.lower() # Utilizamos lower para que convierta todo en minusculas
# Colocamos nuestros condicionales 
if x=="a" or x=="e" or x=="i" or x=="o" or x=="u" :
    print("Es una vocal")
else:
    print ("Es una consonante")
```
[![Captura-de-pantalla-2023-03-14-164315.png](https://i.postimg.cc/d3j62ds1/Captura-de-pantalla-2023-03-14-164315.png)](https://postimg.cc/64TCw8GJ)
## Punto 7

Escriba un programa que pida 5 números reales y calcule las siguientes operaciones:
- El promedio
- La mediana
- El promedio multiplicativo (multilplica todos y luego calcula la raíz de la cantidad de operandos)
- Ordenar los números de forma ascendente
- Ordenar los números de forma descendente
- La potencia del mayor número elevado al menor número
La raíz cúbica del menor número
``` python
#Escriba un programa que pida 5 números reales y calcule las siguientes operaciones:
n1 = int(input("ingrese un número: "))
n2 = int(input("ingrese un número: "))
n3 = int(input("ingrese un número: "))
n4 = int(input("ingrese un número: "))
n5 = int(input("ingrese un número: "))
#El promedio
prom = (n1+n2+n3+n4+n5)/5
print("1) el promedio de los números dados es: ",prom)
```
``` pyton
#La mediana
def num():
    if n1<n2 and n1<n3 and n1<n4 and n1<n5: #n1
        if n2<n3 and n2<n4 and n2<n5: #n1 n2
            if n3<n4 and n3<n5: #n1 n2 n3
                if n4<n5: #n1 n2 n3 n4
                    print(n1,n2,n3,n4,n5) #n1 n2 n3 n4 n5
                elif n5<n4: #n1 n2 n3 n5
                    print(n1,n2,n3,n5,n4) #n1 n2 n3 n5 n4
            elif n4<n3 and n4<n5: #n1 n2 n4
                if n3<n5: #n1 n2 n4 n3 n5
                    print(n1,n2,n4,n3,n5)
                elif n5<n3: #n1 n2 n4 n5 n3
                    print(n1,n2,n4,n5,n3)
            elif n5<n3 and n5<n4: #n1 n2 n5
                if n3<n4: #n1 n2 n5 n3 n4
                    print(n1,n2,n5,n3,n4)
                elif n4<n3: #n1 n2 n5 n4 n3
                    print(n1,n2,n5,n4,n3)
        elif n3<n2 and n3<n4 and n3<n5: #n1 n3
            if n2<n4 and n2<n5: #n1 n3 n2
                if n4<n5: #n1 n3 n2 n4 n5
                    print(n1,n3,n2,n4,n5)
                elif n5<n4: #n1 n3 n2 n5 n4
                    print(n1,n3,n2,n5,n4)
            elif n4<n2 and n4<n5: #n1 n3 n4
                if n2<n5: #n1 n3 n4 n2 n5
                    print(n1,n3,n4,n2,n5)
                elif n5<n2: #n1 n3 n4 n5 n2
                    print(n1,n3,n4,n5,n2)
            elif n5<n2 and n5<n4: #n1 n3 n5
                if n2<n4: #n1 n3 n5 n2 n4
                    print(n1,n3,n5,n2,n4)
                elif n4<n2: #n1 n3 n5 n4 n2
                    print(n1,n3,n5,n4,n2)
        elif n4<n2 and n4<n3 and n4<n5: #n1 n4
            if n2<n3 and n2<n5: #n1 n4 n2
                if n3<n5: #n1 n4 n2 n3 n5
                    print(n1,n4,n2,n3,n5)
                elif n5<n3: #n1 n4 n2 n5 n3
                    print(n1,n4,n2,n5,n3)
            elif n3<n2 and n3<n5: #n1 n4 n3
                if n2<n5:#n1 n4 n3 n2 n5
                    print(n1,n4,n3,n2,n5)
                elif n5<n2: #n1 n4 n3 n5 n2
                    print(n1,n4,n3,n5,n2)
            elif n5<n2 and n5<n3: #n1 n4 n5
                if n2<n3: #n1 n4 n5 n2 n3
                    print(n1,n4,n5,n2,n3)
                elif n3<n2: #n1 n4 n5 n3 n2
                    print(n1,n4,n5,n3,n2)
        elif n5<n2 and n5<n3 and n5<n4: #n1 n5
            if n2<n3 and n2<n4: #n1 n5 n2
                if n3<n4: #n1 n5 n2 n3 n4
                    print(n1,n5,n2,n3,n4)
                elif n4<n3: #n1 n5 n2 n4 n3
                    print(n1,n5,n2,n4,n3)
            elif n3<n2 and n3<n4: #n1 n5 n3
                if n2<n4:#n1 n5 n3 n2 n4
                    print(n1,n5,n3,n2,n4)
                elif n4<n2: #n1 n5 n3 n4 n2
                    print(n1,n5,n3,n4,n2)
            elif n4<n2 and n4<n3: #n1 n5 n4
                if n2<n3:#n1 n5 n4 n2 n3
                    print(n1,n5,n4,n2,n3)
                elif n3<n2:#n1 n5 n4 n3 n2
                    print(n1,n5,n4,n3,n2)
    elif n2<n1 and n2<n3 and n2<n4 and n2<n5: #n2
        if n1<n3 and n1<n4 and n1<n5: #n2 n1
            if n3<n4 and n3<n5: #n2 n1 n3
                if n4<n5: #n2 n1 n3 n4 n5
                    print(n2,n1,n3,n4,n5)
                elif n5<n4: #n2 n1 n3 n5 n4
                    print(n2,n1,n3,n5,n4)
            elif n4<n3 and n4<n5: #n2 n1 n4
                if n3<n5: #n2 n1 n4 n3 n5
                    print(n2,n1,n4,n3,n5)
                elif n5<n3: #n2 n1 n4 n5 n3
                    print(n2,n1,n4,n5,n3)
            elif n5<n3 and n5<n4: #n2 n1 n5
                if n3<n4: #n2 n1 5n n3 n4
                    print(n2,n1,n5,n3,n4)
                elif n4<n3: #n2 n1 n5 n4 n3
                    print(n2,n1,n5,n4,n3)
        elif n3<n1 and n3<n4 and n3<n5: #n2 n3
            if n1<n4 and n1<n5: #n2 n3 n1
                if n4<n5: #n2 n3 n1 n4 n5
                    print(n2,n3,n1,n4,n5)
                elif n5<n4: #n2 n3 n1 n5 n4
                    print(n2,n3,n1,n5,n4)
            elif n4<n1 and n4<n5: #n2 n3 n4
                if n1<n5: #n2 n3 n4 n1 n5
                    print(n2,n3,n4,n1,n5)
                elif n5<n1: #n2 n3 n4 n5 n1
                    print(n2,n3,n4,n5,n1)
            elif n5<n1 and n5<n4: #n2 n3 n5
                if n1<n4: #n2 n3 n5 n1 n4
                    print(n2,n3,n5,n1,n4)
                elif n4<n1: #n2 n3 n5 n4 n1
                    print(n2,n3,n5,n4,n1)
        elif n4<n1 and n4<n3 and n4<n5: #n2 n4
            if n1<n3 and n1<n5:#n2 n4 n1
                if n3<n5: #n2 n4 n1 n3 n5
                    print(n2,n4,n1,n3,n5)
                elif n5<n3: #n2 n4 n1 n5 n3
                    print(n2,n4,n1,n5,n3)
            elif n3<n1 and n3<n5: #n2 n4 n3
                if n1<n5: #n2 n4 n3 n1 n5
                    print(n2,n4,n3,n1,n5)
                elif n5<n1: #n2 n4 n3 n5 n1
                    print(n2,n4,n3,n5,n1)
            elif n5<n1 and n5<n3: #n2 n4 n5
                if n1<n3:#n2 n4 n5 n1 n3
                    print(n2,n4,n5,n1,n3)
                elif n3<n1: #n2 n4 n5 n3 n1
                    print(n2,n4,n5,n3,n1)
        elif n5<n1 and n5<n3 and n5<n4: #n2 n5
            if n1<n3 and n1<n4: #n2 n5 n1
                if n3<n4: #n2 n5 n1 n3 n4
                    print(n2,n5,n1,n3,n4)
                elif n4<n3: #n2 n5 n1 n4 n3
                    print(n2,n5,n1,n4,n3)
            elif n3<n1 and n3<n4: #n2 n5 n3
                if n1<n4: #n2 n5 n3 n1 n4
                    print(n2,n5,n3,n1,n4)
                elif n4<n1: #n2 n5 n3 n4 n1
                    print(n2,n5,n3,n4,n1)
            elif n4<n1 and n4<n3: #n2 n5 n4
                if n1<n3: #n2 n5 n4 n1 n3
                    print(n2,n5,n4,n1,n3)
                elif n3<n1: #n2 n5 n4 n3 n1
                    print(n2,n5,n4,n3,n1)
    elif n3<n1 and n3<n2 and n3<n4 and n3<n5:#n3
        if n1<n2 and n1<n4 and n1<n5: #n3 n1
            if n2<n4 and n2<n5: #n3 n1 n2
                if n4<n5: #n3 n1 n2 n4 n5
                    print(n3,n1,n2,n4,n5)
                elif n5<n4: #n3 n1 n2 n5 n4
                    print(n3,n1,n2,n5,n4)
            elif n4<n2 and n4<n5: #n3 n1 n4
                if n2<n5: #n3 n1 n4 n2 n5
                    print(n3,n1,n4,n2,n5)
                elif n5<n2: #n3 n1 n4 n5 n2
                    print(n3,n1,n4,n5,n2)
            elif n5<n2 and n5<n4: #n3 n1 n5
                if n2<n4: #n3 n1 n5 n2 n4
                    print(n3,n1,n5,n2,n4)
                elif n4<n2: #n3 n1 n5 n4 n2
                    print(n3,n1,n5,n4,n2)
        elif n2<n1 and n2<n4 and n2<n5: #n3 n2
            if n1<n4 and n1<n5: #n3 n2 n1
                if n4<n5: #n3 n2 n1 n4 n5
                    print(n3,n2,n1,n4,n5)
                elif n5<n4: #n3 n2 n1 n5 n4
                    print(n3,n2,n1,n5,n4)
            if n4<n1 and n4<n5: #n3 n2 n4
                if n1<n5: #n3 n2 n4 n1 n5
                    print(n3,n2,n4,n1,n5)
                elif n5<n1: #n3 n2 n4 n5 n1
                    print(n3,n2,n4,n5,n1)
            if n5<n1 and n5<n4: #n3 n2 n5
                if n1<n4: #n3 n2 n5 n1 n4
                    print(n3,n2,n5,n1,n4)
                elif n4<n1: #n3 n2 n5 n4 n1
                    print(n3,n2,n5,n4,n1)
        elif n4<n1 and n4<n2 and n4<n5: #n3 n4
            if n1<n2 and n1<n5: #n3 n4 n1
                if n2<n5: #n3 n4 n1 n2 n5
                    print(n3,n4,n1,n2,n5)
                elif n5<n2: #n3 n4 n1 n5 n2
                    print(n3,n4,n1,n5,n2)
            elif n2<n1 and n2<n5: #n3 n4 n2
                if n1<n5: #n3 n4 n2 n1 n5
                    print(n3,n4,n2,n1,n5)
                elif n5<n1: #n3 n4 n2 n5 n1
                    print(n3,n4,n2,n5,n1)
            elif n5<n1 and n5<n2: #n3 n4 n5
                if n1<n2: #n3 n4 n5 n1 n2
                    print(n3,n4,n5,n1,n2)
                elif n2<n1: #n3 n4 n5 n2 n1
                    print(n3,n4,n5,n2,n1)
        elif n5<n1 and n5<n2 and n5<n4: #n3 n5
            if n1<n2 and n1<n4: #n3 n5 n1
                if n2<n4: #n3 n5 n1 n2 n4
                    print(n3,n5,n1,n2,n4)
                elif n4<n2: #n3 n5 n1 n4 n2
                    print(n3,n5,n1,n4,n2)
            elif n2<n1 and n2<n4: #n3 n5 n2
                if n1<n4: #n3 n5 n2 n1 n4
                    print(n3,n5,n2,n1,n4)
                elif n4<n1: #n3 n5 n2 n4 n1
                    print(n3,n5,n2,n4,n1)
            elif n4<n1 and n4<n2: #n3 n5 n4
                if n1<n2: #n3 n5 n4 n1 n2
                    print(n3,n5,n4,n1,n2)
                elif n2<n1: #n3 n5 n4 n2 n1
                    print(n3,n5,n4,n2,n1)
    elif n4<n1 and n4<n2 and n4<n3 and n4<n5:#n4
        if n1<n2 and n1<n3 and n1<n5: #n4 n1
            if n2<n3 and n2<n5: #n4 n1 n2
                if n3<n5: #n4 n1 n2 n3 n5
                    print(n4,n1,n2,n3,n5)
                elif n5<n3: #n4 n1 n2 n5 n3
                    print(n4,n1,n2,n5,n3)
            elif n3<n2 and n3<n5: #n4 n1 n3
                if n2<n5: #n4 n1 n3 n2 n5
                    print(n4,n1,n3,n2,n5)
                elif n5<n2: #n4 n1 n3 n5 n2
                    print(n4,n1,n3,n5,n2)
            elif n5<n2 and n5<n3: #n4 n1 n5
                if n2<n3: #n4 n1 n5 n2 n3
                    print(n4,n1,n5,n2,n3)
                elif n3<n2: #n4 n1 n5 n3 n2
                    print(n4,n1,n5,n3,n2)
        elif n2<n1 and n2<n3 and n2<n5: #n4 n2
            if n1<n3 and n1<n5: #n4 n2 n1
                if n3<n5: #n4 n2 n1 n3 n5
                    print(n4,n2,n1,n3,n5)
                elif n5<n3: #n4 n2 n1 n5 n3
                    print(n4,n2,n1,n5,n3)
            elif n3<n1 and n3<n5: #n4 n2 n3
                if n1<n5: #n4 n2 n3 n1 n5
                    print(n4,n2,n3,n1,n5)
                elif n5<n1: #n4 n2 n3 n5 n1
                    print(n4,n2,n3,n5,n1)
            elif n5<n1 and n5<n3: #n4 n2 n5
                if n1<n3: #n4 n2 n5 n1 n3
                    print(n4,n2,n5,n1,n3)
                elif n3<n1: #n4 n2 n5 n3 n1
                    print(n4,n2,n5,n3,n1)
        elif n3<n1 and n3<n2 and n3<n5: #n4 n3
            if n1<n2 and n1<n5: #n4 n3 n1
                if n2<n5: #n4 n3 n1 n2 n5
                    print(n4,n3,n1,n2,n5)
                elif n5<n2: #n4 n3 n1 n5 n2
                    print(n4,n3,n1,n5,n2)
            elif n2<n1 and n2<n5: #n4 n3 n2
                if n1<n5: #n4 n3 n2 n1 n5
                    print(n4,n3,n2,n1,n5)
                elif n5<n1: #n4 n3 n2 n5 n1
                    print(n4,n3,n2,n5,n1)
            elif n5<n1 and n5<n2: #n4 n3 n5
                if n1<n2: #n4 n3 n5 n1 n2
                    print(n4,n3,n5,n1,n2)
                elif n2<n1: #n4 n3 n5 n2 n1
                    print(n4,n3,n5,n2,n1)
        elif n5<n1 and n5<n2 and n5<n3: #n4 n5
            if n1<n2 and n1<n3: #n4 n5 n1
                if n2<n3: #n4 n5 n1 n2 n3
                    print(n4,n5,n1,n2,n3)
                elif n3<n2: #n4 n5 n1 n3 n2
                    print(n4,n5,n1,n3,n2)
            elif n2<n1 and n2<n3: #n4 n5 n2
                if n1<n3: #n4 n5 n2 n1 n3
                    print(n4,n5,n2,n1,n3)
                elif n3<n1: #n4 n5 n2 n3 n1
                    print(n4,n5,n2,n3,n1)
            elif n3<n1 and n3<n2: #n4 n5 n3
                if n1<n2: #n4 n5 n3 n1 n2
                    print(n4,n5,n3,n1,n2)
                elif n2<n1: #n4 n5 n3 n2 n1
                    print(n4,n5,n3,n2,n1)
    elif n5<n1 and n5<n2 and n5<n3 and n5<n4: #n5
        if n1<n2 and n1<n3 and n1<n4: #n5 n1
            if n2<n3 and n2<n4: #n5 n1 n2
                if n3<n4: #n5 n1 n2 n3 n4
                    print(n5,n1,n2,n3,n4)
                elif n4<n3: #n5 n1 n2 n4 n3
                    print(n5,n1,n2,n4,n3)
            elif n3<n2 and n3<n4: #n5 n1 n3
                if n2<n4: #n5 n1 n3 n2 n4
                    print(n5,n1,n3,n2,n4)
                elif n4<n2: #n5 n1 n3 n4 n2
                    print(n5,n1,n3,n4,n2)
            elif n4<n2 and n4<n3: #n5 n1 n4
                if n2<n3: #n5 n1 n4 n2 n3
                    print(n5,n1,n4,n2,n3)
                elif n3<n2: #n5 n1 n4 n3 n2
                    print(n5,n1,n4,n3,n2)
        elif n2<n1 and n2<n3 and n2<n4: #n5 n2
            if n1<n3 and n1<n4:#n5 n2 n1
                if n3<n4: #n5 n2 n1 n3 n4
                    print(n5,n2,n1,n3,n4)
                elif n4<n3: #n5 n2 n1 n4 n3
                    print(n5,n2,n1,n4,n3)
            elif n3<n1 and n3<n4: #n5 n2 n3
                if n1<n4: #n5 n2 n3 n1 n4
                    print(n5,n2,n3,n1,n4)
                elif n4<n1: #n5 n2 n3 n4 n1
                    print(n5,n2,n3,n4,n1)
            elif n4<n1 and n4<n3: #n5 n2 n4
                if n1<n3: #n5 n2 n4 n1 n3
                    print(n5,n2,n4,n1,n3)
                elif n3<n1: #n5 n2 n4 n3 n1
                    print(n5,n2,n4,n3,n1)
        elif n3<n1 and n3<n2 and n3<n4: #n5 n3
            if n1<n2 and n1<n4: #n5 n3 n1
                if n2<n4: #n5 n3 n1 n2 n4
                    print(n5,n3,n1,n2,n4)
                elif n4<n2: #n5 n3 n1 n4 n2
                    print(n5,n3,n1,n4,n2)
            elif n2<n1 and n2<n4: #n5 n3 n2
                if n1<n4: #n5 n3 n2 n1 n4
                    print(n5,n3,n2,n1,n4)
                elif n4<n1: #n5 n3 n2 n4 n1
                    print(n5,n3,n2,n4,n1)
            elif n4<n1 and n4<n2: #n5 n3 n4
                if n1<n2: #n5 n3 n4 n1 n2
                    print(n5,n3,n4,n1,n2)
                elif n2<n1: #n5 n3 n4 n2 n1
                    print(n5,n3,n4,n2,n1)
        elif n4<n1 and n4<n2 and n4<n3: #n5 n4
            if n1<n2 and n1<n3: #n5 n4 n1
                if n2<n3: #n5 n4 n1 n2 n3
                    print(n5,n4,n1,n2,n3)
                elif n3<n2: #n5 n4 n1 n3 n2
                    print(n5,n4,n1,n3,n2)
            elif n2<n1 and n2<n3: #n5 n4 n2
                if n1<n3: #n5 n4 n2 n1 n3
                    print(n5,n4,n2,n1,n3)
                elif n3<n1: #n5 n4 n2 n3 n1
                    print(n5,n4,n2,n3,n1)
            elif n3<n1 and n3<n2: #n5 n4 n3
                if n1<n2: #n5 n4 n3 n1 n2
                    print(n5,n4,n3,n1,n2)
                elif n2<n1: #n5 n4 n3 n2 n1
                    print(n5,n4,n3,n2,n1)
```
``` python
print("2) La mediana de los números dados es el número de la mitad ",num(m3))
#El promedio multiplicativo (multiplica todos y luego calcula la raíz de la cantidad de operandos)
prom_mul = (n1*n2*n3*n4*n5)**5
print("3) El promedio multiplicativo de los números dados es: ",prom_mul)
#Ordenar los números de forma ascendente
print("4) Los números organizados de menor a mayor se ve de la siguiente manera: ",num())
#Ordenar los números de forma descendente
def num_inv():
    if n1<n2 and n1<n3 and n1<n4 and n1<n5: #n1
        if n2<n3 and n2<n4 and n2<n5: #n1 n2
            if n3<n4 and n3<n5: #n1 n2 n3
                if n4<n5: #n1 n2 n3 n4
                    print(n5,n4,n3,n2,n1) #n1 n2 n3 n4 n5
                elif n5<n4: #n1 n2 n3 n5
                    print(n4,n5,n3,n2,n1) #n1 n2 n3 n5 n4
            elif n4<n3 and n4<n5: #n1 n2 n4
                if n3<n5: #n1 n2 n4 n3 n5
                    print(n5,n3,n4,n2,n1)
                elif n5<n3: #n1 n2 n4 n5 n3
                    print(n3,n5,n4,n2,n1)
            elif n5<n3 and n5<n4: #n1 n2 n5
                if n3<n4: #n1 n2 n5 n3 n4
                    print(n4,n3,n5,n2,n1)
                elif n4<n3: #n1 n2 n5 n4 n3
                    print(n3,n4,n5,n2,n1)
        elif n3<n2 and n3<n4 and n3<n5: #n1 n3
            if n2<n4 and n2<n5: #n1 n3 n2
                if n4<n5: #n1 n3 n2 n4 n5
                    print(n5,n4,n2,n3,n1)
                elif n5<n4: #n1 n3 n2 n5 n4
                    print(n4,n5,n2,n3,n1)
            elif n4<n2 and n4<n5: #n1 n3 n4
                if n2<n5: #n1 n3 n4 n2 n5
                    print(n5,n2,n4,n3,n1)
                elif n5<n2: #n1 n3 n4 n5 n2
                    print(n2,n5,n4,n3,n1)
            elif n5<n2 and n5<n4: #n1 n3 n5
                if n2<n4: #n1 n3 n5 n2 n4
                    print(n4,n2,n5,n2,n1)
                elif n4<n2: #n1 n3 n5 n4 n2
                    print(n2,n4,n5,n3,n1)
        elif n4<n2 and n4<n3 and n4<n5: #n1 n4
            if n2<n3 and n2<n5: #n1 n4 n2
                if n3<n5: #n1 n4 n2 n3 n5
                    print(n5,n3,n2,n4,n1)
                elif n5<n3: #n1 n4 n2 n5 n3
                    print(n3,n5,n2,n4,n1)
            elif n3<n2 and n3<n5: #n1 n4 n3
                if n2<n5:#n1 n4 n3 n2 n5
                    print(n5,n2,n3,n4,n1)
                elif n5<n2: #n1 n4 n3 n5 n2
                    print(n2,n5,n3,n4,n1)
            elif n5<n2 and n5<n3: #n1 n4 n5
                if n2<n3: #n1 n4 n5 n2 n3
                    print(n3,n2,n5,n4,n1)
                elif n3<n2: #n1 n4 n5 n3 n2
                    print(n2,n3,n5,n4,n1)
        elif n5<n2 and n5<n3 and n5<n4: #n1 n5
            if n2<n3 and n2<n4: #n1 n5 n2
                if n3<n4: #n1 n5 n2 n3 n4
                    print(n4,n3,n2,n5,n1)
                elif n4<n3: #n1 n5 n2 n4 n3
                    print(n3,n4,n2,n5,n1)
            elif n3<n2 and n3<n4: #n1 n5 n3
                if n2<n4:#n1 n5 n3 n2 n4
                    print(n4,n3,n3,n5,n1)
                elif n4<n2: #n1 n5 n3 n4 n2
                    print(n2,n4,n3,n5,n1)
            elif n4<n2 and n4<n3: #n1 n5 n4
                if n2<n3:#n1 n5 n4 n2 n3
                    print(n3,n2,n4,n5,n1)
                elif n3<n2:#n1 n5 n4 n3 n2
                    print(n2,n3,n4,n5,n1)
    elif n2<n1 and n2<n3 and n2<n4 and n2<n5: #n2
        if n1<n3 and n1<n4 and n1<n5: #n2 n1
            if n3<n4 and n3<n5: #n2 n1 n3
                if n4<n5: #n2 n1 n3 n4 n5
                    print(n5,n4,n3,n1,n2)
                elif n5<n4: #n2 n1 n3 n5 n4
                    print(n4,n5,n3,n1,n2)
            elif n4<n3 and n4<n5: #n2 n1 n4
                if n3<n5: #n2 n1 n4 n3 n5
                    print(n5,n3,n4,n1,n2)
                elif n5<n3: #n2 n1 n4 n5 n3
                    print(n3,n5,n4,n1,n2)
            elif n5<n3 and n5<n4: #n2 n1 n5
                if n3<n4: #n2 n1 5n n3 n4
                    print(n4,n3,n5,n1,n2)
                elif n4<n3: #n2 n1 n5 n4 n3
                    print(n3,n4,n5,n1,n2)
        elif n3<n1 and n3<n4 and n3<n5: #n2 n3
            if n1<n4 and n1<n5: #n2 n3 n1
                if n4<n5: #n2 n3 n1 n4 n5
                    print(n5,n4,n1,n3,n2)
                elif n5<n4: #n2 n3 n1 n5 n4
                    print(n4,n5,n1,n3,n2)
            elif n4<n1 and n4<n5: #n2 n3 n4
                if n1<n5: #n2 n3 n4 n1 n5
                    print(n5,n1,n4,n3,n2)
                elif n5<n1: #n2 n3 n4 n5 n1
                    print(n1,n5,n4,n3,n2)
            elif n5<n1 and n5<n4: #n2 n3 n5
                if n1<n4: #n2 n3 n5 n1 n4
                    print(n4,n1,n5,n3,n2)
                elif n4<n1: #n2 n3 n5 n4 n1
                    print(n1,n4,n5,n3,n2)
        elif n4<n1 and n4<n3 and n4<n5: #n2 n4
            if n1<n3 and n1<n5:#n2 n4 n1
                if n3<n5: #n2 n4 n1 n3 n5
                    print(n5,n3,n1,n4,n2)
                elif n5<n3: #n2 n4 n1 n5 n3
                    print(n3,n5,n1,n4,n2)
            elif n3<n1 and n3<n5: #n2 n4 n3
                if n1<n5: #n2 n4 n3 n1 n5
                    print(n5,n1,n3,n4,n2)
                elif n5<n1: #n2 n4 n3 n5 n1
                    print(n1,n5,n3,n4,n2)
            elif n5<n1 and n5<n3: #n2 n4 n5
                if n1<n3:#n2 n4 n5 n1 n3
                    print(n3,n1,n5,n4,n2)
                elif n3<n1: #n2 n4 n5 n3 n1
                    print(n1,n3,n5,n4,n2)
        elif n5<n1 and n5<n3 and n5<n4: #n2 n5
            if n1<n3 and n1<n4: #n2 n5 n1
                if n3<n4: #n2 n5 n1 n3 n4
                    print(n4,n3,n1,n5,n2)
                elif n4<n3: #n2 n5 n1 n4 n3
                    print(n3,n4,n1,n5,n2)
            elif n3<n1 and n3<n4: #n2 n5 n3
                if n1<n4: #n2 n5 n3 n1 n4
                    print(n4,n1,n3,n5,n2)
                elif n4<n1: #n2 n5 n3 n4 n1
                    print(n1,n4,n3,n5,n2)
            elif n4<n1 and n4<n3: #n2 n5 n4
                if n1<n3: #n2 n5 n4 n1 n3
                    print(n3,n1,n4,n5,n2)
                elif n3<n1: #n2 n5 n4 n3 n1
                    print(n1,n3,n4,n5,n2)
    elif n3<n1 and n3<n2 and n3<n4 and n3<n5:#n3
        if n1<n2 and n1<n4 and n1<n5: #n3 n1
            if n2<n4 and n2<n5: #n3 n1 n2
                if n4<n5: #n3 n1 n2 n4 n5
                    print(n5,n4,n2,n1,n3)
                elif n5<n4: #n3 n1 n2 n5 n4
                    print(n4,n5,n2,n1,n3)
            elif n4<n2 and n4<n5: #n3 n1 n4
                if n2<n5: #n3 n1 n4 n2 n5
                    print(n5,n2,n4,n1,n3)
                elif n5<n2: #n3 n1 n4 n5 n2
                    print(n2,n5,n4,n1,n3)
            elif n5<n2 and n5<n4: #n3 n1 n5
                if n2<n4: #n3 n1 n5 n2 n4
                    print(n4,n2,n5,n1,n3)
                elif n4<n2: #n3 n1 n5 n4 n2
                    print(n2,n4,n5,n1,n3)
        elif n2<n1 and n2<n4 and n2<n5: #n3 n2
            if n1<n4 and n1<n5: #n3 n2 n1
                if n4<n5: #n3 n2 n1 n4 n5
                    print(n5,n4,n1,n2,n3)
                elif n5<n4: #n3 n2 n1 n5 n4
                    print(n4,n5,n1,n2,n3)
            if n4<n1 and n4<n5: #n3 n2 n4
                if n1<n5: #n3 n2 n4 n1 n5
                    print(n5,n1,n4,n2,n3)
                elif n5<n1: #n3 n2 n4 n5 n1
                    print(n1,n5,n4,n2,n3)
            if n5<n1 and n5<n4: #n3 n2 n5
                if n1<n4: #n3 n2 n5 n1 n4
                    print(n4,n1,n5,n2,n3)
                elif n4<n1: #n3 n2 n5 n4 n1
                    print(n1,n4,n5,n2,n3)
        elif n4<n1 and n4<n2 and n4<n5: #n3 n4
            if n1<n2 and n1<n5: #n3 n4 n1
                if n2<n5: #n3 n4 n1 n2 n5
                    print(n5,n2,n1,n4,n3)
                elif n5<n2: #n3 n4 n1 n5 n2
                    print(n2,n5,n1,n4,n3)
            elif n2<n1 and n2<n5: #n3 n4 n2
                if n1<n5: #n3 n4 n2 n1 n5
                    print(n5,n1,n2,n4,n3)
                elif n5<n1: #n3 n4 n2 n5 n1
                    print(n1,n5,n2,n4,n3)
            elif n5<n1 and n5<n2: #n3 n4 n5
                if n1<n2: #n3 n4 n5 n1 n2
                    print(n2,n1,n5,n4,n3)
                elif n2<n1: #n3 n4 n5 n2 n1
                    print(n1,n2,n5,n4,n3)
        elif n5<n1 and n5<n2 and n5<n4: #n3 n5
            if n1<n2 and n1<n4: #n3 n5 n1
                if n2<n4: #n3 n5 n1 n2 n4
                    print(n4,n2,n1,n5,n3)
                elif n4<n2: #n3 n5 n1 n4 n2
                    print(n3,n4,n1,n5,n3)
            elif n2<n1 and n2<n4: #n3 n5 n2
                if n1<n4: #n3 n5 n2 n1 n4
                    print(n4,n1,n2,n5,n3)
                elif n4<n1: #n3 n5 n2 n4 n1
                    print(n1,n4,n2,n5,n3)
            elif n4<n1 and n4<n2: #n3 n5 n4
                if n1<n2: #n3 n5 n4 n1 n2
                    print(n2,n1,n4,n5,n3)
                elif n2<n1: #n3 n5 n4 n2 n1
                    print(n1,n2,n4,n5,n3)
    elif n4<n1 and n4<n2 and n4<n3 and n4<n5:#n4
        if n1<n2 and n1<n3 and n1<n5: #n4 n1
            if n2<n3 and n2<n5: #n4 n1 n2
                if n3<n5: #n4 n1 n2 n3 n5
                    print(n5,n3,n2,n1,n4)
                elif n5<n3: #n4 n1 n2 n5 n3
                    print(n3,n5,n2,n1,n4)
            elif n3<n2 and n3<n5: #n4 n1 n3
                if n2<n5: #n4 n1 n3 n2 n5
                    print(n5,n2,n3,n1,n4)
                elif n5<n2: #n4 n1 n3 n5 n2
                    print(n2,n5,n3,n1,n4)
            elif n5<n2 and n5<n3: #n4 n1 n5
                if n2<n3: #n4 n1 n5 n2 n3
                    print(n3,n2,n5,n1,n4)
                elif n3<n2: #n4 n1 n5 n3 n2
                    print(n2,n3,n5,n1,n4)
        elif n2<n1 and n2<n3 and n2<n5: #n4 n2
            if n1<n3 and n1<n5: #n4 n2 n1
                if n3<n5: #n4 n2 n1 n3 n5
                    print(n5,n3,n1,n2,n4)
                elif n5<n3: #n4 n2 n1 n5 n3
                    print(n3,n5,n1,n2,n4)
            elif n3<n1 and n3<n5: #n4 n2 n3
                if n1<n5: #n4 n2 n3 n1 n5
                    print(n1,n5,n3,n2,n4)
                elif n5<n1: #n4 n2 n3 n5 n1
                    print(n1,n5,n3,n2,n4)
            elif n5<n1 and n5<n3: #n4 n2 n5
                if n1<n3: #n4 n2 n5 n1 n3
                    print(n3,n1,n5,n2,n4)
                elif n3<n1: #n4 n2 n5 n3 n1
                    print(n1,n3,n5,n2,n4)
        elif n3<n1 and n3<n2 and n3<n5: #n4 n3
            if n1<n2 and n1<n5: #n4 n3 n1
                if n2<n5: #n4 n3 n1 n2 n5
                    print(n5,n2,n1,n3,n4)
                elif n5<n2: #n4 n3 n1 n5 n2
                    print(n2,n5,n1,n3,n4)
            elif n2<n1 and n2<n5: #n4 n3 n2
                if n1<n5: #n4 n3 n2 n1 n5
                    print(n5,n1,n2,n3,n4)
                elif n5<n1: #n4 n3 n2 n5 n1
                    print(n1,n5,n2,n3,n4)
            elif n5<n1 and n5<n2: #n4 n3 n5
                if n1<n2: #n4 n3 n5 n1 n2
                    print(n2,n1,n5,n3,n4)
                elif n2<n1: #n4 n3 n5 n2 n1
                    print(n1,n2,n5,n3,n4)
        elif n5<n1 and n5<n2 and n5<n3: #n4 n5
            if n1<n2 and n1<n3: #n4 n5 n1
                if n2<n3: #n4 n5 n1 n2 n3
                    print(n3,n2,n1,n5,n4)
                elif n3<n2: #n4 n5 n1 n3 n2
                    print(n2,n3,n1,n5,n4)
            elif n2<n1 and n2<n3: #n4 n5 n2
                if n1<n3: #n4 n5 n2 n1 n3
                    print(n3,n2,n2,n5,n4)
                elif n3<n1: #n4 n5 n2 n3 n1
                    print(n1,n3,n2,n5,n4)
            elif n3<n1 and n3<n2: #n4 n5 n3
                if n1<n2: #n4 n5 n3 n1 n2
                    print(n2,n1,n3,n5,n4)
                elif n2<n1: #n4 n5 n3 n2 n1
                    print(n1,n2,n3,n5,n4)
    elif n5<n1 and n5<n2 and n5<n3 and n5<n4: #n5
        if n1<n2 and n1<n3 and n1<n4: #n5 n1
            if n2<n3 and n2<n4: #n5 n1 n2
                if n3<n4: #n5 n1 n2 n3 n4
                    print(n4,n3,n2,n1,n5)
                elif n4<n3: #n5 n1 n2 n4 n3
                    print(n3,n4,n2,n1,n5)
            elif n3<n2 and n3<n4: #n5 n1 n3
                if n2<n4: #n5 n1 n3 n2 n4
                    print(n4,n2,n3,n1,n5)
                elif n4<n2: #n5 n1 n3 n4 n2
                    print(n2,n4,n3,n1,n5)
            elif n4<n2 and n4<n3: #n5 n1 n4
                if n2<n3: #n5 n1 n4 n2 n3
                    print(n3,n2,n4,n1,n5)
                elif n3<n2: #n5 n1 n4 n3 n2
                    print(n2,n3,n4,n1,n5)
        elif n2<n1 and n2<n3 and n2<n4: #n5 n2
            if n1<n3 and n1<n4:#n5 n2 n1
                if n3<n4: #n5 n2 n1 n3 n4
                    print(n4,n3,n1,n2,n5)
                elif n4<n3: #n5 n2 n1 n4 n3
                    print(n2,n4,n1,n2,n5)
            elif n3<n1 and n3<n4: #n5 n2 n3
                if n1<n4: #n5 n2 n3 n1 n4
                    print(n4,n1,n3,n2,n5)
                elif n4<n1: #n5 n2 n3 n4 n1
                    print(n1,n4,n3,n2,n5)
            elif n4<n1 and n4<n3: #n5 n2 n4
                if n1<n3: #n5 n2 n4 n1 n3
                    print(n3,n1,n4,n2,n5)
                elif n3<n1: #n5 n2 n4 n3 n1
                    print(n1,n3,n4,n2,n5)
        elif n3<n1 and n3<n2 and n3<n4: #n5 n3
            if n1<n2 and n1<n4: #n5 n3 n1
                if n2<n4: #n5 n3 n1 n2 n4
                    print(n4,n2,n1,n3,n5)
                elif n4<n2: #n5 n3 n1 n4 n2
                    print(n2,n4,n1,n3,n5)
            elif n2<n1 and n2<n4: #n5 n3 n2
                if n1<n4: #n5 n3 n2 n1 n4
                    print(n4,n1,n2,n3,n5)
                elif n4<n1: #n5 n3 n2 n4 n1
                    print(n1,n4,n2,n3,n5)
            elif n4<n1 and n4<n2: #n5 n3 n4
                if n1<n2: #n5 n3 n4 n1 n2
                    print(n2,n1,n4,n3,n5)
                elif n2<n1: #n5 n3 n4 n2 n1
                    print(n1,n2,n4,n3,n5)
        elif n4<n1 and n4<n2 and n4<n3: #n5 n4
            if n1<n2 and n1<n3: #n5 n4 n1
                if n2<n3: #n5 n4 n1 n2 n3
                    print(n3,n2,n1,n4,n5)
                elif n3<n2: #n5 n4 n1 n3 n2
                    print(n2,n3,n1,n4,n5)
            elif n2<n1 and n2<n3: #n5 n4 n2
                if n1<n3: #n5 n4 n2 n1 n3
                    print(n3,n1,n2,n4,n5)
                elif n3<n1: #n5 n4 n2 n3 n1
                    print(n1,n3,n2,n4,n5)
            elif n3<n1 and n3<n2: #n5 n4 n3
                if n1<n2: #n5 n4 n3 n1 n2
                    print(n2,n1,n3,n4,n5)
                elif n2<n1: #n5 n4 n3 n2 n1
                    print(n1,n2,n3,n4,n5)
```
``` python
print("4) Los números organizados de mayor a menor se ve de la siguiente manera: ",num_inv)
#La potencia del mayor número elevado al menor número
pot = (num_inv(0))**(num_inv(4))
print("5) La potencia del amyor número elevado al menor número es: ",pot)
#La raíz cúbica del menor número
raiz = (num_inv(4))**(1/3)
print("6) La raíz cúbica del menor número es: ",raiz)
```

## Punto 8

Escriba un programa al que se le ingrese la frecuencia de una onda en hz y como salida arroje en que parte del espectro electromagnetico.

Bueno en este punto solo necesitamos la tabla que verán abajo y solo una variable flotante que pida al lector que ponga una frecuencia después ya vienen los condicionales toca hacer condicional para cada zona por eso empezamos con if y continuamos con elif hasta llegar a nuestro else cómo ven el codigo de abajo solo es hacer esto sucesivamente y en cada condicional pedir que imprima la zona donde está así hasta completar toda la tabla. Por último probar el código y listo. Pico y pala meu

[![Captura-de-pantalla-2023-03-15-174812.png](https://i.postimg.cc/R0wgS2kK/Captura-de-pantalla-2023-03-15-174812.png)](https://postimg.cc/SXN6V1Nx)
``` python
#Ejercicio 8
frecuencia=float(input("ingrese la frecuencia en Hz="))# Escribimos la variable con float para que se entienda que es un real 

print("La frecuencia esta en la region=") # Ponemos el primer pritn que nos indique en cual region estara
# Empezamos con el if despues haremos todo los elif 
if frecuencia > 30.0E+18 :
    print("Rayos Gamma") #Aplicamos el segundo print para decir donde se ubica exactamente asi con todos los demas
elif frecuencia >30.0E+15 and frecuencia <= 30.0E+18 :
    print("Rayo X")
elif frecuencia > 1.5E+15 and frecuencia <= 30.0E+15 :
    print("Ultravioleta extremo")
elif frecuencia > 7.89E+14 and frecuencia <= 1.5E+15 :
    print("Ultravioleta cercano")
elif frecuencia > 384E+12 and frecuencia <= 7.89E+14 :
    print("Espectro Visible")
elif frecuencia > 120E+12 and frecuencia <= 384E+12 :
    print("Infrarrojo cercano")
elif frecuencia > 6.00E+12 and frecuencia <= 120E+12 :
    print("Infrarrojo medio")
elif frecuencia > 300E+9 and frecuencia <= 6.00E+12 :
    print("Infrarrojo lejano")
elif frecuencia > 3E+8 and frecuencia <= 300E+9 :
    print("Microondas")
elif frecuencia > 300E+6 and frecuencia <= 3E+8 :
    print("Ultra Alta Frecuencia-Radio")
elif frecuencia > 30E+6 and frecuencia <= 300E+6 :
    print("Muy Alta Frecuencia-Radio")
elif frecuencia > 1.7E+6 and frecuencia <= 30E+6 :
    print("Onda Corta - Radio")
elif frecuencia > 650E+3 and frecuencia <= 1.7E+6 :
    print("Onda Media - Radio")
elif frecuencia > 30E+3 and frecuencia <= 650E+3 :
    print("Onda Larga - Radio")
elif frecuencia < 30E+3 :
    print("Muy Baja Frecuencia - Radio")
```
[![Captura-de-pantalla-2023-03-14-164332.png](https://i.postimg.cc/Gpbcznxm/Captura-de-pantalla-2023-03-14-164332.png)](https://postimg.cc/LJ0K67Wc)
[![Captura-de-pantalla-2023-03-14-164449.png](https://i.postimg.cc/mrVT5pmN/Captura-de-pantalla-2023-03-14-164449.png)](https://postimg.cc/HJcGJzDV)

## Punto 9

Escriba un programa que reciba el nombre en minúsculas de un país de America y retorne la ciudad capital, si el país no pertenece al continente debe arrojar país no identificado.

Para este punto necesitamos ponerle un input a nuestra variable pais, para lograr digitar el nombre del pais americano que queremos, luego generamos un match con nuestra variable, para asi poder tomar todos los cases posibles de una forma organizada, y ponemos cada uno de los casos de los paises de america que existen imprimiendo su respectiva capitál, y finalmente si el país no esta entre los casos, ponemos un case _:(para tomar todos los casos que no estan dentro de nuestra variable) e imprimir un texto que diga que el pais no se reconoce por nuestro programa.

```python
Pais= (input("Ingrese un país de américa en minúscula"))
match Pais:
  case "colombia":
        print("bogota")
  case "argentina":    
        print("buenos aires")
  case "uruguay":
      print("montevideo")
  case "chile":
      print("santiago")    
  case "peru":
      print("lima")
  case "brasil":
      print("brasilia")
  case "bolivia":
      print("sucre")
  case "venezuela":
      print("caracas")
  case "surinam":
      print("paramaribo")
  case"antigua y barbuda":
      print ("Saint John's")
  case "bahamas":
      print ("nassau")
  case "guatemala":
      print("ciudad de guatemala")
  case "barbados":
      print("bridgetown")
  case "belice":
      print("belmopan")
  case "canada":
      print("ottawa")
  case "costa rica":
      print("san jose")
  case "cuba":
      print("la habana")
  case "mexico":
      print("ciudad de mexico")
  case "republica dominicana":
      print("santo domingo")
  case "dominica":
      print("roseau")
  case "ecuador":
      print("quito")
  case "el salvador":
        print("san salvador")
  case "estados unidos":
        print("washington, D.C.")
  case "granada":
        print("saint george's")
  case "honduras":
        print("tegucigalpa")
  case "guyana":
        print("georgetown")
  case "haiti":
        print("puerto ptincipe")
  case "jamaica":
        print("kingston")
  case "nicaragua":
        print("managua")
  case "paraguay":
        print("asuncion")
  case "panama":
        print("ciudad de panama")
  case "san cristóbal y nieves":
        print("basseterre")
  case "santa lucia":
        print("castries")
  case "san vicente y las granadinas":
        print("kingstown")
  case "trinidad y tobago":
        print("puerto españa")      
  case _: print(str(Pais)+" no es un país de américa")
```
[![Captura-de-pantalla-2023-03-15-173957.png](https://i.postimg.cc/5NcjvGT6/Captura-de-pantalla-2023-03-15-173957.png)](https://postimg.cc/hhrSRCSB)
[![Captura-de-pantalla-2023-03-15-174953.png](https://i.postimg.cc/xC0308yV/Captura-de-pantalla-2023-03-15-174953.png)](https://postimg.cc/Z9MdHTMw)
[![](https://mermaid.ink/img/pako:eNp1lmtu4zYQgK9C6E93gWywdh61vUABxXYdBYkd2Mk-QufHSGJsbiVSS4pOnCCH6QH6o-gRcrEOpVhiuqwBCxyKH2c4L-opSGTKgkFwl8n7ZA2qJFejT0tB8Be-iwRPuHxPPnz4jZw8RWKlmAZFjCAFcE1SRiBniifw_IqQpagHJ8iQxctfFfo7XaKaTOYxh2Vwi3M4eU5juZLly5-35JPDaF4hEwpqxUTJBdy-vj6lsWFCagIczWipFopowZTZrZ_Uek5fxagWz2jG82bP6lnbGlVbPKCpRpmVgW1j6VeaS1GyDU-Z3Kl1ma093ppnrCG-UQ1oO6y86x9xfaxA86wBbmg9wcEH3FtAZnzjuO8L1SZRzLe8xOUbJtijYVkLXNEEFCSgfUiBiDYKvZ03wCUtEMhB8dh7DBAI2WOis8iWxKBik7b6wildABclOZNr8YtXawz2YLBGJbrhTkIqQGswPmLFkUB9JcvBOdskoglH5alNyea1X6WqdKoYUukqnWMEeLpipbwXXpBZjmU8acN8MqY4k8sCvEhij5eAAMcrw5DKsoR7r3GJrApFl0BsUbXQzOYT-S61N96JsZiJHeCaZkDWEKNyH5Hbw-TsgSeyYS7Gjg_rdz5UpYgqVpgYXQEklTnHJoF6mo3moyr7Zf3upxKwS1J70B3agKMZVXhEf-RZgghLDIZNNcR4SH8YXnoNZZkFMqIh27yFzitv7uZ9rNE2dAwDgUmC7Y67uXK9COk96DWerZRij4z2h_veXFV2E3y-SYDJPET1ti5WTGKL81fG2jpoLUVqlFMapzNaspVJ-AqywhvYlanqY-vGY3JNa1X_l9pra-caeMlbTSEtDFMYxAJbcMILb-J9t-B3rF43imch_QNdo9E3PkbYCrZhV4CF2lDTiOZoNE5525NVVNRI25cvQwraoHV-TUXVoPCJBjrM1Enz-qUP1hVs8yRRXJcv_8SQYZMTnG1YG5AF7hZjs2IlU_5ebCuh3giLOsPQgQvbnqxLxZk3CfTm1YQNNh28gFB_BprUGYWt2rHj887n_gijCtwKn5jJePItKWWMl1N7N8yjXbyZLuDl7598Mp3VN3l4TqPpZD5ejMn1FL0ZLchoTMKL8TwahrdVU6w4XIjCRb3Jt3Z40w6v2uGXdnjZDsNpOx7O2vFJ2I4nkTs_d4SxA9dAfdsPrx3hYuwI1WM0c2bGQ1c4dwRsAo6ERe1Ip-4WE1fdqbvszBWmkSNchm-EqSMt_itdueJnR8CYOhL52rqDnDpjJ0zkzBlfvLvj4v3r55x9BHt4Yyis9RS_Fp_sDGbUmuV4HQ5wmLI7MFm5DJbiGZeCKeViK5JgcAeZZnuBKVK8lkf4TYTfFM0sFuCNlCiXytRiMHgKHoJBt9PZx3__oNM9POh1P_b6e8E2GBwd7R93ekfHh8fHH7u9o18Pn_eCx2qDzn6_f9TtHvf6B71Ot9_tHD7_C8L3EDo?type=png)](https://mermaid.live/edit#pako:eNp1lmtu4zYQgK9C6E93gWywdh61vUABxXYdBYkd2Mk-QufHSGJsbiVSS4pOnCCH6QH6o-gRcrEOpVhiuqwBCxyKH2c4L-opSGTKgkFwl8n7ZA2qJFejT0tB8Be-iwRPuHxPPnz4jZw8RWKlmAZFjCAFcE1SRiBniifw_IqQpagHJ8iQxctfFfo7XaKaTOYxh2Vwi3M4eU5juZLly5-35JPDaF4hEwpqxUTJBdy-vj6lsWFCagIczWipFopowZTZrZ_Uek5fxagWz2jG82bP6lnbGlVbPKCpRpmVgW1j6VeaS1GyDU-Z3Kl1ma093ppnrCG-UQ1oO6y86x9xfaxA86wBbmg9wcEH3FtAZnzjuO8L1SZRzLe8xOUbJtijYVkLXNEEFCSgfUiBiDYKvZ03wCUtEMhB8dh7DBAI2WOis8iWxKBik7b6wildABclOZNr8YtXawz2YLBGJbrhTkIqQGswPmLFkUB9JcvBOdskoglH5alNyea1X6WqdKoYUukqnWMEeLpipbwXXpBZjmU8acN8MqY4k8sCvEhij5eAAMcrw5DKsoR7r3GJrApFl0BsUbXQzOYT-S61N96JsZiJHeCaZkDWEKNyH5Hbw-TsgSeyYS7Gjg_rdz5UpYgqVpgYXQEklTnHJoF6mo3moyr7Zf3upxKwS1J70B3agKMZVXhEf-RZgghLDIZNNcR4SH8YXnoNZZkFMqIh27yFzitv7uZ9rNE2dAwDgUmC7Y67uXK9COk96DWerZRij4z2h_veXFV2E3y-SYDJPET1ti5WTGKL81fG2jpoLUVqlFMapzNaspVJ-AqywhvYlanqY-vGY3JNa1X_l9pra-caeMlbTSEtDFMYxAJbcMILb-J9t-B3rF43imch_QNdo9E3PkbYCrZhV4CF2lDTiOZoNE5525NVVNRI25cvQwraoHV-TUXVoPCJBjrM1Enz-qUP1hVs8yRRXJcv_8SQYZMTnG1YG5AF7hZjs2IlU_5ebCuh3giLOsPQgQvbnqxLxZk3CfTm1YQNNh28gFB_BprUGYWt2rHj887n_gijCtwKn5jJePItKWWMl1N7N8yjXbyZLuDl7598Mp3VN3l4TqPpZD5ejMn1FL0ZLchoTMKL8TwahrdVU6w4XIjCRb3Jt3Z40w6v2uGXdnjZDsNpOx7O2vFJ2I4nkTs_d4SxA9dAfdsPrx3hYuwI1WM0c2bGQ1c4dwRsAo6ERe1Ip-4WE1fdqbvszBWmkSNchm-EqSMt_itdueJnR8CYOhL52rqDnDpjJ0zkzBlfvLvj4v3r55x9BHt4Yyis9RS_Fp_sDGbUmuV4HQ5wmLI7MFm5DJbiGZeCKeViK5JgcAeZZnuBKVK8lkf4TYTfFM0sFuCNlCiXytRiMHgKHoJBt9PZx3__oNM9POh1P_b6e8E2GBwd7R93ekfHh8fHH7u9o18Pn_eCx2qDzn6_f9TtHvf6B71Ot9_tHD7_C8L3EDo)

## Punto 10

Bueno el 10 punto este taller este era facilito necesitábamos una variable flotante que le pida una velocidad al lector, después averiguaremos las velocidades de lo que nos piden, después de averiguarlas y de colocarlas en el programa colocaremos la fórmula tiempo=distancia/velocidad para cada dato. Por último colocamos nuestras condiciones, probamos el código y listo. Pico y pala meu 
``` python
#Ejercicio 10
distancia= float(input("Coloque una distancia en m="))
# Colocaremos las velocidades en m/s
velocidaddelaluz=float(2.2998e+8)
velocidaddelsonido=float(343.2)
velocidaddelvehiculo=float(147.7778)
velocidaddeBolt=float(12.4222222)
# la Formula siempre sera la misma d/v para hallar el tiempo
tiempo= (distancia) / (velocidaddelaluz)
tiemposonido= (distancia) / (velocidaddelsonido) 
tiempovehivulo= (distancia) / (velocidaddelvehiculo)
tiempoBolt= (distancia) / (velocidaddeBolt)
# Repetimos el proceso del print para cada velocidad
print("El tiempo que se demora en recorrer la distancia a la velocidad de la luz en segundos es=" )
print(tiempo)
print("El tiempo que se demora en recorrer la distancia a la velocidad del sonido en segundos es=" )
print(tiemposonido)
print("El tiempo que se demora en recorrer la distancia a la velocidad del SSC Tuatara en segundos es=" )
print(tiempovehivulo)
print("El tiempo que se demora en recorrer la distancia a la velocidad de Bolt en segundos es=" )
print(tiempoBolt)
```
[![Captura-de-pantalla-2023-03-14-164538.png](https://i.postimg.cc/Kzkv3r5P/Captura-de-pantalla-2023-03-14-164538.png)](https://postimg.cc/vgydpnkT)
[![Captura-de-pantalla-2023-03-15-183810.png](https://i.postimg.cc/rFwkbNBq/Captura-de-pantalla-2023-03-15-183810.png)](https://postimg.cc/bdWWSkY5)
