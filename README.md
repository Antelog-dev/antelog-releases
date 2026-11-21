# Antelog releases

Downloads for [Antelog](https://antelog.dev), the safety layer for AI agents.
Every action your agent wants to take is written down, checked, and blocked if it's dangerous, before it runs.

This repository contains release downloads only.

## Install

macOS and Linux:

```bash
curl -fsSL https://github.com/Antelog-dev/antelog-releases/releases/latest/download/install.sh | sh
```

Windows (PowerShell):

```powershell
irm https://github.com/Antelog-dev/antelog-releases/releases/latest/download/install.ps1 | iex
```

The installer checks every download against its published SHA-256 checksum before installing.

Then check it's working:

```bash
antelog doctor
```

## Downloads

All versions are on the [Releases](https://github.com/Antelog-dev/antelog-releases/releases) page. Each release has packages for macOS, Linux, and Windows, a `.sha256` checksum for each, and a combined `SHA256SUMS` file.

## License

Antelog is open source under the [Apache 2.0 license](LICENSE).
It is built on [LogAct](https://github.com/facebookresearch/logact) by Meta (MIT license); see [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md).
