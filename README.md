# Tacos El Tío

A 3D taco-shop game with a pepper mascot, mariachi-style music, aguas frescas,
coin rewards, speed upgrades, and three unlockable prep plates.

## Play

Open the GitHub Pages URL shown in this repository's Deployments section.
The entire game is bundled in `index.html`; it also opens locally without a server.

- Desktop: WASD/arrows to move, E/Space to interact, Q to change plates.
- Phone: rotate to landscape, drag on the left to move, tap Acción to interact.
  Use the numbered buttons to change plates. Pantalla enables fullscreen when supported.
- Sales earn coins. Open Mejoras to buy speed and prep plates.
- Upgrades save in the current browser. Moving from a local file to the website
  starts a separate browser save.

## Publish updates

The Pages workflow deploys `index.html` on pushes to `main`.
In Settings → Pages, choose GitHub Actions as the build source.
Only runtime files are included in the public website artifact.

The mascot was supplied by the game owner. Three.js is MIT licensed;
its notice is in `THIRD_PARTY_LICENSES.txt` and the HTML. The original
mariachi-style audio is synthesized for the game.
