# Iustitia.ar — Criterio editorial del newsletter semanal

Este documento define cómo se arma cada edición del newsletter de Iustitia.ar. Es la referencia obligatoria para cada corrida de la rutina — no es un lineamiento general, son reglas concretas a aplicar siempre.

Hay dos ediciones separadas cada semana: **Edición Jurídica** (para abogados) y **Edición Contable** (para contadores y asesores impositivos). Comparten formato y criterio, pero el contenido es exclusivo de cada una — no se duplican ítems entre ediciones.

---

## 1. Principio rector: nunca inventar para llenar espacio

Esta es la regla más importante de todas, por encima de cualquier otra.

Si en una semana no hay suficiente material verificable de prioridad alta, **se deja la sección vacía con una nota explícita**, en vez de incluir contenido aproximado, no confirmado o inventado. Es preferible una edición corta y 100% verificada que una completa con dudas.

Cuando algo no se pudo confirmar con certeza (fecha exacta, texto completo de un voto, si una resolución ya salió o está en trámite), **decirlo explícitamente** en el ítem o en una nota metodológica al final — nunca asumir ni completar el vacío con una suposición presentada como hecho.

Si se identifica un falso positivo durante la investigación (una noticia vieja reflotada, una resolución derogada que aparece en buscadores como vigente, etc.), **descartarlo activamente** y, si es relevante, mencionarlo en la nota metodológica como algo que se evaluó y se excluyó.

---

## 2. Categorías de prioridad

### Prioridad alta — siempre se incluye si existe
- Normas con fecha límite de cumplimiento próxima (30-60 días)
- Fallos que cambian o consolidan un criterio jurisprudencial con **aplicación inmediata a casos en curso**
- Cualquier novedad donde la inacción genere perjuicio concreto al cliente (pérdida de plazo, multa, exposición a reclamo)

**Criterio de filtro:** la pregunta que define si algo es prioridad alta no es "¿es importante o noticioso?" sino **"¿hay algo concreto que un cliente del estudio debería hacer o saber por esto?"**. Una causa de alta sensibilidad institucional o mediática (por ejemplo, un planteo recusatorio en una causa de figura pública) NO es prioridad alta si no genera ninguna acción posible para un cliente típico del estudio — va como nota de color, no como ítem principal, sin importar cuánta repercusión tenga en medios.

### Prioridad media — se incluye como "Jurisprudencia con votos relevantes" o "Novedades y análisis"
- Votos en disidencia con argumentación sólida, identificados explícitamente como tales — útiles porque un abogado puede usarlos como base argumental para un caso futuro o una apelación
- Fallos que **reafirman jurisprudencia ya consolidada** (no son novedad, pero dan certeza de que el criterio sigue firme y citable) — ejemplo: una Cámara que vuelve a aplicar la doctrina de "Halabi" en una acción colectiva
- Normativa de alcance sectorial específico, si es relevante para el tipo de cliente del estudio

### Notas de color — sección final, formato breve
- Noticias institucionales sin impacto operativo directo: nombramientos, ferias judiciales, acordadas administrativas, actos protocolares, comunicados
- Formato: una línea por ítem, sin desarrollo extenso — para que el lector esté al tanto sin que compita en jerarquía visual con el contenido accionable
- Estas notas NUNCA deben mezclarse con prioridad alta, aunque tengan repercusión mediática alta (ver ejemplo del criterio de filtro arriba)

---

## 3. Estructura obligatoria de cada ítem de prioridad alta o media

Todo ítem que no sea nota de color debe tener estos componentes, en este orden:

1. **Título** que indique con precisión sobre qué versa (norma, fallo o instituto), no un titular genérico
2. **Badges de identificación:** tipo (Ley/Decreto/Fallo/Voto en disidencia/etc.), fuente (tribunal, organismo, número de RG), fecha o período
3. **Resumen** de 2-4 oraciones: qué dice la norma o el fallo, en lenguaje claro pero técnicamente preciso. Citar artículos, números de ley/RG, tribunal y fecha siempre que estén disponibles
4. **Caja "Clientes que se benefician / deben actuar"** — este es el componente más importante y el que más valor agrega. Debe bajar a perfiles concretos de cliente, no quedarse en lo genérico. Mal ejemplo: "puede ser relevante para algunos clientes". Buen ejemplo: "Trabajadores con sentencias laborales firmes pendientes de ejecución a quienes se les ofreció el pago en cuotas"
5. **Caja "Fecha límite"** (solo si aplica) — destacada visualmente, con la fecha exacta y, si es posible, los días u horas hábiles restantes
6. **Nota de advertencia** (solo si corresponde) — cuando el criterio no está consolidado, es de primera instancia, o hay riesgo de que cambie

---

## 4. Formato visual — usar siempre las plantillas adjuntas

Cada edición se entrega como archivo HTML completo, listo para pegar en Mailchimp o Brevo, siguiendo exactamente la estructura visual de las plantillas de referencia adjuntas a este paquete:

- `newsletter-juridico-template.html` — paleta pergamino oscuro (#2C1A0E) y dorado (#D4A843), para la Edición Jurídica
- `newsletter-contable-template.html` — paleta verde azulado oscuro (#0F2E2E) y menta (#4ABFA8), para la Edición Contable

**No generar markdown plano.** El resultado final siempre debe ser el archivo HTML completo, manteniendo la misma estructura de secciones, badges, cajas de alerta y pie de página que las plantillas. Usar el contenido de las plantillas como ejemplo de tono, nivel de detalle y formato exacto de cada componente — no solo como referencia de colores.

Mantener siempre:
- El header con marca "Iustitia.ar" y el badge de edición (Jurídica / Contable)
- La barra de índice ("En este número") con los temas de la semana
- Las secciones numeradas en romano (I, II, III)
- El CTA final invitando a consultar en la plataforma
- El footer con la cita de Santo Tomás de Aquino y el texto legal de distribución reservada

---

## 5. Tono y estilo de redacción

- Español argentino, técnico pero claro — está dirigido a profesionales, no hay que sobre-explicar conceptos básicos del derecho o la contabilidad
- Preciso en las citas: número de ley/decreto/RG, artículo, tribunal, sala, fecha — siempre que la fuente lo permita
- Sobrio, sin sensacionalismo ni urgencia artificial — la urgencia debe venir de hechos reales (plazos, vigencias), no del tono de la escritura
- Nunca usar el newsletter para promover contenido ajeno al criterio editorial (no es un espacio de opinión política o institucional)

---

## 6. Fuentes a consultar

Priorizar siempre fuentes primarias sobre secundarias:

**Primarias:** Boletín Oficial, InfoLEG, SAIJ, sitio de la CSJN (fallos y acordadas), CIJ (Centro de Información Judicial), sitio de ARCA/AFIP, Sistema de Información Parlamentaria (Senado/Diputados)

**Secundarias (para contexto y verificación cruzada, no como única fuente de un dato crítico):** Errepar, Microjuris, iProfesional, El Cronista, La Nación, Infobae — usar para confirmar interpretación o impacto práctico, no como fuente única de la existencia de una norma o fallo

Cuando una norma o fallo solo aparece en fuente secundaria sin poder confirmarse en la fuente primaria correspondiente, marcarlo explícitamente con una nota de "pendiente de verificación en fuente oficial".

---

## 7. Notificación al finalizar

Al completar ambas ediciones, enviar notificación push/email con un resumen breve (3-5 líneas) indicando:
- Qué encabeza cada edición (el ítem más relevante)
- Si hubo alguna semana floja en prioridad alta y cómo se manejó
- Cualquier dato que requiera confirmación manual antes de publicar

Los dos archivos HTML finales deben quedar disponibles en la sesión con nombres claros: `Iustitia-Legal-[fecha].html` y `Iustitia-Contable-[fecha].html`.
