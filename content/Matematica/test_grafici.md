---
title: "Test Grafici"
draft: false
weight: 99
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

## Prova di grafici
Grafico della funzione esponenziale $y = e^{ax}$


GRAFICO VUOTO SOTTO

{{%expand "Mostra grafico" %}}
<div align="center">
<div id="NOMEGRAFICO" class="jxgbox" style="width:500px; height:500px;"></div>
<script type="text/javascript">

</script>
</div>
{{% /expand%}}

### Test


![](https://upload.wikimedia.org/wikipedia/commons/8/80/Wikipedia-logo-v2.svg)


<div align="center">
<div id="insiemi" class="jxgbox" style="width:700px; height:300px;"></div>
<script type="text/javascript">
var b = JXG.JSXGraph.initBoard('insiemi', {boundingbox: [-5, 2, 5, -2], axis:true});
var p1 = b.createElement('point',[0,0], {name:'A',size: 4, face: 'o'});
var p2 = b.createElement('point',[1.5,0], {name:'B',size: 4, face: 'o'});
var p3 = b.createElement('point',[1,0], {name:'C',size: 4, face: 'o'});
var p4 = b.createElement('point',[2.5,0], {name:'D',size: 4, face: 'o'});
var ci1 = b.create('circle',[p1,p2], 
    {strokeWidth:1, fillColor:'red', fillOpacity:0.5 });
var ci2 = b.create('circle',[p3,p4], 
    {strokeWidth:1, fillColor:'blue', fillOpacity:0.5 });
var i1 = brd.create('intersection', [c1,c2,0], {visible:false});
var i2 = brd.create('intersection', [c1,c2,1], {visible:false});
var arc1 = brd.create('arc', [p1, i1, i2], {visible:false});
var arc2 = brd.create('arc', [p3, i2, i1], {visible:false});
var c3 = JXG.joinCurves(brd, [arc1,arc2], 
        {   strokeColor:'black', 
            strokeWidth:3, 
            fillColor:'yellow', fillOpacity:0.2
        });

p1.setProperty({fixed:true});
</script>
</div>


<div class="mxgraph" style="max-width:100%;border:1px solid transparent;" data-mxgraph="{&quot;highlight&quot;:&quot;#0000ff&quot;,&quot;nav&quot;:true,&quot;resize&quot;:true,&quot;toolbar&quot;:&quot;zoom layers lightbox&quot;,&quot;edit&quot;:&quot;_blank&quot;,&quot;xml&quot;:&quot;&lt;mxfile userAgent=\&quot;Mozilla/5.0 (X11; Linux x86_64; rv:60.0) Gecko/20100101 Firefox/60.0\&quot; version=\&quot;8.7.6\&quot; editor=\&quot;www.draw.io\&quot;&gt;&lt;diagram id=\&quot;a85d93c3-41de-b1e3-3a9c-9b1449ab0cb2\&quot; name=\&quot;Page-1\&quot;&gt;5ZWxkpswEIafhh6QjUl5+M5Jk8pFahktoDmBGCEHnKfPCknGOuyZFJ67IhSM9K+0Wn3/DkRk307fFe2bn5KBiNKYTRF5jdJ0l+f4NsLFCtuYWKFWnFkpWYQj/wNOjJ165gyGYKGWUmjeh2Ipuw5KHWhUKTmGyyopwlN7WsNKOJZUrNVfnOnGqnm6W/QfwOvGn5xk32zkRMv3Wslz586LUlLNjw231OdyFx0ayuR4I5G3iOyVlNqO2mkPwqD12Oy+w4PotW4Fnf6XDc6W31ScwVc816UvngVuQOw4KcaGazj2tDSREY1HrdGtwFmCQzr01ouKT4D5i4oLsZdCqjkRifE5YCHFoJV8h5tIVuZwqjAiMTnXpmmyzCz0dGKcuEpBaZge3ja5MsTWBNmCVhdc4jd47K4tczcdF4+vS5pbf71IXV/V19QLWxw4vPdRp5+I+nAwsO+hPuXbzTZeo64VZRwxvnKFmbnsMAB00M8Bv/lC7tmK+8sKPN5Mh4RDcJ3s4ANlJ1HBa8OqRBKAemE4cfySvLhAyxkTjyydvxTGwLnDg3b/4M8TTMhDExKydmFzx4RneLBbeVD8nx4k2aeZgNPlPzLHbv7V5O0v&lt;/diagram&gt;&lt;/mxfile&gt;&quot;}"></div>
<script type="text/javascript" src="https://www.draw.io/js/viewer.min.js"></script>

<svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="202px" version="1.1" viewBox="0 0 202 122" style="max-width:100%;max-height:122px;"><defs/><g transform="translate(0.5,0.5)"><ellipse cx="140" cy="60" rx="60" ry="60" fill-opacity="0.66" fill="#0000ff" stroke="#6c8ebf" stroke-opacity="0.66" pointer-events="none"/><ellipse cx="60" cy="60" rx="60" ry="60" fill-opacity="0.66" fill="#ff0000" stroke="#b85450" stroke-opacity="0.66" pointer-events="none"/><g transform="translate(55.5,53.5)"><switch><foreignObject style="overflow:visible;" pointer-events="all" width="8" height="12" requiredFeatures="http://www.w3.org/TR/SVG11/feature#Extensibility"><div xmlns="http://www.w3.org/1999/xhtml" style="display: inline-block; font-size: 12px; font-family: Helvetica; color: rgb(0, 0, 0); line-height: 1.2; vertical-align: top; width: 9px; white-space: nowrap; overflow-wrap: normal; text-align: center;"><div xmlns="http://www.w3.org/1999/xhtml" style="display:inline-block;text-align:inherit;text-decoration:inherit;">A</div></div></foreignObject><text x="4" y="12" fill="#000000" text-anchor="middle" font-size="12px" font-family="Helvetica">A</text></switch></g><g transform="translate(136.5,53.5)"><switch><foreignObject style="overflow:visible;" pointer-events="all" width="7" height="12" requiredFeatures="http://www.w3.org/TR/SVG11/feature#Extensibility"><div xmlns="http://www.w3.org/1999/xhtml" style="display: inline-block; font-size: 12px; font-family: Helvetica; color: rgb(0, 0, 0); line-height: 1.2; vertical-align: top; width: 8px; white-space: nowrap; overflow-wrap: normal; text-align: center;"><div xmlns="http://www.w3.org/1999/xhtml" style="display:inline-block;text-align:inherit;text-decoration:inherit;">B</div></div></foreignObject><text x="4" y="12" fill="#000000" text-anchor="middle" font-size="12px" font-family="Helvetica">B</text></switch></g></g></svg>


![immagine](https://upload.wikimedia.org/wikipedia/commons/thumb/3/35/Tux.svg/280px-Tux.svg.png)

_Intersezione_

