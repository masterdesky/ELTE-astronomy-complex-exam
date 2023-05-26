# 3. Stellar structure

## 3.1. Hydrostatic equilibrium and the virial theorem
### 3.1.1. Virial theorem
The virial theorem is a fundamental principle that establishes a relationship between the average kinetic energy and the potential energy of a system in equilibrium. It is a generalization of the theorem of kinetic energy for a particle moving in a conservative force field. For stable systems, the theorem states that the average kinetic energy is equal to half the average potential energy with an opposite sign. Mathematically:

$$
\langle T \rangle = -\frac{1}{2} \langle U \rangle \, ,
$$

where $\langle T \rangle$ is the average kinetic energy and $\langle U \rangle$ is the average potential energy. This applies to gravitational systems as well as to systems bound by an electric force or any other conservative force.

### 3.1.2. Hydrostatic equilibrium in stars
Stars are an example of a self-gravitating system where the virial theorem applies. The gravitational potential energy relates to the gravitational forces pulling inward, while the kinetic energy pertains to the thermal motion of particles, which is associated with pressure pushing outward.

When a star is in a state of hydrostatic equilibrium, these inward and outward forces balance each other. The pressure gradient, primarily generated from the thermal energy of nuclear fusion reactions in the star's core, counteracts the gravitational pull acting on the star's mass.

This equilibrium state for a relativistic, isotropic, spherically symmetric, self-gravitating object is described by the Tolman-Oppenheimer-Volkoff equation:

$$
\frac{dP}{dr}
=
-\frac{G}{r^{2}} \frac{M(r)}{c^{2}} \varrho (r)
\left( 1 + \frac{P}{\varrho (r) c^{2}} \right)
\left( 1 + \frac{4 \pi r^{3} P}{M(r) c^{2}} \right)
\left( 1 - \frac{2 G M(r)}{r c^{2}} \right)^{-1} \, .
$$

In the Newtonian limit, this equation reduces to the classical form of the hydrostatic equilibrium equation:

$$
\frac{dP}{dr} = -\frac{G M(r)}{r^{2}} \varrho(r) \, ,
$$

where $dP/dr$ is the pressure gradient, $G$ is the gravitational constant, $M(r)$ is the mass within a given radius $r$ and $\varrho$ is the density. This equation states that the change in pressure with respect to distance (i.e., the pressure gradient) is balanced by the gravitational force.

The condition of hydrostatic equilibrium is not static but dynamic, with the star continuously adjusting its internal structure in response to changes in energy production and loss, under the constraints set by the virial theorem.

## 3.2. Energy generation (nuclear fusion processes)
The energy source that powers stars and enables them to shine brightly for billions of years is nuclear fusion. This is a process where atomic nuclei combine, or "fuse," to form a heavier nucleus, and in the process release energy.

### 3.2.1. Proton-proton chain
The primary nuclear fusion process in stars like the Sun is the proton-proton chain. This process involves the combination of hydrogen nuclei (protons) to form helium, with several steps:

1. Two protons combine to form a deuterium nucleus (a proton and a neutron), a positron, and a neutrino:
    $$
    p^{+} + p^{+}
    \to
    d^{+} + e^{+} + \nu_{e}
    $$

2. The deuterium nucleus then combines with another proton to form a helium-3 nucleus:
    $$
    d^{+} + p^{+}
    \to
    \operatorname{He}^{3} + γ
    $$
3. Finally, two helium-3 nuclei combine to form helium-4, releasing two protons in the process:
    $$
    \operatorname{He}^{3} + \operatorname{He}^{3}
    \to
    \operatorname{He}^{4} + p^{+} + p^{+}
    $$
In this process, some mass is converted into energy, as described by Einstein's famous equation $E=mc^{2}$. The energy released in the form of gamma-ray photons ($\gamma$) eventually reaches the surface of the star and is emitted as light.

### 3.2.2. CNO cycle
The CNO (carbon-nitrogen-oxygen) cycle is a competing nuclear fusion process that is more efficient than the proton-proton chain at higher temperatures. In stars heavier than the Sun, it becomes the primary energy generation process. The CNO cycle involves protons combining with carbon, nitrogen, and oxygen nuclei to form helium. This process is a cycle rather than a chain, with the heavy nuclei acting as catalysts and being regenerated at the end of the cycle.

The basic CNO cycle involves these reactions:

1. $\operatorname{C}^{12}$ captures a proton to form $\operatorname{N}^{13}$:
    $$
    \operatorname{C}^{12} + p^{+} \to N-13
    $$

2. $\operatorname{N}^{13}$ undergoes beta decay to form $\operatorname{C}^{13}$:
    $$
    \operatorname{N}^{13} \to \operatorname{C}^{13} + e^{+} + \nu_{e}
    $$

3. $\operatorname{C}^{13}$ captures a proton to form $\operatorname{N}^{14}$:
    $$
    \operatorname{C}^{13} + p^{+} \to \operatorname{N}^{14}
    $$

4. Nitrogen-14 (N-14) captures a proton to form $\operatorname{C}^{15}$:
    $$
    \operatorname{N}^{14} + p^{+} \to \operatorname{C}^{15}
    $$

5. $\operatorname{C}^{15}$ undergoes beta decay to form $\operatorname{N}^{15}$:
    $$
    \operatorname{C}^{15} \to \operatorname{N}^{15} + e^{+} + \nu_{e}
    $$

6. $\operatorname{N}^{15}$ captures a proton and releases a helium-4 nucleus, regenerating the initial $\operatorname{C}^{12}$ nucleus:
    $$
    \operatorname{N}^{15} + p^{+} \to \operatorname{C}^{12} + \operatorname{He}^{4}
    $$

The net effect of the CNO cycle, like the p-p chain, is to convert hydrogen into helium, with a release of energy.

While the exact details and dominant process depend on the mass and temperature of the star, these nuclear fusion reactions are the key energy source that enables stars to shine over astronomically long timescales.

## 3.3. Stellar atmospheres and spectra
A star's spectra is a rich source of information about its physical and chemical properties. The light we see from a star has passed through its outer layers, and the interaction between this light and the star's atmosphere leaves distinctive signatures in the star's spectra.

### 3.3.1. Structure of the Sun's Atmosphere
Using the Sun as an example, the stellar atmosphere is commonly divided into three main layers:

1. **Photosphere**: The photosphere is the star's visible surface, the layer that we see when we look at a star. The photosphere emits the starlight we see, and its temperature is about 5,500 degrees Celsius on the Sun. This is the layer where the temperature begins to decrease with increasing distance from the star's center.

2. **Chromosphere**: Above the photosphere is the chromosphere. While usually invisible due to the bright light from the photosphere, it can be seen during total solar eclipses as a thin, reddish rim. The temperature in the chromosphere increases with height, contrary to what happens in the photosphere.

3. **Corona**: The corona is the outermost layer of a star's atmosphere, characterized by low densities and high temperatures, reaching millions of degrees Celsius in the case of the Sun. It is usually only visible during a total solar eclipse, when it appears as a halo around the eclipsed Sun. The heating mechanism of the corona is a subject of ongoing research.

### 3.3.2. Stellar Spectra
Each of these layers contributes to the formation of the star's spectra. The photosphere produces a continuous spectrum - a rainbow of colors - due to the thermal motion of its atoms. Superimposed on this are absorption lines (dark lines), called Fraunhofer lines, which are the result of atoms in the photosphere absorbing light at specific wavelengths.

The pattern of absorption lines is like a fingerprint for each star. It depends on the star's chemical composition, temperature, and pressure, and it allows astronomers to determine these properties. For instance, hydrogen lines are prominent in cooler stars, while lines from ionized atoms appear in hotter stars.

### 3.3.3. Energy Transport: Convection and Radiation
The transfer of energy from the hot core to the cooler outer layers of a star occurs mainly through radiation and convection. In the radiative zone, which is the layer below the photosphere in the Sun, energy is transferred via the absorption and re-emission of photons. However, as these photons move outward and the temperature decreases, convection becomes a more efficient mode of energy transport.

In the convective zone, the gas conducts heat and rises to the surface in convective currents, cools off at the surface, and sinks back down to pick up more heat, similar to the boiling of water in a pot. In the Sun, the convective zone extends from about 70% of the solar radius to the photosphere.

Different stars have different zones depending on their mass and composition, affecting their temperature gradients and hence the dominant mode of energy transport. These differences contribute to the observed variety in stellar properties and spectral classifications.

## 3.4. Stellar models and Hertzsprung-Russell diagram
The fundamental physical principles dictating stellar structure are embodied in stellar structure equations, a set of differential equations. These equations (mass conservation, hydrostatic equilibrium, energy conservation, and energy transport), combined with an equation of state and opacities, describe how the pressure, temperature, mass, and luminosity of a star change with radius, providing a complete description of the star's structure.

These principles and equations together form the foundation of our understanding of stars, their structures, their lifetimes, and their evolution.

### 3.4.1. Hertzsprung-Russell Diagram
The Hertzsprung-Russell diagram is a pivotal tool in understanding stellar evolution. It is a scatter graph of stars, where each star is represented as a dot. The diagram is named after the astronomers Ejnar Hertzsprung and Henry Norris Russell who independently discovered the relationship between the luminosity of a star and its temperature, forming the basis for the diagram.

On the vertical axis of an H-R diagram, we have the luminosity or the absolute magnitude of stars (which is a measure of their total energy output), and on the horizontal axis, we have the temperature or spectral class. However, the temperature axis is typically displayed in reverse order with the hottest stars (O-type) on the left and the coolest stars (M-type) on the right.

Most stars, including the Sun, lie within a region called the "main sequence," which runs diagonally across the diagram. These are stars in the stable phase of their life, where they are burning hydrogen into helium in their cores.

### 3.4.2. Stellar Models
Stellar models, developed through the solution of the equations of stellar structure, are crucial in interpreting the H-R diagram. The models provide the theoretical underpinning to understand the relationship between luminosity, temperature, and the life stages of stars reflected in the diagram.

Using these models, astronomers have been able to map out stellar evolutionary tracks - the path a star takes on the H-R diagram as it evolves. For example, after a star exhausts its core hydrogen fuel, it moves off the main sequence to become a red giant, which is reflected in a shift to the upper right of the H-R diagram.

These models also predict how a star's radius, surface temperature, and luminosity will change over time. By observing a star's position on the H-R diagram and comparing it to these models, we can infer properties such as the star's age, mass, and stage of evolution.