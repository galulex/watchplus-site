---
name: Authenticator
order: 4
cat: tools
kind: app
accent: "#f5a524"
accent2: "#ff5a36"
tagline: 2FA codes on your wrist, fully offline
title: 2FA codes, <em>no phone.</em>
pitch: Your two-factor codes on the watch, fresh every 30 seconds. It works fully offline. The watch makes the codes from its own clock.
zepp: 126613
pro: Pro $2.99 once
shots: 3
chips: ["🔐 New code every <span>30 s</span>", "✈️ Works offline"]
facts:
  - { v: "Offline", k: "No phone and no internet to read a code" }
  - { v: "6 sources", k: "Import from Google Authenticator, Aegis, 2FAS and more" }
  - { v: "6 free", k: "accounts; Pro removes the limit" }
features_title: Log in without reaching for the phone.
features:
  - { i: "⏱️", t: "Codes every 30 s", d: "Standard TOTP: the same codes your phone app shows, with a countdown.", w: 3 }
  - { i: "📥", t: "Bring your accounts", d: "Import a Google Authenticator export QR, QR screenshots, Aegis, 2FAS, andOTP or Raivo.", w: 3 }
  - { i: "🧩", t: "Widget and shortcut", d: "Your codes one swipe from the watch face." }
  - { i: "🔎", t: "Search and order", d: "Find an account fast, put the important ones first, swipe to delete." }
  - { i: "💾", t: "Export (Pro)", d: "Back up your accounts as andOTP JSON, ready to import anywhere." }
steps:
  - { t: "Install", d: "Install Authenticator from the Zepp app." }
  - { t: "Add accounts", d: "In the app’s settings on your phone, scan or import your accounts. They sync to the watch." }
  - { t: "Read the code", d: "Open the app or swipe to the card, and type the code you see." }
plans:
  - { name: "Free", price: "$0", items: ["Up to 6 accounts", "Every import source", "Widget and shortcut"] }
  - { name: "Pro", price: "$2.99", per: "once", pro: true, items: ["Unlimited accounts", "Export and backup", "Supports development"] }
faq:
  - { q: "Does it need my phone to show a code?", a: "No. The codes are made on the watch from its clock, so it works in airplane mode." }
  - { q: "Where are my secrets kept?", a: "On your watch and in the app’s settings in the Zepp app on your phone. We don’t run a server for them." }
  - { q: "A code is rejected. Why?", a: "TOTP depends on the time. Make sure the watch has synced its time with your phone." }
  - { q: "Can I move my accounts later?", a: "Yes. Pro exports them as andOTP JSON, which most authenticator apps can import." }
final: Log in faster.
---
