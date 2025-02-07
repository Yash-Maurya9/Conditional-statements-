# Conditional-statements-
Conditional statements are if else 

let age = 27;
if (age >= 18){
    console.log("Youre not eligible");
}




let num = 13;
if(num%2  === 0){
    console.log("Number is even ")
} else {
    console.log("Number is odd")
}



let mode = "dark";
let color;

if(mode === "dark"){
    color = "black";
}else if (mode === "pink"){
    color = "pink";
}else if (mode === "blue"){
    color = " blue";
}else{
    color = "white";
}

console.log(color);


let num1 = prompt("Enter Your Number:");
if(num1 % 5 === 0) {
    console.log( num1 ,"Divisible");
}else{
    console.log(num1,"not divisble");
};
