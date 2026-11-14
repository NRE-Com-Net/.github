# Changelog

Format nach [Keep a Changelog](https://keepachangelog.com/de/1.1.0/).

## [Unveröffentlicht] – 2026-11-14

### Hinzugefügt

- `default.json`: gemeinsame Renovate-Grundeinstellung. Repositories binden sie mit
  `"extends": ["local>NRE-Com-Net/.github"]` ein. Sie enthält `config:recommended`,
  `docker:pinDigests` (Docker-Images auf Digests festlegen), `helpers:pinGitHubActionDigests`
  (GitHub Actions auf Commit-Hashes festlegen) und `minimumReleaseAge` von einem Tag.
