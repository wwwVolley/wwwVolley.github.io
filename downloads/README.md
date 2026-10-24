# LimeCode release files

This directory is reserved for verified public release artifacts.

Publish only the four files generated from the same source revision and version:

- `LimeCode-1.0.0-macOS-universal2-app.dmg`
- `LimeCode-1.0.0-macOS-universal2-full.dmg`
- `LimeCode-1.0.0-macOS-universal2-cli.pkg`
- `LimeCode-1.0.0-macOS-universal2-mcp.pkg`

Each artifact must be signed, notarized, stapled, checked with Gatekeeper tools, and accompanied by SHA-256 checksums before publishing. Do not upload local debug builds or unsigned packages.
