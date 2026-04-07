# homebrew-tap

Homebrew formulae and Scoop manifests for [Verda CLI](https://github.com/verda-cloud/verda-cli).

## Install

### macOS / Linux (Homebrew)

```sh
brew tap verda-cloud/tap
brew install verda-cli
```

### Windows (Scoop)

```sh
scoop bucket add verda https://github.com/verda-cloud/homebrew-tap
scoop install verda-cli
```

## Structure

```
Formula/   — Homebrew formulae (managed by GoReleaser)
bucket/    — Scoop manifests (managed by GoReleaser)
```
