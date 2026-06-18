## Ch08 - Mixture and Solutions{{attrs[#blk-hpc38i7w3uuj]}}

Welcome to **Ch08 - Mixture and Solutions**. Replace this with your own material.

## Thermodynamics of mixing{{attrs[#blk-tb1d0pqq8bhl]}}

The tendency for substances to mix is governed by thermodynamics, specifically the change in Gibbs free energy (ΔG) upon mixing:

$$\Delta G_{mix} = \Delta H_{mix} - T \Delta S_{mix}$$

Where:

* $\Delta G_{mix}$ is the Gibbs free energy change of mixing.
* $\Delta H_{mix}$ is the enthalpy change of mixing (related to interaction energies).
* $\Delta S_{mix}$ is the entropy change of mixing (related to randomness/disorder).
* $T$ is the absolute temperature.

Mixing occurs spontaneously only if **$\Delta G_{mix}$ is negative**. This requires either favorable interactions ($\Delta H_{mix} < 0$, exothermic) or a sufficient increase in disorder ($\Delta S_{mix} > 0$), or both. Understanding how $\Delta H_{mix}$ and $\Delta S_{mix}$ differ between small molecules and polymers is crucial for predicting polymer solubility and solution behavior, which underpins many everyday applications.

**Everyday Relevance:** Why does oil (non-polar) not mix with water (polar)? Why does sugar dissolve in water? Why does adding a small amount of certain polymers drastically thicken shampoo? The principles governing these observations are rooted in the thermodynamics of mixing. Understanding polymer solutions helps us design products ranging from paints and adhesives to food thickeners and drug delivery systems.

### Mixing Small Molecules

Consider mixing two simple liquids, A and B.

* **Enthalpy ($\Delta H_{mix}$):** This term reflects the net change in interaction energy. We compare the energy of A-B interactions in the mixture to the A-A and B-B interactions in the pure components. If breaking A-A and B-B bonds and forming A-B bonds results in a net release of energy, $\Delta H_{mix} < 0$ (favorable). If it requires energy input (A and B prefer their own kind), $\Delta H_{mix} > 0$ (unfavorable). For many simple liquids with similar interaction types (e.g., dispersion forces), the energy balance is close, and $\Delta H_{mix} \approx 0$ (athermal mixing).
* **Entropy ($\Delta S_{mix}$):** When small, independent molecules mix, there's a large increase in the number of possible spatial arrangements (combinatorial entropy). This significant increase in randomness strongly favors mixing ($\Delta S_{mix}$ is large and positive). Mathematically, for ideal mixing, $\Delta S_{mix} = -R(n_1 \ln(x_1) + n_2 \ln(x_2))$, where n is moles and x is mole fraction.
* **Overall:** For small molecules, the large, positive $T\Delta S_{mix}$ term often dominates, making $\Delta G_{mix}$ negative even if $\Delta H_{mix}$ is slightly positive. This explains why many simple liquids are readily miscible (e.g., ethanol and water).

### Mixing Polymers and Solvents (or Other Polymers)

Now consider mixing a polymer (long chains of repeating segments, component 2) with a small molecule solvent (component 1).

* **Enthalpy ($\Delta H_{mix}$):** The principle is the same – comparing segment-solvent interactions to segment-segment and solvent-solvent interactions. However, even small energy differences per interaction add up over the long chain. Unless there are specific favorable interactions (like hydrogen bonds between polymer and solvent), mixing is often endothermic ($\Delta H_{mix} > 0$).
* **Entropy ($\Delta S_{mix}$):** This is the critical difference. Polymer segments are covalently linked. When placing polymer chains and solvent molecules onto a conceptual lattice, the connectivity of the polymer chain drastically reduces the number of possible arrangements compared to mixing the same number of disconnected segments and solvent molecules. Therefore, the combinatorial **$\Delta S_{mix}$ for polymer solutions is much smaller** than for small molecule solutions of comparable volume.
<!--    *_Suggested visual: Schematic comparing the number of ways to arrange independent small molecules vs. connected polymer segments on a lattice, highlighting the reduced configurations for polymers._* -->
* **Overall:** Because the entropic driving force ($T\Delta S_{mix}$) is significantly reduced, the enthalpy term ($\Delta H_{mix}$) plays a much more dominant role. Even small unfavorable interactions (positive $\Delta H_{mix}$) can prevent mixing, especially for high molecular weight polymers. The "like dissolves like" principle is even more stringent for polymers – the interaction energies must be very closely matched or specifically favorable for dissolution to occur ($\Delta G_{mix}$ must be negative). This is why dissolving a specific polymer often requires careful solvent selection.

### Flory-Huggins Theory

![](https://upload.wikimedia.org/wikipedia/commons/e/e8/Wpp1.jpg)

This foundational model uses a simplified lattice approach to describe the thermodynamics of polymer solutions. It provides an equation for the Gibbs free energy of mixing:

$$\frac{\Delta G_{mix}}{RT} = n_1 \ln(\phi_1) + n_2 \ln(\phi_2) + n_1 \phi_2 \chi$$

Where:

* $R$ is the ideal gas constant, $T$ is absolute temperature.
* $n_1$ and $n_2$ are the number of moles of solvent and polymer, respectively.
* $\phi_1$ and $\phi_2$ are the **volume fractions** of solvent and polymer ($\phi_1 + \phi_2 = 1$). Using volume fractions accounts for the size difference between solvent molecules and polymer chains. Compare to the equation for mixing small molecules, we use volume fraction here instead of mole fraction above. Mole fraction and volume fraction for small molecules would be very close one another; but for polymers they would be dramatically different. 
* **$\chi$** is the dimensionless **Flory-Huggins interaction parameter**.
<!--    *_Suggested visual: Schematic of the Flory-Huggins lattice model showing solvent molecules (1 site) and polymer chains (multiple connected sites) occupying lattice positions._* -->

**Understanding the Terms:**

* The first two terms ($n_1 \ln(\phi_1)$ and $n_2 \ln(\phi_2)$) represent the combinatorial entropy of mixing, adapted for components of different sizes. As noted, this term is smaller for polymer solutions than for small molecule mixtures.
* The last term ($n_1 \phi_2 \chi$) represents the enthalpy contribution (interaction energy) scaled by thermal energy.

**The Flory-Huggins Interaction Parameter ($\chi$):**

* This parameter quantifies the net energy change when creating polymer-solvent contacts relative to maintaining polymer-polymer and solvent-solvent contacts.
* It can be related to the interaction energies ($w_{ij}$) between components on the lattice model: $\chi \approx \frac{z \Delta w}{kT}$, where $z$ is the lattice coordination number (number of nearest neighbors), $k$ is Boltzmann's constant, and $\Delta w = w_{12} - \frac{(w_{11} + w_{22})}{2}$ is the "exchange energy" – the energy cost (if positive) or gain (if negative) of forming a 1-2 contact from 1-1 and 2-2 contacts.
* **$\chi \approx 0$:** Athermic mixing ($\Delta H_{mix} \approx 0$). Mixing is driven solely by the small entropy gain. 
* **$\chi > 0$:** Unfavorable polymer-solvent interactions (endothermic, $\Delta H_{mix} > 0$). Mixing becomes less favorable as $\chi$ increases. This is common. In this case, a higher temperature promotes dissolution. 
* **$\chi < 0$:** Favorable polymer-solvent interactions (exothermic, $\Delta H_{mix} < 0$). Promotes mixing (e.g., due to hydrogen bonding). If this is the case, the polymer can, in principle, dissolve in this solvent at any temperature with whatever concentration. 
* **Interpretation & Prediction:**
    * For spontaneous mixing ($\Delta G_{mix} < 0$), the small negative entropy contribution must overcome any positive enthalpy contribution (positive $\chi$).
    * Therefore, polymer miscibility generally requires $\chi$ to be small (if it is positive), zero, or negative.
    * **Critical Value & Theta ($\theta$) Condition:** For high molecular weight polymers, phase separation (immiscibility) typically occurs if **$\chi > 0.5$**. The condition $\chi = 0.5$ defines the **theta ($\theta$) condition**, representing a balance point where unfavorable enthalpy effects effectively cancel the polymer coil's tendency to expand due to excluded volume.
    * The Flory-Huggins equation predicts that miscibility decreases as polymer molecular weight increases (as the entropy term per mole becomes even smaller relative to the enthalpy term). It also predicts the conditions ($\chi$, T, $\phi$) under which a single-phase solution will separate into two phases (one polymer-rich, one solvent-rich).
<!--        *_Suggested visual: Plot of $\Delta G_{mix}$ vs. $\phi_2$ for different values of $\chi$ (e.g., < 0, = 0.5, > 0.5), showing how a convex curve (miscible) changes to one with concave regions (indicating phase separation)._* -->

**Assumptions and Limitations of Flory-Huggins Theory:**
The theory relies on several simplifying assumptions:

1.  Incompressible system (no volume change on mixing).
2.  Mixing occurs on a rigid lattice.
3.  Uniform segment density (mean-field approximation; ignores local concentration variations within coils).
4.  Interaction energy ($\chi$) is independent of concentration.
5.  Entropy is purely combinatorial.

These assumptions mean the theory works best for concentrated solutions and provides a qualitative/semi-quantitative understanding rather than precise predictions, especially for dilute solutions or systems with specific interactions. However, it provides the essential framework for understanding polymer solubility.

## Properties of Polymer Solutions{{attrs[#blk-q71dgf3lxpm4]}}

### Dilute Solutions

In dilute solutions, polymer coils are mostly isolated from each other. Their behavior is dictated by the balance between chain entropy (favoring a random coil) and polymer-solvent interactions.

* **Conformation:** Chains adopt a flexible, random coil conformation. Key size parameters:
    * **Radius of Gyration ($R_g$):** Root-mean-square distance of segments from the center of mass. Measurable by light scattering.
    * **Hydrodynamic Volume ($V_h$):** Effective volume swept out by the coil as it moves in the solvent. Determines GPC/SEC elution and viscosity.
<!--        *_Suggested visual: Diagram illustrating the effect of solvent quality on polymer coil conformation: expanded coil in a good solvent, unperturbed coil in a theta solvent, collapsed coil in a poor solvent._* -->
* **Solvent Quality & Second Virial Coefficient ($A_2$):** Solvent quality, related to $\chi$, affects coil size and inter-chain interactions. The **second virial coefficient ($A_2$)**, is a measure of the deviation of a real solution from ideal solution behavior. It *quantifies the effect of intermolecular forces* and the finite size of molecules on the pressure and volume. It is  measurable by osmometry or light scattering, quantifies these interactions:
    * **Good Solvent ($\chi < 0.5, A_2 > 0$):** Favorable polymer-solvent interactions. Chains expand (larger $R_g$, $V_h$). Positive $A_2$ reflects effective repulsion between coils. _Example:_ Polystyrene dissolved in toluene.
    * **Poor Solvent ($\chi > 0.5, A_2 < 0$):** Unfavorable polymer-solvent interactions. Chains contract (smaller $R_g$, $V_h$). Negative $A_2$ reflects effective attraction, potentially leading to aggregation or phase separation. _Example:_ Polystyrene in methanol.
    * **Theta ($\theta$) Solvent ($\chi = 0.5, A_2 = 0$):** Enthalpy and excluded volume effects balance. Chain adopts "unperturbed" dimensions. $A_2 = 0$ signifies ideal solution behavior regarding inter-chain interactions. The solution behaves as an ideal solution; the polymer chain behaves as an ideal chain. _Example:_ Polystyrene in cyclohexane at ~34.5 °C.
<!--        *_Suggested visual: Plot of $\Pi/(cRT)$ vs c (osmometry) or $Kc/R_{\theta}$ vs c (light scattering), showing extrapolation to $1/M$ at c=0 and slope related to $A_2$. Illustrate positive slope ($A_2>0$, good solvent), zero slope ($A_2=0$, theta solvent), and negative slope ($A_2<0$, poor solvent)._* -->

### Other Properties & Applications

* **Viscosity:** Polymers dramatically increase solution viscosity due to their large hydrodynamic volume ($V_h$). Even small amounts of dissolved polymer can significantly impede solvent flow. **Intrinsic viscosity $[\eta]$** characterizes a single coil's contribution to viscosity at infinite dilution.
    * **Application Example: Thickeners:** This viscosity-enhancing property is widely used. Small amounts of water-soluble polymers (e.g., hydroxyethyl cellulose, poly(ethylene oxide), carbomers, xanthan gum) are added to shampoos, lotions, liquid soaps, and condiments (like ketchup or sauces) to achieve the desired consistency and flow properties. The polymer must be in a relatively good solvent (low $\chi$ with water/base formulation) to expand and create a large $V_h$, maximizing the thickening effect. The choice of polymer and its concentration allows fine-tuning of the final product viscosity. Similarly, polymers are added to paints to control flow and prevent dripping.
    * **Application Example: Motor Oil Viscosity Index Improvers:** Polymers are added to engine oils. These polymers must dissolve in the base oil ($\chi$ must be low enough). They are designed such that their coils expand more significantly at higher temperatures (effectively, the oil becomes a better solvent, or thermal expansion dominates). This expansion counteracts the natural tendency of the oil to become thinner at high temperatures, helping maintain lubrication efficiency over a wider temperature range. The Flory-Huggins theory helps understand the solubility and temperature-dependent conformation ($V_h$) crucial for this application.
* **Osmotic Pressure ($\Pi$):** Colligative property historically used to measure **number-average molar mass ($M_n$)** via the van't Hoff law limit: $\lim_{c\to 0} \frac{\Pi}{c} = \frac{RT}{M_n}$. At low concentrations, the $A_2$ term is negligible. Deviations at higher concentrations yield $A_2$ term.
* **Phase Separation:** Occurs in poor solvents ($\chi > 0.5$) or when temperature changes alter $\chi$ across the miscibility threshold (e.g., Upper or Lower Critical Solution Temperature, UCST/LCST). <!--    *_Suggested visual: Generic polymer-solvent phase diagram (Temperature vs Composition) showing regions of miscibility and phase separation, indicating UCST or LCST._* -->
    * **Application Example: Coatings (Paint, Nail Polish):** These start as solutions of a polymer (e.g., acrylic, nitrocellulose) in a volatile solvent. The solvent is chosen to be good ($\chi < 0.5$) so the polymer dissolves completely. As the solvent evaporates, the polymer concentration increases. Eventually, the system effectively phase separates, leaving behind a solid, polymer-rich film (the coating). The initial solubility (governed by $\chi$) and the solvent evaporation rate are critical for forming a uniform, defect-free coating.
    * **Application Example: Hydrogels (Contact Lenses, Diapers):** Soft contact lenses are made of crosslinked hydrophilic polymers swollen with water or saline solution. Diapers use superabsorbent polymers (like crosslinked sodium polyacrylate). These are networks, not simple solutions, but the extent of swelling is governed by the balance between the thermodynamic drive for water to mix with the polymer (favorable interaction, low $\chi$) and the elastic retraction force of the crosslinked network. Flory-Huggins concepts, adapted for networks, help describe this swelling equilibrium.

### Examples of Polymer-Solvent Systems

The "like dissolves like" principle, refined by the Flory-Huggins parameter $\chi$, guides solvent selection:

* **Polystyrene (PS):** A relatively non-polar polymer with bulky phenyl rings.
    * _Good Solvents ($\chi < 0.5, A_2 > 0$):_ Toluene, Tetrahydrofuran (THF), Chloroform. These solvents have similar polarity and interact favorably with the phenyl rings. PS chains are expanded. _Application:_ PS dissolved in toluene can be used as a simple adhesive or coating.
    * _Poor Solvents ($\chi > 0.5, A_2 < 0$):_ Methanol, Water, Acetone. These solvents are more polar or have strong self-interactions (H-bonding) and interact unfavorably with PS. PS chains contract or precipitate.
    * _Theta Solvent ($\chi \approx 0.5, A_2 \approx 0$):_ Cyclohexane at ~34.5 °C. Used in research to study fundamental polymer physics under ideal conditions.
* **Poly(methyl methacrylate) (PMMA):** More polar than PS due to the ester group.
    * _Good Solvents:_ Acetone, THF, Chloroform. These can interact favorably with the ester group. _Application:_ PMMA dissolved in appropriate solvents can be used as a lacquer or adhesive ("acrylic cement").
    * _Poor Solvents:_ Water, Hexane, Methanol. Polarity mismatch or lack of favorable interactions.
* **Polyethylene (PE):** Very non-polar, often crystalline which hinders dissolution except at high temperatures.
    * _Good Solvents (usually require heat):_ Toluene, Xylene, Decalin (at elevated temperatures, e.g., > 80-100 °C). These non-polar solvents can interact with the hydrocarbon chain. _Application:_ High-temperature GPC/SEC analysis of PE requires dissolving it in such solvents.
    * _Poor Solvents (at room temp):_ Most common solvents, including water, alcohols, acetone, THF.

Finding a suitable solvent often involves matching polarity or using solubility parameters (like Hildebrand or Hansen parameters), which provide a practical way to estimate interaction energies and thus predict $\chi$.

## Polymer Molar Mass Measurement: Principles and Techniques{{attrs[#blk-23wejyc5prhk]}}

Determining the molar mass and its distribution is crucial for understanding polymer properties and predicting performance in applications like those described above.

### Principle of Light Scattering (LS)

When light (an electromagnetic wave) passes through a solution, the oscillating electric field induces oscillating dipoles in the solvent and polymer molecules. These oscillating dipoles act as secondary sources, re-radiating (scattering) light in directions other than the incident beam.

* **Intensity:** The intensity of the scattered light is proportional to the square of the molecule's polarizability (how easily its electron cloud is distorted), which is directly related to its size and thus its molar mass ($M$). It's also proportional to the concentration $c$ of the scattering molecules.
* **Concentration Fluctuations:** In solutions, scattering arises primarily from local fluctuations in concentration (and thus refractive index) compared to the average. These fluctuations are thermodynamically related to the osmotic pressure compressibility ($\partial \Pi / \partial c$), linking scattering intensity to $M$ and the second virial coefficient ($A_2$). The fundamental equation relates the excess Rayleigh ratio ($R_{\theta}$, normalized scattered intensity) to $M_w$ and $A_2$: 

$$\frac{Kc}{R_{\theta}} = \frac{1}{M_w} + 2A_2 c + ...$$

where $K$ is an optical constant depending on wavelength and refractive index increment ($dn/dc$).
* **Angular Dependence (for large molecules):** If the polymer coil size ($R_g$) is significant compared to the wavelength of light (> ~$\lambda/20$), light scattered from different parts of the same molecule interferes. This interference is angle-dependent (more destructive interference at higher angles), causing scattered intensity to decrease with increasing angle. Analyzing this angular dependence (using MALS detectors) allows the determination of $R_g$.

### Principle of Intrinsic Viscosity ($[\eta]$)

Viscosity measures a fluid's resistance to flow. Dissolving polymers increases solution viscosity ($\eta$) compared to the solvent viscosity ($\eta_s$) because the large polymer coils disrupt the smooth flow lines of the solvent.

* **Hydrodynamic Volume:** The viscosity increase depends on the total volume fraction effectively occupied by the polymer coils (hydrodynamic volume, $V_h$). As seen in the thickener examples, a larger $V_h$ (due to higher $M$ or better solvent quality) leads to a greater viscosity increase.
* **Intrinsic Viscosity:** To isolate the contribution of individual, non-interacting polymer coils, we extrapolate measurements to infinite dilution. The **intrinsic viscosity $[\eta]$** is defined as the fractional viscosity increase per unit concentration as concentration approaches zero: 
$$[\eta] = \lim_{c\to 0} \left[ \frac{(\eta - \eta_s)}{(\eta_s \cdot c)} \right]$$
* **Physical Meaning:** $[\eta]$ represents the effective hydrodynamic volume occupied by the polymer per unit mass (e.g., units of dL/g). It reflects both the molar mass and the conformation (expansion/contraction via $R_g$ and $V_h$) of the polymer coil in that specific solvent and temperature. Larger coils (higher $M$ or better solvent, i.e., lower $\chi$) lead to higher $[\eta]$.
<!--    *_Suggested visual: Huggins plot ($\eta_{sp}/c$ vs c) and Kraemer plot ($\ln(\eta_{rel})/c$ vs c) showing linear extrapolation to the same intercept $[\eta]$ at c=0._* -->

### Gel Permeation Chromatography (GPC) / Size Exclusion Chromatography (SEC)

This is the workhorse technique for determining polymer molecular weight and its distribution.

* **Principle:** Solution flows through columns packed with porous gel. Separation occurs based on **hydrodynamic volume ($V_h$)**. The same property that makes polymers good thickeners is used here for separation.
    * **Larger coils (higher $V_h$)** are excluded from more pores, travel a shorter path, and elute **first**.
    * **Smaller coils (lower $V_h$)** explore more pore volume, travel a longer path, and elute **later**. <!--        *_Suggested visual: Schematic of a GPC/SEC setup showing solvent reservoir, pump, injector, columns, detectors, and waste._*     *_Suggested visual: Typical GPC chromatogram showing detector signal (e.g., RI) vs. elution volume/time, with high MW eluting first (low volume/time)._* -->
* **Detectors:** Monitor the eluent composition versus elution volume/time. 
    * **Refractive Index (RI):** Concentration-sensitive (signal $\propto c$). Requires **column calibration** with standards of known $M$ and similar chemistry for relative molecular weight distribution (MMD).
    * **Light Scattering (LS / MALS):** Measures scattered light intensity ($I \sim c \cdot M \cdot P(\theta)$). Allows **direct determination of $M_w$** at each slice without $M$ calibration. Provides absolute $M_w$ and MMD. Can yield $R_g$.
    * **Viscometer:** Measures differential pressure related to viscosity. Combined with concentration (RI), determines **$[\eta]$** at each slice. Uses **Universal Calibration** ($\log([\eta]M)$ vs. elution volume) and **Mark-Houwink equation ($[\eta] = K \cdot M^a$)** to find $M$. The Mark-Houwink parameters $K$ and '$a$' depend on the polymer, solvent (i.e., $\chi$), and temperature, reflecting how $V_h$ scales with $M$ under those conditions.
* **Outcome:** GPC/SEC analysis yields:
    * The full **Molar Mass Distribution (MMD)** curve.
    * Average molar masses ($M_n$, $M_w$, $M_z$, etc.).
    * **Polydispersity Index (PDI):** PDI = $M_w / M_n$ (measures distribution breadth).
* **Other Techniques:** While GPC/SEC is dominant, other methods exist: Membrane Osmometry ($M_n$, $A_2$), standalone Light Scattering ($M_w$, $R_g$, $A_2$), End-Group Analysis ($M_n$ for low MW), MALDI-TOF MS (absolute MMD for low MW), DOSY NMR ($M_n$).

## Conclusion{{attrs[#blk-i7y6bh90wvtl]}}

Polymer mixing thermodynamics is uniquely governed by the interplay between a small combinatorial entropy gain and the enthalpy of interaction, well-described qualitatively by Flory-Huggins theory and the $\chi$ parameter. This dictates solubility ($\Delta G_{mix}$), phase behavior, and solution conformation (coil size, $R_g$, $V_h$), which depends strongly on solvent quality (good, poor, theta) quantified by $\chi$ or $A_2$. These solution properties are not just theoretical concepts; they are exploited in numerous everyday applications, from controlling the viscosity of shampoos and paints to enabling the formation of coatings and the function of hydrogels. Understanding these principles also underpins crucial characterization techniques like light scattering (measuring $M_w$, $R_g$, $A_2$) and viscometry (measuring $[\eta]$, related to $V_h$). GPC/SEC, the primary tool for MMD analysis, relies directly on separation by hydrodynamic volume ($V_h$), a fundamental property rooted in the polymer's interaction with the solvent. Determining the molar mass distribution is essential, as it profoundly influences the material's processability and end-use performance in all these applications.



:::info
**Example Questions Level 1**
1. True or False: Mixing always results in an increase of entropy. Why?
2. What thermodynamic condition must be met for mixing to occur spontaneously?
3. Why is the entropy gain upon mixing polymers generally smaller than for small molecules?
5. What value of the Flory-Huggins interaction parameter ($\chi$) typically indicates a good solvent for a polymer?
7. How does a polymer chain conformation differ in a good solvent compared to a poor solvent?
8. What is the primary principle of separation in Gel Permeation Chromatography (GPC) / Size Exclusion Chromatography (SEC)?
9. What is a dilute solution of a polymer.

:::


{{markdown ./license.md}}
