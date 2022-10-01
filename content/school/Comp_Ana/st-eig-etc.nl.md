---
title: Eigenschappen, Stellingen en gevolgen
---

# Hoofdstuk 1: Basisbegrippen

## Stelling 1.1.3

Zij `\(f:\Omega\to\mathbb{C}\)` met `\(u=\text{Re}(f)\)` en `\(v=\text{Im}(f)\)`. De volgende uitspraken zijn equivalent:

1. `\(f\)` is analytisch in `\(\Omega\)`

1. De partiële afgeleiden `\(\dfrac{\partial f}{\partial x}\)` en `\(\dfrac{\partial f}{\partial y}\)` bestaan en zijn continu op `\(\Omega\)` en er geldt `$$\dfrac{\partial f}{\partial x}=\dfrac{1}{i}\dfrac{\partial f}{\partial y}$$` of equivalent `$$\dfrac{\partial u}{\partial x}=\dfrac{\partial v}{\partial y},\dfrac{\partial u }{\partial y}=-\dfrac{\partial v}{\partial x}$$`

## Propositie 1.1.4

Zij `\(\Omega\subset\mathbb{C}\)` open en samenhangend. Zij `\(f:\Omega\to\mathbb{C}\)` analytisch. Als `\(|f|\)` constant is dan is `\(f\)` constant.

## Propositie 1.1.6

Zij `\(f=u+iv:\Omega\to\mathbb{C}\)` analytisch met `\(u,v\)` van klasse `\(C^2\)`. Dan zijn `\(u\)` en `\(v\)` beide harmonische functies.

## Stelling 1.1.7

Zij `\(\sum_{n\geq0}\alpha_nz^n\)` een complexe machtreeks met convergentiestraal `\(R>0\)`. Dan is `$$f:B(0,R)\to\mathbb{C}:z\mapsto\sum_{n=0}^{\infty}a_nz^n$$` analytisch in `\(B(0,R)\)`.

## Eigenschappen 1.1.8

1. Is `\(f\)` complex differentieerbaar in `\(z_0\)` dan is `\(f\)` continu in `\(z_0\)`.

1. Zij `\(f\)` en `\(g\)` complex differentieerbaar in `\(z_0\)` en is `\(\alpha\in\mathbb{C}\)` dan zijn ook `\(f+\alpha g\)`, `\(fg\)` en `\(\dfrac{f}{g}\)` (mits `\(g(z_0)\neq0\)`) complex differentieerbaar in `\(z_0\)` en hun afgeleiden worden gegeven door de gebruikelijke formules.

1. Is `\(f\)` complex differentieerbaar in `\(z_0\)` en is `\(g\)` gedefinieerd op een omgeving van `\(f(z_0)\)` en complex differentieerbaar in `\(f(z_0)\)` dan is `\(g\circ f\)` complex differentieerbaar in `\(z_0\)` en er geldt `\((g\circ f)'(z_0)=g'(f(z_0))f'(z_0)\)`.

## Stelling 1.1.10 (inverse functiestelling voor analytische functie) {#stelling-1110}

Zij `\(f:\Omega\to\mathbb{C}\)` analytisch, `\(z_0\in\Omega\)` en `\(f(z_0)\neq0\)`. Dan is er een bolomgeving `\(U\)` van `\(z_0\)` in `\(\Omega\)` zodat `\(f|_U\)` injectief is, zodat `\(f(U):=V\)` open is en zodat `\((f|_U)^{-1}:V\to U\)` analytisch is.

## Eigenschap 1.2.4

Zij `\(z=z(t)=(x(t),y(t)),t\in[a,b]\)` en `\(f=u+iv\)` beide zoals in [Definitie 1.2.1](/nl/school/comp_ana/begrippenlijst/#definitie-121). We beschouwen de volgende vectorvelden op `\(\Omega\)`:

`$$\vec{F^1}=(u,-v)$$`

`$$\vec{F^2}=(v,u)$$`

Dan is `$$\int_\mathcal{C}f(z)dz=\int_\mathcal{C}udx-vdy+i(vdx+udy)=\int_\mathcal{C}\vec{F^1}\bullet d\mathbf{r}+i\int_\mathcal{C}\vec{F^2}\bullet d\mathbf{r}$$`

## Propositie 1.2.5

Zij `\(\Omega\subset\mathcal{C}\)` stervormig en zij `\(f:\Omega\to\mathcal{C}\)`. We schrijven `\(f=u+iv\)`. De volgende uitspraken zijn equivalent:

1. `\(f\)` is analytisch

1. de vectorvelden `\(\vec{F^1}\)` en `\(\vec{F^2}\)` uit [Eigenschap 1.2.4](#eigenschap-124) zijn gradiënt vectorvelden.

## Propositie 1.2.6

Zij `\(\mathcal{C}\subset\Omega\)` een kromme met parametrisatie `\(z=\sigma(t),t\in[a,b]\)`. Zij `\(g\)` een `\(C^1\)` functie op `\(\Omega\)`. Dan is `$$\int_\mathcal{C}\vec{\nabla}g\bullet d\mathbf{r}=g(\sigma(b))-g(\sigma(a)).$$`

De lengte `\(L\)` van een kromme `\(\mathcal{C}\)` met parametrisatie `\(z=\sigma(t),t\in[a,b]\)` is `\(L=\int_a^b|\sigma'(t)|dt\)`.

## Lemma 1.2.7 ("ML"-lemma) {#lemma-127}

Zij `\(\mathcal{C}\)` een kromme met lengte `\(L\)`. zij `\(f:\mathcal{C}\to\mathbb{C}\)` continu. Noteer `\(M=\max_{z\in\mathcal{C}}|f(z)|\)`. Dan geldt: `$$\left|\int_\mathcal{C}f(z)dz\right|\leq ML.$$`

## Propositie 1.2.9

Zij `\(F:\Omega\to\mathbb{C}\)` analytisch en zij `\(F'=f\)`. Zij `\(\mathcal{C}\subset\Omega\)` een kromme met bijbehorende parametrisatie `\(\sigma(t),t\in[a,b]\)`. Dan is `$$\int_\mathcal{C}f(z)dz=F(\sigma(b))-F(\sigma(a)).$$`

# Hoofdstuk 2: De representatieformule van Cauchy

# Hoofdstuk 3: Enige meetkunde in `\(\mathbb{C}\)`

# Hoofdstuk 4: Nulpunten, singuliere punten

# Hoofdstuk 5: Evaluatie van integralen

# Hoofdstuk 6: Conforme transformaties

# Hoofdstuk 7: Aanvullende begrippen
