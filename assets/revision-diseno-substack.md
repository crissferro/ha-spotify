# Revision De Diseno Del Substack

Fecha:

2026-05-06

Sitio revisado:

https://crissferrotech.substack.com/

## Estado detectado

- La portada usa una imagen cuadrada con el logo `CF tech`.
- La imagen publica actual quedo guardada como `assets/substack-cover-current.png`.
- El color de acento de Substack esta en naranja `#FF6719`.
- La portada usa layout tipo welcome/subscribe con imagen superior, titulo, descripcion y formulario.
- La interfaz visible aparece en ingles: `Subscribe`, `No thanks`, `Type your email...`, `Launched a month ago`.
- En el HTML publico figura `logo_url: null`, por lo que el sitio no parece tener logo de publicacion cargado como logo separado; esta usando el logo dentro del cover.

## Diagnostico

La marca se ve limpia y moderna. El logo funciona bien como identidad visual, pero la portada todavia no comunica lo suficiente el tema principal: Home Assistant, domotica y tecnologia practica desde Argentina.

El riesgo actual es que una persona nueva vea "CF tech" y entienda que es una marca tech, pero no necesariamente que el sitio habla de casa inteligente, Home Assistant, automatizaciones, WLED, ESP32 y problemas reales de domotica.

## Mejoras prioritarias

1. Configurar idioma espanol en Substack si esta disponible.
2. Cargar el logo como logo de publicacion, no solo como cover.
3. Mantener el cover actual como base de marca, pero crear una portada mas contextual.
4. Crear una serie visual consistente para los posts.
5. Usar imagenes 16:9 para posts y portada horizontal, y cuadradas para podcast/Spotify.

## Recomendacion para portada del sitio

Usar una imagen tipo banner horizontal con:

- Fondo oscuro consistente con el logo.
- Logo `CF tech` integrado.
- Elementos sutiles de domotica: casa conectada, nodos, sensores, luces, dashboard Home Assistant abstracto.
- Texto minimo o sin texto, porque Substack ya superpone titulo y descripcion.

Medidas recomendadas:

- 2400 x 900 px para portada horizontal.
- Exportar tambien 1600 x 900 px como version liviana.

## Recomendacion para imagenes de posts

Crear una plantilla comun:

- Fondo oscuro.
- Acentos azul/celeste/violeta del logo.
- Pequeno acento naranja Substack.
- Icono o render simple del tema del post.
- Titulo corto grande, no el titulo completo si es muy largo.
- Marca pequena `crissferro.tech`.

Temas visuales por post:

- Miedo a la oscuridad: pasillo nocturno, luz tenue, sensor de movimiento.
- Lamparitas/interrupores/enchufes: comparativa visual de tres dispositivos.
- Tiras LED/modo cine: living con TV y luz ambiente.
- Aire acondicionado/Broadlink: control IR, aire acondicionado y ondas infrarrojas.
- Haciendo todo mal: apps dispersas contra un sistema centralizado.
- Mini PC/Home Assistant: mini PC con dashboard abstracto.
- Node-RED/PS4: flujo de nodos conectando consola, TV y luces.
- ESP32/WLED: placa ESP32, tira WS2812B y sensor.

## Herramientas recomendadas

- ChatGPT con generacion de imagenes: para crear portadas y variantes rapidamente usando el logo como referencia.
- Canva: para armar plantillas reutilizables de posts y podcast.
- Figma: para controlar mejor consistencia visual si se va a escalar la marca.
- Adobe Express: alternativa simple a Canva.

## Prompt base para ChatGPT

Crear una imagen horizontal 2400x900 para la portada de un Substack llamado "crissferro.tech". Tema: Home Assistant, domotica y tecnologia practica desde Argentina. Usar una estetica moderna, oscura y limpia, inspirada en un logo CF tech con degradado celeste, azul y violeta. Incluir referencias sutiles a casa inteligente: nodos conectados, luces, sensores, dashboard de Home Assistant abstracto y ondas de automatizacion. No usar personas. No poner texto grande dentro de la imagen, porque el sitio ya muestra el titulo y la descripcion. Alto contraste, aspecto profesional, tecnologico, sin parecer stock generico.

## Prompt para imagen de post

Crear una imagen 16:9 para un post de Substack de crissferro.tech. Tema: [TEMA DEL POST]. Estilo moderno, oscuro, tecnologico y limpio, con acentos celeste, azul, violeta y un detalle naranja. Debe comunicar Home Assistant/domotica practica desde Argentina. Incluir un elemento visual principal claro: [DISPOSITIVO O ESCENA]. Evitar exceso de texto. Dejar espacio seguro para recortes en redes sociales. Alta calidad, aspecto editorial tecnico.

## Prompt para portada de podcast

Crear portada cuadrada 3000x3000 para "crissferro.tech Podcast". Tema: Home Assistant, domotica y tecnologia desde Argentina. Usar fondo oscuro, logo CF tech como elemento principal, acentos celeste azul violeta, detalles sutiles de casa inteligente, ondas de audio y nodos conectados. Texto grande y legible: "crissferro.tech" y debajo "Podcast". Alto contraste, muy legible en miniatura, profesional y moderno.

## Cambios que requeririan acceso

Para modificar el sitio directamente haria falta acceso a Substack:

- Cambiar idioma/configuracion publica.
- Cargar logo de publicacion.
- Cambiar cover.
- Ajustar descripcion o tagline.
- Reemplazar imagenes de posts.
