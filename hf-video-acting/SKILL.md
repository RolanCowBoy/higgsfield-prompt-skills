---
name: hf-video-acting
description: "Write Higgsfield prompts for a readable single-shot character performance: intention, reaction, partner interaction, comic beat, or emotional turn. Use when animating an established character or directing acting in a short video; keep physical stunt choreography and multi-shot editing distinct from the performance brief."
---

# Higgsfield acting in one shot

Read [the shared contract](references/prompt-core.md). For a psychologically complex or comic beat, read [performance patterns](references/performance-patterns.md).

## Separate directing intent from the generation text
Extract the event, what the character wants, what prevents it, whom/what the action addresses, and what changes by the end.
Use internal biography only to choose behavior. Do not send pages of motivation that cannot appear on screen.
Choose the acting register the user wants: restrained, stylized, grotesque, theatrical, or another supplied register. Task-based acting does not require suppressing expression, comedy, or broad animation.

When the objective is already clear, proceed without a questionnaire. If the request is only an adjective, propose a concrete behavior that expresses it and state the assumption briefly.

## Find the visible performance
Translate objective → tactic toward partner/object → response → next tactic or endpoint.
Choose a few readable action beats for the duration. “Two to four” is a starting heuristic, not a model limit or required count.
Use gaze targets, handling of a prop, spatial distance, hesitation, concealment, or a change in tempo to carry intent. Add facial cues where they contribute. Distinguish eye direction from head rotation and body position.
For a stillness accent, preserve breathing and world motion unless a true freeze is requested. Do not demand both an unchanging gaze and multiple gaze targets in the same interval.

## Stage what the audience must see
Define the first frame: who is present, stance/seat, prop ownership, partner location, gaze target and camera placement. Establish the last frame and any changed prop or costume state.
Verify that the decisive gesture or expression is visible at the moment it matters. Do not rely on a face hidden behind the character, outside a mirror, too small in frame, or behind opaque glass.
For mirrors, distinguish camera view, reflected view and the characters' viewing paths. If mutual visibility cannot be confirmed from the input, avoid asserting it; choose an intelligible staging or request the layout when it is essential.
Specify camera behavior independently from acting. Keep it simple enough to read the event, but preserve requested movement and style.
For a short hold or a minimal reaction, do not invent a narrative arc with excessive gestures.

## Assemble the prompt
Use only needed sections:
- scene event and acting register;
- reference roles and identity anchors;
- first frame/blocking and eyelines;
- camera/framing;
- ordered visible beats, approximate timing if useful;
- secondary motion and contacts;
- lighting/style and audio;
- endpoint and a few critical constraints.

Preserve approved design and render layers. Make lighting support readability without moving magically with the face. A hand gripping an object, planted feet, and costume follow-through should have believable contact and delay.

If the user requires too many events in a fixed duration, preserve their hard constraints explicitly: offer a compressed single-shot version or a longer/segmented alternative, and state what each changes. Do not insert cuts into an explicitly unbroken take or silently enlarge duration.

## Deliver and assess
Return the ready prompt with only necessary settings/reference notes and a few observable checks. For complex tasks, add a short Russian directing explanation without embedding it all in the prompt.
If asked to generate, follow actual available Higgsfield capabilities and authorization; otherwise stop at the prompt.
Assess identity, readable intention, event order, eyelines, visibility, physical contacts, and final state on supplied outputs. Text quality alone is not proof of convincing acting.
