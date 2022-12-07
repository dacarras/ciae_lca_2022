
# CIAE LCA 2022

-   Repositorio de los ejemplos de código empleados para ajustar modelos
    de clases latentes.
-   Material empleado para la clase “Modelos de clases latentes”,
    realizada para el curso “Metodología Cuantitativa II”, realizada
    como profesor invitado.

## Instalación

Para reproducir los resultados de los codigos compartidos se requiere
instalar las siguientes librerías:

``` r
# libreria empleada para instalar librerías compartidas en github
install.packages('devtools')

# libreria que contiene los datos empleados, y las funciones de preparación de datos
devtools::install_github('dacarras/ilsa',force = TRUE)

# libreria empleada para ajustar modelos de clases latentes
## desde cran
install.packages('glca')
## desde github
devtools::install_github('kim0sun/glca')
# ver: https://kim0sun.github.io/glca/

# librerias empleadas para manejo de datos
install.packages('dplyr')
install.packages('tidyr')

# librerias empleadas para crear figuras y plots
install.packages('ggplot2')
```

> Nota: the present command requires to the `devtools` library. To
> install this library we can use the following command
> `install.packages('devtools')`.

# Descripción

## listado de códigos compartidos

-   00_preparar_datos.md
-   01_numero_de_clases.md
-   02_resultados.md
-   03_extraer_resultados.md
-   04_graficos.md
-   05_ejercicio.rmd
-   06_ejercicio_resuelto.rmd
