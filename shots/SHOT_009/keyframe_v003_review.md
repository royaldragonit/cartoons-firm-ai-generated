# SHOT_009 — Keyframe v003 classroom and fourth-row continuity review

Status: REVIEW_REQUIRED
Human approval: NOT RECORDED
Candidate: `shots/SHOT_009/keyframe_v003.png`
Date: 2026-10-06
Video: NOT GENERATED

## Rejected history and scope

V001 remains rejected for overly close framing and camera/staging not faithful enough to 5.jpg. V002 is now explicitly REJECTED by human review: the board was lost, desks/chairs disappeared, and Ah Lim's seating position was wrong. Both PNGs and their reviews remain unchanged as history. This human rejection supersedes earlier positive continuity findings.

V003 is one corrected candidate, not approved. Requested fixes: restore the board, restore desk/chair rows, and seat Ah Lim in row four with three rows in front of him. Preserve v002's comic half-body Ah Da and source-directed left/right depth structure. No other shot or asset was generated.

## Direct inspection of saved PNG

| Check | Finding |
| --- | --- |
| Board presence | PASS for visible restoration: pale writing surface, thin dark frame and lower tray at the far-left/front edge beside Ah Da's raised hand. It is no longer a featureless wall. |
| Board content | Sparse nonlexical black strokes indicate classroom notes. No exact names, dialogue, farewell text or invented readable wording. |
| Front/back logic | The board is cropped at the near/front edge, not placed behind distant Ah Lim. Windows remain screen-right in this oblique reverse view. Exact camera reconstruction against the full location master remains a human-review judgment. |
| Furniture coverage | Visibly increased versus v002: densely repeated tan desk/chair sets occupy center and right with receding rows and aisles. No claim that every partly hidden desk in other camera views is individually accounted for. |
| Fourth-row seating | PASS for the visible column count: three empty desks precede Ah Lim's occupied desk in the right-side column, making his the fourth from the front. See count below. |
| Desk/chair family | Tan rectangular tops, tan chair backs/seats, gray supports and simple black outlines follow PROP_03 / LOC_01. Overlapping legs and partly occluded chairs still require human geometry review. |
| Source 5.jpg staging | Ah Da remains left foreground, upper body to hips with raised viewer-left hand, other forearm low, wide mouth and two exaggerated blue tear streams. Ah Lim is small, seated and confused at right background. No left/right reversal or balanced close two-shot. |
| Ah Da identity / emotion | Light-beige short hair, pale youthful angular face, prominent ears and white/green uniform preserved from v002. Theatrical cartoon crying is strong; mocking relief versus sad wailing remains a human performance judgment. |
| Ah Lim identity | Young black-haired identity, white shirt and small surprised reaction retained. Lower body/footwear are occluded by intervening furniture; dark-shoe continuity remains required but cannot be verified here. |
| Classroom continuity shots | SHOT_007 v003 establishes written front board and depth; SHOT_008 v002 establishes distant seated Ah Lim across rows. They remain review candidates, not newly approved or fully reliable geometry masters. Latest user instruction is the explicit fourth-row authority. |
| Style | PASS: clean simple 2D cartoon outlines, restrained colors, minimal shading; no photorealism, glossy 3D or painterly redesign. |
| Unrequested details retained | Small comic accent strokes remain beside Ah Da's hand and Ah Lim's head despite the prompt requesting no extra streaks. Do not treat these as approved motion FX. |
| Text / extras | No dialogue text, subtitles, speech bubbles, extra characters or new handheld props. |
| Video suitability | Spacious layout and small background reaction remain usable for review. No motion test was performed; tear attachment, raised-hand anatomy and furniture stability would need later motion planning after human approval. |

### Fourth-row count

Count from the near/front teaching area toward Ah Lim, following the right-side desk column, not from the back wall:

1. Near empty desk, large tabletop at the lower-right (roughly 74–88% of image height).
2. Next empty desk, tabletop roughly 57–66% of image height.
3. Next smaller empty desk, tabletop roughly 48–53% of image height.
4. Ah Lim's occupied desk, tabletop roughly 42–45% of image height, with his hands resting on it.

These coordinates are descriptive inspection aids, not rendered labels. Three empty desk/chair positions visibly intervene before his occupied desk. Whole-room row alignment and exact seat-column matching across angles are not independently certified.

## Remaining human-review checks

- Confirm restored front-board placement reads naturally as the same classroom, not a newly introduced side/rear board.
- Confirm three intervening rows and the precise seat-column relationship to SHOT_007/008.
- Check partially occluded chair orientation/support geometry and overall desk inventory across cuts.
- Decide whether the small inherited comic accent strokes are acceptable.
- Confirm Ah Da's performance reads as comic relief/teasing, not sincere despair.

No automated finding constitutes approval. Status remains REVIEW_REQUIRED.

## References and generation provenance

Method: built-in imagegen edit, using the imagegen skill to preserve v002's staging while changing room/seating continuity. One output image generated. An initial request exceeded the tool's five-reference limit and was rejected before image generation; it produced no alternate take.

Input images in order:
1. `shots/SHOT_009/keyframe_v002.png`
2. `5.jpg`
3. `shots/SHOT_007/keyframe_v003.png`
4. `shots/SHOT_008/keyframe_v002.png`
5. `assets/locations/LOC_01_classroom/masters/master_wide.png`

Also inspected approved LOC_01 front, window-side and door-side masters, PROP_03 desk/chair, CHAR_01 seated-neutral and CHAR_02 face-front-neutral. These additional masters were visual checks, not separate uploaded generation inputs. PROJECT_STATE.md, AGENTS.md, live manifest and SHOT_007/008/009 briefs/reviews informed continuity; manifest statuses govern asset approval.

Saved generated PNG directly to the requested versioned output and visually re-opened it. Earlier keyframes and approved masters were not modified. No video generated.

### Final prompt

```text
Use case: compositing / illustration-story continuity correction.
Produce ONE 16:9 clean 2D animation keyframe, SHOT_009 v003. Edit image 1 (SHOT_009 v002) while preserving its humorous left-foreground half-body Ah Da, raised hand, huge flowing cartoon tears and smaller confused right-background Ah Lim. Repair ONLY the classroom geometry, furniture coverage and Ah Lim seating continuity, not a new close-up.
REFERENCE ROLES:
1 = immediate edit target SHOT009 v002. Preserve its overall character hierarchy, colors, line style, theatrical Ah Da performance, upper-body framing. Its blank wall and too-forward Ah Lim placement are WRONG.
2 = source 5.jpg, authority for comic pose, board-edge near raised hand, left/right staging; do not copy speech bubbles, text or border.
3 = SHOT007 v003, continuity evidence for classroom front whiteboard with sparse nonlexical notes and separation across student rows; do not copy its reverse camera.
4 = SHOT008 v002, continuity evidence for deep desk rows and small distant seated Ah Lim; do not copy foreground crop or backwards-facing empty chairs.
5 = approved LOC01 master_wide, authority for board/frame/tray, cream walls, gray window frames, tan wooden desks/chairs and gray legs. This is a camera-facing-front master, not this shot's camera.
Preserve the established young character identities from image1 and continuity images3/4: Ah Lim black irregular fringe and dark shoes; Ah Da youthful light beige short hair, pale slim face and prominent ears.
MANDATORY BOARD REPAIR: At the far LEFT foreground, restore the visible cropped portion of the FRONT teaching whiteboard on its front wall, viewed steeply obliquely near Ah Da's raised hand, as the board-edge/tray cue in source 5.jpg. Show enough pale writing surface, thin dark frame and lower tray that it unequivocally reads WHITEBOARD, not a cream blank wall strip. Sparse black nonlexical classroom-list squiggles on the visible part, echo image 3, not exact words. The board stays at the FRONT of the room, close beside Ah Da at camera-left; do NOT put it behind distant Ah Lim on the rear wall. Camera is near the front/door-side teaching area looking diagonally back along classroom rows, with a sliver of front board in the left edge of its oblique field. Keep screen-right windows as image1, same room not mirrored. No new doorway needed.
MANDATORY FOURTH-ROW SEATING: Ah Lim must sit in ROW FOUR counting from the board/front. THREE COMPLETE EMPTY ROWS of student desk-and-chair sets must be visibly IN FRONT OF HIM, between the front teaching area/camera and his own desk. His desk is the FOURTH, farther up/right in screen depth. Do not put him at the first foreground desk as image1. Arrange repeated aligned desk rows with clear aisles and separation; show three distinguishable successive desk tops in his longitudinal column leading from near-camera row1, through row2 and row3, to occupied row4. Their perspective scale decreases toward him. Do not count his own desk as one of the three empty rows. Do not add captions, numbers, arrows or diagram labels. Allow near desks to partly cover his lower legs naturally, but leave his small surprised face, white-shirt upper torso, and hands at his fourth-row desktop readable. He is small background RIGHT, gaze directed toward Ah Da LEFT. Do NOT enlarge him. Young black irregular fringe, white short-sleeved collared shirt with chest pocket, green trousers, DARK shoes if visible, confused open mouth and slight sweat.
RESTORE FURNITURE: Keep a populated field of tan desks AND matching chairs across center and right, not large areas of emptied floor. Multiple longitudinal columns and at least four depth rows; coherent perspective and spacing. Every desk has one chair on its rear side, farther from classroom FRONT; all student seating faces the board/front-left/camera area, not random directions. The three empty rows before Ah Lim must be countable. Maintain usable aisles; no furniture fused together, no missing supports or giant tables.
PRESERVE AH DA: dominant left foreground shown head to hips, full raised arm and simple hand, opposite forearm bent low. Half-body, NOT a face close-up, not centered portrait. Keep image1 youthful light-beige short hair visibly present, pale slim face, prominent ears, white short-sleeved school shirt, green trousers. One dramatic palm-up raised hand; huge exaggerated blue tear streams, open comic wailing/speaking mouth, theatrical brows. Comedic mock-dramatic relief and teasing joy, not tragic realism. Do not fill whole frame with his head. Preserve ample central/right room depth.
STYLE: same clean simple 2D cartoon line art, black outlines, restrained flat colors, minimal shading. All classroom objects clear, not photographic blur. Exactly two characters only.
AVOID: readable dialogue/text, speech bubbles, subtitles, farewell wording, extra characters, extra props, additional boards, board on rear wall, disappearing desks, Ah Lim in rows1-3, random chair orientations, white shoes, elderly traits, realistic grief, photorealism, glossy 3D, extra motion streaks. Render one final frame only, no contact sheet or alternatives.
```

