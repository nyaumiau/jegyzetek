#### 1.) Mit ért azon, hogy az $f \in \mathbb{R} \rightarrow \mathbb{R}$ függvénynek valamely helyen lokális minimuma van?
Az $f$ függvénynek az $a \in \text{int}D_f$ pontban lokális minimuma van, ha 

$$ \exists K(a) \subset D_f : \forall x \in K(a) : f(x) \geq f(a).$$

Az $a \in \text{int} D_f$ pont $f$ lokális minimumhelye, $f(a)$ pedig $f$ lokális minimuma.

#### 2.) Mit ért azon, hogy az $f \in \mathbb{R} \rightarrow \mathbb{R}$ függvénynek valamely helyen lokális maximuma van?
Az $f$ függvénynek az $a \in \text{int}D_f$ pontban lokális maximuma van, ha 

$$ \exists K(a) \subset D_f : \forall x \in K(a) : f(x) \leq f(a).$$

Az $a \in \text{int} D_f$ pont $f$ lokális maximumhelye, $f(a)$ pedig $f$ lokális maximuma.

#### 3.) Hogyan szól a lokális szélsőértékre vonatkozó elsőrendű szükséges feltétel?
Tegyük fel, hogy az $f$ függvénynek az $a \in \text{int} D_f$ pontban lokális szélsőértéke van és $f \in D\\{a\\}.$ Ekkor:

$$f'(a) = 0$$

#### 4.) Adjon példát olyan $f \in \mathbb{R} \rightarrow \mathbb{R}$ függvényre, amelyre valamely $a \in \mathbb{R}$ esetén $f \in D\\{a\\}, f'(a)=0$ teljesül, de az $f$ függvénynek az $a$ pontban nincs lokális szélsőértéke! 
Az $f(x):=x^3$ függvény esetén:

1.) $f$ polinomfüggvény, így deriválható $\mathbb{R}$-en, így az $a = 0$ pontban is

2.) $(x^3)' = 3x^2 \rightarrow a = 0$ esetén $3 \cdot 0^2 = 0 \space \checkmark$

De $f$ szigorúan monoton növekvő $\mathbb{R}$-en, így az $a = 0$ pontban nem lehet lokális szélsőértéke.

#### 5.) Milyen szükséges és elégséges feltételt ismer differenciálható függvény monoton növekedésével kapcsolatban?
Legyen $(a,b) \subset \mathbb{R}\space$ egy **nyílt intervallum**. Tegyük fel, hogy $f \in D(a,b).$ Ekkor:

$$f \text{ monoton növekvő } \space (a,b)\text{-n } \Longleftrightarrow f' \geq 0 \space (a,b)\text{-n }$$

#### 6.) Milyen elégséges feltételt ismer differenciálható függvény szigorú monoton növekedésével kapcsolatban?
Legyen $(a,b) \subset \mathbb{R}\space$ egy **nyílt intervallum**. Tegyük fel, hogy $f \in D(a,b).$ Ekkor:

$$f' \gt 0 \space (a,b)\text{-n } \Longrightarrow f \text{ szigorúan monoton nő } (a,b)\text{-n }$$

#### 7.) Milyen szükséges és elégséges feltételt ismer differenciálható függvény szigorú monoton növekedésével kapcsolatban?
Legyen $(a,b) \subset \mathbb{R}\space$ egy **nyílt intervallum**. Tegyük fel, hogy $f \in D(a,b).$ Ekkor:

$$f \text{ szigorúan monoton } \space (a,b)\text{-n } \Longleftrightarrow f' \geq 0 \text{ , és } \space (a,b) \text{ -nek nincsen olyan részintervalluma, ahol } f' \text{ azonosan } 0.$$

#### 8.) Mit ért azon, hogy egy függvény valamely helyen jelet vált?
Azt mondjuk, hogy a $h$ függvény a $c \in \text{int}D_h$ pontban negatívból pozitívba megy át (h-nak c-ben $(-,+)$ előjelváltása van), ha:

$$h(c) = 0 \space \text{ és } \space \exists \delta \gt 0 : h(x) \lt 0 \text{ , ha  } \space x \in (c-\delta, c) \text{ és } h(x) \gt 0 \text{ , ha  } \space x \in (c, c+\delta).$$

A $(+,-)$ előjelváltást hasonlóan értelmezzük.

Azt mondjuk, hogy a $h$ függvény $c$-ben előjelet vált, ha $h$-nak $c$-ben $(-,+)$ vagy $(+,-)$ előjelváltása van.

#### 9.) Hogyan szól a lokális minimumra vonatkozó elsőrendű elégséges feltétel?
Legyen $-\infty \lt a \lt b \lt +\infty$ és $f:(a,b) \rightarrow \mathbb{R}.$ Tegyük fel, hogy:

$$1.) f \in D(a,b)$$
$$2.) \text{ egy } c \in (a,b) \text{ pontban } f'(c) = 0.$$
$$3.) \text{ az } f' \text{deriváltfüggvény előjelet vált } c \text{-ben}.$$

Ekkor, ha az $f$ függvénynek $c$-ben $(-,+)$ előjelváltása van, akkor $c$ az $f$ függvény szigorú lokális minimumhelye.

#### 10.) Hogyan szól a lokális maximumra vonatkozó elsőrendű elégséges feltétel?
Legyen $-\infty \lt a \lt b \lt +\infty$ és $f:(a,b) \rightarrow \mathbb{R}.$ Tegyük fel, hogy:

$$1.) f \in D(a,b)$$
$$2.) \text{ egy } c \in (a,b) \text{ pontban } f'(c) = 0.$$
$$3.) \text{ az } f' \text{deriváltfüggvény előjelet vált } c \text{-ben}.$$

Ekkor, ha az $f$ függvénynek $c$-ben $(+,-)$ előjelváltása van, akkor $c$ az $f$ függvény szigorú lokális maximumhelye.

#### 11.) Írja le a lokális minimumra vonatkozó másodrendű elégséges feltételt!
Legyen $-\infty \lt a \lt b \lt +\infty, f:(a,b) \rightarrow \mathbb{R}$ és $c \in (a,b).$ Tegyük fel, hogy:

$$1.) f \in D^2\\{c\\}$$
$$2.) f'(c) = 0$$
$$3.) f''(c) \neq 0$$

Ekkor, ha $f''(c) \gt 0$, akkor $c$ az $f$ függvénynek szigorú lokális minimumhelye.

#### 12.) Írja le a lokális maximumra vonatkozó másodrendű elégséges feltételt!
Legyen $-\infty \lt a \lt b \lt +\infty, f:(a,b) \rightarrow \mathbb{R}$ és $c \in (a,b).$ Tegyük fel, hogy:

$$1.) f \in D^2\\{c\\}$$
$$2.) f'(c) = 0$$
$$3.) f''(c) \neq 0$$

Ekkor, ha $f''(c) \lt 0$, akkor $c$ az $f$ függvénynek szigorú lokális maximumhelye.

#### 13.) Fogalmazza meg a Weierstrass-tételt!
Korlátos és zárt $[a,b] \subset \mathbb{R}$ intervallumon folytonos függvénynek léteznek abszolút szélsőértékei, azaz

$$\exists \alpha, \beta \in [a,b] : \forall x \in [a,b] : f(\beta) \leq f(x) \leq f(\alpha).$$
