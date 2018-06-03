---
title: "Goniometria"
draft: false
weight: 7
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


- [Le funzioni goniometriche](#le-funzioni-goniometriche)
        - [Angoli e misure](#angoli-e-misure)
        - [Le funzioni goniomentriche](#le-funzioni-goniomentriche)
        - [Le relazioni fondamentali](#le-relazioni-fondamentali)
        - [Le cofunzioni](#le-cofunzioni)
        - [Gli archi associati](#gli-archi-associati)
- [Le formule](#le-formule)
        - [Formule di addizione](#formule-di-addizione)
        - [Formule di duplicazione](#formule-di-duplicazione)
        - [Formule di bisezione](#formule-di-bisezione)
        - [Formule di parametriche](#formule-di-parametriche)
        - [Formule di prostaferesi](#formule-di-prostaferesi)
        - [Formule di Werner](#formule-di-werner)
- [La trigonometria](#la-trigonometria)
        - [I triangoli rettangoli](#i-triangoli-rettangoli)
        - [L'area di un triangolo e il teorema della corda](#larea-di-un-triangolo-e-il-teorema-della-corda)
        - [I triangoli qualunque](#i-triangoli-qualunque)
- [Le equazioni e le disequazioni goniometriche](#le-equazioni-e-le-disequazioni-goniometriche)
        - [Le funzioni goniometriche inverse](#le-funzioni-goniometriche-inverse)
        - [Equazioni di tipo elementare](#equazioni-di-tipo-elementare)
        - [Equazioni che prevedono il confronto di funzioni goniometriche](#equazioni-che-prevedono-il-confronto-di-funzioni-goniometriche)
        - [Equazioni lineari](#equazioni-lineari)
        - [Equazioni omogenee](#equazioni-omogenee)
        - [Disequazioni elementari](#disequazioni-elementari)
        - [Disequazioni frazionarie e sistemi](#disequazioni-frazionarie-e-sistemi)
        - [Disequazioni lineari](#disequazioni-lineari)
        - [Disequazioni omogenee](#disequazioni-omogenee)

## Le funzioni goniometriche
### Angoli e misure
Gli angoli si possono misurare in **gradi** oppure in **radianti**:
* se $\alpha$ è un angolo al centro di una circonferenza di raggio $r$ che insiste su un arco $AB$:


<div align="center">
$\alpha \space \text{[in radianti]} \space = \dfrac{\text{lunghezza dell'arco} \space AB \space \text{rettificato}}{r}$
</div>

* se $x$ è la misura di $a$ in radianti e $y$ è quella in gradi, per passare da un sistema all'altro si usa la proporzione

<div align="center">
$\pi : x = 180 : y$
</div>

### Le funzioni goniomentriche
Considerata la circonferenza goniometrica (avente centro nell'origine di un sistema di assi cartesiani ortogonali e raggio unitario) ed un angolo $\alpha$ avente vertice nell'origine e un lato coincidente con il semiasse positivo delle ascisse, si definisce:
* $\sin \alpha$ l'ordinata del punto $P$
* $\cos \alpha$ l'ascissa del punto $P$
* $\tan \alpha$ l'ordinata del punto $Q$

§IMMAGINE§

La funzione $y = \sin x$ è periodica di periodo $2 \pi$ ed il suo grafico: 

§IMMAGINE§

La funzione $y = \cos x$ è periodica di periodo $2 \pi$ ed il suo grafico: 

§IMMAGINE§

La funzione $y = \tan x$ è periodica di periodo $\pi$ ed il suo grafico: 

§IMMAGINE§

### Le relazioni fondamentali
Le relazioni fondamentali che legano le funzioni goniometriche sono:

<div align="center">
$\sin^2 \alpha + \cos^2 \alpha = 1$
</div>

<div align="center">
$\tan \alpha = \dfrac{\sin \alpha}{\cos \alpha}$
</div>

Da esse si ricavano le formule di:
* $\sin \alpha$ in funzione di $\cos \alpha$: $\sin \alpha = \pm \sqrt{1 - \cos^2 \alpha}$ 
* $\sin \alpha$ in funzione di $\tan \alpha$: $\sin \alpha = \pm \dfrac{\tan \alpha}{\sqrt{1 + \tan^2 \alpha}}$
* $\cos \alpha$ in funzione di $\sin \alpha$: $\sin \alpha = \pm \sqrt{1 - \sin^2 \alpha}$ 
* $\cos \alpha$ in funzione di $\tan \alpha$: $\sin \alpha = \pm \dfrac{1}{\sqrt{1 + \tan^2 \alpha}}$

La seconda relazione fondamentale consente poi di stabilire che il coefficiente angolare di una retta rappresenta la tangente dell'angolo $\alpha$ che essa forma con la direzione positiva dell'asse $x$: $m = \tan \alpha$.

### Le cofunzioni
Si definiscono poi le seguenti funzioni che prendono il nome di **cofunzioni goniometriche**:
* $\sec \alpha = \dfrac{1}{\cos \alpha}$
* $\csc \alpha = \dfrac{1}{\sin \alpha}$
* $\cot \alpha = \dfrac{\cos \alpha}{\sin \alpha}$ ed è $\forall \alpha \neq k \dfrac{\pi}{2}$
* $\cot \alpha = \dfrac{1}{\tan \alpha}$
        

{{%expand "Mostra grafico interattivo delle funzioni e cofunzioni goniometriche" %}}
<div align="center">
<div id="box" class="jxgbox" style="width:500px; height:500px;">
</div>
<script type="text/javascript">
var brd = JXG.JSXGraph.initBoard('box', {boundingbox: [-3, 3, 3, -3]});
var ax = brd.create('line',[[0,0],[1,0]],{visible:false});
var ay = brd.create('line',[[0,0],[0,1]],{visible:false});
var p0 = brd.create('point',[0,0],{fixed:true,visible:false});
var p1 = brd.create('point',[1,0],{name:'',visible:false,fixed:true});
var c = brd.create('circle',[p0,p1],{dash:2,strokeWidth:1,strokeOpacity:0.6});
var p2 = brd.create('glider',[0.4,1.0,c],{name:'',withLabel:false});
var p3 = brd.create('point',[function(){return p2.X();},0.0],{visible:false,name:'',withLabel:false});
var p4 = brd.create('point',[0.0,function(){return p2.Y();}],{visible:false,name:'',withLabel:false});
brd.create('line',[p0,p2],{straightFirst:false,straightLast:false,strokeColor:'black'});   // Hypotenuse
brd.create('line',[p2,p3],{straightFirst:false,straightLast:false,strokeColor:'red'});     // sin
brd.create('line',[p2,p4],{straightFirst:false,straightLast:false,strokeColor:'red'});     // cos
var t = brd.create('tangent',[p2],{visible:false});
var p5 = brd.create('intersection',[t,ax,0],{visible:false,name:'',withLabel:false});
var p6 = brd.create('intersection',[t,ay,0],{visible:false,name:'',withLabel:false});
brd.create('line',[p5,p6],{straightFirst:false,straightLast:false});    // tan + cot
brd.create('line',[p0,p6],{straightFirst:false,straightLast:false,strokeColor:'green'});   // csc
brd.create('line',[p0,p5],{straightFirst:false,straightLast:false,strokeColor:'green'});   // sec
brd.create('text',[
        function(){return (p0.X()+p2.X())*0.5;},
        function(){return (p0.Y()+p2.Y())*0.5;},
        '1'],{});
brd.create('text',[
        function(){return (p2.X()+p4.X())*0.3;},
        function(){return (p2.Y()+p4.Y())*0.5;},
        'cos'],{});
brd.create('text',[
        function(){return (p2.X()+p3.X())*0.5;},
        function(){return (p2.Y()+p3.Y())*0.5;},
        'sin'],{});
brd.create('text',[
        function(){return 0.1+(p2.X()+p5.X())*0.5;},
        function(){return 0.1+(p2.Y()+p5.Y())*0.5;},
        'tan'],{});
brd.create('text',[
        function(){return 0.1+(p2.X()+p6.X())*0.5;},
        function(){return 0.1+(p2.Y()+p6.Y())*0.5;},
        'cot'],{});
brd.create('text',[
        function(){return -0.2+(p0.X()+p6.X())*0.5;},
        function(){return (p0.Y()+p6.Y())*0.5;},
        'csc'],{});
brd.create('text',[
        function(){return (p0.X()+p5.X())*0.5;},
        function(){return (p0.Y()+p5.Y())*0.5;},
        'sec'],{});
</script>
</div>
{{% /expand%}}

### Gli archi associati
Gli angoli associati ad un angolo $\alpha$ sono quelli che hanno i valori delle funzioni goniometriche complessivamente uguali a quelli di $\alpha$. Per ricavare i valori del seno, del coseno e della tangente di tali angoli basta ricordare i seguenti disegni:


§IMMAGINI§


## Le formule
### Formule di addizione
* $\sin (\alpha \pm \beta) = \sin \alpha \cos \beta \pm \cos \alpha \sin \beta$
* $\cos (\alpha \pm \beta) = \cos \alpha \cos \beta + \sin \alpha \sin \beta$
* $tan (\alpha \pm \beta) = \dfrac{\tan \alpha \pm \tan \beta}{1 \mp \tan \alpha \tan \beta}$

### Formule di duplicazione
* $\sin 2 \alpha = 2 \sin \alpha \cos \alpha$

* $\cos 2 \alpha = \cos^2 \alpha - \sin^2 \alpha =  2 \cos^2 \alpha - 1 \leftrightarrow 1 - 2 \sin^2 \alpha$

* $\tan 2 \alpha = \dfrac{2 \tan \alpha}{1 - \tan^2 \alpha}$

### Formule di bisezione
* $\sin{\dfrac{\alpha}{2}} = \pm \sqrt{\dfrac{1 - \cos \alpha}{2}}$
* $\cos{\dfrac{\alpha}{2}} = \pm \sqrt{\dfrac{1 + \cos \alpha}{2}}$
* $\tan{\dfrac{\alpha}{2}} = \dfrac{\sin \alpha}{1 + \cos \alpha} = \dfrac{1 - \cos \alpha}{\sin \alpha}$

### Formule di parametriche
$\forall \alpha \neq \pi + 2k \pi$:
* $\sin \alpha = \dfrac{2 \tan{\dfrac{\alpha}{2}}}{1 + \tan^2{\dfrac{\alpha}{2}}}$
* $\cos \alpha = \dfrac{1 - \tan^2{\dfrac{\alpha}{2}}}{1 + \tan^2{\dfrac{\alpha}{2}}}$
* $\tan \alpha = \dfrac{2 \tan^2{\dfrac{\alpha}{2}}}{1 - \tan^2{\dfrac{\alpha}{2}}}$ 

### Formule di prostaferesi
* $\sin p + \sin q = 2 \sin \dfrac{p + q}{2} \cos \dfrac{p - q}{2}$
* $\sin p - \sin q = 2 \cos \dfrac{p + q}{2} \sin \dfrac{p - q}{2}$
* $\cos p + \cos q = 2 \cos \dfrac{p + q}{2} \cos \dfrac{p - q}{2}$
* $\cos p - \cos q = 2 \sin \dfrac{p + q}{2} \sin \dfrac{p - q}{2}$

### Formule di Werner
* $\sin \alpha \sin \beta = \dfrac{1}{2} [\cos (\alpha - \beta) - \cos(\alpha + \beta)]$
* $\cos \alpha \cos \beta = \dfrac{1}{2} [\cos (\alpha - \beta) + \cos(\alpha + \beta)]$
* $\sin \alpha \cos \beta = \dfrac{1}{2} [\sin (\alpha - \beta) + \sin(\alpha + \beta)]$


## La trigonometria

### I triangoli rettangoli
I triangoli rettangoli godono delle proprietà enunciate dai seguenti teoremi:
* **Primo Teorema**. In ogni triangolo rettangolo la misura di un cateto è uguale al prodotto della misura dell'ipotenusa per
     * il seno dell'angolo opposto: $b = a \sin \beta$ e $c = a \sin \gamma$
     * il coseno dell'angolo adiacente: $b = a \cos \gamma$ e $c = a \cos \beta$
        
* **Secondo teorema**. In ogni triangolo rettangolo la misura di un cateto è uguale al prodotto della misura dell'altro cateto per
    * la tangente dell'angolo opposto: $b = c \tan \beta$ e $c = b \tan \gamma$
    * la cotangente dell'angolo adiacente: $b = c \cot \gamma$ e $c = b \cot \beta$

§IMMAGINE§

### L'area di un triangolo e il teorema della corda
Le conseguenze immediate dei due precedenti teoremi sono le seguenti:
* l'area di un triangolo qualsiasi si può trovare calcolando il semiprodotto della misura di due lati per il seno dell'angolo fra essi compreso:

<div align="center">
$\text{area}  = \dfrac{1}{2} ab \sin \gamma$
</div>

* la misura di una corda $AB$ di una circonferenza di raggio $r$ è uguale al prodotto del diametro per il seno di uno qualsiasi degli angoli alla circonferenza $a$ che insistono sulla corda:

<div align="center">
$\overline{AB} = 2r \sin \alpha$
</div>

§IMMAGINE§

### I triangoli qualunque
Per i triangoli di qualsiasi tipo valgono i seguenti teoremi:
* **Teorema dei seni**: 

<div align="center">
$\dfrac{a}{\sin \alpha} = \dfrac{b}{\sin \beta} = \dfrac{c}{\sin \gamma}$
</div>

* **Teorema di Carnot**:

<div align="center">
$a^2 = b^2 + c^2 - 2bc \cos \alpha$
</div>

<div align="center">
$b^2 = b^2 + c^2 - 2bc \cos \beta$
</div>

<div align="center">
$c^2 = a^2 + b^2 - 2ab \cos \gamma$
</div>

## Le equazioni e le disequazioni goniometriche

### Le funzioni goniometriche inverse
Le funzioni inverse della goniometriche fondamentali sono:
* $y = \arcsin x$ definita in $[ -1, \space 1]$ con codominio $\left [ - \dfrac{\pi}{2}, \space \dfrac{\pi}{2} \right ]$
* $y = \arccos x$ definita in $[ -1, \space 1]$ con codominio $[0, \space \pi]$
* $y = \arctan x$ definita in $[ - \infty, \space + \infty]$ con codominio $\left ( - \dfrac{\pi}{2}, \space \dfrac{\pi}{2} \right )$

Accanto a queste ricordiamo anche l'inversa della funzione cotangente:
* $y = \textrm{arccot} \space x$ definita in $[ - \infty, \space + \infty]$ con codominio $(0, \space \pi)$

### Equazioni di tipo elementare
In generale, un'equazione goniometrica si può sempre ricondurre alla risoluzione di una o più **equazioni elementari** della forma:
* $\sin x = a$ con $-1 \leq a \leq 1$
* $\cos x = b$ con $-1 \leq b \leq 1$
* $\tan x = c$ con $c \in \mathbb{R}$

Ciascuna di queste equazioni ha infinite soluzioni che differiscono fra loro per il periodo della funzione; tenendo presente l'intervallo di inversione delle funzioni goniometriche e indicando con $\alpha$ l'angolo appartenente a tale intervallo, le soluzioni si possono scrivere nei seguenti modi:
* $\sin x = a$ se $\alpha = \arcsin a: \space x = \alpha + 2k \pi \space \vee \space x = (\pi - \alpha) + 2k \pi$
* $\cos x = b$ se $\alpha = \arccos b: \space x = \alpha + 2k \pi \space \vee \space x = - \alpha + 2k \pi$
* $\tan x = c$ se $\alpha = \arctan c: \space x = \alpha + k \pi$

### Equazioni che prevedono il confronto di funzioni goniometriche
* $\sin [f(x)] = \sin [g(x)]$ è equivalente a $f(x) = g(x) + 2k \pi \space \vee \space f(x) + g(x) = \pi + 2k \pi$
* $\cos [f(x)] = \cos [g(x)]$ è equivalente a $f(x) = g(x) + 2k \pi \space \vee \space f(x) + g(x) = \pi + 2k \pi$
* $\tan [f(x)] = \tan [g(x)]$ è equivalente a $f(x) = g(x) + k \pi$

### Equazioni lineari
Un'equazione lineare assume la forma: $a \sin x + b \cos x + c = 0$
* Se $c = 0$, e solo in questo caso, si può dividere per $\cos x$ ottenendo l'equazione elementare equivalente: $a \tan x + b = 0$
* Se $c \neq 0$ si possono seguire diversi metodi:
    * usare le formule parametriche verificando preventivamente se $x = \pi + 2k \pi$ è soluzione dell'equazione
    * utilizzare il metodo del sistema associato all'equazione l'identità $\sin x^2 x + \cos^2 x = 1$:

    <div align="center">
    $\begin{cases} a \sin x + b \cos x + c = 0 \\ \sin x^2 x + \cos^2 x = 1 \end{cases}$
    </div>

    * utilizzare il medodo grafico ponendo nel precedente sistema $sin x = Y$ e $\cos x = X$:

    <div align="center">
    $\begin{cases} a Y + b X + c = 0 \\ X^2 + Y  = 1 \end{cases}$
    </div>

    Le soluzioni sono rappresentate dalle intersezioni della circonferenza avente centro nell'origine e raggio $1$ con la retta di equazione $a Y + b X + c = 0$.

### Equazioni omogenee
Un'equazione omogenea di secondo grado ha la forma: $a \sin^2 x + b \sin x \cos x + c \cos^2 x = 0$

Per risolverla si divide per $cos^2 x$ ottenendo l'equazione equivalente $a \tan^2 x + b tan x + c = 0$

Questo metodo **non si può applicare** se $a = 0$ perché vengono eliminate delle soluzioni; in questo caso l'equazione diventa $b \sin x \cos x + c \cos^2 x = 0$ e si può: 
* raccogliere $\cos x$; quindi $\cos x (b \sin x + c cos x) = 0$
* dividere per $\sin^2 x$ se $c \neq 0$: $b \cot x + c \cot^2 x = 0$

L'equazione $a \sin^2 x + b \sin x \cos x + c \cos^2 x = d$ si trasforma in un'omogenea moltiplicando $d$ per $1$ cioè per $\sin x^2 x + \cos^2 x$:

$a \sin^2 x + b \sin x \cos x + c \cos^2 x = d(\sin x^2 x + \cos^2 x)$

### Disequazioni elementari
Per risolvere una **disequazione elementare** in una delle forme $\sin x \lessgtr k$, $\cos x \lessgtr k$ o $\tan x \lessgtr k$, si ricorre alla circonferenza goniometrica individuando gli archi per i quali la funzione al primo membro soddisfa la disequazione.

§IMMAGINI§

### Disequazioni frazionarie e sistemi
Per risolvere una disequazione goniometrica frazionaria oppure un sistema di disequazionigoniometriche si usano gli stessi metodi applicati per le analoghe disequazioni algebriche. È però conveniente usare delle tabelle circolari al posto di quelle lineari

### Disequazioni lineari
Per risolvere una **disequazione lineare** si possono usare gli stessi metodi utilizzati per la risoluzione delle analoghe equazioni; in particolare il motodo grafico risulta spesso più conveniente.

Occorre poi fare attenzione alle disequazioni in cui non c'è il termine noto, che assumono quindi la forma $a \sin x + b \cos x \lessgtr 0$ perché in questo caso **non si può dividere per $\cos x$** senza ulteriori analisi del suo segno.

### Disequazioni omogenee
Per risolvere una **disequazione omogenea** di secondo grado si divide per $\cos^2 x$ e si risolve la corrispondente disequazione di secondo grado in tangente. Occorre però verificare se $\dfrac{\pi}{2} + k \pi$ fa parte dell'insieme delle soluzioni.