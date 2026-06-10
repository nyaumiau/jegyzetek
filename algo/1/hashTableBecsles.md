#### Nyílt címzés esetén, amennyiben törölt rést nem tartalmaz a tábla, milyen feltételekkel tudjuk kiszámolni a sikertelen és a sikeres keresések várható hosszának becslését? Adja meg a megfelelő becsléseket!

Legyen $\alpha = \dfrac{n}{m},$ ahol $m$ a hasító tábla mérete, $n$ pedig a hasító táblában jelenleg tárolt elemek száma.

Ekkor, ha *egyenletes hasítást* alkalmazunk, *nincsenek törölt rések* és $0 \lt \alpha \lt 1:$

1. Sikertelen keresés és sikeres beszúrás várható hossza legalább: $\dfrac{1}{1 - \alpha}.$
2. Sikeres keresés és sikertelen beszúrás várható hossza legalább: $\dfrac{1}{\alpha}ln \dfrac{1}{1 - \alpha}$

#### Adott kitöltöttség mellett, a sikeres vagy a sikertelen keresés várható hossza lesz a nagyobb? Miért?

Tegyük fel, hogy a sikertelen keresés/sikeres beszúrás várható hossza a nagyobb. Ekkor:

$$\forall \alpha \in (0;1): \dfrac{1}{1 - \alpha} \gt \dfrac{1}{\alpha}ln \dfrac{1}{1 - \alpha}.$$

Bizonyítás:

$$\dfrac{1}{1 - \alpha} \gt \dfrac{1}{\alpha}ln \dfrac{1}{1 - \alpha}$$

$$\dfrac{\dfrac{1}{1 - \alpha}}{\dfrac{1}{\alpha}}  \gt ln \dfrac{1}{1 - \alpha}$$

$$\dfrac{1}{1 - \alpha} \dfrac{\alpha}{1}  \gt ln \dfrac{1}{1 - \alpha}$$

$$\dfrac{\alpha}{1 - \alpha}  \gt ln \dfrac{1}{1 - \alpha}$$

$$ {e}^{\dfrac{\alpha}{1 - \alpha}}  \gt \dfrac{1}{1 - \alpha}$$

Mivel $\alpha \in (0;1),$ ezért $\dfrac{1}{1-\alpha}$ felírható a 

$$\sum_{n=0} \alpha^{n}$$ 

végtelen sor összegeként, valamint ${e}^{\dfrac{\alpha}{1 - \alpha}}$ felírható a 

$$\sum_{n=0} \dfrac{(\dfrac{\alpha}{1-\alpha})^n}{n!}$$

végtelen sor összegeként.

Ekkor:

$$\sum_{n=0}^{\infty} \dfrac{(\dfrac{\alpha}{1-\alpha})^n}{n!} > \sum_{n=0}^{\infty} \alpha^{n}$$

$$1 + \dfrac{\alpha}{1-\alpha} + \dfrac{(\dfrac{\alpha}{1-\alpha})^2}{2!} + ... > 1 + \alpha + \alpha^{2} + ...$$

$$\dfrac{\alpha}{1-\alpha} + \dfrac{(\dfrac{\alpha}{1-\alpha})^2}{2!} + ... > \alpha + \alpha^{2} + ...$$

$$\dfrac{\alpha}{1-\alpha} + \dfrac{(\dfrac{\alpha}{1-\alpha})^2}{2!} + ... - ( \alpha + \alpha^{2} + ... ) > 0$$

$$\alpha (\dfrac{1}{1-\alpha} + \dfrac{(\dfrac{\alpha}{1-\alpha})^2}{2!\alpha} + ... - ( 1 + \alpha + ... )) > 0$$

$$\alpha (\dfrac{1}{1-\alpha} + \dfrac{(\dfrac{\alpha}{1-\alpha})^2}{2!\alpha} + ... - \dfrac{1}{1-\alpha}) > 0$$

$$\alpha (\dfrac{(\dfrac{\alpha}{1-\alpha})^2}{2!\alpha} + ...) > 0$$

$$\dfrac{(\dfrac{\alpha}{1-\alpha})^2}{2!} + ... > 0$$

$$\sum_{n=2}^{\infty} \dfrac{(\dfrac{\alpha}{1-\alpha})^n}{n!} > 0$$

Mivel $\alpha \in (0;1),$ ezért $\dfrac{\alpha}{1-\alpha} > 0,$ így minden $n \geq 2$ esetén $\dfrac{(\dfrac{\alpha}{1-\alpha})^n}{n!} > 0,$ azaz a sor $(s_n)$ részletösszeg-sorozata monoton növekvő, és $s_1 > 0$, így $lim(s_n) \gt 0$. Ezzel igazoltuk az egyenlőtlenséget, így az eredeti feltevést is.
