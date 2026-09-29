# homebrew-tap

Homebrew cask for the Lucity CLI (`lucity`). Published automatically by goreleaser.

```sh
brew install --cask zeitlos/tap/lucity
```

Up to 26.7.2 the CLI was published as a formula, which no longer receives updates. If you installed it back then, remove the formula before installing the cask, because otherwise the cask leaves the old binary on your `PATH`:

```sh
brew uninstall --formula lucity
brew install --cask zeitlos/tap/lucity
```
