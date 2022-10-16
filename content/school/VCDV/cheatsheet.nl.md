---
title: "Cheat Sheet VCDV"
---

# Les 1
## Parametervergelijkingen

Een **parametrisatie** is een stelsel vergelijkingen uitgedrukt in één of meerdere parameters (meestal `\(t\)` en `\((u,v)\)`). Een **vlakke kromme** is een verzameling punten in het vlak die een parametrisatie bezit, deze parametrisatie is niet uniek. Belangrijk voorbeeld: de grafiek van een continue functie `\(f\)` is een vlakke kromme met parametrisatie `\((t,f(t))\)`.

## Raaklijn en normaal aan vlakke kromme

Richtingscoëfficiënt van de raaklijn: `\(\dfrac{dy}{dx}=\dfrac{g'(t)}{f'(t)},\ f'(t)\neq0\)` op **ganse** interval `\(I\)` waarover `\(t\)` loopt. Rico normaal: `\(-\dfrac{dx}{dy}=-\dfrac{f'(t)}{g'(t)},\ g'(t)\neq0\)`. Een vlakke kromme is dus glad behalve mogelijks waar `\(f'(t)\)` en `\(g'(t)\)` beide nul zijn, bv. `\(r(t)=(t^3,t^6)\)` is een parametrisatie van de parabool `\(y=x^2\)` en dus overal glad, terwijl de afgeleiden nul zijn voor `\(t=0\)`.

Als `\(f'\)` en `\(g'\)` continu zijn en niet beide nul in `\(t_0\)`, dan is `$$\begin{dcases}x=f(t_0)+f'(t_0)(t-t_0)\\y=g(t_0)+g'(t_0)(t-t_0)\end{dcases}\qquad-\infty<t<\infty$$` een parametrisatie van de raaklijn aan de kromme `\(x=f(t),\ y=g(t)\)` in het punt `\(\left(f(t_0),g(t_0)\right)\)`.

Voor de normaal: `$$\begin{dcases}x=f(t_0)+g'(t_0)(t-t_0)\\y=g(t_0)-f'(t_0)(t-t_0)\end{dcases}\qquad-\infty<t<\infty$$`

## Poolcoördinaten

`\(x=r\cos\theta\)`

`\(y=r\sin\theta\)`

`\(r^2=x^2+y^2\)`

`\(\tan\theta=\dfrac{y}{x}\)`

`\(dA=r\ dr\ d\theta\)`

## Punt-normaal vergelijking

Gegeven een punt `\(P_0=(x_0,y_0,z_0)\)` met positievector `\(\vec{r_0}\)` en een normaalvector `\(\vec{n}=A\hat{i}+B\hat{j}+C\hat{k}\)` is `$$\vec{n}\bullet\left(\vec{r}-\vec{r_0}\right)=0$$` de vergelijking van het vlak door `\(P_0\)` met normaal `\(\vec{n}\)`.

Scalair: `$$A(x-x_0)+B(y-y_0)+C(z-z_0)=0$$`

## Lijnen in 3D

Gegeven een punt `\(P_0=(x_0,y_0,z_0)\)` met positievector `\(\vec{r_0}\)` en een andere vector `\(\vec{v}=a\hat{i}+b\hat{j}+c\hat{k}\)` is `$$\vec{r}=\vec{r_0}+t\vec{v}$$` de vergelijking van de lijn door `\(P_0\)` evenwijdig met `\(\vec{v}\)`.

Scalair: `$$\begin{dcases}x=x_0+at\\y=y_0+bt\\z=z_0+ct\end{dcases}\qquad-\infty<t<\infty$$` of na elimineren van `\(t\)`: `$$\dfrac{x-x_0}{a}=\dfrac{y-y_0}{b}=\dfrac{z-z_0}{c}$$`

## Gradiënt

De gradiënt van een functie wordt gegeven door `$$\mathbf{grad}\ f(x,y,z)=\nabla f(x,y,z)=\dfrac{\partial f}{\partial x}\hat{i}+\dfrac{\partial f}{\partial y}\hat{j}+\dfrac{\partial f}{\partial z}\hat{k}$$` en geeft de richting van de maximale verandering van die functie weer, alsook een normaal aan de niveaukromme van de functie.

## Raakvlak aan een grafiek

Als `\(z=f(x,y)\)` en `\(g(x,y,z)=f(x,y)-z\)` dan kan men het raakvlak aan de grafiek van `\(f\)` in een punt `\((a,b)\)` berekenen met `$$z=f(a,b)+\dfrac{\partial f(a,b)}{\partial x}(x-a)+\dfrac{\partial f(a,b)}{\partial y}(y-b).$$`

## Normalen

Normaal aan de grafiek van een functie `\(z=f(x,y)\)`: `$$\vec{n}=\dfrac{\partial f}{\partial x}\hat{i}+\dfrac{\partial f}{\partial y}\hat{j}-\hat{k}.$$`

Impliciete functie `\(g(x,y,z)=0\)`: `$$\vec{n}=\nabla g(x,y,z)$$`

Parametrisatie `\(\begin{dcases}x=x(u,v)\\y=y(u,v)\\z=z(u,v)\end{dcases}:\)` `$$\vec{n}=\dfrac{\partial\vec{r}}{\partial u}\times\dfrac{\partial\vec{r}}{\partial v}$$`

## Jacobiaan(se matrix)

`$$D\mathbf{f(x)}=\begin{pmatrix}\dfrac{\partial f_1}{\partial x_1}&\dfrac{\partial f_1}{\partial x_2}&\ldots&\dfrac{\partial f_1}{\partial x_n}\\\dfrac{\partial f_2}{\partial x_1}&\ddots&&\\\vdots&&\ddots&\end{pmatrix}$$` oftewel `$$\left[D\mathbf{f(x)}\right]_{i,j}=\dfrac{\partial f_i}{\partial x_j}$$`

## Jacobiaanse determinant

`\(\dfrac{\partial(u,v)}{\partial(x,y)}=\begin{vmatrix}\dfrac{\partial u}{\partial x}&\dfrac{\partial u}{\partial y}\\\dfrac{\partial v}{\partial x}&\dfrac{\partial v}{\partial y}\end{vmatrix}\)`

`\(\dfrac{\partial(u,v)}{\partial(x,y)}=\dfrac{1}{\dfrac{\partial(x,y)}{\partial(u,v)}}\)`

## Inverse functiestelling

We herschrijven een stelsen `\(\begin{dcases}x=f(u,v)\\y=g(u,v)\end{dcases}\)` als volgt: `\(\begin{dcases}F(x,y,u,v):=f(u,v)-x=0\\G(x,y,u,v):=g(u,v)-y=0\end{dcases}\)`. Dan kunnen we via de impliciete functiestelling `\(\begin{dcases}u=\alpha(x,y)\\v=\beta(x,y)\end{dcases}\)` vinden zodat `\(F=0\)` en `\(G=0\)` als `\(\dfrac{\partial(F,G)}{\partial(u,v)}\neq0\)`.

## Verandering van coördinaten

`\(dA=dx\ dy= \text{abs}\left(\dfrac{\partial(x,y)}{\partial(u,v)}\right)\)`

Voor een dubbele integraal: `$$\iint_Df(x,y)dxdy=\iint_Sg(u,v)\left|\dfrac{\partial(x,y)}{\partial(u,v)}\right|dudv$$`

# Les 2
## Cylindrische Coördinaten

`\(x=r\cos\theta\)`

`\(y=r\sin\theta\)`

`\(z=z\)`

`\(r^2=x^2+y^2\)`

`\(\tan\theta=\dfrac{y}{x}\)`

`\(dV=r\ dr\ d\theta\ dz\)`

## Bolcoördinaten

`\(x=R\sin\varphi\cos\theta\)`

`\(y=R\sin\varphi\sin\theta\)`

`\(z=R\cos\varphi\)`

`\(R^2=x^2+y^2+z^2=r^2+z^2\)`

`\(r=\sqrt{x^2+y^2}=R\sin\varphi\)`

`\(\tan\varphi=\dfrac{r}{z}=\dfrac{\sqrt{x^2+y^2}}{z}\)`

`\(\tan\theta=\dfrac{y}{x}\)`

`\(dV=R^2\sin\varphi\ dR\ d\varphi\ d\theta\)`

## Veldlijnen

`\(\dfrac{dx}{F_1(x,y,z)}=\dfrac{dy}{F_2(x,y,z)}=\dfrac{dz}{F_3(x,y,z)}\)`

## Basisvectoren

`\(\hat{r}=\cos\theta\hat{i}+\sin\theta\hat{j}\)`

`\(\hat{\theta}=-\sin\theta\hat{i}+\cos\theta\hat{j}\)`

## Conservatief veld

`\(\mathbf{F}(x,y,z)=\nabla\varphi(x,y,z)\)`

`\(\dfrac{\partial}{\partial y}F_1(x,y)=\dfrac{\partial}{\partial x}F_2(x,y)\)`

`\(\dfrac{\partial F_1}{\partial y}=\dfrac{\partial F_2}{\partial x},\dfrac{\partial F_1}{\partial z}=\dfrac{\partial F_3}{\partial x},\dfrac{\partial F_2}{\partial z}=\dfrac{\partial F_3}{\partial y}\)`

`\(\begin{vmatrix}\hat{i}&\hat{j}&\hat{k}\\\dfrac{\partial}{\partial x}&\dfrac{\partial}{\partial y}&\dfrac{\partial}{\partial z}\\F_1&F_2&F_3\end{vmatrix}=\vec{0}\)`

# Les 3
## Lijnintegraal van een scalaire functie

`$$\int_\mathcal{C}f(x,y,z)ds=\int_a^bf(\mathbf{r}(t))\left|\dfrac{d\mathbf{r}}{dt}\right|dt$$` met `\(\mathbf{r=r}(t),a\leq t\leq b\)` een parametrisatie van de kromme `\(\mathcal{C}\)`.

De lijnintegraal is dus niet afhankelijk van de parametrisatie, enkel van de kromme en de functie. Ook in de tegengestelde richting de kromme doorlopen geeft hetzelfde resultaat. Interpretatie: oppervlakte onder een 3D-funtie over een bepaalde kromme.

## Lijnintegraal van een vectorveld

`$$\int_\mathcal{C}\mathbf{F}\bullet d\mathbf{r}=\int_\mathcal{C}\mathbf{F}\bullet\mathbf{\hat{T}}ds$$` met `\(\mathbf{\hat{T}}\)` de raakvector aan de kromme. Hier is de absolute waarde van de integraal onafhankelijk van de parametrisatie, maar het teken draait wel om als we de kromme in omgekeerde richting doorlopen (raakvector draait om). Interpretatie: arbeid die door een kracht wordt geleverd op een voorwerp dat zich verplaatst.

## Onafhankelijkheid van pad
Indien we een **open, samenhangend gebied** `\(D\)` hebben en als een vectorveld op `\(D\)` **conservatief** is, dan zijn de lijnintegralen onafhankelijk van het gekozen pad, en zijn deze lijnintegralen gelijk aan de potentiaal in het eindpunt min de potentiaal in het beginpunt. Hieruit volgt direct dat een lijnintegraal over een gesloten kromme nul is voor een conservatief vectorveld.
`$$\int_\mathcal{C}\mathbf{F}\bullet d\mathbf{r}=\int_\mathcal{C}d\varphi=\varphi(P_1)-\varphi(P_0).$$`

## Oppervlakte-integraal
`$$\mathbf{n}=\dfrac{\partial\mathbf{r}}{\partial u}\times\dfrac{\partial\mathbf{r}}{\partial v}=\begin{vmatrix}\mathbf{i}&\mathbf{j}&\mathbf{k}\\\dfrac{\partial x}{\partial u}&\dfrac{\partial y}{\partial u}&\dfrac{\partial z}{\partial u}\\\dfrac{\partial x}{\partial v}&\dfrac{\partial y}{\partial v}&\dfrac{\partial z}{\partial v}\end{vmatrix}$$`
`$$dS=\left|\dfrac{\partial\mathbf{r}}{\partial u}\times\dfrac{\partial\mathbf{r}}{\partial v}\right|du\ dv$$`
Voor de grafiek van een functie `\(z=g(x,y)\)` en parametrisatie `\(x=u,y=v,z=g(u,v)\)`: `$$\iint_\mathfrak{s}f(x,y,z)dS$$` `$$=\iint_Df(x,y,g(x,y))\sqrt{1+\left(\dfrac{\partial}{\partial x}g(x,y)\right)^2+\left(\dfrac{\partial}{\partial y}g(x,y)\right)^2}dx\ dy$$`


## Samenvattende tabel

| |Lijnintegraal|Niet-cons. vectorveld|Cons. vectorveld|
|--|--|:--:|--:|
|| `\(\int_a^b f\left(\mathbf{r}(t)\right)\bigg\lvert\dfrac{d\mathbf{r}}{dt}\bigg\rvert dt\)` | `\(\int_\mathcal{C}\mathbf{F}\bullet d\mathbf{r}=\int_\mathcal{C}\mathbf{F}\bullet\mathbf{\hat{T}}ds\)` | `\(\varphi(P_1)-\varphi(P_0)\)`
|Afhankelijk parametrisatie?|neen|absolute waarde niet|absolute waarde niet|
|Afhankelijk oriëntatie?|neen|ja, minteken|ja, minteken|
|Afhankelijk pad?|ja|ja|neen, zolang begin en einde gelijk blijven|
|Gesloten kromme?|niet per se nul|niet nul|nul|

# Les 4

## 1D integralen

|Lijnintegraal|Lijnintegraal vectorveld|
|:--|--:|
| `\(\int_a^bf(x(t),y(t),z(t))\Bigg\lvert\dfrac{d\vec{r}}{dt}\Bigg\rvert dt\)` | `\(\int_a^b\left(F_1\dfrac{dx}{dt}+F_2\dfrac{dy}{dt}+F_3\dfrac{dz}{dt}\right)dt\)` |

## 2D integralen

|Oppervlakte-integraal|fluxintegraal|
|:--|--:|
| `\(\int_Df(x(u,v),y(u,v),z(u,v))\Bigg\lvert\dfrac{d\vec{r}}{du}\times\dfrac{d\vec{r}}{dv}\Bigg\rvert\)` | `\(\int_D\vec{F}(\vec{r}(u,v))\bullet\left(\dfrac{d\vec{r}}{du}\times\dfrac{d\vec{r}}{dv}\right)du\ dv\)` |

## Georiënteerd oppervlak

Een oppervlak is **oriënteerbaar** als er een eenheids-vectorveld `\(\hat{N}(P)\)` bestaat zodat dit vectorveld continu is als P over het oppervlak beweegt en het vectorveld overal normaal is aan het oppervlak. Zo'n vectorveld bepaalt een **oriëntatie** op van het oppervlak. Een georiënteerd oppervlak bepaalt ook een oriëntatie voor de curves die de rand van het oppervlak bepalen: het oppervlak moet links liggen ten opzichte van deze oriëntatie, rechts moet leeg zijn.

## Fluxintegraal

`\(d\mathbf{S}=\hat{\mathbf{N}}\ dS=\pm\mathbf{n}\ du\ dv\)`

Voor een oppervlak met vergelijking `\(z=f(x,y)\)`: `\(d\mathbf{S}=\hat{\mathbf{N}}\ dS=\pm\left(-\dfrac{d f}{dx}\hat{i}-\dfrac{d f}{dy}\hat{j}+\hat{k}\right)dx\ dy\)`.

## Grad, div, curl

### grad: functie naar vector

`\(\mathbf{grad}f(x,y,z)=\nabla f(x,y,z)=\dfrac{d f}{dx}\hat{i}+\dfrac{d f}{dy}\hat{j}+\dfrac{d f}{dz}\hat{k}\)`

### div: vectorveld naar functie

`\(\mathbf{div\ F}=\nabla\bullet\mathbf{F}=\dfrac{d F_1}{dx}+\dfrac{d F_2}{dy}+\dfrac{d F_3}{dz}\)`

"Flux in een punt", "hoeveelheid die wegstroomt" (>0 source, <0 sink, =0 equilibrium) 

### curl: vectorveld naar vectorveld

`\(\mathbf{curl\ F}=\nabla\times\mathbf{F}=\begin{vmatrix}\hat{i}&\hat{j}&\hat{k}\\\dfrac{\partial}{\partial x}&\dfrac{\partial}{\partial y}&\dfrac{\partial}{\partial z}\\F_1&F_2&F_3\end{vmatrix}\)`

"draaiing" (positief is tegenwijzerzin)

Laplaciaan: `\(\Delta\varphi=\nabla^2\varphi=\mathbf{div\ grad}\ \varphi\)`. Harmonische functie als `\(\Delta\varphi=0\)`.

`\(\mathbf{div\ curl}=0\)` (curl van een vectorveld is solenoïdaal)

`\(\mathbf{curl\ grad}=\vec{0}\)` (conservatief vectorveld is irrotationaal)

Een vectorveld `\(\mathbf{F}\)` is **solenoïdaal** als `\(\mathbf{div\ F}=0\)`.

Een vectorveld `\(\mathbf{F}\)` is **irrotationaal** als `\(\mathbf{curl\ F}=\vec{0}\)`.
