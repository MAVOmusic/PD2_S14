# PD2 S14 Project — CHANGELOG

Newest first. Each entry records the scope, deliverables, and synchronization status. Prices elsewhere are estimates, not live trade-site quotes.

---

## v0.17.0 — 2026-10-25

### Read / added
- Read the player's `docs/16-53 Identified.xlsx` update, resolving U-016–U-053: rejuvenation potions, seven Craft Infusions, and 29 named map icons.
- Updated `docs/04D_Inventory_Misc.md` for U-016/U-017 and `docs/04F_Inventory_Gems.md` for U-018–U-024.
- Queried the official PD2 [Maps](https://wiki.projectdiablo2.com/wiki/Maps) page for U-035–U-053 (tier/zone level and map immunities), and cross-checked U-025–U-034. Logged map name/tier/value discrepancies in `docs/04I_Inventory_Maps.md` rather than silently changing player-supplied entries.
- Removed U-016–U-053 from `docs/Unidentified_Icons_and_Items.xlsx`; 55 unresolved rows U-054–U-108 remain. Player upload retained as the source record.
- Updated version, context and protocol to active branch `arena/c5de4f66-pd2-s14`. Broad Wiki review and Item Filter remain deferred.

### Sync status
- Commit/push on the active session branch; sync `main` through a PR (never direct-push).

---

## v0.16.0 — 2026-10-25

### Read / added
- Read the player's update `docs/1-15 Identified.xlsx` and confirmed the first 15 entries (U-001–U-015) are readable.
- Updated `docs/04D_Inventory_Misc.md` with player-supplied names/uses, visible quantities, and the two-cell placements for one Vial of Lightsong and one Lilith's Mirror. Left U-016/U-017 unresolved.
- Checked the specific U-001 Wiki example: Recipes lists `1–15 Jewels + Key → 1–15 Jewel Fragments`; the page notes fragments stack to 50. Linked the relevant page in the Misc document. Broader Wiki research remains deferred until all IDs are complete.
- Removed U-001–U-015 from `docs/Unidentified_Icons_and_Items.xlsx`; 93 unresolved rows remain. Kept the player's `docs/1-15 Identified.xlsx` upload as the source record.
- Set the identification cadence to updates of up to 20 completed lines; Runs remain limited to 15 new images per named Run.

### Sync status
- Commit/push on active branch `arena/c58dcbfc-pd2-s14`; sync `main` through a PR, never direct-push.

---

## v0.15.1 — 2026-10-25

### Corrections / added
- Created `docs/Unidentified_Icons_and_Items.xlsx` with 108 rows: 100 unclear inventory/UI icons across Misc, Gems, Maps and Ubers, plus 8 previously uncertain skill-tree icon/name checks. Each row has its source tab, screenshot, location, current visual description, uncertainty and a blank player-identification field.
- Corrected the Charms interpretation: the 24 charms are currently equipped and their effects are already included in character stats. Withdrawn prior charm equip/bench/sell recommendations and double-counting calculations until a fresh stat comparison is available.
- Corrected the merc gear plan: Purity Prayer healing is relied on, so keep the bow as the current baseline. Ramfodder is a bolt quiver and is not compatible with the bow; revisit only after a Purity crossbow is crafted/equipped.
- Created `Runs/Run 1` through `Runs/Run 10` and `Runs/README.md`; maximum 15 new item images per Run, and only process the Run the player explicitly names.
- Item Filter remains unread. Await the player's completed icon-identification workbook before final keep/sell/swap/trade conclusions.
- Updated version, context and work protocol for active branch `arena/2ad22dfd-pd2-s14`.

### Sync status
- Commit/push to the session branch and sync `main` via PR; never push directly to `main`.

---

## v0.15.0 — 2026-10-25

### Read / added
- Read all 9 screenshots in `MAVOmusicHC - Stats - V1.0/Images/MAVOmusicHC - 05 - Merc Items/` (Merc Items only; Item Filter was not opened).
- Added `docs/05_Merc_Gear.md` with Mahala's level 77 stats, no-buff/with-buff screens, all equipped gear slots plus arrows, and visible mods.
- Recorded uncertainty around the gold Sigon's 10% life-leech tooltip line and did not assume buff source or difficulty display convention.
- Compared Purity and current arrows against documented stash candidates (Riphook, Ramfodder, damage Sharp Arrows), and assessed boot/armor swaps with explicit resistance tradeoffs. HC recommendations are cautious safe-area tests, not blind swaps.
- No live prices assigned to equipped merc gear. Item Filter remains unread pending explicit confirmation.
- Updated version/context/protocol for active branch `arena/5f5eb123-pd2-s14`.

### Sync status
- Commit and push to the session branch; sync `main` through a PR (never direct-push to `main`). Stop for user confirmation before reading Item Filter.

---

## v0.14.0 — 2026-10-25

### Read / added
- Read the single image in `MAVOmusicHC - Stats - V1.0/Images/MAVOmusicHC - 04 - Inventory/Duplicates - Good Corruption Tab/`.
- Added `docs/04K_Inventory_Duplicates.md` for a corrupted Sigon's Wrap Plated Belt: +10% Increased Chance of Blocking, +20 Life, +20% Fire Res, required level 6.
- Cross-referenced the separate Sigon's Wrap [C] in Sortables (+13% Pierce) and preserved both as distinct observed copies/corruptions.
- Marked it as niche LLD sale-check only; rough Pul–Mal estimate is LOW confidence and not based on live listings.
- This completes review of all 11 Inventory tabs. Updated version/context/protocol docs for active branch `arena/78b69598-pd2-s14`.
- Next source batch is `05 - Merc Items` plus `Item Filter`; wait for explicit user confirmation before reading either.

### Sync status
- Commit and push to the session branch; sync `main` through a PR (never direct-push to `main`).

---

## v0.13.0 — 2026-10-25

### Read / added
- Read the single `Ubers.PNG` overview in `MAVOmusicHC - Stats - V1.0/Images/MAVOmusicHC - 04 - Inventory/Ubers Tab/`.
- Added `docs/04J_Inventory_Ubers.md`, recording the 10-icon left grid and 16-icon right grid, with the only visible `1` overlay noted.
- No item identities, stack quantities or prices are guessed: the screenshot has no tooltips. Warned not to vendor any Uber-tab items until identified.
- Updated version/context/protocol docs for the active branch `arena/6cc2977c-pd2-s14`. Next tab is Duplicates - Good Corruption; stop for user confirmation after pushing.

### Sync status
- Commit and push to the session branch; sync `main` through a PR (never direct-push to `main`).

---

## v0.12.0 — 2026-10-25

### Read / added
- Read all three map-tier screenshots in `MAVOmusicHC - Stats - V1.0/Images/MAVOmusicHC - 04 - Inventory/Maps Tab/`.
- Added `docs/04I_Inventory_Maps.md`, recording Tier 1/2/3 labels, visible map-shaped tile counts (10/10/9), and the repeated 3×7 lower grid.
- Filenames say “No Maps,” but map-shaped icons appear in the tier grids. No tooltip, quantity, or ownership indicator is visible, so they are not counted as owned/saleable maps and no prices are assigned.
- Updated version/context/protocol docs for active branch `arena/c738bbe3-pd2-s14`. Next tab is Ubers; stop for user confirmation after pushing.

### Sync status
- Commit and push to the session branch; sync `main` through a PR (never direct-push to `main`).

---

## v0.11.0 — 2026-10-25

### Read / added
- Read all 8 screenshots in `MAVOmusicHC - Stats - V1.0/Images/MAVOmusicHC - 04 - Inventory/GF Tab/`.
- Added `docs/04H_Inventory_GF.md` with 2 crafted LLD rings, a corrupted +83% GF LLD amulet, 2 GF Grand Charms, and 3 +10% GF Small Charms transcribed. Combined visible GF: +260%.
- Prioritized the corrupted amulet and +40% GF / +104 AR ring for a price check; recommended bundling the GF charms rather than spending separate listing slots. No combat swap advised solely for GF in Hardcore.
- Price ranges are low-confidence estimates, not verified live HC S14 listings.
- Updated version/context/protocol docs for active branch `arena/f1a0fa3f-pd2-s14`. Next tab is Maps; stop for user confirmation after pushing.

### Sync status
- Commit and push to the session branch; sync `main` through a PR (never direct-push to `main`).

---

## v0.10.0 — 2026-10-25

### Read / added
- Read all three supplied screenshots in `MAVOmusicHC - Stats - V1.0/Images/MAVOmusicHC - 04 - Inventory/MF Tab/`.
- Added `docs/04G_Inventory_MF.md` with the corrupted LLD MF/resist amulet, 22% MF Battle Gauntlets, and 36% MF Nagelring transcribed.
- Marked the amulet and Nagelring as potential sale/MF-swap candidates, but warned against sacrificing life leech or Hardcore resistances without compensating gear. Battle Gauntlets' status as craft base vs finished item remains uncertain.
- Added rough confidence-tagged tradeability estimates; no live HC S14 listing was checked.
- Updated version/context/protocol docs for active branch `arena/c08afd55-pd2-s14`. Next tab is GF; stop for user confirmation after pushing.

### Sync status
- Commit and push to the session branch; sync `main` through a PR (never direct-push to `main`).

---

## v0.9.0 — 2026-10-25

### Read / added
- Read `MAVOmusicHC - Stats - V1.0/Images/MAVOmusicHC - 04 - Inventory/Gems Tab/Gems.PNG`.
- Added `docs/04F_Inventory_Gems.md`, transcribing 116 visible gems: 8 chipped, 9 flawed, 7 normal, 6 flawless and 86 perfect.
- Perfect-gem counts: Ruby 8, Amethyst 13, Sapphire 9, Emerald 13, Topaz 16, Diamond 16, Skull 11. The seven unnumbered bottom-row icons are left unidentified/not counted.
- No trade prices assigned without current HC S14 listings. Recommended hold/bundle/craft triage; trade-site bulk price verification remains needed.
- Updated version/context/protocol files for active branch `arena/734a136e-pd2-s14`. Next tab is MF; stop for user confirmation after pushing.

### Sync status
- Commit and push to the session branch; sync `main` through a PR (never direct-push to `main`).

---

## v0.8.0 — 2026-10-25

### Read / added
- Read the single Runes Tab screenshot: `MAVOmusicHC - Stats - V1.0/Images/MAVOmusicHC - 04 - Inventory/Runes Tab/Runes.PNG`.
- Added `docs/04E_Inventory_Runes.md`, mapping the 33 positions in standard El-to-Zod order and recording visible stack quantities (147 runes total).
- Rune counts are visually clear; names are medium-confidence because there are no hover tooltips. Highest shown is Gul ×1; no Um or higher rune is present.
- Left trade prices unassigned pending current HC S14 listings. Noted likely trade prioritization: Gul individually; Lem/Pul bundled or held; common low runes not individually listed.
- Updated version/context/protocol docs for active branch `arena/f469fe0a-pd2-s14`. Next tab is Gems; stop for user confirmation after pushing.

### Sync status
- Commit and push to the session branch; sync `main` through a PR (never direct-push to `main`).

---

## v0.7.0 — 2026-10-25

### Read / added
- Read `MAVOmusicHC - Stats - V1.0/Images/MAVOmusicHC - 04 - Inventory/Misc Tab/Misc.PNG` (one overview screenshot).
- Added `docs/04D_Inventory_Misc.md`; recorded 17 visible slots and all discernible stack counts, while explicitly leaving item identities and prices unknown because no tooltips are shown.
- Flagged the 45-count multicolor cluster, 3-count red shard, and 223-count purple potion-like stack for tooltip follow-up. No items are priced or recommended for vendor/sale from appearance alone.
- Updated version/context/protocol files for active branch `arena/e21a31e0-pd2-s14`. Next tab is Runes; stop for user confirmation after pushing.

### Sync status
- Commit and push to the session branch; sync `main` through a PR (never direct-push to `main`).

---

## v0.6.0 — 2026-10-25

### Read / added
- Read all 31 supplied screenshots in `MAVOmusicHC - Stats - V1.0/Images/MAVOmusicHC - 04 - Inventory/Sortables Tab/`.
- Added `docs/04C_Inventory_Sortables.md` with transcriptions and provisional HC tradeability/swap triage.
- Important gear candidates: a crafted Jawbone Cap with +2 Throwing Mastery, +2 Shout, +2 Double Swing and 6% mana leech (but no all-res/CB); corrupted Sharkskin Boots with 40 FRW and 38 poison res (but loss of current cold/light res); a second observed Nokozan Relic roll; and a Great Pilum to compare against the Fool's Francisca.
- Trade candidates include a corrupted high-FRW/resist boot, Assassin Traps skiller with fire damage, 15 IAS / 4 poison-skill jewel, LLD damage/strength/MF jewel, 10 FCR dual-res ring and Paladin Combat skiller. Values are rough, low-confidence HC estimates, not live quotes.
- No clean blank elite throwing-weapon crafting base was shown. The ethereal Diamond Mail already has affixes; the Great Pilum and Simbilan are modified/crafted items.
- Updated version/context/protocol docs for the active branch `arena/5075a7b7-pd2-s14`. Next tab is Misc; stop for explicit confirmation after pushing this tab.

### Sync status
- Commit and push to the session branch; sync `main` through a PR (never direct-push to `main`).

---

## v0.5.0 — 2026-10-25

### Read / added
- Read all 26 supplied screenshots in `MAVOmusicHC - Stats - V1.0/Images/MAVOmusicHC - 04 - Inventory/Set Items Tab/`.
- Added `docs/04B_Inventory_Sets.md` with 26 item transcriptions, visible set-piece groups, practical keep/sell/vendor triage, and confidence-tagged HC tradeability estimates.
- Flagged clipped values on Civerb's Ward, Milabrega's Orb, and Cathan's Rule rather than guessing. The in-game counter indicates 32 pages, so the screenshots may be a partial capture.
- Key practical candidates: Cow King's Hooves and Vidala's Fetlock both offer 30% FRW versus current Chain Boots; previously recorded Infernostride remains the stronger fire-safety option. No elite crafting bases or useful Hell Act 1 merc weapon upgrade were found in this tab.
- Synced through PR #2; next tab was Sortables, awaiting user confirmation.

---

## v0.4.1 — 2026-10-25

### Handoff / protocol reconciliation
- Re-verified that this session can read the PNG images (opened `01 - Character + Skill Tree/Stats - No Buff.PNG`).
- Reconciled stale version/context/protocol documents with the earlier Arena session branch `arena/cb987047-pd2-s14`, based on `fd15029a02072770a6d6dc8181262bd6052b97fd` (`v0.4.0`).
- Clarified that changes are committed and pushed to a fixed working branch; `main` synchronization must happen through a PR, never by direct push.
- The earlier chat reported that 24 Set Items screenshots had been opened before the context-limit interruption, but no findings were saved. The Set Items tab has since been re-read and documented in v0.5.0.
- This handoff correction was merged into main through PR #1; later Arena continuation branches are recorded in the current VERSION/context files.

---

## v0.4.0 — 2026-10-25

### Read / added
- `MAVOmusicHC - Stats - V1.0/Images/MAVOmusicHC - 04 - Inventory/Unique Items Tab/` — 23 screenshots transcribed in `docs/04A_Inventory_Uniques.md`.
- The screenshots' page counters suggest the in-game tab may contain more uniques than the 23 screenshots supplied; this uncertainty is recorded in the item document.
- Added unique-item swap candidates and a first-pass trade-priority list. Values are estimates with confidence labels, not verified live listings.

---

## v0.3.0 — 2026-10-25

### Player correction (applied)
- Character-sheet resistances are already Hell-applied: Fire 49 / Cold 80 (true 99) / Light 75 (true 83) / Poison 58.
- Retracted v0.2.0's “resists are the crisis” interpretation. Fire is 26 below cap and poison 17 below; charms can address both. Cold/light are overcapped by 19/8 points.
- Belt and boots should be evaluated as mobility/IAS/leech/life upgrade slots, not automatically as resistance slots.

### Read / added
- `MAVOmusicHC - Stats - V1.0/Images/MAVOmusicHC - 03 - Charms/` — all 24 files (14 SC, 6 GC, 4 LC).
- `docs/03_Charms.md` — charm table, owned-charm resistance recommendation, overcap analysis and estimated values.
- Findings recorded there include no torch/annihilus/Gheed's/skiller; an SC All Res 5% + 4% MF; and an LLD light-damage/resistance SC that should not be vendored.

---

## v0.2.0 — 2026-10-25

### Read / added
- `01 - Character + Skill Tree/` — 5 screenshots; `02 - Equipped Items/` — 12 screenshots.
- `docs/02_Character_And_Gear_Snapshot.md` — transcribed stats/skills/equipped gear and initial farm notes.
- Skill-name/icon uncertainties are marked for verification; trade values are estimates.

---

## v0.1.0 — 2026-10-25

### Added
- Repository inventory: 161 PNG screenshots in six top-level source folders plus `Item Filter/Hiim_Crafting_Barbarian_Focused.filter`.
- Vision check passed; this chat can read the screenshots.
- Initial folder batching and save/push protocol.
