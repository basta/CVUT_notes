# Lineární prostory

## Lineární kombinace a obal
#### $I$-tice vektorů
>Ať $L$ je lineární prostor nad $\mathbb{F}$ a ať $I$ je jakákoliv množina. Funkci $v : I \rightarrow L$ říkáme $I$-tice vektorů v $L$. Budeme ji značit $(\vec{v}_i)_{i\in I}$.

#### Lineární kombinace
>Ať $(\vec{v}_i)_{i\in I}$ je $I$-tice vektorů. Její *lineární kombinace* je vektor $$\sum_{i \in I}{a_i*\vec{v_i}}$$ kde a_i (tzv. *koeficienty lineární kombinace*) jsou z $\mathbb{F}$ a množina $\{i \in I | a_i \neq 0\}$ je konečná.

- To nejobecnější, co nám lineární prostor dovoluje počítat.
- **koeficienty musí být konečná množina, nelze napříkad vzít jako koeficienty $\mathbb{N}$**

##### Příklady
###### 1
Pro $I = \{1,2,3\}$ je seznam $(2x, 2x, 4x^3)$ $I$-tice vektorů v lineárním prostoru $\mathbb{R}[x]$. Lineární kombinací pro tento seznam je například polynom $5x^3 - 5x$. Koeficienty této kombinace jsou $(a_1, a_2, a_3) \rightarrow(\frac{-3}{2}, -1, \frac{5}{4})$.

Můžeme si ale všimnout, že tento daný polynom lze zapsat různými koeficienty, které k němu vedou (třeba $(0, \frac{-5}{2}, \frac{5}{4})$).

---

###### 2
$M = \{x,x^7\}$ je podmnožina $\mathbb{R}[x]$. Jak vypadají *všechny* lineární kombinace prvků $M$?
>Obecná $I$-tice prvků množiny $M$ má tvar $(p_i(x))_{i \in I}$, kde každé $p_i(x)$ je buď polynom $x$ nebo $x^7$. Lineární kombinace této $I$-tice musí mít jako koeficienty $a_i$