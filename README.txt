CANDY POP ADVENTURE — EPIC EDITION

This is an original, lightweight Match-3 browser game prototype for phones and desktop. It is inspired by the general match-3 puzzle genre and does not include original Candy Crush assets.

RUN LOCALLY IN TERMUX
1. Extract this ZIP.
2. Open Termux and enter the extracted folder (the folder containing index.html).
3. Run: python -m http.server 8000
4. Open http://127.0.0.1:8000 in your browser.
5. Keep Termux running while testing. Stop the server with CTRL+C.

PUBLISH
Upload index.html, sw.js, manifest.webmanifest, icon.svg and this README.txt to a NEW GitHub repository. For Cloudflare Pages, connect that repository, set the root directory to /, leave the build command empty, and deploy the static files. HTTPS hosting is required for service-worker/offline support.

FEATURES INCLUDED
- 8x8 match-3 board, candy swapping, matches and falling refill
- 30-level progression concept, score, moves, target and lives
- hint, shuffle, power move and sound toggle
- map and informational Goals/Friends/Collection/Shop panels
- local device progress storage and service worker caching

LIMITATIONS
- This is a self-contained prototype, not an exact recreation of any commercial game. Friends/multiplayer and real-money shop purchases are not implemented. Some panels are informational. Test gameplay on your device before publishing; this package has not been validated across all browsers.
