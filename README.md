HTML/CSS/JavaScript Conceptos básicos
=====================================

HTML significa HyperText Markup Language. Se usa en la parte frontal y le da estructura a la página web, que puede diseñar usando CSS y hacer interactivo usando JavaScript.

CSS o Cascading Style Sheets es el lenguaje utilizado para diseñar el front-end de cualquier sitio web. CSS es una tecnología fundamental de la World Wide Web, junto con HTML y JavaScript.

JavaScript le permite agregar interactividad a sus páginas. Es posible que haya visto ejemplos comunes en los sitios web: controles deslizantes, interacciones de clic, ventanas emergentes, etc.

Videos para conocer un poco más a fondo lo mencionado anteriormente, no es necesario poner en práctica esto, utilizar este material para mejorar el conocimiento acerca de la GUI (Graphical User Interface).

- HTML Basico : https://www.youtube.com/watch?v=MJkdaVFHrto

- CSS Basico : https://www.youtube.com/watch?v=wZniZEbPAzk

- JavaScript Basico: https://www.youtube.com/watch?v=8GTaO9XhA5M

- Introducción a la programación: https://www.youtube.com/watch?v=VxrIZGQfxmE

- Introducciòn a GIT: https://www.youtube.com/watch?v=mCVQgSyjCkI

- Playlist de pseudocódigo : https://youtube.com/playlist?list=PLQxX2eiEaqbwHMRObsvtRSb6sA43msUJt&si=2Itywcmv6lDMP67Y


Podríamos comenzar a dar los primeros pasos si se animan, lo primero sería buscar un IDE o un editor para comenzar a programar, instalar el JDK y realizar las configuraciones necesarias. Les dejo unos videos que les puede servir para trabajar con VSCODE.
https://www.youtube.com/watch?v=tWN601sU9PM
Siguiendo los pasos del video anterior, creen un proyecto para prácticas y comiencen con estas primeras lecciones:

Lección 1: Hola Mundo en Java
-----------------------------
public class HolaMundo {

    public static void main(String[] args) {
        System.out.println("¡Hola, Mundo!");
    }
}

*Explicación:*

- public class HolaMundo: Define una clase llamada HolaMundo.
- public static void main(String[] args): Punto de entrada del programa.
- System.out.println("¡Hola, Mundo!");: Imprime "¡Hola, Mundo!" en la consola.


Lección 2: Variables y Operaciones Básicas
------------------------------------------

public class OperacionesBasicas {

    public static void main(String[] args) {
        int a = 5;
        int b = 3;
        int suma = a + b;
        int resta = a - b;
        int multiplicacion = a * b;
        double division = (double) a / b;

        System.out.println("Suma: " + suma);
        System.out.println("Resta: " + resta);
        System.out.println("Multiplicación: " + multiplicacion);
        System.out.println("División: " + division);
    }
}


Lección 3: Estructuras de Control - Condicionales
-------------------------------------------------

public class Condicionales {

    public static void main(String[] args) {
        int numero = 8;

        if (numero % 2 == 0) {
            System.out.println("El número es par.");
        } else {
            System.out.println("El número es impar.");
        }
    }
}


Lección 4: Estructuras de Control - Bucles
------------------------------------------

public class BucleFor {

    public static void main(String[] args) {
        for (int i = 1; i <= 5; i++) {
            System.out.println("Iteración " + i);
        }
    }
}

Ejercicios de Práctica:
-----------------------
1. Crea un programa que calcule y muestre el área de un rectángulo (Área = longitud x anchura).
2. Escribe un programa que verifique si un número ingresado por el usuario es positivo, negativo o cero.
3. Construye un programa que imprima los primeros 10 números naturales.
4. Desarrolla un programa que solicite dos números al usuario y muestre el resultado de su multiplicación.
5. Crea un programa que calcule el promedio de tres números ingresados por el usuario.
6. Escribe un programa que determine si un año es bisiesto o no (un año es bisiesto si es divisible por 4, excepto los años que son divisibles por 100 pero no por 400).
7. Construye un programa que imprima la serie de Fibonacci hasta el décimo término.
8. Desarrolla un programa que solicite un número al usuario y muestre su tabla de multiplicar del 1 al 10.
9. Crea un programa que determine si un número ingresado por el usuario es primo.
10. Escribe un programa que calcule el factorial de un número ingresado por el usuario.

Pueden ir colaborando con cursos de Udemy o de cualquier plataforma.
-------------------------------------------------------------------
**Cursos:**
- Programación para testers: https://infocorp.udemy.com/course/programacion-para-testers-todo-lo-que-necesitas-saber/
- Fundamentos de Programación: https://infocorp.udemy.com/course/fundamentos-de-la-programacion/
