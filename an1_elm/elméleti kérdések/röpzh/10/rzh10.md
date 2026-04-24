#### 1. Mit tud mondani a hatványsor összegfüggvényének a határértékéről?
Tegyük fel, hogy a $\sum \alpha_n (x-a)^n$ hatványsor R konvergenciasugara pozitív. Jelölje

$$f(x):=\sum\limits_{n=0}^{+ \infty} \alpha_n (x-a)^n \space (x \in K_R (a))$$

az összegfüggvényét. Ekkor $\forall b \in K_R (a)$ pontban létezik a $\lim\limits_{x \rightarrow b} f(x)$ határérték, és

$$\lim\limits_{x \rightarrow b} f(x) = f(b) = \sum\limits_{n=0}^{+ \infty} \alpha_n (x-a)^n$$

#### 2. Mit tud mondani monoton függvények határértékéről?
Legyen $(\alpha , \beta) \subset \mathbb{R}$ tetszőleges (korlátos vagy nem korlátos) nyílt intervallum. Ha az $f$ függvény monoton $(\alpha , \beta)$-n, akkor $f$-nek $\forall a \in (\alpha , \beta)$ pontban létezik jobb és bal oldali határértéke és ezek végesek.

a) Ha $f$ monoton nő $(\alpha , \beta)$-n, akkor

$$\lim\limits_{a+0} f = \text{inf} \space \\{ \space f(x) | x \in (\alpha , \beta), \space x > a\\}$$

$$\lim\limits_{a-0} f = \text{sup} \space \\{ \space f(x) | x \in (\alpha , \beta), \space x < a\\}$$

b) Ha $f$ monoton csökken $(\alpha , \beta)$-n, akkor

$$\lim\limits_{a+0} f = \text{sup} \space \\{ \space f(x) | x \in (\alpha , \beta), \space x > a\\}$$

$$\lim\limits_{a-0} f = \text{inf} \space \\{ \space f(x) | x \in (\alpha , \beta), \space x < a\\}$$

#### 3. Definiálja egy $f \in \mathbb{R} \rightarrow \mathbb{R}$ függvény pontbeli folytonosságát!
Azt mondjuk, hogy az $f \in \mathbb{R} \rightarrow \mathbb{R}$ függvény folytonos az $a \in D_f$ pontban, ha

$$\forall ε \gt 0 : \exists \delta \gt 0 : \forall x \in D_f ,\space | x - a | \lt \delta : \space |f(x) - f(a)| < ε.$$

Jelölés: $f \in C\\{a\\}$

#### 4. Mi a kapcsolat a pontbeli folytonosság és a határérték között?
Legyen $f : \mathbb{R} \rightarrow \mathbb{R}.$ 
1. Ha $a \in D_f \space \backslash \space D'_f,$ azaz $a$ izolált pontja $D_f$-nek, akkor $f \in C\\{ a \\}.$
2. Ha $a \in D_f \space \cap \space D'_f,$ azaz $a$ torlódási pontja $D_f$-nek, akkor:

$$f \in C\\{ a \\} \space \Longleftrightarrow \space \exists \lim\limits_{a} f \text{ és } \lim\limits_{a} f = f(a).$$

#### 5. Írja le a folytonosságra vonatkozó átviteli elvet!
Tegyük fel, hogy $f \in \mathbb{R} \rightarrow \mathbb{R}$ és $a \in D_f.$ Ekkor:

$$f \in C\\{ a \\} \space \Longleftrightarrow \space \forall (x_n) : \mathbb{N} \rightarrow D_f, \lim\limits_{n \rightarrow +\infty} x_n = a \space : \space \lim\limits_{n \rightarrow +\infty}f(x_n) = f(a).$$

#### 6. Milyen tételt ismer hatványsor összegfüggvényének a folytonosságáról?
Minden hatványsor összegfüggvénye folytonos a hatványsor teljes konvergenciahalmazán.

#### 7. Milyen tételt ismer a folytonos függvények előjeltartásáról?
Tegyük fel, hogy az $f \in \mathbb{R} \rightarrow \mathbb{R}$ függvény folytonos az $a \in D_f$ pontban és $f(a) > 0.$ Ekkor:

$$\exists K(a) : \forall x \in (D_f \cap K(a)) : f(x) > 0$$

Azaz $f(a)$ előjelét egy alkalmas $K(a)$ környezetben felvett függvényértékek is öröklik.

#### 8. Mondja ki az összetett függvény folytonosságára vonatkozó tételt!
Tegyük fel, hogy $f, g \in \mathbb{R} \rightarrow \mathbb{R}, \space g \in C\\{a\\}$ és $f \in C\\{g(a)\\}.$ Ekkor $f \circ g \in C\\{a\\},$ azaz az összetett függvény örökli a belső és a külső függvény folytonosságát.
