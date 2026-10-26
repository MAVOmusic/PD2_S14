# 02 — Character & Gear Snapshot (Folders 01 + 02)
**Version:** v0.25.0 · **Updated:** 2026-10-26 · **Sources:** original `MAVOmusicHC - Stats - V1.0/Images/MAVOmusicHC - 01 …` and `… 02 …` screenshots; 2026-10-26 player reports, weapon screenshots, and latest Buff / No Buff stat panels.

> Transcribed verbatim from screenshots. Anything marked `⚠` is a best-effort read, not certain.

---

## 1. Character sheet

| Field | No buffs | With buffs (BO/BC up) |
|---|---|---|
| Name / Class | MAVOmusicHC — Barbarian | same |
| Level | **77** | 77 |
| Experience | 544,532,832 | — |
| Next level | 572,485,967 | — |
| Strength | 194 | 194 |
| Dexterity | 155 | 155 |
| Vitality | 165 | 165 |
| Energy | 34 | 34 |
| Life | 875 | **1,025** |
| Mana | 211 | 281 (262 on one page) |
| Stamina | 562 | 627 |
| Defense | 328 | 569 |
| Frenzy damage | 525–2,435 / 344–1,201 | 553–2,503 / 362–1,259 |
| Double Throw damage | 1,340–2,577 / 442–1,219 | 1,413–2,711 / 466–1,281 |
| Frenzy AR | 4,668 / 8,212 | 4,824 / 8,487 |
| Double Throw AR | 8,345 / 14,681 | 8,671 / 15,255 |

**Snapshot caveat:** this original character-sheet table is a level-77, pre-swap record. It is historical, not the current character state. Latest player-supplied level-79 stat panels are transcribed below; their labels and differences are preserved as shown rather than reconciled by inference.

### Latest player-supplied stat panels (Level 79, 2026-10-26)

The two attachments were named `Buff.PNG` and `No Buff.PNG` by the player. The table below follows those filenames exactly; no equipment changes were reported between captures, but some values do not form a straightforward buff-only delta.

| Visible panel value | `Buff.PNG` | `No Buff.PNG` |
|---|---:|---:|
| Level / area | 79 · Hell · Kurast Docks | 79 · Hell · Kurast Docks |
| Fire Resist | 81 / 75 | 73 / 75 |
| Cold Resist | 109 / 80 | 191 / 80 |
| Lightning Resist | 80 / 75 | 72 / 75 |
| Poison Resist (length) | 68 / 75 (200%) | 60 / 75 (200%) |
| Curse Resist (length) | 20 / 75 (100%) | 20 / 75 (100%) |
| IAS / Double Throw | 52 IAS; breakpoint line shown below | 52 IAS; same breakpoint line |
| Double Throw IAS breakpoint text | `0 / 2 / 7 / 15 / 24 / 40 (10) / 63 / 99 / 168 / 395` | same |
| Crushing Blow | 27% | 27% |
| Open Wounds | 39% / +768 | 38% / +748 |
| Deadly Strike | 0 / 75 / 150% | 0 / 75 / 150% |
| Critical Strike | 29 / 75 / 200% | 29 / 75 / 200% |
| Life Leech / Mana Leech | 9% / 6% | 9% / 6% |
| Projectile Pierce | 42% | 41% |
| HP / MP per kill | 0 / 16 | 0 / 16 |
| Base AR | Dex 810 + equip 72 = total 882 | same |
| Base Defense | Dex 41 + equip 239 = total 280 | same |
| Other visible combat stats | FCR 10 · FHR 7 · Block 0 · Run/Walk 25 · Attack Rate 110 · MF 33 | same |

**Comparison caution:** as named, the `No Buff` panel has +82 Cold Resist versus `Buff.PNG`, while `Buff.PNG` has +8 Fire, +8 Lightning, +8 Poison, +1% Pierce and +1% OW chance. Treat the filenames as user-provided labels, but don't attribute those changes solely to BO/BC or derive one authoritative resist profile without confirming that gear and other effects were identical. Both panels show 9% Life Leech even though Wraith Flight's tooltip has +7% Life Stolen per Hit; record the panel value as observed and leave the item-vs-panel contribution unresolved. At IAS 52, the displayed sequence appears to put the next listed threshold at 63 (11 more displayed IAS); actual Double Throw frames still need in-game confirmation with this mixed-base weapon pair.

### Historical resistances — level-77 pre-swap baseline (not current)

| Resist | No buff | With buff | Hell penalty (−100) reality |
|---|---|---|---|
| Fire | 41 | 49 | ~−51 … −59 → **taking huge fire damage** |
| Cold | **80** | 80 | capped-ish, fine |
| Lightning | 75 | 75 | capped, fine |
| Poison | 50 | 58 | ~−42 … −50 → **long poison ticks** |

PD2 caps resists at 75 (higher with +max res). On this level-77 pre-swap snapshot, **Fire and Poison were the two largest gaps**. This assessment is superseded by the latest level-79 panels above, whose Buff/No Buff resist values differ; use those labeled readings and clarify the active profile before relying on a single total. Both elements matter in Hell Arcane Sanctuary and Canyon of the Magi.

**Current safe-gearing note (after inventory review):**
1. Keep the equipped +10 Strength / +24 all-res amulet; no stash amulet is a proven general Hell upgrade. Latest level-79 panels are transcribed above; their Buff/No Buff resist difference is not internally consistent enough to merge into one reading without confirmation. See `docs/07_Full_Inventory_Action_Matrix.md` and `docs/09_Run_2_Checkpoint.md` before changing defensive gear.
2. No free socket in the current helm/armor was verified. Use the +28 Fire Res jewel or Ral/Ort only after confirming an open socket and that the item is staying equipped.
3. The charms shown in folder 03 are already equipped and their stats are already reflected in this screenshot. Do not treat them as spare upgrades; any charm change requires a fresh character-sheet/stat comparison.
4. With Double Throw active, use a two-throwing-weapon setup; any shield/defensive setup is a separate weapon-swap/test, not the normal Double Throw configuration.

---

## 2. Skill tree — player labels and build rationale (U-101–U-108)

The player identified the remaining skill icons by name. The official PD2 [Combat Skills](https://wiki.projectdiablo2.com/wiki/Combat_Skills_(Barbarian)), [Combat Masteries](https://wiki.projectdiablo2.com/wiki/Combat_Masteries), and [Warcries](https://wiki.projectdiablo2.com/wiki/Warcries) pages explain how the choices fit together. This is an explanation of the displayed allocation, not a respec recommendation.

### Core Throw skills — Combat Skills tree

| ID | Player-identified skill | Why it fits the Throw Barbarian |
|---|---|---|
| U-101 | Double Swing | Required to reach Frenzy and Double Throw; also gives Double Throw +6% damage per hard point as a synergy. Screenshot showed skill level 14. |
| U-102 | Frenzy | Required by Double Throw and also provides Double Throw +6% damage per hard point. Frenzy itself builds attack/movement speed charges when attacking with two weapons, giving utility beyond its synergy. Screenshot showed skill level 21. |
| U-103 | Double Throw | The main ranged attack: throws two different throwing weapons and its projectiles bounce to nearby enemies (Wiki lists up to 8 bounces). Screenshot showed skill level 21. |
| U-104 | Top: Bash; middle: Stun; bottom: Leap | The one-point prerequisite route to Leap. The Wiki lists Bash and Stun as Leap prerequisites, and Stun itself requires Bash; one point in each is enough to open the mobility skill. The player's stated purpose is to leap away from danger or over hazardous situations. |

Wiki also lists Double Swing as a Frenzy synergy (+20% damage per hard point), while Frenzy and Stun benefit Double Swing. For this character, the especially relevant direction is both Double Swing and Frenzy boosting Double Throw.

### Throwing and defensive passives — Combat Masteries tree

| ID | Player-identified skill(s) | What the points do / route logic |
|---|---|---|
| U-105 | Throwing Mastery | Direct throwing-weapon passive: improves thrown-weapon damage/attack rating, critical strike, and adds pierce. It naturally supports the main Double Throw attack. Screenshot showed skill level 21. |
| U-106 | Top-left: Combat Reflexes; bottom-left: Increased Speed; bottom-middle: Deep Wounds; top-right: Iron Skin; bottom-right: Natural Resistance | Utility/survival passives. Combat Reflexes adds life and hit recovery; Iron Skin adds defense and physical-damage reduction; Increased Speed adds movement speed and attack speed; Natural Resistance adds elemental/poison resistances; Deep Wounds boosts Open Wounds. Their tree gates explain the spread: Increased Speed requires Combat Reflexes; Natural Resistance requires Iron Skin; Deep Wounds requires Combat Reflexes, Iron Skin, and Increased Speed. |

The defensive nodes can therefore be deliberate one-hard-point investments on the way to later passives, while still adding useful utility. In the old screenshot summary these nodes displayed level 2; with Battle Command and/or item +skills active, that display should not be mistaken for two hard points in each skill.

### Warcries and potion utility

| ID | Player-identified skill(s) | Why the path makes sense |
|---|---|---|
| U-107 | Find Potion | Standalone level-1 utility skill with no prerequisite; use it on slain-monster corpses for a chance to find a potion. The player has not stated a specific reason beyond including it in this build. |
| U-108 | Howl → Shout → Battle Orders → Battle Command | A prerequisite chain to the core buffs. Shout requires Howl; Battle Orders requires Howl and Shout; Battle Command requires Howl, Shout, and Battle Orders. Battle Orders increases maximum life and mana; Battle Command raises current skill levels. The documented build already uses BO/BC pre-buffs. |

### Interpreting the displayed levels

The existing screenshots were summarized with Battle Command active. Battle Command adds +1 to current skill levels, and gear can also add soft levels. Thus displayed values such as 21 may correspond to 20 hard points if there are no other +skills affecting that skill; similarly, a displayed 14 may mean roughly 13 hard points. Treat those as estimates, not a verified hard-point audit. The overall logic is now clear: max the main throw skill and Throwing Mastery, use Frenzy and Double Swing as damage synergies (with Frenzy also giving speed charges), spend sparingly on prerequisite/mobility/survival passives, and take the BO/BC buff chain.

---

## 3. Equipped gear (reported current main throwing-weapon pair; post-swap stats unverified)

| Slot | Item | Key mods (transcribed) | Req | Verdict / value |
|---|---|---|---|---|
| **Weapon 1** | **Lacerator [C]** — ethereal Winged Axe, `291% ED` | Throw 31–293 · one-hand 50–273 · melee attacks deal splash · **8% chance to cast lvl 27 Amplify Damage on striking** · **+30% IAS** · +291% ED · **33% chance of Open Wounds / +450 OW damage per second** · Prevent Monster Heal | Lvl 68 · 112 Dex / 86 Str · very fast axe (base speed −10, range +1) | **Currently equipped per player (2026-10-26).** Strong throw pair component: fast base + item IAS, Amp proc, OW and PMH. Verify actual Double Throw breakpoint, Amp uptime and safety after the swap. Ethereal; cannot be repaired. |
| **Weapon 2** | **Wraith Flight [C]** — ethereal Ghost Glaive, `224% ED` | Throw 119–314 · one-hand 74–243 · melee attacks deal splash · **30% chance to Pierce** · +224% ED · **adds 200–450 magic damage** · **7% life stolen per hit** · −44 monster defense per hit · +20% curse resistance · 6% reanimate as Wraith · +13 mana after each kill | Lvl 76 · 127 Dex / 79 Str · slow javelin class (base speed 20, range +3) | **Currently equipped per player (2026-10-26).** Adds pierce, magic damage, leech and mana-on-kill alongside Lacerator's physical/curse/OW package. Verify current damage/AR and actual clear/survival; item screenshot says ethereal (cannot be repaired). |
| **Displaced pair** | **Simbilan** (`343% ED`, `23% CB`) + Fool's **Francisca** (`121% ED`, 10% lvl 19 Amp) | Historical pair shown in the original character snapshot; detailed mods retained in the prior gear record. | — | Player says these are swapped out, not sold. Keep as rollback/comparison gear until the Lacerator/Wraith pair is proven in safe runs; do not list or vendor yet. |
| **Helm** | **Fanged Helm (barb only)** — `27% CB`, `20% RES` | +68 AR · **27% CB** · +3 Find Potion (barb) · +24 Energy · **All Res +20** · **Defense 16 (!)** | Lvl 55 · 35 Str | Crafted, resists carried here. **Base is bad (def 16 = cracked/low-quality base)** — re-craft on a clean Fanged/Avenger Guard base when you have the runes. Self-use; trade ~Pul |
| **Armor** | **Hawkmail** (unique Scale Mail) | +3 Summon Ravens · **25% FRW** · 97% ED · +5% max cold res · Cold res 26% · **Cannot be Frozen** | Lvl 15 · 44 Str | Utility only — **CBF is why it is on**. Very low trade value (Lem/Pul, probably unsellable). **First upgrade target** once you have a CBF source (Raven Frost / Kira's / crafted) or a Treachery/Vipermagi-type body |
| **Belt** | **Mesh Belt** (Run 1 crafted) | +58% ED · +54 Life · 10% FCR · Fire Res +19% · Poison Res +20% · attacker takes 10 | Lvl 29 | **Currently equipped per player (2026-10-26)** with the Run 1 Gauntlets and 04C #14 ring. The player has since supplied level-79 overall stats, but no isolated before/after belt comparison; retain Plated Belt as rollback. |
| **Boots** | **Chain Boots** — `18% MF`, `23% C`, `32% L` | 86% ED · +3 Dex · Cold res 23% · **Light res 32%** · **18% MF** | Lvl 27 · 30 Str | Solid budget boots. **FRW is missing — that hurts a throw barb's kiting.** Trade ~Pul |
| **Gloves** | **Crafted Gauntlets** (Run 1) | +20% IAS · +16% ED · +10% bonus AR · 3% life leech · +19 Mana · Cold Res +22% · +6 Light Radius | Req. level not recorded here | **Currently equipped per player (2026-10-26).** The previous Heavy Bracers (+109 flat AR, 3% leech, 13% MF) remain a rollback option until the new setup is confirmed in a fresh stat/run check. |
| **Amulet** | Amulet — `24% RES` | **+10 Str · All Res +24** (iLvl 68, crafted aLvl 72) | Lvl 41 | Good utility. Only 2 visible mods → keep as resist glue. Trade ~Um |
| **Ring 1** | Ring — `3MK 5% MF HFD` | **6% Life leech** · +51 Mana · Half Freeze Duration · +3 Mana/kill · 5% MF | Lvl 35 | Main leech source. Keep. Trade low |
| **Ring 2** | Corrupted ring (`04C #14`) | Fire/Cold/Lightning Res +13% each · Poison Res +27% · Physical Damage Taken Reduced by 4 | Lvl 59 | **Currently equipped per player (2026-10-26)** in the Run 1 defensive package. The former Ring 2 (+4% leech/+83 AR/+10 poison/+3 mana per kill) is now in stash; keep it until the package is confirmed in fresh stats/runs, then trade to an LLD buyer rather than vendor. |
| **Swap** | **Harpoon** — `+2 BArb Sks`, `10% IAS` | +2 Barb skills · 10% IAS · +11 min dmg · 165% dmg to undead · 230 AR vs undead · 5% mana leech · (base speed −10, range 3) | Lvl 42 · 25 Str / 118 Dex | Off-hand BO stick. Fine |
| **Swap** | **Glaive** — `+3 Warcries` | +3 Warcries (barb only) · 9% Mana leech | Lvl 48 · 52 Str / 35 Dex | +3 BO stick — **this is the one you pre-buff with.** Keep |

---

## 4. Latest weapon/stat checkpoint and earlier A2 safety notes

- The original level-77 character sheet, with Simbilan 343% ED + Fool's Francisca, listed **Double Throw at 1,340–2,577** (no buff). This is historical only; the latest level-79 panels do not show Double Throw damage or throw AR. The player reports that Lacerator + Wraith Flight melted Duriel in under a minute and is moving into Act 3; this is a player-reported clear result, not independently measured.
- The old Arcane Sanctuary notes remain historical safety reminders, not a current diagnosis:
  1. Original sheet resist gaps were Fire/Poison (−51 / −42 after Hell penalty). The latest panels show Fire/Lightning near their listed caps and Poison at 60–68/75, but their buff/no-buff labels differ unusually; verify which profile is active before making another resist swap.
  2. Current panel shows FHR 7 and Run/Walk 25; it does not list a CBF stat. Avoid interpreting the old stagger/kiting note as evidence that the current resistance/gear setup is unchanged.
  3. Both latest panels display 9% Life Leech even though Wraith Flight visibly has +7% Life Stolen per Hit; the character panel result is transcribed as displayed, but the contribution discrepancy remains unresolved. Leech effectiveness also depends on landing physical damage.
  4. Both latest panels show 16 MP per kill, consistent with Ring 1's +3 plus Wraith Flight's +13 visible item mod; Double Throw still consumes mana.

**Earlier A2 playstyle fixes (still useful as needed):**
- Pre-buff **Battle Orders + Battle Command** on swap every run, then swap back — you already have the sticks.
- **Pull ghosts into the corridor** rather than fighting in the open star-platforms; you cannot out-tank the lightning.
- In Canyon of the Magi, kill the **claw vipers last** and never fight in a doorway (you'll get body-blocked with no block chance for a throw build).

---

## 5. Draft farming plan — elite crafting bases + resists (cap: Hell A2 Arcane Sanctuary)

> Folders 03/04/05 and the documented inventory tabs have now been reviewed; the Item Filter remains unread pending explicit authorization. Area level (alvl) governs which bases drop. Gear comparisons are consolidated in `docs/07_Full_Inventory_Action_Matrix.md`.

### A. Elite throwing-weapon bases (what an endgame Throw Barb actually wants)
| Base | Type | alvl needed | Where you can get it (≤ Hell A2) |
|---|---|---|---|
| **Winged Axe** | elite throwing axe | ~75+ | **Arcane Sanctuary (alvl 79)**, Canyon of the Magi (alvl 77) — best shot |
| **Winged Knife** | elite throwing knife | ~75+ | Arcane Sanctuary, Canyon |
| **Hyperion Javelin / Balrog Spear** | elite jav | 75+ | Arcane Sanctuary (ghosts drop a lot of bases) |
| **Ghost Glaive** | elite polearm/jav | 75+ | Arcane Sanctuary |
| Note | — | — | Normal-Cow / NM-Cow can't reach elite throw bases reliably; **Arcane Sanctuary is genuinely your best legal spot** |

### B. Crafting-base + rune farming loop (efficient, low risk)
1. **Arcane Sanctuary full clear** (4 wings + Summoner) — ghosts drop runes, bases, and charms. Best single spot for you. Expect **1–2 elite throw bases per 3–4 runs**.
2. **Canyon of the Magi → Tal Rasha's Tombs (Duriel)** — elite bases from sarcophagi packs; avoid Hephasto.
3. **Halls of the Dead / Lost City (A2)** — safe, dense, good for gold + gem finds; useful for the crafting mats (P. Amethyst/Ruby/Sapphire + jewels).
4. **Nightmare Cows (repeatable, safe)** — the practical source of **crafting runes (Ral/Io/Nef/Tal/Shael)** and flawless gems in bulk, since Hell Cow is out of reach.
5. **Normal Cows** — cheap base shopping (clean white/Gray throwing bases for Larzuk sockets).

### C. What to pick up for *crafting* (moves into the filter work)
- Clean/gray **elite throw bases** (Winged Axe / Winged Knife / Hyperion Javelin / Ghost Glaive).
- **Jewels** (any quality — craft fuel), **Perfect Amethyst/Ruby/Sapphire**, **Ral / Nef / Tal / Io / Shael** runes.
- **Charms**: skillers (barb combat) and any fire/poison resist small charms.
- Any **all-res / fire-res magic amulet or ring** (your resist holes).

### Warnings
- ⚠ **Hardcore.** No shield, no CBF on anything but Hawkmail (don't drop Hawkmail until replaced), fire/poison gaps. Cap the plan at Arcane Sanctuary as agreed; do **not** push into A3 without fire res ≥ 60.
- ⚠ **Simbilan vs elite base:** upgrading the Simbilan needs 127 Str / 95 Dex — you'd lose 20+ stat points' worth of vitality. Prefer rolling a **new elite base** at alvl 79 rather than upgrading.

---

## 6. Data status / remaining gated work

- Character sheet, 24 equipped charms, all previously documented Inventory tabs, and Mahala's 9 merc screenshots have been reviewed. The current all-items keep/swap/trade recommendations are in `docs/07_Full_Inventory_Action_Matrix.md`; Run 1 details and workbook guide values are in `docs/06_Run_1_Findings_and_Trade_Plan.md`.
- `Item Filter/Hiim_Crafting_Barbarian_Focused.filter` remains unread and must not be opened without explicit authorization.
- A broader PD2 Wiki review and the sorted XLSX trade-price inventory remain separate project tasks. No live HC trade listing was checked in the Run 1 price analysis.
