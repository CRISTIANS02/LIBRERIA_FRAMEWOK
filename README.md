# *Los mejores frameworks de desarrollo web de Python*

![Alt text](DZq7DBfj_400x400-removebg-preview.png)


   > Python es uno de los lenguajes de programación más populares y fáciles de aprender y se usa en casi todas partes, incluido el desarrollo web. Hay muchos frameworks para esto, algunos de los cuales no solo facilitan el desarrollo, sino que también brindan herramientas que le permiten crear un sitio terminado en solo unos días.

   > Dichos frameworks pertenecen a la categoría de pila completa. Son geniales, tienen un montón de herramientas y todo está incluido, pero eso puede hacerlos pesados, lentos e inflexibles. Además de los frameworks full-stack, existen otros, como los micro-frameworks o los frameworks asíncronos.

## *Frameworks de pila completa.*

   >Hay todo lo que necesita para crear una aplicación: arquitectura MVC (Model-View-Controller), implementación de ORM, motor de plantillas, enrutamiento y todo lo demás. Dichos frameworks son adecuados para todas las tareas, pero para proyectos más pequeños puede arreglárselas con algo menos voluminoso
   > microestructuras. Incluyen solo componentes básicos y están diseñados para el desarrollo rápido de proyectos relativamente pequeños. Es posible que no tengan, por ejemplo, validación de formularios o una interfaz para la base de datos, por lo que habrá que agregar o conectar algo de bibliotecas de terceros. Algunos microframeworks escalan fácilmente según sea necesario.

## *Tramas asíncronas.*
   > El principio básico es que las tareas no deben ejecutarse secuencialmente: la siguiente puede comenzar a contar antes de que finalice la anterior. Dado que normalmente lleva mucho más tiempo transferir los datos al usuario y esperar su respuesta que el propio servidor, dichos frameworks no pierden el tiempo esperando. Esto les permite gestionar un gran número de conexiones al mismo tiempo.

   >La principal ventaja de los frameworks de pila completa es que ya tienen todo lo que necesita para una aplicación completa. No es necesario buscar bibliotecas separadas para cada tarea pequeña y pensar en la compatibilidad, por lo que incluso los principiantes pueden crear rápidamente una aplicación de trabajo lista para usar. En este artículo, hablaremos sobre estos frameworks.

     • Django
     • Pirámide
     • Turboengranajes
     • Matraz
     • Ciclón

# *Django*
 > Un framework de alto nivel diseñado para un desarrollo rápido y eficiente. Su arquitectura está diseñada de tal manera que ahorre su tiempo y esfuerzo tanto como sea posible y, en el futuro, el tiempo y el dinero de los clientes. Los fundamentos de la filosofía de Django -DRY y desarrollo rápido- fomentan la reutilización del código y reducen la redundancia.
## *Características*
      •  Control de versiones de base de datos (migraciones).
      •  Motor de plantillas propio.
      •  Asignaciones relacionales de objetos (ORM).
      •  Enrutamiento de URL.
      •  Soporte de servidor web.
      •  Soporte de autenticación.
      •  Apoyo a la internacionalización.

## *Ventajas*

 ###  _Toneladas de bibliotecas._ 
 >La funcionalidad básica no necesita ser escrita por usted mismo; ya se ha escrito mucho, todo lo que queda es importar las bibliotecas apropiadas. La calidad de las bibliotecas de Django es generalmente confiable.
### _Comunidad y Documentación._
 Django tiene una extensa documentación y una comunidad amigable, por lo que siempre puede descubrir qué funciona o preguntar a los expertos.
### _Escalabilidad._
>Si no tiene idea de qué tan grande será su proyecto, o si crecerá (como suelen hacer las nuevas empresas), Django le permite comenzar de a poco y crecer según sea necesario.
## *Los menos*
 * Django no es compatible con WebSockets de fábrica, por lo que no es adecuado para el trabajo en tiempo real.
* Las bibliotecas listas para usar generalmente son buenas, pero a menudo reducen la flexibilidad.
  
*¿Dónde se usa?*
* Instagram es una red social para compartir fotos y videos.

* Spotify es una plataforma de música que recomienda música a los usuarios en función de sus preferencias.

Django es uno de los frameworks más populares, muchos estudios web trabajan con él, por lo que es importante poder usarlo si vas a trabajar en tecnologías web. Puede aprenderlo y otras herramientas necesarias para un desarrollador web en el curso SkillFactory.

# *Pirámide*
>Si quieres algo más minimalista, te puede gustar Pyramid. Este framework es adecuado para proyectos de cualquier tamaño. Tiene funciones útiles para crear aplicaciones complejas o escalar inicialmente sitios pequeños para aumentar la carga.

## Características

 * Herramientas útiles para trabajar con recursos estáticos.
 * Predicados y renderizadores.
 * Generación de URL.
## Ventajas
 
### Flexibilidad y facilidad de personalización. 
 > Se puede reemplazar cualquier componente del framework, ya sea una base de datos o un motor de plantillas. Incluso puede usar varios componentes diferentes al mismo tiempo (por ejemplo, conectar dos bases de datos diferentes).
### Solicitudes prácticas de Ajax. 
 Gracias al sistema de decoradores y vistas, puedes enviar solicitudes XHR sin ningún esfuerzo adicional por parte del desarrollador.
### soporte de alquimia SQL.
 SQLAlchemy proporciona una experiencia de base de datos cómoda incluso para consultas complejas.

*Los menos*
 La implementación y preparación para el desarrollo lleva tiempo.
 Para hacer la personalización, necesitas conocer bien Pyramid.
 Para aplicaciones simples, SQLAlchemy puede resultar difícil de manejar.

*¿Dónde se usa?*

>Charte.ca es un editor de mapas en línea para no especialistas.
Easy Blog Networks es un proveedor de alojamiento.
Substance-D es un entorno de desarrollo de aplicaciones web.
# *TurboGears*
Sitio web | PIS | Centro Git | Desbordamiento de Pila

TurboGears es un framework de código abierto para el desarrollo rápido de aplicaciones que funcionan con datos. Es compatible con SQLAlchemy, Genshi, WebOb y Repoze, por lo que TurboGears es ideal para cualquier sistema que necesite un buen soporte de base de datos.

## Características
* Compatibilidad con la partición de datos horizontal.
* Integración con la librería javascript de MochiKit.
* Soporte para múltiples bases de datos al mismo tiempo.
* Soporte de arquitectura MVC.
* Widgets Tosca.
* Plantillas PasteScript.
* Valide a través de FormEncode.
## Ventajas
### Flexibilidad.  
TurboGears se puede utilizar como un microframeworkpara la creación rápida de prototipos y como un framework completo para respaldar proyectos a gran escala.
### Extensibilidad.  
Puede crear sus propios complementos o agregar funcionalidad a los existentes.
Los menos
Tiene tantas opciones de expansión que es fácil perderse.

*¿Dónde se usa?* 

Apache Allura es una plataforma de gestión de repositorios de código en línea creada por SourceForge.
Kamisons es un sitio de venta de paraguas.
# *Matraz*
Flask es un framework WSGI que es adecuado tanto para sitios simples como para plataformas complejas. Es compatible con bibliotecas de terceros y tiene muchas extensiones.

## Características
* Depurador incorporado rápido.
* Servidor de desarrollo integrado.
* Modelos Jinja2.
* Soporte para solicitudes REST.
* Compatible con cualquier ORM.
* Cookies seguras para la gestión de sesiones en el cliente.
* Soporte de pruebas unitarias.
* Cumple con WSGI 1.0.
## Ventajas
Framework minimalista claro. 
Es bastante fácil entender qué está pasando exactamente y qué proceso es responsable de qué. La lógica de trabajo no cambia de una versión a otra.
Prototipo rápido. Todas las herramientas que necesita para crear un prototipo funcionan de inmediato.

*Los menos*

El framework es de un nivel relativamente bajo, por lo que primero debe comprenderlo, y los requisitos para el nivel de programador son más altos que otros. Si no quiere saber qué y cómo funciona bajo el capó, pero crea sitios web de inmediato, es mejor elegir otra cosa.

*¿Dónde se usa?*

* Rainist es una plataforma de gestión de finanzas personales en línea.
* Netflix es una de las plataformas de streaming más grandes del mundo.
* Lyft es una plataforma de pedidos de taxis y alquiler de vehículos.
# Ciclón
>
Un framework asíncrono, gracias a un intercambio de datos sin bloqueo, capaz de soportar simultáneamente numerosas conexiones de usuarios. Perfecto para tareas que requieren una larga conexión con cada usuario.

## Características
* Tiene su propio mecanismo de autenticación, si es necesario, puede conectar a terceros.
* Soporte para traducciones y localización.
* Trabaja en tiempo real.

*¿Dónde se usa?*

Uploadcare es un servicio en la nube para trabajar con archivos.
En el artículo, hablamos solo sobre los frameworks más populares. Algunos son más flexibles, otros son fáciles de usar; algunos son más adecuados para proyectos pequeños, mientras que otros son más adecuados para proyectos más grandes. Pero todos ellos de alguna manera simplifican el desarrollo y le permiten trabajar en su proyecto, no en interfaces a bases de datos o análisis de consultas.

>Python y sus framework son solo una parte de lo que un desarrollador web necesita saber. También debería poder trabajar con HTML, CSS, SQL y otras herramientas. Todo esto se discutirá en el curso SkillFactory, después del cual tendrá un conjunto básico de conocimientos y habilidades para comenzar a trabajar como desarrollador web.