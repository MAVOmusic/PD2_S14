# 05 — Mercenary Gear and Stats

**v0.22.0** · revised 2026-10-26 · source folder `MAVOmusicHC - Stats - V1.0/Images/MAVOmusicHC - 05 - Merc Items/` (9 screenshots), prior inventory docs, and current PD2 Wiki set/mercenary/runeword/quiver mechanics.

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

### Quiver: role-specific swaps, not a one-item ranking

- Current Sharp Arrows: +15 maximum damage, 7% life leech, Prevent Monster Heal, +29% poison resistance and +5 mana after each kill. Keep them as the Hardcore/boss baseline until a replacement wins a live comparison.
- **Swiftwind Needle** (Run 1 Sharp Arrows): +34% FRW, +12–14 damage, −28 monster defense per hit, +28 Dexterity, +50 cold res and +25 lightning res. Rogue Scouts have a wiki-listed 66% baseline pierce chance; the separate +13% Pierce Sigon's Wrap may add useful multi-target throughput with a bow. Swiftwind gives up the current arrows' 7% life leech, PMH and +29 poison res. Treat it as an offensive/mobility test, not an automatic upgrade; check hit chance and poison resistance after the swap.
- **Blunt Arrows** (Run 1): the screenshot-recorded +188–268 fire damage, +50 poison damage over 5 seconds, 20% Open Wounds / +241 OW damage per second, +20 lightning res, GF and MF make this a serious offensive test. It loses the equipped arrows' 7% leech and +29 poison res, but OW is an actual anti-regeneration effect while active; merc OW damage is reduced to 1/4. PD2 Wiki notes PMH does not affect Ubers, while poison/OW damage halts their natural regeneration, so Blunt may be preferable to PMH arrows in an Uber/regen-control test if OW uptime is adequate. It remains probabilistic, so keep Sharp as the general PMH/leech/poison-res option and verify survival.
- Stash Ramfodder is a **Light Bolts** unique: −2% enemy physical resistance, +10% IAS, +20% FHR, Knockback, +10–25 Life and stamina. It cannot be equipped with the current bow. **A Purity crossbow is technically compatible**: PD2 Wiki lists Purity as a 3-socket polearm/spear/staff/bow/crossbow runeword (Amn–Eth–Thul). Keep the current Purity Long Bow; do not dismantle it. With the documented Amn/Eth/Thul stock, a second Purity can be made in an exact 3-socket crossbow base, then tested with Ramfodder. Prefer a fast base and verify actual attack frames; mercenaries use the same breakpoints for bows and crossbows when WSM and IAS match.
- Crossbow is not a free quiver upgrade: Ramfodder gives no listed life leech or PMH, and the Season 12 patch notes state that crossbows no longer physically pierce. The Mercenaries page separately lists Rogue Scouts' 66% baseline pierce, so confirm bolt penetration in-game rather than assuming bow-like multi-target behavior. Compare Ramfodder's +10 IAS / −2% enemy physical resistance / knockback against the arrow options in a safe area. Keep the current bow/quiver intact for reversal.
- **Purity tooltip discrepancy to verify:** the recorded current Long Bow screenshot says Prayer aura level 2, while the current PD2 Bow Runewords page lists a level 10–12 Prayer aura. The healing source itself is confirmed; read the live tooltip on both current and any newly crafted Purity before comparing healing output.

### Boots: avoid a blind resistance trade

Current displayed resists are 33 Fire / 46 Cold / 75 Lightning / 75 Poison. The equipped Boneweave Boots contribute +13 cold / +24 lightning / +21 poison and 30 FRW.

- **Infernostride** (in Uniques) would trade those cold/light/poison boots resists for +30 Fire Res, +5% maximum Fire Res and 30 FRW. Approximate resulting displayed values: 63/33/51/54 if the stat screen is already difficulty-adjusted.
- **Corrupted Sharkskin Boots** (in Sortables) have 40 FRW, +37 cold and +38 poison res, but no fire/lightning res. Approximate result: 33/70/51/92.
- Neither is a universal upgrade. The Sharkskins help cold/poison and mobility; Infernostride helps fire/max-fire. Both lower lightning res from 75 to about 51. Choose only for the zone and after checking live post-swap stats.

### Armor: defense increase may cost resists and leech

The ethereal Diamond Mail in Sortables is listed at 734 defense with +231 defense based on character level and +10% FCR; it is not a blank base. Compared with Sigon's Shelter, it could add substantial defense, but the displayed armor has no listed resistances and replacing Shelter may break the displayed Sigon's life-leech set bonus. Avoid a blind swap; compare Mahala's full post-swap resists, defense and leech first.

### Run 1 follow-up: restore the Sigon's set synergy before judging Tal's or Smoke

The first-pass plan undercounted Sigon's set interactions and is superseded. Mahala currently wears Sigon's Visor + Shelter, so the 2-piece +10% life leech is active. Run 1/04B contains a **separate Sigon's Wrap with +13% Pierce** (`04B #13`); `04K #1` is a different +10% block copy. Do not confuse the two.

- **First test: equip the +13% Pierce Sigon's Wrap instead of Infernal Sign**, keeping Visor, Shelter, Purity and Sharp Arrows. Current Wiki set data lists +10% life leech at 2 pieces and +100 Defense at 3; the Wrap also gets +2 Defense per character level when 2+ Sigon pieces are worn. At Mahala level 77, that level-based line is +154 Defense. Using the observed belt base defense 11, the listed belt/set components sum to approximately 11 + 154 + 100 = 265 defense; this is not a claim about the character-sheet total. If the live item tooltip shows roughly +300, record that exact tooltip and reconcile it rather than dismissing it. The belt keeps the current +20 Life, adds +20 Fire Res and +13% Pierce, and should preserve the set leech while adding the three-piece defense. Versus Infernal Sign's 3 base +25 defense, the listed defense components imply about +237 net defense (calculated, not live). If the Rogue's 66% baseline and +13 item pierce add directly, that is nominally 79% pierce; verify the actual stat and behavior. Check live defense, resistances and set text after equip.
- **Then test Tal's Crest as a helm alternative while keeping Sigon's Shelter + Wrap.** This leaves 2 Sigon pieces active: the shared +10% life leech and the Wrap's +2 defense/level remain. Tal's adds +8% leech, +7% mana leech, +56 Life, +28 Mana and +16 all res. Compared with the 3-piece Visor/Shelter/Wrap setup, it gives up the Visor's +616 level-scaled AR and the 3-piece +100 Defense, but retains the belt's +154 level defense; the +8 helm leech is an addition on top of the still-active 2-piece bonus, not a replacement for it. This makes Tal's a meaningful tradeoff to test, not an automatic loss of two points of leech.
- **Smoke is a separate armor alternative:** Smoke in the Run 1 Wire Fleece [2] (Nef–Lum) can be tested with Sigon's Visor + Wrap (2 Sigon pieces) to retain the 10% set leech, visor AR and belt level-defense while dropping Shelter's +30 Lightning Res and the 3-piece +100 Defense. Smoke's +30–50 all res can more than offset Shelter's lightning contribution, but exact defense/resists need a live check. Using Tal's + Smoke + only the Wrap is a resist-first, no-active-Sigon-set alternative; with the current arrows its documented leech calculation is 22% (7 bow + 7 arrows + 8 Tal), not a default over the set-preserving options.
- **Arrow tests come after the belt/helm check.** With Purity + Tal's + Sigon's Shelter/Wrap, the recorded leech totals are 32% with current Sharp Arrows and 25% with Swiftwind or Blunt (bow 7 + Tal 8 + 2-piece Sigon 10, plus arrow leech where present). Swiftwind/Blunt also remove the current arrows' +29 poison res; based on the documented current stat display and item deltas, Tal + Wrap + Swiftwind/Blunt would leave roughly 62 displayed poison res before any new armor correction. Do not assume this is safe; check actual post-swap resistances. Keep Sharp for PMH and safer poison coverage.
- **Crossbow test is viable without sacrificing the current baseline.** The current runes are sufficient for another Purity (Amn–Eth–Thul) in a 3-socket crossbow; craft a second item and retain the Long Bow. Ramfodder's +10 IAS and −2% enemy physical resistance may be useful, but it loses Sharp's leech/PMH/poison res and may give up arrow-style piercing. Confirm current Purity aura level and actual bolt behavior in-game first.
- All defense/resistance totals above are calculations from the recorded item lines, not a live comparison. The current Purity screenshot's aura-level-2 transcription conflicts with the current Wiki's 10–12 roll; the active healing aura is user-confirmed, but compare the actual tooltips.

## Immediate recommendations

1. **Keep Purity + current Sharp Arrows as the reversible baseline.** Mahala's Prayer healing is relied on; keep the current weapon and quiver until each alternative is tested. The in-game Purity aura level must be checked because the screenshot transcription and current Wiki differ.
2. **First low-risk test: 04B #13 Sigon's Wrap (+13% Pierce) instead of Infernal Sign.** This completes the current Visor/Shelter 3-piece set, keeps 10% set leech, and adds the Wrap's level-scaled defense plus the 3-piece +100 Defense. The official Wiki set table lists +100 at 3 items; at level 77, the belt's own +2/level line adds +154. Keep 04K #1's +10% block belt separate; block is not a ranged Rogue benefit.
3. **Second test: Tal's Crest for Sigon's Visor while retaining Shelter + Wrap.** It retains the 2-piece leech and belt defense line, adds life/leech/resists, and trades away +616 AR plus the 3-piece +100 Defense. Compare actual hit chance/defense/resists rather than assuming either wins.
4. **Only then test Smoke as its own armor alternative**, preferably with Sigon's Visor + Wrap to retain two-piece bonuses. Tal + Smoke is a separate resist-first option that breaks Sigon's set; don't present it as the only or automatically best setup.
5. **After post-belt/helm resist checks, compare Swiftwind and Blunt arrows in safe content.** Keep Sharp for PMH and poison-res safety; Swiftwind is mobility/hit/damage, Blunt is burst/OW. Neither is a universal replacement.
6. **Ramfodder merits a reversible crossbow test:** make a second Purity in a 3-socket crossbow rather than dismantling the existing bow. Compare its speed, bolts, healing aura, pierce and survival in-game; keep the arrow setup for immediate reversion.
7. Infernostride/Sharkskins are zone-specific boot tests; don't blind-swap. Avoid the eth Diamond Mail until its defense can be compared against the set/leech/resist alternatives.

## Confidence and open checks

- Visible stats/item names: HIGH where transcribed; all nine merc screenshots reviewed. The two Sigon's Wrap copies are distinct observed items: `04B #13` +13% Pierce and `04K #1` +10% block.
- Sigon set mechanics: current PD2 Wiki page lists +10% life leech at 2 items and +100 Defense at 3; it lists Wrap +2 Defense per character level with 2 pieces. At level 77, +154 is a calculation; verify the combined in-game tooltip.
- Rogue baseline 66% pierce, crossbow weapon/runeword compatibility and mercenary weapon breakpoints were checked against PD2 Wiki pages. A Season 12 crossbow-pierce patch note and the merc baseline-pierce line should be reconciled with actual bolt behavior in-game.
- Mechanics references (checked 2026-10-26): [Sigon's set data](https://wiki.projectdiablo2.com/wiki/Normal), [Mercenaries](https://wiki.projectdiablo2.com/wiki/Mercenaries), [Mercenary Skills](https://wiki.projectdiablo2.com/wiki/Mercenary_Skills), [Purity compatibility/stats](https://wiki.projectdiablo2.com/wiki/Bow_Runewords), [Quivers](https://wiki.projectdiablo2.com/wiki/Quivers), [S12 crossbow pierce note](https://wiki.projectdiablo2.com/wiki/Patch:Season_12), [Open Wounds/attack mechanics](https://wiki.projectdiablo2.com/wiki/Game_Mechanics), and [monster regeneration](https://wiki.projectdiablo2.com/wiki/Monsters).
- The current Purity screenshot says aura level 2, while the current Wiki lists 10–12. User confirms Prayer healing is active; read the live tooltip before recrafting.
- Resistance and leech totals are calculations from recorded stats/item mods, not live screenshots; verify display convention and values after each swap.
- No live trade price is assigned to equipped gear; this is a gear/survival comparison, not a market appraisal.
