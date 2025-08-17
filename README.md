# de-emdash
A bookmarklet for IOS safari to remove all em-dashes from the page in a single click.

```js
javascript:(function(){ for(var x=document.querySelectorAll('*'),i=0;i&lt;x.length;i++){var n=x[i].childNodes;for(var j=0;j&lt;n.length;j++){var d=n[j];if(d.nodeType===3)d.nodeValue=d.nodeValue.split('—').join('');}}})();

