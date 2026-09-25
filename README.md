# UST2026

## Universal Stasis Theory (UST)
### Two-Scale Hosting Time and Environmental Ascent Clock Theory

**Author:** Sami Samir Ibrahim El-Sayed  
**Researcher / Independent Researcher**  
**ORCID:** 0009-0006-0807-0582

---

## Overview

UST2026 is a research project developing the **Universal Stasis Theory (UST)** and its associated **Two-Scale Hosting Time** and **Environmental Ascent Clock** framework.

The project develops a unified mathematical and computational framework intended to investigate physical dynamics through environmental equilibrium, medium-dependent response, hosting-time scaling, and operational environmental clocks.

The project is organized as a continuous research program rather than as independent papers.

The current integrated closure extends through:

**Parts I–VI**

---

# 1. Universal Stasis Theory (UST)

Universal Stasis Theory investigates the possibility that observed physical dynamics can be described through environmental equilibrium and gradients of the surrounding physical medium.

The central dynamical form used in the framework is:

$$
\mathbf{a}
=
-\frac{K}{S}\nabla M(\mathbf{x})
$$

where:

- $K$ is the Cosmic Equilibrium Constant.
- $S$ represents Structural Resistance.
- $M(\mathbf{x})$ represents the relevant environmental medium field.

The framework investigates how environmental gradients may generate measurable acceleration and organized motion.

The theory is developed without assuming gravitational acceleration as the fundamental mechanism of the proposed UST dynamics.

---

# 2. Unified Environmental Force Framework

A generalized force representation used in the framework is:

$$
m\mathbf{a}
=
k_1
\int_S
P_{\rm env}(\mathbf{x})\mathbf{n}\,dA
-
k_2
\int_S
\boldsymbol{\sigma}_{\rm int}\cdot\mathbf{n}\,dA
$$

with corresponding environmental-field representations including:

$$
\nabla^2 P_{\rm env}
=
-\beta\rho+S_P
$$

and

$$
\partial_t I
+
\mathbf{u}_{\rm env}\cdot\nabla I
=
-\lambda I
+
\kappa\nabla\Phi
$$

The unified form is represented by:

$$
\rho(\mathbf{x})\mathbf{a}(\mathbf{x})
=
-k_1\nabla P_{\rm env}
-k_2\nabla\cdot\boldsymbol{\sigma}_{\rm int}
+
\rho(\mathbf{x})\mathbf{b}_{\rm body}
$$

The constants and environmental parameters are treated as quantities requiring calibration and empirical testing.

---

# 3. Two-Scale Hosting Time

The project introduces an operational concept of **Hosting Time**.

The retained Planck-time scale is:

$$
t_p
=
5.391247\times10^{-44}\ {\rm s}
$$

The host-time transformation is represented by:

$$
T_H(t)
=
t_p
\exp\left(
\frac{R_r t}{t_p}
\right)
$$

Using the retained calibration:

$$
1\ {\rm local\ day}
\longleftrightarrow
1000\ {\rm hosting\ years}
$$

with

$$
t_d=86400\ {\rm s}
$$

the response-rate parameter is:

$$
R_r
=
\frac{t_p}{t_d}
\ln(365250)
\approx
7.99223\times10^{-48}\ {\rm s}
$$

The corresponding characteristic interval is approximately:

$$
\tau_H
=
\frac{t_p}{R_r}
\approx
6745.61\ {\rm s}
\approx
1.8738\ {\rm h}
$$

These quantities are retained as part of the integrated Parts I–VI framework.

---

# 4. Environmental Ascent Clock

A central development of the later parts of UST2026 is the **Environmental Ascent Clock**.

The operational definition of a clock is:

> A clock consists of a carrier, a reference, an environment, an observable process, an initial reference time, a frequency/rate definition, and a continuous counting rule.

Therefore:

$$
\text{Time}\neq\text{Clock}
$$

A clock is an operational physical realization of temporal progression.

For a cyclic observable with phase $\theta$, the cumulative progress is represented by:

$$
U_\phi
=
N_\phi
+
\frac{\theta_\phi}{2\pi}
$$

After phase unwrapping:

$$
U_\phi(t)
=
\frac{
\widetilde{\theta}(t)
-
\widetilde{\theta}(t_0)
}{
2\pi
}
$$

---

# 5. Environmental Calendar

The retained environmental-calendar convention is:

$$
1\ {\rm Ascent\ Year}
=
12\ {\rm months}
\times
30\ {\rm days/month}
\times
100\ {\rm hours/day}
$$

Therefore:

$$
1\ {\rm Ascent\ Year}
=
360\ {\rm days}
=
36\,000\ {\rm hours}
$$

The framework retains the previously established host-time calibration:

$$
1\ {\rm local\ day}
\longleftrightarrow
1000\ {\rm hosting\ years}
$$

---

# 6. Galactic Environmental Clock

The astronomical realization developed in Part V uses:

- **Carrier:** Solar System Barycenter (SSB)
- **Reference:** Galactic Center (GC)
- **Environment:** Milky Way
- **Observable process:** Galactocentric azimuth

The proposed operational identity is:

$$
\mathrm{GalClock}
=
(
SSB,
E_{\rm MW},
GC,
P_{\rm azimuth},
t_0,
F,
D,
A
)
$$

The wrapped Galactocentric phase is:

$$
\Theta_G
=
\operatorname{atan2}(y,x)
$$

The continuous clock coordinate is:

$$
U_G(t)
=
\frac{
\widetilde{\Theta}_G(t)
-
\widetilde{\Theta}_G(t_0)
}{
2\pi
}
$$

The instantaneous angular rate is:

$$
\Omega_G
=
\frac{xv_y-yv_x}{x^2+y^2}
$$

Therefore:

$$
\frac{dU_G}{dt}
=
\frac{\Omega_G}{2\pi}
$$

For an approximately constant angular rate:

$$
P_G
=
\frac{2\pi}{|\Omega_G|}
$$

This construction does not claim that a complete Galactic revolution has already been directly observed within the modern observational interval.

---

# 7. Sampling-Safe Phase Unwrapping

Because the observed phase is wrapped into the interval $(-\pi,\pi]$, phase unwrapping requires an explicit sampling condition.

The wrapped phase difference is:

$$
\delta_i^{\rm wrap}
=
\operatorname{atan2}
\left(
\sin\delta_i,
\cos\delta_i
\right)
$$

For a conservative maximum angular rate $\Omega_{\max}$, an interval is accepted only when:

$$
\Omega_{\max}\Delta t_i+\mu<\pi
$$

With uncertainty:

$$
\Omega_{\max}\Delta t_i
+
k\Sigma_{\Delta\theta_i}
+
\mu
<
\pi
$$

The branch-clearance condition is:

$$
C_i
=
\pi
-
\left|
\delta_i^{\rm wrap}
\right|
$$

and the interval must satisfy:

$$
C_i
>
\mu
+
k\Sigma_{\Delta\theta_i}
$$

The adaptive acceptance rule is:

$$
A_i
=
\Omega_{\max}\Delta t_i
+
k\Sigma_{\Delta\theta_i}
+
\mu
<
\pi
$$

and

$$
C_i>B_i,
\qquad
B_i=\mu+k\Sigma_{\Delta\theta_i}
$$

Only accepted intervals are used for continuous phase reconstruction:

$$
\widetilde{\Theta}_{G,i+1}
=
\widetilde{\Theta}_{G,i}
+
\delta_i^{\rm wrap}
$$

---

# 8. Numerical Validation and Reproducibility

UST2026 includes explicit computational procedures for numerical validation.

The retained candidate numerical evolution law is:

$$
s_{t+1}
=
s_t
-
\alpha Ls_t
+
\beta
\left(
s_t-s_t^{\circ 3}
\right)
$$

The retained reference configuration includes:

$$
N=400
$$

$$
\alpha=0.05
$$

$$
\beta=0.50
$$

The numerical experiments include multiple system sizes and independent random seeds.

The reported numerical results include:

- nontrivial equilibrium classification,
- convergence measurements,
- residual evaluation,
- amplitude evaluation,
- reproducibility across independent runs.

The numerical validation is explicitly treated as **numerical evidence for the mathematical candidate dynamics**, not as observational proof of the physical theory.

---

# 9. Observational Testing

The project distinguishes clearly between:

1. mathematical derivation,
2. numerical testing,
3. observational testing,
4. empirical acceptance or rejection.

No missing observational covariance result is fabricated.

Where a full observational covariance matrix is required, the complete covariance matrix must be supplied before a definitive likelihood calculation is claimed.

Historical diagonal tests are retained only as historical controls and are not presented as substitutes for the required full-covariance analysis.

---

# 10. BAO and Hubble-Scale Testing

The integrated framework defines:

$$
D_H(z)
=
\frac{c}{H(z)}
$$

and

$$
D_M(z)
=
c
\int_0^z
\frac{dz'}{H(z')}
$$

The dimensionless BAO observable vector is:

$$
\mathbf{D}
=
\left(
\frac{D_M}{r_d},
\frac{D_H}{r_d}
\right)
$$

The appropriate covariance-aware statistic is:

$$
\chi^2
=
(\mathbf{D}_{\rm data}-\mathbf{D}_{\rm model})^T
C^{-1}
(\mathbf{D}_{\rm data}-\mathbf{D}_{\rm model})
$$

The off-diagonal covariance terms must be retained.

The project therefore does not treat an incomplete or diagonalized covariance matrix as equivalent to the full observational likelihood.

---

# 11. Retained Environmental Clock Candidate

The integrated Parts I–VI framework retains the candidate environmental period:

$$
P_{\rm cand}
=
1017.75608937
\ {\rm local\ years}
$$

The corresponding clock factor is:

$$
C_{\rm clock}
=
\frac{P_{\rm cand}}{1000}
=
1.01775608937
$$

The fractional offset is:

$$
\delta_{\rm clock}
=
C_{\rm clock}-1
=
0.01775608937
$$

Therefore:

$$
\delta_{\rm clock}
=
1.775608937\%
$$

These values are treated as retained quantities of the integrated model and are not re-fitted in the corresponding fixed-clock prediction.

---

# 12. Hubble-Scale Prediction

Using the retained reference value:

$$
H_{\rm early}
=
67.4\ {\rm km\,s^{-1}\,Mpc^{-1}}
$$

the fixed-clock transformation is:

$$
H_{\rm clock}
=
C_{\rm clock}H_{\rm early}
$$

Therefore:

$$
H_{\rm clock}
=
1.01775608937
\times
67.4
$$

$$
H_{\rm clock}
=
68.5967604235
\ {\rm km\,s^{-1}\,Mpc^{-1}}
$$

The rounded reporting value is:

$$
\boxed{
H_{\rm clock}
\approx
68.5968
\ {\rm km\,s^{-1}\,Mpc^{-1}}
}
$$

This is retained as a **model prediction**, not as a fitted observational parameter.

---

# 13. Redshift-Dependent Test

The fixed-clock hypothesis can be written:

$$
H_{\rm model}(z)
=
C_{\rm clock}H_{\rm base}(z)
$$

with

$$
H_{\rm base}(z)
=
H_{\rm early}
\sqrt{
\Omega_M(1+z)^3
+
1-\Omega_M
}
$$

The observational test should therefore evaluate the complete redshift dependence of:

$$
H(z),
\qquad
D_H(z),
\qquad
D_M(z)
$$

using the appropriate observational covariance matrix.

---

# 14. Environmental Closure Relation

The integrated framework introduces:

$$
R_{\rm env}(z)
=
\frac{H_{\rm local}(z)}
{H_{\rm host}(z)}
$$

The local relation is represented as:

$$
H_{\rm local}(z)
=
C_{\rm clock}
R_{\rm env}(z)
H_{\rm early}(z)
$$

For the retained local reference comparison:

$$
H_{\rm local}(0)
=
73.04
\ {\rm km\,s^{-1}\,Mpc^{-1}}
$$

the corresponding diagnostic ratio is approximately:

$$
R_{\rm env}(0)
\approx
\frac{73.04}{68.5967604235}
$$

This quantity is treated as a diagnostic parameter for subsequent environmental testing.

---

# 15. Scientific Method

The permanent methodological rule of UST2026 is:

$$
\boxed{
\text{Derive}
\rightarrow
\text{Freeze}
\rightarrow
\text{Predict}
\rightarrow
\text{Test}
\rightarrow
\text{Accept or Reject}
}
$$

A parameter that has been frozen for a prediction is not subsequently adjusted merely to improve agreement with the same dataset.

The project distinguishes between:

- theoretical assumptions,
- derived quantities,
- retained calibration values,
- predictions,
- numerical controls,
- observational measurements,
- statistical tests,
- falsification criteria.

---

# 16. Reproducibility

The objective of the UST2026 repository is to preserve:

- mathematical definitions,
- derivations,
- numerical procedures,
- simulation code,
- parameter values,
- testing protocols,
- observational data pathways,
- uncertainty treatment,
- covariance requirements,
- publication materials.

Reproducible results should be generated from explicitly documented inputs and procedures.

No unavailable observational result is replaced by an invented value.

---

# 17. Research Structure

The current integrated research sequence is:

### Part I
Foundational development of the Universal Stasis framework.

### Part II
Physical and operational development of the Two-Scale Hosting Time hypothesis.

### Part III
Extension and mathematical development of the framework.

### Part IV
Integrated theoretical and computational development.

### Part V
Environmental Ascent Clock Theory, astronomical realization, phase unwrapping, uncertainty propagation, sampling safety, and reproducible testing.

### Part VI
Complete Integrated Closure of Parts I–VI, including the Two-Scale Hosting Time and Environmental Ascent Clock framework, numerical validation procedures, and the fixed-clock Hubble-scale prediction.

---

# 18. Status of the Research

UST2026 is an ongoing independent research program.

The computational and numerical results included in the project should be distinguished from experimental or observational confirmation.

The framework is intended to remain testable and falsifiable.

Future observational tests may support, constrain, modify, or reject individual components of the framework.

---

# 19. Publication and Archival Record

The research materials are intended for permanent scholarly preservation through public repositories and version-controlled research archives.

GitHub provides the version-controlled development and source repository.

Zenodo provides archival preservation and DOI-based scholarly identification for archived releases.

Each archived release should correspond to a clearly identified state of the research materials.

---

# 20. Citation

When citing the project, please use the archived Zenodo record and its DOI corresponding to the specific version being cited.

**Author:**  
Sami Samir Ibrahim El-Sayed

**ORCID:**  
0009-0006-0807-0582

**Project:**  
UST2026 — Universal Stasis Theory

---

# 21. License and Research Integrity

Research materials should be used with appropriate attribution.

Results should not be presented as experimentally confirmed unless the corresponding experimental or observational evidence has actually been obtained and independently reproduced.

The repository preserves the distinction between theoretical proposal, computational evidence, and empirical validation.

---

## UST2026

**Universal Stasis Theory (UST)**  
**Two-Scale Hosting Time**  
**Environmental Ascent Clock Theory**

**Parts I–VI — Complete Integrated Research Framework**