# Message in a Bottle

Static multi-page web experience. No build step — serve the folder.

**GitHub Pages:** push this folder's contents to the repo (root or `/docs`), then
Settings → Pages → Deploy from branch.

**Local:** `python3 -m http.server` in this folder, open http://localhost:8000

## Pages
| File | Screen |
| --- | --- |
| index.html | Captain's Map (entry point) |
| cuba.html | Cuba landfall |
| havana-dock.html | Havana Dock |
| cargo-hold.html | Cargo Hold puzzle |
| dream-state.html | Dream State |
| point-nemo.html | Point Nemo |

`support.js` is the shared runtime; `assets/` holds images, fonts and audio.
Requires an internet connection for map data, web fonts and d3.
