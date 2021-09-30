# Limity
## Termíny
### Okolí
- **Okolí** bodu $U$ je prostor kolem daného bodu. Například okolí o $U(a, 1)$ je interval $(a-1; a+1)$. 
- **Prstencové okolí** $P$ je množina bodů $U(a,r) ∖ \{a\}$

## Definice limity
> Nechť funkce f je definována na prstencovém okolí $a \in \bar{R}$ . Řekněme, že funkce $f$ má v bodě $a$ limitu $b$ značeno:
> $$\lim_{x \to a}f(x) = b$$
> Pokud pro každé okolí $U$ bodu $f$ existuje prstencové okolí bodu $a$ tak, že: 
> $$f(P) \subset U $$

##### Příklad
Pro funkci $f(x) = x^3$ a okolí bodu $U(8, 1)$ na ose *y*. Hodnota funkce $f$ je v tomto okolí pro interval $(\sqrt[3]{8-1}; \sqrt[3]{8+1}) =(1.9; 2.1)$
- Hodnoty x v intervalu jsou tedy $(1.9; 2.1)$
- Hodnoty f(x) v okolí (a pro interval) jsou tedy $(8;10)$

Pro dané okolí $U$ jsme tedy našli prstencové okolí $P(2, 0.1)$.

Proto také platí, že aplikováním $f(x)$ na body z $P$ dostaneme pouze hodnoty v $U$ -> neboli formálně $f(P) \subset U$.

Pro každé sebemenší okolí $U$ a limitu $b$ vždy můžeme najít dané $P(b, r)$.