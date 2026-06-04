# Stack To Nearby Chests

A [Stardew Valley](https://www.stardewvalley.net/) mod that adds a button to your inventory screen to quickly stack all matching items from your inventory into nearby chests.

## Features

- Adds a stack button to the inventory tab of the game menu
- Stacks items from your inventory into any chest within a configurable radius
- Only stacks items if the chest already contains at least one of that item (matching type and quality)
- Plays a sound effect when items are moved

## Requirements

- [SMAPI](https://smapi.io/) 2.0 or later

## Installation

1. Install SMAPI if you haven't already
2. Download the latest release and extract it into your `Stardew Valley/Mods` folder
3. Launch the game through SMAPI

## Usage

Open your inventory (E by default), then click the stack button that appears to the right of your inventory panel. All eligible items will be moved into chests within the configured radius.

## Configuration

After running the mod once, a `config.json` file will be created in the mod folder:

```json
{
  "Radius": 5
}
```

| Option | Default | Description |
|--------|---------|-------------|
| `Radius` | `5` | Tile radius around the player to search for chests |

## Source Code

[GitHub](https://github.com/stebaker92/StackToNearbyChests)
