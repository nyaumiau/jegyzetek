#### 1. Mit jelent az, hogy $a \in \mathbb{\overline{R}}$ torlódási pontja a $H \in \mathbb{R}$ halmaznak?
Azt mondjuk, hogy a $\emptyset \neq H \subset \mathbb{R}$ halmaznak a $a \in \mathbb{\overline{R}}$ *torlódási pontja*, ha az *a* minden környezete végtelen sok $H$-beli elemet tartalmaz, azaz:

$$\forall ε > 0 : K_{ε}(a) \cap H \text{ végtelen halmaz.}$$

A $H$ halmaz torlódási pontjainak halmazát $H'$-vel jelöljük.

#### 2. Környezetek segítségével adja meg a függvényhatárérték egységes definícióját!
Azt mondjuk, hogy az $f \in \mathbb{R} \rightarrow \mathbb{R}$ függvénynek az $a \in D'_f$ pontban van határértéke, ha:

$$\exists A \in \mathbb{\overline{R}} : \forall ε > 0 : \exists \delta > 0 : \forall x \in (K_{\delta}(a) \space \backslash \space \\{ a \\} ) \cap D_f : \space f(x) \in K_{ε}(A)$$

Ekkor $A$-t a függvény $a$-beli *határértékének* nevezzük és az alábbiak valamelyikével jelöljük:

$$\lim_{a} f = A , \quad \lim_{x \rightarrow a} f(x) = A, \quad f(x) \rightarrow A, \text{ ha } x \rightarrow a$$

#### 3. Adja meg egyenlőtlenségek segítségével a végesben vett véges határérték definícióját!
Legyen $f : \mathbb{R} \rightarrow \mathbb{R}$ függvény és $a \in \mathbb{R}$ és legyen $\lim\limits_{a} f = A$ . Ekkor, ha $A \in \mathbb{R}$ véges, valós szám, akkor: 

$$\forall ε > 0 : \exists \delta > 0 : \forall x \in D_f, \space 0<|x-a|<\delta : | f(x)-A | < ε.$$

#### 4. Adja meg egyenlőtlenségek segítségével a plusz végtelenben vett véges határérték definícióját!

Legyen $f : \mathbb{R} \rightarrow \mathbb{R}$ függvény és legyen $\lim\limits_{+\infty} f = A$ . Ekkor, ha $A \in \mathbb{R}$ véges, valós szám, akkor: 

$$\forall ε > 0 : \exists x_0 > 0 : \forall x \in D_f, x > x_0 : |f(x)-A| < ε.$$

#### 5. Írja le a határértékre vonatkozó átviteli elvet!
Legyen $f \in \mathbb{R} \rightarrow \mathbb{R}$ függvény, $a \in D'_f$ és $A \in \mathbb{\overline{R}}$ . Ekkor:

$$\lim_{a} f = A \space \Longleftrightarrow \space \forall (x_n) : \mathbb{N} \rightarrow D_f \space \backslash \space \\{a\\} , \lim_{n \rightarrow +\infty} x_n = a \text{ esetén } \lim_{n \rightarrow +\infty} f(x_n) = A.$$

#### 6. Hogyan szól a függvények hányadosának a határértékére vonatkozó tétel?
Tegyük fel, hogy $f,g \in \mathbb{R} \rightarrow \mathbb{R}$ és  $a \in (D_f \cap D_g)'$ és léteznek az $A := \lim\limits_{a} f \in \mathbb{\overline{R}}$ , $B := \lim\limits_{a} g \in \mathbb{\overline{R}}$ határértékek. Ekkor:

Az $f/g$ hányadosfüggvénynek is van határtértéke $a$-ban és 

$$\lim_{a} \dfrac{f}{g} = \dfrac{\lim\limits_{a}f}{\lim\limits_{a}g} = \dfrac{A}{B}$$ 

feltéve, hogy az $\dfrac{A}{B} \in \mathbb{\overline{R}}$ hányados értelmezve van.

#### 7. Definiálja függvény jobb oldali határértékét!
Legyen $f : \mathbb{R} \rightarrow \mathbb{R}.$ Tegyük fel, hogy $a \in \mathbb{R}$ és $a \in (D_f \cap (a, +\infty))'.$ Azt mondjuk, hogy az $f$ függvénynek az $a$ helyen (vagy $a$-ban) akkor *van jobb oldali határértéke, ha:*

$$\exists A \in \mathbb{\overline{R}} : \forall ε > 0 : \exists \delta > 0 : \forall x \in D_f, a < x < a + \delta : f(x) \in K_ε(A).$$

Ekkor $A$ egyértelmű, és ezt az $f$ függvény $a$-ban vett *jobb oldali határértékének* nevezzük, és az alábbiak valamelyikével jelöljük:

$$\lim_{a+0} f = A , \quad \lim_{x \rightarrow a+0} f(x) = A, \quad f(a+0) = A.$$
