# Source

- Upstream repository: https://github.com/harry0703/MoneyPrinterTurbo
- Upstream path: `docs/skill/SKILL.md`, `docs/skill/mpt_agent.py`
- Installed skill name: `moneyprinterturbo-video`
- License: MIT
- Installed: 2026-11-05 (skill version 1.3.2)

This file is provenance metadata added by the installer; it is not part of the skill.

Notes: this is the MoneyPrinterTurbo project's own official agent skill. The MoneyPrinterTurbo application itself is NOT vendored — at run time the adjacent `mpt_agent.py` installs the app (via `uv`) under the user's home directory, reuses `config.toml`, drives generation end to end, and returns the finished MP4 path. It needs an LLM provider API key and (for stock footage) a Pexels key; default voice-over is Edge TTS (free); the default output is one 9:16 portrait video unless parameters say otherwise.
