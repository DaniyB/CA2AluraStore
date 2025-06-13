# Análisis de Datos de Tiendas - Challenge Data Science Latam

## Descripción General

Este proyecto realiza un análisis exploratorio de datos de ventas de cuatro tiendas diferentes. El objetivo es extraer insights sobre el rendimiento de cada tienda, incluyendo ingresos, popularidad de producto y calificaciones de clientes. Este análisis forma parte del "Challenge 1 Data Science Latam" propuesto por Alura Latam.

Los datos de cada tienda se proporcionan en archivos CSV separados, cada uno con información detallada sobre las transacciones, productos, clientes y aspectos logísticos.

## Objetivos del Análisis

El proyecto aborda varios "challenges" o desafíos específicos:

1.  **Ingresos Totales:** Calcular y comparar el ingreso total generado por cada tienda.
2.  **Ventas por Categoría de Producto:** Determinar la cantidad de productos vendidos por categoría en cada tienda, identificando las categorías más populares.
3.  **Calificación Promedio:** Calcular y comparar la calificación promedio otorgada por los clientes a cada tienda.
4.  **Productos Más y Menos Vendidos:** Identificar los N productos más vendidos y los N productos menos vendidos en cada tienda.
5.  **Costo de Envío Promedio:** Calcular y comparar el costo de envío promedio para cada tienda.
6.  **(Añadido por el usuario)** Otros análisis exploratorios que surjan.

## Estructura de los Datos

Cada archivo CSV de tienda (`tienda_1.csv`, `tienda_2.csv`, etc.) contiene las siguientes columnas:

*   `Producto`: Nombre o descripción del producto.
*   `Categoría del Producto`: Categoría a la que pertenece el producto.
*   `Precio`: Precio de venta del producto.
*   `Costo de envío`: Costo asociado al envío del producto.
*   `Fecha de Compra`: Fecha en la que se realizó la compra.
*   `Vendedor`: Identificador o nombre del vendedor.
*   `Lugar de Compra`: Ubicación donde se efectuó la compra.
*   `Calificación`: Calificación otorgada por el cliente a la transacción o producto (ej. 1-5 estrellas).
*   `Método de pago`: Método de pago utilizado por el cliente.
*   `Cantidad de cuotas`: Número de cuotas en las que se dividió el pago (si aplica).
*   `lat`: Latitud geográfica asociada a la compra.
*   `lon`: Longitud geográfica asociada a la compra.

## Tecnologías Utilizadas

*   **Python 3.x**
*   **Pandas:** Para la manipulación y análisis de datos.
*   **Matplotlib:** Para la creación de visualizaciones estáticas.
*   **Jupyter Notebook/Lab o Google Colab:** Para un entorno interactivo de desarrollo y presentación (si aplica).

## Archivos del Proyecto

*   `AluraStoreLatam.ipynb`: El notebook que contiene el código para el análisis y la generación de gráficos.
*   `README.md`: Este archivo.

## Cómo Ejecutar el Código

1.  **Instalar Dependencias:**
    Asegúrate de tener Python instalado. Luego, instala las librerías necesarias: Pandas, Matplotlib
	    
  
2.  **Fuentes de Datos:**
    El script carga los datos directamente desde las URLs proporcionadas por Alura Latam:
    *   Tienda 1: `https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_1%20.csv`
    *   Tienda 2: `https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_2.csv`
    *   Tienda 3: `https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_3.csv`
    *   Tienda 4: `https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_4.csv`
    No es necesario descargar los archivos CSV localmente si se mantiene esta carga directa.

## Informe de los Hallazgos y Visualizaciones

## Conclusiones

*Los datos de todas las tiendas son muy similares, el margen de la tienda que menos rinde es muy pequeño, lo que tambien dificulta el analisis mediante graficos. 


---