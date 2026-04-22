#### 1. Mi a végtelen sor definíciója?
Az $(a_n) : \mathbb{N} \rightarrow \mathbb{R}$ sorozatból képzett 

$$s_n := a_0 + a_1 + a_2 + ... + a_n \space (n \in \mathbb{N})$$ 

sorozatot az $(a_n)$ által generált *végtelen sornak* (röviden *sornak*) nevezzük, és így jelöljük:

$$\sum a_n, \text{ vagy } \sum_{n=0}a_n, \text{ vagy } a_0 + a_1 + a_2 + ...$$ 

Ekkor azt mondjuk, hogy $s_n$ a $\sum a_n$ sor *n-edik részletösszege*, illetve $a_n$ a $\sum a_n$ sor *n-edik tagja*, ahol $n \in \mathbb{N}.$

#### 2. Mit jelent az, hogy a $\sum a_n$ végtelen sor konvergens, és hogyan értelmezzük az összegét?
Azt mondjuk, hogy a $\sum a_n$ sor *konvergens*, ha a részletösszegeinek az $(s_n)$ sorozata konvergens, és ha létezik és véges a $\lim(s_n)$ határérték. Ekkor ezt a határértéket a $\sum a_n$ *végtelen sor összegének* nevezzük és így jelöljük: 

$$\sum_{n=0}^{+\infty}a_n := \lim(s_n).$$ 

A $\sum a_n$ sor *divergens*, ha részletösszegekből képzett $(s_n)$ sorozat divergens. Ebben az esetben:
- $\lim (s_n) = +\infty$, azaz a $\sum a_n$ sor összege $+\infty,$ vagy
- $\lim (s_n) = -\infty$, azaz a $\sum a_n$ sor összege $-\infty,$ vagy
- $\lim (s_n)$ nem létezik, azaz a $\sum a_n$ sornak nincs határértéke.

A létező határértékek jelölései: $$\sum_{n=0}^{+\infty}a_n := +\infty\text{ , }\sum_{n=0}^{+\infty}a_n := -\infty$$

#### 3. Milyen tételt ismer $q \in \mathbb{R}$ esetén a $\sum\limits_{n=0} q^n$ geometriai sor konvergenciájáról?
Legyen $q \in \mathbb{R}.$ A $(q^n)$ sorozatból képzett $\sum\limits_{n=0} q^n$ *geometriai* vagy *mértani sor* akkor és csak akkor konvergens, ha $|q| < 1$ és ekkor az összege: 

$$\sum\limits_{n=0}^{+\infty} q^n = 1 + q + q^2 + q^3 + ... = \dfrac{1}{1-q} \space (|q| < 1).$$

Ha $q \geq 1,$ akkor a $\sum\limits_{n=0}q^n$ sornak van összege és $\sum\limits_{n=0}^{+\infty} q^n = +\infty.$

#### 4. Mi a teleszkopikus sor, és milyen állítást ismer a konvergenciájával kapcsolatban?
A $\sum\limits_{n=1} \dfrac{1}{n(n+1)}$ *teleszkopikus sor* konvergens és összege 1, azaz: 

$$\sum\limits_{n=1}^{+\infty} \dfrac{1}{n(n+1)} = \dfrac{1}{1 \cdot 2} + \dfrac{1}{2 \cdot 3} + \dfrac{1}{3 \cdot 4} + ... = 1.$$

#### 5. Mi a harmonikus sor, és milyen állítást ismer a konvergenciájával kapcsolatban?
A $\sum\limits_{n=1} \dfrac{1}{n}$ formájú sort *harmonikus sornak* nevezzük. A $\sum\limits_{n=1}^{+\infty} \dfrac{1}{n}$ összeg divergens, valamint: 

$$\sum\limits_{n=1}^{+\infty} \dfrac{1}{n} = 1 + \dfrac{1}{2} + \dfrac{1}{3} + ... = +\infty$$

#### 6. Igaz-e az, hogy ha $\lim(a_n) = 0$, akkor a $\sum a_n$ sor konvergens? (A válaszát indokolja meg!)
Az, hogy az $(a_n)$ sorozat nullsorozat, a $\sum a_n$ sor konvergenciájának *szükséges, de nem elégséges* feltétele.
Ellenpélda: Legyen $(a_n):=\dfrac{1}{n}.$ Ekkor $\lim (a_n) = 0$, viszont a $\sum\limits_{n=1}^{+\infty}a_n$ sor divergens.

Azaz az állítás hamis.
