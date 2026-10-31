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

**Spotify Dataset 1921–2020, 600k+ Tracks**, publicado en Kaggle por el usuario *yamaerenay*:
https://www.kaggle.com/datasets/yamaerenay/spotify-dataset-19212020-600k-tracks

- `tracks.csv`: una fila por canción, con fecha de lanzamiento, popularidad y características de audio (energy, valence, danceability, acousticness, tempo, etc.).
- `artists.csv`: artistas con seguidores, popularidad y géneros. Se usa para identificar la música argentina.

**Cómo obtenerlo:** por su tamaño, el dataset no está subido al repositorio. El notebook lo descarga automáticamente desde Kaggle con la librería `kagglehub`. Para la descarga manual desde la página de Kaggle hace falta una cuenta.

## Contenido del repositorio

| Archivo | Descripción |
|---|---|
| `02_exploracion_y_analisis_spotify.ipynb` | Notebook completo: exploración (3.1), pregunta (3.2), transformaciones y resúmenes (3.3) y gráficos (3.4). |
| `01_exploracion_spotify.ipynb` | Primera versión de la exploración inicial. |
| _próximamente_ | Gráficos exportados, informe en PDF y presentación. |

## Cómo correr el notebook

1. Abrir el `.ipynb` en [Google Colab](https://colab.research.google.com/) (*Archivo → Abrir notebook → GitHub* y pegar el link de este repositorio).
2. *Entorno de ejecución → Ejecutar todas*.

## Uso de IA

Parte del código y de la planificación del análisis se hizo con asistencia de Claude (Anthropic). En el notebook, las celdas asistidas están marcadas con **[Asistido por IA]** y los prompts utilizados están listados al comienzo.
