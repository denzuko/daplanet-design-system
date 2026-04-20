# daplanet-design-system

Canonical CSS design system for Da Planet Security / Da Planet Radio.

Tokens verified against [klaxon.dapla.net](https://klaxon.dapla.net) and [thelounge-theme-daplanet](https://github.com/denzuko/thelounge-theme-daplanet) v1.0.8. Zero framework dependencies.

## Files

| File | Purpose |
|------|---------|
| `daplanet-design-system.css` | Standalone drop-in — tokens, resets, all components |
| `werc/style.css` | werc site theme override |

## Usage

```html
<link rel="stylesheet" href="daplanet-design-system.css" />
```

jsDelivr CDN:

```html
<link rel="stylesheet"
  href="https://cdn.jsdelivr.net/gh/denzuko/daplanet-design-system@master/daplanet-design-system.css" />
```

## Components

- Tokens — 9 canonical color tokens, typography, spacing scale
- `.dp-scanlines` — CRT scanline overlay mixin
- `.btn` — bracket-style buttons (primary, secondary, ghost, danger, sm, lg)
- `.card` — panel cards with accent bar (amber/red variants)
- `.badge` — status badges including animated `.badge-live`
- `.stat-row` / `.stat-grid` — icecast-style key/value stat rows
- `.dp-nav` — `[ bracket ]` navigation pattern
- `.mount-card` — stream/mount point card
- `.now-playing-bar` — now-playing strip

## Related

- [thelounge-theme-daplanet](https://github.com/denzuko/thelounge-theme-daplanet)
- [navidrome-theme-daplanet](https://github.com/denzuko/navidrome-theme-daplanet)
- [navidrome-landing-daplanet](https://github.com/denzuko/navidrome-landing-daplanet)

## License

BSD-2-Clause © Dwight Spencer / Da Planet Security
