#### 1. Mit mond ki a Dedekind-axióma vagy szétválasztási axióma?
Tegyük fel, hogy az $A, B \subset \mathbb{R}$ halmazokra a következők teljesülnek:
- $A \neq \emptyset$  és $B \neq \emptyset$
- minden $a \in A$ és minden $b \in B$ elemre $a \leq b$.

Ekkor:

$$\exists \xi \in \mathbb{R} : \forall a \in A, b \in B : a \leq \xi \leq b .$$

#### 2.  Írja le pozitív formában azt, hogy egy $\emptyset \neq A \subset \mathbb{R}$ halmaz felülről nem korlátos?
Legyen $A \subset \mathbb{R}$ nemüres számhalmaz. Ekkor $A$ akkor és csak akkor felülről nem korlátos, ha:

$$\forall K \subset \mathbb{R} : \exists x \in A : x \gt K.$$

#### 3.  Fogalmazza meg egyenlőtlenségekkel azt a tényt, hogy egy $\emptyset \neq A \subset \mathbb{R}$ halmaz korlátos!
Egy $\emptyset \neq A \subset \mathbb{R}$ számhalmaz akkor és csak akkor korlátos (azaz alulról és felülről is korlátos), ha:

$$\exists K \subset \mathbb{R} : \forall x \in A : | x | \leq K;$$vagy:
$$\exists K \subset \mathbb{R} : \forall x \in A : -K \leq x \leq K.$$

#### 4. Fogalmazza meg a szuprémum elvet!
Legyen $\ H \subset \mathbb{R}$ és tegyük fel, hogy: 
1. $H \neq \emptyset$ *és*
2. $H$ *felülről korlátos.* 

*Ekkor:*

$\exists \min \\{ K \in \mathbb{R} \space | \space K$ *felső korlátja* $H$ *-nak* $\\}.$

#### 5.  Mi a szuprémum definíciója?
A felülről korlátos $\emptyset \neq H \subset \mathbb{R}$ számhalmaz legkisebb felső korlátját $H$ **szuprémumának** nevezzük, és sup $H$ -val jelöljük.

#### 6. Fogalmazza meg egyenlőtlenségekkel azt a tényt, hogy $\xi =$ sup $H \in \mathbb{R}$ !
Legyen $\emptyset \neq H \subset \mathbb{R}$ *felülről korlátos* halmaz. Ekkor:

$\xi =$ sup $H \Longleftrightarrow$ A következő állításokkal: 
1. $\xi$ *felső korlát, azaz:* $\forall x \in H : x \leq \xi$
2. $\xi$ *a legkisebb felső korlát, azaz:* $\forall ε \gt 0 : \exists x \in H : \xi-ε \lt x$.

#### 7. Mi az infimum definíciója?
Az alulról korlátos $\emptyset \neq H \subset \mathbb{R}$ számhalmaz legnagyobb alsó korlátját $H$ **infimumának** nevezzük, és inf $H$-val jelöljük.

#### 8. Fogalmazza meg egyenlőtlenségekkel azt a tényt, hogy $\xi =$ inf $H \in \mathbb{R}$ !
Legyen $\emptyset \neq H \subset \mathbb{R}$ *alulról korlátos* halmaz. Ekkor:

$\xi =$ inf $H \Longleftrightarrow$ A következő állításokkal: 
1. $\xi$ *alsó korlát, azaz:* $\forall x \in H : x \geq \xi$
2. $\xi$ *a legnagyobb alsó korlát, azaz:* $\forall ε \gt 0 : \exists x \in H : \xi+ε \gt x$.

#### 9. Mi a kapcsolat egy halmaz maximuma és a szuprémuma között?

Legyen $H \subset \mathbb{R}$.

$$\exists \text{max} H \space\space\Longleftrightarrow\space\space \sup H \in H \text{ , és ekkor: sup} H = \text{max} H.$$

#### 10. Mi a kapcsolat egy halmaz minimuma és a infimuma között?

Legyen $H \subset \mathbb{R}$ .

$$\exists \text{min} H \space\space\Longleftrightarrow\space\space \inf H \in H \text{ , és ekkor: inf} H = \text{min} H.$$
