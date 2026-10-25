# WORK_PROTOCOL.md — rules for every chat on this repo

These rules preserve progress across chats and the context-limit interruption.

## 1. Source-folder batching
- Read at most **2 source folders per batch**, then stop and wait for the user's explicit go-ahead before starting the next batch.
- Inventory is stricter: each tab subfolder is its own checkpoint. Complete one tab, save/version/log/push, then stop and wait for confirmation before reading another tab.
- Do not bulk-read ahead.

## 2. Save before reporting
After each completed batch/checkpoint:
1. Save the source transcription or deliverable.
2. Update `docs/VERSION.md`, `docs/CHANGELOG.md`, and `docs/00_CONTEXT_BLOCK.md`.
3. Commit and push to `arena/e21a31e0-pd2-s14`.
4. Keep `main` current through a PR from the working branch; never push directly to `main`.
5. Only then report to the user and, for Inventory, wait for confirmation.

## 3. Git constraints
- Work only on the fixed Arena branch `arena/e21a31e0-pd2-s14`. Never rename or switch branches.
- Push only to the session branch. **Do not directly push to `main`; use a PR for main synchronization.**
- Commit messages: `vX.Y.Z: <what changed>`.

## 4. Versioning
- MAJOR — protocol/architecture change.
- MINOR — a new source folder batch or deliverable milestone.
- PATCH — corrections, re-reads, or handoff/protocol fixes.

## 5. Accuracy
- Transcribe what is visible; mark uncertain reads with `⚠`.
- Do not invent item mods or infer unshown values.
- Prices are estimates unless checked against current listings; tag confidence HIGH / MED / LOW and include realm/currency basis where known.
- Record missing or cropped tooltip data.

## 6. Deliverable tracker
- [x] Vision check
- [x] Character + equipped gear snapshot
- [x] Charms
- [ ] Full inventory tabs
- [ ] Merc gear
- [ ] Final farm plan (elite crafting bases, self + merc; practical ceiling Arcane Sanctuary)
- [ ] Revised item filter (strong tiered colors; hide redundant/vendor-trash)
- [ ] XLSX of stored items with estimated trade values, sorted high to low
- [ ] Finalized keep/sell/vendor and swap recommendations
