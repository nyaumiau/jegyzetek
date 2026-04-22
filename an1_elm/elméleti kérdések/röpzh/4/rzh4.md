#### 1. Mit tud mondani nullsorozatok összegéről?
Tegyük fel, hogy $\lim(a_n)=0 \text{ és } \lim(b_n)=0$. Ekkor: $(a_n + b_n)$ is nullsorozat.

#### 2. Mit tud mondani korlátos sorozat és nullsorozat szorzatáról?
Tegyük fel, hogy $\lim(a_n)=0$. Ekkor: ha $(c_n)$ korlátos sorozat, akkor $(c_n \cdot a_n)$ is nullsorozat. 

#### 3. Mondjon példát olyan $(a_n), (b_n) : \mathbb{N} \rightarrow \mathbb{R}$ sorozatokra, amelyekre $\lim(a_n) = 0, \lim(b_n) = 0$ és a $\lim(a_n/b_n)$ határérték nem létezik.
Legyen $(a_n) := \dfrac{(-1)^n}{n}$ és $(b_n) := \dfrac{1}{n}$. Ekkor $\lim(a_n)=lim(b_n)=0$ és: 

$$\dfrac{a_n}{b_n} = \dfrac{\dfrac{(-1)^n}{n}}{\dfrac{1}{n}} = \dfrac{(-1)^n}{n} \cdot \dfrac{n}{1} = \dfrac{(-1)^n\cdot n}{n} = (-1)^n.$$ 

Mivel a $(-1)^n$ határérték nem létezik, ezért a $\lim(\dfrac{a_n}{b_n})$ határérték sem létezik.

#### 4. Milyen állítást ismer konvergens sorozatok összegéről?
Tegyük fel, hogy $(a_n)$ és $(b_n)$ sorozat konvergens és legyen:

$$\lim(a_n)=:A \in \mathbb{R} \text{ és } \lim(b_n)=:B \in \mathbb{R}.$$ 

Ekkor: 

$$(a_n + b_n) \text{ is konvergens és } \lim(a_n+b_n) = \lim(a_n) + \lim(b_n) = A + B.$$

#### 5. Milyen állítást ismer konvergens sorozatok szorzatáról?
Tegyük fel, hogy $(a_n)$ és $(b_n)$ sorozat konvergens és legyen: 

$$\lim(a_n)=:A \in \mathbb{R} \text{ és } \lim(b_n)=:B \in \mathbb{R}.$$ 

Ekkor: 

$$(a_n \cdot b_n) \text{ is konvergens és } \lim(a_n \cdot b_n) = \lim(a_n) \cdot \lim(b_n) = A \cdot B.$$

#### 6. Milyen állítást ismer konvergens sorozatok hányadosáról?
Tegyük fel, hogy $(a_n)$ és $(b_n)$ sorozat konvergens és legyen: 

$$\lim(a_n)=:A \in \mathbb{R} \text{ és } \lim(b_n)=:B \in \mathbb{R}.$$ 

Ekkor, ha  $\forall n \in \mathbb{N} : b_n \neq 0$ és $\lim(b_n) \neq 0$, akkor: 

$$(\dfrac{a_n}{b_n}) \text{ is konvergens és } \lim(\dfrac{a_n}{b_n}) = \dfrac{\lim(a_n)}{\lim(b_n)} = \dfrac{A}{B}.$$

#### 7. Milyen állítást tud mondani (tágabb értelemben) határértékkel bíró sorozatok összegéről?
Tegyük fel, hogy $(a_n)$ és $(b_n)$ sorozatnak van határértéke és legyen: 

$$\lim(a_n)=:A \in \mathbb{\overline{R}} \text{ és } \lim(b_n)=:B \in \mathbb{\overline{R}}.$$

Ekkor az $(a_n+b_n)$ összeg-sorozatnak is van határértéke és: 

$$\lim(a_n+b_n) = \lim(a_n) + \lim(b_n) = A + B,$$ 

feltéve, ha az $A + B \in \mathbb{\overline{R}}$ összeg értelmezve van.

#### 8. Milyen állítást tud mondani (tágabb értelemben) határértékkel bíró sorozatok szorzatáról?
Tegyük fel, hogy $(a_n)$ és $(b_n)$ sorozatnak van határértéke és legyen: 

$$\lim(a_n)=:A \in \mathbb{\overline{R}} \text{ és } \lim(b_n)=:B \in \mathbb{\overline{R}}.$$ 

Ekkor az $(a_n \cdot b_n)$ szorzat-sorozatnak is van határértéke és: 

$$\lim(a_n \cdot b_n) = \lim(a_n) \cdot \lim(b_n) = A \cdot B,$$ 

feltéve, ha az $A \cdot B \in \mathbb{\overline{R}}$ szorzat értelmezve van.

#### 9. Milyen állítást tud mondani (tágabb értelemben) határértékkel bíró sorozatok hányadosáról?
Tegyük fel, hogy $(a_n)$ és $(b_n)$ sorozatnak van határértéke és legyen: 

$$\lim(a_n)=:A \in \mathbb{\overline{R}} \text{ és } \lim(b_n)=:B \in \mathbb{\overline{R}}.$$ 

Ekkor, ha $\forall n \in \mathbb{N} : b_n \neq 0$, akkor az $(\dfrac{a_n}{b_n})$ hányados-sorozatnak is van határértéke és

$$\lim(\dfrac{a_n}{b_n}) = \dfrac{\lim(a_n)}{\lim(b_n)} = \dfrac{A}{B},$$ 

feltéve, hogy az $\dfrac{A}{B} \in \mathbb{\overline{R}}$ hányados értelmezve van.

#### 10. Legyen $q \in \mathbb{R}$. Mit tud mondani a $(q^n)$ sorozatról határérték szempontjából?
Minden rögzített $q \in \mathbb{R}$ esetén a $(q^n)$ mértani sorozat határértékére a következők teljesülnek: 

1. $|q| < 1$ esetén: $\lim(q^n) = 0$
2. $q = 1$ esetén: $\lim(q^n) = 1$
3. $q > 1$ esetén: $\lim(q^n) = +\infty$
4. $q \leq -1$ esetén: $\lim(q^n)$ nem létezik.
