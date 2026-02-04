# nomi pass — Brand Assets

## Brand Name
- Written as: **nomi pass** (lowercase, two words with space)
- "nomi" = regular weight, white
- "pass" = semibold weight, gold

## Colors

| Name | Hex | Usage |
|------|-----|-------|
| Black | `#1A1A1A` | Primary background |
| Black Deep | `#111111` | Secondary background |
| Accent (Gold/Taupe) | `#C4A77D` | Logo "pass", CTAs, highlights |
| Accent Hover | `#D4B78D` | Hover states |
| White | `#FFFFFF` | Text, logo "nomi" |
| Gray | `#888888` | Muted text |
| Border | `#2A2A2A` | Subtle borders |

## Typography

| Usage | Font | Weight |
|-------|------|--------|
| Logo | Sora | 400 (nomi), 600 (pass) |
| Headings | Sora | 600-700 |
| Body | Inter | 400-500 |

**Letter Spacing:** Logo uses `0.1em` spacing

## Logo Files

### Full Logo
- `logo-full.svg` — "nomi pass" horizontal logo

### Icon (Gateway)
- `icon-gp.svg` — Gateway arch icon (512x512)
- `icon-gp-standalone.svg` — Gateway arch icon with paths (no font dependency)
- `favicon.svg` — Optimized for small sizes (32x32 favicon)

### Icon Design
The gateway arch symbol represents:
- Opening doors to extraordinary experiences
- Access and exclusivity
- Premium membership

### Icon Colors
- **Arch** = White (`#FFFFFF`)
- **Accent bar** = Gold (`#C4A77D`)
- **Background** = Black (`#1A1A1A`)

## Favicons

Copy these to the site root:
- `favicon.svg` — Modern browsers
- `favicon.ico` — Legacy browsers (generate from SVG)
- `apple-touch-icon.png` — iOS (180x180, generate from icon-gp-standalone.svg)

## Generating PNG Icons

To generate PNG icons from SVG for app icons:

```bash
# Using Inkscape (if installed)
inkscape icon-gp-standalone.svg -w 180 -h 180 -o apple-touch-icon.png
inkscape icon-gp-standalone.svg -w 192 -h 192 -o icon-192.png
inkscape icon-gp-standalone.svg -w 512 -h 512 -o icon-512.png

# Or use online tools like realfavicongenerator.net
```

## App Icon Sizes Needed

| Platform | Size | File |
|----------|------|------|
| Favicon | 32x32 | favicon.ico |
| Apple Touch | 180x180 | apple-touch-icon.png |
| Android | 192x192 | icon-192.png |
| Android | 512x512 | icon-512.png |
| iOS App | 1024x1024 | AppIcon.png |
