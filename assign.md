<Closure>

-a closure is an inner function that has access to the outer function’s variables, and parameters. 
-a closure still can get access to the local variable after the outer function has been returned. 

code example:

function myAddress (streetNo, city){
var introAddress = “My address is”;
/* inner function that has access to introAddress ‘which is an outer function’s variable’ 
and (streetNo, city) ‘which are outer function’s parameters
*/
function whereILive() {
return introAddress + streetNo +city
}
Return whereILive();
}
myAddress( 100 Burrard St, Vancouver) // My address is 100 Burrard St Vancouver


http://eloquentjavascript.net/Eloquent_JavaScript.pdf
http://javascriptissexy.com/understand-javascript-closures-with-ease/
https://developer.mozilla.org/ko/docs/Web/JavaScript/Guide/Closures
https://www.youtube.com/watch?v=71AtaJpJHw0

