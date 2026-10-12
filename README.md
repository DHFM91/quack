# QUACK

A retro first-person shooter in the spirit of DOOM and QUAKE, except every enemy is a duck and your only weapon is bread.

Feed each duck until it's satisfied and it flies away happy. Find the keycard, reach the EXIT door, and move on to the next randomly generated level.

## Play

Live at: https://dhfm91.github.io/quack/

## Controls

**Desktop:** WASD to move, mouse to look, click (or Space) to throw bread, Shift to run, Tab or M for the automap.

**Mobile:** left side of the screen is a move joystick, drag on the right side to look, THROW button to throw, MAP button for the automap.

## The ducks

- **Duckling**: fast, weak peck, one slice of bread fills it up.
- **Mallard**: the regular. Three slices.
- **Goose**: big, mean, hits hard. Seven slices.

Bread loaves and first aid kits are scattered around each level. Levels grow larger and more crowded as you go.

## Tech

One self-contained `index.html`: vanilla JavaScript, HTML5 Canvas raycaster, procedural textures, sprites and sound. No build step.
