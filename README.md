# 3HPM Nuvio Wizard v2026 - browser-based setup helper 2026

> **A browser-based setup helper for Nuvio v2026 that simplifies debrid integration, produces scraper manifest URLs, and assembles Comet configuration through a modern web flow.**

[![Platform](https://img.shields.io/badge/Platform-Web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/willio2001/3hpm-nuvio-config-wizard?style=flat-square)](https://github.com/willio2001/3hpm-nuvio-config-wizard)

---

<p align="center">
  <a href="https://willio2001.github.io/3hpm-nuvio-config-wizard/">
    <img src="https://img.shields.io/badge/Download-3HPM%20Nuvio%20Wizard%20Latest-brightgreen?style=for-the-badge" alt="Download 3HPM Nuvio Wizard">
  </a>
</p>

> **[Direct Download - 3HPM Nuvio Wizard v2026](https://willio2001.github.io/3hpm-nuvio-config-wizard/)**

---

[Download Latest Build](https://willio2001.github.io/3hpm-nuvio-config-wizard/)

---

## Overview

3HPM Nuvio Wizard is a browser-first setup companion for the Nuvio v2026 workflow. It is intended to prepare the pieces used for debrid integration, create scraper manifest URLs, and shape Comet configuration without depending on a traditional desktop installation.

Because it is delivered as a static web app, you can open it directly in a browser and use it as a compact configuration tool. It works well when you want a guided way to produce consistent setup output for the current release while keeping everything centered in the web interface.

---

## What it does

- Creates scraper manifest URLs for Nuvio-related setup flows
- Produces Comet configuration output for the current release
- Includes a Connected Services workflow
- Base64-encodes generated output for easier transport or embedding
- Keeps API keys out of the generated manifest
- Operates as a static browser-based web app
- Supports a lightweight workflow for web configuration tasks
- Targets the Nuvio v2026 release path

---

## Installation

Clone or download the repository, then open the static web app in your browser.

```bash
git clone https://github.com/willio2001/3hpm-nuvio-config-wizard.git
cd REPO
```

Once the files are available locally, open the main HTML file in a browser or serve the folder with any local static server.

---

## How to use it

1. Open the app in a browser.
2. Fill in the details required for your Nuvio setup flow.
3. Generate the scraper manifest URL or Comet configuration.
4. Copy the Base64-encoded output when your workflow needs it.
5. Use the Connected Services flow if your setup calls for that path.

Example local preview:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000` and open the page from there.

---

## Configuration notes

Since this is a static web app, most behavior comes from the page itself and the values entered during generation.

If you want to change defaults or labels, check the HTML and any included script file that powers the setup interface.

```text
Configuration location:
- Main HTML page
- Embedded script or linked JavaScript, if present
```

No API keys should be embedded in the generated manifest output.

---

## Requirements

- A modern web browser
- Access to the static app files
- Optional local static server for previewing or testing
- Enough storage for the repository files and generated text output
- A setup path compatible with the Nuvio v2026 workflow

---

## FAQ

**Is installation required?**  
No separate installer is needed. The project is meant to run as a browser-based static web app.

**How are updates delivered?**  
Updates come through the repository and its published build or hosted page.

**Can the generated configuration be adjusted?**  
Yes. Change the app inputs and review the generated manifest or Comet configuration before using it.

**What should I do if the page will not load locally?**  
Verify that you are opening the correct HTML file or serving the folder with a local web server.

**Are API keys written into the manifest?**  
The generated manifest is designed so that API keys are not embedded directly.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
