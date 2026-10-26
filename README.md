# Transmission Helm Homebrew tap

```bash
brew tap transmission-helm/tap
brew install --cask --no-quarantine transmission-helm
```

The app is not code-signed. `--no-quarantine` lets it open directly; without it, right-click the app and choose **Open** the first time.

Upgrade with `brew upgrade --cask transmission-helm`. The cask is updated from the release checksums in the main repository: https://github.com/transmission-helm/transmission-helm
