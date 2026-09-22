#### 1. Mi a belső pont definíciója?
Legyen $\emptyset \neq A \subset \mathbb{R}.$ Az $a \in A$ pont az A halmaz belső pontja, ha:

$$\exists r \gt 0 : K_r(a)=(a-r,a+r) \subset A.$$

Jelölés: int $A := \\{ \space a \in A | a \space \text{belső pontja} \space A \text{-nak} \space \\}$


#### 2. Mikor mondja azt, hogy egy $f \in \mathbb{R} \rightarrow \mathbb{R}$ függvény differenciálható valamely $a ∈ int D_f$ pontban?

Az $f \in \mathbb{R} \rightarrow \mathbb{R}$ függvény az $a ∈ int D_f$ pontban **differenciálható** (vagy **deriválható**), ha:

$$\exists \space \text{ és véges a } \space \lim_{h \rightarrow 0} \dfrac{f(a+h) - f(a)}{h} \space \text{határérték}.$$

Ezt $f'(a)$ -val jelöljük, és az $f$ függvény $a$ **pontbeli deriváltjának** (vagy **differenciálhányadosának**) nevezzük, azaz

$$f'(a) := \lim_{h \rightarrow 0} \dfrac{f(a+h) - f(a)}{h} \in \mathbb{R}.$$

Ezt a tényt a következőképpen fogjuk jelölni: $f \in D \\{a\\}.$


#### 3. Mi a kapcsolat a pontbeli differenciálhatóság és a folytonosság között?

Tegyük fel, hogy $\space f \in \mathbb{R} \rightarrow \mathbb{R} \space$ és $\space a \in \text{int} D_f.$ Ekkor:

$$1.) \space f \in D \\{a\\} \Longrightarrow \space f \in C \\{a\\}$$

$$2.)\space \text{Az állítás megfordítása nem igaz.}$$

#### 4. Adjon példát olyan függvényre, ami az $\space a \in \mathbb{R}\space$ pontban folytonos, de nem differenciálható!

Példa: 

$$\text{abs}\in C\\{0\\},\space \text{de }\space \text{abs} \notin D\\{0\\},$$

mivel

$$\lim_{x \rightarrow 0^{+}} \dfrac{abs(x) - abs(0)}{x - 0} = \lim_{x \rightarrow 0^{+}} \dfrac{|x|}{x} = \lim_{x \rightarrow 0^{+}} \dfrac{x}{x} = \lim_{x \rightarrow 0^{+}} 1 = 1$$

$$\lim_{x \rightarrow 0^{-}} \dfrac{abs(x) - abs(0)}{x - 0} = \lim_{x \rightarrow 0^{-}} \dfrac{|x|}{x} = \lim_{x \rightarrow 0^{-}} \dfrac{-x}{x} = \lim_{x \rightarrow 0^{-}} -1 = -1$$

Mivel a bal és jobb oldali határértékek nem egyeznek meg, ezért az $a=0$ pontban nem létezik a határérték.

#### 5. Milyen tételt ismer két függvény szorzatának valamely pontbeli differenciálhatóságáról és a deriváltjáról?

Tegyük fel, hogy $f,g \in D\\{a\\}$ valamilyen $a \in \text{int}(D_f \cap D_g)$ pontban. Ekkor:

$$f \cdot g \in D_\\{a\\} \space \text{, és} \space (f \cdot g)'(a) = f'(a) \cdot g(a) + f(a) \cdot g'(a).$$

#### 6. Milyen tételt ismer két függvény hányadosának valamely pontbeli differenciálhatóságáról és a deriváltjáról?

Tegyük fel, hogy $f,g \in D\\{a\\}$ valamilyen $a \in \text{int}(D_f \cap D_g)$ pontban, valamint $g(a) \neq 0$. Ekkor:

$$\dfrac{f}{g} \in D_\\{a\\} \space \text{, és} \space (\dfrac{f}{g})'(a) = \dfrac{f'(a) \cdot g(a) - f(a) \cdot g'(a)}{g^{2}(a)}.$$

#### 7. Milyen tételt ismer két függvény kompozíciójának valamely pontbeli differenciálhatóságáról és a deriváltjáról?

Tegyük fel, hogy $f, g \in \mathbb{R} \rightarrow \mathbb{R}, R_g \subset D_f, \space$ és egy $a \in \text{int}D_g\space$ pontban $g\in D\\{a\\},$ valamint $f \in D\\{g(a)\\}.$ Ekkor $f \circ g \in D\\{a\\}, \space$ és 

$$(f \circ g)'(a) = f'(g(a)) \cdot g'(a)$$

#### 8. Mi az exp, sin, cos függvények deriváltfüggvénye?

Legyen:

$$\text{exp}x:=\sum_{n=0}^{+\infty} \dfrac{x^n}{n!} \space(x \in \mathbb{R})$$

$$\text{sin}x:=\sum_{n=0}^{+\infty} (-1)^n \dfrac{x^{2n+1}}{(2n+1)!} \space(x \in \mathbb{R})$$

$$\text{cos}x:=\sum_{n=0}^{+\infty} (-1)^n \dfrac{x^{2n}}{(2n)!} \space(x \in \mathbb{R})$$

Az exp, sin, cos függvények deriválhatóak és:

$$\text{exp}'(x) = (e^x)' = e^x \space (x \in \mathbb{R})$$

$$\text{sin}'(x) = cosx \space (x \in \mathbb{R})$$

$$\text{cos}'(x) = -sinx \space (x \in \mathbb{R})$$

#### 9. Milyen tételt ismer hatványsor összegfüggvényének differenciálhatóságáról és a deriváltjáról?

Tegyük fel, hogy a $\sum_{n=0} \alpha_n(x-a)^n \space(x \in \mathbb{R}) \space$ hatványsor R konvergenciasugara pozitív, és legyen 

$$f(x) := \sum_{n=0}^{+\infty} \alpha_n(x-a)^n \space(x \in K_R(a))$$

Ekkor minden $x \in K_R(a)$ pontban $f \in D\\{x\\},$ és 

$$f'(x) := \sum_{n=1}^{+\infty} n\alpha_n(x-a)^{n-1} \space(\forall x \in K_R(a))$$
