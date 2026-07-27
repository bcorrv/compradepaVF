# Compra Depa VF

Plataforma estática y modular para evaluar la compra personal de un departamento en Vitacura.

## Estructura

- `index.html`: interfaz y módulos.
- `assets/css/styles.css`: estilos.
- `assets/js/app.js`: comportamiento, cálculos, minuta y editor del plano.
- `assets/images/`: imágenes desacopladas del HTML.
- `data/property.json`: inmueble, comparables, zonas y fuentes.
- `data/decision.json`: encaje personal, valoración, liquidez y evidencia.
- `data/workflow.json`: preguntas, minuta, inspección y documentos.
- `data/app.json`: metadatos de versión.

## Publicar con GitHub Pages

1. Abrir **Settings → Pages**.
2. En **Build and deployment**, seleccionar **Deploy from a branch**.
3. Elegir `main` y carpeta `/ (root)`.
4. Guardar. La URL será `https://bcorrv.github.io/compradepaVF/`.

## Guardado

La plataforma guarda automáticamente en `localStorage`. Los datos quedan en el navegador y pueden exportarse/importarse como JSON desde la interfaz. GitHub aloja el código y los valores iniciales, no las notas personales guardadas durante el uso.

## Edición de contenido inicial

Los datos iniciales están separados por dominio dentro de `/data`. Después de editar un JSON, basta con recargar la página.
