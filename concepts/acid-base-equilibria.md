# Chapter 16 Concept Map: Acid-Base Equilibria and Solubility Equilibria

## Source and Scope

**Reference:** instructor's own lecture notes (Yu Wang, University of Louisiana at Lafayette),
Chapter 16 (CC BY 4.0). **Audience:** introductory undergraduate general chemistry. **Note:** covers
Buffer Solutions, Titrations, Solubility Equilibria, and Complex Equilibria. Simple Markdown only —
no images, diagrams, or orz containers.

## Chapter Summary

Chapter 16 is an applications chapter: it introduces no new calculation method beyond Chapter 15's
ICE-table/Ka-Kb toolkit, but applies it to four increasingly practical situations. Buffer solutions
(a weak acid/base together with its conjugate) resist pH change because both species are present to
consume added H⁺ or OH⁻; the Henderson-Hasselbalch equation reframes the same Ka expression
algebraically so buffer pH can be found without solving a quadratic. Titrations extend this further
by tracking pH through an entire addition of titrant, using different reasoning before, at, and
after the equivalence point depending on whether the acid/base is strong or weak — and by
connecting indicator choice to the steepness of the pH jump at equivalence.

The chapter then turns to a structurally identical but conceptually distinct equilibrium: solubility
equilibria, where Ksp plays the same role Ka/Kb played for acids, including the common ion effect
(a specific case of Le Chatelier's principle from Chapter 14) and precipitation prediction (Q vs.
Ksp, mirroring Q vs. K). Complex-ion equilibria (Kf) close the chapter as a final, brief application
of the same equilibrium-constant framework. Because this chapter's content is almost entirely
applied practice rather than new theory, it mainly reinforces Chapters 14–15 rather than feeding
forward into new material.

## Prerequisites and Later Payoff

| Connection | Concepts needed or enabled | Why it matters |
|---|---|---|
| Prior chapter(s) | Ch. 14 (K, Q, ICE tables, Le Chatelier's principle), Ch. 15 (Ka, Kb, pH calculations, conjugate acid-base pairs) | Every calculation in this chapter is Chapter 14–15's toolkit applied to a buffer, a titration, a slightly soluble salt, or a complex ion. |
| This chapter | Buffers, Henderson-Hasselbalch equation, titration curves, indicators, Ksp, common ion effect, Kf | Rounds out the equilibrium sequence with its most common practical applications. |
| Later chapter(s) | None directly — this chapter is largely terminal within the course sequence, reinforcing Ch. 14–15 rather than feeding new machinery forward. | Its value is consolidation: students see the same ICE-table/equilibrium-constant method work across four distinct, realistic scenarios. |

## Core Dependency Chain

- **Buffer solutions and the Henderson-Hasselbalch equation**
  - Reinforces Ch. 15's Ka/ICE-table method; introduces no new later dependency, but is directly
    reused within this chapter for buffer-pH calculations during titrations.
- **Titrations (strong-strong, weak-strong, strong-weak)**
  - Directly reuses buffer-region reasoning (before equivalence) and salt-hydrolysis reasoning (at
    equivalence, from Ch. 15) within the same problem.
- **Solubility equilibria (Ksp, molar solubility, common ion effect, precipitation prediction)**
  - Mirrors Ch. 14's K/Q framework exactly, substituting Ksp/Q_sp for K/Q.
- **Complex-ion equilibria (Kf)**
  - A brief, final application of the same equilibrium-constant framework to metal-ligand
    complexation.

## Logical Order for Teaching

| Order | Introduce | Reason for placement |
|---|---|---|
| 1 | Buffer Solutions | Builds directly on Ch. 15's weak acid/base equilibrium method, adding only the presence of a conjugate salt. |
| 2 | Titrations | Extends buffer reasoning (Section 1) across an entire titration curve, requiring both buffer-region and equivalence-point (salt hydrolysis) reasoning together. |
| 3 | Solubility Equilibria | Shifts to a structurally parallel but distinct equilibrium type (Ksp), reusing the K/Q/ICE-table framework from Ch. 14. |
| 4 | Complex Equilibria | Closes the chapter with a brief, final equilibrium-constant application (Kf), naturally following solubility equilibria as another "specialized K." |

## Section-Level Concept Map and Objectives

This section is the course's **learning-outcome registry**. Every ID defined below is reused verbatim by the study guide (which badges the bullet or bullets that teach it), by the slide deck, by the assessment guide (which gives each one a full entry with question guides), and by every practice question. Searching all five files for a single ID therefore traces one outcome from concept map to graded question. The QA harness enforces this: any ID declared here and missing from another carrier is a release-blocking failure.

### 1. Buffer Solutions (§16.1)

**Learning objectives:**
- **Objective 16.1a** — Explain buffer action and calculate buffer pH
- **Objective 16.1b** — Calculate buffer pH after a stress, and design a buffer at a target pH

**Concept flow:**
- Buffer (weak acid/base + its conjugate, comparable amounts) → acid component neutralizes added
  OH⁻; base component neutralizes added H⁺
- Henderson-Hasselbalch equation (pH = pKa + log([conjugate base]/[acid])) → algebraic
  rearrangement of the Ka expression, avoiding a full ICE-table solve
- Buffer capacity/design → choose an acid whose pKa is close to the target pH so acid and
  conjugate base are present in comparable amounts

### 2. Titrations (§16.2)

**Learning objectives:**
- **Objective 16.2a** — Describe titration pH behavior by acid/base strength combination
- **Objective 16.2b** — Calculate pH at any point during a titration
- **Objective 16.2c** — Select an appropriate acid-base indicator

**Concept flow:**
- Titration progress → before equivalence (buffer-region calculation, Section 1's method); at
  equivalence (salt hydrolysis, Ch. 15's method); after equivalence (excess strong titrant, direct
  calculation)
- Strong-strong titration → pH = 7 at equivalence; weak acid-strong base → pH > 7 at equivalence;
  strong acid-weak base → pH < 7 at equivalence
- Indicator selection → color-change range (pKa ± 1) must fall within the titration curve's steep
  region near the equivalence point

### 3. Solubility Equilibria (§16.3)

**Learning objectives:**
- **Objective 16.3a** — Write Ksp expressions and convert between Ksp and molar solubility
- **Objective 16.3b** — Predict precipitation by comparing Q to Ksp
- **Objective 16.3c** — Calculate solubility with a common ion present

**Concept flow:**
- Ksp (product of ion concentrations, each raised to its stoichiometric coefficient) → analogous
  to K_c from Ch. 14, applied to a dissolution equilibrium
- Molar solubility ↔ Ksp conversion → requires the correct stoichiometric relationship between
  cation and anion concentrations
- Q vs. Ksp (mirrors Ch. 14's Q vs. K) → Q < Ksp unsaturated; Q = Ksp saturated; Q > Ksp
  precipitation occurs
- Common ion effect (an application of Le Chatelier's principle, Ch. 14) → solubility decreases
  when a common ion is already present in solution

### 4. Complex Equilibria (§16.4)

**Learning objectives:**
- **Objective 16.4a** — Define complex ion/formation constant and solve Kf problems

**Concept flow:**
- Complex ion (metal cation, a Lewis acid, + ligands, Lewis bases) → formation constant Kf
  (larger Kf = more stable complex)
- Kf equilibrium problems → same equilibrium-constant/ICE-table framework as every other
  equilibrium type in Ch. 14–16

## Common Student Bottlenecks

| Bottleneck | Conceptual repair |
|---|---|
| Using the full ICE-table method for every buffer-pH calculation instead of recognizing when Henderson-Hasselbalch applies directly | Teach Henderson-Hasselbalch as a shortcut valid specifically when the "x is small" approximation already holds (initial acid/conjugate-base concentrations are both much larger than the equilibrium change), not as a universally different method. |
| Using the wrong calculation method for the titration stage in question (buffer-region vs. equivalence-point vs. post-equivalence) | Require students to explicitly classify which of the three regions a given point falls into *before* selecting a calculation method, rather than defaulting to one approach for the whole curve. |
| Assuming the equivalence point of any acid-base titration is always pH 7 | Tie the equivalence-point pH explicitly to whether the product salt hydrolyzes: only strong acid–strong base titrations give pH 7 at equivalence. |
| Writing the Ksp expression with incorrect stoichiometric exponents (e.g., forgetting to square [OH⁻] for a compound like Ca(OH)₂) | Have students write the dissolution equation with correct coefficients first, then transcribe those coefficients directly as exponents in the Ksp expression. |
| Confusing "more soluble" with "larger Ksp" when comparing compounds with different stoichiometries (e.g., a 1:1 vs. a 1:2 salt) | Emphasize that Ksp values are comparable as a solubility ranking *only* for compounds with the same ion-count stoichiometry; otherwise, molar solubility must be calculated and compared directly. |
