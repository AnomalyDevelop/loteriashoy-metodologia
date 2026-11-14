---
layout: default
title: Cómo usar el CSV de cobertura
---

# Cómo usar el CSV de cobertura

El [CSV público de cobertura](https://loteriashoy.net/metodologia-y-cobertura/?descargar_cobertura=csv) sirve para revisar el alcance del histórico en una hoja de cálculo o una herramienta de análisis.

## Flujo recomendado

1. Conserva los identificadores como texto para no alterar claves.
2. Interpreta `first_date` y `last_date` como los límites observados, no como una promesa de cobertura total.
3. Compara `stored_draws` con `expected_draws` antes de calcular tendencias.
4. Separa los juegos: una cifra agregada puede ocultar huecos concretos.

## Ejemplo de pregunta válida

“¿Qué juegos tienen datos suficientes dentro de la ventana observada para comparar frecuencias?” es una pregunta descriptiva. “¿Qué número va a salir?” no se responde con este archivo.

Consulta la [explicación canónica de la metodología](https://loteriashoy.net/metodologia-y-cobertura/) antes de publicar conclusiones.

[Volver al centro de documentación](index.html)
