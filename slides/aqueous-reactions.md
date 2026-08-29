<!-- deck
title: Chapter 4: Reactions in Aqueous Solutions
ratio: 16:9
-->

<!-- slide template=title -->
# Reactions in Aqueous Solutions
## Three families, one set of concentration tools
**General Chemistry, Chapter 4**

<!-- slide 2col -->
## Chapter Learning Objectives
<!-- @left -->
- **Objective 4.1a** — Classify solutes as strong, weak, or nonelectrolytes
- **Objective 4.2a** — Apply solubility rules to predict whether a compound is soluble
- **Objective 4.2b** — Write molecular, ionic, and net ionic equations for precipitation reactions
- **Objective 4.3a** — Distinguish Arrhenius and Brønsted acid/base definitions, and identify common strong and weak acids
- **Objective 4.3b** — Write net ionic equations for neutralization reactions
<!-- @right -->
- **Objective 4.4a** — Determine oxidation numbers
- **Objective 4.4b** — Classify types of redox reactions and use the activity series
- **Objective 4.5a** — Calculate molarity and apply the dilution equation
- **Objective 4.5b** — Apply solution stoichiometry (including ion concentration from a compound's molarity)

<!-- slide template=outline -->
## Roadmap
1. General properties of aqueous solutions
2. Precipitation reactions
3. Acid-base reactions
4. Oxidation-reduction reactions
5. Solution stoichiometry

<!-- slide -->
## Chapter Logic
{{mermaid
graph TD
  A["Electrolytes:<br/>strong, weak, nonelectrolyte"] --> B["Three reaction families:<br/>precipitation, acid-base, redox"]
  B --> C["Molarity and dilution:<br/>M = mol solute / L solution"]
  C --> D["Solution stoichiometry:<br/>titrations, gravimetric analysis"]
}}
**Visual description:** electrolyte classification underlies three reaction families; molarity and dilution give the quantitative tools; solution stoichiometry (titration, gravimetric analysis) applies them.

<!-- slide template=section -->
# 1. General Properties of Aqueous Solutions

<!-- slide -->
## Why some solutions conduct
![Strong, weak and nonelectrolyte compared](https://alembic.orz.how/d/doc-od59d9n53t0c =820x)
A solution conducts only if it contains **free ions** — neutral molecules cannot carry current

<!-- slide -->
## Dissolving, at the particle level
![Ionic lattice dissolving into hydrated ions](https://alembic.orz.how/d/doc-s9x9j9qj2f0h =800x)
**Hydration:** polar water turns its negative end toward cations, its positive end toward anions

<!-- slide -->
## Electrolytes
- Strong: dissociates completely (soluble salts, strong acids/bases)
- Weak: dissociates partially (weak acids/bases)
- Nonelectrolyte: doesn't conduct at all

<!-- slide template=section -->
# 2. Precipitation Reactions

<!-- slide -->
## Key solubility rules
- Alkali metal, $\ce{NH4+}$: always soluble
- $\ce{NO3-}$, $\ce{ClO3-}$, $\ce{HCO3-}$: always soluble
- $\ce{Cl-/Br-/I-}$: soluble except Ag salts
- $\ce{SO4^2-}$: soluble except $\ce{BaSO4}$
- $\ce{OH-/CO3^2-}$: insoluble except alkali/$\ce{NH4+}$

<!-- slide -->
## Precipitation reaction
![Precipitation reaction](https://alembic.orz.how/d/doc-po7khc0bq9sm =620x)
Only $\ce{Ag+}$ and $\ce{Cl-}$ react — $\ce{Na+}$ and $\ce{NO3-}$ are spectators

<!-- slide step -->
## Worked example — net ionic equation
$\ce{AgNO3 + NaCl -> AgCl(s) + NaNO3}$
- Dissociate strong electrolytes{{attrs[.fragment]}}
- Cancel $\ce{Na+}$, $\ce{NO3-}$ spectators{{attrs[.fragment]}}
- **$\ce{Ag+(aq) + Cl-(aq) -> AgCl(s)}$**{{attrs[.fragment]}}

<!-- slide template=section -->
# 3. Acid-Base Reactions

<!-- slide -->
## Acid-base definitions
- Arrhenius acid: produces $\ce{H+}$ in water
- Arrhenius base: produces $\ce{OH-}$ in water
- Brønsted acid: proton donor · Brønsted base: proton acceptor

<!-- slide -->
## Common strong acids
$\ce{HCl}$, $\ce{HNO3}$, $\ce{H2SO4}$, $\ce{HBr}$, $\ce{HI}$, $\ce{HClO4}$, $\ce{HClO3}$ — all ionize completely
:::warning
$\ce{HSO4-}$ (from the second ionization of $\ce{H2SO4}$) is itself only a **weak** acid.
:::

<!-- slide step -->
## Worked example — weak acid neutralization
$\ce{HCN + NaOH -> NaCN + H2O}$
- $\ce{HCN}$ is weak: stays undissociated{{attrs[.fragment]}}
- Cancel only $\ce{Na+}${{attrs[.fragment]}}
- **$\ce{HCN + OH- -> CN- + H2O}$**{{attrs[.fragment]}}

<!-- slide template=section -->
# 4. Oxidation-Reduction Reactions

<!-- slide -->
## Oxidation and reduction
![Electron transfer Na to F](https://alembic.orz.how/d/doc-yizfw6lrpz84 =430x)
One electron moves; both atoms end with a neon octet (2, 8)
Oxidation = electron loss · Reduction = electron gain — always paired

<!-- slide -->
## Oxidation number as a scale
![Oxidation number line with a worked assignment](https://alembic.orz.how/d/doc-7au6eddlqcq3 =800x)
Number goes **up** = oxidation · number goes **down** = reduction

<!-- slide -->
## Oxidation-number rules
1. Free element = 0
2. Monatomic ion = its charge
3. H usually +1, O usually −2
4. Group 1A = +1, 2A = +2, F always −1
5. Sum = 0 (neutral) or net charge (ion)

<!-- slide -->
## Types of redox reactions
- Combination, decomposition, combustion
- Displacement (H, metal, or halogen)
- Disproportionation (same element, both oxidized and reduced)

<!-- slide -->
## The activity series
![Activity series](https://alembic.orz.how/d/doc-paer7277t7vh =340x)
A metal displaces any less-active metal below it

<!-- slide step -->
## Metal displacement in action
![Displaced copper](https://alembic.orz.how/d/doc-v5wdgyhqoj08 =340x)
Iron (more active) displaces copper from $\ce{CuCl2}$ solution:{{attrs[.fragment]}}
**$\ce{Fe(s) + CuCl2(aq) -> FeCl2(aq) + Cu(s)}$**{{attrs[.fragment]}}

<!-- slide template=section -->
# 5. Solution Stoichiometry

<!-- slide -->
## Dilution: the moles stay put
![Same solute, larger volume](https://alembic.orz.how/d/doc-4lx533p53kxn =780x)
$M_iV_i = M_fV_f$ — because adding water adds no solute

<!-- slide -->
## Molarity and dilution
$$M=\frac{\text{mol solute}}{\text{L solution}} \qquad M_iV_i=M_fV_f$$

<!-- slide step -->
## Worked example — mass needed for a solution
250 mL of 0.283 mol/L glucose ($\ce{C6H12O6}$, 180.18 g/mol)
- $0.250\,\text{L}\times0.283\,\text{mol/L}=0.0708$ mol{{attrs[.fragment]}}
- **$\times180.18$ g/mol = 12.7 g**{{attrs[.fragment]}}

<!-- slide step -->
## Worked example — dilution
50 mL of 1.00 mol/L HCl from 3.92 mol/L stock
- $V_i=\dfrac{1.00\times50}{3.92}$ {{attrs[.fragment]}}
- **= 12.8 mL** of stock, diluted to 50 mL{{attrs[.fragment]}}

<!-- slide -->
## Gravimetric analysis and titration
- Gravimetric: precipitate, filter, dry, weigh → find unknown amount
- Titration: add known-concentration solution to unknown until equivalence point (indicator signals it)

<!-- slide -->
## Titration
![Titration apparatus and the equivalence point](https://alembic.orz.how/d/doc-hdq1ic53wa36 =800x)
The **equivalence point** is a fact about the chemistry; the **endpoint** is what the indicator shows you

<!-- slide template=closing -->
# One toolkit, three reaction families
Electrolyte classification determines how a reaction is written in ionic form; precipitation, acid-base, and redox each have their own predictive rule; molarity and dilution are the shared quantitative language across all three, carried forward into solutions (Ch. 12) and acid-base equilibria (Ch. 16).
