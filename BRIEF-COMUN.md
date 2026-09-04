# BRIEF COMÚN — Demos de venta (plantilla: copiar a la raíz del repo de demos)

Estas páginas son DEMOS de venta: el dueño del negocio la abre desde un DM de Instagram
(90% móvil) y debe decir "esto es lo que necesito". Cada página se juega un cierre.

## Regla de oro: que NO parezca hecha con IA

Prohibido el look genérico: hero centrado + 3 cards iguales + testimonios + footer.
Cada demo tiene su propio ARQUETIPO DE LAYOUT y sus COMPONENTES (vienen en el brief
individual). Además:

- Layouts asimétricos donde aplique; jerarquía tipográfica agresiva (display grande de
  verdad, 96-140px en desktop para el H1 si el arquetipo lo pide).
- Cero lorem ipsum, cero "[placeholder]", cero datos inventados: SOLO el contenido real del
  brief individual. Si falta un dato, escribe copy que no lo necesite.
- Nada de emojis como bullets. Nada de degradados morados por defecto ni glassmorphism gratuito.
- Microcopy con acento venezolano natural y profesional ("Escríbenos", "Cotiza por WhatsApp").
- Detalles artesanales: numeración de secciones (01/02/03), reglas/bordes finos, etiquetas
  uppercase con tracking, patrones SVG propios del rubro, transiciones sutiles.

## Stack técnico (obligatorio)

- UN archivo `index.html` autocontenido (CSS en `<style>`, JS vanilla mínimo inline).
  Assets locales en `./assets/` (logo y fotos del negocio si existen).
- Google Fonts: máximo 2 familias (las indica el brief individual). `preconnect` correcto.
- Mobile-first responsive. Probar mentalmente en 390px: el hero debe impactar EN MÓVIL.
- Imágenes externas: SOLO si verificas con curl que la URL devuelve 200 y es hotlinkeable
  (images.unsplash.com funciona). Si no, arte CSS/SVG: gradientes cinematográficos, patrones,
  siluetas SVG dibujadas por ti. Un hero de gradiente + patrón + tipografía enorme bien hecho
  vale más que una foto rota. NUNCA dejes un <img> sin verificar.
- `<meta name="robots" content="noindex">` (es una demo).
- `<meta name="color-scheme" content="only light">` + `html { color-scheme: only light; }` — las demos
  se diseñan en UNA sola versión; sin esto, el modo oscuro automático de Chrome/Android recalcula
  los colores y arruina la paleta (vinotinto→rosa, degradados descuadrados; visto en Coferpan).
- OG tags + `<title>` con el nombre del negocio. Favicon: emoji SVG inline o logo local.
- Accesibilidad: contraste AA mínimo, `alt` en imágenes, un solo `h1`, focus-visible,
  `prefers-reduced-motion` respetado.
- JS permitido y recomendado con moderación: menú móvil, reveal-on-scroll sutil
  (IntersectionObserver), y la interacción específica que pida el brief (filtros, steppers,
  selectores de sede). Sin librerías.

## Elementos obligatorios en TODAS las demos (la FORMA la dicta el brief individual)

Estos son ELEMENTOS requeridos, NO formas fijas: el nav y el footer deben variar de forma
entre demos (píldora flotante, rail lateral, overlay, footer-póster, una línea minimal, etc.
— el brief individual asigna cuál). Dos demos con el mismo nav o el mismo footer = fallo.

1. **Navegación** con acceso al logo (asset local o wordmark tipográfico fiel) + CTA WhatsApp,
   en la forma que asigne el brief individual.
2. **Hero** según dirección de arte del brief individual.
3. **Botón flotante de WhatsApp** (esquina inferior derecha, SVG del logo de WhatsApp, verde
   #25D366) con `https://wa.me/<numero>?text=<mensaje prellenado url-encoded>` — número y
   mensaje en el brief individual. Si el negocio no tiene WhatsApp público, el FAB apunta a su
   Instagram DM.
4. **Contacto/ubicación** con los datos reales.
5. **Cierre de página** (footer en la forma asignada) con: redes sociales reales (SVG icons
   inline, no font-awesome), datos del negocio, y el sello: `Demo diseñada por Medine.tech ·
   Esta es una propuesta de diseño — no es el sitio oficial` (discreto pero visible, con link
   a https://medine.tech).
6. Los precios/promos reales del brief individual — son el corazón de la demo: el dueño debe
   ver SU negocio, no un template. Si hay fotos reales del negocio en ./assets/, tienen
   prioridad sobre cualquier stock.
7. **2-3 técnicas modernas de frontend** (las asigna el brief individual) al servicio de la
   marca — nunca decoración gratuita; siempre con fallback y prefers-reduced-motion.

## Definición de "listo"

Antes de terminar: relee tu HTML completo, verifica que cada link funciona (wa.me bien
formado, redes correctas), que no quedó ningún TODO/placeholder, que el contraste pasa AA,
y que en 390px nada se desborda horizontalmente. Tu último mensaje debe ser solo: ruta del
archivo + 3 líneas describiendo el concepto visual elegido.
