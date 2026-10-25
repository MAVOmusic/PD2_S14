# 00_CONTEXT_BLOCK.md — paste into a new chat to resume

> Copy this file (or everything below the line) into a new chat. It is the project handoff.
> Updated: **2026-10-25** · Project **v0.5.0** · repo `MAVOmusic/PD2_S14` · session branch `arena/959937bb-pd2-s14`.

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
3. Commit and push to `arena/959937bb-pd2-s14` before reporting results. Keep `main` current through a PR from the session branch. **Never push directly to `main`.**
4. Stay on the fixed Arena branch `arena/959937bb-pd2-s14`. Do not rename or switch branches.
5. Transcribe only what the images show; label uncertain reads `⚠`. Do not invent mods. Tag estimated prices HIGH/MED/LOW confidence and distinguish estimates from verified current listings.
6. Do not start the next Inventory tab until the user confirms that the last push/checkpoint is accepted.

## IMAGE / SOURCE STATUS

- ✅ Vision confirmed: the PNG screenshots are readable.
- Source root: `MAVOmusicHC - Stats - V1.0/`.
- Completed and documented: `01 - Character + Skill Tree` (5 images), `02 - Equipped Items` (12), `03 - Charms` (24), `04 - Inventory/Unique Items Tab` (23 supplied screenshots), and `04 - Inventory/Set Items Tab` (26 supplied screenshots).
- See `docs/02_Character_And_Gear_Snapshot.md`, `docs/03_Charms.md`, `docs/04A_Inventory_Uniques.md`, and `docs/04B_Inventory_Sets.md`.
- Unique Items and Set Items screenshot page counters suggest the screenshots may be partial captures; both docs explicitly limit their scope to the supplied images.
- Remaining Inventory tabs: `Sortables Tab`, `Misc Tab`, `Runes Tab`, `Gems Tab`, `MF Tab`, `GF Tab`, `Maps Tab`, `Ubers Tab`, and `Duplicates - Good Corruption Tab`.
- Also not yet reviewed: `05 - Merc Items/` and `Item Filter/Hiim_Crafting_Barbarian_Focused.filter`.

## SAVED FINDINGS TO CARRY FORWARD

- Hell-applied resistances are Fire 49 / Cold 80 / Lightning 75 / Poison 58; cold/light are overcapped, while fire/poison are the gaps. Charm findings/recommended resists are in `docs/03_Charms.md`.
- Equipped gear/stat details and first-pass farm notes are in `docs/02_Character_And_Gear_Snapshot.md`.
- Unique-item highlights in `docs/04A_Inventory_Uniques.md`: possible upgrades include Infernostride boots (FRW/fire protection), Riphook and Ramfodder for the Act 1 merc, Nokozan Relic as a fire/FHR swap, and The Scalper as a weapon comparison. Candidates only; validate against remaining inventory and merc gear.
- Set-tab highlights in `docs/04B_Inventory_Sets.md`: Cow King's Hooves and Vidala's Fetlock each add 30% FRW versus the current Chain Boots, but Infernostride remains the stronger documented fire-safety option. Set tab contains no elite crafting bases or useful Hell merc weapon upgrade. Most set items are vendor/set-bundle; LLD values are uncertain.
- Trade estimates are not verified live listings. The HC S14 market/pricing basis still needs confirmation before final spreadsheet pricing.

## NEXT CHECKPOINT — WAIT FOR USER CONFIRMATION

**Sortables Tab** is next, but do not open it until the user confirms this Set Items checkpoint/push is visible and accepted.

After remaining inventory, read `05 - Merc Items` and the filter (no more than two source folders in that batch), then finish the farming plan, filter, trade workbook, and gear-swap review. Outstanding decisions: workbook column order, standalone filter vs patch, and HC pricing/currency basis; ask when needed.
