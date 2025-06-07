# Curso rxJava - 2019
## 🇲🇽 Español
## Contexto
Este repositorio contiene ejercicios recuperados de un curso que impartí en 2019 sobre la libreria rxJava. Debido a que este curso fue impartido en México, gran parde del codigo está en **español**.
## Que puedes encontrar 
- Una introducción a la programación reactiva.
- Dado que este repositorio proviene de un curso, encontrarás algunos métodos que requieren implementación. Si decides usar este repositorio para aprender, te recomiendo encarecidamente que implementes esos métodos por tu cuenta.
- Codigo de algun asistente al curso, en especial en `CLI`, el proyecto final, econtraras versiones declarativas e imperativas. Le llamamos _Funcional-Reactivo_ y _Objetos-Reactivos_

# Requerimientos
- Java 8 
  - Debido al uso de tools.jar se recomienda **OpenJDK 1.8** (o bien ajusta los assert por tu cuenta )
- rxJava 1.1.8
  
## Sobre el orden
Si decides utilizar este repositorio para aprender rxJava o embarcarte en la `programación reactiva` este es el orden que te recomiendo seguir:
- principales
  -  [`HolaObserver.java`](./src/main/java/principales/HolaObserver.java)
  -  HolaSuscripcion.java
  -  HolaSucriptor.java
  -  HolaCreador.java
  -  HolaFunciones.java
  -  HolaInfinito.java
  -  HolaInfinitoControlado.java
- noticias (proyecto guiado)
- sesion06
- sesion07
- cli (proyecto final del curso)
  - opc2
  - opc1
    - frp (un approach declarativo, programación funcional)
    - oor (un approach OO)
  
  ##  ¿Quieres contribuir?
 Sientete libre de hacer un fork y enviar pull request.

## 🇬🇧 English
## About
This repository contains exercises recovered from a course I taught in Mexico in 2019 about the RxJava library. Since the course was taught in Mexico, most of the code is in Spanish.
## What will you find 
- An introduction to reactive programming.
- Since this repo comes from a course, you'll find some methods that are left for implementation. If you decide to use this repo for learning, I highly recommend implementing those methods by yourself.
- You'll find code and solutions from course attendees, especially the `CLI` (final project). These apply "paradigms" we call _Functional-Reactive_ and _Reactive-Objects_.
# Requirements
- Java 8 (OpenJDK 1.8)
  - Since tools.jar is used **OpenJDK** **1.8** is **highly recommended** Alternatively, you can fix this by adding tools.jar to the classpath or by updating the Assert invocations.
- rxJava 1.1.8 (check the pom.xml)
