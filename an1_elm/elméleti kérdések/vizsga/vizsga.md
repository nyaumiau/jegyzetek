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

#### 24. Mi a definíciója a sorozatnak?

#### 25. Mit ért azon, hogy egy valós sorozat felülről korlátos?

#### 26. Pozitív állítás formájában fogalmazza meg azt, hogy egy valós sorozat felülről nem korlátos!

#### 27. Fogalmazza meg egyenlőtlenségekkel azt a tényt, hogy egy valós számsorozat korlátos!

#### 28. Mikor mondja azt, hogy egy valós sorozat monoton növő?

#### 29. Mikor mondja azt, hogy egy valós sorozat szigorúan monoton növő?

#### 30. Mikor mondja azt, hogy egy valós sorozat monoton csökkenő?

#### 31. Mikor mondja azt, hogy egy valós sorozat szigorúan monoton csökkenő?

#### 32. Adja meg az a ∈ R középpontú r > 0 sugarú környezet fogalmát!

#### 33. Adja meg a +∞ elem r > 0 sugarú környezetének a fogalmát!

#### 34. Adja meg a −∞ elem r > 0 sugarú környezetének a fogalmát!

#### 35. Mit ért azon, hogy egy számsorozat konvergens?

Azt mondjuk, hogy az $(a_n):\mathbb{N} \rightarrow \mathbb{R}$ sorozat konvergens, ha:

$$\exists A \in \mathbb{R} : \forall ε>0: \exists n_0 \in \mathbb{N} : \forall n \gt n_0 : |a_n - A| \lt ε.$$

Ekkor az $A$ számot a sorozat *határértékének* nevezzük, és az alábbi szimbólumok valamelyikével jelöljük: 

$$\lim(a_n):=A; \space \lim_{n \to \infty} a_n := A; \space a_n \rightarrow A (n \rightarrow +\infty).$$

Az $a_n$ sorozatot divergensnek nevezzük, ha nem konvergens.

#### 36. Mit ért azon, hogy egy számsorozat divergens?

Legyen $(a_n)$ tetszőleges számsorozat. Ekkor $(a_n)$ divergens, ha nem konvergens, azaz:

$$\nexists A \in \mathbb{R} : \forall ε>0: \exists n_0 \in \mathbb{N} : \forall n \gt n_0 : |a_n - A| \lt ε.$$

#### 37. Pozitív állítás formájában fogalmazza meg azt, hogy egy számsorozat divergens!

Legyen $(a_n)$ tetszőleges számsorozat. Ekkor $(a_n)$ divergens, ha: 

$$\forall A \in \mathbb{R} : \exists ε>0: \forall n_0 \in \mathbb{N} : \exists n \gt n_0 : |a_n - A| \ge ε.$$

#### 38. Milyen állítást ismer sorozatok esetén a konvergencia és a korlátosság kapcsolatáról?
Ha az $(a_n)$ sorozat konvergens, akkor korlátos is, viszont, ha $(a_n)$ korlátos, akkor nem feltétlenül konvergens. Azaz: 

$$(a_n) \text{ konvergens }\implies (a_n) \text{ korlátos}.$$

Vagyis egy sorozat konvergenciájának a korlátosság *szükséges, de nem elégséges* feltétele.

#### 39. Mit jelent az, hogy egy valós számsorozatnak $+\infty$ a határértéke?
Azt mondjuk, hogy az $(a_n)$ sorozat **határértéke $+\infty$** (vagyis a sorozat **$+\infty$-hez tart**), ha: 

$$\forall P \gt 0 : \exists n_0 \in \mathbb{N}: \forall n \gt n_0 : a_n > P.$$ 

Ezt az alábbi szimbólumok valamelyikével jelöljük: 

$$\lim(a_n):=+\infty; \space \lim_{n \to \infty} a_n := +\infty; \space a_n \rightarrow +\infty (n \rightarrow +\infty).$$

#### 40. Mit jelent az, hogy egy valós számsorozatnak $-\infty$ a határértéke?
Azt mondjuk, hogy az $(a_n)$ sorozat **határértéke $-\infty$** (vagyis a sorozat **$-\infty$-hez tart**), ha: 

$$\forall P \lt 0 : \exists n_0 \in \mathbb{N}: \forall n \gt n_0 : a_n < P.$$ 

Ezt az alábbi szimbólumok valamelyikével jelöljük:

$$\lim(a_n):=-\infty; \space \lim_{n \to \infty} a_n := -\infty; \space a_n \rightarrow -\infty (n \rightarrow + \infty).$$ 

#### 41. Környezetekkel fogalmazza meg azt, hogy az $(a_n)$ valós számsorozatnak (tágabb értelemben) van határértéke.
Azt mondjuk, hogy az $(a_n)$ sorozatnak *tágabb értelemben van határtértéke*, ha: 

$$\exists A \in \mathbb{\overline{R}} : \forall ε > 0 : \exists n_0 \in \mathbb{N} : \forall n \gt n_0 : a_n \in K_ε (A).$$

*Megjegyzés:*
- $\mathbb{\overline{R}}$ a végtelenekkel konjugált valós számok halmazát jelöli, azaz: $\mathbb{\overline{R}} = \mathbb{R} \space\cup\space \{-\infty,+\infty\}$.
- $K_ε (A)$ az $A \in \mathbb{\overline{R}}$ szám $ε$ sugarú körét jelöli.

#### 42. Hogyan definiálja egy sorozat részsorozatát?
Legyen $a = (a_n) : \mathbb{N} \rightarrow \mathbb{R}$ egy valós sorozat és $v = (v_n) : \mathbb{N} \rightarrow \mathbb{N}$ egy szigorúan monoton növekvő sorozat (röviden: $v_n$ *indexsorozat*). Ekkor az $a \circ v$ függvény is sorozat, amelyet az $(a_n)$ sorozat $v$ indexsorozat által meghatározott *részsorozatának* nevezünk. Az $a \circ v$ sorozat *n-edik tagja*: 

$$(a \circ v)(n) = a(v_n) = a_{v_n}, (n \in \mathbb{N}),$$

így: 

$$a \circ v = (a_{v_n}).$$
