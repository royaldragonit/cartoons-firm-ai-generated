# SHOT_037 — Manual Runway Web Test Pack v001

Prepared: 2026-09-23. Status: READY_FOR_MANUAL_TEST. No media generated in this task.

## A. Current shot status

- `shots/SHOT_037/keyframe_v002.png` is HUMAN-APPROVED and LOCKED. Its review explicitly accepts the window-side target seat and the hand-to-seat composition.
- The human has REJECTED `video_v001.mp4`: its deterministic still-image zoom was insufficient. It remains review history, not an approved animation or a video reference for this attempt. Its existing review is stale and is outside this task's edit scope.
- The next test is one true model-generated image-to-video attempt from the approved PNG. `keyframe_v001.png` remains rejected history; no new keyframe is needed.
- Both preflight files identify SHOT_037 as READY, narrative scene 5, LOC_01, source 20.jpg, with no missing dependencies, text lock, or motion FX requirement. Older “video not started” statements describe earlier checkpoints.
- Manifest-verified approved references: `LOC_01_WINDOW_SIDE` and `PROP_03_DESK_CHAIR_MASTER`. The shot brief and preflight establish the prop's use here despite its incomplete legacy manifest shot list.

## B–D. Upload files, roles, and order

Repository root: `D:\Personals\Projects\Films\Cartoons`. Links below resolve to the exact existing files. Upload order, if separate auxiliary-reference slots are available, follows the numbered rows.

| Order / priority | Exact file | Role and permitted use |
| --- | --- | --- |
| 1 — REQUIRED | [shots/SHOT_037/keyframe_v002.png](D:/Personals/Projects/Films/Cartoons/shots/SHOT_037/keyframe_v002.png) | **Primary visual authority / starting image.** Locked composition, color, style, anatomy, exact target seat. 1448 × 1086, 4:3. |
| 2 — RECOMMENDED support | [assets/locations/LOC_01_classroom/masters/window_side.png](D:/Personals/Projects/Films/Cartoons/assets/locations/LOC_01_classroom/masters/window_side.png) | **Environment identity support.** APPROVED LOC_01_WINDOW_SIDE. Confirm window design, architecture, palette, and daylight; do not import its wider framing or additional visible furniture. |
| 3 — RECOMMENDED support | [assets/props/PROP_03_desk_chair/master.png](D:/Personals/Projects/Films/Cartoons/assets/props/PROP_03_desk_chair/master.png) | **Prop identity support.** APPROVED PROP_03_DESK_CHAIR_MASTER. Confirm wood surfaces, chair backs, and dark legs. Its multiple views are a reference sheet, not extra sets to add. |
| 4 — OPTIONAL support | [20.jpg](D:/Personals/Projects/Films/Cartoons/20.jpg) | **Staging reference.** Original partial hand from the right indicating a seat beside the window. Do not import panel borders, watermark, speech bubble, text, or its different drawing/framing over the approved keyframe. |
| 5 — OPTIONAL support | [21.jpg](D:/Personals/Projects/Films/Cartoons/21.jpg) | **Continuity reference.** Establishes the later Ah Guang window-seat vignette. The people and caption belong to that later panel; this test's seat remains empty. Prefer human comparison only. |

**Default first test: upload only keyframe_v002.png as the starting image.** Keep the four support images open locally for the operator's reference. Runway's documented Gen-4.5 workflow takes an image plus prompt; additional reference inputs are not established by that workflow. Do not assume a multi-image stack exists. If the chosen web mode explicitly supports auxiliary references while retaining an independent starting frame, add only the useful support images in table order and identify their roles. Never place a support image in an end-frame slot, replace the starting image, or create a collage/new keyframe. See [Runway's Gen-4.5 workflow](https://help.runwayml.com/hc/en-us/articles/46974685288467-Creating-with-Gen-4-5).

The last connector check reported workspace Long on Free with no available video models. That check did not verify the human's current web-session access; confirm an enabled image-to-video mode before running the manual test.

## H. Manual setup and generation target

1. Open Runway web's image-to-video mode available to the signed-in workspace. Use the existing PNG directly; avoid image creation, video-to-video, and automatic prompt/image redesign.
2. Upload the required starting image first. Verify the preview shows the correct hand, empty chair/desk, and window, with the original 4:3 composition intact. Use source/input aspect ratio or 4:3 where available; do not accept an automatic widescreen crop that changes the composition.
3. Select **one output, five seconds** (target approximately 4.9–5 seconds). Keep native model timing; frame-rate conversion or an exact 4.9-second editorial trim is outside this test. Select silent output / audio off if exposed; add no voice, dialogue, music, or sound effects.
4. Choose **either** the long prompt below or the short prompt for a quick test. They are alternatives for the same single attempt, not a request for two clips. Paste text only; the model does not gain access to local files from filenames in the prompt.
5. Review the starting-image preview and settings, then the human may submit **one** generation. Retain the returned clip separately from rejected video_v001, with its model/settings/prompt noted for review. Do not auto-approve, upscale, extend, batch, or start another shot.

Target: one continuous eye-level INSERT/WIDE shot with a very slight slow push-in, the exact approved seat and pointing relationship, mostly held hand pose, and restrained natural life inside the scene. Optional hand settling or ambient life must never weaken target clarity. A clip whose only movement is uniform scaling of the still fails the test.

Runway's web documentation supports a 5-second image-to-video setup and preserving the input aspect ratio for Gen-4.5 when enabled. Availability and controls must be checked in the actual web session; this pack does not assert that the connected Free workspace can run it. [Settings reference](https://help.runwayml.com/hc/en-us/articles/46974685288467-Creating-with-Gen-4-5).

## E. Long ready-to-paste prompt

Identical to `runway_prompt_v001.txt`. Use this if it fits the selected model's prompt field; use the complete short version if it does not.

```text
Animate the supplied keyframe_v002.png as the primary visual authority and exact starting composition for SHOT_037. One continuous approximately five-second silent image-to-video shot, eye-level, with only a very slight, slow, smooth camera push-in.

The visual read remains HAND -> EMPTY WINDOW-SIDE SEAT -> WINDOW. Only the existing partial pointing hand and forearm at the right edge are visible. The fingertip continues to indicate the same empty chair and desk directly beside the left-side classroom window for the entire clip. The target seat stays empty. The rest of the pointing person remains outside the frame.

The hand mostly holds its approved pose. Optional tiny natural settling in the wrist or forearm is restrained and anatomically coherent, with the pointing direction and target unchanged. Optional extremely subtle ambient life is acceptable only when nondistracting and consistent with the existing image. The result should feel like the approved still has gently come to life, with subtle life within the scene rather than only a uniform slideshow zoom.

Preserve the approved framing hierarchy, hand-to-seat relationship, seat-to-window relationship, classroom architecture, window geometry, furniture count and placement, and stable daylight. Keep clean simple 2D cartoon line art, black outlines, restrained flat colors, minimal shading, and the low-detail comic feeling. Any supplied supporting references clarify existing identities and staging only; keyframe_v002.png controls this shot.

Do not redesign the classroom, redirect the finger, change the indicated seat, move or morph desks/chairs, or add/remove furniture. Do not introduce students, a full character, extra hands/fingers, arm deformation, new props, text, speech bubbles, motion FX, wind, or dust. No pan, tilt, orbit, strong zoom, pronounced parallax, lighting transformation, cuts, photorealism, 3D, painterly rendering, or anime restyling. No audio or dialogue.
```

## F. Short ready-to-paste prompt

Identical to `runway_prompt_short_v001.txt`.

```text
Animate keyframe_v002.png, the primary visual authority, as one silent 5-second eye-level shot. Very slight slow push-in only. Preserve HAND -> EMPTY WINDOW-SIDE SEAT -> WINDOW: the existing partial hand/forearm at frame right keeps pointing at the same empty window-side chair/desk. The seat stays empty; the full person stays offscreen. The hand mostly holds, with optional tiny natural settling that keeps its target and anatomy stable; ambient life is optional and barely perceptible. Feel gently alive within the frame, not just a slideshow zoom. Keep classroom/window geometry, furniture placement and clean simple 2D line art, black outlines, restrained flat colors, minimal shading. No finger redirection, seat change, furniture morphing, redesign, added students/characters/props/text/FX, extra fingers, pan/tilt/orbit, strong zoom or audio.
```

These are motion-focused prompts anchored to the existing image, following [Runway's image-to-video guidance](https://help.runwayml.com/hc/en-us/articles/48324313115155-Image-to-Video-Prompting-Guide). The explicit exclusions retain this project's requirements; they are not guaranteed enforcement. Runway's [Gen-4 prompting guide](https://help.runwayml.com/hc/en-us/articles/39789879462419-Gen-4-Video-Prompting-Guide) cautions that negative phrasing can behave unpredictably. Do not assume a separate negative-prompt control exists or paste the review checklist as extra prompt text.

## G. Negative constraints / failure conditions

Reject a returned clip for any of the following:

- The finger drifts, changes target, points to floor/window alone, or makes the intended seat ambiguous.
- The chair becomes occupied, furniture moves independently/morphs, furniture count changes, or the classroom/window arrangement is redesigned.
- Extra hands/fingers, arm deformation, a full pointing character, students, or other people appear.
- New props, text, bubbles, watermarks, wind, dust, streaks, or other FX appear.
- Pan, tilt, orbit, strong zoom, conspicuous parallax, reframing, cuts, or dramatic lighting changes occur.
- The simple 2D style changes to photorealism, 3D, painterly rendering, or anime styling; outlines shimmer or geometry pulses.
- Audio/dialogue is present, or the shot is merely a static-image slideshow zoom with no believable animated life.

## I. Human review checklist

Watch the full clip silently, then inspect the opening, middle, and final frames against keyframe_v002. Mark every item PASS / FAIL; approval requires explicit human review.

1. [ ] **Target-seat clarity:** HAND -> EMPTY WINDOW-SIDE SEAT -> WINDOW remains obvious at every moment; the same seat stays empty.
2. [ ] **Hand/finger stability:** approved anatomy and pointing direction hold; any settling is tiny and never changes the target.
3. [ ] **Desk/chair stability:** shape, count, placement, and furniture identity remain fixed within the scene.
4. [ ] **Window geometry stability:** frames, panes, sill, and seat/window spacing stay coherent.
5. [ ] **Classroom continuity:** approved LOC_01 window-side architecture, scale, lighting, and eye-level staging persist.
6. [ ] **Style continuity:** clean simple 2D line art, black outlines, restrained flat colors, minimal shading; no flicker or restyling.
7. [ ] **No extra characters:** only the approved partial hand/forearm is visible; the full person remains offscreen.
8. [ ] **No extra props:** no additions, disappearances, text, or effects.
9. [ ] **Push-in remains very slight:** smooth, slow forward movement; no pan, tilt, orbit, strong zoom, or disruptive parallax.
10. [ ] **Animated life:** the scene feels gently alive rather than being only uniformly scaled; natural motion remains subtle and nondistracting.

Also confirm one approximately five-second clip and silent output. Central review question: **without reading or hearing dialogue, is it immediately obvious throughout which window-side seat is indicated?**

Stop after this one manual test and its human review. This pack preparation created no media and grants no automatic production approval.
