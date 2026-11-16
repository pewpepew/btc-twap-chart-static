# BTC/USD TWAP 60s — live chart

A live TradingView-style chart of Chainlink Data Streams' **BTC/USD TWAP 60s** feed, as a single static page.

**Bring your own credentials:** sign in with your own Chainlink Data Streams username and secret. They stay in your browser and are sent only to `api.dataengine.chain.link`; this site has no server. "Remember me" keeps them in this browser; otherwise they're cleared when the tab closes. **Log out** erases them.

- Live price polled about once a second; the last hour of history loads on open (+1h button for more, up to 6h)
- 1s to 1h candles, bars/line/area, SMA 20 / EMA 50, time zone picker
- Price is the 60-second time-weighted average reported by the Chainlink DON, not spot

Not affiliated with Chainlink. Charts by [TradingView Lightweight Charts](https://www.tradingview.com/lightweight-charts/).
