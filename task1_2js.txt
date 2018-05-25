setTimeout(function(){
document.getElementById("div1").getElementByClassName("toshow").style.visibility = "block";

},1000);                                                                                 //The function is only executed once. If you need to repeat execution, use the setInterval() method.

setTimeout(function(){
document.getElementById("div2").getElementByClassName("toshow").style.visibility = "block";

},2000);

setTimeout(function(){
document.getElementById("div3").getElementByClassName("toshow").style.visibility = "block";

},3000);

setTimeout(function(){
document.getElementById("div4").getElementByClassName("toshow").style.visibility = "block";

},5000);