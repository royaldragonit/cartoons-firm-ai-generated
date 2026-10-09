# Shot Production Preflight Audit

Stage 6 asset production is complete for current production needs. This is an audit and planning document only; no shots, video, FX, or blocking references were generated.

## 1. Production readiness summary

| Status | Count |
| --- | ---: |
| READY | 8 |
| READY_WITH_BLOCKING_REFERENCE | 53 |
| BLOCKED | 5 |

Text-lock shots: **2**. VIDEO_STAGE_FX shots: **4**.

Classification rule: `READY` means approved assets are present and the shot is simple enough to proceed directly. `READY_WITH_BLOCKING_REFERENCE` means dependencies are available but source-specific staging, multi-character eyelines, object interaction, or complex positioning should be locked first. `BLOCKED` means a required continuity asset or identity is absent or unresolved.

## 2. Shot-by-shot table

| Shot | Scene | Source | Location | Characters / variant | Important props | Status | Blocking ref | Text lock | Motion FX | Blocker / note |
| --- | ---: | --- | --- | --- | --- | --- | :---: | :---: | --- | --- |
| SHOT_001 | 1 | 1.jpg | LOC_05 | CHAR_01 elderly hospital variant; anonymous hospital staff/extras | PROP_04_BED_TUBING | READY_WITH_BLOCKING_REFERENCE | YES | NO | NONE | Use canonical EXTRA_HOSPITAL_STAFF_GROUP; old family/visitors wording is stale. |
| SHOT_002 | 1 | 1.jpg | LOC_05 | CHAR_01 elderly hospital variant; anonymous hospital staff/extras | PROP_04_BED_TUBING | READY_WITH_BLOCKING_REFERENCE | YES | NO | NONE | Use canonical EXTRA_HOSPITAL_STAFF_GROUP; old family/visitors wording is stale. |
| SHOT_003 | 1 | 2.jpg | LOC_05 | CHAR_01 elderly hospital variant | none | READY | NO | NO | NONE | Direct-generation candidate from approved masters; no special blocking reference required. |
| SHOT_004 | 2 | 3.jpg | LOC_01 | CHAR_01 young/afterlife; CHAR_02 young/afterlife | PROP_03_DESK_CHAIR_MASTER | READY | NO | NO | NONE | Direct-generation candidate from approved masters; no special blocking reference required. |
| SHOT_005 | 2 | 3.jpg | LOC_01 | CHAR_01 young/afterlife; CHAR_02 young/afterlife | PROP_03_DESK_CHAIR_MASTER | READY | NO | NO | NONE | Direct-generation candidate from approved masters; no special blocking reference required. |
| SHOT_006 | 2 | 3.jpg | LOC_01 | CHAR_01 young/afterlife; CHAR_02 young/afterlife | PROP_03_DESK_CHAIR_MASTER | READY | NO | NO | NONE | Direct-generation candidate from approved masters; no special blocking reference required. |
| SHOT_007 | 2 | 4.jpg | LOC_01 | CHAR_01 young/afterlife; CHAR_02 young/afterlife | PROP_03_DESK_CHAIR_MASTER | READY_WITH_BLOCKING_REFERENCE | YES | NO | NONE | Approved assets are available; create a source-specific blocking/keyframe reference before shot rendering. |
| SHOT_008 | 2 | 4.jpg | LOC_01 | CHAR_01 young/afterlife; CHAR_02 young/afterlife | PROP_03_DESK_CHAIR_MASTER | READY_WITH_BLOCKING_REFERENCE | YES | NO | NONE | Approved assets are available; create a source-specific blocking/keyframe reference before shot rendering. |
| SHOT_009 | 2 | 5.jpg | LOC_01 | CHAR_01 young/afterlife; CHAR_02 young/afterlife | PROP_03_DESK_CHAIR_MASTER | READY_WITH_BLOCKING_REFERENCE | YES | NO | NONE | Approved assets are available; create a source-specific blocking/keyframe reference before shot rendering. |
| SHOT_010 | 2 | 5.jpg | LOC_01 | CHAR_01 young/afterlife; CHAR_02 young/afterlife | PROP_03_DESK_CHAIR_MASTER | READY_WITH_BLOCKING_REFERENCE | YES | NO | NONE | Approved assets are available; create a source-specific blocking/keyframe reference before shot rendering. |
| SHOT_011 | 2 | 6.jpg | LOC_01 | CHAR_01 young/afterlife; CHAR_02 young/afterlife | PROP_02_ATTENDANCE_PAPER | READY_WITH_BLOCKING_REFERENCE | YES | YES | NONE | TEXT_LOCK_REQUIRED: use approved deterministic attendance paper; source panel 6 corresponds to SHOT_011 while the manifest dependency is stale at SHOT_012. |
| SHOT_012 | 2 | 7.jpg | LOC_01 | CHAR_01 young/afterlife; CHAR_02 young/afterlife | PROP_03_DESK_CHAIR_MASTER | READY_WITH_BLOCKING_REFERENCE | YES | NO | NONE | Approved assets are available; create a source-specific blocking/keyframe reference before shot rendering. |
| SHOT_013 | 2 | 7.jpg | LOC_01 | CHAR_01 young/afterlife; CHAR_02 young/afterlife | PROP_03_DESK_CHAIR_MASTER | READY_WITH_BLOCKING_REFERENCE | YES | NO | NONE | Approved assets are available; create a source-specific blocking/keyframe reference before shot rendering. |
| SHOT_014 | 2 | 8.jpg | LOC_01 | CHAR_01 young/afterlife; CHAR_02 young/afterlife | PROP_03_DESK_CHAIR_MASTER | READY_WITH_BLOCKING_REFERENCE | YES | NO | NONE | Approved assets are available; create a source-specific blocking/keyframe reference before shot rendering. |
| SHOT_015 | 2 | 8.jpg | LOC_01 | CHAR_01 young/afterlife; CHAR_02 young/afterlife | PROP_03_DESK_CHAIR_MASTER | READY_WITH_BLOCKING_REFERENCE | YES | NO | NONE | Approved assets are available; create a source-specific blocking/keyframe reference before shot rendering. |
| SHOT_016 | 2 | 9.jpg | LOC_01 | CHAR_01 young/afterlife; CHAR_02 young/afterlife | PROP_03_DESK_CHAIR_MASTER | READY_WITH_BLOCKING_REFERENCE | YES | NO | NONE | Approved assets are available; create a source-specific blocking/keyframe reference before shot rendering. |
| SHOT_017 | 2 | 9.jpg | LOC_01 | CHAR_01 young/afterlife; CHAR_02 young/afterlife | PROP_03_DESK_CHAIR_MASTER | READY_WITH_BLOCKING_REFERENCE | YES | NO | NONE | Approved assets are available; create a source-specific blocking/keyframe reference before shot rendering. |
| SHOT_018 | 3 | 10.jpg | LOC_01 | CHAR_01 young/afterlife; CHAR_02 young/afterlife | PROP_01_WATCH | BLOCKED | YES | NO | NONE | BLOCKED: PROP_01_WATCH is absent; 10.jpg visibly uses the wristwatch for the three-hour story beat. |
| SHOT_019 | 3 | 10.jpg | LOC_01 | CHAR_01 young/afterlife; CHAR_02 young/afterlife | PROP_01_WATCH | BLOCKED | YES | NO | NONE | BLOCKED: PROP_01_WATCH is absent; 10.jpg visibly uses the wristwatch for the three-hour story beat. |
| SHOT_020 | 3 | 11.jpg | LOC_01 | CHAR_01 young/afterlife; CHAR_02 young/afterlife | PROP_03_DESK_CHAIR_MASTER | READY_WITH_BLOCKING_REFERENCE | YES | NO | NONE | Approved assets are available; create a source-specific blocking/keyframe reference before shot rendering. |
| SHOT_021 | 3 | 11.jpg | LOC_01 | CHAR_01 young/afterlife; CHAR_02 young/afterlife | PROP_03_DESK_CHAIR_MASTER | READY_WITH_BLOCKING_REFERENCE | YES | NO | NONE | Approved assets are available; create a source-specific blocking/keyframe reference before shot rendering. |
| SHOT_022 | 3 | 12.jpg | LOC_01 | CHAR_01 young/afterlife; CHAR_02 young/afterlife | PROP_03_DESK_CHAIR_MASTER | READY_WITH_BLOCKING_REFERENCE | YES | NO | NONE | Approved assets are available; create a source-specific blocking/keyframe reference before shot rendering. |
| SHOT_023 | 3 | 12.jpg | LOC_01 | CHAR_01 young/afterlife; CHAR_02 young/afterlife | PROP_03_DESK_CHAIR_MASTER | READY_WITH_BLOCKING_REFERENCE | YES | NO | NONE | Approved assets are available; create a source-specific blocking/keyframe reference before shot rendering. |
| SHOT_024 | 3 | 13.jpg | LOC_01 | CHAR_01 young/afterlife; CHAR_02 young/afterlife | PROP_03_DESK_CHAIR_MASTER | READY_WITH_BLOCKING_REFERENCE | YES | NO | NONE | Approved assets are available; create a source-specific blocking/keyframe reference before shot rendering. |
| SHOT_025 | 3 | 13.jpg | LOC_01 | CHAR_01 young/afterlife; CHAR_02 young/afterlife | PROP_03_DESK_CHAIR_MASTER | READY_WITH_BLOCKING_REFERENCE | YES | NO | NONE | Approved assets are available; create a source-specific blocking/keyframe reference before shot rendering. |
| SHOT_026 | 3 | 14.jpg | LOC_01 | CHAR_01 young/afterlife; CHAR_02 young/afterlife | PROP_03_DESK_CHAIR_MASTER | READY_WITH_BLOCKING_REFERENCE | YES | NO | NONE | Approved assets are available; create a source-specific blocking/keyframe reference before shot rendering. |
| SHOT_027 | 3 | 14.jpg | LOC_01 | CHAR_01 young/afterlife; CHAR_02 young/afterlife | PROP_03_DESK_CHAIR_MASTER | READY_WITH_BLOCKING_REFERENCE | YES | NO | NONE | Approved assets are available; create a source-specific blocking/keyframe reference before shot rendering. |
| SHOT_028 | 3 | 15.jpg | LOC_01 | CHAR_01 young/afterlife; CHAR_02 young/afterlife | PROP_03_DESK_CHAIR_MASTER | READY_WITH_BLOCKING_REFERENCE | YES | NO | NONE | Approved assets are available; create a source-specific blocking/keyframe reference before shot rendering. |
| SHOT_029 | 3 | 15.jpg | LOC_01 | CHAR_01 young/afterlife; CHAR_02 young/afterlife | PROP_03_DESK_CHAIR_MASTER | READY_WITH_BLOCKING_REFERENCE | YES | NO | NONE | Approved assets are available; create a source-specific blocking/keyframe reference before shot rendering. |
| SHOT_030 | 3 | 16.jpg | LOC_01 | CHAR_01 young/afterlife; CHAR_02 young/afterlife | PROP_03_DESK_CHAIR_MASTER | READY_WITH_BLOCKING_REFERENCE | YES | NO | NONE | Approved assets are available; create a source-specific blocking/keyframe reference before shot rendering. |
| SHOT_031 | 3 | 16.jpg | LOC_01 | CHAR_01 young/afterlife; CHAR_02 young/afterlife | PROP_03_DESK_CHAIR_MASTER | READY_WITH_BLOCKING_REFERENCE | YES | NO | NONE | Approved assets are available; create a source-specific blocking/keyframe reference before shot rendering. |
| SHOT_032 | 3 | 17.jpg | LOC_01 | CHAR_01 young/afterlife; CHAR_02 young/afterlife | PROP_03_DESK_CHAIR_MASTER | READY_WITH_BLOCKING_REFERENCE | YES | NO | NONE | Approved assets are available; create a source-specific blocking/keyframe reference before shot rendering. |
| SHOT_033 | 3 | 17.jpg | LOC_01 | CHAR_01 young/afterlife; CHAR_02 young/afterlife | PROP_03_DESK_CHAIR_MASTER | READY_WITH_BLOCKING_REFERENCE | YES | NO | NONE | Approved assets are available; create a source-specific blocking/keyframe reference before shot rendering. |
| SHOT_034 | 3 | 18.jpg | LOC_01 | CHAR_01 young/afterlife; CHAR_02 young/afterlife | PROP_03_DESK_CHAIR_MASTER | READY_WITH_BLOCKING_REFERENCE | YES | NO | NONE | Approved assets are available; create a source-specific blocking/keyframe reference before shot rendering. |
| SHOT_035 | 3 | 18.jpg | LOC_01 | CHAR_01 young/afterlife; CHAR_02 young/afterlife | PROP_03_DESK_CHAIR_MASTER | READY_WITH_BLOCKING_REFERENCE | YES | NO | NONE | Approved assets are available; create a source-specific blocking/keyframe reference before shot rendering. |
| SHOT_036 | 4 | 19.jpg | LOC_01 | CHAR_03 Jenny; unknown classmate/extras | PROP_03_DESK_CHAIR_MASTER | READY_WITH_BLOCKING_REFERENCE | YES | NO | NONE | Approved assets are available; create a source-specific blocking/keyframe reference before shot rendering. |
| SHOT_037 | 5 | 20.jpg | LOC_01 | none | PROP_03_DESK_CHAIR_MASTER | READY | NO | NO | NONE | Direct-generation candidate from approved masters; no special blocking reference required. |
| SHOT_038 | 5 | 21.jpg | LOC_01 | CHAR_04 Ah Guang; CHAR_02 young/afterlife | PROP_03_DESK_CHAIR_MASTER | READY_WITH_BLOCKING_REFERENCE | YES | NO | NONE | Approved assets are available; create a source-specific blocking/keyframe reference before shot rendering. |
| SHOT_039 | 6 | 22.jpg | LOC_02 | CHAR_05 Huang Ming; unknown classmate/extras | PROP_06_MATTRESS_STACK | READY_WITH_BLOCKING_REFERENCE | YES | NO | NONE | Approved assets are available; create a source-specific blocking/keyframe reference before shot rendering. |
| SHOT_040 | 7 | 23.jpg | LOC_01 | CHAR_06 May; unknown classmate/extras | PROP_03_DESK_CHAIR_MASTER | READY_WITH_BLOCKING_REFERENCE | YES | NO | NONE | Approved assets are available; create a source-specific blocking/keyframe reference before shot rendering. |
| SHOT_041 | 7 | 23.jpg | LOC_01 | CHAR_06 May; unknown classmate/extras | PROP_03_DESK_CHAIR_MASTER | READY_WITH_BLOCKING_REFERENCE | YES | NO | NONE | Approved assets are available; create a source-specific blocking/keyframe reference before shot rendering. |
| SHOT_042 | 8 | 24.jpg | LOC_02 | CHAR_07 Li Jie; unknown classmate/extras | none | READY_WITH_BLOCKING_REFERENCE | YES | NO | VIDEO_STAGE_FX | Motion accents are VIDEO_STAGE_FX; do not create a reusable FX asset. |
| SHOT_043 | 8 | 24.jpg | LOC_02 | CHAR_07 Li Jie; unknown classmate/extras | none | READY_WITH_BLOCKING_REFERENCE | YES | NO | VIDEO_STAGE_FX | Motion accents are VIDEO_STAGE_FX; do not create a reusable FX asset. |
| SHOT_044 | 9 | 25.jpg | LOC_03 | Kim Fook — missing canonical master; stale shot ID is CHAR_08; CHAR_02 young/afterlife | PROP_08_RAILING | BLOCKED | YES | NO | NONE | BLOCKED: source is Kim Fook, but metadata assigns CHAR_08, which is canonical Anna; no Kim Fook master is available. |
| SHOT_045 | 10 | 26.jpg | LOC_06 | CHAR_08 Anna — canonical; stale shot ID is CHAR_09; unknown classmate/extras | PROP_07_BASKETBALL_HOOP | READY_WITH_BLOCKING_REFERENCE | YES | NO | VIDEO_STAGE_FX | Canonicalize stale CHAR_09 to approved CHAR_08 Anna before rendering; preserve source-specific basketball blocking. Motion accents are VIDEO_STAGE_FX; do not create a reusable FX asset. |
| SHOT_046 | 11 | 27.jpg | LOC_01 | CHAR_01 young/afterlife; CHAR_02 young/afterlife | PROP_03_DESK_CHAIR_MASTER | READY_WITH_BLOCKING_REFERENCE | YES | NO | NONE | Approved assets are available; create a source-specific blocking/keyframe reference before shot rendering. |
| SHOT_047 | 11 | 27.jpg | LOC_01 | CHAR_01 young/afterlife; CHAR_02 young/afterlife | PROP_03_DESK_CHAIR_MASTER | READY_WITH_BLOCKING_REFERENCE | YES | NO | NONE | Approved assets are available; create a source-specific blocking/keyframe reference before shot rendering. |
| SHOT_048 | 11 | 28.jpg | LOC_07 | CHAR_01 young/afterlife; CHAR_02 young/afterlife | none | READY_WITH_BLOCKING_REFERENCE | YES | NO | NONE | Use LOC_07 school corridor; any LOC_01 door-side association is stale. |
| SHOT_049 | 11 | 28.jpg | LOC_07 | CHAR_01 young/afterlife; CHAR_02 young/afterlife | none | READY_WITH_BLOCKING_REFERENCE | YES | NO | NONE | Use LOC_07 school corridor; any LOC_01 door-side association is stale. |
| SHOT_050 | 12 | 29.jpg | LOC_04 | CHAR_01 young/afterlife; CHAR_02 young/afterlife | PROP_05_CANTEEN_MEAL, LOC_04_TABLE_SET | READY_WITH_BLOCKING_REFERENCE | YES | NO | NONE | Approved assets are available; create a source-specific blocking/keyframe reference before shot rendering. |
| SHOT_051 | 12 | 29.jpg | LOC_04 | CHAR_01 young/afterlife; CHAR_02 young/afterlife | PROP_05_CANTEEN_MEAL, LOC_04_TABLE_SET | READY_WITH_BLOCKING_REFERENCE | YES | NO | NONE | Approved assets are available; create a source-specific blocking/keyframe reference before shot rendering. |
| SHOT_052 | 12 | 29.jpg | LOC_04 | CHAR_01 young/afterlife; CHAR_02 young/afterlife | PROP_05_CANTEEN_MEAL, LOC_04_TABLE_SET | READY_WITH_BLOCKING_REFERENCE | YES | NO | NONE | Approved assets are available; create a source-specific blocking/keyframe reference before shot rendering. |
| SHOT_053 | 12 | 29.jpg | LOC_04 | CHAR_01 young/afterlife; CHAR_02 young/afterlife | PROP_05_CANTEEN_MEAL, LOC_04_TABLE_SET | READY | NO | NO | NONE | Direct-generation candidate from approved masters; no special blocking reference required. |
| SHOT_054 | 12 | 30.jpg | LOC_04 | CHAR_01 young/afterlife; CHAR_02 young/afterlife | PROP_05_CANTEEN_MEAL, LOC_04_TABLE_SET | READY_WITH_BLOCKING_REFERENCE | YES | NO | NONE | Approved assets are available; create a source-specific blocking/keyframe reference before shot rendering. |
| SHOT_055 | 12 | 30.jpg | LOC_04 | CHAR_01 young/afterlife; CHAR_02 young/afterlife | PROP_05_CANTEEN_MEAL, LOC_04_TABLE_SET | READY_WITH_BLOCKING_REFERENCE | YES | NO | NONE | Approved assets are available; create a source-specific blocking/keyframe reference before shot rendering. |
| SHOT_056 | 12 | 30.jpg | LOC_04 | CHAR_01 young/afterlife; CHAR_02 young/afterlife | PROP_05_CANTEEN_MEAL, LOC_04_TABLE_SET | READY_WITH_BLOCKING_REFERENCE | YES | NO | NONE | Approved assets are available; create a source-specific blocking/keyframe reference before shot rendering. |
| SHOT_057 | 12 | 31.jpg | LOC_04 | CHAR_01 young/afterlife; CHAR_02 young/afterlife | PROP_01_WATCH | BLOCKED | YES | NO | NONE | BLOCKED: 31.jpg visibly shows the wristwatch as the time cue; PROP_01_WATCH remains deferred and absent. |
| SHOT_058 | 12 | 31.jpg | LOC_04 | CHAR_01 young/afterlife; CHAR_02 young/afterlife | PROP_01_WATCH | BLOCKED | YES | NO | NONE | BLOCKED: 31.jpg visibly shows the wristwatch as the time cue; PROP_01_WATCH remains deferred and absent. |
| SHOT_059 | 13 | 32.jpg | LOC_03 | CHAR_01 young/afterlife; CHAR_02 young/afterlife | PROP_08_RAILING | READY_WITH_BLOCKING_REFERENCE | YES | NO | NONE | Approved assets are available; create a source-specific blocking/keyframe reference before shot rendering. |
| SHOT_060 | 13 | 32.jpg | LOC_03 | CHAR_01 young/afterlife; CHAR_02 young/afterlife | PROP_08_RAILING | READY_WITH_BLOCKING_REFERENCE | YES | NO | NONE | Approved assets are available; create a source-specific blocking/keyframe reference before shot rendering. |
| SHOT_061 | 13 | 33.jpg | LOC_03 | CHAR_01 young/afterlife; CHAR_02 young/afterlife | PROP_08_RAILING | READY_WITH_BLOCKING_REFERENCE | YES | NO | NONE | Approved assets are available; create a source-specific blocking/keyframe reference before shot rendering. |
| SHOT_062 | 13 | 33.jpg | LOC_03 | CHAR_01 young/afterlife; CHAR_02 young/afterlife | PROP_08_RAILING | READY_WITH_BLOCKING_REFERENCE | YES | NO | NONE | Approved assets are available; create a source-specific blocking/keyframe reference before shot rendering. |
| SHOT_063 | 13 | 34.jpg | LOC_03 | CHAR_02 young/afterlife | none | READY_WITH_BLOCKING_REFERENCE | YES | NO | VIDEO_STAGE_FX | Motion accents are VIDEO_STAGE_FX; do not create a reusable FX asset. |
| SHOT_064 | 13 | 35.jpg | LOC_03 | CHAR_02 young/afterlife | none | READY_WITH_BLOCKING_REFERENCE | YES | NO | NONE | Approved assets are available; create a source-specific blocking/keyframe reference before shot rendering. |
| SHOT_065 | 13 | 35.jpg | LOC_03 | CHAR_02 young/afterlife | none | READY | NO | NO | NONE | Direct-generation candidate from approved masters; no special blocking reference required. |
| SHOT_066 | 14 | 36.jpg | LOC_01 | none | PROP_09_WHITEBOARD, PROP_03_DESK_CHAIR_MASTER | READY | NO | YES | NONE | TEXT_LOCK_REQUIRED: use approved deterministic PROP_09_WHITEBOARD; do not ask the video model to recreate farewell writing. |

## 3. Blocking-reference queue

Create blocking/keyframe references before rendering these shots; do not generate them during this audit.

- SHOT_001
- SHOT_002
- SHOT_007
- SHOT_008
- SHOT_009
- SHOT_010
- SHOT_011
- SHOT_012
- SHOT_013
- SHOT_014
- SHOT_015
- SHOT_016
- SHOT_017
- SHOT_020
- SHOT_021
- SHOT_022
- SHOT_023
- SHOT_024
- SHOT_025
- SHOT_026
- SHOT_027
- SHOT_028
- SHOT_029
- SHOT_030
- SHOT_031
- SHOT_032
- SHOT_033
- SHOT_034
- SHOT_035
- SHOT_036
- SHOT_038
- SHOT_039
- SHOT_040
- SHOT_041
- SHOT_042
- SHOT_043
- SHOT_045
- SHOT_046
- SHOT_047
- SHOT_048
- SHOT_049
- SHOT_050
- SHOT_051
- SHOT_052
- SHOT_054
- SHOT_055
- SHOT_056
- SHOT_059
- SHOT_060
- SHOT_061
- SHOT_062
- SHOT_063
- SHOT_064

## 4. Direct-generation queue

- SHOT_003
- SHOT_004
- SHOT_005
- SHOT_006
- SHOT_037
- SHOT_053
- SHOT_065
- SHOT_066

## 5. Blocked shots

| Shot | Exact blocker | Required action |
| --- | --- | --- |
| SHOT_018 | `PROP_01_WATCH` is NOT_GENERATED; 10.jpg makes the wristwatch part of the three-hour beat. | Generate/approve the watch or explicitly authorize an alternative before rendering. |
| SHOT_019 | `PROP_01_WATCH` is NOT_GENERATED; 10.jpg makes the wristwatch part of the three-hour beat. | Generate/approve the watch or explicitly authorize an alternative before rendering. |
| SHOT_044 | Source character is Kim Fook, but metadata says CHAR_08; CHAR_08 is canonical Anna and no Kim Fook master exists. | Resolve the character ID and provide/approve the correct Kim Fook reference. |
| SHOT_057 | `PROP_01_WATCH` is NOT_GENERATED; 31.jpg visibly uses the wristwatch as the time cue. | Generate/approve the watch or explicitly authorize an alternative before rendering. |
| SHOT_058 | `PROP_01_WATCH` is NOT_GENERATED; 31.jpg visibly uses the wristwatch as the time cue. | Generate/approve the watch or explicitly authorize an alternative before rendering. |

## 6. Deferred items

- `PROP_01_WATCH`: `DEFERRED_NONBLOCKING` for shots that do not require it, but it becomes a `MISSING_BLOCKER` for SHOT_018, SHOT_019, SHOT_057, and SHOT_058 because the source visibly makes the watch story-critical. It remains NOT_GENERATED; do not generate it during this audit.
- Anonymous classmates/extras: `NOT_REQUIRED_AS_SEPARATE_ASSET`; use source-specific blocking or background silhouettes as appropriate.
- Hospital visitor/family terminology: use the approved anonymous hospital staff group; the obsolete visitor group is noncanonical.

## 7. Metadata inconsistencies

These are reported for later cleanup; no existing shot-list or manifest JSON was modified.
- **Anna ID drift:** `06_scenes.json`, `07_shot_list.md`, `08_shot_list.json`, `10_asset_design_plan.md`, and `12_generation_queue.md` still use CHAR_09 for Anna/SHOT_045. Canonical Anna is CHAR_08; no CHAR_09 asset should be created.
- **Kim Fook identity collision:** SHOT_044 uses CHAR_08 in `07_shot_list.md`/`08_shot_list.json`, but source 25.jpg is Kim Fook and CHAR_08 is Anna. No canonical Kim Fook pack exists.
- **Hospital terminology:** source/shot metadata still says family/visitors in places; current continuity uses `EXTRA_HOSPITAL_STAFF_GROUP`, while the obsolete visitor group is noncanonical.
- **Watch dependencies:** manifest/queue list PROP_01_WATCH for SHOT_013 and SHOT_054, but source panels 10 and 31 make it relevant to SHOT_018/019 and SHOT_057/058. The current missing watch blocks those four shots.
- **Attendance-paper dependency:** manifest assigns PROP_02_ATTENDANCE_PAPER to SHOT_012, although source panel 6 and the shot list use SHOT_011.
- **Classroom door-side dependency:** manifest/queue associate LOC_01_DOOR_SIDE with SHOT_048, but source 28.jpg and current shot list use LOC_07 corridor for SHOT_048/049.
- **Field master dependency:** manifest lists LOC_02_MASTER for SHOT_041, although SHOT_041 is May in LOC_01; LOC_02 is operationally needed for SHOT_039.
- **Gate/canteen overlap:** LOC_03 manifest dependencies still include SHOT_057/058 even though those shots are canteen LOC_04; LOC_03 remains correct for SHOT_044 and SHOT_059–065.
- **Stale generation queue:** `12_generation_queue.md` still shows old NOT_GENERATED planning, obsolete CHAR_09 paths, and omissions from the inserted hospital/stage-6 corrections; it is not executable authority.
- **Provisional summary:** `09_production_summary.md` remains a high-level difficulty/runtime summary; use this preflight for current readiness and dependency decisions.

## 8. Recommended FIRST production shot

**SHOT_037** — a low-complexity window/desk insert with no visible character, using approved LOC_01_WINDOW_SIDE and classroom furniture. It is a useful pipeline test for environment continuity, camera movement, and narration/caption handling before multi-character blocking or missing-asset shots.

No shot rendering has started.

