# Defiance Index Pipeline — monitoring site

Static dashboard tracking candidate indices/ETFs for Defiance to launch with its
exchange partners (Binance, OKX, Bybit, Bitget). Scored, weighted, with live
trailing returns and an on-the-fly basket builder.

- `index.html` — the full self-contained dashboard (mirror of the Claude artifact).
- Deployed to Vercel (project **index-pipeline**) → https://defiance-index-pipeline.vercel.app
- Refreshed weekly by an automated scan; every push to `main` auto-deploys.
