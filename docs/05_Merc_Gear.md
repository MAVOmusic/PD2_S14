# 05 — Mercenary Gear and Stats

**v0.15.1** · read 2026-10-25 · source folder `MAVOmusicHC - Stats - V1.0/Images/MAVOmusicHC - 05 - Merc Items/` (9 screenshots)

Mercenary: **Mahala**, Act 1 Rogue, level 77.

## Mercenary stats

| Stat | No Buff screenshot | With Buff screenshot |
|---|---:|---:|
| Life | 1,220 / 1,220 | 1,360 / 1,360 |
| Strength | 128 | 128 |
| Dexterity | 193 | 193 |
| Damage | 76–190 | 89–217 |
| Defense | 1,334 | 2,467 |
| Fire resistance | 33 | 33 |
| Cold resistance | 46 | 46 |
| Lightning resistance | 75 | 75 |
| Poison resistance | 75 | 75 |
| Level | 77 | 77 |
| Experience | 46,253,816 | 46,253,816 |

Resistances are transcribed as displayed; the screenshot does not identify difficulty. Fire (33) and cold (46) are the clear gaps versus lightning/poison (75). Do not apply another Hell penalty without verifying the character screen's display convention.

## Equipped gear transcribed

| Slot | Item | Visible mods / details |
|---|---|---|
| Weapon | **Purity** Long Bow, 3 sockets, `AmnEthThul` | Damage 12–24; very fast attack speed; req. DEX 19 / STR 22 / level 25; level 2 Prayer aura when equipped; +45% IAS; +141% ED; −25% target defense; +86% damage to demons; +200 AR vs demons; 30% reduced curse duration; adds 3–14 cold damage; 7% life stolen per hit |
| Armor | **Sigon's Shelter** Gothic Plate | Defense 161; +25% ED; Lightning Res +30%; attacker takes damage of 20. Tooltip also displays a gold `10% Life Stolen per Hit` set line; likely the active Sigon's set bonus with Sigon's Visor, but verify the exact set threshold in-game |
| Arrows/quiver | **Sharp Arrows** | +15 maximum damage; 7% life stolen per hit; Prevent Monster Heal; +5 Energy; Poison Res +29%; +5 Mana after each Kill. Req. level 25; item level 43; affix level 31; crafted alvl 47. The displayed Ko + Pul + perfect-gem upgrade recipe is a guide overlay, not an item stat |
| Belt | **Infernal Sign** Heavy Belt | Defense 3; +25 Defense; +20 Life; req. STR 45 / level 5 |
| Boots | **Boneweave Boots** (self-repairing) | +30% FRW; adds 1–12 lightning damage; 80% slower stamina drain; Cold Res +13%; Lightning Res +24%; Poison Res +21%; repairs 1 durability in 20 seconds. Req. STR 118 / level 57; item level 85; affix level 71; crafted alvl 61; experimental affix quality 41% |
| Gloves | **Chain Gloves** (self-repairing) | +12% ED; +31% enhanced defense; Half Freeze Duration; +51% Extra Gold from Monsters; repairs 1 durability in 33 seconds. Req. STR 25 / level 17; item level 33; affix level 27; crafted alvl 48; experimental affix quality 0% |
| Helm | **Sigon's Visor** Great Helm | Defense 57; +25 Defense; +30 Mana; +616 AR (based on character level). Tooltip also displays the gold `10% Life Stolen per Hit` set line; see Armor note |

## Candidate tests using already documented stash items

### Bow: retain Purity for Prayer healing

The player confirms **Purity is intentionally equipped for its Prayer healing aura**, which Mahala currently relies on. Keep Purity equipped; do not recommend switching to Riphook while that healing is needed. Riphook (222% ED; 50% IAS, 9% life leech, 30% Open Wounds, 10% slow) remains a future physical-damage/control candidate, but it loses Purity's level 2 Prayer aura, demon-specific damage/AR, curse-duration reduction and cold damage. Revisit only after the player confirms the healing is no longer needed or a tested alternative preserves it.

### Quiver: damage versus leech/utility

- Current quiver: 7% life leech, Prevent Monster Heal, +29% poison res, +15 max damage and +5 mana after kill.
- Stash Ramfodder from `docs/04A_Inventory_Uniques.md` is a **bolt quiver**: 10% IAS, 20% FHR, knockback, −2% enemy physical resistance and +22 Life. It is not compatible with the currently equipped bow. The player would first need to craft/equip a crossbow with Purity; keep the current bow and arrow quiver until then, preserving Prayer healing. Reassess Ramfodder only in that crossbow setup.
- Another Sharp Arrows in Sortables (`docs/04C_Inventory_Sortables.md`) has +44% ED, +10 max damage and +57–177 cold damage. This is a **different item** from the equipped arrows; compare actual damage but account for losing leech, PMH and poison resistance.
- For Hardcore, retain the current Purity bow + Sharp Arrows by default. Ramfodder is not an option with this bow; revisit it only after a Purity crossbow is crafted/equipped and its healing aura is confirmed active. The alternative Sharp Arrows could be tested with the bow, but only after a safe comparison that accounts for lost leech/PMH/poison resistance.

### Boots: avoid a blind resistance trade

Current displayed resists are 33 Fire / 46 Cold / 75 Lightning / 75 Poison. The equipped Boneweave Boots contribute +13 cold / +24 lightning / +21 poison and 30 FRW.

- **Infernostride** (in Uniques) would trade those cold/light/poison boots resists for +30 Fire Res, +5% maximum Fire Res and 30 FRW. Approximate resulting displayed values: 63/33/51/54 if the stat screen is already difficulty-adjusted.
- **Corrupted Sharkskin Boots** (in Sortables) have 40 FRW, +37 cold and +38 poison res, but no fire/lightning res. Approximate result: 33/70/51/92.
- Neither is a universal upgrade. The Sharkskins help cold/poison and mobility; Infernostride helps fire/max-fire. Both lower lightning res from 75 to about 51. Choose only for the zone and after checking live post-swap stats.

### Armor: defense increase may cost resists and leech

The ethereal Diamond Mail in Sortables is listed at 734 defense with +231 defense based on character level and +10% FCR; it is not a blank base. Compared with Sigon's Shelter, it could add substantial defense, but the displayed armor has no listed resistances and replacing Shelter may break the displayed Sigon's life-leech set bonus. Avoid a blind swap; compare Mahala's full post-swap resists, defense and leech first.

## Immediate recommendations

1. **Keep current Purity + Sharp Arrows as the safe baseline.** Purity's Prayer aura is intentionally used for healing; do not swap it until the player no longer relies on it or has tested a healing-preserving alternative. Together the bow and arrows show 14% life leech before any active set bonus.
2. **Fire resistance is Mahala's biggest visible defensive gap (33)**. Consider the Infernostride fire swap for fire-heavy content, but it reduces several other resistances; the Sharkskins instead prioritize poison/cold.
3. Do not equip the eth Diamond Mail solely for its defense before checking the possible 10% Sigon's leech bonus and lightning resistance loss.
4. The LLD/early-level Infernal Sign belt and Sigon's Shelter/Visor have low-level requirements and are not obvious level-77 upgrades; current belt/helm should be evaluated only after the full merc gear set and actual defense/resist totals are considered.

## Confidence and open checks

- Visible stats and item names: HIGH where listed; all nine screenshots reviewed.
- Whether the gold 10% life-leech line is an active Sigon's set bonus: MEDIUM; verify the set threshold in-game.
- Resistance comparisons assume the displayed 33/46/75/75 values are current applied stats and item mods add/subtract directly; confirm in-game after each equipment change.
- No live trade price is assigned to equipped gear. This review is for gear swaps and survival, not a current-market appraisal.
