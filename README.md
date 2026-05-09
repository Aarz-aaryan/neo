# neo — 3D Printing Research Agent

Finds, evaluates, downloads, validates, and uploads 3D models for printing.

## What Neo does
1. Search Printables, Thingiverse, MakerWorld, MyMiniFactory, Cults3D for models
2. Evaluate quality: triangle count, print time, filament usage, ratings
3. Download via Composio Browser Tool
4. Validate mesh with Blender (non-manifold check, triangle count, dimensions)
5. Upload to Google Drive
6. Report findings

## Architecture
- Neo runs in tmux as profile `neo` (MiniMax-M2.7)
- Blender on Aarz's local machine only — started on-demand via `blender-start.sh`
- Composio Browser Tool for web navigation and downloads
- Google Drive for storage

## Agent Profile
- Profile: `~/.hermes/profiles/neo`
- Spawn: `tmux new-session -d -s neo -x 300 -y 60 'hermes -p neo'`
