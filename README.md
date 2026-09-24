# RookiOS72.github.io

Personal landing page for [RookiOS72](https://github.com/RookiOS72) — a shelf of media (an Atari arcade board, an Apple II floppy), one per game, each carrying its own artwork. Click one and it drops into the matching slot on the deck, whose screen plays the game in its original machine's look.

## Projects

- **[Asteroids](https://rookios72.github.io/asteroids/)** — the 1979 arcade classic in your browser. Vector graphics, WebAudio sound, replay-the-same-field-when-you-die, opt-in size-aware asteroid collisions.
- **[Lode Runner](https://rookios72.github.io/loderunner/)** — the 1983 classic in your browser. All 150 original levels, trap-and-recapture digging, gold-carrying guards, a level editor, and saved progress.

## Adding a new project

Add a medium to the `.shelf` in `index.html` (a `.m` button with a `data-id`), an entry in the `G` table in the script, and a preview in the deck's screen. Each game is shown on the medium it shipped on.

## Deployment

Auto-deployed via GitHub Pages from the `main` branch. Push to `main` and the site updates within ~30 seconds.
