# DAYFLOW v4

Organizador personal web, compatible con GitHub Pages.

## Cambios de esta versión
- Horarios de trabajo como franjas reutilizables: configura horas una vez y selecciona varios días.
- Se pueden añadir varias franjas semanales, incluso distintas franjas el mismo día.
- Los cambios en los días no vuelven a dibujar el formulario mientras se editan, evitando reinicios de las horas.
- Admite turnos nocturnos como 22:00–06:00, incluyendo la parte del turno que cae en el día siguiente.
- Las tareas de prioridad alta que ya tienen hora asignada quedan protegidas en las propuestas.
- Las tareas restantes pueden recolocarse usando su duración actual, incluso si antes tenían un horario concreto.
- Si no hay hueco para todas las tareas, la aplicación impide aceptar una propuesta incompleta.
- Exportación/importación de copias compatible con los formatos anteriores de DAYFLOW.
- Service worker actualizado para renovar la caché.

## Publicación
Sube `index.html`, `manifest.webmanifest`, `icon.svg` y `sw.js` a la raíz del repositorio GitHub Pages y confirma los cambios.

## Datos
Las tareas y horarios se guardan en `localStorage` del navegador. No se sincronizan automáticamente entre dispositivos. Exporta una copia de seguridad antes de borrar datos o cambiar de navegador.
