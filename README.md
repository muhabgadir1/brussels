# Brussels Bedroom Planner

Live site: https://muhabgadir1.github.io/brussels/ (once GitHub Pages is switched on, see below)

A phone-friendly, to-scale floor plan of the 270 × 370 cm bedroom for trying out furniture layouts.

Open `index.html` in any browser (no build step, no install).

- Add furniture from the catalogue, or enter the size of something you're thinking of buying.
- Tap anything to select it: furniture, the door, a window, a radiator, or a wall (the room itself).
- Drag to move it. Door, windows and radiators slide along their wall; drag one near another wall to move it there.
- Drag the blue dots to resize, or type exact sizes in the panel (width, depth, height, position from the corner, sill height).
- Door panel: flip the hinge side or make it open outward. Room panel: resize the room, add windows or radiators.
- Red = doesn't physically fit (overlaps, sticks out of the room, blocks the door). Amber = fits, but a door, drawers, a window or a desk chair won't have room.
- Blue numbers show the gap in cm to the nearest wall or piece of furniture.
- **Save** names the room you're working on; changes also save automatically. **My rooms** lists every saved room; tap one for its details (size, door, windows, radiators, each piece of furniture with its size and position, what doesn't fit), then open, share, copy the details as text, duplicate or delete it.
- **My rooms → New room** starts an empty room of any size.
- Rooms are stored in each person's own browser. **Share link** gives a link that opens a room on any device; the other person's edits don't change yours.

Measurements from the sketch: room 270 × 370 cm, radiator 140 cm on the bottom wall with 130 cm to the door corner, bed 140 × 200.
The window and door positions are estimated from the video and can be moved and resized directly on the plan.

## Publishing

The site is plain static files, served by GitHub Pages: Settings → Pages → Build and deployment → Source: *Deploy from a branch*, branch `claude/room-layout-design-tool-2s5b5g`, folder `/ (root)`. Every push to that branch updates the site.
