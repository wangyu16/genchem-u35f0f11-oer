# Chapter 14 Concept Map: Chemical Equilibrium

## Source and Scope

**Reference:** instructor's own lecture notes (Yu Wang, University of Louisiana at Lafayette),
Chapter 14 (CC BY 4.0). **Audience:** introductory undergraduate general chemistry. **Note:** covers
Chemical Equilibrium, Equilibrium Constants (homogeneous, heterogeneous, multi-step reactions),
Reaction Quotient, Equilibrium Concentrations (ICE tables), and Le Chatelier's Principle. Simple
Markdown only — no images, diagrams, or orz containers.

## Chapter Summary

Chapter 14 introduces the idea that most reactions do not go to completion but instead settle at a
dynamic balance point where forward and reverse rates are equal — connecting directly to Chapter
13's kinetics, since K = k_f/k_r. It develops the equilibrium constant expression (K_c for
concentrations, K_p for gas-phase partial pressures, interconvertible via PV = nRT from Chapter 5),
distinguishes homogeneous from heterogeneous equilibria (pure solids/liquids omitted from the
expression), and shows that equilibrium constants for summed reactions multiply (an equilibrium
analog of Chapter 6's Hess's law).

The chapter's central problem-solving tool is the reaction quotient Q (compared to K to predict
reaction direction) and the ICE table (Initial-Change-Equilibrium) method for solving for unknown
equilibrium concentrations. Le Chatelier's principle then supplies qualitative predictions for how
a system at equilibrium responds to stress (concentration, pressure/volume, or temperature
changes). This chapter's K_c/K_p/Q/ICE-table toolkit is the foundation for essentially all of
Chapters 15–16 (acid-base and solubility equilibria are the same method applied to specific
equilibrium types) and reconnects to Chapter 17 (ΔG° = −RT ln K) and Chapter 18 (E° related to K).

## Prerequisites and Later Payoff

| Connection | Concepts needed or enabled | Why it matters |
|---|---|---|
| Prior chapter(s) | Ch. 13 (forward/reverse rate constants), Ch. 5 (PV = nRT, for K_p ↔ K_c conversion), Ch. 6 (Hess's-law-style reasoning, for multi-step K) | K is defined from Ch. 13's rate constants; K_p/K_c conversion and multi-step K calculations directly reuse earlier chapters' math. |
| This chapter | Equilibrium constant (K_c, K_p), reaction quotient Q, ICE tables, Le Chatelier's principle | Supplies the equilibrium-constant framework and ICE-table method reused throughout the rest of the course. |
| Later chapter(s) | Ch. 15 Acids and Bases (K_a/K_b are equilibrium constants), Ch. 16 Acid-Base Equilibria (buffers, titrations, K_sp, K_f all reuse ICE tables), Ch. 17 Thermodynamics (ΔG° = −RT ln K), Ch. 18 Electrochemistry (E° related to K) | Nearly every later equilibrium-type calculation in the course is this chapter's method applied to a new context. |

## Core Dependency Chain

- **Equilibrium constant expression (K_c, K_p) and homogeneous/heterogeneous equilibria**
  - This enables: Ch. 15–16 — K_a, K_b, K_sp, and K_f are all specific names for the same
    equilibrium-constant concept.
- **Reaction quotient Q and comparison to K**
  - This enables: predicting reaction direction in any later equilibrium problem, including
    acid-base, buffer, and solubility contexts.
- **ICE tables**
  - This enables: essentially every quantitative acid-base, buffer, titration, and solubility
    calculation in Ch. 15–16.
- **Le Chatelier's principle**
  - This enables: qualitative equilibrium-shift reasoning reused in Ch. 15–16 (e.g., common ion
    effect) and Ch. 17 (temperature effect on spontaneity).

## Logical Order for Teaching

| Order | Introduce | Reason for placement |
|---|---|---|
| 1 | Chemical Equilibrium | Establishes the core idea (forward rate = reverse rate) and connects it to Chapter 13's rate constants. |
| 2 | Equilibrium Constants | Builds the K_c/K_p expression and the rules for homogeneous/heterogeneous and multi-step reactions. |
| 3 | Reaction Quotient | Introduces Q as a diagnostic tool, requiring K's definition (Section 2) first. |
| 4 | Equilibrium Concentrations | Applies K (Section 2) via the ICE-table method to solve for unknown concentrations — the chapter's central problem-solving skill. |
| 5 | Le Chatelier's Principle | Closes the chapter with qualitative predictions, best understood only after the quantitative machinery (Sections 2–4) is in place. |

## Section-Level Concept Map and Objectives

This section is the course's **learning-outcome registry**. Every ID defined below is reused verbatim by the study guide (which badges the bullet or bullets that teach it), by the slide deck, by the assessment guide (which gives each one a full entry with question guides), and by every practice question. Searching all five files for a single ID therefore traces one outcome from concept map to graded question. The QA harness enforces this: any ID declared here and missing from another carrier is a release-blocking failure.

### 1. Chemical Equilibrium (§14.1)

**Learning objectives:**
- **Objective 14.1a** — Derive and apply K = k_f/k_r, including the effect of reversing a reaction
- **Objective 14.1b** — Interpret the magnitude of K

**Concept flow:**
- Forward rate = reverse rate at equilibrium (from Ch. 13) → K = k_f/k_r
- K expression (products over reactants, each raised to its coefficient) → dimensionless
- Reversing a reaction → K becomes its reciprocal

### 2. Equilibrium Constants (§14.2)

**Learning objectives:**
- **Objective 14.2a** — Write and convert K_c/K_p for homogeneous gas-phase equilibria
- **Objective 14.2b** — Write equilibrium expressions for liquid-phase and heterogeneous equilibria
- **Objective 14.2c** — Combine equilibrium constants for multi-step reactions

**Concept flow:**
- Homogeneous equilibria (all species same phase) → K_c (concentrations) or K_p (partial
  pressures), related by K_p = K_c(RT)^Δn (from PV = nRT, Ch. 5)
- Heterogeneous equilibria (multiple phases) → pure solids/liquids omitted from the expression
- Multi-step reactions (reaction 3 = reaction 1 + reaction 2) → K₃ = K₁ × K₂ (equilibrium analog
  of Hess's law, Ch. 6)

### 3. Reaction Quotient (§14.3)

**Learning objectives:**
- **Objective 14.3a** — Calculate Q and compare to K to predict reaction direction

**Concept flow:**
- Q (same expression as K, but with initial/current concentrations rather than equilibrium
  concentrations) → compare to K
  - Q > K → reaction proceeds in reverse; Q = K → at equilibrium; Q < K → reaction proceeds forward

### 4. Equilibrium Concentrations (§14.4)

**Learning objectives:**
- **Objective 14.4a** — Set up and solve an ICE table for equilibrium concentrations
- **Objective 14.4b** — Apply and validate the small-x approximation

**Concept flow:**
- ICE table (Initial, Change, Equilibrium rows) → express equilibrium concentrations in terms of a
  single unknown, x, using stoichiometric coefficients for the Change row
- Substitute equilibrium-row expressions into the K expression → solve for x → back-calculate all
  equilibrium concentrations

### 5. Le Chatelier's Principle (§14.5)

**Learning objectives:**
- **Objective 14.5a** — Apply Le Chatelier's principle across all stress types

**Concept flow:**
- Le Chatelier's principle (system partially offsets an applied stress) → predicts shift direction
  for each stress type
  - Concentration/pressure/volume changes → shift equilibrium position, but K unchanged
  - Temperature changes → shift equilibrium AND change the value of K itself (endothermic
    direction favored by increased temperature)
  - Catalyst → speeds up approach to equilibrium but does not shift it or change K

## Common Student Bottlenecks

| Bottleneck | Conceptual repair |
|---|---|
| Including pure solids, pure liquids, or solvent in an equilibrium expression | Require students to explicitly cross out any pure solid/liquid/solvent species before writing the final K expression, every time. |
| Confusing Q and K, or comparing them without first calculating both correctly | Emphasize the defining difference explicitly: Q uses whatever concentrations are given (often *not* at equilibrium); K uses equilibrium concentrations only. |
| Forgetting to convert K_p to K_c (or vice versa) when the problem's units don't match the given K | Check the phase and units of the given data against the K provided; if they don't match, apply K_p = K_c(RT)^Δn before proceeding. |
| Sign or algebra errors in the ICE table when x appears with a coefficient other than 1 | Have students write out the balanced equation's coefficients above each ICE-table column before filling in the Change row, so the correct multiple of x is used automatically. |
| Believing a catalyst shifts equilibrium position or increases yield | State explicitly, every time catalysts are discussed: a catalyst changes only the *rate* of reaching equilibrium, never the equilibrium position or the value of K. |
