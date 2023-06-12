# 13. Astrophysical methods of cosmic distance determination

## 13.1. Cosmic distance ladder
The cosmic distance ladder is the succession of methods by which astronomers determine the distances to celestial objects. The concept is somewhat like a ladder because each rung of the ladder depends on the rungs below it.

1. **Radar ranging**: The first and most direct method is radar ranging, where we bounce radio waves off nearby objects like asteroids or planets and measure the time it takes for the signal to return. This gives us a very accurate measure of the distance.
2. **Stellar parallax**: The next rung is stellar is parallax, which involves observing the apparent shift in position of a nearby star against the background of distant stars as Earth orbits the Sun. This method is limited to relatively nearby stars, up to a few thousand light-years away.
3. **Spectroscopic parallax**: For stars further away, we use spectroscopic parallax. This method involves comparing the apparent brightness of a star with its absolute brightness, which we can estimate from its spectrum. The difference gives us the distance.
4. **Cepheid variables and RR Lyrae stars**: For even greater distances, we use variable stars like Cepheids and RR Lyrae stars. These peculiar stars, which have a well-defined relationship between their period of variability and their intrinsic brightness, are used as "standard candles" to measure distances. By comparing the observed brightness of a variable to its known intrinsic brightness, the distance can be determined. This method can be used to measure distances to galaxies up to about $60$ million light-years away.
5. **Type Ia supernovae**: Like Cepheids and RR Lyrae stars, Type Ia supernovae serve as standard candles because their intrinsic brightness is well known. These supernovae are several orders of magnitude brighter than individual stars, allowing them to be used to measure distances to galaxies billions of light-years away. However, they are rare events, and their use requires careful correction for the effects of dust absorption and the precise determination of their peak brightness.
6. **Tully-Fisher relation and Faber-Jackson relation**: For galaxies, the Tully-Fisher relation, which relates the luminosity of a spiral galaxy to its maximum rotation speed, and the Faber-Jackson relation, which relates the size, surface brightness, and velocity dispersion of an elliptical galaxy, can be used to estimate distances.
7. **Hubble-Lemaître law**: Finally, for extremly distant objects on the largest scales, the Hubble-Lemaître law can be used. This law describes the relationship between their distance and the redshift of their spectral lines due to the expansion of the universe.

Each of these methods has its limitations and uncertainties, and astronomers are constantly working to refine them and extend the ladder to greater distances. The cosmic distance ladder is crucial for understanding the scale of the universe and for determining the Hubble constant, which is a measure of the rate of expansion of the universe.

## 13.2. Parallax
Parallax is one of the fundamental methods used in astrometry to measure distances to nearby stars. It is based on the apparent shift in position of a nearby star against the background of distant stars as observed from different points.

The principle of parallax is similar to the effect you see when you hold up a finger and look at it with one eye closed, then switch eyes. Your finger appears to move against the background even though it's stationary, because you're looking at it from two different points.

In the case of stellar parallax, the two points are the Earth at two different points in its orbit around the Sun, six months apart. The star's parallax is the angle subtended at the star by the radius of the Earth's orbit. The unit of measurement here is the arcsecond, and one *parsec* is defined as the distance to a star that has a parallax of one arcsecond. The formula relating distance $d$ in parsecs and parallax $p$ is:

$$
    d[pc] = \frac{1}{p['']}
$$

This method is most effective for stars within a few hundred light-years of Earth. Beyond this, the parallax angle becomes too small to measure accurately with current technology.

It's important to note that parallax measurements are affected by factors such as the motion of the Earth around the galactic center and the intrinsic motion of the stars themselves. Therefore, careful measurements and corrections are necessary to obtain accurate results. Although this adds complexity, the motion of the solar system around the galactic center provides a longer baseline (the distance between the two observation points) for parallax measurements, making them more accurate

## 13.3. Standard candles
### 13.3.1. Cepheid variables and RR Lyrae stars
Specific variable stars, like Cepheid variables and RR Lyrae stars that exhibit a clear, periodic variation in brightness can be efficiently used as standard candles. They have a crucial position in the cosmic distance ladder due to their period-luminosity relationship.

Cepheid variables are massive, luminous stars whose brightness varies with a regular period that ranges from a few days to a few months. The period of a Cepheid variable is directly related to its intrinsic luminosity, a relationship discovered by Henrietta Swan Leavitt in the early 20th century. This period-luminosity relationship allows astronomers to determine the absolute magnitude of a Cepheid variable from its period, and thus calculate its distance using the inverse square law of light. The period-luminosity relationship for Cepheid variables is given by:

$$
    M = -2.43 \cdot (\log(P) - 1) - 4.05 \, ,
$$

where $M$ is the absolute magnitude and $P$ is the period in days. From this, the distance can be calculated using the formula:

$$
    d = 10^{(m - M + 5) / 5} \operatorname{pc} \, ,
$$

where $m$ is the apparent magnitude and $M$ is the absolute magnitude. The average absolute magnitude of Cepheid variables is about $M_{V} = -3.0$ in the visual band.

RR Lyrae stars are less luminous than Cepheid variables, but they also exhibit a period-luminosity relationship. Their periods are typically less than a day, and they all have roughly the same average absolute magnitude. This makes them useful as standard candles, especially for determining the distances to globular clusters, where they are often found. The average absolute magnitude of RR Lyrae stars is about $M_{V} = 0.75$ in the visual band.

Both Cepheid variables and RR Lyrae stars have been instrumental in establishing the scale of the universe. Originally, Edwin Hubble also used Cepheid variables to determine the distance to the Andromeda galaxy, and thus prove that it was a separate galaxy outside the Milky Way. Nowadays they are also used to calibrate other methods of distance measurement, such as the Tully-Fisher relation and the use of Type Ia supernovae as standard candles.

### 13.3.2. Type Ia supernovae
Type Ia supernovae are a specific type of stellar explosions that are used as "standard candles" in astronomy due to their consistent peak luminosity. They are among the most luminous events in the universe, making them detectable across cosmological distances.

Type Ia supernovae occur in binary star systems where one of the stars is a white dwarf. The white dwarf accretes matter from its companion star until it reaches a critical mass (the Chandrasekhar limit, about $1.4 \operatorname{M_{\odot}}$), at which point it undergoes a catastrophic thermonuclear explosion.

The peak luminosity of a Type Ia supernova is remarkably consistent, with a maximum absolute magnitude of about $M_{V} = -19.3 \pm 0.3$ in the visual band. This consistency is what allows astronomers to use Type Ia supernovae as standard candles: by comparing the observed brightness of the supernova with its known absolute brightness, we can calculate its distance using the same relation as for Cepheid variables and RR Lyrae stars.

One of the key advantages of Type Ia supernovae as standard candles is their high luminosity, which makes them visible across great distances. This has allowed astronomers to measure the expansion rate of the universe (the Hubble constant) and provided evidence for the acceleration of this expansion, leading to the discovery of dark energy.

However, there are some challenges in using Type Ia supernovae as standard candles. There are slight variations in their peak luminosities, and the exact nature of the progenitor systems and the explosion mechanism are still areas of active research. Despite these challenges, Type Ia supernovae remain one of the most powerful tools for measuring cosmic distances.

## 13.4. Standard sirens
Standard sirens are a relatively new method of distance measurement in cosmology, based on the detection of gravitational waves from inspiraling and merging compact objects, such as neutron stars or black holes.

The term "standard siren" is an analogy to "standard candles" in traditional astronomy. However, instead of using light to measure distances, standard sirens use gravitational waves. The term "siren" comes from the characteristic sound that the gravitational wave signal makes when converted to an audio signal.

The concept of standard sirens was proposed by Bernard Schutz in 1986, but it wasn't until the first detection of gravitational waves by the LIGO and Virgo collaborations in 2015 that it became a practical method for measuring cosmic distances.

The principle behind standard sirens is that the amplitude of the gravitational wave signal gives a direct measure of the "luminosity distance" to the source, without the need for a cosmic distance ladder. 

The key idea is that the gravitational wave signal from the inspiral and merger of compact objects carries precise information about the system's intrinsic parameters, including the "chirp mass"

$$
    \mathcal{M}
    =
    \frac{(m_{1} m_{2})^{3/5}}{(m_{1} + m_{2})^{1/5}} \, ,
$$
where $m_{1}$ and $m_{2}$ are the masses of the two objects. The chirp mass is related to the luminosity distance $d_{L}$ by the formula and the amplitude of the gravitational wave signal, which depends on the distance to the system. The amplitude of the gravitational wave signal decreases with increasing distance, following an inverse-square law, similar to light. Therefore, by observing the amplitude of the gravitational wave signal, one can infer the distance to the source.

The first successful application of this method was with the detection of the binary neutron star merger GW170817, which was accompanied by a gamma-ray burst and an optical afterglow. The combined gravitational wave and electromagnetic observations allowed for an independent measurement of the Hubble constant.

Standard sirens have the potential to revolutionize cosmology by providing a completely independent, and potentially very precise, measurement of cosmic distances and the expansion rate of the universe. However, this method is still in its early stages and there are many challenges to overcome.


## 13.5. Tully-Fisher relation and Faber-Jackson relation
The Tully-Fisher relation and the Faber-Jackson relation are empirical relationships that provide indirect methods for estimating the distances to galaxies. They are based on observable properties of galaxies that correlate with their luminosities, 

### 13.5.1. Tully-Fisher Relation
The Tully-Fisher relation is an empirical relationship between the luminosity of a spiral galaxy and its maximum rotation velocity. It was first introduced by astronomers R. Brent Tully and J. Richard Fisher in 1977. The relationship is given by:

$$
    L \propto V_{\max}^{4} \, ,
$$

where $L$ is the total luminosity of the galaxy and $V_{\max}$ is the maximum rotation velocity of the galaxy. The exact exponent can vary depending on the wavelength of the observations and the specifics of the galaxy sample, but it is typically close to $4$.

The Tully-Fisher relation is particularly useful because the maximum rotation velocity of a galaxy can be measured relatively easily from 21-cm radio observations of neutral hydrogen, which is abundant in spiral galaxies. By comparing the observed brightness of the galaxy with its luminosity inferred from the Tully-Fisher relation, we can estimate the distance to the galaxy.

### 13.5.2. Faber-Jackson Relation
The Faber-Jackson relation is a similar empirical relationship for elliptical galaxies. It relates the luminosity of an elliptical galaxy to the velocity dispersion of its stars. The relationship is given by:

$$
    L \propto \sigma^{4} \, ,
$$

where $L$ is the total luminosity of the galaxy and $\sigma$ is the velocity dispersion of the stars in the galaxy. Like the Tully-Fisher relation, the exact exponent can vary but is typically close to $4$.

The Faber-Jackson relation is useful because the velocity dispersion of stars in an elliptical galaxy can be measured from the broadening of spectral lines. By comparing the observed brightness of the galaxy with its luminosity inferred from the Faber-Jackson relation, we can estimate the distance to the galaxy.

Both the Tully-Fisher relation and the Faber-Jackson relation are examples of "scaling relations" in astronomy, which relate the properties of galaxies to their sizes or masses. These relations are not fully understood from a theoretical perspective, but they are thought to reflect the underlying physics of galaxy formation and evolution.

## 13.6. Hubble-Lemaître law
The Hubble-Lemaître law is a fundamental principle in cosmology that provides a method for determining cosmic distances based on the redshift of galaxies. The law states that the redshift of a galaxy is proportional to its distance from us. This relationship is expressed as:

$$
    cz = H_{0} d
$$

where $c$ is the speed of light, $z$ is the redshift of the galaxy, $d$ is the distance to the galaxy, and $H_{0}$ is the Hubble constant, which represents the current rate of expansion of the universe.

The redshift $z$ of a galaxy is a measure of the shift in the wavelength of its light towards longer (redder) wavelengths, which is caused by the motion of the galaxy away from us due to the expansion of the universe. The redshift can be measured from the galaxy's spectrum by looking at the displacement of spectral lines from their rest wavelengths or by broad-band photometry, by comparing the fluxes in different wavelength bands to the colors expected for galaxies at different redshifts.

By measuring the redshift of a galaxy, we can use the Hubble-Lemaître law to estimate its distance. This method is particularly useful for very distant galaxies, for which other methods of distance measurement (such as parallax or standard candles) are not practically feasible.

However, the accuracy of distance measurements using the Hubble-Lemaître law strongly depends on the value of the Hubble constant, $H_{0}$, which is a subject of ongoing research and debate. As the time of writing, the most precise measurements from the cosmic microwave background radiation give a value of about $67.66 \operatorname{km/s/Mpc}$, while measurements based on supernovae and the cosmic distance ladder give a slightly higher value of about $74 \operatorname{km/s/Mpc}$. Also measurements based on gravitational waves give a value of about $70 \operatorname{km/s/Mpc}$, however the uncertainty on this value is very large. This discrepancy, known as the "Hubble tension", is one of the major unsolved problems in cosmology as of 2023.

Despite this uncertainty, the Hubble-Lemaître law remains a powerful tool for measuring cosmic distances and investigating the large-scale structure and evolution of the universe.