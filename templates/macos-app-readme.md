<!--
Jonathan Arteaga macOS app README template

Use this for public or portfolio-ready macOS apps.

Required assets:
- docs/assets/<app-slug>-icon.png, ideally 512x512 or 1024x1024
- docs/assets/<app-slug>-preview.png, a clean hero screenshot

Optional assets:
- docs/assets/<app-slug>-demo.gif
- docs/assets/<app-slug>-settings.png

Keep the README scannable:
- One clear promise above the fold.
- One primary action.
- One strong screenshot before long text.
- Advanced build/release details inside <details>.
-->

<p align="center">
  <img src="docs/assets/<app-slug>-icon.png" width="112" alt="<App Name> app icon">
</p>

<h1 align="center"><App Name></h1>

<p align="center">
  <strong><One-sentence product promise.></strong>
</p>

<p align="center">
  <a href="https://github.com/jonathan-arteaga/<repo>/releases/latest">
    <img alt="Latest release" src="https://img.shields.io/github/v/release/jonathan-arteaga/<repo>?label=release&color=111111">
  </a>
  <img alt="macOS <version>+" src="https://img.shields.io/badge/macOS-<version>%2B-111111?logo=apple">
  <img alt="Built with Swift" src="https://img.shields.io/badge/Swift-111111?logo=swift&logoColor=white">
  <img alt="<Distribution status>" src="https://img.shields.io/badge/<Distribution%20status>-111111">
</p>

<p align="center">
  <a href="https://github.com/jonathan-arteaga/<repo>/releases/latest"><strong>Download</strong></a>
  ·
  <a href="#features">Features</a>
  ·
  <a href="#install">Install</a>
  ·
  <a href="#troubleshooting">Troubleshooting</a>
</p>

![<App Name> preview](docs/assets/<app-slug>-preview.png)

<App Name> is a native macOS app for <audience/job>. It helps you <primary outcome> without <main pain avoided>.

## Why <App Name>

- <Benefit 1>
- <Benefit 2>
- <Benefit 3>

## Features

| | |
|---|---|
| **<Feature group 1>** | <Short explanation.> |
| **<Feature group 2>** | <Short explanation.> |
| **<Feature group 3>** | <Short explanation.> |
| **<Feature group 4>** | <Short explanation.> |

## Install

1. Download the latest release.
2. Open the DMG or ZIP.
3. Move `<App Name>.app` into Applications.
4. Open `<App Name>` once so macOS can finish registration.
5. <First useful action.>

> [!NOTE]
> <Permission/signing/notarization note.>

## Privacy

<Plain-language privacy posture. Say what stays on device, what is never uploaded, and whether accounts/network calls are used.>

## Troubleshooting

<details>
<summary><App Name> is not working as expected</summary>

### <Problem 1>

<Fix.>

### <Problem 2>

<Fix.>

### Clean local caches

```bash
<optional command>
```

</details>

## Build From Source

<details>
<summary>Developer setup, packaging, and release notes</summary>

Build and run locally:

```bash
./script/build_and_run.sh
```

Run tests:

```bash
swift test
```

Package a release artifact:

```bash
./script/package_dmg.sh
```

Public distribution should use Developer ID signing, hardened runtime, notarization, and stapling.

</details>

## Status

<One short sentence about maturity: prototype, early but usable, public beta, stable, etc.>
