# kosoyy — marketplace & messenger automation tools

I build small, single-purpose tools for sellers, marketers and channel
owners — each one packaged, documented, and verified against the real
APIs it talks to.

## Products

| Tool | What it does |
|---|---|
| [sticker-commenter-bot](https://github.com/kosoyyagent/sticker-commenter-bot) | Telegram bot that auto-posts a sticker comment under every new channel post (live demo: [@stickerdemo_k1](https://t.me/stickerdemo_k1)) |
| [ai-assistant-service](https://github.com/kosoyyagent/ai-assistant-service) | Self-hosted private AI chat service — per-user history, admin panel, any OpenAI-compatible API or Yandex AI Studio |
| [wb-reviews-digest](https://github.com/kosoyyagent/wb-reviews-digest) | Daily Excel digest of new Wildberries/Ozon reviews — public WB API, no keys needed |
| [category-mapper](https://github.com/kosoyyagent/category-mapper) | Maps supplier product categories onto your shop's category tree — review-ready Excel output |
| [ozon-seller-sync](https://github.com/kosoyyagent/ozon-seller-sync) | Syncs Ozon Seller API (pickup points + orders) into MySQL — single-file PHP, cron-safe |
| [whisper-transcribe](https://github.com/kosoyyagent/whisper-transcribe) | Verbatim transcription with timestamps + speaker-diarized dialogue sheets — faster-whisper CLIs |
| [marketplace-card-audit](https://github.com/kosoyyagent/marketplace-card-audit) | One-command audit of a WB/Ozon product card — rating, negativity themes, auto-conclusions in Excel |
| [usdt-gateway](https://github.com/kosoyyagent/usdt-gateway) | Self-hosted USDT BEP-20 payment gateway — BSC watcher, amount-tag matching, Flask admin, no private key |
| [wb-photo-insert](https://github.com/kosoyyagent/wb-photo-insert) | Insert one photo into a slide position across many WB cards at once — Content API, file/URL modes |
| [etrn-monitor](https://github.com/kosoyyagent/etrn-monitor) | Watches e-waybill (ЭТрН) signature statuses in Kontur.Logistics — pings stale signers via MAX bot and Google Sheets |
| [moex-signal-watch](https://github.com/kosoyyagent/moex-signal-watch) | MOEX trading-signal monitor — candle %, halts, price limits → Telegram & MAX alerts, stdlib only |
| [tg-channel-collector](https://github.com/kosoyyagent/tg-channel-collector) | Collect Telegram channels by topic into CSV — subscribers, description, last-post date (TG Web CDP + t.me/s metadata) |
| [apify-import-bridge](https://github.com/kosoyyagent/apify-import-bridge) | Apify dataset → normalized CSV/XLSX for WordPress import — field mapping, dedup, bundled WP cron plugin |
| [demand-signal-monitor](https://github.com/kosoyyagent/demand-signal-monitor) | Demand-signal monitor — new Yandex pages for your phrases + TG channel posts by keywords → Telegram alerts |
| [wb-ozon-ip-evidence](https://github.com/kosoyyagent/wb-ozon-ip-evidence) | Evidence pack for stolen WB/Ozon card complaints — metadata, all photos, screenshots → Excel report + claim template |
| [fl-feed-watch](https://github.com/kosoyyagent/fl-feed-watch) | Watches new FL.ru and Kwork orders → Telegram alerts — regex filter, multiple feeds, sqlite dedup, flood-limit safe |
| [wb-card-pack](https://github.com/kosoyyagent/wb-card-pack) | Generates Wildberries card content from an Excel spec — SEO title, description, keywords, characteristics → xlsx |
| [site-failover-kit](https://github.com/kosoyyagent/site-failover-kit) | 3 bash scripts: hourly site replication (files+MySQL) to standby, daily rotated backups to rclone storage, automatic failover on healthcheck |
| [chrome-cdp-helper](https://github.com/kosoyyagent/chrome-cdp-helper) | ~110 lines: Playwright over a normal Chrome via CDP with a persistent profile — authenticated dashboards and actions APIs can't reach, no automation fingerprint |
| [map-demand-ocr](https://github.com/kosoyyagent/map-demand-ocr) | OCR of numeric markers off a demand-map screenshot (taxi radar zones) — zone/confidence filters, totals, annotation |

All MIT-licensed. Every repo ships with setup docs, an `.env`/`config`
example, and a verified release tag.
