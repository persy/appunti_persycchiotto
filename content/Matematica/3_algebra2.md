---
title: "Algebra 2"
draft: false
weight: 3
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

## I sistemi lineari

### I sistemi
Un'equazione in due o più variabili, se non è impossibile, ammette sempre infinite soluzioni; se di due o più equazioni
in due o più incognite si vogliono trovare le soluzioni comuni si deve risolvere il sistema delle loro equazioni. Scrivere
un sistema di equazioni significa quindi richiedere che tutte le equazioni siano verificate per gli stessi valori delle variabili.

Il grado di un sistema è il prodotto dei gradi delle sue equazioni; in particolare un sistema è di primo grado se tutte le
sue equazioni sono di primo grado.
Un sistema può essere:
* determinato se ha un numero finito di soluzioni
* indeterminato se ha infinite soluzioni
* impossibile se non ha soluzioni.

### I principi di equivalenza
Due sistemi sono equivalenti se hanno le stesse soluzioni.

Come nel caso delle equazioni, per risolvere un sistema, supponiamo di due equazioni in due incognite, si deve passare da una forma ad un'altra ad essa equivalente fino ad arrivare a una del tipo 

<div align="center">
$\begin{cases}
x = k \\
y = h 
\end{cases}$
</div> 
 
in questo caso la soluzione del sistema è la coppia ordinata $(k, \space h)$.

I principi di equivalenza che valgono per un sistema di equazioni sono i seguenti.
* **principio di sostituzione**. Se in un sistema si sostituisce ad una incognita la sua espressione ricavata da un'altra equazione, si ottiene un sistema equivalente a quello dato.
* **principio di riduzione**. Se in un sistema si sommano membro a membro le sue equazioni (tutte o alcune) e si sostituisce l'equazione ottenuta ad una di esse, si ottiene un sistema equivalente a quello dato.

### I sistemi lineari
Un sistema è lineare se è di primo grado. Se è composto da due equazioni in due incognite $x$ e $y$ la sua forma normale è la seguente

<div align="center">
$\begin{cases}
ax + by = c \\
dx + ey = f 
\end{cases}$ 
</div>

I metodi per la risoluzione di un sistema si basano sui principi di equivalenza e sono i seguenti:
* il **metodo di sostituzione**, che consiste nel ricavare l'espressione di una variabile da una delle equazioni e sostituire tale espressione nelle altre
* il **metodo di riduzione**, che consiste nel sostituire ad una delle equazioni quella che si ottiene sommando membro a membro l'equazione stessa con un'altra (dopo averle eventualmente moltiplicate per un opportuno fattore non nullo), in modo da eliminare una delle variabili
* il **metodo del confronto**, che consiste nel ricavare l'espressione della stessa variabile da due equazioni e nel confrontare le espressioni ottenute.

### Le matrici e i determinanti
Una tabella di numeri della forma 

<div align="center">
$\begin{bmatrix}
a & b\\ 
c & d
\end{bmatrix}$ 
</div>

si chiama matrice e poiché ha due righe e due colonne si dice che è una matrice quadrata di ordine due. Ad ogni matrice di questo tipo si può associare un numero, chiamato **determinante**,
che si calcola in questo modo:

<div align="center">
$
\begin{vmatrix}
a & b\\ 
c & d
\end{vmatrix} = ad - bc
$
</div>

### Il metodo di Cramer
Per risolvere un sistema lineare, oltre ai precedenti metodi, si può usare uno schema di risoluzione che prende il nome di metodo di Cramer. Relativamente ai sistemi lineari di due equazioni in due incognite scritti in forma normale, si devono calcolare i seguenti **determinanti**:

<div align="center">
$\Delta =
\begin{vmatrix}
a & b\\ 
c & d
\end{vmatrix} = ae - bd$
</div>

<div align="center">
$\Delta x =
\begin{vmatrix}
c & b\\ 
f & e
\end{vmatrix} = ce - bf$
</div>

<div align="center">
$\Delta y =
\begin{vmatrix}
a & c\\ 
d & f
\end{vmatrix} = af - cd$
</div>

e si verifica che:

* se $\Delta \neq 0$ il sistema è determinato con soluzione 

<div align="center">
$\begin{cases}
x = \dfrac{\Delta x}{\Delta} \\
\\ 
y = \dfrac{\Delta x}{\Delta}  
\end{cases}$
</div>

* se $\Delta = 0$ e $\Delta x = \Delta y = 0$ il sistema è indeterminato
* se $\Delta = 0$ e $\Delta x \neq 0$ oppure $\Delta \neq 0$ il sistema è impossibile.

Alle stesse conclusioni si può giungere anche analizzando i rapporti tra i coefficienti delle due equazioni; si verifica
infatti che:

* il sistema è **determinato** se $\dfrac{a}{d} \neq \dfrac{b}{e}$
* il sistema è **indeterminato** se  $\dfrac{a}{d} = \dfrac{b}{e} = \dfrac{c}{f}$
* il sistema è impossibile se $\dfrac{a}{d} = \dfrac{b}{e} \neq \dfrac{c}{f}$


## I radicali

### La funzione radice e i radicali
Nell'insieme $\mathbb{R}^+ _0$ dei numeri reali positivi o nulli l'operazione di elevamento a potenza si può invertire e l'operazione
inversa è l'estrazione di radice.

Dato un qualunque numero reale $a \geq 0$, si dice radice $n$-esima di $a$ il numero non negativo $b$ per il quale $b^n = a$.

La radice $n$-esima di $a$ si indica con il simbolo $\sqrt[n]{a}$.

### La proprietà invariantiva
I radicali in $\mathbb{R}^+ _0$ godono della fondamentale **proprietà invariantiva**:

* se l'indice della radice e l'esponente del radicando vengono moltiplicati o divisi per uno stesso numero intero positivo, si ottiene un radicale che ha lo stesso valore di quello dato: $\sqrt[n]{a^m} = \sqrt[np]{a^{mp}}; \; \forall p \in Z^+$

Grazie a questa proprietà si possono eseguire le seguenti operazioni:

* semplificare un radicale dividendo indice della radice ed esponente del radicando per il loro M.C.D.
* ridurre due o più radicali allo stesso indice che è il m.c.m fra gli indici delle radici
* moltiplicare o dividere due radicali se questi hanno lo stesso indice:

<div align="center">
$\sqrt[n]{a} \cdot \sqrt[n]{b} = \sqrt[n]{ab}$
</div>



<div align="center">
$\dfrac{\sqrt[n]{a}}{\sqrt[n]{b}} = \sqrt[n]{\dfrac{a}{b}}$
</div>

* portar dentro o portar fuori dal simbolo di radice i possibili fattori.

Quando due radicali non hanno lo stesso indice, per trovare il loro prodotto o quoziente si devono prima ricondurre allo stesso indice.

### Radicali e moduli
Quando si eseguono delle operazioni sui radicali, si deve prestare attenzione a che:

* il dominio dell'espressione che si ottiene come risultato sia lo stesso di quello dell'espressione data
* il segno dell'espressione che si ottiene come risultato sia lo stesso di quello dell'espressione data.

In caso contrario, si deve valutare di quali fattori è necessario considerare il modulo al fine di mantenere lo stesso dominio e lo stesso segno.

### Operazioni con i radicali

* **Moltiplicazione e divisione**: si possono eseguire solo tra radicali dello stesso indice.
    * Radicali quadratici: $\sqrt{a} \cdot \sqrt{b} = \sqrt{ab}$; $\dfrac{\sqrt{a}}{\sqrt{b}}= \sqrt{\dfrac{a}{b}}$


    * Radicali cubici: $\sqrt[3]{a} \cdot \sqrt[3]{b} = \sqrt[3]{ab}$; $\dfrac{\sqrt[3]{a}}{\sqrt[3]{b}}= \sqrt[3]{\dfrac{a}{b}}$

* **Addizione e sottrazione**: si possono eseguire solo tra radicali simili.
    * Radicali quadratici: $\sqrt{a} + 3 \sqrt{a} = 4 \sqrt{a}$
    
    * Radicali cubici: $2 \sqrt[3]{a} + \sqrt[3]{a} = 3 \sqrt[3]{a}$


* **Potenza**: si eleva a potenza l'argomento del radicale $(\sqrt{a} ) ^3 = \sqrt{a^3}$

### I radicali quadratici doppi
Un radicale quadratico doppio è un radicale che ha la forma $\sqrt{a \pm \sqrt{b}}$.

Se $a^2 - b$ è un quadrato perfetto, il radicale si può trasformare nella somma o differenza di due radicali semplici con la formula:

<div align="center">
$\sqrt{a \pm \sqrt{b}} = \sqrt{\dfrac{a + \sqrt{a^2 -b}}{2}} \pm \sqrt{\dfrac{a - \sqrt{a^2 -b}}{2}}$
</div>



### La razionalizzazione
Razionalizzare una frazione che ha un denominatore che contiene dei radicali significa scriverla in modo che il denominatore diventi un'espressione razionale. Per fare questo si devono moltiplicare il numeratore e il denominatore della frazione per un opportuno **fattore razionalizzante** che ha una forma diversa a seconda dei casi:

* se la frazione è del tipo $\dfrac{1}{\sqrt{a}}$; il fattore razionalizzante è $\sqrt{a}$
* se la frazione è del tipo $\dfrac{1}{\sqrt[3]{a^k}}$; il fattore razionalizzante è $\sqrt[3]{a^{3 - k}}$ con $k < 3$
* se la frazione è del tipo $\dfrac{1}{\sqrt{a} \pm \sqrt{b}}$; il fattore razionalizzante è $\sqrt{a} \mp \sqrt{b}$
* se la frazione è del tipo $\dfrac{1}{\sqrt[3]{a} \pm \sqrt[3]{b}}$; il fattore razionalizzante è $(\sqrt[3]{a^2} \mp \sqrt[3]{ab} + \sqrt[3]{b^2})$

### Le potenze ad esponente razionale
Un radicale di argomento $a \geq 0$ si può scrivere sotto forma di potenza ad esponente razionale con la seguente corrispondenza: $\sqrt[n]{a^m} = a^{\frac{m}{n}}$.
Alle potenze ad esponente frazionario si possono applicare proprietà analoghe a quelle delle potenze ad esponente
intero.

## Il piano cartesiano e la retta

### Il sistema di ascisse sulal retta
Fissato su una retta orientata un sistema di ascisse:

* la misura del segmento di estremi $A(x)$ e $B(x_B)$ è uguale a: $|x_B - x_A|$
* l'ascissa del punto medio del segmento $AB$ è: $\dfrac{x_A + x_B}{2}$

### Il sistema di riferimento cartesiano nel piano

Fissato nel piano un sistema di riferimento cartesiano ortogonale e dati due punti $A(x_A, \space y_A)$ e $B(x_B, \space y_B)$:

* la distanza fra $A$ e $B$ è uguale a: $\overline{AB} = \sqrt{(x_B - x_A) ^2 + (y_B - y_A) ^2}$
    + in particolare, se $A$ e $B$ hanno la stessa ordinata: $\overline{AB} = |x_B - x_A|$
    + se $A$ e $B$ hanno la stessa ascissa: $\overline{AB} = |y_B - y_A|$
* le coordinate del punto $M$ medio fra $A$ e $B$ sono: $x_M = \dfrac{x_A + x_B}{2}$ e $y_M = \dfrac{y_A + y_B}{2}$

### Le isometrie nel piano cartesiano
Un'isometria è una funzione che ad ogni punto del piano fa corrispondere un altro punto in modo che a segmenti congruenti corrispondano segmenti congruenti. In un sistema di assi cartesiani ortogonali, le isometrie più semplici sono le simmetrie rispetto agli assi cartesiani e rispetto a un punto (l'origine o qualsiasi altro punto) e le traslazioni.

Dato un punto $P(x, \space y)$:

* il suo **simmetrico rispetto all'asse** $x$ è il punto ${P}'(x, \space -y)$
* il suo **simmetrico rispetto all'asse** $y$ è il punto ${P}'(-x, \space y)$
* il suo **simmetrico rispetto all'origine** $O$ è il punto ${P}'(-x, \space -y)$
* il suo **simmetrico rispetto al punto** $A(a, \space b)$ è il punto ${P}'(2a - x, \space 2b - y)$
* il suo corrispondente nella **translazione** di vettore $\vec v (v_x, \space v_y)$ è il punto ${P}'(x + v_x, \space y + v_y)$

### L'equazione della retta
In un sistema di riferimento cartesiano ortogonale, una retta ha equazione:

* $x = h$ se è parallela all'asse $y$; in particolare l'asse $y$ ha equazione $x = 0$
* $y = k$ se è parallela all'asse $x$; in particolare l'asse $x$ ha equazione $y = 0$
* $y = mx$ se passa per l'origine
* $y = mx + q$ se non passa per l'origine

La forma implicita dell'equazione di una retta è $ax + by + c = 0$

In particolare poi:

* $y = x$ è l'equazione della bisettrice del primo e terzo quadrante
* $y = -x$ è l'equazione della bisettrice del secondo e quarto quadrante

### Il coefficiente angolare di una retta
Il parametro $m$ rappresenta il coefficiente angolare e si ha che:

* se $m > 0$ la retta forma un angolo acuto con la direzione poisitiva dell'asse $x$
* se $m < 0$ la retta forma un angolo ottuso con la direzione poisitiva dell'asse $x$ 
* se $m = 0$ la retta è parallela all'asse $x$

Una retta parallela all'asse $y$ non ha un coefficiente angolare.

Se sono note le coordinate $(x_1, \space y_1)$ e $(x_2, \space y_2)$ di due punti di una retta ed è $x_1 \neq x_2$: $m = \dfrac{y_2 - y_1}{x_2 - x_1}$

### Come scrivere l'equazione di una retta
Se di una retta si conoscono le coordinate di un punto $(x_0, \space y_0)$ ed il coefficiente angolare $m$, la sua equazione si trova con la formula $y - y_0 = m(x - x_0)$.

Se di una retta si conoscono le coordinate di due punti $(x_1, \space y_1)$ e $(x_2, \space y_2)$ e se la retta non è parallela agli assi cartesiani, la sua equazione si trova con la formula $\dfrac{y - y_1}{y_2 - y_1} = \dfrac{x - x_1}{x_2 - x_1}$.

La condizione di parallelismo fra due rette è $m = {m}'$.

La condizione di perpendicolarità fra due rette è $m \cdot {m}' = -1$

### Altre considerazioni sulla retta
Per trovare il **punto di intersezione di due rette** si deve risolvere il sistema formato dalle loro equazioni. Le situazioni che si possono presentare sono:

* il sistema è determinato e allora le due rette si intersecano in un punto
* il sistema è indeterminato e allora le due rette coincidono (sono in realtà la stessa retta)
* il sistema è impossibile e allora le due rette sono parallele e non coincidenti

La **distanza** $d$ del punto $P(x_0, \space y_0)$ dalla retta $r$ di equazione $ax + by + c = 0$ si calcola con la formula:

<div align="center">
$d = \dfrac{|a x_0 + b y_0 + c|}{\sqrt{a^2 + b^2}}$
</div>

### Gli zeri di una funzione e le soluzioni di una disequazione
Se il grafico di una funzione $f(x)$ interseca l'asse $x$ in uno o più punti, di ciascuna delle ascisse di questi punti si dice che rappresenta uno **zero** della funzione.

La soluzione di ogni equazione lineare $ax + b = 0$ può quindi essere interpretata come lo zero della funzione $y = ax + b$, cioè come l'ascissa del punto di intersezione di una retta con l'asse $x$.

Anche le soluzioni della disequazione $ax + b > 0$ oppure $ax + b < 0$ si possono interpretare in modo grafico ricercando le ascisse dei punti della retta che hanno una ordinata rispettivamente positiva o negativa.

### I fasci di retta
L'insieme delle rette che passano per $P(x_0, \space y_0)$ è un fascio proprio di rette la cui equazione è $y - y_0 = m(x - x_0)$, con $m$ parametro variabile.

L'insieme delle rette parallele di coefficiente angolare $m$ è un fascio improprio di rette la cui equazione è $y = mx + k$, con $k$ parametro variabile.

## Luoghi di punti e funzioni

### Luoghi di punti
Luogo dei punti è l'insieme di tutti e soli i punti che godono di una medesima proprietà $P$.
Fissato nel piano un sistema di assi cartesiani ortogonali, un luogo di punti si può rappresentare mediante una relazione algebrica fra le coordinate $(x, \space y)$ dei suoi punti

### Parabola

* la parabola è il luogo dei punti del piano equidistanti da un punto fisso detto **fuoco** e da una retta fissa detta **direttrice**. È una curva simmetrica rispetto alla retta che passa per il fuoco ed è perpendicolare alla direttrice. Il punto. Il punto di intersezione di tale asse di simmetria con la parabola si chiama **vertice**.
* in un sistema di riferimento cartesiano ortogonale, una parabola che ha l'asse di simmetria parallelo all'asse $y$ ha equazione $y = ax^2 + bx + c$. 

Se $a > 0$, la parabola volge la concavità verso l'alto, se $a < 0$ la concavità è verso il basso.

Posto $\Delta = b^2 - 4ac$, il vertice è il punto $V \left ( - \dfrac{b}{2a}, \space - \dfrac{\Delta}{4a} \right )$

IMMAGINI PARABOLE: vertice, delta positivo e negativo

### Proporzionalità
Due insiemi di grandezze in corrispondenza biunivoca sono:

* **direttamente proporzionali**  se il rapporto fra due qualsiasi elementi del primo insieme è uguale al rapporto fra i corrispondenti due elementi del secondo insieme; in tal caso si verifica che è costante il rapporto tra le misure di elementi che si corrispondono; tale costante prende il nome di costante di proporzionalità diretta
* **inversamente proporzionali** se il rapporto fra due qualsiasi elementi del primo insieme è uguale al rapporto inverso fra i corrispondenti due elementi del secondo insieme; in tal caso si verifica che è costante il prodotto fra le misure di elementi che si corrispondono; tale costante prende il nome di costante di proporzionalità inversa

In un sistema di riferimento cartesiano ortogonale:

* una relazione di proporzionalità diretta di costante $m$ è rappresentata dalla retta di equazione $y = mx$
* Una relazione di proporzionalità inversa di costante $k$ è rappresentata dall'iperbole di equazione $xy = k$

IMMAGINI PROPORZIONALITA'

### Funzioni circolari

Considerata la circonferenza goniometrica, avente centro nell'origine di un sistema di assi cartesiani ortogonali e raggio unitario, ed un angolo $\alpha$ avente vertice nell'origine e un lato coincidente con il semiasse positivo delle ascisse che interseca la semicirconferenza in $P$, si definisce:

* $\sin \alpha$ l'ordinata del punto $P$
* $\cos \alpha$ l'ascissa del punto $P$

Tracciata poi la retta tangente alla circonferenza nel suo punto di coordinate $(1, \space 0)$ e indicato con $Q$ il punto d'intersezione con la semiretta $OP$, si definisce:

* $\tan \alpha$ l'ordinata del punto $Q$

IMMAGINI FUNZIONI CIRCOLARI

## Le equazioni di secondo grado

Un'equazione di secondo grado si può sempre ricondurre alla sua forma normale $ax^2 + bx +c = 0$ nella quale deve essere $a \neq 0$. Se i coefficienti $b$ o $c$ sono nulli l'equazione si dice incompleta e le sue soluzioni si trovano applicando la legge di annullamento del prodotto oppure la definizione di radicale:

* $ax^2 + bx = 0 \space \rightarrow \space x(ax + b) = 0 \space \rightarrow \space x = 0 \space \vee \space x = - \dfrac{b}{a}$
* $ax^2 + c = 0 \space \rightarrow \space x = \pm \sqrt{- \dfrac{c}{a}}$  se  $- \dfrac{c}{a} > 0$
* $ax^2 = 0 \space \rightarrow \space x = 0$

Le soluzioni dell'equazione completa si trovano applicando la formula $\dfrac{-b \pm \sqrt{b^2 - 4ac}}{2a}$, nella quale l'espressione $b^2 - 4ac$ si chiama **discriminante** e si indica con il simbolo $\Delta$, oppure con la formula ridotta se $b$ è pari $x = \dfrac{- \dfrac{b}{2} \pm \sqrt{\left ( \dfrac{b}{2} \right ) ^2 -ac}}{a}$

In base al valore del discriminante l'equazione:

* ammette due soluzioni reali e distinte se $\Delta > 0$
* ammette due soluzioni reali coincidenti se $\Delta = 0$
* non ha soluzioni reali se $\Delta < 0$

### Relazioni fra coefficienti e soluzioni
Fra le soluzioni $x_1$ e $x_2$ di un'equazione di secondo grado ed i suoi coefficienti sussistono le seguenti relazioni:

<div align="center">
$x_1 + x_2 = - \dfrac{b}{a}; \space x_1 \cdot x_2 = \dfrac{c}{a}$
</div>
Mediante la loro applicazione è possibile:

* trovare due numeri conoscendo la loro somma $s$ ed il loro prodotto $p$ risolvendo l'equazione: $x^2 - sx + p = 0$
* scomporre il trinomio $ax^2 + bx + c$ con la formula: $a(x - x_1)(x - x_2)$.

### L'interpretazione grafica
Ad ogni equazione di secondo grado $ax^2 + bx + c = 0$ si può associare la parabola di equazione $y = ax^2 + bx + c$. Le soluzioni dell'equazione, se esistono reali, rappresentano, dal punto di vista grafico, le ascisse
dei punti di intersezione della parabola con l'asse $x$, sono cioè gli zeri della funzione.

## Le disequazioni di secondo grado

### Come si risolve una disequazione di secondo grado
Per risolvere la disequazione $ax^2 + bx + c  \lessgtr 0$, dove si suppone che sia $a > 0$, si disegna la parabola $y = ax^2 + bx + c$ rappresentando la sua posizione relativamente all'asse $x$; i casi che si possono presentare, a secon-
da del segno del disciminante, sono i seguenti:

IMMAGINI DELTA PARABOLE

Di conseguenza:

* se $\Delta > 0$ il trinomio è positivo per valori esterni all'intervallo delle radici, è negativo per valori compresi
* se $\Delta = 0$ il trinomio è positivo per ogni $x \in \mathbb{R}$ escluso il punto in cui il trinomio si annulla e non è mai negativo
* se $\Delta < 0$ il trinomio è sempre positivo.

### Le disequazioni frazionarie e di grado superiore al secondo

* Per risolvere una disequazione frazionaria della forma $\dfrac{A(x)}{B(x)} \lessgtr 0$ si devono studiare i segni dei polinomi $A(x)$ e $B(x)$, riportare le variazioni di segno in una tabella e da essa dedurre il segno della frazione.
* Qualunque disequazione di grado superiore al secondo nella forma $E(x) \lessgtr 0$ si risolve scomponendo in fattori al più di secondo grado l'equazione $E(x)$ e studiando poi il segno di ciascuno di tali fattori; se $E(x)$ non è scomponibile, la disequazione non può essere risolta per via algebrica.

### Le equazioni e le disequazioni con i moduli
Per risolvere un'equazione o una disequazione con i moduli si deve studiare il segno di ciascuna espressione argomento di un modulo, costruire una tabella con la distribuzione dei segni, risolvere l'equazione o la disequazione che si ottiene in ciascuno degli intervalli individuati.

## Equazioni di grado superiore al secondo e irrazionali

Le equazioni polinomiali di grado superiore al secondo
Ogni equazione polinomiale del tipo $E(x) = 0$ di grado $n > 2$ si può risolvere solo se il polinomio $E(x)$ è scomponibile in fattori al più di secondo grado; in tal caso, per trovare le soluzioni, si applica la legge di annullamento del
prodotto.

### Equazioni particolari
Fra le equazioni di grado superiore al secondo ve ne sono alcune che si risolvono con metodi particolari.

* Le equazioni **reciproche** hanno la caratteristica di avere i coefficienti dei termini equidistanti dagli estremi che sono uguali oppure opposti; di esse si può dire che, se ammettono la soluzione $k$, ammettono anche la soluzione $\dfrac{1}{k}$. Le equazioni di grado dispari e quelle di grado pari in cui manca il termine centrale ammettono sempre la soluzione $1$ oppure $-1$. Le equazioni di quarto grado complete della forma $ax^4 + bx^3 + cx^2 + bx + a = 0$ si risolvono in questo modo:
    + si dividono entrambi i membri per $x^2$: $ax^2 + bx + c + \dfrac{b}{x} + \dfrac{a}{x^2} = 0$
    + si raccoglie a fattor comune fra i termini di uguale coefficiente: $a \left ( x^2 + \dfrac{1}{x^2} \right ) + b \left ( x + \dfrac{1}{x} \right ) + c = 0$
    + si operano le sostituzioni: $x^2 + \dfrac{1}{x^2} = t^2$ e $x + \dfrac{1}{x} = t$
    + dopo aver risolto l'equazione in $t$ si torna alla variabile $x$ operando la sostituzione inversa.
* Le equazioni **binomie** sono riconducibili alla forma $x^n = k$ e per risolverle si applica la definizione di radicale:
    + se $n$ è pari e $k \geq 0$ allora $x = \pm \sqrt{k}$
    + se $n$ è pari e $k < 0$ allora l'equazione è impossibile
    + se $n$ è dispari allora $x = \sqrt{k}$
* Le equazioni **trinomie** sono riconducibili alla forma $ax^{2n} + bx^n + c = 0$ e per risolverle si opera la sostituzione $x^n = t$
* Nel caso in cui $n = 2$ l'equazione si dice **biquadratica**.

### Le equazioni irrazionali
Un'equazione è **irrazionale** se l'incognita fa parte ell'argomento di un radicale.

* Le equazioni della forma $\sqrt{A(x)} = B(x)$ si possono risolvere in due modi:
    * risolvendo l'equazione $A(x) = [B(x)]^2$ e procedendo alla verifica delle soluzioni
    * risolvendo l'equazione $A(x) = [B(x)]^2$ con la condizione $B(x) \geq 0$
* Le equazioni della forma $\sqrt[3]{A(x)} = B(x)$ sono sempre equivalenti all'equazione $A(x) = [B(x)]^3$.


## Sistemi non lineari

Un sistema è non lineare se almeno una delle sue equazioni è di grado superiore al primo. In particolare:

* in un **sistema di secondo grado** tutte le equazioni sono di primo grado tranne una che è di secondo;
* in un **sistema di terzo grado** tutte le equazioni sono di primo grado tranne una che è di terzo.

Per risolvere un sistema non lineare si applicano i due principi di sostituzione e/o di riduzione; se il sistema è di secondo o di terzo grado conviene ricavare l'espressione di una variabile da una delle equazioni di primo grado e
sostituire in tutte le altre.

### Sistemi simmetrici
Un sistema si dice **simmetrico** se, scambiando fra loro le incognite, si ottiene ancora il sistema dato; la sua caratteristica è che, se ammette come soluzione la coppia $(a, \space b)$, allora ammette anche la coppia $(b, a)$.

Un sistema simmetrico di secondo grado si può sempre ricondurre alla forma

<div align="center">
$\begin{cases}
x + y = s \\
xy = p
\end{cases}$
</div>

e per trovare le sue soluzioni si può risolvere l'equazione di secondo grado $t^2 - st + p = 0$; in questo caso le soluzioni del sistema sono le coppie $(t_1, \space t_2) \space \vee \space (t_2, \space t_1)$ dove $t_1$ e $t_2$ sono le soluzioni dell'equazione in $t$.

Per sistemi simmetrici che si presentano in forme diverse è utile ricordare le seguenti relazioni:

<div align="center">
$x^2 + y^2 - (x + y)^2 - 2xy$
</div>

<div align="center">
$x^3 + y^3 - (x + y)^3 - 3xy(x + y)$
</div>
