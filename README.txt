BEANS STOCK — Install as a phone app
=======================================

Keep ALL of these files together, in the same folder layout:
  index.html, manifest.webmanifest, sw.js, icons/

1) Put the folder online (needs an https link). Easiest, no commands:
   - Go to https://app.netlify.com/drop  → drag this whole folder in → you get a link.
   - Or Firebase Hosting (same project: beans-live-windmill):
       npm i -g firebase-tools
       firebase login
       firebase init hosting   (public directory = this folder, single-page = No)
       firebase deploy          → https://beans-live-windmill.web.app

2) Send that LINK on WhatsApp (not the file).

3) On the phone, open the link:
   - Android (Chrome):  ⋮ menu → "Install app" / "Add to Home screen"
   - iPhone (Safari):   Share → "Add to Home Screen"

The Beans Stock "B" icon appears on the home screen and opens full screen like an app.
Stock data stays live from Firebase.
