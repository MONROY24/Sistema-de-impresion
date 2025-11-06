#  Sistema de Cola de Impresión 

Proyecto final para la materia **Estructura de Datos I**. Este programa simula un sistema de gestión de trabajos de impresión utilizando una estructura de datos de **Cola** para procesar documentos en el orden en que llegan (FIFO - First-In, First-Out).

##  Descripción del Proyecto

El sistema permite a los usuarios agregar trabajos de impresión a una cola. Cada trabajo se almacena con la siguiente información:
* **Nombre del archivo:** Identificador del documento.
* **Número de páginas:** Cantidad de páginas del documento.
* **Usuario:** Persona que envió el trabajo.

El sistema procesa los trabajos uno por uno, simulando el comportamiento de una impresora de red compartida.

---

## Operaciones Principales

La simulación implementa las operaciones básicas de una cola:

1.  **`enqueue()` (Agregar trabajo):** Permite al usuario ingresar los datos de un nuevo documento (nombre, páginas, usuario) y lo añade al final de la cola de impresión.
2.  **`dequeue()` (Procesar trabajo):** Simula la impresión del siguiente documento. Toma el primer trabajo de la cola (el más antiguo), muestra sus detalles y lo elimina, liberando espacio para el siguiente.
3.  **`mostrarCola()` (Mostrar trabajos pendientes):** Muestra una lista de todos los trabajos que están actualmente en espera de ser impresos, en el orden en que serán procesados.
