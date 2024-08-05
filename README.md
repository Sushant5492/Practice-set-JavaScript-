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

// 5/8/2024 functions and loops in js
let marks = {
  harry: 90,
  shubham: 9,
  lovish: 56,
  Monika: 4
}


// Problem No 1
for (let i = 0; i < Object.keys(marks).length; i++) {
  // console.log("The marks of " + Object.keys(marks)[i] + " are " + marks[Object.keys(marks)[i]])
}

// Problem No 2
for (let key in marks) {
  // console.log("The marks of " + key + " are " + marks[key])
}

// Problem No 3
let cn = 43
let i
while (i != cn) {
  console.log("Try again")
  i = prompt("Enter a number")
}
console.log("You have entered a correct number")

// Problem No 4
const mean = (a, b, c, d) => {
  return (a + b + c + d) / 4
}

console.log(mean(4, 5, 6, 7))

