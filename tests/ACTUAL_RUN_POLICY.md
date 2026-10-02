# ACTUAL RUN POLICY — STRICT

A generated board/collage that visually *describes* multiple tests is not an actual controlled run.

## A valid run is atomic
One run = one exact prompt execution producing one original output asset.

For an A/B pair:
- Control is generated independently and registered.
- Test is generated independently and registered.
- The test prompt differs only in the intended semantic variable as far as practical.
- A later collage may display them side by side, but the collage is derived evidence, never the original run.

## Invalid as evidence
- A single infographic prompt asking the model to draw “control vs test”.
- A mock dashboard containing invented metadata.
- An image that prints a model name/date/run count that was not captured from the real generation.
- A synthetic “failure example” intentionally illustrated rather than observed.

## Rule
If provenance cannot be reconstructed from an atomic generation, classify the asset as DOCUMENTATION_ILLUSTRATION.
