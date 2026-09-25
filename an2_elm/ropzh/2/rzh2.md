#### 1. Írja fel az $\space \text{exp},\space \text{ln},\space \text{sin},\space \text{cos},\space \text{tg},\space a^x\space (a > 0, x ∈ \mathbb{R})\space$ függvények deriváltfüggvényét.

$$(\text{exp}(x))' = (e^x)' = e^x = \text{exp}(x)$$

$$(\text{ln}(x))' = \dfrac{1}{x}$$

$$(\text{sin}(x))' = \text{cos}(x)$$

$$(cos(x))' = -sin(x)$$

$$(\text{tg}(x))' = \dfrac{1}{\text{cos}^2(x)}$$

$$(a^x)' = (e^{x\text{ln}(a)}) = e^{x\text{ln}(a)}\text{ln}(a) = a^x\text{ln}(a)$$

#### 2. Milyen ekvivalens átfogalmazást ismer a pontbeli deriválhatóságra lineáris közelítéssel?

Legyen $f \in \mathbb{R} \rightarrow \mathbb{R} \space \text{és} \space a \in \text{int}D_f.$ Ekkor

$$f \in \text{D}\\{a\\} \Longleftrightarrow \exists A \in \mathbb{R} \text{ és } \exists \epsilon : D_f \rightarrow \mathbb{R}, \lim_{a} \epsilon = 0 : f(x)-f(a) = A \cdot (x-a) + \epsilon (x) (x-a)$$

és $A = f'(a).$

#### 3. Mi az érintő definíciója?

Az $f \in \mathbb{R} \rightarrow \mathbb{R}$ függvény grafikonjának az $(a,f(a))$ pontban van érintője, ha $f \in \text{D}\\{a\\}.$ Az f függvény grafikonjának $(a,f(a))$ pontbeli érintőjén az 

$$y = f'(a) \cdot (x-a) + f(a)$$

egyenletű egyenest értjük.

#### 4. Írja le az inverz függvény differenciálhatóságáról szóló tételt!

Legyen $\text{I} \subset \mathbb{R}$ nyílt intervallum és $f : \text{I} \rightarrow \mathbb{R}.$ Tegyük fel, hogy:

$$\text{a) f szigorúan monoton és folytonos I-n}$$

$$\text{b) egy } a \in \text{ I pontban } f \in \text{D}\\{a\\} \text{ és } f'(a) \neq 0.$$

Ekkor az $f^{-1}$ inverz függvény differenciálható a $b := f(a)$ pontban, és:

$$(f^{-1})'(b)=\dfrac{1}{f'(a)} = \dfrac{1}{f'(f^{-1}(b))}$$
