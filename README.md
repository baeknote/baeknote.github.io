# Tundra Pacman

A self-contained HTML arcade game set in an icy tundra. Collect vodka bottles, use frost shots to counter ghosts, and clear every stage.

## Play

Open [index.html](index.html) in a modern browser.

## Controls

- Desktop: Arrow keys or `W`, `A`, `S`, `D`
- Mobile: Use the circular on-screen direction pad
- `R`: End the current run and show the game-over screen

## Game behavior

- Each new run creates a varied ice maze with protected, overlapping escape loops.
- A reachability check prevents vodka bottles from appearing in isolated areas.
- Ice floes are only placed when they preserve a fully connected floor network.
- Ghosts move on alternate beats, giving Pacman time to take a different route.
- Every vodka bottle is worth 10 points.
- Frost shots are worth 50 points and turn ghosts blue for a short time. Touching a blue ghost sends it home and earns escalating bonus points.
- Clearing every bottle and frost shot automatically starts the next randomized stage while keeping the score.
- Touching a ghost outside a frost-shot window ends the game.
