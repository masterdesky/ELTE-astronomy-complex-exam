# 7. Cosmological inflation

## 7.1. The horizon problem and the smoothness problem
The horizon problem and the smoothness problem are two of the main issues of the Big Bang cosmology that the theory of cosmological inflation aims to solve.

The horizon problem arises from the observation that different regions of the universe, which are too far apart to have ever been in causal contact, have nearly the same temperature. This is puzzling because, according to the standard Big Bang model, there hasn't been enough time since the Big Bang for light (or any information) to travel from one of these regions to the other. So, how could they have reached the same temperature? Inflation solves this problem by proposing that the universe underwent a period of rapid expansion, which allowed these regions to be in causal contact before inflation, and then rapidly moved them apart.

The smoothness problem, also known as the flatness problem, refers to the observation that the universe is remarkably flat and homogeneous on large scales, much more than the standard Big Bang model would predict. Inflation explains this by suggesting that the rapid expansion stretched out any initial curvature or inhomogeneities, leading to a universe that appears flat and homogeneous on large scales.

In both cases, the idea is that the universe started out small enough for light to travel across it and for it to reach a uniform temperature and curvature. Then, during the inflationary period, the universe expanded so rapidly that it preserved this initial uniformity, but became much larger than the region that we can currently observe.

## 7.2. Cosmological equation of motion
The energy density and pressure of a classical scalar field, such as the inflaton field, are key quantities in cosmology. They enter into the Friedmann equations, which govern the dynamics of the universe.

The action of a scalar field $\phi$ in a curved spacetime is given by

$$
    S
    =
    \int \mathrm{d}^4x \mathcal{L}[\phi]
    \equiv
    \int \mathrm{d}^4x \sqrt{-g}
    \left[
        \frac{1}{2} g^{\mu\nu} \partial_{\mu} \phi \partial_{\nu} \phi
        +
        V(\phi)
    \right] \, ,
$$

where $g$ is the determinant of the metric tensor $g_{\mu\nu}$, and $V(\phi)$ is the potential of the scalar field $\phi$. The Lagrangian density $\mathcal{L}[\phi]$ is the integrand of the action $S$.

The equation of motion of the scalar field $\phi$ is obtained by varying the action $S$ with respect to $\phi$. This yields the following Euler-Lagrange equation[^1]:

$$
    \delta S = 0
    =
    -
    \partial_{\mu}
    \frac{\partial \sqrt{-g} \mathcal{L}}{\partial (\partial_{\mu} \phi)}
    +
    \frac{\partial \sqrt{-g} \mathcal{L}}{\partial \phi}
    =
    \ddot{\phi} + 3H \dot{\phi} - \frac{1}{a^{2}} \nabla^{2} \phi + \frac{\partial V}{\partial \phi} \, ,
$$

where $H = \dot{a}/a$ is the Hubble parameter, and $a$ is the scale factor of the universe. If we assume that gradients of the scalar field are negligible, then the equation of motion of the scalar field $\phi$ in a curved spacetime reduces to

$$
    \ddot{\phi} + 3H \dot{\phi} + \frac{\partial V(\phi)}{\partial \phi}
    =
    0 \, .
$$

This equation describes how the inflaton field evolves over time, driving the inflationary expansion of the universe. While the term $\ddot{\phi}$ represents the acceleration of the inflaton field, the term $3H \dot{\phi}$ describes the damping effect due to the expansion of the universe. It tends to slow down the change of the inflaton field. The term $\partial V / \partial \phi$ represents the "force" experienced by the inflaton field due to the potential $V(\phi(t))$. It drives the field towards lower potential energy.

## 7.3. Energy density and pressure of a classical scalar field
Both the energy density and pressure for a perfect, isotropic fluid can be derived from the stress-energy tensor $T_{\mu\nu}$ of the scalar field $\phi$. We found in [chapter 1](./1-COSMOLOGY_Fundamentals_of_Relativistic_Cosmology.md) that the stress-energy tensor is of the following form[^2]:

$$
    T_{\alpha\beta}
    =
    - \partial_{\alpha} \phi
    \frac{\partial \mathcal{L}}{\partial (\partial^{\beta} \phi)}
    +
    g_{\alpha\beta} \mathcal{L}
    \equiv
    \partial_{\alpha} \phi \partial_{\beta} \phi
    -
    g_{\alpha\beta}
    \left(
        \frac{1}{2} g^{\mu\nu} \partial_{\mu} \phi \partial_{\nu} \phi
        +
        V(\phi)
    \right)
$$

Without any anisotropies, the stress-energy tensor is diagonal, in which the energy density is given by the $T_{00}$ component and pressure is given by the $T_{ii}$ components. The energy density and pressure of the scalar field $\phi$ are then given by

$$
    \varrho_{\phi}
    =
    T_{00}
    =
    \frac{1}{2} \dot{\phi}^{2} + V(\phi)
$$

$$
    p_{\phi}
    =
    T_{ii}
    =
    \frac{1}{2} \dot{\phi}^{2} - V(\phi) \, .
$$

During the inflationary period, the potential energy $V(\phi)$ dominates over the kinetic energy $\frac{1}{2} \dot{\phi}^{2}$. This leads to a large positive energy density $\varrho$ and a large negative pressure $p$. According to the Friedmann equations, this results in a rapid exponential expansion of the universe, which is the defining feature of inflation.

Inserting these equations for the energy density and pressure into the continuity equation $\dot{\varrho} + 3H(\varrho + p) = 0$ yields us the already familiar equation of motion of the scalar field $\phi$:

$$
    \ddot{\phi} + 3H \dot{\phi} + \frac{\partial V(\phi)}{\partial \phi}
    =
    0 \, .
$$

It's also worth noting that the equation of state for a single-component scalar field is given by $w = p/\varrho$, where $c = 1$ (as it was discussed in [chapter 2](./2-COSMOLOGY_The_Evolution_of_the_Universe.md)). During inflation, when the potential energy dominates, the equation of state is approximately $-1$, which corresponds to a vacuum-like energy density. This is another way of seeing why inflation leads to a rapid expansion: a vacuum-like equation of state causes the universe to expand as if it were empty, even though it is filled with the energy of the inflaton field.

## 7.4. Inflationary potential inspired by GUT spontaneous symmetry breaking
The inflationary potential is a key component of the theory of cosmological inflation. It describes the potential energy of the inflaton field, which drives the inflationary expansion of the universe. The specific form of the inflationary potential is not known from first principles, but it is often inspired by theories of high-energy physics, such as grand unified theories (GUTs).

In the context of GUTs, the inflationary potential is often associated with spontaneous symmetry breaking. This is a process where a system goes from a symmetric state to a state with lower symmetry, in order to minimize its potential energy. In the early universe, this could occur when the temperature drops below a certain critical value, triggering a phase transition.

## 7.5. The typical time and energy scale of inflation
The time and energy scales of inflation are key parameters that characterize the inflationary period. They are typically set by the properties of the inflaton field and its potential.

- **Time scale of inflation**: The duration of the inflationary period is typically characterized by the number of e-folds, which is the amount by which the universe expands during inflation. One e-fold corresponds to the universe doubling in size. The exact number of e-folds during inflation is not known, but it is generally believed to be around $60$. This is enough to solve the horizon and flatness problems and to ensure that the observable universe today originated from a causally connected region before inflation. This process happened in the early universe, approximately $10^{-36}$ seconds after the Big Bang and it ended around $10^{-33}$ or $10^{-32}$ seconds after it.

- **Energy scale of inflation**: The energy scale of inflation is set by the value of the inflaton potential $V(\phi)$ during inflation. This is typically estimated to be around $10^{16} \operatorname{GeV}$, which is close to the scale of grand unified theories (GUTs). This is based on observations of the cosmic microwave background, which provide information about the amplitude of density fluctuations generated during inflation. However, the exact energy scale could be somewhat lower or higher, depending on the details of the inflationary model.

## 7.6. Inflationary solution of the cosmological problems
Cosmological inflation provides elegant solutions to several problems that are not adequately addressed by the standard Big Bang model. These include the horizon problem, the flatness problem, and the monopole problem.

- **Horizon Problem**: The horizon problem refers to the fact that different regions of the universe, which are too far apart to have ever been in causal contact, have nearly the same temperature. Inflation solves this problem by proposing that the universe underwent a period of rapid expansion, which allowed these regions to be in causal contact before inflation, and then rapidly moved them apart.
- **Flatness Problem**: The flatness problem refers to the observation that the universe is remarkably flat and homogeneous on large scales, much more than the standard Big Bang model would predict. Inflation explains this by suggesting that the rapid expansion stretched out any initial curvature or inhomogeneities, leading to a universe that appears flat and homogeneous on large scales.
- **Monopole Problem**: The monopole problem arises from the prediction of grand unified theories (GUTs) that a large number of magnetic monopoles should have been produced in the early universe. However, we do not observe these monopoles today. Inflation solves this problem by diluting the density of monopoles. During the rapid expansion, the monopoles are pushed so far apart that their density today is extremely low, making it unlikely that we would observe one.

In each case, the idea is that the universe started out small enough for light to travel across it and for it to reach a uniform temperature and curvature. Then, during the inflationary period, the universe expanded so rapidly that it preserved this initial uniformity, but became much larger than the region that we can currently observe. This explains why the observable universe appears so uniform and flat, and why we do not observe magnetic monopoles.

[^1]: Enqvist, K. (2012). Cosmological inflation. arXiv preprint arXiv:1201.6164.
[^2]: DePies, M. Survey of dark energy and quintessence.