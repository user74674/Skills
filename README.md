# Skills

**435 agent skills** for [OpenCode](https://opencode.ai), installed 2026-11-05 (394) and 2026-11-06 (41).

OpenCode discovers everything automatically: drop this folder as `.opencode/skills/`
into any workspace and each `<name>/SKILL.md` becomes an available skill.

## What's inside

| What | Where |
| --- | --- |
| The skills | `<name>/SKILL.md` + their structured folders (`references/`, `assets/`, `scripts/`, demos, companions) |
| Library manifest by source | [`SKILLS.md`](SKILLS.md) |
| Ranked YouTube-explainer playbook + scenario recipes | [`SKILLS-YOUTUBE.md`](SKILLS-YOUTUBE.md) |
| Provenance per skill | `<name>/SOURCE.md` (upstream repo, path, license) |

Coverage: Remotion official (13), Motion (1), GSAP (8), Motion Canvas (3), Three.js/WebGL (14), NixieFX (2), FrankX motion design (5), AI Dev Kit (56), iart-ai motion packs (56), MengTo/Skills (180 — web explainers, illustration, production workflows), emilkowalski/skills (17 — animation/UX craft), story craft (24), YouTube packaging & growth (11), code-video direction (1), plus two 2026-11-05 story engines: `video-shotcraft` (Apache-2.0 — 124 Remotion shot recipe cards + capture-to-MP4 pipeline) and `moneyprinterturbo-video` (MIT — official topic→MP4 agent skill vendored from harry0703/MoneyPrinterTurbo). Fourth pass (2026-11-06): explainer-video direction and craft — `huashu-motion`, `rossark-motion-skill`, `take-one`, `explainroo`, `earshot` + `real-sound`, HeyGen `hyperframes` pack (9), `humanizer` — plus 25 software-engineering process skills from addyosmani/agent-skills.

See `SKILLS.md` for the complete source-by-source list and the story-engine ranking.

## Licenses

Each skill keeps its upstream license; the per-folder `SOURCE.md` records it.
Highlights: `hyperframes` pack Apache-2.0, `video-shotcraft` Apache-2.0, `moneyprinterturbo-video` MIT (app itself installed at run time), Remotion skills MIT (Remotion render engine has its own license — free for individuals/small teams).

## Notes

- Fonts/audio/data payloads ship with skills only where they are self-contained; heavy media (demo MP4s, SFX) is fetched on demand at run time.
- Sensitive data: none of the skills contain API keys; cloud-connected skills ask for keys at run time.
