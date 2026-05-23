# Strategy Map

## Core positioning

Do not position the project as a broad invention of PUF, optical PUF, solar PUF, blockchain IoT, or light-field imaging.

Position it as a combined workflow:

1. **Material entropy** — patterned DSSC photosensitive layer, TiO₂ porous structure, dye adsorption distribution, electrolyte/contact variance, and fabrication micro-variation.
2. **Controlled readout** — I-V curve acquisition under defined illumination and measurement conditions.
3. **Feature extraction** — Voc, Isc, FF, Vmpp, Impp, Rs, Rsh, curve shape descriptors, and stability descriptors.
4. **Identity reconstruction** — panel ID registration, template creation, distance / classifier thresholding.
5. **Event record** — material event signature with timestamp, measurement condition, feature hash, and optional external anchor.

## Strategic moat

| Layer | Why it matters | Evidence needed |
|---|---|---|
| Patterned DSSC entropy | Differentiates from silicon-cell or circuit PUF | process photos, sample set, microscopy if available |
| I-V signature | Converts material variation into machine-readable identity | repeated I-V curves and feature extraction notebook |
| Multi-condition reconstruction | Handles light sensitivity and environmental variation | same sample under multiple light states |
| Event signature | Connects identity to administrative / audit workflow | CSV / JSON schema and demo log |
| External anchor | Adds tamper-evident indexing without overclaiming blockchain | hash examples and verification flow |

## Product language

Use:

- DSSC material identity;
- patterned photovoltaic PUF element;
- I-V signature reconstruction;
- material event signature;
- verification under controlled illumination;
- audit anchor.

Avoid:

- all-purpose blockchain security;
- commercial-grade certification claims;
- claiming all solar cells are PUFs;
- claiming light-field imaging as the core invention;
- implying optical PUF novelty broadly.

## Decision rule

When adding a feature, ask:

> Does this strengthen the DSSC material-identity workflow, or does it drag the project into a crowded generic category?

If the latter, keep it as optional / dependent / future work.
