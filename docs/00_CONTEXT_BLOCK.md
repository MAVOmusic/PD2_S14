# 00_CONTEXT_BLOCK.md — paste into a new chat to resume

> Copy this file (or everything below the line) into a new chat. It is the project handoff.
> Updated: **2026-10-25** · Project **v0.11.0** · repo `MAVOmusic/PD2_S14` · session branch `arena/f1a0fa3f-pd2-s14`.

---

## PLAYER / GOAL

I play **Project Diablo 2, Season 14 Hardcore**.

- Character: Level **77 Throw Barbarian** (MAVOmusicHC).
- Mercenary: **Act 1 Rogue**.
- Practical progression ceiling: **Hell Act 2 Arcane Sanctuary**; Canyon of the Magi is difficult.
- Goals: identify elite crafting weapon bases and safe farming zones for me and my merc; compare stash items with equipped gear; tune/create an item filter that emphasizes useful and high-trade-value drops while hiding redundant/vendor-trash items; produce a sorted Excel trade sheet of stored items with estimated PD2 trade values.

## MANDATORY WORKFLOW

1. Read **at most two source folders per batch**, then stop for confirmation before starting another batch.
2. For the Inventory folder, treat each tab subfolder as a checkpoint: complete only one tab, save its findings and update `VERSION.md`, `CHANGELOG.md`, and this context file, commit/push to the session branch, then stop and wait for the user's explicit confirmation before opening the next tab.
3. Commit and push to `arena/f1a0fa3f-pd2-s14` before reporting results. Keep `main` current through a PR from the session branch. **Never push directly to `main`.**
4. Stay on the fixed Arena branch `arena/f1a0fa3f-pd2-s14`. Do not rename or switch branches.
5. Transcribe only what the images show; label uncertain reads `⚠`. Do not invent mods. Tag estimated prices HIGH/MED/LOW confidence and distinguish estimates from verified current listings.
6. Do not start the next Inventory tab until the user confirms that the last push/checkpoint is accepted.

## IMAGE / SOURCE STATUS

- ✅ Vision confirmed: the PNG screenshots are readable.
- Source root: `MAVOmusicHC - Stats - V1.0/`.
- Completed and documented: `01 - Character + Skill Tree` (5 images), `02 - Equipped Items` (12), `03 - Charms` (24), `04 - Inventory/Unique Items Tab` (23 supplied screenshots), `Set Items Tab` (26), `Sortables Tab` (31), `Misc Tab` (one overview screenshot), `Runes Tab` (one full-grid screenshot), `Gems Tab` (one full-grid screenshot), `MF Tab` (3 screenshots), and `GF Tab` (8 screenshots).
- See `docs/02_Character_And_Gear_Snapshot.md`, `docs/03_Charms.md`, and `docs/04A_Inventory_Uniques.md` through `docs/04H_Inventory_GF.md`.
- Unique Items and Set Items counters suggest their screenshots may be partial captures; each doc limits its scope to supplied images.
- The Misc overview has no item tooltips; its 17 visible slots and stack numbers are recorded but mostly unidentified. Do not price or vendor these by icon alone; tooltip screenshots are needed.
- Rune quantities are visually clear, but names are mapped from standard El-to-Zod grid order without hover labels (medium confidence). Total 147; highest shown Gul ×1, no Um+.
- Gems tab records 116 counted gems: 86 Perfect (Ruby 8, Amethyst 13, Sapphire 9, Emerald 13, Topaz 16, Diamond 16, Skull 11). Seven unnumbered bottom-row icons remain unidentified/not counted.
- MF tab has an LLD amulet (31% MF, +14 all res, +6 Str), 22% MF Battle Gauntlets (craft-base status uncertain), and 36% MF Nagelring.
- GF tab records 8 items totaling +260% visible GF: a corrupted LLD amulet (+83 GF), two GF rings (+40 / +36), two GF Grand Charms (+38 / +33) and three 10-GF Small Charms. Prices remain low-confidence estimates.
- Remaining Inventory tabs: `Maps Tab`, `Ubers Tab`, and `Duplicates - Good Corruption Tab`.
- Also not yet reviewed: `05 - Merc Items/` and `Item Filter/Hiim_Crafting_Barbarian_Focused.filter`.

## SAVED FINDINGS TO CARRY FORWARD

- Hell-applied resistances are Fire 49 / Cold 80 / Lightning 75 / Poison 58; cold/light are overcapped, while fire/poison are the gaps. Charm findings/recommended resists are in `docs/03_Charms.md`.
- Equipped gear/stat details and first-pass farm notes are in `docs/02_Character_And_Gear_Snapshot.md`.
- Unique-item candidates in `docs/04A_Inventory_Uniques.md` include Infernostride, Riphook, Ramfodder, Nokozan Relic and The Scalper; validate versus full stash and merc gear.
- Set-tab notes in `docs/04B_Inventory_Sets.md`: Cow King's Hooves and Vidala's Fetlock each add 30% FRW; Infernostride remains the stronger documented fire-safety option.
- Sortables notes in `docs/04C_Inventory_Sortables.md`: potentially useful Sharkskin Boots (40 FRW, +38 poison res), crafted Jawbone Cap (+2 Throwing Mastery / Shout / Double Swing, 6% mana leech but loses helm res/CB), possible second Nokozan Relic roll, Great Pilum comparison, 10 FCR dual-res ring, and niche charms/jewels. Respect resistance tradeoffs before equipping anything in Hardcore.
- No clean blank elite throwing-weapon base has been identified yet. Trade estimates are rough and not live listing quotes; pricing basis still needs confirmation.

## NEXT CHECKPOINT — WAIT FOR USER CONFIRMATION

The GF tab is documented in `docs/04H_Inventory_GF.md`. The next tab is **Maps Tab**; do not read it until the user confirms this push/checkpoint is visible and accepted.

After remaining inventory, read `05 - Merc Items` and the filter (no more than two source folders in that batch), then finish the farming plan, filter, trade workbook, and gear-swap review. Outstanding decisions: workbook column order, standalone filter vs patch, and HC pricing/currency basis; ask when needed.
