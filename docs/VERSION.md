# PD2 S14 Project — VERSION

| Field | Value |
|---|---|
| Project version | **v0.26.0** |
| Doc schema | 1 |
| Last updated | 2026-10-26 |
| Working branch | `arena/56066609-pd2-s14` |
| Main sync | Use a PR from the working branch; never push directly to `main` |
| Game | Project Diablo 2 — Season 14 Hardcore |
| Character | MAVOmusicHC — Level 79 Throw Barbarian; Act 1 Rogue mercenary |

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
| v0.15.1 | 2026-10-25 | Unidentified-icon workbook; charm/Purity/Ramfodder corrections; Runs 1–10 scaffolding |
| v0.16.0 | 2026-10-25 | First 15 icons identified; Misc inventory and Recipes wiki reference updated |
| v0.17.0 | 2026-10-25 | U-016–U-053 identified; Craft Infusions and map Wiki lookup added |
| v0.18.0 | 2026-10-25 | U-054–U-074 identified; map-modification uses documented; unresolved tracker reduced to U-075–U-108 |
| **v0.26.0** | **2026-10-26** | Reviewed Run 2 images 1–15; found Anvilguard Strap Heavy Bolts and documented a second Purity crossbow trial |
| v0.25.0 | 2026-10-26 | Recorded level-79 stat panels, Duriel clear report, and checked Run 2 before the item batch arrived |
| v0.24.0 | 2026-10-26 | Recorded ethereal Lacerator + Wraith Flight as current Throw Barb weapons, recent trade/purchases, and post-swap testing caveats |
| v0.23.0 | 2026-10-26 | Recorded player-equipped Run 1 Barb package and Sigon merc belt; added vendor/trade queue and updated current gear records |
| v0.22.0 | 2026-10-26 | Reassessed Throw Barbarian and merc gear; corrected Sigon's set/Wrap synergy, compared Tal's/Swiftwind/Blunt, and documented reversible Purity-crossbow/Ramfodder test |
| v0.21.0 | 2026-10-25 | Exhaustive item-by-item action matrix across equipped gear, all documented inventory tabs and Run 1; uncertainties sourced by location |
| v0.20.0 | 2026-10-25 | Run 1 (23 authorized images) gear/trade plan; community workbook price guidance; merc Smoke/Tal's test; stale swap advice corrected |
| v0.19.0 | 2026-10-25 | U-075–U-108 identified; all 108 IDs complete; Barbarian skill-tree allocation explained from PD2 Wiki |

## Milestones

| # | Milestone | Status |
|---|---|---|
| M1 | Verify image-reading ability | ✅ DONE |
| M2 | `01 - Character + Skill Tree` and `02 - Equipped Items` | ✅ DONE |
| M3 | `03 - Charms` | ✅ Current equipped charm loadout transcribed; stats dependency clarified |
| M4 | `04 - Inventory` | ✅ All 11 inventory tabs processed; all 108 icon IDs identified (tooltip/quantity/value follow-up remains where noted) |
| M5 | `05 - Merc Items` and Item Filter | ⏳ Merc Items DONE; Item Filter unread pending explicit user instruction |
| M6 | Farm plan for elite crafting weapon bases (self + merc) within practical Hell A2 Arcane Sanctuary limit | ⏸ Draft notes exist; final plan pending inventory/merc review |
| M7 | Item filter tuning/custom filter | ⏸ NOT STARTED — source unread pending authorization |
| M8 | Sorted XLSX inventory/trade-price sheet | ⏸ NOT STARTED; needs remaining item details and pricing basis |
| M9 | Inventory-to-equipped swaps | ⏳ Lacerator/Wraith pair is player-reported and cleared Duriel quickly; level-79 panels show IAS 52, but resist labels conflict and Strength / damage / exact frames remain unverified. Run 2 Heavy Bolts await a Purity crossbow test. |

## Current checkpoint

- Active session branch: `arena/56066609-pd2-s14`, based on main commit `81433fa3ec88e4db9d798bc72077f88564c83535`.
- All icon IDs U-001–U-108 are identified and documented; `docs/Unidentified_Icons_and_Items.xlsx` has no unresolved data rows. Item Filter remains unread and requires explicit authorization.
- **Inventory action matrix updated:** `docs/07_Full_Inventory_Action_Matrix.md` covers the equipped Barbarian and mercenary gear, 24 charms, documented inventory tabs, all 23 Run 1 finds, and the first 15 Run 2 finds. `docs/09_Run_2_Checkpoint.md` contains full Run 2 transcriptions and current stat panels. The key Run 2 crossbow-compatible unique bolts need an exact 3-socket crossbow; no crossbow base appeared in this batch.
- Quantity/ownership limitations remain: some Ubers/map material stacks have no tooltips; map catalog icons are not proven owned; `04A` and `04B` screenshots omit parts of their in-game page lists. These are itemized by source location in the new matrix.
- No live HC market listings were checked. The player reports Run 1 Gauntlets + Mesh Belt + `04C #14` ring, ethereal Lacerator [C] + Wraith Flight [C] on the Throw Barbarian, and `04B #13` Sigon's Wrap on Mahala. Latest level-79 panels show IAS 52, displayed leech 9%, Pierce 41–42%, and Buff/No Buff resist profiles that conflict; no Throw damage/AR or Strength panel is supplied. The player reports Duriel died in under one minute and they are moving into Act 3. Run 2 images 1–15 are reviewed; image 13 Anvilguard Strap Heavy Bolts are held for a second Purity crossbow trial. Image 10 is a 4-socket bow, not a crossbow; no 3-socket crossbow base was found. A Poisoned Well map ×1 requires level 80. Reported WSS/Gul trades are recorded; exact Paladin skiller-copy identity is unconfirmed. PD2info values remain Softcore estimates, not current quotes.
- Preserve constraints: all 24 Charms-tab charms remain equipped; do not swap them without comparing stats. Mahala's Purity Prayer healing is relied on; keep Purity Long Bow + Sharp Arrows baseline. Run 2's Anvilguard Strap Heavy Bolts (and separately Ramfodder) merit a reversible second Purity crossbow test, but crossbow bolt Pierce must be verified. Do not dismantle current bow. `04B #13` Sigon's Wrap (+13% Pierce) and `04K #1` (+10% block) are distinct. Run 2 images 1–15 have been reviewed; do not exceed 15 new item images for a Run without explicit revision. Run 1's 23 images were a one-time authorized exception.
- Wait for the player's next instruction before opening another Run, Inventory source folder or Item Filter. The broader PD2 Wiki review and sorted XLSX trade sheet remain separate work items.
