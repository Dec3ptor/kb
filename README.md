# kb — browser intros

[Demoscene](https://en.wikipedia.org/wiki/Demoscene)-style intros. Each is a single HTML file with no assets and no libraries:
graphics and music are computed in the browser when you press play.

| Intro | File | Size | What it is |
|---|---|---|---|
| Meridian | `meridian/index.html` | 27 KB (64k class) | Six cinematic scenes with HDR bloom and a two-minute soundtrack |
| Matrix 4k | `matrix4k.html` | 3.3 KB | 3D glyph rain, tunnel and corridor, with music |
| Neon 4k | `neon.html` | 3.0 KB | Sunset grid, mountains, synthwave loop |
| kb 4k | `4k.html` | 3.8 KB | Four shader scenes, sine scroller, synthesised music |
| Oldschool 1k | `oldschool.html` | 987 B | Plasma, copper bars, sine scroller, bytebeat |
| Matrix 512 | `matrix512.html` | 512 B | Dense rain with bright heads; click for bytebeat |
| Matrix 256 | `matrix.html` | 256 B | Katakana digital rain |

`index.html` is a browser for all of them: pick one in the list and it plays in the page.

Controls: click to start. In the 4k intros a second click goes fullscreen; in Meridian press `f` or double-click.
`#30` on the URL of a 4k intro or Meridian starts 30 s in. Meridian renders at up to 720 lines and lowers its
resolution by itself if the frame rate drops; `?q=1080` raises the cap, `?q=480` lowers it.

To publish: Settings → Pages → deploy from branch, root folder.
