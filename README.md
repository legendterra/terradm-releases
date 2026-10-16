# TerraDM — downloads

Releases of **TerraDM (Terra Download Manager)** for Windows: an IDM-style download manager that
splits one file over several networks at once, with browser capture, a "Download this video" bar,
YouTube/stream grabbing with subtitles, queues and live recording.

Get the latest from **[Releases](https://github.com/legendterra/terradm-releases/releases/latest)**:

| File | What it is |
| --- | --- |
| `terradm-<version>-setup.exe` | Installer (Windows 10/11, x64). Starts with Windows; updates in place. |
| `terradm-<version>-portable-x64.zip` | Portable: unzip anywhere (an external drive too) and run `TerraDM.exe`. |
| `terradm-firefox-<version>-unsigned.xpi` | Firefox extension (Developer Edition/Nightly, or `about:debugging` › Load Temporary Add-on). |
| `terradm-chrome-<version>-unsigned.zip` | Chrome / Brave / Vivaldi: unzip, `chrome://extensions` › Developer mode › Load unpacked. |
| `terradm-edge-<version>-unsigned.zip` | Edge: same, from `edge://extensions`. |
| `terradm-opera-<version>-unsigned.zip` | Opera: same, from `opera://extensions`. |

The installer isn't code-signed yet: on first run Windows SmartScreen may ask — **More info ›
Run anyway**.

What changed in each version is in each release's notes.

## Credits

TerraDM is made by [legendterra](https://github.com/legendterra) (Mochammad Raihan). It is a fork
of [Plexo](https://github.com/anmolkapil/plexo) by Anmol Kapil: the multi-network download
engine is Plexo's. Both are MIT-licensed — see [LICENSE](LICENSE). Bundled: ffmpeg (LGPL) and
yt-dlp (Unlicense).
