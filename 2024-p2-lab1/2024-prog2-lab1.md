# Proyecto de Programación - Sistema de Gestión de Tareas Pendientes

**Materia:** Programación 2

## Objetivos del proyecto:
- Reforzar los conceptos de programación orientada a objetos, y estructuras de datos lineales, en particular listas enlazadas.
- Practicar el uso de la noción de orden y análisis de algoritmos , en este caso en listas enlazadas.
- Fomentar el trabajo en equipo y la colaboración entre estudiantes mediante aprendizaje basado en proyectos

## Contenidos que se ejercitan:
- Programación orientada a objetos (POO).
- Análisis de algoritmos y notación asintótica.
- Implementación y manejo de estructuras de datos (listas enlazadas).
- Entrada y salida de datos.
- Comentarios y documentación del código.
- Validacion, verificacion y testing

# Consigna de trabajo:
Se les entregará dos archivos tareas.py y tareas.csv que un sistema de gestión de tareas pendientes (un todo list) que permita a los usuarios agregar, eliminar y marcar tareas como completadas. Además, el sistema debe ofrecer funcionalidades adicionales como la priorización de tareas, la organización por categorías y la generación de informes sobre el progreso. Los estudiantes deberán completar y mejorar el código según las siguientes instrucciones:

## Tareas del proyecto

1. **Comentar el código:** Cada línea de código debe estar comentada explicando su función y cómo contribuye al funcionamiento del programa.

2. **Comprender de una estructura de datos:** Esta estructura de datos ya se encuentra funcionando, deberán leerla, entenderla y explicarla en un informe (ver mas abajo la estructura del informe)
   - Utilizar una lista enlazada ordenada para almacenar las tareas pendientes.
   
3. **Agregar validaciones:** Deberán agregar validaciones para el correcto funcionamiento del programa
   - * Verificar si la tarea ya existe antes de agregarla.
   - * Mostrar un mensaje de error si se intenta eliminar o marcar una tarea que no existe. 
   - * Incorpore otras validaciones que consideren necesarias. 

4. **Funciones básicas del sistema:**
    De las siguientes funcionalidades, implemente las que estan marcadas con asterisco.
   - Agregar una nueva tarea.
   - * Marcar una tarea como completada.
   - Eliminar una tarea existente.
   - Mostrar todas las tareas.
   - * Mostrar tareas pendientes.
   - * Buscar una tarea por su descripcion (busca si existe una tarea con una descripción, esto sirve para chequear si existe antes de crearla)

5. **Características avanzadas:**
    De las siguientes funcionalidades, implemente las que estan marcadas con asterisco.
   - Priorizar tareas según su importancia.
   - Mostrar las tareas de una categorías indicada por el usuario. *
   - * Mostrar tareas por descripcion. Toma un texto y muestra todas las tareas que tengan ese texto en la descripcion. 
   - Generar informes sobre el progreso de las tareas, incluyendo el número de tareas completadas y las próximas a vencer por cada categoría. (una de las funciones a implementar es  numero_tareas_pendientes_lineal) * 

6. **Análisis y optimización:**
   - Calcule el orden del metodo agregar_tarea utilizando notación asintótica para evaluar la eficiencia de las funciones implementadas.
   - Para el módulo de estadísticas del TODO list implementó numero_tareas_pendientes_lineal que es de orden lineal, modifique la clase y cree el método numero_tareas_pendientes_cte, que devuelva la cantidad de tareas pendientes  cuyo orden sea contante. Calcule el orden de la funcion para mostrar que es constante

**Nota**: Puede ser que necesiten implementar otros metodos ademas de los mencionados para cumplir con la tarea, por ejemplo buscar_tarea_id(), o contar_tareas, o contar tareas por categoria, les doy libertad en ese sentido.

# Entregables:**
   - Código fuente comentado
   - Informe de análisis de algoritmos y optimización segun la estructura de informe
   - Planilla de autoevaluación completada (ver modelo mas abajo).

## Criterios de evaluación:**
- Trabajo grupal, segun la tabla de autoevaluacion (disponible al final)
- Trabajo en git, se mirará los commits de cada uno de los participantes del grupo
- Correcta implementación de las funcionalidades básicas y avanzadas.
- Claridad y calidad de los comentarios y la documentación del código.
- Calidad y claridad del informe de análisis de algoritmos y optimización.
- Trabajo en equipo y colaboración efectiva entre los miembros del grupo.

Este proyecto se realizará en grupos de tres estudiantes y se evaluará según los criterios mencionados anteriormente.

## Estructura del informe

Informe del Proyecto: Sistema de Gestión de Tareas Pendientes
1. Introducción

    Breve descripción del proyecto y su importancia.
    Objetivos del proyecto y qué se espera lograr con la implementación del sistema.

2. Descripción del Sistema

    Funcionalidades Implementadas:
        Lista y descripción de las funcionalidades básicas y avanzadas desarrolladas.
    Estructuras de Datos Utilizadas:
        Explicación de la implementación de la lista enlazada y nodos en el sistema.

3. Metodología y Diseño
    Diseño del Código:
        Descripción concisa de las clases principales (Tarea, Nodo, ListaEnlazada) y su interacción.

4. Implementación y Ejemplos

    Detalles de Implementación:
        Explicación breve de cómo se implementaron las funcionalidades principales.
    Casos de Uso y Ejemplos:
        Ejemplos de ejecución del sistema para diferentes escenarios de uso.

5. Preguntas Conceptuales

    Preguntas para Análisis:
        ¿Qué sucede si intentamos agregar una tarea que ya existe en la lista?
        ¿Cómo se implementa la priorización de tareas en la lista enlazada? ¿Qué sucede si dos tareas tienen la misma prioridad?
        ¿Cuál es la complejidad temporal del método para eliminar una tarea de la lista enlazada?
        ¿Cómo podríamos modificar el sistema para soportar múltiples categorías por tarea?

6. Resultados y Conclusiones

    Resultados Obtenidos:
        Evaluación del éxito en la implementación de las funcionalidades.
    Conclusiones:
        Resumen de los hallazgos y reflexiones sobre lecciones aprendidas y mejoras futuras.

7. Referencias

    Lista de referencias utilizadas para la implementación y desarrollo del sistema.

Apéndices

    Código fuente comentado (si es necesario).
    Ejemplos adicionales de ejecución o casos de prueba.


## Planilla de Autoevaluación

| Tarea                              | Responsable(s)          | Valoración                                                                                       |
|------------------------------------|-------------------------|-------------------------------------------------------------------------------------------------|
| Comentar el código                 |                         |                                                                                                 |
| Validación y control de entrada de usuario en el menu     |                         |                                                                                                 |
| Control de división por cero       |                         |                                                                                                 |
| Implementación de lista enlazada   |                         |                                                                                                 |
| Funcionalidad básica del sistema   |                         |                                                                                                 |
| Funcionalidades avanzadas          |                         |                                                                                                 |
| Análisis y optimización            |                         |                                                                                                 |
| Documentación del código           |                         |                                                                                                 |
| Presentación del diagrama de flujo |                         |                                                                                                 |
| Ejecución y presentación de la traza del programa |                         |                                                                                                 |
| Revisión final y entrega           |                         |                                                                                                 |
| Colaboración y trabajo en equipo   |                         |                                                                                                 |
| Gestión del tiempo                 |                         |                                                                                                 |
| Evaluación de la calidad del código|                         |                                                                                                 |
