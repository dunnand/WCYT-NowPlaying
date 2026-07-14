# WCYT-NowPlaying

Live now-playing data for [wcyt.org](https://wcyt.org), auto-committed every
song change by `bsi_watcher.py` running at the station.

| File | Contents |
|---|---|
| `Point_Display_OUT.htm` | Simian BSI output — The Point 91 FM (now playing, album/year, recently played) |
| `2_Display_OUT.htm` | Simian BSI output — 2.0 |
| `point_status.json` | Simian automation status — The Point (mode, log loaded, playing) |
| `wcyt2_status.json` | Simian automation status — 2.0 |

The website reads these via `raw.githubusercontent.com`. This repo exists so
the constant machine commits stay out of the website repo
([dunnand/WCYT-Website](https://github.com/dunnand/WCYT-Website)).
