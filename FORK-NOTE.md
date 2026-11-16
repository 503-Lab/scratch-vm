# Fork note

- Upstream (canonical for all code except local changes): `scratchfoundation/scratch-vm` (remote `upstream`).
- This clone tracks upstream; version at time of writing: 4.8.94.
- The sibling clone `scratch-vm-pjm` is based on an older upstream (4.8.33) and holds the only copy of
  `src/extensions/scratch3_light_sensing/` (canonical there). Do not duplicate that extension here without a decision to consolidate.
- Sync upstream with `git merge upstream/develop`. Do not delete either clone without the owner's decision.
