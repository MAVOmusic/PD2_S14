# PD2 S14 Project — CHANGELOG

All changes are append-only, newest first. Every entry states what was read, what was produced, and what was pushed.

---

## v0.2.0 — 2026-10-25

### Read (folder batch 1 of 6)
- `MAVOmusicHC - Stats - V1.0/Images/MAVOmusicHC - 01 - Character + Skill Tree/` — all 5 files
  - `Stats - No Buff.PNG`, `Stats - With Buff.PNG`, `C + Combat Masteries.PNG`, `C + Combat Skills.PNG`, `C + Warcries.PNG`
- `MAVOmusicHC - Stats - V1.0/Images/MAVOmusicHC - 02 - Equipped Items/` — all 12 files
  - Weapons 1–2, Helm, Armor, Belt, Boots, Gloves, Amulet, Rings 1–2, BO Stick 1–2

### Added
- `docs/02_Character_And_Gear_Snapshot.md` — full transcribed stats, skill-point read, equipped gear table, swap-slot (BO stick) read, per-item value estimate, first-pass resist-hole analysis, and a draft farming plan for a Throw Barb capped at Hell A2 Arcane Sanctuary.
- `docs/VERSION.md`, `docs/CHANGELOG.md`, `docs/00_CONTEXT_BLOCK.md`, `docs/WORK_PROTOCOL.md`.

### Notes / corrections carried forward
- Skill-tree point numbers are read from icon badges (blue = hard points, values shown while Battle Command/BO buff active). Skill **names** per icon are best-effort and flagged `⚠ verify` in the snapshot; tooltip screenshots would settle them.
- Fanged Helm shows **Defense 16** — flagged as a suspicious low base (cracked/low-quality base used for the craft), which matters if re-crafting.
- Prices are **estimates** (no trade-site access from this sandbox); each row carries a confidence tag.

### Pushed
- `arena/360df353-pd2-s14` and mirrored to `main`.

---

## v0.1.0 — 2026-10-25

### Added
- Repository audit: 161 PNG screenshots in 6 top-level folders + 1 item filter file (`Item Filter/Hiim_Crafting_Barbarian_Focused.filter`).
- **Vision check: PASSED** — this chat reads images natively (verified on `Stats - No Buff.PNG`).
- Working protocol (`docs/WORK_PROTOCOL.md`): read max **2 folders per turn**, then stop and wait for the user's go-ahead; write version/changelog/context updates and **git push before reporting results**, so nothing is ever lost if the chat dies.

### Pushed
- `arena/360df353-pd2-s14` + mirrored to `main`.
