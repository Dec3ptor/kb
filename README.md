# kb — browser intros

[Demoscene](https://en.wikipedia.org/wiki/Demoscene)-style intros. Each is a single HTML file with no assets and no libraries:
graphics and music are computed in the browser when you press play.

| Intro | File | Size | What it is |
|---|---|---|---|
| Matrix 256 | `matrix.html` | 256 B | Katakana digital rain |
| Matrix 512 | `matrix512.html` | 512 B | Denser rain with bright heads; click for a bytebeat soundtrack |
| kb 4k | `index.html` | 3.8 KB | Four shader scenes, sine scroller, synthesised music |
| Meridian | `meridian/index.html` | 27 KB (64k class) | Six cinematic scenes with HDR bloom and a two-minute soundtrack |

Controls: click to start. In `index.html` a second click goes fullscreen; in Meridian press `f` or double-click.
`#30` on the URL starts 30 s in. Meridian renders at 720 lines by default; `?q=1080` raises it, `?q=480` helps slow GPUs.

To publish: Settings → Pages → deploy from branch, root folder.
