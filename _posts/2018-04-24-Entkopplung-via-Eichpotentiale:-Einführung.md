---
published: true
---
## Entkopplung via Eichpotentiale: Einführung

---
Vakuum heißt: $$ \rho = 0, \vec j = \vec 0 $$. d.h. keine Ladung und somit ist die Entkopplung einfach:

- (I) $$ \vec \nabla \vec E = 0$$
- (II) $$ \vec \nabla \vec B = 0$$
- (III) $$ \vec \nabla \wedge \vec E + \partial_{ct} \vec B = 0$$
- (IV) $$ \vec \nabla \wedge \vec B - \partial_{ct} \vec E = 0$$

Symmetrie: $$ \vec E \mapsto \vec B, \vec B \mapsto \vec E $$ 

$$\vec \nabla \wedge (II) \Rightarrow \vec \nabla \wedge (\vec \nabla \wedge \vec E) + \partial_{ct} \vec \nabla \wedge \vec B = \vec 0$$

$$ \require{cancel} \rightarrow \vec \nabla (\cancel{\vec \nabla \vec E}) - \Delta \vec E + \partial_{ct}^2 \vec E =  \vec 0 $$

Bemerkung:Nach (IV) $$ \vec \nabla \wedge \vec B = \partial_{ct} \vec E $$

$$\vec \nabla \wedge (IV) \Rightarrow \vec \nabla \wedge (\vec \nabla \wedge \vec B) - \partial_{ct} \vec \nabla \wedge \vec E = \vec 0 $$

$$ \require{cancel} \rightarrow \vec \nabla (\cancel{\vec \nabla \vec B}) - \Delta \vec B + \partial_{ct}^2 \vec B =  \vec 0 $$ 


$$ \rightarrow (-\Delta + \partial_{ct}^2) \vec E (\vec x,t) = \vec 0 $$

$$ \rightarrow (-\Delta + \partial_{ct}^2) \vec B (\vec x,t) = \vec 0 $$

Fazit: Vakuum-Wellenausbreitung ist isotrop und mit Geschwindigkeit c.

---
## 2.2 Eichpotentiale
---
- (I) $$ \vec \nabla \vec E = 4 \pi \rho $$ 
- (II) $$ \vec \nabla \wedge \vec E + \partial_{ct} \vec B = \vec 0 $$
- (III) $$ \vec \nabla \vec B  = 0 $$
- (IV) $$ \vec \nabla \wedge \vec B - \partial_{ct} \vec E = \vec 0 $$

Erster Schritt in Richtung der Entkopplung durch Ansatz (A):

[ $$ \phi :$$ Skalarpotential ]
[ $$ \vec A :$$ Vektorpotential ]

$$ \vec E (\vec x, t) = - \vec \nabla \phi(\vec x, t) - \partial_{ct} \vec A (\vec x, t) $$

$$ \vec B(\vec x, t) =  ( \vec \nabla \wedge \vec A) (\vec x, t)$$

Finden wir für gegebenes $$ \vec E, \vec B $$ ein $$ \phi, \vec A $$ ? Ja.

Sind $$ \phi, \vec A $$ eindeutig? Nein.

Homogene Gleichungen ( (II),(III) ) ) direkt erfüllt:

$$ \vec \nabla \wedge \vec E =^{A} - \partial_{ct} \vec \nabla \wedge \vec A =^{A} -\partial_{ct} \vec B \Rightarrow \text{ (II) }$$

$$ \vec \nabla \cdot \vec B =^{A} 0 \Rightarrow \text{ (III) }$$

Inhomogene Gleichungen sind immer noch gekoppelt: 

(I) $$ \Rightarrow  -\Delta \phi - \partial_{ct} \vec \nabla \vec A = 4\pi \rho$$

(IV) $$ \Rightarrow \vec \nabla \wedge (\vec \nabla \wedge \vec A) + \partial_{ct} \vec \nabla \phi + \partial_{ct}^2 \vec A = \dfrac{4 \pi}{c} \vec j$$


$$ \Rightarrow $$ Wir erhalten 4 Gleichungen für 4 Größen $$ (\phi,\vec A) $$ 

$$ \Rightarrow $$ Immer noch gekoppelt, Besserung druch Nebenbedingungen (NB)?

---
## 2.3. Eichbedingungen
---
**Definiton**: Für beliebige $$ \chi (\vec x,t) \in \mathbb{R} $$ lässt die Eichtransformation:
- $$\phi (\vec x,t) \rightarrow \phi'(\vec x,t) = \phi(\vec x,t) - \partial_{ct} \chi(\vec x,t)$$ 
- $$\vec A (\vec x,t) \rightarrow \vec A'(\vec x,t) = \vec A (\vec x,t) -\vec \nabla \vec A (\vec x,t)$$

die Felder $$ \vec E, \vec B $$ invariant (' $$ \Leftrightarrow$$ 'neu' ) 

_Bemerkung_: 
- $$ \vec E' = -\vec \nabla \phi' - \partial_{ct} \vec A' = -\vec \nabla \phi +\partial_{ct} \vec A - \partial_{ct} \vec \nabla \chi = \vec E$$
- $$ \require{cancel} \vec B' = \vec \nabla \wedge \vec A' = \vec \nabla \wedge \vec A + \cancel{\vec \nabla \wedge (\vec \nabla \chi)} =  \vec B$$ 

$$\Rightarrow$$ (I) - (IV) (lassen alle Physik) invariant unter Eichtransformation

$$\Rightarrow \phi , \vec A$$ sind nicht direkt beobachtbar, nichtsdestotrotz Behandlung als Observable in der Quantenmechanik ('Aharonov-Bohm-Effekt').

$$\Rightarrow$$ Die Wahl von $$ \chi $$ eröffnet die Möglichkeit zur cleveren (d.h. situationsangepassten) Entkopplung von (I) und (IV).

$$ \Rightarrow$$ Populäre Eichungen: Coulomb, Lorenz.

**Definition**: $$ \phi ,\vec A $$ in Coulombeichung, falls 

$$ \require{boxed} \boxed{ \phi \ \text{beliebig}, \vec \nabla \cdot \vec A = 0 \  \text{('C')}}$$

_Bemerkung_: Mit C-Eichung folgt aus (NB-Gleichungen)

$$ ( (I) - C) - \Delta \phi (\vec x,t) = 4 \pi \rho (\vec x, t) $$

$$ ( (IV) -C ) - \Delta \vec A (\vec x, t) + \partial_{ct}^2 \vec A(\vec x,t) = \dfrac{4 \pi}{c} \vec j - \partial_{ct} \vec \nabla \phi (\vec x,t) $$

(I-C) heißt Poisson-Gleichung (analog Elektrostatik/Gravitationsphysik) 

**Allgemeine Lösung:**

$$ \require{boxed} \require{cancel} \boxed{\phi(\vec x,t) = \int \dfrac{\rho (\vec x,t) }{\mid\vec x -\vec x'\mid} {\rm d}^3 x' + \phi_{\rm hom} (\vec x, t) \\ \Rightarrow \phi_{\rm part.} - \Delta \cancelto{0}{ \phi_{\rm hom.} } = \phi } $$

_Bemerkung_: $$ \phi_{\rm part.} $$ ist nicht relativistisch invariant, ein modifiziertes $$ \rho (\vec x, t) $$ ergibt ein modifiziertes $$ \phi (\vec x, t) $$ . Hierbei bezeichnet $$ \vec x \Leftrightarrow \vec x' $$ eine _instantane Fernwirkung_.

_Bemerkung_: C-NB ist nicht relativistisch invariant.

Neue rechte Seite von (IV - C) enthält $$ \vec j_{\perp}$$ von $$ \vec j$$ , wo $$ \vec j = \vec j_{\parallel} + \vec j_{\perp}$$ gemäß Helmholtz, denn C-NB und Kontinuitätsgleichung geben

$$\vec \nabla \dfrac{\rm d}{\rm d t} \phi = \vec \nabla \int \dfrac{- \vec \nabla \vec j(\vec x,t)}{\mid\vec x - \vec x'\mid} {\rm d}^3 x' = \dfrac{4 \pi}{c} \vec j_{\parallel} (\vec x,t) $$

**Definiton**: $$ \phi, \vec A$$ in Lorenzeichung, falls 

$$ \partial_{ct} \phi (\vec x,t) + \vec \nabla \cdot \vec A (\vec x,t) = 0 \ ('L-NB')$$

_Bemerkung_: Mit L-NB folgt aus NB-Gleichungen

- $$ (I-L): (-\Delta + \partial_{ct}^2) \phi (\vec x,t) = 4 \pi \rho (\vec x,t) $$
- $$ (I-L): (-\Delta + \partial_{ct}^2) \vec A (\vec x',t) = \dfrac{4 \pi}{c} \vec j (\vec x,t) $$

$$ \Rightarrow $$ Wellengleichung für $$ \phi, \vec A $$ (4 Gleichungen für 4 Unbekannte).

$$ \Rightarrow $$ Entkopplung ist total d.h. ohne $$\perp$$-Anteil.

$$ \Rightarrow $$ Allgemeine Lösung via retardierter Potential (siehe später {GREENSCHE-FUNKTION}). D.h. :

$$ \phi (\vec x,t) \leftarrow \rho (\vec x',t_{ \rm ret.}) $$ mit $$ t_{ \rm ret.} = t - \dfrac{\mid \vec x -\vec x'\mid}{c}$$ 

$$ \vec A (\vec x,t) \leftarrow \vec j (\vec x',t_{ \rm ret.}) $$ mit $$ t_{ \rm ret.} = t - \dfrac{\mid \vec x -\vec x'\mid}{c}$$ 

L-NB ist relativistisch invariant!

_Bemerkung_: C-NB immer erzielbar und nicht eindeutig:

$$ 0 =^! \vec \nabla \cdot \vec A' = \vec \nabla \cdot \vec A + \Delta A \chi $$ 

