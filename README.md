# Metabolism under pressure

Two browser based drylab demos that scaffold early biomedical science teaching:

- **Stage 1 — Energy Journey** (`docs/stage1.html`): a visual first encounter with food fuel, oxygen, mitochondria and ATP as reusable energy packets. It uses a glucose fuel parcel, pyruvate energy train and fatty acid worm instead of biochemical pathway detail.
- **Stage 2 — Metabolism under pressure** (`docs/index.html`): links glycolysis, beta oxidation, the tricarboxylic acid (TCA) cycle and the mitochondrial electron transport chain, then lets students vary substrate availability, oxygen, lactate and succinate.

## Teaching purpose

The Stage 2 page is designed to prompt explanation and prediction: what happens to ATP production when oxygen falls, why lactate accumulates in hypoxia, and why succinate can contribute to reactive oxygen species during early reperfusion.

It is deliberately a **conceptual, qualitative model**, not a clinical tool or a quantitative simulation of a cell, organ, or patient. The readouts show directional relationships derived from core lecture concepts. They should be discussed alongside the assumptions and limitations stated on the page.

## Use

Open the published page and move the sliders, or use a starting scenario. Students can record a prediction before changing a variable, then explain the observed direction of change using the pathway diagram.

The linked [Stage 2 case challenge](docs/challenge.html) asks students to calculate glucose from an absorbance standard curve, select the necessary metabolic assays, calculate the same modelled ATP output, and assign a teaching phenotype.

## Local preview

Open `docs/index.html` in a modern browser. No build step or external dependency is required.

## Deployment

GitHub Pages is served from the `docs/` directory on the `main` branch.
