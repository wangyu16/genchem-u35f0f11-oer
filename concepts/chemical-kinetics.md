# Chapter 13 Concept Map: Chemical Kinetics

## Source and Scope

**Reference:** instructor's own lecture notes (Yu Wang, University of Louisiana at Lafayette),
Chapter 13 (CC BY 4.0). **Audience:** introductory undergraduate general chemistry. **Note:** covers
Rate of Reaction and Rate Law, Reaction Orders (first, second, zero), Temperature Effect
(collision theory, Arrhenius equation), Reaction Mechanisms, and Catalysis. Simple Markdown only —
no images, diagrams, or orz containers.

## Chapter Summary

Chapter 13 asks how fast a reaction proceeds, opening a new axis of chemical reasoning distinct
from the "how much" questions of Chapter 3 and the "what state" questions of Chapters 5 and 11. It
defines reaction rate from a balanced equation, then introduces the experimentally-determined rate
law (rate = k[A]ˣ[B]ʸ), stressing that the exponents x and y must come from data, not from the
balanced equation's coefficients. Each reaction order (zero, first, second) then gets its own
integrated rate law and half-life formula, giving students a graphical method (plotting [A], ln[A],
or 1/[A] vs. time) for determining order from data.

The chapter then explains *why* rate depends on temperature via collision theory and the Arrhenius
equation, connecting macroscopic rate constants to microscopic activation energy. Reaction
mechanisms show how an overall reaction can be built from elementary steps, with the
rate-determining step controlling the observed rate law, and the chapter closes with catalysis
(rate enhancement without net consumption). This chapter's first-order kinetics and half-life
formula are reused, essentially unchanged, in Chapter 19 for radioactive decay, and its
"forward/reverse rate constants" framing is the direct bridge to Chapter 14's equilibrium constant
(K = k_f/k_r).

## Prerequisites and Later Payoff

| Connection | Concepts needed or enabled | Why it matters |
|---|---|---|
| Prior chapter(s) | Ch. 3 (balanced equations, stoichiometric coefficients) | Rate expressions are written using the same coefficients as balancing, though the rate *law* exponents are independent of them. |
| This chapter | Rate law, reaction order, integrated rate laws, half-life, Arrhenius equation, reaction mechanisms, rate-determining step, catalysis | Establishes how reaction rate is measured, modeled, and explained mechanistically. |
| Later chapter(s) | Ch. 14 Chemical Equilibrium (K = k_f/k_r derived from forward/reverse rates), Ch. 19 Nuclear Chemistry (radioactive decay reuses first-order kinetics and half-life directly) | Both chapters reuse this chapter's mathematics without re-deriving it from scratch. |

## Core Dependency Chain

- **Rate law and reaction order (determined experimentally)**
  - This enables: the integrated rate laws and half-life formulas used to solve concentration-vs-
    time problems in this chapter and in Ch. 19.
- **Integrated rate laws and half-life (zero, first, second order)**
  - This enables: Ch. 19 Nuclear Chemistry — radioactive decay is always first-order, and the
    exact half-life formula (t₁/₂ = ln2/k) from this chapter is reused directly.
- **Collision theory and the Arrhenius equation**
  - This enables: calculating rate constants at different temperatures and activation energies —
    a self-contained but frequently reused calculation type.
- **Reaction mechanisms and rate-determining step**
  - This enables: Ch. 14 Chemical Equilibrium — the idea of forward and reverse elementary
    reactions with their own rate constants (k_f, k_r) is the direct conceptual bridge to defining
    the equilibrium constant K = k_f/k_r.

## Logical Order for Teaching

| Order | Introduce | Reason for placement |
|---|---|---|
| 1 | Rate of Reaction and Rate Law | Establishes how to express and measure reaction rate before any mathematical model is introduced. |
| 2 | Reaction Orders | Builds the integrated rate laws and half-life relationships needed to extract quantitative information from concentration-vs-time data. |
| 3 | Temperature Effect | Explains why rate constants themselves depend on temperature, a natural next question once rate laws are established. |
| 4 | Reaction Mechanisms | Explains *why* a particular rate law is observed, connecting macroscopic kinetics to a molecular-level step-by-step picture. |
| 5 | Catalysis | Closes the chapter with a practical application (rate enhancement) that draws on the mechanism concept from Section 4. |

## Section-Level Concept Map and Objectives

This section is the course's **learning-outcome registry**. Every ID defined below is reused verbatim by the study guide (which badges the bullet or bullets that teach it), by the slide deck, by the assessment guide (which gives each one a full entry with question guides), and by every practice question. Searching all five files for a single ID therefore traces one outcome from concept map to graded question. The QA harness enforces this: any ID declared here and missing from another carrier is a release-blocking failure.

### 1. Rate of Reaction and Rate Law (§13.1)

**Learning objectives:**
- **Objective 13.1a** — Write rate expressions from a balanced equation
- **Objective 13.1b** — Determine a rate law and rate constant from experimental data

**Concept flow:**
- Balanced equation → rate expression (rate = −(1/a)Δ[A]/Δt = … = (1/d)Δ[D]/Δt)
- Rate law (rate = k[A]ˣ[B]ʸ) → exponents x, y determined experimentally, NOT from stoichiometric
  coefficients a, b
- Method of initial rates → compare experiments where only one concentration changes at a time to
  isolate each exponent

### 2. Reaction Orders (§13.2)

**Learning objectives:**
- **Objective 13.2a** — Apply integrated rate laws
- **Objective 13.2b** — Calculate half-life and determine order graphically

**Concept flow:**
- Order determines both the integrated rate law's form ([A] vs. t, ln[A] vs. t, or 1/[A] vs. t)
  and its half-life formula
  - Zero-order: [A]ₜ = [A]₀ − kt; half-life = [A]₀/2k
  - First-order: ln[A]ₜ = ln[A]₀ − kt; half-life = ln2/k (constant, independent of concentration)
  - Second-order: 1/[A]ₜ = 1/[A]₀ + kt; half-life = 1/(k[A]₀)
- Which plot is linear (concentration, ln concentration, or inverse concentration vs. time)
  identifies the reaction order from experimental data

### 3. Temperature Effect (§13.3)

**Learning objectives:**
- **Objective 13.3a** — Apply collision theory concepts
- **Objective 13.3b** — Apply the Arrhenius equation

**Concept flow:**
- Collision theory → rate ∝ collision frequency AND fraction of collisions with energy ≥
  activation energy (Ea)
- Arrhenius equation (k = Ae^(−Ea/RT)) → quantifies how k depends on temperature and Ea
  - Two-temperature form (ln(k₁/k₂) = (Ea/R)(1/T₂ − 1/T₁)) → solve for Ea or an unknown rate
    constant

### 4. Reaction Mechanisms (§13.4)

**Learning objectives:**
- **Objective 13.4a** — Analyze reaction mechanisms
- **Objective 13.4b** — Interpret a potential-energy profile

**Concept flow:**
- Overall reaction = sum of elementary steps; species that cancel are intermediates (formed then
  consumed)
- Elementary-step rate law → written directly from molecularity (no experimental determination
  needed, unlike overall rate laws)
- Rate-determining step (the slowest elementary step) → determines the observed overall rate law
- Potential-energy profile → maxima = transition states (number = number of steps); minima
  (excluding reactants/products) = intermediates; the step with the largest activation energy is
  rate-determining

### 5. Catalysis (§13.5)

**Learning objectives:**
- **Objective 13.5a** — Explain catalysis and distinguish catalyst types

**Concept flow:**
- Catalyst → provides an alternative pathway with lower activation energy for both forward and
  reverse reactions, without appearing in the overall balanced equation
- Three types (heterogeneous, homogeneous, enzyme) → classified by phase relationship between
  catalyst and reactants

## Common Student Bottlenecks

| Bottleneck | Conceptual repair |
|---|---|
| Assuming rate-law exponents equal the balanced equation's stoichiometric coefficients | State explicitly, every time a rate law is introduced: exponents come from experimental data and equal stoichiometric coefficients *only* for an elementary step. |
| Selecting the wrong integrated rate law or half-life formula for the reaction's actual order | Require students to confirm reaction order (from a linearized plot or given rate law) before selecting an integrated rate law or half-life formula — never assume first-order by default. |
| Forgetting that first-order half-life is constant, while zero- and second-order half-lives depend on [A]₀ | Have students explicitly check whether the half-life formula depends on [A]₀ before assuming successive half-lives are equal. |
| Confusing activation energy with the reaction's overall ΔH (thermodynamic quantity) | Keep the potential-energy profile picture central: Ea is measured relative to reactants (or intermediates) up to a transition state peak, while ΔH compares only reactants to final products. |
| Assuming the rate-determining step must be the first step in a mechanism | Emphasize that the rate-determining step is identified by having the largest activation energy on the potential-energy profile — it can occur at any point in the mechanism. |
