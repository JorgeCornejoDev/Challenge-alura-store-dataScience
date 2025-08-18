# **Alura Store Challenge**

## **Objetivo:**
El Señor Juan quiere decidir que tienda de su cadena Alura Store debe vender para inicar un nuevo emprendimiento. Para ello se analizará datos de ventas, rendimiento y reseña de las 4 tiendas de Alura Store. El objetivo es identificar la tienda menos eficiente y presentar una recomendación detallada final basada en los datos. 

## Competencias 

* Cargar y manipular datos CSV con la biblioteca Pandas.
* Crear visualiaciones de datos con biblioteca Matplotlib.
* Analizar métricas como ingresos, reseñas y rendimiento de ventas.

## Requisitos

### Analizar datos de la tienda; 
* Evaluar información como los ingresos, las categorías más vendidas, las reseñas de los clientes, los productos más vendidos y el envío promedio. 

### Crear gráficos para visualización
* Decidir qué tipos de gráficos utilizar para presentar los resultados de forma clara y visual.
* Mínimo de 3 gráficos diferentes, que puedan incluir gráficos de barras, circulares, de dispersión y otros. 

### Envíar una recomendación
* Posterior al análisis, redactar una recomendación detallada explicando a qué tienda debería vender el Sr. Juan y por qué, con base a los datos presentados. 


## **Conociendo el conjunto de Datos**
Antes de pasar a un análisis más detallado, es esencial explorar el conjunto de satos para comprender su estructura y contenido. Esto permite identificar patrones, inconsistencias y las columnas más relevantes para los siguientes pasos. 

### **Estructura de datos**
El conjunto de datos contiene la siguiente información:
* **Producto y Categorías:** Artículos vendidos y sus calificaciones.
* **Precio y Envío**: Valores de venta y costos asociados.
* **Fecha y ubicación de compra**: Información temporal y geográfica.
* **Evaluación de compra**: Comentarios de clientes.
* **Tipo de pago y cuotas:** Métodos utilizados por los clientes.
* **Coordenadas geográficas:** Ubicación de las transacciones.

🔍 Explorar y comprender bien estos datos es el primer paso hacia un análisis eficiente. 

## **Ingreso total por cada tienda**
Primer análisis, se debe calcular el **ingreso total** de cada tienda. Sumando los valores de las columnas **Precio** de cada conjunto de datos de la tienda para estimar los ingresos.

## **Venta por categoría**
Se debe calcular la **cantidad de productos vendidos** por **categoría** en cada tienda. La idea es agrupar los datos por categoría y contar el número de ventas de cada tipo, mostrando **las categorías más populares** de cada tienda. 

## **Valoración media por tienda**
Calcular las calificiaciones promedio de los clientes para cada tienda. El objetivo es **conocer la satisfacción del cliente con los productos vendidos*** 

## **Productos más vendidos y menos vendidos**
Se debe identificar qué productos fueron los más vendidos y los menos vendidos en cada tienda. Visualizamos los resultados para que quede claro qué productos destacaron en ventas en cada tienda. 

## **Valor del envío promedio por tienda**
Calcular el costo de envío promedio para cada tienda. El objetivo es comprender cuánto se gasta, en promedio, en el envío de cada tienda.


## **Visualización** 
Hora de transformar sus resultados en visualizaciones que le ayuden a comprender mejor los patrones y los insights encontrados.

De acuerdo con funciones que haya creado, le recomendamos que genere al menos tres gráficos. Estos gráficos deben ser de diferentes tipos (como barras, líneas, dispersión, entre otros) para presentar una visión completa de los datos.

## **Análisis del desempeño geográfico**

**Desafío:**

Utilice los datos de latitud (lat) y longitud (lon) para mapear las ventas de cada tienda y analizar la distribución geográfica de los productos vendidos.

Genere gráficos de dispersión o mapas de calor (Heatmaps) para visualizar datos e identificar áreas con la mayor concentración de ventas.

Explore si algunas tiendas tienen un rendimiento superior o inferior al esperado en determinadas regiones e identifique si existen patrones geográficos que puedan influir en el rendimiento de las tiendas.





