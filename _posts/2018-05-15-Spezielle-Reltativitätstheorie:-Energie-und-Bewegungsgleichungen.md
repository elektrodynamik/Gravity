---
published: true
---
# Spezielle-Reltativitätstheorie:Energie und Bewegungsgleichungen 

---

## Wiederholung

---

Skalarprodukt: $$ \langle \cdot, \cdot \rangle $$ bezüglich (+ + + +), (- - - -) ; $$ \langle x, y \rangle = \langle x', y' \rangle = \langle Rx, Ry \rangle \\ \to R^T \ R  = I; \langle \cdot , \cdot  \rangle$$ bezüglich (+ - - -) oder (- + + +) mit Drehmatrix $$R$$.

Lorentz-Boost kann als Drehung in der Raumzeit interpretiert werden.

$$ \langle x, y \rangle = \langle x', y' \rangle = \langle \Lambda x, \Lambda y \rangle \\ \Rightarrow \Lambda^T \eta \Lambda = \eta \stackrel{\cdot \eta, \Lambda^{-1}}{\to} \eta \Lambda^T \eta = \Lambda^{-1}.  $$

Betrachte Lorenzboost in x-Richtung: 

$$ \begin{pmatrix} \gamma & -\beta \gamma  & 0 & 0\\ -\beta \gamma & \gamma & 0 & 0 \\ 0 & 0 & 1 & 0  \\ 0 & 0 & 0 & 1 \end{pmatrix}^{-1} = \begin{pmatrix} \gamma & \beta \gamma  & 0 & 0\\ \beta \gamma & \gamma & 0 & 0 \\ 0 & 0 & 1 & 0  \\ 0 & 0 & 0 & 1 \end{pmatrix}. $$

Indexkontraktion:

$$ x'^{\mu} = \Lambda^{\mu}_ {\ \nu} x^\nu, y'_ \mu = \Lambda_{\mu}^ {\ \nu} y_\nu, z^\mu = \eta^{\mu \nu} z_\nu, z_\mu =  \eta_{\mu \nu} z^\nu \\ \eta_{\mu \sigma} \eta^{\sigma \nu} = \delta^\mu_{\ \nu}. $$ Das heißt  $$ \eta^{\star \star} = (\eta_{\star \star})^{-1} $$

Fingerübung zur Indexkontraktion:

$$ {t'}_ {\alpha} ^{\beta}_ {\gamma} = \Lambda_{\alpha}^ {\ \mu} \Lambda^{\beta}_ { \ \nu} \Lambda^{\sigma }_ {\ \gamma} t_\mu^ \nu_ \sigma $$

### Achtung: d$$x^\mu$$ ist ein Vierervektor, aber d$$t$$ ist ein Lorenzskalar, d.h.:

$$ \dfrac{\rm d x^\mu}{\rm d t} $$ ist **kein** Vierervektor, d$$\tau = \rm d s $$ ist ein Lorenzskalar, d.h. $$ \dfrac{\rm d x^\mu}{\rm d \tau} = u^\mu  $$ ist ein Vierervektor, d.h. $$u'^\mu = \Lambda^{\mu}_ {\ \nu} u^\nu $$

Also: $$ u^\mu =  \dfrac{\rm d t}{\rm d \tau} \dfrac{\rm d x^\mu}{\rm d t}, $$ Mit $$ \dfrac{\rm d t}{\rm d \tau} = \gamma (v)$$ folgt: $$ (u^\mu) = \gamma (v) (c, \vec v)^T $$ wo $$ \vec v $$ die übliche Dreiergeschwindigkeit ist.

---

$$ u^\mu $$ hat die fixe Länge: $$ \mid u^\mu \mid^2 = \langle u, u \rangle \eta = u_\mu u^\mu = u^\nu u_\nu = \gamma^2 (v) [ c^2 - \vec v^2 ] \to \dfrac{1}{1-\beta^2} c^2 [1-\beta^2] = c^2 $$

Das Betragsquadrat beträgt immer $$c^2$$. 

Nochmalige Ableitung nach der Eigenzeit $$ \tau $$ ergibt Viererbeschleunigung:

$$ a^\mu := \dfrac{\rm d u^\mu}{\rm d \tau} = \gamma (v) \dfrac{\rm d u^\mu}{\rm d t} = \gamma (v) \dfrac{\rm d}{\rm dt} {\gamma (c, \vec v)^T)  $$ 


