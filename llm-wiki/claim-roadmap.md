# Claim Roadmap

## Candidate independent claim families

### A. Device / material article

A patterned dye-sensitized solar cell structure configured so fabrication variation in the photosensitive layer contributes to a measurable identity signature.

Narrowing features:

- patterned DSSC photosensitive layer;
- TiO₂ porous layer / dye adsorption / electrolyte / electrode interface as entropy contributors;
- transparent or semi-transparent substrate optional;
- no requirement to claim all photovoltaic devices.

### B. Measurement / verification method

A method for registering and verifying a DSSC device by acquiring I-V curves under defined illumination conditions, extracting features, and comparing against a registered template.

Narrowing features:

- controlled illumination profile;
- I-V sweep protocol;
- feature vector;
- threshold / classifier;
- multi-condition stability check.

### C. Material event signature system

A system that records panel ID, measurement condition, extracted feature digest, timestamp, and optional external anchor.

Narrowing features:

- event signature is derived from measured material response;
- ledger stores hash / anchor, not material truth itself;
- regulatory energy certificate not claimed.

## Dependent claim candidates

- use of specific I-V features: Voc, Isc, FF, Vmpp, Impp, Rs, Rsh;
- repeatability under multiple illumination intensities or spectra;
- drift compensation / normalization;
- threshold update or model versioning;
- transparent device mounting;
- optional optical image / pattern signal as secondary feature;
- optional ledger / distributed timestamp anchor.

## Avoid in first filing unless counsel clears

- generic light-field camera claims;
- generic optical scattering PUF claims;
- generic blockchain trust-engine claims;
- broad self-powered PUF claims across all photovoltaic materials.
