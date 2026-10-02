# CALIBRATION RUNBOOK — FIRST FIVE

Do not mark VERIFIED during generation. Generate → log → review.

## Order 1 — C002 /lowangle
Benchmarks: B01, B05, B12.
For each benchmark:
A. generate baseline control;
B. duplicate exact prompt and append only `/lowangle`;
C. repeat actual trials;
D. save all runs;
E. compare camera viewpoint and unintended changes.

## Order 2 — L007 /rembrandt
Benchmarks: B01, B02.
Use portrait framing suitable for observing facial shadows. Control uses neutral portrait light. Test appends only `/rembrandt`.
Review actual lighting pattern, not mood.

## Order 3 — O005 /leadinglines
Benchmarks: B12, then B01 in an environment containing usable structural lines.
Control must not mention lines.
Test appends only `/leadinglines`.
Review whether lines guide attention toward/through subject.

## Order 4 — P001 /contrapposto
Benchmarks: B01, B02.
Full body required, feet visible.
Control = neutral standing pose.
Test appends only `/contrapposto`.
Review weight-bearing leg, relaxed leg, pelvis/shoulder counterbalance and anatomy.

## Order 5 — R005 /explodedview
Benchmark: B08.
Use only a product with known component structure.
Separate two judgments:
1. exploded-view visual semantics;
2. engineering correctness.
A result can pass #1 and fail #2.

## Logging
Every generated asset receives a test_results.csv row. Do not enter scores before inspecting the actual output.
