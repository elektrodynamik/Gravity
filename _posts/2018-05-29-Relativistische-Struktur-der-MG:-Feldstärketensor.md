---
published: true
---
# Relativistische Struktur der MG: Feldstärketensor

---

## 4.1 Partielle Ableitungen

---

- Bisheriges Inventar: $$ \{ x_\mu, y^\mu , x_\mu y^\mu, \delta^{\nu}_ { \ \mu} , \eta_{\mu \nu} \}  $$

- $$ t_{ \alpha \  \gamma}^ { \ \beta} \text{ ~ } x_\alpha y^\beta z_\gamma $$

Notation und Transformation partieller Ableitungen:

- $$ \partial_\mu := \frac{\partial}{\partial^\mu} \text{ ~ } y_\mu \text{ d.h. } \partial'_ \mu \text{ ~ } \Lambda_\mu^{\ \nu} \partial_\nu $$  


- $$ \partial^\mu := \frac{\partial}{\partial_\mu} \text{ ~ } y_\mu \text{ d.h. } \partial'^ \mu \text{ ~ } \Lambda^\mu_{\ \nu} \partial^\nu $$

- $$ \frac{\partial t_{ \nu \ \sigma}^{ \ \rho} }{\partial_\mu}  := \partial_\mu t_{ \nu \ \ \sigma}^{ \ \rho} \text{ ~ } \delta_{ \mu \ \nu \ \ \sigma}^{ \ \ \rho}  $$


- $$ \frac{\partial t_{ \nu \ \sigma}^{ \ \rho} }{\partial^\mu}  := \partial^\mu t_{ \nu \ \ \sigma}^{ \ \rho} \text{ ~ } \delta_{ \ \nu \ \ \sigma}^{ \mu \ \ \rho}  $$

Herleitung mit $$ \ \Lambda_\star^{\ \star} \stackrel{\Lambda^{-1} }{\to} \Lambda^\star_{\ \star} $$

- $$ x'^\mu \text{ ~ } \Lambda^\mu_ {\ \nu } x^{\nu} $$

- $$ \Lambda_{\mu}^{ \ \kappa} x'^\mu = \Lambda_\mu^{ \ \kappa} \Lambda^\mu_{ \ \nu} x^\nu = \delta_\nu^{ \kappa} x^\kappa  $$

- $$ \dfrac{x'^\mu}{x^\nu} = \Lambda^\mu_{ \ \nu} \Leftrightarrow \dfrac{x'^\nu}{x'^\mu} = \Lambda_\mu ^{\ \nu} $$

Ausbau für höhere partielle Ableitungen:

- $$ \frac{\partial}{\partial x^\mu} \frac{\partial}{\partial x^\nu} t^{\rho \sigma} \text{ ~ } \delta_{\mu \nu}^{\ \ \rho \sigma} $$

- $$ \partial_\mu \partial^\mu f^\alpha_{\ \beta \gamma} \text{ ~ } f^\alpha_{\ \beta \gamma} \Rightarrow \partial_\mu \partial^\mu = \frac{1}{c^2} \partial^2_t - \Delta = \square $$ ist ein Lorenzskalar.

---

## Inhomogene Maxwellgleichungen (IMG)

---

- $$ \vec \nabla E = 4 \pi \rho , \vec \nabla \wedge \vec B - \partial_{ct} \vec E = \frac{4 \pi}{c} \vec j $$ sind lorenzinvariant (LI), d.h. in \textbg{allen} Inertialsystemen gültig.

- Kontinuitätsgleichung 'K': $$ \partial_{ct} c \rho + \vec \nabla \vec j $$ folgt aus IMG.

Falls IMG $$ \to $$ K ist LI, so gilt K $$ \Leftrightarrow \partial_\mu j^\mu = 0 = \partial^\mu j_\mu $$

---
Definitionen: 

- $$ (\vec j^\mu (x) ) = \begin{pmatrix} c \rho (x) \\ \vec j (x) \end{pmatrix} $$ 

- $$ ( \partial_\mu ) = \begin{pmatrix} \partial_0 \\ \vec \nabla \end{pmatrix} $$

- $$ (\vec j^\mu (x) ) = \begin{pmatrix} c \rho (x) \\ \vec - j (x) \end{pmatrix} $$ 

- $$ ( \partial^\mu ) = \begin{pmatrix} \partial_0 \\ -\vec \nabla \end{pmatrix} $$

$$ \to \partial_\mu \text{ ~ } $$ kovariante Vektorvariable, $$ j^\mu $$ kontravariante VV $$ \to \partial_mu j^\mu \text{ ~ Skalar} = 0 $$

$$ \to \partial^\mu \text{ ~ } $$ kontravariante Vektorvariable, $$ j^\mu $$ kovariante VV $$ \to \partial^mu j_\mu \text{ ~ Skalar} = 0 $$

$$ \to $$ K lautet:

$$\boxed{\partial_\mu j^\mu = 0 $$ 

- Ladung q ( Allgemein Anzahl an Elementarladungen) ist LI. d$$q = \rm{d}^3x \rm{d} \frac{j^0}{c} $$ 

Definition: Feldstärketensor.


$$ (F^{mu \nu} ) = \begin{pmatrix} 0 & - E_x & - E_y - & E_z \\ E_x & 0  & - B_z & B_y \\ E_y & B_z & 0 & -B_x \\ E_z & -B_y & B_x & 0 \end{pmatrix} $$ 

- IMG umformuliert

$$ \boxed{ \partial_\mu F^{\mu \nu} (x) = \frac{4 \pi}{c} j^\nu (x) } $$

Nachrechnen zeigt: 

- $$ \nu = 0; \vec \nabla \vec E = \frac{4 \pi}{c} c \rho $$ 

- $$ \nu = i; \vec \nabla \wedge \vec B (x) - \partial_{ct} E(x) = \frac{4 \pi}{c} \vec j (x) $$

Zusammenhang:

$$ F_{\star \star} \to A_\star $$

A. Lorenzeichbedingung: $$ \partial_{ct} \phi (x) + \vec \nabla \vec A (x) = 0 $$

B. Lorenzeichbedingung: $$ \partial_\mu A^\mu $$  