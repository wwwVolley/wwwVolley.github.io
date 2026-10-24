# LimeCode 1.0.0 public release files

These are the public Developer ID distribution artifacts for version 1.0.0. The DMGs and installer packages are universal2, signed, notarized, and stapled where supported. They require macOS 12 or later.

Publish only the four files generated from the same source revision and version:

- `LimeCode-1.0.0-macOS-universal2-app.dmg`
- `LimeCode-1.0.0-macOS-universal2-full.dmg`
- `LimeCode-1.0.0-macOS-universal2-cli.pkg`
- `LimeCode-1.0.0-macOS-universal2-mcp.pkg`

`SHA256SUMS` contains the SHA-256 digest for each downloadable artifact. From this directory, verify downloads with:

```sh
shasum -a 256 -c SHA256SUMS
```

These files are the website distribution, not the App Store submission package. Do not replace them with local debug builds, unsigned packages, or App Store-specific packages.
