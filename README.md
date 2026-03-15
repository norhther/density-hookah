# La Escala de Densidad de Sarkis

**La guía técnica y matemática para el packeo perfecto de cachimba/hookah.**

Desarrollada por **Sarkis Alexander** (Hookah UNLTD), esta herramienta elimina las suposiciones al preparar una cazoleta. Basada en entender la capacidad máxima de cada cazoleta (Cement Pack) y calcular matemáticamente todos los niveles de densidad a partir de ahí.

## Demo

Abre `index.html` en tu navegador — no requiere servidor ni dependencias externas.

## Cómo funciona

1. **Cement Pack (100%)** — Máxima cantidad absoluta de tabaco que cabe aplastado al máximo. Solo sirve como referencia de cálculo, no se fuma.
2. **Dense Pack = 90% del Cement Pack** — La piedra angular de la escala.
3. Todos los demás niveles se calculan como porcentaje del Dense Pack:

| Nivel | Fórmula | Ideal para |
|---|---|---|
| Fluff Pack | Dense × 0.50 | Social Smoke, Chaos, tabaco alemán |
| Semi-Fluff | Dense × 0.625 | Tabacos rubios ligeros |
| Normal Pack | Dense × 0.75 | Al Fakher, Adalya, Haze, Overdozz |
| Semi-Dense | Dense × 0.875 | Darkside, Nakhla, Must Have |
| Dense Pack | Dense × 1.0 | Tangiers, KFC, Serpent |

### Micro-variaciones (Normal, Semi-Dense, Dense)

- **Light** — Nivel − 1g (rozando la densidad inferior)
- **Standard** — El gramaje exacto del nivel
- **Plus** — Punto medio entre el nivel actual y el siguiente (para marcas con más melaza o corte especial)

## Ejemplo práctico (cazoleta Alpaca Mini Rook / Gravyl)

| Nivel | Gramaje |
|---|---|
| Cement Pack | 22 g |
| Dense Pack | ~19.8 g |
| Semi-Dense | ~17.3 g |
| Normal Pack | ~14.9 g |
| Semi-Fluff | ~12.4 g |
| Fluff Pack | ~9.9 g |

## Tecnología

- HTML5 / CSS3 / JavaScript vanilla
- Sin frameworks ni dependencias — un único archivo `index.html`
- Google Fonts: Cinzel, Cormorant Garamond, DM Mono
- Canvas API para efectos de partículas de brasa

## Créditos

Fórmula y metodología: **Sarkis Alexander — Hookah UNLTD**
Implementación web: **norhther**
