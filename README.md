# mselin's Homebrew tap

Homebrew formulae for programs by [mselin](https://github.com/mselin).

| Formula | What it is |
|---|---|
| [`sleazeburg-presence`](Formula/sleazeburg-presence.rb) | The optional helper that shows what you are doing in [Sleazeburg 64](https://mselin.github.io/gta-c64/) on your Discord profile. Built on your Mac from the tagged source code. |

## Install

```bash
brew tap mselin/tap
```

```bash
brew install mselin/tap/sleazeburg-presence
```

Installing by the full name trusts that one formula, not everything in the tap. Code in a tap runs with your
user's permissions, so read the formula before installing it: it is a short file in [`Formula/`](Formula/).

Nothing prebuilt is downloaded. Homebrew fetches the release's source archive from GitHub, checks it against
the checksum in the formula, and builds the program with Go, so macOS has no downloaded binary to warn about.

What the program does, how to start it automatically and how to remove it are in its
[README](https://github.com/mselin/mselin.github.io/tree/main/gta-c64/tools/presence-bridge#readme).

## Where the formulae come from

Each release of the presence bridge is built by the release workflow in
[mselin/mselin.github.io](https://github.com/mselin/mselin.github.io), which attaches the formula for that release.
The file here is that formula, unchanged.

## Licence

The formulae are free software under the [GNU General Public License](LICENSE), version 2 or later, like the
programs they install.
