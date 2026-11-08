# PaintCast v2026 - browser projection tool 2026

> **PaintCast is a web browser tool for arranging reference images, shaping them to fit a canvas or subject, and preparing a projector-ready cast view in version 2026.**

[![Platform](https://img.shields.io/badge/Platform-web%20browser-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/adamsflorian975/paintcast-browser-reference-hub?style=flat-square)](https://github.com/adamsflorian975/paintcast-browser-reference-hub)

---

<p align="center">
  <a href="https://adamsflorian975.github.io/paintcast-browser-reference-hub/">
    <img src="https://img.shields.io/badge/Download-PaintCast%20Latest-brightgreen?style=for-the-badge" alt="Download PaintCast">
  </a>
</p>

> **[Direct Download - PaintCast v2026](https://adamsflorian975.github.io/paintcast-browser-reference-hub/)**

---

[Download Latest Build](https://adamsflorian975.github.io/paintcast-browser-reference-hub/)

---

## About PaintCast

PaintCast is built for painters who want a browser-based way to position reference material before projecting it onto a real surface. It gives you a simple workspace for combining image layers, adjusting them to match your canvas layout, and preparing a view that can be sent to a projector when you are ready.

It is especially useful when you need to compare sketches, references, and overlays in one place. The tool keeps project slots in local storage, supports cross-tab synchronization, and focuses on quick visual adjustments rather than a complex editing workflow.

---

## Features

- Drag and drop image layers into the workspace
- Compose multiple layers in a single projection setup
- Move, zoom, rotate, and deform layers for better alignment
- Use corner-based correction to handle perspective changes
- Save and revisit project slots with local persistence
- Switch to blackout mode when you want a darker projection view
- View rotated cast output intended for projector use
- Keep open tabs in sync with cross-tab synchronization

---

## Installation

PaintCast runs in a web browser, so setup is lightweight.

1. Clone or download the repository:
   - `git clone https://github.com/adamsflorian975/paintcast-browser-reference-hub.git
2. Open the project in a browser from the downloaded files or serve it with a local web server.
3. Load the app and start arranging your images.

If you prefer a hosted build, use the download link above and open the latest available version in your browser.

---

## Usage

1. Add one or more reference images to the canvas.
2. Position each layer with drag, zoom, rotate, or deformation controls.
3. Use corner adjustment to line the image up with your painting surface.
4. Save the current setup into a project slot.
5. Enable the cast view and send the browser tab to your projector.
6. Turn on blackout mode when you want to reduce visible interface elements.

A typical workflow is to build the composition first, fine-tune alignment second, and then switch to projection mode for the painting session.

---

## Configuration

Most settings are stored locally in the browser.

```text
Storage: localStorage / IndexedDB
Projects: saved in project slots
Sync: shared across open tabs
```

Because the app relies on browser storage, clearing site data may remove saved project state. If you are using multiple tabs, keep them on the same origin so synchronization can work correctly.

---

## Requirements

- A modern web browser
- JavaScript enabled
- Local browser storage support
- Enough screen space for arranging and adjusting layers
- A projector or external display if you plan to use cast output

---

## FAQ

**How do I get started?**  
Open the app in a browser, add your reference images, and begin aligning the layers to your canvas or subject.

**Where are my projects saved?**  
Project data is stored locally in the browser using persistent storage.

**Can I work in more than one tab?**  
Yes. PaintCast supports cross-tab synchronization so open tabs can stay aligned.

**What if the projection is not lined up?**  
Use move, zoom, rotate, deformation, and corner correction tools to refine the fit before casting.

**How do I change settings?**  
Look for browser-based storage and project state controls inside the app. If needed, clear site data to reset local state.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
