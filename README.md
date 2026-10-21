# Metabolism under pressure

Four browser based drylab pages scaffold early biomedical science teaching:

1. **Fuel pathways** (`docs/stage1.html`) — carbohydrates, lipids and ketone bodies; the overall ideas of glycolysis, β oxidation and ketolysis.
2. **TCA wheel** (`docs/tca.html`) — visual carbon entry, carbon dioxide release and NADH energy carriers.
3. **Mitochondrial membrane** (`docs/mitochondria.html`) — complexes I to IV, NADH and succinate entry, oxygen, proton pumping and ATP synthase.
4. **Integrated model** (`docs/index.html`) — Stage 1 dashboard linking the pathways with adjustable substrate, oxygen, lactate and succinate conditions.

## Dashboard

[Open the live Stage 1 dashboard](https://julio0029.github.io/biomed-metabolism-drylab/)

## Teaching purpose

The sequence supports explanation and prediction: how fuels converge on mitochondria, why carbon dioxide is released, how NADH and succinate feed the respiratory chain, what happens to ATP production when oxygen falls, and why succinate can contribute to reactive oxygen species during early reperfusion.

It is deliberately a **conceptual, qualitative model**, not a clinical tool or a quantitative simulation of a cell, organ, or patient. The readouts show directional relationships derived from core lecture concepts. They should be discussed alongside the assumptions and limitations stated on the page.

## Use

Open the published page and move the sliders, or use a starting scenario. Students can record a prediction before changing a variable, then explain the observed direction of change using the pathway diagram.

The linked [case challenge](docs/challenge.html) asks students to calculate glucose from an absorbance standard curve, select the necessary metabolic assays, calculate the same modelled ATP output, and assign a teaching phenotype.

## Local preview

Open `docs/index.html` in a modern browser. No build step or external dependency is required.

## Deployment

GitHub Pages is served from the `docs/` directory on the `main` branch.
