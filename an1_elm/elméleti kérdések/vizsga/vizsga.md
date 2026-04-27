#### 1. Hogyan értelmezi a függvényt?
Legyen $A$ és $B$ tetszőleges nemüres halmaz. A:
$\emptyset \neq f \subset A \times B$ hozzárendelést **függvénynek** nevezzük, ha: 

$$\forall x \in D_f : \exists!\space y \in R_f : (x,y) \in f.$$ 

Az $y$ elemet az $f$ függvény $x$ helyen felvett *helyettesítési értékének* nevezzük és $f(x)$-el jelöljük. 
Ekkor azt is mondjuk, hogy az $f$ függvény $x$-hez az $f(x)$ értéket *rendeli*.

*Megjegyzés:* A " $\exists !$ " azt jelenti, hogy *csak egy létezik*.

#### 2.  Mit jelent az $f \in A \rightarrow B$ szimbólum?
Legyenek $A, B$ nemüres halmazok. Ekkor az $f \in A \rightarrow B$ jelölés azt jelenti, hogy:
 $f$ egy olyan függvény, ahol $D_f = A$ és $R_f \subset B$, azaz: $f$ leképez az $A$ halmazról a $B$ halmaz egy részhalmazára.

#### 3. Mit jelent az $f : A \rightarrow B$ szimbólum?

Legyenek $A, B$ nemüres halmazok. Ekkor az $f : A \rightarrow B$ jelölés azt jelenti, hogy: 
 $f$ egy olyan függvény, ahol $D_f = A$ és $R_f = B$, azaz: $f$ leképez az $A$ halmazról a $B$ halmazra.

#### 4. Mikor nevez egy függvényt invertálhatónak (vagy injektívnek)?
Akkor mondjuk, hogy egy $f : A \rightarrow B$ függvény invertálható (más néven injektív), ha az $A = D_f$ halmaz bármely két különböző pontjának a képe különböző. 

Ezt három különböző módon is le lehet írni: 
- $f$ invertálható $\Longleftrightarrow \forall x,t \in D_f : x \neq t \implies f(x) \neq f(t)$;
- $f$ invertálható $\Longleftrightarrow \forall x,t \in D_f : f(x)=f(t) \implies x = t$;
- $f$ invertálható $\Longleftrightarrow \forall y \in R_f : \exists!\space x \in D_f : f(x)=y$.

#### 5. Definiálja az inverz függvényt!

Legyen $f : A \rightarrow B$ injektív függvény. Ekkor $f$ inverz függvényét (röviden inverzét) így értelmezzük:

$$f^{-1} : R_f \ni y \mapsto x \space : \space f(x)=y$$

#### 6. Mit mond ki a Dedekind-axióma vagy szétválasztási axióma?
Tegyük fel, hogy az $A, B \subset \mathbb{R}$ halmazokra a következők teljesülnek:
- $A \neq \emptyset$  és $B \neq \emptyset$
- minden $a \in A$ és minden $b \in B$ elemre $a \leq b$.

Ekkor:

$$\exists \xi \in \mathbb{R} : \forall a \in A, b \in B : a \leq \xi \leq b .$$

#### 7. Mikor mondjuk azt, hogy egy H ⊂ R halmaz induktív? Adjon egy példát induktív halmazra!

#### 8. Mondja ki tétel formájában a teljes indukció elvét!

#### 9. Mikor nevez egy ∅ ̸= A ⊂ R halmazt felülről korlátosnak?

#### 10.  Írja le pozitív formában azt, hogy egy $\emptyset \neq A \subset \mathbb{R}$ halmaz felülről nem korlátos?
Legyen $A \subset \mathbb{R}$ nemüres számhalmaz. Ekkor $A$ akkor és csak akkor felülről nem korlátos, ha:

$$\forall K \subset \mathbb{R} : \exists x \in A : x \gt K.$$

#### 11.  Fogalmazza meg egyenlőtlenségekkel azt a tényt, hogy egy $\emptyset \neq A \subset \mathbb{R}$ halmaz korlátos!
Egy $\emptyset \neq A \subset \mathbb{R}$ számhalmaz akkor és csak akkor korlátos (azaz alulról és felülről is korlátos), ha:

$$\exists K \subset \mathbb{R} : \forall x \in A : | x | \leq K;$$vagy:
$$\exists K \subset \mathbb{R} : \forall x \in A : -K \leq x \leq K.$$

#### 12. Fogalmazza meg a szuprémum elvet!
Legyen $\ H \subset \mathbb{R}$ és tegyük fel, hogy: 
1. $H \neq \emptyset$ *és*
2. $H$ *felülről korlátos.* 

*Ekkor:*

$\exists \min \\{ K \in \mathbb{R} \space | \space K$ *felső korlátja* $H$ *-nak* $\\}.$

#### 13.  Mi a szuprémum definíciója?
A felülről korlátos $\emptyset \neq H \subset \mathbb{R}$ számhalmaz legkisebb felső korlátját $H$ **szuprémumának** nevezzük, és sup $H$ -val jelöljük.

#### 14. Fogalmazza meg egyenlőtlenségekkel azt a tényt, hogy $\xi =$ sup $H \in \mathbb{R}$ !
Legyen $\emptyset \neq H \subset \mathbb{R}$ *felülről korlátos* halmaz. Ekkor:

$\xi =$ sup $H \Longleftrightarrow$ A következő állításokkal: 
1. $\xi$ *felső korlát, azaz:* $\forall x \in H : x \leq \xi$
2. $\xi$ *a legkisebb felső korlát, azaz:* $\forall ε \gt 0 : \exists x \in H : \xi-ε \lt x$.

#### 15. Mi az infimum definíciója?
Az alulról korlátos $\emptyset \neq H \subset \mathbb{R}$ számhalmaz legnagyobb alsó korlátját $H$ **infimumának** nevezzük, és inf $H$-val jelöljük.

#### 16. Fogalmazza meg egyenlőtlenségekkel azt a tényt, hogy $\xi =$ inf $H \in \mathbb{R}$ !
Legyen $\emptyset \neq H \subset \mathbb{R}$ *alulról korlátos* halmaz. Ekkor:

$\xi =$ inf $H \Longleftrightarrow$ A következő állításokkal: 
1. $\xi$ *alsó korlát, azaz:* $\forall x \in H : x \geq \xi$
2. $\xi$ *a legnagyobb alsó korlát, azaz:* $\forall ε \gt 0 : \exists x \in H : \xi+ε \gt x$.

#### 17. Mi a kapcsolat egy halmaz maximuma és a szuprémuma között?

Legyen $H \subset \mathbb{R}$.

$$\exists \text{max} H \space\space\Longleftrightarrow\space\space \sup H \in H \text{ , és ekkor: sup} H = \text{max} H.$$

#### 18. Mi a kapcsolat egy halmaz minimuma és a infimuma között?

Legyen $H \subset \mathbb{R}$ .

$$\exists \text{min} H \space\space\Longleftrightarrow\space\space \inf H \in H \text{ , és ekkor: inf} H = \text{min} H.$$

#### 19. Írja le az arkhimédészi tulajdonságot!

#### 20. Mit állít a Cantor-tulajdonság?

#### 21. Definiálja a halmaznak függvény által létesített képét!
Legyen $f : A \rightarrow B$ egy adott függvény és $C \subset A$. Ekkor a $C$ *halmaz* $f$ *által létesített képén* az:

$$f [C]:= \\{ \space f(x) \space|\space x \in C \space \\} = \\{ \space y \in B \space | \space \exists x \in C : y = f(x) \space \\} \subset B$$

halmazt értjük.
Megállapodunk abban, hogy $f[\emptyset] = \emptyset.$

#### 22. Definiálja a halmaznak függvény által létesített ősképét!
Legyen $f : A \rightarrow B$ egy adott függvény és $D \subset B$. Ekkor a $D$ *halmaz* $f$ *által létesített ősképén* az:

$$f^{-1}[D]:= \\{ \space x \in D_f \space | \space f(x) \in D \space \\} \subset A$$ 

halmazt értjük.
Megállapodunk abban, hogy $f^{-1}[\emptyset] = \emptyset$.

#### 23. Mi a definíciója az összetett függvénynek?

Tegyük fel, hogy $f : A \rightarrow B$ és $g : C \rightarrow D$ olyan függvények, amelyekre:

$$\\{\space x \in D_g \space  | \space g(x) \in D_f \space \\} \neq \emptyset.$$

Ebben az esetben az $f$ (*külső*) és $g$ (*belső*) függvény *összetett függvényét* (vagy más szóval $f$ és $g$ *kompozícióját*) $f \circ g$ -vel jelöljük és így értelmezzük:

$$f \circ g := \\{ \space x \in D_g \space  | \space g(x) \in D_f \space \\} \rightarrow B, \space \space \space f \circ g(x) := f(g(x)).$$
