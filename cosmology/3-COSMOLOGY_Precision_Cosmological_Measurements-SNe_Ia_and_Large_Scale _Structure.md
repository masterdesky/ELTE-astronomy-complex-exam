# 3. Precision Cosmological Measurements: SNe Ia and Large-scale structure

## 3.1. Application of SNe Ia in precision cosmology
Type Ia supernovae (SNe Ia) have been instrumental in precision cosmology due to their role as "standard candles". This term refers to their consistent intrinsic brightness, which allows us to calculate their distance from Earth.

The key principle is that the peak luminosity of SNe Ia is nearly uniform across all such events. This uniformity arises from the mechanism of their explosion: a white dwarf in a binary system accretes matter from its companion until it reaches a critical mass (the Chandrasekhar limit), leading to a thermonuclear explosion.

By comparing the observed brightness of SNe Ia with their known intrinsic brightness, we can determine their distance using the inverse square law of light. This is crucial for mapping the universe and understanding its expansion.

SNe Ia were pivotal in the discovery of the accelerating expansion of the universe, leading to the concept of dark energy. Observations of distant SNe Ia showed they were dimmer than expected, implying they were further away than predicted by a universe expanding at a constant rate.

The most important equation related to this topic is the distance modulus formula, which relates the apparent magnitude ($m$), absolute magnitude ($M$), and distance ($d$) in parsecs:

$$
    m - M = 5 \log(d) - 5
$$

This equation is used to calculate the distance to a supernova based on its observed and intrinsic brightness.

## 3.2. The origin of density fluctuations
Density fluctuations in the early universe are believed to be the seeds of the large-scale structures we observe today, such as galaxies and galaxy clusters. These fluctuations are thought to have originated from quantum fluctuations during the inflationary period of the universe.

Inflation theory posits that the universe underwent a rapid exponential expansion in the fractions of a second after the Big Bang. During this period, quantum fluctuations at the microscopic scale were stretched to cosmic scales, creating density variations in the otherwise homogeneous and isotropic early universe.

These density fluctuations are crucial because they break the perfect symmetry of the universe and provide the initial conditions for structure formation. Regions of higher density would have a stronger gravitational pull, attracting more matter and leading to the growth of structures over time.

The Cosmic Microwave Background (CMB) provides the earliest observable evidence for these density fluctuations. Tiny temperature variations in the CMB correspond to regions of slightly different densities in the early universe.

To describe the statistical properties of these fluctuations, we use the power spectrum $P(k)$ of the density field, which describes the amplitude of density fluctuations as a function of scale (given by the wavenumber $k$). The exact form of the power spectrum depends on the specifics of the inflationary model, but a common feature is a "scale-invariant" spectrum, where $P(k)$ is approximately constant over a wide range of scales.

## 3.3. Linear fluctuation growth
The growth of density fluctuations in the universe is a fundamental aspect of structure formation. In the early universe, these fluctuations were small, and their evolution can be described using eg. linear perturbation theory, also known as Zel'dovich approximation.

The Zel'dovich approximation is applicable when the so-called matter overdensity, defined as $\delta(\mathbf{x}) = (\varrho(\mathbf{x}) - \bar{\varrho})/\bar{\varrho}$, is much less than $1$. Here, $\varrho$ is the local density, and $\bar{\varrho}$ is the mean density of the universe. In this regime, the fluctuations grow proportionally with the scale factor of the universe, $a(t)$, in matter-dominated epochs.

The growth of these fluctuations can be described by the linear growth factor, $D(a)$, which represents the growth of density fluctuations relative to the scale factor of the universe. This factor is given by the following integral:

$$
    D(a)
    =
    \frac{5 \Omega_{m}}{2a} \frac{da}{d\tau}
    \int_{0}^{a} \left( \frac{da'}{d\tau} \right)^{-3} \mathrm{d}a'
$$

Here, $H(a)$ is the Hubble parameter, $H_0$ is the Hubble constant, and $\Omega_m(a)$ is the matter density parameter. In a matter-dominated universe with no cosmological constant, the growth factor is proportional to $a$, i.e., $D(a) \propto a$.

However, the presence of dark energy affects the growth of structures. In a universe with a cosmological constant, the growth of structures slows down at late times due to the accelerated expansion of the universe. If we assume a universe with densities $\Omega_{m}$ and $\Omega_{\Lambda}$, we can use the approximation formula for the growth factor[^1]:

$$
    D(\Omega_{m}, \Omega_{\Lambda})
    \approx
    \frac{5}{2} \Omega_{m}
    \left[
        \Omega_{m}^{4/7} - \Omega_{\Lambda}
        +
        (1 + \Omega_{m}/2) (1 + \Omega_{\Lambda}/70)
    \right]^{-1}    
$$

The first order approximation for the growth factor has its limitations. As structures grow and become more dense, non-linear effects become important, and the evolution of structures must be studied using numerical simulations or non-linear analytical methods.

## 3.4. Large-scale structure of the universe
The large-scale structure of the universe refers to the distribution of matter on scales larger than individual galaxies. This structure is characterized by a "cosmic web" of galaxy clusters and filaments, separated by vast voids.

The origin of this structure can be traced back to the small density fluctuations in the early universe. Regions of higher density attracted more matter due to their stronger gravitational pull, leading to the formation of structures. As time progressed, these structures grew and evolved, eventually forming the large-scale structure we observe today.

Two key concepts in the study of large-scale structure are the correlation function and the power spectrum. The correlation function, $\xi(r)$, measures the excess probability of finding a pair of galaxies separated by a distance $r$, compared to a random distribution. The power spectrum $P(k)$, is the Fourier transform of the correlation function and describes the distribution of matter on different scales.

The correlation function is defined as follows:
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

From this definition, we can relate the correlation function to the power spectrum using the Fourier transform:

$$
    \xi(r)
    =
    \frac{1}{(2\pi)^{3}}
    \int \mathrm{d}^{3}k P(k) e^{i \mathbf{k} (\mathbf{x} - \mathbf{x'})}
$$

Through the quantities discussed in this chapter, the large-scale structure of the universe provides important clues about the nature of dark matter and dark energy, the geometry of the universe, and the theory of gravity. Observations of the large-scale structure, such as galaxy surveys and measurements of the cosmic microwave background, are crucial for testing cosmological models and understanding the evolution of the universe.

Although the large-scale structure provides a wealth of information, interpreting this data is a complex task that requires a careful analysis and modeling. Factors such as galaxy bias, non-linear gravitational evolution, and redshift-space distortions can complicate the interpretation of large-scale structure observations. Numerical simulations are widely employed to study these effects and to make predictions for cosmological observables.


[^1]: Carroll, S. M. (2001). The cosmological constant. Living reviews in relativity, 4(1), 1-56.