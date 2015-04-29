var multiple = [];
var total = 0;
var sum = function(){
    for(i = 0; i < multiple.length - 1; i++){
        total += multiple[i];
    }
}
var check = function(counter){
    for(counter = 1; counter < 1001; counter++){
        if(counter % 3 === 0 || counter % 5 === 0){
            multiple.push(counter);
        }
    }
}
check();
sum();
console.log(total);