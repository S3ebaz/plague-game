# 🌾 Bitácora de Plagas: Manual de Campo

Manual de campo interactivo sobre las plagas más comunes en grano almacenado, almacenes, fábricas de alimentos y cocinas. Incluye un quiz de inspección con 10 preguntas al azar (con opciones de respuesta también en orden aleatorio en cada intento) y un catálogo con 28 especies, cada una con fotografía real, filtrable por categoría.

## ✅ Funciona sin internet

Todo el proyecto vive en un único archivo (`index.html`): HTML, CSS y JavaScript están incluidos ahí mismo, no hay fuentes, imágenes ni scripts externos. Esto significa que:

- Puedes **descargar el archivo `index.html` y abrirlo directamente con doble clic** en cualquier navegador (Chrome, Firefox, Edge, Safari), con o sin wifi, con o sin datos móviles.
- Una vez que lo tengas guardado en tu celular o computadora, no necesita conexión a internet para funcionar, ni siquiera la primera vez.
- Si lo publicas en GitHub Pages (ver abajo), la primera carga sí requiere internet para descargar la página, pero puedes guardarla localmente (Ctrl+S / "Guardar página como") para usarla después sin conexión.

## 📂 Estructura del repositorio

```
.
├── index.html   # La aplicación (HTML + CSS + JS en un solo archivo)
├── images/      # Fotografías de cada especie (28 archivos .jpg)
└── README.md    # Este archivo
```

Las fotografías están incluidas como archivos locales dentro de `images/`, así que siguen funcionando sin conexión igual que el resto de la app — solo asegúrate de subir también esa carpeta a GitHub y de mantenerla junto a `index.html` si copias o mueves el proyecto.

## 🚀 Cómo subirlo a GitHub

1. Crea un repositorio nuevo en GitHub (por ejemplo `bitacora-plagas`).
2. En tu computadora, dentro de la carpeta con estos archivos:
   ```bash
   git init
   git add .
   git commit -m "Primera versión de la Bitácora de Plagas"
   git branch -M main
   git remote add origin https://github.com/TU-USUARIO/bitacora-plagas.git
   git push -u origin main
   ```

## 🌐 Cómo publicarlo con GitHub Pages (opcional)

Si quieres que cualquier persona pueda abrirlo desde un enlace, sin descargar el archivo:

1. Ve a tu repositorio en GitHub → **Settings** → **Pages**.
2. En "Source" selecciona la rama `main` y la carpeta `/ (root)`.
3. Guarda. En unos minutos tu app estará disponible en:
   `https://TU-USUARIO.github.io/bitacora-plagas/`

## 📱 Usarlo sin conexión desde el celular

- Abre el enlace de GitHub Pages una vez (o descarga `index.html`).
- En el navegador, usa la opción "Agregar a pantalla de inicio" o guarda el archivo localmente.
- A partir de ahí podrás abrirlo aunque no tengas wifi ni datos.

## ⚠️ Aviso

Contenido con fines educativos. La aplicación de fumigantes, insecticidas o rodenticidas debe realizarla siempre personal certificado, siguiendo la etiqueta del producto y la normativa fitosanitaria local.
