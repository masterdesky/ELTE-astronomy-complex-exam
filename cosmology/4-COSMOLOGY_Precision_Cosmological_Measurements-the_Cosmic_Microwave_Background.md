# 4. Precision Cosmological Measurements: the Cosmic Microwave Background

## 4.1. The origin and properties of CMB
The Cosmic Microwave Background (CMB) is an extremely redshifted relic radiation from the Big Bang, which occurred approximately $13.8$ billion years ago. It is the oldest light in the universe that we can observe, and it provides us with a snapshot of the universe when it was only about $380\,000$ years old. At this time, the universe had cooled enough for protons and electrons to combine and form neutral hydrogen atoms, a process known as recombination. This allowed photons to travel freely through the universe without being scattered by charged particles, creating the CMB. The photons that traveled to us from the CMB have been redshifted by a factor of about $1090$[^1] due to the expansion of the universe.

The CMB has several key properties:
- **Uniformity and isotropy**: The CMB is remarkably uniform across the sky, with a nearly constant temperature of about $2.725 \operatorname{K}$. This uniformity is a reflection of the isotropy and homogeneity of the early universe. It also give rise to the horizon problem in cosmology, which is the problem of explaining how two regions of the universe that are separated by a large distance have the same temperature. This problem is solved by the theory of cosmic inflation, which is discussed in the next chapters.
- **Blackbody spectrum**: The CMB follows a perfect blackbody spectrum, which is a type of emission spectrum that is characteristic of an idealized object that absorbs all incident light and re-emits it with a specific distribution that only depends on the object's temperature. This was confirmed by the COBE (Cosmic Background Explorer) satellite, which found that the CMB's spectrum matches a blackbody spectrum at a temperature of $2.725 \operatorname{K}$, as it was mentioned above.
- **Anisotropies**: Despite the overall uniformity, the CMB contains tiny temperature fluctuations or so-called *anisotropies*. These anisotropies are on the order of $10^{-5} \operatorname{K}$ and are believed to be the seeds of all current structures in the universe, such as galaxies and clusters of galaxies.
- **Polarization**: The CMB is also polarized, which is a result of Thomson scattering in the early universe. This polarization provides additional information about the early universe and the formation of cosmic structures.

In the next sections, I will delve deeper into the anisotropies and the cosmological implications of the CMB.

## 4.2. CMB anisotropies
Anisotropies in the CMB are caused by either gravitational interaction or scattering of photons by electrons (eg. by Compton- or Inverse Compton scattering). They can be divided into two large categories: primary anisotropies and secondary anisotropies. Primary anisotropies are temperature fluctuations that were already present at the time of recombination, while secondary anisotropies are caused by the interaction of CMB photons with matter after recombination. The primary anisotropies are the most important ones, since they are the seeds of all current structures in the universe. The secondary anisotropies are also important, since they provide additional information about the early universe and the formation of cosmic structures.

The most powerful tool for studying the statistical properties of the CMB anisotropies is the power spectrum, which is discussed in the next section.

### 4.2.1. Power spectrum
The power spectrum of the CMB anisotropies provides a statistical description of the temperature fluctuations as a function of their scale on the sky. It is obtained by decomposing the CMB temperature map into spherical harmonics and calculating the average "power" or "strength" of each component. The temperature map is a function of the direction on the sky, which can be represented in spherical coordinates with the coordinate-pair $\vartheta$ and $\varphi$. The temperature map can be expanded in spherical harmonics as follows:

$$
    T(\vartheta, \varphi)
    =
    \sum_{\ell=0}^{\infty} \sum_{m=-\ell}^{\ell} a_{\ell m} Y_{\ell m}(\vartheta, \varphi)
$$

where $a_{\ell m}$ are the spherical harmonic coefficients, and $Y_{\ell m}$ are the spherical harmonics. The power spectrum is then defined as the average of the square of the absolute value of the coefficients $a_{\ell m}$:

$$
    C_{\ell}
    =
    \frac{1}{2\ell + 1} \sum_{m=-\ell}^{\ell} \left| a_{\ell m} \right|^2
$$

The power spectrum is typically represented as a graph, with the multipole moment (which is inversely related to the scale on the sky) on the x-axis and the power (which is related to the square of the amplitude of the temperature fluctuations) on the y-axis. The graph shows a series of peaks, which correspond to different scales of the primordial density fluctuations in the early universe.

Both the individual multipole moments and the peaks in the power spectrum could provide us valuable information about physical phenomena affecting the CMB.

### 4.2.2. Multipole moments
While the first monopole moment ($\ell = 0$) simply corresponds to the mean temperature of the CMB, the dipole moment ($\ell = 1$) is caused by the Doppler effect due to the motion of the Earth relative to the CMB rest frame. This causes the CMB to appear slightly hotter in the direction of motion and slightly colder in the opposite direction. Any higher multipole moments ($\ell \geq 2$) are considered to be the result by the primordial density fluctuations in the early universe.

However, we can observe several anomalies in the CMB multipole moments. The most notable one is the so-called "axis of evil", which is a large-scale alignment of the quadrupole and octupole moments ($\ell = 2$ and $\ell = 3$) with the ecliptic plane. This is highly problematic, since the ecliptic plane is a purely observational artifact, which should not have any physical significance. Another anomaly is the so-called "cold spot", which is a large-scale region of the sky in the Eriadnus constellation with a much lower temperature than the average.  This could be explained by the presence of a supervoid, which is a large region of space with a lower density than the average. However, it is still unclear whether this is the case.

### 4.2.3. Meaning of peaks in the power spectrum
The first peak in the power spectrum corresponds to the scale of the sound horizon at the time of recombination. This is the largest scale at which pressure waves (or "sound waves") could have traveled in the early universe before the photons decoupled from the baryons. The height of this peak provides information about the curvature of the universe (but not it's shape). In a flat universe, as predicted by the inflationary paradigm, this peak is expected to be the highest.

The subsequent peaks correspond to smaller scales and provide information about the relative amounts of ordinary matter (baryons), dark matter, and dark energy in the universe. The second peak is primarily sensitive to the amount of baryons, while the third peak is sensitive to the amount of dark matter. The exact positions and heights of these peaks provide a way to measure these cosmological parameters with high precision.

The power spectrum of the CMB anisotropies has been measured with great precision by experiments such as COBE, WMAP, and Planck. The results are in excellent agreement with the predictions of the standard model of cosmology, providing strong evidence for the Big Bang theory and the inflationary paradigm.

## 4.3. Cosmological analysis of the CMB power spectrum
The power spectrum of the CMB anisotropies is a treasure trove of cosmological information. By analyzing the power spectrum, we can infer key parameters of the $\Lambda$CDM model that assumes a flat universe dominated by a cosmological constant ($\Lambda$) and cold dark matter (CDM).

1. **Baryon density**: The relative heights of the first few peaks in the power spectrum are sensitive to the baryon density of the universe. Baryons contribute to the gravitational potential wells that the photons have to climb out of, and they also contribute to the pressure that opposes gravity. An increase in the baryon density increases the depth of the potential wells and the pressure, leading to a higher second peak and a lower third peak.
2. **Dark matter density**: The position of the peaks in the power spectrum is sensitive to the total matter density (baryons + dark matter) of the universe. More matter leads to a larger gravitational force, which makes the universe recombine later when it is smaller. This shifts the peaks to smaller scales (higher multipole moments).
3. **Hubble constant**: The Hubble constant, which measures the current rate of expansion of the universe, affects the distance to the surface of last scattering. A larger Hubble constant makes the universe recombine when it is smaller, which shifts the peaks to smaller scales.
4. **Cosmological constant (dark energy)**: The cosmological constant, or equivalently the dark energy density, affects the late-time evolution of the universe. A larger cosmological constant leads to an earlier onset of the accelerated expansion, which increases the distance to the surface of last scattering and shifts the peaks to larger scales.
5. **Scalar spectral index**: The scalar spectral index describes the initial power spectrum of the primordial density fluctuations. A scale-invariant spectrum (index = 1) is a prediction of the simplest inflationary models. Deviations from this value can provide evidence for more complex models of inflation.
6. **Reionization**: The process of reionization, which is believed to have occurred when the first stars formed and ionized the neutral hydrogen in the universe, leaves an imprint on the CMB in the form of a suppression of the power at small scales (high multipoles). This can be used to infer the optical depth to reionization.

By fitting the observed CMB power spectrum to theoretical models, we can obtain best-fit values and uncertainties for these parameters. The results from the Planck satellite, which has measured the CMB power spectrum with unprecedented precision, are in excellent agreement with the Lambda-CDM model and have provided the most precise measurements of these parameters to date.

## 4.4. Primordial gravitational waves
Primordial gravitational waves are ripples in the fabric of spacetime that were generated in the early universe. According to the theory of inflation, these gravitational waves were produced by quantum fluctuations that were stretched to macroscopic scales during the rapid expansion of the universe. These waves then left an imprint on the Cosmic Microwave Background (CMB) radiation.

There are two ways that primordial gravitational waves could leave an imprint on the CMB:

1. **CMB polarization**: Gravitational waves from the early universe would have created patterns of polarization in the CMB. These patterns can be divided into two types: E-modes and B-modes. E-modes can be produced both by density fluctuations (scalar perturbations) and by gravitational waves (tensor perturbations), while B-modes can only be produced by gravitational waves and lensing of E-modes by large-scale structure. Therefore, the detection of primordial B-modes is considered a "smoking gun" for inflation and would provide direct evidence of the quantum gravitational origin of cosmic structure.
2. **Effects on the temperature power spectrum**: Gravitational waves also contribute to the temperature fluctuations of the CMB, although this effect is much smaller than the effect on polarization. The contribution of gravitational waves to the temperature fluctuations is expected to be most significant on large scales (low multipoles), leading to a slight increase in power at these scales.

Despite extensive searches, primordial gravitational waves have not yet been detected. The BICEP2 experiment announced a detection of B-modes in 2014, but this was later shown to be due to dust in our own galaxy. Current and future experiments, such as the Simons Observatory and the CMB-S4 project, aim to achieve the sensitivity needed to detect or place stringent limits on the amplitude of primordial gravitational waves.

The detection of primordial gravitational waves would have profound implications for our understanding of the universe. It would provide strong evidence for inflation, allow us to probe the energy scale of inflation, and give us a glimpse of the universe at even earlier times than the CMB. It would also provide a form of evidence for quantum gravity, as the gravitational waves are thought to be produced by quantum fluctuations of the gravitational field.

[^1]: Planck Collaboration. (2020). Planck 2018 results-VI. Cosmological parameters. Astronomy & Astrophysics, 641, A6., arXiv:1807.06209.