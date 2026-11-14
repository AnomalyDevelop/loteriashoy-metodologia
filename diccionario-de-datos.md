---
layout: default
title: Diccionario de datos de cobertura
---

# Diccionario de datos de cobertura

La exportación de cobertura describe qué parte del histórico está disponible por lotería y juego. No contiene boletos, datos personales ni una predicción del siguiente sorteo.

## Identificación

- `lottery_key`: identificador estable de la lotería dentro del sistema.
- `lottery_name`: nombre legible mostrado al público.
- `game_key`: identificador estable del juego.
- `game_name`: nombre legible del juego.

## Período y volumen

- `first_date`: fecha más antigua disponible para ese juego.
- `last_date`: fecha más reciente incluida en el cálculo.
- `stored_draws`: sorteos guardados en el período observado.
- `expected_draws`: estimación de sorteos esperados según la ventana y el calendario configurado.

## Calidad y procedencia

- `coverage_percent`: relación entre registros guardados y esperados. No mide si un número es más probable.
- `coverage_status`: etiqueta resumida del estado de cobertura.
- `source_keys`: identificadores de las fuentes consultadas.

Los valores actuales pueden descargarse desde la [tabla de metodología y cobertura](https://loteriashoy.net/metodologia-y-cobertura/) o consultarse como [JSON estructurado](https://loteriashoy.net/metodologia-y-cobertura/?descargar_cobertura=json).

[Volver al centro de documentación](index.html)
