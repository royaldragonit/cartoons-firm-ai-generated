# SHOT_007 — Keyframe v003 review

Status: REVIEW_REQUIRED
Human approval: NOT RECORDED
Candidate: `shots/SHOT_007/keyframe_v003.png`
Date: 2026-10-05
Video: NOT GENERATED

## Scope and history

V001 remains REJECTED for interpreting source 4.jpg as a close face-to-face conversation. V002 is close but NOT APPROVED: its improved depth composition omitted the source-specific writing on the whiteboard. Both earlier PNGs and reviews are preserved.

V003 is a single targeted built-in imagegen edit of v002, not a new shot design. Only sparse writing-like marks were requested. Automated inspection findings below are not human approval.

## Source and continuity comparison

- Source 4.jpg visibly shows short wavy classroom-board strokes in loose rows/groups, behind the distant seated Ah Da. V003 echoes this information cue without attempting exact lexical transcription.
- Source 3.jpg provides the preceding waking/confused emotional context.
- Approved young Ah Lim profile and Ah Da greeting references support the identities. Elderly Ah Lim references were not used.
- LOC_01 classroom masters support the front board, left windows, furniture and room depth.
- PROP_09_WHITEBOARD was inspected for the thin-frame board family only. Its source-36 farewell wording is not appropriate here and was not supplied to the image edit.

## Visual inspection findings

| Check | Finding |
| --- | --- |
| Board no longer blank | PASS: black writing-like strokes are visibly present across the board. |
| Source-specific classroom-content cue | PASS: approximately five airy rows in three loose groups read as a list/notes, broadly echoing 4.jpg. This is not a literal reproduction of each source stroke. |
| Text constraint | PASS: deliberate nonlexical squiggles, no precise Vietnamese paragraph, invented names, readable attendance statuses, dialogue, farewell message, subtitle or speech bubble. |
| Foreground/background staging | PASS: young Ah Lim remains large at right foreground; Ah Da remains much smaller at center-left, across the room. No balanced close two-shot. |
| Ah Lim identity/direction | PASS on visual inspection: black fringe, youthful profile facing left, wide confused eye, parted mouth and sweat mark retained. |
| Ah Da identity/action | PASS on visual inspection: short beige hair, white shirt, green trousers, seated book/crossed-leg greeting retained. He remains the narrative speaker, not the largest visual subject. |
| Classroom continuity | PASS on visual inspection: left windows, front board, aligned tan desks/chairs and depth remain consistent with v002. No new door. |
| Board integration | PASS: marks stay within the writing surface and do not cover characters or frame. Board proportions and tray remain visually consistent. |
| Style | PASS: clean black outlines, restrained colors, simple 2D cartoon treatment; no stylistic redesign observed. |
| Other content | PASS: no added characters or unrelated props observed. |

The marks are intentional graphical shorthand representing written classroom content, not failed OCR or a claim to recovered wording. No exact readable text was requested or composited.

The composition appears essentially unchanged outside the board; this is a visual comparison, not a claim of pixel-identical generative output. Ah Da's distant face and exact eye contact should still be judged at intended playback size during human review. The board-content correction does not constitute approval of the whole shot.

## Generation provenance

Method: built-in imagegen, one image edit, one output. No video.
Edit target: `shots/SHOT_007/keyframe_v002.png`.
Supporting input: `4.jpg`, only for board-writing appearance.
Approved masters were inspected but not modified.

### Final prompt

```text
Use case: precise-object-edit.
Create ONE corrected 16:9 2D cartoon production keyframe, SHOT_007 v003.
Image 1 is the EDIT TARGET and authoritative composition, character identity, furniture, architecture and colors. Image 2 is source panel 4.jpg, used ONLY for the sparse list-like marks on the classroom board. Do NOT copy its speech bubbles, words, border or alternate room design.
Change ONLY the blank writing surface of the distant whiteboard in Image 1: add visible restrained black marker-like pseudo-writing, approximately five or six airy rows arranged in three loose groups/columns, with short irregular wavy strokes and small writing blocks, similar to the board marks in Image 2. These are intentionally NON-LEXICAL, abstract classroom list/attendance-note marks, not actual words. Keep ample margins and spacing, low detail, not a dense paragraph. The board must visibly read as containing a classroom list/notes. Keep all strokes inside the board surface, naturally occluded by Ah Da and foreground Ah Lim. Do not put marks on characters or frame.
Preserve everything else from Image 1 as closely as possible: large black-haired young Ah Lim at RIGHT FOREGROUND in left-facing profile, wide confused/startled eye, sweat mark and parted mouth; much smaller pale short beige-haired Ah Da at CENTER-LEFT BACKGROUND, seated with book and crossed legs, friendly energetic greeting; exact relative character scales, poses and positions. Preserve camera crop, strong classroom depth, left windows, desk/chair count and alignment, board/frame/tray proportions, colors, lighting and clean black outlines. Do not enlarge Ah Da or change to a balanced close two-shot. Do not change faces, hair, clothing, architecture or furniture. No new door, no new props, no other characters.
Style remains clean simple 2D cartoon line art, restrained flat colors, minimal shading, low-detail source-comic feeling.
NO readable text, names, numbers, headings, Vietnamese paragraphs, dialogue, farewell wording, subtitles, speech bubbles, logos or watermark. Only the sparse nonlexical board markings are new. One image only, no alternatives.
```

## Recommendation

Ready for human inspection of the board-content correction. Keep REVIEW_REQUIRED until explicit human approval. Do not advance to SHOT_008 or video generation.

