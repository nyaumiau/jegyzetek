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
