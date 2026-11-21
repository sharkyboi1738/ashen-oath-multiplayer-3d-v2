# Ashen Oath — Knight Combat Edition

This is a two-player browser Soulslike prototype with **original armored knight characters** and dedicated authored sword-combat animations. It does not include third-party model files or professional motion-capture animations; characters are built from Three.js geometry and articulated by code. No model license or external asset download is required.

## Run locally

Node.js 18+ required. Run `npm install` then `npm start`. Open http://localhost:3000 (or the port reported by the server). Create a room and share its URL. For internet play deploy the repository as a Render **Web Service** with build `npm install` and start `npm start`.

## Controls

WASD move; mouse look; left click slash; right click heavy attack; Space dodge; F heal; Q lock; 1–3 weapons; 4–6 armor.

## Changes

Replaced the robot placeholder with original armored knights. Added dedicated timed slash, overhead heavy attack, dodge-roll, healing, and walking animations. Knight helmets, breastplates, and sword geometry have more detail. Existing co-op, three bosses, equipment and rooms remain.

## Limitations

This is not a professionally rigged or motion-captured character model. No live multiplayer test has been completed; the project needs browser testing after deployment. The game client loads Three.js modules from a CDN and therefore needs internet access.
