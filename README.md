Análisis de Base de Datos – Canción de Huntrix
Objetivo del Proyecto

Este repositorio contiene el análisis de características de la base de datos generada a partir de la canción de Huntrix.
El trabajo se organiza en cinco ramas, cada una enfocada en dos variables relacionadas entre sí.

Cada rama incluye:

Definición de las variables

Relación entre ellas

Justificación de comparabilidad

Métodos de medición o extracción

Ejemplos SQL, código o pseudocódigo

Visualización sugerida

Historial reproducible del trabajo

Integrantes del equipo

Emiliano Delgado Martínez

Cruz Miranda Valeria

Estructura del Repositorio
huntrix-song-db-analysis/
│
├─ README.md
├─ dataset/
│   ├─ huntrix_songs.csv
│   └─ huntrix_songs.sql (opcional)
│
├─ branches/
│   ├─ branch-tone/variables.md
│   ├─ branch-grammar/variables.md
│   ├─ branch-tempo/variables.md
│   ├─ branch-key/variables.md
│   └─ branch-popularity/variables.md
│
└─ team_report.md


En caso de que el dataset completo sea muy pesado, se puede incluir únicamente una muestra (sample.csv) y agregar instrucciones para descargar el archivo completo desde almacenamiento externo.

Contenido de Cada Rama
1. branch-tone

Variables:

loudness

energy

2. branch-grammar

Variables:

avg_sentence_length

grammar_errors_per_100_words

3. branch-tempo

Variables:

tempo_bpm

danceability

4. branch-key

Variables:

key

mode

5. branch-popularity

Variables:

play_count

likes

Cada archivo variables.md de estas ramas contiene:

Explicación detallada de las dos variables

Ejemplos de medición o extracción

Sugerencias de visualización

Bitácora de pasos para reproducir el trabajo

Cómo reproducir el trabajo
# 1. Clonar el repositorio
git clone https://github.com/<usuario>/huntrix-song-db-analysis.git

# 2. Ver ramas disponibles
git branch -a

# 3. Cambiar a una rama para revisar su contenido
git checkout branch-tone


Abrir el archivo:

branches/branch-tone/variables.md


y seguir el historial de pasos documentado en el mismo archivo
