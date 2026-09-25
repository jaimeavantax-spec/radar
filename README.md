# Radar

Sistema propio de detección de tendencias, novedades y oportunidades de mercado para el desarrollo de aplicaciones.

## Qué hace

Radar rastrea a diario múltiples fuentes públicas (foros, noticias, tendencias de búsqueda, lanzamientos de productos) para detectar novedades y necesidades no resueltas, y a partir de ellas genera propuestas de aplicaciones a desarrollar, validando cada idea contra el mercado existente.

## Cómo funciona

El sistema opera con dos motores complementarios:

- **Motor de tendencias:** parte de novedades y temas emergentes del día, y evalúa si representan una oportunidad de app en un mercado abierto.
- **Motor de necesidades:** detecta quejas y necesidades recurrentes sobre software ya existente, para hallar huecos reales en mercados maduros.

Por cada oportunidad, Radar verifica en las tiendas de aplicaciones si ya existe algo similar, analiza las reseñas de los competidores y entrega un reporte con las propuestas priorizadas.

## Fuentes de datos

Radar consulta fuentes públicas mediante sus APIs oficiales, entre ellas:

- Reddit (Data API)
- Product Hunt
- Hacker News
- Google Trends
- RSS de medios de tecnología y negocios

## Uso

Proyecto de uso personal. Se ejecuta como un proceso programado (batch diario) que genera reportes de oportunidades para su análisis.

## Estado

En desarrollo activo.
