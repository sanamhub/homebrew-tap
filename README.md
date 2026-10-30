# Homebrew tap for Sluice

[Sluice](https://github.com/sanamhub/sluice) sends a file straight from one computer to another.
Nothing is stored in between.

```sh
brew install sanamhub/tap/sluice
```

The formula installs the release binary for macOS or Linux, on arm64 or x86_64. Upgrade with
`brew upgrade sluice` and remove with `brew uninstall sluice`.

`Formula/sluice.rb` is generated from the release's checksums by `cargo xtask package` in the Sluice
repository. Do not edit it by hand: change the template there and generate it again.
[`docs/install.md`](https://github.com/sanamhub/sluice/blob/main/docs/install.md) lists every way to
install Sluice and how to verify a download.
