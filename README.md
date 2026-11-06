# ¿La música se volvió más enérgica y menos alegre? Argentina frente al mundo

Trabajo Práctico Grupal · Laboratorio de Métodos Cuantitativos Aplicados a la Gestión · FCE UBA · 2do Cuatrimestre 2026

## Integrantes

| Nombre | N° de registro | Usuario de GitHub |
|---|---|---|
|Sergio Sebastian Cordoba|921765|sebastiancordoba949-sys|
|Mauro Nohara Gushiken|922170|mauronohara1|
|Facundo Malpeli|921871|FacundoMalpeli|
|Manuel Mariani|921739|manuelmariani6|

## Pregunta de investigación

¿La música se volvió más enérgica y menos alegre entre 1920 y 2021? ¿La música argentina siguió la misma tendencia que la global?


## Dataset

Usamos el [Spotify Dataset 1921–2020, 600k+ Tracks](https://www.kaggle.com/datasets/yamaerenay/spotify-dataset-19212020-600k-tracks), publicado en Kaggle por el usuario *yamaerenay*.

- `tracks.csv`: canciones, fechas de lanzamiento y características de audio, entre ellas `energy` y `valence`.
- `artists.csv`: artistas, popularidad, seguidores y géneros asociados.

### Criterio de clasificación

Usamos la columna `genres` de `artists.csv`, que contiene etiquetas de géneros musicales, incluidos géneros argentinos. Clasificamos una canción como argentina cuando el artista principal tiene una etiqueta incluida en el criterio del notebook: coincidencias con términos como `argentin`, `tango`, `rock nacional`, `cuarteto`, `chamame`, `cumbia villera` o `rkt`, con algunas exclusiones para evitar coincidencias de otros países.. La categoría «resto» incluye las canciones que no cumplen ese criterio, incluso las que no tienen un género que permita clasificarlas como argentinas.

`Valence` se utiliza como una aproximación a la positividad musical percibida; no mide directamente las emociones ni las preferencias de quienes escuchan.

## Contenido del repositorio

| Archivo | Descripción |
| --- | --- |
| `02_exploracion_y_analisis_spotify_version2.ipynb` | Notebook principal: exploración y preparación de los datos, resúmenes estadísticos y gráficos. |
| `Informe_académico___Trabajo_grupal_laboratorio.pdf` | Informe académico. |
| `PresentacionPP.pptx` | Presentación. |

El dataset no está incluido en el repositorio por su tamaño. El notebook intenta descargarlo desde Kaggle mediante `kagglehub`; también se pueden descargar los archivos desde la página del dataset.

## Cómo ejecutar el notebook

La consigna propone trabajar en Google Colab:

1. Abrir el repositorio en Google Colab desde **Archivo → Abrir notebook → GitHub**.
2. Seleccionar `02_exploracion_y_analisis_spotify.ipynb`.
3. Ejecutar todas las celdas y guardar el notebook con sus resultados.

El notebook también puede abrirse en VS Code con la extensión de Jupyter instalada.

## Uso de inteligencia artificial

Se utilizó asistencia de Claude (Anthropic) en la planificación y elaboración de algunas celdas. En el notebook se identifican las celdas asistidas y se incluyen los prompts utilizados. El grupo revisa los resultados y es responsable de las interpretaciones y conclusiones.