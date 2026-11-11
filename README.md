# kuno2011.github.io

Public pages for Kuno's games, served at https://kuno2011.github.io/.

- `immortal-chase/`: the game's page, which installs it as an app (a PWA: `manifest.webmanifest`, `sw.js`), and
  `play/`, the game itself (the web build, which updates itself every time it is opened).
- `immortal-chase/join/#CODE`: a room invitation. It opens the game straight in the room (Android App Links:
  `.well-known/assetlinks.json` holds the Android build's signing key), else its button opens the game in the room
  (`play/?join=CODE`).
- `immortal-wars/`: the same for Immortal Wars (its page installs it as an app; `play/` is the game).
- `.nojekyll` keeps GitHub Pages from dropping `.well-known/`.

The games' code is private (kuno2011/immortal-chase, kuno2011/immortal-wars); only these pages and the built games are here.
