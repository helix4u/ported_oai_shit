# Codex Linux One-File Installer

Linux installer script is published as a GitHub Release asset:

- Release page: `https://github.com/helix4u/ported_oai_shit/releases/tag/linux-onefile-v1`
- Direct download: `https://github.com/helix4u/ported_oai_shit/releases/download/linux-onefile-v1/install-codex-linux-onefile.sh`

## Install

```bash
curl -L -o install-codex-linux-onefile.sh \
  https://github.com/helix4u/ported_oai_shit/releases/download/linux-onefile-v1/install-codex-linux-onefile.sh
chmod +x install-codex-linux-onefile.sh
./install-codex-linux-onefile.sh
```

## What it installs

- App files to `~/.local/opt/Codex`
- Launcher symlink at `~/.local/bin/codex`
- Desktop file `codex.desktop`

## Requirements

- Linux `x86_64` (not ARM)
- User-writable home directory

## Optional verification

Release asset SHA-256:

```text
5a2713941c73de19a177791afde3c7d29aab3d859b4ec5356e3dd4dd87654f9a
```

You can verify after download:

```bash
sha256sum install-codex-linux-onefile.sh
```
