# Fairy Ring

A small browser game. Lead Pip's trail of fairies in loops around iron Nailbugs and Rust Hounds, chain rings for streaks, and last until dawn.

**Play it:** https://phoenix-valentine.github.io/fairy-ring/

## How to play

- **Fly:** arrow keys or WASD (on a phone, drag)
- **Dash:** Space (on a phone, the Dash button)
- **Pause:** Esc or P · **Mute:** M · **Restart:** R

Catch glowing lost fairies to grow your trail. Fly back across your own trail to close a fairy ring: every bug inside pops, and big rings score far more (bugs popped, squared). Chain rings quickly for a streak multiplier, and a ring of 6 bugs heals a heart. A bug touching your trail snaps it, but the fairies that flee can be caught again.

The night lasts 3 minutes. Try a Gentle night from the title screen for a relaxed game.

## Tweaking

The whole game is one file, `index.html`. All the tunable numbers (speeds, ring size, spawn rates, night length) are in the `SETTINGS` block at the top of the script, each with a plain-English comment.

Made with HTML, JavaScript and canvas, no libraries. Sounds are generated in code.
