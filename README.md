# watch.ab.team

Jekyll site on GitHub Pages. Push to `main` and GitHub builds it. No JS: filters and tabs are CSS (`:has()` on radio inputs), effects are CSS scroll-driven animations.

## Add an app

1. Images in `assets/apps/<slug>/`, all webp: `icon.webp` (192 px), Zepp screenshots `z1.webp…` (the store's 360×360 masked PNGs), Garmin screenshots `g1.webp…`.
2. Watches in `_data/support.yml` under `<slug>`: `amazfit:` names from `_data/devices.yml`, `garmin:` names from `_data/garmin.yml`.
3. `_apps/<slug>.md`. The page appears at `/apps/<slug>/` and as a card on the home page.

```yaml
---
name: LED Remote
order: 7                 # position in the grid
cat: tools               # tesla | tools | talk | sport | life ("More apps" picks the same cat)
kind: app                # app | watchface
new: true                # optional "New" badge + filter
soon: true               # optional: not approved yet (no zepp id needed)
accent: "#ff3bd4"        # page colour; accent2 optional
tagline: Control Bluetooth LED strips from your watch   # card + SEO title
title: Your LED strip, <em>on your wrist.</em>          # hero headline, <em> takes the accent
pitch: One or two sentences under the headline (also the meta description).
zepp: 173878             # store id = the number in zepp.amazla.app/app/<id>
garmin: <uuid>           # optional, apps.garmin.com/apps/<uuid>; garmin_name if the Garmin title differs
garmin_soon: true        # optional "Garmin · coming soon" button
site: https://amazla.app  # optional landing page (button "site_label ↗")
companion: https://wt.ab.team  # optional web companion (button "companion_label ↗", "Web" tag on the card)
pro: Pro $2.99 once      # optional, shown in the price line; any value sets the Pro badge
shots: 4                 # number of z*.webp; gshots / gsize for Garmin
chips: ["🎨 Colour", "💡 On"]               # 2 floating labels on the hero
facts: [{ v: "Direct", k: "…" }]             # 3 stat cards
features: [{ i: "🌈", t: "Title", d: "Text", w: 4 }]   # bento; w = 2/3/4/6 of 6 columns
steps: [{ t: "…", d: "…" }]
plans: [{ name: Free, price: "$0", items: [...] }, { name: Pro, price: "$2.99", per: once, pro: true, items: [...] }]
faq: [{ q: "…", a: "…" }]                    # also emitted as FAQPage JSON-LD
final: Light it up.      # closing headline
---
Optional Markdown, shown as "The story".
```

Preview locally: `jekyll serve` → http://localhost:4000

New Zepp watch: add it to `_data/devices.yml` (name, label, shape, image in `assets/devices/`).
