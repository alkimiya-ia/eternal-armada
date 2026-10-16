# Eternal Armada

Project repository for Eternal Armada: Spanish historical heavy/power metal releases, production guidance, release planning, channel strategy, analytics, and historical research notes.

## Repository structure

- `releases/` — release records, production bibles, metadata and campaign decisions.
- `strategy/` — YouTube, SEO and playlist strategy.
- `production/` — shared visual and video-production conventions.
- `analytics/` — durable decisions and Ask Studio analysis.
- `audio/` — final lossless masters.

## Audio masters

WAV and FLAC masters are tracked through Git LFS rules in `.gitattributes`.

When adding masters, use an LFS-capable Git workflow so the repository stores LFS pointers instead of committing large audio files directly.
