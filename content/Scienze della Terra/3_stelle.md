---
title: "3. Le stelle"
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
<!-- script JSXGraph -->
<script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/jsxgraph/0.99.7/jsxgraphcore.js">
</script>

A causa delle enormi distanze che le separano dalla Terra, le **stelle** appaiono all’osservatore in posizioni reciproche praticamente immutabili. Nel corso dei secoli, l’uomo con la sua immaginazione ha riconosciuto in particolari allineamenti o raggruppamenti stellari il profilo o la struttura di oggetti, animali e personaggi mitologici e ha dato loro il nome di **costellazioni**. Lo sviluppo di tecniche astronomiche ha permesso di **classificare le stelle** e di **comprenderne la struttura**: sono sfere di gas incandescente, tenute insieme dalla forza di gravità; risplendono di luce propria, prodotta in seguito a **reazioni di fusione termonucleare**. Le stelle sono in continua evoluzione: **gli stadi della vita delle stelle** sono rappresentati nel **diagramma di Hertzsprung-Russell**, in cui compaiono i parametri temperatura e magnitudine (o luminosità).

{{< figure src="https://upload.wikimedia.org/wikipedia/commons/8/89/Sagittarius_Star_Cloud.jpg" title="A parte il Sole, le stelle sono così lontane da essere visibili solo come punti di luce, nonostante il loro diametro sia di milioni di chilometri. Nell'immagine, scattata dal telescopio spaziale Hubble, la Nube stellare del Sagittario (M24), un ammasso aperto nell'omonima costellazione" >}}

## La struttura stellare

I parametri fondamentali per caratterizzare una stella sono la magnitudine, la temperatura superficiale, il colore, il raggio e la massa.

### La magnitudine stellare

Osservando il cielo a occhio nudo, ci si rende conto che non tutte le stelle appaiono luminose allo stesso modo; ciò permette di classificarle in base alla cosiddetta **magnitudine apparente**.

La scala delle magnitudini stellari fu introdotta dal matematico e astronomo greco Ipparco (150 a.C.), il quale classificò le stelle in 6 categorie, o classi di magnitudine (apparente), ponendo le stelle più luminose nella 1 a classe (1 a magnitudine) e quelle appena visibili a occhio nudo nella 6 a classe.

Oggi la magnitudine apparente, m, di un astro viene misurata con una formula che si accorda con la vecchia classificazione di Ipparco:

<div align="center">
$m_2 – m_1 = – 2,5 \log F_2/F_1$
</div>

dove compaiono la differenza fra le magnitudini $m_1$ e $m_2$ di due stelle e il logaritmo del rapporto dei due rispettivi flussi luminosi, $F_1$ e $F_2$, che riceviamo.

Quella delle magnitudini apparenti è una scala relativa, che non fa riferimento a unità assolute di energia luminosa: è perciò necessario scegliere come riferimento una stella campione (per convenzione è stata scelta la Stella Polare, alla quale è assegnata magnitudine apparente uguale a 2).

Grazie all’ausilio di nuovi strumenti astronomici, le classi si sono moltiplicate e per gli oggetti celesti più luminosi, rispetto alla prima classificazione, vengono oggi assegnate magnitudini negative.

Poiché la luminosità di una stella diminuisce proporzionalmente al quadrato della distanza, per poter confrontare tra loro le luminosità effettive di due stelle dovremmo poterle osservare tutte alla medesima distanza. Si definisce **magnitudine assoluta** la magnitudine apparente di una stella se fosse posta alla distanza standard di 32,6 anni luce (10 parsec).

La magnitudine apparente viene misurata attraverso un dispositivo detto fotometro, o tramite l’annerimento di una la strafotografica esposta per un dato tempo. Misurata la magnitudine apparente, conoscendo la distanza della stella si può, con una semplice formula, risalire alla magnitudine assoluta, oppure, conoscendo la magnitudine assoluta, si può calcolare la distanza.

### Il colore e la temperatura

Le stelle mostrano colori diversi l’una dall’altra; nella costellazione di Orione, per esempio, Betelgèuse è rossa, mentre Rigel è bianco-azzurra. Questo fenomeno è spiegato dalla **legge di Wien**, secondo la quale la lunghezza d’onda, cioè il colore, della luce emessa da un corpo dipende dalla temperatura del corpo stesso. All’aumentare della temperatura di un corpo, diminuisce la lunghezza d’onda delle radiazioni luminose che esso emette in prevalenza e si passa perciò dal rosso al blu. Una stella che emette luce rossa (lunghezza d’onda maggiore) è più fredda rispetto a una stella che emette luce blu.  Tutti questi dati ci sono forniti dalla **spettroscopia stellare**. Attraverso l’analisi degli spettri di  225.000 stelle si è giunti a formulare una classificazione secondo dieci **tipi**, o **classi spettrali** (che inizialmente erano sette), ordinati in funzione della temperatura superficiale decrescente e distinti con lettere dell’alfabeto: O, B, A, F, G, K, M. Le varie classi sono suddivise in sottoclassi, indicate da numeri (2, 8, 0); per esempio, il Sole è una stella di classe spettrale G2.  I corpi con temperature inferiori ai 3500 °C emettono radiazioni nella banda del rosso (M); verso i 6000 °C la radiazione è giallastra (F, G), mentre stelle con temperature superiori ai 25.000 °C producono una luce bianco-azzurra (O).

{{< figure src="https://upload.wikimedia.org/wikipedia/commons/8/8b/Morgan-Keenan_spectral_classification.png" title="Schema della classificazione spettrale Morgan-Keenan-Kellman" >}}

<div style="overflow-x:auto;">
<table>
 <caption>Tabella sulle classi spettrali stellari.</caption>
  <tr>
    <th>Classe</th>
    <th>Temperatura (K)</th>
    <th>Colore</th>
    <th>Massa (M☉)</th>
    <th>Raggio (R☉)</th>
    <th>Luminosità (L☉)</th>
    <th>Linee di assorbimento</th>
    <th>Esempio</th>
  </tr>
  <tr>
    <td>O</td>
    <td>28 000 - 50 000</td>
    <td>Blu-azzurro</td>
    <td>16 - 150</td>
    <td>15</td>
    <td>fino a 1.400.000</td>
    <td>N, C, He e O</td>
    <td>10 Lacertae</td>
  </tr>
  <tr>
    <td>B</td>
    <td>9 600 - 28 000</td>
    <td>Bianco-azzurro</td>
    <td>3,1 - 16</td>
    <td>7</td>
    <td>20.000</td>
    <td>He, H</td>
    <td>Regolo</td>
  </tr>
  <tr>
    <td>A</td>
    <td>7 100 - 9 600</td>
    <td>Bianco</td>
    <td>1,7 - 3,1</td>
    <td>2,1</td>
    <td>80</td>
    <td>H</td>
    <td>Altair</td>
  </tr>
  <tr>
    <td>F</td>
    <td>5 700 - 7 100</td>
    <td>Bianco-giallastro</td>
    <td>1,2 - 1,7</td>
    <td>1,3</td>
    <td>6</td>
    <td>Metalli: Fe, Ti, Ca, Sr e Mg</td>
    <td>Procione</td>
  </tr>
  <tr>
    <td>G</td>
    <td>4 600 - 5 700</td>
    <td>Giallo</td>
    <td>0,9 - 1,2</td>
    <td>1,1</td>
    <td>1,2</td>
    <td>Ca, He, H e altri</td>
    <td>Sole</td>
  </tr>
  <tr>
    <td>K</td>
    <td>3 200 - 4 600</td>
    <td>Arancione</td>
    <td>0,4 - 0,8</td>
    <td>0,9</td>
    <td>0,4</td>
    <td>Metalli  TiO<sub>2</sub></td>
    <td>α Centauri B</td>
  </tr>
  <tr>
    <td>M</td>
    <td>1 700 - 3 200</td>
    <td>Rosso</td>
    <td>0,08 - 0,4</td>
    <td>0,4</td>
    <td>0,04</td>
    <td>Come sopra</td>
    <td>Stella di Barnard</td>
  </tr>
</table>
</div>

{{< figure src="https://upload.wikimedia.org/wikipedia/commons/b/b1/Hubble_heic0206j.jpg" title="Parte della Cintura di Gould e delle stelle di una vicina regione di formazione stellare formano il gruppo di astri conosciuti in tutto il mondo col nome di costellazione di Orione" >}}

### La massa e il raggio

**Le masse stellari non possono essere misurate direttamente**, ma possono essere calcolate misurando gli effetti gravitazionali che una stella produce su un’altra, con la quale costituisca un **sistema binario**, formato cioè da due stelle che ruotano intorno al comune baricentro per effetto di una mutua attrazione gravitazionale (analogamente al sistema Terra-Luna). Per riuscire a stimare la massa anche per altre stelle, si ricorre alla relazione statistica tra massa e luminosità dedotta dal fisico e astronomo inglese A. Eddington (1924).  **Il raggio di una stella è una grandezza molto difficile misurare**. Solo per il Sole l’osservazione fornisce direttamente il diametro angolare (32'); tutte le altre stelle appaiono come punti luminosi (infatti, le loro dimensioni sono inferiori alla risoluzione angolare dei telescopi da Terra).

{{< figure src="https://upload.wikimedia.org/wikipedia/commons/a/a7/Nebulosa_de_Eta_Carinae_o_NGC_3372.jpg" title="Eta Carinae (circondata dalla Nebulosa Omuncolo) possiede una massa circa 150 volte quella del Sole" >}}

### La spettroscopia stellare

Attraverso le loro radiazioni, le stelle ci inviano messaggi. La **spettroscopia** si occupa delle proprietà della luce che dipendono dalla sua lunghezza d’onda. Una radiazione luminosa viene analizzata mediante uno strumento detto spettroscopio, che la scompone nelle sue lunghezze d’onda componenti, corrispondenti ai vari colori; si ottiene così uno spettro il quale ci permette di descrivere la distribuzione energetica tra le varie lunghezze d’onda presenti, da quelle più lunghe (bassa energia) a quelle più corte (alta energia).  I primi studi sistematici sullo spettro solare furono compiuti agli inizi del 1800 dal fisico tedesco J. Fraunhofer (1787-1826).  Nel 1859 G. Kirchhoff (1824-87) formulò le **tre leggi della spettroscopia**:

* un solido, un liquido o un gas molto denso, portati all’incandescenza, presentano uno spettro di emissione continuo, cioè emettono radiazioni a tutte le lunghezze d’onda (prima legge);
* un gas rarefatto incandescente possiede uno spettro di emissione a righe, ossia emette radiazioni soltanto a certe lunghezze d’onda, caratteristiche degli elementi o dei composti chimici presenti nel gas (seconda legge);
* un gas rarefatto, posto di fronte a una sorgente di radiazione continua avente temperatura più elevata, dà origine a uno spettro di assorbimento a righe, alle stesse lunghezze d’onda che esso mostra nello spettro di emissione (terza legge). Dalle proprietà spettrali di una sorgente luminosa si possono ottenere informazioni sulla sua composizione chimica.

{{< figure src="https://upload.wikimedia.org/wikipedia/commons/thumb/8/88/Spectroscopy_overview_it.svg/2000px-Spectroscopy_overview_it.svg.png" title="Schema di un'analisi mediante spettroscopio" >}}

## La distanza delle stelle

Le principali unità di misura per le distanze in astronomia sono l’unità astronomica, l’anno luce e il parsec.  L’**unità astronomica** (**UA**) corrisponde alla distanza media fra la Terra e il Sole ed equivale a 149 600 000 km circa (è usata per fornire le distanze di oggetti all’interno del sistema solare).  L’**anno luce** (**al**) equivale alla distanza percorsa nell’arco di un anno dalla luce, che nel vuoto si muove a una velocità pari a 299 792 458 m/sec.  Il **parsec** (**parallasse**-secondo, simbolo **pc**) è la distanza di un punto dal quale si vedrebbe sotto l’angolo di 1" (secondo) d’arco il semiasse maggiore dell’orbita terrestre (cioè la distanza massima Terra-Sole). Il parsec corrisponde a 3,26 anni luce.

<div style="overflow-x:auto;" class="TableData">
<table>
 <caption>Principali unità di misura in astronomia.</caption>
  <tr>
    <th>Unità di misura</th>
    <th>km</th>
    <th>UA</th>
    <th>al</th>
    <th>pc</th>
  </tr>
  <tr>
    <td>unità astronomica</td>
    <td>49 600 600</td>
    <td>1</td>
    <td>15,8 x 10<sup>6</sup></td>
    <td>4,8 x 10<sup>6</sup></td>
  </tr>
  <tr>
    <td>anno luce (al)</td>
    <td>9.463 x 10<sup>9</sup></td>
    <td>63 x 10<sup>3</sup></td>
    <td>1</td>
    <td>0,31</td>
  </tr>
  <tr>
    <td>parsec (pc)</td>
    <td>30 900 x 10<sup>9</sup></td>
    <td>206 265</td>
    <td>3,26</td>
    <td>1</td>
  </tr>
</table>
</div>

<div style="overflow-x:auto;" class="TableData">
<table>
 <caption>Stelle più vicine al Sistema solare</caption>
  <tr>
    <th>Stella</th>
    <th>Costellazione</th>
    <th>Distanza (anni luce)</th>
  </tr>
  <tr>
    <td>α Centauri o Proxima Centauri</td>
    <td>Centauro</td>
    <td>4,3</td>
  </tr>
  <tr>
    <td>Stella di Barnard</td>
    <td>Ofiuco</td>
    <td>6</td>
  </tr>
  <tr>
    <td>Wolf 359</td>
    <td>Leone</td>
    <td>7</td>
  </tr>
  <tr>
    <td>BD  36° 2 147</td>
    <td>Orsa Maggiore</td>
    <td>8,2</td>
  </tr>
  <tr>
    <td>Luyten 726-8</td>
    <td>Balena</td>
    <td>8,4</td>
  </tr>
  <tr>
    <td>Sirio</td>
    <td>Cane Maggiore</td>
    <td>8,6</td>
  </tr>
  <tr>
    <td>Ross 154</td>
    <td>Sagittario</td>
    <td>9,4</td>
  </tr>
  <tr>
    <td>Ross 248</td>
    <td>Andromeda</td>
    <td>10,4</td>
  </tr>
  <tr>
    <td>ε Eridani</td>
    <td>Eridano</td>
    <td>10,8</td>
  </tr>
</table>
</div>

## Il moto delle stelle

Le stelle a occhio nudo sembrano mantenere inalterata nel tempo la loro posizione, tanto che si introdusse il termine di **stelle fisse**. In realtà, l’osservazione con il telescopio mostra che, durante il corso di una notte, le costellazioni seguono un moto che le fa sorgere a est e tramontare a ovest, descrivendo un grande arco che culmina a sud. Il moto degli astri, dovuto alla rotazione terrestre, è un moto solo apparente: la Terra, ruotando, offre all’osservatore panorami variabili dell’universo.  La **Stella Polare**, trovandosi a circa 1 grado dalla direzione dell’asse di rotazione terrestre, appare quindi ferma tutta la notte, mentre tutte le altre stelle appaiono invece in rotazione intorno a essa.  In realtà, la Terra ha anche un moto di rivoluzione intorno al Sole, con durata di un anno, e quindi velocità di circa 1 grado al giorno. A causa del moto di rivoluzione terrestre, notte dopo notte le **costellazioni appaiono sorgere, culminare e tramontare circa 1 grado più a ovest e circa 4 minuti in anticipo rispetto alla notte precedente**. Questo significa che, mese dopo mese, nel mezzo della notte saranno osservabili costellazioni sempre diverse.

{{< figure src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/b9/Stars_Circle_over_the_Residencia_at_Cerro_Paranal.jpg/1280px-Stars_Circle_over_the_Residencia_at_Cerro_Paranal.jpg" title="Aumentando il tempo di esposizione si nota il moto apparente delle stelle, dovuto alla rotazione della Terra sul proprio asse e quello di rivoluzione attorno al Sole" >}}

## L’evoluzione stellare

Nel corso del tempo, la struttura di una stella subisce modificazioni, passando attraverso una serie di fasi, caratterizzate da luminosità e temperatura differenti, che rappresentano il ciclo di vita stellare.

### Il diagramma di Hertzsprung-Russell

Le principali tappe della vita delle stelle sono state ricostruite, indipendentemente, dall’astronomo danese E. Hertzsprung e dall’astronomo americano N.H. Russell in un diagramma statistico “a nube di punti” (diagramma di Hertzsprung-Russell, o H-R) che mostra l’esistenza di una dipendenza tra luminosità stellare e temperatura superficiale. La maggior parte dei punti, corrispondenti alle varie stelle, si distribuisce su una banda diagonale o sequenza principale che unisce la zona a basse temperature (rosse) e basse luminosità alla zona ad alte temperature (blu) e alte luminosità (se le due grandezze, luminosità e temperatura, fossero indipendenti, i punti corrispondenti alle diverse stelle dovrebbero distribuirsi a caso su tutto il diagramma). Per ogni stella si può così determinare la posizione utilizzando due coordinate: temperatura e luminosità. Sull’asse verticale del diagramma sono riportate le luminosità (o le magnitudini assolute) delle stelle dell’insieme: in alto si ritrovano i valori più elevati. Sull’asse orizzontale sono riportate le temperature: le più alte sono verso sinistra (al posto delle temperature si possono indicare le classi spettrali delle stelle).  Un grandissimo numero di stelle, appartenenti alla **sequenza principale**, si raccoglie lungo una fascia che attraversa trasversalmente il grafico. Sono stelle stabili, che si trovano nella fase media della propria vita; quanto più una di queste stelle è luminosa, tanto più è calda (e azzurra). Il Sole appartiene a questa sequenza e vi compare in posizione intermedia, come stella gialla.  Al di fuori della sequenza principale, nella parte in alto a destra del diagramma, compare la zona delle stelle **giganti rosse** (e quella delle **supergiganti**). La posizione corrisponde a temperature fredde e medie magnitudini; le stelle appartenenti a questo gruppo devono necessariamente essere enormi, dato che la potenza irradiata è proporzionale alla quarta potenza della temperatura (legge di Stefan-Boltzmann): l’alta luminosità è quindi associata all’estensione, cioè al diametro della stella stessa.  In basso a sinistra si trova il gruppo delle **nane bianche**. Si tratta di stelle calde e poco luminose, che quindi devono essere piccole (con raggi simili a quello della Terra).  L’appartenenza a un gruppo del diagramma H-R significa semplicemente che la stella si trova in una particolare fase della sua evoluzione.

{{< figure src="https://upload.wikimedia.org/wikipedia/commons/1/17/Hertzsprung-Russel_StarData.png" title="Diagramma H-R e posizione del Sole" >}}

### La vita delle stelle

Il processo di formazione delle stelle avviene all’interno di grandi nubi di gas (in prevalenza idrogeno) e polveri interstellari (nebulose) e ha inizio quando **una porzione di gas raggiunge una densità sufficiente a provocare un collasso gravitazionale del gas**. La compressione provoca il riscaldamento del gas, che verso il centro raggiunge una temperatura di alcuni milioni di gradi, innescando le prime reazioni di fusione nucleare dell’idrogeno (perché ciò accada, la massa della stella deve essere superiore a 0,08 volte la massa solare). Il processo di fusione termonucleare produce elio e un’enorme quantità di energia, che contrasta il collasso gravitazionale fino a bloccarlo completamente: la stella raggiunge così una configurazione stabile, che mantiene per buona parte della sua vita. Questa fase corrisponde alla permanenza della stella nella sequenza principale nel diagramma di Hertzsprung-Russell.  La posizione e la permanenza di una stella nella sequenza principale dipendono dalla massa della nebulosa da cui si è originata: stelle nate con una grande massa diventano più calde (blu) e consumano il loro idrogeno nel giro di milioni di anni; stelle con massa piccola rimangono meno calde (rosse) e sono più longeve, miliardi di anni. Le stelle gialle rimangono nella sequenza circa 10 miliardi di anni: il Sole, che ha già 5 miliardi di anni, è una stella di “mezza età”.  Quando quasi tutto l’idrogeno nel nucleo di una stella si è consumato e al suo posto è subentrato elio, le reazioni di fusione nucleare si interrompono. Gli strati esterni della stella, non più “sostenuti”, collassano e tale processo provoca un aumento della temperatura, sufficiente a innescare nuove reazioni di fusione termonucleari. L’energia prodotta fa espandere l’involucro esterno di gas, che si raffredda tanto da cambiare colore e divenire rosso: si forma così una gigante rossa. Quel che avviene in seguito dipende dalla massa della stella.  Se la massa è simile a quella del Sole, la **gigante rossa** può perdere gli strati esterni al nucleo, che formano una nube in espansione (nebulosa planetaria); il nucleo resta “nudo”, caldissimo, ma in assenza di reazioni nucleari, e si raffredda lentamente: appare sotto forma di **nana bianca**, destinata a trasformarsi in un corpo oscuro di materia inerte (nana nera).  Se la massa è un po’ maggiore di quella del Sole, nella stella, durante la contrazione, si libera una quantità di energia tale da provocare delle vere esplosioni stellari, con espulsioni di nubi di materia verso lo spazio circostante. È questo lo stadio di **nova**.  Il collasso gravitazionale, quando la stella ha massa maggiore di almeno tre volte quella del Sole, è di così vaste proporzioni da provocare un’immane esplosione, a seguito della quale gran parte della stella si disintegra e viene lanciata nello spazio: è lo stadio di **supernova**. Si forma una nube di gas in rapida espansione, mentre il nucleo collassa rapidamente fino a formare una **stella di neutroni**, estremamente densa e compatta, che può emettere impulsi radio molto frequenti e precisi, presentandosi come **pulsar**.  Se la massa della stella è nettamente superiore a tre masse solari, il collasso gravitazionale prosegue indefinitamente.  La densità continua ad aumentare e si forma un corpo sempre più piccolo, circondato da un campo gravitazionale immenso: si forma in tal modo un **buco nero**.

{{< figure src="https://upload.wikimedia.org/wikipedia/commons/7/7c/Stellar_evolutionary_tracks-it.svg" title="Il percorso evolutivo di diverse stelle lungo il diagramma H-R" >}}

### Reazioni di fusione termonucleare

Le reazioni nucleari nelle stelle sono dette termonucleari e assicurano il rifornimento energetico. Esse comportano la trasformazione di idrogeno, H, che costituisce mediamente circa il 70% della massa stellare, in elio, He, che assomma in media al 28%. Quanto al processo di trasformazione, è sufficiente ricordare che per giungere alla formazione di un nucleo attraverso la fusione nucleare, le particelle devono essere dotate di elevatissima energia cinetica, al fine di superare la barriera repulsiva di potenziale coulombiano: le particelle devono, cioè, avvicinarsi fra loro a distanze inferiori al “raggio d’azione” (r) delle forze nucleari (r ≈ 10 -13 cm).  Nel 1938 il fisico tedesco H. Bethe formulò la teoria del bruciamento dell’idrogeno secondo due distinte catene di reazioni, dipendenti dalla temperatura: catena protone-protone e ciclo CNO (carbonio-azoto ossigeno). Entrambe le catene formano, a partire da quattro protoni (nuclei di idrogeno, 1H), un nucleo di elio-4, 4He, con liberazione di energia radiante e di energia cinetica dei prodotti della reazione.

{{< figure src="https://c1.staticflickr.com/8/7273/6892984686_7484afefb3_b.jpg" title="Schema degli \"strati a cipolla\" di una stella massiccia nelle ultime fasi di vita. (Non in scala)" >}}

## Tipi di stelle

Gli stadi che una stella attraversa nella sua vita corrispondono anche ai diversi tipi di stelle che si possono osservare in cielo tramite gli strumenti astronomici.

{{< figure src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/eb/The_life_of_Sun-like_stars.jpg/1024px-The_life_of_Sun-like_stars.jpg" title="Ciclo vitale di una stella della massa del Sole dalla sua formazione (a sinistra) alla sua evoluzione in gigante rossa dopo miliardi di anni (a destra)" >}}

### Giganti rosse

Si tratta di stelle in cui, conseguentemente alla combustione dell’idrogeno in elio, si è formato un **nucleo molto denso**, **il quale collassando provoca un riscaldamento in grado di innescare successive reazioni termonucleari** (che, a partire da nuclei di elio-4, <sup>4</sup>He, danno origine a nuclei di carbonio-12, <sup>12</sup>C). A causa dell’alta temperatura, la stella si espande enormemente, originando una **gigante rossa**. Tale espansione abbassa la temperatura negli strati superficiali, facendo assumere alla stella il caratteristico colore rosso. In una gigante rossa la combustione dell’elio dura per un tempo pari a 1/5 di quello necessario per bruciare l’idrogeno quando la stella si trovava nella sequenza principale. Il meccanismo delle reazioni nucleari si ripete, ma non indefinitamente: quando l’elio si esaurisce, entrano in gioco altri combustibili nucleari (ferro-56, <sup>56</sup>Fe), che si esauriranno anch’essi, con conseguenti contrazioni e aumenti di temperatura e, quando tutti gli elementi si saranno esauriti, nessuna pressione dall’interno potrà opporsi alla compressione della forza gravitazionale.

{{< figure src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/5c/Aldebaran-Sun_comparison-it.svg/772px-Aldebaran-Sun_comparison-it.svg.png" title="La stella gigante Aldebaran" >}}

### Nane bianche

Nelle stelle **con massa inferiore a 1,44 masse solari** la pressione e temperatura del nucleo non arrivano a innescare la combustione del carbonio e dell’ossigeno: la stella residua inizia a raffreddarsi, formando una **nana bianca**. **Inizia la contrazione gravitazionale**, che si arresta solo quando è bilanciata dalla pressione del gas nel nucleo (la densità è di alcune tonnellate per centimetro cubo). **A causa della bassa luminosità, le nane bianche sono difficilmente osservabili**; con il passare del tempo, la stella si raffredderà sempre più, diventando una scura e fredda sfera di carbonio e ossigeno solidi, più o meno delle dimensioni della Terra (**nana nera**).

{{< figure src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/0e/Sirius_A-Sun_comparison.png/1024px-Sirius_A-Sun_comparison.png" title="Raffronto tra le dimensioni della nana bianca Sirio B e del Sole" >}}

### Nove

**Le stelle con nuclei di massa superiore a 1,44 masse solari** attraversano fasi di contrazione e di fusione nucleare, producendo nel loro nucleo elementi sempre più pesanti.  Le **nove sono stelle di tipo esplosivo, componenti di sistemi binari di stelle**, costituiti di norma da una gigante rossa e da una nana bianca. La nana bianca attira gravitazionalmente l’idrogeno dalla gigante rossa e in tal modo si accresce, causando l’aumento della pressione e della temperatura nello strato superficiale. Raggiunta la temperatura di innesco della fusione nucleare, la nova esplode, con un improvviso aumento della luminosità stellare che dura per qualche giorno, per poi tornare, con il passare del tempo, alle condizioni iniziali.

{{< figure src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/11/GKPersei-MiniSuperNova-20150316.jpg/1280px-GKPersei-MiniSuperNova-20150316.jpg" title="GK Persei ripresa da Chandra, il telescopio orbitale della NASA per l'osservazione del cielo nei raggi X" >}}

### Supernove

Quando **la massa di una stella è di almeno una decina di volte maggiore di quella del Sole**, si giunge alla formazione di un nucleo di ferro-56, 56 Fe, non più in grado di liberare ulteriore energia: come conseguenza, **la stella collassa e la temperatura si innalza fino ad alcuni miliardi di gradi** in brevissimo tempo; quando i gusci più esterni in contrazione si imbattono nel nucleo solido, generano un’onda d’urto, che si propaga verso l’esterno della stella; giunta sulla superficie della stella, l’onda trascina una grande quantità di gas nello spazio esterno alla stella: si realizza così un’immane “**esplosione di supernova**” e la luminosità della stella cresce enormemente, raggiungendo in poche ore valori fino a circa un miliardo di volte superiori rispetto a quella del Sole. La **supernova** arricchisce lo spazio interstellare circostante di molti elementi pesanti, ciò che resta del suo nucleo è una stella di neutroni o, alternativamente, quando si parte con differenti condizioni iniziali, un buco nero.

{{< figure src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/00/Crab_Nebula.jpg/1024px-Crab_Nebula.jpg" title="La Nebulosa Granchio è la nebulosa associata alla supernova SN 1054" >}}

### Stelle di neutroni e pulsar

Dopo l’esplosione di una supernova, il materiale che rimane collassa per gravità: si forma un **nucleo estremamente denso di neutroni**, che viene detto stella di neutroni, sede di intensi campi magnetici.  Nel 1967 sono state scoperte altre sorgenti simili, chiamate **pulsar**, cioè **sorgenti di onde radio pulsanti**. Il periodo di rotazione di una pulsar è destinato ad aumentare nel tempo.  Alcune pulsar fanno parte di sistemi doppi, cioè sono legate gravitazionalmente a un’altra stella. In questa situazione, durante la rotazione la stella di neutroni attira su di sé materia dalla sua compagna, con la conseguenza di modificare la sua velocità di rotazione.

{{< figure src="https://c1.staticflickr.com/9/8072/8358597173_6722c2e2fd_b.jpg" title="Ciclo dei raggi X della pulsar delle Vele" >}}

### Buchi neri

Un **buco nero è un oggetto celeste**, con diametro variabile da 10 a 30 km, **la cui materia è eccezionalmente addensata ed esercita un’attrazione gravitazionale così intensa da impedire alla materia stessa, alla luce e a qualunque altra radiazione elettromagnetica di sfuggirne**. È presumibilmente lo stadio finale dell’evoluzione di una stella di grande massa (almeno tre volte quella del Sole): in questo caso, quando la stella esplode come supernova, la sua parte centrale subisce un violento collasso gravitazionale, che comprime la materia indefinitamente generando il buco nero, che successivamente può catturare altra materia e aumentare così la propria massa fino a valori di milioni di volte quella del Sole; prima di “cadere” nel buco nero, la materia gli ruota attorno muovendo a spirale e formando un disco di accrescimento. In questa zona dello spazio si instaura un campo gravitazionale intensissimo.

{{< figure src="https://upload.wikimedia.org/wikipedia/commons/c/cd/Black_Hole_Milkyway.jpg" title="Effetto lente gravitazionale causato dal passaggio di una galassia dietro a un buco nero in primo piano" >}}

## Le costellazioni

In base a una convenzione sottoscritta nel 1928 dall’Unione Astronomica Internazionale, tutto il cielo è stato suddiviso in 88 **costellazioni**: 18 boreali, 36 australi e 34 equatoriali.  Le costellazioni conservano il nome attribuito dalla tradizione occidentale, che nella disposizione delle stelle vedeva l’immagine di animali, personaggi mitologici e oggetti (Orsa Maggiore, Orione, Leone ecc.). Tra le più antiche sono le costellazioni dello zodiaco, immaginate dai Caldei e dai Babilonesi, che ne hanno riconosciute 12 lungo l’eclittica, cioè in corrispondenza del cammino apparente del Sole sulla volta celeste: Aries, Taurus, Gemini, Cancer, Leo, Virgo, Libra, Scorpius, Sagittarius, Capricornus, Aquarius, Pisces; da queste è poi derivata la suddivisione dell’anno solare in 12 mesi.  Le 48 costellazioni introdotte da Tolomeo comprendono i principali raggruppamenti visibili dalla latitudine di Alessandria d’Egitto. Tra queste, alcune sono estremamente deboli e mal definite, il che fa pensare che abbiano perduto luminosità nel tempo. La **forma delle costellazioni**, anche considerando tempi lunghissimi, **non si modifica**. Le stelle, infatti, pur essendo dotate di moto proprio, si spostano molto lentamente nel cielo. **Il loro moto complessivo apparente è dovuto ai moti diurno e annuo della Terra** e avviene mantenendo inalterata la loro posizione relativa. Le costellazioni di Tolomeo non coprono però tutto il cielo, sia perché tra esse esistevano vuoti che sarebbero stati riempiti solo successivamente, sia perché Tolomeo e i Greci non avevano mai osservato stelle del cielo australe. A quelle descritte da Tolomeo si sono quindi aggiunte numerose altre costellazioni, spesso con nomi presi da strumenti scientifici appena scoperti, (come, per esempio, **Telescopium, Microscopium**).  Le costellazioni non hanno una realtà fisica, in quanto le stelle che le costituiscono sono estremamente lontane tra loro e appaiono vicine solo per effetto della prospettiva, ma costituiscono uno strumento utilissimo per identificare una qualsiasi zona del cielo. Secondo convenzioni internazionali consolidate, le stelle più luminose di ogni costellazione sono indicate con il nome di una lettera dell’alfabeto greco in ordine decrescente di luminosità (alfa, beta ecc.), seguita dall’abbreviazione del genitivo del nome latino della costellazione di appartenenza.

{{< figure src="https://upload.wikimedia.org/wikipedia/commons/8/84/Milkwy_way_chart_hemispheres.png" title="Mappa stellare dell'emisfero boreale e australe" >}}
