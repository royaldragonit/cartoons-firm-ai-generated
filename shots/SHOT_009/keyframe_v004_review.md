# SHOT_009 — Keyframe v004 perspective and comic-performance review

Status: REVIEW_REQUIRED
Human approval: NOT RECORDED
Candidate: `shots/SHOT_009/keyframe_v004.png`
Date: 2026-10-06
Video: NOT GENERATED

## Human review history and scope

V003 is REJECTED and preserved unchanged as review history. Human review accepted its seating position and broad source-panel staging as the base, but requested three corrections: straighten room perspective, correct teacher-desk/front-furniture angle, and push Ah Da's comic crying further. This supersedes earlier positive geometric findings; it does not revoke any approved master.

V001 and v002 remain rejected history. V004 is one candidate only, generated with built-in imagegen as an edit of v003. No approval, video, other shot, new master or extra take.

## Direct inspection of saved PNG

| Check | Observation |
| --- | --- |
| Stable eye-level presentation | Improved: ceiling junction and window crossbars read horizontally; wall corners, mullions and desk legs read vertically; the broad diagonal slant is reduced. Not a measured single-vanishing-system certification. |
| Student furniture perspective | Desk front edges are more level and the repeated tops recede in a consistent general direction. Leg overlaps and exact convergence remain human-review checks. |
| Teacher desk / lectern correction | REVIEW_REQUIRED: the front-class area is partly hidden by Ah Da, and a complete distinct teacher desk is not clearly identifiable. Visible nearby furniture is straighter, but a fully verified teacher-desk/podium fix cannot be claimed. No new lectern was added to force visibility. |
| Board / tray | Board remains visible on the near left with frame, tray and sparse nonlexical strokes. Tray still has conspicuous depth diagonals; human must judge whether these now fit the corrected room. No readable dialogue or new wording. |
| Window-wall continuity | REVIEW_REQUIRED: windows became substantially more front-on while the board retains an oblique side view. This can flatten/change the perceived wall relationship even though individual lines are straighter. Exact LOC_01 continuity is not established merely by level edges. |
| Ah Lim fourth-row seat | Retained in the same background-right column. Three empty desks precede his occupied desk: nearest large top at roughly 75–87% image height, next at 59–67%, next at 50–54%, then occupied desk at 44–48%. No move to an earlier row is visible. |
| Ah Lim scale / reaction | Small young black-haired confused student, white shirt, hands on desk, secondary to Ah Da. Minor screen-position shift accompanies the redraw; logical row/column remains. Footwear occluded and not independently checked. |
| Desk coverage / depth | Full central/right desk field and repeated chairs retained; no newly emptied zone. Exact hidden furniture inventory across shots remains unverified. |
| Ah Da mouth | Noticeably wider and taller open wailing mouth than v003, simplified teeth and tongue; clear escalation without turning into a facial close-up. |
| Ah Da tears | Much more forceful outward-curving fountain ribbons and large drops from both eyes. Clearly stylized absurd cartoon crying, not realistic tears. |
| Brows / gesture | Exaggerated lifted brows, squeezed eyes and open palm-up raised hand strengthen theatrical appeal. Half-body left-foreground staging and other bent forearm preserved. |
| Emotional nuance | Strong comic overreaction is visible. Whether it reads specifically as relieved, teasing mock-sentimentality instead of sadness remains human judgment; do not approve from intensity alone. |
| Identity | Youthful beige hair cap, pale angular face, ears and white/green uniform remain recognizable. Extreme mouth/brow deformation is shot performance, not a replacement identity master. |
| Source composition | Ah Da left foreground, Ah Lim small right background, board-side context and intervening desks remain. No accidental mirror or balanced close two-shot. |
| Style / exclusions | Clean 2D outlines, restrained flat colors, minimal shading. No extra characters, speech bubbles, subtitles, readable text, photorealism or 3D. Small inherited comic accent strokes remain. |
| Future motion | No animation generated or tested. Broad tear ribbons, wide mouth, raised hand, furniture and seated reaction would need controlled motion planning after approval. |

## Review conclusion

The stronger comic performance and straighter individual architectural/furniture lines are visible. Ah Lim's fourth-row read is retained. The teacher-desk correction is not fully verifiable because of occlusion/ambiguous furniture identity, and the changed window-wall plane needs particular scrutiny. Overall status remains REVIEW_REQUIRED; this is not an automatic PASS or human approval.

## References and method

Built-in imagegen; the imagegen skill guided a non-destructive, invariant-preserving edit and direct saved-PNG review. One generation call, one output.

Input roles:
1. `shots/SHOT_009/keyframe_v003.png` — immediate edit base; accepted seating/staging components, rejected perspective/performance.
2. `5.jpg` — source-panel composition and theatrical performance; lettering excluded.
3. `assets/locations/LOC_01_classroom/masters/front.png` — approved architectural/teacher-furniture family, not camera direction.
4. `assets/props/PROP_03_desk_chair/master.png` — approved student furniture construction.
5. `assets/characters/CHAR_02_Ah_Da/masters/face_front_neutral.png` — approved identity, not neutral expression.

AGENTS.md, PROJECT_STATE.md, live manifest, current SHOT_009 brief and v003 review were consulted. Earlier continuity findings remain historical context, not newly granted approval. Approved references and earlier keyframe PNGs/reviews were not modified. No manifest, shot-list, preflight or SHOT_010 changes.

### Final prompt

```text
Use case: precise-object-edit / illustration-story.
Generate ONE corrected 16:9 keyframe SHOT_009 v004 by editing image 1 (v003). Keep its successful composition and seating, not a new camera setup.
INPUT ROLES: image1 = exact edit base and blocking authority. Image2 = source comic panel 5.jpg, comic performance/left-right staging only, omit lettering/bubbles/border. Image3 = approved LOC01 front master, stable rectangular classroom/teacher-desk geometry and style ONLY, do not copy camera direction. Image4 = approved student desk/chair construction. Image5 = approved youthful Ah Da identity; expression may exaggerate dramatically but keep hair/ears/skull/skin and uniform.
PRESERVE: Ah Da dominant half-body LEFT FOREGROUND at board side, raised viewer-left arm and other arm bent low; small young black-haired Ah Lim at same background-RIGHT desk position (approximately x80%, head y30%). Ah Lim's occupied desk remains ROW FOUR from the front: exactly THREE empty desk rows between camera/front and his occupied desk. Maintain the same longitudinal column, desk population and room depth. Keep visible board surface/frame/tray at far-left foreground and window wall at screen-right. Board is NOT behind Ah Lim. Keep scale, spacing, colors and shot direction. No zoom or enlarged face framing.
CHANGE A: Rebuild only the wonky architectural and furniture lines into a STABLE EYE-LEVEL perspective, with zero camera roll. Rear-wall ceiling junction is horizontal; all structural verticals truly upright. Desk front edges and corresponding horizontal window members read level across each plane; receding depth lines converge coherently on the SAME level eye-height horizon. Do not flatten depth into a wall of furniture. Keep rectangular tabletops, evenly aligned rows, matching chairs, credible vertical legs. Straighten the room, not rotate the entire bitmap. Remove conflicting vanishing directions and any sheared/twisted furniture. Preserve same room layout and all three intervening desks in front of Ah Lim.
CHANGE B: Correct the visible front-class furniture/teacher desk area near Ah Da into the SAME coherent perspective system as student desks. Its top must be a rigid rectangular plane, upright sides/legs, no leaning podium, crooked wedges or independently rotated front edge. Match the simple teacher desk family in image3 if the visible portion needs reconstruction; do not add a new lectern or large furniture object, do not obscure Ah Da or swallow the rows. Correct the board tray/front edge too; not a steep diagonal wedge. Board remains clearly visible with the same sparse nonlexical squiggles, no new words.
CHANGE C: Push Ah Da's face and raised-hand performance MUCH further, noticeably stronger than image1. A huge WIDER open comic wailing/speaking mouth, broader and taller with simplified upper teeth/tongue, squeezed exuberant eyes, outrageously arched expressive brows, mock-sentimental overjoyed relief. Thick forceful blue ribbon-like tears POUR from both eyes with absurd fountain-like outward bends and large simple drops, a cartoon torrent not natural wet cheeks. It should feel hilariously theatrical, sarcastic, almost 'finally you arrived after forever', NOT realistically grief-stricken. Raised hand can spread in an exaggerated palm-up appeal, slight shoulder lift; preserve same arm direction/pose and complete hand visibility. Do not increase his overall head scale or create a facial close-up. Keep youthful light beige VERY short hair cap visibly present, prominent ears and canonical identity. No bald old man, extra face wrinkles or tragic realism.
Ah Lim remains the same small confused surprised secondary reaction with white shirt/green trousers, dark shoes if visible, hands on his own fourth-row desk, not moved into another row or coequal subject.
STYLE LOCK: clean simple 2D cartoon black line art, restrained flat colors, minimal shading, simple source-comic geometry. Exactly two characters. Keep background legible.
NO text, dialogue, speech bubbles, subtitles, labels, added characters, added props, new doors/boards, missing desks, turned desks, tilted camera, photorealism, 3D, elaborate anime, painterly details or alternative variants. One image only.
```

