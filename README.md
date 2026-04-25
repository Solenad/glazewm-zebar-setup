<div align="center">

# GlazeWM + Zebar Setup

Tiling window manager and system bar configuration for Windows.

[![License: MIT](https://img.shields.io/badge/License-MIT-orange.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

</div>

## What is this?

A desktop setup pairing [GlazeWM](https://github.com/larsgorges/glazewm) (a tiling window manager for Windows) with [Zebar](https://github.com/glzr-io/zebar) (a customizable system bar). Includes configuration files and a custom Zebar theme.

## Quick Start

### GlazeWM

1. Install GlazeWM from [releases](https://github.com/larsgorges/glazewm/releases)
2. Copy `glazewm/config.yaml` to `%APPDATA%\glazewm\config.yaml`

### Zebar

1. Install Zebar from [releases](https://github.com/glzr-io/zebar/releases)
2. Copy `zebar/settings.json` to `%APPDATA%\zebar\settings.json`
3. For the neobrutal theme, use `zebar/neobrutal-zebar/`

## Project Structure

```
.
├── glazewm/
│   ├── config.yaml      # GlazeWM window manager config
│   └── errors.log       # Error logs
├── zebar/
│   ├── .github/         # GitHub workflows (for Zebar repo)
│   ├── .marketplace/    # Marketplace assets
│   ├── neobrutal-zebar/ # Custom Zebar theme
│   ├── settings.json    # Zebar configuration
│   └── errors.log       # Error logs
├── LICENSE
└── README.md
```

## Customization

### GlazeWM

Edit `glazewm/config.yaml` to modify:

- Keybindings (default: `Alt` as modifier)
- Window sizing and gaps
- Workspace layouts
- Startup programs

### Zebar

- Base config: `zebar/settings.json`
- Neobrutal theme: explore `zebar/neobrutal-zebar/`
- Zebar supports multiple providers (weather, clock, media, etc.) — add them in settings

## Why This Setup?

- **GlazeWM** brings Linux-style tiling window management to Windows
- **Zebar** provides a modern, customizable system bar
- The **neobrutal-zebar** theme offers a distinctive aesthetic inspired by neobrutalism

## Gotchas

- GlazeWM requires Windows 10/11
- Some apps may need manual rules in `config.yaml` to tile correctly (e.g., floating dialogs)
- Zebar providers may require additional configuration (API keys for weather, etc.)

## License

MIT License — see [LICENSE](LICENSE) for details.

---

</div>
