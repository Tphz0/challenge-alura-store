1. Propósito del análisis realizado
El análisis tiene como objetivo evaluar el desempeño de cuatro tiendas diferentes, comparando indicadores clave como facturación, productos más vendidos, categorías populares, calificaciones de clientes y costos de envío. La meta final es generar un resumen claro y comparativo que permita identificar cuál de las tiendas presenta el menor rendimiento global, facilitando la toma de decisiones del dueño del negocio.

2. Estructura del proyecto
Los datos de cada tienda se almacenan en un diccionario llamado tiendas, con claves como 'Tienda 1', 'Tienda 2', etc., y valores correspondientes a sus respectivos DataFrames.
```python
tiendas = {
  'Tienda 1': tienda,
  'Tienda 2': tienda2,
  'Tienda 3': tienda3,
  'Tienda 4': tienda4
}
```
Hay distintos bloques de còdigo, donde cada uno analiza un aspecto específico de desempeño:
Facturación total
Categoría más popular
Calificación promedio
Productos más y menos vendidos
Costo de envío promedio
Cada uno crea un DataFrame intermedio que luego se combina en un resumen final consolidado.

3. Instrucciones para ejectutar
Para correr correctamente este notebook en un entorno local o en Google Colab:
Requisitos previos
Python 3.x instalado
Librerías necesarias: pandas, IPython.display

Pasos a seguir
a. Cargar los datos de las tiendas
En el archivo estàn cargados los datos de cada tienda, se debe correr primero para poder trabajarlos.
b. Ejecutar cada bloque de análisis
Los bloques ya están diseñados para recorrer todas las tiendas, generar DataFrames resumen e imprimirlos con display().
c. Ejecutar el bloque de resumen final
Este consolidará todos los indicadores en un solo DataFrame para comparación.