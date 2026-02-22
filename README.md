# homebrew-tap

Homebrew tap for Aman Thanvi CLI tools.

## Install Heimdall

```bash
brew tap amanthanvi/tap
brew install amanthanvi/tap/heimdall
```

## Verify install

```bash
heimdall --help
heimdall version
```

## Release and formula conventions

- Canonical formula location: `Formula/heimdall.rb`
- Formula URLs must reference released `tar.gz` assets named `heimdall-<os>-<arch>.tar.gz`
- Each archive must contain the `heimdall` binary at archive root
