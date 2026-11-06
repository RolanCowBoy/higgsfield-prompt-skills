# Image-edit patterns

Authored examples informed by PASSPORT RUSH records 70, 72–75 and 84 and the user's iterative character work. They are instructions to test, not claims of pixel-level control.

## Short local edit
Task: open the forehead and reduce the teeth.
Prompt:
“Edit the supplied base image. Lift the front curls away from the forehead so both eyebrows are visible, retaining the overall messy hair volume. Reduce the two visible front teeth to a more proportionate size. Preserve the character's face identity, pose, clothing, framing, environment and existing rendering style. Allow only the local hair and mouth changes and their necessary shading.”

Avoid adding a new expression or relighting the whole scene unless requested.

## Base scene plus character donor
Bindings:
- BASE: composition, forest, other figure, viewpoint and sketch medium;
- CHARACTER: boy's identity, head/body proportions, hair mass and costume;
- requested change: replace only the seated boy, with the specified new orientation.

Describe pose and gaze relative to an actual target in the base. Translate the donor into the base's linework and shading without retaining glossy CG surfaces. Preserve large identity anchors.
Do not claim the precise scene geometry if the base is missing.

## Selective visual transfer
BASE controls buildings, crane, camera and object positions.
LOOK controls only surface grain, edge treatment, light direction and temperature.

State both inclusion and exclusion:
“Transfer the restrained surface texture and cool high daylight from LOOK. Keep BASE's architecture, silhouettes, camera and objects. Do not import LOOK's buildings or composition.”
Allow shading to change where the relighting requires it. “Keep all shadow pixels unchanged” would defeat the task.

## Object-state change
For a damaged vehicle, keep the same chassis and livery while defining the authorized damage. Replace “make it broken” with the specific altered part, remaining structure and edge treatment.
Do not import people or other objects from a donor whose sole role is damage reference.

## Past version plus new subject
When the user says “return the forest to the earlier sketch, keep the latest boy,” identify the two sources explicitly. The earlier image is authoritative only for environment and composition; the latest boy supplies identity. If the earlier image is unavailable, request that image rather than silently approximate and claim restoration.
