# Spec — Landing "Ayelen Productos Capilares"

Fecha: 2026-06-23

## Objetivo
Landing tipo catálogo elegante cuyo objetivo principal es que la persona **contacte por WhatsApp**. Sin carrito ni pagos online.

## Marca
- Nombre: **Ayelen Productos Capilares** (alisados y tratamientos capilares)
- Instagram: @productos_capilares_aye
- WhatsApp: 11 7666-5975  → link `https://wa.me/5491176665975`
- Estética: **glam / lujo** → fondo oscuro (berenjena/negro), detalles **dorados** y **lila**, tipografía con toques de caligrafía como el logo.

## Técnico
- **Un solo archivo `index.html`** autocontenido (HTML + CSS + JS embebido). Sin frameworks ni build.
- **Mobile-first** (tráfico viene de Instagram en celular). Botones ≥44px, texto legible, animaciones que degradan en pantallas chicas.
- Hosteable en Netlify / Vercel / GitHub Pages.

## Secciones (orden vertical, mobile-first)
1. **Header fijo** — logo + acceso a WhatsApp.
2. **Hero** — degradado lila/dorado sobre fondo oscuro, logo, titular, botones WhatsApp (principal) + Instagram.
3. **Por qué Ayelen** — 3 íconos: calidad profesional · resultados que duran · atención personalizada.
4. **Catálogo de alisados** — grid de tarjetas oscuras con borde dorado. 14 alisados, cada uno con nombre + micro-descripción + botón "Consultar" que abre WhatsApp con mensaje pre-cargado del producto.
5. **CTA final** — franja con botón grande de WhatsApp.
6. **Footer** — Instagram, WhatsApp, @.

## Extras
- Botón **flotante** de WhatsApp siempre visible.
- Links de WhatsApp con mensaje pre-cargado por producto.
- Animaciones suaves al hacer scroll.

## Catálogo (por categorías, generado por JS en index.html)
- **Alisados:** Japonés, Diamante, 3 en 1, XXL, Bio Plex, Cherry, Espejo, Extra Fuerte, Siliconado, Cirugía, Cristal, Colágeno y Argán, Ácido Hialurónico, Plex.
- **Nutriciones:** Cirugía, Diamante, Aceite de Coco, Colágeno y Argán, Brasilera, Botox.
- **Tratamientos:** Botox, Queratina, Biotina, Levanta Muerto, Oro Líquido, Matizador Violeta.

Descripciones de **Japonés** y **Diamante** = textuales (las pasó la clienta). El resto son borradores a confirmar.

## Pendientes / a revisar por la clienta
- **Descripciones (borrador)**: todas menos Japonés y Diamante están redactadas por nosotros; la clienta debe revisarlas para que las propiedades de cada producto sean exactas.
- **Fotos**: las actuales (botella rosa sobre manta) no combinan con el look oscuro; el catálogo va en texto. Sección de galería futura cuando haya fotos con buen fondo.
- Confirmar número de WhatsApp definitivo (el logo dice 11 7666-5975; una etiqueta vieja decía 1138134614).
