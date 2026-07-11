## Overview{{attrs[#blk-snsif1frksjl]}}

The central challenge in polymer chemistry is to precisely tailor molecular architectures and functionalities, mirroring the complexity and specificity found in biomacromolecules. Proteins, for example, exhibit a precise sequential order of amino acids along their polypeptide chains. These polypeptides fold into specific three-dimensional structures, providing distinct functionalities. Achieving this level of precision is the ultimate goal of polymer chemistry. However, we are still far from reaching this objective.

<!-- It is worth noting that nature also makes use of many other macromolecular materials that are not so well-controlled as proteins and DNA; examples include polysaccharides such as cellulose, chitin, and starch. -->

### Limits of conventional polymerization methods

Conventional polymerization methods typically involve linking a single type of monomer unit repeatedly or combining a few types of monomer units in a statistical manner. 

- The average molecular weight of the polymers cannot be easily adjusted as demanded. 
- This often results in polymers with broad molecular weight distributions. 
- While these methods can produce linear, branched, or crosslinked polymers, they do not allow for the design of more complex architectures;
- or provide precise control over the composition at specific positions within the molecule. 

### Living polymerization

Achieving the precision found in biological systems remains a significant challenge, but notable progress has been made. A pioneering example is the ‘living polymerization’ discovered by Michael Szwarc in 1956. He demonstrated that the anionic polymerization of styrene with an alkali metal/naphthalene system in tetrahydrofuran (THF) could continue until all monomers were consumed. Remarkably, adding another batch of monomer could extend the polymerization, provided it was not intentionally quenched.  

Living polymerization 
: Chain-growth process for which there are no irreversible termination or transfer reactions.

Living polymerization has several significant features:

1. The number of active centers remains constant throughout the polymerization process, meaning each initiator (or initiation site) results in one polymer chain with one active chain end.
2. All initiators initiate the polymerization at roughly the same time. 
3. The number average degree of polymerization can be easily calculated as the number of monomers consumed divided by the number of active centers.
4. The polymers have chain end functional groups determined by the structures of the initiator and externally added chain terminator.
5. The molecular weight distribution is narrow, i.e., $M_w/M_n \approx 1 + \frac{1}{DP_n}$

These features enable the design of polymers with relatively uniform sizes and desired molecular weights. Additionally, the functional groups at the chain ends can be utilized for further reactions, allowing for the construction of more complex macromolecular architectures.

### Beyond living anionic polymerization

The majority of conventional polymerization methods, with the exception of some anionic polymerizations, are not living. The challenge lies in adjusting reaction systems to achieve the features that mimic living polymerization. A typical desired polymerization scheme involves an initiator with the structure $\ce{R-X}$, which generates an active center, $\ce{R^*}$. From this active center, a polymer chain can grow resulting in $\ce{R-M_i-X}$. The resulting polymer possesses an $\ce{-X}$ chain end, which can serve as a macroinitiator for further polymerization. Living anionic polymerization meets these criteria. For instance, polymerization initiated by n-butyllithium ($\ce{BuLi}$) produces polymers with the structure $\ce{BuM_iLi}$. The question remains: how can other types of polymerization, such as cationic and radical, be adapted to follow this scheme?

$$\ce{R-X ->[+M] R-M_i-X}$$

#### Reversible deactivation

One commonly applied strategy is **reversible deactivation polymerization**. If the initiator ($\ce{R-X}$) can be activated spontaneously or by a catalyst to produce the active center and establish an equilibrium between a dormant and an activated state, it becomes possible to control the molecular weight, molecular weight distribution, and chain-end functionalities. This strategy can be applied to cationic polymerization, radical polymerizations, and some ring-opening polymerizations. Although chain transfer and termination can still occur, under properly selected conditions, the majority of the product will have the desired structure ($\ce{R-M_i-X}$) and chain length. 

$$\ce{R-X ->[activation] R^* ->[+M] R-M_i^* ->[deactivation] R-M_i-X}$$

#### Fixed chain end catalyst

Another possible route is to use an initiator $\ce{R-X}$, where the $\ce{-X}$ functionality, typically a catalyst, remains associated with the propagating chain end while monomers are added through a coordination and insertion mechanism. This allows for controlled polymerization, known as **single-site catalyst polymerization**. Heterogeneous Ti-based Ziegler-Natta catalysts do not meet this requirement because chain transfer occurs frequently, meaning each catalyst initiates one polymer chain and another, which become dead chains once chain transfer happens. Therefore, using a strongly associated transition metal catalyst that always coordinates to one chain end and typically does not involve transfer reactions can make coordination polymerization controllable. besides coordination plymerization of olefins, ring-opening metathesis polymerization (ROMP) can be conducted similarly to produce “living” polymers. 

$$\ce{R-Cat ->[+M] R-M_i-Cat}$$

where Cat means the catalyst. 

**Catalyst transfer polycondensation (CTP)** is a chain-growth polycondensation mechanism in which the monomers do not directly react with one another and instead the monomer will only react with the polymer end group through a catalyst-mediated mechanism. 

#### Other strategies

Certain polycondensations of AB-type monomers can mimic chain-growth polymerization, resulting in a narrow molecular weight distribution. The key is that the monomers should not react directly with each other under the polymerization conditions. Instead, an initiator with an activated B group ($\ce{RB^*}$) can react with the A groups of the monomers. Once this reaction occurs, the B functional group from the previous monomer becomes activated and can continue to react with other monomers, leading to polymers of the form $\ce{RB(AB)_iAB^*}$. This type of polymerization is known as **living chain-growth polycondensation**. However, generalizing this concept is challenging, and only a limited number of monomers can be polymerized using living chain-growth polycondensation.  

$$\ce{RB^* ->[+AB] RB(AB)_iAB^*}$$

Some other less commonly used strategies include starve-fed approach, confined reactor and confined catalyst approaches, etc.  

### Stereoselective polymerization

Another significant feature we observed in biomacromolecules is their stereospecificity. Only L-amino acids serve as the building blocks of life. D-amino acid residues are rarely found in proteins; and if found, they are typically converted from L-amino acids through post-translational modifications. In contrast, synthetic polymers are predominantly meso compounds. Controlling stereoselectivity can significantly influence the properties of the product, such as crystallinity and mechanical properties. However, stereoselectivity is inherently involved only in coordination polymerization. As of the third decade of the 21st century, other polymerization methods achieve stereoselectivity only under specific conditions and for limited types of products. 

### Towards precise sequence control

Is there a way to synthesize polymers with precise sequence structures? One possible approach is to employ gene-engineered cells, using recombinant DNA techniques, to produce polymers. Although this method is not the focus of our discussion, it is certainly very useful. Focusing on purely synthetic approaches, it is possible to achieve precise sequence structures by adding one monomer at a time, purifying the product after each addition, and then repeating the process. While this step-by-step synthesis can be tedious, it has proven to be useful. With the advent of automated synthesis by programmed machines, this method can now be used to produce polymers with up to a hundred repeating units within a reasonable time frame. The synthesis of dentrimers can also be put into this category.   

### Outlook

The pursuit of simpler and more generalizable synthetic methods to produce polymers with higher levels of structural precision continues. As mentioned earlier, the ultimate goal is to achieve the precision found in biomacromolecules, such as proteins. The key question is: What can we learn from nature, and how can we utilize these lessons to pave the way for future development?

Firstly, a blueprint or template is essential. To produce polymers with precise sequence structures, we must first instruct the synthetic instrument on the specific order to follow. In cells, this blueprint is DNA or RNA. In a synthetic scenario, we can use a molecule as the blueprint or program the sequence into a computer.

Secondly, the monomers should not react with each other spontaneously under the polymerization conditions. For example, amino acids can react to form amides under suitable conditions. However, this would result in step-growth polymerization, leading to uncontrolled chain lengths and sequence structures. In cells, amino acids do not react directly with each other but instead react with the propagating polypeptide chain end, facilitated by transfer RNA (tRNA) and enzyme catalysts. 

One fascinating example of precise polymer synthesis is the Polymerase Chain Reaction (PCR) testing, which gained widespread use during the COVID-19 pandemic. From a polymer synthesis perspective, PCR is astonishing. Essentially, PCR selects a specific type of DNA strand from hundreds or thousands and reproduces the targeted one millions or billions of times. The process is step-by-step, but the selection of the targeted DNA is automatic by using proper primers, and no purification is needed after each cycle. The procedure includes: 

1. Denaturation
    - The DNA sample is heated to around 94-98°C, causing the double-stranded DNA to separate into two single strands.
2. Annealing
    - The temperature is lowered to around 50-65°C, allowing short DNA sequences called primers to bind (anneal) to their complementary sequences on the single-stranded DNA. These primers are designed to flank the target DNA region.
3. Extension
    - The temperature is raised to around 72°C, the optimal temperature for the enzyme Taq polymerase. This enzyme synthesizes new DNA strands by adding nucleotides to the primers, using the original DNA strands as templates.
3. Cycling
    - These steps (denaturation, annealing, and extension) are repeated 20-40 times, doubling the amount of target DNA with each cycle. This exponential amplification results in millions to billions of copies of the specific DNA segment. 
    
![](https://upload.wikimedia.org/wikipedia/commons/9/96/Polymerase_chain_reaction.svg)
    
 This involves a combination of biomolecules, such as DNA and enzymes, and artificial synthetic procedures, like adding reagents and changing the temperature. The result is remarkable: precise polymer synthesis via a relatively simple procedure. However, not many monomers are like nucleotides that can recognize each other and polymerize under simple conditions. Therefore, the procedure cannot be generalized for other types of polymer synthesis. Nonetheless, it is definitely inspiring.

## Reversible deactivation approach{{attrs[#blk-vzrvblmi1cao]}}

To apply a reversible deactivation scheme in a polymerization process, start by considering a polymer chain with an X chain-end functional group. Identify the conditions or catalysts required to remove this X group, leaving behind an active center of interest. Ensure that the reaction is reversible. Once these conditions are established, design a small molecule with an R group that resembles a monomer unit and an X group as described. This RX molecule can then serve as the initiator. Under appropriate reaction conditions and in the presence of monomers, the polymerization will proceed as a reversible deactivation polymerization. Additionally, the initiator structure may sometimes vary slightly or be generated in situ, providing greater flexibility in the initiation system.

### Reversible-deactivation radical polymerization

#### Nitroxide mediated radical polymerization (NMP)

Aminoxyl denotes a radical functional group with general structure $\ce{R2N–O*}$. It is commonly known as a nitroxyl radical or a nitroxide. Sterically hindered aminoxyls without α-hydrogens, such TEMPO and TEMPOL, and are persistent (stable) radicals and find use in a range of applications. 

:::: cols
::: col
TEMPO: 

![](https://upload.wikimedia.org/wikipedia/commons/5/5c/2%2C2%2C6%2C6-Tetramethylpiperidinyloxyl.svg =150x)
:::
::: col
TEMPOL: 

![](https://upload.wikimedia.org/wikipedia/commons/5/59/4-Hydroxy-TEMPO.svg =150x)

::::
They can be used in the radical polymerization of styrene and make this process an reversible deactivation polymerization. 

<!-- The Mechanism of the Self-Initiated Thermal Polymerization of Styrene. Theoretical Solution of a Classic Problem, JASC 2005, 127, 4, 1265, https://doi.org/10.1021/ja0448667 -->

Consider the simplest radical polymerization system using purified styrene monomer in a sealed flask, devoid of oxygen. When heated to 100°C, self-initiated polymerization occurs. Although the self-initiation mechanism is complex, once initiated, polymer chains grow by adding monomers and eventually terminate, forming dead chains. The polymerization process is relatively slow, achieving about 2% monomer conversion per hour at 100°C. While chain transfer does occur, it is negligible. Due to the low radical concentration, each radical has a relatively long lifetime, resulting in polymers with high molecular weight.

![TEMPOStyrene](https://hackmd.io/_uploads/r1EmEU10R.svg =200x)

When 1% (mol/mol) of 2,2,6,6-Tetramethyl-1-(1-phenylethoxy)piperidine is added to styrene and heated to 110-130°C, the polymerization behavior changes significantly. The C-O bond in this compound can undergo reversible dissociation at elevated temperatures, although the equilibrium heavily favors the associated molecule. Despite this, even at very low concentrations (typically around $\pu{1e-8 mol/L}$), carbon radicals are produced and can initiate polymerization by adding to monomers. TEMPO is also generated, which rapidly captures the propagating radicals and returns them to a dormant state. Consequently, each molecule of 2,2,6,6-Tetramethyl-1-(1-phenylethoxy)piperidine acts as an initiator, resulting in one polymer chain capped by a TEMPO unit. Since all initiators statistically begin polymer chain growth simultaneously and each polymer chain grows at the same rate, the resulting polymers exhibit a narrow molecular weight distribution. The experimental value of $M_w/M_n$ typically ranges from 1.1 to 1.2.

Self-initiation occurs as usual, contributing to the formation of additional polymer chains. However, since self-initiation is relatively slow, the number of these additional chains is much lower than the number of initiators. Termination also occurs as a competing reaction with propagation, resulting in dead chains. As long as the number of dead chains is relatively small compared to the number of initiators, the majority of the resulting polymers remain “alive” with TEMPO-capped chain ends, which can be used for further reactions. Consequently, no polymer chains grow significantly longer than others, leading to polymers with comparable molecular weights and a narrow molecular weight distribution. 

![link text](https://pubs.acs.org/cms/10.1021/cr990119u/asset/images/medium/cr990119uh00005.gif =400x)

This type of polymerization is known as nitroxide-mediated polymerization (NMP), a reversible-deactivation approach to achieve controlled polymerization. The key to this technique is the spontaneous and reversible dissociation of the chain-end functional group. Compared to the polymerization of pure styrene without any additional reagents, this system involves only one additional ingredient: TEMPO. However, the introduction of this ingredient can increase complexity beyond the desired level. TEMPO can also lead to a catalytic termination process, increasing the number of dead chains. In case of styrene and TEMPO system, the catalytic termination is negligible. However, depending on the monomers, nitroxide, and temperature, the contribution of these side reactions can vary significantly. It is common that introducing one more reagent to the reaction system not only leads to the desired reaction mechanisms but also causes unwanted side reactions. But we do not always have full knowledge about those side reactions.  

![](https://pubs.acs.org/cms/10.1021/cr990119u/asset/images/medium/cr990119uh00017.gif =400x)

<!--
Unfortunately, TEMPO only works for styrene and similar monomers. 

Design the stable radical to adjust the activity and expand possible monomers. 

Advantages and limits 
-->

#### Atom transfer radical polymerization (ATRP)

ATRP is a catalyzed reversible deactivation process. Usually a halogen chain end is involved, which can be activated by a transition metal catalyst. Thus, ATRP usually employs an alkyl halide as the initiator (R-X). Various transition metal complexes, namely those of Cu, Fe, Ru, Ni, and Os, have been employed as catalysts for ATRP. In an ATRP process, the dormant species is activated by the transition metal complex to generate radicals via one electron transfer process. Simultaneously the transition metal is oxidized to higher oxidation state. This reversible process rapidly establishes an equilibrium that is predominately shifted to the side with very low radical concentrations. The number of polymer chains is determined by the number of initiators. Each growing chain has the same probability to propagate with monomers to form living/dormant polymer chains (R-Pn-X). As a result, polymers with similar molecular weights and narrow molecular weight distribution can be prepared. 

![](https://upload.wikimedia.org/wikipedia/commons/c/c5/ATRP_on_styrene.png)

ATRP of styrene with targeted degree of polymerization 100. PMDETA stands for N,N,N′,N′′,N′′-pentamethyldiethylenetriamine.

<!-- 
catalyst activity
monomers 
Initiator activity
Advantages and limits 
-->

#### Reversible addition-fragmentation chain transfer (RAFT)

In RAFT polymerization, a dormant polymer chain is capped by a thiocarbonylthio group. When another propagating chain with a chain-end radical approaches, chain transfer can rapidly occur at the chain end, forming an intermediate species that links both polymer chains. This unstable intermediate species then dissociates, resulting in one propagating chain and one capped dormant chain, as illustrated in the figure below. 

![](https://upload.wikimedia.org/wikipedia/commons/9/96/RAFT_ChainEquilibration.png)


The reactions associated with RAFT equilibria occur in addition to the conventional radical polymerization steps of initiation, propagation, and termination. In an ideal RAFT process, the RAFT agent functions solely as a transfer agent. Once radicals are generated from initiators such as AIBN, they initiate the growth of polymer chains. However, the propagating radicals quickly transfer to another chain, and then another, facilitated by the chain transfer agent. Consequently, all chains have an equal probability of growing, with the majority being capped by thiocarbonylthio groups. Termination is not suppressed by the RAFT process. The retention of thiocarbonylthio groups in the polymeric product is responsible for the living character of RAFT polymerization, making the process suitable for synthesizing block copolymers and end-functional polymers.

<!-- 
CTA design 
monomers
Advantages and limits 
-->

<!--

#### Other RDRP

-->

#### Common features

The prerequisite of a successful RDRP is fast and reversible activation/deactivation of propagating chains. There are many RDRP methods but all can be categoried into three types: deactivation by catalyzed reversible coupling, e.g., ATRP, deactivation by spontaneous reversible coupling, e.g., NMP, and deactivation by degenerative transfer (or reversible chain transfer), e.g., RAFT. A mixture of different mechanisms is possible; e.g. a transition metal mediated RDRP could switch among ATRP, OMRP and DT mechanisms depending on the reaction conditions and reagents used.

In any RDRP processes, the radicals can propagate with the rate coefficient $k_p$ by addition of a few monomer units before the deactivation reaction occurs to regenerate the dormant species. Concurrently, two radicals may react with each other to form dead chains with the rate coefficient $k_t$. The rates of propagation and termination between two radicals usually are not influenced by the mechanism of deactivation or the catalyst used in the system.

In addition, other chain breaking reactions such as irreversible chain transfer and catalytic termination reactions that involves the propagating radicals and solvent, monomer, polymer, catalyst, additives, etc. would introduce additional loss of chain end functionality. 

![](https://upload.wikimedia.org/wikipedia/commons/8/8d/Three_types_of_mechanisms_of_RDRP.svg)

In all RDRP methods, the theoretical number average molecular weight of obtained polymers, $M_n$, can be defined by following equation:

$$M_n = M_m\times\frac{[\ce{M}]_0 - [\ce{M}]_t}{[\ce{R-X}]_0}$$

where $M_m$ is the molecular weight of monomer; $[\ce{M}]_0$ and $[\ce{M}]_t$ are the monomer concentrations at time $0$ and time $t$; $[\ce{R-X}]_0$ is the initial concentration of the initiator.

Besides the designed molecular weight, a well controlled RDRP should give polymers with narrow molecular distributions, which can be quantified by $M_w/M_n$ values, and well preserved chain end functionalities. 

A well controlled RDRP process requires: 1) the reversible deactivation process should be sufficiently fast; 2) the chain breaking reactions which cause the loss of chain end functionalities should be limited; 3) properly maintained radical concentration; 4) the initiator should have proper activity that facilitates fast initiation.

### Living cationic polymerization

In conventional cationic polymerization the actual initiator is usually $\ce{H+}$. However, a single initiator species is often not sufficient in cationic polymerizatin. A second ingredient or cocatalyst is needed. The initiator systems are generally Lewis acids, such as $\ce{BF3, AlCl3, TiCl4}$ with a proton-donating coinitiator like water or methanol, or protic acids, such as $\ce{H2SO4, HClO4, HI}$. In case of Lewis acid catlysts, equilibria are established. 

$$
\begin{align*}
& \ce{H2O + BF3 <=> H+ + F3BOH-} \\
& \ce{H2O + AlCl3 <=> H+ + Cl3AlOH-} \\
& \ce{CH3OH + TiCl4 <=> H+ + Cl4TiOCH3-}
\end{align*}
$$

With insufficient cocatalyst the equilibrium lie far to the left, while too much cocatalyst can terminate the chain or destroy the catalyst. 

In case of protic acids, the proton concentration depend on the ionization equilibria which are stronly influenced the choice of solvent. 

In both cases, not all available protons intiate the polymerization at the same time, but rather slow initiation is often observed.

Besides initiation and propagation, cationic polymerization often involves several complications such as $\beta$-proton transfer, hydride transfer from monomer, intermolecular hydride transfer, spontaneous termination (or chain transfer to counterion). 

To approach living cationic polymerization, there are to tasks: 1) enable fast initiation that all initiators start to propagate at the same time; 2) select conditions that maximize the rate of propagation relative to transfer. To extend the lifetime of the growing chain, a reversible deactivation equilibrium is favorable. 

One simple example is $\ce{HI}$ initiated polymerization of vinyl ether in the presence of $\ce{I2}$. Fist, $\ce{H+}$ reacts with monomer via a typical addition reactin. The presence of $\ce{I2}$ can activate the addition product by removing the I to form $\ce{I3-}$ living a carbocation with can propagate with monomers. The equilibrium lies strongly towards the dormant state. 

![](https://pubs.acs.org/cms/10.1021/cr900225g/asset/images/medium/cr-2009-00225g_0037.gif)

## Kinetics of RDRP{{attrs[#blk-4a6nlesqbse7]}}

In this section, we will examine the following key parameters involved in the polymerization process: the polymerization rate, which is proportional to the radical concentration; the number of polymers produced; the relationship between the number-average molecular weight and monomer conversion; and the distribution of molecular weight. Be careful -- in this section, we consider only ideal kinetic models, including thermal initiator decomposition, propagation, termination, and RDRP equilibrium. Real systems are often far more complex, and deviations from these ideal cases may occur.

### NMP and normal ATRP

**NMP** represents the simplest RDRP system. The initiator utilized for the NMP of styrene is 2,2,6,6-tetramethyl-1-(1-phenylethoxy)piperidine. Structurally, it resembles the addition product formed by styrene (with one extra hydrogen atom) and a TEMPO molecule. For simplicity, we refer to this compound as St-TEMPO.

Consider the scenario involving two St-TEMPO molecules. When heated, each molecule can dissociate into two components: St* and TEMPO. This dissociation process is reversible, allowing the fragments to recombine into the original St-TEMPO molecule. However, it is not obligatory for TEMPO to reattach to its original partner; TEMPO can also couple with a different St*. Additionally, two St* radicals can react with each other to form an St-St molecule. Notably, TEMPO radicals cannot couple with one another. The accompanying figure illustrates all three possible reactions.

![](https://lh3.googleusercontent.com/d/1-C26KG6QWNJFigfIBcbONIZc8197tHvx =600x)

If a system contains many St-TEMPO molecules, heating it will establish a dynamic equilibrium between St-TEMPO and its dissociation products, St* and TEMPO. During this process, reactions between St* radicals will occur, leading to a gradual decrease in the number of St-TEMPO molecules. This decrease is accompanied by the accumulation of TEMPO. This phenomenon, known as the persistent radical effect, arises from TEMPO's stability as a long-lived radical, causing its concentration to increase gradually and continuously. As the concentration of St* decreases, the coupling reaction rate between two St* radicals correspondingly diminishes.

$$\ce{St-TEMPO <=>[K_{NMP}] St* + TEMPO}$$

$$K_{NMP} = \frac{[\ce{St*}][\ce{TEMPO}]}{[\ce{St-TEMPO}]}$$

The value of $K_{NMP}$ is very small, thus the concentration of radicals, $[\ce{St*}]$, is always very low. Especially, the concentration of TEMPO will build up, leaving even lower level of $[\ce{St*}]$. 

Finally, introducing styrene to the system at a concentration much higher than that of St-TEMPO initiates polymerization. The number of resulting polymer chains theoretically equals the initial number of St-TEMPO molecules. Upon the formation of St*, it can react with styrene units to create (St)$_n*$ radicals. Regardless of the number of monomer units added to an individual polymer chain, the subsequent reactions—whether between (St)$_n*$ and TEMPO, or between two (St)$_n*$ radicals—proceed in the same manner as previously described. 

Due to termination reactions, the actual number of active polymers—defined as polymers with TEMPO chain ends—is slightly lower than the initial number of St-TEMPO molecules. The number of active polymers decreases slowly but continueously during the polymerizatin. However, when calculating the theoretical average molecular weight, we still use the initial concentration of St-TEMPO, represented as $[\ce{R-X}]_0$.

The formula for the theoretical number-average molecular weight is given by: 
$$M_n = M_m \times \frac{[\ce{M}]_0 - [\ce{M}]_t}{[\ce{R-X}]_0}$$

where:
- $M_m$ is the molecular weight of the monomer,
- $[\ce{M}]_0$ is the monomer concentration at time $t=0$,
- $[\ce{M}]_t$ is the monomer concentration at time $t$.

During polymerization, the radical concentration is initially high but drops rapidly as TEMPO accumulates. As polymerization progresses, the radical concentration decreases at a much slower rate, influenced by the persistent radical effect. 

**Normal ATRP** utilizes alkyl halide (RX) as the initiator. The process requires a catalyst, such as Cu(I)X paired with a suitable ligand, to generate an alkyl radical by facilitating the transfer of the halogen atom to oxidize Cu(I)X into Cu(II)X$_2$. Assuming the initial concentrations of RX and Cu(I)X are equal, the reaction kinetics closely resemble those observed in NMP. 

![](https://upload.wikimedia.org/wikipedia/commons/6/6a/ATRP_general.png)

Equilibrium radical concentration:

![](https://wikimedia.org/api/rest_v1/media/math/render/svg/30cc5d17e88a09ffcf5c87757ad665152bca820d)

In the example shown above, chlorine serves as the halogen.
The system achieves equilibrium involving four key reagents: RCl, Cu(I)Cl/ligand, R* (or P*), and Cu(II)Cl$_2$/ligand. Initially, the radical concentration is relatively high; however, as termination occurs and Cu(II)Cl$_2$/ligand accumulates, the radical concentration gradually diminishes to a much lower level. As polymerization progresses, the radical concentration continues to decrease slowly, accompanied by a steady increase in Cu(II)Cl$_2$/ligand. The calculation of theoretical molecular weight is based on the initial concentration of RCl, though the actual number of halogen capped polymer chains decreases slowly and coninuously.

In both NMP and normal ATRP, the average molecular weight of the resulting polymers increases linearly with monomer conversion. As polymer chains continue to grow, the molecular weight distribution becomes progressively narrower. 

### ICAR ATRP and RAFT

**ATRP by Activator Regeneration** 

In ATRP, it is not necessary to have an equal amount of initial RX and Cu(I). For example, polymerization can proceed with only 10% Cu(I) relative to RX. Even with just 1% Cu(I), the polymerization will begin, but may halt once the majority of Cu(I) is converted to Cu(II). To overcome this, introducing a method to reduce Cu(II) back to Cu(I) can allow the polymerization to continue. Furthermore, if a mechanism to regenerate Cu(I) from Cu(II) is available, the initial amount of Cu catalyst can be further minimized. Interestingly, it is not essential to start with Cu(I)—beginning with Cu(II) and reducing it to Cu(I) in situ will enable the polymerization to progress equally effectively. ATRP utilizing trace amounts of Cu catalyst has become widely adopted due to its efficiency and versatility. The process of reducing Cu(II) to Cu(I), known as activator regeneration, plays a pivotal role in sustaining polymerization. Various methods can be employed for activator regeneration, including the use of reducing agents like vitamin C, thermal initiators such as AIBN, electrochemical reactions, photoreduction, or even mechanical reactions. These approaches offer flexibility, enabling precise control over the polymerization process and minimizing the catalyst's environmental impact.

![](https://upload.wikimedia.org/wikipedia/commons/e/eb/Activator_Regeneration_Atom_Transfer_Radical_Polymerization.svg)

**ICAR ATRP** 

ATRP with trace amounts of Cu catalyst, when paired with a thermal initiator, is termed Initiators for Continuous Activator Regeneration (ICAR) ATRP. The reaction system typically comprises a thermal initiator, such as AIBN, a monomer, an alkyl halide initiator (RX), and a Cu catalyst, which can be either Cu(I) or Cu(II).

If RX and the Cu catalyst are removed from the system, the resulting mixture mirrors a conventional radical polymerization setup, as discussed in the previous chapter. Thus, when RX and Cu are present, all the reactions characteristic of conventional radical polymerization still occur in the same manner.

Introducing RX alone into a conventional radical polymerization system has no effect, as RX remains unchanged throughout polymerization. Likewise, adding Cu(I) catalyst without RX does not lead to any reaction involving Cu(I) during polymerization.

However, when both RX and Cu catalyst are introduced into a conventional radical polymerization system, new reactions emerge, leading to the establishment of ATRP equilibrium. Cu(I)X/L interacts with RX or PX to generate radicals, while these radicals react with Cu(II)X₂/L to form RX or PX. A radical generated from AIBN does not merely initiate a single polymer chain but is continuously transferred to other RX molecules due to the ATRP mechanism. This does not mean that the same radical is passed from one chain to another; rather, ATRP equilibrium ensures that whenever one radical is deactivated, another is activated, preventing net radical consumption. The decomposition of AIBN contributes to the net radical generation, while termination accounts for radical consumption. Before termination occurs, a single radical can enable multiple polymer chains to incorporate more monomer units, ensuring that polymer chains grow at a similar rate.

Consequently, the radical concentration in ICAR ATRP should be comparable to that of conventional radical polymerization under identical conditions without RX and Cu. Likewise, the polymerization rate and extent of termination should be nearly the same. However, the number of polymer chains in ICAR ATRP is primarily dictated by the number of RX molecules, whereas in conventional radical polymerization, it is determined by the number of decomposed AIBN molecules. In ICAR ATRP, AIBN decomposition contributes a small fraction of additional polymer chains beyond those derived from RX. Since AIBN is typically present at much lower concentrations than RX, and only a small fraction undergoes decomposition, the number of polymer chains remains predominantly governed by the RX count.

**RAFT** 

RAFT polymerization relies on a thermal initiator to generate radicals, each of which can be transferred to multiple polymer chains via reversible chain transfer, facilitated by RAFT agents (also known as chain transfer agents, CTAs). The net radical generation and consumption in RAFT polymerization are equivalent to those in ICAR ATRP. The number of polymer chains is primarily determined by the quantity of CTA, with each CTA effectively leading to the formation of a single polymer chain. Similar to ICAR ATRP, a small fraction of polymers arises from AIBN decomposition, contributing to the overall polymer system.

In both ICAR ATRP and RAFT, the average molecular weight of the resulting polymers increases linearly with monomer conversion. As polymer chains continue to grow, the molecular weight distribution becomes progressively narrower. The number of active polymers, i.e., those with halogen chain end for ATRP and CTA for RAFT, remains constant. This is different from normal ATRP. However, there would be additional polymer chains produced by thermal initiator decomposition. 

> [OVESET -- Atom Transfer Radical Polymerization](https://colab.research.google.com/github/wangyu16/PolymerScienceEducation/blob/master/OVESET/04_ATRP.ipynb)

## Single site catalyst approach{{attrs[#blk-4ez7tzyshzwq]}}

### Ziegler-Natta catalysts

Ziegler–Natta recipe consists of two components: 
- a halide or other compound of a transition metal from among the group IVB to VIIIB elements, 
	- including $\ce{TiCl4, TiCl3, VCl4, VCl3, ZrCl4, CrCl3, MoCl5, CuCl}$;
- and an organometallic compound of a representative metal from groups IA to IIIA,
	- including $\ce{(C2H4)3Al, (C2H5)2Mg, C4H9Li, (C2H5)2Zn}$.

The individual components can initiate polymerizations:
- $\ce{TiCl4}$ can initiate cationic polymerization;
- $\ce{C4H9Li}$ can initiate anionic polymerization. 

But the combination is responsible for another different mechanism. When the two components are used together, complicated exchange reactions are possible. The catylst often must "age" to attain maximum effectiveness. Possible exchange equilibria are

$$\ce{2Al(C2H5)3 <=> Al2(C2H5)6 <=> [Al(C2H5)2]+ + [Al(C2H5)4]-}$$

$$\ce{TiCl4 + [Al(C2H5)2]+ <=> C2H5TiCl3 + [Al(C2H5)Cl]+}$$

The organotitanium halide can be reduced to $\ce{TiCl3}$

$$\ce{C2H5TiCl3 -> TiCl3 + C2H5*}$$

The free radical can initiate radical polymerization. The Ziegler-Natta systems encompass several mechanisms for the initiation of polymerization. To account for stereoregularity, there must be a coordination mechanism in which both the grwoing chain and the monomer coordinate with the catalyst. 

Since the coordination almost certainly involves the transition metal atom, there is a resemblance here to anionic polymerization. 

Variables of Zieglar-Natta catalyst system include:

1. Catalyst solubility. Ti based catalysts are mostly heterogeneous systems. Monomers that interact weakly with catalysts, i.e., non-polar monomers, requires more extreme orienting effect of solid surface for the formation of a stereoregular product. Thus heterogeneous catalysts are needed. For polar monomers, they interact stronger with catalysts, thus homogeneous catalysts are able to exert sufficient control for stereoregularity. 
2. crystal structure of solids. The $\alpha$-crystal form of $\ce{TiCl3}$ is an excellent catalyst. It is believed the stereoactive Ti ions in this crystal are located at the edges of the crystal, where chloride ion vacancies in the coordination sphere allow coordination with the monomer molecules. 
3. Tacticity of products. Most solid catalysts produce isotactic products. Syndiotacticity is mostly produced by soluble catalysts. Syndiotactic polymerizations are carried out at low temperatures, and even the catalyst must be prepared at low temperatures. With polar monomers syndiotacticity is also promoted by polar reaction media.
4. Rate of polymerization. The rate of polymerization for homogeneous systems closely resembles anionic polymerization. For heterogeneous systems the concentration of alkylated transition metal sites on the surface appears in the rate law. Faster polymerization may result in lower degree of stereoregularity. 

The general picture postulates an interaction between monomer and catalyst such that a complex is formed between the $\pi$ electrons of the olefin and the $d$ orbitals of the transition metal. A crucial consideration in the coordination is maximizing the overlap of the orbitals involved. Titanium(III) ions seem ideally suited for this function; higher effective nuclear charge on the metal results in less spatial extension of d orbitals and diminished overlap.

Two generalized models about the mechanism: monometallic mechanism and bimetallic mechanism.

Monometallic mechanism. This shifts the vacancy – represented by the square – in the coordination sphere of the titanium to a different site. Syndiotactic regulation occurs if the next addition takes place via this newly created vacancy. Isotactic growth the polymer chain must migrate back to its original position.

![fig5_11](./img/Monometallic.png)

Bimetallic mechanism. The precise distribution of halides and alkyls is not spelled out because of the exchanges described by Reaction. An alkyl bridge is assumed based on observations of other organometallic compounds. The $\pi$ coordination of the olefin with the titanium is followed by insertion of the monomer into the bridge to propagate the reaction.

![fig5_12](./img/Bimetallic.png)

In Ziegler-Natta system there might be multiple catalytic sites active in a given polymerization leading to greatly different propagation rates. Polymer materials produced by Ziegler–Natta catalysts, especially under commercial conditions, tend to be highly heterogeneous at the molecular level. 

Heterogeneous catalysts are the majority in commercial use. Though complicated in mechanisms, it is easy to separate the catalyst from the product. 

### Single site catalyst 

Single-site catalyst
: One that has a single, well-defined catalytic geometry that can control the desired aspect of propagation.

Single-site polymerization catalysts are usually homogeneous: they are molecularly dispersed within the reaction medium. This situation leads to better defined products, and is much more amenable to detailed studies of mechanism. Furthermore, strategies for immobilizing such catalysts are available, making them also of potential commercial interest.

Most single-site catalysts have the general formula [L~n~MP], where L~n~ represents a set of ligands, M is the active metal center, and P is the growing polymer. Cyclopentadienyl (Cp) rings are common ligands lead to metallocene systems. 

Single-site catalysts involve another component. The most common is a partially hydrolyzed trimethyl aluminum species -- methylaluminoxane (MAO). The active center is more properly denoted [L~n~MP]^+^[X]^-^. The counterion contains MAO and a displaced ligand, such as chloride. 

The stereoregulation of monomer addition can be achieved through one of two modes.

- **Chain-end control:** the addition of a monomer is influenced mostly by the configuration of the previous repeat unit. 
- **Site control:** the ligand set may be chosen to provide a chiral confining environment, which exerts a dominant influence on the stereochemistry of addition. 

#### α-olefin polymerization

Catalysts with a plane of symmetry, or $C_s$, provides:
- site control $\to$ syndiotactic polymers;
- chain-end control $\to$ iso- or syndiotactic polymers. 

$C_2$ symmetry [5.XVI] is isospecific under site control. The proposed mechanism is 

![str5_16](./img/Zr-1.png =100x)


![fig5_14](./img/Zr-2.png =600x)


[5.XVII] is syndiospecific, consistent with its $C_s$ symmetry. 

![str5_17](./img/Zr-3.png =150x)


Zirconocene [5.XVIII] oscillates between two isomeric structures. One catalyze isotactic polypropylene (left), the other atactic (right). The exchange between the two structures is slower than propagation resulting in blocky polymers with about 20 isotactic units and 20 atactic units in sequence. 

![str5_18](./img/Zr-4.png =300x)

<!-- G.W. Coates, Precise control of polyolefin stereochemistry using single-site metal catalysts, Chem. Rev., 100, 1223, 2000. -->


#### Polar vinyl monomer polymerization

<!-- Chem. Rev. 2009, 109, 11, 5157–5214 https://doi.org/10.1021/cr9000258 -->

Coordination polymerization of polar vinyl monomers by single-site metal catalysts will include two major types of coordination polymerization: migratory insertion (i.e., coordination-insertion) and conjugate addition (coordination-addition).Metal-catalyzedcoordination-insertion polymerization of nonpolar or polar R-olefins and metalmediated coordination-addition polymerization of polar vinyl monomers are two fundamentally different polymerization processes. 

![](https://pubs.acs.org/cms/10.1021/cr9000258/asset/images/medium/cr-2009-000258_0032.gif)

Example: Chain Initiation and Propagation Steps in MMA Polymerization by $\ce{[Cp^*_2SmH]2}$

![Screenshot 2024-09-30 at 9.38.31 AM](https://hackmd.io/_uploads/HyYEOV_AC.png =600x)


### Living ring-opening metathesis polymerization

<!-- Progress in Polymer Science Volume 32, Issue 1 , January 2007, Pages 1-29, https://doi.org/10.1016/j.progpolymsci.2006.08.006 -->

Generally, ROMP reactions involve the conversion of a cyclic olefin with significant ring-strain (>5 kcal/mol), such as cyclobutene, norbornene, cyclopentene, etc., to a polymer that also contains double bonds. The important thing to note about ring-opening metathesis polymerizations is that the double bond is usually maintained in the backbone, which can allow it to be considered "living" under the right conditions.

The general reaction process is as shown below

![1-s2.0-S0079670006000736-gr2](https://hackmd.io/_uploads/SJkLtNuA0.gif)

Major possible undesirable side reactions include

![1-s2.0-S0079670006000736-gr3](https://hackmd.io/_uploads/B1CdK4uC0.gif)

One series of very successful catalysts developed by Robert H. Grubbs are named as Grubbs catalyst which became the most commonly used catalysts for living ROMP. The figure below shows the first generation Grubbs catalyst and two of the second generation Grubbs catalysts. 

![](https://upload.wikimedia.org/wikipedia/commons/7/7b/GrubbsMetathesisCatalysts.png =400x)

One example of the synthesis of well defined block copolymer by living ROMP is shown in the figure below. 

![1-s2.0-S0079670006000736-gr26](https://hackmd.io/_uploads/HyGdo4uAC.gif)

## Step-by-step synthesis{{attrs[#blk-v7vqlbcvq04d]}}

Step-by-step synthesis discussed here aims to produce large molecular weight molecules with precise chain sequence and the same molecular architecture. 

General features: 

* The reactions involved must be highly efficient that a decent overal yield could be achieved after several/many generations/steps.
* Purification is needed after each step. 
* If AB or AB~n~ type monomers are used, usually protection and deprotection of one type of functional group is necessary.
* Using AA and BB (or B~n~) type monomers can help to avoid protection/deprotection. Similarly, using AA (or A~n~) and BC type monomers, where B and C do not react with each other but both react with A, can help to avoid protection/deprotection as well. 
* Using solid immobilized initiators to grow polymers on the solid surface can help to simplify the purification process after each step of reaction. 


### Dendrimers

Dendrimers are highly ordered, branched polymeric molecules. Typically, dendrimers are symmetric about the core, and often adopt a spherical three-dimensional morphology. The word dendron is also encountered frequently. A dendron usually contains a single chemically addressable group called the focal point or core. The difference between dendrons and dendrimers is illustrated in the figure below, but the terms are typically encountered interchangeably.

![](https://upload.wikimedia.org/wikipedia/commons/e/e8/Graphs.jpg =600x)

Dendritic molecules are characterized by structural perfection. Dendrimers and dendrons are monodisperse and usually highly symmetric, spherical compounds. A dendrimer is a nanoparticle with the size at nanometer ragnge. The surface functional groups can be used to anchor detecting agents, affinity ligands, targeting components, radioligands, imaging agents, pharmaceutically active compounds, etc. The inner space can also be used to load drugs, etc. It typically takes a long route to synthesize dendrimers, either divergently or convergently. Thus the potential applications are mainly in highly value-added areas, such as drug delivery. 

![](https://ars.els-cdn.com/content/image/1-s2.0-S2468519417302033-gr3_lrg.jpg =600x)<!-- https://doi.org/10.1016/j.mtchem.2019.04.004 -->

The figure below shows one example synthetic procedure of a dendrimer.  

![](https://ars.els-cdn.com/content/image/1-s2.0-S2468519417302033-gr6_lrg.jpg =800x)

### Precise sequence

Robotic automated synthesis gained significant progress in the first two decades of 21^st^ century. Without automation, synthesising a molecule with a precise sequence order of 100 monomer units is very time consuming. It is very doughtful if anyone would try to do so. The advance of robotic automated synthesis made such kind of task possible and applicable. 

Here are two reported examples:

Bradley L. Pentelute and coworkers at the Massachusetts Institute of Technology created an automated chemical protocol to synthesize peptides up to 164 amino acids long in hours. The machine they used is shown in the figure below. 

<!-- C&EN by Leigh Krietsch Boerner, 
May 28, 2020, A version of this story appeared in Volume 98, Issue 21. -->

![](https://s7d1.scene7.com/is/image/CENODS/09821-scicon6-amidator?$responsive$&wid=700&qlt=90,0&resMode=sharp2)

The work was published in Science 29 May 2020, Vol 368, Issue 6494, pp. 980-987, https://doi.org/10.1126/science.abb24.

Using Automated Glycan Assembly (AGA), researchers achieved the synthesis of a 100-mer polysaccharide through a 201-step process completed in 188 hours. Additionally, the convergent block coupling of 30- and 31-mer oligosaccharide fragments, also prepared via AGA, resulted in a highly branched 151-mer polymannoside. This significant advancement was published in the Journal of the American Chemical Society in 2020 (Vol. 142, Issue 19, pp. 8561–8564, https://doi.org/10.1021/jacs.0c00751).

![images_medium_ja0c00751_0003](https://hackmd.io/_uploads/S1KznQOAC.gif)


<!-- Macromolecules 2015, 48, 14, 4759–4767 

Similar synthetic procedure can be used to synthesize non-naturally occurring polymers. 
The monomer units of a polymer can be used to encode a message. This property is used, for instance, by nature to store genetic information in DNA macromolecules. Therefore, during the past decades, many researchers have aimed to recreate in vitro or in vivo the properties of nucleic acids. Peptide nucleic acids, or more generally speaking xeno-nucleic acids, are interesting examples of man-made genetic polymers. However, the genetic code is surely not the only type of code that can be “written” in a polymer. In principle, many other monomer-based codes could be developed. For example, a binary code can be potentially implemented in a synthetic macromolecule using two comonomers defined as 0 and 1 bit. This possibility is exciting because it would permit to develop a full new class of synthetic polymers, which contain sequence-coded information. Such polymers could be interesting for a variety of new applications, for example in the field of data storage and product identification. However, these tempting options are currently underexplored. It should be clarified that the development of information-containing macromolecules is not trivial. First of all, in order to contain “readable” information, such polymers should possess perfectly controlled comonomer sequences. Moreover, chemical and analytical methods that allow deciphering of sequence-coded information have to be developed. The aim of the present Perspective is to show that significant progress has been done in that direction during the past two years. For instance, convenient strategies have been reported for the preparation of monodisperse sequence-defined macromolecules. In addition, encouraging advances have been made for the sequencing of non-natural polymers. These recent results are discussed and critically analyzed herein. Altogether, monomer-based information storage should be regarded as a new property of synthetic matter.

![](https://media.springernature.com/full/springer-static/image/art%3A10.1038%2Fncomms8237/MediaObjects/41467_2015_Article_BFncomms8237_Fig1_HTML.jpg?as=webp)

-->

## Macromolecular engineering{{attrs[#blk-9gp4ytm026ug]}}

Macromolecular engineering involves (precisely) designing macromolecular structures to achieve specific material functionalities.

Broadly speaking, all polymer material development falls under the umbrella of macromolecular engineering. However, this discussion focuses on topics such as pursuing higher levels of precision and ordered structures, incorporating novel functional moieties into polymer chains, and deriving functionalities from the design of individual macromolecules. The properties of polymers synthesized directly by conventional polymerization methods from common commercial monomers are not the focus of this section.

### Miscellaneous synthetic methods

Previous sections discussed several general stragegies to achieve controlled or living polymerization to produce polymers with narrow molecular weight distribution and predetermined chain end functionalities, which are valuable tools for macromolecular engineering. Some other synthetic methods are also frequently used for tailoring the molecular structures. 

#### Click chemistry

Click chemistry is an approach to chemical synthesis that emphasizes efficiency, simplicity, selectivity, and modularity in chemical processes used to join molecular building blocks. 

For a reaction to be considered a click reaction, it must satisfy certain characteristics:

- modularity
- insensitivity to solvent parameters
- high chemical yields
- insensitivity towards oxygen and water
- regiospecificity and stereospecificity
- a large thermodynamic driving force (>20 kcal/mol) to favor a reaction with a single reaction product. A distinct exothermic reaction makes a reactant "spring-loaded".

The process would preferably:

- have simple reaction conditions
- use readily available starting materials and reagents
- use no solvent or use a solvent that is benign or easily removed (preferably water)
- provide simple product isolation by non-chromatographic methods (crystallisation or distillation)
- have high atom economy.

One most commonly used click reaction is copper(I) catalyzed azide-alkyne cycloaddition (CuAAC). 

![](https://upload.wikimedia.org/wikipedia/commons/6/6b/Azide_Alkyne_cycloaddition.png =600x)

This reaction can be used to link polymer strands together or to add pandent functional groups or to the chain ends. 

#### Supramolecular chemistry

Supramolecular polymer
: polymeric arrays of monomeric units that are connected by reversible and highly directional secondary interactions–that is, non-covalent bonds. 


![](./img/Supramolecular.png)

Supramolecular structures of polymers describe the interaction of polymer molecules to form higher level ordered structure, such as the self-assembly of block copolymer, the double helix of DNA. This is different from supramolecular polymer because in these cases the polymers are based on covalent bonds.

Apparently, there could be a combination of two. For example, two homopolymers with complementary end groups that can recognize and associate with each other can form supromolecular polymer and self-assemble as block copolymers.  

<!-- More strategies to convert step-growth polymerization to "living" polymerizations. Confined space, confined catalyst, slow addition. -->

<!-- stereo control -->


### Macromolecular architectures

Many possible macromolecular architectures have been discussed in previous sections. Here, the discussion is mainly on how to choose proper synthetic methods to achieve specific well-defined polymer structures. 

#### Polymers with specific chain end functional groups 

Living polymerization, as well as polymerization methods resembles the featuers of living polymerization, results in polymers with the same chain end functionalities. This is important for further reaction to introduce the polymer into more complex structures with higher level of order. But the chain end functional group resulted directly from the polymerization may or may not be suitable for the desired next step reactions. 

Using ATRP as an example, some possible end group transition reactions are: 

![](https://www.cmu.edu/maty/images/8d-scheme-2.jpg =600x)

End group modification is simply organic chemistry. However, the reaction must be highly efficient and selective. Otherwise, ill structured polymers will be obtained and will be difficult to remove from the product. 

#### Block copolymers

Reversible deactivation polymerization and single site catalyst polymerization typically allow sequential addition of monomers to make block copolymers. Generally, more active monomers should be polymerized first and less active monomers later; otherwise slow initiation or even no initiation would happen when trying to polymerize the second monomer. The activity here refers to both the activation of the polymer with a functional chain end group and the addition of the next monomer. 

It is also possible to use a dual functional initiator to polymerize two types of monomers via different mechanisms. Sometimes, the two polymerizations can happen simultaneously to produce a block copolymer in one pot and one step. 

In addition, click reaction can be used to link together two polymers with complementary chain end functional groups. 

#### Molecular brushes or bottlebrush polymers

<!-- Bottlebrush polymers: From controlled synthesis, self-assembly, properties to applications. Progress in Polymer Science Volume 116 , May 2021, 101387. https://doi.org/10.1016/j.progpolymsci.2021.101387 -->

Overview of the synthetic approaches and possible architectures of the products. 

![image](https://hackmd.io/_uploads/H1dY2PO0A.png)

Example of grafting from approach

![image](https://hackmd.io/_uploads/rJoR2DuAR.png)

Example of grafting through approach

![image](https://hackmd.io/_uploads/HymT3v_AA.png)


#### Surface initiated polymers

![image](https://hackmd.io/_uploads/ByCaTPdAR.png)

![image](https://hackmd.io/_uploads/rk6CTPOR0.png)

#### Bio conjugate materials

enerating polymer-modified exosomes. the conjugation of an oligonucleotide with Chol, which is then immobilized onto the exosome surface, causing the negatively charged deoxyribonucleic acid (DNA) to extend outward from the lipid membrane. This method of exosome surface modification with tailored polymers allows for the adjustment of stability and in vivo behavior of these biological entities. 

![image](https://hackmd.io/_uploads/SkSRJuuA0.png)

#### Supramolecular structures

![image](https://hackmd.io/_uploads/B1Vk-dOCA.png)

![image](https://hackmd.io/_uploads/BJSQZ_dRR.png)

![fig-9-photonic-crystals-based-on-bottlebrush-block-uoz4ld97](https://hackmd.io/_uploads/HJQ2Zu_0A.png)

#### Functional units in the polymer chains

For example, self-healing materials are typically synthesized by introducing dynamic covalent bonds into the polymer framework. 

![image](https://hackmd.io/_uploads/ByK7z__0C.png)

![](https://upload.wikimedia.org/wikipedia/commons/e/eb/Cross-linking_DA.png =600x)

### Functional materials 

The above discussion is mainly about synthetic techniques to achieve specific molecular structures and compositions. Some application aspects were also briefly involved. 

For scientific exploration we always prefer relatively simple components, clear reaction mechanisms, well defined local chemical structure and overall molecular architecture, etc. However, for commertial applications,  perfectly ordered molecular structures are not always required; instead, useful products generated from least effort and cost are prefered. These two aspects interwoven in scientific research and development, and, apparently, both are important. 

ABS resin is a copolymer of acrylonitrile, butadiene and styrene. But it is not a simple statistic copolymer of three monomers. The resin is produced by radical polymerization of acrylonitrile and styrene in the presence of polybutadiene. Due to the presence of alkene groups in the backbone of polybutadiene, the copolymer of acrylonitrile and styrene has the chance to grow onto the polybutadiene backbone. As a result, a certain fraction of grafting copolymer is produced. The final product is possiblely a mixture of acrylonitrile/styrene copolymer, grafting copolymer, unreacted polybutadiene. The grafting copolymer has variable chain lengthes and different number of branching points. The mechanical property of ABS resin can be adjusted by changing the ratio of three components. The soft polybutadiene provides impact resistancy and the acrylonitrile/sytrene copolymer provides hardness and strength. It is a very useful material with special molecular architecture, but do not have high precision molecular structures. Many application oriented material development is like the case of ABS resin. But some applications require more uniform molecular size and well defined structures, such as dendrimers used as nanoparticles for drug delivery. 

As long as useful materials are produced, the lack of precision of the composition and molecular structure should not be a issue for commercial products. One problem in common is the batch-to-batch variation of the product could be significant, which should be taken care of. 

Regardless, the ability to achieve more precise control on the molecular structure and targeted functionality is more appealing. Inspired by bio functional macromolecules, many efforts were made to pursuit such advanced functional materials. Some examples are as follows.

**Biodegradable non-metal magnetic resonance imaging agents** are synthesized as a block copolymer of poly(ethylene glycol) and polycarbonate based polymer containing pendant persistent organic radicals. The block copolymer self-assemble into micellar nanoparticles in aqueous media and can preferentially accumulate in tumor tissue. The nanomaterials are effective as metal-free MRI contrast agents. Anticancer drugs can be readily loaded into the nanoparticles for therapeutic delivery. 

![Screenshot 2024-09-30 at 3.19.43 PM](https://hackmd.io/_uploads/H1WzdKd0A.png =600x)

![image](https://hackmd.io/_uploads/H1zmdFuRR.png)


**Colorimetric pH sensor**

<!-- ACS Nano 2014, 8, 3, 2848–2856,
https://doi.org/10.1021/nn406657b -->

Blue and orange color-emitting QDs (BQDs and OQDs) are tethered on graphene oxide using poly(acrylic acid) and poly(2-vinylpyridine) as the spacer, respectively. Both polymers are pH sensitive. The PAA chains change their conformation at around pH = 4.5, while p2VP exhibit coil-globule transition at aroung pH = 3.0. The change of the polymer conformations is reflected by the change of the strength of the fluorescent emmision and can be seen directly. 


![image](https://hackmd.io/_uploads/BJeoiYORA.png)

![image](https://hackmd.io/_uploads/Sky3jFd00.png)

**Lubrication materials**

Core/shell charged polymer brushes-grafted hollow silica nanoparticles were prepared. Because of the excellent hydration capability of the shells consisting of charged polymer brushes, the functional nanoparticles can achieve a good lubricating effect in aqueous media via hydration lubrication mechanism. The ionic polymer is from 3-sulfopropyl methacrylate potassium salt. 

![image](https://hackmd.io/_uploads/BkC6RtuCC.png)





:::info
**Example Questions**

1. Compared to conventional radical polymerization what RDRP can control or improve? Average chain length, polymerization rate, molecular weight distribution, tacticity of polymers, chain end functionality, rate of termination, etc. 
2. Why conventional radical, cationic, and coordination polymerizations are not living polymerization?
3. What are the features of living polymerization?
4. Describe the main components in a NMP, normal ATRP, ICAR ATRP, and RAFT system. 
5. What are typical strategies to convert a non-living polymerization into a process mimicking the features of living polymerization? 
6. Why can the Polymerase Chain Reaction (PCR) method synthesize DNA strands with a specific sequence structure in a mixture of many other sequence structures? 
7. Describe the species involved in the equilibria of NMP, normal ATRP, ICAR ATRP, and RAFT. What are the expressions of the equilibria constants?
8. Compare a conventional radical polymerization and a ICAR ATRP under identical eraction conditions after the same reaction time, except that the ICAR ATRP has alkyle halide initiator and trace amount of Cu catalyst added. What are the same and what are different? Monomer conversion, number of polymers, molecular weight and molecular weight distribution of the resulting polymers, reaction rate of AIBN decomposition, propogation, radical termination. 
:::


{{markdown ./license.md}}
