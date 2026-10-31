LATEST MODIFICATIONS — 2026-10-08

1. ALL JUDGES PDF
- Competition name and MAT number are now displayed in the header of every judge page.
- Judge name at the top is larger.
- Poomsae names are now in a dedicated POOMSAE column immediately beside CATEGORY and are larger/easier to read.
- Bottom repeated competition / MAT / judge-name footer remains removed.
- Signature block spacing improved:
  Mme Reem Bousselmi
  رئيسة لجنة التحكيم الوطنية للبومزا والفريستايل
- Page number remains at the bottom.

2. PRINT / PDF OFFICIAL RESULTS (TOP 4)
- Added the same Reem Bousselmi signature block with clearer spacing between name and role.
- Competition and MAT remain in the results header.

3. TUNISIA GOVERNORATE MAP
- Corrected the governorate code/name table (24 governorates).
- Replaced the previous riateLab governorate GeoJSON because it contained repeated governorate IDs/geometries.
- The interactive map now loads the Tunisia governorate topology from the mtimet/tnacmaps Tunisia administrative map project and converts TopoJSON directly in the browser.
- Arabic governorate names are normalized through canonical governorate IDs/names.
- Added a local reference-map fallback image if the online topology cannot be loaded.

No scoring formulas or tournament workflow were intentionally changed.

V11 — JUDGE SCREEN REFINEMENT + ROUND/PERFORMANCE PRESS COUNTERS
- Accuracy adjustment counters are now temporary and isolated to the active athlete, round, poomsae and scoring session.
- The four counters (+/- 0.1 and +/- 0.3) reset when the active scoring identity changes.
- All four counters reset to zero after the operator acknowledges receipt of the submitted score.
- Counter values are no longer restored from localStorage, preventing old counts from returning for a later athlete/round.
- Refined the judge phone interface with a calmer dark-blue visual hierarchy, clearer match header, improved card spacing, more legible labels, polished touch controls and responsive spacing.
- Scoring values, scoring formulas, presentation parameters, judge submission payload and competition workflow remain unchanged.
