# Análisis Geográfico de Datos de Ventas 🗺️

**Proyecto Adicional - Alura Latam & Oracle**

Este proyecto explora la distribución geográfica de los datos de ventas de cuatro tiendas utilizando las coordenadas de latitud y longitud proporcionadas. El objetivo es identificar patrones relacionados con la ubicación de las compras y analizar cómo las variables geográficas podrían influir en el rendimiento de las tiendas.

## Descripción

Se utilizaron las bibliotecas de Python `pandas`, `matplotlib`, y `seaborn` para cargar, limpiar y visualizar los datos de ventas de cada tienda en función de su ubicación geográfica. El análisis incluyó la generación de gráficos de dispersión para observar la distribución de las ventas y mapas de calor para identificar áreas de alta concentración de ventas para cada tienda. Adicionalmente, se realizó un análisis exploratorio para entender la posible influencia de la ubicación en el precio promedio de los productos vendidos y, si los datos lo permitían, en las calificaciones de los clientes.

## Tecnologías Usadas

* **Python 3**
* **Pandas:** Para la manipulación y análisis de datos tabulares.
* **Matplotlib:** Para la creación de gráficos básicos y personalizables.
* **Seaborn:** Para la creación de gráficos estadísticos avanzados y visualizaciones informativas.

## Estructura del Proyecto

├── analisis_geografico_ventas.ipynb:  Notebook de Jupyter con el código del análisis.
├── README.md:                         Documentación del proyecto.
├── data/
│   ├── tienda_1.csv:                  Datos de ventas de la Tienda 1.
│   ├── tienda_2.csv:                  Datos de ventas de la Tienda 2.
│   ├── tienda_3.csv:                  Datos de ventas de la Tienda 3.
│   └── tienda_4.csv:                  Datos de ventas de la Tienda 4.
└── ... (otros archivos si los hubiera)


## Resultados del Análisis

El análisis generó las siguientes visualizaciones para cada tienda:

* **Gráficos de Dispersión:** Mostrando la ubicación de cada venta individual en un plano de latitud y longitud. Esto permitió observar la distribución general de las ventas de cada tienda.
* **Mapas de Calor (KDE Plots):** Ilustrando la densidad de las ventas. Las áreas con colores más intensos indican una mayor concentración de transacciones.
* **Análisis de Precio Promedio por Área Geográfica:** (Aproximación) Un gráfico de dispersión donde el tamaño y el color de los puntos representan el precio promedio de las ventas en diferentes áreas geográficas discretizadas. Esto ofreció una visión preliminar de cómo el precio podría variar según la ubicación.
* **(Opcional) Análisis de Puntuación Promedio por Área Geográfica:** Si la columna de 'Puntuación' estaba presente, se generó un gráfico similar al del precio para visualizar las calificaciones promedio por área.

## Conclusiones y Posibles Patrones Identificados

(Esta sección se llenaría con las observaciones específicas basadas en los gráficos generados. Algunos ejemplos podrían ser:)

* Se observó que las ventas de la Tienda X tienden a concentrarse en la región [mencionar región geográfica específica].
* La Tienda Y parece tener una distribución de ventas más dispersa geográficamente.
* En las áreas de alta densidad de ventas de la Tienda Z, el precio promedio de los productos vendidos tiende a ser [mayor/menor].
* (Si se analizó la puntuación) No se encontraron patrones geográficos evidentes que influyeran significativamente en la calificación promedio de los clientes.

## Cómo Ejecutar el Código

1.  **Clona el repositorio (si está en GitHub):**
    ```bash
    git clone [https://github.com/cran/DELTD](https://github.com/cran/DELTD)
    ```
2.  **Navega al directorio del proyecto:**
    ```bash
    cd [nombre del directorio del proyecto]
    ```
3.  **Asegúrate de tener instaladas las librerías necesarias:**
    ```bash
    pip install pandas matplotlib seaborn
    ```
4.  **Ejecuta el notebook de Jupyter:**
    ```bash
    jupyter notebook analisis_geografico_ventas.ipynb
    ```
    O abre el archivo `.ipynb` en tu entorno de desarrollo de Python preferido.

## Posibles Extensiones

* **Integración con Folium:** Utilizar la biblioteca `folium` para crear mapas interactivos con marcadores para cada venta o mapas de calor superpuestos en mapas reales.
* **Análisis de Clusters:** Aplicar algoritmos de clustering (como K-Means) para identificar grupos de ventas geográficamente cercanos.
* **Correlación Espacial:** Utilizar técnicas de estadística espacial para cuantificar la autocorrelación espacial de las ventas o el precio.
* **Incorporación de Datos Externos:** Enriquecer el análisis con datos demográficos, económicos o de puntos de interés de las áreas geográficas de las ventas.

¡Gracias por explorar el análisis geográfico de los datos de ventas!
