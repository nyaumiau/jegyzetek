#### 1. Fogalmazza meg a végtelen sorokra vonatkozó összehasonlító kritériumokat!
Legyenek $\sum a_n, \sum b_n$ nemnegatív tagú sorok. Tegyük fel, hogy: 

$$\exists N \in \mathbb{N}:\forall n \gt N : 0 \leq a_n \leq b_n.$$ 

Ekkor:
1. **Majoráns kritérium:** ha a $\sum b_n$ sor konvergens, akkor a $\sum a_n$ sor is konvergens.
2. **Minoráns kritérium:** ha a $\sum a_n$ sor divergens, akkor a $\sum b_n$ sor is divergens.

#### 2. Fogalmazza meg a végtelen sorokra vonatkozó Cauchy-féle gyökkritériumot!
Tekintsük a $\sum a_n$ végtelen sort, és tegyük fel, hogy létezik az 

$$A:=\lim_{n \rightarrow +\infty} \sqrt[n]{|a_n|} \in \mathbb{\overline{R}}$$ 

határérték. Ekkor:
1. $0 \leq A \lt 1$ esetén a $\sum a_n$ sor abszolút konvergens, tehát konvergens is, vagy
2. $A \gt 1$ esetén a $\sum a_n$ sor divergens, vagy
3. $A=1$ esetén a $\sum a_n$ sor lehet konvergens és divergens is.

#### 3. Mit jelent az, hogy a Cauchy-féle gyökkritérium bizonyos esetekben nem alkalmazható? Illusztrálja példákkal mindezt!
Tegyük fel, hogy 

$$A:=\lim_{n \rightarrow +\infty} \sqrt[n]{|a_n|} = 1.$$ 

Ekkor például:
- A $\sum \dfrac{1}{n}$ divergens sor esetében $|a_n| = \dfrac{1}{n}$, azaz $\lim\limits_{n \rightarrow +\infty} \sqrt[n]{|a_n|} = \lim\limits_{n \rightarrow +\infty} {\dfrac{1}{\sqrt[n]{n}}} = 1;$
- A $\sum \dfrac{1}{n^2}$ konvergens sor esetében $|a_n| = \dfrac{1}{n^2}$, azaz $\lim\limits_{n \rightarrow +\infty} \sqrt[n]{|a_n|} = \lim\limits_{n \rightarrow +\infty} {\dfrac{1}{\sqrt[n]{n^2}}} = 1.$

#### 4. Fogalmazza meg a végtelen sorokra vonatkozó d'Alembert-féle hányadoskritériumot!
Tegyük fel, hogy a $\sum a_n$ végtelen sor egyik tagja sem $0$, valamint, hogy létezik az 

$$A:=\lim_{n \rightarrow +\infty} \sqrt[n]{|{\dfrac{a_{n+1}}{a_n}}|}\in \mathbb{\overline{R}}$$ 

határérték. Ekkor:
1. $0 \leq A \lt 1$ esetén a $\sum a_n$ sor abszolút konvergens, tehát konvergens is, vagy
2. $A \gt 1$ esetén a $\sum a_n$ sor divergens, vagy
3. $A=1$ esetén a $\sum a_n$ sor lehet konvergens és divergens is.

#### 5. Mit jelent az, hogy a d'Alembert-féle hányadoskritérium bizonyos esetekben nem alkalmazható? Illusztrálja példákkal mindezt!
Tegyük fel, hogy 

$$A:=\lim_{n \rightarrow +\infty} \sqrt[n]{|{\dfrac{a_{n+1}}{a_n}}|} = 1.$$ 

Ekkor például:
- A $\sum \dfrac{1}{n}$ divergens sor esetében $|a_n| = \dfrac{1}{n}$, azaz $\lim\limits_{n \rightarrow +\infty} \dfrac{|a_{n+1}|}{|a_n|} = \lim\limits_{n \rightarrow +\infty} {\dfrac{n}{n+1}} = 1;$
- A $\sum \dfrac{1}{n^2}$ divergens sor esetében $|a_n| = \dfrac{1}{n^2}$, azaz $\lim\limits_{n \rightarrow +\infty} \dfrac{|a_{n+1}|}{|a_n|} = \lim\limits_{n \rightarrow +\infty} {\dfrac{n^2}{(n+1)^2}} = 1.$

#### 6. Mik a Leibniz-típusú sorok és milyen konvergenciatételt ismer ezekkel kapcsolatban?
A $0 \leq a_{n+1} \leq a_n \space(n \in \mathbb{N}^+)$ feltételt kielégítő sorozatból képzett 

$$\sum_{n=1}(-1)^{n+1}a_n = a_1 - a_2 + a_3 - a_4 + ...$$ 

váltakozó előjelű sort *Leibniz-típusú sornak* nevezzük.

**A Leibniz-kritérium**

A $\sum\limits_{n=1}(-1)^{n+1}a_n$ Leibniz-típusú sor *akkor és csak akkor* konvergens, ha $(a_n)$ nullsorozat, azaz $\lim (a_n) = 0.$

#### 7. Mit értünk egy $[0, 1]$-beli szám diadikus tört alakján?
Legyen $\alpha \in [0,1]$ és $(a_n) : \mathbb{N}^+ \rightarrow \{0,1\}$ olyan sorozat, amire

$$\alpha = \sum_{n=1}^{+\infty} \dfrac{a_n}{2^n}$$

teljesül. Ekkor azt mondjuk, hogy a $0,{a_1}{a_2}{a_3}... (2)$ felírás az $\alpha$ szám diadikus tört alakja és ezt az $\alpha = 0,{a_1}{a_2}{a_3}..._{(2)}$ egyenlőséggel fejezzük ki.
