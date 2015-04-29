var fib = [0,1];
var evens = [];
var sequence = function(){
    for(i = 0; i < 4000000; i++){
        fib[i+2] = fib[i] + fib[1+i];
        if(fib[i+2] > 4000000){
            break;}
        isEven(fib[i+2]);
    }
}
var isEven = function(val){
    if(val % 2 === 0){
       evens.push(val);
    }
}
var total = 0;
var sum = function(){
    for(i = 0; i < evens.length; i++){
        total = evens[i] + total;
    }
}
sequence();
sum();
console.log(total);