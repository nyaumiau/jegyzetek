#### 1.) Mi a konvex függvény definíciója?
Azt mondjuk, hogy az $f : I \rightarrow \mathbb{R}$ függvény konvex az $I$ intervallumon, ha:

$$\forall a,b \in I, a < b : f(x) \leq \dfrac{f(b)-f(a)}{b-a}(x-a) + f(a).$$

Ha az állításban $\leq$ helyett $\lt$ áll, akkor az $f$ függvány szigúran konvex az $I$ intervallumon.

#### 2.) Mi a konkáv függvény definíciója?
Azt mondjuk, hogy az $f : I \rightarrow \mathbb{R}$ függvény konkáv az $I$ intervallumon, ha:

$$\forall a,b \in I, a < b : f(x) \geq \dfrac{f(b)-f(a)}{b-a}(x-a) + f(a).$$

Ha az állításban $\geq$ helyett $\gt$ áll, akkor az $f$ függvány szigúran konkáv az $I$ intervallumon.

#### 3.) Jellemezze egy függvény konvexitását az első deriváltfüggvény segítségével!
Tegyük fel, hogy $I \subset \mathbb{R}$ nyílt intervallum és $f \in \text{D}(I).$ Ekkor:

$$f \text{ konvex } I \text{-n} \Longleftrightarrow f' \text{ monoton növekvő } I \text{-n}$$

Ha $f'$ szigorúan monoton növekvő, akkor $f$ szigorúan konvex $I$-n.

#### 4.) Jellemezze egy függvény konkávitását az első deriváltfüggvény segítségével!
Tegyük fel, hogy $I \subset \mathbb{R}$ nyílt intervallum és $f \in \text{D}(I).$ Ekkor:

$$f \text{ konkáv } I \text{-n} \Longleftrightarrow f' \text{ monoton csökkenő } I \text{-n}$$

Ha $f'$ szigorúan monoton csökkenő, akkor $f$ szigorúan konkáv $I$-n.

#### 5.) Jellemezze egy függvény konvexitását a második deriváltfüggvény segítségével!
Tegyük fel, hogy $I \subset \mathbb{R}$ nyílt intervallum és $f \in \text{D}^2(I).$ Ekkor:

$$1.) f \text{ konvex } I \text{-n} \Longleftrightarrow f'' \geq 0 I \text{-n}.$$
$$2.) f'' > 0 I \text{-n} \Longrightarrow f \text{ szigorúan konvex } I \text{-n}.$$

#### 6.) Jellemezze egy függvény konkávitását a második deriváltfüggvény segítségével!
Tegyük fel, hogy $I \subset \mathbb{R}$ nyílt intervallum és $f \in \text{D}^2(I).$ Ekkor:

$$1.) f \text{ konkáv } I \text{-n} \Longleftrightarrow f'' \leq 0 I \text{-n}.$$
$$2.) f'' < 0 I \text{-n} \Longrightarrow f \text{ szigorúan konkáv } I \text{-n}.$$

#### 7.) Mi az inflexiós pont definíciója?
Legyyen $I$ nyílt intervallum és tegyük fel, hogy $f \in \text{D}(I).$ Azt mondjuk, hogy a $c \in I$ pont az $f$ függvénynek inflexiós pontja, ha:

$$\exists \delta > 0 : f \text{ konvex } (c-\delta,c] \text{-n és konkáv } [c, c+\delta) \text{-n, vagy fordítva.}.$$

#### 8.) Mondja ki a konvexitás és az érintő kapcsolatára vonatkozó tételt!
Tegyük fel, hogy $I \subset \mathbb{R}$ nyílt intervallum és $f \in \text{D}(I).$ Ekkor:

$$f \text{ konvex } I \text{-n} \Longleftrightarrow \forall a \in I : f(x) \geq e_{f,a}(x).$$

#### 9.) Mondja ki a konkávitás és az érintő kapcsolatára vonatkozó tételt!
Tegyük fel, hogy $I \subset \mathbb{R}$ nyílt intervallum és $f \in \text{D}(I).$ Ekkor:

$$f \text{ konkáv } I \text{-n} \Longleftrightarrow \forall a \in I : f(x) \leq e_{f,a}(x).$$

#### 10.) Mikor mondjuk, hogy egy függvénynek aszimptotája van a $+\infty$-ben?
Legyen $a \in \mathbb{R}$ és $f : (a,+\infty) \rightarrow \mathbb{R}.$ Azt mondjuk, hogy $f$-nek van aszimptotája $(+\infty)$-ben, ha:

$$\exists l(x) = Ax + b \space (x \in \mathbb{R}) \space : \space \lim_{x \rightarrow +\infty}(f(x)-l(x)) = 0$$

Ekkor az $l(x) \space (x \in \mathbb{R}) \space$ egyenes az $f$ aszimptotája $(+\infty)$-ben.

#### 11.) Hogyan szól a $+\infty$-beli aszimptota létezésére vonatkozó feltétel?
Az $f : (a,+\infty) \rightarrow \mathbb{R}$ függvénynek akkor és csak akkor van aszimptotája $(+\infty)$-ben, ha léteznek és végesek a:

$$\lim_{x \rightarrow +\infty} \dfrac{f(x)}{x} =: A \in \mathbb{R} \space , \space \lim_{x \rightarrow +\infty}(f(x)-Ax) =: B \in \mathbb{R} \space \text{ határértékek. }$$

Ekkor az $l(x) = Ax + B \space (x \in \mathbb{R}) \space$ egyenes az $f$ aszimptotája $(+\infty)$-ben.
