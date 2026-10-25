# 00_CONTEXT_BLOCK.md — paste into a new chat to resume

> Project **v0.16.0** · updated 2026-10-25 · repo `MAVOmusic/PD2_S14` · active session branch `arena/c58dcbfc-pd2-s14`.

---

## PLAYER / GOAL

I play **Project Diablo 2, Season 14 Hardcore**.

- Character: Level **77 Throw Barbarian** (MAVOmusicHC).
- Mercenary: **Mahala, Act 1 Rogue**, level 77.
- Practical progression ceiling: **Hell Act 2 Arcane Sanctuary**; Canyon of the Magi is difficult.
- Long-term goals: identify elite crafting weapon bases and safe farming zones; compare stash items with currently equipped gear; review the item filter only when authorized; prepare a sorted trade sheet; and make item-specific keep/sell/swap/trade recommendations.

## BINDING USER CORRECTIONS

1. **Charms:** the `03 - Charms` tab shows the 24 charms currently equipped/carried on the character. They already contribute to displayed character stats. Do not treat them as spare charms or recommend selling/benching/swapping them without a fresh stat comparison. Earlier charm recommendations/double-counted calculations are withdrawn.
2. **Merc bow:** Purity is intentionally equipped because Mahala relies on its Prayer healing aura. Keep it until the player says healing is no longer needed or a tested alternative preserves it.
3. **Quiver compatibility:** Ramfodder is a bolt quiver and cannot be equipped with the current bow. The player would need to craft/equip a Purity crossbow before trying Ramfodder.
4. **Identification workflow:** player supplies descriptions in batches of up to 20 rows. Record each batch, update related docs, then remove completed rows from the unresolved workbook. The separate player-uploaded identification workbook is retained as the source record.
5. **Future Wiki research:** after all identification is complete, review the relevant Project Diablo 2 Wiki information to validate mechanics and improve conclusions. Do not do the broad Wiki review early.

## WORKFLOW

- Work only on active branch `arena/c58dcbfc-pd2-s14`; keep `main` current via PR, never direct-push to `main`.
- Read at most two source folders per batch. Inventory subfolders and each named `Runs/Run N` are separate checkpoints; do not bulk-read ahead.
- The player names the Run to review; each Run allows up to 15 new item images. Do not read other Runs.
- Transcribe visible information only, mark uncertainty, and distinguish estimates from live quotes.

## CURRENT DELIVERABLES / STATUS

- **First identification batch complete:** the player's `docs/1-15 Identified.xlsx` identifies U-001–U-015. The resolved items and relevant notes are now recorded in `docs/04D_Inventory_Misc.md`; those 15 rows are removed from `docs/Unidentified_Icons_and_Items.xlsx`. The unresolved tracker now has 93 rows (85 inventory/UI entries + 8 skill-icon checks).
- Identified Misc items: Jewel Fragments ×45, Larzuk's Puzzlepiece ×1, Demonic Cube, one two-cell Vial of Lightsong, one two-cell Lilith's Mirror, Worldstone Shards ×3, Larzuk's Puzzlebox, Tainted Worldstone Shard, two Twisted Essences of Suffering, Charged Essence of Hatred, Burning Essence of Terror, Festering Essence of Destruction ×1, and Token of Absolution. Remaining Misc icons U-016 and U-017 are unconfirmed purple potion-shaped stacks (2 and 223).
- Specific Wiki check complete for the player's U-001 example: Recipes page has `1–15 Jewels + Key → 1–15 Jewel Fragments`; fragments have no affixes and stack to 50. This line is in the Consumables table immediately before the Breakdown Recipes subsection. See `docs/04D_Inventory_Misc.md`. Broad Wiki review is deferred until all IDs are completed.
- The corrected charm status is documented in `docs/03_Charms.md`; the character snapshot is corrected in `docs/02_Character_And_Gear_Snapshot.md`.
- Merc gear/stats are in `docs/05_Merc_Gear.md`; Purity + Sharp Arrows remains the baseline due to Prayer healing. Ramfodder is deferred until a Purity crossbow is available.
- The unresolved workbook is `docs/Unidentified_Icons_and_Items.xlsx`. It originally contained 108 rows; 15 resolved rows were removed, leaving 93. Keep stable IDs (U-016 onward) and update batches in blocks of up to 20.
- `Runs/Run 1` through `Runs/Run 10` exist with instructions in `Runs/README.md`; 15 new item images maximum per Run. Wait for the player to name a Run before reading it.
- All 11 inventory subfolders were previously reviewed and documented (`docs/04A` through `docs/04K`). Item Filter remains unread and must not be opened unless explicitly authorized.

## NEXT STEP

Wait for the player's next identification batch (up to 20 rows). Record the answers, update source inventory notes, remove resolved lines from the unresolved tracker, and update version/context/changelog. Continue to defer broad Wiki research until all identifications are done. Do not read Item Filter unless explicitly asked.
