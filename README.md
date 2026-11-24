# Amalgama Day

Sitio de una sola página para el Amalgama Day: fecha, qué esperar, la oficina nueva, el cronograma del día y los equipos.

## Cómo verlo

Abrí `index.html` en el navegador. No necesita build ni dependencias: las tipografías (Google Fonts) y GSAP + ScrollTrigger se cargan desde CDN.

Para servirlo en local:

```bash
python3 -m http.server 8000
```

## Dónde cambiar los datos

- Fecha, lugar y búsqueda de Google Maps: el objeto `EVENT` al principio del `<script>` en `index.html`.
- Equipos: el array `TEAMS` en el mismo script.
- Figuras de Amalgama: `assets/` (también están embebidas en el HTML).
