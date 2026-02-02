# JS-Notes
what is javascript?
=
js is programing launage used to make websites interactive and dynamic.
if a website can respond to clicks, show pop-ups, validate forms,animate content,orload data without refreshing, that's javascript working behind the scenes.
HTML: Structure(text,button,imgaes)
css:style(colors,layout,design)
javascript: behavior(actions& login)

steps:
VARIABLES,
DATA TYPES,
OPRATORS,
CONDITIONS(IF,ELSE),
LOOPS(FOR, WHILE),
FUNCTIONS,
=
>DOM(web interaction)
> document.getElementById
> events(click,submit)
> form validation
> changing html/css using js
=
>
what is variable ?
variable it can store the variable.it also keyword.
js

javascript numbers
js has only one type of number.numbers can be written with or whithout decimal.
example: var x = 3.14;
decimals
         var y = 3;
decimals
# variables: 
used to store data:
1.)variable: var is older js, it can be redeclared,  reassigned, function scoped(not block scoped)
example: 
var x = 10;
var x = 20; //Allowed(re-declare)
x = 30;     //Allowed(re-assign)
console.log(x);


2.)let : Blocked scoped{} , cannot be re-declared in same scope , can be re-assigned
example:
let y =10;
 //let y=20; ERROR(cannot redeclare)
y=23;  //Allowed
console.log(y);

3.) const : blocked scope , cannot be re-declared,cannot be re-assigned.
example: IT CANNOT CHANGED THE VALUES
const z =100;
    ///z =200;    ERROR
    ///const z;   ERROR
console.log(z);







