# Homebrew tap for Disk Steward

This is the official Homebrew tap for [Disk Steward](https://github.com/KMerdan/disk_steward), a private macOS menu-bar monitor that turns disk growth into bounded evidence a human, Codex, or Claude can inspect.

## Developer-preview status

The tap is public, but the cask is intentionally **disabled** until an immutable Disk Steward release asset passes Developer ID signing, notarization, stapling, Gatekeeper, and launch verification. This lets the packaging contract be inspected without distributing an unnotarized build.

```sh
brew tap KMerdan/disk-steward
brew install --cask disk-steward
```

The tap command works today. The install command stops with the explicit disabled reason. It will become installable only after the notarized release gate passes and the cask is pinned to an exact version, release URL, and SHA-256.

Release details and the activation checklist live in the [main repository](https://github.com/KMerdan/disk_steward/blob/main/Packaging/Homebrew/README.md).

## License

The tap is available under the [MIT License](LICENSE).
