---
title: "Geometria Analitica 1"
draft: false
weight: 5
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
<script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/jsxgraph/0.99.7/jsxgraphcore.js">
</script>


## La parabola

### La parabola e la sua equazione
La parabola è il luogo dei punti che hanno uguale distanza da un punto fisso $F$, detto fuoco, e da una retta fissa $d$, detta direttrice.

In un sistema di riferimento cartesiano ortogonale, l'equazione di una parabola ha forma diversa a secondo che l'asse di simmetria sia parallelo all'asse $x$ o all'asse $y$.

* Se l'asse di simmetria è parallelo all'asse $y$ la parabola ha equazione

<div align="center">
$y = a x^2 + bx +c$
</div>

e la concavità è rivolta:

* verso l'alto se $a > 0$
* verso il basso se $a < 0$

* Se l'asse di simmetria è parallelo all'asse $x$ la parabola ha equazione

<div align="center">
$x = a y^2 + by +c$
</div>

e la concavità è rivolta:

* verso destra se $a > 0$
* verso sinistra se $a < 0$

§IMMAGINE§

### Gli elementi caratteristici
Se si conosce l'equazione di una parabola, posto $\Delta = b^2 - 4 ac$, si possono trovare il vertice, il fuoco, l'equazione dell'asse e della direttrice con queste formule:

* per la parabola $y = a x^2 + bx + c$:
    * vertice $V \left ( - \dfrac{b}{2a}, \space - \dfrac{\Delta}{4a} \right )$
    * fuoco $F \left ( - \dfrac{b}{2a}, \space \dfrac{1 - \Delta}{4a} \right )$
    * asse $x = - \dfrac{b}{2a}$
    * direttrice $y = - \dfrac{1 + \Delta}{4a}$

* per la parabola $x = a y^2 + by + c$:
    * vertice $V \left ( - \dfrac{\Delta}{4a}, \space   - \dfrac{b}{2a} \right )$
    * fuoco $F \left ( \dfrac{1 - \Delta}{4a}, \space - \dfrac{b}{2a} \right )$
    * asse $x = - \dfrac{b}{2a}$
    * direttrice $y = - \dfrac{1 + \Delta}{4a}$

§IMMAGINI§

### Il grafico
Per traccia il grafico di una parabola quando è nota la sua equazione è indispensabile trovare il vertice e le coordinate di qualche punto (non è necessario, anche se può essere utile, trovare le coordinate del fuoco e l'equazione dell'asse o della direttrice)

### Le condizioni per determinare l'equazione di una parabola

Per trovare l'equazione di una parabola sono necessarie e sufficienti tre informazioni indipendenti; in particolare:

* se è noto il vertice $(x_0, \space y_0)$ è comodo usare la formula
    * $y - y_0 = a(x - x_0) ^2$ se la parabola ha l'asse di simmetria parallelo all'asse $y$
    * $x - x_0 = a(y - y_0) ^2$ se la parabola ha l'asse di simmetria parallelo all'asse $x$

Serve poi un'altra informazione per determinare il parametro $a$.

* se sono note  le coordinate di tre punti, basta sostituire tali coordinate nell'equazione generale della parabola e risolvere il sistema ottenuto

### Rette e parabole
Per determinare la **posizione di una retta rispetto a una parabola** si deve:

* impostare il sistema retta-parabola
* determinare l'equazione risolvente di secondo grado nella variabile $x$ (oppure $y$) a seconda del tipo di parabola
* calcolare il discriminante $\Delta$ di questa equazione:
    * se $\Delta > 0$ la retta è secante la parabola
    * se $\Delta = 0$ la retta è tangente alla parabola
    * se $\Delta < 0$ la retta non interseca la parabola

{{%expand "Mostra grafico della parabola" %}}
<div align="center">
<div id="parabola" class="jxgbox" style="width:500px; height:500px;"></div>
<script type="text/javascript">
var brd5=JXG.JSXGraph.initBoard('parabola',{boundingbox:[-3,3,3,-3], keepaspectratio:true});

var A = brd5.create('point',[-1,1]);
var B = brd5.create('point',[1,1]);
var line = brd5.create('line',[A,B]);
var C = brd5.create('point',[0,-1]);
var par = brd5.create('parabola',[C,line]);
</script>
</div>
{{% /expand%}}

### Le rette tangenti
Per trovare l'equazione della **retta tangente** a una parabola si deve calcolare il discriminante $\Delta$ dell'equazione risolvente il sistema retta-parabola e imporre che sia $\Delta = 0$
In particolare, se la retta tangente deve passare per un punto $P(x_0, \space y_0)$ che appartiene alla parabola, oltre al metodo illustrato è possibile seguire anche queste procedure:

* applicare le **formule di sdoppiamento** ponendo nell'equazione della parabola, a seconda della forma:
    * $x_0 x$ al posto di $x^2$
    * $y_0 y$ al posto di $y^2$
    * $\dfrac{1}{2} (x_0 + x)$ al posto di $x$
    * $\dfrac{1}{2} (y_0 + y)$ al posto di $y$
* scrivere l'equazione della retta $y - y_0 = m(x - x_0)$ dove:
    * $m = 2ax _0 + b$ se la parabole è del tipo $y = a x^2 + bx + c$
    * $m = \dfrac{1}{2a y_0 + b}$ se la parabola è del tipo $x = a y^2 + 2y + c$




### I fasci di parabole
Se l'equazione di una parabola dipende da un parametro, si ha un **fascio di parabole**; ognuna di esse, salvo casi particolari, si ottiene attribuendo un particolare valore al parametro. Fra le parabole del fascio può essere compresa una retta che rappresenta la parabola degenere.
Se due parabole del fascio si intersecano, anche tutte le altre si intersecano negli stessi punti che si dicono **punti base** del fascio; può quindi capitare che un fascio abbia:

* due punti base
* un solo punto base
* nessun punto base 

## La circonferenza
LA circonferenza è il luogo dei punti del piano che hanno la stessa distanza da un punto fisso chiamato centro; la distanza comune è il raggio.
Nel piano cartesiano l'equazione di una circonferenza ha sempre la forma $x^2 + y^2 + ax + by = 0$

Il centro e il raggio si possono calcolare con le formule $C \left ( - \dfrac{a}{2}, \space - \dfrac{b}{2}\right )$ e $r = \dfrac{1}{2} \sqrt{a^2 + b^2 -4c}$

Se $a^2 + b^2 - 4c <0$ la circonferenza non esiste.

In particolare, una circonferenza che ha centro nell'origine e raggio $r$ ha equazione $x^2 + y^2 = r^2$.

### Le condizioni per determinare l'equazione di una circonferenza

Per trovare l'equazione di una circonferenza sono necessarie e sufficienti tre informazioni indipendenti; in particolare:

* se si conoscono le coordinate $(p, \space q)$ del centro e la misura $r$ del raggio, la sua equazione è $(x - p) ^2 + (y - p) ^2 = r^2$
* se si conoscono le coordinate di tre punti, basta sostituire tali coordinate nell'equazione generale della circonferenza e risolvere il sistema ottenuto.

{{%expand "Mostra grafico della circonferenza" %}}
<div align="center">
<div id="cerchio" class="jxgbox" style="width:750px; height:300px;"></div>
<script type="text/javascript">
var b = JXG.JSXGraph.initBoard('cerchio',  {boundingbox: [-5, 2, 5, -2]});
var p1 = b.createElement('point',[0,0], {name:'A',size: 4, face: 'o'});
var p2 = b.createElement('point',[2,-1], {name:'B',size: 4, face: 'o'});
var ci = b.createElement('circle',["A","B"], {strokeColor:'#00ff00',strokeWidth:2});
</script>
</div>
{{% /expand%}}

### Le rette tangenti
Per trovare la retta tangente ad una circonferenza si può procedere in due modi:

* **primo modo**:
    + si scrive il sistema fra l'equazione della circonferenza e l'equazione della retta e si trova l'equazione risolvente 
    + si impone che il discriminante di tale equazione sia uguale a zero
* **secondo modo**:
    + si calcola la distanza del centro della circonferenza dalla retta
    + si impone che tale distanza sia uguale al raggio

In particolare, se la retta tangente passa per un punto $P(x_0, \space y_0)$ che appartiene alla circonferenza si può anche:

* usare le formule di sdoppiamento ponendo:
    + $x_0 x$ al posto di $x^2$
    + $y_0 y$ al posto di $y^2$
    + $\dfrac{1}{2} (x_0 + x)$ al posto di $x$
    + $\dfrac{1}{2} (y_0 + y)$ al posto di $y$
* detto $C$ il centro della circonferenza, scrivere l'equazione della retta che passa per $P$ ed è perpendicolare a $CP$.

## L'ellisse

### L'ellisse e la sua equazione
L'ellisse è il luogo dei punti del piano per i quali è costante la somma delle distanze da due punti fissi detti fuochi. L'equazione di un'ellisse con centro nell'origine e assi di simmetria coincidenti con gli assi cartesiani è:

<div align="center">
$\dfrac{x^2}{a^2} + \dfrac{y^2}{b^2} = 1$
</div>

dove $a$ rappresenta il semiasse appartenente all'asse delle ascisse e $b$ rappresenta il semiasse appartenente all'asse delle ordinate.

{{%expand "Mostra grafico della ellisse" %}}
<div align="center">
<div id="ellisse" class="jxgbox" style="width:500px; height:500px;"></div>
<script type="text/javascript">
var brd1=JXG.JSXGraph.initBoard('ellisse',{boundingbox:[-3,3,3,-3], keepaspectratio:true});

var D = brd1.create('point',[-1,1]);
var E = brd1.create('point',[1,1]);
var F = brd1.create('point',[0,-1]);
var ell = brd1.create('ellipse',[D,E,F]);
</script>
</div>
{{% /expand%}}

### Le caratteristiche di un'ellisse 
Le caratteristiche di un'ellisse si possono ricavare dalla sua equazione:

* i vertici sono i punti di coordinate $(\pm a, \space 0) \space (0, \space \pm b)$
* i fuochi appartengono all'asse $x$ se è $a > b$ quindi $F (\pm \sqrt{a^2 - b^2}, \space 0)$
* i fuochi appartengono all'asse $y$ se $a < b$ quindi $F(0, \space \pm \sqrt{b^2 - a^2})$

### L'eccentricità dell'ellisse
L'eccentricità $e$ di un'ellisse è definita come il rapporto tra la semidistanza focale $c$ ed il semiasse maggiore:

<div align="center">
$e = \dfrac{c}{semiasse \space maggiore}$
</div>

Essa rappresenta lo "schiacciamento" dell'ellisse sulla retta del semiasse maggiore ed è un numero reale compreso fra $0$ e $1$; se $e = 0$ l'ellisse diventa una circonferenza, se $e = 1$ l'ellisse degenera nel segmento individuato dai fuochi

{{%expand "Mostra grafico dell'eccentricità" %}}
<div align="center">
<div id="ecc_ell" class="jxgbox" style="width:500px; height:500px;"></div>
<script type="text/javascript">
var brd2=JXG.JSXGraph.initBoard('ecc_ell',{boundingbox:[-3,3,3,-3], keepaspectratio:true});

var A = brd2.create('point',[-1,0]);
var B = brd2.create('point',[1,0]);
var t = brd2.create('slider',[[-1,-2],[1,-2],[0,4,10]]);
var ell = brd2.create('ellipse',[A,B,function(){return t.Value();}]);
</script>
</div>
{{% /expand%}}

### Le rette tangenti
Per trovare l'equazione della retta tangente ad un'ellisse si deve:

* scrivere l'equazione generale della retta
* impostare il sistema fra l'equazione dell'ellisse e l'equazione della retta
* trovare l'equazione risolvente del sistema
* calcolare il discriminante di questa equazione e imporre che sia uguale a zero

In particolare, se la retta tangente passa per un punto $P(x_0, \space y_0)$ che appartiene all'ellisse, oltre al metodo illustrato si possno usare le formule di sdoppiamento ponendo nell'equazione dell'ellisse:
* $x_0 x$ al posto di $x^2$
* $y_0 y$ al posto di $y^2$


## L'iperbole

### L'iperbole e la sua equazione
L'iperbole è il luogo dei punti del piano per i quali è costante la differenza delle distanze da due punti fissi detti fuochi. L'equazione di un'iperbole che centro nell'origine e assi di simmetria coincidenti con gli assi cartesiani è

- $\dfrac{x ^2}{a ^2} - \dfrac{y ^2}{b ^2} = 1$ se i fuochi appartengono all'asse delle ascisse
- $\dfrac{x ^2}{a ^2} - \dfrac{y ^2}{b ^2} = - 1$ se i fuochi appartengono all'asse delle ordinate

{{%expand "Mostra grafico dell'iperbole" %}}
<div align="center">
<div id="iperbole" class="jxgbox" style="width:500px; height:500px;"></div>
<script type="text/javascript">
var brd3=JXG.JSXGraph.initBoard('iperbole',{boundingbox:[-3,3,3,-3], keepaspectratio:true});

var A = brd3.create('point',[0,1]);
var B = brd3.create('point',[1,1]);
var C = brd3.create('point',[0,-1]);
var hyp = brd3.create('hyperbola',[A,B,C]);
</script>
</div>
{{% /expand%}}

### Le caratteristiche di un'iperbole
Le caratteristiche di un'iperbole si possono ricavare dalla sua equazione:

- nel caso dell'iperbole di equazione $\dfrac{x ^2}{a ^2} - \dfrac{y ^2}{b ^2} = 1$:
    * $a$ rappresenta il semiasse trasverso
    * $b$ rappresenta il semiasse non trasverso
    * i vertici reali sono i punti di coordinate $(-a, \space 0) \space (a, \space 0)$
    * i vertici immaginari sono i punti di coordinate $(0, \space -b) \space (0, \space b)$
    * i fuochi sono i punti di coordinate $(\pm c, \space 0)$ dove $c = \sqrt{a^2 + b^2}$
    * gli asintoti hanno equazione $y = \pm \dfrac{b}{a} x$
- nel caso dell'iperbole di equazione $\dfrac{x ^2}{a ^2} - \dfrac{y ^2}{b ^2} = - 1$:
    * $a$ rappresenta il semiasse trasverso
    * $b$ rappresenta il semiasse non trasverso
    * i vertici reali sono i punti di coordinate $(0, \space -b) \space (0, \space b)$
    * i vertici immaginari sono i punti di coordinate $(-a, \space 0) \space (a, \space 0)$
    * i fuochi sono i punti di coordinate $(0, \space \pm c)$ dove $c = \sqrt{a^2 + b^2}$
    * gli asintoti hanno equazione $y = \pm \dfrac{b}{a} x$

### L'eccentricità dell'iperbole
L'eccentricità di un'iperbole è definita come il rapporto fra la semidistanza focale $c$ ed il semiasse trasverso:

<div align="center">
$e = \dfrac{semiasse \space focale}{semiasse \space trasverso} = \begin{cases} \dfrac{c}{a} \space \text{se i fuochi appartengono all'asse } x \\ \dfrac{c}{b} \space \text{se i fuochi appartengono all'asse } y \end{cases}$
</div>

Essa rappresenta l'ampiezza dell'iperbole ed è un numero reale maggiore di $1$.

{{%expand "Mostra grafico dell'eccentricità" %}}
<div align="center">
<div id="eccentricita_ip" class="jxgbox" style="width:500px; height:500px;"></div>
<script type="text/javascript">
var brd4=JXG.JSXGraph.initBoard('eccentricita_ip',{boundingbox:[-3,3,3,-3], keepaspectratio:true});

var C = brd4.create('point',[-1,0]);
var D = brd4.create('point',[1,0]);
var s = brd4.create('slider',[[-1,-2],[1,-2],[0,0.5,3]]);
var hyp = brd4.create('hyperbola',[C,D,function(){return s.Value();}]);
</script>
</div>
{{% /expand%}}

## Le rette tangenti
Per trovare l'equazione della **retta tangente** ad un'iperbole si deve:

* scrivere l'equazione generale della retta
* impostare il sistema fra l'equazione dell'iperbole e l'equazione della retta
* trovare l'equazione risolvente del sistema
* calcolare il discriminante di questa equazione e imporre che sia uguale a zero

In particolare, se la retta tangente passa per un punto $P(x_0, \space y_0)$ che appartiene all'iperbole, oltre al metodo illustrato si possono usare le formule di sdoppiamento ponendo nell'equazione dell'iperbole:

* $x_0 x$ al posto di $x^2$
* $y_0 y$ al posto di $y^2$
* $\dfrac{1}{2}(x_0 \cdot y + y_0 \cdot x)$ al posto di $xy$

### L'iperbole equilatera
Se in un'iperbole $a = b$, essa si dice **equilatera** e la sua equazione diventa:

* equazione riferita al centro e agli assi:
    * $x^2 - y^2 = a^2$ se i fuochi sono sull'asse $x$ $\rightarrow$ $F(\pm a \sqrt{2}, \space 0)$ con asintoti $y = \pm x$ 
    * $x^2 - y^2 = - a^2$ se i fuochi sono sull'asse $y$ $\rightarrow$ $F(0, \space \pm a \sqrt{2})$ con asintoti $y = \pm x$ 
* equazione riferita agli asintoti:
    * $xy = h$ se gli asintoti coincidono con gli assi cartesiani

La curva di equazione $xy = h$ è il grafico della proporzionalità inversa.

L'eccentricità di un'iperbole equilatera è sempre $e = \sqrt{2}$

Traslando un'iperbole equilatera riferita agli asintoti si ottiene una nuova iperbole la cui equazione ha la forma

<div align="center">
$y = \dfrac{ax + b}{cx + d} \space \text{ con } \space c \neq 0 \space \wedge \space ad - bc \neq 0$
</div>

Essa prende il nome di **funzione omografica** e l'iperbole che rappresenta ha per asintoti le rette

<div align="center">
$y = \dfrac{a}{c} \space \text{ e } \space x = - \dfrac{d}{c}$
</div>


## Le coniche e la risoluzione grafica delle equazioni

### I grafici delle funzioni irrazionali e con i moduli

* Per tracciare il grafico della funzione $y = \sqrt{f(x)}$, posta la condizione $f(x) \geq 0$, si costruire il grafico di $y^2 = f(x)$ e di tale grafico si considera solo la parte che appartiene al semipiano positivo o nullo delle ordinate

Analogamente, per tracciare il grafico della funzione $y = - \sqrt{f(x)}$, posta la condizione $f(x) \geq 0$, si costruisce il grafico di $y^2 = f(x)$ e di tale grafico si considera solo la parte che appartiene al semipiano negatico o nullo delle ordinate

* Per tracciare il grafico della funzione $y = |f(x)|$ si costruisce quello di $y = f(x)$ e si ribaltano le sue parti negative nel semipiano positivo delle ordinate.

### La risoluzione grafica di equazioni e disequazioni

* Per risolvere graficamente un'equazione della forma $f(x) = g(x)$, oppure l'analoga disequazione $f(x) \lessgtr g(x)$ si disegnano i grafici delle due funzioni e si individua se esistono punti di intersezione:
    + le ascisse di tali punti sono le soluzioni dell'equazione
    + gli intervalli sull'asse $x$ per i quali il grafico di $f(x)$ assume valori maggiori (oppure minori) del grafico di $g(x)$ sono le soluzioni della disequazione
* Per risolvere la disequazione in due variabili $f(x, \space y) \lessgtr 0 $:
    + si traccia il grafico della curva di equazione $f(x, \space y) = 0$ e si individuano le regioni di piano da esso delimitate
    + si considera un punto qualunque $P(x_0, \space y_0)$ in una regione e si valuta $f(x_0, \space y_0)$
    + se le coordinate di $P$ soddisfano la disequazione, la regione che lo contiene appartiene all'insieme delle soluzioni

### Zeri di funzioni e risoluzione approssimata delle equazioni

* **Zero** di una funzione $f(x)$ è l'ascissa $x_0$ del punto in cui la funzione $f$ inserseca l'asse $x$. L'esistenza degli zeri in una funzione è garantita dal seguente teorema:

Una funzione continua $f(x)$ possiede almeno uno zero in un intervallo $(a, \space b)$ se $f(a) \cdot f(b) < 0$

* Per trovare in modo approssimato le soluzioni di un'equazione polinomiale $a x^2 + b x^{n - 1} + ... + cx + d = 0$ si deve:

    + rappresentare graficamente la funzione $a x^2 + b x^{n - 1} + ... + cx + d = 0$ e stabilire se esistono degli zeri
    + individuare un intervallo che contiene lo zero
    * trovare un suo valore approssimato applicando il metodo delle sostituzioni successive oppure il metodo di bisezione


{{%expand "Mostra grafico della sezione conica attraverso 5 punti" %}}
<div align="center">
<div id="cinque_punti" class="jxgbox" style="width:500px; height:500px;"></div>
<script type="text/javascript">
var brd6=JXG.JSXGraph.initBoard('cinque_punti',{boundingbox:[-3,3,3,-3], keepaspectratio:true});

var A = brd6.create('point',[0.55,0]);
var B = brd6.create('point',[1,1]);
var C = brd6.create('point',[2,-1]);
var D = brd6.create('point',[2,2]);
var E = brd6.create('point',[0.3,-2]);
var con = brd6.create('conic',[A,B,C,D,E]);
</script>
</div>
{{% /expand%}}
















