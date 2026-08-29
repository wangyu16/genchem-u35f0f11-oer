# Chapter 17 Concept Map: Entropy, Free Energy, and Equilibrium

## Source and Scope

**Reference:** instructor's own lecture notes (Yu Wang, University of Louisiana at Lafayette),
Chapter 17 (CC BY 4.0). **Audience:** introductory undergraduate general chemistry. **Note:** covers
Entropy, the Laws of Thermodynamics, and Free Energy. Simple Markdown only — no images, diagrams,
or orz containers.

## Chapter Summary

Chapter 17 returns to the energy bookkeeping of Chapter 6 and asks a different question: not "how
much heat," but "why does a reaction happen at all." Entropy (S) is introduced as a measure of the
number of accessible microstates, giving a microscopic definition of disorder and a qualitative
rule of thumb (gas > liquid > solid; more complex molecules have higher entropy). The four laws of
thermodynamics are stated, with the second law — that total universe entropy increases in any
spontaneous process — as the chapter's organizing principle.

Gibbs free energy (G = H − TS) then combines enthalpy (Chapter 6) and entropy into a single
criterion for spontaneity: ΔG < 0 means spontaneous, ΔG > 0 means the reverse reaction is
spontaneous, and ΔG = 0 means equilibrium. The chapter's major payoff is two equations that
reconnect this chapter to the rest of the course: ΔG° = −RT ln K links free energy directly to
Chapter 14's equilibrium constant, and (in Chapter 18) ΔG° = −nFE° will link it to electrode
potential. This chapter is therefore best understood as a *unifying* chapter — it explains, in
energetic terms, why equilibrium constants and spontaneous reaction directions are what they are.

## Prerequisites and Later Payoff

| Connection | Concepts needed or enabled | Why it matters |
|---|---|---|
| Prior chapter(s) | Ch. 6 (enthalpy, Hess's law, standard enthalpies of formation), Ch. 14 (equilibrium constant K) | ΔG = ΔH − TΔS reuses Ch. 6's enthalpy data and Hess's-law-style addition; ΔG° = −RT ln K reconnects directly to Ch. 14's equilibrium constant. |
| This chapter | Entropy, the laws of thermodynamics, Gibbs free energy, ΔG-K relationship, reaction quotient in ΔG = ΔG° + RT ln Q | Supplies the thermodynamic (spontaneity) lens applied to reactions and phase transitions throughout the rest of the course. |
| Later chapter(s) | Ch. 18 Electrochemistry (ΔG° = −nFE° links free energy directly to standard cell potential, closing the loop between thermodynamics, equilibrium, and electrochemistry) | Chapter 18 opens its Nernst-equation section by directly reusing this chapter's ΔG-Q relationship. |

## Core Dependency Chain

- **Entropy (S) and its qualitative trends (state, molecular complexity)**
  - This enables: predicting the sign of ΔS for a reaction or phase change, used throughout the
    Free Energy section of this chapter.
- **The laws of thermodynamics (especially the second law)**
  - This enables: the spontaneity criterion (total entropy of the universe must increase) that
    Gibbs free energy is designed to evaluate without directly calculating surroundings' entropy.
- **Gibbs free energy (ΔG = ΔH − TΔS) and standard free energy of formation**
  - This enables: predicting reaction spontaneity, calculating phase-transition temperatures
    (ΔG = 0), and — via ΔG° = −RT ln K — connecting back to Ch. 14's equilibrium constant.
- **ΔG° = −RT ln K and ΔG = ΔG° + RT ln Q**
  - This enables: Ch. 18 Electrochemistry — the same equilibrium-constant/reaction-quotient
    relationship reappears as ΔG° = −nFE° and the Nernst equation.

## Logical Order for Teaching

| Order | Introduce | Reason for placement |
|---|---|---|
| 1 | Entropy | Introduces the microscopic (microstate) definition of disorder needed before free energy can be discussed quantitatively. |
| 2 | The Laws of Thermodynamics | States the governing principles (especially the second law) that motivate why a combined enthalpy-entropy criterion (free energy) is needed. |
| 3 | Free Energy | Capstones the chapter by combining entropy (Section 1) and enthalpy (Ch. 6) into Gibbs free energy, then connecting it to equilibrium (Ch. 14). |

## Section-Level Concept Map and Objectives

This section is the course's **learning-outcome registry**. Every ID defined below is reused verbatim by the study guide (which badges the bullet or bullets that teach it), by the slide deck, by the assessment guide (which gives each one a full entry with question guides), and by every practice question. Searching all five files for a single ID therefore traces one outcome from concept map to graded question. The QA harness enforces this: any ID declared here and missing from another carrier is a release-blocking failure.

### 1. Entropy (§17.1)

**Learning objectives:**
- **Objective 17.1a** — Define entropy via microstates and predict the sign of ΔS
- **Objective 17.1b** — Calculate the standard entropy of a reaction

**Concept flow:**
- Entropy (S = k ln W) → more accessible microstates means higher entropy
- Entropy trends → gas > liquid > solid; more complex molecules (same state) have higher entropy;
  more gas moles produced generally increases ΔS°rxn
- ΔS°rxn = Σ nS°(products) − Σ mS°(reactants) → calculated the same way as ΔH°rxn (Ch. 6)

### 2. The Laws of Thermodynamics (§17.2)

**Learning objectives:**
- **Objective 17.2a** — State the laws of thermodynamics and explain the second law as the spontaneity criterion
- **Objective 17.2b** — Explain the third law's role in absolute entropy

**Concept flow:**
- Zeroth law (thermal equilibrium is transitive) → first law (energy conservation, from Ch. 6) →
  second law (spontaneous processes increase total universe entropy) → third law (perfect
  crystal at 0 K has zero entropy)
- Second law → the organizing principle: a process is spontaneous only if ΔS_universe > 0
- Third law → enables absolute (not just relative) entropy values to be tabulated

### 3. Free Energy (§17.3)

**Learning objectives:**
- **Objective 17.3a** — Define Gibbs free energy and apply the spontaneity criterion
- **Objective 17.3b** — Calculate standard free energy of reaction
- **Objective 17.3c** — Determine transition temperatures by setting ΔG = 0
- **Objective 17.3d** — Relate ΔG° to the equilibrium constant K
- **Objective 17.3e** — Calculate ΔG under non-standard conditions and predict reaction direction

**Concept flow:**
- Second law (ΔS_universe > 0) → rewritten in terms of the system alone as ΔG_sys < 0 for a
  spontaneous process at constant T and P
- Gibbs free energy (G = H − TS) → ΔG = ΔH − TΔS; sign of ΔG determines spontaneity (< 0
  spontaneous forward; > 0 spontaneous reverse; = 0 equilibrium)
- ΔG°rxn = Σ nΔG°f(products) − Σ mΔG°f(reactants) → same additive method as Ch. 6's ΔH°rxn
- Phase transitions and reaction thresholds → set ΔG = 0 to solve for the transition temperature
- ΔG° = −RT ln K → links free energy to Ch. 14's equilibrium constant; ΔG = ΔG° + RT ln Q →
  predicts spontaneity under non-standard conditions using Q (from Ch. 14)

## Common Student Bottlenecks

| Bottleneck | Conceptual repair |
|---|---|
| Predicting the sign of ΔS incorrectly by focusing only on temperature change rather than state/mole-count change | Anchor ΔS predictions to the two explicit rules: phase (gas > liquid > solid) and change in moles of gas, before considering any other factor. |
| Confusing the spontaneity criterion ΔG_sys < 0 with requiring ΔS_sys > 0 alone | Emphasize explicitly that ΔG combines ΔH and ΔS specifically so that *only the system's* properties need to be checked — a reaction with negative ΔS can still be spontaneous if ΔH is sufficiently negative (or vice versa with temperature). |
| Sign errors when solving ΔG = ΔH − TΔS = 0 for a transition temperature | Have students isolate T algebraically first (T = ΔH/ΔS) before substituting numbers, to avoid mid-calculation sign slips. |
| Confusing ΔG° (fixed value under standard conditions) with ΔG (variable, depends on current Q) | Keep the two symbols and their equations visually distinct: ΔG° = −RT ln K is a single number; ΔG = ΔG° + RT ln Q changes as the reaction proceeds and Q changes. |
| Using the wrong sign convention when relating ΔG° and K (forgetting the negative sign in ΔG° = −RT ln K) | Have students first predict qualitatively whether K should be greater or less than 1 from the sign of ΔG°, then verify the calculated K matches that expectation. |
