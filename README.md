# Patricio Fuentealba — CV / Portafolio

Página personal en HTML, CSS y JavaScript puro (sin frameworks), pensada para publicarse con **GitHub Pages**.

## Estructura

```
.
├── index.html          # Contenido de la página
├── style.css           # Estilos (tema oscuro + cards con brillo violeta en hover)
├── script.js           # Interacciones mínimas (año del footer)
├── assets/
│   └── CV_Patricio_Fuentealba.pdf   # CV descargable
└── Fuentes/             # PDFs originales usados como fuente (CV + export de LinkedIn)
```

## Publicar en GitHub Pages

1. Crea un repositorio en GitHub (por ejemplo `patricio-fuentealba.github.io` o cualquier nombre).
2. Sube este contenido al repositorio:
   ```bash
   git remote add origin <URL_DEL_REPO>
   git branch -M main
   git push -u origin main
   ```
3. En GitHub, ve a **Settings → Pages**, selecciona la rama `main` y la carpeta `/ (root)`.
4. La página quedará publicada en `https://<usuario>.github.io/<repo>/` (o en la raíz si el repo se llama `<usuario>.github.io`).

## Personalización

- Colores: variables CSS al inicio de `style.css` (`--bg`, `--violet`, `--violet-bright`, etc.).
- Contenido: editar directamente las secciones en `index.html`.
- CV descargable: reemplazar el PDF en `assets/`.
