# REGISTRO de demos — ledger de unicidad (plantilla: copiar a la raíz del repo de demos)

Leer ANTES de diseñar cualquier demo nueva: arquetipos, firmas y componentes aquí listados
están QUEMADOS y no se repiten. Actualizar en el MISMO commit de cada demo publicada
(antes del push — ver "Publicar" en la skill `demo-landing`).
Base: `https://mnonline2001.github.io/medine-demos/<slug>/`

| Negocio | Slug | Paleta | Tipografía / Densidad | Arquetipo | Técnica de firma | Nav / Footer | Tarjetas / CTAs | Fecha | Estado contacto |
|---|---|---|---|---|---|---|---|---|---|
| Silvio Centeno — técnico A/A (Maturín) | `silvio-centeno` | navy #101b33 + cobalto #254a90/#5374ca, blanco #f7f8f8 | Archivo (display black) + Permanent Marker acento; denso editorial técnico; base oscura con banda clara | spec-sheet industrial en bandas numeradas con hairlines | termostato gigante 33°→17° (contador + fondo que se enfría) + foto real duotono con clip-path diagonal | píldora flotante centrada / footer-póster display gigante | filas full-width sin cards; CTA rectángulo duro con sombra sólida | 2026-07-23 | demo enviada; llamada vie 24 10 am |
| Od. Jennifer Álvarez — odontóloga (Maturín) | `jennifer-alvarez` | claro #fbfdfd + tinta #16303a + aqua #2aa5a0 (coral 10%) | Fraunces + Karla; minimal con aire; base clara fría | bento grid desigual de celdas redondeadas | "agenda viva": selector día/turno que teclea burbuja de chat → wa.me + arco de sonrisa SVG line-drawing | wordmark suelto sin barra / footer una línea | celdas redondeadas sombra suave; CTA píldora | 2026-07-23 | por enviar (tras paso previo del playbook) |
| Juan Carlos Hernández — abogado (Sucre) | `juan-carlos-hernandez` | crema #f6f1e7 + tinta #1a2238 + ámbar #a97f2f | Playfair Display + Source Sans 3; editorial serena; base clara cálida | expediente editorial en columna angosta (cláusulas romanas, capitulares, §) | sello circular SVG que se estampa + frase que se entinta con el scroll | nav aparece-al-subir / footer-índice romano | renglones de formulario sin cards; CTA subrayado tipográfico | 2026-07-23 | enviado jue 23 noche |
| Dojo J.J. Rondón — karate-do (Maturín) | `dojo-jj-rondon` | carbón #17181c + rojo #d63a2f + hueso #f5f4f0 (colores de cinturones solo en la firma) | Bebas Neue + Work Sans; cartel deportivo denso; base oscura neutra | cartel de torneo one-pager con cortes diagonales (clip-path) y dorsales 01/02/03 de fondo | "camino del cinturón": franja sticky de 7 grados que se llena con el scroll + silueta SVG angular de patada | barra sticky clásica con borde rojo / mega-footer por columnas | tarjetas-cartel con corte diagonal y scroll-snap horizontal; CTA paralelogramo (skewX) | 2026-07-24 | por enviar |

## Notas de unicidad

- Los DIEZ campos de la fila importan: una demo nueva no puede repetir arquetipo, firma,
  nav, footer ni tratamiento de tarjetas de ninguna fila anterior (ejes de unicidad de
  `references/diseno.md` de la skill `demo-landing`).
- Anotar técnicas que se van quemando (ej. si `background-clip:text` ya se usó 2 veces,
  vetarlo) y alternar bases claras/oscuras y densidades entre demos consecutivas.
