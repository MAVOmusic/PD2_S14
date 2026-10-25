# WORK_PROTOCOL.md — rules for every chat on this repo

These rules preserve progress across chats and the context-limit interruption.

## 1. Source-folder batching
- Read at most **2 source folders per batch**, then stop and wait for the user's explicit go-ahead before starting another batch.
- Inventory tabs are independent checkpoints. Complete one tab, save/version/log/push, then wait for confirmation before opening another tab.
- Each `Runs/Run N` folder is also a separate checkpoint. The player names the Run to review; each Run may contain at most 15 new item images. Do not read ahead.
- Do not open the Item Filter source without explicit authorization.

## 2. Identification workbook batches
- Workbook: `docs/Unidentified_Icons_and_Items.xlsx`; the player supplies up to **20 identified rows** per update.
- Record each identified batch in the relevant item/source documents, then remove only those completed IDs from the unresolved workbook. Preserve stable IDs for remaining rows.
- Keep the player's uploaded identification workbook(s) as source records; do not overwrite them unless explicitly requested.
- After each batch, update `docs/VERSION.md`, `docs/CHANGELOG.md`, and `docs/00_CONTEXT_BLOCK.md`, then commit/push and sync `main` through a PR.

## 3. Wiki research
- The player wants a broader review of relevant Project Diablo 2 Wiki information **after all icon identifications are complete**.
- Until then, only do narrow source checks explicitly needed to resolve a question (such as the U-001 Jewel Fragments recipe). Do not start a general Wiki research sweep early.

## 4. Save / Git workflow
1. Save the transcription or deliverable.
2. Commit and push to `arena/c58dcbfc-pd2-s14`.
3. Keep `main` current through a PR; never push directly to `main`.
4. Report only after the checkpoint is pushed; stop for confirmation when another source folder/batch is due.

## 5. Accuracy / current-state corrections
- Transcribe visible information only; mark uncertainty; do not invent item mods.
- Price estimates are not live quotes unless explicitly checked; tag confidence and realm/currency where known.
- The 24 charms shown in the Charms tab are currently equipped and already included in character-sheet stats. Do not recommend swapping/selling them without fresh stats.
- Mahala uses Purity for Prayer healing. Keep it until the player says healing is no longer needed or an alternative is tested.
- Ramfodder is a bolt quiver and cannot be used with the current bow; only reconsider after a Purity crossbow is crafted/equipped.
- Record missing/cropped tooltip data.

## 6. Deliverable tracker
- [x] Vision check
- [x] Character + equipped gear snapshot
- [x] Equipped charms transcribed; stat dependency clarified
- [x] Inventory tab screenshots reviewed (with documented tooltip/identity limitations)
- [x] Merc gear and stats transcribed (`docs/05_Merc_Gear.md`)
- [x] Unknown icon workbook created; 15 IDs identified, 93 rows remain
- [x] `Runs/Run 1` through `Runs/Run 10` scaffolding created (max 15 images each)
- [ ] Complete remaining icon identifications in batches of up to 20
- [ ] Broader Wiki review after all identifications
- [ ] Item Filter (unread; wait for explicit authorization)
- [ ] Final farm plan and sorted XLSX trade-price inventory
- [ ] Final keep/sell/vendor/trade/swap recommendations
