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

## 3.3. Stellar atmospheres and spectra
The study of stellar atmospheres is crucial for understanding the properties of stars, as most of the information we receive from stars comes from their atmospheres. The atmosphere of a star is the outer layer from which electromagnetic radiation escapes to space. It is typically divided into several layers, including the photosphere, chromosphere, and corona.

### 3.3.1. Structure of the Sun's atmosphere
Using the Sun as an example, the stellar atmosphere is commonly divided into three main layers:

1. **Photosphere**: The photosphere is the visible surface of the Sun, the layer that we see when we look at a star. The photosphere emits the starlight we see. Its temperature is about $5\,500 \operatorname{K}$ on the Sun. This is the layer where the temperature begins to decrease with increasing distance from the star's center. The photosphere is also where sunspots occur, which are areas of lower temperature caused by magnetic activity.

2. **Chromosphere**: Above the photosphere is the chromosphere. While usually invisible due to the bright light from the photosphere, it can be seen during total solar eclipses as a thin, reddish rim. The temperature in the chromosphere increases with height, contrary to what happens in the photosphere. This increase in temperature is a phenomenon that is not yet fully understood but is thought to be related to magnetic field fluctuations and shock waves.

3. **Corona**: The corona is the outermost layer of a star's atmosphere, characterized by low densities and high temperatures, reaching millions of degrees Celsius in the case of the Sun. It is usually only visible during a total solar eclipse, when it appears as a halo around the eclipsed Sun. The heating mechanism of the corona is a subject of ongoing research, but it is thought to involve magnetic reconnection and wave heating.

The transition from the chromosphere to the corona is sharp, and this region is called the transition region. It is characterized by a rapid increase in temperature from about $20\,000 \operatorname{K}$ in the chromosphere to over a million degrees in the corona. The mechanisms driving this rapid temperature increase are still a topic of active research.

### 3.3.2. Stellar spectra
Stellar spectra provide a wealth of information about stars, including their temperature, chemical composition, and velocity relative to Earth. The spectrum of a star is the intensity of light as a function of wavelength, and it is usually characterized by a continuum with superimposed absorption lines, known as Fraunhofer lines.

These absorption lines are caused by the interaction of the star's light with the atoms in its atmosphere. Each element absorbs light at specific wavelengths, producing a unique pattern of lines in the spectrum. By studying these lines, astronomers can determine which elements are present in a star's atmosphere.

The shape of the stellar spectrum (the distribution of energy with wavelength) is primarily determined by the star's surface temperature and is well described by Planck's law of blackbody radiation:

$$
    B_{\lambda}(T)
    =
    \frac{2 h c^{2}}{\lambda^{5}}
    \frac{1}{e^{\frac{h c}{\lambda k_{B} T}} - 1} \, ,
$$

where $B_{\lambda}(T)$ is the spectral radiance, $h$ is Planck's constant, $c$ is the speed of light, $\lambda$ is the wavelength, $k_{B}$ is Boltzmann's constant, and $T$ is the absolute temperature.

The temperature of a star can be estimated by finding the peak of the blackbody curve, using Wien's displacement law:

$$
    \lambda_{\text{max}} T = b \, ,
$$

where $\lambda_{\text{max}}$ is the wavelength at which the blackbody curve peaks, $T$ is the absolute temperature, and $b$ is Wien'sdisplacement constant ($b \approx 2.898 \times 10^{-3}$ m K).

### 3.3.3. Energy transport: Radiation and Convection
The transfer of energy from the hot core to the cooler outer layers of a star occurs mainly through radiation and convection. The layers are separated by the temperature gradient, which determines the dominant mode of energy transport. Deep inside the star, where the temperature is high, the gas is ionized and opaque to radiation, so energy is only able to escape through convection. As the temperature decreases with increasing distance from the core, the gas becomes neutral and transparent to radiation and the mean free path of photons increases, allowing energy to be transported by radiation.

In the inner parts of a star, where temperatures are highest, energy is primarily transported by radiation. Photons, or light particles, carry energy away from the core through a series of absorptions and re-emissions by atoms in the star's interior. This process is described by the radiative transfer equation, which, in its simplest form, can be written as:

$$
    \frac{d I_{\nu}}{d s} = - \kappa_{\nu} I_{\nu} + j_{\nu} \, ,
$$

where $I_{\nu}$ is the specific intensity of the radiation, $\kappa_{\nu}$ is the absorption coefficient, $j_{\nu}$ is the emission coefficient, and $s$ is the distance along the path of the radiation. The absorption coefficient is given by

$$
    \kappa_{\nu} = \sigma_{\nu} \varrho \, ,
$$

where $\sigma_{\nu}$ is the absorption cross section and $\varrho$ is the density of the material. The emission coefficient is given by

$$
    j_{\nu} = \sigma_{\nu} \varrho B_{\nu} \, ,
$$

where $B_{\nu}$ is the Planck function. The equation of radiative transfer can be solved analytically for simple geometries and boundary conditions, but in general it requires numerical methods. The radiative transfer equation is a special case of the Boltzmann transport equation, which describes the transport of particles through a medium.

In the convective zone, the gas conducts heat and rises to the surface in convective currents, cools off at the surface, and sinks back down to pick up more heat, similar to the boiling of water in a pot. This process can be described by the Schwarzschild criterion for convection, which states that convection will occur if the actual temperature gradient in a star is steeper than the adiabatic temperature gradient. In the Sun, the convective zone extends from about $70\%$ of the solar radius to the photosphere.

Different stars have different zones depending on their mass and composition, affecting their temperature gradients and hence the dominant mode of energy transport. These differences contribute to the observed variety in stellar properties and spectral classifications.

## 3.4. Stellar models and Hertzsprung-Russell Diagram
The study of stars, their structures, and their life cycles is a fundamental aspect of astrophysics. Two key tools in this field are stellar models and the Hertzsprung-Russell (H-R) diagram. Stellar models provide theoretical frameworks that describe the properties and evolution of stars, while the H-R diagram offers a powerful graphical representation of the relationship between the stars' luminosities and their effective temperatures. Together, these tools allow us to understand the physical processes occurring within stars and predict their future evolution.

In this section, we will delve into the Hertzsprung-Russell diagram and stellar models, exploring their significance and how they contribute to our understanding of stellar phenomena.

### 3.4.1. Hertzsprung-Russell Diagram
The Hertzsprung-Russell (H-R) diagram is a pivotal tool in understanding stellar evolution. Named after the astronomers Ejnar Hertzsprung and Henry Norris Russell who independently discovered the relationship between the luminosity of a star and its temperature, the H-R diagram is a scatter graph where each star is represented as a dot.

On the vertical axis of an H-R diagram, we have the luminosity or the absolute magnitude of stars, which is a measure of their total energy output. On the horizontal axis, we have the temperature or spectral class. However, the temperature axis is typically displayed in reverse order with the hottest stars (O-type) on the left and the coolest stars (M-type) on the right.

On the H-R diagram, stars are distributed in distinct regions:
1. Most stars, including the Sun, lie within a region called the **Main Sequence** which runs diagonally across the diagram. These are stars in the stable phase of their life, where they are burning hydrogen into helium in their cores. The mass of a star determines its position along the main sequence, with more massive stars being hotter and more luminous.
2. Above and to the right of the main sequence are the **Giants** and **Supergiants**. These are highly luminous stars that have exhausted the hydrogen fuel in their cores and have expanded and cooled, moving off the main sequence. These stars are in a later stage of stellar evolution and are often characterized by a helium or heavier element core and a hydrogen-burning shell.
3. At the bottom left of the H-R diagram are the **White Dwarfs**. These are the remnants of low- and medium-mass stars that have shed their outer layers and left behind a hot core. They are very hot but low in luminosity due to their small size. White dwarfs represent the final stage of stellar evolution for most stars, including the Sun.

The H-R diagram is a powerful tool because it can be used to infer the age and evolutionary state of a star cluster, and it provides a testing ground for stellar models. By comparing the observed H-R diagram of a star cluster with the theoretical H-R diagram predicted by stellar models, astronomers can test and refine the models. It also allows us to classify stars and understand their evolution, providing a roadmap of a star's life cycle.

### 3.4.2. Stellar models
Stellar models are theoretical constructs that utilize physical laws to predict the properties of stars at various stages of their lives. They are based on a set of differential equations derived from principles such as conservation of mass, conservation of energy, and the state of hydrostatic equilibrium. These equations are coupled with equations of state, opacities, and nuclear reaction rates to form a complex system that is typically solved numerically.

Stellar models help us understand the structure and evolution of stars, predicting their internal profiles of temperature, pressure, density, and composition, as well as their observable properties such as luminosity, radius, surface temperature, and spectral lines. They also provide insight into the processes occurring within stars, such as nuclear fusion reactions and energy transport mechanisms.

The construction of a stellar model involves several steps:
- **Assumptions**: Certain assumptions are made to simplify the complex physics involved. These may include assuming that the star is spherically symmetric, in a state of hydrostatic equilibrium, and that energy transport occurs via radiation and convection.
- **Input physics**: The model incorporates various physical laws and parameters, such as the equations of state, opacities, nuclear reaction rates, and boundary conditions at the surface and center of the star. Unfortunately the exact physics behind some of these parameters is not well understood, such as the opacities and convection parameters, resulting in uncertainties in all stellar model predictions for a large variety of parameter ranges.
- **Solution of stellar structure equations**: The equations describing the stellar structure, derived from the principles of conservation of mass and energy and the state of hydrostatic equilibrium, are solved numerically. This yields the profiles of various quantities such as temperature, pressure, density, and composition as a function of radius within the star.
- **Comparison with observations**: The predictions of the model are compared with observations, such as the star's luminosity, radius, surface temperature, and spectral lines. Discrepancies between the model predictions and observations can lead to refinements in the model or reveal new physics.