# How the three models were tested

This is founder / engineering QA, not a clinical trial. No patient data.

## Protocol rules (automated)

Checked in planning:
- n is 2–4
- After cover, the encoded set is not visible
- Home cannot raise n, delay, or wrap
- Clinic changes at most one parameter at a time
- Home block caps at 8 trials

Result: PASS

## Walkthrough (you + optional Nan session on you only)

Same n=3, delay=5s, wrap=Sentence, 4 trials each model.

| Model | What you use | Pass if |
|---|---|---|
| All physical | cubes, folder, printed scene, paper log | You can cover, wait, find, wrap without a phone |
| All digital | this page, Mode Digital | Icons hide, no back to peek, tap-find works with mouse and finger |
| Hybrid A | cubes + folder + digital scene | Folder is the cover; phone only shows the scene after delay |
| Hybrid B | digital flash + paper scene | Screen goes black; you search paper |

Score each model 0–2 on: cover integrity, ease, visual comfort, wrap quality. Winner is the one Nan will actually run, not the flashiest.

Do not enroll other Onword clients.
