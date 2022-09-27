---
title: "Begrippenlijst"
output:
  pdf_document:
    includes:
      in_header: header.tex
---

# Hoofdstuk 1: Basisbegrippen

## Definitie 1.1.1

\- Analytische/holomorfe functie: een functie `\(f:\Omega\to\mathbb{C}\)` is een analytische/holomorfe functie in `\(\Omega\)` als ze in elk punt `\(z_0\in\Omega\)` complex differentieerbaar is en indien `\(f'\)` continu is.

\- Complex differentieerbaar: `$$\lim_{z\to z_0}\dfrac{f(z)-f(z_0)}{z-z_0}=:f'(z)$$` bestaat in `\(\mathbb{C}\)`.

## Definitie 1.1.5

\- Harmonische functie: Een functie `\(f:\Omega\subset\mathbb{R}^2\to\mathbb{R}\)` heet **harmonisch** indien `\(\nabla^2\varphi=0\)`, met `\(\nabla^2\)` de **Laplaciaan**, d.i. `$$\nabla^2\varphi=\dfrac{\partial^2\varphi}{\partial x^2}+\dfrac{\partial^2\varphi}{\partial y^2}$$`

\- Harmonisch toegevoegde: Een functie `\(v(x,y)\)` heet het harmonisch toegevoegde van harmonisch functie `\(u(x,y)\)` indien `\(u\)` en `\(v\)` voldoen aan de vergelijkingen van Cauchy-Riemann.

## Definitie 1.5

De `\(\sigma\)`-algebra `\(\mathcal{B(C)}\)` gedefinieerd door [Stelling 1.4](/nl/school/fundamenten/st-eig-etc#stelling-14) heet: de `\(\sigma\)`-algebra voortgebracht door de klasse `\(\mathcal{C}\)`.

## Definitie 1.6

Een kansmaat `\(P\)` op `\(\mathcal{B}\)` is een functie `$$P:\mathcal{B}\to\mathbb{R}$$` `$$A\mapsto P(A)$$` zodanig dat:

\- [P1]: `\(P(\Omega)=1\)`

\- [P2]: voor alle `\(A\in\mathcal{B}:P(A)\geq0\)`

\- [P3]: (axioma der **aftelbare additiviteit**): voor `\(A_n\in\mathcal{B},n=1,2,...,\)` paarsgewijs disjunct, geldt: `$$P\left(\cup_{n=1}^{\infty}A_n\right)=\sum_{n=1}^{\infty}P(A_n)$$`

## Definitie 1.8

Een drietal `\((\Omega,\mathcal{B},P)\)` heet een **kansruimte**.

# Hoofdstuk 2: De representatieformule van Cauchy

## Definitie 2.1

Zij `\((\Omega,\mathcal{B},P)\)` een kansruimte. Zij `\(B\in\mathcal{B}\)` met `\(P(B)>0\)`. De **voorwaardelijke kans van** `\(A\in\mathcal{B}\)`**, gegeven** `\(B\)` wordt genoteerd door `\(P(A|B)\)` en gedefinieerd door `$$P(A|B)=\dfrac{P(A\cap B)}{P(B)}.$$`Voor `\(P(B)=0\)` is `\(P(A|B)\)` niet gedefinieerd.

## Definitie 2.4

Twee gebeurtenissen `\(A\)` en `\(B\)` heten **onafhankelijk** indien `$$P(A\cap B)=P(A)\cdot P(B).$$`

## Definitie 2.5

Een familie gebeurtenissen `\(A_1,A_2,...,A_n;(n\geq2)\)` heet **onderling onafhankelijk** indien voor **elke** keuze van r verschillende indices `\(i_1,i_2,...,i_r\)` uit `\(1,...,n\)` en voor elke `\(r=2,...,n\)` geldt: `$$P(A_{i_1}\cap A_{i_2}\cap\ldots\cap A_{i_r})=P(A_{i_2})P(A_{i_2})\cdots P(A_{i_r}).$$`

## Definitie 2.6

Een oneindige familie gebeurtenissen `\(A_1,A_2,...\)` heet onderling onafhankelijk indien elke eindige deelfamilie onderling onafhankelijk is in de zin van [Definitie 2.5](#definitie-25).

# Hoofdstuk 3: Enige meetkunde in  `\(\mathbb{C}\)`

# Hoofdstuk 4: Nulpunten, singuliere punten

# Hoofdstuk 5: Evaluatie van integralen

# Hoofdstuk 6: Conforme transformaties

# Hoofdstuk 7: Aanvullende begrippen
