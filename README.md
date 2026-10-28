# Inspección de calidad · Bote, Etiquetado y Tapas

App instalable (PWA) para registrar inspecciones de calidad por franjas de 30 min en las máquinas de Bote blanco (MEPER), Bote etiquetado (Etiquetadoras) y Tapas (NISSEI).

- Los datos se guardan en la hoja de Google "Piloto Inspecciones Botes y Tapas" mediante su Apps Script (`doPost`).
- Funciona sin internet: la app queda guardada en el celular y los registros se envían al volver la señal.
- Para instalar: abre la página en Chrome y toca **Instalar app** (o ⋮ → *Instalar aplicación*).

Al publicar cambios, sube la constante `VERSION` en `sw.js` para que los celulares descarguen la versión nueva.
