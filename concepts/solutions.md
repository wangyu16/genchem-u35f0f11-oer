# Chapter 12 Concept Map: Physical Properties of Solutions

## Source and Scope

**Reference:** instructor's own lecture notes (Yu Wang, University of Louisiana at Lafayette),
Chapter 12 (CC BY 4.0). **Audience:** introductory undergraduate general chemistry. **Note:** covers
Some General Concepts and Rules (solution formation, solubility, temperature/pressure effects), and
Concentration Units and Colligative Properties. Simple Markdown only — no images, diagrams, or orz
containers.

## Chapter Summary

Chapter 12 explains why some substances dissolve in others by returning directly to Chapter 11's
intermolecular-force framework: solution formation is a competition between breaking
solvent-solvent and solute-solute interactions and forming new solvent-solute interactions, and
"like dissolves like" is a direct consequence of which forces are compatible. From there, the
chapter formalizes four ways to express concentration — mole fraction, percent by mass, molarity
(reused from Chapter 4), and molality — and shows how to convert between them given density and
molar mass.

The chapter's second major idea is colligative properties: vapor-pressure lowering (Raoult's law),
boiling-point elevation, freezing-point depression, and osmotic pressure all depend only on the
*number* of dissolved particles, not their chemical identity — extended to electrolyte solutions
via the van't Hoff factor, i. This chapter's concentration-unit toolkit (especially molarity and
molality) is reused directly in Chapter 15–16's pH and buffer calculations and in Chapter 18's
Nernst-equation problems, making it a quantitative bridge between the structural chapters (9–11)
and the equilibrium/electrochemistry chapters (14–18).

## Prerequisites and Later Payoff

| Connection | Concepts needed or enabled | Why it matters |
|---|---|---|
| Prior chapter(s) | Ch. 4 (molarity, introduced there), Ch. 11 (intermolecular forces) | Chapter 12 extends molarity to three additional concentration units and explains solubility using Chapter 11's force classification. |
| This chapter | Solution formation (like dissolves like), mole fraction, percent by mass, molarity, molality, colligative properties, van't Hoff factor | Supplies the concentration-unit toolkit and the particle-counting logic (colligative properties) used in later quantitative chapters. |
| Later chapter(s) | Ch. 15–16 Acid-Base (Equilibria) (molarity used throughout pH/buffer/titration calculations), Ch. 18 Electrochemistry (molarity used in Nernst-equation and concentration-cell problems) | Both chapters assume fluency with molarity (and, less often, molality) without re-deriving it. |

## Core Dependency Chain

- **Solution formation and "like dissolves like" (built on Ch. 11 intermolecular forces)**
  - This enables: qualitative solubility predictions used whenever a later problem asks whether a
    substance will dissolve in a given solvent.
- **Concentration units (mole fraction, percent by mass, molarity, molality) and interconversion**
  - This enables: Ch. 15–16 (pH, buffer, titration calculations) and Ch. 18 (Nernst equation,
    concentration cells) — all reuse molarity/molality directly.
- **Colligative properties (vapor-pressure lowering, boiling-point elevation, freezing-point
  depression, osmotic pressure) and the van't Hoff factor**
  - Largely a terminal application within this chapter, but the "count particles, not identity"
    reasoning reappears conceptually whenever electrolyte dissociation is discussed (Ch. 15).

## Logical Order for Teaching

| Order | Introduce | Reason for placement |
|---|---|---|
| 1 | Some General Concepts and Rules | Explains *why* solutions form (intermolecular-force competition) before any quantitative concentration measure is introduced. |
| 2 | Concentration Units | Builds the four ways to quantify "how much" solute is present, needed before colligative-property calculations can be performed. |
| 3 | Colligative Properties | Capstones the chapter by applying the concentration units from Section 2 to predict measurable solution properties. |

## Section-Level Concept Map and Objectives

This section is the course's **learning-outcome registry**. Every ID defined below is reused verbatim by the study guide (which badges the bullet or bullets that teach it), by the slide deck, by the assessment guide (which gives each one a full entry with question guides), and by every practice question. Searching all five files for a single ID therefore traces one outcome from concept map to graded question. The QA harness enforces this: any ID declared here and missing from another carrier is a release-blocking failure.

### 1. Some General Concepts and Rules (§12.1)

**Learning objectives:**
- **Objective 12.1a** — Explain solution formation and classify solutions by saturation
- **Objective 12.1b** — Apply "like dissolves like" to predict solubility
- **Objective 12.1c** — Predict temperature/pressure effects on solubility, including Henry's law

**Concept flow:**
- Saturated (maximum solute dissolved) vs. unsaturated vs. supersaturated (unstable, exceeds
  saturation) solutions
- Solution formation → break solvent-solvent + break solute-solute interactions, form
  solvent-solute interactions → net exothermic or endothermic depending on relative interaction
  strengths
- "Like dissolves like" (from Ch. 11 intermolecular-force compatibility) → predicts miscibility
  and solubility
- Temperature effect (solids: variable; gases: solubility always decreases with increasing
  temperature) and pressure effect (solids/liquids: none; gases: Henry's law, solubility ∝
  pressure)

### 2. Concentration Units (§12.2)

**Learning objectives:**
- **Objective 12.2a** — Calculate mole fraction, percent by mass, molarity, and molality
- **Objective 12.2b** — Convert between concentration units given density and molar mass

**Concept flow:**
- Mole fraction (moles of A / total moles) and percent by mass (mass of solute / mass of solution
  × 100%) → composition-based units, independent of volume
- Molarity (mol solute / L solution) and molality (mol solute / kg solvent) → volume-based vs.
  mass-based concentration units
- Density and molar mass → the conversion bridge between any two of the four units

### 3. Colligative Properties (§12.3)

**Learning objectives:**
- **Objective 12.3a** — Apply Raoult's law to calculate vapor-pressure lowering
- **Objective 12.3b** — Calculate boiling-point elevation and freezing-point depression
- **Objective 12.3c** — Calculate osmotic pressure
- **Objective 12.3d** — Apply the van't Hoff factor to electrolyte solutions

**Concept flow:**
- Colligative properties (depend only on number of solute particles, not identity) → vapor-
  pressure lowering, boiling-point elevation, freezing-point depression, osmotic pressure
- Raoult's law (P₁ = X₁P₁°) → vapor-pressure lowering proportional to solvent mole fraction
- ΔTb = Kbm and ΔTf = Kfm → boiling-point elevation and freezing-point depression proportional to
  molality
- Osmotic pressure (π = MRT) → pressure needed to stop solvent flow across a semipermeable
  membrane
- Electrolyte solutions → van't Hoff factor i (actual particles / formula units dissolved)
  multiplies each colligative-property formula

## Common Student Bottlenecks

| Bottleneck | Conceptual repair |
|---|---|
| Using molarity when a colligative-property formula requires molality (or vice versa) | Anchor which formulas use which unit as a fixed rule: boiling-point elevation and freezing-point depression use molality (temperature-independent denominator); osmotic pressure uses molarity. |
| Forgetting the van't Hoff factor for ionic solutes, or misjudging its value | Require students to write the dissociation equation for the solute first and count the resulting ions before assigning i, rather than assuming i = 1 by default. |
| Confusing "solubility increases with temperature" as a universal rule | Separate solids (variable, no universal rule) from gases (solubility always decreases with increasing temperature) explicitly before predicting a temperature effect. |
| Applying Henry's law to a gas that chemically reacts with the solvent (e.g., CO₂ or NH₃ in water) | Flag Henry's law's key assumption explicitly — no chemical reaction between solute and solvent — before applying it to a specific gas. |
| Mixing up which concentration unit's denominator changes with temperature (volume-based units like molarity) vs. which stays fixed (mass-based units like molality) | Tie unit choice to the physical scenario: molarity is convenient for delivered volumes but is temperature-sensitive (volume expands/contracts); molality is temperature-independent, which is why colligative-property constants use it. |
