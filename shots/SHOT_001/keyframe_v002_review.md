# SHOT_001 — Keyframe v002 review

status: APPROVED
human approval: EXPLICIT HUMAN APPROVAL RECORDED
keyframe lock: LOCKED
approved file: `keyframe_v002.png` (`shots/SHOT_001/keyframe_v002.png`)

Generated file: `shots/SHOT_001/keyframe_v002.png`
Dimensions: 1536 × 1024 PNG (3:2).
Inspection date: 2026-09-23.
Method: built-in image_gen, one reference-guided edit/generation; the saved production PNG was reopened and visually inspected.

## Human rejection of v001 / current authority

The human rejected `keyframe_v001.png` for framing: it reads as a medium/wide bedside group shot rather than the CU specified in both shot lists. Five visible staff, excessive bed coverage and the foreground footboard diminish Ah Lim's emotional prominence. V001 remains preserved, unmodified rejected review history and is not a locked visual reference. Its historical review's pending wording is superseded by the human rejection; that review is unchanged. The shot brief now identifies approved v002 as the locked reference and retains the rejected v001 prompt only as history.

V002 has been explicitly HUMAN-APPROVED and is LOCKED as the canonical visual starting point for SHOT_001. This approval supersedes the initial pending-review findings below. V001 remains rejected review history. No image was changed or regenerated to record this approval; no v003 or SHOT_001 video has been generated.

## Explicit human approval — 2026-09-23

The human reviewer visually reviewed `keyframe_v002.png` and APPROVED it. The corrected close-up resolves v001's framing failure.

| Human review criterion | Result |
| --- | --- |
| CLOSE-UP framing | PASS |
| Elderly Ah Lim identity | PASS |
| Critical / near-death condition readability | PASS |
| Oxygen mask and breathing tube continuity | PASS |
| Hospital context | PASS |
| Staff remain secondary context | PASS |
| Character direction | PASS |
| Emotional clarity | PASS |
| 2D style continuity | PASS |
| Suitability as image-to-video starting frame | PASS |

Accepted story read: "elderly Ah Lim is critically weak and dependent on breathing support in a hospital bed."

The human confirms that the closed/heavy eyelids read as severe exhaustion and critical weakness, not ordinary sleep. The tighter composition emphasizes extreme facial frailty, gaunt neck, oxygen mask, breathing tube and passive hospital-bed posture. Identity and emotional-read concerns from the initial inspection are resolved by this explicit human approval, not by an automated assessment.

Next stage: prepare the SHOT_001 motion/video brief in a separate task. Approval of this starting frame is not approval of a generated video; no video has been generated.

## References and hierarchy

All five canonical records were rechecked as APPROVED in the live manifest, and every image below was visually inspected.

| Reference | Authority used |
| --- | --- |
| `1.jpg` | Supine patient, central head/bed axis, flanking staff, rightward breathing support and somber hospital situation. The human-requested CU replaces the source's broad framing; source text/graphics are excluded. |
| `assets/characters/CHAR_01_Ah_Lim/elderly/hospital_portrait.png` | CHAR_01_ELDERLY_HOSPITAL_PORTRAIT: 90+ identity, gaunt aged face, sparse gray-white hair, prominent ears, wrinkles and thin neck. |
| `assets/characters/CHAR_01_Ah_Lim/elderly/bed_pose.png` | CHAR_01_ELDERLY_BED_POSE: passive supported supine posture, closed-eye direction, pale blue gown, mask, pillow and tubing. |
| `assets/locations/LOC_05_hospital/masters/master_wide.png` | LOC_05_HOSPITAL_MASTER: cream hospital/bed palette, simple head support and apparatus on viewer-right. Most room landmarks appropriately fall outside this close-up. |
| `assets/props/PROP_04_hospital_bed/master.png` | PROP_04_BED_TUBING: rounded cream bed family, white bedding and dark tube/simple apparatus continuity. |
| `assets/extras/hospital_staff/group.png` | EXTRA_HOSPITAL_STAFF_GROUP: anonymous white/pale-blue clinical clothes only; no obsolete visitors. |
| `shots/SHOT_001/keyframe_v001.png` | Edit target and established shot style/direction, explicitly not framing authority. |

Five images were supplied to image_gen: v001, elderly portrait, elderly bed pose, hospital location and canonical staff group. Source 1.jpg and standalone PROP_04 were inspected separately and their constraints described in the prompt; the bed/tubing family is also visible in the supplied approved references. No young Ah Lim or obsolete visitor image was used.

## Initial generation inspection — historical, superseded by human approval

The following five-question table and additional inspection notes preserve the original assistant assessment before human review. Any REVIEW_REQUIRED or pending-human wording in this historical section is resolved by the explicit approval above and is not the current shot status.

| Question | Finding |
| --- | --- |
| 1. Does this clearly read as a CLOSE-UP? | PASS — crown through upper chest fills the frame; the head occupies roughly half its height. Pillow and shoulders support the face. No full bed, lower body, hands or foreground footboard is visible. |
| 2. Is elderly Ah Lim unquestionably the visual subject? | PASS — his large central face and mask dominate. Staff are reduced to cropped white/blue clothing and arm fragments at the extreme sides; no complete staff faces or figures compete for attention. |
| 3. Does he read as critically weak / near death rather than merely sleeping? | REVIEW_REQUIRED — exposed gaunt cheeks, exhausted eyelids, pronounced age lines, thin neck, slack supported posture and prominent breathing support make severe frailty more legible than in v001. However, a still closed-eye image cannot guarantee the near-death reading rather than sleep/unresponsiveness. Human review must confirm this emotional distinction. No death, flatline, distress grimace, tears or emergency action is depicted. |
| 4. Are oxygen mask, tube and hospital context immediately understandable? | PASS — the mask covers nose/mouth, its connector is clear, and one dark corrugated hose curves toward viewer-right. Pillow, pale blue gown, cream head support and clinical edge fragments establish the hospital setting; a small apparatus crop remains at upper-right. |
| 5. Is the approved elderly identity preserved? | PASS for visible identity traits — receding crown, sparse gray-white side hair, gray brows, elongated gaunt face, prominent ears, age lines and thin neck remain consistent with the approved elderly portrait/bed pose. Mask occlusion limits comparison of mouth/chin details; exact identity acceptance remains with the human. No young/afterlife traits appear. |

### Additional continuity and composition inspection — historical

- **Eye direction:** eyelids remain shut/heavily lowered with narrow dark lid shapes, no widened/open-eye expression or directed gaze. This retains the approved bed-pose direction. Human review can check whether the tiny dark slits read as sufficiently closed.
- **Source staging / direction:** patient stays supine on supported pillow, facing the established frontal bed axis; hose remains viewer-right, not mirrored. Source flanking staff are represented by edge fragments with the remaining group offscreen. The source's five-person count is deliberately not made visible in this CU.
- **Staff continuity:** white scrubs at viewer-left and pale blue at viewer-right remain anonymous supporting context. No caps, stethoscopes, grief gestures or visitor/family styling. Faces are outside the crop, so facial expressions cannot be assessed.
- **LOC_05 / prop continuity:** cream rounded head support with elongated opening, pale pillow/gown and dark hose preserve the approved design family. Window, door, floor, footboard and most apparatus are cropped away, not redesigned. The visible panel behind the pillow is the head support, not a foreground footboard.
- **2D style:** PASS — simple black outlines, restrained pale colors, flat fills with light shading. No photorealism, glossy 3D, painterly/anime redesign, text, logos or added medical equipment.
- **Future image-to-video suitability:** the face/mask/pillow/tube silhouettes are clearly separated and the partial staff remain peripheral. Static composition is suitable for human review as a future motion starting frame; motion stability has not been tested and video is not authorized by this task.
- **Remaining review focus:** confirm critical weakness rather than ordinary sleep; confirm exact elderly likeness under mask occlusion. No further generation was attempted.

## Integrity / scope

- V002 SHA-256: `7b49da765e3a3b42a026c25c771e77fa0419384e98cb39e6b230766173885de3`.
- V001 preserved SHA-256: `809d8fa4c4ba24155dfd4654afc10d66479ec85f6ce08493e7777fc47ff5f5c5`.
- The generation task created v002 PNG and this review and updated PROJECT_STATE.md. This approval-only task updates this review, `shot_001_brief.md` and PROJECT_STATE.md; it does not alter any image.
- No manifest status changes, approved-master edits, shot-list/dialogue changes, other-shot work, v003 or video.
- Explicit human approval is now recorded above. V002 is APPROVED and LOCKED; stop after recording approval, before motion/video brief preparation or generation.

## Exact generation prompt

```text
Use case: identity-preserve.
Asset type: ONE corrected 2D animated-film keyframe for SHOT_001, keyframe_v002. Single landscape 3:2 frame. This is a close-up composition correction to image 1, NOT a new character or environment design. Generate only one image.

INPUT ROLES, IN ORDER:
1. keyframe_v001.png — edit target / continuity basis. Preserve its elderly patient, hospital design, costume colors, mask/tube, frontal bed axis and simple 2D visual style. REJECT its wide bedside group framing. Move the camera much closer to the patient's head and upper chest. Do not retain the whole bed, footboard or complete staff figures.
2. hospital_portrait.png — APPROVED primary elderly Ah Lim identity authority. Preserve the exact narrow gaunt aged face, prominent ears, receding mostly bare crown, sparse gray-white hair, gray eyebrows, wrinkle design and thin neck. He is over 90, not the young/afterlife version. Do not copy this portrait's upright pose or partly open eyes.
3. bed_pose.png — APPROVED supine hospital posture, CLOSED eyes, pale blue gown, pillow, mask and dark corrugated hose authority. Maintain these features, adapting only to the frontal source axis and much tighter camera. Do not copy its diagonal whole-bed framing or black vignette.
4. LOC_05 hospital master_wide.png — APPROVED hospital architecture/palette and right-head-side simple apparatus continuity only, not wide composition. In a real close-up most of this room is offscreen.
5. hospital_staff/group.png — APPROVED anonymous pale-blue/white clinical-clothing language. Staff are peripheral context only, mostly OFFSCREEN. Do not copy the asset-sheet arrangement or dark backdrop.

SOURCE CONTINUITY:
The separately inspected original 1.jpg establishes the patient lying on his back, head centered at the bed's head end, medical breathing support curving toward viewer-right, and quiet staff flanking him. Preserve these spatial relationships and somber illness beat WITHOUT copying its broad composition or any text. The separately inspected approved PROP_04_BED_TUBING is the same rounded cream bed/pale pillow/dark hose/simple right-side apparatus family shown in the supplied approved bed pose and hospital. Use these identities, not new equipment. Source staff positions continue beyond the crop; do not try to fit all five into this close-up.

PRIMARY CORRECTION — TRUE CLOSE-UP:
The frame is dominated by elderly Ah Lim's HEAD, FACE, OXYGEN MASK, PILLOW, THIN NECK, SHOULDERS and UPPER CHEST. His head and face are near the visual center and immediately, unquestionably the main subject. His head from crown to chin occupies roughly half the frame height, not a tiny face inside a room. Frame from a small amount of pillow/head support above his crown down to his frail upper chest. Cut off the lower torso, hands, lower blanket and the entire foot end. The pillow fills much of the background surrounding the face. At most a narrow sliver of the existing cream head support can remain behind the pillow.
Patient remains reclined/supine with shallow raised head support, not seated upright. Keep the established frontal, eye-level cinematic view; no overhead, profile or dramatic tilt.
Show the mask clearly over nose and mouth, with ONE legible corrugated breathing hose curving naturally from the mask toward VIEWER-RIGHT and leaving the crop toward the existing apparatus. A tiny cropped edge of the existing bedside apparatus may remain at the far right only if there is room; never widen to include a monitor.
At the extreme edges only, allow small cropped white/pale-blue staff shoulders, torso or arm fragments oriented inward toward him. No complete staff faces or figures are needed. They must not surround him as five visible people or compete with the face.
NO foreground footboard, full bed, full hands, legs, floor, full window, full door or broad room view. This is a cinematic patient close-up, not a bedside group shot and not an asset sheet.

CRITICAL-CONDITION / IDENTITY LOCK:
Preserve his approved elderly identity precisely: 90+ frailty, sparse receding gray-white hair, gaunt wrinkled face, prominent ears, thin neck, pale blue hospital gown, and eyes CLOSED as in the approved bed pose and v001. He is profoundly weak, exhausted and passive, with slack unsupported-looking facial muscles and shoulders resting into the pillow, not a comfortable nap or contented sleep. Let the existing sunken cheeks, exhausted eyelids, thin neck and breathing support read clearly at close scale. No serene smile, rounded healthy cheeks or relaxed happy expression. Convey severity through the approved frail anatomy and proximity, not extra invented wrinkles, changed face proportions or melodrama.
Do not show death, a flatline, suffering grimace, tears, blood, emergency action, open eyes, or new medical devices. No identity drift or youthful traits.

STYLE / INVARIANTS:
Keep clean simple 2D cartoon black outlines, restrained flat cream/pale-blue/gray colors, minimal shading, low-detail source-comic style and subdued clinical atmosphere. Coherent line weight and scale. No photorealism, glossy 3D, painterly treatment, elaborate anime, heavy textures, dramatic lighting, depth-of-field blur or dark vignette.
Anonymous canonical staff only, not visitors; no caps, stethoscopes, named roles or dramatic grief.
No readable text, numbers, dialogue bubbles, titles, logos, watermarks, extra characters, new props or alternate versions.
Only the tighter framing and clearer reading of existing severe frailty are intended changes. Produce ONE corrected close-up image.
```

