# Bitácora de Plagas

Sitio web para identificar plagas de grano almacenado, almacenes, molinos y cocinas.

**Página en vivo:** https://s3ebaz.github.io/plague-game/

## Archivos que van en GitHub

| Archivo | Para qué |
|---|---|
| `index.html` | El sitio completo (fichas, fotos, quiz, niveles) |
| `sw.js` | Cache para que cargue mejor en el celular |
| `manifest.webmanifest` | Nombre e icono del sitio |
| `icon-192.png` | Icono chico |
| `icon-512.png` | Icono grande |
| `README.md` | Esta guía |
| `.gitignore` | Ignora archivos basura del sistema |

No hace falta carpeta `images`: las fotos ya van dentro de `index.html`.

## Cómo subirlo (si lo haces a mano)

1. Entra a https://github.com/S3ebaz/plague-game
2. *Add file → Upload files*
3. Sube los archivos de la tabla
4. Commit a la rama `main`
5. *Settings → Pages → Deploy from a branch → main / root*

Al cabo de uno o dos minutos abre:

https://s3ebaz.github.io/plague-game/

## Qué incluye el sitio

- Nombre de jugador e insignias
- 10 niveles (de reconocer el insecto hasta sitio + plaguicida)
- 5 niveles especiales al terminar los 10
- Luego los 10 se repiten más difíciles
- Preguntas y opciones siempre al azar
- Top 10 del mes (en ese navegador)
- Catálogo y mapa por silo, bodega, molino, cocina
- Productos Preserve en cada ficha

## Aviso

Contenido educativo. La fosfina y otros plaguicidas solo los aplica personal autorizado.
