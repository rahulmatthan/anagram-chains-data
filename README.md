# Anagram Stack - Chain Data Repository

This repository contains anagram chain data for the Anagram Stack iOS game.

## Structure

- `manifest.json` - Master list of all available chains
- `chains/` - Individual chain JSON files

## Usage

The iOS app fetches the manifest from GitHub and downloads new chains automatically.

## Adding Chains

1. Use the macOS Admin App to create chains
2. Click "Export All Chains" to save to this repository
3. Commit and push changes to GitHub
4. iOS app will auto-update on next launch
