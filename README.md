# Kikizake Cup 利き酒

A sake tasting game: pick a bottle from your cellar, taste it, guess its profile, then compare your guess with the bottle's.

- **Taste**: pick a bottle, guess, then see how close you were.
- **Cellar**: your bottles, with status (opened, finished) and where they're kept (fridge or shelf).
- **Log**: your past tastings.

Bottle profiles come from the retailer's tasting card or notes, your own Notion label, or Claude's estimate (marked unverified).

## Run it

It's a single HTML file built as a **Claude.ai artifact**: it saves your cellar and tastings with the artifact's built-in storage, so it only works inside Claude.ai, not as a plain web page.

1. In Claude.ai, ask Claude to publish `kikizake-cup.html` as an artifact for you.
2. Optional: to pull bottles from Notion, connect the Notion connector and set `NOTION_DS` at the top of the file to your sake database (`collection://<data source id>`).

## License

MIT. See `LICENSE`.
