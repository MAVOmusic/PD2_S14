# 00_CONTEXT_BLOCK.md — paste into a new chat to resume

> Copy this file (or everything below the line) into a new chat. It is the project handoff.
> Updated: **2026-10-25** · Project **v0.14.0** · repo `MAVOmusic/PD2_S14` · session branch `arena/78b69598-pd2-s14`.

---

## PLAYER / GOAL

I play **Project Diablo 2, Season 14 Hardcore**.

- Character: Level **77 Throw Barbarian** (MAVOmusicHC).
- Mercenary: **Act 1 Rogue**.
- Practical progression ceiling: **Hell Act 2 Arcane Sanctuary**; Canyon of the Magi is difficult.
- Goals: identify elite crafting weapon bases and safe farming zones for me and my merc; compare stash items with equipped gear; tune/create an item filter that emphasizes useful and high-trade-value drops while hiding redundant/vendor-trash items; produce a sorted Excel trade sheet of stored items with estimated PD2 trade values.

## MANDATORY WORKFLOW

1. Read **at most two source folders per batch**, then stop for confirmation before starting another batch.
2. For the Inventory folder, each tab subfolder is its own checkpoint. Complete one tab, update its document plus `VERSION.md`, `CHANGELOG.md`, and this context file, commit/push, then stop for the user's confirmation before opening another tab.
3. Commit and push to `arena/78b69598-pd2-s14` before reporting. Keep `main` current via a PR from the working branch. **Never push directly to `main`.**
4. Stay on the fixed Arena branch `arena/78b69598-pd2-s14`; never rename or switch branches.
5. Transcribe only visible information; use `⚠` for uncertainty; do not invent item mods. Price estimates need HIGH/MED/LOW confidence and must be distinguished from live listing quotes.
6. The user confirmed the Duplicates tab only. Wait for explicit confirmation before reading the next source folders, `05 - Merc Items` and Item Filter.

## IMAGE / SOURCE STATUS

- ✅ Vision confirmed: PNG screenshots are readable.
- Source root: `MAVOmusicHC - Stats - V1.0/`.
- Character/gear/charms reviewed: `01 - Character + Skill Tree` (5 images), `02 - Equipped Items` (12), `03 - Charms` (24).
- All 11 Inventory tabs reviewed and documented: Unique Items (23 supplied screenshots), Set Items (26), Sortables (31), Misc (1), Runes (1), Gems (1), MF (3), GF (8), Maps (3), Ubers (1), Duplicates - Good Corruption (1).
- See `docs/02_Character_And_Gear_Snapshot.md`, `docs/03_Charms.md`, and `docs/04A_Inventory_Uniques.md` through `docs/04K_Inventory_Duplicates.md`.
- Unique Items and Set Items screenshot counters suggest partial captures; docs limit their scope to supplied images.
- Misc screenshot has no hover tooltips: 17 slots recorded visually, item IDs/prices unknown. Do not vendor by icon alone.
- Runes: 147 total mapped by standard El-to-Zod grid order (medium confidence); highest Gul ×1, no Um+.
- Gems: 116 counted (86 perfect); seven unnumbered bottom-row icons remain unknown/not counted.
- MF: corrupted LLD amulet (31% MF, +14 all res, +6 Str), 22% MF Battle Gauntlets (craft-base status uncertain), Nagelring (36% MF).
- GF: 8 items with +260% combined GF (corrupted +83 GF amulet; rings +40/+36; GCs +38/+33; three 10-GF SCs). Prices low-confidence.
- Maps filenames say “No Maps”; map-like tier UI icons do not confirm ownership/counts. Do not list or value as owned maps without tooltips.
- Ubers screenshot has 26 item-like icons (10 left, 16 right), identities/quantities unverified. Do not vendor without identifying.
- Duplicates tab: Sigon's Wrap [C] (+10% block, +20 Life, +20 Fire Res, req 6), separate from the Sortables Sigon's Wrap [C] (+13% Pierce). See `docs/04K_Inventory_Duplicates.md`.
- Still not read: `05 - Merc Items/` and `Item Filter/Hiim_Crafting_Barbarian_Focused.filter`.

## SAVED FINDINGS TO CARRY FORWARD

- Hell-applied resistances are Fire 49 / Cold 80 / Lightning 75 / Poison 58; cold/light are overcapped, fire/poison are gaps. Charm analysis is in `docs/03_Charms.md`.
- Equipped gear/stats and first-pass farm notes are in `docs/02_Character_And_Gear_Snapshot.md`.
- Unique candidates include Infernostride, Riphook, Ramfodder, Nokozan Relic and The Scalper; validate against merc gear and full inventory.
- Other candidates in docs: Cow King's Hooves/Vidala's Fetlock (FRW), corrupted Sharkskin Boots (40 FRW/+38 poison res), crafted Jawbone Cap (+2 Throwing Mastery/Shout/Double Swing; loses current helm's all-res/CB), Great Pilum comparison, MF/GF swaps, etc. Do not compromise Hardcore resists/leech without checking actual post-swap stats.
- No clean blank elite throwing-weapon crafting base has been identified yet. Prices are estimates, not checked against live PD2 listings.

## NEXT CHECKPOINT — WAIT FOR USER CONFIRMATION

All 11 Inventory tabs are reviewed; the latest is documented in `docs/04K_Inventory_Duplicates.md`. This checkpoint must be pushed and accepted first.

**Next batch after the user confirms:** `05 - Merc Items/` and `Item Filter/Hiim_Crafting_Barbarian_Focused.filter` (two source folders). Do not read either until confirmation. Then finish the farming plan, filter revision, trade workbook, and swap recommendations. Open decisions: spreadsheet column order, standalone filter vs patch, and HC pricing/currency basis.
