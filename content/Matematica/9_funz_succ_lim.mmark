---
title: "Funzioni, successioni e limite"
draft: false
weight: 9
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


- [Insiemi numerici e funzioni](#insiemi-numerici-e-funzioni)
  - [Gli insiemi di numeri reali](#gli-insiemi-di-numeri-reali)
  - [Intervalli, intorni e punti di accumulazione](#intervalli--intorni-e-punti-di-accumulazione)
  - [Funzioni](#funzioni)
  - [Monotonia e periodicità di una funzione](#monotonia-e-periodicita-di-una-funzione)
- [Funzioni e limiti](#funzioni-e-limiti)
  - [Le definizioni di limite](#le-definizioni-di-limite)
  - [Gli asintoti](#gli-asintoti)
  - [Teoremi sui limiti](#teoremi-sui-limiti)
  - [Le forme di indeterminazione](#le-forme-di-indeterminazione)
  - [I limiti notevoli](#i-limiti-notevoli)
  - [Infiniti e infinitesimi](#infiniti-e-infinitesimi)
  - [Le successioni](#le-successioni)
  - [Il comportamento di una successione](#il-comportamento-di-una-successione)
- [Funzioni e continuità](#funzioni-e-continuita)
  - [Le funzioni continue e i criteri per la continuità](#le-funzioni-continue-e-i-criteri-per-la-continuita)
  - [I punti di discontinuità](#i-punti-di-discontinuita)
  - [Le proprietà delle funzioni continue](#le-proprieta-delle-funzioni-continue)
  - [Gli asintoti di una funzione](#gli-asintoti-di-una-funzione)
  - [Il grafico probabile](#il-grafico-probabile)

## Insiemi numerici e funzioni
### Gli insiemi di numeri reali
Un insieme $\mathbb{E}$ di numeri reali si dice:
* **limitato superiormente** se esiste un numero $k$, non necessariamente appartenente a $E$, che è maggiore di tutti gli elementi di $E$
* **limitato inferiormente** se esiste un numero $h$, non necessariamente appartenente a $E$, che è minore di tutti gli elementi di $E$

Un insieme che è limitato sia inferiormente che superiormente si dice semplicemente **limitato**.
* L'**estremo inferiore** di un insieme $E$ è il più grande dei numeri $h$ e, se appartiene all'insieme, è il **minimo** di $E$
* L'**estremo superiore** di un insieme $E$ è il più piccolo dei numeri $k$ e, se appartiene all'insieme, è il **massimo** di $E$

### Intervalli, intorni e punti di accumulazione
Si chiama **intervello** un qualunque insieme di numeri reali compresi fra altri due $a$ e $b$, dove $a$ o $b$ possono essere finiti o infiniti. In particolare:
* $(a, \space b)$ è un intervallo aperto che corrisponde all'insieme degli $x$ tali che $a < x < b$
* $[a, \space b]$ è un intervallo chiuso che corrisponde all'insieme degli $x$ tali che $a \leq x \leq b$

In pratica, la parentesi tonda indica che l'estremo dell'intervallo non appartiene all'insieme, la parentesi quadra indica che gli appartiene; sui simboli di $\infty$ si usa solo la parentesi tonda.

**Intorno** di un punto $x_0$ è ogni intervallo aperto che contiene $x_0$ al suo interno; intorno di $ + \infty$ è un qualunque intervallo del tipo $(a, \space + \infty)$, intorno di $ - \infty$ è un qualunque intervallo del tipo $( - \infty, \space b)$, intorno di infinito è l'unione di un intorno $ + \infty$ con un intorno $ - \infty$.

Un punto $x_0$ si dice di **accumulazione** per un insieme $E$ se ogni intorno di $x_0$ contiene infiniti punti di $E$.

### Funzioni
Una **funzione** è una corrispondenza univoca fra un insieme $D$ di elementi $x$ ed un insieme $E$ di elementi $y$, cioè una legge che ad ogni elementi di $D$ associa uno e un solo elemento di $E$.

Se $D$ ed $E$ sono insieme numerici, la legge che $y$ ad $x$ su può esprimere mediante una relazione algebrica nella forma $y = f(x)$.

L'elemento $y$ che corrisponde ad un particolare $x$ si dice **immagine** di $x$; l'insieme delle immagini è il **codominio** della funzione.

Ogni elemento $x$ che resta associato ad un elemento $y$ si dice **controimmagine**; l'insieme delle controimmagini rappresenta l'**insieme di definizione** della funzione.

Una funzione $f: \space D \to E$ si dice:
* **surietiva** se $f(D) = E$
* **iniettiva** se a elementi distinti in $D$ corrispondono elementi distinti in $E$
* **biiettiva** se è iniettiva e suriettiva

Le funzioni biiettive sono corrispondenze biunivoche e sono le sole funzioni invertibili

Se una funzione $f(x)$ è definita in un punto $x_0$ e si verifica che:
* $f(x_0) \geq f(x)$ per ogni $x$ del dominio, allora si dice che $x_0$ è un **punto di massimo assoluto** e che $f(x_0)$ è il massimo assoluto della funzione
* $f(x_0) \leq f(x)$ per ogni $x$ del dominio, allora si dice che $x_0$ è un **punto di minimo assoluto** e che $f(x_0)$ è il minimo assoluto della funzione

### Monotonia e periodicità di una funzione
Una funzione $f(x)$ di dominio $D$ è:
* **monotòna crescente** in un intervallo $I \subseteq D$ se $\forall x_1, \space x_2 \in I$ con $x_1 < x_2$ si ha che $f(x_1) < f(x_2)$. Se in quest'ultima relazione vale anche il segno di uguaglianza, cioè se $f(x_1) \leq f(x_2)$, allora la funzione monotòna non descrescente, cioè in pratica cresce o tutt'al più si mantiene costante, ma non descresce mai
* **monotòna decrescente** in un intervallo $I \subseteq D$ se $\forall x_1, \space x_2 \in I$ con $x_1 < x_2$ si ha che $f(x_1) > f(x_2)$. Se in quest'ultima relazione vale anche il segno di uguaglianza, cioè se $f(x_1) \geq f(x_2)$, allora la funzione monotòna non crescente, cioè in pratica decresce o tutt'al più si mantiene costante, ma non cresce mai
* **pari** se $f( - x) = f(x)$ ed allora il suo grafico presenta una simmetria rispetto all'asse $y$
* **dispari** se $f(x) = - f(x)$ ed allora il suo grafico presenta una simmetria rispetto all'origine
* **periodica** di periodo $k$ se $f(x + k) = f(x)$, in particolare:
  * $\sin kx$ e $\cos kx$ sono periodiche di periodo $\dfrac{2 \pi}{k}$
  * $\tan kx$ e $\cot kx$ sono periodiche di periodo $\dfrac{\pi}{k}$


## Funzioni e limiti
### Le definizioni di limite
Una funzione ha per limite un numero $l$ finito per $x \to c$ (con $c$ finito o infinito) se la disequazione $|f(x) - l | < \varepsilon$ ha fra le sue soluzioni un intorno di $c$.

Una funzione ha per limite $\infty$ per $x \to c$ (con $c$ finito o infinito) se la disequazione $|f(x)| > M$ è verificata in un intorno di $c$.


### Gli asintoti
Una funzione $f(x)$ possiede:
* **asintoto orizzontale** di equazione $y = l$ se $\lim\limits_{x \to \infty} f(x) = l$
* **asintoto verticale** di equazione $x = c$ se $\lim\limits_{x \to c} f(x) = \infty$


### Teoremi sui limiti
Se $\lim\limits_{x \to c} f(x) = l$ e $\lim\limits_{x \to c} g(x) = l'$ e $l$ e $l'$ sono due valori finiti, allora:
* $\lim\limits_{x \to c} [f(x) \pm g(x)] = l \pm l'$
* $\lim\limits_{x \to c} [f(x) \cdot g(x)] = l \cdot l'$
* $\lim\limits_{x \to c} k \cdot f(x) = k \cdot f(x)$ con $k \in \mathbb{R}$
* $\lim\limits_{x \to c} [f(x)] ^n = l^n$
* $\lim\limits_{x \to c} \dfrac{f(x)}{g(x)} = \dfrac{l}{l'}$ se $l' \neq 0$

### Le forme di indeterminazione
Nel calcolo di un limite, generalmente quando $c$ è infinito oppure i limiti $l$ e $l'$ sono nulli, si può giungere a quelle si chiamano **forme di indeterminazione** che sono:
* $( + \infty) - (+ \infty)$
* $( + \infty) + (- \infty)$
* $0 \cdot (\pm \infty)$
* $\dfrac{\pm \infty}{\pm \infty}$
* $\dfrac{0}{0}$
* $1^{\pm \infty}$
* $0^0$
* $(\pm \infty) ^0$

Per risolvere alcune di queste forme occorre tenere presenti queste regole:
* il limite per $x \to \infty$ di un polinomio è uguale al limite del termine di grado massimo:

<div align="center">
$\lim\limits_{x \to \infty} (a_0 x^n + a_1 x^{n - 1} + ... + a_{n - 1} x + a_n) = \lim\limits_{x \to \infty} a_0 x^n$
</div>

* il limite per $x \to \infty$ del rapporto fra due polinomi è uguale al limite del rapporto fra i termini di grado massimo:

<div align="center">
$\lim\limits_{x \to \infty} \dfrac{a_0 x^k + ... + a_k}{b_0 x^h + ... + b_h} = \lim\limits_{x \to \infty} \dfrac{a_0 x^k}{b_0 x^h}$
</div>

  e si ha che:
  * se $k > h$ il limite vale $\infty$
  * se $k = h$ il limite vale $\dfrac{a_0}{b_0}$
  * se $k < h$ il limite vale $0$

* se $\lim\limits_{x \to c} \dfrac{A(x)}{B(x)}$ si presenta nella forma $\dfrac{0}{0}$, si semplifica la frazione scomponendo i polinomi $A(x)$ e $B(x)$ e si calcola il limite della funzione che si ottiene
* se $\lim\limits_{x \to \infty} (\sqrt{A(x)} \pm \sqrt{B(x)})$ si presenta nella forma $\infty - \infty$, si moltiplica e si divide per $(\sqrt{A(x)} \mp \sqrt{B(x)})$ e si calcola il limite della funzione che si ottiene.

### I limiti notevoli
Valgono i seguenti limiti notevoli:
* $\lim\limits_{x \to 0} \dfrac{\sin x}{x} = 1$ e $\lim\limits_{x \to c} \dfrac{\sin f(x)}{f(x)} = 1$ quando $f(x) \to 0$ per $x \to c$
* $\lim\limits_{x \to \infty} \left ( 1 + \dfrac{1}{x} \right) ^x = e$ e $\lim\limits_{x \to c} \left ( 1 + \dfrac{1}{f(x)} \right) ^{f(x)} = e$ quando $f(x) \to \infty$ per $x \to c$

### Infiniti e infinitesimi
Si dice che:
* la funzione $y = f(x)$ è un **infinitesimo** per $x \to c$ se $\lim\limits_{x \to c} f(x) = 0$
* la funzione $y = f(x)$ è un **infinito** per $x \to c$ se $\lim\limits_{x \to c} f(x) = \infty$

Di due funzioni $f(x)$ e $g(x)$ entrambe infinitesime per $x \to c$ diciamo che:
* $f(x)$ è di ordine superiore a $g(x)$ se $\lim\limits_{x \to c} \dfrac{f(x)}{g(x)} = 0$
* $f(x)$ è dello stesso ordine di $g(x)$ se $\lim\limits_{x \to c} \dfrac{f(x)}{g(x)} = l \neq 0$
* $f(x)$ è di ordine inferiore a $g(x)$ se $\lim\limits_{x \to c} \dfrac{f(x)}{g(x)} = \infty$

Di due funzioni $f(x)$ e $g(x)$ entrambe infinite per $x \to c$ diciamo che:
* $f(x)$ è di ordine superiore a $g(x)$ se $\lim\limits_{x \to c} \dfrac{f(x)}{g(x)} = \infty$
* $f(x)$ è dello stesso ordine di $g(x)$ se $\lim\limits_{x \to c} \dfrac{f(x)}{g(x)} = l \neq 0$
* $f(x)$ è di ordine inferiore a $g(x)$ se $\lim\limits_{x \to c} \dfrac{f(x)}{g(x)} = 0$

### Le successioni
Una **successione** è una funzione che ha come dominio l'insieme $\mathbb{N}$ dei numeri naturali. I suoi termini si possono rappresentare:

* mediante il suo termine generale $a_0$ espresso in funzione di $n$
* mediante una formula ricorsiva definita in questo modo:
  * $a_0$ è valore del primo termine della successione

  * $a_n$ è regola che esprime $a_0$ in funzione di $a _{n-1}$

### Il comportamento di una successione
Una successione può essere:

* **convergente** se $\lim\limits _{n \to + \infty} a_n = l$ cioè se $\forall \varepsilon > 0$ esiste un indice $\nu$ tale che $\forall n > \nu$ sia $|a_n - l| < \varepsilon$

* **divergente** se $\lim\limits _{n \to + \infty} a_n = + \infty$  $\lim\limits _{n \to + \infty} a_n = - \infty$ cioè se, $\forall M > 0$, esiste un indice $\nu$ tale che $\forall n > \nu$ sia rispettivamente $a_n > M$ o $a_n < - M$

* **irregolare** se né converge né diverge

Per il calcolo del limite di una successione valgono teoremi analoghi a quelli per i limiti delle funzioni di numeri reali.


## Funzioni e continuità
### Le funzioni continue e i criteri per la continuità
Una funzione $f(x)$ definita in un insieme $D$ è **continua** in un punto $x_0 \in D$ e di accumulazione per $D$ se $\lim\limits _{x \to x_0} f(x) = f(x_0)$

Quindi per vedere se una funzione è continua in $x_0$ si deve:
* calcolare $f(x_0)$
* calcolare $\lim\limits _{x \to x_0} f(x)$
* verificare che i due valori trovati coincidano

Se due funzioni $f(x)$ e $g(x)$ sono continue nel punto $x_0$ allora sono continue in $x_0$ anche le funzioni:
* $- f(x)$ e $|f(x)|$
* $f(x) \pm g(x)$
* $f(x) \cdot g(x)$ e in particolare $k f(x)$ e $[f(x)] ^n$
* $\dfrac{f(x)}{g(x)}$ e in particolare $\dfrac{1}{g(x)}$ se $g(x_0) \neq 0$

### I punti di discontinuità
Se una funzione non è continua un un punto $x_0$ si dice $x_0$ è un **punto di discontinuità** o anche che è un **punto singolare**.

I punti di discontinuità si possono classificare con il seguente criterio:
* discontinuità di **prima specie** se il limite sinistro e il limite destro sono finiti ma diversi:

<div align="center">
$\lim\limits _{x \to x_0 ^-} f(x) = l_1 \space \wedge \space \lim\limits _{x \to x_0 ^+} f(x) = l_2$ con $l_1 \neq l_2$
</div>

* discontinuità di **seconda specie** se almeno uno dei due limiti dalla sinistra o dalla destra è infinito o non esiste:

<div align="center">
$\lim\limits _{x \to x_0 ^-} f(x) = \infty \space \vee \space \lim\limits _{x \to x_0 ^+} f(x) = \infty \space \vee \space \nexists \lim\limits _{x \to x_0 ^\pm} f(x)$
</div>

* discontinuità di **terza specie** o **eliminabile** se esiste finito il limite per $x \to x_0$ ma tale valore è diverso da quello assunto dalla funzione o se la funzione non esiste in $x_0$:

<div align="center">
$\lim\limits _{x \to x_0} f(x) \neq f(x_0)$ oppure $\lim\limits _{x \to x_0} f(x) = l \space \wedge \space \nexists f(x_0)$
</div>

### Le proprietà delle funzioni continue
Le proprietà delle funzioni continue sono elencate dai seguenti teoremi:
* **permanenza del segno**: se una funzione è continua in un punto $x_0$ e $f(x_0) \neq 0$, esiste un intorno di tale punto in cui la funzione assume lo stesso segno di $f(x)$
* **esistenza degli zeri**: se una funzione $f(x)$ è continua in un intervallo $[ a, \space b ]$ e se $f(a)$ e $f(b)$ hanno segno opposto, allora esiste almeno un punto interno ad $[ a, \space b ]$ in cui la funzione si annulla
* **di Weierstrass**: se una funzione $f(x)$ è continua in un intervallo $[ a, \space b ]$, essa è limitata in tale intervallo ed esiste almeno un punto in cui assume il valore massimo ed almeno un punto in cui assume il valore minimo
* **di Bolzano-Darboux**: se una funzione $f(x)$ è continua in un intervallo chiuso e limitato $[ a, \space b ]$ e se $x_1$ e $x_2$ sono due punti di tale intervallo tali che $f(x_1) \neq f(x_2)$, allora la funzione assume almeno una volta tutti i valori compresi fra $f(x_1)$ e $f(x_2)$ al variare di $x$ in $(x_1, \space x_2)$

Dagli ultimi due teoremi si deduce poi che se $f(x)$ è continua in $[ a, \space b ]$, allora assume almeno una volta ciascun valore compreso tra il minimo e il massimo.


### Gli asintoti di una funzione
Una funzione $f(x)$ di dominio $D$:
* ha un **asintoto verticale** di equazione $x = x_0$ se $\lim\limits _{x \to x_0} f(x) = \infty$
* ha un **asintoto orizzontale** di equazione $y = l$ se $\lim\limits _{x \to \infty} = l$
* ha un **asintoto obliquo** di equazione $y = mx + q$ se esistono finiti i limiti

<div align="center">
$\lim\limits _{x \to \infty} \dfrac{f(x)}{x} = m$ e $\lim\limits _{x \to \infty} [f(x) - mx] = q$ e se $m \neq 0$
</div>

### Il grafico probabile
Il **grafico probabile** di una funzione $f(x)$ si determina calcolando
* l'insieme di definizione $D$
* il comportamento agli estremi $D$
* gli eventuali asintoti
* le intersezioni, se esistono, con gli assi cartesiani
* il segno
* le coordinate di alcuni punti significativi

