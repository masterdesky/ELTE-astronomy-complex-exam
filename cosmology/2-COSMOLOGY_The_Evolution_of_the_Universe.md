# 2. The Evolution of the Universe

## 2.1. Single and multicomponent solutions of Friedmann equations
The Friedmann equations are the set of equations that describe the expansion of the universe in the context of general relativity. They are derived from Einstein's field equations and assume a homogeneous and isotropic universe, often described as the cosmological principle. They were explained in detail in the [previous chapter](1-COSMOLOGY_The_Big_Bang_Theory.md).

### 2.1.1. Single component solutions
In the simplest form, the Friedmann equations describe a universe filled with a single component of matter or energy. For instance, a universe filled with only matter (either baryonic or dark matter), or a universe filled with only radiation. Solutions utilizing this constraint are sometimes referred to as a "one-fluid" solutions too. This solution employs a perfect fluid model with the equation of state

$$
    p = w \varrho c^2 \, ,
$$

where $p$ is the pressure, $\varrho$ is the density, $c$ is the speed of light, and $w$ is the equation of state parameter. We can express the scale parameter $a(t)$ as a function of time $t$ as

$$
    a(t) = a_0 t^{\frac{2}{3 (w + 1)}} \, ,
$$

where $a_0$ is the scale factor at the present time.

The solutions of the Friedmann equations for a matter-dominated universe (where $w=0$) in this case indicate that the scale factor $a(t)$ evolves as $a \propto t^{2/3}$, meaning the universe expands but the rate of expansion decreases over time. For a universe filled with radiation ($w=1/3$), the scale factor evolves as $a \propto t^{1/2}$, indicating a universe that is also expanding but at a decelerating rate.

### 2.1.2. Multicomponent solutions
In a more realistic universe, there are multiple components, each with different equations of state. The Friedmann equations can be solved for such a multicomponent universe as well, though the solutions are more complex. This is important because in reality, our universe is filled with a mix of matter, radiation, and dark energy, each dominating at different stages of the universe's evolution.

For example, in the early universe, radiation dominated, and therefore the universe expanded according to the solution for a radiation-filled universe. As the universe cooled and expanded, matter became dominant, and the expansion followed the matter-dominated solution. Today, dark energy appears to be the dominant component, leading to an accelerating expansion of the universe.

Similarly to the single component solutions we can describe the non-iteracting fluids in our universe with the equation of state

$$
    \dot{\varrho_{i}}
    =
    -3 H \left( \varrho_{i} + w_{i} p_{i} \right) \, ,
$$

where $H$ is the Hubble parameter, $\varrho_{i}$ is the density, $w_{i}$ is the equation of state parameter, and $p_{i}$ is the pressure of the $i$-th component. We can get the following dependence for $\rho_{i}$ as

$$
    \varrho_{i} \propto a^{-3 (1 + w_{i})} \, .
$$

From these we can then construct arbitrary linear combinations of the components to get the total density of the universe. Based on our most recent knowledge about the universe, we can construct one such combination as seen in the previous chapter.

In our universe, the total energy density appears to be very close to the critical density (also discussed in the previous chapter), suggesting a flat universe that will continue to expand indefinitely, especially due to the influence of dark energy.

## 2.2. The LCDM cosmological model
The $\Lambda$CDM (Lambda-Cold Dark Matter) parameter model is currently the most accepted cosmological model that describes the evolution of the universe. It's characterized by a cosmological constant, represented by Lambda ($\Lambda$), and Cold Dark Matter (CDM). It is also consistent with an enormous number of observations of fundamental physical phenomena in cosmology, such as the CMB or the large-scale structure of the universe.

The simple $\Lambda$CDM model in its present form is based on the following key assumptions:
1. **Homogeneity and isotropy of the universe (the Cosmological Principle)**: The universe, on large scales, is the same everywhere (homogeneity) and the same in all directions (isotropy).
2. **Existence of the Cold Dark Matter**: This is matter that does not interact with electromagnetic radiation (i.e., light), but whose presence can be inferred from its gravitational effects on visible matter. In this model, it is assumed to be "cold," meaning it was non-relativistic at the time of matter-radiation equality.
3. **Existence of Dark Energy (Cosmological Constant $\Lambda$)**: This is a form of energy that permeates all of space and exerts a negative pressure, leading to an acceleration of the expansion of the universe. It is represented by the cosmological constant $\Lambda$ in Einstein's field equations.

Additionally, this list can be extended to include inflation, baryogenesis, and other phenomena. The Friedmann equations, when combined with these (and some additional) assumptions, lead to a model of a universe that began with a Big Bang, followed by an inflationary epoch, then radiation domination, matter domination, and now dark energy domination.

Being a so-called "parameter model," the $\Lambda$CDM model is characterized by a set of parameters that describe the universe. There are 6 "independet" parameters, which are:
1. Physical baryon density parameter $\Omega_b h^2$ *(with a current value of $0.02237 \pm 0.00015$)*.
2. Physical dark matter density parameter $\Omega_c h^2$ *(with a current value of $0.1200 \pm 0.0012$)*.
3. Age of the universe $t_0$ *(with a current value of $13.797 \pm 0.023$ billion years)*.
4. Scalar spectral index $n_s$ *(with a current value of $0.0544 \pm 0.0073$)*.
5. Curvature fluctuation amplitude $A_s$ *(with a current value of $2.100 \pm 0.030  \times 10^{-9}$)*.
6. Reionization optical depth $\tau$ *(with a current value of $0.0561 \pm 0.0071$)*.

These parameters can be determined from observations such as the cosmic microwave background (CMB) and large-scale structure surveys. Current observations suggest a flat universe ($\Omega_k = 0$), dominated by dark energy ($\Omega_{\Lambda} = 0.6847 \pm 0.0073$), with the remainder being dark matter ($\Omega_c = 0.260 \pm 0.011$) and baryonic matter ($\Omega_b = 0.0486 \pm 0.0005$).

Despite its success, the $\Lambda$CDM model also has several unresolved questions, issues and challenges, such as the nature of dark matter and dark energy, the cosmological constant problem, and the horizon and flatness problems, among others. However, as of 2023, it remains the most successful and widely accepted model we have for the evolution of the universe.

## 2.3. Characteristics of dark matter and dark energy
### 2.3.1. Dark matter
Dark matter is a form of matter that does not interact with electromagnetic radiation, hence "dark". It neither emits nor absorbs light or any other electromagnetic radiation at any significant level. Its existence is inferred from its gravitational effects on visible matter, on the large-scale structure of the universe, and on the anisotropies in the cosmic microwave background.

Key characteristics of dark matter include:
- **Non-Baryonic**: Dark matter is thought to be composed of particles that are not baryons (protons, neutrons, etc.). This conclusion comes from Big Bang nucleosynthesis and the density of baryonic matter predicted by the cosmic microwave background, both of which are in agreement and much smaller than the total matter density.
- **"Cold"**: Dark matter is assumed to be "cold", which means it was non-relativistic at the time of matter-radiation equality. This characteristic leads to specific predictions for the formation of large-scale structure.
- **Dissipationless**: Dark matter is thought to be dissipationless, meaning it does not lose energy through emission mechanisms.
- **Collisionless**: Dark matter is thought to be collisionless, meaning it does not interact with other particles through the electromagnetic force, only through gravity and maybe the weak force.
- **Gravitational Lensing**: Dark matter's presence is inferred from its gravitational effects, such as gravitational lensing, where the path of light is bent when passing through or near a massive object. Dark matter's distribution in galaxies and clusters of galaxies is often studied using gravitational lensing effects.
- **Galaxy Rotation Curves**: Observations of the rotation curves of galaxies provide strong evidence for dark matter. The observed flat rotation curves, where the orbital speed of stars and gas do not decrease with distance from the galactic center, imply the presence of a large amount of unseen matter.

### 2.3.2. Dark energy
Dark energy is a hypothetical form of energy that permeates all of space and tends to increase the rate of expansion of the universe. Its existence has been inferred from the observation of the accelerating expansion of the universe.

Key characteristics of dark energy include:
- **Uniformly Distributed**: Dark energy is thought to be homogeneously distributed in space, not clustering like matter does.
- **Negative Pressure**: Dark energy is characterized by a strong negative pressure. This negative pressure is what leads to the acceleration of the universe's expansion.
- **Dominant Component of the Universe**: Current observations suggest that about 70% of the energy density of the universe is in the form of dark energy.
- **Cosmological Constant $\Lambda$**: In the context of the $\Lambda$CDM model, dark energy is often associated with the cosmological constant in Einstein's field equations. However, other models of dark energy also exist, including quintessence and phantom energy models.
- **Equation of State**: The equation of state of dark energy is usually written in the form $p = w\varrho c^2$, where $p$ is the pressure, $\varrho$ is the energy density, $c$ is the speed of light, and $w$ is the equation of state parameter. For the cosmological constant as a constituent of the Unverse, $w = -1$.

The nature of dark energy remains one of the greatest mysteries in science. Understanding its properties and effects on the universe is a key goal in cosmology.

## 2.4. Observational pillars of the Big Bang theory
1. **Redshift of galaxies**: Observations show that galaxies are moving away from us, with those further away moving faster. This is known as Hubble's law, and it suggests that the universe is expanding. This idea is a cornerstone of the Big Bang theory.
2. **Cosmic Microwave Background Radiation**: The CMB is radiation that fills all space in the observable universe. It's considered a remnant from the hot, dense state of the early universe, and its discovery was a landmark piece of evidence for the Big Bang theory.
3. **Abundance of light elements**: The relative amounts of light elements (hydrogen, helium, and lithium) in the universe match predictions made by the Big Bang theory. According to this theory, these elements were created in the first few minutes after the Big Bang during a period known as "big bang nucleosynthesis".
4. **Large-Scale Structure of the universe**: The large-scale structure of the universe, including the distribution of galaxies and galaxy clusters, aligns with the expectations of the Big Bang model, which predicts that matter should clump together under the influence of gravity over time. Although on small scales (up to $200 \operatorname{Mpc}$) there are complex structures violating both homogeneity and isotropy, on larger scales the universe appears to satisfy the cosmological principle. (Although this arises another problem, referred to as the "horizon problem".)
5. **Time evolution of galaxy morphologies**: Observations show that galaxies evolved over time, with younger galaxies appearing different from older ones. This is consistent with an evolving universe as suggested by the Big Bang theory.
6. **Age of the oldest known objects**: The oldest known objects in the universe, including globular clusters and white dwarf stars, have ages that are consistent with the universe's estimated age of approximately 13.8 billion years, as predicted by the Big Bang theory.

## 2.5. The future of the universe
