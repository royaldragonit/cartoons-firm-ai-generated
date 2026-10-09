# SHOT_002 — Keyframe v001 review

status: APPROVED
human approval: EXPLICIT HUMAN APPROVAL RECORDED
keyframe lock: LOCKED
approved file: `keyframe_v001.png` (`shots/SHOT_002/keyframe_v001.png`)

Generated file: `shots/SHOT_002/keyframe_v001.png`
Dimensions: 1536 × 1024 PNG (3:2).
Source panel: `1.jpg`
Location: LOC_05.
Shot type: MEDIUM, eye level.
Planned duration: approximately 6.4 seconds.
Camera movement: very slight push-in.
SHA-256: `618fc02b672648484094f6d0c725e7a92ce5bd7a8266b8c25c333d79765b67a7`.
Method: one built-in image_gen generation with five reference images. The PNG was copied to the production path and visually reopened.

## SHOT_002 resolution before generation

The live shot list and JSON specify SHOT_002 as a MEDIUM eye-level shot from 1.jpg, not the CLOSE-UP used for approved SHOT_001 v002. The shot's exact dialogue remains:

> Đành chịu thôi, có lẽ cũng sắp đến lúc ông ấy phải ra đi rồi...

No dialogue, text or speech bubble is rendered in this keyframe. The intended editorial function is a wider bedside reveal: elderly Ah Lim remains in bed while the anonymous hospital staff, hospital room and right-side support become legible.

SHOT_001 keyframe_v002 remains HUMAN-APPROVED and LOCKED. This SHOT_002 frame continues its identity and medical continuity but correctly uses the live medium-shot specification. SHOT_001 keyframe_v001 remains rejected framing history and is unchanged.

## Explicit human approval

The human reviewer visually reviewed `shots/SHOT_002/keyframe_v001.png` and APPROVED it. The keyframe is now LOCKED as the canonical visual reference for SHOT_002.

| Human review criterion | Result |
| --- | --- |
| Continuity from SHOT_001 | PASS |
| Elderly Ah Lim identity | PASS |
| Medium bedside framing | PASS |
| Source staging relationship | PASS |
| Hospital staff placement | PASS |
| Bed/tubing continuity | PASS |
| LOC_05 continuity | PASS |
| Character direction | PASS |
| Emotional clarity | PASS |
| 2D style continuity | PASS |
| Suitability for image-to-video | PASS |

Accepted editorial progression: SHOT_001 is the close-up of critically weak elderly Ah Lim; SHOT_002 is the medium bedside reveal with Ah Lim centered, three anonymous staff on viewer-left, two anonymous staff on viewer-right, and right-side medical support visible.

Non-blocking animation note: the overlapping forearm/hand area among the viewer-left staff is acceptable in the still. Future animation must keep staff motion extremely restrained to reduce anatomy and morphing instability.

Next stage: prepare the SHOT_002 motion/video brief. No SHOT_002 video has been generated.

## Reference use

- `1.jpg`: source staging, five-person bedside arrangement, right-side equipment, patient direction and emotional context; page graphics excluded.
- `shots/SHOT_001/keyframe_v002.png`: approved elderly identity, mask/tube, gown, pillow and 2D continuity.
- `assets/locations/LOC_05_hospital/masters/master_wide.png`: approved LOC_05 environment.
- `assets/characters/CHAR_01_Ah_Lim/elderly/bed_pose.png`: approved elderly bed posture and medical-support continuity.
- `assets/extras/hospital_staff/group.png`: approved anonymous hospital staff; obsolete visitors excluded.
- `assets/props/PROP_04_hospital_bed/master.png`: inspected approved bed/tubing continuity reference; no new equipment added.

## Review checks

These are provisional visual checks only. They do not constitute human approval.

| Check | Finding |
| --- | --- |
| 1. Continuity from SHOT_001 | PASS — elderly Ah Lim, pale blue gown, pillow, mask, rightward tube and simple 2D hospital language continue from the approved v002. The camera intentionally opens to the next shot's medium scale. |
| 2. Elderly Ah Lim identity | PASS — sparse receding gray-white hair, gaunt aged face, prominent ears, wrinkles, thin neck and 90+ hospital appearance remain recognizable. No young/afterlife traits or school uniform appear. |
| 3. Source-panel staging fidelity | PASS — patient is centered in bed, staff flank him on both sides, and the right-side support/equipment relationship is preserved without source-page graphics. The source's three-left/two-right staff structure is represented. |
| 4. Shot-type / framing fidelity | PASS — the frame reads as a medium eye-level bedside group shot, wider than v002 but not an extreme-wide room view. Ah Lim remains large enough to read; the bed footboard does not dominate. |
| 5. Hospital staff placement | PASS — three anonymous staff appear on viewer-left and two on viewer-right, facing inward/down with restrained professional concern. They remain supporting context rather than named characters or visitors. |
| 6. Bed/tubing continuity | PASS — rounded cream head/bed structure, pale pillow and bedding, oxygen mask and one dark corrugated tube remain in the approved PROP_04/bed-pose family. The tube is attached and exits toward viewer-right. |
| 7. LOC_05 continuity | PASS — cream walls, left window edge, right door edge, central bed and right-side monitor/support apparatus match the approved hospital master. No unsupported room redesign is visible. |
| 8. Character direction | PASS — Ah Lim remains supine on the frontal bed axis; staff look toward him; the medical tube direction is not mirrored. |
| 9. Emotional clarity | PASS provisionally — the gaunt elderly face, closed/heavy eyes, oxygen support and quiet bedside attention communicate critical weakness and near-death context. Human review should confirm the intended somber read without dialogue. |
| 10. Suitability for image-to-video | REVIEW_REQUIRED — the medium composition has clear patient/staff/bed/tube separations and a stable axis for a restrained push-in, but motion stability has not been tested. |
| 11. 2D style continuity | PASS — clean black outlines, restrained flat cream/pale-blue colors, minimal shading and low-detail source-comic treatment match the approved production language. |

## Human review focus

1. Does the frame immediately read as SHOT_002's medium bedside reveal rather than SHOT_001's close-up?
2. Is elderly Ah Lim still the primary subject and unmistakably the approved 90+ variant?
3. Are all five staff secondary, anonymous and source-directionally placed?
4. Are the mask, rightward tube, bed and monitor/support relationship stable and readable?
5. Does the somber dialogue beat remain visually clear without adding text?

## Integrity and scope

- Status is APPROVED; explicit human approval is recorded above and the keyframe is LOCKED.
- SHOT_001 keyframe_v002 remains HUMAN-APPROVED, LOCKED and unchanged.
- SHOT_001 keyframe_v001 remains rejected review history and unchanged.
- No video, audio, SHOT_002 keyframe_v002, SHOT_003 work, approved-master edit or preflight modification was performed.

## Exact generation prompt

```text
Use case: illustration-story.
Asset type: ONE production blocking/keyframe reference for animated-film SHOT_002. Generate exactly one finished landscape 3:2 image, not a sheet, collage, comparison, or alternate take.

SHOT SPECIFICATION:
SHOT_002, narrative scene 1, source panel 1.jpg, location LOC_05 hospital room, eye-level MEDIUM SHOT, approximately 6.4 seconds for later video planning, very slight slow push-in. Visual action: elderly patient lies in bed while anonymous hospital staff surround him. Emotion: somber, quiet, critical illness. This is the next editorial beat after the approved SHOT_001 close-up, but it must follow SHOT_002's medium-shot framing rather than repeating the close-up.

REFERENCE ROLES, IN PROVIDED ORDER:
1) 1.jpg — authoritative source-specific staging: central supine patient, five surrounding silhouettes, bed relationship, apparatus on viewer-right, serious hospital situation. Ignore its title, speech bubbles, all readable text, border, credits and watermark; do not render any of them.
2) shots/SHOT_001/keyframe_v002.png — HUMAN-APPROVED and LOCKED identity/continuity reference. Preserve the exact elderly Ah Lim face, age, mask placement, rightward tube direction, pale blue gown, pillow and clean 2D style. It governs Ah Lim identity and medical continuity, not this shot's framing.
3) LOC_05 hospital master_wide.png — APPROVED hospital-room geometry, cream walls, central bed axis, right-side monitor/support apparatus, restrained clinical palette.
4) CHAR_01 elderly bed_pose.png — APPROVED frail supine pose, closed/heavy eyelids, pale blue gown, pillow, breathing mask and tube continuity. Do not copy its diagonal asset-sheet camera or dark vignette.
5) EXTRA_HOSPITAL_STAFF_GROUP group.png — APPROVED anonymous nursing/caregiver identity and white/pale-blue clinical clothing. Reuse this simple staff design language for the five source-supported anonymous bedside silhouettes. They are staff, not family or visitors. Do not copy the dark vignette or asset-sheet lineup as a background.

SHOT_001 CONTINUITY:
SHOT_001 keyframe_v002 is already approved and locked. SHOT_002 is the wider following beat: the viewer should now see the patient in context with the bedside staff and right-side support. Keep Ah Lim recognizable and central, but do not simply crop or duplicate the approved close-up. Do not modify or reference SHOT_001's rejected v001 as authority; its broad composition was inspected only as history and is not being reused as the SHOT_002 design.

COMPOSITION:
Create a coherent eye-level medium bedside group shot, wider than SHOT_001 v002 but clearly not an extreme wide room view. Ah Lim remains the primary visual subject, centered on the hospital bed at a readable medium scale. Show his head, pillow, oxygen mask, thin neck, shoulders and upper torso/blanket; enough of the bed to make the lying posture clear, but do not let a large foreground footboard dominate. Keep the head end centered and the compact monitor/medical support at viewer-right. The single dark corrugated breathing tube is visibly attached to the mask and curves toward viewer-right without crossing through bodies.

Use the source panel's staff relationship: three anonymous staff silhouettes on viewer-left and two on viewer-right, all looking inward/down toward Ah Lim with quiet professional concern. Show them as medium-shot supporting figures cropped naturally by the frame or by the bedside composition; their faces/upper bodies may be visible, but no staff member should dominate Ah Lim. Reuse only the approved generic clinical staff language. Do not turn them into named characters, family, visitors or a dramatic grieving crowd. Keep the patient, staff, bed and right-side apparatus spatially coherent and not mirrored.

CRITICAL CONDITION / IDENTITY:
Ah Lim is the approved elderly 90+ hospital variant, not young/afterlife Ah Lim. Preserve sparse receding gray-white hair, gaunt wrinkled face, prominent ears, thin neck, pale blue hospital gown and passive supported posture. Keep eyes closed/heavy as approved; at medium scale they must read as severe exhaustion and critical weakness, not ordinary healthy sleep. Oxygen mask remains clearly readable. The intended story read is: elderly Ah Lim is critically weak, near death, and dependent on breathing support. Convey this through approved frailty and medical support, not melodrama.
Do not show death, flatline, blood, tears, emergency treatment, open alert eyes, speaking, smiling, dramatic grimace, new medical devices, or sudden movement. No age regression or face morphing.

ENVIRONMENT / PROP:
Preserve LOC_05's simple cream hospital room, frontal bed axis, restrained clinical light, partial window/door only if they naturally enter this medium framing, and right-side support apparatus. Preserve PROP_04 bed/tubing family: rounded cream bed/headboard, pale pillow and bedding, gray support structure and one attached dark breathing tube. Keep the bed recognizable without an oversized footboard. No other patients, visitors, extra furniture, text or unsupported equipment.

STYLE:
Clean simple 2D cartoon line art, black outlines, restrained flat cream/pale-blue/gray colors, minimal shading, low-detail source-comic feeling. Match the approved production references. No photorealism, glossy 3D, painterly rendering, elaborate anime redesign, heavy gradients, dark vignette, dramatic lens blur, text, speech bubbles, logos or watermark.

OUTPUT:
One SHOT_002 review blocking/keyframe only. Preserve source direction and the medium-shot read. Do not generate video, keyframe_v002, another shot, alternate versions, or any readable dialogue/narration in the image.
```

