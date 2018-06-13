---
title: "2. Astronomia fondamentale"
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

Osservando il cielo di notte, le stelle sembrano essere “fisse”, cioè come “incastonate” tutte alla stessa distanza dalla Terra su un immenso emisfero (sfera celeste), dotato di movimento apparente da est verso ovest. Per stabilire la posizione degli astri sulla sfera celeste sono stati concepiti vari sistemi di coordinate, costruiti sulla base di punti caratteristici e piani convenzionali. Da tali osservazioni, realizzate utilizzando strumenti astronomici sempre più raffinati, si sono evoluti sia la misura del tempo, sia le modalità della sua misurazione.

## I riferimenti sulla sfera celeste

La sfera celeste, o volta celeste, può essere considerata come una sfera di raggio infinito con centro in corrispondenza dell’osservatore stesso, che si suppone collocato al centro della Terra (la sfera celeste si può considerare un ingrandimento immensamente esteso della sfera terrestre, perciò l’equatore celeste si trova al medesimo piano dell’equatore terrestre e l’asse della sfera celeste, detto asse del mondo, si trova sul prolungamento dell’asse di rotazione terrestre).

Per studiare il moto dei corpi celesti, occorre fissare sulla sfera celeste dei riferimenti per stabilire sistemi di coordinate astronomiche.

Di seguito vengono descritti i principali riferimenti sulla sfera celeste (si rammenta che, tagliando una sfera con piani passanti per il suo centro si individuano, nei punti di intersezione sulla superficie della sfera, circonferenze dette cerchi massimi).

**Polo Nord e polo Sud celesti**: sono i punti di intersezione con la sfera celeste della retta che si ottiene prolungando nelle direzioni opposte l’asse di rotazione terrestre.

**Equatore celeste**: cerchio massimo equidistante in ogni punto dai poli celesti, che divide la sfera celeste in due emisferi, settentrionale (boreale) e meridionale (australe); esso si trova nel medesimo piano in cui giace l’equatore terrestre.

**Paralleli celesti**: circoli tracciati sulla sfera celeste parallelamente all’equatore celeste e di diametro decrescente procedendo verso i poli celesti.

**Meridiani celesti**: cerchi massimi sulla sfera celeste, detti cerchi orari (a ogni ora ciascuno di essi passa davanti a un osservatore), passanti per i poli celesti e perpendicolari all’equatore celeste.

**Eclittica**: circolo massimo che il Sole sembra descrivere sulla sfera celeste durante il suo cammino annuale apparente (eclittica è anche chiamata l’orbita descritta dalla Terra nel suo moto di rivoluzione intorno al Sole); l’eclittica è inclinata di circa $23°$ rispetto all’equatore celeste e taglia quest’ultimo in due punti, detti punti equinoziali, o equinozi (nodi dell’eclittica). Il Sole passa rispettivamente per i punti equinoziali e solstiziali, attraversando l’equatore celeste in corrispondenza dell’equinozio primaverile e autunnale. Il punto dell’equinozio di primavera è detto punto gamma, o primo punto d’Ariete. Il meridiano celeste passante per i punti equinoziali è detto coluro equinoziale. A $90°$ di distanza angolare dai punti equinoziali sull’eclittica si trovano i punti solstiziali.

**Orizzonte celeste (orizzonte astronomico)**: intersezione con la sfera celeste del piano passante per il centro della Terra e perpendicolare alla verticale innalzata rispetto all’osservatore terrestre.

{{< figure src="https://upload.wikimedia.org/wikipedia/commons/6/61/AxialTiltObliquity.png" title="Sfera Celeste e piano dell'eclittica" >}}

---

**Zenit**: punto in cui la verticale innalzata dalla posizione in cui si trova l’osservatore terrestre incontra la sfera celeste.

**Nadir**: è il punto diametralmente opposto allo zenit.

**Cerchi verticali**: circoli massimi passanti per lo zenit e il nadir perpendicolari al piano dell’orizzonte celeste; il cerchio verticale passante anche per i poli celesti è detto cerchio meridiano (o meridiano celeste); il cerchio verticale perpendicolare al cerchio meridiano (detto primo cerchio verticale) taglia l’orizzonte celeste in due punti corrispondenti all’Est e all’Ovest.

{{< figure src="http://2.bp.blogspot.com/-HJddweG4R0w/UZJW00EYT0I/AAAAAAAAD5c/IXxWIJYMNws/s1600/perglossario.png" title="Cerchio meridiano e primo cerchio verticale" >}}

---

## Le coordinate celesti

L’**astronomia di posizione** considera solo le direzioni relative degli astri e le distanze apparenti tra questi, che vengono espresse in termini di angoli. Per fissare la posizione degli oggetti celesti si fa uso di **sistemi di coordinate sferiche**. La determinazione è semplificata, se supponiamo che l’osservatore si trovi al centro della sfera stessa. I sistemi di coordinate astronomiche hanno tutti un piano di riferimento passante per il centro della sfera celeste e due punti sulla sfera celeste: i due poli del piano scelto. La posizione di un punto è individuata da due coordinate: l’ascissa sferica e l’ordinata sferica. I sistemi di coordinate sono: il **sistema altazimutale**, il **primo sistema equatoriale** (o sistema orario) e il **secondo sistema equatoriale** (trattati di seguito), **il sistema di coordinate eclittiche** e il **sistema di coordinate galattiche**.

### Il sistema orizzontale (altazimutale)

**Nel sistema altazimutale il circolo di riferimento è l’orizzonte visivo dell’osservatore** (cioè la linea dell’orizzonte terrestre) e le due coordinate, che permettono di definire la posizione angolare degli astri, sono l’altezza e l’azimut. L’**altezza** è l’arco di circolo verticale (misurato in gradi, primi e secondi d’arco) compreso fra l’astro e l’orizzonte. Varia da $0°$ a $90°$, valore che assume quando l’astro è sulla verticale dell’osservatore, cioè allo zenit:

<div align="center">
$0° \leq \beta \leq 90°$
</div>

Il complemento all’altezza è detto angolo zenitale ed è la distanza angolare tra astro e zenit ($\gamma$). L’**azimut** è definito come l’arco di orizzonte compreso tra il punto Sud e il punto in cui il circolo verticale passante per l’astro incontra l'orizzonte. L’azimut si misura dal punto Sud verso ovest e varia da $0°$ a $360°$.

<div align="center">
$0° \leq \alpha \leq 360°$
</div>

**Il vantaggio di questo sistema è che si ottengono immediatamente le coordinate di un astro rispetto a un osservatore**, in quanto queste sono riferite semplicemente al suo orizzonte e alla sua verticale. Ha però l’**inconveniente che**, per un osservatore non posto al polo, in conseguenza dell’apparente rotazione diurna della sfera celeste, **i valori delle coordinate di uno stesso oggetto variano con la posizione geografica** e, per effetto della rotazione della sfera celeste, anche con l’ora di osservazione. Per ovviare a questo inconveniente, si fa uso dei sistemi di coordinate equatoriali, per i quali una sola (primo sistema) o entrambe (secondo sistema) le coordinate sono indipendenti dal tempo.

#### Primo sistema di coordinate equatoriali

Questo sistema di coordinate assume come cerchio massimo di riferimento l’**equatore celeste**. Le due coordinate sono la declinazione e l’angolo orario. Il cerchio orario passante per l’astro in oggetto è detto cerchio di declinazione. La **declinazione** di un astro è l’arco di circolo di declinazione che costituisce la distanza angolare dell’astro dall’equatore celeste. Si misura in gradi (da $0°$ a $90°$ N nell’emisfero boreale e da $0°$ a $90°$ S in quello australe):

<div align="center">
$0° \leq \delta \leq 90°$
</div>

L’**angolo orario** (H) è la distanza angolare tra il mezzocielo (punto sull’equatore celeste determinato dall’intersezione del meridiano dell’osservatore passante per i punti zenit e Sud) e il meridiano dell’oggetto celeste:

<div align="center">
$0 h \leq H \leq 24 h$
</div>

Si misura in ore (h), minuti (min) e secondi (s) con origine nel **mezzocielo** andando verso ovest. In questo sistema la declinazione resta costante, ma, per la rotazione apparente della sfera celeste, l’angolo orario assume tutti i valori tra 0 e 24 ore nell’arco di un giorno. Esso varia inoltre da punto a punto.

#### Secondo sistema di coordinate equatoriali

Usa come cerchio massimo di riferimento l’**equatore celeste** e si basa sulle coordinate celesti declinazione (vista nel caso precedente) e ascensione retta. L’**ascensione retta** (AR) è la distanza angolare tra il meridiano che passa per l’astro e il meridiano che passa per il primo punto di Ariete. Si misura in ore, minuti e secondi da 0 a 24 ore in direzione est (senso antiorario), cioè in verso contrario a quello dell’angolo orario.

<div align="center">
$0 h \leq AR \leq 24 h$
</div>

**Le coordinate definite da questo sistema sono quelle riportate nei cataloghi stellari**, negli atlanti celesti, negli annuari, in quanto indipendenti dal luogo e dall’ora di osservazione. Anche per questo sistema esiste, però, una dipendenza dal tempo, dovuta al moto proprio delle stelle e allo spostamento lento ma graduale dell’origine delle coordinate, cioè del punto γ, per effetto del moto di precessione dell’asse terrestre.

{{< figure src="https://upload.wikimedia.org/wikipedia/commons/6/66/Ra_and_dec_demo_animation_small.gif" title="Sistema di coordinate equatoriali" >}}

---

### Il moto diurno

Per effetto della rotazione della Terra attorno al suo asse, la sfera celeste descrive una **rotazione apparente** alla quale è dovuto il sorgere e il tramontare del Sole, delle stelle e degli altri corpi celesti. **Nel tempo di un giorno**, **gli astri**, **in rotazione apparente da est a ovest incontrano due volte il meridiano celeste**. In un incontro, la loro altezza sull’orizzonte è massima e si ha una culminazione superiore; nell’altro è minima e si ha una culminazione inferiore. **All’equatore i poli celesti si trovano all’orizzonte**; tutte le stelle restano al di sopra dell’orizzonte per metà di un giorno e tramontano e sorgono muovendosi perpendicolarmente all’orizzonte. **Ai poli**, invece, **l’equatore celeste coincide con l’orizzonte** e tutte le stelle si muovono in traiettorie circolari senza mai sorgere né tramontare. Nessuna stella dell’altro emisfero può essere mai osservata. A latitudini intermedie si hanno situazioni intermedie. Solo un certo gruppo di stelle, quelle circumpolari, la cui distanza dal polo è minore della latitudine dell’osservatore, non tramontano mai e di esse si può osservare sia la culminazione superiore, sia la culminazione inferiore.

### Sistemi di coordinate eclittiche e di coordinate galattiche

Il sistema di coordinate eclittiche usa come circolo massimo di riferimento l’**eclittica**, sul cui piano si muove la maggior parte dei corpi del sistema solare. Le coordinate sono la **latitudine** e la **longitudine eclittica**. La **latitudine eclittica** ($\beta$) è l’ampiezza dell’arco di circolo massimo (circolo di longitudine) compreso fra l’astro e la sua proiezione sull’eclittica. È misurata in gradi tra $0°$ e $90°$ N nell’emisfero che contiene il polo Nord celeste e tra $0°$ e $90°$ S nell’emisfero che comprende il polo Sud.

<div align="center">
$0° \leq \beta \leq 90°$
</div>

La **longitudine** ($\lambda$) è l’arco di eclittica compreso tra il punto γ e il punto in cui il circolo di longitudine passante per l’astro taglia l’eclittica. È misurata in gradi tra $0°$ e $360°$ in direzione est, in senso congruente con l’ascensione retta. Poiché la maggior parte dei pianeti si muove in prossimità del piano dell’eclittica, questo sistema è adatto alla trattazione di problemi legati al moto planetario.

<div align="center">
$0° \leq \lambda \leq 360°$
</div>

Il sistema di coordinate galattiche ha come riferimento il piano dell’**equatore galattico**; le coordinate sono la **latitudine** e la **longitudine galattica**, definite analogamente alla latitudine e longitudine celeste. Le longitudini galattiche hanno origine nel punto in cui dal sistema solare vediamo proiettato il centro galattico (nella costellazione del Sagittario). L’arco tra equatore galattico ed equatore celeste è pari a 62°.

## Strumenti di osservazione

Fino all’inizio del XVII secolo, le osservazioni del cielo venivano compiute a **occhio nudo**. Le osservazioni astronomiche si limitavano a cercare di conoscere con la maggior precisione possibile le posizioni dei corpi celesti. L’occhio permette di stimare la distanza di oggetti vicini, ma l’osservazione si complica quando si vogliono osservare stelle o pianeti. Le potenzialità dell’occhio aumentarono in modo modesto quando, nel 1609, Galileo Galilei (1564-1642) mise a punto un **cannocchiale**, precursore del telescopio astronomico. Egli riuscì tuttavia a osservare particolari fino ad allora sconosciuti, quali il rilievo lunare, le macchie solari, le fasi di Venere, i quattro maggiori satelliti di Giove; scoprì, inoltre, che la Via Lattea è formata da numerosissime stelle.

#### I telescopi

In un **telescopio** (dal greco **têle**, lontano, e **scopéo**, guardare) un telescopio, un dispositivo ottico, l’obiettivo, raccoglie la luce degli oggetti celesti e la focalizza in un punto, costruendone così l’immagine; questa viene osservata attraverso l’oculare, oppure viene raccolta su una lastra fotografica o un dispositivo elettronico. Vi sono due categorie di telescopi, in funzione del tipo di obiettivo: rifrattori e riflettori. Nel **telescopio rifrattore**, strutturalmente simile a quello usato per la prima volta da Galilei, l’obiettivo è costituito da due lenti (uno svantaggio è che non si possono utilizzare lenti con diametro molto grande). Nel **telescopio riflettore**, inventato da Newton (1642-1727) come obiettivo si usa uno specchio concavo (meno costoso, perché più facilmente realizzabile) e i raggi luminosi da esso riflessi vengono raccolti da uno specchio secondario, che li invia all’oculare o agli strumenti di analisi della luce. La nostra pupilla ha un diametro di pochi millimetri e raccoglie una quantità di energia molto limitata. Grandi specchi sono in grado di catturare una quantità di energia enormemente maggiore e ciò consente l’individuazione di oggetti celesti che, a causa della loro grande distanza, non sarebbero individuati (per esempio, il telescopio di Monte Palomar, negli Stati Uniti, può osservare la luce di stelle un milione di volte più deboli di quelle osservabili a occhio nudo). L’**ingrandimento** di un telescopio cresce con la distanza focale dell’obiettivo; le stelle, tuttavia, appaiono sempre come oggetti puntiformi. L’ingrandimento è una proprietà che entra in gioco quando si osservano sorgenti estese (pianeti). All’astronomo interessa poter “separare” due stelle molto vicine tra loro. Questa caratteristica, detta **potere risolutivo** del telescopio, dipende dal diametro dell’obiettivo e cresce con le sue dimensioni. La terza qualità è la **luminosità**, cioè la capacità di scorgere oggetti molto deboli, che aumenta al crescere del diametro dell’obiettivo. Oltre che nella banda della luce visibile, il cosmo ci invia messaggi su tutte le frequenze dello spettro elettromagnetico (raggi gamma, X, ultravioletti, infrarossi, onde radio ecc.). Oggi un ruolo importantissimo in astronomia, astrofisica e cosmologia è svolto dall’osservazione nei raggi X e gamma e dall’uso dei **radiotelescopi**, che appaiono come gigantesche antenne di forma parabolica che raccolgono le onde radio emesse dai corpi celesti e le indirizzano su un ricevitore, e il segnale ricevuto viene amplificato e analizzato. Se con i telescopi si arriva a distanza di qualche miliardo di anni luce, i radiotelescopi estendono questa capacità oltre 10 miliardi di anni-luce. La radioastronomia ha permesso la scoperta di oggetti celesti come quasar e pulsar.

#### Effetti dell’atmosfera sulle osservazioni astronomiche

L’osservazione di un astro con un telescopio da Terra è soggetta a perturbazioni da parte dell’atmosfera terrestre. L’atmosfera produce una deviazione angolare progressiva dei raggi luminosi provenienti da una sorgente celeste. È come se la traiettoria della luce fosse curva (ne risulta che l’osservatore vede l’astro a un’altezza maggiore di quella reale). Quando un raggio di luce attraversa l’atmosfera terrestre, viene parzialmente assorbito dalla massa d’aria in cui transita. Tale fenomeno è tanto più accentuato quanto più è ampio l’angolo zenitale (angolo fra la linea di zenit e il tragitto del raggio luminoso). La turbolenza atmosferica limita le prestazioni dei grandi strumenti astronomici (l’immagine fluttua irregolarmente, va “fuori fuoco”).

## Il tempo in astronomia

In astronomia si considerano due “categorie” di tempo distinte: il **tempo solare**, basato sul moto diurno del Sole, e il **tempo siderale**, basato sul moto diurno della sfera celeste. Il giorno solare è l’intervallo di tempo tra due passaggi successivi del Sole, in corrispondenza del medesimo meridiano; il giorno siderale è l’intervallo tra due passaggi al meridiano di una qualsiasi stella fissa. Le due durate, per effetto del moto terrestre, non coincidono. Si tratta in entrambi i casi di **tempi locali**, in quanto il loro valore, in uno stesso istante, dipende dalla posizione geografica (latitudine e longitudine) dell’osservatore sulla Terra; da tale variabilità è sorta l’esigenza di introdurre i **fusi orari**, 24 zone della Terra in ognuna delle quali vige convenzionalmente lo stesso tempo. Ogni fuso orario adotta l’ora del proprio meridiano centrale, che è in ritardo di un’ora rispetto al meridiano centrale immediatamente a est e in anticipo di un’ora rispetto a quello immediatamente a ovest. Il meridiano iniziale è quello di Greenwich (Londra). I fusi orari hanno in genere linee sinuose per adattarsi ai confini degli Stati nei quali sono adottate le ore corrispondenti. Ai tempi locali si contrappone il tempo universale (TU), considerato come tempo locale del meridiano fondamentale, passante per l’osservatorio di Greenwich.

{{< figure src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e8/Standard_World_Time_Zones.png/800px-Standard_World_Time_Zones.png" title="I fusi orari, aggiornati al 2017" >}}

---

### I calendari

Rappresentano il sistema per raggruppare organicamente lunghi intervalli di tempo determinati attraverso l’osservazione dei fenomeni astronomici. Considerano generalmente l’anno come intervallo di base. A questa periodicità è stata poi sovrapposta la settimana, inizialmente solo con significato religioso, poi con valore civile. Nei diversi calendari sviluppati nel corso della storia dell’umanità si è fatto, e si fa tuttora, ricorso a fenomeni legati al Sole, o alla Luna, o a entrambi gli astri, prendendo come base le suddette periodicità. Si hanno quindi **calendari solari** (come quello gregoriano), che fanno riferimento al moto apparente del Sole attraverso le costellazioni; **calendari lunari** fanno riferimento al ripetersi delle fasi lunari e **calendari lunisolari**, che cercano di accordarsi il meglio possibile a entrambe le periodicità. La precisione dei diversi calendari è rappresentata dalla precisione con cui si trovano multipli dei periodi dei fenomeni astronomici interessati. In pratica, tale precisione aumenta aggiungendo periodicamente all’anno o al mese un giorno supplementare. Le regole con cui tale aggiunta viene effettuata sono tanto più complesse quanto maggiore è la precisione che si vuole conseguire.

#### Calendario gregoriano

È il calendario attualmente in uso nella maggior parte dei paesi industrializzati. Pur essendo un calendario solare, nella divisione in mesi e in altri particolari mantiene tracce di precedenti calendari lunari. Esso trae le sue origini dirette dal primitivo calendario di Roma, modificato con una riforma di Giulio Cesare del 46 a.C. Il calendario riformato, detto calendario giuliano, era di 12 mesi e di 365 giorni per tre anni consecutivi; ogni quattro anni era di 366 giorni. Il giorno supplementare andava aggiunto dopo il 25 febbraio, che era il sesto giorno prima delle calende di marzo(l’inizio del mese). Il giorno aggiunto era dunque il **bis-sextus**, cioè ripetizione del sesto, da cui il nome di **anno bisestile** per gli anni di 366 giorni. Nel II secolo venne usata anche la settimana, di origine ebraica, sovrapposta al ciclo annuale e mensile. L’aggiungere un giorno ogni quattro anni presupponeva che l’anno tropico (intervallo tra due successivi passaggi del Sole al primo punto di Ariete) fosse di 365,25 giorni solari, cioè un po’ maggiore di quanto in realtà non sia (365,242). Il sommarsi delle frazioni eccedenti portò a un errore già avvertibile nel 730. Per tener conto della differenza, papa Gregorio XIII promulgò nel 1582 la riforma del calendario, che portò al calendario tuttora adottato. Si fece seguire a giovedì 4 ottobre 1582 il venerdì 15 ottobre e si stabilì che fossero bisestili gli anni divisibili per quattro e che degli anni terminanti con due zeri fossero bisestili solo quelli divisibili per 400.

{{< figure src="https://upload.wikimedia.org/wikipedia/commons/1/17/Inter-grav.jpg" title="Prima pagina della bolla papale \"Inter gravissimas\" " >}}

---
