---
layout: default
title: ZNM — Privacy Policy
description: ZNM collects nothing and sends nothing to us. Everything happens on your phone; it goes online only to fetch link previews.
permalink: /znm/privacy.html
---
<div class="legal" markdown="1">
# ZNM — Privacy Policy

_Last updated: 13 October 2026_

ZNM ("the app") is a notification helper for Amazfit / Zepp OS watches. This policy
explains what the app does and does not do with your data.

## The short version

ZNM collects nothing and sends nothing to us. There are no servers of ours, no accounts, no
analytics and no ads. Everything happens on your phone. The app goes online for one thing only:
fetching link previews straight from the linked site (see below), which you can switch off.

## What the app accesses

ZNM uses Android's **Notification access**. While that access is granted, Android lets the app
see your notifications and when they are removed. ZNM uses it to:

- **Mark as read:** notice that your watch removed a notification and trigger that
  notification's own "mark as read" action.
- **Deliver via ZNM** (only for apps you switch to it): read the notification's title, recent
  messages, sender names and image, and post ZNM's own copy of it on your phone. The Zepp app
  forwards that copy to your watch, exactly as it forwards any other notification. When the
  original notification goes away, ZNM removes its copy.
- **Replies:** a reply you send from the watch on a ZNM copy is handed to the original app's
  own reply action, as if you had replied from the phone's notification.
- **ZNM Notify+ watch app** (only if you switch it on): ZNM hands the same notification
  content to the Notify+ app on your watch, through the Zepp app on your phone and its
  Bluetooth link to the watch. ZNM listens for it on your phone only (127.0.0.1, not reachable
  from the network). Your replies and button presses come back the same way. Notify+ keeps
  recent notifications on the watch, and you can clear them there at any time.

ZNM never uploads notification content anywhere. For apps not switched to Deliver via ZNM, it
does not read message text at all.

## Link previews

When a message ZNM shows on your watch contains a link, ZNM can fetch that link's preview
picture so the watch can show it, the way messengers do. Your phone requests the page or image
directly from the site the link points to; nothing passes through us. As with opening any
link, that site sees an ordinary request from your phone's internet connection. Links to your
own local network are never fetched. You can turn this off at any time in
**Settings → Link previews**.

## What the app stores

On your device only, in the app's private storage, ZNM keeps:

- your settings: which apps are switched off, which use Deliver via ZNM, and whether link
  previews are on,
- a short rolling on-screen activity log (app name, event type and time — never message
  text), capped at the most recent entries,
- a diagnostic log of the notifications ZNM handles (app, title and text, and what ZNM did with
  them), capped at 512 KB with the oldest lines dropped. It never leaves your phone unless you
  tap **Share log** and pick where to send it, for example to us when you report a problem,
- while a ZNM copy is showing, a scaled-down copy of its picture, deleted as soon as the copy
  is removed or replaced.

The text of a ZNM copy lives in that notification only, like any other notification on your
phone, and disappears with it. None of this data leaves your phone, it is excluded from
backups, and it is deleted when you uninstall the app or clear its data.

## Purchases

ZNM Pro is bought through Google Play. Google handles the payment; ZNM only asks Google Play
whether you own Pro. We never see your payment details.

## What the app shares

Nothing with us or any third party. There are no analytics, no advertising, no third-party
SDKs, and no servers of ours. The only network requests are the link-preview fetches described
above, made directly to the linked site.

## Children

ZNM is a utility with no content directed at children and collects no personal data.

## Contact

Questions about this policy or the app: **watch@ab.team**

</div>
