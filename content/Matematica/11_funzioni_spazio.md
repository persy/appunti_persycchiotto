---
title: "Funzioni nella spazio"
draft: false
weight: 11
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


- [Le funzioni di due variabili](#le-funzioni-di-due-variabili)
  - [Il sistema di riferimento nello spazio](#il-sistema-di-riferimento-nello-spazio)
  - [Il piano e la sua equazione](#il-piano-e-la-sua-equazione)
  - [I fasci di coniche](#i-fasci-di-coniche)
  - [Le disequazioni in due variabili](#le-disequazioni-in-due-variabili)
  - [Le funzioni di due variabili](#le-funzioni-di-due-variabili)
  - [Massimi e minimi delle funzioni di due variabili](#massimi-e-minimi-delle-funzioni-di-due-variabili)

## Le funzioni di due variabili
### Il sistema di riferimento nello spazio
Fissato un sistema di assi cartesiani ortogonali nello spazio, ciascun punto è individuato da una terna ordinata di numeri $(x, \space y, \space z)$ che rappresentano rispettivamente la sua ascissa, la sua ordinata e la sua quota. In tale sistema di riferimento, dati i punti $A(x_1, \space y_1, \space z_1)$ e $B(x_2, \space y_2, \space z_2)$, si ha che:
* la misura del segmento $AB$ è $\overline{AB} = \sqrt{(x_2 - x_1) ^2 + (y_2 - y_1) ^2 + (z_2 - z_1) ^2}$, in particolare:
    * se $AB$ è parallelo all'asse $x \rightarrow \overline{AB} = |x_2 - x_1|$
    * se $AB$ è parallelo all'asse $y \rightarrow \overline{AB} = |y_2 - y_1|$
    * se $AB$ è parallelo all'asse $z \rightarrow \overline{AB} = |z_2 - z_1|$
* il punto medio $M$ del segmento $AB$ ha come coordinate la semisomma delle coordinate di $A$ e di $B$:

<div align="center">
$x_M = \dfrac{x_1 + x_2}{2}, \qquad y_M = \dfrac{y_1 + y_2}{2}, \qquad z_M = \dfrac{z_1 + z_2}{2}$
</div>

### Il piano e la sua equazione
Un piano nello spazio ha equazion della forma $ax + by + cz + d = 0$

In particolare: 
* se $d = 0$ il piano passa per l'origine
* se manca una delle variabili, il piano è parallelo all'asse di quella variabile
* se mancano due variabili, il piano è parallelo al piano di quelle variabili

### I fasci di coniche
Un'equazione della forma $a x^2 + bxy + cy^2 + dx + ey + f = 0$ rappresenta sempre una conica; posto $\Delta = b^2 - 4ac$, si ha che:
* se $\Delta > 0$ la conica è un'iperbole
* se $\Delta = 0$ la conica è una parabola
* se $\Delta < 0$ la conica è un'ellisse (oppure una circonferenza se $b = 0$ e $a = c$)

Quando l'equazione di una conica dipende da un parametro, si ha un faascio di coniche.

### Le disequazioni in due variabili
Una disequazione lineare in due variabili $f(x, \space y) > 0$ ha per soluzione l'insieme delle coppie $(x, \space y)$ che appartengono a una determinata regione del piano. Per individuare tale regione si deve:
* considerare l'equazione $f(x, \space y) = 0$ e disegnare la curva ad essa associata che divide il piano in due o più regioni separate e complementari
* scegliere un punto $A$ qualsiasi del piano che appartenga ad una delle regioni individuate dalal curva
* sostituire le sue coordinate nella disequazione: se la diseguaglianza ottenuta è vera, la regione di piano delle soluzioni è quella che contiene $A$

### Le funzioni di due variabili
Una funzione di due variabili è una legge che ad ogni coppia ordinata di numeri reali $(x, \space y)$ appartenente a un insieme $D$ associa uno e un solo numero reale $z$; si scrive in questo caso:

<div align="center">
$z = f(x, \space y)$
</div>

Intersecando una superficie $z = f(x, \space y)$ con un piano parallelo ad uno dei piani coordinati, si ottengono delle funzioni di una sola variabile che ganno come immagini delle linee su tale piano. In particolare si parla di:
* **linee sezione** se si interseva la superficie con un piano $y = k$ parallelo al piano $xz$ ed in questo caso si ottiene il fascio di curve di equazione $z = f(x, \space y)$
* **linee di livello** se si interseca la superficie con un piano $z = k$ parallelo al piano $xy$ ed in questo caso si ottiene il fascio di curve di equazione $f(x, space y) = k$

### Massimi e minimi delle funzioni di due variabili
Data una funzione $f(x. \space y)$ ed un suo punto $P(x_0, \space y_0)$ si diche che:
* $P$ è un **punto di minimo relativo** per $f$ se esiste un intorno di $P$ per tutti punti del quale vale la relazione $f(x, \space y) \geq f(x_0, \space y_0)$
* $P$ è un **punto di massimo relativo** per $f$ se esiste un intorno di $P$ per tutti punti del quale vale la relazione $f(x, \space y) \leq f(x_0, \space y_0)$

I punti di massimo e minimo relativo si possono trovare analizzando il comportamento delle linee di livello.



