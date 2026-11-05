# Design Changelog — El Matador

Version history for the 150 g combat robot chassis, designed in Autodesk Fusion 360.

## V4 — NiMH battery configuration

**CAD:** `CAD/V4/Matador V3 NiMH.f3d`  
**Based on:** V3

### Changed
- Adapted the **bottom chassis** central battery compartment and surrounding  walls to accommodate a NiMH battery rather than the original LiPo battery.
- Retained everything else from V3

### Unchanged / reused
- **V3 top chassis**, reused without modification.
- Intended mounting, drivetrain, motor and electronics positions, and assembly interfaces.
- Design wall thickness goals of 2 mm externally and at least 1.2 mm internally.

### Manufacturing preparation
- Selected the V3 top and V4 bottom as the print pair.
- Prepared separate STL files for the University of Bristol Rapid Prototyping Service.
- Requested ABS FDM printing with lightweight settings (0.20 mm layer height, 2 perimeters, 10% infill).
- Estimated combined chassis mass from an earlier Bambu Studio setup: **91.64 g**.

## V3 — LiPo chassis and dimensional reduction

**CAD:** `CAD/V3/Matador V3 LiPo.f3z`

- Reduced chassis dimensions to address the V2 mass problem.
- Established an approximately **250 mm wide** chassis.
- Packaged the original LiPo battery along with drivetrain and electronic components.
- Reached the intended chassis, electronics, and drive train weight in slicing estimates (143.7g).

## V2 — Weight-reduction iteration

**CAD:** `CAD/V2/`

- Introduced pockets on the bottom chassis to reduce mass.
- Added ribs to maintain support around lightened areas.
- Improved on the V1 geometry but remained too heavy for the design target.

## V1 — Initial concept

**CAD:** `CAD/V1/`

- Created the first chassis geometry and initial electronics packaging.
- The initial CAD concept did **not include motors and wheels**.


**Project lead:** Matthew Wang  
**Updated:** 2026-11-05
