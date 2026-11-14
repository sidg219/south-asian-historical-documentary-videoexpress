# Realistic Walks Through Ancient & Medieval India — Playbook v1

## 0. Mission

Create a 4–6 minute faceless, narrated documentary about history, society or culture in ancient or medieval India. The finished episode should feel like a guided walk through a place and its past, while making the limits of the evidence visible. The deliverable is a detailed Markdown packet for manual image generation and manual VideoExpress production.

Use a browser-capable video tool for production. The workflow may use present-day footage, generated images, image-to-video clips, maps, object close-ups and narration. Generated scenes are reconstructions, never archival evidence.

## 1. Intake

Collect: topic or title; region and place; date range; central question; intended audience; target length; narration language and accent; aspect ratio; source links/notes; and whether the user has location or object images. Defaults: 4–6 minutes, 16:9, female English narration with a clear Indian English accent, and no on-camera host.

Write a five-line production card:

TITLE · region · period · aspect ratio · target length
Question: ...
Evidence: ...
Visual method: present-day footage + labelled reconstruction
Narrator: off-camera, consistent voice

## 2. Research brief and claim ledger

Build a compact brief with geography, chronology, key people or communities, material culture, surviving evidence and the episode’s unanswered question. Prefer primary sources, archaeological reports, museum or archive records, university publications and reputable scholarship.

For every factual sentence, record: ID | narration claim | source | evidence type | confidence | label | visual implication.

Labels are DOCUMENTED, INTERPRETED or RECONSTRUCTED; follow the definitions in docs/research-and-ethics.md. Do not create the narration until every claim has a source or is explicitly marked as interpretation/reconstruction.

## 3. Narration

Use a single narrator Voice Lock: language + accent + gender presentation if requested + pace + warm/curious/documentary delivery. Keep the voice wording identical in every generated clip. Do not show a speaking face.

Structure: hook with a question or sensory detail; orient the viewer in place and time; introduce the material clue; widen to society, trade, belief or power; acknowledge disagreement or absence of evidence; end by returning to the surviving place or object.

Use short sentences, concrete nouns and cautious verbs. No invented quotations. If quoting a translated primary source, name the source and keep the quotation short enough to verify.

## 4. World Lock

Create one World Lock per period/location and paste it verbatim into every reconstruction prompt. Include landscape, settlement pattern, landmarks, materials, clothing, tools, transport, weather, time of day, light direction, camera side and anachronism exclusions. If the episode moves across centuries, create separate locks and a transition card.

## 5. Scene map

Plan approximately 24–36 scenes for a 4–6 minute episode, normally 8–12 seconds per scene. Each scene has: S## | timecode | narration IDs | evidence label | visual source | camera | sound | on-screen text. A scene may contain 2–3 internal shots for VideoExpress; keep the scene’s visual idea coherent.

Recommended rhythm: present-day establishing view; map/route; surviving object or architecture; reconstructed activity; close material detail; social context; uncertainty card; return to place. Keep faces secondary: backs, profiles, hands, groups and silhouettes support the faceless format.

## 6. Image prompts

For a reconstruction, begin: Photorealistic historical visual reconstruction, clearly not archival footage, documentary restraint, natural skin texture, period-appropriate materials, no text, no logos, no watermark. Then add the verbatim World Lock, scene action, composition and light. Specify no modern signage, plastic, concrete, synthetic fabric, electric lighting or anachronistic tools unless the shot is deliberately present-day.

For present-day footage, identify it as present-day and do not colour-grade it to look historical. For maps and diagrams, use simple, legible labels and verify every place-name and boundary.

Write a complete image prompt for every scene before writing any video prompt. Each prompt must include the scene ID, evidence label, present-day/reconstruction status, World Lock, subject placement, camera, lens or shot size, lighting, period details, continuity anchors, exclusions and aspect ratio. Never write “same as above” in place of the full prompt.

## 7. VideoExpress multishot prompts

After all image prompts, write the VideoExpress prompts in the same scene order. Each clip starts `S## —` and is designed for an image-to-multishot workflow. Use 2–3 shots per prompt, joined by `A hard cut transitions to…`; specify shot size, camera movement, action, continuity, atmosphere and the exact narration line used in that scene. Keep narration short enough for the clip and split long scenes into sequential clips. Add `audio: female narrator speaking English with a clear Indian English accent, warm documentary delivery; natural location sound; no music` unless music is requested. These prompts are for the user to paste into VideoExpress manually.

Never ask the model to show the narrator speaking. For reconstruction clips, include on-screen label: VISUAL RECONSTRUCTION where needed. If an image model invents readable writing, remove it or replace it with a verified graphic in the edit.

## 8. Production and edit

Generate shots in order, keeping the same World Lock, lens language, palette and narrator Voice Lock. Save a clear scene ID with every asset. Assemble in sequence, align narration first, then visuals. Trim only dead air at heads and tails; preserve meaningful pauses. Add captions, evidence labels, map credits, image credits and a final sources card.

Use a restrained sound bed beneath narration only where it does not imply evidence. Keep natural ambiences separate from reconstruction sound and label reconstructed sound design in the production notes.

## 9. Fact-check and safety pass

Before export, verify: every claim has a source or label; dates and place names agree; costumes/tools/materials fit the World Lock; maps do not project modern borders without explanation; reconstructions are labelled; no invented quotation or archival implication remains; captions are readable; narration and visuals do not contradict; credits are complete.

## 10. Markdown episode handoff

Deliver exactly one complete Markdown document using `templates/episode-output.md`: title and production card; research brief; source and claim ledger; full narration; World Locks; scene map; all scene-by-scene image prompts; then all matching VideoExpress multishot prompts; uncertainty notes; credits; and a manual production checklist. The image-prompt section must come before the VideoExpress section. Save the reusable episode packet in the structure described in examples/README.md.

