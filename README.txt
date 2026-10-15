MedTrack - how to run
=====================
Easiest (no install, works offline + installable): Netlify Drop
1. Open https://app.netlify.com/drop  (free account)
2. Drag this whole "medtrack" folder onto the page.
3. You get an https link. Open it in Chrome/Edge, then click the install icon in the address bar.
4. On the phone: open the same link in Chrome > menu > "Add to Home screen".

Local only (needs Python): open a terminal in this folder and run
   python -m http.server 8000
then open http://localhost:8000
(Do NOT double-click index.html: offline mode needs a server.)
