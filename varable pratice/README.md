This file contain the code for the varable pratice code. 
The readme file holds the code and notes that explain what everything does. 

script.js code

/*Variable challenges*/
const name = "Samantha";/*Varable string*/
const userage = 18; /*Varable number*/
const studentornot = true; /*Varable boolean*/
const favecolor = null; /*This varable has not been chosen to be defined, so add a null to nullafiy the varable*/


const message = `Hi, my name is ${name} and I am ${userage} years old. Am I a student? ${studentornot}`
/*Combanation of all the const varables*/
 console.log(message);
/*Console log message*/

const playername = "Player200745";/*Varable is a string*/
let points = 50;/*Varable number, will change used let */
let over = false; /*Varable boolean. will change used let */
const playermessage = `${playername} finished the game with ${points}. Game over? ${over}`;
/* Combined varables*/
console.log(playermessage);
/*Consle log display*/

points= 100; /*Changed varable points*/
over= true; /*Changed varable over*/
console.log(`End Points: ${points}`);/*Displayed new varable content*/
console.log(`Game over? ${over}`);/*Displayed new varable content*/


const movie = "Transformers";
const watched = 2;
const likedornot = false;
const rating = null;
const moviemessage = `I watched ${movie} ${watched} times. Did I like it? ${likedornot}.`
console.log(moviemessage)
