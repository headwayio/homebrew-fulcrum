# homebrew-fulcrum

Homebrew tap for the [Fulcrum CLI](https://github.com/headwayio/fulcrum-cli).

```sh
brew install headwayio/fulcrum/fulcrum
```

Linux has no Homebrew cask support, so install there with:

```sh
curl -fsSL https://raw.githubusercontent.com/headwayio/fulcrum-cli/main/install.sh | sh
```

## This tap is generated

`Casks/fulcrum.rb` is written by GoReleaser when a `v*` tag is pushed to
`headwayio/fulcrum-cli`. Do not edit it by hand — the next release overwrites
it. Change `.goreleaser.yml` in that repository instead.

It is a **cask**, not a formula: it installs the pre-built binary, so nobody
needs a Go toolchain to install the CLI.
