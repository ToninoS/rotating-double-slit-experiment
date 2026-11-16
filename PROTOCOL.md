# Experimental protocol — co-rotating double slit

**Concept proposer: Tonino Schäfer | 16 November 2026**

## Aim

Determine whether calibrated interference-fringe visibility, expressed in the optical apparatus's own reference frame, changes during controlled **whole-rig rotation** beyond expected optical, mechanical, inertial and imaging effects. This preliminary laser experiment cannot independently test quantum wavefunction collapse.

## Equipment and calibration

- Fully enclosed, balanced and guarded rotation stage with documented laser safety review; **no exposed moving beam**.
- Rigidly mounted source, precision double-slit mask, fixed observation plane and camera; use optical fiducials to identify small relative movement.
- Fixed-focus calibrated global-shutter camera, linear/raw imaging, fixed gain/exposure and synchronization to stage motion.
- Angular position, speed and acceleration metrology, vibration sensing, and temperature/light-power monitoring.
- Measured slit separation/width, optical wavelength, source stability, detector resolution and geometry.

## Preliminary test matrix

| Arm | Treatment | Rationale |
| --- | --- | --- |
| A | Stationary, motor off | Baseline |
| B | Stationary, motor powered | Electrical and thermal sham |
| C | Low-speed clockwise rotation | Motion test |
| D | Low-speed counterclockwise | Directionality test |
| E | Higher-speed rotation, both ways | Exploratory speed dependence |
| F | Known vibration without average rotation | Positive artifact control |
| G | Stationary at corresponding rig orientations | Gravity/flexure/orientation control |
| H | Controlled rigid translation, if feasible | Distinguish translation and rotation |

Interleave controls with randomized test blocks. Select speeds, exposures, number of replicates and exclusion rules using a pilot, then freeze the confirmatory protocol before final acquisition.

## Record for each run

Raw frames, acquisition timestamps, exposure/gain and calibration; angular motion and vibration; slit geometry and optical conditions; fiducial displacements; temperature/laser stability; fitted fringe contrast, pitch and phase; fit uncertainty and saturation statistics.

## Analysis

Pre-register the image region and fit model, including single-slit envelope and background. Determine fringe visibility **V = (Imax − Imin)/(Imax + Imin)** or an equivalent calibrated amplitude metric. Estimate a within-block moving-versus-static contrast with uncertainties that include temporal correlation and multiple testing. Distinguish loss of contrast from a displaced pattern averaged over exposure. Release raw data and code; report all negative and inconclusive findings.

## Threats to validity

Motion blur, camera readout, vibration, optical bending, air movement, laser drift, polarization changes, slight mutual displacement of components and known inertial interference effects can mimic or cause changes. A replicated residual after controlling for these merits attention, but does **not** uniquely support physical wakes. A subsequent single-photon experiment would require a new design and quantitative alternative hypothesis.

## Research safety

The original rope-swing illustration is **historical only**. Use a qualified optical and mechanical lab, beam enclosure, retention, guarding and interlocks.

## Collaboration

Researchers are invited to propose improved optical simulations, control designs, preregistration and independent replication. Contact the originator through the repository's Issues facility.
