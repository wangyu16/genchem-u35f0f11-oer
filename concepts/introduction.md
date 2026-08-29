# Chapter 1 Concept Map: Introduction to Chemistry

## Source and Scope

**Reference:** instructor's own lecture notes (Yu Wang, University of Louisiana at Lafayette),
Chapter 1 (CC BY 4.0). **Audience:** introductory undergraduate general chemistry, no prior
chemistry assumed. **Note:** covers the four sections of Chapter 1 — General Concepts in
Chemistry, Measurement, Numbers, and Dimensional Analysis. This file is simple Markdown only — no
images, diagrams, or orz containers — so it renders correctly anywhere.

## Chapter Summary

Chapter 1 is the course's on-ramp: it introduces no chemical reactions and no atomic theory, but
instead builds the *vocabulary and toolkit* every later chapter depends on. It opens by
classifying matter (substance vs. mixture, element vs. compound, physical vs. chemical change,
extensive vs. intensive properties) so students can talk precisely about what chemistry studies.
It then turns to measurement — SI units and prefixes, mass, volume, density, and temperature
scales — which gives students the quantities chemists actually measure in the lab.

The second half of the chapter is purely mathematical: scientific notation, significant figures,
accuracy vs. precision, and dimensional analysis. These are not chemistry topics per se, but they
are the single most-reused skill set in the entire course — every gas-law problem, every
stoichiometry calculation, every pH calculation from Chapter 3 onward assumes fluency with unit
conversion and correct significant-figure reporting. A student who leaves Chapter 1 without this
fluency will struggle with the arithmetic of every later chapter, even when the underlying
chemical concept is understood.

## Prerequisites and Later Payoff

| Connection | Concepts needed or enabled | Why it matters |
|---|---|---|
| Prior chapter(s) | None — this is the first chapter | No chemistry background is assumed. |
| This chapter | Matter classification, SI units, density, temperature scales, scientific notation, significant figures, dimensional analysis | Establishes the measurement and unit-conversion toolkit used throughout the course. |
| Later chapter(s) | Ch. 3 Stoichiometry (molar mass, mass↔mole conversion), Ch. 5 Gases (unit-heavy PV = nRT problems), Ch. 12 Solutions (concentration-unit conversions) | Dimensional analysis and significant figures reappear explicitly in these chapters and implicitly in every numeric problem afterward. |

## Core Dependency Chain

- **Classification of matter (substance, mixture, element, compound, physical/chemical change)**
  - This enables: Ch. 2's classification of pure substances into elements, compounds, and ions —
    the same conceptual distinctions, applied at the atomic/molecular level.
- **SI units, mass, volume, density**
  - This enables: Ch. 3 molar mass and mass-mole-particle conversions; Ch. 5 gas density and molar
    mass calculations; any later problem reporting a physical quantity with correct units.
- **Scientific notation and significant figures**
  - This enables: every multi-step numeric calculation in every later chapter — correct
    significant-figure reporting is expected from Chapter 3 onward without re-teaching it.
- **Dimensional analysis**
  - This enables: the unit-factor-label method reused directly in Ch. 3 (stoichiometric
    conversions), Ch. 5 (gas-law unit conversions), and Ch. 12 (concentration-unit conversions).

## Logical Order for Teaching

| Order | Introduce | Reason for placement |
|---|---|---|
| 1 | General Concepts in Chemistry | Purely conceptual; gives vocabulary before any calculation is attempted. |
| 2 | Measurement (units, mass/weight, volume, density, temperature) | Introduces the physical quantities chemists measure, motivating the need for careful numerical treatment. |
| 3 | Numbers (scientific notation, significant figures, accuracy/precision) | Once there are quantities to report, students need the rules for expressing and combining them correctly. |
| 4 | Dimensional Analysis | Capstones the chapter by combining units (Measurement) and numbers (Numbers) into a single problem-solving method used for the rest of the course. |

## Section-Level Concept Map and Objectives

This section is the course's **learning-outcome registry**. Every ID defined below is reused verbatim by the study guide (which badges the bullet or bullets that teach it), by the slide deck, by the assessment guide (which gives each one a full entry with question guides), and by every practice question. Searching all five files for a single ID therefore traces one outcome from concept map to graded question. The QA harness enforces this: any ID declared here and missing from another carrier is a release-blocking failure.

### 1. General Concepts in Chemistry (§1.1)

**Learning objectives:**
- **Objective 1.1a** — Classify matter as a substance or mixture, and identify elements and compounds
- **Objective 1.1b** — Distinguish physical from chemical change, and extensive from intensive properties

**Concept flow:**
- Matter
  - Substance (definite composition) vs. Mixture (variable composition)
    - Mixture → homogeneous or heterogeneous
  - Element (cannot be separated chemically) vs. Compound (fixed-ratio combination of elements)
  - Change matter undergoes
    - Physical change (no new substance) vs. chemical change (new substance formed)
  - Properties used to describe matter
    - Extensive (depends on amount) vs. intensive (independent of amount)

### 2. Measurement (§1.2)

**Learning objectives:**
- **Objective 1.2a** — Use SI base units and prefixes; distinguish mass from weight
- **Objective 1.2b** — Convert volume units and calculate density
- **Objective 1.2c** — Convert temperature between Celsius, Fahrenheit, and Kelvin

**Concept flow:**
- SI system → base units (m, kg, s, A, K, mol, cd) + prefixes (tera- through pico-)
  - Mass (kg) vs. weight (force of gravity on an object)
  - Volume → derived from length (m³), with common lab units (mL, L)
  - Density = mass / volume → links mass and volume measurements
  - Temperature → three interconvertible scales (°C, °F, K)

### 3. Numbers (§1.3)

**Learning objectives:**
- **Objective 1.3a** — Convert to and from scientific notation, and perform arithmetic in scientific notation
- **Objective 1.3b** — Apply significant-figure rules to a measured value
- **Objective 1.3c** — Apply significant-figure rules in calculations, and distinguish accuracy from precision

**Concept flow:**
- Scientific notation (N × 10ⁿ) → a compact way to write very large/small numbers
  - Arithmetic rules differ for addition/subtraction (match exponents) vs. multiplication/division
    (add/subtract exponents)
- Significant figures → rules for zeros, and separate rules for addition/subtraction vs.
  multiplication/division
  - Exact numbers (definitions, counted objects) → infinite significant figures, never limit a
    calculation
- Accuracy (closeness to true value) vs. precision (closeness of repeated measurements to each
  other) → two independent measures of measurement quality
- Reading an instrument → certain digits + one estimated digit

### 4. Dimensional Analysis (§1.4)

**Learning objectives:**
- **Objective 1.4a** — Solve unit-conversion problems using dimensional analysis

**Concept flow:**
- Given quantity (with units) × conversion factor(s) (unit ratios equal to 1) → desired quantity
  (with units)
  - Multiple conversion factors can be chained in a single calculation (e.g., mass → moles →
    volume)

## Common Student Bottlenecks

| Bottleneck | Conceptual repair |
|---|---|
| Miscounting significant figures in numbers with zeros (e.g., 3400 mL, 0.0068 m) | Walk through the explicit zero rules one at a time (leading zeros never count; zeros between nonzero digits always count; trailing zeros after a decimal point always count; trailing zeros with no decimal point are ambiguous — use scientific notation to remove the ambiguity). |
| Treating an exact (counted or defined) number as if it limited significant figures | Explicitly flag exact numbers in a problem (e.g., "2" in a defined ratio, a counted number of objects) as having infinite significant figures before applying sig-fig rules to the rest of the calculation. |
| Mixing up the addition/subtraction sig-fig rule (decimal places) with the multiplication/division rule (total sig figs) | Before rounding a final answer, first identify which operation was performed last, then apply the matching rule. |
| Sign or formula confusion when converting between °C, °F, and K | Anchor to two fixed reference points every time (water freezes at 0 °C/32 °F/273.15 K; the K scale never uses a degree symbol) before plugging into a conversion formula. |
| Losing track of units mid-calculation in a multi-step dimensional-analysis problem | Write every conversion factor explicitly as a fraction with units, and cross out canceling units at each step rather than only at the end. |
