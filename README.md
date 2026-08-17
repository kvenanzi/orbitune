# Orbitune

An orbital music box in a single HTML file. Planets orbit a sun; each time one
crosses the top of its orbit, it plays a note. Orbit radius sets pitch (closer
= higher), so the whole system becomes a generative, endlessly looping melody
you compose by placing planets in space.

Built in one shot from a single open-ended Claude prompt, with free rein on
concept and implementation — no framework, no build step, just Canvas 2D and
the Web Audio API.

## Run it

Open `index.html` in a browser. No install, no server required.

## Controls

- **Click** open space — place a planet (closer to the sun = higher pitch)
- **Double-click** a planet — remove it
- **Tempo** — speeds up or slows down every orbit
- **Scale** — pentatonic, minor pentatonic, major, or whole tone
- **Surprise Me** — replaces the current layout with a random cluster
- **Clear** — removes all planets
- **Sound On/Off** — mute toggle
