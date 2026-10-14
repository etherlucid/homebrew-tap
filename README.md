# etherlucid/tap

Official Homebrew tap for [etherlucid](https://github.com/etherlucid).

---

## Installation

Add this tap to your Homebrew installation:

```bash
brew tap etherlucid/tap
```

---

## Available Formulae

| Formula | Description | Installation |
| :--- | :--- | :--- |
| **`nowplaying-scrobbler`** | Real-time ListenBrainz desktop scrobbler for YouTube Music Safari PWA and MediaRemote | `brew install nowplaying-scrobbler` |

---

## Service Management

For daemons packaged with background services:

```bash
# Start background service at login
brew services start etherlucid/tap/nowplaying-scrobbler

# Stop service
brew services stop etherlucid/tap/nowplaying-scrobbler
```
