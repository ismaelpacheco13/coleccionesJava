# Colecciones Java (Resumen)

## Concepto
Una colección es un contenedor para un conjunto de elementos de un tipo en una sola unidad.
Se usan para el almacenamiento, recuperación y manipulación de datos.

Las colecciones estan disponibles en Java desde la versión 2.
Pertenecen al paquete java.util

## Interfaces y clases en Java

<img src="imagenes/diagramaInterfacesClases" alt="Diagrama de Interfaces y Clases en Java">

## Iterable(E)
- Patrón de diseño que permite recorrer y eliminar una sucesión de elementos.
- Permite ser recorrido mediante el uso de un bucle for-each o el método forEach.

## Collection(E)
- Extiende a Iterable(E) heredando su funcionalidad.
- Collection(E) representa a un grupo de elementos.
- El resto de interfaces heredan de Collection (salvo Map y derivados).
- También permite tener una serie de métodos comunes a casi todos los tipos de colecciones.
- JDK no ofrece implementación directa de esta interfaz.
- Sirve para manipular colecciones de una forma general.

Las operaciones disponibles son las siguientes:
- Verificación de tamaño: size y isEmpty
- Comprobación de elementos: contains
- Añadir y eliminar elementos: add y remove
- Iterar: iterator
- Operaciones con un conjunto de datos: containsAll, addAll, removeAll, removeIf, retainAll, clear
- Transformar en array: toArray
- Streams: stream, parallelStream

## Set< E >
- Se trata de un Collection<E> que no permite elementos duplicados.
- Es una abstracción del concepto matemático de conjunto.
- No añade ningún método a los heredados de Collection(E)
- No hay
