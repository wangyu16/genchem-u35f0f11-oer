# Chapter 5 Concept Map: Gases

## Source and Scope

**Reference:** instructor's own lecture notes (Yu Wang, University of Louisiana at Lafayette),
Chapter 5 (CC BY 4.0). **Audience:** introductory undergraduate general chemistry. **Note:** covers
General Concepts (substances that exist as gases, pressure), the Gas Laws (including the ideal gas
equation), Partial Pressures, the Kinetic Molecular Theory of Gases, and Deviations from Ideal
Behavior. Simple Markdown only — no images, diagrams, or orz containers.

## Chapter Summary

Chapter 5 studies the gas phase as a distinct, highly quantifiable state of matter. It begins with
pressure as a measurable quantity and its several common units, then builds up the individual gas
laws (Boyle's, Charles's, Avogadro's) into the single ideal gas equation, PV = nRT — a relationship
that lets students move fluidly between pressure, volume, temperature, and moles (and, via molar
mass, grams) for any gas. Dalton's law of partial pressures extends this to gas mixtures, letting
students treat each component of a mixture as if it alone occupied the container.

The kinetic molecular theory then supplies the *microscopic explanation* for every macroscopic gas
law already covered — connecting molecular motion and collision frequency to pressure, and average
kinetic energy to temperature — before the chapter closes by acknowledging the ideal gas law's
limits (the van der Waals equation) at high pressure or low temperature. Gas-phase reasoning
reappears directly in Chapter 14 (converting between K_p and K_c using PV = nRT), and the same
mole-bridge logic used here (P, V, T, n, and molar mass all related through one equation) mirrors
the mass-based mole bridge from Chapter 3.

## Prerequisites and Later Payoff

| Connection | Concepts needed or enabled | Why it matters |
|---|---|---|
| Prior chapter(s) | Ch. 1 (units, dimensional analysis), Ch. 3 (mole concept, stoichiometry) | The ideal gas law is a unit-heavy equation, and gas stoichiometry problems route through the same mole bridge built in Chapter 3. |
| This chapter | Pressure, the ideal gas law (PV = nRT), Dalton's law of partial pressures, kinetic molecular theory | Supplies the P-V-T-n relationship used whenever a gas-phase quantity needs to be calculated. |
| Later chapter(s) | Ch. 14 Chemical Equilibrium (K_p ↔ K_c conversion via RT) | PV = nRT is used directly, not re-derived, when converting between pressure-based and concentration-based equilibrium constants. |

## Core Dependency Chain

- **Pressure and its units (atm, mmHg/torr, Pa)**
  - This enables: every gas-law calculation in this chapter and any later gas-phase problem
    (including Ch. 14 equilibrium).
- **The ideal gas equation (PV = nRT)**
  - This enables:
    - Gas density and molar mass calculations (this chapter) — the same equation rearranged.
    - Ch. 14 Chemical Equilibrium — the K_p = K_c(RT)^Δn relationship is derived directly from
      PV = nRT.
- **Dalton's law of partial pressures**
  - This enables: gas-collected-over-water calculations (this chapter) and multi-gas equilibrium
    problems (Ch. 14).
- **Kinetic molecular theory**
  - This enables: a conceptual (non-mathematical) explanation reused whenever a course asks
    "why" a gas law holds, and underlies the root-mean-square speed and effusion/diffusion
    relationships in this chapter.

## Logical Order for Teaching

| Order | Introduce | Reason for placement |
|---|---|---|
| 1 | General Concepts (substances that exist as gases, pressure) | Establishes what a gas is and how pressure is measured before any law is introduced. |
| 2 | The Gas Laws (Boyle's, Charles's, Avogadro's, ideal gas equation) | Builds the central quantitative relationship (PV = nRT) students will use for the rest of the chapter and beyond. |
| 3 | Partial Pressures | Extends the ideal gas law from a single gas to a mixture of gases. |
| 4 | The Kinetic Molecular Theory of Gases | Supplies the microscopic explanation for the macroscopic laws already covered, reinforcing why they work. |
| 5 | Deviations from Ideal Behavior | Closes the chapter by acknowledging the ideal gas law's limits, appropriately placed after the ideal model is fully understood. |

## Section-Level Concept Map and Objectives

This section is the course's **learning-outcome registry**. Every ID defined below is reused verbatim by the study guide (which badges the bullet or bullets that teach it), by the slide deck, by the assessment guide (which gives each one a full entry with question guides), and by every practice question. Searching all five files for a single ID therefore traces one outcome from concept map to graded question. The QA harness enforces this: any ID declared here and missing from another carrier is a release-blocking failure.

### 1. General Concepts and Pressure (§5.1)

**Learning objectives:**
- **Objective 5.1a** — Convert between pressure units

**Concept flow:**
- Physical characteristics of gases (fill container, compressible, mix completely, low density)
  → motivates treating gases as a distinct, simplified state
- Pressure = force / area → multiple equivalent units (Pa, atm, mmHg, torr) requiring conversion

### 2. The Gas Laws (§5.2)

**Learning objectives:**
- **Objective 5.2a** — Apply the ideal gas equation
- **Objective 5.2b** — Calculate gas density and molar mass

**Concept flow:**
- Boyle's law (P ∝ 1/V) + Charles's law (V ∝ T) + Avogadro's law (V ∝ n) → combined into the ideal
  gas equation, PV = nRT
- Ideal gas equation rearranged → gas density and molar mass calculations (𝓜 = dRT/P)

### 3. Partial Pressures (§5.3)

**Learning objectives:**
- **Objective 5.3a** — Apply Dalton's law of partial pressures and mole fraction
- **Objective 5.3b** — Correct for water vapor pressure when a gas is collected over water

**Concept flow:**
- Gas mixture → total pressure = sum of partial pressures (Dalton's law)
- Mole fraction (Xᵢ = nᵢ/n) → Pᵢ = XᵢP relates composition to partial pressure
- Gas collected over water → subtract water's vapor pressure from total pressure to find the
  partial pressure of the gas of interest

### 4. The Kinetic Molecular Theory of Gases (§5.4)

**Learning objectives:**
- **Objective 5.4a** — State the kinetic molecular theory and use it to explain gas-law behavior
- **Objective 5.4b** — Apply Graham's law of effusion and diffusion

**Concept flow:**
- Kinetic molecular theory assumptions (negligible molecular volume, constant random motion,
  elastic collisions, KE ∝ T) → microscopic explanation for every gas law in Section 2 and 3
- Average kinetic energy ∝ temperature → root-mean-square speed (u_rms = √(3RT/𝓜))
- Diffusion and effusion rates → inversely proportional to the square root of molar mass

### 5. Deviations from Ideal Behavior (§5.5)

**Learning objectives:**
- **Objective 5.5a** — Explain why and when real gases deviate from ideal behavior

**Concept flow:**
- Real gas molecules have finite volume and intermolecular attractions (violating kinetic
  molecular theory assumptions) → deviations most significant at high pressure/low temperature
- Van der Waals equation → corrects pressure (for attraction) and volume (for molecular size) terms
  in the ideal gas law

## Common Student Bottlenecks

| Bottleneck | Conceptual repair |
|---|---|
| Using temperature in °C directly in PV = nRT instead of converting to Kelvin | Make "convert T to Kelvin first" a fixed first step for every gas-law problem, before any other substitution. |
| Selecting the wrong value of R (units mismatch with the given pressure/volume units) | Have students identify the units of P and V in the problem *before* selecting R, matching units consistently (e.g., atm/L → R = 0.0821 L·atm/K·mol). |
| Confusing partial pressure with mole fraction, or forgetting that partial pressures sum to total pressure | Always write Dalton's law (P = P₁ + P₂ + …) explicitly before solving for an individual partial pressure. |
| Assuming all gases behave ideally under any condition | Explicitly tie "high pressure" and "low temperature" to *why* they cause deviation (molecules forced closer together, so molecular volume and attraction become non-negligible) rather than treating it as a memorized fact. |
| Misapplying the square-root diffusion/effusion relationship (inverting the ratio) | Anchor with the qualitative check first: the heavier gas always diffuses/effuses more slowly, then verify the calculated ratio matches that direction. |
