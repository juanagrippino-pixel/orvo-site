# Orvo × La Pyme: landing copy and section spec

Status: **copy/section spec only**. This document is for Fable/Codex to design and implement a future landing. It does **not** rewrite `index.html` yet.

Sources reviewed:
- `BRIEF.md`: keep Orvo as an operational control plane, not a generic bot; static HTML/CSS/JS; Rioplatense, direct copy; Calendly must remain operational.
- Current `index.html`: existing site is WhatsApp/D2C-agent led and should be reframed toward a premium app-first PyME operating console.
- `/root/orvo-agent/docs/research/2026-06-11-lapyme-deep-research.md`: La Pyme validates the category “sistema operativo para PyMEs”; Orvo should borrow the category breadth and seriousness, not clone ERP parity.

## Strategic direction

### Positioning

**Orvo es el centro operativo con agentes para PyMEs argentinas.**

Expanded promise:

> Orvo conecta ventas, stock, chats, facturación y caja en una consola app-first. Los agentes monitorean la operación, detectan casos y proponen próximos pasos, pero las decisiones salen de datos reales, evidencia y trazabilidad.

### What to say

- “Centro operativo con agentes para PyMEs argentinas.”
- “La consola de tu negocio: ventas, stock, WhatsApp, ARCA y caja en una sola vista.”
- “Agentes que monitorean, priorizan y recomiendan acciones.”
- “WhatsApp como canal de alerta, no como centro de control.”
- “La Pyme/Tango moderno, pero agentic, app-first y orientado a acción.”

### What to avoid

- Do not lead with “bot de WhatsApp”.
- Do not present Orvo as a generic AI platform.
- Do not fake ERP parity: accounting, full ARCA issuance, POS, multicurrency, and full inventory should be roadmap/readiness, not promised as live today.
- Do not make WhatsApp the hero surface. It is an alert/brief/escalation channel.
- Do not invent metrics. Use qualitative claims unless a verified customer metric is available.

## Visual direction for Fable/Codex

### Mood

Premium, calm, serious, local. Less “chatbot demo”, more “operating system for a growing business”.

### Palette

- Deep navy / near-black: `#0B1020`, `#111827`
- Electric blue: `#2563EB`
- Teal accent: `#14B8A6`
- Warm off-white: `#F8FAFC`, `#FFFFFF`
- Soft borders: `#E2E8F0`
- Success green only for resolved/healthy states: `#16A34A`

### UI references

- La Pyme/Tango category: familiar modules like ventas, stock, facturación, caja.
- Orvo differentiation: app-first console, operational cases, agent recommendations, evidence timeline.
- Premium SaaS: large hero mockup, glass cards, subtle gradients, crisp typography, high whitespace.

### Hero mockup prompt

Create an app mockup that looks like a real operating console, not a chat UI.

Suggested mockup content:

- Header: `Orvo OS` / `Consola operativa`
- Top cards:
  - `Ventas de hoy`
  - `Casos abiertos`
  - `Riesgo de stockout`
  - `ARCA pendiente`
  - `Caja / Mercado Pago`
- Main panel:
  - `Casos prioritarios`
  - `Causa probable`
  - `Evidencia`
  - `Acción sugerida`
- Right rail:
  - `Estado de módulos`
  - `Ventas · Conectado`
  - `Stock · Revisar`
  - `WhatsApp · Alertas activas`
  - `ARCA · Pendiente configurar`
  - `Caja · Pendiente conciliar`
- Small bottom note:
  - `WhatsApp se usa para alertas y briefs. La decisión y evidencia viven en Orvo.`

## Proposed landing structure

### 1. Announcement bar

**Purpose:** Signal the new category without overpromising.

**Copy:**

> Nuevo enfoque: Orvo pasa de agente puntual a centro operativo con agentes para PyMEs argentinas.

Optional CTA:

> Ver propuesta de landing

### 2. Navigation

**Nav labels:**

- Producto
- Módulos
- Agentes
- Casos
- Implementación
- Preguntas
- Agendá una llamada

**CTA:**

> Ver demo de consola

or

> Agendá una llamada

### 3. Hero

**Label:**

> Centro operativo con agentes para PyMEs

**H1 options:**

1. `Tu negocio no necesita otro bot. Necesita una consola que ordene la operación.`
2. `Orvo es la consola operativa de tu PyME, con agentes que detectan qué está pasando y qué hacer.`
3. `Ventas, stock, chats, facturación y caja en una sola consola con agentes.`

**Recommended H1:**

> Tu PyME no necesita otro bot. Necesita una consola que ordene la operación.

**Subcopy:**

> Orvo conecta ventas, stock, WhatsApp, facturación y caja para mostrar qué está pasando, qué está roto y qué acción conviene ejecutar. Los agentes monitorean la operación; la consola deja evidencia, trazabilidad y próximos pasos.

**Primary CTA:**

> Ver la consola

**Secondary CTA:**

> Agendá una llamada

**Proof strip:**

- `App-first`
- `Agentes con evidencia`
- `WhatsApp como alerta`
- `Para comercios y ecommerce argentinos`

### 4. Problem section

**Label:**

> El problema

**H2:**

> Crecer hace que la operación se rompa en pedazos.

**Body:**

> Cuando aumentan ventas, stock, chats y pagos, el equipo empieza a vivir entre pantallas: Tiendanube, WhatsApp, planillas, ARCA, Mercado Pago y mensajes internos. El problema no es falta de esfuerzo. Es falta de una consola que ordene señales, casos y decisiones.

**Cards:**

1. **Datos repartidos**
   - Ventas, stock, chats y caja viven en sistemas distintos. El equipo pierde tiempo cruzando información.

2. **Casos que aparecen tarde**
   - Stock bajo, pedidos pendientes, facturación incompleta o caja sin conciliar se detectan cuando ya molestan al cliente.

3. **WhatsApp domina todo**
   - El canal más rápido termina siendo el centro operativo. Mensajes, decisiones y evidencia se mezclan.

4. **Reportes que no mandan acción**
   - Un dashboard muestra qué pasó. Orvo ayuda a ver qué está pasando, por qué importa y qué conviene hacer ahora.

### 5. Product promise / app-first console

**Label:**

> Producto

**H2:**

> Una consola app-first para operar tu PyME con menos ruido.

**Body:**

> Orvo no reemplaza a tu sistema actual de golpe. Se apoya sobre tus fuentes de verdad y arma una capa operativa: módulos conectados, salud de operación, casos prioritarios, evidencia y recomendaciones de agentes.

**Feature blocks:**

1. **Vista diaria de operación**
   - Ventas, pedidos, stock, chats, ARCA y caja en una vista pensada para decidir rápido.

2. **Casos operativos**
   - Cada excepción tiene causa, evidencia, prioridad y próximo paso recomendado.

3. **Agentes gobernados**
   - Los agentes monitorean, comparan, resumen y proponen. No inventan métricas ni toman decisiones sin evidencia.

4. **Trazabilidad**
   - Historial de corridas, cambios, alertas y acciones para que el equipo sepa qué pasó y quién lo resolvió.

### 6. Module map

**Label:**

> Módulos

**H2:**

> La dirección de La Pyme/Tango, con ejecución agéntica.

**Body:**

> La promesa no es clonar un ERP. Es empezar por los módulos que más duelen en una PyME real y convertirlos en una consola accionable.

**Module cards:**

1. **Ventas / pedidos**
   - Estado de ventas, pedidos, canales y señales de caída o acumulación.
   - MVP: real / fuerte wedge.

2. **Stock**
   - Riesgos de stockout, productos críticos y alertas de inventario cuando hay fuente disponible.
   - MVP: readiness + riesgo mínimo real.

3. **WhatsApp / atención**
   - Conversaciones pendientes, escalados y briefs.
   - Importante: WhatsApp es canal de alerta, no la consola principal.

4. **Facturación / ARCA**
   - Checklist de conexión, facturas pendientes y readiness para automatizar emisión.
   - MVP: checklist primero; emisión completa luego.

5. **Caja / Mercado Pago**
   - Pagos, conciliación y señales de caja cuando la fuente está conectada.
   - MVP: readiness + conciliación mínima.

6. **Agentes / recomendaciones**
   - Monitoreo, priorización, explicación y próximos pasos.
   - MVP: casos operativos con evidencia.

**Optional roadmap note:**

> Más adelante: compras, contabilidad, multimoneda, MCP/API y más automatizaciones. No los mostramos como disponibles hoy si todavía no están conectados.

### 7. How Orvo works

**Label:**

> Cómo trabaja

**H2:**

> De datos dispersos a casos accionables.

**Flow:**

1. **Conecta fuentes**
   - Tiendanube, WhatsApp, stock, ARCA, Mercado Pago, planillas o APIs según el caso.

2. **Monitorea módulos**
   - Orvo revisa señales reales: ventas, stock, chats, facturación y caja.

3. **Abre casos**
   - Si algo está roto, atrasado o requiere decisión, aparece como caso con prioridad.

4. **Genera evidencia**
   - Cada caso muestra datos, origen y contexto. Nada de “el agente dice”.

5. **Recomienda acción**
   - El agente propone qué revisar, qué responder o qué configurar.

6. **Envía alertas**
   - WhatsApp, email u otros canales reciben alertas y briefs. La consola sigue siendo la fuente de decisión.

**Copy note:**

> WhatsApp puede avisar, pero no debería ser donde se decide la operación completa.

### 8. Use cases

**Label:**

> Casos de uso

**H2:**

> Casos que una PyME entiende enseguida.

**Cards:**

1. **Stockout en productos clave**
   - “Este producto está por quedarse sin stock y sigue vendiéndose.”

2. **Ventas fuera de patrón**
   - “Las ventas de hoy bajaron respecto al patrón esperado; revisá canal, stock o campaña.”

3. **Chats pendientes**
   - “Hay conversaciones sin respuesta que pueden convertirse en reclamos o ventas perdidas.”

4. **ARCA pendiente**
   - “Falta conectar facturación o hay comprobantes pendientes de revisión.”

5. **Caja sin conciliar**
   - “Hay pagos de Mercado Pago o movimientos que conviene revisar antes de cerrar el día.”

6. **Fuente desconectada**
   - “El módulo está marcado como pendiente porque falta acceso, token o configuración.”

### 9. WhatsApp positioning section

**Label:**

> Canal vs consola

**H2:**

> WhatsApp es clave. Pero no debería ser tu sistema operativo.

**Body:**

> Para una PyME argentina, WhatsApp es donde llegan clientes, proveedores y urgencias. Por eso Orvo lo usa como canal de alerta y brief. Pero la consola, la evidencia, los casos y las decisiones viven en Orvo.

**Comparison table:**

| Antes | Con Orvo |
|---|---|
| Decisiones mezcladas en chats | Casos priorizados en consola |
| Alertas sueltas | Alertas con evidencia y próximo paso |
| WhatsApp como sistema operativo informal | WhatsApp como canal de notificación |
| Reportes que miran el pasado | Casos que ayudan a decidir ahora |

### 10. Why Orvo is different

**Label:**

> Diferencia Orvo

**H2:**

> No es un ERP, no es un dashboard y no es un bot suelto.

**Three columns:**

1. **ERP tradicional**
   - Ordena datos, pero suele pedir que el equipo encuentre el problema.
   - Orvo agrega casos, agentes y evidencia.

2. **Dashboard**
   - Muestra métricas.
   - Orvo explica qué está pasando y qué acción conviene tomar.

3. **Bot de WhatsApp**
   - Responde en un canal.
   - Orvo monitorea la operación completa y usa WhatsApp solo para alertas.

**Closing copy:**

> La categoría es sistema operativo de PyME. La ventaja de Orvo es que ese sistema operativo tiene agentes gobernados, evidencia y una consola app-first.

### 11. Implementation / pilot

**Label:**

> Implementación

**H2:**

> Arrancamos por una consola útil, no por una migración infinita.

**Body:**

> El primer piloto conecta las fuentes más críticas, arma la vista diaria y deja casos operativos reales. Después sumamos módulos, automatizaciones y agentes según el valor que aparezca en la operación.

**Steps:**

1. **Diagnóstico operativo**
   - Revisamos ventas, stock, chats, facturación y caja.

2. **Mapa de fuentes**
   - Definimos qué sistemas ya existen, qué falta y qué se puede conectar.

3. **Consola inicial**
   - Armamos la vista diaria y los primeros casos accionables.

4. **Agentes gobernados**
   - Configuramos monitoreo, alertas, evidencia y recomendaciones.

5. **Iteración con datos reales**
   - Ajustamos prioridades, módulos y automatizaciones según uso real.

**Pilot CTA copy:**

> Piloto recomendado: consola diaria + casos operativos + alertas por WhatsApp.

### 12. CTA section

**H2:**

> Construyamos la consola operativa de tu PyME.

**Body:**

> Si hoy tu equipo vive entre WhatsApp, Tiendanube, stock, ARCA, Mercado Pago y planillas, Orvo puede ordenar esa operación en una consola con agentes, evidencia y próximos pasos.

**CTA:**

> Agendá una llamada

**Secondary:**

> Ver estructura propuesta

### 13. FAQ

**Questions and answers:**

1. **¿Orvo reemplaza a La Pyme, Tango o mi sistema actual?**
   - No necesariamente. La idea inicial es conectar fuentes existentes y agregar una consola operativa con agentes. Con el tiempo, Orvo puede crecer hacia más módulos, pero no arrancamos prometiendo clonar un ERP completo.

2. **¿WhatsApp va a seguir siendo importante?**
   - Sí. WhatsApp es un canal clave para alertas, briefs y escalados. La diferencia es que la decisión, evidencia y trazabilidad viven en la consola de Orvo.

3. **¿Orvo es un bot?**
   - Puede incluir agentes, pero no es solo un bot. Es una consola operativa que usa agentes para monitorear, priorizar y recomendar acciones sobre datos reales.

4. **¿Qué módulos entran primero?**
   - Para una PyME/ecommerce, lo más útil suele ser ventas/pedidos, stock, WhatsApp/atención, ARCA readiness y caja/Mercado Pago. El orden depende de las fuentes disponibles.

5. **¿Necesito un equipo técnico?**
   - No. La idea es que el equipo opere desde la consola. La integración y configuración pueden manejarse como implementación asistida.

6. **¿Orvo inventa métricas o conclusiones?**
   - No. Las métricas y casos salen de fuentes conectadas, evidencia y reglas verificables. Si falta una fuente, Orvo debe marcarlo como pendiente, no inventarlo.

7. **¿Cuándo conviene usar Orvo?**
   - Cuando la operación ya no entra en una planilla, WhatsApp se volvió el sistema operativo informal y el equipo necesita ver casos, prioridades y próximos pasos.

## Suggested SEO metadata

**Title:**

> Orvo — Centro operativo con agentes para PyMEs argentinas

**Meta description:**

> Orvo conecta ventas, stock, chats, facturación y caja en una consola app-first con agentes, evidencia y casos accionables para PyMEs argentinas.

**OG title:**

> Orvo — Consola operativa con agentes para PyMEs

**OG description:**

> Una consola app-first para ordenar ventas, stock, WhatsApp, ARCA y caja con agentes gobernados y evidencia.

## Implementation notes for Codex

- Keep the site static: HTML/CSS/JS vanilla.
- Preserve Calendly functionality.
- Do not add secrets, tokens, phone numbers, or personal data.
- Use Spanish Rioplatense: “vos”, “agendá”, “hacés”, “tenés”.
- Make the first screen feel like a premium app, not a chatbot landing.
- Keep WhatsApp visible, but never as the main interface.
- If a module is not ready, label it as “readiness”, “pendiente”, “próximamente” or “checklist”, not as live functionality.
- Use proof carefully: Artemea can remain as a real WhatsApp-agent case, but the new PyME landing should not pretend Artemea validates the full operating console unless that is true.

## One-line creative brief

> Diseñar una landing premium para Orvo como “centro operativo con agentes para PyMEs argentinas”: app-first, con consola realista, módulos tipo La Pyme/Tango, agentes gobernados, evidencia y WhatsApp solo como canal de alerta.
