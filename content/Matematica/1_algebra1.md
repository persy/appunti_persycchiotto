---
title: "Algebra"
draft: false
weight: 1
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



## Insiemi e funzioni

### Gli insiemi e la loro rappresentazione

La parola **insieme** indica un raggruppamento di oggetti di natura qualunque pensati come un unico ente; gli oggetti che formano un insieme sono i suoi **elementi**. Un insieme è finito se si possono elencare tutti i suoi elementi; infinito in caso contrario. Un insieme che non ha elementi si dice **vuoto**.

Un insieme si può rappresentare:

* per **elencazione** scrivendo l'elenco dei suoi elementi all'interno di una coppia di parentesi graffe
* mediante **proprietà caratteristica** indicando la frase che individui quali sono gli elementi dell'insieme
* graficamente mediante un **diagramma di Eulero-Venn**.

### I sottoinsiemi

Si dice che $B$  un **sottoinsieme** di un insieme $A$ se tutti gli elementi di $B$ sono anche elementi di $A$ e si scrive $B \subseteq A$. In particolare se in $A$ ci sono altri elementi oltre a quelli di $B$, allora $B$ è un **sottoinsieme proprio** di $A$ e vale la relazione $B \subset A$; se in $A$ non ci sono altri elementi oltre a quelli di $B$ allora $B = A$. L'insieme $A$ stesso e l'insieme vuoto sono i **sottoinsiemi impropri** di $A$.

{{%expand "Diagramma di Eulero-Venn di un sottoinsieme" %}}

![immagine](/Matematica/images/sottoinsieme.svg)

{{% /expand%}}

### Le operazioni fra insiemi

* **Intersezione**: $A \cap B$  è l'insieme i cui elementi appartengono contemporaneamente sia ad $A$ che a $B$. Se l'intersezione fra due insiemi è vuota, i due insiemi si dicono **disgiunti**
* **Unione**: $A \cup B$ è l'insieme i cui elementi appartengono ad $A$ oppure a $B$, quindi anche ad entrambi
* **Differenza**: $A - B$ è l'insieme degli elementi di $A$ che non appartengono a $B$. 

{{%expand "Le operazioni fra sistemi" %}}
![immagine](/Matematica/images/intersezione.svg)
![immagine](/Matematica/images/unione.svg)
![immagine](/Matematica/images/differenza.svg)

1. *Intersezione*
2. *Unione*
3. *Differenza*
{{% /expand%}}

Nel caso particolare in cui $B$ è un sottoinsieme di $A$, dell'insieme $A - B$ si dice che è il complementare di $B$ rispetto ad $A$ e si indica con uno dei seguenti simboli: $C_A B$ o $\bar{B}_A$

{{%expand "Insieme complementare" %}}

![immagine](/Matematica/images/complementari.svg)

{{% /expand%}}


#### Proprietà dell'intersezione

* commutativa: $A \cap B = B \cap A$
* associativa: $(A \cap B) \cap C = A \cap (B \cap C)$
* distributiva rispetto all'unione: $A \cap (B \cup C) = (A \cap B) \cup (A \cap C)$

#### Proprietà dell'unione

* commutativa: $A \cup B = B \cup A$
* associativa: $(A \cup B) \cup C = A \cup (B \cup C)$
* distributiva rispetto all'unione: $A \cup (B \cap C) = (A \cup B) \cap (A \cup C)$

Valgono poi le seguenti **leggi di De Morgan** che semplificano a volte l'esecuzione di alcune operazioni:

* prima legge: $\overline{A \cap B} = \overline{A} \cup \overline{B}$
* seconda legge: $\overline{A \cup B} = \overline{A} \cap \overline{B}$

### La partizione di un insieme

Si dice che si esegue una **partizione** di un insieme $A$ se si possono ripartire gli elementi di $A$ in $n$ sottoinsiemi $B_i$  tali che:

* nessuno dei $B_i$ sia vuoto
* l'intersezione fra due qualsiasi di essi sia l'insieme vuoto
* l'unione di tutti i $B_i$ dia l'insieme $A$

{{%expand "Partizionamento di un insieme" %}}

![partizione](/Matematica/images/partizione.svg)

{{% /expand%}}


### Il prodotto cartesiano

Dati due insiemi $A$ e $B$ si definisce poi il **prodotto cartesiano** $A \times B$ come l'insieme i cui elementi sono tutte e sole le **coppie ordinate** $(a, \qquadb)$ dove $a$ è un qualunque elemento di $A$ e $b$ è un qualunque elemento di $B$.
Il prodotto cartesiano fra insiemi si può rappresentare elencando tutte le coppie che si vengono a formare oppure mediante un diagramma a frecce, mediante una tabella a doppia entrata, mediante un diagramma cartesiano oppure mediante un diagramma ad albero.

### Le funzioni

Si dice **funzione** una corrispondenza tra gli elementi di un insieme $A$ e quelli di un insieme $B$ in modo che ad ogni elemento di $A$ sia associato uno e un solo elemento di $B$.
Una funzione può quindi essere:

* una **corrispondenza univoca**: ad ogni $x$ è associato un solo $y$
* una **corrispondenza biunivoca**: ad ogni $x$ è associato un solo $y$ e, viceversa, ad ogni $y$ è associato un solo $x$

{{%expand "Corrispondenza univoca e biunivoca" %}}

![immagine](/Matematica/images/univoca.svg)
![immagine](/Matematica/images/biunivoca.svg)

1. *Univoca*
2. *Biunivoca*

{{% /expand%}}

Le corrispondenze biunivoche sono le sole *funzioni invertibili*.

Una funzione $k$ è il prodotto di altre due funzioni $f$ e $g$, e si scrive $k = g \circ f$,
quando la funzione $g$ è applicata agli elementi generati dalla funzione $f$. La funzione $g$, anche se è scritta per prima nel prodotto, è quella che viene applicata per seconda.

{{%expand "Funzione prodotto" %}}

![immagine](/Matematica/images/prodotto.svg)

{{% /expand%}}

## Gli insiemi $\mathbb{N}$ e $\mathbb{Z}$

### I numeri naturali

I numeri naturali sono quelli della successione 0, 1, 2, 3, 4, 5, ... e si indica con $\mathbb{N}$, l'insieme dei numeri naturali privato dello zero si indica con $\mathbb{N}_0$.
Le operazioni interne a $\mathbb{N}$ sono solo l'addizione e la moltiplicazione, mentre la sottrazione è possibile solo se il primo numero è maggiore del secondo, la divisione è possibile solo se il primo numero è multiplo del secondo.

L'addizione e la moltiplicazione sono:

* commutative: $a + b = b + a$; $a \cdot b= b \cdot a$  
* associative: $(a + b) + c = a + (b+ c)$; $(a \cdot b) \cdot c = a \cdot (b \cdot c)$  
* inoltre vale la proprietà distributiva della moltiplicazione rispetto all'addizione: $(a+b) \cdot c = a \cdot c + b \cdot c$

### Le potenze e le proprietà delle potenze

La potenza $a^n$, con $n$ numero naturale maggiore di 1, equivale al prodotto $\underset{n \space volte}{\underbrace{a \cdot a \cdot ... \cdot a}}$.

Si definisce poi $a^1=a$ e  $a^0=1$, mentre non ha significato la scrittura $0^0$.

Valgono le seguenti proprietà:

* $a^m \cdot a^n = a^{m+n}$
* $a^m : a^n = a^{m-n}$
* $(a^m) ^n = a^{m \cdot n}$

### La divisibilità in $\mathbb{N}$

Se $c= a \cdot b$ si dice che $c$ è **multiplo** di $a$ secondo $b$; si dice anche che $c$ è divisibile per $a$ e per $b$.

Un numero che è divisibile solo per se stesso e per 1 si dice primo; due numeri che non hanno divisori comuni oltre all'unità si dicono **primi tra loro**.

Scomporre un numero naturale in fattori primi significa scriverlo come prodotto di soli fattori primi; la scomposizione di un numero in fattori primi è unica.

Il **massimo comun divisore** (M.C.D.) fra due numeri naturali è il più grande fra i divisori comuni ai due numeri; per trovarlo, si scompongono i due numeri e si calcola il prodotto dei soli fattori comuni presi con il minimo esponente.

Il **minimo comune multiplo** (m.c.m.) fra due numeri naturali è il più piccolo fra i multipli comuni ai due numeri; per trovarlo, si scompongono i due numeri e si calcola il prodotto dei fattori comuni e non comuni presi con il massimo esponente.

### I numeri interi

Un **numero intero** si esprime mediante un numero naturale preceduto da un segno $+$ o da un segno $-$. Il segno $+$ indica che il numero intero esprime una quantità che si trova al di sopra di un certo livello di riferimento; il segno $-$ che si trova al di sotto. Il livello di riferimento scelto è lo zero e si dice che i numeri $+1, +2, +3, ...$ sono **interi positivi**, i numeri $-1, -2, -3, ...$ sono **interi negativi**; allo zero non si attribuisce alcun segno.

L'insieme dei numeri interi si indica con la lettera $\mathbb{Z}$, l'insieme degli interi privato dello zero si indica con $\mathbb{Z_0}$.

Se due numeri hanno lo stesso segno si dicono **concordi**, se hanno segno diverso si dicono **discordi**.

Si chiama **valore assoluto** di un numero intero il numero stesso privato del suo segno. Due numeri interi che hanno lo stesso valore assoluto e segni opposti si dicono **opposti**.

### Le operazioni in $\mathbb{Z}$

La **somma** di due numeri interi si calcola con la seguente regola:

* se i due numeri sono concordi si sommano i valori assoluti dei due numeri e al risultato si attribuisce il segno comune
* se i due numeri sono discordi si calcola la differenza fra i valori assoluti e al risultato si attribuisce il segno del numero che ha valore assoluto maggiore.

Per esempio: $+3+(+4)=+7$; $-2+(-6)=-8$; $+3+(-9)=-6$

La **differenza** tra due numeri interi è la somma del primo con l'opposto del secondo.
Il **prodotto** di due numeri interi è il numero che si ottiene moltiplicando i valori assoluti dei due numeri e attribuendo
segno $+$ se i due numeri sono concordi, segno $-$ se i due numeri sono discordi.
Per esempio: $(+6) \cdot (+4) = +24$; $(+2) 1\cdot (-3) = -6$; $(-8) \cdot (-2) = +16$

## Gli insiemi $\mathbb{Q}$ e $\mathbb{R}$

### I numeri razionali

Una frazione si ottiene combinando in modo ordinato coppie di numeri naturali;

diciamo che due frazioni $\dfrac{a}{b}$ e $\dfrac{c}{d}$ sono equivalenti se $a \cdot d = b \cdot c$.

Si chiama **numero razionale** ogni sottoinsieme di frazioni tra loro equivalenti.

Per rappresentare un numero razionale si può usare una qualunque delle frazioni tra loro equivalenti oppure il numero decimale, finito o periodico, corrispondente.

Se, con le stesse convenzioni adottate per i numeri interi, associamo ad ogni numero razionale assoluto un segno $+$ e un segno $-$ (tranne che allo zero cui non si attribuisce segno) otteniamo l'insieme $\mathbb{Q}$ dei numeri razionali relativi.

### Le potenze e le proprietà delle potenze

Dato un numero razionale $a$ qualsiasi ed un intero $n \neq 0$ chiamiamo **potenza n-esima** di $a$, e si scrive $a^n$:

* $\underset{n \space volte}{\underbrace{a \cdot a \cdot ... \cdot a}}$, se $n \geq 2$
* $\dfrac{1}{a^{n}}=\dfrac{1}{{\underset{n \space volte}{\underbrace{a \cdot a \cdot ... \cdot a}}}}$ se $n < 0$ 

Si pone poi: $a^1 = a$ per ogni $a$; $a^0 = 1$ se $a \neq 0$;  non si attribuisce significato alla scrittura $0^0$.

Se $n$ e $m$ sono due numeri interi, tenendo presenti le considerazioni fatte sulla base della potenza, valgono le seguenti proprietà:

* $a^n \cdot a^m = a^{n+m}$
* $a^n : a^m = a^{n-m}$
* $(a^n) ^m = a^{n \cdot m}$
* $a \cdot b)^n = a^n \cdot b^n$
* $(a : b) ^n = a^n : b^n$

### Percentuali, rapporti e proporzioni

Una percentuale equivale a una frazione con denominatore $100$: $30 \%$ è la stessa cosa di $\dfrac{30}{100}$.

**Rapporto** fra due numeri $a$ e $b$, con $b \neq 0$, è il quoziente $a : b$.

Una proporzione è l'uguaglianza fra due rapporti $\dfrac{a}{b}$ e $\dfrac{c}{d}$ (con $b, \qquad  d \neq 0$) e si scrive $a : b = c : d$ 

Per essa vale la proprietà fondamentale $a \cdot d = b \cdot c$.

A partire dalla proporzione $a : b = c : d$ (dove supponiamo che i quattro numeri siano diversi da zero) se ne possono ottenere altre applicando le seguenti proprietà:

* permutare: $a : c = b : d$; $d : b = c : a$  
* invertire: $b : a = d : c$
* comporre: $(a + b) : a = (c + d ) : c$; $(a + b) : b = (c + d) : d$   
* scomporre: $(a - b) : a = (c - d ) : c$; $(a - b) : b = (c - d) : d$ 

### I numeri reali

Ci sono operazioni, come per esempio l'estrazione di radice, che portano a considerare numeri che non sono razionali. Si chiamano **irrazionali** quei numeri che si possono esprimere mediante un numero decimale illimitato non periodico, vale a dire un numero le cui cifre decimali si susseguono senza mai ripetersi in successione costante.
L'unione fra l'insieme dei numeri razionali e l'insieme dei numeri irrazionali dà origine all'**insieme dei numeri reali**. Un numero reale è quindi un numero che è razionale oppure irrazionale.

### Le caratteristiche principali degli insiemi numerici

$\mathbb{N}$:

* insieme infinito che ha come primo elemento $0$, non esiste ultimo elemento: $0, 1, 2, 3, ...$
* è un insieme discreto
* le operazioni interne sono: l'addizione, la moltiplicazione

$\mathbb{Z}$:

* insieme infinito che non ha né primo né ultimo elemento: $-3, -2, -1, 0, 1, 2, 3, ...$
* è un insieme discreto
* le operazioni interne sono: l'addizione e la sua inversa sottrazione, la moltiplicazione

$\mathbb{Q}$:

* insieme infinito che non ha né primo né ultimo elemento; i suoi elementi si possono esprimere come frazioni oppure come numeri decimali finiti o periodici
* è un insieme denso
* le operazioni interne sono: l'addizione e la sua inversa sottrazione, la moltiplicazione e la sua inversa divisione 

$\mathbb{R}$:

* insieme infinito che non ha né primo né ultimo elemento; i suoi elementi sono i numeri razionali e irrazionali
* è un insieme continuo
* si possono eseguire tutte le operazioni ad eccezione dell'estrazione di radice di indice pari di un numero negativo

### Le proprietà delle operazioni

* Addizione:
  + è un'operazione interna a qualsiasi insieme numerico
  + è commutativa e associativa
  + ha elemento neutro: $0$
  + è invertibile in $\mathbb{Z}$ e $\mathbb{Q}$ e l'operazione inversa è la sottrazione
* Sottrazione:
  + è un'operazione interna a $\mathbb{Z}$  e $\mathbb{Q}$, non sempre è possibile in $\mathbb{N}$ e $\mathbb{Q_a}$
  + possiede la proprietà invariantiva
* Moltiplicazione
  + è un'operazione interna a qualsiasi insieme numerico
  + è commutativa e associativa
  + è distributiva rispetto all'addizione e alla sottrazione
  + ha elemento neutro: $1$ 
  + è invertibile in $\mathbb{Q_0}$ e l'operazione inversa è la divisione
* Divisione
  + è un'operazione interna a $\mathbb{Q}$, non sempre è possibile in $\mathbb{N}$ e $\mathbb{Z}$
  + possiede la proprietà invariantiva
  + è distributiva solo a sinistra rispetto all'addizione e alla sottrazione

### Il grafico delle funzioni

Ogni funzione $y = f(x)$ può essere rappresentata graficamente in un piano cartesiano mediante l'insieme dei punti di coordinate $(x, \qquad  y)$ che si ottengono attribuendo a $x$ un valore del dominio e calcolando il corrispondente valore di $y$.

## I monomi e polinomi

### Le espressioni algebriche

Un'**espressione algebrica letterale** è un'espressione nella quale alcuni numeri sono rappresentati da lettere. In particolare si parla di:

* **monomi** se nell'espressione ci sono solo operazioni di moltiplicazione fra le lettere che hanno esponente intero positivo
* **polinomi** se nell'espressione, oltre alle moltiplicazioni, ci sono anche operazioni di addizione e sottrazione.

In ogni caso, sia i monomi che i polinomi non contengono operazioni di divisione fra lettere.

### I monomi

Il **grado di un monomio** è la somma dei gradi delle sue lettere; se è in forma normale, il grado rispetto ad ogni sua lettera è il grado di quella lettera; tutte le lettere che non compaiono in un monomio hanno grado zero.
Diciamo poi che due monomi sono:

* **uguali** se hanno lo stesso coefficiente numerico e la stessa parte letterale: $3ab$ è uguale a $3ab$
* **opposti** se hanno la stessa parte letterale e coefficienti numerici opposti:  $5x^2$ e $-5x^2$ sono opposti
* **simili** se hanno la stessa parte letterale: $2ax$ e $-6ax^2$.

### Le operazioni fra monomi

* La **somma** o la **differenza** fra monomi dà luogo ad un monomio solo se i monomi sono simili; la somma di monomi non simili è un polinomio: $2ax - 3ax = -ax$ è un monomio; $2a + 3b$ è un polinomio;
* il **prodotto** fra monomi si può sempre eseguire applicando le proprietà delle potenze: $4ab^2 \cdot (-3abx) = -12a^2 b^3 x$;
* il **quoziente** fra monomi dà luogo a un monomio solo se le lettere del divisore hanno una potenza minore o uguale di quelle corrispondenti del dividendo: $\dfrac{5}{2}b^3 y^2 z : \left ( - \dfrac{10}{9} b y \right ) = - \dfrac{9}{4}b^2 y z \qquad 4a^3 b : 2ax = \dfrac{2a^2 b}{x}$ (non è un monomio)

### I polinomi

Un polinomio è la somma algebrica di più monomi.

Il **grado di un polinomio** è il massimo dei gradi dei monomi che lo compongono; il grado rispetto a una sua lettera è il massimo dei gradi con cui quella lettera compare.
Diciamo poi che un polinomio è:

* **omogeneo** se i suoi monomi sono tutti dello stesso grado: $2x^2y - 3xy^2 + x^3 - y^3$
* **ordinato** rispetto a una sua lettera se le potenze di quella lettera sono scritte in ordine crescente o decrescente: $a^3 - 2a^2 +1$
* **completo** rispetto ad una lettera se il polinomio contiene tutte le potenze di quella lettera, da quella più è grande fino a zero: $y^3 + 5y^2 -4y -2$


{{%expand "Grafico di un polinomio di quinto grado $a x^5 + b x^4 + c x^3 + d x^2 + e x + f$" %}}
<div align="center">
<table style="width:100%">
  <tr>
    <td><div id="coeff" class="jxgbox" style="width:200px; height:250px;"></div>
<script type="text/javascript">
var brd1 = JXG.JSXGraph.initBoard('coeff', {boundingbox: [2, 0, 20, -20], showNavigation:false, showCopyright: false, axis:false});
var a5 = brd1.create('slider',[[3,-2],[11,-2],[-5,0,5]], {name:'a'});
var a4 = brd1.create('slider',[[3,-4],[11,-4],[-5,0,5]], {name:'b'});
var a3 = brd1.create('slider',[[3,-6],[11,-6],[-5,0,5]], {name:'c'});
var a2 = brd1.create('slider',[[3,-8],[11,-8],[-5,0,5]], {name:'d'});
var a1 = brd1.create('slider',[[3,-10],[11,-10],[-5,0,5]], {name:'e'});
var a0 = brd1.create('slider',[[3,-12],[11,-12],[-5,0,5]], {name:'f'});
</script></td>
    <td>
        <div id="poly" class="jxgbox" style="width:500px; height:500px;">
        </div>
        <script type="text/javascript">
var brd = JXG.JSXGraph.initBoard('poly', {boundingbox: [-10, 20, 10, -20], axis:true});
       brd1.addChild(brd);

var f = brd.create('functiongraph',[function(x){ 
	return a5.Value()*x*x*x*x*x + a4.Value()*x*x*x*x + a3.Value()*x*x*x + a2.Value()*x*x + a1.Value()*x + a0.Value(); 
}]);

var button1 = brd1.create('button', [3, -15, 'Reset', function() {
	a5.moveTo([7,-2]); 
	a4.moveTo([7,-4]);
	a3.moveTo([7,-6]);
	a2.moveTo([7,-8]);
	a1.moveTo([7,-10]);
	a0.moveTo([7,-12]);
	brd.update();
}], {});
    
a5.on('drag',function(){ brd.update();});
a4.on('drag',function(){ brd.update();});
a3.on('drag',function(){ brd.update();});
a2.on('drag',function(){ brd.update();});
a1.on('drag',function(){ brd.update();});
a0.on('drag',function(){ brd.update();});
        </script>
    </td>
  </tr> 
</table>
</div>
{{% /expand%}}

### Le operazioni fra polinomi

Poiché in un'espressione letterale le lettere rappresentano numeri, le **operazioni fra polinomi** si eseguono tenendo presenti le proprietà delle operazioni fra numeri.

* **la somma o la differenza** fra polinomi si esegue sommando o sottraendo i monomi simili dei due polinomi; la sottrazione si può sempre trasformare in una addizione cambiando i segni dei termini del secondo polinomio: $(6a - 3x + 1) - (4a + 5 - x) = 6a - 3x + 1 - 4a - 5 + x = 2a - 2x - 4$
* il **prodotto fra polinomi** si esegue applicando la proprietà distributiva della moltiplicazione rispetto all'addizione: $(3x - b)(1 + 2x) = 3x + 6x^2 - b - 2bx$
* il **quoziente fra un polinomio e un monomio** si esegue, quando possibile, dividendo ciascun termine del polinomio per il monomio divisore e sommando i quozienti ottenuti;
* il **quoziente fra due polinomi** non sempre dà luogo a un polinomio; per eseguire la divisione si esegue una procedura analoga a quella della divisione fra numeri.

### I prodotti notevoli

Il calcolo di alcuni prodotti fra polinomi si può abbreviare tenendo conto di particolari regole:

* quadrato di un binomio: $(a + b)^2 = a^2 + 2ab + b^2$
* quadrato di un trinomio: $(a + b + c)^2 = a^2 + b^2 + c^2 + 2ab + 2ac + 2bc$
* cubo di un binomio: $(a + b)^3 = a^3 + 3a^2b + 3ab^2 + b^3$ 
* somma di due monomi per la loro differenza: $(a + b)(a - b) = a^2 - b^2$

### Il teorema del resto e la divisibilità dei polinomi

Le divisioni di un polinomio  per un binomio di primo grado della forma  hanno un particolare rilievo; per esse valgono i seguenti teoremi:

* teorema del resto: il resto della divisione di $P(x)$ per $(x - a)$ è uguale a $P(a)$. 
  $P(x) = x^3 - 2x^2 + 4$, divisore: $x - 1$ → resto: $P(1) = 3$
* teorema di Ruffini: un polinomio $P(x)$ divisibile per il binomio $(x - a)$ se e solo se $P(a) = 0$. In questo caso $a$ rappresenta uno **zero** del polinomio.

Il teorema di Ruffini rappresenta quindi un criterio di divisibilità di $P(x)$ per $(x - a)$. 

## Fattorizzazione dei polinomi

### La fattorizzazione

Scomporre un polinomio significa scriverlo come prodotto di due o più polinomi, possibilmente non ulteriormente scomponibili.
I metodi per eseguire la scomposizione si basano sui seguenti criteri:

* i raccoglimenti a fattor comune parziale o totale
* il riconoscimento di prodotti notevoli
* la regola del trinomio caratteristico
* l'individuazione dei divisori della forma $x -a$

### Come eseguire una fattorizzazione

Nella pratica, per scomporre un polinomio conviene tenere presenti, in successione, le seguenti considerazioni:

* controllare se è possibile eseguire un raccoglimento totale o parziale
* cercare i divisori della forma riferirsi a regole particolari guardando il numero dei termini del polinomio;

#### Binomio

* differenza di quadrati: $x^2 - a^2 = (x - a)(x + a)$
* somma di quadrati: $x^2 + a^2$ (irriducibile)
* somma di cubi: $x^3 + a^3 = (x + a)(x^2 - ax + a^2)$
* differenze di cubi: $x^3 - a^3 = (x - a)(x^2 + ax + a^2)$

#### Trinomio

* quadrato di un binomio: $a^2 \pm 2ab + b^2 = (a \pm b)^2$
* trinomio caratteristico: $x^2 + (a + b)x + ab = (x + a)(x + b)$

#### Quadrinomio

* cubo di un binomio: $a^3 \pm 3a^2b + 3ab^2 \pm b^3 = (a \pm b)^3$
* differenza di due quadrati: 
$a^2 + 2ab + b^2 - x^2 = (a + b)^2  - x^2 = (a + b + x)(a + b - x) $

#### Polinomio di sei termini

* quadrato di un trinomio: $a^2 + 4b^2 + 9 + 4ab - 6a - 12b = (a + 2b -3)^2$
* differenza dei quadrati di due binomi:
$a^2 + 2a + 1 - x^2 + 2xy - y^2 = (a^2 + 2a + 1) - (x^2 - 2xy + y^2)$ 
$= (a + 1) ^2 - (x - y) ^2 = (a + 1 + x - y)(a + 1 - x + y)$


### M.C.D. e m.c.m. fra polinomi

* Il M.C.D. fra due o più polinomi già fattorizzati è il prodotto dei soli fattori comuni con il minimo esponente.
* il m.c.m. fra due o più polinomi già fattorizzati è il prodotto dei fattori comuni e non comuni con il massimo esponente.

## Le frazioni algebriche

Una frazione algebrica rappresenta il quoziente $\dfrac{A}{B}$ fra due polinomi $A$ e $B$ con $B \neq 0$.

Essa è funzione delle lettere che vi compaiono e, poiché la divisione per zero non è  consentita, le variabili non possono assumere valori che annullano il polinomio al denominatore.

L'insieme dei valori che è possibile attribuire alle lettere è il dominio della frazione.
Per determinare il **dominio** è necessario scomporre il polinomio $B$ e imporre che ciascun fattore della scomposizione sia diverso da zero (condizioni di esistenza).

### Frazioni equivalenti

Due frazioni algebriche sono **equivalenti** se attribuendo valori uguali a lettere uguali, si ottengono sempre frazioni numeriche equivalenti.
L'equivalenza fra due frazioni algebriche $\dfrac{A}{B}$ e $\dfrac{C}{D}$  si riconosce verificando l'uguaglianza $A \cdot D = B \cdot C$.

Per passare da una frazione a un'altra ad essa equivalente si applica la proprietà invariantiva, cioè si moltiplicano o si dividono numeratore e denominatore della frazione per uno stesso polinomio non nullo.

### Le operazioni

Con le frazioni algebriche si possono eseguire tutte le operazioni che si possono eseguire con le frazioni numeriche; quindi:

* si può semplificare una frazione scomponendo i suoi termini e dividendo numeratore e denominatore per i fattori comuni
* si possono sommare, sottrarre, moltiplicare o dividere due frazioni algebriche con regole analoghe a quelle applicate alle stesse operazioni con le frazioni numeriche:

<div align="center">
$
\dfrac{A}{B} + \dfrac{C}{D} = \dfrac{AD + BC}{BD}; \qquad\dfrac{A}{B}\cdot \dfrac{C}{D} = \dfrac{AC}{BD}; \qquad\dfrac{A}{B} : \dfrac{C}{D} = \dfrac{A}{B} \cdot \dfrac{D}{C} = \dfrac{AD}{BC}
$
</div>

* si può elevare a potenza una frazione elevando a quella potenza il numeratore e il denominatore:

<div align="center">
$
\left ( \dfrac{A} {B} \right) ^n = \dfrac{A^n} {B^n}
$
</div>

## Le equazioni

### Identità ed equazioni

Una **identità** è l'uguaglianza fra due espressioni algebriche che è verificata qualunque siano i valori, appartenenti al dominio delle due espressioni, che vengono attribuiti alle variabili.

Un'**equazione** è l'uguaglianza fra due espressioni algebriche che è verificata solo quando le sue variabili assumono particolari valori; tali valori sono le sue soluzioni o radici.

In base al numero di soluzioni, un'equazione può essere:

* **determinata** se ha un numero finito di soluzioni
* **indeterminata** se ha un numero infinito di soluzioni
* **impossibile** se non ha soluzioni

Un'equazione si dice poi:

* **intera** se i denominatori non contengono l'incognita, **frazionaria** in caso contrario
* **numerica** se l'unica lettera è l'incognita, **letterale** se contiene anche altre lettere

### Equazioni equivalenti

Due equazioni sono **equivalenti** se hanno le stesse soluzioni.
Per passare da un'equazione di dominio $D$ ad un'altra ad essa equivalente si applicano due principi di equivalenza:

* *primo principio*: sommando ai due membri di un'equazione una stessa espressione di dominio $D$ si ottiene un'equazione equivalente a quella data
* *secondo principio*: moltiplicando i due membri di un'equazione per una stessa espressione di dominio  e non nulla si ottiene un'equazione equivalente a quella data.

Conseguenze di questi due principi sono le seguenti:

* si può spostare un termine da un membro all'altro cambiandogli segno
* due termini uguali in due membri diversi si possono elidere
* si può scrivere un'equazione intera in forma normale trasportando tutti i termini al primo membro
* se i due membri dell'equazione hanno un fattore comune numerico non nullo, questo può essere semplificato
* si possono cambiare i segni a tutti i termini di un'equazione
* si possono eliminare i denominatori dell'equazione moltiplicando entrambi i membri per il loro m.c.m

### Equazioni lineari

Il **grado** di un'equazione intera $E(x) = 0$ è il grado del polinomio $E(x)$.
Un'equazione di primo grado, o equazione lineare, assume quindi la forma $ax + b = 0$.

Per risolvere un'equazione lineare si applicano i due principi di equivalenza e:

* se $a \neq 0$, la soluzione è $- \dfrac{b}{a}$ 
* se $a = 0$ e anche $b = 0$ l'equazione è indeterminata, ovvero ha infinite soluzioni
* $a = 0$ e $b \neq 0$ l'equazione è impossibile

### Equazioni non lineari

Per risolvere un'equazione $E(x) = 0$ dove $E(x)$ è un polinomio di grado superiore al primo, si deve:

* scomporre  in fattori tutti di primo grado: $(x - a)(x - b)(x - c) = 0$

* applicare la legge di annullamento del prodotto: $x - a = 0 \space \vee \space x - b = 0 \space \vee \space x - c = 0$

* da cui si ricavano le soluzioni: $x = a  \space \vee \space x = b  \space \vee \space x = c $

## Le disequazioni

### Le proprietà delle disuguaglianze numeriche

Dalla relazione $a > b$ (o dalla sua analoga $a < b$) si possono dedurre anche le seguenti:

* si può sommare (o sottrarre) ai due membri di una disuguaglianza uno stesso numero: $a + c > b + c$ 
* se si moltiplicano (o si dividono) entrambi i membri di una disuguaglianza per uno stesso numero positivo si ottiene una disuguaglianza dello stesso verso: $a \cdot c > b \cdot c$  se $c > 0$
* se si moltiplicano (o si dividono) entrambi i membri di una disuguaglianza per uno stesso numero negativo si ottiene una disuguaglianza di verso opposto: $a \cdot c < b \cdot c$  se $c < 0$  
 
### Disequazioni e disequazioni lineari

Una disequazione è una relazione della forma $A(x) > B(x)$ (oppure $A(x) < B(x)$); risolverla significa determinare i valori di $x$ per i quali l'espressione $A(x)$ assume valori maggiori (oppure minori) dell'espressione $B(x)$.
Una **disequazione intera lineare** si può sempre ricondurre alla forma $ax + b > 0$ che ha soluzione:

* $x > -\dfrac{b}{a}$ se $a > 0$ 
* $x < -\dfrac{b}{a}$ se $a < 0$

Se $a = 0$ la disequazione diventa una disuguaglianza numerica; se tale disuguaglianza è vera allora $S = R$, se è falsa allora $S = \varnothing$.

### Disequazioni frazionarie

Una **disequazione frazionaria** si può sempre scrivere nella forma $\dfrac{A(x)}{B(x)} > 0$ oppure $\dfrac{A(x)}{B(x)} < 0$ nelle quali il denominatore non si può eliminare.

Per risolverla si studiano i segni del polinomio $A(x)$ e del polinomio $B(x)$ e si riporta la loro variazione in una tabella; dal segno di ciascuno dei fattori si deduce poi il segno della frazione e, di conseguenza, l'insieme delle soluzioni.

### Disequazioni non lineari

Una **disequazione non lineare** $A(x)$  si può risolvere con un metodo analogo a quello seguito per le disequazioni frazionarie se l'espressione $A(x)$ è un polinomio scomponibile nel prodotto di fattori di primo grado. In questo caso, si studia la variazione del segno di ogni fattore del prodotto, si costruisce la tabella dei segni, si determina il segno di $A(x)$ e da esso si deduce l'insieme delle soluzioni.

### Sistemi di disequazioni

Due o più disequazioni si scrivono in un **sistema** se si vuole che esse siano verificate contemporaneamente. Per determinare l'insieme delle soluzioni si risolve ciascuna disequazione e si calcola l'**intersezione** degli insiemi soluzione.

### Equazioni e disequazioni con i moduli

Se un'equazione o una disequazione contengono un modulo, si deve studiare il segno dell'espressione che è argomento del modulo e risolvere poi l'equazione o la disequazione nell'ambito del segno studiato:

* l'equazione $|A(x)| = B(x)$ è equivalente ai due sistemi:

<div align="center">
$$\begin{cases}
A(x) \geq 0 \\ 
A(x) = B(x) 
\end{cases} \qquad  \vee \qquad   
\begin{cases}
A(x) < 0 \\ 
-A(x) = B(x) 
\end{cases}$$
</div>

* la disequazione $|A(x)| > B(x)$ è equivalente ai due sistemi:

<div align="center">
$$\begin{cases}
A(x) \geq 0 \\ 
A(x) > B(x) 
\end{cases} \qquad  \vee \qquad   
\begin{cases}
A(x) < 0 \\ 
-A(x) > B(x) 
\end{cases}$$
</div>
