# Análisis de Ventas de Tiendas

## Descripción

Proyecto de análisis de datos de ventas de varias tiendas, enfocado en calcular ingresos, productos más vendidos, calificaciones de clientes, costos de envío y análisis geográfico de las ventas.  
Incluye visualizaciones para facilitar la interpretación y toma de decisiones.

---

## Tabla de Contenidos
 
- [Dependencias](#dependencias)  
- [Uso](#uso)  
- [Análisis y Resultados](#análisis-y-resultados)  
- [Problemas comunes y soluciones](#problemas-comunes-y-soluciones)  
- [Contribuciones](#contribuciones)  
- [Licencia](#licencia)  

---

El proyecto utiliza las siguientes librerías principales:

    Python 3.8 o superior

    pandas

    matplotlib

    seaborn

    folium (opcional, para mapas interactivos)

Puedes instalar todas con:

pip install pandas matplotlib seaborn folium

Uso

El análisis está contenido en un notebook de Jupyter (AnalisisVentas.ipynb) que puedes abrir con:

jupyter notebook AnalisisVentas.ipynb

O en Google Colab para ejecutar en la nube.

El notebook incluye instrucciones para cargar tus archivos de datos y ejecutar cada paso del análisis.
Análisis y Resultados

El proyecto realiza los siguientes análisis:

    Ingresos totales por tienda

    Productos más y menos vendidos

    Distribución de ventas por categoría

    Calificaciones promedio de clientes por tienda

    Costos de envío promedio

    Análisis geográfico de ventas con mapas de dispersión y mapas de calor

Además, genera gráficos que permiten visualizar y comparar el desempeño de cada tienda en los diferentes aspectos analizados.
Problemas comunes y soluciones

    KeyError al acceder a columnas en pandas:
    Verifica que los nombres de las columnas coincidan exactamente (mayúsculas, espacios, etc.). Usa print(df.columns) para inspeccionar.

    Errores por falta de librerías:
    Asegúrate de instalar todas las dependencias con pip install.

    Valores nulos en datos numéricos:
    Algunos cálculos pueden fallar si hay datos faltantes. Usa df.dropna() o fillna() para limpiar los datos.

Contribuciones

Las contribuciones son bienvenidas. Puedes abrir issues para reportar problemas o sugerir mejoras, y enviar pull requests para colaborar.
Licencia

Este proyecto está bajo la licencia CNPDOMO. 
