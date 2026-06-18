## Ideal chains{{attrs[#blk-psefbb0x0eyx]}}

In this chapter, we will discuss the statistical features of polymer chain conformations and "sizes".

* To simplify the discussion we will use linear polyethylene as the example until the last section.
* A polyethylene molecule is a chain of C atoms linked together covalently. Each C atom also bond to a few H atoms.
* We only consider the positions of the C atoms to evaluate the conformation of the polymer chain.

To further simplify our discussion, we'll treat each C atom as a point in 3D space with mass, but no volume. The atoms do not have interaction unless they are covalently bonded together. While this treatment is not realistic, it allows us to create ideal chain models that enable simple mathematical descriptions. We’ll discuss the real chain conformation in a later section.


### Chain models

A polyethylene chain consists of a sequence of $n+1$ C atoms, where:

* There are $n$ bond vectors connecting adjacent C atoms with each bond has a length $l$ and a direction;
* $(n−1)$ bond angles ($\theta$) represent the angles between adjacent bond vectors;
* $(n−2)$ torsion angles ($\phi$) that are defined by three adjacent bonds labeled as $(i−1)$, $i$, and $(i+1)$. Specifically:
    * Bonds $(i−1)$ and $i$ define a plane A.
    * Bonds $i$ and $(i+1)$ define a plane B.
    * The dihedral angle between plane A and plane B is the torsion angle. This describes the rotation around the middle bond (bond $i$).

**Note: The angle between two adjacent bonds in a polyethylene chain typically has a constant value of $109.5 ^\circ$. However, in some calculations the angle between the directions of two adjacent bond vectors is used, which is actually $180^\circ - 109.5^\circ = 70.5^\circ$.**

<iframe width="100%" height="429" frameborder="0"
  src="https://observablehq.com/embed/f83e7bfd6e4996a4@109?cells=bondAngle"></iframe>

#### Freely-jointed chain (FJC) model

The simplest chain model to start with is a random walk in 3 dimensions. This model assumes all atoms are linked together with fixed bond lengths ($l$), but the bond angles ($\theta$) and torsion angles ($\phi$) can take any possible random values. Imagine each bond pointing in a completely random direction, independent of the previous bond (like steps in a random walk). This model is called freely-jointed chain model or freely-hinged chain model. To construct such a chain model, we can generate $n$ vectors with the same lengths $l$ and random directions. Then generate a series of $n+1$ points representing the atoms in 3D space by linking together the bond vectors one by one. Apparently, this model is not realistic since the bond angle for polyethylene must be $109.5 ^\circ$ rather than any random values. We will evaluate this model together with other models to see the differences and what are in common.

<iframe width="100%" height="526" frameborder="0"
  src="https://observablehq.com/embed/f83e7bfd6e4996a4@53?cells=RandomWalk3D"></iframe>

#### Freely-rotation chain (FRC) model

To make the model a little more realistic than freely-hinged chain, we can require all bond angles ($\theta$) to have a fixed value (e.g., $109.5 ^\circ$ for polyethylene). Mathematically, the bond angle can be any value between 0 and $180 ^\circ$, as long as all bond angles take the same value. However, we still allow the chain segments to rotate freely around any bond (meaning the torsion angle $\phi$ can be any value). This introduces some correlation between bond directions compared to FJC, as the next bond must lie on a cone defined by the fixed bond angle relative to the previous bond. Thus, the chain model is called freely-rotation chain model.

<iframe width="100%" height="526" frameborder="0"
  src="https://observablehq.com/embed/f83e7bfd6e4996a4@104?cells=freeRotation"></iframe>

#### Hindered-rotation chain (HRC) model

To move a little further to reality, we should consider the energy difference associated with different torsion angles ($\phi$). Due to steric interactions between atoms or groups attached to the backbone, some rotational angles are energetically more favorable than others. Polymers would prefer to adopt conformations (arrangements in space) with lower energies rather than those with higher energies. Thus the chain segments cannot rotate completely freely but suffer from some energy barriers, although these barriers are typically low enough (comparable to thermal energy $kT$) that rotation still occurs. By taking into account the rotational energy differences, we reach a new model called hindered-rotation chain model.

The *trans* (t) orientation (where substituents are furthest apart, $\phi = 180^\circ$) often has the lowest energy. The *gauche plus* (g$^+$) and *gauche minus* (g$^-$) orientations (e.g., $\phi \approx \pm 60^\circ$) are local energy minima but typically have slightly higher energy. For polyethylene, the trans ($t$) conformation has much lower energy than gauche ($g^+$ and $g^-$). The relative energy difference is about $\Delta E = 3$ kJ/mol (or 0.72 $kT$ at 500 K). The chance that the system is in a higher energy gauche state compared to the lower energy trans state can be estimated using the Boltzmann distribution ($\propto e^{-\Delta E/kT}$), which comes out to about 0.48 in this case. The energy barrier to rotate between conformations (e.g., passing through the high-energy *cis* or eclipsed state) is about 10 kJ/mol (around 2 $kT$ at 500K). This relatively low barrier means rotation is fairly easy, and polyethylene is considered a flexible polymer.

The following figure shows the conformational energy levels of butane (a short 4-carbon chain), which serves as a good model for the rotational energy profile around a C-C bond in polyethylene.

![](https://upload.wikimedia.org/wikipedia/commons/2/22/Butane_conformations_and_relative_energies.svg =600x)

### Measures of Average Chain Sizes

Since a polymer chain, composed of $n+1$ C atoms connected by $n$ bonds of length $l$, constantly changes its conformation due to thermal energy, we use statistical averages derived from the chain models (Freely-hinged, Freely-rotation, Hindered-rotation) to describe its average dimensions.

#### The Ergodic Assumption

When we calculate average properties using statistical mechanics, we typically imagine taking a snapshot of a huge number (an *ensemble*) of identical polymer chains at one instant and averaging the property over all of them. However, in experiments, we usually observe a macroscopic sample (containing many chains) over a period of time. The **ergodic assumption** bridges this gap. It states that for a system in thermal equilibrium, the average value of a property measured over a long time for a *single* system (as it explores all its possible configurations) is the same as the average value calculated over a large *ensemble* of systems at a single instant. This assumption allows us to confidently apply the results of statistical mechanics (ensemble averages) to predict the outcomes of real-world experiments (time averages on macroscopic samples).

#### End-to-End Distance

**End-to-End Vector ($\overrightarrow{h}$) and Distance ($h$):**
    
The vector connecting the first C atom (atom 0) to the last C atom (atom $n$) is the end-to-end vector, $\overrightarrow{h}$. It's calculated by adding up all the individual bond vectors $\overrightarrow{l}_i$ (each representing a single bond in the chain backbone) from the first bond ($i=1$) to the last bond ($i=n$):
$$\overrightarrow{h} =\sum_{i=1}^n\overrightarrow{l}_i$$
*(Think of this like finding your final displacement after taking $n$ steps, where each step $\overrightarrow{l}_i$ has a fixed length $l$ but potentially varying direction).*

The instantaneous end-to-end distance is simply the magnitude (length) of this vector: $h = |\overrightarrow{h}|$. This value changes constantly as the polymer chain wiggles.

For any chain model allowing random overall orientation in space, the *average* end-to-end vector is zero: $\langle \overrightarrow{h} \rangle = \overrightarrow{0}$.

*(Explanation: The chain is equally likely to end up in any direction relative to its starting point. For every possible vector $\overrightarrow{h}$, there's an equally likely vector $-\overrightarrow{h}$. When averaged over all possibilities, these cancel out, resulting in a zero average vector).*

**Root-Mean-Square (RMS) End-to-End Distance ($\langle h^2\rangle^{1/2}$):**
        
Since the average vector $\langle \overrightarrow{h} \rangle$ is zero and not informative about size, we look at the *mean square* end-to-end distance, $\langle h^2\rangle$. This is the average of the squared magnitude of the end-to-end vector, calculated as the dot product of the vector with itself: $\langle h^2\rangle = \langle\overrightarrow{h}\cdot\overrightarrow{h}\rangle$. Because $h^2$ is always non-negative, its average will be non-zero and provides a measure of the chain's average squared span. The square root of this average, $\langle h^2\rangle^{1/2}$, gives the RMS end-to-end distance, which has units of length and represents a characteristic size of the polymer coil. The general expression for $\langle h^2\rangle$ is derived by substituting $\overrightarrow{h} = \sum \overrightarrow{l}_i$ into the dot product:

$$\langle h^2\rangle = \langle (\sum_{i=1}^n \overrightarrow{l}_i) \cdot (\sum_{j=1}^n \overrightarrow{l}_j) \rangle = \sum_{i=1}^n \sum_{j=1}^n \langle \overrightarrow{l}_i \cdot \overrightarrow{l}_j \rangle$$
                
This double sum can be split into terms where $i=j$ and terms where $i \neq j$. When $i=j$, $\langle \overrightarrow{l}_i \cdot \overrightarrow{l}_i \rangle = \langle l^2 \rangle = l^2$ (since bond length $l$ is fixed). There are $n$ such terms, giving a total of $nl^2$. 

When $i \neq j$, $\langle \overrightarrow{l}_i \cdot \overrightarrow{l}_j \rangle = \langle l \cdot l \cos\theta_{ij} \rangle = l^2 \langle\cos\theta_{ij}\rangle$, where $\theta_{ij}$ is the angle between bond vector $i$ and bond vector $j$. This term accounts for the correlation (or lack thereof) between the orientations of different bonds.
                
Combining these gives the general result:
                
$$\langle h^2\rangle = nl^2 + l^2\sum_{i=1}^n\sum_{j\neq i}^n\langle\cos\theta_{ij}\rangle$$
                
*(The first term, $nl^2$, represents the simple sum if all bonds were uncorrelated like in FJC. The second term captures the effect of correlations introduced by fixed bond angles or hindered rotations).*

The specific result for $\langle h^2\rangle$ depends on how $\langle\cos\theta_{ij}\rangle$ behaves in each chain model.

**For the Freely-Jointed Chain (FJC):** The bond angle term averages to 0, thus:

$$\langle h^2\rangle = nl^2$$


**For the Freely-Rotating Chain (FRC):** The bond angle $\theta$ between adjacent bonds is fixed, but the torsion angle $\phi$ is random. This creates correlations: adjacent bonds ($j=i\pm 1$) have $\langle\cos\theta_{i, i\pm 1}\rangle = \cos\theta$. Bonds further apart also have non-zero average correlations that decay with separation $|i-j|$. Evaluating the sum $\sum_{i\neq j}\langle\cos\theta_{ij}\rangle$ (details omitted here) leads to:
    
$$ \langle h^2\rangle = nl^2\frac{1+\cos\theta}{1-\cos\theta} $$

*(Note: In this formula, following modern convention [e.g., Doi & Edwards, Rubinstein & Colby], $\theta$ represents the direct angle between adjacent bond vectors, typically the tetrahedral angle $\approx 109.5^\circ$. An older convention [Flory] sometimes defined $\theta$ as the supplement angle $180^\circ - 109.5^\circ \approx 70.5^\circ$, which requires careful interpretation of the correlation terms.)*

Interpretation using the modern convention: If $\theta=90^\circ$, $\cos\theta=0$, and we recover the FJC result. For typical tetrahedral angles like $109.5^\circ$, $\cos\theta \approx -1/3$. The factor $\frac{1+\cos\theta}{1-\cos\theta}$ becomes $\frac{1 - 1/3}{1 - (-1/3)} = \frac{2/3}{4/3} = 1/2$. The FRC restricts the angle to $109.5^\circ$. The average projection of one bond onto the next is $\cos(109.5^\circ) \approx -1/3$. This negative projection means successive bonds tend to point slightly backwards on average relative to each other, leading to a more compact structure ($\langle h^2 \rangle \approx nl^2/2$) than an FJC where $\langle \vec{l}_i \cdot \vec{l}_{i+1} \rangle = 0$. The factor $\frac{1+\cos\theta}{1-\cos\theta}$ quantifies how this fixed bond angle influences the overall chain dimensions compared to the FJC model. <!-- Can add to simulation assignment, to test when theta is very small, 90, 109.5, and close to 180, how does the size of FJC compare to FRC model. -->

**For the Hindered-rotation Chain (HRC):** Now, both the bond angle $\theta$ is fixed, and the torsion angle $\phi$ rotation is restricted (it prefers certain angles like *trans* over others like *gauche*). This introduces further correlations. The effect of hindered rotation is captured by the average value of $\cos\phi$, denoted $\langle\cos\phi\rangle$. The final result multiplies the FRC result by another factor related to this average:
        
$$\langle h^2\rangle=nl^2\left(\frac{1+\cos\theta}{1-\cos\theta}\right)\left(\frac{1+\langle\cos\phi\rangle}{1-\langle\cos\phi\rangle}\right)$$

This shows how each constraint builds upon the previous model. The first factor accounts for the fixed bond angle, and the second factor accounts for the preferred torsion angles. If rotation were free, $\langle\cos\phi\rangle=0$, and we'd recover the FRC result. If certain angles are preferred, $\langle\cos\phi\rangle \neq 0$, modifying the size.

The average $\langle\cos\phi\rangle$ is calculated using statistical mechanics, weighting each possible angle $\phi$ by its Boltzmann factor $\exp[-U(\phi)/kT]$, where $U(\phi)$ is the potential energy associated with that torsion angle, $k$ is Boltzmann's constant, and $T$ is temperature. Angles with lower energy $U(\phi)$ have a higher probability.
       
$$\langle\cos\phi\rangle = \frac{\int_0^{2\pi}\cos\phi\exp[-U(\phi)/kT]\mathrm{d}\phi}{\int_0^{2\pi}\exp[-U(\phi)/kT]\mathrm{d}\phi}$$
        
*(This is a standard formula for calculating the average value of a quantity (here $\cos\phi$) over a distribution determined by energy levels and temperature. The integral in the numerator sums $\cos\phi$ weighted by its probability, and the integral in the denominator normalizes the total probability to 1).*

#### Radius of Gyration 

The end-to-end distance is useful but has limitations: it's hard to measure directly for a single chain, and it only considers the two ends, ignoring the path in between. For branched or ring polymers, it's not even clearly defined. The radius of gyration, $R_g$, provides a more general and experimentally relevant measure of a polymer coil's size.

**Radius of Gyration ($R_g$)** represents the root-mean-square distance of the chain's constituent parts (the monomers, here the $N=n+1$ C atoms) from the chain's center of mass ($\overrightarrow{r}_c$). It's analogous to the radius of gyration in mechanics, describing how mass is distributed around the center. If $\overrightarrow{r}_i$ is the position of monomer $i$ and $\overrightarrow{s}_i = \overrightarrow{r}_i - \overrightarrow{r}_c$ is its position relative to the center of mass, then for monomers of equal mass:
        
$$R_g = \langle s^2\rangle^{1/2} = \left(\frac{1}{N}\sum_{i=1}^N s_i^2\right)^{1/2} = \left(\frac{1}{n+1}\sum_{i=0}^{n} s_i^2\right)^{1/2}$$
        
*(This formula calculates the average squared distance ($s_i^2$) of each monomer from the center of mass, then takes the square root. We assume the atoms are indexed 0 to $n$, giving $n+1 = N$ atoms in total).*

The mean square radius of gyration, $\langle R_g^2 \rangle$, is the quantity usually calculated theoretically. It can be related to the average squared distances $\langle r_{ij}^2 \rangle$ between all possible pairs of monomers ($i$ and $j$) in the chain. (The derivation involves some algebraic manipulation, omitted here). The result is:
        
$$\langle R_g^2 \rangle = \frac{1}{2N^2}\sum_{i=1}^N\sum_{j=1}^N\langle r_{ij}^2 \rangle = \frac{1}{2(n+1)^2}\sum_{i=0}^{n}\sum_{j=0}^{n}\langle r_{ij}^2 \rangle$$

This formula emphasizes that $R_g$ depends on the average separation between *all* pairs of monomers, making it a measure of the overall spatial distribution, unlike $h$ which only involves the first and last monomer.

**Relationship to $\langle h^2\rangle$:** For long, linear polymer chains ($n \gg 1$), a very important and useful relationship exists between the mean square radius of gyration and the mean square end-to-end distance, regardless of the specific ideal chain model (FJC, FRC, HRC):

$$\langle R_g^2 \rangle \approx \frac{\langle h^2 \rangle}{6}$$

This simple geometric relationship holds for random coils. It means that these two different measures of size are directly proportional for long chains. Since $R_g$ is often easier to measure experimentally, this allows estimation of $\langle h^2 \rangle$. $R_g$ is experimentally accessible via techniques like static light scattering (SLS) and small-angle neutron scattering (SANS), making it a crucial link between theoretical models and real polymer systems.



#### Distributions of Chain Sizes

While average values like $\langle h^2\rangle^{1/2}$ and $R_g$ give us a typical size, they don't tell the whole story. The actual end-to-end distance $h$ and the positions of the monomers are constantly fluctuating. Probability distributions describe the likelihood of finding the chain with a particular size or shape.

**Distribution of End-to-End Vector:** For a long chain (large $n$) that behaves like a three-dimensional random walk (which is a good approximation for the FJC model, and often used as a starting point for others), the probability $P(n,\overrightarrow{h}) d^3h$ of finding the end-to-end vector $\overrightarrow{h}$ within a small volume element $d^3h$ around a specific vector value approaches a **Gaussian function**:
    
$$P(n,\overrightarrow{h}) \approx \left(\frac{3}{2\pi \langle h^2 \rangle}\right)^{3/2}\exp\left(-\frac{3h^2}{2\langle h^2 \rangle}\right)$$

Explanation of terms:
* The term $\left(\frac{3}{2\pi \langle h^2 \rangle}\right)^{3/2}$ is a normalization constant ensuring the total probability integrates to 1.
* $\exp\left(-\frac{3h^2}{2\langle h^2 \rangle}\right)$ is the core Gaussian shape. $h^2 = |\overrightarrow{h}|^2$ is the squared magnitude of the end-to-end vector.
* $\langle h^2 \rangle$ is the mean square end-to-end distance for the model (e.g., $nl^2$ for FJC). It sets the characteristic width of the distribution.
* The probability is highest when $h^2=0$, meaning the most probable end-to-end *vector* is the zero vector ($\overrightarrow{h}=0$).
* The probability decreases rapidly as the end-to-end distance $h$ increases, following the bell curve shape.
* This distribution arises from the central limit theorem applied to the sum of many (nearly) independent random bond vectors.

**Distribution of End-to-End Distance:** Often, we only care about the end-to-end *distance* $h$, not the specific direction of the vector $\overrightarrow{h}$. To find the probability $P(n,h) dh$ of the distance being between $h$ and $h+dh$, we need to consider all possible directions. This involves multiplying the vector probability $P(n,\overrightarrow{h})$ by the volume of a spherical shell of radius $h$ and thickness $dh$, which is $4\pi h^2 dh$.
    
$$P(n,h) = 4\pi h^2 P(n,\overrightarrow{h}) \approx 4\pi h^2\left(\frac{3}{2\pi \langle h^2 \rangle}\right)^{3/2}\exp\left(-\frac{3h^2}{2\langle h^2 \rangle}\right)$$
    
*(This is the radial distribution function. Although the most probable *vector* is zero, the $4\pi h^2$ factor means the probability of finding a zero *distance* is zero. This function starts at 0, rises to a peak at a non-zero value of $h$ (representing the most probable end-to-end distance), and then decays back to zero for large $h$.)*

**Distribution about the Center of Mass:** The distribution of monomers around the center of mass, which determines $R_g$, can also be described by a probability distribution. For long chains, this distribution is also often approximated by a Gaussian function, but deriving its exact analytical form is more complex than for the end-to-end distance.

### Scaling Laws: Relating Size to Chain Length

A key finding from the analysis of ideal chain models (FJC, FRC, HRC) is how the average size scales with the number of bonds, $n$ (which is proportional to the degree of polymerization or molar mass $M$). This relationship is often expressed as a **scaling law**.

* For all these ideal chain models, the mean square end-to-end distance is directly proportional to the number of bonds: $\langle h^2 \rangle \propto n$.
* This means the RMS end-to-end distance scales with the square root of the number of bonds:
    
$$\langle h^2\rangle^{1/2} \propto n^{0.5}$$
    
*(This exponent 0.5 is characteristic of random walks. It tells us that if you double the length of an ideal polymer chain (double $n$), its average size only increases by a factor of $\sqrt{2} \approx 1.414$, not by a factor of 2. The chain becomes larger, but relatively more compact as it gets longer).*
* Since $\langle R_g^2 \rangle \approx \langle h^2 \rangle / 6$ for long linear chains, the radius of gyration follows the same scaling relationship:
    
$$R_g \propto n^{0.5}$$
    
(or $R_g \propto M^{0.5}$, where $M$ is the molar mass, as $M \propto n$).

This $n^{0.5}$ scaling is a fundamental result for ideal polymer chains (and real chains under specific conditions called theta conditions, discussed later). It provides a baseline for understanding how chain size depends on chain length before considering more complex effects like self-avoidance or solvent interactions.

### Simulation

To visualize the polymer chains generated from different models and evaluate the end-to-end distance, the radius of gyration, and the distributions, use the following simulator:

> [OVESET -- Single chain conformation](https://colab.research.google.com/github/wangyu16/PolymerScienceEducation/blob/master/OVESET/07_Single_Chain_Conformation.ipynb)

## Self-avoiding chains{{attrs[#blk-9qxx12c8oi5o]}}

The ideal chain models discussed so far made a crucial simplification: they treated monomers as points with no volume and allowed the chain to cross itself. In reality, this is impossible. A real polymer chain occupies space, and no two monomers can be in the same place at the same time. This is known as the **excluded volume** effect. Taking this into account means the chain conformation is no longer a simple random walk but rather a **self-avoiding walk (SAW)**.

Mathematically, incorporating self-avoidance makes the problem much harder. Simple analytical expressions like those for $\langle h^2 \rangle$ or the Gaussian distribution are generally not available for SAWs. Computer simulations and advanced theoretical techniques (like renormalization group theory) are needed.

The main consequence of the excluded volume effect is that it forces the chain to swell and occupy a larger volume than an ideal chain of the same length would. The chain segments effectively repel each other to avoid overlapping. This leads to a different scaling law for the size:
$$R_g\sim N^{\nu} \quad \text{with} \quad \nu \approx 0.588$$
(often approximated as $\nu \approx 3/5$). This exponent is larger than the ideal chain exponent of $1/2$, indicating that the size of a real chain in a good solvent grows faster with chain length $N$ than an ideal chain does.

Another factor omitted in ideal models is the interaction energy between chain segments themselves, and between segments and solvent molecules (if the polymer is in solution). This part will be explained in more details in the next chapter.

* If segment-segment attractions are strong compared to segment-solvent interactions (a **poor solvent**), the chain prefers to interact with itself and tends to collapse into a more compact, dense globule to minimize contact with the solvent. In this case, the scaling exponent approaches $\nu = 1/3$, similar to how the radius of a sphere scales with its volume (or mass).
* If segment-solvent interactions are favorable (a **good solvent**), the solvent helps to push the segments apart, leading to the swollen coil described by the SAW model ($\nu \approx 3/5$).
* There exists a special condition called the **theta ($\theta$) condition** (specific solvent and temperature) where the segment-segment attraction exactly balances the excluded volume repulsion. Under these conditions, the chain behaves ideally, and the scaling exponent becomes $\nu = 1/2$, just like the ideal chain models predict. Polymer melts (polymers without solvent) also often exhibit ideal scaling ($\nu=1/2$) because the interactions between segments of one chain are screened by the presence of many other chains.

Using computer simulation, we can compare the ideal chains with self-avoiding chains and derive the scaling factor of self-avoiding chains under given conditions.

> [OVESET -- Self-avoid chains](https://colab.research.google.com/drive/1ED9QYOoa0fRQlHOnWTEdt7X-3INu5Bic?usp=sharing)

## Star and branched polymers{{attrs[#blk-2q32xn9u3ete]}}

Besides simple linear chains, polymers can have more complex architectures, such as **star polymers** (multiple linear arms joined at a central core) or **branched polymers** (having side chains attached to the main backbone). These architectures significantly affect the chain's overall size and shape compared to a linear chain of the same total mass. Deriving analytical expressions for their sizes is even more challenging than for linear chains. Again, computer simulations are a powerful tool to study the properties of these branched structures.

> [OVESET -- Star and branched polymers](https://colab.research.google.com/drive/1W7-I-zBetNG3Zaqym3i0QcMRoLz42AU-?usp=sharing)

The simulation linked above explores polymers made from two types of monomers: bifunctional (linking to two others, forming linear segments) and trifunctional (linking to three others, creating branch points). By controlling how these monomers react (e.g., using trifunctional first for a star core, or mixing them randomly for general branching), different architectures can be generated and their properties studied.



:::info
**Example Questions Level 1**

1. According to the freely hinged model, a linear polystyrene sample with an average degree of polymerization (DP) of 10,000 should have RMS end-to-end distance or RMS radius of gyration approximately how many times larger than a sample with an average DP of 100? Would the answer be the same or different if based on the freely rotating and hindered rotation models?
2. What does root-mean-square end-to-end distance represent for a polymer chain? What does radius of gyration represent? 
2. Which statement is true?  
	(a). The end-to-end distance of a freely rotating chain must be greater than that of a freely hinged chain if both chains have the same DP.  
	(b). The radius of gyration of a freely rotating chain must be greater than that of a freely hinged chain if both chains have the same DP.  
	\(c). If the DP increases by a factor of 3, the RMS end-to-end distance increases by a factor of 6.  
	(d). If the RMS end-to-end distance of freely rotating polymer chains with DP 50 is *c* times larger than that of freely hinged chains with the same DP, the RMS end-to-end distance of freely rotating polymer chains with DP 500 should also be *c* times larger than that of freely hinged chains with the same DP.  
3. What is the bond angle between three adjacent carbon atoms in a linear polyethylene molecule?
4. What are the differences among freely-hinged chain, freely-rotating chain, and hindered rotation chain models?
5. How does the excluded volume (self-avoidance) effect influence the scaling relationship of the RMS end-to-end distance and radius of gyration?
6. Regarding the bond length, bond angle, and torsion angle, what are required to have fixed values in a freely-hinged model, a freely-rotation model, and a hindered-rotation model. 
:::


{{markdown ./license.md}}
