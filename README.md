# Releases

Public download host for **Untitled Repo LLC**'s macOS apps. Contains **no
source** — only compiled, Developer ID-signed and Apple-notarized builds and
Sparkle update assets, served over GitHub's CDN, free of charge.

Each app gets its own **rolling release tag**; assets are versioned by filename:

| App | Tag | Site | Assets |
|-----|-----|------|--------|
| DiskLoupe | [`diskloupe`](../../releases/tag/diskloupe) | <https://diskloupe.com> | `DiskLoupe-<v>.dmg` (download), `DiskLoupe-<v>.zip` (auto-update) |
| StreamCheck | [`streamcheck`](../../releases/tag/streamcheck) | <https://www.ptrandco.com/streamcheck> | `StreamCheck-<v>.dmg` (download), `StreamCheck-<v>.zip` (auto-update) |
| Cuetally Relay | [`cuetally-relay`](../../releases/tag/cuetally-relay) | <https://app.cuetally.app> | `Cuetally-Relay-<v>.dmg` (download), `Cuetally-Relay-<v>.zip`, `Cuetally-Relay.dmg` (always the latest) |

Each app's in-app Sparkle updater reads an appcast on that app's own site, which
points at the `.zip` assets here. (Cuetally Relay has no auto-update yet: it's
downloaded again, from the fixed-name `Cuetally-Relay.dmg`.) Downloads are free and unauthenticated; the
apps are licensed separately.
