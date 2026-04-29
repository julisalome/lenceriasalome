# Lencería Salomé — Sitio Web

Landing page para **Lencería Salomé**, La Plata, Buenos Aires.

## Estructura

```
salome-web/
├── index.html       ← página principal
├── images/          ← carpeta para las fotos (crear antes de subir)
└── README.md
```

## Cómo agregar las fotos

Creá una carpeta `images/` y guardá ahí tus fotos. Luego en `index.html` buscá los comentarios que dicen:

```html
<!-- <img src="foto-hero.jpg" ...> -->
```

Reemplazá esa línea por:

```html
<img src="images/foto-hero.jpg" style="width:100%;height:100%;object-fit:cover;position:absolute;inset:0;">
```

### Fotos que necesitás:

| Archivo sugerido | Dónde va |
|---|---|
| `images/hero.jpg` | Foto grande del hero (sección principal) |
| `images/local.jpg` | Foto del showroom / local |
| `images/croissant.jpg` | Línea Croissant |
| `images/praiano.jpg` | Línea Praiano |
| `images/harley.jpg` | Línea Harley |
| `images/body-aretha.jpg` | Body Nude Aretha |
| `images/basicos.jpg` | Básicos del Día a Día |
| `images/bodies.jpg` | Bodies & Moldería |

## Cómo publicar en GitHub Pages

1. Creá una cuenta en [github.com](https://github.com) si no tenés
2. Creá un repositorio nuevo llamado `lenceria-salome` (público)
3. Subí todos los archivos de esta carpeta
4. Andá a **Settings → Pages**
5. En "Branch" seleccioná `main` y carpeta `/ (root)`
6. Guardá — en unos minutos tu página va a estar en:

```
https://TU-USUARIO.github.io/lenceria-salome
```

## Contacto del negocio

- WhatsApp: 221 559-3527
- Instagram: @lenceriasalome12
- Dirección: Calle 12 e/ 60 y 61, La Plata
