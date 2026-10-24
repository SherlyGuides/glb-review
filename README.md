# ThinkPro GLB Review

A review copy of the LMS Player for ThinkPro, hosted on GitHub Pages, for sending builds to reviewers.

Reviewers mark each step OK or Needs change, add notes, and click on the model to pin comments. "Send review" gives them a link, an email, a file, or a GitHub issue. Opening a review link (or "Open review file…") shows that reviewer's comments on the model, read-only.

## Add a model

1. Make `models/<id>/model.glb` and `models/<id>/lesson.json` (copy an existing one; `fps`, `introFrames`, `framesPerStep`, and one entry per step).
2. Add `{ "id": "<id>", "title": "…" }` to `models.json`.
3. Push. Share `https://sherlyguides.github.io/glb-review/?m=<id>`.

Set `reviewEmail` in `models.json` to pre-fill the "Email the review" recipient.
