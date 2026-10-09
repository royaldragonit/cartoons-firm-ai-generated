# SHOT_008 — Keyframe v001 review

Status: REVIEW_REQUIRED
Human approval: NOT RECORDED
Candidate: `shots/SHOT_008/keyframe_v001.png`
Date: 2026-10-05
Video: NOT GENERATED

## Scope

One review keyframe generated. The user-directed reverse angle is intentionally different from source 4.jpg's foreground Ah Lim view and SHOT_007 v003. Source 4.jpg remains authority for the confused recognition relationship, not a requirement to repeat its camera.

SHOT_007 v003, SHOT_006 v001 and SHOT_004 v005 were inspected as unapproved continuity candidates. No SHOT_005 file was available. Approved masters remain identity/architecture authority. Previous shots, asset masters, manifest and preflight files were not edited.

## Visual review

These are model inspection findings, not human approval.

| Check | Finding |
| --- | --- |
| 1. Reverse-angle clarity | PASS: Ah Da's cropped head/shoulder is now left foreground; Ah Lim is the clearly visible medium subject. The view looks toward the rear, not toward the front board as in SHOT_007. |
| 2. Ah Lim identity | PASS on inspection: youthful slim face, short black irregular fringe, simple nose/ears, white shirt and chest pocket remain recognizable. No elderly traits. Expression intentionally changes from neutral masters. |
| 3. Ah Da identity | REVIEW_REQUIRED for full confirmation: beige close-cropped hair, pale skin, ear and white shirt match visible identity cues, but most of his face is intentionally hidden by reverse-angle staging. |
| 4. Ah Lim as speaker | PASS: unobstructed open mouth, confused brows/eyes and sweat mark make him the emotional focus. He reads as hesitantly questioning, not shouting. |
| 5. Ah Da as listener | PASS: back/partial side of head directs attention toward Ah Lim; no visible speaking mouth or gesture competes. |
| 6. Connected eyelines | PASS on visible cues: Ah Lim's pupils look screen-left toward Ah Da, whose head turns inward toward him. Ah Da's exact eye direction is obscured and must be inferred from head orientation. |
| 7. Medium framing | PASS: Ah Lim is visible from head through upper torso to desk/waist level, with both forearms and hands. Not a symmetric two-shot. |
| 8. Classroom continuity | PASS for visible architecture: right-side windows in reverse view, cream rear wall, tan desks and gray supports. Board is behind camera and absent; no door added. Exact row-to-row spatial correspondence to SHOT_007 needs editorial human review. |
| 9. Long dialogue animation suitability | Suitable starting candidate: stable unobstructed mouth/face and simple desk-supported hands. Motion stability and actual duration remain untested; no animation was produced. |
| 10. 2D style continuity | PASS: simple black outlines, restrained school palette, low detail and light shading; no photorealistic, glossy 3D or elaborate anime treatment. |

## Remaining human-review notes

- Ah Da's foreground shoulder occupies roughly the left third at the bottom, larger than the prompt's preferred narrow edge allowance. His head is cropped and Ah Lim still carries the visible expression and speaking focus; judge whether the foreground weight is acceptable.
- The medium reverse angle visually compresses the distance compared with SHOT_007's wide depth reveal. Check the cut for consistent seating distance; this review does not certify an exact reconstructed room model.
- Ah Lim's brows read worried/confused rather than the extreme wake-up shock of SHOT_004, appropriate to hesitant dialogue but subject to human emotional review.
- No dialogue, text, speech bubble, added character or motion effect is visible.
- No automatic approval. Do not treat this as a locked reference yet.

## Generation provenance

Method: built-in imagegen, one completed image output. An initial invocation exceeded the tool's five-reference limit and was rejected before generation; the corrected invocation used five inspected references and produced the single candidate.

Input order:
1. `shots/SHOT_007/keyframe_v003.png` — preceding staging/continuity, camera explicitly reversed.
2. `assets/characters/CHAR_01_Ah_Lim/masters/face_front_neutral.png` — young Ah Lim identity authority.
3. `assets/characters/CHAR_02_Ah_Da/masters/full_body_3q.png` — Ah Da identity/outfit.
4. `assets/locations/LOC_01_classroom/masters/master_wide.png` — canonical architecture/palette.
5. `4.jpg` — source relationship and emotional context; no dialogue rendered.

### Final prompt

```text
Use case: illustration-story. Generate ONE 16:9 production review keyframe for SHOT_008, a MEDIUM reverse-angle dialogue shot in this simple 2D cartoon classroom.
REFERENCE ROLES: Image 1 is previous shot SHOT_007: use identities, furniture, palette and room relationships, but DO NOT COPY ITS CAMERA OR COMPOSITION. Image 2 is authoritative young Ah Lim front face identity. Image 3 is approved Ah Da identity/outfit. Image 4 is approved classroom geometry/palette viewed toward the FRONT: this shot looks in the OPPOSITE direction toward the REAR. Image 5 is source 4.jpg: use confused/sweaty Ah Lim and reunion relationship, not its camera or speech bubbles. Preserve the wooden desk/chair design visible in Images 1 and 4.
REQUIRED NEW COMPOSITION: camera at seated eye level near Ah Da at the FRONT teaching area, looking BACK into the student seating area, over a small cropped portion of Ah Da's shoulder. Ah Da is only a partial left-foreground edge frame: back/three-quarter back of very short light-beige-haired head, prominent ear and white-shirt shoulder, cropped by LEFT EDGE, occupying at most 15–20 percent of image width. His head points screen-right toward Ah Lim, listening; do not show a large dominant face. Young BLACK-haired Ah Lim is the clear primary subject at center-right, completely visible head and upper body down to waist/desk edge, MEDIUM framing, seated naturally behind his wooden school desk, facing toward the classroom front/camera and turned slightly screen-left to look at Ah Da. Ah Lim's face and mouth must be easy to animate and unobstructed. Do not put the characters side-by-side or equal size. There remains believable classroom distance/aisle between them; do not move them to a shared table. This is reverse coverage of the same conversation, NOT a mirrored copy of image 1.
AH LIM: match exact approved youthful face proportions, narrow chin, short black hair and irregular fringe, simple ears/nose, pale skin, white short-sleeve collared shirt with left chest pocket. Alert confused eyes with pupils clearly looking to Ah Da at screen-left, raised uncertain brows, one small cheek sweat drop, mouth moderately open in hesitant speech (not laughing, not screaming), mildly tense shoulders. Emotion: startled, overwhelmed, asking where he is and whether this is his old classmate. Simple two hands resting/braced on own desk, no gesture, normal fingers. No elderly traits. Preserve restrained source-comic identity, not cute redesign.
AH DA: same young adult as approved beige-haired reference, visible short hair not bald, pale skin, rounded ear, white school shirt. Calm attentive listening posture turned toward Ah Lim; mouth hidden or closed. His book/crossed legs remain below the crop, don't introduce new objects or gestures.
ROOM: reverse-view LOC_01. Simple pale rear wall, a few orderly tan wooden desks/chairs with gray thin supports, all student chairs BEHIND their desks as seen from front camera, facing toward camera/front. Windows are on SCREEN-RIGHT in this reversed camera view because they were screen-left when facing the front board. Match existing window framing, neutral daylight, pale sky and restrained greenery. Whiteboard and front teaching area are BEHIND CAMERA and NOT VISIBLE. No board-like rear panel, no background door, no rearranged classroom. Background subdued and simple, no decoration.
STYLE: clean black outlines, restrained flat colors, minimal shading, low-detail hand-drawn 2D comic feeling. No photorealism, 3D, painterly or elaborate anime style. No shallow-focus photographic blur.
No text, speech bubbles, subtitles, writing, FX, extra students, duplicate characters, props, diagrams, asset-sheet layout. Single coherent cinematic frame only. Make Ah Lim unequivocally the speaking focus and Ah Da the secondary foreground listener.
```

## Disposition

REVIEW_REQUIRED. Human approval NOT RECORDED. No video generated; no SHOT_009 work.

