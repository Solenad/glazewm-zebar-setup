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

## License

MIT License — see [LICENSE](LICENSE) for details.

---

<div align="center">

[![Star History Chart](https://api.star-history.com/svg?repos=Solenad/glazewm-zebar-setup&type=Date)](https://star-history.com/#Solenad/glazewm-zebar-setup&Date)

</div>
