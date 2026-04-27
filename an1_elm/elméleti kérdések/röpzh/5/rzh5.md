#### 1. Adja meg az $e$ számot definiáló sorozatot!

Az 

$$(a_n) := (1+\dfrac{1}{n})^n \space(n \in \mathbb{N}^+)$$ 

sorozat szigorúan monoton növekvő és felülről korlátos, tehát konvergens. Ekkor:

$$e:=\lim_{n \to \infty}(1+\dfrac{1}{n})^n.$$

#### 2. Fogalmazza meg a sorozatokra vonatkozó közrefogási elvet!
Tegyük fel, hogy az $(a_n), (b_n), (c_n)$ sorozatokra teljesülnek a következők:
- $\exists N \in \mathbb{N} : \forall n \gt N : a_n \leq b_n \leq c_n,$
- az $(a_n)$ és $(c_n)$ sorozatnak van határértéke, továbbá
  
$$\lim(a_n)=\lim(c_n)=A \in \overline{\mathbb{R}}$$

Ekkor a $(b_n)$ sorozatnak is van határértéke és $\lim(b_n) = A.$

#### 3. Milyen tételt ismer monoton sorozatok határértékével kapcsolatban?
Minden $(a_n)$ monoton sorozatnak van határértéke.
1. a) Ha $(a_n)$ monoton növekvő és felülről korlátos, akkor $(a_n)$ konvergens és: $$\lim(a_n)=\text{sup}\{a_n | n \in \mathbb{N}\}.$$

   b) Ha $(a_n)$ monoton csökkenő és alulról korlátos, akkor $(a_n)$ konvergens és $$\lim(a_n)=\text{inf}\{a_n | n \in \mathbb{N}\}.$$
3. a) Ha $(a_n)$ monoton növekvő és felülről nem korlátos, akkor $$\lim(a_n)=+\infty$$

   b) Ha $(a_n)$ monoton csökkenő és alulról nem korlátos, akkor $$\lim(a_n)=-\infty.$$


#### 4. Igaz-e az, hogy ha az $(a_n)$ és a $(b_n)$ sorozatoknak van határértéke és $a_n \gt b_n$ minden n-re, akkor $\lim(an) \gt \lim(bn)$ ?
Legyen $(a_n) := n+1, (b_n) := n.$ Ekkor: 

$$\forall n \in \mathbb{N}:a_n \gt b_n, \text{ viszont: } \lim(a_n)=\lim(b_n)=+\infty$$

Ezért az állítás hamis.

#### 5. Fogalmazza meg egy valós szám $m$-edik gyökének a létezésére vonatkozó tételt, és adjon olyan eljárást, amivel ezek a számok nagy pontossággal előállíthatók.
*Newton-féle iterációs eljárás m-edik gyökök keresésére*

Legyen $A \gt 0$ valós szám, $m \ge 2$ természetes szám. Ekkor az 

$$a_0 \in \mathbb{R}^+ \space , \space a_{n+1} := \dfrac{1}{m} \cdot (\dfrac{A}{a_n^{m-1}} + (m-1)a_n \space) \space , \space(n \in \mathbb{N})$$

rekurzióval értelmezett $(a_n)$ sorozat konvergens, és az $\alpha := \lim(a_n)$ határértékre igaz, hogy:

$$\alpha > 0 \text{ és } \alpha^m = A.$$

Ebből a tételből következik az, hogy minden pozitív valós számnak pontosan egy $m$-edik gyöke létezik a valós számok halmazán.

#### 6. Hogyan szól a Bolzano-Weierstrass-féle kiválasztási tétel?
Minden korlátos valós sorozatnak van konvergens részsorozata.

#### 7. Mikor nevez egy sorozatot Cauchy-sorozatnak?
Az $(a_n)$ valós sorozatot *Cauchy-sorozatnak* nevezzük, ha:

$$\forall ε \gt 0 : \exists n_0 \in \mathbb{N} : \forall m,n \gt n_0 : |a_n - a_m|<ε.$$

#### 8. Mi a kapcsolat a konvergens sorozatok és a Cauchy-sorozatok között?
**A Cauchy-féle konvergenciakritérium:**
Legyen $(a_n)$ egy valós sorozat. Ekkor:

$$(a_n) \text{ konvergens } \Longleftrightarrow (a_n) \text{ Cauchy-sorozat}.$$
