# SHOT_037 Video v001 Review

Status: REVIEW_REQUIRED

Generated video: `shots/SHOT_037/video_v001.mp4`
Primary visual authority: `shots/SHOT_037/keyframe_v002.png` — HUMAN-APPROVED and locked.
Source staging: `20.jpg`. Continuity panel: `21.jpg`.
Approved continuity references: `LOC_01_WINDOW_SIDE` and `PROP_03_DESK_CHAIR_MASTER`.

## Render record

- Exactly one take: v001. No alternate take or v002 was generated.
- Duration: 4.900 seconds; 147 frames at 30 fps.
- Format: H.264 MP4, 1448 × 1086, matching the approved keyframe's 4:3 framing; yuv420p, CRF 16, fast-start playback.
- Method: deterministic image-to-video camera move using Pillow affine resampling and FFmpeg 7.1 / libx264 encoding. No generative video model was used. All visual content comes directly from the approved keyframe.
- Requested motion: very slight, slow push-in only.
- Implemented motion: a single global scale from 100% to 102%, smoothly eased about the fixed image center. No pan, tilt, orbit, depth synthesis, or independent object animation.
- Hand/forearm: held in the approved pose. Optional settling motion was omitted.
- Audio: absent; the MP4 has no audio stream, speech, or narration.

## Composition lock and inspection

The required relationship remains **HAND → EMPTY WINDOW-SIDE SEAT → WINDOW**. A uniform transform applies equally to the finger, indicated chair/desk, windows, and classroom. The finger is not redirected, and the seat does not move independently. The slight edge crop inherent in the 2% push-in keeps the target seat, pointing fingertip, and adjacent window clearly visible.

Technical verification decoded all 147 frames successfully and confirmed the expected resolution, frame rate, 4.9-second duration, and absence of audio. Every decoded frame was compared with its intended transformed keyframe; the largest per-frame mean absolute RGB error was 1.58/255, consistent with the chosen lossy video encoding. The first and last frames differ, confirming that the push-in is present.

Visual inspection of decoded frames 0, 36, 73, 110, and 146 found:

- The same empty window-side seat remains the pointing target.
- Hand shape, finger direction, desk/chair identity, window geometry, and classroom layout remain consistent with keyframe_v002.
- No new characters, hands, furniture, text, props, or motion FX are present.
- The clean outlines, restrained colors, and lighting remain consistent.
- The final frame still reads as the same approved shot with a very slight enlargement.

These checks are technical and sampled visual findings, not human approval or a substitute for viewing the clip in motion.

## Human review pending

- Target-seat clarity throughout playback: PENDING HUMAN REVIEW.
- Hand/finger stability: PENDING HUMAN REVIEW.
- Furniture/window stability: PENDING HUMAN REVIEW.
- Style and LOC_01 / PROP_03 continuity: PENDING HUMAN REVIEW.
- Push-in pacing, subtlety, and temporal smoothness: PENDING HUMAN REVIEW.

Review question: without dialogue, is it immediately obvious throughout the clip which empty window-side seat the hand indicates?

No human approval has been recorded for this video. Status remains REVIEW_REQUIRED. Further refinement or shot production waits for human review.

## Integrity

- Approved keyframe SHA-256: `af1d1b0f89b1960f42390f4dfbb3279fae9efda578604ae5a9ced6cfc3ae6996`.
- Video SHA-256: `c5dcb36eddde73f249b9de5aff20edcfee40f247c607330475714029fd712240`.
- Approved keyframes, asset masters, source panels, preflight records, and manifest statuses were preserved. `keyframe_v001.png` remains rejected review history.
