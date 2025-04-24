# Proyecto 2: DeepLearning
 Descripción general

Este proyecto evalúa el efecto del filtro Sobel en una tarea de clasificación de imágenes satelitales usando redes neuronales convolucionales (CNN). Se parte del dataset EuroSAT, que contiene más de 27,000 imágenes de diferentes tipos de cobertura terrestre (zonas agrícolas, bosques, ríos, etc.).

Se compara el desempeño del modelo entrenado con:

Imágenes originales

Imágenes procesadas con el filtro Sobel (resaltando bordes)

## ¿Qué hace el código?

1. Descarga y extrae automáticamente el dataset EuroSAT.

2. Carga y preprocesa las imágenes, redimensionándolas a 64x64 píxeles.

3. Aplica el filtro Sobel a una copia del dataset para detectar bordes.

4. Entrena dos CNNs:

-Una con imágenes originales

-Otra con imágenes filtradas

5. Compara la precisión de ambos modelos para analizar si el filtro ayuda o perjudica la clasificación.

6. Visualiza imágenes y gráficas de rendimiento.

## Justificación del filtro Sobel

El filtro Sobel se utiliza para resaltar bordes y contornos en las imágenes. En este proyecto se analiza si extraer esta información estructural mejora la capacidad de la red neuronal para distinguir entre clases geográficas.

## Resultados esperados

El proyecto incluye:

- Comparación de precisión entre modelos con y sin filtro.

- Visualización de imágenes originales vs filtradas.

- Gráficas de entrenamiento (loss y accuracy).

- Conclusión sobre el impacto del filtro en el desempeño del modelo.
