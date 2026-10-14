---
name: Glucose Field
order: 23
cat: health
kind: app
os: garmin
soon: true
accent: "#ff4d5e"
accent2: "#3fd46a"
tagline: Your CGM glucose live on the run screen
title: Glucose, <em>mid-run.</em>
pitch: Your CGM reading right where you train, from Nightscout. No reaching for your phone, no leaving the activity screen.
pro: Pro available
gshots: 3
gsize: [400, 513]
chips: ["🩸 <span>112</span> mg/dL →", "🟢 In range"]
facts:
  - { v: "5 min", k: "background updates, even mid-run" }
  - { v: "Any CGM", k: "With a Nightscout uploader" }
  - { v: "Colours", k: "Green in range, amber high, red low" }
features_title: Train with your numbers.
features:
  - { i: "🩸", t: "Live reading", d: "Your glucose in an activity data field, coloured by range.", w: 3 }
  - { i: "⏱️", t: "Reading age", d: "Time since the last value, so you notice sensor gaps.", w: 3 }
  - { i: "👀", t: "Glance", d: "Value, trend and age in the glance list." }
  - { i: "📈", t: "Pro", d: "Trend arrow, 5-minute delta, and your own high and low colours." }
  - { i: "🔌", t: "Your CGM", d: "Dexcom G6/G7, Libre 2/3, Guardian 4, Eversense and more, through Nightscout." }
plans:
  - { name: "Free", price: "$0", items: ["Live glucose in a data field", "Range colours", "Reading age", "Glance"] }
  - { name: "Pro", pro: true, items: ["Trend arrow", "5-minute delta", "Your own thresholds"] }
faq:
  - { q: "What do I need?", a: "A running Nightscout instance, and your phone with Garmin Connect nearby for updates." }
  - { q: "Is it a medical device?", a: "No. Don’t make treatment decisions from it." }
final: Run steady.
---
