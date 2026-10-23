# Modern Dharma — Reading Room 2.0 experiments

A separate sandbox for Reading Room 2.0 prototypes. Nothing here is deployed to,
or changes, moderndharma.life.

Each experiment lives on its own branch:

- `experiment/reading-room-2-entry` — *What should it feel like to enter?*
  Opens on the open question "What keeps showing up?", with evidence from
  different notebooks laid one trace at a time, ending on
  "What else could explain it?"

## Run an experiment locally
```
git checkout experiment/reading-room-2-entry
python3 -m http.server 8000
```
Then open http://localhost:8000/reading-room-2/
