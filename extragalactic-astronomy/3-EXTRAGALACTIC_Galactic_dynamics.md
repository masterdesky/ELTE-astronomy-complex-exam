# 3. Galactic dynamics

## 3.1. Rotation curves and evidence for dark matter
Rotation curves are plots of the orbital speeds of visible stars or gas in a galaxy versus their radial distance from that galaxy's center. It is observed that the speed does not decrease with radius as would be the case if the visible matter were the only matter in the galaxy. Instead, the speed tends to remain constant or even increase with radius. This discrepancy is known as the galaxy rotation problem and is one of the strongest pieces of evidence for the existence of dark matter.

In the early 20th century, astronomers expected that the rotational velocities of stars in a galaxy would decrease with distance from the galactic center, similar to how the planets in our solar system slow down in their orbits the further they are from the Sun. This expectation was based on Kepler's laws of motion and the assumption that all the mass causing the gravitational attraction in a galaxy was visible.

However, in the 1970s, Vera Rubin and her colleagues discovered[^1] that the rotational velocities of stars in spiral galaxies remained constant or even increased with distance from the galactic center. This was unexpected and could not be explained by the visible matter alone. The gravitational pull from the visible matter was not enough to keep these fast-moving stars in the galaxy.

To resolve this discrepancy, astronomers postulated the existence of a new type of matter that does not emit light or interact with electromagnetic radiation, hence the name "dark matter". This dark matter forms a halo around galaxies, extending well beyond the visible matter. The additional gravitational pull from this dark matter halo explains the observed rotation curves. The distribution of this mysterious dark matter halo is thought to be spherical, with the galaxy at its center and its profile is described by the Navarro-Frenk-White (NFW) profile

$$
    \varrho(r)
    =
    \frac{
        \varrho_{0}
        }{
        \frac{r}{R_{s}} \left( 1 + \frac{r}{R_{s}} \right)^{2}
    } \, ,
$$

where the characteristic density $\varrho_{0}$ and the scale radius $R_{s}$ are determined by fitting the profile to the observed matter distribution.

The rotation curves of galaxies provide strong evidence for the existence of dark matter, but the exact nature of this dark matter remains one of the biggest unsolved mysteries in astrophysics. Various candidates have been proposed, including weakly interacting massive particles (WIMPs), axions, and modified theories of gravity. However, as of the time writing, no definitive detection of dark matter has been made.

## 3.2. Virial theorem and mass estimations
The virial theorem is a fundamental principle that establishes a relationship between the average kinetic energy and the potential energy of a system in equilibrium. It is a generalization of the theorem of kinetic energy for a particle moving in a conservative force field. For stable systems, the theorem states that the average kinetic energy is equal to half the average potential energy with an opposite sign. Mathematically:

$$
    \langle T \rangle = -\frac{1}{2} \langle U \rangle \, ,
$$

where $\langle T \rangle$ is the average kinetic energy and $\langle U \rangle$ is the average potential energy. This applies to gravitational systems as well as to systems bound by an electric force or any other conservative force.

In the context of galaxies, the virial theorem is a powerful tool for estimating the total mass of a galaxy or a cluster of galaxies. The theorem allows us to relate the kinetic energy of the stars or galaxies in the system (which we can measure) to the gravitational potential energy of the system (which depends on the total mass of the system).

For a galaxy, the kinetic energy of a star can be estimated from its velocity, which can be measured from its Doppler shift. The gravitational potential energy depends on the mass distribution within the galaxy, which is more difficult to measure directly. However, by assuming that the galaxy is in a state of virial equilibrium (i.e., the gravitational forces are balanced by the kinetic energy of the stars), we can use the virial theorem to estimate the total mass of the galaxy.

By measuring the velocities of many stars in a galaxy, we can estimate $\langle T \rangle$. Then, using the virial theorem, we can estimate $\langle U \rangle$. Since the gravitational potential is of the known formula

$$
    \nabla^{2} V
    =
    4\pi G \varrho \, ,
$$

and the potential energy is given by

$$
    U
    =
    -\frac{1}{2} \int \varrho V dV \, ,
$$

the total mass of the galaxy can be determined. This method often gives a higher mass than what is observed in visible matter, providing further evidence for the existence of dark matter.

It's important to note that the virial theorem assumes that the system is in equilibrium and that all the mass is acting as a single point mass at the center of the galaxy. These assumptions are not strictly true for real galaxies, so the mass estimates obtained from the virial theorem are approximations. However, they are often the best estimates we can make given the available data.

## 3.3. Dynamical friction and galaxy interactions
Dynamical friction, also known as gravitational drag, is a phenomenon in astrophysics usually referest to the phenomenon when a massive object moves through a field of less massive objects, such as a galaxy moving through a cluster of galaxies or a star moving through a galaxy. The fluctuating gravitational interactions between the massive object and the less massive objects cause the massive object to slow down and lose energy, an effect similar to the drag force experienced by an object moving through a fluid.

The concept of dynamical friction was first introduced by the astrophysicist Chandrasekhar in 1943[^2]. The basic idea is that as a massive object moves through a field of less massive objects, it attracts the less massive objects due to gravity. This creates an overdensity of less massive objects behind the massive object and an underdensity in front of it. The gravitational pull from the overdense region behind the massive object slows it down, causing it to lose kinetic energy and momentum. This is the essence of dynamical friction.

The equation for dynamical friction, known as Chandrasekhar's formula describes the force of dynamical friction. We usually assume a large body (eg. a galaxy) with mass $M$ moving through a medium with velocity $\mathbf{v_{M}}$ that consists of eg. stars of mass $m$. The special case is also employed, where the distribution function of the stellar velocity field is described by a Maxwellian distribution. The full Chandrasekhar's formula is then reduced to[^3]

$$
    M \frac{\mathrm{d}\mathbf{v_{M}}}{\mathrm{d}t}
    =
    \frac{-4\pi G^{2} M^{2} m \ln(\Lambda) \varrho(r)}{v_{M}^{3}}
    B(X) \mathbf{v_{M}} \, ,
$$

where

$$
    B(X)
    =
    \mathrm{erf}(X) - \frac{2}{\sqrt{\pi}} X e^{-X^{2}} \, .
$$

In these equations, $\varrho(r)$ is the density of the medium, $G$ is the gravitational constant, $\ln(\Lambda)$ is the Coulomb logarithm, and $X = v_{M}/\sqrt{2}\sigma$, where $\sigma$ is the velocity dispersion of the medium. The Coulomb logarithm is a dimensionless parameter that depends on the size of the system and the number of particles in it. It is usually taken to be $\ln(\Lambda) = 10$.

Dynamical friction plays a crucial role in galaxy interactions. When two galaxies pass close to each other, the gravitational interactions between the stars in the two galaxies can lead to energy and momentum exchange. Dynamical friction can cause the galaxies to slow down and possibly merge. This is thought to be a common process in the universe and is one of the main ways that galaxies grow and evolve.

Galaxy interactions can lead to a variety of phenomena, including tidal tails, bridges, and shells, as well as starburst activity and the formation of active galactic nuclei. The exact outcomes depend on the properties of the interacting galaxies, including their masses, sizes, gas content, and relative velocities, as well as the geometry of the interaction. Some of these interactions are discussed in [chapter 4](./4-EXTRAGALACTIC_Interacting_galaxies_AGN_and_quasars.md) of the extragalactic astronomy section.

In the case of a small galaxy interacting with a much larger galaxy, the small galaxy can be completely disrupted by the tidal forces from the large galaxy, a process known as tidal disruption. The stars from the small galaxy can then become part of the large galaxy, a process known as galactic cannibalism. This is thought to be a common way that large galaxies grow.

In the case of two large galaxies of comparable size interacting, the outcome can be a major merger, resulting in the formation of a single, larger galaxy. This can trigger a burst of star formation, as the gas in the galaxies is compressed and collapses to form new stars. Major mergers can also lead to the formation of elliptical galaxies and galaxy clusters.

## 3.4. Galactic orbits and resonances
In a galaxy, stars and gas clouds follow orbits determined by the gravitational potential of the galaxy. These orbits can be circular, elliptical, or even more complex shapes depending on the distribution of mass in the galaxy and the initial conditions of the star or gas cloud. However we usually just differentiate between two types: ordered and chaotic orbits. Ordered orbits are those that are regular and predictable using analytic methods, eg. using canonical perturbation theory. On the other hand, chaotic orbits can only be studied using various numerical methods.

The nature of stellar orbits within a galaxy is fundamentally determined by the gravitational potential of the host galaxy. This potential is intrinsically linked to the galaxy's type, which encompasses its structural properties and mass distribution. Moreover, the morphology of the galaxy, such as its overall shape, and kinematic properties, such as its rotational velocity, exert significant influence on the trajectories of stars. Therefore, a comprehensive understanding of stellar orbits necessitates a thorough examination of these galactic characteristics.

Elliptical galaxies, contingent upon their rotational characteristics and degree of symmetry, exhibit distinct classes of stellar orbits. Slowly rotating, asymmetric elliptical galaxies predominantly feature "box orbits", which are characterized by quasi-random, three-dimensional paths that fill a box-shaped region. Conversely, rapidly rotating, symmetric elliptical galaxies are characterized by "tube orbits", which are orbits that circulate around one of the axes and oscillate along the other two, thereby tracing out a tube-like shape in space. In the case of spiral galaxies, the gravitational potential engenders a more diverse mixture of orbit types, including both box and tube orbits, among others.

Additionally, the orbits of stars can be significantly influenced by resonances between their orbital frequencies and the pattern speeds of non-axisymmetric features in the galaxy, such as bars or spiral arms. For instance, in a barred galaxy, a resonance can occur between the orbital frequency of a star and the pattern speed of the bar. This resonance can trap the star into a specific type of orbit, shaping the overall structure of the galaxy and influencing the distribution of gas and star formation.

In spiral galaxies, similar resonances can occur between the orbital frequency of a star and the pattern speed of the spiral arms. These resonances, known as Lindblad resonances, can trap stars into specific types of orbits, leading to the formation of features such as spiral density waves and rings. At a Lindblad resonance, the frequency of a star's epicyclic motion, superimposed on its circular orbit due to perturbations in the gravitational potential, matches the pattern speed of the spiral arms. This can cause the star to be "caught" by the spiral arm, reinforcing the spiral structure and leading to the formation of spiral density waves.

## 3.5. Spiral structure and density waves
Spiral galaxies, such as our own Milky Way, are characterized by their prominent spiral arms. These arms are regions of higher density compared to their surroundings, and they are often sites of intense star formation. The exact mechanism behind the formation and maintenance of spiral arms has been a subject of debate among astronomers for many years.

One of the leading theories is the density wave theory, first proposed by C.C. Lin and Frank Shu in the 1960s. According to this theory, spiral arms are not material entities but rather areas of greater density, akin to traffic jams on a highway. Stars and gas clouds move in and out of these density waves as they orbit the galaxy, but the overall pattern of the spiral arms persists.

The density wave theory explains several observed features of spiral galaxies. For instance, it accounts for the fact that spiral arms are often sites of star formation. As a gas cloud enters a spiral arm, the increased gravitational attraction due to the higher density can cause the cloud to collapse and form new stars. These young, bright stars light up the spiral arm, making it visible.

The density wave theory also explains why spiral arms can be maintained over long periods of time. If spiral arms were simply material entities, they would wind up over time due to differential rotation (the fact that stars closer to the center of the galaxy orbit faster than stars further out). However, if spiral arms are density waves, they can persist as a standing wave pattern, even as individual stars and gas clouds move in and out of the arms.

Despite the success of the density wave theory, it does not explain all observed features of spiral galaxies, and other mechanisms may also play a role in the formation and maintenance of spiral arms. For example, gravitational interactions between galaxies can trigger the formation of spiral arms, and self-propagating star formation can maintain the spiral pattern. As of the time writing, the exact mechanisms behind the spiral structure formation remain an active area of research in astrophysics.

[^1]: Rubin, V. C., & Ford Jr, W. K. (1970). Rotation of the Andromeda nebula from a spectroscopic survey of emission regions. The Astrophysical Journal, 159, 379.
[^2]: Chandrasekhar, S. (1943). Dynamical friction. I. General considerations: the coefficient of dynamical friction. Astrophysical Journal, 97, 255-262.
[^3]: Silva, J. M., Lima, J. A. S. D., De Souza, R. E., Del Popolo, A., Le Delliou, M., & Lee, X. G. (2016). Chandrasekhar's dynamical friction and non-extensive statistics. Journal of Cosmology and Astroparticle Physics, 2016(05), 021.