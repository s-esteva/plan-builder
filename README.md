# VHIL plan builder

Build a plan for the Stanford VHIL mixed-reality tour on a phone or laptop: pick the beats, put them in order, name the
plan if you like, and show it as a QR code. The tour guide's headset reads the code with **Scan plan** on its
sequence panel.

**Open it:** https://s-esteva.github.io/plan-builder/

- Works offline once loaded, and makes no network requests. A plan can also travel as a link (the page keeps it in
  the URL), and **Share** on the code sends that link.
- This repository only serves the page. `index.html` and `beats.js` are copied here automatically from the lab's
  private repository whenever they change there, so edits made here are overwritten.
- The QR library is [qrcode-generator](https://github.com/kazuhikoarase/qrcode-generator) by Kazuhiko Arase (MIT),
  inlined in `index.html` with its licence header.
