# Kontext Security Homebrew Tap

Homebrew formulae maintained by [Kontext Security](https://kontext.security).

## Sandy

Sandy is installed independently and does not require the Kontext CLI or
daemon.

```bash
brew install kontext-security/tap/sandy
```

Verify that macOS sandboxing is available:

```bash
sandy doctor
```

## Kontext

```bash
brew install kontext-security/tap/kontext
```

Kontext is installed and configured independently with `kontext setup`.

## Upgrade

```bash
brew upgrade sandy kontext
```
