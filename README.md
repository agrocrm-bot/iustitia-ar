# Paquete de referencia — Newsletter semanal Iustitia.ar

Este paquete contiene todo lo necesario para que la rutina semanal en Claude Code Remote genere las dos ediciones del newsletter (Jurídica y Contable) con el formato y criterio correctos, sin tener que adivinar nada en cada corrida.

## Contenido

- **CRITERIO-EDITORIAL.md** — las reglas completas de selección, prioridad, estructura y tono. Es la referencia obligatoria de cómo armar cada edición.
- **newsletter-juridico-template.html** — plantilla de formato exacto para la Edición Jurídica (paleta pergamino/dorado).
- **newsletter-contable-template.html** — plantilla de formato exacto para la Edición Contable (paleta verde/menta).

## Cómo usarlo en Code Remote

1. Subí estos tres archivos al repositorio o entorno conectado a la rutina "Weekly Iustitia.ar newsletter" (en la sección "Seleccionar un repositorio" del formulario de la rutina).

2. Actualizá el campo de Instrucciones de la rutina para que incluya esta referencia explícita:

   > "Antes de redactar, leé CRITERIO-EDITORIAL.md y seguilo estrictamente. Usá newsletter-juridico-template.html y newsletter-contable-template.html como plantilla exacta de formato — el resultado final debe ser HTML completo en esa misma estructura visual, no markdown plano. Reemplazá el contenido de ejemplo por las novedades reales de la semana en curso, manteniendo la misma estructura de secciones, badges y cajas."

3. Verificá que el conector tenga acceso de lectura a esos archivos en cada ejecución.

4. Corré una ejecución manual de prueba después de subir los archivos, y revisá que el resultado ya sea HTML con el formato correcto antes de dejar que corra en automático el domingo.

## Qué cambió respecto a la primera prueba

La primera ejecución (30/06/2026) no tenía estos archivos conectados — la sesión partió de cero y generó buen contenido jurídico pero en markdown plano, sin el formato HTML ni la capa de "clientes que se benefician" desarrollada como corresponde. Este paquete resuelve exactamente eso.
