# DAYFLOW v3

Actualización de DAYFLOW con calendario mensual, tareas por duración o por horario fijo, aviso de solapamientos, propuestas de agenda con revisión de conflictos y soporte para turnos de trabajo nocturnos.

## Publicar en GitHub Pages
1. Descomprime el ZIP.
2. Sube los archivos `index.html`, `manifest.webmanifest`, `icon.svg` y `sw.js` a la raíz del repositorio existente.
3. Confirma los cambios en la rama `main`.
4. Abre la página publicada y recarga. El service worker usa una caché nueva (`dayflow-v3-cache`).

## Datos
Las tareas y el horario se guardan en el almacenamiento local del navegador. Exporta una copia de seguridad antes de limpiar datos del navegador o cambiar de dispositivo. GitHub Pages publica los archivos de la aplicación, no debería publicar los datos guardados localmente.
