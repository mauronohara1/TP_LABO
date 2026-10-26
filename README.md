# Evolución de la música en Spotify

Trabajo Práctico Grupal · Laboratorio de Métodos Cuantitativos Aplicados a la Gestión · FCE UBA · 2do Cuatrimestre 2026

## Integrantes

| Nombre | N° de registro | Usuario de GitHub |
|---|---|---|
|Sergio Sebastian Cordoba|921765|sebastiancordoba949-sys|
|Mauro Nohara Gushiken|922170|mauronohara1|
|Facundo Malpeli|921871|FacundoMalpeli|
|Manuel Mariani|921739|manuelmariani6|

## Pregunta de investigación

_En definición._ El eje del trabajo es cómo cambian las preferencias musicales según el género a lo largo del tiempo.

## Dataset

**Spotify Dataset 1921–2020, 600k+ Tracks**, publicado en Kaggle por el usuario *yamaerenay*:
https://www.kaggle.com/datasets/yamaerenay/spotify-dataset-19212020-600k-tracks

- `tracks.csv`: una fila por canción, con fecha de lanzamiento, popularidad y características de audio (danceability, energy, valence, acousticness, tempo, etc.).
- `artists.csv`: artistas con seguidores, popularidad y géneros.

**Cómo obtenerlo:** por su tamaño, el dataset no está subido al repositorio. El notebook lo descarga automáticamente desde Kaggle con la librería `kagglehub`, sin necesidad de cuenta. Como alternativa, se puede bajar el ZIP desde el link de arriba y subir `tracks.csv` a Colab. Para descargarlo, hay que tener una cuenta en Kaggle.

## Contenido del repositorio

| Archivo | Descripción |
|---|---|
| `01_exploracion_spotify.ipynb` | Carga y exploración inicial: estructura, cobertura temporal y calidad de los datos (punto 3.1). |
| _próximamente_ | Transformaciones, gráficos, informe en PDF y presentación. |

## Cómo correr el notebook

1. Abrir el `.ipynb` en [Google Colab](https://colab.research.google.com/) (*Archivo → Abrir notebook → GitHub* y pegar el link de este repositorio).
2. *Entorno de ejecución → Ejecutar todas*.

## Uso de IA

Parte del código y de la planificación del análisis se hizo con asistencia de Claude (Anthropic). En el notebook, las celdas asistidas están marcadas con **[Asistido por IA]** junto con el prompt utilizado.
