# Project state and recovery handoff

Handoff date: 2026-09-18 (Asia/Bangkok). Repository HEAD at audit: `4a23550`.
Current project root: `D:\Projects\cartoons-firm-ai-generated`.
The former root `D:\Personals\Projects\Films\Cartoons` is obsolete and must not be used operationally.

## Purpose and authority

Produce reusable visual assets, then animated shots, from 36 source comic/storyboard panels. The shot plan contains 66 shots grouped into 14 narrative scenes, with a provisional estimated runtime of 401.9 seconds. `06_scenes.json` contains 36 panel-level scene records; this differs intentionally from the narrative-scene grouping.

`11_asset_manifest.json` is the primary authority for current asset IDs and statuses. Review files preserve human-review history but several have not been synchronized. Approved generated masters govern stable character identity and location continuity; source panels govern story-specific staging, pose, directionality, props, and emotion. Preserve approved identity when incidental source variation conflicts, unless the human requests a source-specific variant.

Workflow: NOT_GENERATED -> GENERATED -> APPROVED. Generated assets require human review. Never auto-approve or modify approved assets without explicit human instruction. Generate only the requested asset and stop. Action references normally contain one character and minimal supporting furniture/props, not a complete scene. Add environments and other characters during shot blocking. Defer speed streaks, wind, dust, and motion accents to shots/video unless an FX asset is specifically requested. Reuse approved props and locations. Use deterministic compositing for important readable text. Do not invent dialogue for [INDISTINCT CHATTER].

## Current production stage

Stage 6 (secondary props) is partially complete. Stages 1-5 and inserted hospital continuity stage 3.5 are APPROVED according to the manifest. This is an asset-production checkpoint, not evidence of completed animated shots.

| Stage | Scope | Manifest state |
| --- | --- | --- |
| 1 | Ah Lim and Ah Da young/afterlife masters | 14 approved |
| 2 | Classroom and desk/chair lock | 6 approved |
| 3 | Pilot support | 5 approved |
| 3.5 | Elderly Ah Lim portrait/bed pose and hospital staff | 3 approved |
| 4 | Remaining locations and canteen table set | 7 approved |
| 5 | Six supporting portrait/action packs | 12 approved |
| 6 | Secondary props | 2 approved, 2 generated, 3 not generated |

Total: **54 manifest assets: 48 APPROVED, 3 GENERATED, 3 NOT_GENERATED**. Counts are manifest states, not a fresh approval or a guarantee of file correctness.

## Audit findings — unresolved, no fixes applied

1. **Watch deferred:** `PROP_01_WATCH` was reset from an invalid GENERATED state to `NOT_GENERATED` because its expected output and review files were missing after migration. It remains a low-priority deferred prop; no asset was regenerated. Regenerate only if SHOT_013 or SHOT_054 later requires a visible watch.
2. **Profile repair completed:** The old approved `profile_left.png` was an accidental duplicate of `face_3q_talking.png`; it was preserved as `profile_left_obsolete_duplicate.png`. The corrected true viewer-left profile was human-reviewed and restored to `APPROVED` for `CHAR_01_PROFILE_LEFT`. The obsolete backup remains non-canonical.
3. **Outdated reviews:** all seven Ah Lim stage-1 master reviews and six Ah Da stage-1 reviews (all except seated-neutral) still state GENERATED or REVIEW_REQUIRED despite APPROVED manifest status. Treat them as stale history, not authority to revoke approval. Their exact IDs are listed below. `LOC_01_FRONT` also retains a superseded approval-required sentence inside a review that records explicit approval.
4. **Obsolete visitor assets:** `assets/extras/hospital_visitors/group.png` and `group_review.md` are unreferenced remnants. They are not canonical or part of the pending manifest queue. Preserve them on disk. `EXTRA_HOSPITAL_STAFF_GROUP` is approved and present. Visitor wording also survives in `06_scenes.json`, hospital shots in `07_shot_list.md`/`08_shot_list.json`, `10_asset_design_plan.md`, and the bed/tubing review.
5. **Stale identity mapping:** `03_character_bible.md`, `06_scenes.json`, `07_shot_list.md`, `08_shot_list.json`, `10_asset_design_plan.md`, and `12_generation_queue.md` still map Kim Fook to CHAR_08 and Anna to CHAR_09. Current manifest and files correctly map Anna to CHAR_08, with no CHAR_09 entries or folder. Kim Fook remains in source panel 25 / SHOT_044 but has no current dedicated manifest pack. This is an unresolved coverage/mapping gap, not authorization to reuse Anna or create CHAR_09.
6. **Stale queue:** `12_generation_queue.md` still lists every planned entry as NOT_GENERATED, includes obsolete Kim Fook/CHAR_09 paths, and omits the inserted elderly/staff assets. Use its stage order only after checking the current manifest; do not execute it literally.
7. **Stale shot dependencies:** examples in the manifest/queue include attendance paper assigned SHOT_012 although the roll-call panel is SHOT_011; watch assigned SHOT_013/054 although watch panels 10/31 map to SHOT_018/019 and SHOT_057/058; LOC_02 includes SHOT_041 (May/classroom) instead of Li Jie's SHOT_042/043; gate includes SHOT_057/058 (canteen) while gate panel 32 starts SHOT_059. Validate dependencies against source panels and the shot list before shot work. SHOT_044's LOC_01 assignment also needs source-specific railing staging review.
8. **Stale descriptive notes:** CHAR_05_PORTRAIT's manifest notes describe a curled mattress action although its name/path/review establish a portrait. Some approved May, Li Jie, and meal entries retain 'human approval required' wording. Explicit status remains authoritative.
9. **Whiteboard approved:** `PROP_09_WHITEBOARD` is now APPROVED. Its source text matches `36.jpg`, geometry is acceptable, and the source-ambiguous `5l` class glyph was accepted by human review.
10. **Downstream planning is provisional:** vignette `narration_exact` fields point to the transcript rather than containing final narration, and several lengthy captions have short provisional shot durations. Do not treat the runtime estimate as a finalized narrated cut. `05_continuity_report.md` also contains a farewell description inconsistent with the shot list (it says the guide departs and the black-haired student remains at 33->35); check original panels before blocking.

### Integrity and missing-review checks

- All 49 approved output paths exist and are nonempty. All have corresponding review files.
- Of two generated outputs, the whiteboard exists with a review; the watch and its review are missing.
- The three NOT_GENERATED output files and their reviews are absent, as expected at that status: attendance paper, basketball/hoop, railing.
- Assets directory contains 52 PNGs and 51 review files: 51 manifest-linked image/review pairs plus the obsolete visitor pair and the obsolete profile backup.
- No duplicate manifest asset IDs or output paths. No duplicate canonical character identities found; young/elderly CHAR_01 are intentional variants. The one byte-duplicate image pair is described above.
- All 36 numbered source panels exist. No obsolete operational root reference was found in the existing text files searched. Existing project files were left untouched.
- Reviewed the twelve numbered production documents, the complete assets inventory, and all 51 review files. Parsed scene/shot/manifest JSON and checked file paths, statuses, duplicate hashes, and historical references. Targeted visual inspection covered the duplicated Ah Lim image, whiteboard, and source panel 36. This was not a new visual approval pass over every asset.

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

`PROP_08_RAILING` has been generated at `assets/props/PROP_08_railing/master.png` from manifest source `25.jpg` for `SHOT_044` and is awaiting human review. No other asset was generated.

## Recommended next task

First perform a human-directed recovery review of the missing watch and the duplicated approved Ah Lim profile, seeking the intended original files/backups before considering regeneration. Review the pending whiteboard and resolve its class-label ambiguity before approval. Reconcile stale identity/shot metadata in a separately authorized task before shot generation. None of these changes were performed during bootstrap.

After those issues are resolved and the human explicitly selects one asset, the first ungenerated Stage 6 queue item is `PROP_02_ATTENDANCE_PAPER`; then `PROP_07_BASKETBALL_HOOP` and `PROP_08_RAILING` remain. Assess whether the approved court and Anna action already provide sufficient hoop/ball references before creating a redundant prop. Do not automatically advance this queue.

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

### GENERATED

| Asset ID | Stage | Output path | File present |
| --- | --- | --- | --- |
| PROP_01_WATCH | 6 | assets/props/PROP_01_watch/master.png | No |
| PROP_09_WHITEBOARD | 6 | assets/props/PROP_09_whiteboard/master.png | Yes |

### NOT_GENERATED

| Asset ID | Stage | Output path | File present |
| --- | --- | --- | --- |
| PROP_02_ATTENDANCE_PAPER | 6 | assets/props/PROP_02_attendance_paper/master.png | No |
| PROP_07_BASKETBALL_HOOP | 6 | assets/props/PROP_07_basketball_hoop/master.png | No |
| PROP_08_RAILING | 6 | assets/props/PROP_08_railing/master.png | No |

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
