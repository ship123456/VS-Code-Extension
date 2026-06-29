# Technical Documentation Generator

## Installation Guide

**Version:** 1.0

**Last Updated:** June 2026

## Table of Contents

- [Introduction](#introduction)
- [System Requirements](#system-requirements)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Manual Installation (.vsix)](#manual-installation-vsix)
- [Verifying the Installation](#verifying-the-installation)
- [Getting Started](#getting-started)
- [Updating the Extension](#updating-the-extension)
- [Uninstalling the Extension](#uninstalling-the-extension)
- [Troubleshooting Installation](#troubleshooting-installation)

## Introduction

This guide explains how to install, verify, update, and remove the Technical Documentation Generator extension in Visual Studio Code.

The extension allows users to generate standardized software documentation directly from the Visual Studio Code environment.

## System Requirements

### Operating Systems

- Windows
- macOS
- Linux

### Software Requirements

For extension users:

- Visual Studio Code 1.80 or later
- Internet connection (required only for Marketplace installation)

For extension developers (optional):

- Node.js
- npm

## Prerequisites

Before installation, ensure that:

- Visual Studio Code is installed.
- A project folder is available (recommended for generating documentation).
- The user has permission to install Visual Studio Code extensions.

## Installation

1. Open Visual Studio Code.
2. Select the **Extensions** icon from the Activity Bar.
3. Search for **Technical Documentation Generator**.
4. Select the extension from the search results.
5. Click **Install**.
6. Restart Visual Studio Code if prompted.

## Manual Installation (.vsix)

If access to the Visual Studio Code Marketplace is unavailable, the extension can be installed manually using a VSIX package.

1. Download the extension's `.vsix` file.
2. Open Visual Studio Code.
3. Open the **Extensions** view.
4. Select the **More Actions (···)** menu.
5. Choose **Install from VSIX...**
6. Select the downloaded `.vsix` file.
7. Restart Visual Studio Code if prompted.

Manual installation is commonly used in enterprise or secure environments where Marketplace access is restricted.

## Verifying the Installation

After installation:

1. Open the Command Palette.

**Windows / Linux**

```text
Ctrl + Shift + P
```

**macOS**

```text
Cmd + Shift + P
```

2. Search for one of the available commands:

- Generate README
- Generate User Guide
- Generate API Documentation

3. If the commands appear, the extension has been installed successfully.

## Getting Started

After installation:

1. Open an existing project or create a new workspace.
2. Launch the Command Palette.
3. Select the required documentation template.
4. Enter the requested project information.
5. Generate the documentation.
6. Save the generated Markdown file.

## Updating the Extension

To update the extension:

1. Open the **Extensions** view.
2. Locate **Technical Documentation Generator**.
3. Click **Update** if a newer version is available.
4. Restart Visual Studio Code if required.

## Uninstalling the Extension

To remove the extension:

1. Open the **Extensions** view.
2. Locate **Technical Documentation Generator**.
3. Click **Uninstall**.
4. Restart Visual Studio Code if prompted.

## Troubleshooting Installation

| Issue | Solution |
|--------|----------|
| Extension not found | Verify the extension name and search again. |
| Installation failed | Check your internet connection and try again. |
| Commands not available | Restart Visual Studio Code and reopen the workspace. |
| Extension not activated | Ensure Visual Studio Code meets the minimum version requirement. |
| Installation incomplete | Reinstall the extension from the Extensions Marketplace. |
| VSIX installation blocked | Verify that your organization allows local extension installation or contact your system administrator. |
