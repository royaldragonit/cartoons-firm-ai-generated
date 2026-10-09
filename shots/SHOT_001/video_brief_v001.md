# SHOT_001 — Controlled motion/video brief v001

Prepared: 2026-09-23
Status: PREPARED — ready for external image-to-video testing in a separately authorized task.
Keyframe status: HUMAN-APPROVED / LOCKED.
Video status: NOT GENERATED. No video approval is implied.

## 1. Verified precondition and shot purpose

The live `shot_001_brief.md`, `keyframe_v002_review.md` and PROJECT_STATE.md explicitly record human approval and lock of `shots/SHOT_001/keyframe_v002.png`. The actual PNG was reopened and inspected. Its SHA-256 is `7b49da765e3a3b42a026c25c771e77fa0419384e98cb39e6b230766173885de3`. This is the only canonical starting frame. V001 remains rejected framing history; never use it as a starting frame or alternate composition.

SHOT_001, narrative scene 1, source panel `1.jpg`, location LOC_05. Character: CHAR_01 **elderly hospital variant**, over 90. Supporting characters: anonymous canonical hospital staff only. Prop: PROP_04_BED_TUBING.

This opening must immediately communicate extreme weakness, near death and dependence on breathing support. Mood: quiet, somber, medically supported, restrained and almost physically exhausted. Do not turn it into emergency action or a death event.

Both shot lists specify CU, eye level and a very slight push-in. Their estimated **6.4-second duration is provisional**, not a newly locked runtime. Use that as the planning target; select and record an actual supported test duration in the future generation task. Do not invent a model-specific duration or silently speed up/loop breathing to meet it. Retain the approved image's landscape 3:2 composition (1536 × 1024 source); do not stretch, outpaint or automatically crop it into another layout.

Preflight remains READY_WITH_BLOCKING_REFERENCE; its blocking requirement is now satisfied by human-approved v002. The preflight files are unchanged. Older shot-list family/visitor wording and audio suggestions do not override canonical staff or this silent visual pilot.

## 2. Reference priority and inspection

Read: AGENTS.md; PROJECT_STATE.md; live asset manifest; shot brief and v002 review; preflight Markdown/JSON and SHOT_001 shot-list Markdown/JSON records. Visually inspected: approved v002, original panel 1.jpg and all five approved canonical references below.

All paths are relative to the repository root.

| Priority / role | Exact reference | Use and limit |
| --- | --- | --- |
| PRIMARY visual authority / starting image | `shots/SHOT_001/keyframe_v002.png` | HUMAN-APPROVED and LOCKED. Governs framing, scale, pose, visible content, facial state and screen-space relationships throughout the clip. |
| Source staging authority | `1.jpg` | Patient/bed relationship, flanking staff, right-side support and somber story context. Do not copy its wider composition, text, bubbles, border or credits. |
| Elderly identity support | `assets/characters/CHAR_01_Ah_Lim/elderly/hospital_portrait.png` | APPROVED CHAR_01_ELDERLY_HOSPITAL_PORTRAIT. Preserve age and facial identity; do not import its upright posture or partly open eyes. |
| Elderly pose support | `assets/characters/CHAR_01_Ah_Lim/elderly/bed_pose.png` | APPROVED CHAR_01_ELDERLY_BED_POSE. Supine frailty, gown and medical support, not its diagonal full-bed framing or vignette. |
| Environment identity | `assets/locations/LOC_05_hospital/masters/master_wide.png` | APPROVED LOC_05_HOSPITAL_MASTER. Design/palette continuity only; do not reveal the full room. |
| Medical prop identity | `assets/props/PROP_04_hospital_bed/master.png` | APPROVED PROP_04_BED_TUBING. Bed, mask/tube family and established apparatus; no new equipment. |
| Staff identity | `assets/extras/hospital_staff/group.png` | APPROVED EXTRA_HOSPITAL_STAFF_GROUP. White/pale-blue clinical clothing; only fragments already visible in v002, not a full group lineup. |

For a future Seedance/Kling or other external test, use v002 as the starting-image input. Supporting references are comparison/identity aids, not alternate starting/end frames. If a tool supports additional references, assign their roles explicitly; never blend or average their framing. **V002 overrides every supporting image whenever composition differs.** Model/version, controls and availability must be checked in the later authorized task; this brief makes no claim about current model capabilities.

Never use young/afterlife Ah Lim masters, obsolete hospital visitors or rejected v001 as generation authority.

## 3. Approved composition and identity lock

Preserve the accepted close-up: Ah Lim's large central head/face, mask, thin neck, shoulders/upper chest, pale pillow and rightward breathing tube. Retain the frontal eye-level bed axis, supine supported head, pale blue gown, cream head support, lower-edge blanket and tiny right apparatus crop. The visible panel behind the pillow is the head support, not a foreground footboard.

Staff stay secondary white/blue clothing and arm fragments at the extreme edges. Their faces and most bodies are outside this frame. Do not reveal them, widen to show five people, restore the full bed/footboard, or reconstruct the wide source composition.

Lock the 90+ facial proportions, receding sparse gray-white hair, gaunt face, forehead/cheek wrinkles, heavy aged eyelids, gray aged eyebrows, prominent ears, thin neck and mask placement. No age regression, fuller cheeks, different hairline, beard/mustache, redesigned eyes, wrinkle crawling, face morphing or sliding mask.

The human has accepted the heavy/closed eyelids as critical exhaustion rather than ordinary sleep. Preserve that state; do not reopen this design decision through animation.

## 4. Motion hierarchy and limits

Very little moves. Use real localized temporal motion, not a deterministic still-image zoom presented as image-to-video.

1. **Primary:** extremely shallow, slow upper-chest respiration.
2. **Secondary:** very slight, slow camera push-in toward face/mask.
3. **Optional tertiary:** tiny medically coherent secondary movement, only if stable.
4. **Lowest priority:** minimal staff micro-motion, only if stable and within existing edge fragments.

If optional movement threatens identity, attachments or composition, omit it. A stable mask, tube, staff and environment are preferred to extra activity. Preserve subtle chest life so the result is not merely a slideshow zoom.

### Ah Lim and breathing

Allow an almost imperceptible slow rise/fall of upper chest beneath the gown, with minimal related neck/chest respiration and barely perceptible blanket response. He remains almost completely motionless. Weak, labored breathing is suggested by extremely small amplitude and frailty, not heaving, gasping or facial acting. Do not impose a dramatic breath-hold, final exhalation or abrupt cessation.

Head, ears, hairline, face outline, brows and mouth remain still. Default: eyelids stay unchanged. An optional tiny eyelid micro-movement is acceptable only if it does not reveal/open the eyes or suggest waking; omit it for the initial restrained test if uncertain.

No alertness, speech, mouth movement, head turn, hand lift, reaching, large expression, grimace, cough, dramatic gasp, convulsion, sitting up, recovery, on-screen death or flatline.

### Oxygen mask and tube

Keep the mask fitted over the same nose/mouth position, with unchanged shape and connection. The one existing dark corrugated tube follows its approved arc and exits toward **viewer-right** for the entire shot.

Optional motion is limited to tiny coupled respiration movement at the mask, extremely subtle tube settling or breathing-consistent vibration. It must never look like an independent animated object. Default: hold the mask and hose stable.

No detachment, sliding, mask deformation, growing/shrinking tube, altered thickness, changing side, extra/missing tube, penetration through skin/clothing, whipping, connector separation or corrugation shimmer.

### Bed, pillow and blanket

Bed/head support and pillow remain fixed. Preserve folds and attachments. Only the blanket immediately affected by shallow breathing may move very slightly; no swelling, aggressive fold changes, pillow drift, morphing furniture, added equipment or removed medical support.

### Staff

Canonical anonymous clinical staff, not relatives/visitors. Default: still. Only tiny breathing/posture settling within the already visible edge fragments may be tolerated. A slight inward head inclination would be permissible only where a head is already visible; **v002 has no complete visible staff heads, so do not reveal or invent one to animate it**.

No walking, talking, dramatic gestures, crying, touching/manipulating Ah Lim, treatment, new staff, named roles, visitor styling, caps or stethoscopes. Staff never become the subject.

### Camera

One continuous, very slight slow push-in, centered on the existing face/mask relationship. It must be barely perceptible and preserve the recognizable composition at the end. No movement toward staff and no new angle.

No pan, tilt, orbit, widening, rapid/aggressive zoom, dramatic rack-focus, camera shake or strong parallax. Keep the whole mask/connector and enough rightward tube and pillow visible; do not crop away the critical medical context. Do not use a camera effect to conceal a motionless subject.

### Environment and style

Preserve LOC_05. Default: static environment and lighting. In the inspected v002, only a small apparatus edge is visible, not a readable monitor screen; do not introduce a screen/waveform or reveal one merely to animate it. Extremely subtle glow variation is allowable only on genuinely visible existing illuminated material and only if nondistracting; no flicker is required.

No flashing emergency lights, moving doors, new people/props, text, visual alarms, changed room geometry, daylight shift, lighting drama or FX.

Keep clean simple 2D cartoon line art, black outlines, restrained flat colors, minimal shading and low-detail comic feeling. No photorealism, glossy 3D, painterly/anime redesign, excessive motion blur, temporal line shimmer, texture drift or pulsing shadows.

## 5. Audio and future test boundaries

The visual pilot must be **silent**. No generated/invented dialogue, lip-sync, breathing sounds, monitor beeps, music or hospital ambience. The shot list's dialogue and UNKNOWN speaker remain untouched; neither is an instruction to synthesize audio here. If a future tool offers audio controls, request audio off and verify the returned clip is actually silent.

This brief prepares a meaningful true image-to-video benchmark, such as a future Seedance/Kling test, not a generation run or a commitment to a specific provider. The selection priority is:

**identity consistency > medical-prop stability > composition preservation > subtle motion quality > visual spectacle.**

Use the same locked keyframe and motion constraints for any later authorized comparison. Record actual model/version, settings, duration, starting-image hash and any supported-reference inputs then. No batch tests or queue advancement are authorized here.

## 6. Future generation direction

The following is a model-neutral motion description, to be used only in a later authorized generation task with v002 as the actual image input:

> Animate the supplied approved SHOT_001 keyframe_v002 without reconstructing it. Preserve this exact close-up of elderly Ah Lim, over 90, critically weak in a hospital bed. His gaunt face, sparse gray-white hair, heavy closed eyelids, thin neck, pale blue gown, oxygen mask, pillow and rightward breathing tube remain the same throughout. His eyes stay closed/heavy and his mouth and head remain still. Only extremely shallow, slow upper-chest breathing beneath the gown gives this almost motionless figure a faint sense of life. Any related mask or tubing motion is tiny and mechanically stable; holding these props still is preferred to deformation. The camera makes only a very slight slow push-in toward his face and mask. Staff remain anonymous, almost still fragments at the edges. The bed, pillow, hospital geometry, restrained lighting and clean simple 2D outlines/flat colors stay stable. Maintain the same critical exhaustion and breathing dependence from first frame to last: no waking, recovery, acting, emergency or death. No widening, new objects, text, audio, style change or dramatic motion. The scene should feel gently alive, not like a still-image zoom.

All limits in sections 3–5 remain binding even if a future interface requires a shorter prompt.

## 7. Human video review checklist

No clip has been generated; every item below is **NOT TESTED**, not an approval. Review at normal speed for emotion/motion and scrub first/middle/last plus any unstable frames against v002. Compensate mentally for the tiny push-in when comparing geometry. Check that chest motion occurs relative to a stable pillow/bed rather than all pixels merely enlarging.

1. Elderly Ah Lim identity remains stable.
2. Age stays 90+; no younger or fuller facial features.
3. Face geometry, ears, hairline, wrinkles and eyebrows stay stable.
4. Oxygen mask remains fitted with stable shape/placement/connector.
5. One breathing tube keeps its shape, attachment and viewer-right exit.
6. Extremely shallow slow breathing is readable, without heaving or stopping as a death cue.
7. Critical-condition emotional read persists without dialogue.
8. No accidental waking, opening eyes or alert expression.
9. No dramatic acting, speech, cough, gasp, recovery or death.
10. Staff remain secondary cropped edge context.
11. Staff identity, clinical clothing and 2D style stay stable.
12. Bed/head support, pillow and blanket geometry remain coherent.
13. LOC_05 hospital continuity remains intact.
14. Approved close-up composition is preserved; no v001 group framing.
15. Camera uses a very slight slow push-in only.
16. No new characters, props, text or medical equipment.
17. No temporal style drift, line shimmer or texture changes.
18. No obvious AI morphing, intersecting tube, detached mask or warped anatomy.
19. Final frame still reads unmistakably as approved SHOT_001.
20. Scene feels gently alive through localized breathing, not just a static zoom.

Also verify silence, recorded duration and undistorted approved composition. Any identity drift, mask/tube failure, waking/death cue, widened frame or invented content is a correction/rejection issue, regardless of attractive motion. A zoom-only result fails the intended model benchmark. Human approval of v002 does not automatically approve any video.

## 8. Pass condition and stop

Without dialogue or audio, throughout the clip the viewer must read:

"An extremely frail elderly Ah Lim is critically ill and barely breathing with oxygen support."

It must not read as peaceful sleep, recovery, emergency action, active conversation or death already completed.

This task creates only this motion/video brief and briefly updates PROJECT_STATE.md. No video, new keyframe, asset edit, preflight modification or other-shot work. V002 remains HUMAN-APPROVED and LOCKED; v001 remains rejected history. Stop here. Future clip generation and its human review require a separate task.

