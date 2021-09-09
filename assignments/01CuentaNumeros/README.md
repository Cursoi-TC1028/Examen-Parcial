![Tec de Monterrey](../../images/logotecmty.png)
# Sumatoria de 1 a n

Modifica el programa que se encuentra en la carpeta `src` que se llama
`exercise.py` y que contiene el siguiente código:

```python
def main():
  #escribe tu código abajo de esta línea

if __name__ == '__main__':
    main()
```
La línea `#escribe tu código abajo de esta línea` es un comentario,
el programa la va a ignorar al ejecutarse.

<div style="font-family:verdana; font-size:10px">

Escribe un programa que utilice ciclos para mostrar una secuencia como la que se muestra en el ejemplo:

Si el usuario teclea el número 5, el programa mostrará lo siguiente:
1 = 1 
1+2 = 3 
1+2+3 = 6 
1+2+3+4 = 10 
1+2+3+4+5 = 15 
La suma de la serie es: 35

Toma en consideración que el programa deberá solicitar un número entero positivo al usuario que deberá enviarse a una función en la cual se realizarán las operaciones que sean necesarias. 
La función deberá retornar el resultado de la suma que deberás utilizar para desplegar la línea final mostrada en el ejemplo.

Si el usuario ingresa un número negativo o cero como entrada, el programa deberá mostrar el mensaje "El número es inválido".

Entrada
Un número entero positivo n.

Salida
Una secuencia como la que se muestra en el ejemplo.

Ejemplos de ejecución del programa:
>>>2
1 = 1                                                                                                                             
1 + 2 = 3                                                                                                                         
La suma de la serie es: 4


>>>7
1 = 1 
1+2 = 3 
1+2+3 = 6 
1+2+3+4 = 10 
1+2+3+4+5 = 15 
1+2+3+4+5+6 = 21 
1+2+3+4+5+6+7 = 28                                                                                                                      
La suma de la serie es: 84


>>>-33
El número es inválido


El nombre del programa debe ser <b>sumatoria_secuencial.py</b>
</div>


#### Entrada
Un número entero positivo n

#### Salida
Los números enteros desde 1 hasta n, uno en cada renglón

#### NOTA IMPORTANTE:
Tu programa NO debe incluir ningún mensaje para pedir los datos y la salida debe coincidir exactamente con el formato y/o tipo de dato que se te pide como salida.

La salida del programa debe de ser exactamente de la siguiente forma:

```
5
1
2
3
4
5



15
1
2
3
4
5
6
7
8
9
10
11
12
13
14
15

10
1
2
3
4
5
6
7
8
9
10

```

**Nota:** No te preocupes por esta parte del código
`if __name__ == '__main__':` por el momento.
No la vamos a necesitar para este programa, pero es una buena práctica
incluirla y quedará más claro para que sirve en los siguientes ejercicios.

Una vez que termines tu actividad y la hayas probado con
`python -m pytest --tb=short -v`, subela a tu repositorio en GitHub,
con el proceso de commit + push.
