# PD2 S14 Project — CHANGELOG

Newest first. Each entry records the scope, deliverables, and synchronization status. Prices elsewhere are estimates, not live trade-site quotes.

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
