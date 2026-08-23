# LucasOyarzun's Homebrew tap

A [Homebrew tap](https://docs.brew.sh/Taps) is just a repository of install
recipes. This one holds casks for macOS apps I publish.

## Install

```bash
brew install --cask LucasOyarzun/tap/bongo-token-cat
```

The `homebrew-` prefix is dropped in that name — Homebrew assumes it.

## Casks

| Cask | What it is |
|---|---|
| [`bongo-token-cat`](Casks/bongo-token-cat.rb) | A bongo cat per coding agent, drumming to its output. ([source](https://github.com/LucasOyarzun/BongoTokenCat)) |

Casks here are generated: each one's source of truth lives in the app's own
repository and is stamped with a version and checksum at release time. Send fixes
to the app repository rather than editing them here, or the next release will
overwrite them.