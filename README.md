# CAMPAR SGC Digital v0.1

Prototipo front-end estático para presentar y pilotear el Sistema de Gestión de Calidad CAMPAR.

## Ejecutar localmente

No requiere instalación.

1. Abra `index.html` directamente en un navegador, o
2. use un servidor estático local:

```bash
python -m http.server 8080
```

Luego abra `http://localhost:8080`.

## Publicar en GitHub Pages

Suba el contenido de esta carpeta a un repositorio y active GitHub Pages desde la rama principal.

## Alcance v0.1

- Login de demostración
- Dashboard
- Órdenes
- Producción
- Inspecciones con wizard de ejemplo
- Inventario
- Entregas
- No conformidades
- Proveedores
- Productos
- Vista SGC
- Vista Piloto 1 con gates

## Importante

- No hay backend ni autenticación real.
- Los datos son simulados.
- El logotipo mostrado es un marcador visual construido en CSS, no el logotipo oficial. Sustituirlo cuando se proporcione el archivo PNG/SVG oficial de CAMPAR.
- La regla de muestreo del piloto evita usar Ac/Re no cotejados.
