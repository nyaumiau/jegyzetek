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
