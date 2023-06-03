# 1. Fundamentals of Relativistic Cosmology
The Einstein Field Equations (EFE) are a set of 10 non-linear partial differential equations that describe the gravitational interaction of matter in the presence of spacetime curvature. The field equations are derived from the Einstein-Hilbert action, which describes the dynamics of the gravitational field by means of the metric tensor $g_{\alpha\beta}$, which is a function of the coordinates $x^\mu$ of the manifold. The action is given by

$$
    S
    =
    \int \left[
        \frac{1}{2\kappa} R + \mathcal{L}_{M}
    \right]
    \sqrt{-g} \, \operatorname{d}^4x
$$

where $R$ is the Ricci curvature scalar, $\mathcal{L}_{M}$ is the action of the matter fields, and $\kappa = 8\pi G / c^{4}$. The Einstein Field Equations are obtained by varying the action with respect to the metric tensor, which yields

$$
    R_{\alpha\beta}
    -
    \frac{1}{2} R g_{\alpha\beta} \left( + \Lambda g_{\alpha\beta} \right)
    =
    \kappa T_{\alpha\beta}
    \equiv
    \frac{8\pi G}{c^4} T_{\alpha\beta} \, ,
$$

where $G_{\alpha\beta}$ is the Einstein tensor, $R_{\alpha\beta}$ is the Ricci tensor, and $T_{\alpha\beta}$ is the stress-energy tensor. The cosmological constant $\Lambda$ is a free parameter that was originally introduced by Einstein to allow for a static universe. However, the discovery of the expansion of the universe by Hubble in 1929 rendered it unnecessary. The cosmological constant was later revived by the discovery of the accelerated expansion of the universe in 1998, which was attributed to a non-zero cosmological constant.

The stress-energy tensor appearing in the EFE is given by definition as

$$
    T_{\alpha\beta}
    :=
    \frac{-2}{\sqrt{-g}} \frac{\delta (\sqrt{-g} \mathcal{L}_{M})}{\delta g^{\alpha\beta}}
    =
    -2 \frac{\delta \mathcal{L}_{M}}{\delta g^{\alpha\beta}}
    +
    g_{\alpha\beta} \mathcal{L}_{M} \, .
$$

Solutions to the EFE provide the mathematical descriptions of physical spacetime configurations, or the so-called *metrics* of spacetimes. These "solutions" are in fact models of the universe (or a part of it) that satisfy the equations under certain assumptions.

At a basic level, a solution to the EFE is a metric tensor, $g_{\alpha\beta}$, which defines a spacetime geometry that fulfills the field equations given a particular distribution of matter and energy, represented by the stress-energy tensor $T_{\alpha\beta}$. In other words, these solutions describe the curvature of spacetime as a consequence of the distribution of matter and energy within it, in accordance with the principles of General Relativity.

The complexity and nonlinearity of the EFE often necessitate simplifying assumptions to make the equations tractable. These assumptions, though simplifications, should still reflect the physical reality we observe. For instance, the cosmological principle, which posits that the universe is homogeneous and isotropic on large scales, provides a fundamental basis for many cosmological models.

In the context of cosmology, some of the most important solutions to the EFE are the Friedmann-Lemaître-Robertson-Walker (FLRW) metric. This solution represents an expanding (or contracting) universe and serve as the basis for the *standard model* of Big Bang cosmology. It encapsulates the large-scale dynamics of our universe, from its hot, dense beginnings to its current accelerated expansion.

## 1.1. The cosmological and Copernican principles
The cosmological and Copernican principles are two foundational assumptions in modern cosmology that greatly shape our understanding of the universe's structure and evolution.

The **Cosmological Principle** states that the universe, on large scales, is homogeneous and isotropic. Homogeneity implies that the universe is uniform throughout: it has the same properties and structure at every point in space. Isotropy, on the other hand, means that the universe appears the same in all directions, regardless of our observation point. However, we should keep in mind that these are approximations; on smaller scales (such as within galaxy clusters), the universe is neither perfectly homogeneous nor isotropic. There are both theoretical models and observations that challenge the assumption of large-scale isotropy, such as the AvERA cosmological model or the Cold Spot in the cosmic microwave background (CMB).

The **Copernican Principle** is a philosophical statement about our place in the universe. It posits that we are not in a special or central location; our vantage point is not privileged in any way. This principle is an extension of the cosmological principle and serves as a philosophical underpinning for it. The Copernican Principle is named after the astronomer Nicolaus Copernicus, who argued for a heliocentric model of the solar system, displacing Earth from the center of the universe.

Together, these principles lay the groundwork for the Friedmann-Lemaître-Robertson-Walker (FLRW) metric, which we will explore in the next section. The FLRW metric, which assumes a homogeneous and isotropic universe, forms the backbone of the standard model of Big Bang cosmology.

## 1.2. FLRW metric
The Friedmann-Lemaître-Robertson-Walker (FLRW) metric is one of the most important results in cosmology. It describes the spacetime geometry of a homogeneous and isotropic universe, and serves as the basis for the standard model of Big Bang cosmology. Contrary to everything said in the introduction of this section, the FLRW metric is not a direct solution to the EFE. Rather it was derived simply from the geometrical properties of homogeneity and isotropy. The FLRW metric is given by

$$
    \operatorname{d}s^2
    =
    -c^2 \operatorname{d}t^2 + a^2(t) \operatorname{d} \mathbf{\Sigma}^2 \, .
$$

Here $\operatorname{d} \mathbf{\Sigma}^2$ is the line element of a 3-dimensional space of constant curvature. The function $a(t)$ is the scale factor, which describes the expansion of the universe as a function of cosmic time $t$. Regardless of the coordinate system used to describe the line element $\operatorname{d} \mathbf{\Sigma}^2$, the curvature of the $3$-space may be encapsulated by the curvature parameter $k$, with $k=+1$ representing positive curvature (spherical geometry), $k=0$ representing zero curvature (flat geometry), and $k=-1$ representing negative curvature (hyperbolic geometry).

The goal of the FLRW metric is to underpin the Big Bang model of cosmology, providing a mathematical description of a universe that expands from a hot, dense state (the Big Bang singularity), and continues to expand over time. Additionally, the scale factor $a(t)$, and its rate of change, encapsulate the dynamics of this expansion.

However, it's worth noting that while the FLRW metric has been used as the basis for the Big Bang cosmology, it's based on an idealization. In reality, the universe exhibits structure on all scales, from galaxies to galaxy clusters and superclusters that cannot be explained by the FLRW metric that assumes a homogeneous and isotropic universe. This is why the FLRW metric is often used as a starting point for more complex models that incorporate inhomogeneities and anisotropies. 

## 1.3. Friedmann equations
While it was already stated that the FLRW metric is not a direct solution to the EFE, they are needed to derive the Friedmann equations, a set of two independent equations that describe the time evolution of the scale factor $a(t)$.

The first Friedmann equation is essentially an energy conservation equation, accounting for the total energy of a comoving volume of the universe:

$$
    \dot{\varrho}
    =
    -3 \frac{\dot{a}}{a} \left( \varrho + \frac{p}{c^2} \right)
$$

Here, $\dot{a}$ denotes the derivative of the scale factor with respect to time, $G$ is the gravitational constant, $\varrho$ is the energy density of the universe, $k$ is the spatial curvature constant as defined in the FLRW metric, and $\Lambda$ is the cosmological constant.

The second Friedmann equation describes the acceleration of the universe, it is:

$$
    \frac{\ddot{a}}{a}
    =
    -\frac{4\pi G}{3} \left( \varrho + \frac{3p}{c^2} \right)
    +
    \frac{\Lambda c^2}{3}
    \, .
$$

Here, $\ddot{a}$ denotes the second derivative of the scale factor with respect to time, and $p$ is the pressure of the matter-energy content of the universe. It states that the acceleration can be affected by the total energy density of the universe, as well as the pressure of the matter-energy content of the universe, effectively decelerating the expansion process.

Reformulating and simplyfying the Friedmann equations we can arrive on an easier-to-use form:

$$
    H^2
    =
    \left( \frac{\dot{a}}{a} \right)^2
    =
    \frac{8\pi G}{3} \varrho
    -
    \frac{kc^2}{a^2} \, ,
$$

$$
    \dot{H} + H^2
    =
    \frac{\ddot{a}}{a}
    =
    -\frac{4\pi G}{3} \left( \varrho + \frac{3p}{c^2} \right) \, .
$$

The equations above incorporate the three main "constituents" of the universe: matter (characterized by its energy density $\rho$), curvature (characterized by $k$), and dark energy or the cosmological constant ($\Lambda$). By solving these equations, we can describe the evolution of the universe as a function of its matter and energy content.

We can define a specific density parameter $\Omega$ for each of these constituents, which is the ratio of the actual density of the constituent to the critical density $\varrho_c$:

$$
    \Omega
    =
    \frac{\varrho}{\varrho_c}
    =
    \frac{8\pi G \varrho}{3 H^2} \, ,
    \quad\quad
    \Omega_{i}
    =
    \frac{\varrho_{i}(t)}{\varrho_{c}(t)}
$$

We can then define a density $\Omega_{i}$ for each of the constituents themeselves:

$$
    \Omega
    =
    \Omega_R + \Omega_M + \Omega_k + \Omega_\Lambda
    \left( + \Omega_{\text{others}} \right) \, .
$$

Here, $\Omega_R$ is the density parameter for radiation, $\Omega_M$ is the density parameter for matter (dark matter and baryonic matter), $\Omega_k$ is the density parameter for curvature, and $\Omega_\Lambda$ is the density parameter for dark energy. $\Omega_{\text{others}}$ is a placeholder for other constituents that may be present in the universe, not known to science at the time of writing.

Using these densities, the first Friedmann equation can then be rewritten for any epoch of the universe in context of the present epoch (where $a=1$ and $H=H_{0}$) and where the density parameters are fixed at their present values:

$$
    \frac{H^{2}}{H_{0}^{2}}
    =
    \Omega_{0,R} a^{-4} + \Omega_{0,M} a^{-3}
    +
    \Omega_{0,k} a^{-2} + \Omega_{0,\Lambda} \, .
$$

Here eg. $\Omega_{0,R}$ is the density parameter for radiation at the present epoch, $\Omega_{0,M}$ is the density parameter for matter at the present epoch, and so on.

Similarly to the remarks made about the FLRW metric, the Friedmann equations are best applicable on large scales where the assumptions of the cosmological principle hold. For smaller scales or in cases where more detail is needed, more complex models and equations may be needed.

## 1.4. Conservation of energy in an expanding universe
In closed systems, the total amount of energy - whether in the form of kinetic energy, potential energy, or internal energy - is always conserved. However, in the context of an expanding universe, the traditional concept of energy conservation is much more complex.

In a static universe, the conservation of energy holds without much controversy as one can apply Noether's first theorem by taking advantage of time symmetry. This symmetry leads to the conservation of energy: the total energy of the system at one point in time is the same at any other point in time.

However, in an expanding and dynamic universe, governed by general relativity, the situation is less straightforward. The energy conservation principle encounters complexities when extended from flat spacetime, the setting for special relativity, to curved spacetimes, the arena for general relativity. The principle, as a differential equation, extends smoothly, stating that no energy is created in any infinitesimal piece of spacetime. However, the same doesn't hold when considering non-infinitesimal pieces of spacetime. Curvature in spacetime, which is perceived as gravity, complicates the concept of energy conservation. Incorporating gravitational potential energy and possibly energy carried by gravitational waves becomes necessary to achieve a comprehensive understanding of energy conservation in non-infinitesimal pieces of spacetime​.[^1]

While the local conservation of energy still holds in general relativity as expressed through the covariant divergence of the stress-energy tensor equaling zero:

$$
    \nabla_{\mathrm{cov}} T
    =
    \sum_{\mu} \nabla_\mu T^{\mu \nu} = 0 \, ,
$$

a global conservation law is much more elusive. At the end of the day, when we talk about "conservation of energy" in the context of cosmology and general relativity, we talk about energy conservation in a local sense, where it is still valid.

Moreover, in an expanding universe, one has to take into account the redshift of photons. As the universe expands, the energy of a photon decreases as its wavelength gets stretched. This energy seemingly "disappears". Some propose that this radiant energy transforms into gravitational energy, while others suggest the energy is simply lost. Regardless, these phenomena aren't considered as "exceptions" to the law of energy conservation, but rather a reflection of the fact that the notion of "total energy" is more subtle in the context of general relativity and an expanding universe.

## 1.5. Hubble-Lemaître law and peculiar velocities
The Hubble-Lemaître Law, named after astronomers Edwin Hubble and Georges Lemaître, is a key principle in modern cosmology. It states that the universe is expanding uniformly, with galaxies moving away from each other at a speed proportional to their distance. This can be expressed as:

$$
    v = H_{0} d
$$

where $v$ is the velocity of the galaxy, $H_{0}$ is the Hubble constant, and $d$ is the distance to the galaxy.

Galactic dynamics are not so simple though: the velocities of galaxies are not solely determined by the expansion of the universe. Galaxies also exhibit what are known as "peculiar velocities" – motions that deviate from the uniform expansion predicted by the Hubble-Lemaître Law. These velocities are induced by gravitational interactions with other nearby masses and the overall matter distribution in the universe.

Peculiar velocities can be significant, particularly for galaxies in clusters, where gravitational forces are strong. They can cause galaxies to move towards each other, in apparent contradiction to the overall expansion of the universe. However, these peculiar velocities are local deviations from the general trend of cosmic expansion and do not contradict the Hubble-Lemaître Law or the cosmological principle.

When observing galaxies other than the Milky Way, it is necessary to account for both the expansion of the universe (as described by the Hubble-Lemaître Law) and these peculiar velocities. Obviously, this complicates the measurement of cosmic distances, especially at smaller redshifts, where the velocity predicted from the Hubble-Lemaître Law is comparable to the peculiar velocity.

## 1.6. Spatial geometry of the universe
The spatial geometry of the universe is another important aspect of cosmology that has significant implications for the nature and fate of the universe. According to the theory of General Relativity, the distribution of matter and energy in the universe determines the curvature of spacetime, which in turn influences the evolution and geometry of the universe.

There are three possible spatial geometries for the universe: flat, positively curved (spherical), and negatively curved (hyperbolic). Each of these geometries is associated with different cosmological models and has different implications for the ultimate fate of the universe.

1. **Flat Universe**: In a flat universe, parallel lines remain parallel forever, the angles of a triangle sum up to $180$ degrees, and the universe is infinite in extent. The density of matter and energy in a flat universe is exactly equal to the critical density, which is the density required to keep the universe flat. A flat universe will continue to expand forever, but at a rate that slows down over time.

2. **Positively Curved Universe**: In a positively curved or spherical universe, parallel lines eventually converge, the angles of a triangle sum up to more than $180$ degrees, and the universe is finite but unbounded. The density of matter and energy in a positively curved universe is greater than the critical density. A positively curved universe will eventually stop expanding and begin to contract in a "Big Crunch."

3. **Negatively Curved Universe**: In a negatively curved or hyperbolic universe, parallel lines diverge, the angles of a triangle sum up to less than $180$ degrees, and the universe is infinite. The density of matter and energy in a negatively curved universe is less than the critical density. A negatively curved universe will continue to expand forever, at an ever-increasing rate.

Observations, such as those from the Planck satellite, strongly suggest that our universe is flat, or very close to flat. However, these observations do not completely rule out a slightly curved universe. Examining the spatial geometry of the universe remains an active area of research in cosmology.

## 1.7. Cosmological constant
The cosmological constant $\Lambda$, is nowadays a key term in the Einstein field equations of general relativity, initially introduced by Einstein himself as a mechanism to preserve the notion of a static Universe. Its inclusion allows a non-zero vacuum energy, presenting a possibility of a Universe with a repulsive force countering gravity on cosmological scales.

### 1.7.1. Historical background
The cosmological constant was first proposed by Einstein in 1917 as a means of ensuring that the mathematical solutions of his field equations were consistent with the then-popular idea of ​​a "static" universe. However, Edwin Hubble's discovery of the expansion of the Universe in 1929 essentially invalidated the need for a cosmological constant, which would lead Einstein to call it his "greatest blunder."

### 1.7.2. Revival and dark energy
Despite its rocky inception, $\Lambda$ made a comeback in the late 20th century. Observations of distant SNe in the 1990s indicated that the expansion of the Universe is accelerating, contrary to the expectations of a Universe dominated by matter. This accelerated expansion could be accounted for by reintroducing the cosmological constant, this time with a positive value, into the Einstein Field Equations, where it now represents the energy density of the vacuum, or so-called "Dark Energy" with a value of $\Lambda = 0.6847 \pm 0.0073$ acoording to the 2018 Planck results[^2].

In the cosmological $\Lambda$CDM model (where $\Lambda$ represents the cosmological constant, CDM stands for Cold Dark Matter), dark energy is responsible for approximately $70\%$ of the total energy density of the universe. It is uniformly distributed in space, does not dilute as the universe expands, and causes the expansion of the universe to accelerate.

### 1.7.3. Vacuum energy and the cosmological constant problem
In quantum field theory (QFT), the vacuum is not an empty space but "filled" with zero-point energy due to quantum fluctuations. Theoretically, this zero-point energy contributes to the cosmological constant and hence, to the energy density of the universe. However, when its contribution to the cosmological constant is calculated using QFT, it is approximately $50 - 120$ orders of magnitude larger than the observed value of the cosmological constant – this discrepancy is known as the cosmological constant problem and is one of the greatest unsolved problems in theoretical physics.

### 1.7.4. Future perspectives
Given its central role in our current understanding of the universe's large-scale structure and dynamics, the cosmological constant remains an active area of research. Many experiments, such as those examining cosmic microwave background radiation, are refining our understanding of $\Lambda$ and its implications on cosmic evolution. Moreover, it is also being investigated in the context of quantum gravity and string theory, where it is related to the geometry of the hidden extra dimensions.

The cosmological constant, from its precarious introduction and temporary abandonment, to its surprising revival, has turned out to be a cornerstone of modern cosmology. Its precise nature, whether it's truly constant, or slowly evolving with time (in which case it would be termed quintessence), remains an open question and the subject of ongoing cosmological research.


[^1]: Baez, J. C., Weiss, M. (2017). *Is Energy Conserved in General Relativity?* University of California, Riverside. Retrieved May 30, 2023, from https://math.ucr.edu/home/baez/physics/Relativity/GR/energy_gr.html

[^2]: Planck Collaboration (2020). *Planck 2018 results-VI. Cosmological parameters*. Astronomy & Astrophysics, 641, A6.