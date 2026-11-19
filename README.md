# THE DEAD SHIFT

Single-file first-person stalker horror (no build step, no dependencies for solo play).
Open `index.html` in a browser, or upload it to any static host (GitHub Pages, Netlify, itch.io HTML upload).

## Play
Find 4 fuses, restore the power, then escape through the loading door before the Foreman catches you.
WASD move, SHIFT sprint, C crouch (quiet), MOUSE/arrows look, E use/take/hide/open, F flashlight,
R spare battery, G throw a bottle (he investigates the noise), ESC releases the mouse.

## Co-op (up to 4)
Host co-op shows a 5-letter code; friends choose Join co-op and type it. Peer-to-peer through WebRTC with the free
public PeerJS broker (the library loads from jsDelivr only when you use co-op), so you need no accounts or server.
The host's browser runs the Foreman; keep that tab visible. Everyone shares the same seeded building, fuses, doors and items.
Caught players spectate. The run ends when everyone is caught or out.
Add `?net=local` to the URL to test co-op between two tabs of the same browser without any network.
