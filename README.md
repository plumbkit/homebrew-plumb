# homebrew-plumb

Homebrew tap for [**plumb**](https://github.com/plumbkit/plumb) — the IDE intelligence
layer for AI coding agents: LSP semantics, a tree-sitter topology index, per-project
memory, and concurrency-safe edits, delivered as an MCP server.

## Install

```sh
brew install plumbkit/plumb/plumb
```

That is shorthand for tapping this repo and installing the formula:

```sh
brew tap plumbkit/plumb
brew install plumb
```

Upgrade to the latest release:

```sh
brew upgrade plumb
```

## What's in this repo

`Formula/plumb.rb` is generated and updated automatically by
[GoReleaser](https://goreleaser.com) on every [plumb release](https://github.com/plumbkit/plumb/releases)
— **do not edit it by hand.** Each release publishes binaries for macOS
(Intel + Apple Silicon) and Linux (Intel + ARM); the formula selects the right
one for your platform.

## Links

- Main project: <https://github.com/plumbkit/plumb>
- Issues & support: <https://github.com/plumbkit/plumb/issues>

## Licence

MIT — see [LICENSE](LICENSE).
