# Architecture — OwlSter-Clicker

## Overview

OwlSter Clicker — Unity WebGL кликер-игра. Компилированный билд для веба.

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Engine | Unity (WebGL export) |
| Runtime | WebAssembly |

## Project Structure

```
├── index.html       # Unity WebGL loader
├── Build/           # Compiled WASM + data
├── TemplateData/    # Unity template assets
└── LICENSE          # MIT
```

## Key Concepts

- **Clicker game** — геймплей на кликах/тапах
- **WebGL build** — билд без исходников
- **Source** → см. [OwlSter-Source](file:///c:/100star/OwlSter-Source)
