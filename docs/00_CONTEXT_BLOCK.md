# 00_CONTEXT_BLOCK.md — paste into a new chat to resume

> Copy this file (or everything below the line) into a new chat. It is the project handoff.
> Updated: **2026-10-25** · Project **v0.15.0** · repo `MAVOmusic/PD2_S14` · session branch `arena/5f5eb123-pd2-s14`.

---

## PLAYER / GOAL

I play **Project Diablo 2, Season 14 Hardcore**.

- Character: Level **77 Throw Barbarian** (MAVOmusicHC).
- Mercenary: **Mahala, Act 1 Rogue**, level 77.
- Practical progression ceiling: **Hell Act 2 Arcane Sanctuary**; Canyon of the Magi is difficult.
- Goals: identify elite crafting weapon bases and safe farming zones for me and my merc; compare stash items with equipped gear; tune/create an item filter that emphasizes useful and high-trade-value drops while hiding redundant/vendor-trash items; produce a sorted Excel trade sheet of stored items with estimated PD2 trade values.

## MANDATORY WORKFLOW

1. Read at most two source folders per batch, then stop for confirmation before starting another batch.
2. For the Inventory folder, each tab subfolder is its own checkpoint. Complete one tab, update its document plus `VERSION.md`, `CHANGELOG.md`, and this context file, commit/push, then stop for the user's confirmation before opening another tab.
3. Push each completed checkpoint to `arena/5f5eb123-pd2-s14` before reporting. Keep `main` current through a PR; **never push directly to `main`**.
4. Stay on the fixed Arena branch `arena/5f5eb123-pd2-s14`; never rename or switch branches.
5. Transcribe only visible information; mark uncertainty. Do not invent item mods. Estimates must be labeled and distinguished from live quotes.
6. The user authorized **Merc Items only** in this source batch. After this checkpoint is pushed and merged, stop and wait for explicit confirmation before opening Item Filter.

## IMAGE / SOURCE STATUS

- ✅ Vision confirmed: PNG screenshots are readable.
- Source root: `MAVOmusicHC - Stats - V1.0/`.
- Character/gear/charms reviewed: `01 - Character + Skill Tree` (5 images), `02 - Equipped Items` (12), `03 - Charms` (24).
- All 11 Inventory tabs reviewed and documented: Unique Items (23 supplied screenshots), Set Items (26), Sortables (31), Misc (1), Runes (1), Gems (1), MF (3), GF (8), Maps (3), Ubers (1), Duplicates - Good Corruption (1).
- Merc Items: all 9 screenshots reviewed and transcribed in `docs/05_Merc_Gear.md`.
- See `docs/02_Character_And_Gear_Snapshot.md`, `docs/03_Charms.md`, `docs/04A_Inventory_Uniques.md` through `docs/04K_Inventory_Duplicates.md`, and `docs/05_Merc_Gear.md`.
- Unique Items and Set Items screenshot counters suggest partial captures; docs limit scope to supplied images.
- Misc overview has no hover tooltips: item identities/prices remain unknown. Do not vendor by icon alone.
- Runes: 147 total mapped by standard El-to-Zod grid order (medium confidence); highest Gul ×1, no Um+.
- Gems: 116 counted (86 perfect); seven unnumbered bottom-row icons remain unknown/not counted.
- MF: corrupted LLD amulet (31% MF, +14 all res, +6 Str), 22% MF Battle Gauntlets (craft-base status uncertain), Nagelring (36% MF).
- GF: 8 items with +260% combined GF (corrupted +83 GF amulet; rings +40/+36; GCs +38/+33; three 10-GF SCs). Prices low-confidence.
- Maps filenames say “No Maps”; map-like tier UI icons do not confirm ownership/counts. Do not list or value as owned maps without tooltips.
- Ubers screenshot has 26 item-like icons (10 left, 16 right), identities/quantities unverified. Do not vendor without identifying.
- Duplicates tab: Sigon's Wrap [C] (+10% block, +20 Life, +20 Fire Res, req 6), distinct from the Sortables copy (+13% Pierce). See `docs/04K_Inventory_Duplicates.md`.
- **Still unread and unauthorized:** `Item Filter/Hiim_Crafting_Barbarian_Focused.filter`.

## SAVED FINDINGS TO CARRY FORWARD

- Barbarian Hell-applied resistances are Fire 49 / Cold 80 / Lightning 75 / Poison 58; cold/light are overcapped, fire/poison are gaps. Charm analysis is in `docs/03_Charms.md`.
- Barbarian equipped gear/stats and first-pass farm notes are in `docs/02_Character_And_Gear_Snapshot.md`.
- Mahala: level 77; displayed life 1,220 unbuffed / 1,360 buffed; damage 76–190 / 89–217; defense 1,334 / 2,467; displayed resists Fire 33 / Cold 46 / Lightning 75 / Poison 75. Purity Long Bow grants level 2 Prayer; current arrows add 7% life leech. Sigon's Shelter + Visor each show a gold 10% life-leech set line; active set threshold should be verified. Full transcription and safe swap notes are in `docs/05_Merc_Gear.md`.
- Merc gear swap candidates already documented: Riphook (physical damage/IAS/slow/OW versus Purity's Prayer aura and demon mods), Ramfodder (IAS/FHR/knockback versus current quiver leech/PMH), Infernostride or Sharkskin boots (resistance trades), and eth Diamond Mail (defense versus resists/set bonus). Do not swap blindly in Hardcore; check actual post-swap stats.
- Other candidates in inventory docs: Infernostride, Riphook, Ramfodder, Nokozan Relic, The Scalper; Cow King's Hooves/Vidala's Fetlock (FRW), corrupted Sharkskin Boots (40 FRW/+38 poison res), crafted Jawbone Cap (+2 Throwing Mastery/Shout/Double Swing; loses current helm's all-res/CB), Great Pilum comparison, MF/GF swaps, etc.
- No clean blank elite throwing-weapon crafting base has been identified yet. Prices are estimates, not checked against live PD2 listings.

## NEXT CHECKPOINT — WAIT FOR USER CONFIRMATION

Merc Items is documented in `docs/05_Merc_Gear.md`; all 9 authorized screenshots were read. The checkpoint must be committed/pushed on `arena/5f5eb123-pd2-s14` and merged to `main` via PR first.

**After the push/merge, stop and wait for explicit user confirmation before reading the Item Filter source folder.** Longer-term work still pending: item-filter review/revision, final farming/crafting-base analysis, sorted XLSX inventory/trade sheet, and gear-swap recommendations. Open decisions include spreadsheet column order, standalone filter vs patch, and HC pricing/currency basis.
