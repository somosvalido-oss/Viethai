# Andaman to Hanoi 2027

Offline trip companion for Thailand → Vietnam → Thailand, 29 Jan – 20 Feb 2027.

`index.html` is the whole app (inline CSS + JS, data in localStorage). The other files only make it installable and offline as a PWA:
`manifest.webmanifest`, `sw.js` (offline cache) and the icons. Host the folder on any HTTPS static host (e.g. GitHub Pages), open it once online, then add it to the home screen.

Sync between phones: Settings (top-right) → **Share file** → send it to the WhatsApp group → others open Settings → **Choose file** → **Merge**.
