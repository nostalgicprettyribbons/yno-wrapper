# YNOproject

A desktop wrapper for [YNOproject](https://ynoproject.net), built with [Tauri](https://tauri.app/).

YNOproject lets you play Yume Nikki and related fan games games directly in your browser. This project packages the existing YNOproject website as a simple desktop application.

## Downloads

[GitHub Releases](https://github.com/nostalgicprettyribbons/yno-wrapper/releases)

### Windows

Download the `.exe` installer and run it.

### Linux

A `.deb` package is provided for Debian/Ubuntu-based distributions.

Arch users can convert the `.deb` to an Arch package using [`debtap`](https://github.com/helixarch/debtap).

## Development

### Requirements

* Node.js
* Rust
* Tauri CLI

### Install dependencies

```bash
npm install
```

### Run in development

```bash
npm run tauri dev
```

### Build

```bash
npm run tauri build
```
