# AI Cost Hub

Synthwave single-page hub for **AI cost & the right model for the job**.

- Everyday model price board (Anthropic / OpenAI / Google / xAI)
- Task cost calculator (same tokens, different lanes)
- Meeting thesis: **Sonnet by default, Opus for the thinking**

## Live

GitHub Pages: https://americos.github.io/ai-cost-hub/

## Notes

Prices are a dated snapshot from public vendor docs. Re-check before purchasing.

## Price freshness

`prices.json` holds the model rates and an `asOf` timestamp shown on the page.

- Refreshing the browser only reloads that file — it does **not** scrape vendors live.
- A daily Grok Bot routine re-checks Anthropic / OpenAI / Google / xAI docs and pushes an updated `prices.json` when rates change (and always refreshes the stamp).
