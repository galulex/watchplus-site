---
name: HTTP
order: 11
cat: tools
kind: app
accent: "#7a5cff"
accent2: "#22d3a6"
tagline: Send HTTP requests from your watch
title: One tap. <em>Any API.</em>
pitch: "Send HTTP requests from your watch. Set up an action once in the Zepp app, then fire it with a tap: open the garage, run a webhook, ping Home Assistant."
zepp: 124128
pro: Pro $2.99 once
shots: 2
chips: ["▶ POST /garage", "✅ <span>200</span> OK"]
facts:
  - { v: "1–4", k: "big buttons per screen" }
  - { v: "Any method", k: "Headers and body included" }
  - { v: "Widgets", k: "Trigger from the watch face" }
features_title: An API client for your wrist.
features:
  - { i: "⚡", t: "Any request", d: "Any URL, any method, headers and a body. If it has an endpoint, you can hit it.", w: 4 }
  - { i: "🔘", t: "Big buttons", d: "1 to 4 per screen, easy to hit on the move.", w: 2 }
  - { i: "🧩", t: "Widget and cards", d: "Fire an action without opening the app." }
  - { i: "📋", t: "See the reply", d: "The status code and the response on screen." }
  - { i: "⚙️", t: "Set up on your phone", d: "Build your actions in the Zepp app. No typing on the watch." }
steps:
  - { t: "Add an action", d: "In the Zepp app, give it a name, a URL, a method, headers and a body." }
  - { t: "It syncs", d: "The button is on your watch a moment later." }
  - { t: "Tap", d: "Tap it in the app or on the card. The phone sends the request." }
plans:
  - { name: "Free", price: "$0", items: ["3 actions", "Every method, headers and body", "Widget and cards"] }
  - { name: "Pro", price: "$2.99", per: "once", pro: true, items: ["Unlimited actions", "Backup and restore", "Supports development"] }
faq:
  - { q: "What can I use it for?", a: "Home Assistant, IFTTT and Zapier webhooks, Shelly relays, garage openers, Slack or Telegram bots, your own server. Anything with a URL." }
  - { q: "Does the request go through your server?", a: "No. Your phone sends it straight to your endpoint." }
  - { q: "Can I send JSON?", a: "Yes. Set a Content-Type header and put the JSON in the body." }
final: Automate it.
---
