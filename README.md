# de-emdash
A bookmarklet for IOS safari to remove all em-dashes from the page in a single click.


<pre>
<code id="bm">javascript:(function(){for(var x=document.querySelectorAll('*'),i=0;i<x.length;i++){var n=x[i].childNodes;for(var j=0;j<n.length;j++){var d=n[j];if(d.nodeType===3)d.nodeValue=d.nodeValue.split('—').join('');}}})();</code>
</pre>

