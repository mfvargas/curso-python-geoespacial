# Python
--------
Este es un curso introductorio al lenguaje de programación Python, con un énfasis en el procesamiento de datos geoespaciales.

Sitio web:
[https://mfvargas.github.io/curso-intro-python/](https://mfvargas.github.io/curso-intro-python/)

## Índice
---------
[1. Introducción](https://github.com/mfvargas/curso-intro-python/blob/master/README.md#1-introducci%C3%B3n)

## 1. Introducción
------------------

### Acerca de Python
| ![](img/python-logo.png) |
|:---:|
| Figura 1. Logotipo del lenguaje Python<br>Fuente: [Python.org](http://www.python.org/)|

[Python](https://www.python.org/) es un lenguaje de programación de propósito general que ha alcanzado una [gran popularidad en los últimos años](https://www.infoworld.com/article/3331603/pythons-popularity-surges-as-a-mainstay-language.html). Fue declarado el lenguaje del año 2018 por el índice [Tiobe](https://www.tiobe.com/tiobe-index/) de popularidad de lenguajes de programación, debido al crecimiento de su uso en diversas áreas, entre las que destacan la [ciencia de datos](https://en.wikipedia.org/wiki/Data_science) y el [aprendizaje de máquinas](https://en.wikipedia.org/wiki/Machine_learning), además de otras como [pruebas de sistemas](https://en.wikipedia.org/wiki/System_testing), [desarrollo web](https://en.wikipedia.org/wiki/Web_development), [scripting](https://en.wikipedia.org/wiki/Scripting_language) y [visualización de datos](https://en.wikipedia.org/wiki/Data_visualization), entre muchas. Esta popularidad es respaldada por otras fuentes como el índice [PYPL](http://pypl.github.io/PYPL.html) y la comunidad de programadores [Stack Overflow](https://stackoverflow.com/). Esta última lo considera el [lenguaje de programación de mayor crecimiento en los países de alto ingreso](https://stackoverflow.blog/2017/09/06/incredible-growth-python/?_ga=2.202250515.367846061.1552160385-2089845565.1546395318), como se muestra en la figura 2.

| ![](img/growth_major_languages.png) |
|:---:|
| Figura 2. Crecimiento de los principales lenguajes de programación en los países de alto ingreso<br>Fuente: [Stack Overflow](https://stackoverflow.blog/2017/09/06/incredible-growth-python/?_ga=2.202250515.367846061.1552160385-2089845565.1546395318)|

En la actualidad, Python es ampliamente utilizado en enseñanza de la programación y es el [lenguaje más empleado en cursos introductorios de programación de las principales universidades de Estados Unidos](https://cacm.acm.org/blogs/blog-cacm/176450-python-is-now-the-most-popular-introductory-teaching-language-at-top-u-s-universities/fulltext) debido, entre otras razones, a que sus programas son fáciles de leer y requieren menos líneas de código que otros lenguajes de amplia difusión, tales como [Java](http://oracle.com/java/), [C](https://en.wikipedia.org/wiki/C_(programming_language)) o [C++](https://isocpp.org/).

Python fue creado por el programador holandés [Guido van Rossum](https://gvanrossum.github.io//), quién concibió el diseño original del lenguaje a finales de la década de 1980 y dio a conocer la primera versión en 1991. Van Rossum eligió el nombre del lenguaje en honor al grupo de comedia británico [Monty Python](https://es.wikipedia.org/wiki/Monty_Python). Según van Rossum, en diciembre de 1989 buscaba un proyecto de programación como "pasatiempo" durante los días cercanos a la navidad, por lo que decidió escribir un interpretador para un lenguaje de programación en el que había estado pensando recientemente. Escogió el nombre Python por encontrarse en un "humor ligeramente irreverente" y ser un gran aficionado al programa de televisión ["El circo volador de Monty Python" (_Monty Python's Flying Circus_)](https://en.wikipedia.org/wiki/Monty_Python%27s_Flying_Circus).

| ![](img/Guido-portrait-2014.jpg) | ![](img/montypython.jpg) |
|:---:|:---:|
| Figura 3. Guido van Rossum, creador de Python<br>Fuente: [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Guido-portrait-2014.jpg) | Figura 4. El circo volador de Monty Python<br>Fuente: [Internet Movie Database (IMDB)](http://www.imdb.com/title/tt0063929/)|

### Principales características del lenguaje
* Es [interpretado](https://en.wikipedia.org/wiki/Interpreter_(computing)): las instrucciones se traducen una por una a [lenguaje máquina](https://en.wikipedia.org/wiki/Machine_code), a diferencia de los [lenguajes compilados](https://en.wikipedia.org/wiki/Compiler), que traducen simultáneamente una unidad completa (ej. un programa o una biblioteca). Los lenguajes interpretados tienden a ser más lentos que los compilados, pero también son más flexibles como entornos de desarrollo y depuración.
* Es [multiplataforma](https://en.wikipedia.org/wiki/Cross-platform_software): puede ejecutarse en los sistemas operativos más populares (ej. Microsoft Windows, macOS, Linux).
* Ofrece un [sistema de tipos de datos](https://en.wikipedia.org/wiki/Type_system) dinámico: las variables pueden tomar diferentes tipos de datos (ej. textuales, numéricos) durante la ejecución del programa, a diferencia de un sistema de tipos de datos estático, en el que las variables solo pueden tener un tipo de datos. La mayoría de los lenguajes de tipos dinámicos son lenguajes interpretados.
* Cuenta con [administración de memoria](https://en.wikipedia.org/wiki/Memory_management) automática. 
* Soporta varios [paradigmas de programación](https://es.wikipedia.org/wiki/Paradigma_de_programaci%C3%B3n), incluyendo [programación orientada a objetos](https://es.wikipedia.org/wiki/Programaci%C3%B3n_orientada_a_objetos), [programación imperativa](https://es.wikipedia.org/wiki/Programaci%C3%B3n_imperativa), [programación funcional](https://es.wikipedia.org/wiki/Programaci%C3%B3n_funcional) y [programación procedimental](https://es.wikipedia.org/wiki/Programaci%C3%B3n_por_procedimientos).

### Python 2 vs Python 3
