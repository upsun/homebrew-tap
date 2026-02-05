# Homebrew Tap & Scoop Bucket

This repository hosts [Homebrew](https://brew.sh/) formulae and [Scoop](https://scoop.sh/) manifests for Upsun CLI.

## Homebrew (macOS/Linux)

### Installation

```bash
# Add the tap
brew tap upsun/tap

# Install Upsun CLI
brew install upsun-cli

# Or just
brew install upsun/tap/upsun-cli
```

### Upgrading

```bash
brew update
brew upgrade upsun-cli
```

## Scoop (Windows)

### Installation

```powershell
# Add the bucket
scoop bucket add upsun https://github.com/upsun/homebrew-tap.git

# Install Upsun CLI
scoop install upsun/upsun
```

### Upgrading

```powershell
scoop update upsun/upsun
```

## License

MIT
