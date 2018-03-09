# propertychange<br>
各种属性的转换<br>
<br>
## 用法<br>
1、带对象的数组，转字符串的时候，数组内的对象会变成[object]。用了这个就可以将数组中的对象也转成字符串。<br>
注意：arr2str可接收两个参数。第一个参数为数组，第二个参数为分隔符号。若不传，会自动默认为"$cCtV@$".若不需要分隔符，可以传''过去即可。<br>
例：<br>
var a = [{name:'123',lvl:1},{name:'123',lvl:1},{name:'123',lvl:1}];<br>
console.log(arr2str(a,''));<br>
<br>
输出：{'name':'123','lvl':'1'}{'name':'123','lvl':'1'}{'name':'123','lvl':'1'}<br>


