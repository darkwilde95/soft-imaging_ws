# Taller de análisis de imágenes por software

## Propósito

Introducir el análisis de imágenes/video en el lenguaje de [Processing](https://processing.org/).

## Tareas

Implementar las siguientes operaciones de análisis para imágenes/video:

* Conversión a escala de grises.
* Aplicación de algunas [máscaras de convolución](https://en.wikipedia.org/wiki/Kernel_(image_processing)).
* (solo para imágenes) Despliegue del histograma.
* (solo para imágenes) Segmentación de la imagen a partir del histograma.
* (solo para video) Medición de la [eficiencia computacional](https://processing.org/reference/frameRate.html) para las operaciones realizadas.

Emplear dos [canvas](https://processing.org/reference/PGraphics.html), uno para desplegar la imagen/video original y el otro para el resultado del análisis.

## Integrantes

Complete la tabla:

| Integrante | github nick |
|------------|-------------|
| Raúl Coral | Darkwilde95 |

## Discusión

Se realizó la transformación de la imagen a escala de grises mediante el promedio del valor de cada canal RGB
Se realizó la implementación de la masacara de convolución entre los que esta la masacara de Blur, la mascara de Afilado y la mascara
para la detección de bordes.
Se realizo la implementación de la segmentación de la imagen en escala de grises mediante interacción del mouse con el histograma.

