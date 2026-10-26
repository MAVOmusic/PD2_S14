# WORK_PROTOCOL.md — rules for every chat on this repo

These rules preserve progress across chats and the context-limit interruption.

## 1. Source-folder batching
- Read at most **2 source folders per batch**, then stop and wait for the user's explicit go-ahead before starting another batch.
- Inventory tabs are independent checkpoints. Complete one tab, save/version/log/push, then wait for confirmation before opening another tab.
- Each `Runs/Run N` folder is also a separate checkpoint. The player names the Run to review; each future Run may contain at most 15 new item images unless the player explicitly revises the cap. Run 1's 23 images were explicitly authorized as a one-time exception and have been reviewed. Do not read ahead.
- Do not open the Item Filter source without explicit authorization.

## 2. Identification workbook batches
- Workbook: `docs/Unidentified_Icons_and_Items.xlsx`; the player supplies up to **20 identified rows** per update.
- Record each identified batch in the relevant item/source documents, then remove only those completed IDs from the unresolved workbook. Preserve stable IDs for remaining rows.
- Keep player-uploaded identification workbooks as source records; do not overwrite them unless explicitly requested.
- After each batch, update `docs/VERSION.md`, `docs/CHANGELOG.md`, and `docs/00_CONTEXT_BLOCK.md`; commit/push and sync `main` through a PR.

## 3. Wiki research
- The player wants a broad review of relevant Project Diablo 2 Wiki material **after all icon identifications are complete**.
- A narrow Wiki lookup explicitly requested for identified items/maps is allowed. Do not start the broad Wiki review early.
- Cite Wiki pages in the relevant project document and distinguish the page's official table fields from player-entered values. Flag discrepancies; do not silently overwrite them.

## 4. Save / Git workflow
1. Save the transcription or deliverable.
2. Commit and push to the active branch `arena/9c47d90a-pd2-s14`.
3. Keep `main` current through a PR; never push directly to `main`.
4. Report only after the checkpoint is pushed; stop for confirmation when another source folder/batch is due.

## 5. Accuracy / current-state corrections
- Transcribe visible information only; mark uncertainty; do not invent item mods.
- Price estimates are not live quotes unless explicitly checked; tag confidence and realm/currency where known.
- The 24 charms shown in the Charms tab are currently equipped and already included in character-sheet stats. Do not recommend swapping/selling them without fresh stats.
- Mahala uses Purity for Prayer healing. Keep it until the player says healing is no longer needed or an alternative is tested.
- Ramfodder is a Light Bolt quiver; test only with a second Purity crafted in an exact 3-socket crossbow, keeping the existing Purity Long Bow as the baseline. Verify aura tooltip, bolt penetration, IAS breakpoints and safety in-game.
- Record missing/cropped tooltip data.

## 6. Deliverable tracker
- [x] Vision check
- [x] Character + equipped gear snapshot
- [x] Equipped charms transcribed; stat dependency clarified
- [x] Inventory tab screenshots reviewed (with documented tooltip/identity limitations)
- [x] Merc gear and stats transcribed (`docs/05_Merc_Gear.md`)
- [x] Identification workbook updated through U-108; no unresolved rows remain
- [x] `Runs/Run 1` through `Runs/Run 10` scaffolding created (max 15 images each)
- [x] Complete all icon identifications through U-108
- [ ] Broad Wiki review after all identifications
- [ ] Item Filter (unread; wait for explicit authorization)
- [ ] Final farm plan and sorted XLSX trade-price inventory
- [x] Full item-by-item keep/sell/vendor/trade/swap matrix (`docs/07_Full_Inventory_Action_Matrix.md`); live in-game swap verification remains pending
