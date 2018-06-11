---
title: "Modelli di crescita"
draft: false
weight: 6
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


## La funzione esponenziale e la funzione logaritmica

### La funzione esponenziale

La funzione $y = a^x$ (con $a > 0 \space \wedge \space a \neq 1$) si chiama **funzione esponenziale** ed è definita $\forall x \in \mathbb{R}$; il suo grafico è una funzione crescente se $a > 1$, decrescente se $0 < a < 1$; in ogni caso tutte le funzioni esponenziali passano per il punto di coordinate $(0, \space 1)$.
Data la curva esponenziale di equazione $y = a^x$

* la sua simmetrica rispetto all'asse delle ordinate ha equazione $y = a^{-x}$
* la sua simmetrica rispetto all'asse delle ascisse ha equazione $y = - a^{x}$
* la sua corrispondente nella translazione di vettore $\vec{v} (h, \space k)$ ha equazione $y - k = a^{x-h}$
* la sua corrispondente nella dilatazione di fattori $h$ e $k$ ha equazione $y = k \cdot a^{\frac{x}{k}}$

§IMMAGINE§

### La definizione di logaritmo
Chiamiamo **logaritmo in base $a$ di un numero reale positivo $b$** l'esponente $c$ che si deve dare ad $a$ per avere $b$; vale cioè la seguente corrispondenza di scritture (con $a > 0 \space \wedge \space a \neq 1$)

<div align="center">
$\log_a b = c \leftrightarrow a^c = b$
</div>

In base alla definizione si ha anche che:

* $\log_a a = 1$
* $\log_a 1 = 0$
* $a^{\log_a b} = b$

§IMMAGINE§

### La funzione logaritmica
La funzione $y = \log_a x$ (con $a > 0 \space \wedge \space a \neq 1$) si chiama **funzione logaritmica** ed è definita $x > 0$; il suo grafico si può ottenere da quello della funzione esponenziale per simmetria rispetto alla bisettrice del primo e terzo quadrante ed è una funzione crescente se $a > 1$, secrescente se $0 < a < 1$; in ogni caso tutte le funzioni logaritmiche passano per il punto di coordinate $(1, \space 0)$.

Data la curva logaritmica di equazione $y = \log_a x$:

* la sua simmetrica rispetto all'asse delle ordinate ha equazione $y = \log_a (-x)$
* la sua simmetrica rispetto all'asse delle ascisse ha equazione $y = - \log_a x$
* la sua corrispondente nella translazione di vettore $\vec v (h, \space k)$ ha equazione $y - k = \log_a (x - h)$
* la sua corrispondente nella dilatazione di fattori $h$ e $k$ ha equazione $y = k \space \log_a \dfrac{x}{h}$

{{%expand "Mostra grafico della funzione esponenziale $y = e^{ax}$" %}}
<div align="center">
<div id="expo" class="jxgbox" style="width:500px; height:500px;"></div>
<script type="text/javascript">
var board = JXG.JSXGraph.initBoard('expo', {boundingbox: [-5, 20, 5, -2], axis:true});
var A = board.create('point', [1, Math.exp(1)]);
var graph = board.create('functiongraph', [
         function(x) {
            var a = Math.log(A.Y()) / A.X();
            return Math.exp(a * x);
         }]);      
var txt = board.create('text', [-3, 10, function () {
           return "a = " + (Math.log(A.Y()) / A.X()).toFixed(2);
          }], {fontSize: 16});
</script>
</div>
{{% /expand%}}

### Le proprietà dei logaritmi
Valgono le seguenti proprietà dei logaritmi, supposto che $a$, $b$, $c$ siano numeri reali positivi (con $a \neq 1$):

* $\log_a (b \cdot c) = \log_a b + \log_a c$
* $\log_a (\dfrac{b}{c}) = \log_a b - \log_a c$ 
  * in particolare $\log_a \dfrac{1}{b} = - \log_a b$
* $\log_a b^k = k \cdot \log_a b$

Per passare da un sistema di logaritmi in base $a$ ad un sistema di logaritmi in base $c$ si applica la formula

<div align=center>
$log_a b = \dfrac{\log_c b}{\log_c a}$
</div>

In sistemi di logaritmi di uso più comune sono quelli in base 10 indicati con il simbolo $\log$ e quelli naturali indicati con il simbolo $\ln$.

## Equazioni e disequazioni esponenziali e logaritimiche
### Le equazioni esponenziali elementari
Un'equazione si dice **esponenziale** se l'incognita compare nell'esponente di qualche potenza.

Il metodo di risoluzione di un'equazione esponenziale dipende dalla forma di quest'ultima:

* $a^{f(x)} = a^{g(x)}$ è equivalente a $f(x) = g(x)$; in pratica se le due potenze hanno la stessa base basta uguagliare gli esponenti
* $a^{f(x)} = b$ e $b$ non è una potenza di $a$; è equivalente a $\log a^{f(x)} = \log b \rightarrow f(x) \log a = \log b$; in pratica si considerano i logaritmi dei due membri dell'equazione e si applicano poi le proprietà dei logaritmi.

### Le equazioni esponenziali non elementari
Qualunque equazione non elementare può essere ricondotta a una o più di tipo elementare applicando in modo opportuno le proprietà delle potenze.

In particolare se l'equazione assume la forma

<div align="center">
$k \cdot a^{2x} + h \cdot a^x + p = 0$
</div>

si opera la sostituzione $a^x = t$ con la quale l'equazione assume la forma polinomiale:

<div align="center">
$k t^2 + ht + p = 0$
</div>

Risolta questa equazione, si opera poi la sostituzione inversa e si risolvono le equazioni esponenziali elementari ottenute.

### Le disequazioni esponenziali
Per risolvere una disequazione esponenziale nella forma $a^{f(x)} > a^{g(x)}$ si deve tener conto della seguente regola:

* se $a > 1$ si scrive la disuguaglianza dello stesso verso fra gli esponenti:

<div align="center">
$a^{f(x)} > a^{g(x)} \rightarrow f(x) > g(x)$
</div>

* se $0 < a < 1$ si scrive la disuguaglianza di verso opposto fra gli esponenti:

<div align="center">
$a^{f(x)} > a^{g(x)} \rightarrow f(x) < g(x)$
</div>

### Le equazioni logaritmiche elementari
Un'equazione si dice **logaritmica** se l'incognita compare nell'argomento di un logaritmo. In tal caso il dominio dell'equazione si determina imponendo che l'argomento di ciascuno dei logaritmi sia positivo.

Il metodo di risoluzione di un'equazione logaritmica dipende dalla forma di quest'ultima:

* $\log_a f(x) = b$ diventa $log_a f(x) = \log_a a^b$ ed è equivalente al sistema 

<div align="center">
$\begin{cases} f(x) > 0 \\ f(x) = a^b \end{cases}$
</div>

* $\log_a f(x) = \log_a g(x)$ è equivalente al sistema 

<div align="center">
$\begin{cases} f(x) > 0 \\ g(x) > 0 \\ f(x) = g(x) \end{cases}$
</div>

In pratica se due logaritmi hanno la stessa vase, dopo aver posto le condizioni di esistenza, basta uguagliare i due argomenti.

### Le equazioni logaritmiche non elementari
Qualunque equazione non elementare può essere ricondotta a una o più di questa forma applicando in modo opportuno le proprietà dei logaritmi.

In particolare se l'equazione ha la forma

<div align="center">
$k \space \log_a ^2 x + h \space \log_a x + p = 0$
</div>

si opera la sostituzione $\log_a x = t$ con la quale l'equazione assume la forma polinomiale:

<div align="center">
$k t^2 + h t + p = 0$
</div>

Risolta questa equazione, si opera la sostituzione inversa e si risolvono le equazioni logaritmiche elementari ottenute. 

### Le disequazioni logaritmiche
Per risolvere una disequazione logaritmica nella forma $\log_a f(x) > \log_a g(x)$, poste le condizioni di esistenza dei due logaritmi, si deve tener conto della seguente regola:

* se $a > 1$ si scrive la disuguaglianza dello stesso verso fra gli argomenti: 

<div align="center">
$\log_a f(x) > \log_a g(x) \rightarrow \begin{cases} f(x) > 0 \\ g(x) > 0 \\ f(x) > g(x) \end{cases}$
</div>

* se $0 < a < 1$ si scrive la disuguaglianza dello stesso verso fra gli argomenti: 

<div align="center">
$\log_a f(x) > \log_a g(x) \rightarrow \begin{cases} f(x) > 0 \\ g(x) > 0 \\ f(x) < g(x) \end{cases}$
</div>

### La risoluzione grafica
Un'equazione o una disequazione della forma

<div align="center">
$a^{f(x)} \lessgtr g(x)$ oppure $\log_a f(x) \lessgtr g(x)$
</div>

si può risolvere mediante il confronto grafico delle funzioni al primo e al secondo membro delle due relazioni:

<div align="center">
$\begin{cases}y = a^{f(x)} \\ y = g(x) \end{cases}$ e $\begin{cases}y = \log_a f(x) \\ y = g(x) \end{cases}$
</div>





