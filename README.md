# Skyblock Data Repository

![Collections Workflow](https://github.com/outin1337/SkyblockConstant/actions/workflows/auto-update-skyblock-collections.yml/badge.svg)
![Skills Workflow](https://github.com/outin1337/SkyblockConstant/actions/workflows/auto-update-skyblock-skills.yml/badge.svg)
![Items Workflow](https://github.com/outin1337/SkyblockConstant/actions/workflows/auto-update-skyblock-items.yml/badge.svg)

![Collections Last Run](https://img.shields.io/github/actions/workflow/status/outin1337/SkyblockConstant/auto-update-skyblock-collections.yml?label=collections%20last%20run&style=flat)
![Skills Last Run](https://img.shields.io/github/actions/workflow/status/outin1337/SkyblockConstant/auto-update-skyblock-skills.yml?label=skills%20last%20run&style=flat)
![Items Last Run](https://img.shields.io/github/actions/workflow/status/outin1337/SkyblockConstant/auto-update-skyblock-items.yml?label=items%20last%20run&style=flat)

![Update Frequency](https://img.shields.io/badge/update-every%205%20minutes-blue)
![JSON Valid](https://img.shields.io/badge/format-JSON-green)

This repository contains JSON files with Skyblock data from Hypixel. The data is automatically updated every 5 minutes via GitHub Actions.

## Files

- `skyblock_collections.json` – Contains all Skyblock collection data.
- `skyblock_items.json` – Contains all Skyblock item data.
- `skyblock_skills.json` – Contains all Skyblock skill data.

## Updates

Data is fetched from the [Hypixel API](https://api.hypixel.net/) every 5 minutes using GitHub Actions to ensure it stays up-to-date.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
