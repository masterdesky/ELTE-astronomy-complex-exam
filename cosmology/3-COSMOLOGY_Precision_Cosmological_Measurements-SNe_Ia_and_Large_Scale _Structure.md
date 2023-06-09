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
The growth of density fluctuations in the universe is a fundamental aspect of structure formation. In the early universe, these fluctuations were small, and their evolution can be described using eg. the Eulerian linear perturbation theory.

Fluctations causes the density field of the content of the universe to deviate from its mean value, $\bar{\varrho}(\tau)$. The quantity describing this deviation is the density contrast, $\delta(\mathbf{x}, \tau)$, which is defined as the fractional deviation from the mean density:

$$
    \delta(\mathbf{x}, \tau)
    =
    \frac{\varrho(\mathbf{x}, \tau) - \bar{\varrho}(\tau)}{\bar{\varrho}(\tau)} \, ,
$$

Here, $\varrho$ is the local density, and $\bar{\varrho}$ is the mean density of the universe. The coordinate $\mathbf{x}$ is the comoving coordinate, which is related to the physical coordinate $\mathbf{r}$ by $\mathbf{x} = \mathbf{r}/a(\tau)$, where $a(\tau)$ is the scale factor of the universe and $\tau$ is the conformal time.

In the linear approximatiion, we assume that the density contrast is small, i.e., $\delta \ll 1$. This allows us to linearize the problem and obtain the equations of motion of the density field for the linear regime as[^1]

$$
    \frac{\partial \delta(\mathbf{x}, \tau)}{\partial \tau}
    +
    \theta(\mathbf{x}, \tau)
    =
    0 \, ,
$$

$$
    \frac{\partial \mathbf{u}(\mathbf{x}, \tau)}{\partial \tau}
    +
    \mathcal{H}(\tau) \mathbf{u}(\mathbf{x}, \tau)
    =
    - \nabla \Phi(\mathbf{x}, \tau) \, ,
$$

where $\theta(\mathbf{x}, \tau)$ is the divergence of the peculiar velocity field $\mathbf{u}(\mathbf{x}, \tau)$, $\mathcal{H}(\tau) = \dot{a}/a$ is the conformal Hubble parameter, and $\Phi(\mathbf{x}, \tau)$ is the gravitational potential. The first equation is the continuity equation, and the second is the Euler equation.

The equations of motion of the density field combined with the equations for the velocity field results in a differential equation for the evolution of the density contrast. That equation combined with the Friedmann equation for the evolution of the scale factor of the universe, $a(\tau)$, describes the evolution of the density contrast in the linear regime as

$$
    \delta(\mathbf{x}, \tau)
    =
    D_{1}^{(+)} (\tau) A (\mathbf{x}) + D_{1}^{(-)} (\tau) B (\mathbf{x}) \, ,
$$

where $D_{1}^{(+)} (\tau)$ and $D_{1}^{(-)} (\tau)$ are the two solutions of the aforementioned system of differential equations, and $A (\mathbf{x})$ and $B (\mathbf{x})$ are the initial conditions for the density contrast and its time derivative.

Now depending on the density content of the mixture filling the universe, the growth factor $D_{1}^{\pm} (\tau)$ can be calculated in various ways. In the relevant era for the growth of structures in our universe, the universe was dominated by matter with a contribution from dark energy. In this case, the growth factor can be calculated as

$$
    D_{1}^{(+)}
    =
    H(a) \frac{5 \Omega_{m}}{2}
    \int_{0}^{a} \frac{\mathrm{d}a}{a^{3} H(a)} \, ,
$$

$$
    D_{1}^{(-)}
    =
    \frac{\mathcal{H}}{a} \, .
$$

Here, $H(a)$ is the Hubble parameter, and $\Omega_m(a)$ is the matter density parameter. In a universe with a cosmological constant $\Omega_{\Lambda}$, the growth of structures slows down at late times due to the accelerated expansion of the universe. The integral in the expression for $D_{1}^{(+)}$ unfortunately can not be evaluated analytically, but it can be approximated using the following formula[^2]:

$$
    D_{1}^{(+)}(\Omega_{m}, \Omega_{\Lambda})
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

This equation measures the correlation between density fluctuations at two points separated by a distance $\mathbf{r} = \mathbf{x} - \mathbf{x'}$. Here, $\delta(\mathbf{x})$ is the matter overdensity. From this definition, we can relate the correlation function to the power spectrum using the Fourier transform:

$$
    \xi(r)
    =
    \frac{1}{(2\pi)^{3}}
    \int \mathrm{d}^{3}k P(k) e^{i \mathbf{k} (\mathbf{x} - \mathbf{x'})}
$$

Through the quantities discussed in this chapter, the large-scale structure of the universe provides important clues about the nature of dark matter and dark energy, the geometry of the universe, and the theory of gravity. Observations of the large-scale structure, such as galaxy surveys and measurements of the cosmic microwave background, are crucial for testing cosmological models and understanding the evolution of the universe.

Although the large-scale structure provides a wealth of information, interpreting this data is a complex task that requires a careful analysis and modeling. Factors such as galaxy bias, non-linear gravitational evolution, and redshift-space distortions can complicate the interpretation of large-scale structure observations. Numerical simulations are widely employed to study these effects and to make predictions for cosmological observables.


[^1]: Bernardeau, F., Colombi, S., Gaztanaga, E., & Scoccimarro, R. (2002). Large-scale structure of the Universe and cosmological perturbation theory. Physics reports, 367(1-3), 1-248.
[^2]: Carroll, S. M. (2001). The cosmological constant. Living reviews in relativity, 4(1), 1-56.