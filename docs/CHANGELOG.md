# PD2 S14 Project — CHANGELOG

Newest first. Each entry records the scope, deliverables, and synchronization status. Prices elsewhere are estimates, not live trade-site quotes.

---

## v0.4.1 — 2026-10-25

### Handoff / protocol reconciliation
- Re-verified that this session can read the PNG images (opened `01 - Character + Skill Tree/Stats - No Buff.PNG`).
- Reconciled stale version/context/protocol documents with the actual Arena session branch: `arena/cb987047-pd2-s14`, based on `fd15029a02072770a6d6dc8181262bd6052b97fd` (`v0.4.0`).
- Clarified that changes are committed and pushed to the fixed working branch; `main` synchronization must happen through a PR, never by direct push.
- No new inventory tab was processed. The user's requested stop-and-confirm checkpoint before the next Inventory tab is maintained.
- The prior chat transcript reported that 24 Set Items screenshots had been opened before the context-limit interruption, but no Set Items findings were saved. Do not treat them as transcribed; re-read from source after the user confirms.

### Sync status
- This documentation correction is being committed/pushed on `arena/cb987047-pd2-s14`; main sync is via PR.

---

## v0.4.0 — 2026-10-25

### Read / added
- `MAVOmusicHC - Stats - V1.0/Images/MAVOmusicHC - 04 - Inventory/Unique Items Tab/` — 23 screenshots transcribed in `docs/04A_Inventory_Uniques.md`.
- The screenshots' page counters suggest the in-game tab may contain more uniques than the 23 screenshots supplied; this uncertainty is recorded in the item document.
- Added unique-item swap candidates and a first-pass trade-priority list. Values are estimates with confidence labels, not verified live listings.

### Prior branch status
- The previous checkout recorded this as v0.4.0. This session's branch is a fresh Arena branch based at the v0.4.0 commit; see v0.4.1 for current branch/sync handling.

---

## v0.3.0 — 2026-10-25

### Player correction (applied)
- Character-sheet resistances are already Hell-applied: Fire 49 / Cold 80 (true 99) / Light 75 (true 83) / Poison 58.
- Retracted v0.2.0's “resists are the crisis” interpretation. Fire is 26 below cap and poison 17 below; charms can address both. Cold/light are overcapped by 19/8 points.
- Belt and boots should be evaluated as mobility/IAS/leech/life upgrade slots, not automatically as resistance slots.

### Read / added
- `MAVOmusicHC - Stats - V1.0/Images/MAVOmusicHC - 03 - Charms/` — all 24 files (14 SC, 6 GC, 4 LC).
- `docs/03_Charms.md` — charm table, owned-charm resistance recommendation, overcap analysis and estimated values.
- Findings recorded there include no torch/annihilus/Gheed's/skiller; an SC All Res 5% + 4% MF; and an LLD light-damage/resistance SC that should not be vendored.

---

## v0.2.0 — 2026-10-25

### Read / added
- `01 - Character + Skill Tree/` — 5 screenshots; `02 - Equipped Items/` — 12 screenshots.
- `docs/02_Character_And_Gear_Snapshot.md` — transcribed stats/skills/equipped gear and initial farm notes.
- Skill-name/icon uncertainties are marked for verification; trade values are estimates.

---

## v0.1.0 — 2026-10-25

### Added
- Repository inventory: 161 PNG screenshots in six top-level source folders plus `Item Filter/Hiim_Crafting_Barbarian_Focused.filter`.
- Vision check passed; this chat can read the screenshots.
- Initial folder batching and save/push protocol.
