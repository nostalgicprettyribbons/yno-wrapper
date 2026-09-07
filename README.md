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

> On Linux, the application uses the system WebKitGTK runtime.

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

## How it works

The local Tauri page immediately redirects to:

```text
https://ynoproject.net
```

Tauri then displays the existing YNOproject website inside a native desktop window.

## Project structure

```text
yno-wrapper/
├── src/                  # Minimal frontend
├── src-tauri/            # Tauri application
├── index.html            # Redirects to YNOproject
├── package.json
└── vite.config.ts
```

## License

MIT
