<p align="center">
    <img src="https://github.com/GeeksHubsAcademy/2020-geekshubs-media/blob/master/image/logo.png" >	
</p>


	Considere el siguiente problema:

	Dada un número entero que actúa como el límite máximo del tamaño de la secuencia, se desea calcular una 
    montaña de números.
    
	Cada escalón se genera a través del empareamiento de dos de ellos en cada fila excepto la primera fila.
    En este caso base, ésta siempre empezará en 1. Por otro lado, el primer elemento y el último siempre será 1.
    La suma del elemento se hace a través de parejas de dos números consecutivos.

	Montaña :     2              3                   4

	Ejemplo:

	              1              1                   1 
                1   1          1   1               1   1
                             1   2   1           1   2   1
                                               1   3   3   1
   
    Notas:
    
    Tenga en cuenta los espacios entre elementos.
    El algoritmo debe de ser óptimo.



    En la carpeta 'test/suite.test.js' se encuentra el fichero con la suite de test.
    
    El modus operandi de trabajo es el siguiente:
    
    Debes 'forkear' el proyecto a tu cuenta.
    Puedes hacer PR's ilimitadas e ir validando poco a poco la solución contra nuestro respositorio con CI.
    Puedes trabajar en local y subir la solución haciendo un PR a nuestro repositorio.
    Cuando se envíe la PR final, debes indicar el tiempo de dedicación y los intentos que has hecho.
    También puedes añadir un comentario para dar cualquier tipo de feedback.
    
    En caso de duda, revisa en el apartado de 'Referencias'.       
    

    [Suite Tests]
    
         PASS  test/suite.test.js
            √ Tier 1 (4ms)
            √ Tier 2 (1ms)
            √ Tier 3 (2ms)
            √ Tier 4
            √ Tier 5 (1ms)
            √ Tier 10 (1ms)
            √ Tier 15 (1ms)
            √ Tier 20

            Test Suites: 1 passed, 1 total
            Tests:       8 passed, 8 total
            Snapshots:   0 total
            Time:        3.728s		

## Referencias

* [Tutorial - Testing Automatizado](https://github.com/GeeksHubsAcademy/2020-js-vanilla-testing-FFFF/blob/master/README.md)
