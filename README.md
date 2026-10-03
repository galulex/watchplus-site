# watch.ab.team

Jekyll site on GitHub Pages. Push to `main` and GitHub builds it.

## Add an app

Create `_apps/<slug>.md`. The page appears at `/apps/<slug>/` and as a card on the home page.

```yaml
---
name: LED Remote
order: 9                 # position in the grid
kind: app                # app | watchface
tagline: Control BLE LED strips from your watch
icon: https://store-cdn.zepp.com/....png   # copy from zepp.amazla.app/app/<id>
zepp: 123456             # store id = the number in zepp.amazla.app/app/<id>
garmin: <uuid>           # optional; from apps.garmin.com/apps/<uuid>. Missing = "coming soon"
pro: $2.99 once          # optional
shape: round             # optional: round | square | band — which watch frame the shots sit in
devices_except: ["Amazfit Band 7"]  # optional; omit = every watch in _data/devices.yml
shots:                   # optional, CDN URLs (a watch face with none shows its icon)
  - https://store-cdn.zepp.com/....png
---
Description in Markdown.
```

Preview locally: `jekyll serve` → http://localhost:4000

New Zepp watch: add it to `_data/devices.yml` (name, label, shape, image), same as `~/zepp_syncer/src/sync.js`.
