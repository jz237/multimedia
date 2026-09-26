# Jez237 Multimedia

Videos from the lab: game captures, AI films and renders. The full-resolution masters live here and are served through GitHub Pages. You can watch them in the **[jez237.com screening room](https://jez237.com/multimedia/)**.

| Reel | Video | Details | Watch |
|---|---|---|---|
| 01 | **Port Richmond — Title Screen Loop**<br>One slow lap around a real Port Richmond block in the UE5 zombie game, with game audio. | 3:33 · 1080p30 · 2026-09-26 | [screening room](https://jez237.com/multimedia/port-richmond-title-loop/) · [MP4](https://jz237.github.io/multimedia/port-richmond-title-loop/port-richmond-title-loop-1080p.mp4) |

## Adding a video

1. Make a folder named `<slug>/` holding `<slug>-1080p.mp4` (H.264 + AAC, `+faststart`, **under 100 MB**, which is GitHub's per-file limit), `poster.jpg` (16:9), `thumb.webp` (960×540) and `og.jpg` (1200×630).
2. Add an entry to `catalog.json` and a row to the table above.
3. On jez237.com, add a reel card to `multimedia/index.html` and a watch page at `multimedia/<slug>/`. Keep a lite copy under 25 MiB there if you want link previews to play inline, because that is Cloudflare Pages' per-file limit.

Direct file links take the form `https://jz237.github.io/multimedia/<slug>/<slug>-1080p.mp4`.
