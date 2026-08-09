# Garbus-Releases

Automated playtest builds of [Garbus](https://github.com/neco-soft/Garbus) (private).

Each `master-<sha>` prerelease is published by CI from the source repo and contains:

- `Garbus-win-x64.zip` — Windows x64
- `Garbus-linux-x64.zip` — Linux x64
- `Garbus-osx-arm64.zip` — macOS Apple Silicon
- `SHA256SUMS.txt` — download verification

The in-install `update.bat` / `update.sh` scripts pull the newest build from here.
