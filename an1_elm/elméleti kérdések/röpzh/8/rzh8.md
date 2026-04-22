#### 1. Írja le a hatványsor definícióját!
Az adott $(\alpha_n) : \mathbb{N} \rightarrow \mathbb{R}$ sorozattal és az $\alpha \in \mathbb{R}$ számmal képzett 

$$\sum_{n=0}\alpha_{n} (x-a)^n = \alpha_0 + \alpha_1(x-a) + \alpha_2(x-a)^2 + ... \space (x \in \mathbb{R})$$

függvénysort az $a \in \mathbb{R}$ középpontú, $(\alpha_n)$ együtthatójú hatványsornak nevezzük.

#### 2. Hogyan szól a hatványsor konvergenciahalmazára vonatkozó, a konvergenciasugarát meghatározó tétel?
Tetszőleges $\sum\limits_{n=0}\alpha_n(x-a)^n$ hatványsor konvergenciahalmazára a következő három eset egyike áll fenn:
1. $\exists 0 \lt R \lt +\infty$, hogy a hatványsor $\forall x \in \mathbb{R} : |x-a|<R$ pontban abszolút konvergens és $\forall x \in \mathbb{R} : |x-a|>R$ pontban divergens.
2. A hatványsor csak az $x = a$ pontban konvergens. Ekkor legyen $R := 0.$
3. A hatványsor abszolút konvergens $\forall x \in \mathbb{R}$ esetén. Ekkor legyen $R := +\infty.$

$R$ -et a hatványsor *konvergenciasugarának* nevezzük.

#### 3. Adjon meg egy olyan hatványsort, amelyiknek a konvergenciahalmaza a $(-1;1)$ intervallum!
$$\text{KH}(\sum\limits_{n=0} x^n) = (-1;1)$$

#### 4. Adjon meg egy olyan hatványsort, amelyiknek a konvergenciahalmaza a $[−1, 1)$ intervallum!
$$\text{KH}(\sum_{n=1} \dfrac{1}{n} \cdot x^n) = [-1;1)$$ 

#### 5. Definiálja az exp függvényt!
A $\sum\limits_{n=0}\dfrac{x^n}{n!}$ hatványsor $\forall x \in \mathbb{R}$ pontban abszolút konvergens. Az összegfüggvényét, vagyis az 

$$\text{exp}(x) := \sum_{n=0}^{+\infty} \dfrac{x^n}{n!} = 1 + x + \dfrac{x^2}{2!} + \dfrac{x^3}{3!} + \dfrac{x^4}{4!} + ... \space (x \in \mathbb{R})$$

függvényt *exponenciális függvénynek* nevezzük.

#### 6. Definiálja a sin függvényt!
A $\sum\limits_{n=0}(-1)^n \cdot \dfrac{x^{2n+1}}{(2n+1)!}$ hatványsor $\forall x \in \mathbb{R}$ pontban abszolút konvergens. Az összegfüggvényét, vagyis a 

$$\sin x := \sin(x) := \sum\limits_{n=0}(-1)^n \cdot \dfrac{x^{2n+1}}{(2n+1)!} = x - \dfrac{x^3}{3!} + \dfrac{x^5}{5!} + ... \space (x \in \mathbb{R})$$ 

függvényt *szinuszfüggvénynek* nevezzük.

#### 7. Definiálja a cos függvényt!
A $\sum\limits_{n=0}(-1)^n \cdot \dfrac{x^{2n}}{(2n)!}$ hatványsor $\forall x \in \mathbb{R}$ pontban abszolút konvergens. Az összegfüggvényét, vagyis a 

$$\cos x := \cos(x) := \sum\limits_{n=0}(-1)^n \cdot \dfrac{x^{2n}}{(2n)!} = 1 - \dfrac{x^2}{2!} + \dfrac{x^4}{4!} + ... \space (x \in \mathbb{R})$$

függvényt *koszinuszfüggvénynek* nevezzük.
