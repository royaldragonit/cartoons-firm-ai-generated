# SHOT_008 — Keyframe v002 review

Status: REVIEW_REQUIRED
Human approval: NOT RECORDED
Candidate: `shots/SHOT_008/keyframe_v002.png`
Date: 2026-10-06
Video: NOT GENERATED

## Human correction

V001 is REJECTED: the correct reverse-angle idea became too close and intimate, with oversized foreground Ah Da and medium-close Ah Lim. Its original PNG/review are preserved; the current human rejection supersedes earlier framing PASS statements.

V002 is one generated correction candidate. The goal is SHOT_007's spacious across-room depth with the viewing direction reversed, not a close conversation.

## Inspection of saved candidate

| Check | Finding |
| --- | --- |
| Wider camera / room depth | PASS relative to v001: multiple rows, open aisle and substantial classroom area now separate listener and speaker. Not a medium-close composition. |
| Scale match to SHOT_007 | REVIEW_REQUIRED: depth is much closer to the intended across-room relationship; Ah Lim's head is still somewhat larger than distant Ah Da's in SHOT_007. Exact scale/edit matching is not certified. |
| Foreground Ah Da | PASS for reduced dominance: heavily cropped along the left edge. Head extends about 9% of frame width; shoulder widens to about 18% at the bottom, above the prompt's 10–12% preference but much smaller than v001. |
| Distant Ah Lim / speaker | PASS: center-right beyond several desk intervals; only complete visible face, mouth open, confused brows and sweat cue. No portrait-scale dominance. |
| Reverse-angle clarity | PASS: listener now foreground, speaker deeper in room; board behind camera, window wall screen-right, plain rear wall ahead. |
| Ah Lim identity | Recognizable young black-haired canonical identity and white school shirt; no elderly features. Fine facial consistency needs human inspection at the smaller scale. |
| Ah Da identity | Visible beige short hair, pale ear/skin and white shoulder are consistent. Face is mostly hidden, so full face identity cannot be verified from this angle. |
| Eyelines / emotion | Ah Lim looks screen-left toward Ah Da with a hesitant, worried/confused speaking expression; Ah Da faces inward. Listener's exact eye direction is occluded. |
| Desk/chair geometry | REVIEW_REQUIRED: multiple empty-chair backs appear on the camera/near side of their desks, while Ah Lim faces the front/camera from the far side of his own desk. This can make the empty rows read as facing the wrong way in a reverse view. |
| Room identity | Cream walls, right-side canonical window family, tan furniture and thin gray supports retained. No new door or board-like panel. Chair-direction concern above prevents an unconditional geography PASS. |
| Style | PASS: simple 2D black outlines, restrained school colors, minimal shading, no photorealism or elaborate redesign. |
| Unwanted content | No readable text, speech bubbles, subtitles, extra people or motion FX observed. |
| Future animation | Wider staging provides room for restrained motion, but smaller facial scale reduces lip-sync detail. No video test performed. |

The source-panel relationship is preserved in reverse coverage rather than a literal camera copy. The room has not been reconstructed as a measured 3D set; perceived distance, row correspondence and the chair-direction concern need human review before lock. No second candidate was generated to silently resolve these issues.

## References and method

Built-in imagegen, one completed image output; final saved PNG inspected.

1. `shots/SHOT_008/keyframe_v001.png`: rejected framing; identity/emotion and reverse-room direction only.
2. `shots/SHOT_007/keyframe_v003.png`: spacious depth/scale reference; latest review candidate, not human-approved.
3. `assets/characters/CHAR_01_Ah_Lim/masters/face_front_neutral.png`: approved young Ah Lim identity.
4. `assets/characters/CHAR_02_Ah_Da/masters/full_body_3q.png`: approved Ah Da identity.
5. `assets/locations/LOC_01_classroom/masters/master_wide.png`: approved room/furniture identity, interpreted from the reverse direction.

Source `4.jpg` was visually inspected for story/emotion; no dialogue or source lettering rendered.

### Final prompt

```text
Use case: identity-preserve / composition correction. Create ONE 16:9 clean 2D cartoon keyframe, SHOT_008 v002.
INPUT ROLES: Image 1 is rejected SHOT_008 v001, the edit target for identities, emotional pose, reverse-view room direction and palette ONLY. Its camera is much too close: DO NOT preserve its framing or subject sizes. Image 2 is SHOT_007, the authority for the SPACIOUS ACROSS-CLASSROOM DEPTH and apparent scene scale we need to match from the opposite direction. Image 3 is approved young black-haired Ah Lim face identity. Image 4 is approved beige-short-haired Ah Da identity. Image 5 is LOC_01 classroom architectural/furniture identity; its front-facing view must be reversed for this shot.
PRIMARY CHANGE: Move to a genuinely WIDE spacious reverse conversational view from Ah Da's side at the classroom FRONT looking BACK down the same room toward Ah Lim. Keep the perceived across-room distance of Image 2. This is NOT a medium portrait, NOT a close-up, NOT a tight over-the-shoulder. Do not merely shrink the background around the large v001 faces. Both characters must occupy far less canvas than Image 1; expose the classroom between them.
LAYOUT: only a narrow, heavily cropped SLIVER of Ah Da at extreme LEFT foreground, partial back/side of very short light beige-haired head, ear and white shirt shoulder; at most 10–12 percent of frame WIDTH and no broad shoulder mass extending into center. Most of Ah Da is OFFSCREEN LEFT. Do not put the lens against his head. He faces inward toward screen-right listening.
Ah Lim is the only clearly visible face, seated at his own desk FARTHER AWAY in CENTER-RIGHT MID-BACKGROUND, roughly x=63 percent. His head should be around 5–6 percent of FRAME WIDTH, his body width around 10–12 percent, total seated figure around 25–30 percent of frame height, comparable to the small distant Ah Da in Image 2, not the large Ah Lim in Image 1. Show several desk-row intervals and open aisle FLOOR between foreground listener and distant speaker. Include foreground desks large in perspective, middle desks, Ah Lim's desk farther away and rear wall beyond. Neither person fills the frame. The spacious room depth is crucial.
Ah Lim remains recognizable as the approved YOUNG school-age identity: slim pale face, short black hair irregular fringe, simple eyes nose ears, white short-sleeved collared shirt with left chest pocket and green trousers, at desk. Alert confused eyes and hesitant open speaking mouth, uncertain brows, one small cheek sweat mark. He looks toward Ah Da at screen-left, slightly tense upright seated posture, hands resting on his own desk without complex gestures. He is narratively the speaking focus through the only visible expressive face, NOT through large portrait scale. No elderly traits.
Ah Da remains the secondary attentive listener, very short pale beige hair visibly hair not bald, pale skin and white school shirt. Book/legs remain out of crop; no new gestures.
ARCHITECTURE: board/front teaching area is BEHIND camera and must NOT appear anywhere. Plain rear wall, windows along SCREEN-RIGHT wall because camera direction is reversed from Image 2 and Image 5. Keep window framing and muted outdoors consistent. Tan wooden desk/chair rows with thin gray supports. Student desks face the front/camera consistently, chairs behind desk tops toward rear. No new door, no board-like rear rectangle, no altered furniture family, no impossible rotations, no fisheye. Eye-level view, normal natural perspective, no dramatic tilt. Preserve room geography; only camera direction reverses relative to SHOT_007.
STYLE: clean simple 2D cartoon black outlines, restrained flat colors, minimal shading, low-detail comic feeling. No photorealism, glossy 3D, painterly or elaborate anime.
No text, speech bubbles, subtitles, other characters, new props, FX or watermark. Produce exactly ONE image. The key success condition is WIDE ROOM DEPTH with DISTANT SPEAKING AH LIM and MINIMAL AH DA FOREGROUND, not intimate conversation framing.
```

## Disposition

REVIEW_REQUIRED. Human approval NOT RECORDED. Review camera distance and chair orientation before any lock. No video generated, no SHOT_009 work, no approved-master edits.

