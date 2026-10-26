# Tacos El Tío

A 3D taco-shop game with a pepper mascot, mariachi-style music, aguas frescas,
coin rewards, speed upgrades, three unlockable prep plates, and a kitchen helper.

## Play

Open the GitHub Pages URL shown in this repository's Deployments section.
The entire game is bundled in `index.html`; it also opens locally without a server.

- Prepare for 60 seconds before opening, or choose ¡Abrir! when ready.
- Stock pastor, asada, chorizo, onion, cilantro, and warm tortillas in Reservas.
- Taco cards name the meat and toppings; SOLO CARNE means no onion, cilantro, or salsa.
- Desktop: WASD/arrows to move, E/Space to interact, Q to change plates, P to pause.
- Phone: rotate to landscape, drag on the left to move, tap Acción to interact.
  Use the numbered buttons to change plates. Pantalla enables fullscreen when supported.
- Sales earn coins. Open Mejoras to buy speed, prep plates, and a permanent helper (45 coins).
- Upgrades save in the current browser. Moving from a local file to the website
  starts a separate browser save.

## Publish updates

The Pages workflow deploys `index.html` on pushes to `main`.
In Settings → Pages, choose GitHub Actions as the build source.
Only runtime files are included in the public website artifact.

The mascot was supplied by the game owner. Three.js is MIT licensed;
its notice is in `THIRD_PARTY_LICENSES.txt` and the HTML. The original
mariachi-style audio is synthesized for the game.
