# Proyecto Módulo 8: Análisis Espacial y Agrupamiento de la Sismicidad de Alto Impacto en México (Magnitud>=5) 🌍📊

**El Dashboard interactivo lo puedes encontrar aquí:** [Dashboard de Análisis de Sismos](https://coste09.github.io/Proyecto_Modulo_8_TEST/)

## Descripción del Proyecto
Este repositorio alberga el código y los datos utilizados para desarrollar el análisis y un visualizador interactivo de actividad sísmica y su relación con las placas tectónicas en México. 

## Tecnologías Utilizadas
* **Lenguaje:** R
* **Visualización y Reportes:** `flexdashboard`, `rmarkdown`, `leaflet`
* **Análisis Espacial:** `sf`, `rnaturalearth`, `dplyr`
* **Modelado:** `kmeans` (Aprendizaje no supervisado)
* **Automatización (CI/CD):** GitHub Actions y GitHub Pages

## Estructura del Repositorio
* `/datos/`: Contiene el dataset principal (`datos_sismos_2015_2026.csv`) y los *shapefiles* de las placas tectónicas.
* `/.github/workflows/`: Archivo de configuración YAML que orquesta el servidor de Ubuntu y el despliegue automático.
* `flexdashboard_analisis_sismos.Rmd`: Código fuente principal que renderiza el visualizador.
* `analisis_sismos.Rmd`: Contiene todo el análisis de datos
* `FALTA AGREGAR EL HTML que se llamará "reporte...html"

## Equipo de Trabajo
* Araceli Yolanda Cruz Cruz
* Alberto González Padilla
* José Fortino López López
* Karla Valeria Loyola Alarcón
* Luis Antonio Sánchez Montalvo
