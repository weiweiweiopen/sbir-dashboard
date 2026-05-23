# Research Landscape

## Technical clusters

| Cluster | What exists | Strategic implication |
|---|---|---|
| Material PUF | random microstructure, optical scattering, material tags | supports scientific plausibility; weakens broad novelty |
| Solar / energy-harvesting PUF | using photovoltaic or energy-harvesting components as entropy source | makes "solar PUF" crowded; DSSC specificity matters |
| Optoelectronic / perovskite PUF | self-powered photonic/optoelectronic identity primitives | close conceptual neighbor; differentiate via DSSC chemistry and patterning |
| Transparent photodetectors / light-field | transparent sensors and light-field reconstruction | useful for future interface; risky as core patent path |
| Micro-lens / optical enhancement | MLA and optical structures improve solar performance | keep as implementation optimization |
| IoT blockchain security | device trust anchors, keys, distributed logs | use only as audit infrastructure |

## Required experimental evidence

| Evidence | Purpose | Suggested output |
|---|---|---|
| repeated I-V curves per sample | intra-device stability | CSV + plotted curves |
| multiple samples under same condition | inter-device separability | distance matrix / confusion matrix |
| multiple illumination states | robustness | pass/fail table by condition |
| feature-vector definition | reproducible analysis | notebook or script |
| registration / verification demo | system story | panel template + verification result |
| event log schema | administrative value | JSON/CSV event signature |

## Baseline metrics to define

- intra-device distance distribution;
- inter-device distance distribution;
- equal error rate or operating threshold;
- verification success rate by illumination condition;
- degradation / drift after repeated measurement;
- false accept / false reject in POC language.

## Suggested LLM tasks

- generate literature query expansions;
- convert papers into claim-pressure notes;
- draft experiment protocols;
- produce FTO question lists for counsel;
- maintain table of known prior art and boundary language.
