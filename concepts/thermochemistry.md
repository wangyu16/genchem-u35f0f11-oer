# Chapter 6 Concept Map: Thermochemistry

## Source and Scope

**Reference:** instructor's own lecture notes (Yu Wang, University of Louisiana at Lafayette),
Chapter 6 (CC BY 4.0). **Audience:** introductory undergraduate general chemistry. **Note:** covers
Energy (systems, first law of thermodynamics), Enthalpy, Calorimetry, and Standard Enthalpy
(Hess's law, standard enthalpy of formation). Simple Markdown only — no images, diagrams, or orz
containers.

## Chapter Summary

Chapter 6 introduces energy bookkeeping for chemical reactions. It starts by defining a system and
its surroundings, classifying systems as open, closed, or isolated, and stating the first law of
thermodynamics (ΔU = q + w) — energy is conserved, only converted between heat and work. From
there, enthalpy (H) is introduced as the practical energy quantity for reactions run at constant
pressure (the normal lab condition), with sign conventions for exothermic (releases heat, ΔH < 0)
and endothermic (absorbs heat, ΔH > 0) processes.

Calorimetry supplies the experimental method for *measuring* these enthalpy changes (constant-
volume "bomb" calorimetry and constant-pressure "coffee-cup" calorimetry), while the final section
supplies a way to *calculate* them without an experiment at all: Hess's law lets enthalpies of
individual reaction steps be added algebraically, and standard enthalpies of formation let any
reaction's enthalpy be calculated from tabulated values. This chapter's toolkit — ΔH, Hess's law,
and standard formation data — is reused directly in Chapter 11 (phase-change enthalpies) and
Chapter 17 (which combines the same enthalpy data with entropy to get free energy).

## Prerequisites and Later Payoff

| Connection | Concepts needed or enabled | Why it matters |
|---|---|---|
| Prior chapter(s) | Ch. 3 (balanced equations, mole concept, stoichiometric conversions) | Enthalpy calculations are stoichiometry problems where the "product" being converted is heat (kJ) instead of mass. |
| This chapter | System/surroundings, first law of thermodynamics, enthalpy, calorimetry, Hess's law, standard enthalpy of formation | Establishes the energy-per-mole-of-reaction bookkeeping reused in later energy-related chapters. |
| Later chapter(s) | Ch. 11 (molar heats of vaporization/fusion/sublimation), Ch. 17 Thermodynamics (ΔG = ΔH − TΔS uses ΔH data and Hess's-law-style reasoning directly) | Both chapters reuse this chapter's q = nΔH logic and its standard-enthalpy-of-formation tables without re-deriving them. |

## Core Dependency Chain

- **System, surroundings, first law of thermodynamics (ΔU = q + w)**
  - This enables: the sign conventions and energy-conservation framework used throughout the rest
    of the chapter and in Ch. 17's laws of thermodynamics.
- **Enthalpy (H = U + PV) and exothermic/endothermic sign conventions**
  - This enables: every later ΔH calculation, including Ch. 11 phase-change enthalpies and Ch. 17
    free-energy calculations (ΔG = ΔH − TΔS).
- **Calorimetry (constant-volume and constant-pressure)**
  - This enables: the experimental-measurement half of thermochemistry — a technique referenced
    whenever "how was ΔH measured" is asked.
- **Hess's law and standard enthalpy of formation**
  - This enables:
    - Any reaction-enthalpy calculation from tabulated formation data, reused as-is in Ch. 17.
    - The same "add/reverse/scale reactions algebraically" logic reused for equilibrium constants
      (Ch. 14) and standard free energies (Ch. 17).

## Logical Order for Teaching

| Order | Introduce | Reason for placement |
|---|---|---|
| 1 | Energy (systems, first law) | Establishes the conservation-of-energy framework and vocabulary (system, surroundings, heat, work) needed for everything that follows. |
| 2 | Enthalpy | Narrows the general energy framework to the specific, constant-pressure quantity (ΔH) used for chemical reactions. |
| 3 | Calorimetry | Shows how ΔH (and ΔU) are measured experimentally, grounding the abstract quantity in a lab technique. |
| 4 | Standard Enthalpy (Hess's law, formation enthalpies) | Capstones the chapter by showing how ΔH can be *calculated* without a calorimeter, using tabulated data — the method used in every later ΔH problem. |

## Section-Level Concept Map and Objectives

This section is the course's **learning-outcome registry**. Every ID defined below is reused verbatim by the study guide (which badges the bullet or bullets that teach it), by the slide deck, by the assessment guide (which gives each one a full entry with question guides), and by every practice question. Searching all five files for a single ID therefore traces one outcome from concept map to graded question. The QA harness enforces this: any ID declared here and missing from another carrier is a release-blocking failure.

### 1. Energy and the First Law of Thermodynamics (§6.1)

**Learning objectives:**
- **Objective 6.1a** — Distinguish types of energy, types of systems, and exothermic/endothermic processes
- **Objective 6.1b** — Apply the first law of thermodynamics

**Concept flow:**
- System (of interest) vs. surroundings (rest of universe)
  - Open (exchanges mass and energy) vs. closed (energy only) vs. isolated (neither)
- Heat (q) transferred between system and surroundings; exothermic (releases heat) vs. endothermic
  (absorbs heat)
- First law of thermodynamics: ΔU = q + w (energy conserved, converted between heat and work)
  - Work for gas expansion/compression: w = −PΔV

### 2. Enthalpy (§6.2)

**Learning objectives:**
- **Objective 6.2a** — Define enthalpy and apply thermochemical-equation rules
- **Objective 6.2b** — Convert between ΔH and ΔU for a reaction

**Concept flow:**
- Enthalpy (H = U + PV) → constant-pressure heat flow (ΔH) of a system
- Thermochemical equation rules → coefficients = moles; reversing flips ΔH's sign; scaling scales
  ΔH; physical states must be specified
- ΔH ↔ ΔU conversion for gas-phase reactions, using Δn (moles of gas, products − reactants)

### 3. Calorimetry (§6.3)

**Learning objectives:**
- **Objective 6.3a** — Apply specific heat and heat capacity
- **Objective 6.3b** — Use constant-volume and constant-pressure calorimetry

**Concept flow:**
- Specific heat (s) and heat capacity (C = ms) → q = C·ΔT = m·s·ΔT
- Constant-volume calorimetry (bomb) → measures ΔU_rxn; constant-pressure calorimetry (coffee cup)
  → measures ΔH_rxn
  - Heat lost by reaction = heat gained by water/calorimeter (energy conservation between system
    and surroundings)

### 4. Standard Enthalpy (§6.4)

**Learning objectives:**
- **Objective 6.4a** — Apply Hess's Law
- **Objective 6.4b** — Calculate reaction enthalpy from standard enthalpies of formation

**Concept flow:**
- Standard enthalpy of formation (ΔH°f) → zero for elements in their most stable form; tabulated
  for compounds
- Hess's law → ΔH of a multi-step (or hypothetical) reaction equals the sum of the ΔH values of
  steps that add up to it
- ΔH°rxn = Σ nΔH°f(products) − Σ mΔH°f(reactants) → calculate any reaction's enthalpy from formation
  data alone

## Common Student Bottlenecks

| Bottleneck | Conceptual repair |
|---|---|
| Sign confusion in ΔU = q + w, or in exothermic/endothermic ΔH conventions | Anchor every problem to the system's point of view first ("does the system gain or lose energy?") with an explicit diagram, before assigning signs to q, w, or ΔH. |
| Forgetting to scale ΔH when multiplying a thermochemical equation, or to flip its sign when reversing | Treat coefficient-scaling and reaction-reversal as two separate, explicit checks applied to ΔH every time an equation is manipulated, not just when balancing atoms. |
| Confusing q_rxn (heat released/absorbed by the reaction) with q_water/q_calorimeter (heat gained/lost by the surroundings being measured) | State the energy-conservation relationship explicitly every time: q_rxn = −(q_water + q_calorimeter). |
| Treating standard enthalpy of formation of an element as always zero, even for a non-standard-state allotrope | Emphasize "most stable form at 1 atm and 25 °C" specifically — e.g., graphite (not diamond) is carbon's zero-reference state. |
| Losing track of which substances' ΔH°f values to add vs. subtract in the ΔH°rxn formula | Always rewrite the formula symbolically first (products minus reactants, each weighted by its coefficient) before plugging in numbers. |
