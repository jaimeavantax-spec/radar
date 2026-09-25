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

## Uso de la API de Reddit (Reddit API usage)

Radar accede a Reddit en **solo lectura** (read-only) mediante la API oficial de datos de Reddit (PRAW, script app).

- **Sin escritura (no writes):** nunca publica, comenta, vota ni envía mensajes.
- **Bajo volumen (low volume):** una corrida programada al día; solo posts públicos top/hot del día.
- **Sin almacenamiento ni reventa (no storage/resale):** los datos de Reddit se usan de forma transitoria para generar un resumen privado de análisis personal. Nunca se almacenan a largo plazo, se redistribuyen, se venden ni se usan para entrenar modelos de IA.
- **Un solo usuario, no comercial (single user, non-commercial):** herramienta de investigación personal, sin servicio público.

Subreddits consultados: r/technology, r/gadgets, r/SideProject, r/smallbusiness, r/Entrepreneur, r/AppIdeas, r/SomebodyMakeThis.
