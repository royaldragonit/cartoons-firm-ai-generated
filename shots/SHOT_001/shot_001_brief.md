# SHOT_001 — Hospital opening blocking/keyframe brief

Status: APPROVED — explicit HUMAN APPROVAL recorded; keyframe_v002 is LOCKED.

Approved locked shot reference: `shots/SHOT_001/keyframe_v002.png` (1536 × 1024 PNG). Narrative scene 1; source `1.jpg`; location LOC_05. Preflight classification remains READY_WITH_BLOCKING_REFERENCE; the required blocking reference is now human-approved. See `keyframe_v002_review.md` for the explicit approval and accepted checks. `keyframe_v001.png` remains unmodified rejected review history for medium/wide framing, not a production reference.

The human accepts the close-up, elderly identity, critical-condition read, breathing support, hospital context, secondary staff, character direction, emotional clarity, 2D style and suitability as an image-to-video starting frame. Closed/heavy eyelids read as severe exhaustion rather than ordinary sleep. Next stage: prepare SHOT_001 motion/video brief in a separate task. SHOT_001 video has NOT been generated.

## Story and camera

Elderly Ah Lim, over 90, lies critically weak in a hospital bed, surrounded by anonymous hospital staff. His frail face, breathing support and quiet bedside attention establish the opening's somber near-death situation. He must not read as young/afterlife Ah Lim or a healthy sleeping patient.

The shot list specifies CU, eye level, patient lying in bed, somber emotion, and a provisional 6.4-second duration with very slight push-in for eventual video. Approved v002 is a true close-up: elderly Ah Lim's head, face, oxygen mask, pillow, thin neck, shoulders and upper chest dominate. Staff are cropped edge fragments; the full bed and foreground footboard are excluded. This locked framing supersedes v001's rejected close-to-medium interpretation without rewriting the shot list. No motion/video brief or video is produced in this approval task.

Direction lock: Ah Lim remains supine with supported head near visual center; the breathing tube curves toward viewer-right and the upper chest occupies the lower frame. Canonical staff remain secondary edge context. Source 1.jpg's three left and two right staff positions extend beyond the approved CU crop; do not widen the frame to show all five. Preserve v002's exact patient/mask/tube/pillow relationships and approved elderly identity.

## Canonical reference hierarchy

| Reference | Role |
| --- | --- |
| `1.jpg` | Story composition, staff placement, patient direction, bed relationship and emotion; exclude title, bubbles, credits and watermark. |
| `assets/characters/CHAR_01_Ah_Lim/elderly/hospital_portrait.png` | APPROVED CHAR_01_ELDERLY_HOSPITAL_PORTRAIT: face, age, hair, wrinkles, frailty. |
| `assets/characters/CHAR_01_Ah_Lim/elderly/bed_pose.png` | APPROVED CHAR_01_ELDERLY_BED_POSE: supine pose, gown, hands, blanket, breathing mask; adapt its camera to the source axis. |
| `assets/locations/LOC_05_hospital/masters/master_wide.png` | APPROVED LOC_05_HOSPITAL_MASTER: architecture, palette, room/bed/apparatus relationship. |
| `assets/props/PROP_04_hospital_bed/master.png` | APPROVED PROP_04_BED_TUBING: rounded bed family, bedding, simple apparatus and dark tubing. |
| `assets/extras/hospital_staff/group.png` | APPROVED EXTRA_HOSPITAL_STAFF_GROUP: anonymous pale-uniform nursing/caregiver designs, restrained serious demeanor. |

All five asset approvals were verified in the live manifest and the images visually inspected. The obsolete visitor group is excluded. Older family/visitors wording in the shot list and prop review is stale; current manifest, preflight and the human's instructions govern. No young Ah Lim references are used.

## Dialogue and visual exclusions

Existing SHOT_001 dialogue remains unchanged: “Bác Lim đã hơn 90 tuổi rồi, ông ấy đang ngày càng yếu dần đi...” Speaker attribution remains UNKNOWN; no new identity is assigned. Dialogue is contextual only and is not rendered into this image or synthesized as audio.

Maintain clean 2D cartoon outlines, restrained flat colors, minimal shading and simple geometry. Exclude invented text, extra patients, visitor/family interpretation, named medical roles, unnecessary equipment, detailed procedures, FX and source-page graphics. The result must be a coherent dramatic scene rather than an isolated asset sheet.

## Historical v001 generation record / exact prompt — rejected framing

The following prompt is retained only as v001 generation history, not as an instruction for the locked shot. V002's generation prompt and human approval are recorded in `keyframe_v002_review.md`.

Method: built-in image_gen, one reference-guided generation. The tool accepts at most five image inputs: source, elderly portrait, elderly bed pose, hospital location, and staff group. The standalone PROP_04 image was inspected separately; its bed/tubing identity is also visible in the supplied approved bed-pose and hospital masters. A six-reference request was rejected before generation; no image was produced by that validation error. Only keyframe_v001 is requested; human review precedes any revision or video.

```text
Use case: illustration-story.
Asset type: ONE production keyframe / blocking reference for animated-film SHOT_001, hospital opening. Generate exactly one finished landscape 3:2 image, not a sheet, collage, comparison, or multi-panel comic.

REFERENCE ROLES IN PROVIDED ORDER:
1) 1.jpg: authoritative narrative composition, patient direction, staff distribution, bed relationship, and somber emotional beat. Ignore all its title, dialogue bubbles, border, credits, signatures and watermarks.
2) hospital_portrait.png: APPROVED identity authority for Ah Lim at age over 90. Preserve the thin gaunt face, aged chin and cheeks, prominent ears, deep simple wrinkle lines, sparse white/gray side hair and receding crown, gray eyebrows, extremely heavy eyelids, pale aged skin, thin neck. Absolutely no young Ah Lim face, pointed black fringe or school uniform.
3) bed_pose.png: APPROVED frail patient pose and hospital clothing: lying supine, slightly raised pillow/head support, pale blue short-sleeved hospital gown, pale blanket, both hands weakly resting near torso, simple breathing mask and dark corrugated tube. Identity/pose authority only: do not copy its diagonal asset-sheet camera or dark vignette.
4) LOC_05 hospital master_wide.png: APPROVED room identity: plain pale cream walls, gray floor/baseboard, simple left window and right door when within framing, one hospital bed, compact apparatus at the RIGHT head end. Keep restrained clinical light; adapt camera framing but retain spatial relationships.
5) hospital_staff/group.png: APPROVED anonymous nursing/caregiver identity and style: simple pale blue or white scrubs, practical short hair or tied-back dark hair, minimally detailed serious faces, no caps, stethoscopes, ornate coats, logos, badges, ranks. Four reusable designs are shown; the SOURCE staging calls for FIVE anonymous supporting silhouettes, three on the left and two on the right. Use the same generic uniform/design language for all five. They are staff, not visiting family.

PROP CONTINUITY: The separately inspected approved PROP_04 bed/tubing master is represented by the same bed family visible in images 3 and 4: rounded off-white panels with elongated cutouts, pale bedding, gray supports, one dark breathing tube and compact apparatus. Retain these identities while reorienting the bed to source panel 1's frontal axis.

SCENE / COMPOSITION:
A coherent dramatic hospital opening, frontal bedside view along the bed axis. Tight close-to-medium bedside composition consistent with the planned eye-level close-up: elderly Ah Lim's face, pillow and frail upper body are the visual center and large enough to read his approved identity. The bed head is at upper center, blanket extends toward lower foreground; not sideways, not mirrored. Keep five quiet staff in source positions: three distributed on viewer-left and two on viewer-right; crop their lower bodies and near shoulders naturally at the picture edges. Some staff may be partly occluded as in the source. They look inward/down toward the patient, framing him without obscuring his face or mask. Do not line them up facing camera like an asset sheet. Compact monitor and breathing apparatus sit at upper-right head side; the single dark tube curves visibly from the patient's breathing mask toward this right-side apparatus, with clear attachment and no tube intersections through bodies. Show only the needed room background. Monitor may contain a simple non-lexical muted waveform as in the approved location; no readable labels or numbers and no flatline declaration.

EMOTION / POSE:
Ah Lim is critically weak and near death, not healthy or peacefully napping: gaunt age structure, drained face, heavy almost-closed exhausted eyes, passive frail hands, no smile, no active gesture. He lies on his back supported by the pillow. Staff express restrained professional concern, quiet and serious rather than melodramatic grieving. No resuscitation, gore, violence, or new medical procedures. The face/mask/bed/staff relationship must communicate the grave situation without dialogue.

STYLE:
Match the approved references' clean simple 2D cartoon line art, black outlines, restrained flat pale blue/cream/gray colors, minimal shading and low-detail source-comic feeling. Consistent perspective, scale and line weight across characters, bed and room. Keep age lines but no photorealistic skin. No glossy 3D, painterly rendering, elaborate anime redesign, heavy dramatic gradients, dark cutout vignette, cinematic lens blur, or excessive medical texture.

OUTPUT CONSTRAINTS:
Exactly one camera frame and one patient with the five source-supported anonymous staff, one bed, and the established simple apparatus. No obsolete visitor-group design, family styling, added relatives, other patients, decorative objects, text, title, dialogue, speech bubbles, watermark, logos or motion FX. No comparison boards, labels, alternate takes or new keyframes. Leave clear silhouettes suitable for later image-to-video review. Produce only this SHOT_001 keyframe.
```
