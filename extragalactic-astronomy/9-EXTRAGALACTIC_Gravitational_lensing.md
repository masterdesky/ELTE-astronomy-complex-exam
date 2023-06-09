# 9. Gravitational lensing
Gravitational lensing is a phenomenon that was first predicted by Albert Einstein's theory of general relativity. According to GR, mass and energy can warp the fabric of spacetime, causing light to follow curved paths as it passes through this warped spacetime. This effect is known as gravitational lensing.

In the context of astronomy, gravitational lensing can be observed when a massive object (like a galaxy or a cluster of galaxies) lies between a distant light source and the observer. The gravitational field of the massive object bends the light from the source, causing it to take a curved path. This can result in multiple, distorted, or magnified images of the source.

Gravitational lensing is a powerful tool in astrophysics and cosmology. It can be used to study a wide range of phenomena, from the properties of galaxies and galaxy clusters, to the distribution of dark matter in the universe, to the expansion history of the universe itself.

## 9.1. Types of gravitational lensing
We usually distinc three main types of gravitational lensing: strong lensing, weak lensing, and microlensing. Altough they are all caused by the same physical phenomenon, they have different observational signatures and are used to study different things on different scales.

### 9.1.1. Strong Lensing
Strong lensing occurs when the gravitational field of the lensing object is so strong that it produces multiple images of the source. These images can be highly magnified and distorted, often appearing as arcs or rings around the lensing object. Notable examples of strong lensing geometries include Einstein rings and cross-shaped quasar images.

### 9.1.2. Weak Lensing
Weak lensing is a more subtle effect that occurs when the gravitational field of the lensing object is not strong enough to produce multiple images. Instead, it causes small distortions in the shapes of background galaxies. These distortions can be measured statistically to study the distribution of mass in the universe, including the elusive dark matter. Most of the gravitational lensing we observe in the universe in in the regime of weak lensing.

### 9.1.3. Microlensing
Microlensing is a special case of gravitational lensing that occurs when the lensing object is a compact mass, like a star or a planet. Unlike strong and weak lensing, microlensing does not produce multiple or distorted images. Instead, it causes a temporary increase in the brightness of the source. Microlensing events are unpredictable and short-lived, but they can be used to study objects that would otherwise be too faint or too small to observe directly.

## 9.2. Lensing geometries
Gravitational lensing is a geometric phenomenon, and as such, the relative positions of the source, the lens, and the observer play a crucial role in determining the observed effects.

When a beam of light passes close to a massive object, the gravitational field of the object bends the path of the light. This bending is characterized by the lensing angle, often denoted as $\tilde{\alpha}$. In the weak field limit, the lensing angle can be approximated by the formula:

$$
    \tilde{\alpha} \approx \frac{4GM}{c^{2} \xi} \, ,
$$

where $G$ is the gravitational constant, $M$ is the mass of the lensing object, $c$ is the speed of light, and $\xi$ is the distance of closest approach of the light ray to the center of the lensing object.

The Einstein radius $\theta_{E}$, emerges as a characteristic angular scale in gravitational lensing. It is defined as the radius of the ring image produced when the source, the lens, and the observer are perfectly aligned. The Einstein radius can be expressed in terms of the lens mass $M$, the distance to the lens $D_{L}$, the distance to the source $D_{S}$, and the distance from the lens to the source $D_{LS}$, as follows:

$$
    \theta_{E}
    =
    \sqrt{\frac{4GM}{c^{2}} \frac{D_{LS}}{D_{L}D_{S}}} \, .
$$

Connecting all mentioned physical concepts and quantities, we can derive the lens equation, a fundamental equation in gravitational lensing. It connects the angular position of the source $\beta$, the angular position of the image $\theta$, and the lensing angle $\tilde{\alpha}$. The lens equation is typically written as:

$$
    \beta
    =
    \theta - \frac{D_{LS}}{D_{S}}
    \cdot
    \tilde{\alpha}(D_{L}\theta) \, ,
$$

This equation can be solved to find the angular positions and magnifications of the lensed images. An Einstein ring is produced in the special case, where $\beta = 0$.

The geometry of gravitational lensing can lead to a variety of observable configurations. In the case of strong lensing, perfect alignment of the source, lens, and observer results in an Einstein ring, a circular image of the source. If the alignment is slightly off, multiple images of the source can be formed, often appearing as arcs or cross-shaped configurations around the lens. In weak lensing, the images are not multiply-imaged or highly distorted, but their shapes are slightly altered in a coherent way across the sky. In microlensing, the source appears to brighten and then fade, without any change in position or shape.

## 9.3. Weak lensing formalism
Weak gravitational lensing refers to the regime where the deflection angles and distortions of source images are small. In this regime, the lensing effects are subtle and can only be detected statistically by averaging over many galaxies. Fortunately, it produces a coherent signal across the sky, which can be measured by studying the shapes of background galaxies. For these aforementioned reasons, it is a powerful tool for studying the distribution of mass in the universe, including dark matter and large-scale structure.

### 9.3.1. Shear and convergence
The primary observable in weak lensing is the distortion of the shapes of background galaxies. This distortion is often described in terms of the shear, a measure of the stretching of the image along a particular direction. The shear is a complex quantity with two components, $\gamma_{1}$ and $\gamma_{2}$, which correspond to the stretching along two perpendicular axes. The magnitude of the shear $|\gamma|$ gives the amount of stretching, and the phase angle of $\gamma$ gives the direction of stretching. The distortion can be described with a $2 \times 2$ transformation matrix, known as the shear matrix, defined as

$$
    A_{ij}
    \equiv
    \frac{\partial \beta_{i}}{\partial \theta_{j}}
    =
    \begin{pmatrix}
        1 - \kappa - \gamma_{1} & -\gamma_{2} \\
        -\gamma_{2} & 1 - \kappa + \gamma_{1}
    \end{pmatrix} \, ,
$$

where $\kappa$ is the convergence and $\gamma_{1}$ and $\gamma_{2}$ are the two components of the shear:

$$
    \gamma_{1}
    =
    \frac{A_{11} - A_{12}}{2} 
    =
    \frac{1}{2}
    \left(
        \frac{\partial \beta_{1}}{\partial \theta_{1}}
        -
        \frac{\partial \beta_{2}}{\partial \theta_{2}}
    \right)
    =
    \frac{1}{2}
    \left(
        \frac{\partial^{2} \psi}{\partial \theta_{1}^{2}}
        -
        \frac{\partial^{2} \psi}{\partial \theta_{2}^{2}}
    \right) \, ,
$$

$$
    \gamma_{2}
    =
    - A_{12}
    =
    - \frac{\partial \beta_{1}}{\partial \theta_{2}}
    =
    - \frac{\partial \beta_{2}}{\partial \theta_{1}}
    =
    - \frac{\partial^{2} \psi}{\partial \theta_{1} \partial \theta_{2}} \, .
$$

where $\psi$ is the lensing potential.

The convergence $\kappa$ is a measure of the focusing of light rays by the lens. The convergence is related to the surface mass density of the lens $\Sigma$ and the critical surface mass density $\Sigma_{c}$ by the formula:

$$
    \kappa(\theta) = \frac{\Sigma(\theta)}{\Sigma_{E}}
$$

where $\Sigma_{E}$ is the critical surface mass density, defined as

$$
    \Sigma_{E}
    =
    \frac{c^{2}}{4 \pi G}
    \frac{D_{S}}{D_{L}D_{LS}} \, .
$$

The convergence $\kappa$ and the shear $\gamma$ are related by a complex equation known as the lensing equation, which involves the derivatives of the gravitational potential of the lens.

### 9.3.2. Lensing potential
The lensing potential is a crucial quantity in the weak lensing formalism. It is derived from the gravitational potential of the lensing mass distribution and plays a key role in determining the observed lensing effects.

The lensing potential, often denoted by $\psi$, is defined in terms of the two-dimensional projected gravitational potential of the lens. In a flat universe, the lensing potential at a position $\theta$ on the sky can be expressed as a line-of-sight integral over the gravitational potential $\phi$ along the line of sight:

$$
    \psi(\theta)
    =
    \frac{2 D_{LS}}{D_{L}D_{S} c^{2}}
    \int \phi(D_{L}\theta, z) dz \, ,
$$

The lensing potential is related to the convergence $\kappa$ through the relation

$$
    \kappa = \frac{1}{2} \nabla^{2}\psi \, ,
$$

where $\nabla^{2}$ is the two-dimensional Laplacian operator. The lensing potential is related to the shear $\gamma$ through the lens equation that can be now reformulated as

$$
    \theta - \beta = \alpha(\theta) = \nabla \psi(\theta) \, .
$$

These relations show that the lensing potential contains all the information about the lensing effects, including the distortion of the shapes of background galaxies (shear) and the focusing of light rays (convergence). By measuring the shear and convergence, one can reconstruct the lensing potential and hence the underlying mass distribution of the lens.

### 9.3.3. Power Spectrum
The statistical properties of the shear and convergence fields are often described by their power spectra. The power spectrum is a measure of the amplitude of fluctuations in these fields as a function of scale. The shear power spectrum and the convergence power spectrum contain valuable information about the distribution of mass in the universe and the cosmological parameters.

## 9.4. Applications
The weak lensing formalism provides a powerful tool for studying the universe. By measuring the distortions in the shapes of background galaxies, we can learn about the distribution of mass in the universe, test theories of gravity, and constrain cosmological parameters. Here are some of the key applications of weak lensing.

### 9.4.1. Mass Measurements
One of the primary applications of weak lensing is the measurement of mass. The shear and convergence fields are directly related to the projected mass distribution along the line of sight. By measuring these fields, we can reconstruct the mass distribution and estimate the total mass of the lensing object. This is particularly useful for studying dark matter, which does not emit light and can only be detected through its gravitational effects.

The mass $M$ of a lensing object can be estimated from the lensing potential $\psi$ using the relation:

$$
    M
    =
    \frac{c^{2}}{4G} \int \kappa(\theta) d^{2}\theta
    =
    \frac{c^{2}}{4G} \int \nabla^{2} \psi(\theta) d^{2}\theta \, ,
$$

where the integral is over the area of the sky covered by the lensing observations.

### 9.4.2. Studying Distant Galaxies and Cosmology
Weak lensing can also be used to study distant galaxies and the large-scale structure of the universe. The shear field provides a measure of the tidal gravitational field, which is related to the distribution of matter on large scales. By studying the statistical properties of the shear field, we can learn about the distribution of galaxies, the properties of dark matter, and the evolution of the universe.

The power spectrum $P(k)$ of the shear field is a particularly useful statistic. It is defined as the Fourier transform of the two-point correlation function of the shear:

$$
    P(k)
    =
    \int \langle \gamma(\theta) \gamma(\theta') \rangle
    e^{-i k \cdot (\theta - \theta')} d^{2}\theta' \, ,
$$

where the angle brackets denote an average over all pairs of points separated by a fixed angle. The power spectrum contains information about the amplitude and scale-dependence of the fluctuations in the shear field, which can be used to constrain cosmological parameters.

## 9.5. Observations
While weak lensing provides a powerful tool for studying the universe, it also presents several observational challenges. These challenges arise from the subtlety of the weak lensing signal, the complexity of the data analysis, and the need for high-quality astronomical observations.

### 9.5.1. Observational Challenges
The primary challenge in weak lensing observations is the subtlety of the signal. The distortions caused by weak lensing are typically much smaller than the intrinsic shapes of galaxies, making them difficult to measure. To overcome this challenge, weak lensing studies must average over many galaxies to detect the coherent signal.

Another challenge is the correction for observational effects, such as atmospheric blurring, telescope distortions, and detector imperfections. These effects can mimic or obscure the weak lensing signal, and must be carefully corrected using sophisticated image processing techniques.

A further challenge is the need for accurate measurements of the redshifts of the lensed galaxies. The lensing signal depends on the distances to the galaxies, which are determined from their redshifts. However, measuring redshifts is time-consuming and requires spectroscopic observations, which are not always available.

### 9.5.2. Lensing Surveys
Despite these challenges, several large astronomical surveys have been carried out to measure the weak lensing signal. These surveys use wide-field cameras on large telescopes to image hundreds of millions of galaxies, and sophisticated data analysis pipelines to measure the shapes of the galaxies and estimate their redshifts.

Examples of weak lensing surveys include the Kilo-Degree Survey (KiDS), the Dark Energy Survey (DES), and the Hyper Suprime-Cam Subaru Strategic Program (HSC-SSP). These surveys have provided unprecedented maps of the dark matter distribution in the universe and have placed tight constraints on cosmological parameters.

Future surveys, such as the Euclid mission by the European Space Agency and the Vera C. Rubin Observatory's Legacy Survey of Space and Time (LSST), will image billions of galaxies and provide even more precise measurements of the weak lensing signal.

In conclusion, despite the observational challenges, weak lensing is a powerful tool for studying the universe. With ongoing and future lensing surveys, we can look forward to many exciting discoveries in the years to come.