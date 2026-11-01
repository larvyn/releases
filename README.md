# Larvyn

The Laravel workbench: your Laravel apps, their dev services, terminals, data
and AI coding agents in one native window.

This repository only hosts the releases and the install scripts.

## Install

**Linux and macOS**

```sh
curl -fsSL https://raw.githubusercontent.com/ivanmercedes/larvyn-releases/main/install.sh | sh
```

**Windows** (PowerShell)

```powershell
irm https://raw.githubusercontent.com/ivanmercedes/larvyn-releases/main/install.ps1 | iex
```

Run the same command again to update. Every download is checked against the
release's `checksums.txt`.

Linux needs GTK 4 and WebKitGTK 6.0 (Ubuntu 24.04+, Fedora 39+, Arch); the
installer tells you the exact package names if they are missing.

## Uninstall

```sh
curl -fsSL https://raw.githubusercontent.com/ivanmercedes/larvyn-releases/main/install.sh | sh -s -- --uninstall
```

```powershell
$env:LARVYN_UNINSTALL = "1"; irm https://raw.githubusercontent.com/ivanmercedes/larvyn-releases/main/install.ps1 | iex
```

## Manual download

Grab the file for your system from [Releases](https://github.com/ivanmercedes/larvyn-releases/releases).
Windows and macOS builds are not code-signed yet, so a browser download shows
a security warning; the install scripts above avoid it.
