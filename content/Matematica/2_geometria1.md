---
title: "Geometria"
draft: false
weight: 2
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
</script>
<!-- script JSXGraph -->
<script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/jsxgraph/0.99.7/jsxgraphcore.js">
</script>

## I primi elementi e i triangoli

### Termini primitivi assiomi

I **termini primitivi** della geometria euclidea sono *punto*, *retta* e *piano* e di tali termini non si deve perciò dare una definizione. Le loro caratteristiche sono tuttavia indicate implicitamente da una serie di **assiomi**, proposizioni delle quali si stabilisce la verità a priori. Gli assiomi della geometria euclidea indicano:

* l'appartenenza di oggetti geometrici ad altri oggetti geometrici:
    * due punti dello spazio appartengono ad una sola retta
    * tre punti non allineati appartengono ad un solo piano
    * se due punti di una retta appartengono a un piano, la retta stessa appartiene al piano
* la possibilità di fissare un ordinamento dei punti su una retta orientata e di stabilire che qualsiasi retta:
    + è illimitata
    + contiene infiniti punti
* la possibilità di ripartire i punti di un piano in due regioni distinte mediante una retta in modo che, per passare da una regione all'altra, occorre necessariamente intersecare la retta
* la possibilità di trasportare segmenti e angoli nel piano conservando lunghezze e ampiezze.

Le proprietà degli oggetti geometrici che si possono dedurre dagli assiomi sono invece dei **teoremi** e per accertarne la verità occorre condurre la loro dimostrazione.

### Segmenti e angoli
I termini primitivi e gli assiomi consentono di dare le prime definizioni.

* **Segmento** AB è la parte di retta delimitata dai punti A e B che sono gli estremi del segmento; due segmenti sono consecutivi se hanno un estremo in comune, sono adiacenti se sono consecutivi e appartengono alla stessa retta.

IMMAGINE segmenti consecutivi

IMMAGINE segmenti adiacenti

* **Angolo** è ciascuna delle due parti in cui un piano viene diviso da due semirette aventi l'origine in comune; tali semirette costituiscono i lati dell'angolo.

L'angolo che non contiene il prolungamento dei lati è **convesso**, quello che li contiene è **concavo**.
Due angoli sono consecutivi se hanno il vertice e un lato in comune e se gli altri due lati si trovano da parti opposte rispetto a quello comune, sono adiacenti se sono consecutivi e se i lati non comuni appartengono alla stessa retta.

Due angoli convessi sono **opposti al vertice** se i lati del primo sono i prolungamenti di quelli del secondo.

IMMAGINI angolo convesso; concavo; consecutivi, adiacenti, opposti al vertice

### La congruenza
Due figure $F_1$ e $F_2$ sono **congruenti**, e si scrive $F_1 \cong F_2$, se esiste un movimento rigido mediante il quale ogni punto di $F_1$ si sovrappone ad uno e un solo punto di $F_2$.
Attraverso la relazione di congruenza si può definire:

* la lunghezza di un segmento come la caratteristica comune ai segmenti fra loro congruenti
* l'ampiezza di un angolo come la caratteristica comune agli angoli fra loro congruenti
In particolare abbiamo chiamato:
* **punto medio** di un segmento il punto che lo divide in due parti congruenti
* **bisettrice** di un angolo la semiretta uscente dal vertice che lo divide in due angoli congruenti.

### I poligoni
Un poligono è la parte di piano delimitata da una poligonale chiusa; un poligono è **convesso** se qualunque segmento che unisce due punti interni
appartiene interamente al poligono, **concavo** in caso contrario.
Un poligono di tre lati si chiama **triangolo**.

IMMAGINI poligono convesso; concavo

### La congruenza dei triangoli
Si può riconoscere la congruenza di due triangoli in base ad alcuni criteri:

* **primo criterio**: i due triangoli devono avere ordinatamente congruenti due lati e l'angolo fra essi compreso
* **secondo criterio**: i due triangoli devono avere ordinatamente congruenti un lato e i due angoli ad esso adiacenti
* **terzo criterio**: i due triangoli devono avere ordinatamente congruenti i tre lati.

IMMAGINI criteri congruenza triangoli

### La classificazione dei triangoli
I triangoli si possono classificare:

* in base ai lati in:
    * triangoli **scaleni**, se hanno i tre lati disuguali
    * triangoli **isosceli**, se hanno due lati congruenti
    * triangoli **equilateri**, se hanno tutti i lati congruenti
* in base agli angoli in:
    * triangoli **acutangoli**, se tutti gli angoli sono acuti
    * triangoli **ottusangoli**, se uno degli angoli è ottuso
    * triangoli **rettangoli**, se uno degli angoli è retto.
    * 
Possiamo inoltre affermare che:

- in un triangolo isoscele gli angoli opposti ai lati congruenti sono congruenti
- in un triangolo equilatero tutti gli angoli sono congruenti fra loro.

IMMAGINI TIPI DI TRIANGOLO

### Relazioni fra lati e angoli di un triangolo
In un triangolo valgono le seguenti relazioni fra lati e angoli:

* ogni angolo esterno è maggiore di ciascuno degli angoli interni ad esso non adiacenti 
* al lato maggiore sta opposto l'angolo maggiore e, reciprocamente, all'angolo maggiore sta opposto il lato maggiore
* ciascun lato è minore della somma degli altri due e maggiore della loro differenza.

## Parallelismo e perpendicolarità nel piano

Due rette sono **perpendicolari** se intersecandosi formano quattro angoli fra loro congruenti, quindi retti.
La perpendicolare ad una retta $r$ condotta da un punto $P$ (appartenente o no a $r$) esiste sempre ed è unica.

Il concetto di perpendicolarità permette di introdurre le seguenti definizioni:

* **distanza** di un punto $P$ da una retta $r$ è il segmento di perpendicolare condotto da P su r;
* **asse** di un segmento è la retta ad esso perpendicolare passante per il suo punto medio; ogni punto dell'asse è equidistante dagli estremi del segmento.

Relativamente ai triangoli vale poi la seguente proprietà:

* in ogni triangolo isoscele l'altezza e la mediana relative alla base e la bisettrice dell'angolo al vertice coincidono.

IMMAGINI rette perpendicolari; distanza punto-retta; asse segmento

### Le rette parallele e le proprietà
Due rette sono **parallele** se coincidono oppure se non si intersecano.

Una proprietà delle rette parallele è che, tagliate da una trasversale, formano:

* angoli alterni congruenti
* angoli corrispondenti congruenti
* angoli coniugati supplementari.

Viceversa, per stabilire se due rette sono parallele basta verificare che esse formino con una trasversale:

* una coppia di angoli alterni congruenti, oppure
* una coppia di angoli corrispondenti congruenti, oppure
* una coppia di angoli coniugati supplementari.

### Le conseguenze nei poligoni
Relativamente ai triangoli:

* ciascun angolo esterno è congruente alla somma dei due angoli interni ad esso non adiacenti
* la somma degli angoli interni è congruente a un angolo piatto
* due triangoli sono congruenti se hanno due angoli e un lato ordinatamente congruenti.

Relativamente ai poligoni convessi:

* la somma degli angoli interni è uguale a $n - 2$ angoli piatti (con $n$ uguale al numero dei lati del poligono)
* la somma degli angoli esterni è sempre uguale a due angoli piatti (anche per il triangolo).

Relativamente agli angoli:

* due angoli che hanno entrambi i lati paralleli e concordi oppure paralleli e discordi sono congruenti
* due angoli che hanno una coppia di lati paralleli e concordi e l'altra paralleli e discordi sono supplementari.

### La congruenza nei triangoli rettangoli
Poiché tutti i triangoli rettangoli hanno almeno un angolo congruente, quello retto, si può concludere che **due triangoli rettangoli** sono congruenti se hanno ordinatamente congruenti due elementi, di cui almeno uno deve essere un lato; in particolare:

* i due cateti
* l'ipotenusa e un cateto
* un cateto e un angolo acuto
* l'ipotenusa e un angolo acuto.

## Trasformazioni geometriche
Una **trasformazione geometrica** è una corrispondenza biunivoca tra i punti del piano; essa viene stabilita assegnando una legge (che è una funzione) che indica i modi in cui i punti si corrispondono.
In una trasformazione chiamiamo:

* **punti uniti** i punti che hanno per trasformati se stessi
* **invarianti** le caratteristiche delle figure che non cambiano dopo l'applicazione della trasformazione.

### Le isometrie
Le trasformazioni che lasciano invariate le lunghezze dei segmenti si dicono **isometrie**. Le
isometrie fondamentali sono:

* la **simmetria assiale**, definita rispetto ad una retta $r$ (l'asse di simmetria), che ad ogni punto $P$ di un piano associa il punto ${P}'$ che si costruisce in questo modo:
    * si traccia da $P$ la perpendicolare a $r$ che la incontra in $H$
    * si prende su di essa il punto ${P}'$ nel semipiano opposto rispetto a $P$ tale cha sia ${P}'H \cong PH$
* la **simmetria centrale**, definita rispetto ad un punto $O$ (il centro di simmetria), che ad ogni punto $P$ di un piano associa il punto ${P}'$ che si costruisce in questo modo:
    + si traccia la retta $OP$
    + si prende il punto ${P}'$ sulla semiretta di origine $O$ opposta rispetto a $P$ tale che sia ${P}'O \cong PO$
* la **traslazione**, definita da un vettore $\vec v$, che ad ogni punto $P$ di un piano associa il punto ${P}'$ che è il secondo estremo del vettore $\vec v$ quando il primo estremo coincide con $P$
* la **rotazione**, definita assegnando un punto $O$ (il centro di rotazione) ed un angolo orientato , che ad ogni punto $P$ associa il punto ${P}'$ tale che $OP \cong O{P}'$ e $\widehat{POP'}$ orientamento e la stessa ampiezza di $\alpha$.

### I parallelogrammi
Un **parallelogramma** è un quadrilatero che ha un centro di simmetria e quindi
possiede le seguenti proprietà:

* ha i lati opposti paralleli e congruenti
* ha gli angoli opposti congruenti e gli angoli adiacenti supplementari
* le diagonali si incontrano nel punto medio.

### Condizioni per individuare un parallelogramma
Per riconoscere se un quadrilatero è un parallelogramma, oltre ad applicare la definizione, si può verificare che abbia una delle seguenti caratteristiche:

* i lati opposti paralleli
* una coppia di lati opposti congruenti e paralleli
* i lati opposti congruenti
* le diagonali che si incontrano nel punto medio
* gli angoli opposti congruenti oppure quelli adiacenti supplementari.

### I parallelogrammi particolari

* Il rettangolo è un parallelogramma con gli angoli retti; le sue diagonali sono congruenti
* Il rombo è un parallelogramma con i lati congruenti; le sue diagonali sono perpendicolari e bisettrici degli angoli
* Il quadrato è un parallelogramma con i lati congruenti e gli angoli retti e che quindi, riunendo in sè le caratteristiche del rettangolo e del rombo, ha le diagonali congruenti, perpendicolari e bisettrici degli angoli.

Le medesime proprietà possono essere invertite per riconoscere se un parallelogramma è un rettangolo, un rombo oppure un quadrato.

### I parallelogrammi e le isometrie
Tutti i parallelogrammi hanno un centro di simmetria ma, se non sono parallelogrammi particolari, non hanno assi di
simmetria. I soli a possedere assi di simmetria sono:

* il rettangolo, che ha per assi le rette perpendicolari a due lati opposti e passanti per il loro punto medio
* il rombo, che ha come assi le rette delle diagonali
* il quadrato, che ha come assi quelli del rombo e quelli del rettangolo.
 
### Il trapezio
Un **trapezio** è un quadrilatero che ha una coppia di lati paralleli che si dicono basi; i lati non paralleli si chiamano lati obliqui. Se capita che:

* i lati obliqui sono disuguali, il trapezio è scaleno
* i lati obliqui sono congruenti, il trapezio è isoscele
* uno dei lati obliqui è perpendicolare alle basi, il trapezio è rettangolo.
In un trapezio isoscele gli angoli adiacenti alle basi sono congruenti e anche le diagonali sono congruenti.

### La corrispondenza di Talete
Se un fascio di rette parallele interseca una trasverale $r$ nei punti $A, B, C, ...$ e una
trasversale s nei punti $A' , B' , C' , ...$ fra i due insiemi di punti si stabilisce una corrispondenza biunivoca che si chiama **corrispondenza parallela di Talete**. In tale corrispondenza, a segmenti congruenti sulla prima trasversale corrispondono segmenti congruenti sulla seconda trasversale.
Le conseguenze di questo teorema applicate ai triangoli sono le seguenti:

* se per il punto medio di un lato si traccia la parallela ad un altro lato, questa taglia il terzo lato nel suo punto medio
* il segmento che unisce i punti medi di due lati e
È parallelo al terzo lato e congruente alla sua metà.

## La circonferenza e i poligoni

### I luoghi geometrici
Un luogo geometrico è l'insieme di tutti e soli gli oggetti geometrici che hanno una stessa proprietà p; in particolare, si parla di luogo di punti quando gli oggetti sono dei punti. Fra i luoghi di punti ricordiamo:

* l'asse di un segmento: luogo dei punti equidistanti dagli estremi del segmento
* la bisettrice di un angolo: luogo dei punti equidistanti dai lati dell'angolo

### La circonferenza e il cerchio
La **circonferenza** è il luogo dei punti equidistanti da un punto fisso che si chiama centro; la distanza dal centro comune a tutti i punti è il raggio. Il **cerchio** è invece il luogo dei punti che hanno distanza dal centro minore o uguale al raggio; esso è quindi la figura convessa che ha come contorno la circonferenza.

Queste figure sono le figure simmetriche per eccellenza perché hanno:

* un centro di simmetria: il centro della circonferenza
* infiniti assi di simmetria: qualunque retta che passa per il centro.

Si dimostra poi che per individuare una circonferenza sono necessari e sufficienti tre punti non allineati.

### Elementi di una circonferenza
In una circonferenza si possono individuare alcuni elementi:

* le **corde**, sono i segmenti che hanno per estremi due punti della circonferenza; la corda che passa per il centro si chiama diametro
* gli **archi**, sono le parti di circonferenza delimitate da due suoi punti
* gli **angoli al centro**, sono gli angoli che hanno il vertice nel centro della circonferenza.

Si verifica che:

* ad archi congruenti corrispondono corde e angoli al centro rispettivamente congruenti
* corde che hanno uguale distanza dal centro sono congruenti e viceversa.

### Posizioni reciproche di rette e circonferenze
In uno stesso piano, una retta e una circonferenza non possono avere più di due punti in comune; indicata con $d$ la distanza del cen-
tro della circonferenza dalla retta e con $r$ il
raggio si ha che la retta:
* è **secante** se $d < r$
* è **tangente** se $d \cong r$
* è **esterna** se $d > r$

Relativamente alle rette tangenti si può inoltre dire che:

* ogni retta tangente è perpendicolare al raggio nel punto di tangenza
* se da un punto esterno ad una circonferenza si conducono le due rette ad essa tangenti, i segmenti di tangenza sono congruenti e la retta che unisce il punto esterno con il centro è bisettrice dell'angolo formato dalle due tangenti.

### Angoli alla circonferenza e angoli al centro
Ciascun angolo che ha il vertice sulla circonferenza e per lati due semirette secanti oppure una semiretta secante e
l'altra tangente si dice **angolo alla circonferenza**.

Ad ogni angolo alla circonferenza $\alpha$ corrisponde un angolo al centro che ha il vertice nel centro della circonferenza e insiste sullo stesso arco su cui insiste $\alpha$. L'angolo al centro è sempre il doppio del corrispondente angolo alla circonferenza; di conseguenza, tutti gli angoli alla circonferenza che insistono sullo stesso arco sono fra loro congruenti. In particolare, angoli che insistono su una semicirconferenza sono retti.

### Poligoni inscritti e circoscritti
Un poligono si dice:

* **inscritto** in una circonferenza se tutti i suoi vertici sono punti della circonferenza; la circonferenza, a sua volta, si dice circoscritta al poligono.

Condizione necessaria e sufficiente affinché un poligono sia **inscrittibile** in una circonferenza è che gli assi dei suoi lati si intersechino in uno stesso punto che è il centro della circonferenza

* **circoscritto** a una circonferenza se tutti i suoi lati sono tangenti alla circonferenza che, a sua volta, si dice inscritta nel poligono; il raggio della circonferenza è l'**apotema** del poligono.

Condizione necessaria e sufficiente affinché un poligono sia circoscrittibile ad una circonferenza è che le bisettrici dei suoi angoli si intersechino in uno stesso punto che è il centro della circonferenza.

Relativamente ai quadrilateri valgono poi le seguenti proprietà:

* un quadrilatero è inscrittibile in una circonferenza se e solo se gli angoli opposti sono supplementari
* un quadrilatero è circoscrittibile a una circonferenza se e solo se la somma di due lati opposti è congruente alla somma degli altri due.

{{%expand "Mostra grafico dell'approssimazione fra aree dei poligoni e del cerchio" %}}
<div align="center">
<div id="inscr_circ" class="jxgbox" style="width:700px; height:700px;"></div>
<script type="text/javascript">
var brd = JXG.JSXGraph.initBoard('inscr_circ', {boundingbox: [-6, 6, 6, -6], grid: true});
var n = brd.createElement('slider',[[-5,5],[4.5,5],[3,4,25]],{name:'n lati ',snapWidth:1});
var p0 = brd.create('point',[0,0],{strokeColor:'black',fillColor:'white',name:''});
var p1 = brd.create('point',[4,0],{strokeColor:'black',fillColor:'white',name:''});
var rot = brd.create('transform', [function() {return Math.PI*2.0/n.Value();},p0], {type:'rotate'});  // angle, rotation center
var ptmp = brd.create('point',[0,0],{visible:false,withLabel:false});  // dummy point for the rotation
var cOut = brd.create('curve',[[0],[0]],{fillColor:'#5e9abf',highlightFillColor:'#5e9abf',fillOpacity:1,highlightFillOpacity:1,strokeColor:'black',highlightStrokeColor:'black'});
var circ = brd.create('circle',[p0,p1],{fillColor:'#fefd4c',highlightFillColor:'#fefd4c',fillOpacity:0.5,highlightFillOpacity:0.5,strokeColor:'black',highlightStrokeColor:'black'});
var cIn = brd.create('curve',[[0,1,2],[0,1,2]],{fillColor:'#d769a3',highlightFillColor:'#d769a3',fillOpacity:1,highlightFillOpacity:1,strokeColor:'black',highlightStrokeColor:'black'});
var tCirc = brd.create('text',[-4.5,-3.0,function(){
    return 'Area del cerchio = ' + (0.0625*circ.getRadius()*circ.getRadius()*Math.PI).toFixed(5);
  }],{fontSize:15});
var tIn = brd.create('text',[-4.5,-3.5,function(){
    return 'Area del poligono inscritto di ' +n.Value().toFixed(0)+ ' lati = ' + (0.0625*n.Value()*circ.getRadius()*circ.getRadius()*Math.sin(Math.PI/n.Value())).toFixed(5);
  }],{fontSize:15});
var tOut = brd.create('text',[-4.5,-4.0,function(){
    return 'Area del poligono circoscritto di  ' +n.Value().toFixed(0)+ ' lati = ' + (0.0625*n.Value()*circ.getRadius()*circ.getRadius()*Math.tan(Math.PI/n.Value())).toFixed(5);
  }],{fontSize:15});
cIn.updateDataArray = function() {
  var i, len = n.Value();
  this.dataX = [p0.X()+circ.getRadius()];
  this.dataY = [p0.Y()];
  ptmp.setPositionDirectly(JXG.COORDS_BY_USER, [p0.X()+circ.getRadius(), p0.Y()]);
  for (i=0;i<len;i++) {
    rot.applyOnce(ptmp);
    this.dataX.push(ptmp.X());
    this.dataY.push(ptmp.Y());
  }
}
cOut.updateDataArray = function() {
  var i, len = n.Value();
  var s = circ.getRadius()/Math.cos(Math.PI/n.Value());
  this.dataX = [p0.X()+s];
  this.dataY = [p0.Y()];
  ptmp.setPositionDirectly(JXG.COORDS_BY_USER, [p0.X()+s,p0.Y()]);
  for (i=0;i<len;i++) {
    rot.applyOnce(ptmp);
    this.dataX.push(ptmp.X());
    this.dataY.push(ptmp.Y());
  }
}
brd.update();
</script>
</div>
{{% /expand%}}


### Poligoni regolari
Un poligono si dice **regolare** se ha tutti i lati e tutti gli angoli fra loro congruenti. Se un poligono è regolare, allora:

* ha tanti assi di simmetria quanti sono i suoi lati
* ha un centro di simmetria solo se ha un numero pari di lati
* è sempre inscrittibile e circoscrittibile a una circonferenza e le due circonferenze inscritta e circoscritta hanno lo stesso centro.

### Punti notevoli dei triangoli
In ogni triangolo: 

* gli assi dei lati si intersecano in uno stesso punto chiamato **circocentro** che è il centro della circonferenza circoscritta al triangolo
* le bisettrici degli angoli si intersecano in uno stesso punto chiamato **incentro** che è il centro della circonferenza inscritta nel triangolo
* le altezze si intersecano in uno stesso punto chiamato **ortocentro**
* le mediane si incontrano in uno stesso punto detto **baricentro**; il baricentro divide ciascuna mediana in due parti delle quali quella che contiene il vertice è doppia dell'altra.

Il triangolo è quindi il solo poligono che è sempre sia inscrittibile che circoscrittibile a una circonferenza.















