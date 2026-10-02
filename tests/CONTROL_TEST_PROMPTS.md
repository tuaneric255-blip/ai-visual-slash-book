# CONTROL / TEST PROMPT PAIRS — CALIBRATION

These pairs are execution templates. Replace {{REFERENCE}} with the approved benchmark reference instruction.

## C002 /lowangle — B01
CONTROL:
{{REFERENCE}}
Photorealistic full-body studio photograph of the adult benchmark subject in the locked benchmark wardrobe and environment. Neutral relaxed standing posture, head through shoes visible, neutral eye-level straight-on camera, even neutral illumination. Preserve all benchmark locks.

TEST:
Use the exact CONTROL text above, but remove the explicit phrase "eye-level" so the control does not conflict, then append on a new line:
`/lowangle`

## L007 /rembrandt — B01
CONTROL:
{{REFERENCE}}
Photorealistic chest-up portrait of the adult benchmark subject. Neutral straight-on pose, plain studio background, balanced neutral portrait illumination without a named lighting pattern. Preserve identity, pose, wardrobe, background and framing.

TEST:
Exact CONTROL +
`/rembrandt`

## O005 /leadinglines — B12
CONTROL:
{{REFERENCE}}
Photorealistic urban street scene using the locked benchmark street and subject. Neutral composition with no named compositional technique. Preserve subject, wardrobe, scene and daylight baseline.

TEST:
Exact CONTROL +
`/leadinglines`

## P001 /contrapposto — B01
CONTROL:
{{REFERENCE}}
Photorealistic full-body image of the adult benchmark subject standing naturally in a neutral balanced stance, arms relaxed, feet fully visible. Preserve camera, wardrobe, background and lighting.

TEST:
Use the benchmark identity/wardrobe/camera/background/light locks and a neutral full-body framing. Append:
`/contrapposto`

## R005 /explodedview — B08
CONTROL:
{{REFERENCE}}
Neutral technical product presentation of the benchmark object in its normal assembled state. Plain background, even light, no cutaway, no component separation, no callouts.

TEST:
Exact CONTROL +
`/explodedview`

## Method note
Where the control text itself would semantically contradict the tested slash (e.g. "eye-level" vs /lowangle, "neutral balanced stance" vs /contrapposto), remove only the conflicting control phrase while keeping all other variables locked. Record that change in the test plan.
