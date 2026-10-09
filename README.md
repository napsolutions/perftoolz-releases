# perftoolz releases

Public release artifacts for **perftoolz** — a Linux eBPF performance monitor (Debian / Ubuntu, amd64 + arm64).

## Install

```bash
curl -fsSL https://github.com/napsolutions/perftoolz-releases/releases/latest/download/install.sh | sudo bash
```

Downloads the latest `.deb` for your architecture, verifies its SHA-256 checksum and installs it as a systemd service. Dashboard: http://localhost:8411

See [Releases](https://github.com/napsolutions/perftoolz-releases/releases) for versions, release notes, binaries and checksums.

_This repository only hosts release artifacts; it is populated automatically by the build pipeline._
