#### 1. Definiálja a megszüntethető szakadási hely fogalmát!
Az $a \in D_f$ pont az $f$ függvény *megszüntethető szakadási helye*, ha:

$$\exists \lim_{a} f \text{ véges határérték, de } \lim_{a} f \neq f(a).$$

#### 2. Definiálja az elsőfajú szakadási hely fogalmát!
Az $a \in D_f$ pont az $f$ függvény *elsőfokú szakadási helye* (vagyis $f$-nek *ugrása van* $a$-ban), ha:

$$\exists \lim_{a+0} f \text{ és } \exists \lim_{a-0} f \text{ , ezek végesek, de } \lim_{a+0} f \neq \lim_{a-0} f.$$

#### 3. Mit tud mondani korlátos és zárt intervallumon értelmezett folytonos függvény értékkészletéről?
Egy korlátos és zárt intervallumon értelmezett folytonos függvény értékkészlete is korlátos.

#### 4. Hogyan szól a Weierstrass-tétel?
Egy korlátos és zárt intervallumon értelmezett folytonos függvénynek mindig van abszolút maximum- és minimumhelye, azaz:

$$f \in [a;b] \space \Longrightarrow \space \exists \alpha, \beta \in [a;b] : \forall x \in [a;b] : f(\beta) \leq f(x) \leq f(\alpha).$$

#### 5. Mit mond ki a Bolzano-tétel?
Ha egy korlátos és zárt intervallumon értelmezett folytonos függvény az intervallum két végpontjában különböző előjelű, akkor a függvénynek legalább egy zérushelye van, azaz: 

$$f \in C[a;b] \text{ és } f(a) \cdot f(b) \lt 0 \space \Longrightarrow \space \exists \xi \in (a;b) \space : \space f(\xi) = 0.$$

#### 6. Mit jelent az, hogy egy függvény Darboux-tulajdonságú?
Legyen $I \subset \mathbb{R}$ tetszőleges intervallum. Azt mondjuk, hogy az $f \in \mathbb{R} \rightarrow \mathbb{R}$ függvény *Darboux-tulajdonságú* az $I$ intervallumon, ha minden $a,b \in I, \space a < b, \space f(a) \neq f(b)$ esetén az $f$ függvény minden $f(a)$ és $f(b)$ közötti értéket felvesz $(a;b)$-ben.

#### 7. Hogy szól az inverz függvény folytonosságára vonatkozó tétel?
Minden korlátos és zárt intervallumon értelmezett folytonos és invertálható függvény esetén az inverz függvény is folytonos, azaz:

$$f : [a;b] \rightarrow \mathbb{R}, \space f \in C[a;b], \space \exists f^{-1} \space \Longrightarrow \space f^{-1} \in C(R_f).$$
