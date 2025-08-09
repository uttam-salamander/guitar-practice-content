# Guitar Practice Content Repository

This repository contains song data for the Guitar Practice app.

## Structure

- `manifests/` - Master index files
- `songs/` - Individual song JSON files organized by difficulty
- `exercises/` - Practice exercises organized by type
- `assets/` - Supporting files (chord diagrams, etc.)

## Song Data Format

Each song includes:
- Complete metadata (title, artist, year, etc.)
- YouTube backing track with fallback options
- Detailed section breakdown with timestamps
- Chord diagrams with fingering patterns
- Practice guides for different skill levels
- Comprehensive tagging for discoverability

## Usage

This data is fetched by the Guitar Practice app via GitHub's raw file API. The master index provides efficient browsing and filtering capabilities.
