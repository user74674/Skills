# Source

- Upstream repository: https://github.com/Vincentwei1021/video-shotcraft
- Upstream path: `` (repo root — the whole repository is the skill, as upstream recommends)
- Installed skill name: `video-shotcraft`
- License: Apache-2.0
- Installed: 2026-11-05 (depth-1 clone of `main`; `.git` excluded)

This file is provenance metadata added by the installer; it is not part of the skill.

Contents: `SKILL.md` (entry point), `references/` (production pipeline, 124 shot recipe cards in `references/shots/`, sequences, aesthetic rules, music-beat-sync, sound design, Freesound SFX sourcing, JianYing export, social publishing, workbench contract, final review), `demos/` (Remotion reference implementations per shot card), `template/` (runnable complete video template, Ink Press), `assets/` (reusable Remotion components in `assets/lib`, page-capture + Freesound scripts in `assets/scripts`, 5 BGM tracks in `assets/audio/bgm`), `gallery/` (static shot-gallery viewer; sample MP4s are fetched on demand via `gallery/fetch-media.sh`), `workbench/` (post-delivery CapCut-style browser editor), `jianying-export/`, `publish/` (Upload-Post), `shot-polish/`, `agents/`.

Run-time extras this install does not include: demo smoke tests required deps (`@remotion/motion-blur`), gallery sample MP4s (fetched by script), Freesound SFX (downloaded per project), and the Remotion headless Chrome (downloaded by Remotion on first render).
