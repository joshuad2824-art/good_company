# Good Company

Conversation cards for any table — family get-togethers, work events, and church gatherings.

170 prompts across five depth levels, plus wild cards and a seasonal Thanksgiving set. Cards are shuffled with the browser's secure random generator, so every session deals a new order, and no card repeats until the whole deck has been seen.

| Depth | Color | Mark |
| --- | --- | --- |
| Light | Ocean `#0b4a6b` | one dot |
| Story | Rust `#7a3118` | two dots |
| Deeper | Plum `#6b1c4a` | three dots |
| Group | Forest `#0e4a33` | ring |
| Wild | Ochre `#876808` | star |
| Gratitude (Thanksgiving) | Wine `#5a0b25` | leaf |

## Using it

- **iPhone and iPad:** swipe left for the next card, right to go back. Add it to the Home Screen from Safari's Share menu for a full-screen app with its own icon.
- **Computer:** use the Back / Next card buttons or the arrow keys.
- The house icon returns to the home screen, where you can jump back in or reshuffle.

## Deploying

It's a single static page with no build step. On Netlify, connect this repo and leave the build command empty; `netlify.toml` publishes the repo root.

## Files

- `index.html` — the whole app (cards, styles, and script)
- `manifest.webmanifest`, `apple-touch-icon.png`, `icons/` — home-screen icons and install metadata
- `netlify.toml` — Netlify publish settings
