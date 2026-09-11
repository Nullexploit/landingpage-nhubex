# landingpage-nhubex

Nueva versión de la página de presentación de nHubex.

## Objetivo

Rediseñar la landing page pública de nHubex para comunicar con claridad su propuesta de valor, presentar sus capacidades de negocio y organizar sus accesos productivos, de prueba y herramientas técnicas.

## Estado

Primera versión visual disponible en `dist/`. La publicación está preparada con GitHub Pages mediante `.github/workflows/pages.yml`.

## Ver localmente

```bash
python3 -m http.server 4173 --directory dist
```

Después abre `http://localhost:4173`.

## Publicar en GitHub Pages

1. En GitHub abre `Settings` → `Pages`.
2. En `Build and deployment`, selecciona `GitHub Actions`.
3. Ve a la pestaña `Actions` y ejecuta `Publicar Nhubex en GitHub Pages` si no se ejecutó automáticamente.
4. Cuando termine, GitHub mostrará la URL pública del sitio en el entorno `github-pages`.

Cada push posterior a `main` volverá a publicar automáticamente la carpeta `dist/`.
