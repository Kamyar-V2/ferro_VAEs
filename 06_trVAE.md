---
title: Translationally and Rotationally Invariant VAE
---

In this section, we incorporate all invariances—both translational and rotational—within the VAE framework. 

:::{figure} #app:trVAE_widget_1
:name: fig_trVAE_widget_1
:placeholder: ./figures/fig_trVAE_widget_1_placeholder.png
(a) The latent manifold generated from the VAE demonstrates the reconstructed structure across the latent space. (b), (c), (d), (d), (f), (g), (h), (i), (j), and (k) The latent space distribution with KDE highlights clusters.
:::

The observed well-defined clusters strongly suggest the presence of underlying physical principles governing the system. These clusters likely correspond to distinct physical or structural features such as:

1. Variations in chemical composition or atomic arrangements.
2. Differences in polarization states, including translational components ($t_x$, $t_y$) and rotational states $θ$. 
3. Manifestation of lattice distortions or domain wall structures that produce spatial correlations in the data.


:::{figure} #app:trVAE_widget_2
:name: fig_trVAE_widget_2
:placeholder: ./figures/fig_trVAE_widget_2_placeholder.png
latent maps.
:::

The $z_2$ map now clearly reveals chemical and mistilt effects, while the translational components, $t_x$ and $t_y$, exhibit a pattern consistent with the polarization components. Furthermore, the angle variable captures the rotational aspect of the polarization.