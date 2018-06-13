---
title: "Geometria dello spazio"
draft: false
weight: 12
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

## La geometria euclidea nello spazio

### Rette e piani

* Due rette nello spazio sono **complanari** se appartengono allo stesso piano, sono **sghembe** se appartengono a piani diversi; sono **parallele** se sono complanari e non si intersecano oppure coincidono.
* Due piani sono **paralleli** se non hanno punti in comune o se sono coincidenti, sono **incidenti** se hanno in comune una sola retta
* Relativamente a un piano uno retta può essere:
    * **appartenente** al piano se tutti i suoi punti appartengono al piano
    * **parallela** al piano se non lo interseca
    * **incidente** se lo interseca in un solo punto $P$; in particolare è **perpendicolare** al piano se è perpendicolare a tutte le rette del piano che passano per $P$

Si verifica poi che se una retta è perpendicolare a due rette del piano passanti per $P$, è perpendicolare anche a tutte le altre e quindi al piano.

* Per la relazione di perpendicolarità tra una retta e un piano vale il **teorema delle tre perpendicolari**: sia $r$ una retta perpendicolare a un piano $\alpha$ in un punto $P$; sia $t$ una retta qualunque di $\alpha$ e sia $s$ la retta perpendicolare condotta da $P$ su $t$. Allora $t$ è perpendicolare al piano $\beta$ definito da $r$ e da $s$.

### Diedri e angoloidi

Relativamente ai diedri e agli angoloidi si può dire che:

* due semipiani che hanno origine in comune dividono lo spazio in due **angoli diedri** dei quali uno è concavo e l'altro è convesso
* ogni piano che interseca un diedro definisce un angolo che rappresenta la sezione di diedro; se il piano è perpendicolare allo spigolo del diedro si parla di **sezione normale**; la misura di un diedro è la misura della sua sezione normale
* due piani sono perpendicolari se sono incidenti e formano diedri retti
* le smirette che, uscnedo da un punto $P$, intersecano i lati di un poligono appartenente ad un piano che non contiene $P$ definiscono una superficie piramidale, la parte di spazio delimitata da una superficie piramidale si chiama $angoloide$
* un angoloide che ha tre facce si chiama **triedro** ed ha la caratteristica che ciascuna faccia è minore della somma delle altre due e maggiore della loro differenza

§IMMAGINE§

### Poliedri

**Poliedro** è la figura solida delimitata da un numero finito di poligoni (almeno quattro) appartenenti a piani diversi, in modo che abbiano un lato in comune e nessuno di essi tagli il solido.

Un poliedro si dice regolare se le sue facce sono poligoni regolari e se tutti i suoi diedri sono congruenti. I **poliedri regolari** sono cinque:

* il *triedro*, l'*ottaedro* e l'*icosaedro* che hanno per facce triangoli equilateri
* *cubo* che ha per facce dei quadrati
* *dodecaedro* che ha per facce pentagoni regolari

§IMMAGINE§

Altri poliedri sono:

* il **prisma**, che ha come basi due poligoni paralleli e congruenti e come facce laterali dei parallelogrammi. In particolare:
    * un prisma che ha per basi due parallelogrammi si chiama *parallelepipedo*
    * un prisma le cui facce sono perpendicolari ai piani di base è un *prisma retto*
* la **piramide**, che ha come base un poligono e come facce laterali dei triangoli che convergono in un vertice $V$. In particolare, la piramide si dice:
    * *retta* se la sua base si può circoscrivere ad una circonferenza il cui centro è la proiezione del vertice $V$ sul piano di base
    * *regolare* se è retta e se il poligono di base è un poligono regolare

§IMMAGINE§

### Solidi di rotazione

Un solido è di **rotazione** se si ottiene facendo ruotare una figura piana attorno a una retta. I principali solidi di rotazione sono:

* il **cilindro**, generato dalla rotazione completa di un rettangolo attorno alla retta di un suo lato
* il **cono**, generato dalla rotazione completa di un triangolo rettangolo attorno alla retta di un suo cateto
* la **sfera**, generata dalla rotazione completa di un semicerchio attorno al suo diametro

§IMMAGINE§

### Le superfici dei poliedri

Per calcolare la misura della **superficie di un poliedro** basta sviluppare tale superficie in un piano e calcolare le aree dei poligoni così ottenuti: in questo modo, con lo stesso significato dei simboli usato nel testo (in particolare $p$ è il semiperimetro), si ottengono le seguenti formule:

* prisma: $S_t = 2S_b + 2ph$
* piramide retta: $S_t = S_b + pa$
* tronco di piramide retta: $S_t = a (p' + p) + A + A'$
* cubo: $S_t = 6 s^2$
* tetraedro regolare: $S_t = \sqrt{3} s^2$
* ottaedro regolare: $S_t = 2 \sqrt{3} s^2$
* icosaendro regolare: $S_t = 5 \sqrt{3} s^2$
* dodecaedro regolare: $S_t = 3 s^2 \sqrt{25 + 10 \sqrt{5}}$

### Le superfici dei solidi di rotazione

Le seguenti formule esprimono la misura dell'area delle superfici dei principali solidi di rotazione:

* cilindro: $S_l = 2 \pi rh \quad S_b = \pi r^2 \quad S_t= 2 \pi r(h + r)$
* cono: $S_l = \pi ra \quad S_b = \pi r^2 \quad S_t = \pi r(a + r)$
* tronco di cono: $S_t = \pi a(r + R) + \pi r^2 + \pi R^2$
* sfera: $S_t = 4 \pi r^2$

### Volumi ed equivalenza nello spazio

Il **volume** di un solido è la caratteristica comune a tutti i solidi che hanno la medesima estensione spaziale; l'unità di misura dei volumi è il cubo di lato unitario. Si dimostra che:

* i volumi di parallelepipedi rettangoli che hanno basi congruenti sono proporzionali alle rispettive altezze
* il volume di un parallelepipedo rettangolo di dimensioni $a, \space b, \space c$ è dato dalla formula $V = abc$

Due solidi si dicono equivalenti se hanno la stessa estensione. Il **principio di Cavalieri** enuncia un criterio per stabilire se due solidi sono equivalenti:

* se due solidi si possono disporre in modo che risultino equivalenti tutte le loro sezioni con piani paralleli al piano della base, allora essi sono equivalenti

In base a questo principio si dimostra che:

* due prismi sono equivalenti se hanno le basi equivalenti ed altezze congruenti
* due piramidi sono equivalenti se hanno basi equivalenti e altezze congruenti
* una piramide è equivalente alla terza parte di un prisma che ha la base equivalente a quella della piramide e della stessa altezza
* un cilindro è equivalente a un prisma che ha la base equivalente a quella del cilindro e la stessa altezza
* un cono è equivalente a una piramide che ha la base equivalente a quella del cono e la stessa altezza
* una sfera è equivalente all'anticlessidra

### Misure dei volumi

In base ai teoremi di equivalenza si ricavano le seguenti formule per il calcolo dei volumi:

* prisma: $V= S_b h$
* piramide: $V= \dfrac{1}{3} S_b h$
* tronco di piramide: $V= \dfrac{1}{3} h (B + b + \sqrt{bB})$
* cilindro: $V= \pi r?2 h$
* cono: $V= \dfrac{1}{3} \pi r^2 h$
* tronco di cono: $V= \dfrac{1}{3} \pi h (r^2 + R^2 + rR)$
* sfera: $V= \dfrac{4}{3} \pi r^3$
