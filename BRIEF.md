# Brief — Pivot Orvo.space: de inmobiliarias a PyMEs

## Objetivo
Rediseñar `index.html` de orvo.space cambiando el target de **inmobiliarias → PyMEs argentinas**. La web actual vende un agente de IA para inmobiliarias; la nueva versión debe vender **agentes de IA a medida para PyMEs** que automatizan atención al cliente, operaciones, cotizaciones, y cualquier proceso repetitivo.

## Referencia de contenido y estructura
El sitio https://orvo-ar.vercel.app/ (Artemea) ya tiene la dirección correcta de copy y estructura para PyMEs. **Usá su estructura como guía**, pero mejorá, expandí y pulí — queremos "la mejor página posible".

## MUST PRESERVE (no tocar)
1. **Logo Orvo** y branding (el texto/logo "Orvo" en el nav)
2. **Paleta de colores actual:**
   - Primario azul: `#2563eb`, `#1d4ed8`, `#2B55F5`
   - Texto oscuro: `#0f172a`, `#0D1228`
   - Acento teal: `#00B4A6`
   - Grises/fondos: `#f8fafc`, `#f1f5f9`, `#e2e8f0`
   - Éxito: `#16a34a`, `#dcfce7`
3. **Integración Calendly**: `https://calendly.com/juanagrippino/website-services?primary_color=d8dde4` — **dejar exactamente como está** (widget embebido + script asset de Calendly)
4. **Fuente Inter** de Google Fonts
5. Stack actual: **HTML + CSS + JS vanilla en un solo archivo `index.html`** (no agregar frameworks, no convertir a React/Next)
6. **vercel.json** no tocar
7. Meta tags: actualizar `title`, `description`, `og:*`, `twitter:*`, schema.org JSON-LD para reflejar el nuevo posicionamiento PyMEs (pero mantener el formato)

## Secciones a construir (ORDEN SUGERIDO — superá esto si tenés mejor idea)

### 1. Nav
- Logo "Orvo" a la izquierda
- CTA "Agendá una llamada" a la derecha (scroll al Calendly o abre widget)

### 2. Hero
- Título estilo: **"Tu negocio trabaja solo. Nosotros construimos los agentes que lo hacen posible."** (podés mejorarlo)
- Subtítulo: explicá que automatizan cualquier proceso con IA — atención, operaciones, cotizaciones, lo que haga falta
- CTA primario: "Agendá una llamada gratuita" → scroll a Calendly
- CTA secundario: "Ver caso Artemea" → scroll a caso
- Opcional: badge "● Agentes de IA para empresas argentinas"

### 3. Problema ("Tu equipo no debería estar haciendo esto")
4 cards con ícono/emoji:
- ⏳ Horas perdidas en tareas repetitivas
- 🌙 Perdés ventas fuera de horario
- 💸 Los errores manuales te cuestan plata
- 📈 Escalar requiere contratar más gente

### 4. Proceso ("Tres pasos para automatizar tu operación")
- 01 — Diagnóstico gratuito
- 02 — Construimos tu agente a medida
- 03 — Tu negocio se automatiza

### 5. Casos de uso ("¿Qué podemos automatizar?")
6 cards:
- 💬 Atención al cliente 24/7 por WhatsApp
- 📋 Cotizaciones y presupuestos automáticos
- 🗂️ Gestión operativa y planillas
- 📦 Seguimiento de pedidos y envíos
- 🔔 Escalado inteligente al equipo humano
- ⚡ Cualquier proceso repetitivo

### 6. Caso real — Artemea (DESTACADO, es el social proof principal)
**Este caso es real y está en producción.** Armá una sección visual fuerte tipo card/feature:
- Badge: "◆ Caso real · Agente en producción"
- Título: "Artemea — Moda D2C Argentina"
- Story:
  > Artemea es una marca de ropa argentina que vende online. El equipo perdía horas respondiendo por WhatsApp: preguntas de stock, estado de pedidos, tiempos de envío.
  >
  > Construimos un agente que consulta el stock y los pedidos en tiempo real, responde automáticamente las 24 horas, y solo notifica al equipo cuando hay algo que realmente requiere atención humana.
- Quote del cliente:
  > "Nuestro equipo dejó de responder WhatsApp manualmente. El agente lo resuelve solo y solo nos avisa cuando hay algo importante."
- 3 métricas:
  - **24/7** Atención continua
  - **0 hs** Dedicación manual
  - **100%** Consultas resueltas

### 7. (NUEVA — sumá valor) "Cómo trabaja tu agente"
Pequeña sección técnica/visual que muestre el flujo: Cliente → WhatsApp → Agente IA → (consulta sistemas / base de datos / APIs) → Respuesta automática / Escalado a humano. Diagrama simple en CSS o cards con flechas. Esto diferencia de competidores y muestra que hay ingeniería real.

### 8. (NUEVA — sumá valor) "Sectores donde ya vemos resultados"
Grid de 4–6 rubros que aplican (ej. e-commerce, servicios profesionales, salud, inmobiliarias, educación, gastronomía). Breve bajada en cada uno. **Incluí inmobiliarias como un rubro más** (así no perdemos ese mercado, pero ya no es el foco exclusivo).

### 9. Inversión / Pricing posture
- Título: "Cada negocio es distinto"
- Copy: "El precio depende del tipo de agente, la cantidad de procesos y el volumen de uso. Agendá una llamada y armamos una propuesta a medida."
- No mostrar tiers de precio. Solo CTA a Calendly.

### 10. Calendly (CTA FINAL)
- Título: "30 minutos para ver si un agente te hace sentido"
- Subtítulo: explicá qué van a sacar de la llamada (diagnóstico, propuesta concreta, sin compromiso)
- Widget Calendly embebido (mantener exactamente el código actual)

### 11. FAQ (NUEVA — sumá valor)
4–6 preguntas frecuentes:
- ¿Cuánto tarda en estar listo mi agente?
- ¿Con qué sistemas se puede integrar? (WhatsApp, Instagram, sitios web, CRMs, planillas, APIs)
- ¿Necesito equipo técnico?
- ¿Qué pasa si el agente no sabe responder?
- ¿Qué tan a medida es?
- ¿Y si después quiero cambiar cosas?

### 12. Footer
- Logo Orvo
- Email de contacto
- Links a redes (si las hay)
- Copyright 2026

## Requerimientos técnicos
- **Mantener el diseño en un único archivo `index.html`** con CSS y JS inline (así está hoy)
- **Mobile-first responsive** — testear mentalmente desde 375px hasta 1440px
- **Accesibilidad**: semantic HTML, `aria-*` donde aplique, contraste ok
- **Performance**: no sumar libraries nuevas salvo Calendly (que ya está). SVG inline mejor que imágenes
- **Animaciones fade-up existentes**: mantener la clase `.fade-up` si está implementada (la vi en el HTML actual con `d1`, `d2` delays)
- **SEO**: actualizar todos los meta tags, structured data, canonical, keywords para el nuevo posicionamiento PyMEs argentinas
- **Copy en español rioplatense** (voseo, "agendá", "contanos", "sumá", etc.)

## Tone & voice
- Directo, sin vender humo
- Usar ejemplos concretos (Artemea)
- Conciso, sin jerga de IA innecesaria
- Confianza técnica sin ser pretencioso
- Para founders/dueños de PyME que tienen poco tiempo y quieren resultados

## Entregable
`index.html` completamente reescrito (puede ser MUCHO más largo que el actual si hace falta, no te pongas límites). Si queda demasiado grande, está OK — es una landing, no una SPA.

**NO toques** `vercel.json`. **NO crees** archivos nuevos. Todo va en `index.html` (con posible excepción de un `/public` o `/assets` si realmente lo necesitás para SVGs, pero evitálo).

## Success criteria
1. Al abrir el file en el browser se ve pulido, profesional, rápido
2. El mensaje de "agentes de IA para PyMEs" es claro en los primeros 3 segundos
3. El caso Artemea es visualmente destacado y creíble
4. Calendly funciona igual que antes
5. La paleta azul de Orvo se siente consistente
6. Se lee como un producto real, no un template genérico

Go build it. Ultrathink.
