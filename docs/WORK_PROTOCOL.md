# WORK_PROTOCOL.md — rules for every chat on this repo

These rules preserve progress across chats and the context-limit interruption.

## 1. Source-folder batching
- Read at most **2 source folders per batch**, then stop and wait for the user's explicit go-ahead before starting another batch.
- Inventory is stricter: each tab subfolder is its own checkpoint. Complete one tab, save/version/log/push, then stop and wait for confirmation before reading another tab.
- Each `Runs/Run N` folder is also a separate checkpoint. The player must explicitly name the Run to read; do not read ahead. Each Run is limited to 15 new item images.
- Do not bulk-read ahead or open the Item Filter source without explicit authorization.

## 2. Save before reporting
After each completed batch/checkpoint:
1. Save the source transcription or deliverable.
2. Update `docs/VERSION.md`, `docs/CHANGELOG.md`, and `docs/00_CONTEXT_BLOCK.md`.
3. Commit and push to `arena/2ad22dfd-pd2-s14`.
4. Keep `main` current through a PR from the working branch; never push directly to `main`.
5. Only then report to the player and wait for confirmation before reading the next source folder.

## 3. Git constraints
- Work only on the fixed Arena branch `arena/2ad22dfd-pd2-s14`. Never rename or switch branches.
- Push only to the session branch. **Do not directly push to `main`; use a PR for main synchronization.**
- Commit messages: `vX.Y.Z: <what changed>`.

## 4. Versioning
- MAJOR — protocol/architecture change.
- MINOR — a new source folder batch or deliverable milestone.
- PATCH — corrections, re-reads, or handoff/protocol fixes.

## 5. Accuracy / current-state corrections
- Transcribe what is visible; mark uncertain reads with `⚠`.
- Do not invent item mods or infer unshown values.
- Prices are estimates unless checked against current listings; tag confidence HIGH / MED / LOW and include realm/currency basis where known.
- The 24 charms shown in the Charms tab are currently equipped and already included in character-sheet stats. Do not recommend swapping/selling them without a new stat comparison.
- Mahala uses Purity for Prayer healing. Keep it until the player says the healing is no longer needed or an alternative is tested.
- Ramfodder is a bolt quiver and cannot be used with the current bow; only reconsider after a Purity crossbow is crafted/equipped.
- Record missing or cropped tooltip data.

## 6. Deliverable tracker
- [x] Vision check
- [x] Character + equipped gear snapshot
- [x] Equipped charms transcribed; stat dependency clarified
- [x] Inventory tab screenshots reviewed (with documented tooltip/identity limitations)
- [x] Merc gear and stats transcribed (`docs/05_Merc_Gear.md`)
- [x] Unknown icon workbook created (`docs/Unidentified_Icons_and_Items.xlsx`); await player descriptions
- [x] `Runs/Run 1` through `Runs/Run 10` scaffolding created (max 15 images each)
- [ ] Item Filter (unread; wait for explicit player authorization)
- [ ] Final farm plan (elite crafting bases, self + merc; practical ceiling Arcane Sanctuary)
- [ ] XLSX of stored items with estimated trade values, sorted high to low
- [ ] Finalized keep/sell/vendor, trade and swap recommendations (wait for icon answers and corrected current-state comparisons)
