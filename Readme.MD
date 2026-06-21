# Actividad 6 - Deep Learning / NLP: Análisis de reseñas Trustpilot

Este proyecto analiza reseñas de Trustpilot de la empresa `www.halfords.com`, perteneciente al sector `Vehicles & Transportation`.

## Objetivo

El objetivo es aplicar técnicas de NLP para:

- Analizar el sentimiento global de las reseñas.
- Comparar la empresa con competidores del mismo sector.
- Extraer topics principales.
- Analizar sentimiento por topic.
- Identificar fortalezas y áreas de mejora.

## Empresa analizada

- Empresa objetivo: `www.halfords.com`
- Sector: `Vehicles & Transportation`
- Reseñas empresa objetivo: 100
- Competidores comparables: 44 empresas del mismo sector con 100 reseñas cada una

## Metodología

- Limpieza de texto para topic modeling.
- Análisis de sentimiento con VADER Sentiment.
- Extracción de topics con TF-IDF + NMF.
- Comparación de sentimiento y topics frente a la competencia comparable.

## Nota sobre datos

El archivo `trustpilot-reviews-123k.csv` no se incluye en el repositorio porque supera el límite de tamaño recomendado por GitHub. Debe colocarse localmente en:

```text
data/raw/trustpilot-reviews-123k.csv

Enlace al archivo: https://drive.google.com/file/d/1_k7KgvU2TMAGfxHQRcnMuw0-E8EpAiNY/view?usp=classroom_web&authuser=0