# 2. Radiative transfer and emission mechanisms
## 2.1. Radiative transfer
Radiative transfer is the physical process of energy transfer in the form of electromagnetic radiation. It describes the interactions of radiation with matter, and the transport of radiation through matter. The equation of radiative transfer is given by

$$
\frac{d I_{\nu}}{d s} = - \kappa_{\nu} I_{\nu} + j_{\nu} \, ,
$$

where $I_{\nu}$ is the specific intensity of the radiation, $\kappa_{\nu}$ is the absorption coefficient, $j_{\nu}$ is the emission coefficient, and $s$ is the distance along the path of the radiation. The absorption coefficient is given by

$$
\kappa_{\nu} = \sigma_{\nu} \rho \, ,
$$

where $\sigma_{\nu}$ is the absorption cross section and $\rho$ is the density of the material. The emission coefficient is given by

$$
j_{\nu} = \sigma_{\nu} \rho B_{\nu} \, ,
$$

where $B_{\nu}$ is the Planck function. The equation of radiative transfer can be solved analytically for simple geometries and boundary conditions, but in general it requires numerical methods. The radiative transfer equation is a special case of the Boltzmann transport equation, which describes the transport of particles through a medium.

### 2.1.1. Emission
Emission is the process by which matter emits energy in the form of radiation. This can occur through a variety of mechanisms:

- **Thermal Emission**: This is the emission of radiation due to the thermal energy of the emitting body. An example is blackbody radiation, where the radiation is emitted by a body in thermal equilibrium.
- **Line Emission**: This occurs when an atom or molecule transitions from a higher energy state to a lower energy state, emitting a photon in the process. The energy of the photon corresponds to the energy difference between the two states, leading to a line in the spectrum.
- **Synchrotron Emission**: This is the emission of radiation by charged particles (usually electrons) moving at relativistic speeds in a magnetic field.
- **Bremsstrahlung (Free-Free) Emission**: This is the radiation produced by the acceleration or deceleration of a charged particle in the electric field of another charged particle.

### 2.1.2. Absorption
Absorption is the process by which matter absorbs energy from radiation. This can occur through several mechanisms:

- **Photoionization**: This is the process by which an atom or molecule absorbs a photon and becomes ionized, with one or more electrons being ejected.
- **Bound-Bound Absorption**: This occurs when an atom or molecule absorbs a photon and transitions from a lower energy state to a higher energy state. The energy of the photon corresponds to the energy difference between the two states.
- **Bremsstrahlung (Free-Free) Absorption**: This is the absorption of a photon by a free electron in the electric field of an ion.

### 2.1.3. Scattering
Scattering is the process by which the direction of a photon is changed without absorption. This can occur through several mechanisms:

- **Rayleigh Scattering**: This is the scattering of photons by particles that are much smaller than the wavelength of the radiation. It is responsible for the blue color of the sky, as shorter (blue) wavelengths are scattered more than longer (red) wavelengths.
- **Compton Scattering**: This is the scattering of photons by free electrons, where the photon loses energy (and therefore increases in wavelength) and the electron gains kinetic energy.
- **Thomson Scattering**: This is the scattering of photons by free electrons. It is a low-energy limit of Compton scattering.
- **Inverse Compton Scattering**: This is a process where a low-energy photon gains energy by scattering off a high-energy charged particle, typically an electron.

## 2.2 Continuum radiations
### 2.2.1. Blackbody radiation
Blackbody radiation is a continuous spectrum of radiation emitted by an object in thermal equilibrium. It's characterized by the object's temperature, with the peak of the emission shifting to shorter wavelengths as temperature increases (Wien's Displacement Law) and the total energy emitted increasing with the fourth power of the temperature (Stefan-Boltzmann Law). The spectral radiance of the blackbody radiation is given by the Planck's law as

$$
B_{\nu} = \frac{2 h \nu^3}{c^2} \frac{1}{\exp \left( \frac{h \nu}{k_B T} \right) - 1} \, ,
$$

where $h$ is the Planck constant, $c$ is the speed of light, $k_B$ is the Boltzmann constant, $\nu$ is the frequency of the radiation, and $T$ is the temperature of the object. The total energy $j^{\ast}$, radiated per unit surface area of a black body across all wavelengths per unit time is given by the Stefan-Boltzmann law as

$$
j^{\ast} = \sigma T^4 \, ,
$$

where $\sigma$ is the Stefan-Boltzmann constant.

### 2.2.2. Synchrotron radiation
Synchrotron radiation is emitted when charged particles are accelerated radially, i.e., when they are subject to an acceleration perpendicular to their velocity. It is produced, for example, in synchrotrons using bending magnets, undulators and/or wigglers. In astrophysics, synchrotron radiation from high-energy electrons spiraling around magnetic field lines is a major source of radio emission in a variety of objects, including supernova remnants and active galactic nuclei. The instantaneous power radiated by a moving electron, valid in the relativistic case, is given by the Liénard formula

$$
P
=
\frac{2}{3}
\frac{e^2}{4 \pi \epsilon_0}
\frac{1}{c} \gamma^6
\left( \boldsymbol{\dot{\beta}} - \left( \boldsymbol{\beta} \wedge \boldsymbol{\dot{\beta}} \right) \right) \, ,
$$

where $e$ is the electron charge, $\epsilon_{0}$ is the vacuum permittivity, $c$ is the speed of light, $\gamma$ is the Lorentz factor, $\boldsymbol{\beta} = \boldsymbol{v}/c$ is the velocity of the electron in units of the speed of light, and $\boldsymbol{\dot{\beta}} = \boldsymbol{a}/c^2$ is the acceleration of the electron in units of the speed of light squared.

For a non-relativistic electron, the instantaneous power radiated is given by the Larmor formula as:

$$
P
=
\frac{2}{3}
\frac{e^2}{4 \pi \epsilon_0}
\frac{1}{c} \frac{\dot{v}^{2}}{c^{2}} \, ,
$$

where $r$ is the radius of curvature of the electron's trajectory.

### 2.2.3. Bremsstrahlung radiation
Bremsstrahlung radiation is produced by the acceleration or deceleration of a charged particle, usually an electron, in the electric field of another charged particle, such as an atomic nucleus. The radiation is continuous because the energy of the emitted photon can take on any value up to the kinetic energy of the particle. The radiated power can be given similarly to the synchrotron radiation.

Bremmstrahlung radiation is the dominant source of X-rays from the Sun and other stars. It is also the dominant source of gamma rays from the interstellar medium, where it is produced by cosmic ray electrons interacting with the interstellar gas.

### 2.2.4. Compton and Inverse Compton scattering
Compton scattering is the scattering of photons off of relativistic electrons. The energy of the scattered photon is given by the Compton formula as

$$
E_{\gamma}^{\prime}
=
\frac{E_{\gamma}}{1 + \frac{E_{\gamma}}{m_{e} c^{2}} \left( 1 - \cos \theta \right)} \, ,
$$

where $E_{\gamma}$ is the energy of the incident photon, $E_{\gamma}^{\prime}$ is the energy of the scattered photon, $m_{e}$ is the electron mass, $c$ is the speed of light, and $\theta$ is the scattering angle.

Inverse Compton scattering is an important process in astrophysics, where it is responsible for the production of high-energy photons, including gamma rays, X-rays, and extreme ultraviolet photons. It can be also observed in the Cosmic Microwave Background (CMB) radiation, where the CMB photons are scattered off of free electrons in the hot gas of galaxy clusters, causing the Sunyaev-Zel'dovich effect.

## 2.4. Spectral lines and their formation
Spectral lines are distinctive features in the electromagnetic spectrum of a light-emitting object. They are the result of transitions of electrons between different energy levels in atoms or molecules. The energy difference between the levels corresponds to the energy of the photon that is emitted or absorbed, which determines the wavelength of the spectral line.

The formation of spectral lines is a complex process that depends on the physical conditions in and outside of the emitting object. The spectral lines are broadened by several mechanisms, eg. thermal broadening. They are also shifted by the Doppler effect, which depends on the velocity of the emitting object relative to the observer. In case of celestial objects, other effects such as atmospheric and/or interstellar absorption and scattering, gravitational and cosmological redshifts, etc. must also be taken into account.

### 2.4.1. Line formation
By "atomic structure" we refer to the arrangement of electrons around the nucleus in an atom. Electrons occupy discrete energy levels, which are often visualized as shells or orbits around the nucleus. Each energy level can hold a certain number of electrons and is characterized by a specific energy.

When an electron absorbs a photon, it can jump from a lower energy level to a higher energy level. Conversely, when an electron emits a photon, it drops from a higher energy level to a lower energy level. The energy of the photon corresponds to the energy difference between the two levels. The energy levels are governed by selection rules, which determine which transitions are allowed and which are forbidden. This results in the emission or absorption of photons with only specific energies, which correspond to specific wavelengths. These wavelengths are characteristic of the atom and are called spectral lines.

### 2.4.2. Line profiles
Spectral lines observed in astrophysics are often not perfectly sharp. They can be broadened due to various physical processes, and they can be shifted from their rest wavelengths due to the motion of the emitting or absorbing material. Understanding these effects is crucial for interpreting the observed spectra of celestial objects.

#### Line Broadening
Line broadening refers to the widening of spectral lines beyond their natural linewidth. There are several mechanisms that can cause line broadening:

- **Natural Broadening**: This is caused by the uncertainty principle, which states that the energy of a state and the lifetime of the state cannot both be precisely known. This leads to a natural width of the spectral line, also known as the natural linewidth.
- **Thermal Doppler Broadening**: This is caused by the thermal motion of the atoms or molecules. Atoms moving towards or away from the observer will have their spectral lines Doppler shifted to shorter or longer wavelengths, respectively, which broadens the line.
- **Pressure Broadening**: This is caused by collisions between atoms or molecules, which disrupt the energy levels and broaden the spectral line.
- **Instrumental Broadening**: This is caused by the finite resolution of the instrument used to observe the spectral line.

Each of these broadening mechanisms has a characteristic shape, such as a Gaussian for thermal Doppler broadening or a Lorentzian for natural and pressure broadening. The observed line profile is often a convolution of these different shapes.

#### Line Shift
Line shift refers to the displacement of spectral lines from their rest wavelengths. There are two main types of line shift:

- **Doppler Shift**: This is caused by the motion of the emitting or absorbing material relative to the observer. If the material is moving towards the observer, the lines will be shifted to shorter wavelengths (blue shift). If the material is moving away from the observer, the lines will be shifted to longer wavelengths (red shift).
- **Gravitational Redshift**: This is caused by the effect of gravity on light. Light escaping from a massive object, such as a star or a black hole, will be shifted to longer wavelengths due to the gravitational field of the object.
