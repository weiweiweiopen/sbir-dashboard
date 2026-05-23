# IP Landscape

## Patent / patent-publication clusters

| ID | Publication | Owner / applicant | Cluster | Relevance | Risk | Defensive boundary |
|---|---|---|---|---|---|---|
| P1 | US20190188875A1 / US10546382B2 | NRI R&D Patent Licensing LLC | lensless / light-field imaging | adjacent if the project later uses light-field or lensless readout | Medium | Phase 1 core should remain DSSC material identity and I-V measurement, not imaging-system claims |
| P2 | US20210036874A1 / US11206146B2 | University of Kentucky Research Foundation | PUF response architecture | converts physical device differences into PUF response | Medium | avoid generic device-pair, summation-value, or broad PUF response architecture language |
| P3 | US20250167996A1 | TTP PLC | optical PUF | optical fibres / optical response as PUF | Medium | do not frame DSSC as optical-fibre PUF; optical features are auxiliary unless separately cleared |
| P4 | WO2018126029A2 | Intel Corp | blockchain securing IoT devices | external trust, keys, blockchain, IoT device security | Low–Medium | blockchain only stores event hash / identity anchor; material authenticity comes from DSSC measurement |

## Literature / publication clusters that affect novelty

| Cluster | Baseline references | Impact on strategy |
|---|---|---|
| Optical active material PUF | DOI: 10.1002/adma.202502059 | material microstructure PUF is plausible but broad novelty is crowded |
| Energy harvesting / solar PUF | DOI: 10.13023/ETD.2021.019 | solar/energy-harvesting PUF exists; DSSC pattern + I-V workflow must carry novelty |
| Self-powered optoelectronic PUF | DOI: 10.1021/acsaelm.5c01870 | self-powered optoelectronic PUF is close; avoid claiming that category as new |
| Transparent photodetectors / light-field | DOI: 10.1038/s41566-019-0567-3 | relevant to transparent/light-field narrative but not core PUF claim |
| Micro-lens / photovoltaic enhancement | DOI: 10.3390/coatings12121812 and related | efficiency enhancement is auxiliary, not the invention center |

## White-space hypothesis

The likely white space is not a single component. It is the **system combination**:

- patterned DSSC as entropy-bearing photovoltaic material;
- controlled I-V curve identity reconstruction;
- stable verification across illumination variation;
- event signature data model;
- optional public/private ledger anchoring.

## Claim chart skeleton

| Claim element | Prior-art pressure | How to narrow |
|---|---|---|
| PUF from physical variation | high | restrict to patterned DSSC photovoltaic material and defined readout |
| Optical readout | medium-high | make optional or auxiliary; avoid fibre/lensless structures |
| Solar / self-powered PUF | high | emphasize DSSC chemistry, patterning, I-V features, event logging |
| Blockchain identity | high | claim hash anchoring of material event, not generic trust engine |
| Energy certificate | regulatory risk | state audit log only, not statutory certificate |

## Formal FTO next step

Patent counsel should run:

1. exact claim chart against P1–P4;
2. updated keyword search across Google Patents, Lens, Espacenet, WIPO, TIPO;
3. CPC/IPC search around H04L9/32, G06F security, H01G/H01L photovoltaic devices, G01R measurement;
4. assignee search: universities, Intel, TTP, solar-cell security groups.
