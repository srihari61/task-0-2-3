function myButton(){
var q=document.getElementById('initial');
q.style.display="none"
}

document.addEventListener("keyup","findingUserInput");

var index="Arise, awake and stop not till your goal is reached."

//Finding the key user typed
var wordCount=0;  var i=0;

check:

while(i<index.length)
{ 

function findingUserInput(event){
if(i===0){
	var t1= new Date();
	var t11;
	t11=('0' + t1.getMinute()).slice(-2) + ':'+ ('0' + t1.getSeconds()).slice(-2);                   // Record time after first keyup     Ask Joel why for getMonth()+1

}

var key= event.keyCode;

return key;
}

var key123= String.fromCharCode(key);

var textInpChe=findingUserInput;  

//Checking function for finding the validity of input
 

		if(((index[i].keyCode)===textInpChe) && (textInpChe==="32"))   
		{
	        wordCount++;
	        document.getElementById('textinp').innerHTML = key123;
	        i++;
		    break check;

		} 

		if(((index[i].keyCode)===textInpChe) && (textInpChe!=="32"))   
		{
			document.getElementById('textinp').innerHTML = key123;

			if(i===(index.length-1)){
	            var t2= new Date();
	            var t22;
	            t22=('0' + t2.getMinute()).slice(-2) + ':'+ ('0' + t2.getSeconds()).slice(-2);  
	        }
			i++;
		    break check;

		}
		
		else
		{
            break check;
           
		} 

}

function parseTime(s) {
   var c = s.split(':');
   return parseInt(c[0]) * 60 + parseInt(c[1]);

var seconds = parseTime(t22) - parseTime(t11);

var number= Number(seconds);

var number2= number/60;

var avgTypSpeed= wordCount/number2;

var lasttime = document.getElementById('last');

last.style.display= "none";

document.getElementById('last1').innerHTML="Thank You";

document.getElementById('last2').innerHTML="Your typing speed is"+avgTypSpeed+"wpm";

}
