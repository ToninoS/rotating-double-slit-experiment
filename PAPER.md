# A Co-Rotating Young Double-Slit Apparatus for Testing Motion-Dependent Interference Visibility

*Experimental proposal, alternative physical-wake conjecture, and invitation to collaborate*

**Tonino Schäfer | Independent proposer | 16 November 2026**

**Status:** Unreviewed research proposal. No experimental results, discovery, independent replication or peer review are claimed.

## Abstract

A co-rotating optical apparatus is proposed in which the illumination source, Young double-slit mask, detection plane and camera form a single rigid assembly that is rotated or translated while preserving their nominal mutual geometry. The primary outcome is interference-fringe visibility during motion compared with matched stationary controls. The motivation is a speculative physical-wake conjecture: an underlying disturbance, trace, or substrate response associated with propagating particles might be susceptible to mechanical motion independently of which-path readout. This initial optical experiment is not a measurement of wavefunction collapse and cannot, on its own, establish a microscopic quantum mechanism. This paper sets out the apparatus, observable, controls, interpretations and a route toward a later single-particle experiment.

## Archived record

A corresponding Zenodo record was provided by the author: https://zenodo.org/records/24275576 . For an authoritative publication citation or DOI, check the Zenodo record metadata directly. This GitHub manuscript is editable and may change independently of the archived PDFs.

## 1. Origins and research question

The experiment is attributed to Tonino Schäfer, whose recovered conversation-history notes describe the complete co-moving apparatus and related physical-wake conjecture on 7 November 2025. A separate, speculative discrete-spatial-substrate idea is associated with 1 November 2024. **These earlier dates remain provisional until checked against the original conversation export; they do not establish public publication or historical scientific priority.**

The immediate question is: after accounting for established optical, inertial and mechanical effects, does rigid-body motion of a source–slits–screen–camera assembly produce a reproducible change in interference-fringe visibility?

## 2. The speculative conjecture and standard explanations

The proposer conjectures that propagating particles might create minute physical wakes or traces in an underlying spatial structure. Interaction of these disturbances might be associated with interference; a measurement interaction might disturb them; and motion of the complete apparatus might perturb them without measuring which path a particle takes.

**This is not yet a quantitative alternative physical theory.** No governing equations, coupling parameter, preferred frame, threshold, or predicted effect size have been established.

Conventional optics describes interference by coherent field propagation. A moving setup may change measured visibility through finite exposure, misalignment, frame flexure, vibrations, changes in coherence, air motion, polarization, detector effects and known motion-dependent phase effects. A rotating apparatus must be compared with a full, apparatus-specific conventional prediction, not with an assumption that rotation could never matter.

## 3. Apparatus design

The source, slit mask, screen and camera are all fixed in one common moving frame. **The entire apparatus moves together**, rather than merely rotating the slit plate with respect to a stationary source or camera.

The proposer's informal 2025 illustration involved a roughly 1-metre metal conduit, laser, slits scratched into black-coated glass, a screen roughly 10 centimetres beyond the slits, and a co-mounted GoPro, potentially swung as one assembly. These dimensions preserve the history of the concept; they are **not validated optical tolerances or an endorsed safe build**.

For an actual experiment, use an enclosed and mechanically guarded, balanced rotation stage, precision slits, synchronized motion sensors, a calibrated global-shutter imager, and a contained laser beam path assessed for laser and rotation safety. Do not operate an exposed laser on a rope-suspended moving rig.

## 4. Observable

Measure interference contrast in the moving apparatus's own image coordinates. A conventional definition is

**V = (I_max − I_min) / (I_max + I_min)**,

where the intensities are consistently estimated, ideally from an interference-profile fit accounting for the diffraction envelope, sensor response and background. In simple paraxial geometry, approximate fringe pitch is **Δx = λL/d**, for wavelength λ, slit-to-screen distance L, and slit spacing d. For illustration, 650 nm light, L = 0.10 m, d = 0.10 mm produce approximately 0.65 mm fringe spacing. This does not establish that a proposed camera and screen can resolve it adequately.

Distinguish **visibility loss**, **phase shifts**, **fringe displacement**, **pitch changes**, and **image blur**. They have different explanations.

## 5. Candidate test outcomes

| Condition | Conventional account | Physical-wake conjecture (currently unquantified) |
| --- | --- | --- |
| Stationary, aligned | Reproducible fringes if coherent | Fringes expected |
| Motion at measured speed | Changes to be explained by optical/inertial/instrument model | Possible additional suppression, magnitude unspecified |
| Clockwise versus counterclockwise | Can reveal phase or geometric asymmetries | Direction dependence possible but not predicted quantitatively |
| Vibration without mean rotation | May smear or reduce contrast | Not a unique wake signature |
| Single-particle extension | Requires quantum-mechanical predictions and distinguishability analysis | Potentially discriminatory only with a quantitative alternative model |

A lower measured contrast is **not proof** of particle wakes or wavefunction collapse. A replicable residual after excluding known mechanisms could justify further investigation. A null result can establish sensitivity bounds, but without a quantitative wake model cannot rule out every conceivable mechanism.

## 6. Staged experiment

**Phase A — Static baseline.** Calibrate wavelength, source coherence and stability, slit geometry, distance, focus, exposure, detector linearity, thermal drift and baseline fringe visibility.

**Phase B — Sham and positive artifact controls.** Energize the motor without rotation; introduce calibrated vibration/image smear to validate the analysis pipeline.

**Phase C — Controlled motion.** Randomize and interleave stationary recordings with both rotation directions and multiple measured angular speeds/accelerations. Collect synchronized motion, vibration, camera, and optical-fiducial data.

**Phase D — Model and compare.** Fit fringe visibility and phase; quantify exposure blur, alignment changes, flexure, air effects and known inertial contributions; propagate uncertainties and compare residuals with a pre-registered criterion.

**Phase E — Replicate and extend.** Release raw data, calibration and analysis code. Independently reproduce any finding on another rig. Consider a genuine single-photon or matter-wave follow-up only after its scientific interpretation and instrumentation are designed.

See [PROTOCOL.md](PROTOCOL.md) for a proposed experimental matrix and data requirements.

## 7. Interpretation and falsifiability

Before confirmatory data collection, select a principal endpoint, analysis region, velocity schedule, exclusion rules, uncertainty model and minimum relevant effect. Analyze all trial blocks, including null results. A reproducible unexplained motion-associated optical residual is not in itself confirmation of a specific underlying medium. To test the physical-wake account against established physics more directly, its advocates would need to derive testable quantitative predictions that differ from conventional optics or quantum theory.

## 8. Relationship to prior work

Rotation-sensitive interference predates this proposal. Relevant topics include the Sagnac effect, quantum/inertial phase effects, moving-slit experiments and Sagnac-assisted double-slit setups. It has **not been established** that a complete co-rotating Young apparatus is unprecedented. The distinct contribution documented here is the proposer's concrete co-moving apparatus proposal and its conjectured physical-wake motivation, offered for rigorous evaluation.

## 9. Collaboration and credit

Tonino Schäfer is credited as the concept proposer and wishes to participate in an appropriately designed investigation. Experimentalists, theoretical physicists and image-analysis specialists are invited to critique, model, refine or perform the test, including reporting negative results. Future coauthorship and other contributions should be determined fairly by research contributions and journal standards. Cite this proposal when building on it.

## Selected references

1. B.-G. Englert (1996), “Fringe Visibility and Which-Way Information: An Inequality,” *Physical Review Letters* 77, 2154–2157. https://doi.org/10.1103/PhysRevLett.77.2154
2. P. Liu et al. (2023), “Double-slit interference experimental platform based on a Sagnac interferometer,” *Applied Optics* 62, 4524–4529. https://doi.org/10.1364/AO.492342
3. J. Anandan (1977), “Gravitational and rotational effects in quantum interference,” *Physical Review D* 15, 1448. https://doi.org/10.1103/PhysRevD.15.1448
4. “Curved, expanded and inclined patterns of dynamic double slit/cross-double slit/grating experiments,” *IET*, DOI https://doi.org/10.1049/tje2.12101
5. S. M. Barnett (2022), “On single-photon and classical interference,” *Physica Scripta* 97, 114004. https://doi.org/10.1088/1402-4896/ac971a

**Publication integrity:** This is an unreviewed proposal prepared on 16 November 2026. The GitHub commit provides a public timestamp for this version only. An archival DOI and authenticated older transcripts have not yet been supplied.
