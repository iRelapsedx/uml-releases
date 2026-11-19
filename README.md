# UML — Universal Mod Loader: releases

This repository holds the Windows installers for **UML (Universal Mod Loader)**.

## Install

1. Open [Releases](https://github.com/iRelapsedx/UML/releases/latest) and download `UML_<version>_x64-setup.exe`.
2. Run it. It installs UML for your Windows account only (no administrator rights needed) and adds it to the Start menu.

The installer isn't code-signed yet, so Windows SmartScreen may say it's from an unknown publisher. If you downloaded it from this page, choose **More info → Run anyway**.

## Updates

Installed copies check this page for a newer version (you can switch this off in Settings → Updates). You see what's new and decide when to install. An update is installed only if it carries UML's signature; your library, mods and settings are kept.

Each release has three files:

| File | What it is |
|---|---|
| `UML_<version>_x64-setup.exe` | The installer |
| `UML_<version>_x64-setup.exe.sig` | Its update signature |
| `latest.json` | What installed copies read to find the newest version |
