# SHOT_009 — Keyframe v001 review

Status: REVIEW_REQUIRED
Human approval: NOT RECORDED
Candidate: `shots/SHOT_009/keyframe_v001.png`
Date: 2026-10-06
Video: NOT GENERATED

## Inspection findings

These are model visual-inspection findings, not human approval.

| Required check | Finding |
| --- | --- |
| 1. Ah Da main subject | PASS: large left/center face and upper torso dominate; no balanced two-shot. |
| 2. Approved Ah Da identity | Recognizable: light beige close-cropped hair, clear hairline, pale slim face, large ears and white shirt retained. Exaggerated mouth/brows are performance changes. Human identity confirmation remains required. |
| 3. Cartoon crying | PASS: broad stylized pale-blue ribbons, squeezed eyes and open dramatic mouth are conspicuously exaggerated rather than naturalistic. |
| 4. Strong readable tears | PASS: two large streams run down the cheeks with isolated drops. Tears remain visually distinct from skin and shirt. |
| 5. Comic/theatrical rather than tragic | The raised palm and extreme tear graphic support theatrical mock-sobbing. REVIEW_REQUIRED for the nuanced teasing/relieved intention: pinched eyebrows and wailing mouth could still read sad without delivery. No tragic lighting or realistic distress treatment. |
| 6. Gesture supports speech | PASS: one arm lifted on viewer-left, simple palm-up hand, opposite hand near chest; source-inspired theatrical appeal. Future animation should keep fingers and elbow stable. |
| 7. Ah Lim secondary reaction | PASS: smaller right-background seated figure, confused eyes, slight open mouth and sweat cue; does not compete with Ah Da. |
| 8. Classroom continuity | Same pale room, tan/gray school furniture and right-side windows in rear-facing coverage. REVIEW_REQUIRED: some empty-chair placement remains visually ambiguous relative to front-facing student orientation; exact row mapping is not verified. |
| 9. Close-up framing | PASS: Ah Da's large face, tears and upper chest dominate; lower body excluded. The background reaction does not turn it into a wide establishing shot. |
| 10. Image-to-video suitability | Candidate for limited talking/tear/arm motion; large unobstructed face is useful. Tear endpoints, raised fingers and partial lower hand require stability checks. No motion or lip-sync test was performed. |
| 11. 2D style | Foreground preserves simple black outlines and restrained cartoon colors. Background is noticeably softer than foreground; human review should decide whether this softness fits the established line-art treatment. |

## Source comparison / remaining review points

Source 5.jpg has Ah Da at left, raised arm on viewer-left and small seated Ah Lim on the right, all retained in tighter CU coverage. Source speech bubbles and orange border are excluded. The source's rough/older-looking features do not override approved youthful Ah Da identity.

The requested graphic tear streams are visibly present. Added small peach cheek blush strokes are temporary expression accents, not permanent identity marks; review their acceptability. No readable text or additional people are visible.

Ah Da turns toward screen-right, but his eyes are squeezed shut, so a precise eye-contact line cannot be certified. His body is oriented partly toward camera to expose face/tears; human review should assess whether he feels sufficiently directed toward Ah Lim.

Ah Lim is smaller than Ah Da, but not as tiny as the prompt's ideal one-fifth head-height ratio. This does not erase hierarchy; source-depth fidelity still deserves human review. Prior SHOT_007/008 files are review candidates and remain unchanged/unapproved.

## Generation provenance

Method: built-in imagegen via imagegen skill, one completed image output. Saved PNG inspected. No approved reference edited.

Input images in order:
1. `5.jpg` — source placement, gesture and tear performance.
2. `assets/characters/CHAR_02_Ah_Da/masters/face_front_neutral.png` — primary Ah Da identity.
3. `assets/characters/CHAR_02_Ah_Da/masters/face_3q_talking.png` — Ah Da rotation/identity.
4. `assets/characters/CHAR_01_Ah_Lim/masters/face_3q_talking.png` — young Ah Lim identity.
5. `assets/locations/LOC_01_classroom/masters/master_wide.png` — room and furniture family.

### Final prompt

```text
Use case: illustration-story. Generate exactly ONE 16:9 production cartoon keyframe for SHOT_009, an eye-level CLOSE-UP dominated by Ah Da's face, exaggerated streaming tears and theatrical raised-arm gesture.
INPUT REFERENCES: Image 1 = source comic panel 5.jpg, authority for character placement, raised-arm direction, streaming-tear performance and tiny background Ah Lim. Do not copy speech bubbles, lettering, orange border or source age distortions. Image 2 = APPROVED Ah Da neutral face, primary identity authority. Image 3 = APPROVED Ah Da three-quarter talking face, identity/rotation support. Image 4 = APPROVED young Ah Lim face, secondary character identity. Image 5 = approved LOC_01 classroom room/furniture palette and construction, NOT a requirement to copy its front-view camera.
COMPOSITION: source-inspired depth composition, now tighter CLOSE-UP. Ah Da occupies LEFT/CENTER FOREGROUND with head large (approximately 40–45% of frame height), upper chest/shoulders cropped by bottom edge. Include ONE raised expressive arm on viewer-left, elbow bent, hand lifted beside/slightly above shoulder as in source, palm loosely up with simple readable fingers. Other arm low, relaxed bend near chest or cropped, never a duplicate limb. A slight forward lean. Three-quarter head turned toward screen-right/back toward Ah Lim, so he is addressing his classmate rather than the viewer, while both cheeks and tear streams remain clearly readable. Do not show Ah Da's whole body; do not widen to a room establishing shot.
PERFORMANCE: Ah Da is being comically, absurdly overemotional and teasing: funny mock-sobbing, exaggerated 'at last you arrived, I've waited forever' relief and overjoyed reunion energy. NOT genuinely heartbroken or tragic. Broad open dramatic speaking/wailing mouth with upbeat, slightly raised corners, theatrical pinched/raised eyebrows, squeezed delighted overwhelmed eyes. Exactly two strong graphic PALE BLUE CARTOON TEAR RIBBONS pour from the eyes down both cheeks, like a comic flood of tears, with just a few simple falling drops. Not tiny realistic wet streaks. Keep face recognizable under expression; do not stretch jaw grotesquely. This is cartoon mock-crying with almost gloating relief, not quiet sadness or realistic grief.
IDENTITY: match Image 2 exact pale slim slightly elongated angular youthful face, prominent round ears, thin brows, simple small nose, very short LIGHT BEIGE hair cap with visible short hair and clear hairline, NOT BALD, not elderly, no wrinkles. White short-sleeved collared school shirt with left chest pocket, approved simple line-art identity. No black Ah Lim hairstyle on Ah Da.
AH LIM: a SMALL secondary reaction figure in RIGHT BACKGROUND across room, seated at his own tan student desk, youthful short black irregular fringe and white shirt; surprised/confused eyes, small partly open mouth and tiny sweat mark if needed. Looking toward Ah Da at screen-left. His head is far smaller than Ah Da's (about one-fifth the height); he must not compete with the close-up speaker. No equal-size two-shot, no second foreground face.
CLASSROOM: only enough context for same LOC_01: restrained cream rear/side wall, a few tan rectangular desks/chairs with thin gray supports and a narrow section of the canonical windows on screen-right in this rear-facing/oblique coverage from the front zone. Whiteboard and teaching area are behind camera, not visible. No new door or panels. All student desks face classroom FRONT/camera, with chair backs on their FAR side, not between the camera and desktops. Ah Lim remains seated behind his desk facing forward toward Ah Da. Keep room subdued and secondary. No unrelated equipment/props or extra students. Book from prior greeting is below close-up crop, not an added object.
STYLE: clean simple 2D cartoon black line art, restrained flat school colors, minimal shading, low-detail source-comic feeling. Tears graphic and exaggerated within this same style. No photorealism, 3D gloss, painterly or elaborate anime transformation, dramatic gloomy lighting or realistic water texture.
No text, subtitles, dialogue, speech bubbles, logos, watermark, motion streaks, frames or multiple panels. One coherent film frame only, no variants. Prioritize CU face/tear/gesture readability, comic rather than tragic tone, and canonical youthful Ah Da.
```

## Disposition

REVIEW_REQUIRED. Human approval NOT RECORDED. This is not a locked keyframe. No video generated; no SHOT_010 work. Previous shots and approved masters remain unchanged.

