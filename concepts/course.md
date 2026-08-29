# General Chemistry — Course Concept Map

## Source and Scope

**Source of truth:** the instructor's (Yu Wang, University of Louisiana at Lafayette) own lecture
notes, spanning 19 chapters from *Introduction to Chemistry* through *Nuclear Chemistry*. This
mirrors the standard two-semester general chemistry sequence topic order; all prose in the package
is rewritten originally from the underlying facts and equations, not copied from any textbook.

**Scope:** all 19 chapters, kept in their original order (no chapters merged, skipped, or
reordered), packaged as one combined course spanning two semesters.

**Package license:** CC BY 4.0.

**Note:** this file is simple Markdown only — no images, no diagrams, no orz containers — so it
renders correctly anywhere. Per-chapter concept maps (`concepts/<slug>.md`) give the same treatment
at chapter scale.

## Course Summary

This course builds general chemistry from the ground up in three broad movements. The first
movement (Chapters 1–6) establishes how chemists *quantify* matter and its transformations:
measurement and unit reasoning, the atomic/molecular/ionic vocabulary of matter, the mole and
stoichiometry, reaction types in aqueous solution, the behavior of gases, and the energetics of
reactions. The second movement (Chapters 7–12) turns inward to *structure*: why atoms have the
electron arrangements they do, how those arrangements generate the periodic table's trends, how
atoms bond and arrange themselves in space, how the resulting polarity governs intermolecular
attraction, and how all of that structure resurfaces in the behavior of solutions. The third
movement (Chapters 13–19) is about *change and driving force*: how fast reactions go (kinetics),
where they settle (equilibrium, acid-base equilibrium, and the buffer/titration/solubility toolkit
built on it), why they go at all (entropy and free energy), how electron transfer can be harnessed
as electricity (electrochemistry), and finally what happens when the nucleus itself — not just the
electrons — is the site of change (nuclear chemistry).

A single reasoning toolkit recurs throughout: dimensional analysis and significant figures (Ch. 1)
underpin every calculation that follows; the mole concept (Ch. 3) is the currency that converts
between mass, particles, gas volume, solution concentration, heat, and charge; and the ICE-table /
equilibrium-constant method introduced in Chapter 14 is reused, essentially unchanged, through
acid-base chemistry, buffers, titrations, solubility, complex-ion formation, and — via the
free-energy and electrode-potential relationships — thermodynamics and electrochemistry. Seeing
these threads explicitly is what turns 19 chapters of discrete facts into one connected subject.

## Prerequisites and Later Payoff

| Connection | Concepts needed or enabled | Why it matters |
|---|---|---|
| Incoming (nothing prior) | Arithmetic, basic algebra | Ch. 1 assumes no prior chemistry; it builds the measurement/unit toolkit from scratch. |
| This course → itself | Dimensional analysis, the mole, ICE tables, Lewis structures | These three tools, introduced once, are reused with only minor variation in essentially every later chapter (see Core Dependency Chain below). |
| This course → later coursework | Equilibrium reasoning, thermodynamics, electrochemistry, organic functional groups (introduced briefly in Ch. 2) | Directly prerequisite for organic chemistry, analytical chemistry, physical chemistry, and biochemistry. |

## Core Dependency Chain

- **Ch. 1 Introduction (measurement, sig figs, dimensional analysis)**
  - This enables: every numerical calculation in every later chapter — density and unit conversion
    reasoning resurfaces explicitly in Ch. 3 (molar mass), Ch. 5 (gas laws), Ch. 12 (concentration
    units), and implicitly everywhere else.
- **Ch. 2 Atoms, Molecules, and Ions (atomic structure, isotopes, nomenclature)**
  - This enables:
    - Ch. 3 Stoichiometry — chemical formulas are the input to every molar-mass and formula
      calculation.
    - Ch. 4 Aqueous Reactions — naming and formula-writing are assumed when reading reaction
      equations.
    - Ch. 7–8 (electron configuration, periodic table) — atomic number/electron count from Ch. 2
      is what gets organized into shells and subshells.
    - Ch. 19 Nuclear Chemistry — atomic number (Z) and mass number (A) notation is reused directly.
- **Ch. 3 Stoichiometry (mole concept, balancing equations, limiting reagent, yield)**
  - This enables:
    - Ch. 4 Aqueous Reactions — solution stoichiometry is Ch. 3's method applied to molarity.
    - Ch. 5 Gases — gas stoichiometry (moles ↔ volume via PV = nRT) reuses the same mole-bridge logic.
    - Ch. 6 Thermochemistry — converting reaction enthalpies to heat released/absorbed per gram is a
      stoichiometry calculation.
    - Ch. 13 Kinetics — rate expressions are written per mole of reactant/product, mirroring
      stoichiometric coefficients.
- **Ch. 4 Aqueous Reactions (electrolytes, solubility rules, acid-base and redox reaction types,
  molarity)**
  - This enables:
    - Ch. 12 Solutions — molarity is defined here and extended to molality/mole fraction/percent
      mass in Ch. 12.
    - Ch. 15–16 Acid-Base (Equilibria) — the strong/weak acid and base lists and neutralization
      concept introduced here are assumed throughout Ch. 15–16.
    - Ch. 18 Electrochemistry — oxidation-number rules and half-reaction balancing are introduced
      here and formalized/extended in Ch. 18.
- **Ch. 5 Gases (ideal gas law, partial pressures, kinetic molecular theory)**
  - This enables: Ch. 14 Equilibrium — the K_P ↔ K_c conversion uses PV = nRT directly; partial
    pressure reasoning reappears in gas-phase equilibrium problems.
- **Ch. 6 Thermochemistry (ΔH, calorimetry, Hess's law, standard enthalpies of formation)**
  - This enables:
    - Ch. 11 Intermolecular Forces — molar heats of vaporization/fusion/sublimation reuse the same
      q = n·ΔH logic.
    - Ch. 17 Thermodynamics — standard enthalpies of formation and Hess's-law-style addition of
      reactions are reused directly to compute ΔG° and ΔS°.
- **Ch. 7 Quantum Theory (light, photons, Bohr model, quantum numbers, electron configuration)**
  - This enables: Ch. 8 Periodic Table — the electron-configuration and orbital-filling rules built
    here are the mechanism behind every periodic trend in Ch. 8.
- **Ch. 8 Periodic Table (effective nuclear charge, atomic/ionic radius, ionization energy,
  electron affinity, group trends)**
  - This enables:
    - Ch. 9 Chemical Bonding — electronegativity (introduced via the same trends) determines
      ionic vs. polar-covalent vs. covalent bond character.
    - Ch. 15 Acid-Base — oxoacid and hydrohalic-acid strength trends are periodic-trend arguments
      applied to acidity.
- **Ch. 9 Chemical Bonding (Lewis structures, resonance, bond enthalpy, electronegativity)**
  - This enables: Ch. 10 Molecular Geometry — VSEPR and hybridization both start from a correct
    Lewis structure.
- **Ch. 10 Molecular Geometry (VSEPR, dipole moments, valence bond theory, hybridization)**
  - This enables: Ch. 11 Intermolecular Forces — whether a molecule is polar (Ch. 10) determines
    which intermolecular force(s) apply (Ch. 11).
- **Ch. 11 Intermolecular Forces, Liquids, and Solids (IMF types, phase changes, phase diagrams,
  crystal structures)**
  - This enables: Ch. 12 Solutions — solution formation is explained in Ch. 12 entirely in terms of
    solute-solute, solvent-solvent, and solute-solvent intermolecular interactions from Ch. 11.
- **Ch. 12 Solutions (concentration units, colligative properties)**
  - This enables: Ch. 15–16 and Ch. 18 — molarity/molality calculations recur in pH, buffer,
    titration, and Nernst-equation problems.
- **Ch. 13 Chemical Kinetics (rate laws, integrated rate laws, half-life, Arrhenius equation,
  mechanisms, catalysis)**
  - This enables:
    - Ch. 14 Equilibrium — K = k_f / k_r is derived directly from the forward/reverse rate
      expressions of Ch. 13.
    - Ch. 19 Nuclear Chemistry — radioactive decay is a first-order kinetic process; the half-life
      formula from Ch. 13 is reused without modification.
- **Ch. 14 Chemical Equilibrium (K_c, K_p, reaction quotient Q, ICE tables, Le Chatelier's
  principle)**
  - This enables:
    - Ch. 15 Acid-Base — K_a and K_b are equilibrium constants; pH problems are ICE-table problems.
    - Ch. 16 Acid-Base Equilibria — buffers, titrations, K_sp, and K_f all reuse the same
      ICE-table/equilibrium-constant machinery.
    - Ch. 17 Thermodynamics — ΔG° = −RT ln K connects equilibrium directly to free energy.
    - Ch. 18 Electrochemistry — E° = (RT/nF) ln K connects equilibrium directly to cell potential.
- **Ch. 15 Acids and Bases (Brønsted/Lewis definitions, pH, K_a/K_b, acid-base strength trends)**
  - This enables: Ch. 16 — buffers, titration curves, and salt hydrolysis all extend Ch. 15's
    equilibrium calculations to mixtures and multi-step titration problems.
- **Ch. 16 Acid-Base Equilibria and Solubility Equilibria (buffers, titrations, K_sp, complex ions)**
  - Mainly a terminal application chapter; it reinforces the Ch. 14/15 toolkit rather than feeding
    forward to new machinery.
- **Ch. 17 Thermodynamics (entropy, laws of thermodynamics, Gibbs free energy)**
  - This enables: Ch. 18 Electrochemistry — ΔG° = −nFE° links free energy directly to standard
    cell potential, and both connect back to K via Ch. 14's equilibrium constant.
- **Ch. 18 Electrochemistry (redox balancing, galvanic cells, standard reduction potentials, Nernst
  equation, applications)**
  - Synthesizes Ch. 4 (redox reaction types), Ch. 14 (K), and Ch. 17 (ΔG°) into one coherent
    framework; mostly terminal, aside from reinforcing these three chapters.
- **Ch. 19 Nuclear Chemistry (nuclear equations, binding energy, radioactive decay, fission/fusion)**
  - Synthesizes Ch. 2 (atomic number/mass number/isotope notation) and Ch. 13 (first-order kinetics
    and half-life); the course's terminal chapter.

## Logical Order for Teaching

| Order | Introduce | Reason for placement |
|---|---|---|
| 1 | Ch. 1 Introduction | No chemistry content is assumed; establishes the measurement/units/sig-fig toolkit every later chapter needs. |
| 2 | Ch. 2 Atoms, Molecules, and Ions | Gives the vocabulary (atoms, isotopes, ions, formulas, nomenclature) needed to even write a chemical formula. |
| 3 | Ch. 3 Stoichiometry | Introduces the mole, the central quantitative bridge used in every subsequent chapter. |
| 4 | Ch. 4 Aqueous Reactions | Applies stoichiometry to real reaction types (precipitation, acid-base, redox) and introduces molarity. |
| 5 | Ch. 5 Gases | A second physical state to quantify with the mole concept; introduces PV = nRT, needed later for K_p. |
| 6 | Ch. 6 Thermochemistry | Introduces energy bookkeeping (ΔH, Hess's law) once reactions and stoichiometry are established. |
| 7 | Ch. 7 Quantum Theory | Shifts from macroscopic reactions to the electronic structure that explains *why* atoms bond and react as they do. |
| 8 | Ch. 8 Periodic Table | Electron configuration (Ch. 7) is immediately used to explain periodic trends. |
| 9 | Ch. 9 Chemical Bonding | Periodic trends (electronegativity) directly explain ionic vs. covalent bonding. |
| 10 | Ch. 10 Molecular Geometry | Builds on Lewis structures (Ch. 9) to predict 3-D shape and polarity. |
| 11 | Ch. 11 Intermolecular Forces, Liquids, and Solids | Polarity (Ch. 10) determines intermolecular force type, which determines bulk phase behavior. |
| 12 | Ch. 12 Solutions | Solution formation is explained via the intermolecular forces just covered (Ch. 11). |
| 13 | Ch. 13 Chemical Kinetics | Shifts focus from equilibrium composition to the rate at which reactions approach it. |
| 14 | Ch. 14 Chemical Equilibrium | K is derived from the forward/reverse rate constants of Ch. 13. |
| 15 | Ch. 15 Acids and Bases | Applies the general equilibrium toolkit (Ch. 14) to the specific, high-yield case of acid-base chemistry. |
| 16 | Ch. 16 Acid-Base Equilibria and Solubility Equilibria | Extends Ch. 15 to mixtures (buffers), processes (titrations), and other equilibria (K_sp, K_f) using the same method. |
| 17 | Ch. 17 Thermodynamics | Returns to energy (Ch. 6) with the added lens of entropy, explaining *why* reactions are spontaneous — and reconnects to K (Ch. 14) via ΔG° = −RT ln K. |
| 18 | Ch. 18 Electrochemistry | Synthesizes redox (Ch. 4), equilibrium (Ch. 14), and free energy (Ch. 17) into a single quantitative framework. |
| 19 | Ch. 19 Nuclear Chemistry | A capstone that revisits atomic structure (Ch. 2) and first-order kinetics (Ch. 13) in a new context — a fitting close to the sequence. |

**Natural two-semester break:** although this course ships as one combined package, chapters
1–11 (Introduction through Intermolecular Forces/Liquids/Solids) form a natural first-semester
arc ending with the states of matter, and chapters 12–19 (Solutions through Nuclear Chemistry)
form the second-semester arc built on equilibrium, thermodynamics, and electrochemistry.

## Chapter-by-Chapter Objectives

1. **Introduction to Chemistry** — Distinguish matter/substance/mixture/element/compound and
   physical vs. chemical change; use SI units and prefixes; calculate density; convert between
   °C/°F/K; use scientific notation and significant figures correctly in calculations; solve
   problems with dimensional analysis.
2. **Atoms, Molecules, and Ions** — State Dalton's atomic theory and the key historical
   experiments (Thomson, Millikan, Rutherford, Chadwick); relate atomic number, mass number, and
   isotopes; distinguish molecules, ions, and ionic vs. molecular compounds; name ionic compounds,
   molecular compounds, acids, bases, and hydrates.
3. **Stoichiometry** — Calculate atomic, molecular, and formula mass and convert between mass,
   moles, and number of particles; determine percent composition and empirical formula from
   combustion data; balance chemical equations; identify the limiting reagent; calculate
   theoretical and percent yield.
4. **Reactions in Aqueous Solutions** — Classify electrolytes as strong, weak, or non; predict
   precipitation reactions using solubility rules and write net ionic equations; identify
   Brønsted acid-base reactions and common strong/weak acids; assign oxidation numbers and
   classify redox reaction types; calculate molarity and perform dilution and solution
   stoichiometry.
5. **Gases** — Apply Boyle's, Charles's, Avogadro's, and the ideal gas laws; calculate gas
   density and molar mass from P, V, T data; apply Dalton's law of partial pressures; explain gas
   behavior using kinetic molecular theory; use the van der Waals equation to describe deviations
   from ideal behavior.
6. **Thermochemistry** — Distinguish system/surroundings and open/closed/isolated systems;
   apply the first law of thermodynamics (ΔU = q + w); calculate enthalpy changes for reactions;
   use calorimetry (constant-volume and constant-pressure) to measure heat; apply Hess's law and
   standard enthalpies of formation to calculate reaction enthalpies.
7. **Quantum Theory and the Electronic Structure of Atoms** — Relate wavelength, frequency, and
   photon energy; explain the photoelectric effect; describe the Bohr model and atomic emission
   spectra; describe the wave nature of the electron and the four quantum numbers; write ground-
   state electron configurations using the Aufbau principle, Pauli exclusion principle, and
   Hund's rule.
8. **Periodic Relationships Among the Elements** — Classify elements by electron configuration
   (representative, transition, lanthanide/actinide); explain effective nuclear charge; describe
   and predict periodic trends in atomic radius, ionic radius, ionization energy, and electron
   affinity; describe group-by-group chemical behavior and acidic/basic/amphoteric oxide
   character.
9. **Chemical Bonding: Basic Concepts** — Draw Lewis dot symbols and Lewis structures including
   resonance and formal charge; distinguish ionic, polar covalent, and covalent bonds using
   electronegativity difference; explain lattice energy trends; identify exceptions to the octet
   rule; use bond enthalpies to estimate reaction enthalpies.
10. **Molecular Geometry and Bonding Theories** — Predict molecular geometry using VSEPR theory
    for molecules with and without lone pairs on the central atom; determine whether a molecule is
    polar; apply valence bond theory and hybridization (sp, sp², sp³) including molecules with
    double and triple bonds; distinguish sigma and pi bonds.
11. **Intermolecular Forces, Liquids, and Solids** — Identify the intermolecular force(s) present
    in a substance and rank their relative strength; relate intermolecular forces to surface
    tension, viscosity, and water's anomalous properties; classify crystal types and unit cells
    (SCC/BCC/FCC) and calculate coordination numbers; use the Clausius-Clapeyron equation and
    interpret phase diagrams.
12. **Physical Properties of Solutions** — Explain solution formation in terms of intermolecular
    forces and predict solubility using "like dissolves like"; calculate and interconvert mole
    fraction, percent by mass, molarity, and molality; apply Raoult's law and calculate
    boiling-point elevation, freezing-point depression, and osmotic pressure, including for
    electrolyte solutions (van't Hoff factor).
13. **Chemical Kinetics** — Write rate expressions from a balanced equation; determine rate law,
    reaction order, and rate constant from experimental data; apply the integrated rate laws and
    half-life expressions for zero-, first-, and second-order reactions; apply the Arrhenius
    equation; analyze reaction mechanisms, intermediates, and rate-determining steps; describe the
    role of a catalyst.
14. **Chemical Equilibrium** — Write equilibrium constant expressions (K_c, K_p) for homogeneous
    and heterogeneous equilibria and interconvert K_p and K_c; combine equilibrium constants for
    multi-step reactions; calculate and interpret the reaction quotient Q relative to K; use ICE
    tables to solve for equilibrium concentrations; apply Le Chatelier's principle to predict
    equilibrium shifts.
15. **Acids and Bases** — Identify conjugate acid-base pairs and Lewis acids/bases; calculate pH
    and pOH from [H⁺]/[OH⁻]; relate acid/base strength to molecular structure (hydrohalic acids,
    oxoacids); calculate the pH of strong and weak acid/base solutions and of salt solutions using
    hydrolysis; use the K_a·K_b = K_w relationship.
16. **Acid-Base Equilibria and Solubility Equilibria** — Explain how a buffer resists pH change and
    calculate buffer pH with the Henderson-Hasselbalch relationship; calculate pH throughout a
    titration and select an appropriate indicator; calculate and apply K_sp, including the common
    ion effect and predicting precipitation; calculate complex-ion formation using K_f.
17. **Entropy, Free Energy, and Equilibrium** — Explain entropy as a measure of microstates and
    predict the sign of ΔS for a process or reaction; state the laws of thermodynamics; calculate
    and apply Gibbs free energy (ΔG = ΔH − TΔS) to predict spontaneity; relate ΔG° to the
    equilibrium constant K and to non-standard-state ΔG via reaction quotient Q.
18. **Electrochemistry** — Balance redox equations by the half-reaction method in acidic and basic
    solution; describe galvanic cells, cell diagrams, anode/cathode, and standard reduction
    potentials; relate ΔG°, K, and E° for a redox reaction; apply the Nernst equation to
    non-standard conditions and concentration cells; describe corrosion, electrolysis, and common
    battery types.
19. **Nuclear Chemistry** — Balance nuclear equations by mass number and charge conservation;
    calculate nuclear binding energy from mass defect; describe the types of radioactive decay;
    apply first-order kinetics and half-life to radioactive decay and dating problems; distinguish
    nuclear fission from fusion and explain chain reactions and critical mass.

## Common Student Bottlenecks

| Bottleneck | Conceptual repair |
|---|---|
| Sig-fig/unit discipline from Ch. 1 quietly disappears in later numeric chapters | Require units and a sig-fig check on every multi-step numeric answer, in every chapter, not just Ch. 1. |
| Confusing rate-law exponents (Ch. 13) with stoichiometric coefficients | Emphasize explicitly, every time a rate law is written, that exponents are determined experimentally and equal the coefficients *only* for an elementary step. |
| Sign errors in q, w, and ΔH (Ch. 6) | Anchor every calculation to the system's point of view ("heat absorbed *by the system* is positive") with a labeled diagram before plugging into a formula. |
| Mixing up K_c vs. K_p, or Q vs. K (Ch. 14) | Always write which one is being computed and why (K_p needs gas-phase RT conversion; Q uses *initial*, K uses *equilibrium*, values). |
| ICE-table sign or "solvent/pure-solid" omission errors (Ch. 14–16) | Practice writing the equilibrium expression *before* filling in the ICE table, explicitly crossing out pure solids/liquids/solvent. |
| Molarity vs. molality vs. mole fraction confusion (Ch. 12) | Always identify what is held fixed in the denominator (volume of solution vs. mass of solvent vs. total moles) before selecting a formula. |
| Forgetting which acids/bases are strong (Ch. 4, 15) vs. assuming all acids ionize completely | Keep the short memorized strong-acid/strong-base list visibly posted and referenced at the start of every acid-base problem. |
| Reversing anode/cathode or the sign of E°cell (Ch. 18) | Anchor with one fixed rule: the higher standard reduction potential is always the cathode; compute E°cell = E°cathode − E°anode every time, never by inspection. |
| Using the wrong half-life formula for the reaction order (Ch. 13, reused in Ch. 19) | Before using a half-life shortcut, confirm the reaction order — nuclear decay is always first-order, but chemical kinetics problems are not. |

## Keywords and Tags

general chemistry, measurement, significant figures, dimensional analysis, atomic structure,
isotopes, nomenclature, stoichiometry, mole concept, limiting reagent, aqueous reactions,
solubility rules, redox reactions, molarity, gas laws, ideal gas law, kinetic molecular theory,
thermochemistry, enthalpy, Hess's law, calorimetry, quantum theory, photoelectric effect, Bohr
model, quantum numbers, electron configuration, periodic trends, ionization energy, electron
affinity, chemical bonding, Lewis structures, resonance, electronegativity, VSEPR, molecular
geometry, hybridization, sigma and pi bonds, intermolecular forces, hydrogen bonding, phase
diagrams, crystal structures, solutions, colligative properties, osmotic pressure, chemical
kinetics, rate laws, reaction mechanisms, Arrhenius equation, chemical equilibrium, Le Chatelier's
principle, acids and bases, pH, buffers, titrations, solubility equilibria, complex ions,
entropy, Gibbs free energy, thermodynamics, electrochemistry, galvanic cells, standard reduction
potentials, Nernst equation, nuclear chemistry, radioactive decay, nuclear fission, nuclear fusion
