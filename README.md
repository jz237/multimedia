# Jez237 Multimedia

Videos from the lab: game captures, AI films and renders. The full-resolution masters live here and are served through GitHub Pages. You can watch them in the **[jez237.com screening room](https://jez237.com/multimedia/)**.

| Reel | Video | Details | Watch |
|---|---|---|---|
| 01 | **Port Richmond — Witte Street** | 3:35 · 1080p30 · 2026-10-08 | [screening room](https://jez237.com/multimedia/port-richmond-title-loop/) · [MP4](https://jz237.github.io/multimedia/port-richmond-title-loop/port-richmond-title-loop-b8-1080p.mp4) |
| 02 | **Port Richmond — Aramingo Avenue** | 3:34 · 1080p30 · 2026-10-08 | [screening room](https://jez237.com/multimedia/port-richmond-aramingo-walk/) · [MP4](https://jz237.github.io/multimedia/port-richmond-aramingo-walk/port-richmond-aramingo-walk-b8-1080p.mp4) |
| 03 | **Port Richmond — Castor Terminal** | 3:27 · 1080p30 · 2026-10-08 | [screening room](https://jez237.com/multimedia/port-richmond-castor-terminal-walk/) · [MP4](https://jz237.github.io/multimedia/port-richmond-castor-terminal-walk/port-richmond-castor-terminal-walk-b8-1080p.mp4) |
| 04 | **Port Richmond — Under the El** | 3:10 · 1080p30 · 2026-10-08 | [screening room](https://jez237.com/multimedia/port-richmond-el-kensington-walk/) · [MP4](https://jz237.github.io/multimedia/port-richmond-el-kensington-walk/port-richmond-el-kensington-walk-b8-1080p.mp4) |
| 05 | **Port Richmond — Frankford & the Rec Centre** | 4:00 · 1080p30 · 2026-10-08 | [screening room](https://jez237.com/multimedia/port-richmond-frankford-rec-walk/) · [MP4](https://jz237.github.io/multimedia/port-richmond-frankford-rec-walk/port-richmond-frankford-rec-walk-b8-1080p.mp4) |
| 06 | **Port Richmond — Joyce & the Rowhomes** | 3:53 · 1080p30 · 2026-10-08 | [screening room](https://jez237.com/multimedia/port-richmond-rowhomes-joyce-walk/) · [MP4](https://jz237.github.io/multimedia/port-richmond-rowhomes-joyce-walk/port-richmond-rowhomes-joyce-walk-b8-1080p.mp4) |
| 07 | **Port Richmond — Weikel & Tulip** | 3:37 · 1080p30 · 2026-10-08 | [screening room](https://jez237.com/multimedia/port-richmond-weikel-tulip-walk/) · [MP4](https://jz237.github.io/multimedia/port-richmond-weikel-tulip-walk/port-richmond-weikel-tulip-walk-b8-1080p.mp4) |

## Adding a video

1. Make a folder named `<slug>/` holding `<slug>-1080p.mp4` (H.264 + AAC, `+faststart`, **under 100 MB**, which is GitHub's per-file limit), `poster.jpg` (16:9), `thumb.webp` (960Ã—540) and `og.jpg` (1200Ã—630).
2. Add an entry to `catalog.json` and a row to the table above.
3. On jez237.com, add a reel card to `multimedia/index.html` and a watch page at `multimedia/<slug>/`. Keep a lite copy under 25 MiB there if you want link previews to play inline, because that is Cloudflare Pages' per-file limit.

Direct file links take the form `https://jz237.github.io/multimedia/<slug>/<slug>-1080p.mp4`.
