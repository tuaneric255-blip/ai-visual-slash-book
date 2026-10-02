# TEST ASSET NAMING STANDARD

Directory:
tests/<category>/<slash_id>_<slash>/

Files:
- test-plan.md
- control/control_r01.png
- isolated/test_r01.png
- isolated/test_r02.png
- compatibility/<combo>_r01.png
- production/production_r01.png
- failures/failure_r01.png
- review.md

Never overwrite test assets. Every run gets a unique run number.

Metadata must preserve:
slash_id, prompt, platform, model/version if available, generation date, benchmark_id, run number, seed if platform exposes it, source/reference asset, human reviewer.

Image editing after generation:
Do not retouch an evidence image in ways that change the tested visual variable. Layout/caption copies must point back to untouched evidence originals.
