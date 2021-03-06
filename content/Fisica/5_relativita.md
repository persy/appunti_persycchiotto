---
title: "La relatività"
draft: false
weight: 5
---

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

In fisica con teoria della relatività si intendono in generale le trasformazioni matematiche che devono essere applicate alle descrizioni dei fenomeni fisici nel passaggio tra due sistemi di riferimento in moto relativo tra loro, secondo il principio di relatività.

L'espressione è usata anche nel linguaggio comune per riferirsi alle teorie della relatività ristretta o della relatività generale, in quanto esempi più noti del principio di relatività.


## La relatività dello spazio e del tempo 

### L'esperimento di Michelson e Morley 

Michelson e Morley tentarono di mettere in evidenza, grazie a uno speciale interferometro, il movimento della Terra rispetto all'etere, un ipotetico fluido che si riteneva propagasse le onde luminose. I due ricercatori, però, non riuscirono a rilevare alcun effetto.

### Il tempo assoluto 

È il tempo secondo la concezione della meccanica classica: in tutti i sistemi di riferimento gli orologi segnano il trascorrere del tempo con lo stesso ritmo.

_Se esiste il tempo assoluto, anche il giudizio di simultaneità tra due eventi è assoluto; se due fenomeni sono simultanei secondo un osservatore, lo sono secondo ogni altro osservatore in moto rispetto al primo._

### Gli assiomi della relatività 

Albert Einstein pose alla base della sua teoria i seguenti assiomi:

1.  le leggi e i principi della fisica hanno la stessa forma in tutti i sistemi di riferimento inerziali
2.  la velocità della luce è la stessa in tutti i sistemi di riferimento inerziali, indipendentemente sia dal moto del sistema che da quello della sorgente da cui la luce è emessa

_Il secondo assioma di Einstein spiega il risultato nullo dell'esperimento di Michelson e Morley._

### Relatività della simultaneità 

Per definizione, diciamo che due fenomeni sono _simultanei_ se la luce che essi emettono giunge nello stesso istante in un punto $M$ equidistante dai punti in cui essi avvengono, Abbiamo dimostrato che il giudizio di simultaneità e _relativo_ in quanto dipende dal sistema di riferimento in cui ci si trova.

_Se la velocità della luce fosse infinitamente grande, il giudizio di simultaneità sarebbe assoluto, cioè sarebbe condiviso da tutti gli osservatori in moto relativo. In tal caso esisterebbe il tempo assoluto._

### Sincronizzazione degli orologi 

Il fatto che la velocità della luce ha un valore finito impone di indicare in modo esatto il procedimento operativo necessario per sincronizzare orologi lontani tra loro. Uno sperimentatore che si trova in prossimità dell'orologio $2$, posto a distanza $d$ dall'orologio $1$, deve regolare l'orologio $1$ al valore $t = t_0 + D / c$ nell'istante in cui vede l'orologio $1$ segnare il valore $t = t_0$.

_La procedura illustrata serve a tenere conto che lo sperimentatore posto vicino all'orologio_ $2$ _vede l'orologio_ $1$ _segnare il valore_ $t = t_0$ _dopo che è trascorso un intervallo di tempo_ $\Delta t = D / c$ _dall'istante in cui la luce partiva dall'orologio_ $1$.

### Dilatazione dei tempi 

Un fenomeno che ha durata $\Delta t$ nel sistema di riferimento $S$ solidale con esso ha una durata $\Delta t'$ diversa da $\Delta t$ quando la misurazione è effettuata in un altro sistema di riferimento che si muove con velocità di modulo $v$ rispetto a $S$. La relazione tra le due durate è data dalla formula

<div align="center">
$\Delta t' = \dfrac{1}{\sqrt{1 - \left ( \dfrac{v}{c} \right)^2}} \Delta t = \gamma \Delta t$
</div>

### Intervallo di tempo proprio 

Secondo la formula precedente, la durata di un fenomeno ha il valore minimo quando è misurata nel sistema di riferimento solidale con esso. Tale durata minima si indica con $\Delta \tau$ e prende il nome di _intervallo di tempo proprio_ del fenomeno.

_L'intervallo di tempo che intercorre tra la creazione di una particella elementare e il suo decadimento è minimo nel sistema di riferimento della particella, cioè quello in cui la particella è ferma, e risulta più lungo per tutti gli osservatori che vedono la particella in moto._

### Contrazione delle lunghezze nella direzione del moto 

Un segmento $AB$ che misura $\Delta x$ nel sistema di riferimento $S$ solidale con esso risulta avere una lunghezza $\Delta x'$ minore in un sistema di riferimento che si muove, rispetto a $S$, con una velocità $\vec v$ parallela ad $AB$. La relazione tra le due lunghezze è data dalla formula

<div align="center">
$\Delta x' = \dfrac{\Delta x}{\gamma} = \sqrt{1 - \dfrac{v^2}{c^2}} \Delta x$
</div>

### Lunghezza propria 

Secondo la formula precedente, la lunghezza di un segmento ha il valore massimo quando è misurata nel sistema di riferimento solidale con esso. Tale lunghezza massima prende il nome di _lunghezza propria_ del segmento

_Un regolo che è lungo un metro nel sistema di riferimento solidale con esso, cioè in cui esso è fermo, in tutti i sistemi di riferimento che si muovono parallelamente a esso risulta avere una lunghezza inferiore._

### Invarianza delle lunghezze perpendicolari al moto 

Un segmento disposto in direzione perpendicolare a quella del moto relativo tra due sistemi di riferimento ha la stessa lunghezza in entrambi i sistemi.

_"Più veloce" implica che il corpo appare "più corto" ma non "più stretto" o "più largo"._

### Trasformazioni di Lorentz 

Forniscono le leggi che permettono di passare dalle rilevazioni spaziali e temporali nel sistema $S$ a quelle che si ottengono in un sistema di riferimento $S'$
 in moto rispetto a $S$ a velocità $\vec v$. Facendo le convenzioni che 

1.  gli assi coordinati dei due sistemi sono paralleli ed equiversi
2.  $\vec v$ è parallelo agli assi delle ascisse dei due sistemi
3.  all'istante $t = t' = 0$ le origini dei due sistemi coincidono, le trasformazioni di Lorentz assumono la forma

<div align="center">
$\begin{cases} x' &= \dfrac{x -vt}{\sqrt{1 - \dfrac{v^2}{c^2}}} = \gamma (x - vt); \\ y' &= y; \\ z' &= z; \\ t' &= \dfrac{t - \dfrac{vx}{c^2}}{\sqrt{1 - \dfrac{v^2}{c^2}}} = \gamma \left ( t - \dfrac{\beta}{c} x \right ) \end{cases}$
</div>


Le trasformazioni di Lorentz sostituiscono, nella teoria della relatività ristretta, quelle di Galileo. Queste ultime, comunque, si ritrovano come approssimazione di bassa velocità di quelle di Lorentz.



## La relatività ristretta 

### Evento 

È il nome che si dà alla quaterna ordinata ($t$, $x$, $y$, $z$) che fornisce l'istante $t$ in cui un dato avvenimento ha luogo e la posizione spaziale ($x$, $y$, $z$) in cui esso è avvenuto.

_L'evento è la descrizione matematica, in un dato sistema di rifornimento inerziale, del fatto che è avvenuta una certa cosa, in un punto assegnato e a un istante di tempo preciso._

### Intervallo invariante 

L'intervallo invariante relativo a due eventi separati dalle differenze di coordinate $\Delta t$, $\Delta x$, $\Delta y$, $\Delta z$ è definito dalla relazione

<div align="center">
$ (\Delta \sigma  ) ^2 \overset{def}{\equiv} (c \Delta t  ) ^2 -  (\Delta x  ) ^2 - t (\Delta x  ) ^2 -  (\Delta z  ) ^2$
</div>

Passando da un sistema di riferimento inerziale a un altro in moto relativo rispetto a esso, variano i valori di $\Delta t$, $\Delta x$, $\Delta y$, $\Delta z$ ma non quello di $\Delta \sigma$.

_L'intervallo invariante è la "distanza" che separa due eventi. Come la distanza in due e tre dimensioni, il suo valore non dipende dal sistema di riferimento scelto per descrivere gli eventi._

### spaziotempo 

È lo spazio a quattro dimensioni in cui l'intervallo invariante ha la forma data nella definizione precedente.

### Composizione delle velocità 

Le trasformazioni di Lorentz permettono di dimostrare che, se un corpo ha velocità $u$ in un sistema di riferimento $S$, la sua velocità $u'$ in un sistema di riferimento che si muove a velocità $v$ rispetto a $S$ è

<div align="center">
$u' = \dfrac{u - v}{1 - \dfrac{uv}{c^2}}$
</div>

Da tale formula si ricava

<div align="center">
$u = \dfrac{u' + v}{1 + \dfrac{u'v}{c^2}}$
</div>

Per semplicità, entrambe le espressioni si riferiscono al caso in cui i vettori $\vec u$ e $\vec v$ sono paralleli fra di loro.

_Con le formule precedenti, non è mai possibile comporre due velocità con moduli minori o uguali a_ $c$ _e ottenere una nuova velocità con modulo maggiore di_ $c$.

### Equivalenza tra massa ed energia 

Un corpo che assorbe o emette energia aumenta o diminuisce la propria massa secondo la relazione

<div align="center">
$\Delta m = \dfrac{E}{c^2}$
</div>

### Energia di riposo di un corpo 

È l'energia di massa che compete a un corpo fermo di massa $m_0$:

<div align="center">
$E_0 = m_0 c^2$
</div>

Nella teoria della relatività il principio di conservazione dell'energia è verificato soltanto se, nel bilancio energetico, si tiene conto anche dell'energia di riposo dei corpi.

### Energia totale di un corpo 

Un corpo che, nel sistema di riferimento in cui è in quiete, ha una massa $m_0$ e che si muove con velocità $v$ ha un'energia totale data dalla relazione

<div align="center">
$E = \dfrac{m_0 c^2}{\sqrt{1 - \dfrac{v^2}{c^2}}} = \gamma m_0 c^2$
</div>

_L'energia di riposo del corpo non è altro che la sua energia totale misurata nel sistema di riferimento solidale con esso, cioè nel sistema di riferimento in cui il corpo ha_ $v = 0$.

### Velocità limite 

Nessun corpo dotato di massa può essere accelerato fino alla velocità della luce nel vuoto. Infatti, per accelerarlo fino a tale velocità sarebbe necessaria un'energia infinita.

### Energia cinetica relativistica di un corpo 

È definita come la differenza tra l'energia totale del corpo e la sua energia di riposo:

<div align="center">
$K_r \overset{def}{\equiv} (\gamma - 1)m_0 c^2$
</div>

_L'energia cinetica classica_ $K = \dfrac{1}{2} m v^2$ _risulta essere un'approssimazione, valida quando_ $v$ _è molto minore di_ $c$, _dell'energia cinetica relativistica._

### Massa relativistica di un corpo 

È utile definire la massa relativistica $m$ di un corpo che, nel sistema di riferimento in cui è in quiete, ha massa $m_0$ e che si muove con velocità $v$ attraverso la relazione

<div align="center">
$m \overset{def}{\equiv} \gamma m_0 = \dfrac{m_0}{\sqrt{1 - \dfrac{v^2}{c^2}}}$
</div>

Grazie a tale definizione l'energia totale $\Delta E$del corpo può essere scritta nella famosa forma

<div align="center">
$E = m c^2$
</div>

Per $v = 0$, $m$ diviene uguale a $m_0$. Tale quantità prende il nome di _massa di riposo_ del corpo.

### Quantità di moto relativistica di un corpo 

Dato un corpo che, alla velocità $v$, ha massa relativistica $m$, nella teoria della relatività la sua quantità di moto è definita come

<div align="center">
$\vec p_r \overset{def}{\equiv} m \vec v = \dfrac{m_0 \vec v}{\sqrt{1 - \dfrac{v^2}{c^2}}}$
</div>

_Come nel caso dell'energia cinetica, anche la quantità di moto classica è una approssimazione della relazione relativistica, valida per basse velocità._

### Effetto Doppler relativistico 

Consideriamo una sorgente che emette onde luminose di frequenza $f$ e un osservatore che si muove rispetto a essa. Se sorgente e osservatore si allontanano, la frequenza $f'$ della luce rilevata dall'osservatore è

<div align="center">
$f' = f \sqrt{\dfrac{1 - \beta}{1 + \beta}}$
</div>

Se sorgente e osservatore si avvicinano, la relazione tra $f$ e $f'$ è

<div align="center">
$f' = f \sqrt{\dfrac{1 + \beta}{1 - \beta}}$
</div>

In entrambe le relazioni, $\beta$ è il rapporto $\dfrac{v}{c}$. dove $v$ è la velocità relativa tra sorgente e osservatore e $c$ è la velocità della luce nel vuoto.

_Secondo le relazioni precedenti, la luce emessa da un corpo celeste che si allontana da noi giunge sulla Terra con una frequenza inferiore a quella con cui era stata emessa (spostamento verso il rosso o redshift). Al contrario, la luce che proviene da un corpo celeste in avvicinamento giunge sulla Terra con una frequenza superiore a quella originale (spostamento verso il blu o blue-shift)._

## Relatività generale 

### Principio di equivalenza 

Stabilisce che, in una zona delimitata dello spaziotempo, è sempre possibile scegliere un opportuno sistema di riferimento in modo da simulare l'esistenza di un dato campo gravitazionale uniforme o, reciprocamente, in modo da eliminare l'effetto di una forza di gravità costante.

_Per esempio, in un ascensore in caduta libera si avverte la sensazione di "assenza di peso", come se ci si trovasse lontano da qualunque corpo celeste. Al contrario, all'interno di un'astronave in accelerazione si avvertirebbe la presenza di gravità, anche se l'astronave stesse navigando nello spazio profondo._

### Principio di relatività generale 

Secondo il principio di relatività generale, le leggi della fisica hanno la stessa forma in tutti i sistemi di riferimento.

_Il principio di relatività generale supera e completa quello di relatività ristretta, che privilegia i sistemi di riferimento inerziali._

### Gravità e curvatura dello spaziotempo 

La relatività generale spiega gli effetti gravitazionali grazie a una duplice idea:

1.  la presenza di masse incurva lo spaziotempo
2.  i corpo soggetti alla forza di gravità devono essere considerati come particelle libere, che si muovono seguendo le _geodetiche_ dello spaziotempo.

_La materia "dice" allo spaziotempo come deve modellarsi. Lo spaziotempo "dice" alla materia come deve muoversi._

### Spazi piatti 

Sono spazi a curvatura nulla, come lo spazio euclideo e lo spaziotempo di Minkowski. In tali spazi esiste ed è unica la parallela a una retta condotta da un punto esterno alla retta stessa (quinto postulato di Euclide)

_Noi usiamo il termino spaziotempo ma, dal punto di vista geometrico, esso non è altro che un unico spazio, a quattro dimensioni._

### Spazi curvi 

Sono spazi con curvatura positiva (spazi ellittici) o negativa (spazi iperbolici). In essi non vale il quinto postulato di Euclide.

### Equazione di campo di Einstein 

È il cuore della teoria della relatività generale e fa uso di matematica avanzata. Permette di calcolare la geometria dello spaziotempo se è nota la distribuzione delle masse.

### Curve geodetiche 

In un dato spazio, sono le linee di minima lunghezza che connettono due punti fissati.

_Nello spazio euclideo le geodetiche sono segmenti di retta. Sulla sfera sono archi di circonferenza massima._

### Effetti della gravità sulla luce 

In un campo gravitazionale (cioè nello spaziotempo curvo) la luce è deflessa. Inoltre, la frequenza di un raggio luminoso diminuisce quando esso, in un campo gravitazionale, passa da zone dove è più intenso ad altre dove è meno intenso (_redshift gravitazionale_)

### Onde gravitazionali 

La geometria dello spaziotempo, essendo determinata dalla distribuzione delle masse presenti in esso, varia al variare di tale distribuzione. La modifica della geometria si propaga nello spaziotempo a velocità 

, partendo dalla zona in cui essa è stata generata. Tale propagazione della variazione della geometria spaziotemporale è un'onda gravitazionale.

_L'onda gravitazionale è una perturbazione dello spaziotempo che si propaga con carattere ondulatorio._

_Fu prevista nel 1916 nell'ambito della teoria della relatività generale, nella quale l'equazione di campo di Einstein (linearizzata) ammette soluzioni ondulatorie per il tensore metrico, così come avviene per le equazioni di Maxwell riguardo al campo elettromagnetico. Le onde gravitazionali sono quindi a tutti gli effetti una forma di radiazione: al loro passaggio le distanze tra punti dello spazio tridimensionale curvo all'interno del campo gravitazionale si contraggono ed espandono ritmicamente._

_Esistono diversi rivelatori di onde gravitazionali, ma in pochi casi è stato possibile interpretare i dati sperimentali in modo chiaro e univoco. L'evento più significativo è stato annunciato l'11 febbraio 2016 dalla collaborazione LIGO/VIRGO, che nel settembre 2015 ha misurato onde gravitazionali causate dalla collisione di due buchi neri._
