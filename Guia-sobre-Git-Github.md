# Guía sobre el uso de Git y Github
Javier  
Friday, January 09, 2015  

#Primera Parte:

##Introducción

El objetivo de esta guía es dar a conocer unos conocimientos de nivel básico/intermedio
sobre el funcionamiento de Git, las diversas posibilidades que ofrece Github, la
integración de ambos con rstudio y por último aplicar todo lo aprendido de manera
práctica siguiendo una metodología.

### ¿Qué es Git?

Git es un software de control de versiones. El control de versiones, resumiéndolo
mucho, es la gestión de los diversos cambios que se realizan sobre un repositorio
(un repositorio es el nombre que recibe el lugar donde se aloja el código de un 
proyecto de desarrollo en algún lenguaje de programación).

> Git usa cadenas de 40 caracteres llamadas SHA para identificar los cambios 
realizados. Ej: 74be3c2b93c8267de64e6dfde8658d31d7d2fe6c

### Objetos de Git

Hay 4 tipos de objetos en git (el más importante a entender es el commit).

1. Blob: se usa para almacenar datos de archivos, es generalmente un archivo.

2. Tree: es, básicamente, como un directorio, hace referencia a un conjunto de 
   otros trees y/o blobs (por ej. archivos y subdirectorios).

3. Commit: apunta a un determinado tree, marcando cómo era en un momento determinado
   (quien no haya entendido lo que es un tree, sustituya la palabra tree por archivo).
   Contiene información sobre ese momento determinado, los cambios del autor desde 
   el último commit, el commit anterior (conocido como parent), etc. También se puede
   entender un commit, de una forma más imprecisa y coloquial, como la modificación
   o el conjunto de modificaciones a uno o varios archivos del repositorio. Otra forma
   de entenderlo también sería, como una "foto" de uno o varios archivos del 
   repositorio en un momento determinado.

4. Tag: es una forma de marcar un commit como específico de alguna forma. Se usa
   normalmente para marcar algunos commits como releases específicos o algo 
   destacable en esas lineas.

Para más información sobre los objetos de git, dirigirse a: Git Community Book

### ¿Qué es [Github](http://github.com/)?

Github es una plataforma de desarrollo colaborativo de software para alojar proyectos
usando el sistema de control de versiones Git. El código se almacena de forma pública,
aunque también se puede hacer de forma privada, creando una cuenta de pago. También
se pueden obtener repositorios privados (de pago) si se es estudiante.

Github no sólo ofrece alojamiento del código si no muchas más posibilidades asociadas
a los repos como son, forks, issues, pull requests, diffs, etc. Se verán todos con
detalle más adelante.

### ¿Qué es una metodología de desarrollo de software en el mundo de la programación y de qué forma vamos a aplicarla?

Citaré a wikipedia aquí: Metodología de desarrollo de software en ingeniería de 
software es un marco de trabajo usado para estructurar, planificar y controlar el
proceso de desarrollo en sistemas de información.

Básicamente el punto aquí es controlar el proceso de desarrollo para que sea ordenado
y de esta forma lo más productivo posible.

Esto a primera vista es algo muy simple pero se complica extremadamente dando lugar
a diversas metodologías y hay libros muy extensos sobre ello además de mucha 
controversia sobre cual es la mejor. A nosotros esto nos importa más bien poco pero
a donde quiero llegar con esto es a la implementación de una metodología de desarrollo
del emulador.

Este método de desarrollo estaría basado en Git y Github ofreciéndonos una enorme
versatilidad y posibilitando que todo el equipo de desarrollo esté al día en cuanto
a novedades en el desarrollo así como multitud de ventajas que más adelante explicaré.
Esta metodología estaría basada en las branches y pull request.

> Para concluir esta introducción o presentación de la guía me gustaría mencionar
  que todo esto que he resumido arriba es en lo que se basan todos los proyectos
  de desarrollo de software profesionales con unas bases firmes.
  
  
  
# Segunda Parte:

##Git&Github -> Setup


### Set Up Clave SSH

#### Situar la clave SSH en Github.

#### Comprobación

### Set Up Config

### Git&Github

#### Crear un Repositorio

#### Clonar un Repositorio

# Tercera Parte:

## Git-> Realizar cambios, revertirlos y subirlos al repositorio remoto
