
# Sistema de Turnos de Atención

 1. Nombre de la aplicación

**Sistema de Turnos de Atención**

 2. Descripción no técnica del problema

La aplicación busca solucionar la organización de personas que esperan ser atendidas.

En una fila de atención es importante respetar el orden de llegada. Por esta razón, el sistema permite registrar personas, mostrar quién está esperando y atender primero a la persona que llegó primero.

3. Descripción de la solución

El programa simula un sistema de turnos. Las personas son agregadas a una cola y permanecen en ella hasta que llega su turno.

El sistema permite:

* Agregar personas a la cola.
* Mostrar las personas que están esperando.
* Consultar quién será atendido.
* Atender y retirar a la primera persona.
* Controlar cuando la cola está llena.
* Controlar cuando la cola está vacía.

 4. Estructura de datos seleccionada

La estructura seleccionada es una **cola implementada mediante un vector**.

La cola utiliza el principio FIFO (First In, First Out), lo que significa que el primer elemento en entrar es el primero en salir.

El vector almacena los nombres de las personas que están esperando.

 5. Justificación técnica

La cola es adecuada para este problema porque las personas deben ser atendidas en el mismo orden en que llegan.

La operación de inserción se realiza al final de la cola mediante `append()`, mientras que la eliminación se realiza desde la primera posición mediante `pop(0)`.

Una ventaja es que permite representar fácilmente una fila de espera. Una limitación es que la capacidad establecida es fija y retirar el primer elemento puede requerir desplazar los demás elementos.

 6. Análisis de otra estructura

Otra estructura que podría utilizarse es una pila implementada mediante un vector.

La pila utiliza el principio LIFO, donde el último elemento en entrar es el primero en salir.

Esta estructura no sería adecuada para el sistema de turnos, porque una persona que llegara de última sería atendida antes que las personas que llegaron anteriormente.

Por lo tanto, la cola resulta más apropiada para este problema.

 7. Instrucciones para ejecutar el programa

1. Descargar o clonar el repositorio.
2. Tener instalado Python.
3. Abrir el archivo `sistema_turnos.py`.
4. Ejecutar el programa desde un entorno como Visual Studio Code, PyCharm o la terminal.

Comando:

python sistema_turnos.py


 8. Casos de prueba

Caso normal

Se agregan Ana, Carlos y María.

Resultado:

[Ana, Carlos, María]

La primera persona atendida es Ana.

### Caso límite: cola llena

Se agregan personas hasta alcanzar la capacidad máxima.

Cuando se intenta agregar otra persona, el programa informa:
La cola está llena. No se puede agregar más personas.

Caso límite: cola vacía

Después de atender a todas las personas, se intenta atender nuevamente.

Resultado:

La cola está vacía. No hay personas para atender.

 9. Limitaciones y posibles mejoras

La principal limitación es que la capacidad de la cola es fija. Además, retirar el primer elemento del vector puede requerir desplazar los elementos restantes.

Como posible mejora se podría desarrollar una interfaz gráfica para facilitar el registro y visualización de los turnos.

10. Video

**Enlace del video:**
[PEGAR AQUÍ EL ENLACE DEL VIDEO]

## Autor

Estudiante de Ingeniería de Software

