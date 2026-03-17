[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/-s1_zvqh)
# SDLC-Lab01

- Requisitos de entrega y aprobacion:
  - Respetar el formato Markdown.
  - Solo se aceptan los trabajos por GitHub Classroom
  - Todas las respuestas deben realizarse en el archivo **README.md** del repositorio asignado..
  - El Trabajo en individual. Si bien se puede realizar de forma grupal, la entrega es siempre ***individual***
  - Defensa individual
  - Respetar las fechas de entraga. No se aceptan las actividades fuera de termino.

> Si surge algún cambio o aclaración adicional, se comunicará durante la clase.

### Actividad 1
Teniendo en cuenta el material de clase, responda las siguientes preguntas:

1. ¿Por qué el desarrollo de software no puede realizarse simplemente comenzando a programar?

   R:porque el desarrollo de software requiere seguir una serie de pasos como analisis,diseño,codificacion, prueba y finalmente la puesta en marcha, sin estos paso probablemente el resultado no cumplir con las expectativas del cliente y resultar en perdida de tiempo y dinero,

2. ¿Qué significa que un desarrollo sea dirigido por un plan?

   R: que un desarrollo sea dirigido por un plan significa que primero comenzara analizando las necesidades del cliente, y en base a estas, elaborar un plan detallado para desarrollar el software. este plan sera el encargado de dirigir el desarrollo en una serie de etapas sucesivas hasta su funcionamiento.

3. ¿Cuáles son las ventajas de utilizar un plan de desarrollo?

   R: las ventajas son: presupuestar costos, estimar el tiempo de desarrollo, el desarrollo se vuelve mas predecible con etapas secuenciales previamente definididas.
   

5. ¿Qué críticas se hacen a los modelos tradicionales de desarrollo?

   R: las criticas que se hacen son que rara vez los proyectos de software son tan lineales, hay poca interaccion con el cliente, los errores u omisiones de una etapa se arrastrar con facilidad a etapas posteriores, los requerimientos de desarrollo deben obtenerse al comienzo sin posibilidad de cambio y es dificil aplicarlo en proyectos grandes.

6. ¿Por qué en la práctica muchas organizaciones combinan metodologías ágiles y modelos dirigidos por un plan?

   R: las organizaciones combinan metodologias agiles y dirigidos por un plan por que ya el modelo dirigido por un plan tiene una base y usan el modelo agile para mejorarlo. en la practica las organizaciones usan la metodologia dirigida para un plan en las etapas de analisis y diseño ya para tener una base solida y bien definida y luego en las etapas de codificacion y pruebas utilizan el modelo agile para entregar resultados pequeños y adaptsarse a los cambios que surjan hasta llegar al proyecto final. 


### Actividad 2

| Etapa                         | Descripción |
| ----------------------------- | ----------- |
| Análisis                      | en esta etapa se genera la idea, de ver que va ser ese sistema. en esta etapa el equipo de analisis se reune con el cliente y empiezan a ver los detalles del sistema, que quieren que haga el sistema, que alcances y que limitaciones tendra, y se crea un presupuesto para ello. de todo esto se genera un documento que capture todos los requerimientos del usuario y sus limitaciones.            |
| Diseño                        |  en esta etapa se elabora el diseño de una solucion informatica que aborde los problemas identificados en la etapa anterior y respetando las limitaciones. se genera un documento detallado y tecnico que permita a los desarrolladores construir un codigo de manera efectiva.           |
| Codificación                  | en esta etapa son los programadores son los encargados de desarollar el codigo segun las especificaciones del diseño, donde construyen el software empleando un lenguaje de programacion determinado.            |
| Prueba                        | en esta etapa de prueba se encargara de indentificar los posibles errores en el sistema antes de su puesta en uso, con el objetivo de reportarlos y corregirlos            |
| Puesta en marcha / Despliegue | en esta etapa finalmente se instala el softare en la computadora del cliete y se capacita a los usuariospara que puedan utilizar eficientemente el nuevo software.            |


* Luego responda:
  * ¿En qué etapa se obtienen los requerimientos del sistema?
    
    R: los requerimientos del sistema se obtienen en la Etapa de ANALISIS.
  * ¿En qué etapa se construye el programa?

    R: El programa se construye en la Etapa de CODIFICACION.
  * ¿Cuál es el objetivo principal de las pruebas?
    
    R: El objetivo de principal de las pruebas es encontrar posibles errores en el sistema y reportarlos para que sean corregidos.
### Actividad 3
Ordene las siguientes etapas según corresponda  Diseño
-al modelo lineal secuencial:
- Codificación
- Prueba
- Diseño
- Despliegue
- Ingeniería de requerimientos
---
R:
- Ingeniería de requerimientos
- Diseño
- Codificación
- Prueba
- Despliegue

- Luego responder:
  * ¿Qué problema puede surgir si hay un error en una etapa inicial?
    
    R: los problemas que pueden surgir si hay un error en una etapa inicial dependera de su gravedad.si es minimo, como un nombre o logo mal definido en la etapa de ANALISIS que se puede corregir facilmente. pero si problema afecta al diseño los programadores desarrollaran un codigo sobre un diseño mal hecho o no del todo. esto puede provocar fallos en el sistema, mayores costos, retrasos y hasta en los casos mas extremo el fracaso del proyecto y perdida de un cliente.
  * ¿Por qué este modelo puede ser problemático cuando los requerimientos cambian?

    R: este modelo puede ser un problema cuando los requerimientos cambian por al ser un modelo tan rigido los cambios son costosos y retrasan el proyecto mas tiempo. por que se requiere que se vuelva a realizar un analisis, un diseño, devuelta la codificacion lo que puede provocar que al final el proyecto no cumpla con los requisitos del cliente.
### Actividad 4
Complete la siguiente tabla.
| Modelo      | Característica principal | Cuándo conviene usarlo |
| ----------- | ------------------------ | ---------------------- |
| Cascada     | la caracteristica principal es que es un modelo secuencial.  se deben seguir una secuencia de pasos para pasar a la siguiente etapa, y en cada etapa de debe hacernun documento detallado antesvde pasar a la siguiente. | conviene usarlo para proyectos sencillos, si se tiene bajos presupuesto por que es el modelo menos costoso y el mas rapido.                        |
| Incremental | en este modelo a diferencia del lineal o secuencial que se basa en desarrollar el software de forma completa. este modelo se encarga de entregar el software en partes, de este modo ya el usuario puede tener la primera version con algunas funcionalidades y una vez ya implementado se vuelve a realizar el modelo lineal secuencial para entregar un nuevo modelo mas completo.                          | conviene usarlo cuando no se tiene presupuesto para todo el proyecto de una vez y se entregan algunas partes del software.|
| Prototipos  |este modelo se basa en construir una version acotada del software original para que el cliente pueda interactuar y ver como se hara el software y si da el okay se desecha el prototipo y se empieza el desarrollo del software.                        | conviene usarlo cuando el cliente no sabe del todo lo que quiere, para probar partes del software tecnicamente complejas.                         |
| Espiral     |                          |                        |
| RAD         |                          |                        |

- Responder:
  - ¿Qué modelo es más adecuado cuando existen muchos riesgos en el proyecto?
  - ¿Qué modelo ayuda a comprender mejor los requerimientos del usuario?
    
### Actividad 5 – Caso práctico
Una empresa quiere desarrollar un sistema de ventas para un pequeño comercio.

**Características del proyecto:**
- Sistema relativamente pequeño
- Pocos usuarios
- Requerimientos claros
- Tiempo limitado

**Preguntas**

- ¿Qué modelo de desarrollo recomendaría? 

  R: 
- Justifique su respuesta.

  R:
- ¿Qué etapas principales tendría el desarrollo?

  R:

### Actividad 7 – Verdadero o Falso
Indique si las siguientes afirmaciones son Verdaderas (V) o Falsas (F). ***marcar con x la verdaderas, dejar en blanco las falsas***

1. [ ] El modelo en cascada permite cambios constantes en los requerimientos.
2. [ ] El modelo incremental entrega el sistema en varias versiones.
3. [ ] Un prototipo se utiliza para comprender mejor los requerimientos.
4. [ ] El modelo RAD busca reducir los tiempos de desarrollo.
5. [ ] El modelo en espiral incorpora el análisis de riesgos.
