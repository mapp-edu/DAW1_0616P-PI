# Proyecto Intermodular I — DAW / DAM

Sitio web con la guía didáctica y las sesiones del módulo **Proyecto Intermodular I**
(0616 DAW / 0492 DAM) del CEEDCV.

Construido sobre [EduPress](https://github.com/GGEdu/EduPress), plantilla educativa
para VitePress.

## Arranque

```bash
npm install
npm run docs:dev     # → http://localhost:5173/DAM_DAW_Proyecto_Intermodular_1/
```

O con los scripts de Docker (puertos automáticos, sin conflictos entre proyectos):

```bash
./start-project.sh          # servidor de desarrollo
./status-project.sh         # ver la URL de acceso
./stop-project.sh           # detener
./start-project.sh preview  # build de producción + preview
```

## Estructura

```
src/
├── index.md              Guía didáctica (portada del sitio)
├── s1/contenidos/        Sesión 1 · Fundamentos del Project Management
├── s2/contenidos/        Sesión 2 · Metodologías Ágiles. Scrum
├── public/img/           Logos e imágenes
└── .vitepress/
    ├── config/           👤 Toda la personalización se hace aquí
    └── theme/            Tema (componentes, CSS, composables)
```

## Personalización

Los cuatro archivos de `src/.vitepress/config/`:

| Archivo      | Qué configura                                        |
|--------------|------------------------------------------------------|
| `project.ts` | URL base, idioma, redes sociales, copyright, licencia |
| `colors.ts`  | Paleta de color y tipografía (6 paletas disponibles)  |
| `logos.ts`   | Logos, alturas, visibilidad y modo claro/oscuro       |
| `units.ts`   | Sesiones activas, navbar y sidebar                    |

Para añadir una sesión: crear `src/s3/contenidos/*.md` y registrar la unidad
con `code: 's3'` en `units.ts`.

## Despliegue

Cada push a `main` publica el sitio en GitHub Pages mediante
`.github/workflows/deploy.yml`.

Requiere activar **Settings → Pages → Source: GitHub Actions** en el repositorio.

## Licencia

[GPL-3.0](LICENSE).

La plantilla base EduPress se distribuye bajo licencia MIT.
