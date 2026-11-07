# kuno2011.github.io

Public pages for Kuno's games, served at https://kuno2011.github.io/.

- `immortal-chase/`: the game's page and its latest Android build (`immortal-chase.apk`, `version.json`).
- `immortal-chase/join/#CODE`: a room invitation. It opens the game straight in the room (Android App Links:
  `.well-known/assetlinks.json` holds the game's signing key; otherwise the `intent://` link on the page), or
  sends whoever does not have the game to its page.
- `.nojekyll` keeps GitHub Pages from dropping `.well-known/`.

The game's code is private (kuno2011/immortal-chase); only these pages and the built APK are here.
