# 00_CONTEXT_BLOCK.md — paste into a new chat to resume

> Project **v0.23.0** · updated 2026-10-26 · repo `MAVOmusic/PD2_S14` · active session branch `arena/a6017600-pd2-s14`.

---

## PLAYER / GOAL

I play **Project Diablo 2, Season 14 Hardcore**.

- Character: Level **77 Throw Barbarian** (MAVOmusicHC).
- Mercenary: **Mahala, Act 1 Rogue**, level 77.
- Practical progression ceiling: **Hell Act 2 Arcane Sanctuary**; Canyon of the Magi is difficult.
- Long-term goals: identify elite crafting weapon bases and safe farming zones; compare stash items with currently equipped gear; review the item filter only when authorized; prepare a sorted trade sheet; and make item-specific keep/sell/swap/trade recommendations.

## BINDING USER CORRECTIONS

1. **Charms:** the `03 - Charms` tab shows the 24 charms currently equipped/carried on the character. They already contribute to displayed character stats. Do not treat them as spare charms or recommend selling/benching/swapping them without a fresh stat comparison. Earlier charm recommendations/double-counted calculations are withdrawn.
2. **Merc bow:** Purity is intentionally equipped because Mahala relies on its Prayer healing aura. Keep the current bow + Sharp Arrows baseline until a tested alternative preserves healing and survivability. Current screenshot transcribes Prayer level 2 while current PD2 Wiki lists level 10–12; verify the live tooltip.
3. **Sigon's merc belt:** the player reports `04B #13` Sigon's Wrap with +13% Pierce now equipped with Sigon's Visor + Shelter; `04K #1` is a distinct +10% block copy. Wiki lists +10% leech at 2 pieces, +100 Defense at 3, and +2 Defense/level on the Wrap while two pieces are worn (+154 at merc level 77). The post-swap merc sheet has not been supplied; don't present calculated defense/pierce as live.
4. **Quiver compatibility:** Ramfodder is Light Bolts, not arrows. Purity can be made in a 3-socket crossbow; craft a second copy and keep the Long Bow. Verify bolt penetration/attack frames in-game before use.
5. **Throw Barbarian mechanics:** Double Throw's bounce behavior is distinct from Pierce; Throwing Mastery adds pierce to thrown attacks. Keep the Fool's Amp weapon for physical resistance support; compare the Simbilan/Scalper as a weapon-pair test and count 20% IAS only if it crosses a live Double Throw breakpoint.
6. **Identification workflow:** player supplies descriptions in batches of up to 20 rows. Record each batch, update related docs, then remove completed rows from the unresolved workbook. Preserve player-uploaded identification workbooks as source records.
7. **Wiki research:** all icon identifications are now complete, so the planned broader Project Diablo 2 Wiki review is due. The focused Barbarian skill-tree review has been completed and documented; continue broader relevant pages in subsequent checkpoints. Item Filter remains separately gated on explicit authorization.

## WORKFLOW

- Work only on active branch `arena/a6017600-pd2-s14`; keep `main` current via PR, never direct-push to `main`.
- Read at most two source folders per batch. Inventory subfolders and each named `Runs/Run N` are separate checkpoints; do not bulk-read ahead.
- The player names the Run to review; each future Run allows up to 15 new item images unless the player explicitly revises the cap. For Run 1 only, the player explicitly authorized all 23 images, now reviewed; do not read other Runs without a named checkpoint.
- Transcribe visible information only, mark uncertainty, and distinguish estimates from live quotes.

## CURRENT DELIVERABLES / STATUS

- **First identification batch U-001–U-015:** recorded in `docs/04D_Inventory_Misc.md`; source `docs/1-15 Identified.xlsx` retained.
- **Second identification batch U-016–U-053:** supplied in `docs/16-53 Identified.xlsx`. U-016/U-017 are Small/Large Rejuvenation Potions; U-018–U-024 are Blood, Caster, Hitpower, Safety, Bountiful, Brilliant and Vampiric Craft Infusions; U-025–U-053 are named map icons. Details are recorded in `docs/04D_Inventory_Misc.md`, `docs/04F_Inventory_Gems.md`, and `docs/04I_Inventory_Maps.md`.
- All icon IDs U-001–U-108 are identified; `docs/Unidentified_Icons_and_Items.xlsx` now has no unresolved data rows. U-075–U-100 are recorded in `docs/04J_Inventory_Ubers.md`; U-101–U-108 and the PD2 Barbarian skill-tree explanation are in `docs/02_Character_And_Gear_Snapshot.md`.
- For U-035–U-067, the official [Maps Wiki page](https://wiki.projectdiablo2.com/wiki/Maps) was checked for tier/zone level and map immunities. The Wiki lists T1 87, T2 88, T3 89. Differences requiring player confirmation: U-025 Lightning 75 vs Wiki 100; U-033 Sanatorium is Wiki T2 and `Magic 1050` likely should be 105; U-040 “Ruined Temple” has no exact Wiki entry (possible Ruined Cistern); U-047 Wiki summary omits Cold although its monster table lists Cold 140. For U-054–U-067, the Maps Modification table was checked for recipes/effects; U-063 is Wiki-spelled “Orb of Destruction.”
- For U-001, Recipes Wiki confirmed `1–15 Jewels + Key → 1–15 Jewel Fragments`, stack limit 50; see `docs/04D_Inventory_Misc.md`.
- **Run 1 gear/trade review is complete:** all 23 explicitly authorized images plus relevant `PD2info.xlsx` sheets are recorded in `docs/06_Run_1_Findings_and_Trade_Plan.md`. The player reports equipping Run 1 Gauntlets + Mesh Belt + `04C #14` four-res ring on the Barbarian and `04B #13` Sigon's Wrap on Mahala; no post-swap stat screenshots were supplied. `docs/08_Vendor_Trade_Queue.md` gives the current keep/rollback/trade/vendor shortlist. The three Run 1 runes update the rune count to 150 in `docs/04E_Inventory_Runes.md`.
- **Full item-by-item review is complete** in `docs/07_Full_Inventory_Action_Matrix.md`: current Barbarian and mercenary slots; all 24 equipped charms; each documented item row in `docs/04A`–`04K`; Run 1 finds; runes, gems, consumables, map/Uber items; and source locations for unresolved names/quantities. PR #19 and status-only PR #20 are merged. Current user-reported equipment is recorded in docs `02`, `05`, `06`, and `07`; vendor/trade actions are summarized in `docs/08_Vendor_Trade_Queue.md`.
- All 24 player charms remain equipped and reflected in the historical pre-swap stats. Current player-reported package is Gauntlets + Mesh Belt + `04C #14` ring; retain Heavy Bracers, Plated Belt and former LLD ring as rollback pieces until verified. Mahala's current reported set is Visor + Shelter + `04B #13` Wrap, with Purity + Sharp Arrows baseline. Tal's/arrow/crossbow comparisons remain optional.
- `Runs/Run 1` through `Runs/Run 10` exist. Future Runs are limited to 15 new images unless explicitly revised; Run 1's 23 images were a one-time authorized exception. Wait for the player to name a specific Run before reading it.
- All 11 inventory subfolders were reviewed previously (`docs/04A` through `docs/04K`). Item Filter remains unread and must not be opened without explicit authorization. Workbook price estimates are Softcore/community guidance, not live HC quotes.

## NEXT STEP

The vendor/trade shortlist is ready in `docs/08_Vendor_Trade_Queue.md`; current swaps are player-reported and need fresh stat checks before selling rollback gear. The player says Run 2 images will follow; do not open them until supplied, and respect the 15-image limit. Item Filter remains unauthorized.
