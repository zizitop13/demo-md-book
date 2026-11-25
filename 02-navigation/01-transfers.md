# Orbital transfers

A Hohmann transfer connects two coplanar circular orbits using an elliptical transfer orbit and two idealized impulsive burns.

```mermaid
flowchart LR
    A[Initial orbit] --> B[First burn]
    B --> C[Transfer ellipse]
    C --> D[Second burn]
    D --> E[Target orbit]
```

<!-- pagebreak -->

## Transfer duration

For initial and final orbital radii $r_1$ and $r_2$:

$$
a_t=\frac{r_1+r_2}{2}
$$

$$
t=\pi\sqrt{\frac{a_t^3}{\mu}}
$$

Real missions may require additional corrections, inclination changes, or finite-duration burns.
