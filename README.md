script.js
let time = 30;

setInterval(function(){

let timer = document.getElementById("timer");

if(timer){

timer.innerText = time;

time--;

if(time < 0){

let number = Math.floor(Math.random()*10);

let result = document.getElementById("result");

if(result){

result.innerText = "Result: " + number;

}

time = 30;

}

}

},1000);

