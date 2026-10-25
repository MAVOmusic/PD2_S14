# 04I — Inventory: Maps Tab (3 screenshots)

**v0.17.0** · sources:
- `MAVOmusicHC - Stats - V1.0/Images/MAVOmusicHC - 04 - Inventory/Maps Tab/Tier 1 - No Maps.PNG`
- `MAVOmusicHC - Stats - V1.0/Images/MAVOmusicHC - 04 - Inventory/Maps Tab/Tier 2 - No Maps.PNG`
- `MAVOmusicHC - Stats - V1.0/Images/MAVOmusicHC - 04 - Inventory/Maps Tab/Tier 3 - No Maps.PNG`

## Scope and interpretation

The player supplied map names for U-025–U-053 in `docs/16-53 Identified.xlsx`. The upper map-like tiles now have names, but the source filenames say “No Maps” and show no owned-item counts/tooltips. Treat these as map icons/catalog entries, **not confirmed owned or saleable map drops**. The repeated 3×7 lower grid is still unidentified (U-054–U-074 in the identification workbook).

The official Wiki's [Maps](https://wiki.projectdiablo2.com/wiki/Maps) page has an **Immunes** summary listing map-level monster resistances at/above 100%; that is distinct from the full six-type maximum-resistance profiles entered by the player for U-025–U-034. Wiki tier zone levels: T1 **87**, T2 **88**, T3 **89**.

Abbreviations in Wiki column: **P** Physical, **M** Magic, **F** Fire, **L** Lightning, **C** Cold, **Pois** Poison. A blank/no-entry means the summary does not list an inherent immunity for that type. `*` is the Wiki's footnote for extra monsters that drop nothing or do not spawn naturally.

## Map icons and Wiki cross-reference

Player-entered profiles for U-025–U-034 retain the order shown in their workbook: **Physical / Magic / Poison / Fire / Lightning / Cold**. Wiki immunities use its map summary and are listed separately.

| ID | Screenshot group / slot | Player-provided map name | Wiki tier / zone level | Wiki-listed map immunities | Cross-check / note |
|---|---|---|---|---|---|
| U-025 | Tier 1 · R1C1 | Ruins of Viz-Jun | T1 / 87 | P115, L100, C120 | Player profile: 115 / 50 / 80 / 75 / **75** / 120. Wiki's summary lists Lightning 100; apparent mismatch with the player's 75 entry. |
| U-026 | Tier 1 · R1C2 | Phlegethon | T1 / 87 | F120, Pois120 | Player profile: 50 / 50 / 120 / 120 / 80 / 75. |
| U-027 | Tier 1 · R1C3 | Torajan Jungle | T1 / 87 | P*, M*, F*, L*, C120*, Pois120 | Player profile: 50 / 50 / 120 / 75 / 75 / 120. Asterisks follow the Wiki footnote. |
| U-028 | Tier 1 · R1C4 | Tomb of Zoltun Kulle | T1 / 87 | P115, Pois120 | Player profile: 115 / 50 / 120 / 75 / 75 / 75. |
| U-029 | Tier 1 · R1C5 | Lost Temple | T1 / 87 | M105, C120 | Player profile: 55 / 105 / 80 / 75 / 80 / 120. |
| U-030 | Tier 1 · R1C6 | Ancestral Trial | T1 / 87 | F120, L120 | Player profile: 50 / 50 / 75 / 120 / 120 / 75. |
| U-031 | Tier 1 · R1C7 | Fall of Caldeum | T1 / 87 | P115, M105, L120 | Player profile: 115 / 105 / 80 / 75 / 120 / 75. |
| U-032 | Tier 1 · R1C8 | Shadows of Westmarch | T1 / 87 | M105, F120 | Player profile: 50 / 105 / 75 / 120 / 75 / 85. |
| U-033 | Tier 1 · R1C9 | Sanatorium | **T2 / 88** | M105, L120 | Player profile says Magic **1050**. Wiki individual values indicate 105, not 1050; Wiki also classifies Sanatorium as Tier 2, unlike this screenshot group. Verify the entry/slot before changing it. |
| U-034 | Tier 1 · R2C1 | Poisoned Well | T1 / 87 | No inherent monster immunities listed | Player profile: 60 / 55 / 75 / 75 / 75 / 75. Wiki marks this as a new map with no monster immunities. |
| U-035 | Tier 2 · R1C1 | Horazon's Memory | T2 / 88 | P115, L120*, Pois* | Frozen Abyss have an 8-second stun here (Wiki says 8× the Canyon of Sescheron stun). The Wiki also marks special extra immunes with `*`. |
| U-036 | Tier 2 · R1C2 | Sewers of Harrogath | T2 / 88 | F120, Pois120 | Wiki's map immunity summary. |
| U-037 | Tier 2 · R1C3 | Throne of Insanity | T2 / 88 | P115, Pois120 | Wiki's map immunity summary. |
| U-038 | Tier 2 · R1C4 | Pandemonium Citadel | T2 / 88 | M105, C120 | Wiki's map immunity summary. |
| U-039 | Tier 2 · R1C5 | Canyon of Sescheron | T2 / 88 | P115, F120 | Frozen Abyss have a 1-second stun here (Wiki contrasts this with the 8-second stun in Horazon's Memory). |
| U-040 | Tier 2 · R1C6 | **Ruined Temple** (player entry) | No exact match | — | The current Wiki page lists **Ruined Cistern** (T2 / 88; M105, Pois120), but has no “Ruined Temple” map heading. Possible name mismatch; do not assign Ruined Cistern data to this icon unless the player confirms. |
| U-041 | Tier 2 · R1C7 | Ashen Plains | T2 / 88 | F120, C130 | Wiki's map immunity summary. |
| U-042 | Tier 2 · R1C8 | Halls of Torture | T2 / 88 | L120, C120 | Wiki's map immunity summary. |
| U-043 | Tier 2 · R1C9 | Fortress of Aranoch | T2 / 88 | No inherent monster immunities listed | Wiki calls this a new map with no monster immunities; individual monster table is not populated. |
| U-044 | Tier 2 · R2C1 | Descent From Mount Arreat | T2 / 88 | No inherent monster immunities listed | Wiki calls this a new map with no monster immunities; individual monster table is not populated. |
| U-045 | Tier 3 · R1C1 | Bastion Keep | T3 / 89 | P115, M105, C120 | Wiki's map immunity summary. |
| U-046 | Tier 3 · R1C2 | Arreat Battlefield | T3 / 89 | M105, L120, Pois120 | Wiki's map immunity summary. |
| U-047 | Tier 3 · R1C3 | River of Blood | T3 / 89 | M105, L120, Pois120 | Wiki inconsistency: the summary omits Cold, but its individual monster table lists Flesh Beast with Cold 140. Verify current in-game data before planning around it. |
| U-048 | Tier 3 · R1C4 | Blood Moon | T3 / 89 | No inherent monster immunities listed | Wiki says Hell Bovines are the only non-boss monster type unless map affixes add others. |
| U-049 | Tier 3 · R1C5 | Kehjistan Marketplace | T3 / 89 | P115, F120 | Wiki's map immunity summary. |
| U-050 | Tier 3 · R1C6 | Royal Crypts | T3 / 89 | F120, C120 | Wiki's map immunity summary. |
| U-051 | Tier 3 · R1C7 | Skovos Stronghold | T3 / 89 | C120, Pois120 | Wiki's map immunity summary. |
| U-052 | Tier 3 · R1C8 | Demon Road | T3 / 89 | P115, F120, L120 | Wiki's map immunity summary. |
| U-053 | Tier 3 · R1C9 | Kyovoshad | T3 / 89 | No inherent monster immunities listed | Wiki spelling is “Kyovoshad”; no immunity row is listed. |

## Wiki lookup conclusions / unresolved icon work

- The Wiki catalog lists **9 T1, 11 T2 and 9 T3 maps**. The screenshot grids show 10 / 10 / 9 icons. Sanatorium appears in the screenshot's Tier 1 group but is a Wiki T2 map; U-040's “Ruined Temple” is not a Wiki heading. These name/tier mismatches may explain the grid-count difference; please confirm before treating the screenshot labels as exact tier ownership.
- The immunity entries above are from the Wiki's dedicated [Immunes section](https://wiki.projectdiablo2.com/wiki/Maps#Immunes), not a complete six-element max-resistance profile. The page also has individual monster tables; they sometimes conflict with the summary (U-047 is noted above).
- Map level and immunities describe the Wiki entries, not proof the character owns these maps. The original source filenames say “No Maps”; do not count or price the map icons as owned drops without an ownership/tooltip screenshot.
- U-054–U-074 (the repeated lower 3×7 grid) remain unidentified in `docs/Unidentified_Icons_and_Items.xlsx`.
