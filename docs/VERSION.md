# PD2 S14 Project — VERSION

| Field | Value |
|---|---|
| Project version | **v0.3.0** |
| Doc schema | 1 |
| Last updated | 2026-10-25 |
| Branch of record | `arena/360df353-pd2-s14` (mirrored to `main`) |
| Game | Project Diablo 2 — Season 14 |
| Character | MAVOmusicHC — Level 77 Hardcore Throw Barbarian (Act 1 Rogue Merc) |
| Owner | MAVOmusicHC |

## Version history (summary — detail in CHANGELOG.md)

| Version | Date | Headline |
|---|---|---|
| v0.1.0 | 2026-10-25 | Project bootstrap: vision check, folder-work protocol, context/version/changelog stack |
| v0.3.0 | 2026-10-25 | Resist correction applied (Hell-applied values; cold/light overcapped); folder `03 - Charms` fully read; charm loadout + trade values |
| v0.2.0 | 2026-10-25 | Folder batch 1/6 read: `01 - Character + Skill Tree`, `02 - Equipped Items`; character snapshot recorded; item valuations (equipped + swap) added |

## Milestone tracker (overall project)

| # | Milestone | Status |
|---|---|---|
| M1 | Vision capability check | ✅ DONE — this chat CAN read images |
| M2 | Read `01 - Character + Skill Tree` + `02 - Equipped Items` | ✅ DONE (v0.2.0) |
| M3a | Read `03 - Charms` | DONE (v0.3.0) |
| M3b | Read `04 - Inventory` | IN PROGRESS |
| M4 | Read `05 - Merc Items` + `Item Filter` | ⏸ AWAITING USER GO-AHEAD |
| M5 | Farm plan: elite crafting base zones (self + merc) up to Hell A2 Arcane Sanctuary | ⏸ Pending (draft in `02_Character_And_Gear_Snapshot.md`) |
| M6 | Item filter rework / custom filter (tiered colours, hide worthless, highlight top trade value) | ⏸ Pending |
| M7 | Trade-pricing spreadsheet (XLSX) of all stored items, sorted by value | ⏸ Pending (needs M3) |
| M8 | Gear-swap recommendations from inventory | ⏸ Pending (needs M3) |

## Open questions for the user
1. Which Excel column order do you want first — `Value (HR)` then `Asking price`, or `Item` first?
2. Do you want the custom filter delivered as a **full standalone .filter** or as a **patch/diff against `Hiim_Crafting_Barbarian_Focused.filter`** (keeping Hiim's crafting base highlighting)?
3. Realms/currency basis for pricing: PD2 SC/HC ladder rune prices (I will price in runes + `HR` equivalents, HC premium noted).
