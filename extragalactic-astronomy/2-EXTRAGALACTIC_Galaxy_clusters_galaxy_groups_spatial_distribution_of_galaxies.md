# 2. Galaxy clusters, galaxy groups, spatial distribution of galaxies

## 2.1. Galaxy groups
Galaxy groups are smaller collections of galaxies that are gravitationally bound together. They typically contain between a few to several dozens of galaxies, and are the most common systems of galaxies in the universe. The Local Group, which includes the Milky Way, Andromeda and at least $80$ other members (most of them being dwarf galaxies), is a prime example of a galaxy group.

Galaxy groups contain a significant amount of dark matter and hot gas, but in smaller quantities compared to galaxy clusters. The total mass of a galaxy group can range from a few times $10^{12}$ to $10^{13}$ solar masses in a diameter of $1$ to $2$ Mpc. The hot gas, or intragroup medium (IGM), is less dense and cooler than the intracluster medium (ICM) found in galaxy clusters, with temperatures typically around a few million degrees.

The dynamics of galaxy groups are governed by the gravitational interactions between the member galaxies. These interactions can lead to galaxy mergers, tidal stripping of stars and gas, and the heating of the IGM through shock waves. Over time, these processes can lead to the evolution of the group, with the potential for the formation of a single, massive elliptical galaxy.

The study of galaxy groups provides important insights into galaxy formation and evolution. It is in these environments that we can observe processes such as galaxy mergers, star formation, and the influence of the environment on galaxy properties. Galaxy groups also serve as the building blocks for larger structures like galaxy clusters.

## 2.2. Galaxy clusters
Galaxy clusters are the second-largest known gravitationally bound structures in the universe, typically containing hundreds to thousands of galaxies, along with hot gas and dark matter with a total mass of $10^{14}$ to $10^{15}$ solar masses in a diameter of $1$ to $5$ Mpc. They are often characterized by their X-ray emission, which comes from the hot intracluster medium (ICM). The ICM is a plasma that fills the space between the galaxies and is heated to temperatures of tens of millions of degrees by gravitational compression.

The total mass of a galaxy cluster can be estimated using several methods. One common method is through the application of the Virial Theorem, which relates the kinetic energy of the galaxies to the potential energy of the system:

$$
    \langle T \rangle = -\frac{1}{2} \langle U \rangle \, ,
$$

Assuming that the cluster is in dynamical equilibrium described by the Virial theorem, the total mass can be estimated from X-ray observations of the ICM, which can provide an estimate based on the temperature and density of the gas. Another method is through gravitational lensing, where the mass of the cluster can be inferred from the distortion of light from background galaxies. It is estimated that galactic clusters contain about $80\%$ dark matter, with the remainder consisting of stars, gas, and dust.

The distribution of galaxies within clusters is not uniform. The central region, known as the core, typically contains a high concentration of galaxies, with the density decreasing with distance from the center. This is often described by the Navarro-Frenk-White (NFW) profile:

$$
    \varrho(r)
    =
    \frac{
        \varrho_{0}
        }{
        \frac{r}{R_{s}} \left( 1 + \frac{r}{R_{s}} \right)^{2}
    } \, ,
$$

where the central density $\varrho_{0}$ and the scale radius $R_{s}$ are determined by fitting the profile to the observed galaxy distribution. This equation describes the universal density profile of dark matter halos in hierarchically clustering universes[^1].

An important concept in the study of galaxy clusters is the idea of the galaxy color–magnitude diagram (CMD). This encompasses the relationship between the color and absolute magnitude of celestial objects, in this case, galaxies. In the galaxy CMD, galaxies form thre distinct sequences known as the "red sequence", "green valley" and "blue cloud". Each of these sequences corresponds to a different type of galaxy, with the red sequence containing mostly older, elliptical galaxies, the blue cloud containing younger, star-forming spiral galaxies, and the green valley containing galaxies that are transitioning from the blue cloud to the red sequence. Our home, the Milky Way galaxy is assumed to be located in the green valley, as star formation seems to slowly be decreasing.

## 2.3. Large-scale structure of the universe
The large-scale structure (LSS) of the universe refers to the patterns of galaxies and galaxy clusters on scales of hundreds of millions of light-years. These structures are the result of the gravitational growth of small initial density fluctuations in the early universe, a process that was influenced by dark matter and dark energy.

The LSS contains several unique features that hierarchically assemble into larger structures in a fractal-like manner. On large scales it resembles a "web" that consists of trillions of galaxies and dark matter, with filaments that connect galaxy clusters and form the backbone of this web.

Based on N-body simulations and observations, the largest structures in the universe are filaments and walls that form the boundaries of large voides. Above this scale, no further structures exists and the universe is considered to be homogeneous.

The LSS is characterized by the following structures in hierarchical order:
- **Galaxies**, which are vast collections of stars, gas, dust, and dark matter. Galaxies are the building blocks of the universe's larger structures.
- **Galaxy clusters** are groups of galaxies held together by gravity. They are the largest gravitationally bound structures in the universe and contain hundreds to thousands of galaxies, along with large amounts of hot gas and dark matter.
- **Superclusters** are larger still, consisting of multiple galaxy clusters and groups connected by filaments of galaxies. The Milky Way is part of the Virgo Supercluster.
- **Filaments** are the largest known structures in the universe. They are vast, thread-like formations composed of galaxies and dark matter, forming the boundaries between large voids. The universe on large scales resembles a "cosmic web" of galaxies and dark matter, with filaments that connect galaxy clusters and form the backbone of this web.
- **Walls** or *sheets* are large, flat structures of galaxies that form the outer boundaries of voids and the "walls" of the cosmic web. These structures are a type of filament that are extended in two dimensions.
- **Voids** are regions of the universe with a lower density of galaxies. They are surrounded by filaments and walls and can be tens to hundreds of millions of light-years across. 

The formation and evolution of these structures are governed by the interplay of gravity, dark matter, and dark energy. Gravity pulls matter together, dark matter provides additional gravitational "scaffolding," and dark energy drives the accelerated expansion of the universe, which influences the growth of structure on the largest scales.

## 2.4. Galaxy correlation function and power spectrum
Two key concepts in the study of large-scale structure are the correlation function and the power spectrum. The correlation function, often denoted as $\xi(r)$ measures the excess probability of finding a pair of galaxies separated by a distance $r$, compared to a random distribution. The power spectrum $P(k)$, is the Fourier transform of the correlation function and describes the distribution of matter on different scales.

### 2.4.1. Galaxy correlation function
As it was mentioned, the galaxy correlation function measures the excess probability that a galaxy will be found at a certain distance $r$ from another galaxy. It is defined as follows:
$$
    \xi(r)
    =
    \langle \delta(\mathbf{x}) \delta(\mathbf{x'}) \rangle
    =
    \frac{1}{V} \int \mathrm{d}^{3}\mathbf{x} \delta(\mathbf{x}) \delta(\mathbf{x} + r)
$$

This equation measures the correlation between density fluctuations at two points separated by a distance $\mathbf{r} = \mathbf{x} - \mathbf{x'}$. Here, $\delta(\mathbf{x})$ is the matter overdensity at a point $\mathbf{x}$:

$$
    \delta(\mathbf{x})
    =
    \frac{\varrho(\mathbf{x}) - \bar{\varrho}}{\bar{\varrho}} \, .
$$

The correlation function is typically found to be a power law, $\xi(r) = (r/r_{0})^{-\gamma}$, on small scales ($r < 10 \operatorname{Mpc}$), where $r_{0}$ is the correlation length (the distance at which the correlation function is $1$) and $\gamma$ is the slope of the correlation function. This power law behavior indicates that galaxies are more likely to be found close to other galaxies, reflecting the clustered nature of galaxy distribution.

### 2.4.2. Power spectrum
The power spectrum $P(k)$ is another statistical measure of galaxy distribution, but in Fourier space. It measures the amplitude of density fluctuations as a function of their scale, given by the wavenumber $k$ (where $k = 2\pi/\lambda$, and $\lambda$ is the wavelength or scale of the fluctuation).

The power spectrum is related to the correlation function through a Fourier transform. It provides complementary information to the correlation function, being more sensitive to the distribution of galaxies on large scales and to the overall shape of the galaxy distribution:

$$
    \xi(r)
    =
    \frac{1}{(2\pi)^{3}}
    \int \mathrm{d}^{3}k P(k) e^{i \mathbf{k} (\mathbf{x} - \mathbf{x'})}
$$

The shape of the power spectrum is influenced by various cosmological parameters, including the total matter density, the baryon density, and the dark energy density. Because of this, the large-scale structure of the universe provides important clues about the nature of dark matter and dark energy, the geometry of the universe, and the theory of gravity. Observations of the large-scale structure, such as galaxy surveys and measurements of the cosmic microwave background, are crucial for testing cosmological models and understanding the evolution of the universe.


[^1]: Navarro, J. F., Frenk, C. S., & White, S. D. (1997). A universal density profile from hierarchical clustering. The Astrophysical Journal, 490(2), 493.