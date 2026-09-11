 Control de productos de una tienda

 1. Nombre de la aplicación

**Control de productos de una tienda**

2. Descripción no técnica del problema

La aplicación permite llevar un control sencillo de los productos registrados en una pequeña tienda.

El sistema permite agregar, consultar, buscar, modificar y eliminar productos. De esta manera, se puede conocer qué productos están registrados y en qué posición se encuentran.

La aplicación tiene una capacidad máxima de cinco productos.

 3. Descripción de la solución

El programa fue desarrollado en Python y utiliza un vector para almacenar los nombres de los productos.

El usuario puede seleccionar diferentes opciones desde un menú:

* Agregar producto.
* Mostrar productos.
* Buscar producto.
* Modificar producto.
* Eliminar producto.
* Salir del programa.

El programa también controla situaciones especiales, como intentar agregar productos cuando el vector está lleno o realizar operaciones cuando no existen productos registrados.

 4. Estructura de datos seleccionada

La estructura seleccionada es un **vector o arreglo**.

El vector permite almacenar varios elementos y acceder a ellos mediante una posición o índice.

En esta aplicación cada posición representa un producto.

Por ejemplo:

Índice:     0        1        2
Producto: Arroz    Leche    Huevos

Los índices comienzan desde cero.

5. Justificación técnica

Se seleccionó un vector porque la aplicación necesita almacenar una cantidad determinada de productos y acceder a ellos mediante posiciones.

La estructura permite agregar elementos, recorrerlos para mostrarlos, buscar productos, modificar posiciones y eliminar elementos.

Una de sus ventajas es que es sencilla de implementar y permite acceder directamente a una posición mediante su índice.

Una limitación es que la capacidad establecida para esta solución es fija. Además, cuando se elimina un elemento, los elementos posteriores pueden cambiar de posición.

 6. Análisis de otra estructura

Una estructura alternativa sería una matriz.

La matriz organiza los datos mediante filas y columnas. Podría utilizarse para almacenar información adicional como nombre, cantidad y precio de cada producto.

Sin embargo, para la solución propuesta solamente se necesita almacenar los nombres de los productos. Por esta razón, una matriz sería más compleja de lo necesario.

El vector resulta más sencillo y adecuado para el problema planteado.

 7. Instrucciones para ejecutar el programa

1. Descargar o clonar el repositorio.
2. Tener Python instalado.
3. Abrir el archivo `control_productos.py`.
4. Ejecutar el programa desde Visual Studio Code, PyCharm o una terminal.

Comando:
python control_productos.py


 8. Casos de prueba

 Caso normal

Se registran los siguientes productos:

* Arroz
* Leche
* Huevos

Después se muestran los productos y se realiza una búsqueda.

El sistema permite encontrar el producto y mostrar su posición.

### Caso límite: vector lleno

Se registran cinco productos.

Cuando se intenta agregar un sexto producto, el sistema muestra:


El vector está lleno. No se pueden agregar más productos.


### Caso límite: vector vacío

Después de eliminar todos los productos, se intenta mostrar la información.

El sistema muestra:

No hay productos registrados.
 9. Limitaciones y posibles mejoras

La principal limitación es que el vector tiene una capacidad máxima establecida de cinco productos.

Otra limitación es que al eliminar un producto los elementos posteriores pueden cambiar de posición.

Como mejora se podría permitir almacenar una cantidad mayor de productos y agregar información como precio, cantidad disponible y categoría.

También se podría desarrollar una interfaz gráfica para facilitar el uso de la aplicación.

 10. Video

**Enlace del video:**
[PEGAR AQUÍ EL ENLACE DEL VIDEO]

## Autor

Estudiante de Ingeniería de Software

