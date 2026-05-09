# Dracouroboros Downtime Engine

A comprehensive downtime management system for D&D 5e on Foundry VTT v12+.

## Features

- **Downtime Hub** — central dashboard for all downtime activities
- **Crafting** — blueprint-based item crafting with material tracking
- **Training** — skill and language training tracker
- **Resources** — resource ledger with income/expense logging
- **Faction Relations** — track relationships with factions and NPCs
- **Boons & Blessings** — award and track special boons
- **Monster Harvesting** — harvest parts from defeated creatures with skill checks
- **History** — full log of all downtime activities
- **GM Tools** — request dashboard, star tracker, complications, weekly summary, treasure tables, and shop generator
- **Open for Player** — GM can push any player's hub directly to their screen

## Installation

### From Foundry (once published)
1. Open Foundry VTT → Add-on Modules → Install Module
2. Paste the manifest URL: `https://github.com/YOURUSERNAME/dracouroboros-downtime/releases/latest/download/module.json`
3. Click Install

### Manual Installation
1. Download the latest `module.zip` from the Releases page
2. Extract to your Foundry `Data/modules/` folder
3. The folder must be named `dracouroboros-downtime`
4. Enable the module in your world: Game Settings → Manage Modules

## Usage

### Opening the Hub
- **GM**: Click the 🐉 dragon icon in the Scene Controls toolbar (top left), **or** press `Alt+D`
- **Players**: The GM pushes the hub to your screen — it will open automatically

### Sending the Hub to a Player
1. Open the Downtime Hub as GM
2. Select the player's character in the dropdown
3. Click **🖥 Open for Player**
4. The hub opens instantly on that player's screen, showing only their Character Tools

### Player Permissions
Players need **Observer** permission on the module (not the macro). No hotbar setup required.

## Compatibility

- Foundry VTT: v12, v13
- D&D 5e System: 3.0.0+

## License

MIT — free to use, modify, and distribute.
