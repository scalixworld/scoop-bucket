# Scalix World — Scoop Bucket

Official Windows Scoop manifests for [**Scalix Cloud**](https://scalix.world) — manage PostgreSQL databases (ScalixNova), serverless functions, containers (Scalix Run), persistent Linux Computers, object storage, and AI inference with one API key.

## Install

```powershell
scoop bucket add scalix https://github.com/scalixworld/scoop-bucket
scoop install scalix/scalix-cloud
scalix-cloud login   # API key from https://console.scalix.world
```

| Manifest | Package | Binary Releases |
|---|---|---|
| `scalix-cloud` | Scalix Cloud CLI (Windows `x86_64`) | [`scalixworld/scalix-cloud-cli`](https://github.com/scalixworld/scalix-cloud-cli/releases) |

Also available via npm (`npm install -g scalix-cloud`) and Homebrew (macOS/Linux). See [CLI Docs](https://docs.scalix.world/cli).

*(Not to be confused with [`scalix`](https://www.npmjs.com/package/scalix) on npm, which is Scalix Coder, the AI coding agent.)*

---

Scalix Cloud and `scalix-cloud` are proprietary software owned by **Scalix World Pvt Ltd** (India) and licensed internationally via **Energy FW Ltd** (UK). Core source code lives in the private platform monorepo; this bucket distributes Scoop install manifests pointing to prebuilt releases (`BUSL-1.1`).

© 2026 Scalix World Pvt Ltd · [Terms](https://scalix.world/terms) · [Security](https://scalix.world/security)
