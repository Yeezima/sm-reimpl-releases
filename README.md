# sm-reimpl tester builds

Playtest builds of **sm-reimpl**, an unofficial fan reimplementation of the multiplayer of *Warhammer 40,000: Space Marine*
(2011, PC). It is not affiliated with or endorsed by Relic Entertainment, SEGA or Games Workshop.

## What you need

- Your own copy of *Space Marine* (2011) installed through Steam (app 55150). sm-reimpl reads the game's files from your install
  at runtime and never changes them. No original game files are included in these downloads.
- Windows 10 or 11, 64-bit (a Linux build of the dedicated server is also provided).

## Getting a build

Builds are on the [Releases](../../releases) page. Each release has:

- `sm-reimpl-client-win64-<version>.zip`: the game client. Unzip it and run `Play.cmd`.
- `sm-reimpl-server-win64-<version>.zip` and `sm-reimpl-server-linux-x64-<version>.zip`: dedicated servers.
- `sm-reimpl-source-<version>.zip`: the complete source code of that build (GPL-3.0).
- `SHA256SUMS.txt`: checksums of the files above.

A tester guide (install, controls, what to test, known issues) ships inside each client zip.

## Reporting

Use [Issues](../../issues) to report bugs or anything that plays differently from the original game. Please include the
version from `VERSION.txt`. Evidence such as a timestamped link to original gameplay footage helps the most.

## License

sm-reimpl is free software under the GNU General Public License v3.0 (see `LICENSE`). The source code of every build is
attached to its release.
