---
title: "Geometria 2"
draft: false
weight: 4
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


## Equivalenza dei poligoni e il calcolo delle aree

* Due figure $A$ e $B$ si dicono **equivalenti** se hanno la stessa estensione. La caratteristica comune a tutte le figure equivalenti si chiama **area**.
* Date due figure $A$ e $B$ aventi in comune solo una parte del contorno, si definisce loro **somma** la figura $F$ ottenuta dalla loro uione; viceversa se $A + B \doteq F$, la figura $A$ è la **differenza** tra le figure $F$ e $B$, la figura $B$ è la differenza tra $F$ e $A$.

Si verifica che le somme o differenze di figure congruenti oppure equivalenti sono equivalenti.

### I criteri di equivalenza dei poligoni
Due figure che sono somme di figure congruenti si dicono **equicomposte**; due figure equicomposte sono anche equivalenti.

L'equiscomponibilità permette di enunciare i seguenti criteri di equivalenza fra poligoni particolari:

1. due parallelogrammi sono equivalenti se hanno basi e altezze ordinatamente congruenti
2. un parallelogramma e un triangolo sono euivalenti se hanno basi congruenti e se l'altezza del triangolo è doppia di quella del parallelogramma, oppure se hanno altezze congruenti e se la base del triangolo è doppia di quella del parallelogramma
3. un trapezio è equivalente a un triangolo che ha per base la somma delle basi del trapezio e l'altezza congruente a quella del trapezio
4. un poligono circoscritto a una circonferenza è equivalente a un triangolo che ha per base il perimetro del poligono e per altezza il raggio della circonferenza

§IMMAGINI§ 

### I teoremi di Pitagora e di Euclide
In un triangolo rettangolo valgono i seguenti teoremi:

* **teorema di Pitagora**: il quadrato costruito sull'ipotenusa è equivalente alla somma dei quadrati costruiti sui cateti: $q(BC) \doteq q(AB) + q(AC)$
* **primo teorema di Euclide**: il quadrato costruito su un cateto è equivalente al rettangolo che ha come lato l'ipotenusa e la proiezione del cateto sull'ipotenusa: $q(AB) \doteq r(BC, \space BH)$ e $q(AC) \doteq r(BC \space HC)$
* **secondo teorema di Euclide**: il quadrato costruito sull'altezza relativa all'ipotenusa è equivalente al rettangolo che ha per lati le proiezioni dei cateti sull'ipotenusa: $q(AH) \doteq r(BH, \space HC)$

§IMMAGINE§

### Grandezze omogeneee
Un insieme $G$ di elementi costituisce una **classe di grandezze omogenee** se:

* due qualsiasi elementi di $G$ sono sempre confrontabili
* esiste in $G$ un'operazione di addizione commutativa, associativa e dotata di elemento neutro

Due grandezze di una stessa classe si dicono **commensurabili** se hanno un sottomultiplo comune, **incommensurabili** in caso contrario.

Fissata un'unità di misura omogenea con le grandezze di quella classe, a ciascun elemento di $G$ si può associare una misura che è sempre espressa da un numero reale che è:

* razionale se le due grandezze sono commensurabili
* irrazionale se le due grandezze sono incommensurabili

**Rapporto** fra due grandezze omogenee $A$ e $B$ è la misura di $A$ quando $B$ è assunta come unità di misura; si verifica poi che il rapporto $\dfrac{A}{B}$ è anche uguale al quoziente fra le misura delle due grandezze rispetto ad una unità di misura comune.

Se il rapporto fra due grandezze è uguale al rapporto fra altre due (omogenee fra loro le prime e omogenee fra loro le seconde), si dice che le quattro grandezze sono **in proporzione**.

### Proporzionalità diretta e inversa
Due insiemi di grandezze in corrispondenza biunivoca sono:

* **direttamente proporzionali** se il rapporto fra due grandezze del primo insieme è uguale al rapporto fra le corrispondenti due del secondo per ogni coppia di elementi considerati
* **inversamente proporzionali** se il rapporto fra due grandezze del primo insieme è uguale al rapporto inverso fra le corrispondenti due del secondo per ogni coppia di elementi considerati

Oltre che applicando la definizione, si può stabilire se due insiemi di grandezze sono direttamente proporzionali mediante un **criterio generale di proporzionalità**; $A$ e $B$ sono insiemi di grandezze proporzionali se e solo se:

* ad elementi uguali in $A$ corrispondono elementi uguali in $B$ e
* alla somma di due elementi in $A$ cprrisponde la sonna del corrispondenti elementi di $B$
 
### Il teorema di Talete e le sue conseguenze
Le proprietà della proporzionalità diretta relativamente alle figure geometriche sono evidenziate da alcuni teoremi:

* **teorema di Talete**: un fascio di rette parallele intercetta su due trasversali segmenti direttamente proporzionali
* **teorema della bisettrice dell'angolo interno**: la bisettrice di un angolo di un triangolo divide il lato opposto in parti proporzionali agli altri due lati: $BD : DC = AB : AC$
* **teorema della bisettrice dell'angolo esterno**: se la bisettrice di un angolo esterno di un triangolo incontra la retta del lato opposto in un punto $P$, il segmento $PC$ ed il segmento $PB$ stanno nello stesso rapporto degli altri due lati del triangolo: $PC : PB = AC : AB$

§IMMAGINI§

### Le aree dei poligoni
Le principali formule per il calcolo delle aree sono:

* rettangolo di dimensioni $b$ e $h$: $b \cdot h$
* Un quadrato di lato $l$: $l^2$
* parallelogramma di base $b$ e $h$: $b \cdot h$
* triangolo di base $b$ e altezza $h$: $\dfrac{1}{2} b \cdot h$
    * oppure: $\sqrt{p (p - a)(p - b)(p - c)}$ dove $p$ è il semiperimetro e $a$, $b$ e $c$ i lati del triangolo
* trapezio di basi $b$ e $B$ e altezza $h$: $\dfrac{1}{2} (B + b) \cdot h$
* rombo di diagonali $d_1$ e $d_2$: $\dfrac{1}{2} d_1 \cdot d_2$
* poligono di semiperimetro $p$ circoscritto a circonferenza di raggio $r$: $p \cdot r$

### I teoremi di Pitagora e di Euclide
Qualunque relazione tra elementi omogenei di un poligono si può estendere alle misure di quelle grandezze; in particolare:

* teorema di Pitagora: $\overline{AB} ^2 + \overline{AC} ^2 = \overline{BC} ^2$
* primo teorema di Euclide: $\overline{AB} = \overline{BC} \cdot \overline{BH} \wedge \overline{AC} ^2 = \overline{BC} \cdot \overline{HC}$
* secondo teorema di Euclide: $\overline{AH} ^2 = \overline{BH} \cdot \overline{HC}$

### La lunghezza della circonferenza e l'area del cerchio
La lunghezza di una linea curva può essere definita mediante una poligonale approssimante con un numero infinito di lati. In particolare la lunghezza di una circonferenza è definita mediante i poligoni in essa inscritti e ad essa circoscritti.
Le formule per il calcolo della lunghezza $C$ della circonferenza rettificata e dell'area $s$ del cerchio sono:

* $C = 2 \pi r$
* $S = \pi r^2$

Dalla proporzionalità tra angoli al centro $\alpha$ (in gradi) e archi $l$ e fra angoli al centro e settori circolati $T$ si deducono poi le seguenti relazioni:

* $l = 2 \pi r \cdot \dfrac{\alpha}{360}$
* $T = \pi r^2 \cdot \dfrac{\alpha}{360}$

## Omotetie e similitudini

### L'omotetia
Fissati in un piano un punto $O$ e un numero reale $k$ non nullo, si dice **omotetia di centro $O$ e rapporto $k$** la trasformazione del piano in sé che a dogni punto $P$ associa il punto ${P}'$ così costruito: si traccia la retta $OP$ e si prende su di essa il punto ${P}'$ tale che sia $OP' \cong |k|OP$ con la convenzione che se $k > 0$ allora ${P}'$ si trova dalla stessa parte di $P$ rispetto ad $O$, se $k < 0$ allora ${P}'$ si trova da parte opposta di $P$ rispetto ad $O$.

In particolare, se $k =1$ l'omotetia coincide con la trasformazione identica, se $k = -1$ coincide con la simmetria di centro $O$.

§IMMAGINE§

### Le proprietà dell'omotetia
L'omotetia gode delle seguenti proprietà:

* trasforma una retta $r$ in una retta $r'$ ad essa parallela
* trasforma un segmento $AB$ in un segmento ${A}'{B}'$ ad esso parallelo e tale che sia ${A}'{B}' \cong |k|AB$
* trasforma un angolo in un angolo ad esso congruente
* il rapporto fra i perimetri di due poligoni omotetici è $|k|$
* l rapporto fra le aree di due poligoni omotetici è $k^2$

Inoltre si verifica che due triangoli che hanno i lati a due a due paralleli si corrispondono sempre in una omotetia.

### La similitudine
Una similitudine di rapporto $k > 0$ è la trasformazione che si ottiene applicando, in un ordine qualsiasi, una omotetia
di rapporto $k$ o $-k$ e una isometria. In una similitudine:

* il rapporto fra segmenti corrispondenti è uguale $k$
* angoli che si corrispondono sono congruenti.

Inoltre, due poligoni sono simili se e solo se hanno tutti i lati proporzionali e tutti gli angoli ordinatamente congruenti.

### I criteri di similitudine dei triangoli
La similitudine fra triangoli può essere riconosciuta in base a tre **criteri di similitudine** i quali affermano che due triangoli sono simili se hanno:

* due angoli ordinatamente congruenti (**primo criterio**)
* due lati proporzionali e l'angolo fra essi compreso congruente (**secondo criterio**)
* tre lati proporzionali (**terzo criterio**)

Se due triangoli sono simili, allora:

* il rapporto fra altezze, mediane, bisettrici omologhe è uguale al rapporto di similitudine
* il rapporto fra i perimetri è uguale al rapporto di similitudine
* il rapporto fra le aree è uguale al quadrato del rapporto di similitudine

Inoltre, in ogni triangolo rettangolo:

* ciascun cateto è medio proporzionale fra l'ipotenusa e la proiezione del cateto stesso sull'ipotenusa:

<div align="center">
$BC : AB = AB : BH$
</div>

<div align="center">
$BC : AC = AC : HC$
</div>

* l'altezza relativa all'ipotenusa è media proporzionale fra le proiezioni dei cateti sull'ipotenusa

<div align="center">
$BH : AH = AH : HC$
</div>

§IMMAGINI§

### Le applicazioni
Relativamente a duna circonferenza e alle sue corde, secanti e tangenti, valgono le seguenti proprietà:

1. se due corde di una circonferenza si intersecano, i segmenti di una corda sono i medi, i segmenti dell'altra corda sono gli estremi di una proporzione
2. se da un punto esterno si tracciano due secanti, una secante e la sua parte esterna sono i medi, l'altra secante e la sua parte esterna sono gli estremi di una proporzione
3. se da un punto esterno a una circonferenza si tracciano una secante e una tangente, il segmento di tangente è medio proporzionale fra l'intera secante e la sua parte esterna.

§IMMAGINI§
