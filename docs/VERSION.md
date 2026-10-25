# PD2 S14 Project — VERSION

| Field | Value |
|---|---|
| Project version | **v0.9.0** |
| Doc schema | 1 |
| Last updated | 2026-10-25 |
| Working branch | `arena/734a136e-pd2-s14` |
| Main sync | Use a PR from the working branch; never push directly to `main` |
| Game | Project Diablo 2 — Season 14 Hardcore |
| Character | MAVOmusicHC — Level 77 Throw Barbarian; Act 1 Rogue mercenary |

## Version history

| Version | Date | Headline |
|---|---|---|
| v0.1.0 | 2026-10-25 | Bootstrap, vision check and folder/push protocol |
| v0.2.0 | 2026-10-25 | Character/skill and equipped-gear screenshots recorded |
| v0.3.0 | 2026-10-25 | Charms recorded; Hell resistance interpretation corrected |
| v0.4.0 | 2026-10-25 | Unique Items inventory tab (23 screenshots/items documented) |
| v0.4.1 | 2026-10-25 | Handoff/version/context/protocol reconciled; image vision re-verified |
| v0.5.0 | 2026-10-25 | Set Items inventory tab (26 screenshots transcribed); trade and swap triage |
| v0.6.0 | 2026-10-25 | Sortables inventory tab (31 screenshots transcribed); gear, trade and base triage |
| v0.7.0 | 2026-10-25 | Misc tab overview recorded; stack identities flagged for tooltip follow-up |
| v0.8.0 | 2026-10-25 | Runes tab counts recorded; 147 total visible, rune mapping confidence noted |
| **v0.9.0** | **2026-10-25** | Gems tab counts recorded; 116 counted gems including 86 perfect gems |

## Milestones

| # | Milestone | Status |
|---|---|---|
| M1 | Verify image-reading ability | ✅ DONE |
| M2 | `01 - Character + Skill Tree` and `02 - Equipped Items` | ✅ DONE |
| M3 | `03 - Charms` | ✅ DONE |
| M4 | `04 - Inventory` | ⏳ IN PROGRESS — Unique Items, Set Items, Sortables, Misc, Runes and Gems tabs reviewed; remaining tabs not read |
| M5 | `05 - Merc Items` and Item Filter | ⏸ NOT STARTED |
| M6 | Farm plan for elite crafting weapon bases (self + merc) within practical Hell A2 Arcane Sanctuary limit | ⏸ Draft notes exist; final plan pending inventory/merc review |
| M7 | Item filter tuning/custom filter | ⏸ NOT STARTED |
| M8 | Sorted XLSX inventory/trade-price sheet | ⏸ NOT STARTED; needs remaining inventory data and pricing basis |
| M9 | Inventory-to-equipped swaps | ⏳ Partial candidates in inventory docs; validate after remaining inventory/merc tabs |

## Current checkpoint

- This session is on the active Arena branch `arena/734a136e-pd2-s14`, based on the current main snapshot `59ec377fc882e715f9e10bae2e18333f03c2bd77`.
- Gems Tab is transcribed in `docs/04F_Inventory_Gems.md`: 116 counted gems, including 86 perfect gems. Counts are clear; quality/type mapping is medium-high confidence from standard icons and grid order.
- Per the user's rule, the next Inventory tab is **MF Tab** and must not be read until the user confirms this push/checkpoint.
- After confirmation, continue with one Inventory tab at a time, update the three handoff ledgers, push the branch, and sync `main` through a PR before reporting.
