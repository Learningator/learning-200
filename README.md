# Learning 200 -- Hackathon Platzi Master

## Sobre el Proyecto :bulb:

Learning 200 es la herramienta que revolucionará la manera en la que los estudiantes aprenden durante su paso en Platzi Master. Con esta herramienta, los procesos de generación de Learning Paths (LP) serán más exactos, rápidos y mejores para coaches, así como para sus estudiantes.

## Problema :dart:

Cuando un estudiante de Platzi es seleccionado para el programa de élite Platzi Master, selecciona una área de interes: frontend, backend o data science. Consecuentemente, se le asigna un coach académico que hace seguimiento durante el proceso y genera un LP manualmente. En conjunto, el coach lidera a un equipo de diferentes areas para realizar un proyecto final.

Sin embargo, existe un problema cuando los coaches crean LP que están fuera de su expertise. Las experiencias de los estudiantes dependen del conocimiento que tenga su coach en el area que les interesa. Por ejemplo, un coach de frontend puede tener problemas para crear un LP de data science. 

Para entender el problema, levantamos datos que justificaran este problema. Pedimos a 8 coaches que nos compartieran sus experiencias en este proceso

El primer descubrimiento es que 5 coaches son Full Stack, 2 Frontend y 1 Backend.

![Área Expertise](https://github.com/Learningator/learning-200-documentacion/blob/main/Captura%20de%20pantalla%20de%202020-12-18%2006-43-33.png)

Cuando preguntamos sobre la dificultad general para hacer un LP promedio, la mayoría de los coaches enfrentaron una dificultad promedio:

![Dificultad](https://github.com/Learningator/learning-200-documentacion/blob/main/Captura%20de%20pantalla%20de%202020-12-18%2006-44-53.png)

El área con menos dificultad para armar LP es frontend, recordando que la mayoría de los coaches son Full Stack o Frontend.

![Dificultad front](https://github.com/Learningator/learning-200-documentacion/blob/main/Captura%20de%20pantalla%20de%202020-12-18%2006-45-02.png)

Sin embargo, los coaches académicos tienen una mayor dificultad con LP de backend:

![Dificultad back](https://github.com/Learningator/learning-200-documentacion/blob/main/Captura%20de%20pantalla%20de%202020-12-18%2006-45-02%20(1).png?raw=true)

El area donde más problemas es data science, donde 7 de 8 coaches encuentra difícil o muy difícil hacer un LP de esta area:

![Dificultad data](https://github.com/Learningator/learning-200-documentacion/blob/main/Captura%20de%20pantalla%20de%202020-12-18%2006-45-06.png?raw=true)

Como podemos ver, el expertise del coach puede jugar a favor o en contra del coach.

Una de las grandes ventajas es trabajar en equipos multidisciplinarios, por lo cual conseguir coaches que solo dirgina a estudiantes de data science no es una opción plausible.

Otro problema es el tiempo que toma realizar un learning path. En promedio, un LP puede tomar de 4 a 5 horas. Esto esta sujeto a modificaciones y cambios de enfoque del estudiante. Según el testimonio de un coach, puede tomar hasta 12 horas hacer un LP con ajustes posteriores. 

Un problema adicional es que el modelo actual no es escalable porque a medida que se integren nuevos estudiantes a Platzi Master se necesitan más coaches generando manualmente nuevos LP.

## Solución :heavy_check_mark:

Learning 200 automatiza la creación de learning paths, recortando el tiempo de creación sin que dependa del conocimiento del coach académico respecto al área de interés del estudiante. Con esto podemos mejorar la experiencia del estudiante y dándole soporte al coach académico. De esta manera, el coach puede enfocarse en realizar acciones de seguimiento y apoyo del estudiante. 

Al automatizar este proceso, podemos escalar el número de estudiantes que pueden ser atendidos a la vez. 

El producto final es un generador de LP, teniendo en cuenta los conocimientos del estudiante, sus objetivos y experiencia.

El viaje de usuario es el siguiente:

![Viaje de usuario](https://github.com/Learningator/learning-200-documentacion/blob/main/User_journey.png?raw=true)

El mockup en Figma original de este flujo se puede consultar [aquí](https://www.figma.com/file/yKbJ5ibbh79TUOh2ZL7SSj/Learningator?node-id=0%3A1)

La arquitectura del proyecto es la siguiente: 



## Equipo: :muscle:

- **Kevin Zea:** Frontend, UX/UI

- **Ulises Sámano:** Frontend, Backend

- **Joel Gaspar:** Backend, Ingenieria de Datos

- **David Jaramillo:** Ingenieria y Arquitectura de Datos

- **Felipe Martinez** Data Science, Machine Learning

- **Xavier Carrera:** Data Science, Machine Learning


## Stack Tecnológico: :wrench:
- Javascript
- ReactJS 
- Node.js
- Python
- Scrapy
- Scickit Learn
- AWS

## Licencia :scroll:

Este projecto está bajo Licenica MIT
