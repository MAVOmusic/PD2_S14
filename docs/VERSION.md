# PD2 S14 Project — VERSION

| Field | Value |
|---|---|
| Project version | **v0.15.1** |
| Doc schema | 1 |
| Last updated | 2026-10-25 |
| Working branch | `arena/2ad22dfd-pd2-s14` |
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
| v0.9.0 | 2026-10-25 | Gems tab counts recorded; 116 counted gems including 86 perfect gems |
| v0.10.0 | 2026-10-25 | MF tab (3 items) transcribed; sale and Hardcore swap priorities recorded |
| v0.11.0 | 2026-10-25 | GF tab (8 items) transcribed; +260% combined visible GF and trade triage |
| v0.12.0 | 2026-10-25 | Maps tab reviewed; map ownership/item identities not verifiable from screenshots |
| v0.13.0 | 2026-10-25 | Ubers tab overview documented; item identities and values await tooltip screenshots |
| v0.14.0 | 2026-10-25 | Duplicates/Good Corruption tab recorded; final Inventory tab complete |
| v0.15.0 | 2026-10-25 | Act 1 Rogue mercenary gear/stats recorded; safe gear-swap triage |
| **v0.15.1** | **2026-10-25** | Unidentified-icon workbook; charm/Purity/Ramfodder corrections; Runs 1–10 scaffolding |

## Milestones

| # | Milestone | Status |
|---|---|---|
| M1 | Verify image-reading ability | ✅ DONE |
| M2 | `01 - Character + Skill Tree` and `02 - Equipped Items` | ✅ DONE |
| M3 | `03 - Charms` | ✅ Current equipped charm loadout transcribed; stats dependency clarified |
| M4 | `04 - Inventory` | ✅ SOURCE TABS REVIEWED — all 11 inventory tabs processed; several overview-only tabs still need hover details for exact item ID/price |
| M5 | `05 - Merc Items` and Item Filter | ⏳ Merc Items DONE; Item Filter unread pending explicit user instruction |
| M6 | Farm plan for elite crafting weapon bases (self + merc) within practical Hell A2 Arcane Sanctuary limit | ⏸ Draft notes exist; final plan pending inventory/merc review |
| M7 | Item filter tuning/custom filter | ⏸ NOT STARTED — source unread pending authorization |
| M8 | Sorted XLSX inventory/trade-price sheet | ⏸ NOT STARTED; needs remaining item details and pricing basis |
| M9 | Inventory-to-equipped swaps | ⏳ Candidates documented; final recommendations pending corrected current-state assumptions and player identification sheet |

## Current checkpoint

- This session is on the active Arena branch `arena/2ad22dfd-pd2-s14`, based on main commit `b3b98678aa913fedd67f09e3191daf8c09e516ed` (Merc Items PR #12 merged).
- `docs/Unidentified_Icons_and_Items.xlsx` lists 108 unresolved inventory/skill-icon entries, with source tab/location and a blank column for the player's identification.
- Player correction: all 24 charms in the Charms tab are currently equipped; their effects are already included in the character stats. Previous equip/bench/sell charm advice and incremental charm-stat calculations are withdrawn pending a fresh stat comparison.
- Player correction: Purity is kept on Mahala for Prayer healing. Keep it until the player no longer relies on that healing; Ramfodder is a bolt quiver and requires a crossbow, so it cannot be used with the current bow.
- `Runs/Run 1` through `Runs/Run 10` are scaffolded for up to 15 images each. Read only the Run the player explicitly names.
- Item Filter remains unread. Do not proceed until the player explicitly authorizes it; current next step is to receive/follow up on the completed identification workbook before final swap/trade conclusions.
