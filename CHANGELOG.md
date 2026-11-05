# Design Changelog — El Matador

Version history for the 150 g combat robot chassis, designed in Autodesk Fusion 360.

> This documents design iterations and print preparation, not completed physical testing.

## V4 — NiMH battery configuration

**CAD:** `CAD/V4/Matador V3 NiMH.f3d`  
**Based on:** V3

### Changed
- Adapted the **bottom chassis** central battery compartment and surrounding internal walls to accommodate a NiMH battery rather than the original LiPo battery.
- Retained the established external chassis envelope and intended mechanical interfaces.

### Unchanged / reused
- **V3 top chassis**, reused without modification.
- Intended mounting, drivetrain, motor and electronics positions, and top/bottom assembly interfaces.
- Design wall thickness goals of ~2 mm externally and at least ~1.2 mm internally where possible.

### Manufacturing preparation
- Selected the V3 top and V4 bottom as the intended print pair.
- Prepared separate STL files for the University of Bristol Rapid Prototyping Service.
- Requested ABS FDM printing with lightweight settings (preferred: 0.20 mm layer height, 2 perimeters, 10% infill; subject to printer capability).
- Estimated combined chassis mass from an earlier Bambu Studio setup: **91.64 g**; this is **not** a measured printed mass.

**Status:** Prepared for fabrication; physical fit, fastening alignment, weight and strength remain to be tested.

## V3 — LiPo chassis and dimensional reduction

**CAD:** `CAD/V3/Matador V3 LiPo.f3z`

- Reduced chassis dimensions, including overall length, to address the V2 mass problem.
- Established an approximately **250 mm wide** chassis arrangement.
- Packaged the original LiPo battery along with drivetrain and electronic components.
- Reached the intended chassis weight in CAD/slicing estimates, before physical validation.
- Became the reference geometry for V4; the V3 top is reused in the current build.

## V2 — Weight-reduction iteration

**CAD:** `CAD/V2/`

- Introduced material-removal pockets to reduce mass.
- Added ribs/reinforcing features to maintain support around lightened areas.
- Improved on the V1 geometry but remained too heavy for the intended design target.

## V1 — Initial concept

**CAD:** `CAD/V1/`

- Created the first chassis geometry and initial electronics packaging.
- The initial CAD concept did **not yet include motors and wheels**.
- Served as the basis for later mechanical packaging and mass optimisation.

---

## Current intended build

| Item | Configuration |
| --- | --- |
| Top | V3 (unchanged) |
| Bottom | V4 (NiMH-adapted) |
| Battery | NiMH |
| Chassis width | ~250 mm |
| Preferred print material | ABS |
| Robot mass limit | 150 g total |
| Estimated chassis mass | 91.64 g combined (slicer estimate, not measured) |
| Physical assembly/testing | Pending |

## Verification after printing

- Inspect prints for warping and damaged mounting features.
- Confirm NiMH battery fit and wiring clearance.
- Check V3 top / V4 bottom alignment and fasteners.
- Assemble electronics and drivetrain, then weigh the complete robot.
- Perform controlled mechanical and functional tests; document any design changes.

**Project lead:** Matthew Wang  
**Updated:** 2026-11-05
