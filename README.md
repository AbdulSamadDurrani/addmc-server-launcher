# AddMC - Loader and Update Utility 2026

> **Web-based launcher for setting up Minecraft Bedrock servers and opening configured servers from your browser.**

[![Loader](https://img.shields.io/badge/Type-Loader-blue?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-Web%20browser-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/henry-taylores548/addmc-server-launcher?style=flat-square)](https://github.com/henry-taylores548/addmc-server-launcher)

---

<p align="center">
  <a href="https://henry-taylores548.github.io/addmc-server-launcher/">
    <img src="https://img.shields.io/badge/Download-AddMC%20Loader-brightgreen?style=for-the-badge" alt="Download AddMC Loader">
  </a>
</p>

> **[Download AddMC Loader](https://henry-taylores548.github.io/addmc-server-launcher/)**

---

[Download Latest Build](https://henry-taylores548.github.io/addmc-server-launcher/)

---

## Overview

AddMC acts as a web-based server hub for Minecraft Bedrock. It gives you a straightforward way to prepare server entries, modify their displayed information, and keep the relevant details organized before opening a configured server.

Because the launcher operates in a browser, no conventional desktop installer is needed. Use the web interface to set up a server, inspect or edit its details, and then activate the available action to open it directly.

---

## Available Features

- Configure Minecraft Bedrock server entries with a single action
- Modify server information from the browser interface
- Use the launcher without installing a native desktop application
- Open configured servers directly through the server hub
- Keep prepared server entries accessible from one place
- Lightweight interface built with HTML
- Use the published web version
- Reconfigure entries whenever server details are updated

---

## Getting Started

### Use the Hosted Version

1. Open the [AddMC web build](https://henry-taylores548.github.io/addmc-server-launcher/).
2. Choose an existing server entry or create the entry you want to prepare.
3. Change the visible server information where necessary.
4. Select the launch or open control for the configured server.

### Use a Local Checkout

Download the repository with Git, then move into its directory:

```bash
git clone https://github.com/henry-taylores548/addmc-server-launcher.git
cd REPO
```

Open the project's `index.html` file in a web browser. When direct local file access is unsuitable, run a static web server for the repository directory and visit the local address it provides.

### Example Configuration Flow

The usual process for preparing a server entry looks like this:

```text
1. Choose a Minecraft Bedrock server
2. Update its displayed information
3. Save or apply the configuration
4. Open the configured server
```

---

## Distribution and Updates

AddMC is delivered as a browser application, so it does not use separate desktop release channels.

| Channel | Purpose | Access |
| --- | --- | --- |
| Latest | Current published browser build | [Open AddMC](https://henry-taylores548.github.io/addmc-server-launcher/) |
| Manual | Local copy used for testing or customization | Clone the [repository](https://github.com/henry-taylores548/addmc-server-launcher) |

Reload the hosted build after an update to use the newest published interface. A local checkout is updated separately by pulling the latest repository changes.

---

## Troubleshooting Guide

### The hosted page will not load

Verify the published URL and check that the browser can reach the network. If the interface still fails to appear, reload the page or test it in another current browser.

### Edited server information is not applied

Ensure the changed fields were saved or applied before selecting the open action. If previous values remain, reload the page and enter the information again.

### Opening the server has no effect

A browser may stop a new tab or external action from opening. Accept the applicable browser prompt and retry. Confirm as well that all required server details have been entered.

### The local version differs from the hosted build

Check that the clone completed successfully and that you opened the intended HTML entry point. If opening the file directly creates problems, serve the repository through a local static web server.

### An update is not showing

Refresh the published page and clear its cached browser data if needed. Local repositories do not update themselves; pull the newest changes from the repository.

---

## Frequently Asked Questions

### Is AddMC a Minecraft Bedrock server installer?

No. AddMC is a browser-based launcher and configuration hub. It prepares server information and lets you open configured servers, but it is not presented as a tool for installing servers.

### Does AddMC save server information on the device?

The project identifies editable server information but does not define a permanent storage mechanism. Handle entered details according to the behavior of the current hosted build.

### Will the hosted version update by itself?

The published build shows the currently hosted version when loaded. A local copy must be updated manually from the repository.

### Can an older version be restored?

A local checkout can use an earlier repository revision when one is available. The hosted address continues to serve the currently published version.

### Where can I find logs?

The project does not specify a dedicated log directory. For page-level problems, inspect the browser's developer console.

### What platforms can run AddMC?

AddMC is intended for use in a web browser. Minecraft Bedrock support depends on the configured server and the environment used to open that server.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
