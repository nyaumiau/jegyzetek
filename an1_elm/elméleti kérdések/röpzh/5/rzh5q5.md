#### 5. Fogalmazza meg egy valós szám $m$-edik gyökének a létezésére vonatkozó tételt, és adjon olyan eljárást, amivel ezek a számok nagy pontossággal előállíthatók.
*Newton-féle iterációs eljárás m-edik gyökök keresésére*

Legyen $A \gt 0$ valós szám, $m \ge 2$ természetes szám. Ekkor az 

$$a_0 \in \mathbb{R}^+ \space , \space a_{n+1} := \dfrac{1}{m} \cdot (\dfrac{A}{a_n^{m-1}} + (m-1)a_n \space) \space , \space(n \in \mathbb{N})$$

rekurzióval értelmezett $(a_n)$ sorozat konvergens, és az $\alpha := \lim(a_n)$ határértékre igaz, hogy:

$$\alpha > 0 \text{ és } \alpha^m = A.$$

Ebből a tételből következik az, hogy minden pozitív valós számnak pontosan egy $m$-edik gyöke létezik a valós számok halmazán.
