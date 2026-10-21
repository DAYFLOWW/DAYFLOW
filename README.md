# DAYFLOW v2

Versión web progresiva de DAYFLOW.

## Publicar en GitHub Pages
1. Abre el repositorio de DAYFLOW.
2. Sube estos cuatro archivos a la raíz del repositorio y acepta reemplazar `index.html`, `manifest.webmanifest`, `sw.js` e `icon.svg`.
3. Espera a que GitHub Pages publique los cambios.
4. En el iPhone, abre la web en Safari. Si aparece la versión anterior, cierra la app y recarga la página; el service worker usa una caché nueva `dayflow-v2-cache`.

## Funciones
- Calendario mensual para elegir fecha.
- Tareas de 5 a 1440 minutos.
- Horario fijo opcional de inicio y fin.
- Repetición mensual por día del mes.
- Horario de trabajo semanal.
- Propuesta de agenda que requiere aprobación.
- Exportar/importar copia de seguridad local.

Los datos se guardan en `localStorage` en cada dispositivo y navegador. No hay sincronización entre dispositivos, notificaciones garantizadas ni IA conversacional avanzada en esta versión.
