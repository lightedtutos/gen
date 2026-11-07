# Estudio de Embriología

Abre `index.html` (o activa GitHub Pages). Los datos están en `bancos/`, un archivo por capítulo.

- `curado_20_21.js`: preguntas hechas a mano (opción múltiple y abierta).
- `c14`…`c26`: generados desde los PDF de Arteaga. Cada sección del libro es una pregunta de "Explicar" (la respuesta modelo es el texto completo) y cada oración con término técnico es una pregunta de "Completar".

Para agregar un banco: crea `bancos/nuevo.js` con `BANCOS.push({id,nombre,fuente,items})` y añade su `<script>` en `index.html`.
