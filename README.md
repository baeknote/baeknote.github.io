# Tundra Pacman

A self-contained HTML arcade game set in an icy tundra. Collect vodka bottles, avoid the ghosts, and clear every reachable pickup.

## Play

Open [outputs/tundra-pacman.html](outputs/tundra-pacman.html) in a modern browser.

## Controls

- Desktop: Arrow keys or `W`, `A`, `S`, `D`
- Mobile: Use the circular on-screen direction pad
- `R`: End the current run and show the game-over screen

## Game behavior

- Each new run creates a varied ice maze using a connected-path generator.
- A reachability check prevents vodka bottles from appearing in isolated areas.
- Every vodka bottle is worth 10 points.
- Touching a ghost ends the game.
