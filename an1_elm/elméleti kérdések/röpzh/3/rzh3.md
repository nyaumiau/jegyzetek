#### 1. Mit ért azon, hogy egy számsorozat konvergens?

Azt mondjuk, hogy az $(a_n):\mathbb{N} \rightarrow \mathbb{R}$ sorozat konvergens, ha:

$$\exists A \in \mathbb{R} : \forall ε>0: \exists n_0 \in \mathbb{N} : \forall n \gt n_0 : |a_n - A| \lt ε.$$

Ekkor az $A$ számot a sorozat *határértékének* nevezzük, és az alábbi szimbólumok valamelyikével jelöljük: 

$$\lim(a_n):=A; \space \lim_{n \to \infty} a_n := A; \space a_n \rightarrow A (n \rightarrow +\infty).$$

Az $a_n$ sorozatot divergensnek nevezzük, ha nem konvergens.

#### 2. Mit ért azon, hogy egy számsorozat divergens?

Legyen $(a_n)$ tetszőleges számsorozat. Ekkor $(a_n)$ divergens, ha nem konvergens, azaz:

$$\nexists A \in \mathbb{R} : \forall ε>0: \exists n_0 \in \mathbb{N} : \forall n \gt n_0 : |a_n - A| \lt ε.$$

#### 3. Pozitív állítás formájában fogalmazza meg azt, hogy egy számsorozat divergens!

Legyen $(a_n)$ tetszőleges számsorozat. Ekkor $(a_n)$ divergens, ha: 

$$\forall A \in \mathbb{R} : \exists ε>0: \forall n_0 \in \mathbb{N} : \exists n \gt n_0 : |a_n - A| \ge ε.$$

#### 4. Milyen állítást ismer sorozatok esetén a konvergencia és a korlátosság kapcsolatáról?
Ha az $(a_n)$ sorozat konvergens, akkor korlátos is, viszont, ha $(a_n)$ korlátos, akkor nem feltétlenül konvergens. Azaz: 

$$(a_n) \text{ konvergens }\implies (a_n) \text{ korlátos}.$$

Vagyis egy sorozat konvergenciájának a korlátosság *szükséges, de nem elégséges* feltétele.

#### 5. Mit jelent az, hogy egy valós számsorozatnak $+\infty$ a határértéke?
Azt mondjuk, hogy az $(a_n)$ sorozat **határértéke $+\infty$** (vagyis a sorozat **$+\infty$-hez tart**), ha: 

$$\forall P \gt 0 : \exists n_0 \in \mathbb{N}: \forall n \gt n_0 : a_n > P.$$ 

Ezt az alábbi szimbólumok valamelyikével jelöljük: 

$$\lim(a_n):=+\infty; \space \lim_{n \to \infty} a_n := +\infty; \space a_n \rightarrow +\infty (n \rightarrow +\infty).$$

#### 6. Mit jelent az, hogy egy valós számsorozatnak $-\infty$ a határértéke?
Azt mondjuk, hogy az $(a_n)$ sorozat **határértéke $-\infty$** (vagyis a sorozat **$-\infty$-hez tart**), ha: 

$$\forall P \lt 0 : \exists n_0 \in \mathbb{N}: \forall n \gt n_0 : a_n < P.$$ 

Ezt az alábbi szimbólumok valamelyikével jelöljük:

$$\lim(a_n):=-\infty; \space \lim_{n \to \infty} a_n := -\infty; \space a_n \rightarrow -\infty (n \rightarrow + \infty).$$ 

#### 7. Környezetekkel fogalmazza meg azt, hogy az $(a_n)$ valós számsorozatnak (tágabb értelemben) van határértéke.
Azt mondjuk, hogy az $(a_n)$ sorozatnak *tágabb értelemben van határtértéke*, ha: 

$$\exists A \in \mathbb{\overline{R}} : \forall ε > 0 : \exists n_0 \in \mathbb{N} : \forall n \gt n_0 : a_n \in K_ε (A).$$

*Megjegyzés:*
- $\mathbb{\overline{R}}$ a végtelenekkel konjugált valós számok halmazát jelöli, azaz: $\mathbb{\overline{R}} = \mathbb{R} \space\cup\space \{-\infty,+\infty\}$.
- $K_ε (A)$ az $A \in \mathbb{\overline{R}}$ szám $ε$ sugarú körét jelöli.

#### 8. Hogyan definiálja egy sorozat részsorozatát?
Legyen $a = (a_n) : \mathbb{N} \rightarrow \mathbb{R}$ egy valós sorozat és $v = (v_n) : \mathbb{N} \rightarrow \mathbb{N}$ egy szigorúan monoton növekvő sorozat (röviden: $v_n$ *indexsorozat*). Ekkor az $a \circ v$ függvény is sorozat, amelyet az $(a_n)$ sorozat $v$ indexsorozat által meghatározott *részsorozatának* nevezünk. Az $a \circ v$ sorozat *n-edik tagja*: 

$$(a \circ v)(n) = a(v_n) = a_{v_n}, (n \in \mathbb{N}),$$

így: 

$$a \circ v = (a_{v_n}).$$
