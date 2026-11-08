# Aventureros Ecoturismo — sitio web

Landing estática (HTML, CSS y JavaScript en un solo `index.html`, más imágenes). No necesita instalar nada ni compilar.

## Qué trae

- `sitio/`: lo que se publica. `index.html`, `img/` (fotos, marca y textura del globo), `robots.txt` y `netlify.toml`.
- `fuentes/`: archivos de trabajo del globo 3D (`blender/` y `models/`). No se suben a Netlify.

## Publicar en Netlify

**Opción 1, arrastrar y soltar (la más rápida):**

1. Entra a https://app.netlify.com/drop con tu cuenta.
2. Arrastra la carpeta `sitio` completa a la página.
3. Netlify te da una URL tipo `algo.netlify.app`. Cámbiale el nombre en *Site configuration → Change site name*.

**Opción 2, desde la terminal:**

```bash
npm install -g netlify-cli
netlify login
cd sitio
netlify deploy --prod --dir .
```

La primera vez pregunta si crear un sitio nuevo: responde que sí.

## Dominio propio

En Netlify: *Domain management → Add a domain* y sigue los pasos para apuntar el DNS del dominio.

## Probar en local

```bash
cd sitio
python3 -m http.server 8080
```

Y abre http://localhost:8080
