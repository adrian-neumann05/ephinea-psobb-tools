# Ephinea Tools - PSOBB Game Utility 2026

> **Web utilities built for Ephinea PSOBB.** Load inventory exports, inspect character stats, and ballpark item worth against the Ephinea price guide—all from your browser.

[![Game Utility](https://img.shields.io/badge/Type-Game%20Utility-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-Web%20browser-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/adrian-neumann05/ephinea-psobb-tools?style=flat-square)](https://github.com/adrian-neumann05/ephinea-psobb-tools)

---

<p align="center">
  <a href="https://adrian-neumann05.github.io/ephinea-psobb-tools/">
    <img src="https://img.shields.io/badge/Download-Ephinea%20Tools-brightgreen?style=for-the-badge" alt="Download Ephinea Tools">
  </a>
</p>

> **[Download - Ephinea Tools](https://adrian-neumann05.github.io/ephinea-psobb-tools/)**

---

[Download Latest Build](https://adrian-neumann05.github.io/ephinea-psobb-tools/)

---

## What it is

Ephinea Tools is a static, browser-only helper set for Ephinea PSOBB. You can pull inventory data into the page, walk through character details in a status simulator, and cross-check gear against Ephinea price-guide figures.

Everything that touches your inventory runs locally in the browser—nothing is posted to a backend. Status simulation and appraisal sit alongside inventory review so you can plan and reference without leaving the site. Ongoing work keeps those Ephinea-focused lookup and calculation pieces practical.

---

## What you can do

- Bring inventory data into the page for inspection
- Run inventory handling entirely on the client
- Rough out total worth with the Ephinea price guide
- Try character status scenarios in the simulator
- Support everyday Ephinea PSOBB inventory planning
- Use a pure static site—no server upload of inventory
- Keep import, status, and pricing tools in one place
- Skip desktop installs; a normal web browser is enough

---

## Getting started

1. Open the [latest build](https://adrian-neumann05.github.io/ephinea-psobb-tools/).
2. Feed the tool the inventory format it accepts via the import UI.
3. Check the loaded items in the browser.
4. Switch to status simulation or price appraisal when you need them.

You get a static web package. After you grab the files, any static file server can host a local copy. Typical flow:

```text
Download the project -> serve the files -> open the site in a web browser
```

Inventory work stays in the browser; that data is not transmitted to a server.

---

## Tool layout

There is no separate config file—the product is split by utility surface.

| Tool area | Purpose |
| --- | --- |
| Inventory import | Load inventory data for browser-based inspection |
| Status simulator | Explore character status information |
| Price appraisal | Estimate inventory value from the Ephinea price guide |
| Browser processing | Handle imported inventory data locally |

---

## Compatibility

- **Target game:** Ephinea PSOBB
- **Platform:** Modern web browser
- **Delivery format:** Static site
- **Inventory handling:** Processed in the browser
- **Version support:** Results depend on the inventory data and Ephinea price-guide information available to the build

Built for reviewing Ephinea-related data. It is not a game client replacement. Appraised values are reference estimates drawn from the Ephinea price guide.

---

## Changelog

### 2026

- Kept the browser Ephinea PSOBB utility set current
- Carried forward inventory import, status simulation, and price appraisal flows

---

## FAQ

### How do I begin?

Launch the [latest build](https://adrian-neumann05.github.io/ephinea-psobb-tools/) in a browser and pick the utility you need.

### What happens to imported inventory?

Processing stays in the browser; inventory is not uploaded to a server.

### Do I need a desktop app?

No. Ephinea Tools ships as a static site meant to run in a web browser.

### Where do item prices come from?

Appraisal uses the Ephinea price guide bundled with the active build.

### Can I tweak the status simulator?

The simulator is there to explore character status. Inputs and controls live in the web UI itself.

### Does this cover every PSOBB fork?

Focus is Ephinea PSOBB. Behavior can diverge if your inventory dump or price data does not match what the build expects.

### How should I keep a local copy?

Store the project files in a single folder. If file:// access misbehaves, serve that folder with a local static web server.

### How do updates reach me?

Prefer the hosted [latest build](https://adrian-neumann05.github.io/ephinea-psobb-tools/), or pull a newer project release when it appears.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
