Gimp Pixel Tile Map Plugin
===========

A GIMP plugin to help with creating tile maps and tile sets for games.

You can create a level map in Gimp (or other image editors), and use this plugin to help with tile de-duplication and tile set optimizing.

This plugin is not meant to replace tile map editors or creates. Instead it aims to provide quick, in-workflow feedback without having to leave GIMP to analyze tiles in another application.

![Plugin showing tile map helper with an image open](https://raw.githubusercontent.com/bbbbbr/gimp-tilemap-helper/master/info/Screenshot.png)


Features
 * Optional Tile deduplication
 * Overlay of Tile ID # & Map on source image
 * Click to highlight matching tiles on source image
 * Estimates of memory usage for storing Tile Set and Map
 * Use Source Layer or Entire image
 * Variable tile size
 * Tile X/Y Flipping detection
 * Export Tile Set as image -> GIMP
 * Ecport Tile Map as C text array -> Clipboard
 * Works with indexed, 24 bit RGB and alpha masks


OS binaries available for:
 * Linux
 * (Coming soon-ish... Windows)


## Usage:

## Quick instructions:

Native compile/install on Linux using below.

```
make

(and then copy to your GIMP plugin folder, depends on version)
* "plugin-gimp-tilemap-helper"

Plug-in folder locations:
 Linux: ~/.gimp-2.8/plug-ins
 Windows: C:\Program Files\GIMP 2\lib\gimp\2.0\plug-ins

```

## Requirements:

## Known limitations & Issues:

## GIMP usage hints:
