# Game Shelf

> A live collection of 20 small browser games on one page — pick a game, play it on your phone or computer, and your best scores are saved on your device.

**Tech:** HTML, CSS, JavaScript
**Tools:** GitHub, GitHub Pages
**AI Tools:** Claude


## About

A live web page that works as a shelf of small games — puzzles, arcade games, board games and word games. Open the main page, tap a game card, and play. Games work with touch (swipe and tap) and with the keyboard. Best scores are saved in your browser, so there is no sign-up and no server.

At its core it is a **static website**. Each game is one self-contained `index.html` file in its own folder, and the main page (`index.html`) lists them as cards. No framework, no build step, no backend to run.

## Games

| Game | Type | Folder |
|---|---|---|
| Tidepool Merge | Tile-merge puzzle (2048 style) | `tidepool-merge` |
| Reef Snake | Arcade | `reef-snake` |
| Shell Match | Memory cards | `shell-match` |
| Bubble Pop | 30-second reflex | `bubble-pop` |
| Tide Tac Toe | Vs computer, easy or hard | `tide-tac-toe` |
| Word Reef | 5-letter word guess | `word-reef` |
| Fin Flap | Tap-to-fly arcade | `fin-flap` |
| Urchin Sweep | Minesweeper | `urchin-sweep` |
| Drop Four | Connect four, CPU or 2 players | `drop-four` |
| Echo Pearls | Simon-style memory | `echo-pearls` |
| Drift Puzzle | Sliding tiles, 3×3 or 4×4 | `drift-puzzle` |
| Ocean Quiz | 10-question quiz | `ocean-quiz` |
| Crab Whack | Whack-a-mole | `crab-whack` |
| Sea Hangman | Word game | `sea-hangman` |
| Reef Sudoku | 9×9 puzzle, easy or medium | `reef-sudoku` |
| Dots and Boxes | 2 players | `dots-and-boxes` |
| Reef Maze | Growing mazes | `reef-maze` |
| Reef Solitaire | Klondike | `reef-solitaire` |
| Fleet Battle | Battleship, 2 players | `fleet-battle` |
| Tide Pong | Pong, CPU or 2 players | `tide-pong` |

## Project structure

```
index.html              main page (lists all games)
games/
  <game-folder>/
    index.html          one self-contained game
README.md
```

## Add a game

1. Create `games/<folder>/index.html` (HTML, CSS and JS in one file).
2. Add one line to the `GAMES` list in the main `index.html`.
3. Commit and push.

## Deploy on GitHub Pages

1. Upload the files to a GitHub repo, keeping the folder structure.
2. Open **Settings → Pages**.
3. Choose **Deploy from a branch**, then `main` and `/ (root)`, then save.
4. The site goes live at `https://<username>.github.io/<repo>/`.
