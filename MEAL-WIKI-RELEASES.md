# Meal.wiki Platform Release Channel

This branch is reserved for public WordPress update manifests and installable packages for Meal.wiki Platform.

## Branch

- `meal-wiki-platform`

## Planned files

- `update.json`: current WordPress update manifest
- `packages/<version>/package.json`: chunked package descriptor
- `packages/<version>/*.b64`: versioned package chunks
- `checksums/`: SHA-256 records

The plugin source remains private. WordPress updates must validate the SHA-256 checksum before installation. Automatic updates remain disabled by default.
