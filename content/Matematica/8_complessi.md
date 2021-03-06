---
title: "I numeri complessi"
draft: false
weight: 8
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


- [I numeri complessi](#i-numeri-complessi)
- [La risoluzione delle equazioni in $\mathbb{C}$](#la-risoluzione-delle-equazioni-in-mathbbc)
- [Il piano di Gauss](#il-piano-di-gauss)
- [La forma trigonometrica e le operazioni](#la-forma-trigonometrica-e-le-operazioni)
- [Le radici $n$-esime di un numero complesso](#le-radici-n-esime-di-un-numero-complesso)
- [La forma esponenziale](#la-forma-esponenziale)

### I numeri complessi
Si chiama **unità immaginaria** il numero che si indica con il simbolo $i$ e che è caratterizzato dalla relazione $i^2 = -1$.

Un numero immaginario è il prodotto di un numero reale per l'unità immaginaria

La somma di un numero reale con un numero immaginario dà luogo ad un **numero complesso**; un numero complesso ha quindi la forma $a + ib$.

Le operazioni di addizione, sottrazione e moltiplicazione tra numeri complessi seguono le regole del calcolo algebrico letterale tenendo presente che $i^2 = -1$.

L'operazione di divisione si esegue applicando la proprietà invariantiva, moltiplicando sia il dividendo che il divisore per il complesso coniugato del divisore:

<div align="center">
$\dfrac{a + ib}{c + id} = \dfrac{(a + ib)(c - id)}{(c + id)(c - id)} = \dfrac{(a + ib)(c - id)}{c^2 + d^2}$
</div>

{{%expand "Mostra grafico della somma" %}}
<div align="center">
<div id="box" class="jxgbox" style="width:500px; height:500px;"></div>
<script type="text/javascript">
board = JXG.JSXGraph.initBoard('box', {boundingbox: [-6, 6, 8, -4], axis: true});
        
var org = board.create('point', [0,0], {style:10,visible:true,fixed:true,name:' '});
var x = board.create('point', [2,2], {style:5,color:'blue',name:'x'});
var y = board.create('point', [-1,-3], {style:5,color:'blue',name:'y'});
var xy = board.create('point', 
    ["X(x)+X(y)","Y(x)+Y(y)"], {style:7,color:'green',name:'x+y'});
var ax = board.create('arrow', [org,x], {strokeColor:'blue'});
var ay = board.create('arrow', [org,y], {strokeColor:'blue'});
var axy = board.create('arrow', [org,xy], {strokeColor:'red'});
var ax2 = board.create('arrow', [x,xy], {strokeColor:'blue',strokeWidth:1,dash:1});
var ay2 = board.create('arrow', [y,xy], {strokeColor:'blue',strokeWidth:1,dash:1});
</script>
</div>
{{% /expand%}}

### La risoluzione delle equazioni in $\mathbb{C}$
L'unità immaginaria consente di calcolare le radici quadrate dei numeri negativi: ad esempio $\sqrt{-4} = \pm 2i$

Nell'insieme dei numeri complessi un'equazione di grado $n$ ammette sempre $n$ soluzioni, se ciascuna viene contanta con la sua molteplicità. In particolare, un'equazione di secondo grado ammette sempre 2 soluzioni che sono:
* reali e distinte se $\Delta > 0$
* reali e coincidenti se $\Delta = 0$
* complesse e coniugate se $\Delta < 0$

Si può inoltre affermare che un'equazione di grado dispari ammette sempre almeno una soluzione reale.

### Il piano di Gauss
Un numero complesso $z = a + ib$ si può rappresentare graficamente nel piano di Gauss riportando la parte reale $a$ sull'asse delle ascisse (**asse reale**) e il coefficiente $b$ della parte immaginaria sull'asse delle ordinate (**asse immaginario**).

Ad ogni numero complesso $z$ si può quindi associare un punto $P$ di coordinate $(a, \space b)$ o anche un vettore $v$ di componenti $(a, \space b)$.

§IMMAGINE§

### La forma trigonometrica e le operazioni
Ad ogni numero complesso $z = a + ib$ si può associare una **forma trigonometrica**:

<div align="center">
$z = \rho (\cos \vartheta + i \sin \vartheta)$ con $0 \leq \vartheta \leq 2 \pi$
</div>

dove $\rho$ rappresenta il **modulo** del numero complesso e $\vartheta$ la sua **anomalia**.

Fra i numeri $a$ e $b$ della forma algebrica e quelli $\rho$ e $\vartheta$ della forma trigonometrica sussistono le seguenti realzioni:
* $a$ e $b$ in funzione di $\rho$ e $\vartheta$:

<div align="center">
$\begin{cases} a = \rho \cos \vartheta \\ b = \rho \sin \vartheta \end{cases}$
</div>

* $\rho$ e $\vartheta$ in funzione di $a$ e $b$:

<div align="center">
$\rho = \sqrt{a^2 + b^2} \quad \cos \vartheta = \dfrac{a}{\rho} \quad \sin \vartheta \dfrac{b}{\rho} \quad \tan \vartheta \dfrac{b}{a}$
</div>

Le operazioni di moltiplicazione, divisione e potenza si possono eseguire in modo semplice mediante la forma trigonometrica; dati due numeri complessi $z_1 = \rho_1 (\cos \vartheta_1 + i \sin \vartheta_1)$ e $z_2 = \rho_2 (\cos \vartheta_2 + i \sin \vartheta_2)$ si procede in questo modo:
* **prodotto**: si moltiplicano i moduli e si sommano le anomalie: $z_1 \cdot z_2 = \rho_1 \cdot \rho_1[cos(\vartheta_1 + \vartheta_2) i \sin (\vartheta_1 + \vartheta_2)]$
* **quoziente**: si dividono i moduli e si sottraggono le anomalie: $\dfrac{z_1}{z_2} = \dfrac{\rho_1}{\rho_2} [\cos (\vartheta_1 - \vartheta_2) + i \sin (\vartheta_1 - \vartheta_2)]$
* **potenza** $n$-esima: si eleva a potenza $n$ il modulo $\rho$ e si moltiplica per $n$ l'anomalia $\vartheta$: $z^n = \rho^2 (\cos n \vartheta + i \sin n \vartheta)$ (formula di De Moivre)

{{%expand "Mostra grafico del prodotto" %}}
<div align="center">
<div id="box2" class="jxgbox" style="width:500px; height:500px;"></div>
<script type="text/javascript">
brd2 = JXG.JSXGraph.initBoard('box2', {boundingbox: [-6, 6, 8, -4], axis: true});
        
var org2 = brd2.create('point', [0,0], {style:10,visible:true,fixed:true,name:' '});
var x = brd2.create('point', [1,0], {style:4,color:'blue',name:'x'});
var y = brd2.create('point', [0,2], {style:4,color:'red',strokeColor:'red',name:'y'});
var xy = brd2.create('point', 
    ["X(x)*X(y)-Y(x)*Y(y)","X(x)*Y(y)+X(y)*Y(x)"], {style:7,fillColor:'green',strokeColor:'green',name:'x*y'});
var c = brd2.create('circle',[org2,1],{strokeWidth:1,dash:1});
</script>
</div>
{{% /expand%}}

### Le radici $n$-esime di un numero complesso
Ogni numero complesso $z = (\rho, \space \vartheta)$ ha $n$ radici $n$-esime che si esprimono con la formula:

<div align="center">
$\omega_k = \sqrt[n]{\rho} \left [ \cos \left ( \dfrac{\vartheta}{n} + \dfrac{2k \pi}{n} \right ) + i \sin \left ( \dfrac{\vartheta}{n} + \dfrac{2k \pi}{n} \right ) \right ] \space k = 0, 1, ..., n - 1$
</div>

Attraverso il calcolo delle radici $n$-esime di un numero complesso si possono trovare le $n$ soluzioni di equazione algebrica di grado $n$.

### La forma esponenziale
Posto $e^{i \vartheta} \cos \vartheta + i \sin \vartheta$, un numero complesso ha anche una **forma esponenziale**: $z = \rho \cdot e^{i \vartheta}$

Per eseguire prodotti, quozienti e potenze di numeri complessi in forma esponenziale, si applicano le proprietà delle potenze; dati $z_1 = \rho_1 \cdot e^{i \vartheta_1}$ e $z_2 = \rho_2 \cdot e^{i \vartheta_2}$ si ha che:

* prodotto $z_1 \cdot z_2 = \rho_1 \rho_2 \cdot e^{i (\vartheta_1 + \vartheta_2)}$
* quoziente $\dfrac{z_1}{z_2} = \dfrac{\rho_1}{\rho_2} \cdot e^{i (\vartheta_1 - \vartheta_2)}$
* potenza $n$-esima $z^n = \rho^n \cdot e^{i n \vartheta}$

Dalla forma esponenziale di un numero complesso, si ricavano le seguenti formule di Eulero:

<div align="center">
$cos \vartheta = \dfrac{e^{i \vartheta} + e^{ -i \vartheta}}{2} \qquad sin \vartheta = \dfrac{e^{i \vartheta} - e^{ -i \vartheta}}{2i}$
</div>


