![portada](https://github.com/Ironhack-Data-Madrid-Enero-2022/w3-pandas-project/blob/main/images/shark16757032910324.jpg)

# W2 Project - Data cleaning & wrangling

Para la limpieza de datos de este archivo importado desde .csv, he realizado los siguientes pasos, cada uno me llevó a alguna observación o conclusion

    1. #Importar Librerías
    2. #explorar csv
    3. #dimensiones de la tabla
    4. #100% numéricas: año y original order
 OBS. en este paso se ve que de las 24 columnas, solo dos tienen valores numéricos, el reso son objeto porque describen con string características y situaciones registradas.
    5. #espacio que ocupa
    6. #Edición de Encabezados de columnas, estandarizadas en minúscula y sin espacios
    7. #Contar casos unicos y frecuencia
    8. #Manejo de valores nulos
    9. #Contar valores nulos
 OBS. he decidido explorar la columna de pais, que contenía el porcentaje aceptado en las restricciones de nulos, por lo que el análisis se ha centrado en esta información, por eso las filas nan de country han sido eliminadas.
    9. #Eliminar las filas con valores NaN en la columna "country"
    10.#nuevo data frame con base en información de country
    11.#Eliminar las filas con valores NaN en la columna "country"
    12.#inicia la figura y establece el tamaño
OBS. para analizar el resto de las tablas, se han hecho graficos mostrando los valores nulos y se ve en amarillo que son recurrentes, por lo tanto los valores no numéricos han sido reemplazados por UNKNOW y así eliminar datos ilegibles.
    13.#limpiar nan en todas las columnas 
    14.#inicia la figura y establece el tamaño sin nan
    15.#Top 15 de ataques por país
OBS. Contando valores, se puede tener un ranking en la columna country, los tres países con mayor cantidad de insidencias son USA, AUSTRALIA Y SUDAFRICA.
    16.#Revisamos datos estadísticos agrupando el país
    17.#Computar the mean por country
    18.# Computar la mediana por country
    19.# Computar la desviación estandar por country
OBS. uno de los datos numéricos es AÑo del evento, por lo que hice la exploración en esa columna
    20.# Revisamos datos estadísticos de cada año agrupando el país
    21.# Contamos los valores de cada año 
    22.#Computar la media por año
    23.#Computar la mediana por año
    24.#Computar la desviación standard por año
    25.#estadística por año y registros
    26.#valores únicos para la columna year