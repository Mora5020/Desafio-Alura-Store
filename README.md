
Esta es la entrega del primer desafío del curso de analisis de datos en ONE.

Durante este desafío, ayudamos a decidir qué tienda de la cadena Alura Store debe vender. 
Analizamos datos de ventas, rendimiento y reseñas de las 4 tiendas de Alura Store.

**Habilidades desarrolladas:**
Carga y manipulación datos CSV con la biblioteca Pandas.

Cree visualizaciones de datos con la biblioteca Matplotlib.

Analice métricas como ingresos, reseñas y rendimiento de ventas.

## Requisitos:
**Analizar datos de la tienda:**
Debes evaluar información como los ingresos, las categorías más vendidas, las reseñas de los clientes, los productos más vendidos y el envío promedio.

Crear gráficos para visualización.

**Enviar una recomendación:**

Después del análisis, escriba un texto explicando qué tienda debería vender y por qué, basándose en los datos presentados.

## La estructura del proyecto y organización de los archivos.

* Extracción de datos.
* Analisis de estructura de los datos.
* Caluclo de indicadores como: Ingreso total de cada tienda, ventas por categoría, valoracion media de cada tienda, productos mas y menos vendidos y costo promedio de envío.
* Generamos graficos y nuevos indicadores a partir de la visualización como facturación y calificación trimestral, y participación de cada tienda al total de ingresos de las cuatro tiendas.

## Ejemplos de gráficos e insights obtenidos.
Se realizaron las siguientes visualizaciones y análisis comparativos usando Pandas y Matplotlib:

* Ingresos totales:
  
  Gráfico de torta que representa los ingresos totales de las cuatro tiendas y el rendimiento de cada una.
  <div align="center">
  <img src="Graficos/ingresos_totales.png" width="400" alt="Ingresos totales">
</div>

  **La tienda de menor rendimiento es la tienda 4, la de más rendimiento es la tienda 1**

* Facturación trimestral:
  
  Gráfico de lineas que compara la facturacion trimestral de las cuatro tiendas, para profundizar la información sobre el rendimiento de las tiendas.
  <div align="center">
  <img src="Graficos/facturacion_trimestral.png" width="800" alt="Facturación trimestral">
</div>

  **La facturación trimestral muestra un declive anual de la tienda 4.
  Se corresponde con la comparacion de las facturaciones totales de las tiendas.**

## Instrucciones para ejecutar el notebook
Abra el archivo llamado 'AluraStoreLatam.ipynb' y haga click en 'Open in colab'.
