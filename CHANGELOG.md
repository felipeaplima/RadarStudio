# Changelog

All notable changes to RadarStudio.

## 1.9 — 2026-10-13

- **Speed on video.** A new page burns each serve's speed into your match video — a short serves reel or the full game. The video must be on this PC; ffmpeg downloads itself on first use.
- **Share on the internet.** In the Hall overlay you can share the "Last serve" badge over the internet, so a remote OBS — or any screen with a connection — shows the live speed. One click, no router setup.

## 1.8 — 2026-10-12

- **Auto-detect clock offset.** In DV/VS Sync, tick **🔍 auto-detect** and it finds the offset by matching your serves to the readings — handy when the radar CSV comes from a phone on a slightly different clock.
- **Edit or drop any serve.** In the preview you can now type any speed, or **🗑** drop a serve (e.g. one marked out of time) so no speed is written for it.
- **Phone CSV syncs directly.** DV/VS Sync reads the RadarStudio Bridge CSV (date, time, km/h, mph) as a radar source, for when a phone was the capture.
- **Live clock difference.** When a phone is pushing speeds, DV/VS Sync shows the measured phone↔PC clock difference (📡) so you can apply it as the offset in one click.

## 1.7 — 2026-10-10

- **Display font size.** A size slider for the central display, right next to the layout picker.
- **Phone scoreboard — last speeds.** The 📱 Phone view can now show the last serve speeds (below or beside the number). Pick the layout — and whether it follows the panel's colors — in the 📱 Phone dialog.
- **"Receiving from phone" status.** The header shows when serve speeds are coming in over the network from a phone.

## 1.6 — 2026-10-09

- **New "Hall" overlay.** A "Last serve: XXX km/h" overlay card for OBS (📺 Hall button) that uses your chosen colors (Text/Bg), with the label in uppercase. Two styles — **horizontal** (single line) or **vertical** (big number) — in English, Portuguese and Italian. Pick the style and language in the pop-up and copy the URL.

## 1.5 — 2026-10-08

- **VolleyStation support.** The serve-speed page — now **DV/VS Sync** — also reads VolleyStation `.vsm` files, not just DataVolley `.dvw`. It matches each serve's speed by video time, auto-aligns to your radar (with a one-click "first-serve sync" to pin it when needed), and writes the speed into the CUSTOM field. *(New — still being improved.)*

## 1.4 — 2026-10-08

- **Display timer for serves.** New field in the Serve marker box: choose how many seconds a serve speed stays on the display, the OBS overlay and the phone scoreboard before going back to "…" (waiting for the next serve). Set it to 0 to keep the last serve on screen until the next one, as before.

## 1.3 — 2026-10-07

- **Serve mark over the network.** Press **S** on the scout PC and the radar PC captures that serve, so the OBS overlay shows **only serve speeds** instead of every reading. Turn on **"accept serve mark from network"** on the radar PC (Serve marker section). The serve is captured at the source for accuracy, with a short look-back so a slightly late signal still catches it. Your **S** still marks locally for your scout.

## 1.2 — 2026-10-07

- **New in-app guide** in English and Portuguese, with a side menu, screenshots and an overview. The old Help page is gone — everything lives in the guide now.
- **Clearer Bluetooth setup:** the first connection uses the radar's pairing mode (both buttons); after that it reconnects on its own.
- **"Check for updates"** in the About tab, alongside the automatic update notice.
- Display, scout and general stability improvements.
