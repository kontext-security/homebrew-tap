# Kontext Security Homebrew Tap

Homebrew formulae maintained by [Kontext Security](https://kontext.security).

## Sandy (private preview)

Sandy is installed independently and does not require the Kontext CLI or
daemon. During the private preview, authenticate with an account that can read
`kontext-security/sandy`:

```bash
HOMEBREW_GITHUB_API_TOKEN="$(gh auth token)" \
  brew install kontext-security/tap/sandy
```

Use the same environment variable for upgrades:

```bash
HOMEBREW_GITHUB_API_TOKEN="$(gh auth token)" brew upgrade sandy
```

## Kontext

```bash
brew install kontext-security/tap/kontext
```

Kontext is installed and configured independently with `kontext setup`.

## Upgrade

```bash
brew upgrade kontext
```
