# LoL Meta Coach open-source components

LoL Meta Coach, the desktop app from [lolmeta.gg](https://lolmeta.gg), includes two free programs made by
other projects. Both ship exactly as their projects release them and run as separate programs next to the
app. Their licences give you the right to their source code, so here it is.

**Every app version has its own [release](https://github.com/couchcode/lolmeta-coach-sources/releases)**,
named after the app version (`v0.1.0` is LoL Meta Coach 0.1.0). Each release holds the source for exactly
the versions shipped in that installer, the licences, and a `SHA256SUMS` file to check them with.
Releases stay up for as long as the matching installer is offered, and at least three years after that.

| Program | Licence | What it does in LoL Meta Coach |
| --- | --- | --- |
| [OBS Studio](https://obsproject.com/) | GPL-2.0-or-later | Records the game. Shipped unmodified in the `obs` folder and started as its own program. |
| [FFmpeg](https://ffmpeg.org/) ([BtbN Windows build](https://github.com/BtbN/FFmpeg-Builds)) | GPL-3.0-or-later (built with `--enable-gpl --enable-version3`) | Renders reels and Shorts. Shipped unmodified in the `ffmpeg` folder and started as its own program. |

For FFmpeg, each release also carries BtbN's build scripts at the tag that produced the binary. They pin
and configure every library linked into it.

## Written offer

For at least three years after we last distribute a version of LoL Meta Coach, couchcode
(Meyn & Schlickum GbR) will give anyone who asks a complete machine-readable copy of the corresponding
source code of the GPL-licensed programs above, including the libraries built into them, on a medium
customarily used for software interchange, for no more than the cost of physically performing the
distribution. Write to [contact@lolmeta.gg](mailto:contact@lolmeta.gg?subject=Source%20request) and name
the version.

## Everything else

The app itself is built on Electron (MIT) and Chromium (BSD-style and others; the full list is in
`LICENSES.chromium.html` in the installation folder), React, Tailwind CSS, ws and Inter, all under MIT,
Apache-2.0 or OFL licences.

## Trademarks

OBS and OBS Studio are trademarks of the OBS Project. FFmpeg is a trademark of Fabrice Bellard.
LoL Meta Coach is not affiliated with or endorsed by either project.

LoL Meta Coach isn't endorsed by Riot Games and doesn't reflect the views or opinions of Riot Games or
anyone officially involved in producing or managing Riot Games properties. Riot Games, and all associated
properties are trademarks or registered trademarks of Riot Games, Inc.
