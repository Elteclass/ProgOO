# EL PARADIGMA DE LA PROGRAMACION ORIENTADA A OBJETOS
## **¿QUÉ ES PARADIGMA EN EL LENGUAJE DE PROGRAMACIÓN?**
Se denominan paradigmas de programación a las formas de clasificar los lenguajes de programación en función a sus caracteristicas.

## **Los paradigmas de programación comunes incluyen:**
* **Imperativo** en el que el programador instruye a la máquina cómo cambiar su estado. 
* **Procedimental** que agrupa las instrucciones en procedimientos.
* **Orientado a objetos** que agrupa las instrucciones con la parte del estado en el que operan.
* **Declarativo** en el que el programador simplemente declara las propiedades del resultado deseado, pero no cómo calcularlo.
* **Funcional** en el que el resultado deseado se declara como el valor de una seria de aplicaciones de función.
* **Matemático** en el que el resultado deseado se declara como la solución de un problema de optimización.
* **Reactivo** en el que se declara el resultado deseado con flujos de datos y a la propagación del cambio.
----

## **PROGRAMACION ORIENTADA A OBJETOS**
La _programación orientada a objetos_ es un paradigma de programación que parte del concepto de **"objetos"** como base, los cuales contiene información en forma de campos y códigos en forma de métodos.
**Los objetos** son capaces de interactuar y modificar los valores contenidos en sus campos(estado) o atributos a través de sus métodos(comportamiento).

//insertar imagen de POO//
----

## **PRIMER LENGUAJE ORIENTADO A OBJETOS**
El concepto de POO tienen origen en **SIMULA** que es un lenguaje de programación orientada a objetos de 1962 diseñado para hacer simulaciones, creado por **Ole-Johan Dahl** y **Kristen Nygaard**, del centro de cómputo noruego de OSLO, en este centro se trabajaba en simulaciones de naves. La idea surgió al agrupar los diversos tipos de naves en diversas clases de objetos, siendo responsable cada clase de objetos de definir sus "**propios**" datos y comportamientos.
----

## **Abstracción**
Se podría definir como las características que diferencian a un objeto de otro, esto ayuda para poder saber el comportamiento que tiene cierto elemento, por tal motivo la **abstracción** forma parte de los aspectos fundamentales en el modelo de objetos.
----

## **ENCAPSULAMIENTO**
Encapsulación en la programación orienta a objetos consiste en almacenar y organizar en una clase las características y funcionalidades de los objetos, representandolas por medio de atributos y métodos, todo esto se logra como efecto secundario de la abstracción. El encapsulamiento garantiza la integridad de los datos que contiene un objeto y por integridad se refiere a que los datos sean correctos y esten completos, ademas evita el acceso a datos por cualquier otro medio distinto que no se haya especificado en la clase. En conclusión la **encapsulación** es de suma importancia a la hora de querer ocultar los valores o el estado de un objeto estructurados en una clase, evitando el acceso directo a ellos por parte de los clientes de una manera que podría exponer detalles de implementación ocultos.

//insertar imagen de encapsulamiento
----

## **HERENCIA**
La herencia es el mecanismo donde se crean una o varias clases a partir de una clase que ya existe, esto quiere decir que las clases que se vayan a crear se denominan como subclases y la clase a partir de la cual se crean las subclases se le llama clase primaria, clase padre, o super clase.
Las subclases contienen atributos y métodos que provienen de la superclase.
Las ventajas de usar la herencia es la reutilización de código, método que permite que una parte o la totalidad de un programa se pueda ocupar en la construción de otro programa y ahorra tiempo.

//insertar imagen de herencia
----

# UML: DIAGRAMA DE CLASES
## **HISTORIA**
Después de que la Rational Software Corporation contratara a **James Rumbaugh** de General Electric, en 1994, la compañía se convirtió en la fuente de los dos esquemas de modelado orientado a objetos más populares de la época: Object-Modeling Technique (OMT) de Rumbaugh, que era mejor para **análisis orientado a objetos**, y el Método Booch (de **Grady Booch**) que era mejor para el **diseño orientado a objetos**. Poco después se les unió **Ivar Jacobson**, el creador del **método de ingeniería de software orientado a objetos**. Jacobson se unió a Rational, en 1995, después de que su compañía Objectory AB fuera comprada por Rational. Los tres metodologistas eran conocidos como **Los Tres Amigos**, porque se sabía de sus constantes discusiones sobre las prácticas metodológicas.
En 1996 Rational concluyó que la abundancia de lenguajes de modelado estaba alentando la adopción de la tecnología de objetos, y para orientarse hacia un método unificado, encargaron a los Tres Amigos que desarrollaran un **"lenguaje unificado de modelado"** abierto.
Bajo la dirección técnica de los Tres Amigos (Rumbaugh, Jacobson y Booch) fue organizado un consorcio internacional llamado **UML Partners** en 1996, el borrador de la especificación UML 1.0 de UML Partners fue propuesto a la OMG en enero de 1997. Durante el mismo mes, la UML Partners formó una Fuerza de Tarea Semántica, encabezada por **Cris Kobryn** y administrada por **Ed Eykholt**, para finalizar las semánticas de la especificación y para integrarla con otros esfuerzos de estandarización. El resultado de este trabajo, el UML 1.1, fue presentado ante la OMG en agosto de 1997 y adoptado por la OMG en noviembre de 1997.
UML se utiliza principalmente en el desarrollo de software orientado a objetos. Los diagramas de clases son uno de los tipos de diagramas más útiles en UML, ya que trazan claramente la estructura de un sistema concreto al modelar sus clases, atributos, operaciones y relaciones entre objetos.

----
//insertar diagrama