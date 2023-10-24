# 🧑‍💻 ARQUITECTURA DE SOFTWARE 🧑‍💻

<img src="./img/desarrollo-software-1688x844.jpg">


La arquitectura de software es la estructura de un sistema de software, que define sus componentes, sus relaciones y sus principios de diseño. Es un plan de cómo se va a construir un sistema de software, que se desarrolla en las primeras etapas del proceso de desarrollo.

La arquitectura de software es importante porque proporciona una visión general de un sistema de software, lo que permite a los desarrolladores tomar decisiones informadas sobre el diseño y la implementación. También ayuda a garantizar que el sistema de software sea escalable, adaptable y mantenible.

En sus inicios, el desarrollo de software se realizaba de manera informal. Con el tiempo, se han desarrollado nuevos modelos y estándares para resolver los desafíos modernos. Estos modelos y estándares se denominan arquitectura de software. Al igual que los planos de un edificio, la arquitectura de software define la estructura, el funcionamiento y la interacción entre las partes del software.

David Garlan y Mary Shaw, en su libro "An introduction to Software Architecture", definen la arquitectura como un nivel de diseño que se centra en aspectos más allá de los algoritmos y estructuras de datos. El diseño y la especificación de la estructura global del sistema es un nuevo tipo de problema.

# INDICE

1. [¿ QUÉ ES UNN PATRON DE ARQUITECTURA ?](#🏭-¿-qué-es-un-patron-de-arquitectura--🏭)

2. [PATRONES DE ARQUITECTURA](#🌉-patrones-de-arquitectura-🌉)


    2.1 [Patrón de capas](#🔨-patrón-de-capas-🔨)

    2.2 [Patrón cliente-servidor](#🔨-patrón-cliente-servidor-🔨)

    2.3 [Patrón maestro-esclavo](#🔨-patrón-maestro-esclavo-🔨)

    2.4 [Patrón de filtro de tubería](#🔨-patrón-de-filtro-de-tubería-🔨)

    2.5 [Patrón de intermediario](#🔨-patrón-de-intermediario-🔨)

    2.6 [Patrón de igual a igual](#🔨-patrón-de-igual-a-igual-🔨)

    2.7 [Patrón de bus de evento](#🔨-patrón-de-bus-de-evento-🔨)

    2.8 [Modelo-vista-controlador](#🔨-modelo-vista-controlador-🔨)

3. [VENTAJAS DE LOS PATRONES DE ARQUITECTURA](#👍-ventajas-de-los-patrones-de-arquitectura-👍)

4. [¿CÓMO DIFERENCIAR UN PATRÓN ARQUITECTÓNICO?](#❕-¿cómo-diferenciar-un-patrón-arquitectónico-❕)

5. [¿ QUÉ SON LOS ESTILOS ARQUITECTONICOS ?](#❕-¿cómo-diferenciar-un-patrón-arquitectónico-❕)

    5.1 [Estilos arquitectónicos de organización](#🗼-estilos-arquitectónicos-de-organización)

    5.2 [Estilos arquitectónicos de comportamiento](#🗼-estilos-arquitectónicos-de-comportamiento)

6. [Estrategias para elegir un estilo arquitectónico](#🔎-estrategias-para-elegir-un-estilo-arquitectónico-🔎)

7. [fUENTES](#fuentes)

# 🏭 ¿ QUÉ ES UN PATRON DE ARQUITECTURA ? 🏭

Un patrón de arquitectura es una solución general y reutilizable a un problema común en la arquitectura de software dentro de un contexto dado. Los patrones arquitectónicos son similares al patrón de diseño de software pero tienen un alcance más amplio.

Los patrones de arquitectura se utilizan para describir la estructura de un sistema de software, así como las relaciones entre sus componentes. Estos patrones pueden ayudar a los arquitectos de software a diseñar sistemas más flexibles, escalables y fáciles de mantener.

# 🌉 PATRONES DE ARQUITECTURA 🌉

Algunos de los patrones de arquitectura más comunes incluyen:

## 🔨 Patrón de capas 🔨


El patrón de capas es un patrón de arquitectura de software que divide un sistema en capas, cada una de las cuales tiene una responsabilidad específica. Este patrón se basa en el principio de separación de preocupaciones, que establece que las diferentes partes de un sistema deben estar separadas para que puedan ser desarrolladas, mantenidas y mejoradas de forma independiente.

*Ventajas*

El patrón de capas ofrece una serie de ventajas, entre las que se incluyen:

* Escalabilidad: El sistema se puede escalar verticalmente o horizontalmente agregando o quitando capas.

* Mantenibilidad: El sistema es más fácil de mantener porque las capas están separadas y cada capa es responsable de una tarea específica.

* Testabilidad: El sistema es más fácil de probar porque las capas pueden probarse de forma independiente.

*Desventajas*

El patrón de capas también tiene algunas desventajas, entre las que se incluyen:

* Complejidad: El patrón puede ser complejo de implementar y mantener.

* Rendimiento: El patrón puede reducir el rendimiento del sistema si las capas están mal diseñadas.

*Ejemplo*

Un ejemplo de patrón de capas es un sistema de gestión de pedidos. Este sistema podría dividirse en las siguientes capas:

* Capa de presentación: Esta capa es responsable de la interacción con el usuario.

* Capa de lógica de negocio: Esta capa es responsable de la lógica de negocios del sistema.

* Capa de acceso a datos: Esta capa es responsable de acceder a los datos del sistema.

En este ejemplo, la capa de presentación es responsable de mostrar los datos al usuario y de procesar las entradas del usuario. La capa de lógica de negocio es responsable de validar los datos del usuario y de realizar las operaciones comerciales necesarias. La capa de acceso a datos es responsable de acceder a la base de datos y de recuperar o almacenar los datos.

*Implementación*

El patrón de capas se puede implementar de diferentes maneras, dependiendo del lenguaje de programación y el framework utilizado. En general, el patrón se implementa utilizando clases o componentes que están organizados en capas. Las clases o componentes en cada capa están diseñados para trabajar juntos para realizar una tarea específica.

## 🔨 Patrón cliente-servidor 🔨


El patrón cliente-servidor es un patrón de arquitectura de software que divide un sistema en dos componentes: clientes y servidores. Los clientes solicitan servicios a los servidores, y los servidores proporcionan servicios a los clientes.

*Componentes*

Los componentes del patrón cliente-servidor son:

* Cliente: El cliente es un componente que solicita servicios al servidor.

* Servidor: El servidor es un componente que proporciona servicios al cliente.

*Comunicación*

La comunicación entre el cliente y el servidor se realiza a través de una red. El cliente envía una solicitud al servidor, y el servidor envía una respuesta al cliente.

*Ventajas*

El patrón cliente-servidor ofrece una serie de ventajas, entre las que se incluyen:

* Escalabilidad: El sistema se puede escalar verticalmente o horizontalmente agregando o quitando clientes o servidores.

* Mantenibilidad: El sistema es más fácil de mantener porque los clientes y los servidores están separados.

* Seguridad: El sistema es más seguro porque los clientes y los servidores no comparten datos.

*Desventajas*

El patrón cliente-servidor también tiene algunas desventajas, entre las que se incluyen:

* Complejidad: El patrón puede ser complejo de implementar y mantener.

* Rendimiento: El patrón puede reducir el rendimiento del sistema si la red es lenta.

*Ejemplos*

El patrón cliente-servidor se utiliza en una amplia gama de sistemas, entre los que se incluyen:

* Sistemas web: Los clientes son los navegadores web, y los servidores son los servidores web.

* Sistemas de correo electrónico: Los clientes son los clientes de correo electrónico, y los servidores son los servidores de correo electrónico.

* Sistemas de bases de datos: Los clientes son las aplicaciones de bases de datos, y los servidores son los servidores de bases de datos.

*Implementación*

El patrón cliente-servidor se puede implementar de diferentes maneras, dependiendo del lenguaje de programación y el framework utilizado. En general, el patrón se implementa utilizando clases o componentes que representan a los clientes y a los servidores. Las clases o componentes cliente se comunican con las clases o componentes servidor a través de una API.

## 🔨 Patrón maestro-esclavo 🔨


El patrón maestro-esclavo es un patrón de arquitectura de software que divide un sistema en dos partes: un maestro y uno o más esclavos. El maestro es responsable de coordinar el trabajo de los esclavos, mientras que los esclavos son responsables de realizar las tareas asignadas por el maestro.

En este patrón, el maestro es responsable de las siguientes tareas:

* Distribuir el trabajo entre los esclavos.

* Recopilar los resultados del trabajo de los esclavos.

* Combinar los resultados del trabajo de los esclavos para crear un resultado final.

Los esclavos son responsables de las siguientes tareas:

* Ejecutar las tareas asignadas por el maestro.

* Enviar los resultados de su trabajo al maestro.

* El patrón maestro-esclavo es una forma eficaz de distribuir el trabajo entre varios procesos o máquinas. Es especialmente útil en sistemas que requieren un alto rendimiento o una escalabilidad horizontal.

*Ventajas*

* Mejora el rendimiento al distribuir el trabajo entre varios procesos o máquinas.

* Aumenta la escalabilidad al permitir que el sistema se amplíe agregando más esclavos.

* Simplifica el desarrollo al separar las responsabilidades del maestro y los esclavos.

*Desventajas*

* El maestro es un punto único de fallo. Si el maestro falla, todo el sistema fallará.

* Puede ser difícil de implementar en sistemas complejos.

*Ejemplos*

* Sistemas de replicación de bases de datos, donde el maestro es la base de datos principal y los esclavos son las bases de datos de copia de seguridad.

* Sistemas de procesamiento de imágenes, donde el maestro es responsable de dividir la imagen en tareas más pequeñas y los esclavos son responsables de procesar las tareas individuales.

* Sistemas de renderizado de gráficos, donde el maestro es responsable de generar la escena y los esclavos son responsables de renderizar los objetos individuales.

*Implementación*

El patrón maestro-esclavo se puede implementar de muchas maneras diferentes. Una forma común de implementarlo es utilizando un modelo cliente-servidor. En este modelo, el maestro es el servidor y los esclavos son los clientes.

Otra forma de implementar el patrón maestro-esclavo es utilizando un modelo de comunicaciones entre procesos (IPC). En este modelo, el maestro y los esclavos se comunican entre sí a través de un mecanismo de IPC, como un tubo o una cola de mensajes.

## 🔨 Patrón de filtro de tubería 🔨

El patrón de filtro de tubería es un patrón de arquitectura de software que divide un proceso de procesamiento complejo en una serie de pasos independientes. Cada paso, o filtro, se encarga de una tarea específica. Los filtros se conectan entre sí mediante tuberías, que son mecanismos de comunicación que permiten que los datos fluyan de un filtro a otro.

El patrón de filtro de tubería es una forma eficaz de organizar el procesamiento de datos. Es especialmente útil en sistemas que requieren un alto grado de flexibilidad y modularidad.

*Estructura*

El patrón de filtro de tubería se compone de los siguientes elementos:

* Entrada: La entrada es la información que se proporciona al primer filtro.

* Filtros: Los filtros son los componentes que realizan las tareas de procesamiento.

* Tuberías: Las tuberías son los mecanismos de comunicación que permiten que los datos fluyan de un filtro a otro.

* Salida: La salida es la información que se genera por el último filtro.

*Funcionamiento*

El patrón de filtro de tubería funciona de la siguiente manera:

* La entrada se proporciona al primer filtro.

* El primer filtro procesa la entrada y genera una salida.

* La salida del primer filtro se envía al siguiente filtro.

* El proceso continúa hasta que la entrada se haya procesado por todos los filtros.

* La salida del último filtro es el resultado final del procesamiento.

*Ventajas*

El patrón de filtro de tubería ofrece las siguientes ventajas:

* Flexibilidad: El patrón de filtro de tubería es muy flexible, ya que permite agregar o eliminar filtros fácilmente.

* Modularidad: El patrón de filtro de tubería es modular, ya que los filtros se pueden desarrollar e implementar de forma independiente.

* Escalabilidad: El patrón de filtro de tubería es escalable, ya que se puede agregar más filtros para aumentar el rendimiento.

*Desventajas*

El patrón de filtro de tubería tiene las siguientes desventajas:

* Complejidad: El patrón de filtro de tubería puede ser complejo de implementar en sistemas grandes o complejos.

* Rendimiento: El patrón de filtro de tubería puede tener un impacto negativo en el rendimiento si se utilizan demasiados filtros o si los filtros son demasiado complejos.

*Ejemplos*

El patrón de filtro de tubería se puede utilizar en una amplia gama de sistemas, como:

* Sistemas de procesamiento de imágenes: El patrón de filtro de tubería se puede utilizar para procesar imágenes, como para aplicar filtros de nitidez o corrección de color.

* Sistemas de procesamiento de audio: El patrón de filtro de tubería se puede utilizar para procesar audio, como para reducir el ruido o aplicar efectos de sonido.

* Sistemas de análisis de datos: El patrón de filtro de tubería se puede utilizar para analizar datos, como para detectar patrones o anomalías.

*Implementación*

El patrón de filtro de tubería se puede implementar de muchas maneras diferentes. Una forma común de implementarlo es utilizando una arquitectura cliente-servidor. En este modelo, los filtros se implementan como servidores y la entrada y la salida se intercambian a través de una red.

Otra forma de implementar el patrón de filtro de tubería es utilizando un modelo de comunicaciones entre procesos (IPC). En este modelo, los filtros se comunican entre sí a través de un mecanismo de IPC, como un tubo o una cola de mensajes.

## 🔨 Patrón de intermediario 🔨

El patrón de intermediario es un patrón de arquitectura de software que permite que dos o más componentes se comuniquen entre sí sin conocerse directamente. El intermediario actúa como un intermediario entre los componentes, ocultando sus detalles de implementación y proporcionando un nivel de abstracción.

El patrón de intermediario es una forma eficaz de estructurar sistemas distribuidos. Es especialmente útil en sistemas que requieren un alto grado de flexibilidad y escalabilidad.

*Estructura*

El patrón de intermediario se compone de los siguientes elementos:

* Intermediario: El intermediario es el componente que actúa como intermediario entre los componentes.

* Componentes: Los componentes son los componentes que se comunican entre sí a través del intermediario.

*Funcionamiento*

El patrón de intermediario funciona de la siguiente manera:

* Los componentes envían solicitudes al intermediario.

* El intermediario recibe las solicitudes y las reenvía a los componentes apropiados.

* Los componentes destinatarios responden a las solicitudes.

* El intermediario recibe las respuestas y las devuelve a los componentes originales.

*Ventajas*

El patrón de intermediario ofrece las siguientes ventajas:

* Flexibilidad: El patrón de intermediario permite que los componentes se comuniquen entre sí sin conocer sus detalles de implementación.

* Escalabilidad: El patrón de intermediario es escalable, ya que se puede agregar más componentes sin afectar a la comunicación entre los componentes existentes.

* Mantenimiento: El patrón de intermediario facilita el mantenimiento del sistema, ya que el intermediario oculta los detalles de implementación de los componentes.

*Desventajas*

El patrón de intermediario tiene las siguientes desventajas:

* Complejidad: El patrón de intermediario puede ser complejo de implementar en sistemas grandes o complejos.

* Rendimiento: El patrón de intermediario puede tener un impacto negativo en el rendimiento si el intermediario es demasiado complejo o si la comunicación entre el intermediario y los componentes es lenta.

*Ejemplos*

El patrón de intermediario se puede utilizar en una amplia gama de sistemas, como:

* Sistemas distribuidos: El patrón de intermediario se puede utilizar para coordinar la comunicación entre componentes distribuidos.

* Sistemas de seguridad: El patrón de intermediario se puede utilizar para proporcionar seguridad a la comunicación entre componentes.

* Sistemas de registro: El patrón de intermediario se puede utilizar para registrar la comunicación entre componentes.

*Implementación*

El patrón de intermediario se puede implementar de muchas maneras diferentes. Una forma común de implementarlo es utilizando una arquitectura cliente-servidor. En este modelo, el intermediario se implementa como un servidor y los componentes se implementan como clientes.

Otra forma de implementar el patrón de intermediario es utilizando un modelo de comunicaciones entre procesos (IPC). En este modelo, el intermediario y los componentes se comunican entre sí a través de un mecanismo de IPC, como un tubo o una cola de mensajes.

*Ejemplos específicos*

El patrón de intermediario se puede utilizar en una amplia gama de sistemas, como:

* En un sistema de mensajería instantánea, el intermediario puede ser utilizado para coordinar la comunicación entre los usuarios.

* En un sistema de comercio electrónico, el intermediario puede ser utilizado para proporcionar seguridad a la comunicación entre el cliente y el servidor.

* En un sistema de análisis de datos, el intermediario puede ser utilizado para registrar la comunicación entre los componentes.

* En cada caso, el intermediario proporciona un nivel de abstracción que permite que los componentes se comuniquen entre sí sin conocer sus detalles de implementación. Esto facilita el mantenimiento del sistema y lo hace más flexible y escalable.

## 🔨 Patrón de igual a igual 🔨


El patrón de igual a igual, también conocido como peer-to-peer (P2P), es un patrón de arquitectura de software en el que los componentes se comunican entre sí de forma simétrica. Esto significa que no hay un componente que actúe como servidor y otros componentes que actúen como clientes. Todos los componentes son iguales y pueden comunicarse entre sí de forma directa.

El patrón de igual a igual es una forma eficaz de estructurar sistemas distribuidos. Es especialmente útil en sistemas que requieren un alto grado de flexibilidad y escalabilidad.

*Estructura*

El patrón de igual a igual se compone de los siguientes elementos:

* Componentes: Los componentes son los componentes que se comunican entre sí de forma simétrica.
Funcionamiento

El patrón de igual a igual funciona de la siguiente manera:

* Los componentes se conectan a una red.

* Los componentes intercambian información entre sí.

*Ventajas*

El patrón de igual a igual ofrece las siguientes ventajas:

* Flexibilidad: El patrón de igual a igual permite que los componentes se comuniquen entre sí de forma directa, sin necesidad de un servidor central.

* Escalabilidad: El patrón de igual a igual es escalable, ya que se puede agregar más componentes sin afectar a la comunicación entre los componentes existentes.

* Resistencia a fallos: El patrón de igual a igual es resistente a fallos, ya que la pérdida de un componente no afecta a la comunicación entre los demás componentes.

*Desventajas*

El patrón de igual a igual tiene las siguientes desventajas:

* Complejidad: El patrón de igual a igual puede ser complejo de implementar en sistemas grandes o complejos.

* Seguridad: El patrón de igual a igual puede ser vulnerable a ataques, ya que los componentes están directamente expuestos a la red.

*Ejemplos*

El patrón de igual a igual se puede utilizar en una amplia gama de sistemas, como:

* Redes de intercambio de archivos: El patrón de igual a igual se puede utilizar para compartir archivos entre usuarios.

* Sistemas de chat: El patrón de igual a igual se puede utilizar para que los usuarios se comuniquen entre sí.

* Sistemas de juegos en línea: El patrón de igual a igual se puede utilizar para que los jugadores jueguen entre sí.

*Implementación*

El patrón de igual a igual se puede implementar de muchas maneras diferentes. Una forma común de implementarlo es utilizando un modelo de comunicaciones entre procesos (IPC). En este modelo, los componentes se comunican entre sí a través de un mecanismo de IPC, como un tubo o una cola de mensajes.

Otra forma de implementar el patrón de igual a igual es utilizando un protocolo de red P2P. En este modelo, los componentes se comunican entre sí a través de una red P2P, como BitTorrent o Gnutella.

## 🔨 Patrón de bus de evento 🔨

El patrón de bus de evento es un patrón de arquitectura de software que permite a los componentes de un sistema comunicarse entre sí mediante la publicación y suscripción a eventos. Un evento es un cambio significativo en el estado de un componente.

El patrón de bus de evento es una forma eficaz de organizar la comunicación entre componentes en sistemas distribuidos. Es especialmente útil en sistemas que requieren un alto grado de flexibilidad y escalabilidad.

*Estructura*

El patrón de bus de evento se compone de los siguientes elementos:

* Eventos: Los eventos son los mensajes que se envían entre los componentes.

* Publicadores: Los publicadores son los componentes que envían eventos.

* Suscriptores: Los suscriptores son los componentes que reciben eventos.

* Bus de eventos: El bus de eventos es el componente que transmite los eventos entre los publicadores y los suscriptores.

*Funcionamiento*

El patrón de bus de evento funciona de la siguiente manera:

* Los publicadores publican eventos en el bus de eventos.

* Los suscriptores se suscriben a eventos específicos en el bus de eventos.

* El bus de eventos transmite los eventos a los suscriptores suscritos.

*Ventajas*

El patrón de bus de evento ofrece las siguientes ventajas:

* Flexibilidad: El patrón de bus de evento permite que los componentes se comuniquen entre sí de forma independiente.

* Escalabilidad: El patrón de bus de evento es escalable, ya que se puede agregar más componentes sin afectar a la comunicación entre los componentes existentes.

* Resistencia a fallos: El patrón de bus de evento es resistente a fallos, ya que la pérdida de un componente no afecta a la comunicación entre los demás componentes.

*Desventajas*

El patrón de bus de evento tiene las siguientes desventajas:

* Complejidad: El patrón de bus de evento puede ser complejo de implementar en sistemas grandes o complejos.

* Rendimiento: El patrón de bus de evento puede tener un impacto negativo en el rendimiento si el bus de eventos es demasiado complejo o si la comunicación entre el bus de eventos y los componentes es lenta.

*Ejemplos*

El patrón de bus de evento se puede utilizar en una amplia gama de sistemas, como:

* Sistemas de mensajería: El patrón de bus de evento se puede utilizar para enviar mensajes entre usuarios.

* Sistemas de comercio electrónico: El patrón de bus de evento se puede utilizar para notificar a los usuarios sobre cambios en el estado de sus pedidos.

* Sistemas de seguridad: El patrón de bus de evento se puede utilizar para notificar a los componentes de seguridad sobre eventos de seguridad.

*Implementación*

El patrón de bus de evento se puede implementar de muchas maneras diferentes. Una forma común de implementarlo es utilizando un modelo de comunicaciones entre procesos (IPC). En este modelo, el bus de eventos se implementa como un componente que utiliza un mecanismo de IPC, como un tubo o una cola de mensajes.

Otra forma de implementar el patrón de bus de evento es utilizando un servicio de mensajería. En este modelo, el bus de eventos se implementa como un servicio que utiliza un protocolo de mensajería, como AMQP o MQTT.

*Ejemplos específicos*

El patrón de bus de evento se puede utilizar en una amplia gama de sistemas, como:

* En un sistema de mensajería instantánea, el bus de evento puede ser utilizado para notificar a los usuarios sobre nuevos mensajes.

* En un sistema de comercio electrónico, el bus de evento puede ser utilizado para notificar a los usuarios sobre cambios en el estado de sus pedidos.

* En un sistema de seguridad, el bus de evento puede ser utilizado para notificar a los componentes de seguridad sobre eventos de seguridad.

* En cada caso, el bus de evento proporciona un mecanismo para que los componentes se comuniquen entre sí de forma independiente. Esto facilita el mantenimiento del sistema y lo hace más flexible y escalable.

## 🔨 Modelo-vista-controlador 🔨

MVC, o Modelo-Vista-Controlador, es un patrón de arquitectura de software que separa la lógica de la aplicación en tres componentes principales: el modelo, la vista y el controlador.

*Modelo*

El modelo es responsable de almacenar los datos y la lógica de negocios de la aplicación. El modelo no tiene ninguna interacción directa con la vista o el controlador.

*Vista*

La vista es responsable de mostrar la información al usuario. La vista no tiene ninguna interacción directa con el modelo o el controlador.

*Controlador*

El controlador es responsable de manejar las interacciones del usuario. El controlador recibe las entradas del usuario y las envía al modelo para que se procesen. El controlador también recibe los resultados del modelo y los envía a la vista para que se muestren.

*Ventajas*

El patrón MVC ofrece las siguientes ventajas:

* Separación de preocupaciones: El patrón MVC separa la lógica de la aplicación en tres componentes principales, lo que facilita el mantenimiento y la evolución de la aplicación.

* Flexibilidad: El patrón MVC permite que los componentes se puedan intercambiar o actualizar de forma independiente.

* Escalabilidad: El patrón MVC es escalable, ya que los componentes se pueden distribuir en diferentes máquinas.

*Desventajas*

El patrón MVC tiene las siguientes desventajas:

* Complejidad: El patrón MVC puede ser complejo de implementar en sistemas grandes o complejos.

* Rendimiento: El patrón MVC puede tener un impacto negativo en el rendimiento si el controlador es demasiado complejo o si la comunicación entre el controlador y los componentes es lenta.

*Ejemplos*

El patrón MVC se puede utilizar en una amplia gama de sistemas, como:

* Aplicaciones web: El patrón MVC es el patrón de arquitectura más utilizado para aplicaciones web.

* Aplicaciones de escritorio: El patrón MVC se puede utilizar para aplicaciones de escritorio.

* Aplicaciones móviles: El patrón MVC se puede utilizar para aplicaciones móviles.

*Implementación*

El patrón MVC se puede implementar de muchas maneras diferentes. Una forma común de implementarlo es utilizando un modelo de vista de controlador (MVC) de tres capas. En este modelo, el modelo, la vista y el controlador se implementan como tres capas separadas.

Otra forma de implementar el patrón MVC es utilizando un modelo de vista de controlador (MVC) de una capa. En este modelo, el modelo, la vista y el controlador se implementan como una sola capa.

# 👍 VENTAJAS DE LOS PATRONES DE ARQUITECTURA 👍

Aquí hay algunos de los beneficios de utilizar patrones de arquitectura:

* Reutilización: Los patrones de arquitectura se pueden reutilizar en diferentes proyectos. Esto ahorra tiempo y esfuerzo a los arquitectos de software.

* Flexibilidad: Los patrones de arquitectura pueden adaptarse a diferentes necesidades. Esto permite a los arquitectos de software diseñar sistemas que sean flexibles y escalables.

* Mantenibilidad: Los patrones de arquitectura pueden ayudar a los arquitectos de software a diseñar sistemas que sean fáciles de mantener. Esto reduce el costo de mantenimiento a largo plazo.


# ❕ ¿CÓMO DIFERENCIAR UN PATRÓN ARQUITECTÓNICO? ❕

Para diferenciar un patrón arquitectónico, se pueden tener en cuenta los siguientes criterios:

🔹 *Nivel de abstracción:* Los patrones arquitectónicos se centran en la estructura global de un sistema, mientras que los patrones de diseño se centran en el diseño de componentes individuales.

🔹 *Ámbito:*  Los patrones arquitectónicos se centran en problemas comunes en la arquitectura de software, mientras que los patrones de diseño se centran en problemas comunes en el diseño de software.

🔹 *Estructura:* Los patrones arquitectónicos definen la estructura global de un sistema, mientras que los patrones de diseño definen la estructura de componentes individuales.

🔹 *Comportamiento:* Los patrones arquitectónicos definen el comportamiento de un sistema, mientras que los patrones de diseño definen el comportamiento de componentes individuales.


# ¿ QUÉ SON LOS ESTILOS ARQUITECTONICOS ?❓❓❓

Los estilos arquitectónicos son un conjunto de principios y prácticas que se utilizan para diseñar sistemas de software. Los estilos arquitectónicos proporcionan una plantilla para la estructura y el comportamiento de un sistema, y pueden ayudar a los arquitectos a diseñar sistemas más eficientes, escalables y adaptables.

Los estilos arquitectónicos se pueden clasificar en dos categorías principales:

## 🗼 Estilos arquitectónicos de organización: 

Estos estilos se centran en la estructura global de un sistema. Definen la relación entre los componentes de un sistema y cómo se comunican entre sí.

## 🗼 Estilos arquitectónicos de comportamiento: 

Estos estilos se centran en el comportamiento de un sistema. Definen cómo los componentes de un sistema interactúan entre sí para lograr un objetivo.

# 🔎 Estrategias para elegir un estilo arquitectónico: 🔎

Al elegir un estilo arquitectónico, los arquitectos deben considerar los siguientes factores:

☑️ *Los requisitos del sistema:*  Los arquitectos deben considerar los requisitos funcionales y no funcionales del sistema al elegir un estilo arquitectónico.

☑️ *Las limitaciones del sistema:* Los arquitectos deben considerar las limitaciones del sistema, como la plataforma de hardware y software, al elegir un estilo arquitectónico.

☑️ *Las preferencias del equipo:* Los arquitectos deben considerar las preferencias del equipo de desarrollo al elegir un estilo arquitectónico.

# FUENTES

<href link="https://refactoring.guru/es/design-patterns/factory-method">https://refactoring.guru/es/design-patterns/factory-method</href>

<href link="https://github.com/publiosilva/design-patterns-hands-on">https://github.com/publiosilva/design-patterns-hands-on</href>
