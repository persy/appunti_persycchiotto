---
title: "Analisi"
draft: false
weight: 10
---

<!-- script MathJax -->
<script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.1/MathJax.js?config=TeX-AMS-MML_HTMLorMML">
</script>
<script type="text/x-mathjax-config">
MathJax.Hub.Config({
  tex2jax: {
    inlineMath: [['$','$'], ['\\(','$']],
    displayMath: [['$$','$$'], ['\[','\]']],
    processEscapes: true,
    processEnvironments: true,
    skipTags: ['script', 'noscript', 'style', 'textarea', 'pre'],
    TeX: { equationNumbers: { autoNumber: "AMS" },
         extensions: ["AMSmath.js", "AMSsymbols.js"] }
  }
});
</script>
<!-- script JSXGraph -->
<script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/jsxgraph/0.99.7/jsxgraphcore.js"></script>


- [Funzioni e derivate](#funzioni-e-derivate)
  - [Il rapporto incrementale](#il-rapporto-incrementale)
  - [La derivata](#la-derivata)
  - [Le regole di derivazione](#le-regole-di-derivazione)
  - [Il significato geometrico](#il-significato-geometrico)
  - [Il differenziale e il suo significato geometrico](#il-differenziale-e-il-suo-significato-geometrico)
- [I teoremi sulle funzioni derivabili](#i-teoremi-sulle-funzioni-derivabili)
  - [I teoremi di de L'Hospital e il calcolo dei limiti](#i-teoremi-di-de-lhospital-e-il-calcolo-dei-limiti)
- [Punti estremanti e punti di inflessione](#punti-estremanti-e-punti-di-inflessione)
  - [Massimi e minimi relativi](#massimi-e-minimi-relativi)
  - [Criteri di individuazione](#criteri-di-individuazione)
  - [Massimi e minimi assoluti](#massimi-e-minimi-assoluti)
  - [Concavità e flessi](#concavita-e-flessi)
  - [Massimi, minimi e flessi con le derivate successive](#massimi--minimi-e-flessi-con-le-derivate-successive)
- [Lo studio di funzione](#lo-studio-di-funzione)
  - [I grafici deducibili](#i-grafici-deducibili)
- [Gli integrali](#gli-integrali)
  - [L'integrale indefinito](#lintegrale-indefinito)
  - [Le proprietà](#le-proprieta)
  - [Gli integrali immediati](#gli-integrali-immediati)
  - [L'integrazione delle funzioni razionali fratte](#lintegrazione-delle-funzioni-razionali-fratte)
  - [L'integrale definito](#lintegrale-definito)
  - [Le proprietà](#le-proprieta)
  - [La funzione integrale](#la-funzione-integrale)
  - [Il calcolo di un integrale definito](#il-calcolo-di-un-integrale-definito)
  - [Il calcolo delle aree](#il-calcolo-delle-aree)

## Funzioni e derivate
### Il rapporto incrementale
Il **rapporto incrementale** della funzione $f(x)$ relativo al punto $x_0$ e all'incremento $h$ è dato dall'espressione:

<div align="center">
$\dfrac{\Delta y}{\Delta x} = \dfrac{f(x_0 + h) - f(x_0)}{h}$
</div>

### La derivata
Se il limite per $h \to 0$ del rapporto incrementale esiste finito, si dice che $f(x)$ è derivabile nel punto $x_0$; in tal caso l'espressione:

<div align="center">
$f'(x_0) = \lim\limits _{h \to 0} \dfrac{f(x_0 + h) - f(x_0)}{h}$
</div>

rappresenta la **derivata** di $f(x)$ in $x_0$.

Quando il limite non è finito oppure non esiste, si dice che $f(x)$ non è derivabile in $x_0$.
Una funzione non derivabile in $x_0$ può però essere derivabile da sinistra o da destra in tale punto a seconda che esista finito il limite per $h \to 0$ oppure per $h \to 0^{+}$ del rapporto incrementale.

### Le regole di derivazione
Per calcolare la derivata di una funzione si devono conoscere le regole di derivazione delle funzioni elementari:

* $D[k] = 0$
* $D[x ^{\alpha}] = \alpha x ^{\alpha - 1}$
* $D[\sin x] = \cos x$
* $D[\cos x] = - \sin x$
* $D[\log_a x] = \dfrac{1}{x \ln a}$
* $D[\ln x] = \dfrac{1}{x}$
* $D[a^x] = a^x \ln a$
* $D[e^x] = e^x$

ed i seguenti teoremi:

* derivata della somma: $D[f(x) + g(x)] = f'(x) + g'(x)$
* derivata del prodotto: $D[f(x) \cdot g(x)] = f'(x) \cdot g(x) + f(x) \cdot g'(x)$
  * in particolare: $D[k \cdot f(x)] = k \cdot f'(x)$ con $k \in \mathbb{R}$
* derivata del quoziente: $D \left [ \dfrac{f(x)}{g(x)} \right ] = \dfrac{f'(x) \cdot g(x) - f(x) \cdot g'(x)}{[g(x)]^2}$
  * in particolare $D \left [ \dfrac{1}{g(x)} \right ] = - \dfrac{g'(x)}{[g(x)]^2}$
* derivata della funzione composta: $D[g(f(x))] = g'(f(x)) \cdot f'(x)$
  * in particolare se $y = [f(x)] ^{g(x)}$ allora $y' =  [ f(x)] ^{g(x)} \cdot \left[ g'(x) \ln f(x) + g(x) \cdot \dfrac{f'(x)}{f(x)} \right ]$

Dalla regola di derivazione delle funzioni inverse si ha poi che:
* $D[\arcsin x] = \dfrac{1}{\sqrt{1 - x^2}}$
* $D[\arccos x] = - \dfrac{1}{\sqrt{1 - x^2}}$
* $D[\arctan x] = \dfrac{1}{\sqrt{1 + x^2}}$

### Il significato geometrico
Dal punto di vista geometrico $f'(x)$, cioè la derivata calcolata nel punto $x_0$, rappresenta il coefficiente angolare della retta $t$ tangente alla curva in quel punto. Se la funzione è derivabile, l'equazione della retta tangente in $P(x_0, \space f(x_0))$ è quindi:

<div align="center">
$y - f(x_0) = \underset{m}{\underbrace{f'(x_0)}} \cdot (x - x_0)$
</div>

Quando la funzione non è derivabile, si possono presentare i seguenti casi particolari:
* $f'(x) = \infty$ allora la retta tangente è parallela all'asse $y$ (si dice che il punto $P$ è *a tangente verticale*)
* la derivata sinistra e quella destra sono finite ma diverse, oppure una di esse è finita e l'altra infinita; in questo caso esistono due rette tangenti diverse a sinistra e a destra di $x_0$ e $P$ rappresenta un **punto angoloso**
* la derivata sinistra e quella destra sono infinite ma di segno opposto; in questo caso la retta tangente in $P$ è parallela all'asse $y$ e si dice che $P$ è una **cuspide**.

### Il differenziale e il suo significato geometrico
Il **differenziale** di una funzione $f(x)$ in un punto $x$ è il prodotto della derivata della funzione per l'incremento $\Delta x$:

<div align="center">
$df(x) = f'(x) \cdot \Delta x \text{ ed essendo } \Delta x = dx \qquad df(x) = f'(x) \cdot d(x)$
</div>

Dal punto di vista geometrico il differenziale rappresenta l'incremento della variabile dipendente $y$ calcolarlo sulla retta tangente anziché sulla funzione.


## I teoremi sulle funzioni derivabili
Le funzioni $f(x)$ derivabili godono di alcune proprietà che sono riassunte in una serie di teoremi; le ipotesi comuni sono che $f(x)$ deve essere continua in un intervallo $[ a, \space b ]$ e derivabile in $( a, \space b )$. In questo caso:
* **teorema di Rolle**: se la funzione assume valori uguali agli estremi, cioè se $f(a) = f(b)$, allora esiste almeno un punto $c$ in $( a, \space b )$ dove la derivata prima si annulla. Geometricamente questo significa che esiste almeno un punto $c$ in cui la retta tangente alla curva è parallela all'asse $x$.
* **teorema di Lagrange**: esiste almeno un punto $c$ in  $( a, \space b )$ in cui $\dfrac{f(b) - f(a)}{b - a} = f'(c)$. Geometricamente questo significa che esiste almeno un punto $c$ in cui la retta tangente alla curva è parallela alla corda $AB$ che passa per i punti $A(a, \space f(a))$ e $B(b, \space f(b))$

Una delle più importanti conseguenze di questi due teoremi è che:
* quando $f'(x) > 0$ la funzione $f(x)$ è strettamente crescente
* quando $f'(x) < 0$ la funzione $f(x)$ è strettamente decrescente
* quando $f'(x) = 0$ la funzione $f(x)$ è costante

* il **teorema di Cauchy** riguarda due funzioni $f(x)$ e $g(x)$ entrambe continue in $[ a, \space b ]$ e derivabili al suo interno; richiede inoltre che $g'(x)$ non si annulli mai in $( a, \space b )$. In queste ipotesi, esiste almeno un punto $c \in ( a, \space b )$ per il quale vale la relazione $\dfrac{f(b) - f(a)}{g(b) - g(a)} = \dfrac{f'(c)}{g'(c)}$

### I teoremi di de L'Hospital e il calcolo dei limiti
I due **teoremi di de L'Hospital** si utilizzano per calcolare i limiti che si possono ricondurre alle forme di indecisione $\dfrac{0}{0}$ e $\dfrac{\infty}{\infty}$. Essi dicono che:
* se due funzioni $f(x)$ e $g(x)$, entrambe definite in un intorno $I$ di un punto $x_0$, soddisfamo le seguenti ipotesi:
* si annullano entrambe in $x_0$ oppure i loro limiti per $x \to x_0$ sono entrambi infiniti
* sono derivabili in $I$ eccettuato al più $x_0$
* $g'(x)$ non si annulla mai in $I$ eccettuato al più $x_0$
* esiste un limite per $x \to x_0$ del rapporto delle due derivate $f'(x)$ e $g'(x)$

allora il limite del rapporto delel due funzioni è uguale al limite del rapporto delle due derivate:

<div align="center">
$\lim\limits _{x \to x_0} \dfrac{f(x)}{g(x)} = \lim\limits _{x \to x_0} \dfrac{f'(x)}{g'(x)}$
</div>

In pratica, tutte le volte che un limite si presenta nella forma $\dfrac{0}{0}$ o $\dfrac{\infty}{\infty}$ e le due funzioni al numeratore e al denominatore sono derivabili, si può calcolare il limite del rapporto fra  le due derivate

## Punti estremanti e punti di inflessione
### Massimi e minimi relativi
Considerata una funzione $f(x)$ definita in un intervallo $[ a , b ]$:
* un punto $x_0 \in [ a , b ]$ è un **punto di minimo relativo** per $f(x)$ se $f(x_0)$ è il valore più piccolo che la funzione assume in un intorno di tale punto, cioè se esiste un intorno di $x_0$ per tutti i punti $x$ del quale $f(x) \geq f(x_0)$; in questo caso $f(x_0)$ è il minomo relativo della funzione;
* un punto $x_0 \in [ a , b ]$ è un **punto di massimo relativo** per $f(x)$ se $f(x_0)$ è il valore più grande che la funzione assume in un intorno di tale punto, cioè se esiste un intorno di $x_0$ per tutti i punti $x$ del quale $f(x) \leq f(x_0)$; in questo caso $f(x_0)$ è il massimo relativo della funzione;

### Criteri di individuazione
La derivata prima di una funzione rappresenta la pendenza della retta tangente alla curva; essa ci consente di conoscere quando una funzione è crescente (derivata positiva) e quando è decrescente (derivata negativa) ed inoltre ci è utile per calcolare i punti di massimo e di minimo relativi delle funzioni. In particolare, per individuare i punti estremanti si deve:
* trovare i punti che annullano la derivata prima o quelli in cui essa non esiste
* studiare il segno della derivata prima
* dedurre da esso quali punti sono di massimo o di minimo relativo

§IMMAGINE§

### Massimi e minimi assoluti
I **punti di massimo o di minimo assoluti** di una funzione $f(x)$ in un intervallo $[ a , b ]$ sono i punti in cui la funzione assume il valore più grande o il valore più piccolo rispetto a tutti gli altri punti dell'intervallo; essi, se esistono, vanno ricercati fra i massimi o i minimi relativi, oppure fra i valori assunti dalla funzione negli estremi dell'intervallo considerato.

### Concavità e flessi
La derivata seconda di una funzione rappresenta la concavità della curva: se è negativa la concavità è rivolta verso il basso, se è positiva è rivolta verso l'alto. I punti di flesso sono i punti in cui cambia la concavità della curva; per individuarli si deve:
* trovare i punti che annullano la derivata seconda o quelli in cui essa non esiste
* studiare il segno della derivata seconda
* dedurre da esso quali punti rappresentano dei flessi

### Massimi, minimi e flessi con le derivate successive
Per trovare i punti di massimo e di minimo relativo e i punti di flesso di una funzione $f(x)$, in alternativa ai metodi precedenti e se esistono le derivate successive di $f(x)$ fino a quella di ordine $n$, si può seguire questa procedura:
* si cercano i punti $x_0$ che annullano la derivata prima e si calcolano derivare successive in $x_0$ fino a che se ne trova una che è diversa da zero; se questa è di ordine $n$, allora:
  * se $n$ è pari e $f^n (x_0) > 0 \rightarrow x_0$ è un punto di minimo
  * se $n$ è pari e $f^n (x_0) < 0 \rightarrow x_0$ è un punto di massimo
  * se $n$ è dispari $\rightarrow x_0$ è un punto di flesso a tangente orizzontale
* si cercano i punti $x_0$ che annullano la derivata seconda e si calcolano derivare successive in $x_0$ fino a che se ne trova una che è diversa da zero; se questa è di ordine $n$, allora:
  * se $n$ è pari e $f^n (x_0) > 0 \rightarrow x_0$ la funzione è concava verso l'alto
  * se $n$ è pari e $f^n (x_0) < 0 \rightarrow x_0$ la funzione è concava verso il basso
  * se $n$ è dispari $\rightarrow x_0$ è un punto di flesso

## Lo studio di funzione
Per studiare in modo completo una funzione $f(x)$ si deve:
* determinare l'insieme di definzione $D$
* stabilirne le eventuali periodicità e simmetrie (funzioni pari e dispari)
* studiare il comportamento agli esstremi degli intervalli dell'insieme $D$ e trovare gli eventuali asintoti
* studiare il segno della funzione e determinare le eventuali intersezioni con gli assi cartesiani
* trpvare i punti di massimo e di minimo
* trovare i punti di flesso e studiare la concavità

Occorre poi tenere presente che:
* tutte le equazioni e le disequazioni che man mano si affrontano devono essere risolte nell'ambito del dominio della funzione
* di norma si calcolano prima i limiti della funzione e i suoi asintoti e poi il segno, ma questi due passaggi possono essere anche invertiti
* spesso lo studio della derivata seconda non è indispensabile se il comportamento della funzione è già ben delineato dall'individuazione dei punti di massimo e di minimo
* nel caso ci sia simmetria rispetto all'asse $y$ oppure rispetto all'origine, conviene studiare la funzione solo per $x \geq 0$ e poi rappresentare il suo grafico completo sfruttando tali simmetrie
* se una funzione è periodica di periodo $T$, conviene studiarla in un intervallo pari a $T$
* l'individuazione delle coordinate di qualche punto è spesso utile per ottenere un grafico migliore


### I grafici deducibili
Tracciato il grafico $C$ da di una funzione $f(x)$, da esso si possono dedurre quelli di:
* $y = |f(x)|$ mediante una simmetria rispetto all'asse $x$ delle parti negative di $C$
* $y = - f(x)$ mediante una simmetria rispetto all'asse $x$
* $y = f(x) + k$ mediante una traslazione di vettore $\vec v (0, \space k)$
* $y = f(x + h)$ mediante una traslazione di vettore $\vec v (-h, \space 0)$
* $y = f(|x|)$ mediante una simmetria rispetto all'asse $y$ della sola parte di $C$ che appartiene al semiasse positivo delle ascisse

## Gli integrali
### L'integrale indefinito
La funzione $F(x)$ è la **primitiva** di una funzione $f(x)$ in un intervallo $[a, \space b]$ se per tutti i punti di tale intervallo è $F'(x) = f(x)$.

Una funzione $f(x)$ ha infinite primitivev che sono però definite a meno di una costante additiva; l'insieme di tutte le primitive di $f(x)$ è il suo **integrale indefinito**: 

<div align="center">
$\int f(x) dx = F(x) + c$
</div>

### Le proprietà
L'integrale indefinito gode di alcune proprietà
* si può portare fuori dal simbolo di integrazione una costante moltiplicativa $\int k \cdot f(x) dx = k \int f(x) dx$ con $k \in \mathbb{R}$
* l'integrale delal somma di due o più funzioni è la somma degli integrali delle singole funzioni $\int [f_1 (x) + f_2 (x)] dx = \int f_1 (x) dx + \int f_2 (x) dx$

### Gli integrali immediati
Per trovare l'integrale delle funzioni elementari basta leggere la tabella delle derivate da dentra verso sinistra con alcuni accorgimenti:
* $\int x^k dx = \dfrac{1}{k + 1} x ^{k + 1} + c$
  * in particolare $\int dx = x + c$
* $\int [f(x)] ^k \cdot f'(x) dx = \dfrac{1}{k + 1} [f(x)] ^{k + 1} + c$
* $\int \dfrac{1}{x} dx = \ln |x| + c$
* $\int \dfrac{f'(x)}{f(x)} dx = \ln |f(x)| + c$
* $\int \cos x dx = \sin x + c$
* $\int f'(x) \cdot \cos f(x) dx = \sin f(x) + c$
* $\int \sin x dx = - \cos x + c$
* $\int f'(x) \cdot \sin f(x) dx = - \cos f(x) + c$
* $\int \dfrac{1}{\cos ^2 x}dx = \tan x + c$
* $\int \dfrac{f'(x)}{\cos ^2 x}dx = \tan f(x) + c$ 
* $\int \dfrac{1}{\sin ^2 x}dx = - \cot x + c$
* $\int \dfrac{f'(x)}{\sin ^2 x}dx = - \cot f(x) + c$
* $\int a^x dx = \dfrac{1}{\ln a} a^x + c$
  * in particolare $\int e^x dx = e^x + c$
* $\int f'(x) e ^{f(x)} dx = e ^{f(x)} + c$
* $\int \dfrac{1}{\sqrt{1 - x^2}} dx = \arcsin x + c = - \arccos x + c$
* $\int \dfrac{f'(x)}{\sqrt{1 - [f(x)] ^2}} dx = \arcsin f(x) + c = - \arccos f(x) + c$
* $\int \dfrac{1}{1 + x^2} dx = \arctan x + c = - \textrm{arccot} x + c$
* $\int \dfrac{f'(x)}{1 + [f(x)]^2} dx = \arctan f(x) + c = - \textrm{arccot} f(x) + c$

### L'integrazione delle funzioni razionali fratte
Per integrare una funzione razionale fratta che non rientri nelle precedenti forme, dopo avere eventualmente eseguito la divisione del numeratore per il denominatore in modo da ottenere una frazione propria, si segue una procedura particolare: 
* se il denominatore si può scomporre nel prodotto di due o più fattori:
  * si scompone il denominatore della frazione
  * si scrive la funzione come somma di altre frazioni che ahnno come denominatori i fattori delal scomposizione
  * si integra ciascuna frazione ottenuta
* se la frazione è del tipo $\dfrac{1}{a x^2 + b x + c}$ con $b^2 - 4 a c < 0$, si scrive il trinomio al denominatore come una somma di quadrati e si integra applicando la regola dell'arcotangente.

### L'integrale definito
Data una funzione $f(x)$ continua e positiva in un intervallo $[ a, \space b ]$, si chiama **trapezoide** la parte di piano delimitata dalla curva corrispondente, dall'asse $x$ e dalle rette $x = a$ e $x = b$.

L'area di un trapezoide è il limite per $\Delta x \to 0$ dell'area del plurirettangolo e prende il nome di **integrale definito** della funzione $f(x)$ nell'intervallo $[ a, \space b ]$. In simboli esso si indica con la scrittura

<div align="center">
$\int_{a}^{b} f(x) dx$
</div>

### Le proprietà
Le proprietà dell'integrale definito sono le seguenti:
* se gli estremi di integrazione sono uguali, l'integrale è uguale a zero: $\int_{a}^{a} f(x) dx = 0$
* se si scambiano gli estremi di integrazione, l'integrale cambia segno: $\int_{a}^{b} f(x) dx = - \int_{b}^{a} f(x) dx$
* se $c$ è un punto compreso fra $a$ e $b$, l'integrale fra $a$ e $b$ è uguale alal somma degli integrali fra $a$ e $c$ e fra $c$ e $b$: $\int_{a}^{b} f(x) dx = \int_{a}^{c} f(x) dx + \int_{c}^{b} f(x) dx$
* l'integrale fra $a$ e $b$ della somma di due o più funzioni continue è uguale alla somma degli integrali fra $a$ e $b$ di ciascuna funzione: $\int _{a} ^{b} [f _1 (x) + f _2 (x) + ... + f _n (x)] dx = \int _{a} ^{b} f _1 (x) dx + \int _{a} ^{b} f _2 (x) dx + ... + \int _{a} ^{b} f _n (x) dx$
* l'integrale fra $a$ e $b$ di una funzione continua $f(x)$ moltiplicata per una costante $k$ è uguale a $k$ volte l'integrale della funzione: $\int_{a}^{b} k \cdot f(x) dx = k \int_{a}^{b} f(x) dx$
* **Teorema della media**: se $f(x)$ è continua in un intervallo $[ a, \space b ]$, esiste almeno un punto $c \in [ a, \space b ]$ per il quale vale la relazione: $\int_{a}^{b} dx = (b - a) \cdot f(c)$

### La funzione integrale
Considerata una funzione $f(x)$ continua in un intervallo $[ a, \space b ]$, il suo integrale calcolto fra $a$ e un punto $x$ variabile in $[ a, \space b ]$ è essp stessp una funzione che si chiama **funzione integrale**; tale funzione ha espressione

<div align="center">
$F(x) = \int_{a}^{x} f(t) dt \qquad \text{con} \space x \in [a, \space b]$
</div>

La funzione integrale ha come proprietà che la sua derivata coincide con $f(x)$, cioè $F'(x) = f(x)$.

### Il calcolo di un integrale definito
Per calcolare il valore di un integrale definito si usa la **formula di Newton-Leibniz**; se $\varphi (x)$ è una primitiva di $f(x)$, si ha che:

<div align="center">
$\int_{a}^{b} f(t) dt = \left [ \varphi (x) \right] _a ^b = \varphi (b) - \varphi (a)$
</div>

### Il calcolo delle aree
Per calcolare l'area di una regione finita di piano delimitata da una funzione continua $f(x)$ e dall'asse delle ascisse in un intervallo $[ a, \space b ]$ si deve calcolare l'integrale definito di $f(x)$ fra $a$ e $b$ quando $f(x)$ è positiva o nulla, l'opposto di questo integrale se $f(x)$ è negativa.

In pratica, si individuano gli intervalli dell'asse $x$ nei quali la funzione $f(x)$ è poisitiva e quelli in cui è negativa e poi si calcolano gli integrali definiti in questi intervalli prendendoli con segno positivo quando $f(x) \geq 0$, con segno negativo quando $f(x) < 0$. 

<div align="center">
$\int_{a}^{b} f(x) dx - \int_{b}^{c} f(x) dx + \int_{c}^{d} f(x) dx$
</div>

§IMMAGINE§

Se la superficie di cui calcolare l'area è delimitata da più funzioni come nella figura a lato, si affrontano i seguenti passi:
* si individuano le ascisse dei punti di intersezione di ciascuna coppia di curve
* si calcolano gli integrali definiti in ciascuno degli intervalli individuati da dati punti, prestando attenzione ai segni delle aree:

<div align="center">
$\int_{a}^{b} f(x) dx - \int_{b}^{c} g(x) dx + \int_{c}^{a} h(x) dx$
</div>

§IMMAGINE§










