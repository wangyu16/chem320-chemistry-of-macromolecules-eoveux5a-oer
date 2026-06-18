## Glass Transition{{attrs[#blk-jd8jorxwd207]}}

### Introduction: The Glass Transition Phenomenon

As we know, polymers are long-chain molecules whose physical state is highly dependent on temperature. At high temperatures, polymer chains possess significant thermal energy, allowing for considerable movement, often resulting in a rubbery or liquid-like state. As the temperature decreases, this molecular mobility is reduced.

A crucial thermal event in amorphous or semi-crystalline polymers is the **glass transition**. This is not a sharp phase transition like melting, but rather a temperature range over which the polymer changes from a relatively flexible, rubbery state to a rigid, brittle, glassy state upon cooling (or vice-versa upon heating). We characterize this transition by the **Glass Transition Temperature ($T_g$)**, a specific temperature typically defined within this range. Understanding $T_g$ is fundamental to predicting and controlling polymer behavior in various applications.

**Glass and melting transitions**



::: left
![image](https://hackmd.io/_uploads/BkC_qARA0.png =300x)
::: 

The figure shows changes in the specific volume (reciprocal of density) of a polymer with temperature. Above $T_m$, a liquid, range A to B.

If crystalize, slow cooling, goes from B to C and E, F. First order thermodynamic transition. CEF part is due to the amorphous region.

If not crystalize, rapid cooling, goes from B to H and I. HI is glassy state. The glass transition happen in a range of temperature B to H.

Glass transition in practice is not truly a second order phase transition.

### What Happens at the Molecular Level?

Below the $T_g$, the polymer is in a **glassy state**:

* The large-scale, cooperative movement of polymer chain segments is effectively frozen.
* Only localized motions, such as bond vibrations or short side-group movements, remain active.
* Macroscopically, the material is typically hard, stiff, and brittle.

Above the $T_g$, the polymer enters a **rubbery state** (or melt state at higher temperatures):

* Polymer chain segments (typically involving 10-50 backbone atoms) gain sufficient thermal energy to overcome rotational barriers and move past one another. This is often referred to as segmental motion.
* This increased mobility allows the material to deform elastically and exhibit flexibility; it becomes less brittle.

The glass transition, therefore, signifies the onset (upon heating) or cessation (upon cooling) of this large-scale segmental motion within the amorphous regions of the polymer.

<!-- *Suggested visual: A diagram contrasting the tightly packed, immobile polymer chains below Tg with the more loosely arranged chains exhibiting segmental motion above Tg.* -->

### Factors Affecting Glass Transition Temperature ($T_g$)

The specific $T_g$ value varies greatly depending on the polymer's chemical structure and morphology. Key factors include:

1.  **Chain Flexibility:** Polymers with intrinsically flexible backbones (e.g., those containing -O- or -Si-O- linkages) require less thermal energy for segmental motion and thus have lower $T_g$ values. Conversely, rigid backbones incorporating structures like aromatic rings restrict motion and lead to higher $T_g$ values. <!-- *Suggested visual: Schematic drawings comparing polymer chain structures, one flexible (like polyethylene or polydimethylsiloxane) and one rigid (like polycarbonate or polystyrene).* -->
2.  **Side Groups:** Bulky side groups attached to the main chain create steric hindrance, impeding chain rotation and close packing, thereby increasing $T_g$. Smaller, less hindering side groups allow for easier movement and result in a lower $T_g$. <!--  *Suggested visual (Optional): Schematic showing a polymer chain with small side groups vs. one with bulky side groups.* -->
3.  **Intermolecular Forces:** Strong secondary forces between polymer chains (e.g., hydrogen bonding, dipole-dipole interactions) increase the energy required for segments to move apart, thus increasing $T_g$. Weaker forces (like van der Waals) allow for easier movement and lower $T_g$. <!-- *Suggested visual (Optional): Schematic illustrating hydrogen bonds or dipole interactions between adjacent polymer chains.* -->
4.  **Molecular Weight:** $T_g$ generally increases with increasing number-average molecular weight ($M_n$) up to a certain point (typically around 20,000 g/mol), after which it plateaus. This is because chain ends have higher mobility than segments within the chain; increasing chain length reduces the concentration of chain ends per unit volume. The relationship is often described by the Fox-Flory equation: $T_g = T_g^\infty - K/M_n$, where $T_g^\infty$ is the $T_g$ at infinite molecular weight and K is a constant. <!--  *Suggested visual: A plot of Tg on the y-axis versus Mn (or 1/Mn) on the x-axis, showing the characteristic rise and leveling off.* -->
5.  **Cross-linking:** Introducing chemical cross-links between polymer chains restricts segmental mobility significantly, leading to a substantial increase in $T_g$. The extent of the increase depends on the cross-link density.
6.  **Plasticizers:** Adding low molecular weight compounds (plasticizers) increases intermolecular spacing and facilitates chain movement, effectively lowering the $T_g$.

### Fundamental Theories (A Brief Touch)

Several theoretical frameworks attempt to explain the glass transition:

::: left
![image](https://hackmd.io/_uploads/rk4zsR0AR.png =300x)
:::
**Free Volume Theory:** This theory postulates that molecular motion requires a certain amount of empty space, or "free volume". Below $T_g$, the available free volume is insufficient for large-scale segmental rearrangement. As temperature increases, thermal expansion increases the free volume. At $T_g$, the free volume reaches a critical fraction (typically around 2.5%) that permits the onset of segmental motion.

The volume of a piece of material can be divided into to catagories
1. The volume occupied by the molecules $V_{occ}$;
2. The free volume $V_f$ that allow molecules to rearrange their conformations.

The $V_f$ decreases upon cooling from the liquid state, until at $T_g$ it reaches some critical small value. Above $T_g$ the chain segments have enough space to move and to change conformation. Below $T_g$ the chain segments are frozen.


<!--    *Suggested visual: A 2D schematic showing circles (representing chain segments) with gaps (free volume) between them, illustrating how the total free volume increases with temperature.* -->

**Kinetic Theory:** This perspective highlights the time-dependent (kinetic) nature of the glass transition. Molecular rearrangements require time. As a polymer melt is cooled, the rate of segmental rearrangement decreases. If the cooling rate is faster than the molecular relaxation rate, the system falls out of equilibrium at $T_g$, and the liquid structure becomes "frozen" in place. Consequently, the measured $T_g$ depends on the cooling or heating rate – faster rates yield higher apparent $T_g$ values.

**Thermodynamic Theory (Gibbs-DiMarzio):** This theory proposes an underlying second-order thermodynamic transition occurring at a temperature $T2$, which is typically 30-50 K below the experimentally measured $T_g$. At $T2$, the configurational entropy (related to the number of available chain conformations) is postulated to become zero. However, due to kinetic limitations, real systems undergo the glass transition at $T_g$ before reaching this theoretical state.

### Why is $T_g$ Important?

The $T_g$ is arguably the most important property defining the application range of amorphous polymers:

* **Material Selection:** It dictates whether a polymer will behave as a rigid plastic (requires $T_g$ > use temperature) or a flexible elastomer/rubber (requires $T_g$ < use temperature) under specific operating conditions.
* **Mechanical Properties:** Many mechanical properties, such as modulus, impact strength, and creep resistance, change dramatically around $T_g$.
* **Processing:** Knowledge of $T_g$ is essential for optimizing processing parameters for techniques like injection molding, extrusion, and thermoforming, as it influences the material's viscosity and formability.
* **Adhesives & Coatings:** $T_g$ affects the tack, flexibility, and barrier properties of adhesives and coatings.

### Measuring glass transition temperature

**Dilatometry**

To measure the density or volume directly as a function of temperature.

**Calorimetry**

To determine the heat capacity versus temperature. Differential scanning calorimetry (DSC) is a common example of a thermal analysis method.

**Dynamic mechanical analysis**

At fixed frequency, measure the change of modulus $G'$ and $G''$ vs temperature. The loss tangent $\tan\delta=G''/G;$ exhibits a peak at a particular temperature which can be used as an empirical definition of $T_g$.

### Examples of Commercial Polymers and their $T_g$

Let's look at how the structure-$T_g$ relationship plays out in some common polymers:

* **Polydimethylsiloxane (PDMS):**
    * *Structure:* Features a highly flexible silicon-oxygen (-Si-O-) backbone with small, non-polar methyl ($\ce{-CH3}$) side groups.
    * *$T_g$:* Extremely low, around **-125 °C**.
    * *Structure-$T_g$ Link:* The exceptional flexibility of the Si-O bond allows for segmental motion at very low temperatures. The small side groups offer little steric hindrance.
    * *Properties & Applications:* PDMS is a rubbery elastomer at room temperature and far below. Its low $T_g$ contributes to its flexibility over a wide temperature range, making it ideal for **sealants, caulks, medical tubing, and flexible cookware**.

* **Polystyrene (PS):**
    * *Structure:* Consists of a carbon-carbon backbone with a bulky, rigid phenyl ring attached to every other carbon atom.
    * *$T_g$:* Relatively high, around **100 °C**.
    * *Structure-$T_g$ Link:* The large phenyl side groups severely restrict the rotation of the polymer backbone, requiring significantly more thermal energy (higher temperature) to enable segmental motion.
    * *Properties & Applications:* Because its $T_g$ is well above room temperature, PS is a rigid, stiff, and somewhat brittle plastic under normal conditions. It's commonly used for **disposable cups and cutlery, CD jewel cases, and expanded polystyrene foam packaging**.

* **Poly(methyl methacrylate) (PMMA):**
    * *Structure:* Carbon-carbon backbone with two side groups on alternating carbons: a methyl group ($\ce{-CH3}$) and a larger ester group ($\ce{-COOCH3}$).
    * *$T_g$:* Also around **105 °C**, similar to PS.
    * *Structure-$T_g$ Link:* Both side groups contribute to steric hindrance, restricting chain mobility and leading to a high $T_g$. The polar ester group also adds some intermolecular attraction.
    * *Properties & Applications:* PMMA (often known as acrylic, Plexiglas, or Lucite) is a rigid, transparent plastic at room temperature. Its clarity and rigidity make it a **glass substitute in windows (including aircraft), signs, and optical lenses**.

* **Polycarbonate (PC) (Bisphenol A based):**
    * *Structure:* Incorporates rigid aromatic (phenyl) rings directly into the polymer backbone, linked by carbonate (-O-(C=O)-O-) groups and an isopropylidene group.
    * *$T_g$:* High, around **145-150 °C**.
    * *Structure-$T_g$ Link:* The inherent stiffness of the aromatic rings within the main chain significantly restricts segmental motion, resulting in a very high $T_g$.
    * *Properties & Applications:* PC is a strong, exceptionally tough, and transparent thermoplastic that remains rigid well above the boiling point of water. It's used in demanding applications like **safety glasses, riot shields, CDs/DVDs, automotive headlamp covers, and reusable water bottles**.

* **Polyethylene Terephthalate (PET):**
    * *Structure:* Contains both rigid elements (aromatic rings, polar ester groups) and flexible segments ($\ce{-CH2-CH2-}$) within the backbone.
    * *$T_g$:* Moderate, around **70-80 °C**.
    * *Structure-$T_g$ Link:* The $T_g$ reflects a balance between the stiffening effect of the aromatic rings and ester groups and the flexibility introduced by the ethylene glycol segments.
    * *Properties & Applications:* While its $T_g$ is above typical room temperature, PET is often used in a semi-crystalline state, which enhances its strength and thermal stability above $T_g$. Its primary application is in **beverage bottles**, but it's also widely used for **fibers (polyester clothing) and films**.

These examples illustrate how chemists and engineers can tailor polymer structures to achieve specific glass transition temperatures, thereby controlling the material's properties for targeted applications.

**$T_g$ of some commercial polymers**

| Material	| $T_g$ (°C) |
|-----------|------------|
| Tire rubber |	−70	|
| Polyvinylidene fluoride (PVDF) |	−35	|
| Polypropylene (PP atactic) |	−20		|
| Polyvinyl fluoride (PVF) |	−20		|
| Polypropylene (PP isotactic) |	0	|	
| Poly-3-hydroxybutyrate (PHB) |	15	|
| Poly(vinyl acetate) (PVAc) |	30	|	
| Polychlorotrifluoroethylene (PCTFE) |	45	|	
| Polyamide (PA) |	47–60	|
| Polylactic acid (PLA) |	60–65		|
| Polyethylene terephthalate (PET) |	70	|	
| Poly(vinyl chloride) (PVC) |	80		|
| Poly(vinyl alcohol) (PVA)	| 85		|
| Polystyrene (PS)	| 95		|
| Acrylonitrile butadiene styrene (ABS)	| 105	|
| Poly(methyl methacrylate) (PMMA atactic) |	105	|
| Polytetrafluoroethylene (PTFE) |	115	|
| Poly(carbonate) (PC)	| 145	|
| Polysulfone	| 185	|
| Polynorbornene |	215		|


### Conclusion

The glass transition temperature ($T_g$) represents a critical thermal transition in polymers, marking the point where amorphous regions change between a rigid glassy state and a more mobile rubbery state. This transition is fundamentally linked to the onset of cooperative segmental motion of the polymer chains. Understanding the molecular factors influencing $T_g$ (chain structure, intermolecular forces, molecular weight, etc.), the theoretical concepts explaining the phenomenon, and the impact on material properties (illustrated by modulus changes and commercial examples) is crucial for predicting polymer behavior and selecting appropriate materials for engineering applications. $T_g$ dictates the useful temperature range and significantly impacts the mechanical and processing characteristics of polymers.

## Crystallinity{{attrs[#blk-0wi28r0wodch]}}

### Introduction: Order in Long Chains

While the glass transition ($T_g$) describes changes in the *amorphous* regions of polymers, many polymers can also form ordered, crystalline structures. Unlike small molecules that often form perfect, single crystals, polymer crystallization is more complex due to the long, entangled nature of the chains.

**Polymer crystallization** is the process by which polymer chains organize from a disordered state (melt or concentrated solution) into ordered, repeating structures or lattices. Because complete ordering is hindered by chain length, entanglements, and structural irregularities, most crystalline polymers are actually **semi-crystalline**. This means they consist of both ordered crystalline regions (crystallites) embedded within disordered amorphous regions. The degree of crystallinity significantly impacts the material's properties.

### Mechanism of Crystallization: Nucleation and Growth

Polymer crystallization typically occurs upon cooling from the melt state (below the melting temperature, $T_m$, but usually above the glass transition temperature, $T_g$) and proceeds via two main steps:

1.  **Nucleation:** The initial formation of tiny, stable ordered regions (nuclei) within the disordered melt.
    * **Homogeneous Nucleation:** Nuclei form spontaneously from fluctuations within the polymer melt itself. This requires significant undercooling (cooling below $T_m$).
    * **Heterogeneous Nucleation:** Nuclei form more easily on pre-existing surfaces, such as impurities, container walls, or deliberately added nucleating agents. This requires less undercooling and is often the dominant mechanism in practice.


2.  **Growth:** Once stable nuclei are formed, polymer chains from the surrounding melt attach themselves to the nucleus surface, causing the crystalline region to grow.
    * **Lamellae:** The fundamental crystalline structure in polymers is the **lamella** (plural: lamellae), which are thin, plate-like crystals typically 10-20 nm thick. Polymer chains fold back and forth within these lamellae.
    * **Spherulites:** In bulk polymers cooled from the melt, lamellae often grow radially outwards from a central nucleus, branching and twisting as they grow, to form spherical superstructures called **spherulites**. These can range from micrometers to millimeters in diameter and are characteristic of many semi-crystalline polymers. Spherulites impinge on each other as they grow, forming distinct boundaries.

### Crystal structures

Crystal growth is achieved by the further addition of folded polymer chain segments to the nucleus and only occurs for temperatures below the melting temperature $T_m$ and above the glass transition temperature $T_g$. Higher temperatures destroy the molecular arrangement and below the glass transition temperature, the movement of molecular chains is frozen resulting in amorphous structures.Typical polymer crystals have three levels of structure.

1. Individual chain backbones form helices and pack with neighboring chains to form unit cells. The typical unit cell contains only a few monomer units with dimensions of 0.2 - 2 nm on a side.

    ![](https://upload.wikimedia.org/wikipedia/commons/b/bb/Polymerketten_-_amorph_und_kristallinEN.svg =400x)
2. Unit cells pack into thin sheets called lamellae, which are typically 10 - 50 nm thick and several microns wide in the other two dimensions. The chain backbones lie at some fixed angle relative to the thin direction, and often fold by 180° at the lamella surface in order to reenter the crystal.

    ![](https://upload.wikimedia.org/wikipedia/commons/0/01/Lamellenbildung_bei_der_Kristallisation_von_PolymerenEN.svg =400x)
3. In a bulk sample the lamellae grow to fill space, often producing a three-dimensional structure called a spherulite which can be tens or hundreds of microns across.

    ![](https://upload.wikimedia.org/wikipedia/commons/5/5c/Spherulite2.PNG =300x)
    
Another type of crystallization occurs upon extrusion or blow molding used in making fibers and films. In this process, the polymer is forced through, e.g., a nozzle that creates tensile stress which partially aligns its molecules. Such alignment can be considered as crystallization and it affects the material properties. For example, the strength of the fiber is greatly increased in the longitudinal direction, and optical properties show large anisotropy along and perpendicular to the fiber axis. 



### Factors Affecting Crystallization

The ability of a polymer to crystallize and the extent and rate of crystallization depend on several factors:

1.  **Polymer Structure:**
    * **Regularity:** High structural regularity (e.g., linear chains, isotactic or syndiotactic configurations) is crucial. Irregular structures (e.g., atactic polymers, branching, copolymers with random monomer sequences) hinder packing into a crystal lattice and reduce or prevent crystallization.
    * **Chain Flexibility:** While some flexibility is needed for chains to rearrange, very flexible chains might favor amorphous structures. Stiffer chains, if regular, can pack well.
    * **Bulky Side Groups:** Large side groups generally hinder crystallization due to steric interference, although exceptions exist if the side groups themselves can pack regularly.
    * **Intermolecular Forces:** Strong polar interactions (like hydrogen bonding in nylons) can promote crystallization by providing favorable energetics for chain alignment.
2.  **Temperature:** Crystallization occurs between $T_g$ and $T_m$. The rate is typically highest at a temperature roughly midway between $T_g$ and $T_m$. Below $T_g$, chain mobility is too low for rearrangement. Near $T_m$, the driving force for crystallization (undercooling) is small.
3.  **Cooling Rate:** Slower cooling allows more time for chains to organize, generally leading to higher degrees of crystallinity and larger, more perfect crystalline structures (e.g., larger spherulites). Rapid cooling (quenching) can suppress crystallization, potentially yielding a largely amorphous material even for a crystallizable polymer.
4.  **Molecular Weight:** Very low molecular weight chains may crystallize easily but form brittle materials. Extremely high molecular weight chains have high melt viscosity and significant entanglements, which can slow down the crystallization rate.
5.  **Additives:** Nucleating agents can be added to increase the crystallization rate and result in a larger number of smaller spherulites, which can improve optical clarity and sometimes mechanical properties.

### Degree of Crystallinity

Since polymers are rarely 100% crystalline, the **degree of crystallinity** (often expressed as a weight or volume percentage) is a critical parameter. It represents the fraction of the material that is in the ordered crystalline state. Typical values range from 0% (completely amorphous) to about 80-95% for highly crystalline polymers like linear polyethylene.

The degree of crystallinity strongly influences polymer properties. It can be measured using techniques such as:
* **Differential Scanning Calorimetry (DSC):** By measuring the heat absorbed during melting (enthalpy of fusion) and comparing it to the value for a hypothetical 100% crystalline sample.
* **X-ray Diffraction (XRD):** Crystalline regions produce sharp diffraction peaks, while amorphous regions produce a broad halo. The relative areas under these features can quantify crystallinity.
* **Density Measurements:** Crystalline regions are generally denser than amorphous regions. Measuring the sample's density and comparing it to the known densities of purely crystalline and purely amorphous forms allows calculation of the degree of crystallinity.

### Properties and Importance of Crystalline Polymers

Crystallinity significantly impacts material properties compared to fully amorphous polymers:

* **Mechanical Properties:** Crystalline regions act like reinforcing fillers, increasing **stiffness (modulus)**, **strength (yield strength, tensile strength)**, and **hardness**. However, high crystallinity can sometimes reduce **impact toughness** (increase brittleness), especially if large spherulites are present.
* **Thermal Properties:** Crystallites have a defined **melting point ($T_m$)**, which determines the upper service temperature. They also enhance dimensional stability at temperatures between $T_g$ and $T_m$.
* **Optical Properties:** The crystalline regions (and larger structures like spherulites) have different refractive indices than the amorphous regions and can scatter light, making semi-crystalline polymers typically **opaque or translucent**. Amorphous polymers are usually transparent. Smaller spherulite size can improve clarity.
* **Solvent Resistance:** The tightly packed chains in crystalline regions are much less permeable to solvent molecules, leading to significantly **better solvent resistance** compared to their amorphous counterparts.
* **Density:** Crystalline polymers are denser than amorphous polymers of the same chemical structure.

### Examples of Crystalline Polymers

* **Polyethylene (PE):** High-density polyethylene (HDPE) has very linear chains and achieves high crystallinity (60-80%), making it stiff and strong (e.g., milk jugs, pipes). Low-density polyethylene (LDPE) has branched chains, lower crystallinity (40-50%), and is more flexible (e.g., films, bags).
* **Polypropylene (PP):** Isotactic PP is highly crystallizable (typically 30-60% crystallinity) due to its regular structure, making it versatile for packaging, fibers, and automotive parts. Atactic PP is amorphous and rubbery.
* **Nylon (Polyamides):** Regular structures and strong hydrogen bonding lead to high crystallinity, resulting in strong, abrasion-resistant fibers and engineering plastics.
* **Polyethylene Terephthalate (PET):** Can be amorphous (transparent) if quenched rapidly, or semi-crystalline (opaque/translucent, stronger, better thermal stability) if crystallized (e.g., beverage bottles often have controlled crystallinity).

### Conclusion

Polymer crystallization is the process of chain ordering into lamellar structures, often organized into larger spherulites, leading to semi-crystalline materials. The ability to crystallize, the rate, and the final degree of crystallinity are governed by polymer structure (regularity is key) and processing conditions (temperature, cooling rate). Crystallinity profoundly affects a polymer's mechanical strength, stiffness, thermal stability, optical clarity, and chemical resistance, making it a critical factor in material selection and design. Understanding the interplay between polymer structure, crystallization behavior, and resulting properties is essential in polymer science and engineering.

## Viscoelasticity{{attrs[#blk-evz2i7fu4yui]}}

Viscoelastic
: the behavior is intermediate between (elastic) solid and (viscous) liquids.

Steady flow viscosity $\eta$. Polymethylstyrene melt double the molecular weight, the viscosity increase about 10 times.

### Stress and strain

Simple shear: the material is confined between two parallel plates $\mathrm{d}y$ apart, and if one surface is moved a distance $\mathrm{d}x$, we say that the sample has been subjected to a strain $\gamma = \mathrm{d}x/\mathrm{d}y$. The velocity of the plate $v_x = \mathrm{d}x/\mathrm{d}t$ and $\dot{\gamma} = \mathrm{d}\gamma/\mathrm{d}t$ is called the strain rate or shear rate.

The material exerts a force on the moving plate which depends on the area of the plate in contact with the material. The force per unit area is called stress $\sigma$.

Types of deformation include uniaxial elongation, biaxial elongation, simple shear, etc. In all cases it is possible to define a stress, strain, and strain rate.

### Viscosity, modulus, and compliance

**Viscosity** $\eta$ is defined as the ratio of a stress to a strain rate.

$$\sigma = \eta\dot{\gamma}$$

If $\eta$ is independent to the magnitude of $\dot{\gamma}$ the fluid is said to be Newtonian.

Polymer fluids are typically non-Newtonian. But the Newtonian behavior is recovered in the limit that $\dot{\gamma}\to 0$.

**Modulus** $G$ is defined as the ratio of a stress to a strain

$$\sigma = G\gamma$$

If $G$ is independent to the magnitude of $\gamma$, the response is linear.  This is generally true as $\gamma\to 0$. Experimentally, we always need a finite strain to generate a measureable stress and whether the response falls in the so-called linear viscoelastic limit is something that needs to be checked.

**Compliance** $J$ is defined as the ratio of a strain to a stress. Therefore, a compliance is related to the inverse of a modulus. But when the time dependence is involved $J(t)$ is not simply equal to $1/G(t)$.

### Viscous and elastic responses

Viscosity reflects the relative motion of molecules, in which energy is dissipated by friction. A liquid flows until the stress has gone away while energy is dissipated as it does so.

Elasticity reflects the storage of energy. The energy can be recovered by releasing the deformation.

Transient experiment: A strain is suddenly applied and held. The stress is monitored as a function of time. This protocol is called stress relaxation.. The modulus is stress relaxation modulus $G(t) = \sigma(t)/\gamma$.

Creep experiment: A step stress is applied at $t=0$ and the subsequent strain is monitored versus time .The compliance is creep compliance $J(t) = \gamma(t)/\sigma$.

Steady flow experiment: The strain rate is constant. The resulting steady stress gives the steady flow viscosity.

Dynamic experiment: the sample is subjected to a sinusoidally time-varing strain at frequency $\omega$. The resulting dynamic modulus $G^*(\omega)$ can be resolved into two dynamic moduli: one in-phase with the strain, called $G'$, reflecting the elastic component of the total response and one in-phase with the strain rate, called $G''$, reflecting the viscous response.

### Maxwell and Voigt model

::: left
![image](https://hackmd.io/_uploads/HJL3HkJJ1e.png =300x)
:::

The Maxwell element consists of an ideal Hookean spring with spring constant $\widehat{G}$ connected in series with and ideal Newtonian dashpot with viscosity $\widehat{\eta}$.

The Voigt element consists of a spring and a dashpot parallelly.  

The stress in the Maxwell element with two components is given by

$$
\begin{align*}
& \sigma = \widehat{G}\gamma\quad\text{for the spring} \\
& \sigma = \widehat{\eta}\dot{\gamma}\quad\text{for the daspot}
\end{align*}
$$

At time $t=0$ we apply an instantaneous strain of magnitude $\gamma_0$, and hold it indefinitely. The stress as a function of time gives a stress relaxation experiment.

At very short times, the spring takes all the initial deformation, while the stretched spring will then exert a force on the dashpot which will flow slowly in response. Ultimately, the spring will relax back to its rest length and there will be no more stress.

The strain is constant

$$\frac{\mathrm{d}\gamma_0}{\mathrm{d}t} = 0 =\dot{\gamma}_\text{spring} + \dot{\gamma}_\text{dashpot}$$

i.e.,

$$\frac{\mathrm{d}}{\mathrm{d}t}\frac{\sigma(t)}{\widehat{G}} + \frac{\sigma(t)}{\widehat{\eta}}=0$$

Thus we can define a relaxation time $\tau\equiv\widehat{\eta}/\widehat{G}$. The solution of the equation is

$$\sigma(t) = \sigma_0\exp(-t/\tau)$$

The stress relaxation modulus is obtained as

$$G(t) = \frac{\sigma(t)}{\gamma_0} = \widehat{G}\exp(-t/\tau)$$

The Maxwell model captures the main featuer of the stress relaxation response of any liquid. The magnitude of the relaxation time is vital in determining the properties we experience.

Polymers with their many degrees of internal conformational freedom show multiple relaxation times spread over many orders of magnitude.

Polymer processing usually takes place when the polymer is under viscoelstic fluid state.

## Rubber elasticity{{attrs[#blk-o5jlacesirev]}}

Network, gel, crosslinked polymer

A **elastomer** is a cross-linked polymer that undergoes the glass transition well below room temperature, therefor the solid is quite soft and deformable.

A **thermoset** is a polymer in which multifunctional monomers are polymerized or copolymerized to form a relatively rigid solid.

::: left
![image](https://hackmd.io/_uploads/BJObfk1Jyl.png =300x)
:::

Elements within a network:
* *Strand* A section of polymer chain that begins at one junction and ends at another.
* *Junction* A cross-link from which three of more strands emanate. The nunmber of strands that are connected to the junction is called the functionality.
* *Dangling end* A section of polymer chain that one end is linked to a junction and the other end is hanging freely.
* *Loop* A section of polymer chain that begins and ends at the same cross-link, with no intervening junctions.
* *Sol fraction* A chain that have no cross-links, or it may be linked to a finite number of other chains to form a cluster. If the material were placed in a large reservoir of a good solvent the sol fracion could dissolve. Thus the sol fraction contains all the extractable material.

Often, an elastomeric material containing little or no sol fraction is called a rubber, whereas a material containing an equivalent network structure plus a significant amount of solvent or low-molecular-weight diluent would be called a gel.

### Elastic deformation -- Uniaxial extension

A rectangular sample with the original length $L_0$ and face area $A$. When a force $f$ is applied to the sample, the length increases by $\Delta L$.
1. The quantity $\Delta L/L_0$ is proportional to the force.
2. If there are several samples with different face areas, it can be found that the quantity $f/A$ is proportional to $\Delta L/L_0$.
3. The force per unit area is called the uniaxial tension or stress ($\sigma = f/A$). The percent enlongation is called the strain ($\varepsilon = \Delta L/L_0$).

$$\sigma\propto\varepsilon$$

The proportionality constant $E$ is called the tensile modulus or Young's modulus. Since $\varepsilon$ is dimensionless, $E$ and $\varepsilon$ have the same units as $f/A$, namely Pa in SI system.

When the sample is stretched in one dimension, it will shrink in the other two dimensions. The contract fraction is given by

$$-\frac{\Delta d}{d} = -\frac{\Delta h}{h} = v\frac{\Delta L}{L_0} = v\varepsilon$$

The constant $v$ is called Poisson's ratio

$$v = \frac{1}{2}\left(1-\frac{1}{V}\frac{\mathrm{d}V}{\mathrm{d}\varepsilon}\right)$$

If the volume does not change on elongation, the fractional contraction in each of the perpendicular directions is half the fraction increase in length.

Both $E$ and $v$ are needed to describe the response of a sample to tensile force. Poisson's ratio also provides a means to relate $E$ to the shear modulus, $G$, and the compressional modulus, $K$:

$$G(1+v) = E/2$$

$$K(1-2v) = E/3$$

### Thermodynamics of elasticity

The elastic work associated with an increment in elongation is

$$\mathrm{d}w = f\mathrm{d}L$$

If there is a volume change associated with the elongation, a $-p\mathrm{d}V$ term should be added to the change of internal energy

$$
\begin{align*}
\mathrm{d}U & = \mathrm{d}q - p\mathrm{d}V + f\mathrm{d}L \\
& = T\mathrm{d}S - p\mathrm{d}V + f\mathrm{d}L
\end{align*}
$$

The Gibbs free energy and internal energy has the correlation

$$G = U+pV-TS$$

thus

$$\mathrm{d}G = V\mathrm{d}p - S\mathrm{d}T + f\mathrm{d}L$$

and

$$f = \left(\frac{\partial G}{\partial L}\right)_{p,T} = \left(\frac{\partial H}{\partial L}\right)_{p,T} - T\left(\frac{\partial S}{\partial L}\right)_{p,T}$$

This is called the equation of state for an elastomer, by analogy to

$$p = -\left(\frac{\partial U}{\partial V}\right)_T + T\left(\frac{\partial S}{\partial V}\right)_T$$

which is the thermodynamic equation of state for a fluid.

#### Ideal elastomers

For an ideal gas, the internal energy does not depend on the volume since the molecules are noninteracting. Similarly, ideal elastomer can be defined as one for which $(\partial H/\partial L)_{p,T} = 0$, in this case

$$f = -T\left(\frac{\partial S}{\partial L}\right)_{p,T}$$

Interactions among molecules are not neglegible, but there is no change in the enthalpy of the sample as a result of the stretching process. There are two implications:
1. The average energy of interaction between different molecules cannot change, i.e., the density does not change, i.e., the volume is constant.
2. The intramolecular conformational energy change is little, which is approximately true when the conformational energy is determined by the relative populations of trans and gauche conformers, but becomes problematic when strong interactions such as hydrogen bonding are involved or crystallization occurs.

When using Helmholtz free energy instead of Gibbs free energy, the state equation becomes

$$f=\left(\frac{\partial A}{\partial L}\right)_{T,V}=\left(\frac{\partial U}{\partial L}\right)_{T,V} - T\left(\frac{\partial S}{\partial L}\right)_{T,V}$$

Because the volume changes on elastomer deformation are typically so small, a deformation carried out at constant $T$ and $p$ is very close to one done at constant $T$ and $V$.

#### Force to extend a Gaussian chain

For a single chain, the end-to-end distance distribution is Gaussian. Assume the initial distance is $h_0$ and the final is $h$. The equilibrium mean square end-to-end distance $\langle h^2\rangle = Nb^2$. The distribution is given by

$$P(N,\overrightarrow{h}_0) = \left(\frac{3}{2\pi\langle h^2\rangle}\right)^{3/2}\exp\left(-\frac{3h_0^2}{2\langle h^2\rangle}\right)$$

Define the normalization factor

$$\beta\equiv\frac{3}{2\pi\langle h^2\rangle} = \frac{3}{2\pi Nb^2}$$

we have

$$P(N,\overrightarrow{h}_0) = \beta^{3/2}\exp(-\pi\beta h_0^2)$$

Similarly the final state has a probability

$$P(N,\overrightarrow{h}) = \beta^{3/2}\exp(-\pi\beta h^2)$$

The entropy depends on the number of possible conformations which is proportional to the probabilities, thus

$$\Delta S = k\ln\left[\frac{P(N,\overrightarrow{h})}{P(N,\overrightarrow{h}_0)}\right] = -k\pi\beta(h^2-h_0^2)$$

The force to extend the chain from $h_0$ to $h$ is given by

$$f = -T\left(\frac{\partial S}{\partial h}\right) = \frac{3kT}{Nb^2}h$$

The chain is like a Hooke's law spring with zero rest length. The spring stifs at higher temperature. Longer chains are easier to deform.

An elastomer is a network of many strands. The force resonsible for the overall deformation is also just a function of entropy. 

To summarize in one sentance, the elasticity of ideal elastomers is only due to the entropy change. 

:::info
**Example Questions Level 1**
1. What is the fundamental difference between amorphous and crystalline regions in a semi-crystalline polymer?
2. Which of the following is a crucial factor that hinders complete crystallization in polymers?
3. What molecular characteristic of a polymer would generally lead to a higher glass transition temperature ($T_g$)?
4. How does the degree of crystallinity typically affect the mechanical properties of a polymer?
5. Which of the following polymers has the lowest $T_g$? PS, PVC, PMMA, natural rubber (polyisoprene)
6. What techniques can be used to measure the degree of crystallinity in a polymer sample?
7. What is the primary molecular motion that is "frozen" below the glass transition temperature ($T_g$)?
8. What techniques can be used to measure the degree of crystallinity in a polymer sample?
:::



{{markdown ./license.md}}
