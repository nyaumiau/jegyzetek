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
