### Bollinger Resonance Field Ansatz

We introduce a massless scalar test field as the driver of the resonance:

$$
\phi(r,\theta,\phi,t) = \Re \left[ A \, e^{i(\omega t - k r_*)} \, Y_{\ell m}(\theta,\phi) \right]
$$

where  
- $r_*$ is the tortoise coordinate ($dr_* = dr / (1 - 2M r / \Sigma + a^2 / \Sigma)$ in Kerr),  
- $Y_{\ell m}$ are spheroidal harmonics,  
- the mode is tuned just below the superradiant threshold  

$$
\omega = m \, \Omega_\text{H} - \delta \qquad (\delta \ll \Omega_\text{H})
$$

with horizon angular velocity  
$$
\Omega_\text{H} = \frac{a}{2Mr_+}= \frac{a}{2M \left(M + \sqrt{M^2 - a^2}\right)}
$$

The field couples to the background Kerr geometry through an effective stress-energy contribution that sources an **additional** frame-dragging term:

$$
\delta g_{t\phi} \propto (\partial_t \phi)^2 - (\partial_\phi \phi)^2 \quad \text{(quadrupole-like torque)}
$$

This perturbation remains **everywhere timelike or null** (no exotic matter, no negative energy outside the ergosphere) while resonantly pumping rotational energy out of the spin parameter $a$, ultimately driving the inner Cauchy horizon toward a transient, stabilised closed-timelike region.

(Full linearised Einstein–Klein-Gordon equations + stability analysis coming in `theory/bollinger_oscillations_derivation.tex`.)
