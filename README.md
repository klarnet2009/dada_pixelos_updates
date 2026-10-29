# PixelOS (Android 17) for Xiaomi 15 (dada) — update feed

This repository serves the update feed for the built-in **Updater** app of the unofficial PixelOS 17 build for the
Xiaomi 15 (`dada`).

- `dada.json` — OTA feed in the PixelOS Updater schema (`packages/apps/Updater`, `tools/pixelos_feed.py`).
- Releases — incremental OTA packages between consecutive builds (full packages are linked from the release post).

Builds that read this feed set `updater_server_url` to
`https://raw.githubusercontent.com/klarnet2009/dada_pixelos_updates/main/{device}.json`.
