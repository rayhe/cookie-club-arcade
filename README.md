# Cookie Club Arcade 🍪🕹️

Four classic arcade games, rewritten from scratch for [Cookie Club](https://eaiz.net) — a kids' stories and games site — and released as open source so anyone can learn from them, remix them, or drop them into their own site.

## The games

| File | Game | The classic it reimagines |
| --- | --- | --- |
| `snake.html` | **Cookie Snake** 🐍 | Snake — steer a friendly garden snake, munch cookies, catch bonus stars, don't bump the fence or your tail |
| `breakout.html` | **Star Breaker** 🌟 | Breakout — bounce a star ball off your paddle and break every colorful block |
| `pong.html` | **Penguin Pong** 🐧 | Pong — a gentle paddle match against Pip the Penguin; first to 5 wins, difficulty ramps slowly |
| `star-defender.html` | **Star Defender** 🚀 | Space Invaders / fixed shooters — zap falling meteors before they land (no aliens, just rocks!) |

## Clean-room rewrites

These are **original implementations written from scratch** in 2026. No code, art, sound, names, or assets were copied from the original arcade games — only the timeless game *ideas* (guide a growing snake, bounce a ball at blocks, paddle versus paddle, shoot things falling from the sky), which are not copyrightable. All art is drawn at runtime with the HTML Canvas API; all characters (like Pip the Penguin) are new.

## Zero dependencies

Each game is a **single self-contained HTML file**: vanilla HTML, CSS, and JavaScript. No build step, no frameworks, no external assets, no tracking. The only network requests are to Google Fonts (and the games still work fine without them).

Just open a file in a browser, or serve the folder with any static host:

```bash
python3 -m http.server
# then visit http://localhost:8000/snake.html
```

## Kid-friendly by design

- Written for ages 5–12: simple words, big friendly buttons, encouraging messages
- Keyboard **and** touch controls on every game
- Pause any time (and auto-pause when the tab hides)
- No ads, no accounts, no chat, no data collection — best scores live only in the player's own `localStorage`
- Gentle difficulty: opponents and speed ramps are deliberately forgiving

## Differences from the live Cookie Club versions

The copies here are identical to the games live at [eaiz.net](https://eaiz.net/games.html) except the header shows a 🍪 emoji instead of the Cookie Club logo image, so each file works completely standalone.

## License

MIT — see [LICENSE](LICENSE). Play them, learn from them, ship your own versions. A link back to Cookie Club is appreciated but not required.
