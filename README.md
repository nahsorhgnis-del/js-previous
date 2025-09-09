# js-previous
console.log("my name is roshan singh!");
Fullname = "tony stark"
console.log(Fullname);
x = null;
y = undefined;
console.log(x);
console.log(y);
Fullname = 18;
console.log(Fullname);
let Name = "roshan singh";
Name = "roshan";
console.log(Name);
const age = 18;
console.log(age);
{
let name = "ron weasley";
name = "dumbledor";
console.log(name);
}
{
name = "darvin";
console.log(name);
}
let name = "roshan singh";
let age = 18;
let isFollow = true;
let a;
const s = null;
let x = BigInt("777");
y = symbol("hello world!");
const student = {
    fullName : "roshan singh",
    age : 18,
    cgpa :8.5,
    ispass : true, 
}
console.log(student.cgpa);
student["age"] = student["age"] + 1;
console.log(student.age);
student["cgpa"] = student["cgpa"] + 0.5;
console.log(student.cgpa);
const product = {
    fullName : "parker Jotter Standad CT Ball Pen (Black)",
    Rating : 4.0,
    Offer : 5,
    Price : 270, 
}
console.log(product);


const profile = {
    username : "shradhakhapra",
    posts : 195,
    followers : 569,
    following : 4,
    bio : "Entrepreneur & apna college & Ex microsoft DRDO To Educate someone is highest privilege", 
    isFollow : true,
}
console.log(profile);
console.log(typeof profile["posts"]);
we will about arithmetic operators
let a = 5;
let b = 10;
console.log("a + b =", a+b);
console.log("a-b=",a-b);
console.log(a);
console.log(b);
console.log("a = ", a, "& b = ",b);
console.log("a * b = ", a * b);
console.log("a % b =", a % b);
console.log("a ** b = ", a**b);
a--;
console.log(a);
console.log("++b = ",++b);
console.log("b++ = ",b++ );
console.log(b);
a **= 12313542165215432115;
console.log("new one = ", a);
let a = 100;
let b = "100";
console.log(a!==b);
console.log(a<b);
let x = 40;
let y = 42;
let cond1 = x==y;
let cond2 = x<=y;
console.log("cond1 && cond2 = ", cond1 && cond2);
let a = 10;
let b = 20;
condition1 = a<=b;
condition2 = a<b;
console.log("condtition1 && condition2 =", condition1 && condition2);
console.log("c1 && c2",x<=y && x!=y);
console.log("x || y = ", x>=y || x==y);
console.log("!(x!=y) = ", !(x!=y));


conditional statments
age = 10;
if (age >= 18) {
    console.log("you can drive");
} 
if (age < 18) {
    console.log("you CANNOT drive");
} 

let mode = "light";
let color;
if (mode == "dark") {
    color = "black";  
} else {
    color = "white";
}
  
console.log(color); 

let age = 1;
if (age >= 18 ) {
    console.log("vote");
} else {
    console.log("CANNOT vote");
}

let num = 99;
if (num % 2 == 0) {
    console.log(num,"even number");
} else {
    console.log(num,"odd no");
}
        
let age = 10;
if (age >= 18) {
    console.log("you can drive");
} 
else if (age > 50){
    console.log("you cannot drive");
 } else {
    console.log("you cannot drive");
 }


 let age = 60;
if (age < 18){
    console.log("junior");
} else if (age >= 60 ){
    console.log("senior");
} else if (age >= 78){
    console.log("most senior");
} else {
    console.log("middle");
}


let mode = "light";
let color;

if (mode === "light"){
    color = "white";
} else if (mode === "dark") {
    color="black";
} else if (mode === "blue") {
    color="bilu";
} else {
    color="no color default found";
}
console.log(color);


let mode = "pink";
let color;
if (mode === "dark"){
    color = "black";
}
else if (mode === "light"){
    color = "white";
}
else if (mode === "yellow"){
    color = "pila";
} else {
    color = "no color found";
}
console.log(color);

let age = 17;
let result = age >= 18 ? "you can vote" : "you cannot vote";
console.log(result);


let age;
age = 70;
age > 50 ? console.log("you can marry") : console.log("you should live your life");
number = prompt("enter a number");
if ( number % 5 == 0 ){
    console.log("Multiple Of 5 : ", number);
} else {
    console.log("not a multiple of 5");
}

no = prompt("enter a number");
let grade;
if (no >= 90 && no <= 100){
    grade = "Grade A :";
}else if (no >= 70 && no <= 89){
    grade = "Grade B :";
}else if (no >= 60 && no <= 69){
    grade = "Grade C :";
}else if (no >= 50 && no <= 59){
    grade = "Grade D :";
}
else {
    grade = " Grade E : ";
}
console.log("according to your scores, your grade was :" ,grade  ); 
 


//FOR LOOP
for(let count = 1 ; count <= 5; count++){
    console.log("Hello world! my name is Roshan.");
}

//calculate sum from 1 to 5  
let sum = 0;
for (let i = 1; i <= 9999; i++) {
    sum = sum + i;
}
console.log("sum = ", sum);
console.log("loop has ended");

let sum = 0;
for(r=1 ; r <= 50; r++){
    sum = sum + r;
}
console.log("sum is :",sum);

for(var  i=1; i>=0; i++){
    console.log("i is :", i);
}
console.log(i);

let j = 1;
while (j <= 10){
    console.log("roshan is best", j);
    j++;
// }
let str = "apna college";
for(let j of str){
    console.log("j :",j);
}

let str = "roshansingh";
size = 0;
for(let k of str){
console.log("J=",k);
size++;
}

console.log("size is : ",size);

let student = {
    name : "roshan singh",
    age : 18,
    cgpa : 7.5,
    ispass : true,
}
for (let key in student){
    console.log("key :",key,"value: ",[student[key]]);
}

for(num=0; num<=100; num++ ) {
    console.log("number=",num);
}  



practice q1 (enter all odd & even no till 100)
for(no=0; no <= 100; no++) {
    if(no%2!==0){
        console.log("no is odd :",no);
    }
}


practice q2 (guess the game no)
let gameNo = 77;
userinput=prompt("guess the game Number :");
while(gameNo != userinput){
userinput=prompt("you've entered the wrong, try again!");
}
console.log("congo! you've entered the write number");

