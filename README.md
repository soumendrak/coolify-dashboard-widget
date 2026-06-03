<div align="center">
  <img src="./logo.svg" alt="coolify-dashboard-widget" width="120" />
  <h1>Coolify Dashboard Widget</h1>
  <p>Single-file HTML dashboard that pulls deployment status, container health, and resource usage from the Coolify API.</p>

  ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
  ![License: MIT](https://img.shields.io/badge/license-MIT-blue?style=flat)
  ![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen?style=flat)
</div>

---

## Overview

Single-file HTML dashboard that pulls deployment status, container health, and resource usage from the Coolify API.

Built as a single-file HTML application — no build tools, no frameworks, no external dependencies. Just open `index.html` in any modern browser.

## Features

- Connect to any Coolify instance via API URL and bearer token
- Real-time dashboard showing all applications with status badges
- CPU, RAM, and uptime metrics per application
- Resource usage progress bars
- LocalStorage-based config persistence (no server needed)
- Dark theme optimized for monitoring dashboards

## Quick Start

1. Clone the repository
2. Open `index.html` in your browser
3. Enter your Coolify API URL and token
4. Click Refresh

```bash
git clone https://github.com/soumendrak/coolify-dashboard-widget.git
cd coolify-dashboard-widget
open index.html
```

## Project Structure

```
coolify-dashboard-widget/
├── index.html    # The complete application
├── LICENSE       # MIT License
└── README.md     # This file
```

## Dark Theme

All projects in this suite share a consistent dark theme:

| Token | Color | Usage |
|-------|-------|-------|
| `--bg` | `#0f0f1a` | Page background |
| `--surface` | `#1a1a2e` | Cards, headers, panels |
| `--accent` | `#ff6b35` | Buttons, highlights, borders |
| `--text` | `#e0e0e0` | Body text |

## Contributing

Contributions welcome! Open an issue or submit a PR.

## License

MIT © [Soumendra Kumar Sahoo](https://github.com/soumendrak)
