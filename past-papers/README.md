# CHEM1043 past papers: learn the workflows first

Start with a representative question, discover the missing step, consult only the relevant lecture pages, and retry without notes. This is a workflow-first study guide, not a set of official solutions or a prediction of the next examination.

## Corpus and honest limits

The guide maps all six question blocks in each of four retrieved papers: May 2020, December 2020, May 2021 and May 2022. All four are two-hour, 100-mark, open-book examinations with six compulsory questions. Their format is historical evidence, not authorization to use notes in your current examination. See [sources and unavailable records](SOURCES.md) for the source record of each paper.

ExamBase returned 20 course records. Four showed online PDF access and were retrieved; each of the other 16 records was opened and explicitly marked restricted access. No question descriptions or frequencies were inferred for those restricted papers. No past-paper PDF was linked on the inspected Moodle course page.

## How to use the index

- **Priority status:** `true` identifies a representative diagnostic inside that workflow. Multiple priority rows cover genuinely different branches, not a ranking of predicted exam questions.
- **Status:** every row begins `Not solved`. Change it only after you can perform and check that question independently. Reading this guide does not make a question solved.
- **Rows versus papers:** a row can bundle several explicitly labelled subparts. Workflow frequency is the number of listed row bundles; distinct-paper count counts each paper once. Neither is a mark total or a probability.
- **Source labels:** a question label points to the corresponding original PDF. Printed labels and diagrams take precedence over OCR; for example, 2022 Q2(b) compares NO⁺ with N₂⁺.
- **Practice loop:** attempt the priority row closed-notes, diagnose the blocked step, read the targeted lecture section, redo the question, then try a different row in the same group. Finally mix questions from different groups so that you must choose the workflow yourself.

## Workflow frequency

| Workflow | Rows | Distinct papers / 4 |
|---|---:|---:|
| [W01 · Gas measurements → moles → composition or stoichiometry](#w01) | 7 | 4 |
| [W04 · Electron count → MO diagram → bond and magnetic properties](#w04) | 5 | 4 |
| [W12 · Reaction data or K → Gibbs energy → direction and equilibrium](#w12) | 5 | 4 |
| [W06 · Gas solubility and partial pressure → Henry's-law calculation](#w06) | 4 | 4 |
| [W07 · Vapour pressure → mole fraction → concentration or molar mass](#w07) | 4 | 4 |
| [W08 · Particle concentration → freezing, boiling or osmotic pressure](#w08) | 4 | 4 |
| [W09 · Dissolution stoichiometry and pH → solubility](#w09) | 4 | 4 |
| [W10 · Precipitation boundary → separation, amount or buffer requirement](#w10) | 4 | 4 |
| [W15 · Balanced cell reaction ↔ E° ↔ ΔG° and K](#w15) | 4 | 3 |
| [W05 · Band occupancy and band gap → electrical conductivity](#w05) | 3 | 3 |
| [W02 · Ideal-gas assumptions → real-gas corrections](#w02) | 2 | 2 |
| [W03 · Temperature and mass → speed, energy or effusion](#w03) | 2 | 2 |
| [W11 · Complex formation → free metal-ion concentration](#w11) | 2 | 2 |
| [W16 · Nonstandard concentrations and material balance → Nernst potential](#w16) | 2 | 2 |
| [W13 · Specified thermodynamic path → heat, work and entropy](#w13) | 2 | 1 |
| [W14 · Two equilibrium temperatures → van't Hoff enthalpy](#w14) | 1 | 1 |
| [W17 · Molarity and density → molality](#w17) | 1 | 1 |
| [W18 · Temperature-dependent solubility → recrystallization explanation](#w18) | 1 | 1 |

The frequent broad families are not interchangeable shortcuts. For instance, W08 contains osmotic and freezing/boiling branches, while W10 contains selective precipitation, mixed-solution precipitation and buffer control; use the branch cues rather than memorizing a single formula.

## Representative-question route

For an initial diagnostic, work through W01 → W04 → W06 → W07 → W08 → W09 → W10 → W12 → W15. Each appears in at least three of the four retrieved papers, but that is a historical observation only. Then cover W02/W03/W05/W11/W16 and the less frequent W13/W14/W17/W18; low frequency does not mean outside the current syllabus.

Do not skip electrochemistry merely because its lecture slides are not yet linked in the current Moodle snapshot. The topic is in the syllabus and appears as Q6 in all four retrieved papers; only the electrode-potential reference is presently collected.

<a id="w01"></a>
## W01 · Gas measurements → moles → composition or stoichiometry

7 rows · 4 distinct papers. Lecture reference: Topic 1; Tutorial 1; browse the [Moodle-material index](../lectures/README.md).

Recognition cues: P, V and T; gas density or flask masses; wet gas; mixture composition; a decomposing solid.

Minimum prerequisites: Moles, balanced equations, empirical formulas, mole fractions and Kelvin temperatures.

### Workflow

1. Write what the measured pressure represents. For gas collected over water, first use \(P_{gas}=P_{total}-P_{H_2O}\). Convert all units to match the chosen gas constant.
2. Use \(n=PV/(RT)\). For a fixed amount, use \(P_1V_1/T_1=P_2V_2/T_2\). For molar mass use \(M=mRT/(PV)\), with vapour mass equal to filled-flask mass minus empty-flask mass.
3. For composition, take a 100 g basis, turn mass percentages into mole ratios, obtain an empirical formula, and compare its mass with the gas-derived molar mass. For a mixture, calculate each component's moles, then \(P_i=x_iP_{total}\).
4. For a gas-producing reaction, use the balanced mole ratio before converting to solid mass or percentage. Keep the measured volume separate from a volume requested at different conditions.

Common traps: Mass percentages are not mole fractions. Do not use °C in gas equations or blindly subtract water vapour when the question does not describe wet collection.

Check your work: Check that partial pressures sum to the total, formula multipliers are near integers, and a mass percentage lies between 0 and 100.

### Question bank

| # | Source | Question description | Status | Priority status |
|---:|---|---|---|---|
| 1 | [2020-May, Q1(b)(i–iv)](papers/CHEM1043-2020-May.pdf) | Four ideal-gas calculations: pressure, volume, mass and amount. | Not solved | false |
| 2 | [2020-Dec, Q1(a)(i)](papers/CHEM1043-2020-Dec.pdf) | Vapour molar mass from evacuated and filled flask masses. | Not solved | false |
| 3 | [2020-Dec, Q1(a)(ii)](papers/CHEM1043-2020-Dec.pdf) | A fixed amount of nitrogen changes volume at constant pressure. | Not solved | false |
| 4 | [2021-May, Q1(a)](papers/CHEM1043-2021-May.pdf) | Turn gas-mixture mass composition into partial pressures. | Not solved | true: practice 1, 2, 3, 5, 6, 7 |
| 5 | [2021-May, Q1(b)](papers/CHEM1043-2021-May.pdf) | Correct oxygen collected over water and convert its conditions. | Not solved | true: practice 1, 2, 3, 4, 6, 7 |
| 6 | [2022-May, Q1(a)](papers/CHEM1043-2022-May.pdf) | Combine gas molar mass with elemental composition to identify a molecular formula. | Not solved | true: practice 1, 2, 3, 4, 5, 7 |
| 7 | [2022-May, Q1(b)](papers/CHEM1043-2022-May.pdf) | Find chlorate mass percentage from oxygen evolved on heating. | Not solved | false |

<a id="w02"></a>
## W02 · Ideal-gas assumptions → real-gas corrections

2 rows · 2 distinct papers. Lecture reference: Topic 1; browse the [Moodle-material index](../lectures/README.md).

Recognition cues: Kinetic-molecular postulates; high pressure or low temperature; van der Waals constants a and b.

Minimum prerequisites: Ideal-gas equation and the physical meaning of intermolecular attractions and finite molecular volume.

### Workflow

1. List the idealizations relevant to the question: negligible molecular volume, negligible intermolecular forces, random motion and elastic collisions.
2. At high pressure, excluded molecular volume becomes important; at low temperature, attractions become important relative to kinetic energy.
3. Use \((P+a n^2/V^2)(V-nb)=nRT\). If finding temperature, rearrange to \(T=(P+a n^2/V^2)(V-nb)/(nR)\).
4. Calculate the ideal-gas result separately and explain the discrepancy in terms of the two corrections, rather than assuming all real gases always have pressure below the ideal value.

Common traps: The pressure correction uses n²/V², not n/V; a and b must match the pressure and volume units. Avoid claiming one correction dominates at every condition.

Check your work: As a and b approach zero, the equation must reduce to PV=nRT; V must exceed nb.

### Question bank

| # | Source | Question description | Status | Priority status |
|---:|---|---|---|---|
| 8 | [2020-May, Q1(a)(i–ii)](papers/CHEM1043-2020-May.pdf) | Kinetic-molecular postulates and the assumptions that fail at high pressure/low temperature. | Not solved | false |
| 9 | [2020-Dec, Q1(b)(i–iii)](papers/CHEM1043-2020-Dec.pdf) | Use van der Waals to find temperature, compare the ideal value and explain real-gas behaviour. | Not solved | true: practice 8 |

<a id="w03"></a>
## W03 · Temperature and mass → speed, energy or effusion

2 rows · 2 distinct papers. Lecture reference: Topic 1; browse the [Moodle-material index](../lectures/README.md).

Recognition cues: rms speed; kinetic energy per atom; two gases at the same temperature; equal-time effusion.

Minimum prerequisites: Distinguish molar mass from molecular mass and energy per mole from energy per molecule.

### Workflow

1. For rms speed use \(u_{rms}=\sqrt{3RT/M}\), with M in kg mol⁻¹ when R is in SI units. At equal temperature, the speed ratio is the inverse square-root mass ratio.
2. Average translational energy per molecule is \(3k_BT/2\); per mole it is \(3RT/2\). Equal temperature implies equal average translational kinetic energy, not equal speed.
3. For an effusion comparison at equal conditions use \(r_A/r_B=\sqrt{M_B/M_A}\). In equal times, replace rates by escaped amounts, and convert molecule counts to moles when requested.
4. For equal speeds at different temperatures, set T/M equal for the two gases and solve the ratio before inserting numbers.

Common traps: Do not invert Graham's ratio or use molar mass in g mol⁻¹ in an SI speed calculation.

Check your work: A lighter gas must move or effuse faster at the same temperature.

### Question bank

| # | Source | Question description | Status | Priority status |
|---:|---|---|---|---|
| 10 | [2021-May, Q1(c)(i–iii)](papers/CHEM1043-2021-May.pdf) | Connect helium energy and speed to oxygen speed and nitrogen temperature. | Not solved | true: practice 11 |
| 11 | [2022-May, Q1(c)](papers/CHEM1043-2022-May.pdf) | Use nitrogen effusion to find the molar amount of hydrogen escaping in the same time. | Not solved | true: practice 10 |

<a id="w04"></a>
## W04 · Electron count → MO diagram → bond and magnetic properties

5 rows · 4 distinct papers. Lecture reference: Topic 2; Tutorial 2; browse the [Moodle-material index](../lectures/README.md).

Recognition cues: Diatomic molecules or ions; draw an MO diagram; compare bond order, magnetism or bond length; explain MO versus VB.

Minimum prerequisites: Atomic valence configurations, ion charges, Pauli exclusion and Hund's rule.

### Workflow

1. Count valence electrons for each species, adding electrons for a negative charge and subtracting for a positive charge. State whether 1s/core orbitals are omitted.
2. Choose the appropriate MO energy ordering. The relative σ2p and π2p ordering changes across the second period; heteronuclear atomic orbital energies are unequal. Label atomic and molecular sides, energy direction, and bonding/antibonding orbitals.
3. Fill from low energy upwards using Pauli and Hund. Calculate \(BO=(N_{bonding}-N_{antibonding})/2\). Count unpaired electrons for the magnetic property.
4. Explain related-species bond-length/strength changes through occupation of bonding or antibonding orbitals. For conceptual questions, contrast localized VB overlap with orbitals delocalized over the molecule, and constructive with destructive overlap.

Common traps: A single memorized orbital ordering is not valid for every species. Bond order alone is not a universal length ranking across different atom pairs. The 2022 species are NO⁺ and N₂⁺; OCR can corrupt the second label.

Check your work: Electron totals must match the charge; paramagnetism requires at least one unpaired electron.

### Question bank

| # | Source | Question description | Status | Priority status |
|---:|---|---|---|---|
| 12 | [2020-May, Q2(a)(i–ii)](papers/CHEM1043-2020-May.pdf) | Draw B₂ and F₂ diagrams, assign properties, and explain the different MO ordering. | Not solved | true: practice 13, 14, 15, 16 |
| 13 | [2020-Dec, Q2(a)(i–iii)](papers/CHEM1043-2020-Dec.pdf) | MO diagrams and bond/property comparisons for Be₂⁻, CO and O₂⁺. | Not solved | false |
| 14 | [2021-May, Q2(a)(i–iv)](papers/CHEM1043-2021-May.pdf) | Explain σ/π and bonding/antibonding orbitals, then analyse CN⁻. | Not solved | false |
| 15 | [2022-May, Q2(a)](papers/CHEM1043-2022-May.pdf) | Explain the essential VB-versus-MO description of a covalent bond. | Not solved | true: practice 12, 13, 14, 16 |
| 16 | [2022-May, Q2(b)(i–iv)](papers/CHEM1043-2022-May.pdf) | Draw and compare NO⁺ and N₂⁺ configurations, bond orders, magnetism and lengths. | Not solved | false |

<a id="w05"></a>
## W05 · Band occupancy and band gap → electrical conductivity

3 rows · 3 distinct papers. Lecture reference: Topic 2; browse the [Moodle-material index](../lectures/README.md).

Recognition cues: Metals, silicon, magnesium, semiconductors or the formation of bands.

Minimum prerequisites: Many atomic orbitals produce closely spaced levels; electrons need accessible empty states.

### Workflow

1. Explain how combining orbitals from many atoms produces bands of closely spaced energy levels.
2. Draw occupied and available states: a partly filled band or overlapping bands for a conductor, a small gap for a semiconductor, and a large gap for an insulator.
3. Relate conductivity to mobile carriers and accessible states, not merely the number of valence electrons. For Mg, discuss band overlap; for intrinsic semiconductors, discuss thermal excitation across a small gap.

Common traps: An isolated-atom filled shell is not sufficient to declare a solid insulating. Label valence band, conduction band and gap on the sketch.

Check your work: Your drawing must explain where a promoted or moving electron can go.

### Question bank

| # | Source | Question description | Status | Priority status |
|---:|---|---|---|---|
| 17 | [2020-May, Q2(b)(i–ii)](papers/CHEM1043-2020-May.pdf) | Define bands and compare potassium and silicon band structures. | Not solved | true: practice 18, 19 |
| 18 | [2020-Dec, Q2(b)](papers/CHEM1043-2020-Dec.pdf) | Explain why magnesium conducts using band theory. | Not solved | false |
| 19 | [2021-May, Q2(b)](papers/CHEM1043-2021-May.pdf) | Explain semiconductor conductivity using band theory. | Not solved | false |

<a id="w06"></a>
## W06 · Gas solubility and partial pressure → Henry's-law calculation

4 rows · 4 distinct papers. Lecture reference: Topic 3; Tutorial 3; browse the [Moodle-material index](../lectures/README.md).

Recognition cues: Dissolved oxygen/nitrogen/carbon dioxide; gas volume per water volume; minimum atmospheric pressure.

Minimum prerequisites: Molarity, partial pressure and ideal-gas conversion.

### Workflow

1. Read the convention and units of the given Henry constant. For \(c=k_Hp\), kH has concentration/pressure units; some sources use its reciprocal.
2. Convert gas-volume solubility into moles using the temperature and pressure at which that gas volume is reported, then divide by solution volume. Convert mg L⁻¹ to mol L⁻¹ when needed.
3. Use the solute gas's partial pressure, not total air pressure. At fixed temperature, \(c_2/c_1=p_2/p_1\); in air \(p_i=y_iP\).
4. For gas released on heating, calculate dissolved moles before and after using the relevant solubilities, subtract them, then use PV=nRT for the released gas at its stated measurement conditions.

Common traps: Do not confuse the solution temperature with the reporting conditions of a quoted gas volume. Henry's constant changes with temperature. The reporting pressure in 2022 Q3(a) is not explicitly stated; record any assumption rather than inventing certainty.

Check your work: At the same temperature a lower partial pressure must give a lower dissolved concentration.

### Question bank

| # | Source | Question description | Status | Priority status |
|---:|---|---|---|---|
| 20 | [2020-May, Q3(b)](papers/CHEM1043-2020-May.pdf) | Use nitrogen's atmospheric partial pressure to scale dissolved molarity. | Not solved | false |
| 21 | [2020-Dec, Q3(a)(i–ii)](papers/CHEM1043-2020-Dec.pdf) | Convert oxygen volume solubility, raise pressure, then calculate gas expelled on heating. | Not solved | true: practice 20, 22, 23 |
| 22 | [2021-May, Q3(a)(i–iii)](papers/CHEM1043-2021-May.pdf) | Convert a fish-life oxygen threshold to ppm and find minimum oxygen/air pressure. | Not solved | true: practice 20, 21, 23 |
| 23 | [2022-May, Q3(a–b)](papers/CHEM1043-2022-May.pdf) | Convert reported gas solubilities to molarity and scale carbon dioxide to its air partial pressure. | Not solved | false |

<a id="w07"></a>
## W07 · Vapour pressure → mole fraction → concentration or molar mass

4 rows · 4 distinct papers. Lecture reference: Topic 3; browse the [Moodle-material index](../lectures/README.md).

Recognition cues: A nonvolatile solute; solvent vapour-pressure lowering; an unknown molar mass.

Minimum prerequisites: Moles and mole fractions, not mass fractions.

### Workflow

1. For an ideal solution containing a nonvolatile solute, use \(P=x_{solvent}P^*\). If solving an inverse problem, obtain x_solvent from P/P* first.
2. Convert the solvent mass to moles. Then \(n_{solute}=n_{solvent}(1/x_{solvent}-1)\), followed by \(M_{solute}=m_{solute}/n_{solute}\).
3. For a forward problem, calculate both mole amounts, form x_solvent, and multiply by the pure-solvent vapour pressure. Vapour-pressure lowering is P*−P.

Common traps: Mass fraction is not mole fraction. Both volatile components require a two-component Raoult calculation, not the nonvolatile-solute shortcut.

Check your work: For a nonvolatile solute in this ideal model, 0<P<P* and mole fractions sum to 1.

### Question bank

| # | Source | Question description | Status | Priority status |
|---:|---|---|---|---|
| 24 | [2020-May, Q3(c)](papers/CHEM1043-2020-May.pdf) | Find solute molar mass from measured aqueous vapour-pressure lowering. | Not solved | false |
| 25 | [2020-Dec, Q3(b)](papers/CHEM1043-2020-Dec.pdf) | Calculate water vapour pressure and its lowering for ethylene glycol solution. | Not solved | false |
| 26 | [2021-May, Q3(b)(i–ii)](papers/CHEM1043-2021-May.pdf) | Use ethanol's vapour pressure to infer mole fractions and solute molar mass. | Not solved | true: practice 24, 25, 27 |
| 27 | [2022-May, Q3(d)](papers/CHEM1043-2022-May.pdf) | Calculate vapour pressure of ethanol containing benzoic acid. | Not solved | false |

<a id="w08"></a>
## W08 · Particle concentration → freezing, boiling or osmotic pressure

4 rows · 4 distinct papers. Lecture reference: Topic 3; browse the [Moodle-material index](../lectures/README.md).

Recognition cues: Freezing-point depression; boiling-point elevation; osmotic pressure; particle-based rankings.

Minimum prerequisites: Molality uses kilograms of solvent; molarity uses litres of solution; dissociation changes particle counts.

### Workflow

1. Choose the branch: \(\Delta T_f=iK_fm\), \(\Delta T_b=iK_bm\), or \(\Pi=iCRT\). Write the original pure-solvent temperature before applying the change.
2. For an unknown molar mass, infer molality or molarity from the measured property, then moles and M=mass/moles. For a molecular formula, compare the inferred molar mass with the elemental unit mass.
3. For ranking, compare i×molality under the question's dissociation assumptions. The largest particle molality gives the lowest freezing point.
4. For mass-percent solutions, take a 100 g solution basis and distinguish solvent mass from total solution mass.

Common traps: A freezing point goes down, not up. Use consistent pressure units in Π=CRT. Do not assume complete dissociation unless appropriate or explicitly stated.

Check your work: An inferred i should be physically plausible; a non-electrolyte has i≈1 in the ideal dilute model.

### Question bank

| # | Source | Question description | Status | Priority status |
|---:|---|---|---|---|
| 28 | [2020-May, Q3(d)](papers/CHEM1043-2020-May.pdf) | Calculate freezing and boiling points of a 50 mass-percent antifreeze solution. | Not solved | false |
| 29 | [2020-Dec, Q3(c)](papers/CHEM1043-2020-Dec.pdf) | Find unknown molar mass from osmotic pressure. | Not solved | true: practice 28, 30, 31 |
| 30 | [2021-May, Q3(c)](papers/CHEM1043-2021-May.pdf) | Determine sulfur molar mass and molecular formula from freezing-point depression. | Not solved | true: practice 28, 29, 31 |
| 31 | [2022-May, Q3(c)](papers/CHEM1043-2022-May.pdf) | Rank electrolyte/non-electrolyte freezing points using complete dissociation. | Not solved | false |

<a id="w09"></a>
## W09 · Dissolution stoichiometry and pH → solubility

4 rows · 4 distinct papers. Lecture reference: Topic 4, part 1; browse the [Moodle-material index](../lectures/README.md).

Recognition cues: Ksp, molar solubility, common ions, fixed pH, or whether acid increases solubility.

Minimum prerequisites: Balanced dissolution equations, equilibrium products and Kw.

### Workflow

1. Write the dissolution equation before the Ksp expression. For a salt M_aX_b with no pre-existing ions, use [M]=a s and [X]=b s, so \(K_{sp}=(as)^a(bs)^b\).
2. With a common ion, include its initial concentration and the dissolution contribution before making a small-s approximation. For fixed pH obtain [H⁺], then [OH⁻] from Kw when required.
3. For hydroxides use their correct powers: for M(OH)₂, Ksp=[M²⁺][OH⁻]². Solubility s is not the same quantity or unit as Ksp.
4. For qualitative acid effects, ask whether H⁺ consumes the dissolved anion or ligand and thereby drives dissolution. Compare the anion's acid-base chemistry rather than using a blanket rule that all salts dissolve in acid.

Common traps: Do not set every dissolved-ion concentration equal to s. Check the approximation after calculating s and do not treat a buffered pH as changing freely.

Check your work: Substitute the final ion concentrations back into Ksp; a common ion normally decreases solubility in the simple model.

### Question bank

| # | Source | Question description | Status | Priority status |
|---:|---|---|---|---|
| 32 | [2020-May, Q4(a)](papers/CHEM1043-2020-May.pdf) | Find Fe(OH)₃ solubility at a buffered pH. | Not solved | false |
| 33 | [2020-Dec, Q4(a)(i–iii)](papers/CHEM1043-2020-Dec.pdf) | Compare Mg(OH)₂ solubility in water, MgCl₂ and KOH. | Not solved | true: practice 32, 34, 35 |
| 34 | [2021-May, Q4(a–b)](papers/CHEM1043-2021-May.pdf) | Distinguish solubility from Ksp and calculate common-ion solubilities. | Not solved | false |
| 35 | [2022-May, Q4(b)](papers/CHEM1043-2022-May.pdf) | Explain why CuS and AgCl respond differently to acid. | Not solved | true: practice 32, 33, 34 |

<a id="w10"></a>
## W10 · Precipitation boundary → separation, amount or buffer requirement

4 rows · 4 distinct papers. Lecture reference: Topic 4, part 1; class-practice answers; browse the [Moodle-material index](../lectures/README.md).

Recognition cues: Mix solutions; precipitate first; separate ions; maximum reagent before a second salt appears; suppress precipitation with a buffer.

Minimum prerequisites: Dilution, ionic-product expressions, stoichiometric material balances and basic buffer equilibria.

### Workflow

1. After mixing, calculate ion amounts and divide by the total volume. Form Qsp and compare it with Ksp: precipitation is favoured when Qsp>Ksp.
2. For selective precipitation, set Qsp=Ksp separately for each salt to obtain its threshold reagent-ion concentration. Compare thresholds, not bare Ksp values of differently stoichiometric salts.
3. At the onset of the unwanted precipitate, use its threshold reagent concentration in the first salt's Ksp to find how much target ion remains.
4. For the amount precipitated, impose material balances with a precipitated amount variable and the final Ksp condition. A limiting-reagent estimate may need an equilibrium residual correction.
5. For a buffer preventing hydroxide precipitation, derive the maximum [OH⁻] from Ksp and the diluted metal concentration, then use the NH₃/NH₄⁺ equilibrium to find required NH₄⁺. Convert ion moles to salt moles using the salt's stoichiometry.

Common traps: Do not forget dilution or assume 'no precipitate' merely because a salt is sparingly soluble. A buffer-control question adds an acid-base step rather than replacing the Ksp threshold.

Check your work: The proposed separation window must exist; verify Qsp for both salts at your selected reagent concentration.

### Question bank

| # | Source | Question description | Status | Priority status |
|---:|---|---|---|---|
| 36 | [2020-May, Q4(b)(i–ii)](papers/CHEM1043-2020-May.pdf) | State separation criteria and compare CuI/PbI₂ precipitation thresholds. | Not solved | false |
| 37 | [2020-Dec, Q4(b)](papers/CHEM1043-2020-Dec.pdf) | Test mixed AgNO₃/K₂CrO₄ for precipitation and determine precipitate amount. | Not solved | true: practice 36, 38, 39 |
| 38 | [2021-May, Q4(c)](papers/CHEM1043-2021-May.pdf) | Find ammonium sulfate needed to prevent Mg(OH)₂ precipitation in ammonia. | Not solved | true: practice 36, 37, 39 |
| 39 | [2022-May, Q4(a)](papers/CHEM1043-2022-May.pdf) | Maximise AgBr precipitation without precipitating AgCl. | Not solved | true: practice 36, 37, 38 |

<a id="w11"></a>
## W11 · Complex formation → free metal-ion concentration

2 rows · 2 distinct papers. Lecture reference: Topic 4, part 2; browse the [Moodle-material index](../lectures/README.md).

Recognition cues: A metal in excess NH₃; large formation constant; free uncomplexed ion requested.

Minimum prerequisites: Formation equilibrium, ligand stoichiometry and mass balances.

### Workflow

1. Write \(M+qL\rightleftharpoons ML_q\) and \(K_f=[ML_q]/([M][L]^q)\). Distinguish total metal from free metal.
2. If Kf is large and ligand is in excess, estimate [MLq]≈total metal, but subtract q times the complex concentration from the total ligand concentration.
3. Calculate free metal with \([M]\approx[ML_q]/(K_f[L]_{free}^q)\), then check that it is small compared with total metal.
4. If solid dissolution and complexation are coupled, add the reactions and multiply their equilibrium constants; solve a single consistent mass balance.

Common traps: Initial ligand concentration is not necessarily free ligand concentration. The ligand exponent is q, and adding a metal salt does not mean its free-ion concentration equals total metal.

Check your work: For 2022 Q4(c), the large-Kf approximation leaves about 1.20−4×0.20=0.40 M free NH₃, not 1.20 M.

### Question bank

| # | Source | Question description | Status | Priority status |
|---:|---|---|---|---|
| 40 | [2020-May, Q4(c)](papers/CHEM1043-2020-May.pdf) | Find free copper(II) after dissolving copper nitrate in excess ammonia. | Not solved | false |
| 41 | [2022-May, Q4(c)](papers/CHEM1043-2022-May.pdf) | Find free copper(II) accounting for ammonia consumed in the tetraammine complex. | Not solved | true: practice 40 |

<a id="w12"></a>
## W12 · Reaction data or K → Gibbs energy → direction and equilibrium

5 rows · 4 distinct papers. Lecture reference: Topic 5, parts 1–2; browse the [Moodle-material index](../lectures/README.md).

Recognition cues: Tabulated formation data; reaction entropy/enthalpy; K, Q, spontaneity, equilibrium composition or maximum non-expansion work.

Minimum prerequisites: Balanced reactions, reaction quotients and the distinction between standard and actual conditions.

### Workflow

1. Balance the reaction first. For tabulated quantities use products minus reactants, including every stoichiometric coefficient. Calculate ΔH°, ΔS° or ΔG°f sums as required; convert J and kJ consistently.
2. Use \(\Delta G^\circ=\Delta H^\circ-T\Delta S^\circ=-RT\ln K\). For actual conditions, write the dimensionless reaction quotient and use \(\Delta G=\Delta G^\circ+RT\ln Q=RT\ln(Q/K)\).
3. If Q<K the forward direction is favoured; if Q>K the reverse direction is favoured. Pure solids and pure liquids have unit activity and do not appear in Q.
4. For final composition set up an ICE/material-balance table and enforce Q=K. A numerical equilibrium constant does not permit setting every species equal.
5. Maximum useful non-expansion work delivered by a reversible process at fixed T and P is −ΔG for that process. At an already equilibrated mixture the reaction ΔG is zero; ΔG° need not be zero. State which conditions a work answer assumes.

Common traps: A positive ΔG° does not prohibit a forward reaction under nonstandard conditions. Do not use Celsius, forget stoichiometric powers, or call −RT ln K the actual ΔG at equilibrium.

Check your work: Signs must agree: K>1 implies ΔG°<0; Q=K implies ΔG=0. Be explicit about the terse work wording in 2020 May Q5(ii).

### Question bank

| # | Source | Question description | Status | Priority status |
|---:|---|---|---|---|
| 42 | [2020-May, Q5(i–iv)](papers/CHEM1043-2020-May.pdf) | Use equilibrium composition to obtain K, discuss work/direction, and solve a new equilibrium composition. | Not solved | false |
| 43 | [2020-Dec, Q5(a)(i–iv)](papers/CHEM1043-2020-Dec.pdf) | Find ΔS°, ΔH°, ΔG° and K from thermodynamic data. | Not solved | true: practice 42, 44, 45, 46 |
| 44 | [2020-Dec, Q5(b)(i–ii)](papers/CHEM1043-2020-Dec.pdf) | Relate mercury oxide equilibrium to oxygen pressure and conditions favouring decomposition. | Not solved | false |
| 45 | [2021-May, Q5(iv)](papers/CHEM1043-2021-May.pdf) | Balance silver sulfate precipitation and obtain ΔG° and K from formation data. | Not solved | false |
| 46 | [2022-May, Q5(c)](papers/CHEM1043-2022-May.pdf) | Calculate standard and actual Gibbs energies for N₂O₄ dissociation and infer direction. | Not solved | true: practice 42, 43, 44, 45 |

<a id="w13"></a>
## W13 · Specified thermodynamic path → heat, work and entropy

2 rows · 1 distinct papers. Lecture reference: Topic 5, part 1; prerequisite first-law review; browse the [Moodle-material index](../lectures/README.md).

Recognition cues: Reversible/isothermal gas expansion; heating at constant pressure; q, w, ΔU, ΔH or ΔS.

Minimum prerequisites: First-law sign convention and heat capacities.

### Workflow

1. State the sign convention: ΔU=q+w with work done on the system positive. An ideal gas's U and H depend only on temperature.
2. For reversible isothermal expansion, \(w=-nRT\ln(V_2/V_1)\), q=−w and ΔU=ΔH=0.
3. For isothermal ideal-gas entropy change, \(\Delta S=nR\ln(V_2/V_1)\). For heating at fixed pressure with constant Cp, \(\Delta S=nC_{p,m}\ln(T_2/T_1)\).
4. For a combined ideal-gas state change, a reversible reference path gives \(\Delta S=nC_{V,m}\ln(T_2/T_1)+nR\ln(V_2/V_1)\); do not use q/T for an arbitrary irreversible process.

Common traps: Use natural logarithms and Kelvin. A heat capacity described as molar must be multiplied by n. Reversible and irreversible work are not interchangeable.

Check your work: Isothermal expansion has w<0 and ΔS>0; check q+w=0.

### Question bank

| # | Source | Question description | Status | Priority status |
|---:|---|---|---|---|
| 47 | [2022-May, Q5(a)](papers/CHEM1043-2022-May.pdf) | Calculate heat, work and energy changes in reversible isothermal ideal-gas expansion. | Not solved | true: practice 48 |
| 48 | [2022-May, Q5(b)(i–ii)](papers/CHEM1043-2022-May.pdf) | Calculate entropy changes for isothermal expansion and constant-pressure heating. | Not solved | true: practice 47 |

<a id="w14"></a>
## W14 · Two equilibrium temperatures → van't Hoff enthalpy

1 rows · 1 distinct papers. Lecture reference: Topic 5, part 2; browse the [Moodle-material index](../lectures/README.md).

Recognition cues: Two K values at different temperatures; compare inferred ΔH° with formation-data ΔH°.

Minimum prerequisites: Natural logarithms, Kelvin and reaction enthalpy sums.

### Workflow

1. Label (T1,K1) and (T2,K2) explicitly and convert both temperatures to Kelvin.
2. Use \(\ln(K_2/K_1)=-(\Delta H^\circ/R)(1/T_2-1/T_1)\) and solve for ΔH°.
3. Independently calculate the reaction enthalpy from formation data and stoichiometric coefficients. Compare the two estimates and the assumption that ΔH° is approximately constant over the temperature range.

Common traps: Do not mix log10 with ln or invert only one ratio. Report the temperature interval and the constant-enthalpy assumption.

Check your work: If K decreases as temperature rises, the inferred reaction enthalpy should be negative.

### Question bank

| # | Source | Question description | Status | Priority status |
|---:|---|---|---|---|
| 49 | [2021-May, Q5(i–iii)](papers/CHEM1043-2021-May.pdf) | Use two Kp values to infer reaction enthalpy and compare with formation-data estimates. | Not solved | true: only retrieved example |

<a id="w15"></a>
## W15 · Balanced cell reaction ↔ E° ↔ ΔG° and K

4 rows · 3 distinct papers. Lecture reference: Topic 6 syllabus; electrode-potential reference; browse the [Moodle-material index](../lectures/README.md).

Recognition cues: A voltaic cell, standard reduction potentials, theoretical battery voltage, or K from a cell.

Minimum prerequisites: Oxidation/reduction half-equations and balanced electron transfer.

### Workflow

1. Write both half-reactions as reductions to compare tabulated values. Choose the cathode reduction and reverse the anode reaction; balance electron numbers to obtain n and the full cell equation.
2. Use \(E^\circ_{cell}=E^\circ_{cathode}-E^\circ_{anode}\). Multiplying a half-equation does not multiply its electrode potential.
3. Use \(\Delta G^\circ=-nFE^\circ\) and \(\ln K=nFE^\circ/(RT)\). In the reverse direction, obtain ΔG° from formation data and then E°=−ΔG°/(nF).
4. For a cell sketch include the electrodes, solutions, external electron path and ionic connection; electrons flow externally from anode to cathode in a galvanic cell.

Common traps: Do not confuse the sign of an electrode potential with the electrode's name, or scale volts with reaction coefficients. n is the electron count of the balanced overall reaction.

Check your work: A spontaneous standard cell has E°>0, ΔG°<0 and K>1. The silver-zinc cell transfers two electrons per written overall reaction.

### Question bank

| # | Source | Question description | Status | Priority status |
|---:|---|---|---|---|
| 50 | [2020-May, Q6(i–v)](papers/CHEM1043-2020-May.pdf) | Balance a chromium/vanadium cell and link standard potential, Gibbs energy and K. | Not solved | true: practice 51, 52, 53 |
| 51 | [2021-May, Q6](papers/CHEM1043-2021-May.pdf) | Compute silver-zinc battery voltage from thermodynamic formation data. | Not solved | true: practice 50, 52, 53 |
| 52 | [2022-May, Q6(a)(i–iii)](papers/CHEM1043-2022-May.pdf) | Sketch and analyse a chromium/silver voltaic cell. | Not solved | false |
| 53 | [2022-May, Q6(b)](papers/CHEM1043-2022-May.pdf) | Use cell potentials to find reaction Gibbs energy and assess spontaneity. | Not solved | false |

<a id="w16"></a>
## W16 · Nonstandard concentrations and material balance → Nernst potential

2 rows · 2 distinct papers. Lecture reference: Topic 6 syllabus; electrode-potential reference; browse the [Moodle-material index](../lectures/README.md).

Recognition cues: Cell notation contains concentrations; potential as a cell runs; find concentration at a specified E.

Minimum prerequisites: Balanced cell equation, reaction quotient and logarithms.

### Workflow

1. Write and balance the cell reaction in the direction represented by the cell notation, then obtain E° and n.
2. Build Q from the balanced reaction, omitting pure solids/liquids. Use \(E=E^\circ-(RT/nF)\ln Q\), or at 298 K \(E=E^\circ-(0.05916/n)\log_{10}Q\).
3. If the cell runs, update both half-cell compositions using the same reaction extent and the actual solution volumes. State any equal-volume assumption if the paper omits the volumes.
4. For an inverse problem first solve for Q from the target E, then combine that ratio with the material balance. Assess spontaneity from the calculated E in the written direction.

Common traps: Do not use initial Q after the cell has run, invert Q without reversing the reaction, or apply 0.05916 at every temperature.

Check your work: As a galvanic cell approaches equilibrium, E tends to zero and Q tends to K.

### Question bank

| # | Source | Question description | Status | Priority status |
|---:|---|---|---|---|
| 54 | [2020-Dec, Q6(i–iv)](papers/CHEM1043-2020-Dec.pdf) | Track a tin/lead cell's potential and concentrations as it operates. | Not solved | true: practice 55 |
| 55 | [2022-May, Q6(c)](papers/CHEM1043-2022-May.pdf) | Use nonstandard silver/mercury concentrations to test spontaneity. | Not solved | false |

<a id="w17"></a>
## W17 · Molarity and density → molality

1 rows · 1 distinct papers. Lecture reference: Topic 3; browse the [Moodle-material index](../lectures/README.md).

Recognition cues: A solution is specified by molarity and density but molality is requested.

Minimum prerequisites: Mass of solution equals density times volume; solvent mass excludes the solute.

### Workflow

1. Take 1.000 L of solution: the molarity directly gives solute moles.
2. Multiply density by 1000 mL to obtain solution mass. Subtract solute moles times molar mass to obtain solvent mass.
3. Convert solvent mass to kilograms and calculate molality as solute moles per kg solvent.

Common traps: The 1 L basis is solution volume, not solvent volume. Do not divide by solution mass.

Check your work: The inferred solvent mass must be positive and smaller than the total solution mass.

### Question bank

| # | Source | Question description | Status | Priority status |
|---:|---|---|---|---|
| 56 | [2020-May, Q3(a)](papers/CHEM1043-2020-May.pdf) | Convert methanol solution molarity and density into molality. | Not solved | true: only retrieved example |

<a id="w18"></a>
## W18 · Temperature-dependent solubility → recrystallization explanation

1 rows · 1 distinct papers. Lecture reference: Topic 3; browse the [Moodle-material index](../lectures/README.md).

Recognition cues: State the purpose and working principle of recrystallization.

Minimum prerequisites: Solubility varies with temperature; impurities can behave differently.

### Workflow

1. State that the aim is purification of a solid, not chemical conversion.
2. Explain dissolving the impure solid in minimal suitable hot solvent, removing insoluble impurities if needed, then cooling to crystallize the desired material.
3. Explain why soluble impurities ideally remain in the mother liquor and why some product is lost. Identify the need for a suitable hot/cold solubility contrast.

Common traps: Do not claim that every impurity is automatically removed or that cooling creates more solute.

Check your work: Your explanation must connect purification to differential solubility, not only list laboratory steps.

### Question bank

| # | Source | Question description | Status | Priority status |
|---:|---|---|---|---|
| 57 | [2020-May, Q3(e)](papers/CHEM1043-2020-May.pdf) | Explain the use and principle of recrystallization. | Not solved | true: only retrieved example |

## What this guide does not establish

It does not establish a guaranteed question order, a future mark allocation, or the probability that a workflow will appear in 2026–27. The accessible set is small, ends in May 2022 and consists entirely of open-book exams; the newer catalogue records could materially change the picture once obtained.

These are original study methods and question descriptions, not an official marking scheme. Ambiguous wording and unprovided assumptions are identified rather than silently repaired. Source question wording, tables, numerical constants and diagrams remain authoritative.

## Updating the guide

Add newly obtained PDFs and their stable source records, then add precise question labels to `question-index.json`, preserve independent solved status, recalculate row and distinct-paper counts, and revisit representative choices. Do not count a catalogue listing as a paper read. Add new methods when a new paper requires them rather than forcing every question into an existing group.
