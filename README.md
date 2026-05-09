# OneClaw Desktop — Releases

This repository hosts the **public release artifacts** for [OneClaw Desktop](https://oneclawhost.com/download), a graphical AI assistant built on OpenClaw.

The application source code lives in a separate private repository. Only the built binaries (`.dmg`, `.exe`, `.AppImage`, `.deb`, `.rpm`) and electron-updater metadata (`latest*.yml`) are published here so that:

- The official website can fetch release info via the unauthenticated GitHub API
- The desktop app's auto-updater can fall back to GitHub when the primary CDN is unavailable

## Download

Visit **<https://oneclawhost.com/download>** to get the latest version for your platform.

You can also browse all published versions on the [Releases page](https://github.com/aplomb2/Oneclaw_Desktop_Releases/releases).

## Channels

| Channel  | Purpose                  | Promoted to "latest" |
| -------- | ------------------------ | -------------------- |
| `vX.Y.Z` | Stable                   | Yes                  |
| `*-beta` | Public beta              | No (pre-release)     |
| `*-alpha`| Internal / early testing | No (pre-release)     |

## Issues

Found a bug or have feedback? Please open an [Issue](https://github.com/aplomb2/Oneclaw_Desktop_Releases/issues).

## License

See [LICENSE](./LICENSE).
