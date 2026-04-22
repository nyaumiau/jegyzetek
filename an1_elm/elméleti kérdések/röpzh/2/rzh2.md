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

#### 4. Definiálja a halmaznak függvény által létesített képét!
Legyen $f : A \rightarrow B$ egy adott függvény és $C \subset A$. Ekkor a $C$ *halmaz* $f$ *által létesített képén* az:

$$f [C]:= \{f(x) \space|\space x \in C \} = \{y \in B \space | \space \exists x \in C : y = f(x) \} \subset B$$

halmazt értjük.
Megállapodunk abban, hogy $f[\emptyset] = \emptyset.$

#### 5. Definiálja a halmaznak függvény által létesített ősképét!
Legyen $f : A \rightarrow B$ egy adott függvény és $D \subset B$. Ekkor a $D$ *halmaz* $f$ *által létesített ősképén* az:

$$f^{-1}[D]:= \{x \in D_f \space | \space f(x) \in D\} \subset A$$ 

halmazt értjük.
Megállapodunk abban, hogy $f^{-1}[\emptyset] = \emptyset$.

#### 6. Mikor nevez egy függvényt invertálhatónak (vagy injektívnek)?
Akkor mondjuk, hogy egy $f : A \rightarrow B$ függvény invertálható (más néven injektív), ha az $A = D_f$ halmaz bármely két különböző pontjának a képe különböző. 

Ezt három különböző módon is le lehet írni: 
- $f$ invertálható $\Longleftrightarrow \forall x,t \in D_f : x \neq t \implies f(x) \neq f(t)$;
- $f$ invertálható $\Longleftrightarrow \forall x,t \in D_f : f(x)=f(t) \implies x = t$;
- $f$ invertálható $\Longleftrightarrow \forall y \in R_f : \exists!\space x \in D_f : f(x)=y$.

#### 7. Definiálja az inverz függvényt!

Legyen $f : A \rightarrow B$ injektív függvény. Ekkor $f$ inverz függvényét (röviden inverzét) így értelmezzük:

$$f^{-1} : R_f \rightarrow D_f,\space f^{-1}(y)=x ,$$

amerre: $f(x)=y $.

#### 8. Mi a definíciója az összetett függvénynek?

Tegyük fel, hogy $f : A \rightarrow B$ és $g : C \rightarrow D$ olyan függvények, amelyekre:

$$\{x \in D_g \space  | \space g(x) \in D_f\} \neq \emptyset.$$

Ebben az esetben az $f$ (*külső*) és $g$ (*belső*) függvény *összetett függvényét* (vagy más szóval $f$ és $g$ *kompozícióját*) $f \circ g$ -vel jelöljük és így értelmezzük:

$$f \circ g : \{x \in D_g \space  | \space g(x) \in D_f\} \rightarrow B, \space \space \space f \circ g(x) := f(g(x)).$$
