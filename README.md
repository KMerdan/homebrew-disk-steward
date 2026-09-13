# Homebrew tap for Disk Steward

This is the official Homebrew tap for [Disk Steward](https://github.com/KMerdan/disk_steward), a private macOS menu-bar monitor that turns disk growth into bounded evidence a human, Codex, or Claude can inspect.

## Install

Disk Steward 1.0.0 is Developer ID signed, hardened, notarized, and available from this tap:

```sh
brew trust KMerdan/disk-steward
brew tap KMerdan/disk-steward
brew install --cask disk-steward
```

Current Homebrew releases require explicit trust before loading a third-party tap. Trust the KMerdan tap only if you intend to accept its current and future casks. The cask resolves an immutable GitHub release archive and verifies its pinned SHA-256 before installation.

Release details and the activation checklist live in the [main repository](https://github.com/KMerdan/disk_steward/blob/main/Packaging/Homebrew/README.md).

## License

The tap is available under the [MIT License](LICENSE).
