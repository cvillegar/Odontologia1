# Sitio web · Dra. Jessica Mayor, Rehabilitación Oral

Página de una sola hoja en HTML y CSS puro (sin frameworks ni JavaScript).
Abra `index.html` en el navegador para verla.

Los datos de contacto, los servicios, el logo y los colores (rosa y malva)
vienen de la tarjeta de presentación digital: WhatsApp +57 318 077 4500,
Instagram @dra.jessicamayor y Facebook Dra.jessicamayor. Los logos están en
`img/logo-color.png` (encabezado) e `img/logo-blanco.png` (pie de página).

## Qué personalizar

Busque y reemplace los datos de ejemplo:

| Dato | Dónde |
|------|-------|
| Dirección, horario, correo | Sección `#ubicacion` |
| Universidades, registro profesional | Sección `#doctora` y pie de página |
| Precios / formas de pago | Preguntas frecuentes |
| Correo electrónico | Sección `#ubicacion` |

## Fotos

Guarde las imágenes en `img/` y reemplace cada bloque
`<div class="placeholder">…</div>` por una etiqueta `<img>`, por ejemplo:

```html
<img src="img/caso1-antes.jpg" alt="Caso 1, antes del tratamiento" loading="lazy">
```

- **Casos:** publique solo fotos con consentimiento informado y firmado por el
  paciente. Evite que se vea el rostro completo salvo autorización expresa.
- **Mapa:** en Google Maps → Compartir → *Insertar un mapa*, y pegue el
  `<iframe>` en lugar del marcador de la sección de ubicación.

## Publicación

La página se publica en GitHub Pages con el flujo `.github/workflows/pages.yml`,
que publica el sitio cada vez que hay cambios en `main`.

Dirección: https://cvillegar.github.io/Odontologia1/
