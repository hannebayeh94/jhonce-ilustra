# Jhonce Ilustra — Motion Graphics & Diseño Gráfico

Sitio de portafolio (one-page) generado desde el diseño de Stitch `projects/9249624488665845631`, convertido a un proyecto estático con CSS de Tailwind compilado (sin CDN en producción).

## Estructura

```
index.html          Página única (todo el sitio)
css/tailwind.css    CSS compilado (generado, no editar a mano)
src/input.css       Entrada de Tailwind (@tailwind base/components/utilities)
tailwind.config.js  Tema del design system (colores, tipografía, spacing)
```

## Scripts

```bash
npm install       # instala Tailwind
npm run build     # compila css/tailwind.css (minificado)
npm run watch     # recompila al guardar cambios
npm run serve     # sirve el sitio en http://localhost:3000
```

Para ver el sitio sin servidor basta con abrir `index.html` en el navegador.

## Editar

- Cambios de contenido/estructura: `index.html`. Tras editarlo, ejecuta `npm run build` (o `npm run watch`) para regenerar el CSS con las clases nuevas.
- Cambios de tema (colores, fuentes, spacing): `tailwind.config.js`, luego `npm run build`.

## Notas

- Las imágenes (logo, mascota, thumbnails) apuntan a URLs de `lh3.googleusercontent.com` provistas por Stitch. Para producción conviene descargarlas a `assets/` y actualizar las referencias.
- Las fuentes (Space Grotesk, Plus Jakarta Sans, Material Symbols) se cargan desde Google Fonts.
