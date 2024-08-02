# Practice-set-JavaScript-
Let var char ex.
console.log("JavaScript tutorial 3: var, let and const")
 var a = 45;
 var a = "p"
let b = "Sushant";
const author = "Sushant"
author = 5 // Throws an error because constant cannot be changed
b = 4
const Sushant = 0;
let c = null
let d  = undefined  
{
  let b = 'this'
  console.log(b)
}
console.log(b)

#else if javascript
let a = prompt("Hey whats you age?");
a = Number.parseInt(a); // Converting the string to a number
if(a<0){
  alert("This is an invalid age");
}
else if(a<9){
  alert("You are a kid and you cannot even think of driving");
}
else if(a<18 && a>=9){
  alert("You are a kid and you can think of driving after 18");
}
else{
  alert("You can now drive as you are above 18");
}
console.log("Done")
console.log("You can", (a<18? "not drive" :"drive"))
