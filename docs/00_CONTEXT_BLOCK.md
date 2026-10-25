# 00_CONTEXT_BLOCK.md — paste this into any new chat to resume

> Copy everything below the line into a new chat. It is self-contained.
> Last updated: **2026-10-25** · Project **v0.2.0** · repo `MAVOmusicHC/PD2_S14` · branch `arena/360df353-pd2-s14` (mirrored to `main`)

---

## WHO / WHAT

I play **Project Diablo 2, Season 14, HARDCORE**.

- Character: **MAVOmusicHC**, Level **77 Barbarian**, **Throw Barb** (Double Throw + Throw Mastery + Frenzy), **0 skill points left**.
- Merc: **Act 1 Rogue (Bow)**.
- Farthest progress: **Hell Act 2 — Canyon of the Magi is painful, so treat Arcane Sanctuary as the practical ceiling.**
- Goal: (a) farm zones for **elite crafting weapon bases for me AND my merc**, (b) check whether anything in my inventory beats what I wear, (c) **rework my item filter** — hide worthless stuff, make genuinely valuable trade items impossible to miss, (d) get an **Excel sheet of every stored item with trade-site prices, sorted most-expensive first** (I have limited trade-site slots).

## REPO LAYOUT (already uploaded — 161 PNGs)

```
MAVOmusicHC - Stats - V1.0/
  Images/
    MAVOmusicHC - 01 - Character + Skill Tree/   (5 imgs)  ✅ READ
    MAVOmusicHC - 02 - Equipped Items/           (12 imgs) ✅ READ
    MAVOmusicHC - 03 - Charms/                   (24 imgs) ⏸ NOT READ
    MAVOmusicHC - 04 - Inventory/                (9 tabs)  ⏸ NOT READ
        Duplicates - Good Corruption, GF, Gems, MF, Maps, Misc, Runes, Set Items, Sortables, Ubers, Unique Items
    MAVOmusicHC - 05 - Merc Items/               (9 imgs) ⏸ NOT READ
  Item Filter/
    Hiim_Crafting_Barbarian_Focused.filter               ⏸ NOT READ
docs/   ← my working files (VERSION, CHANGELOG, WORK_PROTOCOL, snapshots, deliverables)
```

## HARD RULES FOR THE ASSISTANT (do not violate)

1. **Read at most 2 folders per turn, then STOP and wait for my go-ahead.**
2. **Push before reporting.** After each batch: update `docs/VERSION.md`, `docs/CHANGELOG.md`, `docs/00_CONTEXT_BLOCK.md`, commit, `git push origin arena/360df353-pd2-s14` **and** `git push origin arena/360df353-pd2-s14:main`, *then* tell me the results. If a chat dies, nothing is lost.
3. **Mirror every push to `main`** so other chats never need my feature branch.
4. Work only on branch `arena/360df353-pd2-s14`; never switch branches.
5. Mark uncertain screenshot reads with `⚠`; never invent item mods.
6. Prices are estimates — tag confidence HIGH / MED / LOW.

## ANSWERED ALREADY

- ✅ **This chat can read images** (vision confirmed on the screenshots).

## CURRENT STATE (v0.2.0)

Folders **01** and **02** are done. Full transcription in `docs/02_Character_And_Gear_Snapshot.md`. Headlines:

- Stats (no buff → with BO/BC): Str 194, Dex 155, Vit 165, En 34; Life **875 → 1,025**; Mana 211 → 281; Defense 328 → 569.
  Double Throw **1,340–2,577 → 1,413–2,711**; AR **8,345 → 8,671** (and second line 14,681 / 15,255).
- **Resists — the build's hole:** Fire **41 → 49**, Cold **80**, Light **75**, Poison **50 → 58**. In Hell (×−100) that is roughly **Fire −51, Poison −42 → those are what kill me.**
- Skills (icon reads ⚠): ~20 Double Throw, ~20 Throw Mastery, ~13 Double Swing synergy, 1-pt warcries with ~3 extra BO/BC. 0 points left.
- Gear: **Simbilan 343% ED / 23% CB** (main), **Francisca Fool's [Amp] 121% ED + 20% OW** (best item, ~Ist–Gul), **crafted Fanged Helm 27% CB + 20 all-res (def 16 — bad base)**, **Hawkmail** (only CBF source; weak, upgrade target), crafted Plated Belt (28C/21L + 71% GF), Chain Boots (18% MF, 23C/32L, **no FRW**), Heavy Bracers gloves (**weakest slot**, 3% LL / 13% MF), all-res 24% amulet (+10 Str), leech ring 6% LL / 5% MF, **LLD ring (lvl 12, corrupted) → sell to LLD collectors, Um–Ist, don't vendor**.
- Swap: **+2 Barb / 10% IAS Harpoon** and **+3 Warcries Glaive** → pre-buff BO with the Glaive.
- Farm plan draft: **Arcane Sanctuary (alvl 79)** is the best legal spot for **Winged Axe / Winged Knife / Hyperion Javelin / Ghost Glaive**; NM Cows for crafting runes + gems; Canyon of the Magi + Halls of the Dead for bases and gold. Do not push into A3 until fire res ≥ 60.

## NEXT STEPS (in order)

1. ⏭ **Batch 2/6** — read `03 - Charms` + `04 - Inventory` → fixes resist plan, gives the trade-sheet source data and swap candidates.
2. **Batch 3/6** — read `05 - Merc Items` + `Item Filter/Hiim_Crafting_Barbarian_Focused.filter` → merc upgrade list + filter to modify.
3. Deliver **farm plan v1** (zones + what to pick up, self & merc).
4. Deliver **item filter**: either a full custom `.filter` or a tiered patch over Hiim's — hide vendor-trash, top-value trade items get the loudest colour.
5. Deliver **XLSX trade sheet** of all stored items, sorted by estimated trade value, with confidence tags; separate "keep / sell / vendor" columns.

## PENDING DECISIONS I OWE

- [ ] Column order for the XLSX (value-first vs item-first)
- [ ] Standalone filter vs patch over Hiim's filter
- [ ] Pricing basis: HC ladder, values in `HR` equivalents + named runes
