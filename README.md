# baddatatude.github.io
Cooper Harris’s portfolio of AI systems, games, sports analytics, and chess projects.

## Chess

[Check Yourself](projects/check-yourself/) analyzes completed chess games locally with Stockfish. Explore interactive game reviews and practice positions from synthetic single-game and batch reports.

## Website checkpoint — 2026-11-24

GitHub Pages publishes the repository root from `main`. The homepage features Argus, the Wrong Floor Godot prototype, and Check Yourself v0.2.0. The Argus page links to Eureka's build photos and parts list. Wrong Floor has a project page and awaits a verified browser export.

Check Yourself's project page is at `/projects/check-yourself/`. Its standalone `single.html` and `multi.html` reports use synthetic games and are preserved from website commit `13d9c0b`. Keep their screenshots and `licenses/` notices with the reports. The package is maintained separately at [baddatatude/check-yourself](https://github.com/baddatatude/check-yourself).

For a local preview, run `python3 -m http.server 8765 --bind 127.0.0.1` from the repository root and open `http://127.0.0.1:8765/`. GitHub Pages renders the Markdown licensing index on deployment.
