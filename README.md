# DeluxeWand

A builder's-wand plugin for Spigot/Paper. Right-click with a wand and
the plugin extends or fills blocks of the same type in the direction
you're looking — handy for putting up walls, floors and bridges fast.

## Features

- Multiple configurable wand types (`wands.yml`)
- Custom wand items, names, lore and limits per wand
- WorldGuard region awareness (soft dependency)
- BentoBox island awareness (soft dependency)
- Configurable messages (`messages.yml`)

## Requirements

- Spigot / Paper (built against API 1.13)
- Java 8 or newer
- Optional: WorldGuard, BentoBox

## Commands

- `/deluxewand` (alias: `/builderswand`) — main wand command (give wand, reload, etc.)

## Installation

1. Drop `DeluxeWand.jar` into your server's `plugins/` folder.
2. Start the server once to generate the default configuration.
3. Edit `config.yml`, `wands.yml` and `messages.yml` in
   `plugins/DeluxeWand/`, then reload.

## Configuration

- `config.yml` — global behavior toggles
- `wands.yml` — define each wand type (item, max blocks per use, etc.)
- `messages.yml` — all chat messages
