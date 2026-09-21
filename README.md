# Visual Inspection Station

Automated visual quality control of coated metal parts, running on an
embedded target under a measured cycle-time budget.

## Problem

Visual quality control is still a bottleneck on production lines. A human
operator detects 80–85 % of visible defects on average, and that rate drops
at the end of a shift or at high throughput.

This project builds a complete inspection cell — lighting, acquisition,
processing, decision, physical output — and **measures what it actually
achieves**, rather than assuming it works.

## Target specification

| Requirement | Target |
|---|---|
| Cycle time per part | < 100 ms |
| Measurement unit | millimetres (calibrated), never pixels |
| False reject rate | measured over 100 real passes |
| Hardware | Raspberry Pi, no GPU |

## The parts

100 M10 steel washers, spray-coated matte white. Defects are created
deliberately and under control: scratch through the coating, bending,
edge burr. **Ground truth is controlled — no downloaded dataset.**

## Status

| Phase | Deliverable | State |
|---|---|---|
| 0 | Bench built, repeatability verified | in progress |
| 1 | 200-image dataset, calibration | — |
| 2 | Classical pipeline — V1 | — |
| 3 | Real-time on target — V2 | — |
| 4 | Learned model — V3 | — |
| 5 | Quantised deployment — V4 | — |
| 6 | Validation protocol — V5 | — |

## Results

Empty until measured.

## License

MIT
