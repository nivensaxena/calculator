function add(a,b){
    return a+b;
}

function subtract(a,b){
    return a-b;
}

function mult(a,b){
    return a*b;
}

function divide(a,b){
    return a/b;
}

function square(a){
    return mult(a,a);
}

console.log(add(add(10,8),add(66,22)));
console.log(subtract(subtract(10,8),subtract(66,22)));
console.log(mult(mult(10,8),mult(66,22)));
console.log(divide(divide(10,8),divide(66,22)));
