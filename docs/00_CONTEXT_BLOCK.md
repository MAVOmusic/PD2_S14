# 00_CONTEXT_BLOCK.md — paste into a new chat to resume

> Project **v0.15.1** · updated 2026-10-25 · repo `MAVOmusic/PD2_S14` · active session branch `arena/2ad22dfd-pd2-s14`.

---

## PLAYER / GOAL

I play **Project Diablo 2, Season 14 Hardcore**.

- Character: Level **77 Throw Barbarian** (MAVOmusicHC).
- Mercenary: **Mahala, Act 1 Rogue**, level 77.
- Practical progression ceiling: **Hell Act 2 Arcane Sanctuary**; Canyon of the Magi is difficult.
- Long-term goals: identify elite crafting weapon bases and safe farming zones; compare stash items with currently equipped gear; review the item filter only after authorization; prepare a sorted Excel trade sheet; and make item-specific keep/sell/swap/trade recommendations.

## BINDING USER CORRECTIONS

1. **Charms:** the `03 - Charms` tab shows the 24 charms currently equipped/carried on the character. They already contribute to the displayed character stats. Do not treat them as spare stash charms or recommend selling/benching/swapping them without a new stat comparison. Earlier advice in `docs/03_Charms.md` to equip/bench/sell particular charms and calculations that added their stats again is withdrawn.
2. **Merc bow:** Purity is intentionally equipped because Mahala relies on its Prayer healing aura. Keep it until the player says that healing is no longer needed or a tested healing-preserving alternative is available.
3. **Quiver compatibility:** Ramfodder is a bolt quiver and cannot be equipped with the current bow. The player would need to craft/equip a Purity crossbow before trying Ramfodder. Do not recommend it as a current bow-quiver swap.
4. **Next work:** the player asked for an Excel list of unclear icons, then will fill in the descriptions. Only after those are supplied should ambiguous sources be resolved and final swap/keep/sell/trade recommendations produced. Do not read Item Filter now.

## WORKFLOW

- Work only on active branch `arena/2ad22dfd-pd2-s14`; keep `main` current by PR, never direct-push to `main`.
- Read at most two source folders per batch; Inventory subfolders and each named `Runs/Run N` are separate checkpoints. Do not bulk-read ahead.
- For each Run, the player will explicitly identify which folder to review; each Run may contain up to 15 new item images. Only process the named folder.
- Transcribe visible information only; mark uncertain reads. Price ranges are estimates, not live quotes, unless explicitly checked.

## CURRENT DELIVERABLES / STATUS

- Merc gear/stats are in `docs/05_Merc_Gear.md`; all 9 Merc Items screenshots were reviewed. Mahala's current Purity bow + Sharp Arrows remain the baseline due to Prayer healing. Ramfodder is deferred until a Purity crossbow is available.
- Corrected charm status and withdrawn earlier charm swap/sell advice in `docs/03_Charms.md`; character snapshot correction is in `docs/02_Character_And_Gear_Snapshot.md`.
- `docs/Unidentified_Icons_and_Items.xlsx` contains 108 identification rows: 100 unclear inventory/UI icons across Misc, Gems, Maps, and Ubers, plus 8 uncertain skill-tree icon/name checks. The workbook includes source screenshot, tab, location, visual description, uncertainty, and a blank “Your identification / description” column. No item prices are assigned there.
- `Runs/Run 1` through `Runs/Run 10` exist with upload/review instructions in `Runs/README.md`. Limit each folder to 15 new item images; wait for the player's explicit Run selection.
- All 11 inventory subfolders have previously been reviewed and documented (`docs/04A` through `docs/04K`). Misc, Maps and Ubers contain unidentified visuals. No current live trade pricing has been verified.
- **Item Filter source remains unread**: `Item Filter/Hiim_Crafting_Barbarian_Focused.filter`. Do not open until explicitly authorized.

## NEXT STEP — WAIT FOR PLAYER

Present `docs/Unidentified_Icons_and_Items.xlsx` for the player to fill. Once the player supplies the descriptions/completed workbook, match the answers to the referenced source icons and update the relevant records. Then prepare corrected keep/sell/swap/trade conclusions. Separately, wait for the player to name a specific `Runs/Run N` before reading that batch. Do not read Item Filter unless asked.
