---
published: true
---
## Entkopplung via Eichpotentiale: Wellengleichung im Vakuum

---
Vakuum heißt: $$ \rho = 0, \vec j = \vec 0 $$. d.h. keine Ladung und somit ist die Entkopplung einfach:

- (I) $$ \vec \nabla \vec E = 0$$
- (II) $$ \vec \nabla \vec B = 0$$
- (III) $$ \vec \nabla \wedge \vec E - \partial_{ct} \vec B = 0$$
- (IV) $$ \vec \nabla \wedge \vec B - \partial_{ct} \vec E = 0$$

Symmetrie: $$ \vec E \mapsto \vec B, \vec B \mapsto \vec E $$ 

$$\vec \nabla \wedge (II) \Rightarrow \vec \nabla \wedge (\vec \nabla \wedge \vec E) + \partial_{ct} \vec \nabla \wedge \vec B = \vec 0$$

$$ \require{cancel} \rightarrow \vec \nabla (\cancel{\vec \nabla \vec E}) - \Delta \vec E + \partial_{ct}^2 \vec E =  \vec 0 $$

_Bemerkung_: $$ \vec \nabla \wedge \vec E = \partial_{ct} \vec E \ \text{nach (IV)}$$ 

$$\vec \nabla \wedge (IV) \Rightarrow \vec \nabla \wedge (\vec \nabla \wedge \vec B) - \partial_{ct} \vec \nabla \wedge \vec E = \vec 0$$

$$ \require{cancel} \rightarrow \vec \nabla (\cancel{\vec \nabla \vec B}) - \Delta \vec B + \partial_{ct}^2 \vec B =  \vec 0 $$ nach (II)

---
$$ \rightarrow (-\Delta + \partial_{ct}^2) \vec E (\vec x,t) = 0 $$