# The Therapy Couch International (Rod Waddington)

Online and face to face hypnotherapy, NLP, Mental Space Psychology, coaching. Dukinfield, Manchester.
Current site content and images: `assets/current-site-content.md`, `assets/current-site/`.

## Direction
- Minimal, calm, elegant. Follows the look of good therapy-industry sites: lots of space, few elements, soft colour.
- Nothing from the old site's palette (no dark red, no Wix pastels).

## Colours
Sampled from `references/Color palette/` (palette reference only, not the reference brand's logo or type).

| Token | Hex | Use |
|---|---|---|
| forest | #385B47 | Darkest green, headings on light, footer |
| leaf | #5B826F | Buttons, links |
| sage | #81998C | Secondary accents |
| deep-sea | #4E6D70 | Body text option, dark sections |
| sea-foam | #7F9CA0 | Soft accents, borders |
| stone | #DAD0C6 | Light text on gradient, cards |
| gold | #A37D3F | Sparing highlight only |
| page | #ECE7E1 | Main page background |

## Gradient (hero / background)
Soft blush on the far left, misty blue, sage in the middle, deep forest top right. Sampled points:
left edge #D7CDC6 · left #94AAAF · mid #7D978E / #688D87 · right #476860 · top right #3D624E · bottom right #567575

```css
background:
  radial-gradient(ellipse 60% 70% at 100% 0%, #3D624E 0%, transparent 70%),
  radial-gradient(ellipse 50% 60% at 95% 100%, #567575 0%, transparent 70%),
  radial-gradient(ellipse 60% 70% at 50% 20%, #688D87 0%, transparent 70%),
  linear-gradient(90deg, #D7CDC6 0%, #94AAAF 20%, #7D978E 55%, #476860 100%);
```
(Starting point, not yet previewed against the reference.)

## Fonts
- Headings: Glowgirl (supplied, `assets/glowgirl-modern-elegant-serif-…/`). Regular only, no italic or bold. Self-hosted at `site/fonts/glowgirl.woff2`.
- Body: Jost is still a placeholder. Ask before picking a final body font.
Set via `--font-display` / `--font-body` in `site/css/styles.css`.

## Stack
Plain HTML/CSS/JS in `site/` (first draft). Confirm before any move to Tailwind or Elementor.

## Logo
None exists. Ask before designing one.
