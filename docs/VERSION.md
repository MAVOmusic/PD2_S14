# PD2 S14 Project — VERSION

| Field | Value |
|---|---|
| Project version | **v0.4.1** |
| Doc schema | 1 |
| Last updated | 2026-10-25 |
| Working branch | `arena/cb987047-pd2-s14` |
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
| **v0.4.1** | **2026-10-25** | Handoff/version/context/protocol reconciled to this Arena branch; image vision re-verified |

## Milestones

| # | Milestone | Status |
|---|---|---|
| M1 | Verify image-reading ability | ✅ DONE (reconfirmed this session) |
| M2 | `01 - Character + Skill Tree` and `02 - Equipped Items` | ✅ DONE |
| M3 | `03 - Charms` | ✅ DONE |
| M4 | `04 - Inventory` | ⏳ IN PROGRESS — only `Unique Items Tab` has a saved transcription; Set Items is next after user go-ahead |
| M5 | `05 - Merc Items` and Item Filter | ⏸ NOT STARTED |
| M6 | Farm plan for elite crafting weapon bases (self + merc) within practical Hell A2 Arcane Sanctuary limit | ⏸ Draft notes exist; final plan pending inventory/merc review |
| M7 | Item filter tuning/custom filter | ⏸ NOT STARTED |
| M8 | Sorted XLSX inventory/trade-price sheet | ⏸ NOT STARTED; needs complete inventory data and pricing basis |
| M9 | Inventory-to-equipped swaps | ⏳ Partial candidates in `04A_Inventory_Uniques.md`; validate after remaining inventory/merc tabs |

## Important current state

- User requested no more than two source folders per work batch, a saved version/changelog/context update plus push before reporting, and an explicit stop after each Inventory tab until the user confirms the next tab.
- This turn verified vision on `Stats - No Buff.PNG` only; no new item folder/tab was processed.
- Current source baseline is the main snapshot at `fd15029a02072770a6d6dc8181262bd6052b97fd` (`v0.4.0`). Session work must stay on `arena/cb987047-pd2-s14`; main synchronization must be done through a PR, not a direct push.
