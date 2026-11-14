---
layout: default
title: Informe de cobertura del 14 de noviembre de 2026
---

# Informe reproducible de cobertura

Este corte resume la exportación pública consultada el 14 de noviembre de 2026. Es una fotografía del archivo en ese momento: los valores pueden crecer o cambiar cuando se incorporan sorteos o se publica una corrección.

## Resultados del corte

| Medida | Valor |
|---|---:|
| Juegos incluidos | 59 |
| Grupos de loterías | 9 |
| Sorteos almacenados sumados por juego | 20,181 |
| Identificadores de fuentes presentes | 13 |
| Juegos con estado `complete` | 10 (16.9 %) |
| Juegos con estado `partial` | 46 (78.0 %) |
| Juegos con estado `unavailable` | 3 (5.1 %) |

Los estados son etiquetas del propio archivo. `Complete` significa que la cobertura estimada del juego alcanza el umbral configurado para la ventana; no afirma que la fuente sea infalible ni sustituye la comprobación oficial de un premio.

## Cómo reproducirlo

1. Descarga el [CSV de cobertura](https://loteriashoy.net/metodologia-y-cobertura/?descargar_cobertura=csv).
2. Cuenta las filas por `coverage_status`.
3. Suma `stored_draws` por juego.
4. Cuenta valores únicos de `lottery_key` y de las claves separadas por `|` en `source_keys`.
5. Contrasta el significado de cada campo con la [metodología canónica](https://loteriashoy.net/metodologia-y-cobertura/).

La misma exportación está disponible como [JSON estructurado](https://loteriashoy.net/metodologia-y-cobertura/?descargar_cobertura=json). Si una cifra cambia después de este corte, consulta el [registro público de correcciones](https://loteriashoy.net/correcciones/) y la fecha de actualización del recurso.

## Qué no demuestra

Este informe mide disponibilidad documental. No calcula números “calientes”, no recomienda apuestas y no predice resultados. Las frecuencias históricas describen el conjunto observado; cada sorteo independiente conserva su propia probabilidad.

[Volver al centro de documentación](index.html)
