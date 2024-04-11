# Lab2
Report of second laboratory

## Resumen
Este informe detalla las actividades realizadas en el laboratorio 2, que abarca desde prácticas básicas hasta avanzadas utilizando ROS (Robot Operating System). En las prácticas básicas, se creó un paquete ROS llamado Practicas_lab, se implementaron nodos de publicación y suscripción, y se ejecutaron para demostrar la comunicación entre nodos. En las prácticas avanzadas, se exploraron conceptos como el control de robots simulados en turtlesim, desarrollando un controlador por teclado, dibujando formas geométricas y comparando diferentes estrategias de control como el PID.

## Introducción

En el campo de la robótica y el control de sistemas dinámicos, los controladores Proporcional (P), Proporcional-Integral (PI) y Proporcional-Integral-Derivativo (PID) son herramientas fundamentales para lograr un comportamiento deseado en los sistemas controlados. Estos controladores son ampliamente utilizados en una variedad de aplicaciones debido a su capacidad para regular y estabilizar sistemas en tiempo real.

## Controladores PI, P y PID

- **Controlador Proporcional (P)**: El controlador proporcional es el más simple de los tres, y su acción se basa únicamente en el error presente entre la salida deseada y la salida real del sistema. El controlador P ajusta la señal de control proporcionalmente al error, lo que significa que cuanto mayor sea el error, mayor será la corrección aplicada.

- **Controlador Proporcional-Integral (PI)**: El controlador PI agrega una componente integral al controlador proporcional. Esta componente integral tiene en cuenta el historial completo de los errores pasados y ajusta la señal de control para eliminar el error acumulado.

- **Controlador Proporcional-Integral-Derivativo (PID)**: El controlador PID combina las acciones proporcional, integral y derivativa para proporcionar un control más completo y preciso del sistema. La componente derivativa anticipa la tendencia del error y proporciona una respuesta rápida a cambios en la referencia. Esto ayuda a mejorar la estabilidad y la respuesta dinámica del sistema, reduciendo el tiempo de respuesta y minimizando el sobrepico.

## Problemas

- **Basic**
- Colocar los archivos listener.py y talker.py
- Compilar el paquete.
- Ejecutar el talker
- Ejecutar el listener
  
- **Medium**
- Crear un control por teclado para turtlesim
- Dibujar un cuadrado y un triángulo equilátero con turtlesim (Sin controlador)
  
- **Advanced**
- Control de posición para turtlesim (P)
- Control de posición para turtlesim (PI)
- Control de posición para turtlesim (PID)

## Soluciones  

- Se realizaron ajustes en los archivos de lanzamiento para facilitar la ejecución de los scripts listener y talker en ROS a través de la terminal. Ambos archivos se ejecutaron simultáneamente para garantizar un buen funcionamiento, permitiendo la comunicación de audio bidireccional.

-En cuanto al nivel medio, se desarrolló un código que controla los movimientos de una tortuga en el entorno de simulación, permitiendo que se desplace según lo especificado en el código y rote en ángulos predeterminados. Esto se repitió varias veces para crear figuras geométricas como un triángulo y un cubo. Dado que no hay un controlador específico, las líneas de los movimientos son aleatorias, con la única referencia de la posición inicial y los movimientos codificados.

Para interactuar con la tortuga, se implementó un código que permite al usuario moverla en diferentes direcciones utilizando el teclado, con instrucciones claras sobre cómo avanzar, retroceder, girar a la izquierda y a la derecha, teniendo en cuenta la posición actual de la tortuga.

Por falta de tiempo y organizacion se logro solo hacer del nivel avanzado solo el primer controlador (P).
**Los codigos se encuentran en la carpetas que esta añadida en el documento.**
    
## Conclusiones

Los fundamentos de ROS se estudiaron en este laboratorio, así como las prácticas básicas y avanzadas de control de sistemas robóticos simulados. Todos los ejercicios requeridos se realizaron correctamente, lo que permitió reconocer y comprender los diferentes tipos de controladores, incluidos los controladores Proporcional (P), Proporcional-Integral (PI) y Proporcional-Integral-Derivativo (PID).

La ejecución exitosa de los ejercicios demostró que el equipo tenía la capacidad de aplicar la teoría del control a la práctica en un entorno de simulación robótica. La comprensión de los principios de los controladores y su aplicación en ROS establece una base sólida para futuros proyectos y desarrollos en el campo de la robótica y la automatización.
