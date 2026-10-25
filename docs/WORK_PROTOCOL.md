# WORK_PROTOCOL.md — rules for every chat on this repo

These rules are binding for any assistant session picking up this project.

## 1. Folder batching (hard limit)
- Read **at most 2 folders per turn**. Then **STOP** and wait for the user's explicit go-ahead before touching the next 2.
- Never bulk-read the other folders to "get ahead" — the chat context limit is the reason this protocol exists.

## 2. Push before reporting (hard rule)
- After every batch of work: update `VERSION.md`, `CHANGELOG.md`, `00_CONTEXT_BLOCK.md`, write/refresh the topic docs, **commit, and push** — *then* report results to the user.
- Rationale: a previous chat died with "The conversation is too long for the model." Nothing is allowed to live only inside the chat.

## 3. Git rules
- Work on `arena/360df353-pd2-s14` only. Never switch branches.
- **Mirror to `main` on every push** so other chats only ever need `main`:
  ```
  git push origin arena/360df353-pd2-s14
  git push origin arena/360df353-pd2-s14:main
  ```
- Commit messages: `vX.Y.Z: <what changed>`.

## 4. Versioning
- `MAJOR` — protocol/architecture change.
- `MINOR` — a new folder batch read, a new deliverable finished (spreadsheet, filter, farm plan section).
- `PATCH` — corrections, re-reads, small edits.

## 5. Accuracy rules
- Transcribe what is on screen; mark uncertain icon/name reads with `⚠`.
- Prices are estimates. Always tag confidence: `HIGH` (liquid, commonly traded), `MED` (niche buyer), `LOW` (vendor/basically unsellable).
- Never invent item mods. If a tooltip is cut off in the screenshot, say so and list it under "data still missing".

## 6. Deliverable checklist for this project
- [x] Vision check (can the chat read the PNGs)
- [x] Character + gear snapshot
- [ ] Charms + inventory read
- [ ] Merc + item filter read
- [ ] Farm plan (elite crafting bases, self + merc) — final
- [ ] Custom / tweaked item filter with tiered colours
- [ ] Trade price spreadsheet (XLSX), sorted by value
- [ ] Gear-swap recommendations
- [ ] Always-current context block for new chats
