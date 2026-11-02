# rig-preview

Public preview of [rig](https://github.com/BNewman73/rig-handover)'s `/digest/2026-10-28`, for review
(ADR 0003 in that repo). The page is built and deployed by `.github/workflows/preview.yml`; it is
never committed here.

- Put up (with marker): `gh workflow run preview.yml -R BNewman73/rig-preview -f marker=true`
- Upload over it without marker: `gh workflow run preview.yml -R BNewman73/rig-preview -f marker=false`
- Take down: `gh api -X DELETE repos/BNewman73/rig-preview/pages`
