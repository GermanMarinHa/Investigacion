# Investigacion

Variables Estáticas

Una variable estática, es una variable que ha sido ubicada y estáticamente y cuyo tiempo de vida se extiende durante toda la ejecución del programa. Normalmente una variable estática tiene una vida o un ámbito más amplio que el de las otras variables.

Ciclos de vida de una variable

Variables de instancia (u objeto):

* Se crean cuando se crea el objeto que las contiene.

* Se inicializan por defecto si no se hace de modo explícito:

.0 para números, "false" para booleano, "null" para objetos.

* Se destruyen cuando el recolector de basura de Java

* no encuentra referencias activas para el objeto.

Variables estáticas (o de clase):

* Se crean cuando la clase se usa por primera vez.

.Se inicializan por defecto si no se hace de modo explícito:

* 0 para números, "false" para booleano, "null" para objetos

* Suelen existir para el resto del programa (salvo que no esté cargado).

Variables locales (o de bloque):

* Creadas en la sentencia en la que están definidas.

* No se inicializan por defecto. Contienen datos imprevisibles.

* Se destruyen al salir del bloque (en la llave final).

Memoria Dinámica

La memoria dinámica se refiere a aquella memoria que no puede ser definida ya que no se conoce o no se tiene idea del número de la variable a considerarse, la solución a este problema es la memoria dinámica que permite solicitar memoria en tiempo de ejecución, por lo que cuanta más memoria se necesite, más se solicita al sistema operativo. El sistema operativo maneja la memoria gracias al uso de punteros, por la misma naturaleza del proceso nos impide conocer el tamaño de la memoria necesaria en el momento de compilar.

Un dato importante es que como tal este tipo de datos se crean y se destruyen mientras se ejecuta el programa y por lo tanto la estructura de datos se va dimensionando de forma precisa a los requerimientos del programa, evitándonos así perder datos o desperdiciar memoria si hubiéramos tratado de definir la cantidad de memoria a utilizar en el momento de compilar el programa.

Clase

En informática, una clase es una plantilla para la creación de objetos de datos según un modelo predefinido. Las clases se utilizan para representar entidades o conceptos, como los sustantivos en el lenguaje. Cada clase es un modelo que define un conjunto de variables -el estado, y métodos apropiados para operar con dichos datos -el comportamiento. Cada objeto creado a partir de la clase se denomina instancia de la clase.

Las clases son un pilar fundamental de la programación orientada a objetos. Permiten abstraer los datos y sus operaciones asociadas al modo de una caja negra. Los lenguajes de programación que soportan clases difieren sutilmente en su soporte para diversas características relacionadas con clases. La mayoría soportan diversas formas de herencia. Muchos lenguajes también soportan características para proporcionar encapsulación, como especificadores de acceso.

Las clases se componen de elementos, llamados genéricamente «miembros», de varios tipos: * campos de datos: almacenan el estado de la clase por medio de variables, estructuras de datos e incluso otras clases. * métodos: subrutinas de manipulación de dichos datos. * ciertos lenguajes permiten un tercer tipo de miembro: las «propiedades», a medio camino entre los campos y los métodos.

Objeto

Es una unidad dentro de un programa de computadora que consta de un estado y de un comportamiento, que a su vez constan respectivamente de datos almacenados y de tareas realizables durante el tiempo de ejecución. Un objeto puede ser creado instanciando una clase, como ocurre en la programación orientada a objetos, o mediante escritura directa de código y la replicación otros objetos, como ocurre en la programación basada en prototipos.

Instanciación

En general, cuando se ejecuta un programa en un computador, se dice que éste se instancia. En lenguajes que crean objetos a partir de clases, un objeto es una instancia de una clase. Esto es, un miembro de una clase que tiene atributos en lugar de variables.

Herencia

Es el mecanismo más utilizado para alcanzar algunos de los objetivos más preciados en el desarrollo de software como lo son la reutilización y la extensibilidad. A través de ella los diseñadores pueden crear nuevas clases partiendo de una clase o de una jerarquía de clases preexistente evitando con ello el rediseño, la modificación y verificación de la parte ya implementada.

Sobrecarga

Es la capacidad de un lenguaje de programación, que permite nombrar con el mismo identificador diferentes variables u operaciones.

En programación orientada a objetos la sobrecarga se refiere a la posibilidad de tener dos o más funciones con el mismo nombre pero funcionalidad diferente. Es decir, dos o más funciones con el mismo nombre realizan acciones diferentes. El compilador usará una u otra dependiendo de los parámetros usados. A esto se llama también sobrecarga de funciones.

Ensombrecimiento

El problema de “ensombrecimiento” se produce cuando en un ámbito de validez se define una variable con nombre idéntico a otra válida en un ámbito superior.

Bibliografía

https://es.wikipedia.org/wiki/Variable_est%C3%A1tica http://mit.ocw.universia.net/1.00/s02/class-sessions/lecture-11/lecture-11.pdf https://es.wikipedia.org/wiki/Memoria_din%C3%A1mica_(programaci%C3%B3n) https://es.wikipedia.org/wiki/Clase_(inform%C3%A1tica) https://es.wikipedia.org/wiki/Objeto_(programaci%C3%B3n) https://es.wikipedia.org/wiki/Instancia_(inform%C3%A1tica) http://es.ccm.net/contents/411-poo-herencia https://es.wikipedia.org/wiki/Sobrecarga_(inform%C3%A1tica) http://www.it.uc3m.es/labas/course_notes/variables_es.html
