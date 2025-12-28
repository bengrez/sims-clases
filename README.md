# sims-clases

Repositorio para alojar simulaciones standalone (HTML/JS/CSS) en GitHub Pages.

## Simulaciones disponibles

- Animal Groups Lab v2.1: `animal_groups_lab_v2_1.html`
- Flocking + Sync: `sims/flocking/`

## Ejecutar localmente

```bash
python3 -m http.server 8000
```

Luego abre:

- http://localhost:8000/
- http://localhost:8000/animal_groups_lab_v2_1.html
- http://localhost:8000/sims/flocking/

## Configurar GitHub Pages

1. Ve a **Settings → Pages**.
2. En **Deploy from branch**, selecciona:
   - Branch: `main`
   - Folder: `/(root)`

## Agregar una nueva simulación

1. Crea una carpeta `sims/<nombre>/` con su `index.html`.
2. Agrega el enlace correspondiente en `index.html` (raíz).
