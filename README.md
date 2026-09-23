<div align="center">

# eser

**Conciencia aplicada a la vida.**
Comunicación espiritual contemporánea · El pódcast de René Boiero

</div>

---

## Sobre este repositorio

Sitio web de **eser**: una página única, oscura e inmersiva, construida como sitio estático autónomo (sin build ni dependencias que instalar). Todo el contenido, imágenes y el logo van embebidos en `index.html`.

La web incluye:

- **Hero 3D** con la marca eser y una cinta de infinito (∞) en WebGL, con una luz que recorre el trazo sin fin.
- **El podcast** — episodios con el key‑art real (Ana Antic, Tati Ballesteros), enlazados a YouTube.
- **Manifiesto** en carrusel dinámico.
- **Los libros de René** — carrusel con las tapas reales, enlazadas a Amazon.
- **El universo** — Casa Alma · René Boiero · Fundación Almas.
- **Agenda de eventos** y sección **Conectar** (YouTube, Spotify, Instagram).

```
EserWeb/
├── index.html      → la web completa (HTML + CSS + JS, imágenes y logo embebidos)
├── netlify.toml    → configuración de deploy (publish = ".")
├── favicon.png     → ícono del sitio
├── og.jpg          → imagen para compartir en redes (Open Graph)
└── README.md       → este archivo
```

## Publicar en Netlify

**Opción A — Arrastrar (lo más rápido):**
1. Entrá a [app.netlify.com](https://app.netlify.com) → **Add new site → Deploy manually**.
2. Arrastrá esta carpeta (o su `.zip`) a la zona de deploy.
3. Netlify publica el sitio y te da una URL (`algo.netlify.app`).

**Opción B — Con GitHub (deploy automático):**
1. Creá un repositorio nuevo (por ej. `ProyectoAlma/EserWeb`) y subí estos archivos.
2. En Netlify: **Add new site → Import from Git** → elegí el repo.
3. Build command: *(vacío)* · Publish directory: `.`
4. Cada cambio que subas al repo se publica solo.

## Editar el contenido

Los enlaces y datos editables están en el bloque **CONFIG** al final de `index.html`:

- `LINKS` — YouTube, Spotify, Instagram, links de cada episodio, y la web/IG de Fundación Almas.
- `EVENTS` — próximos eventos (fecha, lugar, enlace).
- `BOOKS` — libros y sus links de Amazon.

## Dominio

Para conectar un dominio propio: **Netlify → Domain settings → Add a domain**, y apuntá el DNS del dominio a Netlify (registro `A` al apex y `CNAME www` al sitio `.netlify.app`).

---

<div align="center">

**eser** · Un espacio del universo **René Boiero** 🇦🇷
Hacer visible aquello que permanece intangible.

</div>
