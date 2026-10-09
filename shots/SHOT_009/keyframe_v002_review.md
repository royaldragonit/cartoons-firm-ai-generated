# SHOT_009 — Keyframe v002 source-panel reconstruction review

Status: REVIEW_REQUIRED
Human approval: NOT RECORDED
Candidate: `shots/SHOT_009/keyframe_v002.png`
Date: 2026-10-06
Video: NOT GENERATED

## Human rejection and correction scope

V001 is REJECTED because its camera angle/staging was not faithful enough to source 5.jpg: the face crop was too close and foreground-dominant. Preserve v001 and its original review as history; the human rejection supersedes earlier framing PASS findings.

V002 is one source-led reconstruction candidate. The latest human instruction takes precedence over the old shot-list CU interpretation. No shot-list files were rewritten.

## Visual comparison

| Check | Observation |
| --- | --- |
| Source placement | PASS for primary relationship: Ah Da stands/leans at left foreground, Ah Lim sits at a desk at right background. No accidental left/right reversal. |
| Upper-body framing | PASS relative to rejected v001: complete head, shoulders, both elbows/arms, raised hand and waist/hips visible. Ah Da is no longer a face crop or centered portrait. |
| Foreground dominance | Ah Da remains the speaking subject but leaves substantial central/right room space visible. His scale is still a production adaptation, not an exact tracing of source coordinates. |
| Small Ah Lim | PASS for hierarchy: seated, confused and clearly smaller; he does not become co-equal. Head-size ratio is roughly comparable to the source rather than the previous close-shot emphasis. |
| Desks / depth | PASS for readable depth: several desk rows recede across the center, with open floor and distinct distant reaction position. |
| Gesture fidelity | One arm raised on viewer-left with sideways hand; other forearm bent low. This is closer to the source than v001's oversized palm-up close-up. |
| Strong cartoon tears | PASS: two broad flowing pale-blue streams with drops, open wailing/speaking mouth and theatrical brows. Not subtle realistic tears. |
| Comic rather than tragic | Broad stylization supports comic overreaction. Teasing relief versus sorrow remains a human performance judgment; mouth/brow shape alone cannot prove the intended sarcasm. |
| Ah Da identity | Beige cropped hair, pale youthful face, prominent ears and school shirt remain recognizable. Exaggerated eye/mouth shapes and near-frontal head are performance adaptations; final identity approval remains human. |
| Ah Lim identity | Young black-haired identity and white/green uniform recognizable. DISCREPANCY: visible shoes are light/white with dark soles instead of the canonical dark footwear. |
| Classroom identity | Cream walls, tan desks, gray supports and right-side windows retain LOC_01 visual family. The view is more oblique than v001 and does not show a board behind Ah Lim. Exact desk-row correspondence is not proven. |
| Style | Clean simple 2D line art, restrained colors and little shading; no photographic blur or glossy 3D. |
| Unrequested accents | Small black comic marks appear beside the raised hand and Ah Lim's head despite the prompt asking to omit them. Source has similar accents, but they are baked into the still; human review should decide whether to retain them before animation. |
| Text / extras | No speech bubbles, subtitles, readable dialogue, additional characters or new handheld props. |
| Later animation | Half-body gesture and face are readable. Raised hand anatomy, tear attachment and accent-mark handling need motion planning; no video or animation stability test performed. |

## Remaining review points

The principal framing/depth correction is visibly improved. Do not treat that as overall approval. Ah Lim's light shoes are a canonical outfit discrepancy. Ah Da faces almost front rather than clearly looking back to Ah Lim; squeezed eyes prevent exact eyeline verification. The small baked-in comic marks and emotional nuance also need human judgment.

One candidate was generated only. No silent second pass or changes to approved references were made.

## References and provenance

Method: built-in imagegen through the imagegen skill, source-panel-led generation. Saved PNG visually inspected.

Inputs in order:
1. `5.jpg` — primary layout, relative scale, raised arm and comic crying.
2. `assets/characters/CHAR_02_Ah_Da/masters/face_front_neutral.png` — approved Ah Da identity.
3. `assets/characters/CHAR_01_Ah_Lim/masters/face_3q_talking.png` — approved young Ah Lim identity.
4. `assets/locations/LOC_01_classroom/masters/master_wide.png` — approved room/furniture family, not camera authority.

Also inspected SHOT_009 v001 and latest SHOT_007 v003 / SHOT_008 v002. Prior shot candidates remain review history, not approved authority.

### Final prompt

```text
Use case: illustration-story, source-panel composition reconstruction.
Generate ONE 16:9 production keyframe SHOT_009 v002. The PRIMARY COMPOSITION AUTHORITY is image 1 (5.jpg). Reconstruct its humorous spatial layout closely, as a clean colored 2D animated adaptation. Do not reinterpret it as a cinematic facial close-up. Remove all speech bubbles, lettering and orange border; use the released space as simple classroom context, not enlarged faces.
REFERENCE ROLES: Image 1 source panel 5.jpg = placement, body/gesture, depth and emotional exaggeration. Image 2 approved Ah Da front neutral = exact youthful identity, pale beige short hair and facial proportions (change expression only). Image 3 approved young Ah Lim = his identity. Image 4 approved LOC_01 master = architecture/furniture family and colors, not its front-facing camera.
CRITICAL SCALE / BLOCKING: Ah Da is a HALF-BODY foreground figure on the LEFT, from complete head to waist/hips, with generous headroom, BOTH shoulders and elbows visible, one full raised hand. Occupy only about the left third of the frame (overall gesture may reach x=12–43%). Head center around x=31%, y=43%; head height about 22–25% of frame, NOT 60%. Waist reaches bottom edge. Do NOT put his face centrally, do NOT make him fill almost all the picture. Keep the entire central and right classroom space available. This is a wider panel-like upper-body scene, NOT a portrait or face crop.
Ah Da stands/leans near left/front teaching-area edge, as in source. One arm on viewer-left bends upward, hand lifted near head height with a loose palm-up theatrical gesture, same source direction. Other forearm bent low across his torso. Head nearly frontal but slightly toward screen-right, addressing Ah Lim behind/right. Clear simple hands, no complicated fingers. No book/equipment added.
Ah Lim is TINY and clearly SECONDARY in the RIGHT BACKGROUND, around x=76%, y=45–58%, seated at his own student desk. His head height at most one-third of Ah Da's head, like source. White shirt, black irregular short fringe, green trousers glimpsed under desk, wide confused eyes, slight open mouth, hands on desk reacting to the performance. He looks toward Ah Da. Never enlarge him into a coequal conversational portrait.
ROOM DEPTH: match source's oblique diagonal view from near front/board-side across several tan classroom desks to far-right seated Ah Lim. Many desks and chairs must remain visible between them and around Ah Lim, with open floor and clear receding perspective. Draw classroom and both characters sharply in the same simple line art, no depth-of-field blur. Cream walls, simple tan wooden rectangular desks/chairs with thin gray supports from image 4. Consistent student desk orientation toward front/near camera; empty chairs on FAR side behind their desks, not on camera side. The front teaching area is near left/offscreen; do not put a big whiteboard behind Ah Lim. A modest side/front wall edge at far-left is enough; no need for a new door or board. Windows if shown remain on far/right side in this reverse/oblique camera direction. Do not force all architecture into view or add clutter.
AH DA PERFORMANCE: retain the successful EXAGGERATED COMIC CRYING, but at source-panel scale. He is mock-dramatic, relieved, absurdly overjoyed and slightly teasing after waiting forever, not sincerely grief-stricken. Wide-open dramatic crying/speaking mouth with comic lifted corners, theatrical brows and squeezed overwhelmed eyes. TWO broad stylized pale-blue tear streams flow strongly down his cheeks with a few simple drops: funny cartoon flood, not realistic subtle wet tears. Strong visible tears despite smaller face. Maintain exact approved pale angular youthful face, prominent rounded ears, very short LIGHT BEIGE HAIR visibly present (not bald, not elderly), simple thin eyebrows and small nose, white short-sleeved collared school shirt with left chest pocket, green uniform trousers at lower crop. No wrinkles, beard, Ah Lim black fringe or permanent face marks.
STYLE: clean simple 2D cartoon black outlines, restrained flat colors, minimal shading, low-detail source-comic feeling. No realistic skin/water, glossy 3D, painterly, elaborate anime, soft-focus background or dramatic lighting.
NO text, speech bubbles, subtitles, dialogue, readable board writing, orange border, extra students, unrelated props, comic motion lines, split panels or variants.
ONE image. Success is the source-panel-like LEFT HALF-BODY AH DA + MANY INTERVENING DESKS + SMALL BACKGROUND RIGHT AH LIM, not the previous excessive close-up.
```

## Disposition

REVIEW_REQUIRED. Human approval NOT RECORDED. No video generated; no SHOT_010 work. Previous images and approved masters preserved.

