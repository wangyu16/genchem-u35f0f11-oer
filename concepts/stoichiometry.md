# Chapter 3 Concept Map: Stoichiometry

## Source and Scope

**Reference:** instructor's own lecture notes (Yu Wang, University of Louisiana at Lafayette),
Chapter 3 (CC BY 4.0). **Audience:** introductory undergraduate general chemistry. **Note:** covers
Molar Mass (atomic mass, molecular mass, formula mass, percent composition, mass spectrometry) and
Balancing Chemical Reactions (balancing equations, limiting reagent, reaction yield). Simple
Markdown only — no images, diagrams, or orz containers.

## Chapter Summary

Chapter 3 introduces the single most important quantitative idea in general chemistry: the mole.
The chapter first builds the mass side of the mole concept — atomic mass, average atomic mass (a
weighted average over isotopes), molecular/formula mass, and molar mass — and shows how percent
composition and combustion-analysis data can be used to determine an empirical formula. This gives
students a reliable bridge between the macroscopic quantity chemists weigh (grams) and the
particle-scale quantity chemistry reasons about (moles, and ultimately atoms/molecules via
Avogadro's number).

The second half applies this bridge to actual chemical reactions: balancing chemical equations so
that atoms are conserved, then using balanced equations and the mole bridge together to predict how
much product forms from a given amount of reactant. This is where the limiting-reagent concept and
percent yield are introduced — recognizing that a reaction's product amount is capped by whichever
reactant runs out first, and that real yields fall short of the theoretical maximum. Every
mass-to-mass, mass-to-particle, or mass-to-volume calculation for the rest of the course routes
through the mole concept built in this chapter.

## Prerequisites and Later Payoff

| Connection | Concepts needed or enabled | Why it matters |
|---|---|---|
| Prior chapter(s) | Ch. 1 (dimensional analysis, significant figures), Ch. 2 (chemical formulas, atomic structure) | Molar-mass and stoichiometry calculations are dimensional-analysis problems performed on formulas from Chapter 2. |
| This chapter | The mole concept, molar mass, balancing equations, limiting reagent, percent yield | The mole is the universal conversion currency reused in essentially every later quantitative chapter. |
| Later chapter(s) | Ch. 4 (solution stoichiometry), Ch. 5 (gas stoichiometry), Ch. 6 (heat per mole of reaction), Ch. 13 (rate expressions per mole) | Each of these chapters applies the same mole-bridge and balanced-equation logic to a new physical quantity (concentration, gas volume, heat, rate). |

## Core Dependency Chain

- **Molar mass (atomic mass → average atomic mass → molecular/formula mass → molar mass)**
  - This enables: every mass ↔ mole ↔ particle-count conversion in the rest of the course,
    including Ch. 4 solution stoichiometry, Ch. 5 gas density/molar mass, and Ch. 12 concentration
    calculations.
- **Percent composition and empirical-formula determination from combustion data**
  - This enables: a general problem-solving pattern (convert mass of combustion products to moles
    of each element, then to a simplest ratio) that reappears whenever a formula must be derived
    from experimental data.
- **Balancing chemical equations**
  - This enables: every reaction-based calculation in Ch. 4 (aqueous reactions), Ch. 6
    (thermochemical equations), Ch. 13 (kinetics), Ch. 14 (equilibrium expressions), and Ch. 18
    (redox equations) — all require a correctly balanced equation as the starting point.
- **Limiting reagent and percent yield**
  - This enables: the same "compare moles available to moles required" reasoning reused in Ch. 4
    solution stoichiometry and any multi-reactant problem in later chapters.

## Logical Order for Teaching

| Order | Introduce | Reason for placement |
|---|---|---|
| 1 | Molar Mass (atomic mass through mass spectrometry) | Builds the mole/mass bridge first, since it is needed to interpret any reaction quantitatively. |
| 2 | Balancing Chemical Reactions (balancing, limiting reagent, yield) | Applies the mole bridge from Section 1 to actual chemical equations, culminating in the limiting-reagent/yield calculations that combine both ideas. |

## Section-Level Concept Map and Objectives

This section is the course's **learning-outcome registry**. Every ID defined below is reused verbatim by the study guide (which badges the bullet or bullets that teach it), by the slide deck, by the assessment guide (which gives each one a full entry with question guides), and by every practice question. Searching all five files for a single ID therefore traces one outcome from concept map to graded question. The QA harness enforces this: any ID declared here and missing from another carrier is a release-blocking failure.

### 1. Molar Mass (§3.1)

**Learning objectives:**
- **Objective 3.1a** — Calculate average atomic mass and understand the mole concept
- **Objective 3.1b** — Convert between mass, moles, and number of particles
- **Objective 3.1c** — Calculate molecular mass, formula mass, and percent composition
- **Objective 3.1d** — Determine an empirical formula from combustion-analysis data

**Concept flow:**
- Atomic mass (amu, relative to ¹²C) → average atomic mass (weighted by isotope abundance)
- Mole (Avogadro's number of entities) → molar mass (grams per mole), numerically equal to atomic/
  molecular/formula mass
  - Molar mass bridges mass (g) ↔ moles (mol) ↔ number of particles (via Nₐ)
- Percent composition (mass % of each element in a compound) ← from molar mass
  - Combustion analysis (mass of CO₂ and H₂O produced) → moles of C and H → empirical formula

### 2. Balancing Chemical Reactions (§3.2)

**Learning objectives:**
- **Objective 3.2a** — Balance chemical equations
- **Objective 3.2b** — Convert between quantities of reactants and products using a balanced equation
- **Objective 3.2c** — Determine the limiting reagent
- **Objective 3.2d** — Calculate theoretical yield and percent yield

**Concept flow:**
- Chemical equation (reactants → products) → balance by adjusting coefficients (never subscripts)
  so atom counts match
- Balanced equation + given amount of one substance → moles (via molar mass) → moles of another
  substance (via coefficient ratio) → desired unit of that substance (via molar mass)
- Multiple reactants given → limiting reagent (the one that produces the least product) caps the
  reaction
  - Theoretical yield (from limiting reagent) vs. actual yield → percent yield =
    actual/theoretical × 100%

## Common Student Bottlenecks

| Bottleneck | Conceptual repair |
|---|---|
| Confusing "amu" (atomic mass, a per-atom scale) with "g/mol" (molar mass, a per-mole scale) | Emphasize that the *numerical value* is the same but the units and the physical scale (single atom vs. one mole of atoms) are different; always attach the correct unit. |
| Balancing an equation by changing subscripts instead of coefficients | State explicitly, every time: subscripts define the substance's identity and can never change; only coefficients (the numbers in front) may be adjusted. |
| Assuming the reactant present in the *smallest mass* (rather than the smallest usable moles, per stoichiometry) is the limiting reagent | Require students to convert every reactant to moles and divide by its coefficient before comparing — mass alone is not a valid shortcut. |
| Confusing percent yield with percent composition, or theoretical yield with actual yield | Keep a fixed vocabulary check: percent composition describes a single compound's makeup; percent yield compares two *amounts of product* from the same reaction. |
| Forgetting to convert combustion-analysis masses (CO₂, H₂O) into moles of the *original elements* (C, H) before finding a ratio | Walk through the unit path explicitly: mass of CO₂ → moles of CO₂ → moles of C (1:1 ratio), and moles of H₂O → moles of H (2:1 ratio), before ever comparing element ratios. |
