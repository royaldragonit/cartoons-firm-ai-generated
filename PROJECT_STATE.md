# Project state and recovery handoff

Handoff date: 2026-09-18 (Asia/Bangkok). Repository HEAD at audit: `4a23550`.
Current project root: `D:\Personals\Projects\Films\Cartoons`.
Previous machine root: `D:\Projects\cartoons-firm-ai-generated`.

## Purpose and authority

Produce reusable visual assets, then animated shots, from 36 source comic/storyboard panels. The shot plan contains 66 shots grouped into 14 narrative scenes, with a provisional estimated runtime of 401.9 seconds. `06_scenes.json` contains 36 panel-level scene records; this differs intentionally from the narrative-scene grouping.

`11_asset_manifest.json` is the primary authority for current asset IDs and statuses. Review files preserve human-review history but several have not been synchronized. Approved generated masters govern stable character identity and location continuity; source panels govern story-specific staging, pose, directionality, props, and emotion. Preserve approved identity when incidental source variation conflicts, unless the human requests a source-specific variant.

Workflow: NOT_GENERATED -> GENERATED -> APPROVED. Generated assets require human review. Never auto-approve or modify approved assets without explicit human instruction. Generate only the requested asset and stop. Action references normally contain one character and minimal supporting furniture/props, not a complete scene. Add environments and other characters during shot blocking. Defer speed streaks, wind, dust, and motion accents to shots/video unless an FX asset is specifically requested. Reuse approved props and locations. Use deterministic compositing for important readable text. Do not invent dialogue for [INDISTINCT CHATTER].

## Current production stage

Stage 6 (secondary props) is COMPLETE for current production needs. `PROP_01_WATCH` remains deferred and low priority; it does not block starting shot production, but it blocks the four shots whose source visibly makes the watch story-critical. Stages 1-5 and inserted hospital continuity stage 3.5 are APPROVED according to the manifest. This is an asset-production checkpoint, not evidence of completed animated shots.

| Stage | Scope | Manifest state |
| --- | --- | --- |
| 1 | Ah Lim and Ah Da young/afterlife masters | 14 approved |
| 2 | Classroom and desk/chair lock | 6 approved |
| 3 | Pilot support | 5 approved |
| 3.5 | Elderly Ah Lim portrait/bed pose and hospital staff | 3 approved |
| 4 | Remaining locations and canteen table set | 7 approved |
| 5 | Six supporting portrait/action packs | 12 approved |
| 6 | Secondary props | 7 approved, 0 generated, 1 not generated (watch deferred) |

Total: **54 manifest assets: 53 APPROVED, 0 GENERATED, 1 NOT_GENERATED**. Counts are manifest states, not a fresh approval or a guarantee of file correctness.

## Audit findings — unresolved, no fixes applied

1. **Watch deferred:** `PROP_01_WATCH` was reset from an invalid GENERATED state to `NOT_GENERATED` because its expected output and review files were missing after migration. It remains a low-priority deferred prop; no asset was regenerated. Regenerate only if SHOT_013 or SHOT_054 later requires a visible watch.
2. **Profile repair completed:** The old approved `profile_left.png` was an accidental duplicate of `face_3q_talking.png`; it was preserved as `profile_left_obsolete_duplicate.png`. The corrected true viewer-left profile was human-reviewed and restored to `APPROVED` for `CHAR_01_PROFILE_LEFT`. The obsolete backup remains non-canonical.
3. **Outdated reviews:** all seven Ah Lim stage-1 master reviews and six Ah Da stage-1 reviews (all except seated-neutral) still state GENERATED or REVIEW_REQUIRED despite APPROVED manifest status. Treat them as stale history, not authority to revoke approval. Their exact IDs are listed below. `LOC_01_FRONT` also retains a superseded approval-required sentence inside a review that records explicit approval.
4. **Obsolete visitor assets:** `assets/extras/hospital_visitors/group.png` and `group_review.md` are unreferenced remnants. They are not canonical or part of the pending manifest queue. Preserve them on disk. `EXTRA_HOSPITAL_STAFF_GROUP` is approved and present. Visitor wording also survives in `06_scenes.json`, hospital shots in `07_shot_list.md`/`08_shot_list.json`, `10_asset_design_plan.md`, and the bed/tubing review.
5. **Stale identity mapping:** `03_character_bible.md`, `06_scenes.json`, `07_shot_list.md`, `08_shot_list.json`, `10_asset_design_plan.md`, and `12_generation_queue.md` still map Kim Fook to CHAR_08 and Anna to CHAR_09. Current manifest and canonical files correctly map Anna to CHAR_08, with no CHAR_09 entries or files; an empty stale `assets/characters/CHAR_09_Anna` directory remains on disk and is not canonical. Kim Fook remains in source panel 25 / SHOT_044 but has no current dedicated manifest pack. This is an unresolved coverage/mapping gap, not authorization to reuse Anna or create CHAR_09.
6. **Stale queue:** `12_generation_queue.md` still lists every planned entry as NOT_GENERATED, includes obsolete Kim Fook/CHAR_09 paths, and omits the inserted elderly/staff assets. Use its stage order only after checking the current manifest; do not execute it literally.
7. **Stale shot dependencies:** examples in the manifest/queue include attendance paper assigned SHOT_012 although the roll-call panel is SHOT_011; watch assigned SHOT_013/054 although watch panels 10/31 map to SHOT_018/019 and SHOT_057/058; LOC_02 includes SHOT_041 (May/classroom) instead of Li Jie's SHOT_042/043; gate includes SHOT_057/058 (canteen) while gate panel 32 starts SHOT_059. Validate dependencies against source panels and the shot list before shot work. The SHOT_044 railing-location mismatch has been corrected to LOC_03.
8. **Stale descriptive notes:** CHAR_05_PORTRAIT's manifest notes describe a curled mattress action although its name/path/review establish a portrait. Some approved May, Li Jie, and meal entries retain 'human approval required' wording. Explicit status remains authoritative.
9. **Whiteboard approved:** `PROP_09_WHITEBOARD` is now APPROVED. Its source text matches `36.jpg`, geometry is acceptable, and the source-ambiguous `5l` class glyph was accepted by human review.
10. **Downstream planning is provisional:** vignette `narration_exact` fields point to the transcript rather than containing final narration, and several lengthy captions have short provisional shot durations. Do not treat the runtime estimate as a finalized narrated cut. `05_continuity_report.md` also contains a farewell description inconsistent with the shot list (it says the guide departs and the black-haired student remains at 33->35); check original panels before blocking.

### Integrity and missing-review checks

- All 53 approved output paths exist and are nonempty. All have corresponding review files.
- `PROP_02_ATTENDANCE_PAPER` is APPROVED with its output and review present. The obsolete LOC_01-based railing archive remains outside the canonical manifest.
- The remaining NOT_GENERATED output file and review are absent, as expected at that status: watch.
- Assets directory contains 56 PNGs and 54 review files: 53 manifest-linked image/review pairs plus the obsolete visitor pair and the obsolete profile/profile-railing backup images.
- No duplicate manifest asset IDs or output paths. No duplicate canonical character identities found; young/elderly CHAR_01 are intentional variants. The one byte-duplicate image pair is described above.
- All 36 numbered source panels exist. No obsolete operational root remains in the operating rules; the previous machine root is retained only as historical context in this handoff note. Existing production assets and manifest statuses were left untouched.
- Reviewed the twelve numbered production documents, the complete assets inventory, and all 53 review files. Parsed scene/shot/manifest JSON and checked file paths, statuses, duplicate hashes, and historical references. Targeted visual inspection covered the duplicated Ah Lim image, whiteboard, attendance paper, and source panel 36. This was not a new visual approval pass over every asset.

## Historical corrections and continuity locks

- CHAR_01 is Ah Lim; CHAR_02 is Ah Da. Young/afterlife Ah Lim and 90+ hospital Ah Lim are the same person with intentionally separate production references. Do not mix their age traits or remove the elderly references.
- Jenny CHAR_03_ACTION is confirmed APPROVED in both manifest and review: blue outfit, ordinary classroom desk, exactly one handheld microphone.
- Ah Guang: quiet window-directed seated action; no photography equipment; facial hatch marks are not identity features.
- Huang Ming: pale brown short messy hair; peaceful curled side-lying action, head upper-right and legs lower-left as in panel 22; do not mirror. Temporary mattress support in the action does not replace the approved three-layer mattress prop.
- May: black hair tied back, blue sleeveless outfit, intense desk crying.
- Li Jie: youthful healthy appearance, exuberant leftward running/shouting; motion FX deferred.
- Anna: CHAR_08, youthful tomboy, short sandy/light-brown spiky hair, blue sleeveless top, simplified athletic build; approved jump/reach action with one basketball. Do not glamorize/feminize or recreate CHAR_09.
- Hospital staff replace the obsolete visitor interpretation. Keep staff anonymous and generic.
- Classroom: board at front, windows left when facing board, door right. LOC_07 corridor is separate geometry. Approved reunion setup's minor blocking differences and field master's small goal detail were explicitly accepted; do not undo them.

## Current update

`PROP_07_BASKETBALL_HOOP` is now APPROVED at `assets/props/PROP_07_basketball_hoop/master.png`. Human approval covered its backboard geometry, rim and net, support structure, single basketball, school-court design, basketball-court visual-language compatibility, and suitability for `SHOT_045`.

`PROP_08_RAILING` continuity was corrected to LOC_03, the previous LOC_01-based output remains archived as obsolete, and the replacement at `assets/props/PROP_08_railing/master.png` is now human-approved for `SHOT_044`. No other asset was generated.

`PROP_02_ATTENDANCE_PAPER` was generated at `assets/props/PROP_02_attendance_paper/master.png` from `6.jpg`. The source-obscured status for `Lim Min Fa` was left blank rather than inferred.

`PROP_02_ATTENDANCE_PAPER` is now human-approved. Its eight names, seven visible `có mặt` entries, accepted canonical layout, and intentionally blank final status were confirmed. Stage 6 secondary-prop production is complete for current needs; `PROP_01_WATCH` remains `NOT_GENERATED` and deferred/low priority. It does not block starting shot production, but it blocks SHOT_018, SHOT_019, SHOT_057, and SHOT_058.

## Recommended next task

Stage 6 secondary-prop production is complete for current needs. `PROP_01_WATCH` remains deferred/low priority and does not block starting shot production, but it blocks four watch-dependent shots. Reconcile stale identity/shot metadata in a separately authorized task before shot generation.

Do not generate `PROP_01_WATCH` unless a later shot-specific need authorizes it.

## Shot production preflight

Stage 6 remains complete for current production needs; `PROP_01_WATCH` is deferred and does not block shot production. A 66-shot preflight audit was performed without changing existing shot-list, scene, manifest, or approved-asset files.

- `READY`: 8 shots
- `READY_WITH_BLOCKING_REFERENCE`: 53 shots
- `BLOCKED`: 5 shots
- Text-lock shots: 2
- `VIDEO_STAGE_FX` shots: 4
- Stale metadata issue groups: 10
- Recommended first production shot: `SHOT_037`
- Plan: `13_shot_production_preflight.md`
- Machine-readable plan: `13_shot_production_preflight.json`

No shot rendering, video generation, FX generation, or blocking-reference generation has started.

`SHOT_037` pilot `keyframe_v001.png` remains rejected review history for composition ambiguity; it is preserved and is not the locked shot reference. Video generation has not started.

`SHOT_037` keyframe_v001 required a composition correction because the indicated seat was ambiguous. Corrected `shots/SHOT_037/keyframe_v002.png` is now HUMAN-APPROVED and locked as the pilot visual reference. The next stage is SHOT_037 motion/video brief preparation; video has not been generated.

`SHOT_037` keyframe_v002 remains HUMAN-APPROVED and locked. Controlled motion brief created at `shots/SHOT_037/video_brief_v001.md`; SHOT_037 is ready for one controlled video-pilot generation. Video generation has NOT started.

### Current SHOT_037 video checkpoint — 2026-09-23

One `SHOT_037` video pilot v001 was rendered at `shots/SHOT_037/video_v001.mp4` from the HUMAN-APPROVED, locked `keyframe_v002.png`. It is a 4.9-second silent clip at 30 fps, using a deterministic 2D push-in from 100% to 102%; no generative video model or independent hand motion was used. Status: **REJECTED by human review** because deterministic still-image zoom was insufficient. The file remains review history. Its earlier `shots/SHOT_037/video_v001_review.md` has not been revised in this prompt-pack task; the human's rejection supersedes its pending-review status.

This supersedes the earlier video-not-started checkpoints above. No further video versions were generated and no other shots were started. Approved images and manifest statuses remain unchanged; human review is required before refinement or the next production step.

Manual Runway test pack for SHOT_037 prepared at `shots/SHOT_037/runway_test_pack_v001.md`, with long and short paste-ready prompts at `shots/SHOT_037/runway_prompt_v001.txt` and `shots/SHOT_037/runway_prompt_short_v001.txt`. The next attempt is one true image-to-video test from approved, locked `keyframe_v002.png`, followed by human review. No video or other media was generated in this task.

### SHOT_001 blocking/keyframe checkpoint — 2026-09-23

**SHOT_001 keyframe_v002 is HUMAN-APPROVED and LOCKED** at `shots/SHOT_001/keyframe_v002.png`, the canonical visual starting point for this shot. Human review passed close-up framing, elderly identity, critical/near-death readability, mask/tube continuity, hospital context, secondary staff, direction, emotional clarity, 2D style and image-to-video starting-frame suitability. V001 remains unchanged rejected framing history. Approval: `shots/SHOT_001/keyframe_v002_review.md`; locked shot reference: `shots/SHOT_001/shot_001_brief.md`. Next stage: prepare the SHOT_001 motion/video brief. **SHOT_001 video has NOT been generated.** This task only records approval; no image changes, keyframe_v003, approved-master edits, preflight changes or other-shot work.

SHOT_001 controlled motion/video brief prepared at `shots/SHOT_001/video_brief_v001.md`. `shots/SHOT_001/keyframe_v002.png` remains HUMAN-APPROVED and LOCKED. SHOT_001 is ready for external image-to-video testing in a separately authorized task, prioritizing extremely shallow breathing, medical-prop stability and a very slight push-in within the approved close-up. No video generated; no keyframe, approved-master, preflight or other-shot changes.

SHOT_002 controlled motion/video brief prepared at `shots/SHOT_002/video_brief_v001.md`. The brief preserves the HUMAN-APPROVED, LOCKED keyframe at `shots/SHOT_002/keyframe_v001.png`, specifies restrained shallow breathing and a very slight push-in, and keeps the medium bedside composition and staff anatomy stable. Ready for an external image-to-video test; no SHOT_002 video generated. SHOT_001 keyframe_v002 remains HUMAN-APPROVED, LOCKED and unchanged; no keyframe_v002 for SHOT_002, approved-master, preflight or other-shot changes.

### SHOT_003 blocking/keyframe checkpoint — 2026-10-05

SHOT_003 keyframe_v001 was generated at `shots/SHOT_003/keyframe_v001.png` from source panel `2.jpg` and the approved elderly hospital references. Status: **REVIEW_REQUIRED**; human approval is not recorded. The frame is an eye-level extreme close-up centered on elderly Ah Lim's exhausted eyes, oxygen mask, pillow, neck and upper chest, with no surrounding staff or source-panel text. Review: `shots/SHOT_003/keyframe_v001_review.md`; brief: `shots/SHOT_003/shot_003_brief.md`.

SHOT_001 keyframe_v002 and SHOT_002 keyframe_v001 remain HUMAN-APPROVED, LOCKED and unchanged. No SHOT_003 video, keyframe_v002, approved-master edit, preflight change, or SHOT_004 work was performed.

### SHOT_004 blocking/keyframe checkpoint — 2026-10-05

SHOT_004 keyframe_v001 was generated at `shots/SHOT_004/keyframe_v001.png` from source panel `3.jpg` and the approved LOC_01 classroom, desk/chair and young/afterlife Ah Lim references. The live shot specification resolves this as an eye-level CU classroom transition: Ah Lim jolts upright at his desk in shock. Status: **REVIEW_REQUIRED**; human approval is not recorded. Review: `shots/SHOT_004/keyframe_v001_review.md`; brief: `shots/SHOT_004/shot_004_brief.md`.

SHOT_001 keyframe_v002 and SHOT_002 keyframe_v001 remain HUMAN-APPROVED, LOCKED and unchanged. SHOT_003 keyframe_v001 remains unchanged. No SHOT_004 video, keyframe_v002, approved-master edit, preflight change, or SHOT_005 work was performed.

### SHOT_004 correction checkpoint — 2026-10-05

SHOT_004 keyframe_v001 is rejected for incorrect classroom geography: the whiteboard appeared directly behind Ah Lim, making the student seem to face away from the classroom front. It remains unchanged as review history. Corrected `shots/SHOT_004/keyframe_v002.png` was generated with a side-front reaction angle, normal student orientation toward the front/whiteboard side, and status **REVIEW_REQUIRED**. Review: `shots/SHOT_004/keyframe_v002_review.md`. No video or SHOT_005 work was performed.

### SHOT_004 v003 correction checkpoint — 2026-10-05

SHOT_004 keyframe_v001 is REJECTED for reversed classroom geography. SHOT_004 keyframe_v002 is REJECTED because the whiteboard remained visible beside Ah Lim and the orientation stayed ambiguous. Corrected `shots/SHOT_004/keyframe_v003.png` was generated with the camera at the front of the classroom, the whiteboard behind camera and absent, and Ah Lim facing forward from a normal student desk. Status: **REVIEW_REQUIRED**; no video generated. Review: `shots/SHOT_004/keyframe_v003_review.md`.

No earlier approved shot, approved master, preflight file, or SHOT_005 content was modified.

### SHOT_004 v004 correction checkpoint — 2026-10-05

SHOT_004 keyframe_v001 is REJECTED for reversed classroom geography. SHOT_004 keyframe_v002 is REJECTED because the whiteboard remained visible beside Ah Lim and the orientation was ambiguous. SHOT_004 keyframe_v003 is REJECTED because its prominent background door was spatially implausible for the setup. Corrected `shots/SHOT_004/keyframe_v004.png` was generated with the camera at the front of the classroom, the whiteboard behind camera and absent, and a simplified rear/side classroom background with no door. Status: **REVIEW_REQUIRED**; no video generated. Review: `shots/SHOT_004/keyframe_v004_review.md`.

No earlier approved shot, approved master, preflight file, or SHOT_005 content was modified.

### SHOT_004 v005 correction checkpoint — 2026-10-05

SHOT_004 keyframe_v004 was close and usable in classroom composition, but remained unapproved because Ah Lim’s shocked reaction was not strong enough. Corrected `shots/SHOT_004/keyframe_v005.png` was generated while preserving the v004 classroom layout and orientation, with a noticeably wider mouth, wide alarmed eyes, and one clear cheek sweat drop. Status: **REVIEW_REQUIRED**; no video generated. Review: `shots/SHOT_004/keyframe_v005_review.md`.

No earlier approved shot, approved master, preflight file, or SHOT_005 content was modified.

### SHOT_006 transitional orientation checkpoint — 2026-10-05

SHOT_006 `shots/SHOT_006/keyframe_v001.png` was generated as a revised transitional classroom orientation shot. The starting frame is a semi-subjective seated-awareness view from Ah Lim’s position, with Ah Da visible ahead but not dominant, supporting later recentering into the SHOT_007 reveal. Status: **REVIEW_REQUIRED**; no video generated. Review: `shots/SHOT_006/keyframe_v001_review.md`.

No approved shot, approved master, preflight file, or SHOT_007 content was modified.

### SHOT_007 greeting keyframe checkpoint — 2026-10-05

`shots/SHOT_007/keyframe_v001.png` was generated as the close reunion/confusion conversation frame after SHOT_006. Ah Da is the dominant greeting speaker and Ah Lim is the clearly connected confused listener. Status: **REVIEW_REQUIRED**; no video generated. Review: `shots/SHOT_007/keyframe_v001_review.md`.

Previous shots, approved masters, shot-list files, preflight files, and SHOT_008 content were not modified.

### SHOT_007 v002 depth-staging correction — 2026-10-05

SHOT_007 `keyframe_v001.png` is **REJECTED** by human review for incorrect shot interpretation: the close conversation lost source 4.jpg's depth staging. Its earlier staging PASS claims are superseded. Corrected `shots/SHOT_007/keyframe_v002.png` was generated with large young Ah Lim in right-foreground left-facing profile and much smaller Ah Da greeting from the left/center-left classroom front. Status: **REVIEW_REQUIRED**; human approval: **NOT RECORDED**. Review: `shots/SHOT_007/keyframe_v002_review.md`. No video generated. V001, previous shots, approved masters, shot-list and preflight files remain unchanged; no SHOT_008 work performed.

### SHOT_007 v003 written-board correction — 2026-10-05

SHOT_007 `keyframe_v002.png` is close but **NOT APPROVED**: depth staging improved, but the whiteboard lacked source-specific classroom content. Generated `shots/SHOT_007/keyframe_v003.png` as a targeted edit preserving the v002 composition and adding sparse, nonlexical list-like board marks based on 4.jpg. Status: **REVIEW_REQUIRED**; human approval: **NOT RECORDED**. Review: `shots/SHOT_007/keyframe_v003_review.md`. V001 remains rejected history; v002 remains unapproved history. No video generated; prior images and approved masters unchanged. No SHOT_008 work performed.

### SHOT_008 reverse-angle keyframe checkpoint — 2026-10-05

Generated `shots/SHOT_008/keyframe_v001.png` as a medium reverse angle from Ah Da's side: partial Ah Da at left foreground, young Ah Lim clearly visible at his desk as the confused speaking subject. The board is behind camera; the window wall appears screen-right in reverse view. Status: **REVIEW_REQUIRED**; human approval: **NOT RECORDED**. Brief: `shots/SHOT_008/shot_008_brief.md`; review: `shots/SHOT_008/keyframe_v001_review.md`. Foreground weighting and perceived inter-character distance remain human-review checks. No video generated. Previous shots, approved masters, manifest, shot lists and preflight files remain unchanged; no SHOT_009 work performed.

### SHOT_008 v002 spacious reverse-angle correction — 2026-10-06

SHOT_008 `keyframe_v001.png` is **REJECTED** by human review because the reverse angle was too tight / camera too close. Generated `shots/SHOT_008/keyframe_v002.png` with a distant speaking Ah Lim, smaller edge-cropped foreground Ah Da and multiple visible desk rows. Status: **REVIEW_REQUIRED**; human approval: **NOT RECORDED**. Review: `shots/SHOT_008/keyframe_v002_review.md`. Perceived scale versus SHOT_007 and empty-chair orientation remain review checks; no approval is implied. No video generated. V001, previous shots, approved masters, shot lists, manifest and preflight files remain unchanged. No SHOT_009 work.

### SHOT_009 comic crying close-up checkpoint — 2026-10-06

Generated `shots/SHOT_009/keyframe_v001.png`: dominant Ah Da close-up with an exaggerated raised-arm appeal and strong cartoon tear streams; small confused Ah Lim reacts from the right background. Status: **REVIEW_REQUIRED**; human approval: **NOT RECORDED**. Brief: `shots/SHOT_009/shot_009_brief.md`; review: `shots/SHOT_009/keyframe_v001_review.md`. Human review should confirm the teasing/relieved rather than tragic emotional read, background softness and chair orientation. No video generated. Previous shots, approved masters, manifest, shot lists and preflight files unchanged; no SHOT_010 work performed.

### SHOT_009 v002 source-panel staging correction — 2026-10-06

SHOT_009 `keyframe_v001.png` is **REJECTED** by human review: camera angle/staging was not faithful enough to 5.jpg, with excessive foreground close-up dominance. Generated `shots/SHOT_009/keyframe_v002.png` restoring left-side half-body Ah Da, small seated right-background Ah Lim, and readable desk-row depth. Status: **REVIEW_REQUIRED**; human approval: **NOT RECORDED**. Review: `shots/SHOT_009/keyframe_v002_review.md`. Remaining review points include light Ah Lim shoes, small comic accent strokes and precise performance/direction. No video generated. Prior images, approved masters, manifest, shot lists and preflight files remain unchanged; no SHOT_010 work performed.

### SHOT_009 v003 classroom/seating correction — 2026-10-06

SHOT_009 `keyframe_v002.png` is **REJECTED** by human review and preserved unchanged as history: board missing, desks/chairs missing, and Ah Lim seated incorrectly. Generated `shots/SHOT_009/keyframe_v003.png` to restore the visible front-board edge, fuller desk/chair rows, and Ah Lim's fourth-row seating with three empty desk rows ahead of him, while preserving left-foreground comic Ah Da and small right-background Ah Lim. Status: **REVIEW_REQUIRED**; human approval: **NOT RECORDED**. Review: `shots/SHOT_009/keyframe_v003_review.md`. Whole-room desk alignment and remaining comic accents/performance nuance require human review. No video generated. Prior keyframes, approved masters, manifest, shot lists and preflight files remain unchanged; no SHOT_010 work.

### SHOT_009 v004 perspective/performance correction — 2026-10-06

SHOT_009 `keyframe_v003.png` is **REJECTED** by human review and preserved unchanged as history. Generated `shots/SHOT_009/keyframe_v004.png` for the requested fixes: straighten room perspective, correct teacher-desk/front-furniture angle, and exaggerate Ah Da's comic crying further, preserving the fourth-row seat and depth staging. Status: **REVIEW_REQUIRED**; human approval: **NOT RECORDED**. Review: `shots/SHOT_009/keyframe_v004_review.md`. Straightened lines and stronger mouth/tears are visible; window-wall perspective and the partly occluded teacher-desk area still require human verification. No video generated. Prior images, approved masters, manifest, shot lists and preflight files unchanged; no SHOT_010 work.

### SHOT_011 attendance-board keyframe — 2026-10-06

The source-6 attendance-board beat is correctly assigned to SHOT_011. V001-v003 remain unchanged; `keyframe_v004.png` edits v003 to strengthen Ah Da's restrained comic cry-laugh and cyan tears while preserving board, roster, chalk pose, camera, and blocking. Status remains **REVIEW_REQUIRED**, human approval **NOT RECORDED**. Brief: `shots/SHOT_011/shot_011_brief.md`; v004 review: `shots/SHOT_011/keyframe_v004_review.md`. The requested “Lim Min Fa — có mặt” remains visible by explicit human direction, though 6.jpg and the approved attendance-paper leave that status obscured/blank; review flags it for human judgment. SHOT_008/009/010/012 remain untouched. `PROP_01_WATCH` remains deferred/NOT_GENERATED and was omitted. No video generated; no approved asset or shot-list/preflight metadata changed.

## Exact manifest inventory at handoff

The following tables are a snapshot; re-read the live manifest before acting. Paths are relative to the current project root.

### APPROVED

| Asset ID | Stage | Output path | File present |
| --- | --- | --- | --- |
| CHAR_01_FACE_FRONT_NEUTRAL | 1 | assets/characters/CHAR_01_Ah_Lim/masters/face_front_neutral.png | Yes |
| CHAR_01_FACE_3Q_TALKING | 1 | assets/characters/CHAR_01_Ah_Lim/masters/face_3q_talking.png | Yes |
| CHAR_01_PROFILE_LEFT | 1 | assets/characters/CHAR_01_Ah_Lim/masters/profile_left.png | Yes |
| CHAR_01_FULL_BODY_FRONT | 1 | assets/characters/CHAR_01_Ah_Lim/masters/full_body_front.png | Yes |
| CHAR_01_FULL_BODY_3Q | 1 | assets/characters/CHAR_01_Ah_Lim/masters/full_body_3q.png | Yes |
| CHAR_01_FULL_BODY_SIDE | 1 | assets/characters/CHAR_01_Ah_Lim/masters/full_body_side.png | Yes |
| CHAR_01_SEATED_NEUTRAL | 1 | assets/characters/CHAR_01_Ah_Lim/masters/seated_neutral.png | Yes |
| CHAR_01_ELDERLY_HOSPITAL_PORTRAIT | 3.5 | assets/characters/CHAR_01_Ah_Lim/elderly/hospital_portrait.png | Yes |
| CHAR_01_ELDERLY_BED_POSE | 3.5 | assets/characters/CHAR_01_Ah_Lim/elderly/bed_pose.png | Yes |
| EXTRA_HOSPITAL_STAFF_GROUP | 3.5 | assets/extras/hospital_staff/group.png | Yes |
| CHAR_02_FACE_FRONT_NEUTRAL | 1 | assets/characters/CHAR_02_Ah_Da/masters/face_front_neutral.png | Yes |
| CHAR_02_FACE_3Q_TALKING | 1 | assets/characters/CHAR_02_Ah_Da/masters/face_3q_talking.png | Yes |
| CHAR_02_PROFILE_LEFT | 1 | assets/characters/CHAR_02_Ah_Da/masters/profile_left.png | Yes |
| CHAR_02_FULL_BODY_FRONT | 1 | assets/characters/CHAR_02_Ah_Da/masters/full_body_front.png | Yes |
| CHAR_02_FULL_BODY_3Q | 1 | assets/characters/CHAR_02_Ah_Da/masters/full_body_3q.png | Yes |
| CHAR_02_FULL_BODY_SIDE | 1 | assets/characters/CHAR_02_Ah_Da/masters/full_body_side.png | Yes |
| CHAR_02_SEATED_NEUTRAL | 1 | assets/characters/CHAR_02_Ah_Da/masters/seated_neutral.png | Yes |
| LOC_01_MASTER_WIDE | 2 | assets/locations/LOC_01_classroom/masters/master_wide.png | Yes |
| LOC_01_FRONT | 2 | assets/locations/LOC_01_classroom/masters/front.png | Yes |
| LOC_01_WINDOW_SIDE | 2 | assets/locations/LOC_01_classroom/masters/window_side.png | Yes |
| LOC_01_SEMICIRCLE | 2 | assets/locations/LOC_01_classroom/masters/semicircle.png | Yes |
| PROP_03_DESK_CHAIR_MASTER | 2 | assets/props/PROP_03_desk_chair/master.png | Yes |
| LOC_01_DOOR_SIDE | 2 | assets/locations/LOC_01_classroom/masters/door_side.png | Yes |
| LOC_05_HOSPITAL_MASTER | 3 | assets/locations/LOC_05_hospital/masters/master_wide.png | Yes |
| PROP_04_BED_TUBING | 3 | assets/props/PROP_04_hospital_bed/master.png | Yes |
| CHAR_01_SHOCK_WAKE_POSE | 3 | assets/characters/CHAR_01_Ah_Lim/poses/wake_shocked.png | Yes |
| CHAR_02_GREETING_POSE | 3 | assets/characters/CHAR_02_Ah_Da/poses/greeting.png | Yes |
| LOC_01_REUNION_SETUP | 3 | assets/locations/LOC_01_classroom/variants/reunion_setup.png | Yes |
| LOC_02_MASTER | 4 | assets/locations/LOC_02_field/masters/master_wide.png | Yes |
| LOC_03_MASTER | 4 | assets/locations/LOC_03_gate/masters/master_wide.png | Yes |
| LOC_04_MASTER | 4 | assets/locations/LOC_04_canteen/masters/master_wide.png | Yes |
| LOC_06_MASTER | 4 | assets/locations/LOC_06_basketball_court/masters/master_wide.png | Yes |
| LOC_07_MASTER | 4 | assets/locations/LOC_07_school_corridor/masters/master_wide.png | Yes |
| LOC_03_FACADE_RUN | 4 | assets/locations/LOC_03_gate/variants/facade_run.png | Yes |
| LOC_04_TABLE_SET | 4 | assets/locations/LOC_04_canteen/props/table_set.png | Yes |
| CHAR_03_PORTRAIT | 5 | assets/characters/CHAR_03_Jenny/portrait.png | Yes |
| CHAR_03_ACTION | 5 | assets/characters/CHAR_03_Jenny/action.png | Yes |
| CHAR_04_PORTRAIT | 5 | assets/characters/CHAR_04_Ah_Guang/portrait.png | Yes |
| CHAR_04_ACTION | 5 | assets/characters/CHAR_04_Ah_Guang/action.png | Yes |
| CHAR_05_PORTRAIT | 5 | assets/characters/CHAR_05_Huang_Ming/portrait.png | Yes |
| CHAR_05_ACTION | 5 | assets/characters/CHAR_05_Huang_Ming/action.png | Yes |
| CHAR_06_PORTRAIT | 5 | assets/characters/CHAR_06_May/portrait.png | Yes |
| CHAR_06_ACTION | 5 | assets/characters/CHAR_06_May/action.png | Yes |
| CHAR_07_PORTRAIT | 5 | assets/characters/CHAR_07_Li_Jie/portrait.png | Yes |
| CHAR_07_ACTION | 5 | assets/characters/CHAR_07_Li_Jie/action.png | Yes |
| CHAR_08_PORTRAIT | 5 | assets/characters/CHAR_08_Anna/portrait.png | Yes |
| CHAR_08_ACTION | 5 | assets/characters/CHAR_08_Anna/action.png | Yes |
| PROP_05_CANTEEN_MEAL | 6 | assets/props/PROP_05_canteen_meal/master.png | Yes |
| PROP_06_MATTRESS_STACK | 6 | assets/props/PROP_06_mattress_stack/master.png | Yes |
| PROP_07_BASKETBALL_HOOP | 6 | assets/props/PROP_07_basketball_hoop/master.png | Yes |
| PROP_09_WHITEBOARD | 6 | assets/props/PROP_09_whiteboard/master.png | Yes |

### GENERATED

| Asset ID | Stage | Output path | File present |
| --- | --- | --- | --- |
| PROP_02_ATTENDANCE_PAPER | 6 | assets/props/PROP_02_attendance_paper/master.png | Yes |

### NOT_GENERATED

| Asset ID | Stage | Output path | File present |
| --- | --- | --- | --- |
| PROP_01_WATCH | 6 | assets/props/PROP_01_watch/master.png | No |

### Approved assets with stale review status

- CHAR_01_FACE_FRONT_NEUTRAL: review says GENERATED; manifest remains APPROVED.
- CHAR_01_FACE_3Q_TALKING: review says REVIEW_REQUIRED; manifest remains APPROVED.
- CHAR_01_PROFILE_LEFT: corrected replacement is human-reviewed and APPROVED. The obsolete duplicate backup is retained and is not canonical.
- CHAR_01_FULL_BODY_FRONT: review says REVIEW_REQUIRED; manifest remains APPROVED.
- CHAR_01_FULL_BODY_3Q: review says REVIEW_REQUIRED; manifest remains APPROVED.
- CHAR_01_FULL_BODY_SIDE: review says REVIEW_REQUIRED; manifest remains APPROVED.
- CHAR_01_SEATED_NEUTRAL: review says REVIEW_REQUIRED; manifest remains APPROVED.
- CHAR_02_FACE_FRONT_NEUTRAL: review says REVIEW_REQUIRED; manifest remains APPROVED.
- CHAR_02_FACE_3Q_TALKING: review says REVIEW_REQUIRED; manifest remains APPROVED.
- CHAR_02_PROFILE_LEFT: review says REVIEW_REQUIRED; manifest remains APPROVED.
- CHAR_02_FULL_BODY_FRONT: review says REVIEW_REQUIRED; manifest remains APPROVED.
- CHAR_02_FULL_BODY_3Q: review says REVIEW_REQUIRED; manifest remains APPROVED.
- CHAR_02_FULL_BODY_SIDE: review says REVIEW_REQUIRED; manifest remains APPROVED.
