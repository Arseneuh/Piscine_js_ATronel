# Piscine_js_ATronel

========== EX00=========

/* Ecrivez une fonction qui prend deux paramètres et qui retourne la somme des deux paramètres. Votre fonction devra se nommer add */

function add(a,b){

}

// Ne touchez pas les lignes en dessous.
module.exports = {
  add
}

========== EX01 ============

/* Ecrivez une fonction qui prend deux paramètres et qui retourne la somme des deux paramètres. Votre fonction devra se nommer add */

function add(nb1,nb2){
return nb1 + nb2;
}

// Ne touchez pas les lignes en dessous.
module.exports = {
  add
}

=========== EX02 ===========

/* Ecrivez une fonction multiply qui prend deux paramètres et retourne la multiplication des deux paramètres */


function multiply (nb1, nb2) {
 return nb1 * nb2;
}

// Ne touchez pas les lignes en dessous.
module.exports = {
  multiply
}

============ EX03 =============

/* Ecrivez une fonction divide qui prend en paramètre deux arguments et qui retourne la division du premier par le second, attention la division par zéro est interdite et doit retourner la chaîne de caractère Forbidden */

function divide (nb1, nb2){
if (nb2 == 0) {
  return("Forbidden")
} else {
  return nb1/nb2;
  }
}

// Ne touchez pas les lignes en dessous.
module.exports = {
  divide
}

======== EX04 =============

/* Ecrivez une fonction modulo qui prend deux paramètres en arguments et qui retourne le premier paramètre modulo le deuxième paramètre */

function modulo (nb1, nb2){
  return nb1%nb2
  }

// Ne touchez pas les lignes en dessous.
module.exports = {
  modulo
}

======= EX05 =============

/* Ecrivez un programme qui affiche uniquement les nombres de 0 à 10 à l'aide d'une variable i */

//Testez votre programme sur index.js

for(let i = 0; i <= 10; i++){
  console.log(i);
}

console.log("fin du programme")

/* la console doit afficher  :
0
1
2
3
4
5
6
7
8
9
10
*/

======== EXO5 ========

/* Ecrivez un programme qui affiche uniquement les nombres de 0 à 10 à l'aide d'une variable i */

//Testez votre programme sur index.js

for(let i = 0; i <= 10; i++){
  console.log(i);
}

console.log("fin du programme")

/* la console doit afficher  :
0
1
2
3
4
5
6
7
8
9
10
*/

============= EX06 ================

/* Créez un programme qui affiche uniquement les nombres pairs de 2 à 100, à l'aide d'une variable */

// Testez votre programme sur index.js

for(let i = 2; i<=100; i = i+2) {
  console.log(i);
}
console.log("fin du programme")





/* la console doit afficher  :

2
4
6
8
10
...
98
100
*/

================= EX07 =======================

// Hello user ! 
/* Ecrire un programme qui affiche dans la console le texte suivant (OUTPUT).
Le programme doit demander à l'utilisateur son prénom. Et ensuite lui souhaiter une belle journée avec son prénom indiqué.

===== OUTPUT =====

Hello user !
How are you today ? What is your name ?> Peter
Have a nice day Peter !

===============

Explications du programme, Peter est le nom indiqué par l'utilisateur, le programme sera testé avec différentes valeurs et devra affiché la valeur indiqué par l'utlisateur lors de la demande du programme.
*/


console.log("Hello user!")
let name= prompt("How are you today ? What is your name ?")
console.log("Have a nice day" + ' '+ name + '!' )

=================== EX08 ===========================

// Rebecca's Secret Message 

/* 
  
Rebecca est amoureuse de David, elle a crée un programme spécialement pour lui avouer sa flamme lors de son prochain cours de programmation.
le programme à la comportement suivant : 

Le programme va saluer l'utilisateur 
Ensuite lui demander son prénom ?
Et si le prénom de l'utilisateur est David, le programme affiche :
"I really wanna stay at your house, and i hope this works out"
Si le prénom de l'utilisateur n'est pas David le programmie affiche : 
"Get away !"

====OUTPUT case David==== 

Welcome to my secret Diary !
What is your name ?> David
I really wanna stay at your house, and i hope this works out...


====OUTPUT case Other==== 
Welcome to my secret Diary !
What is your name ?> Juan
Get Away !


//Pensez à tester votre code sur index.js

  */

console.log("Welcome to my secret Diary !")
const name= prompt("What is your name ?")

if (name === "David") {
  console.log("I really wanna stay at your house, and i hope this works out... ")
} else {
    console.log("Get away !")
}

=============== EX09 ====================

// ChoomChoom

/* Ecrivez une fonction choomChoom qui prend en paramètre un nombre entier et qui retourne la chaîne de caractère Choom si le nombre est pair et ChoomChoom si le nombre est impair */

/* exemple : nombre 4 ===> "Choom"
              nombre 5 ===> "ChoomChoom"    */


function choomChoom(a){
  if (a % 2 == 0) {
     return("choom")
  } else {
   return("choomchoom")
  }
}

// Ne touchez pas les lignes en dessous
module.exports = {
  choomChoom
}

=========== EX10 ====================

function cyberNumber(a){

if (a % 3 == 0 && a % 5 == 0  ) {
  console.log("CyberPunk2077");
  return "CyberPunk2077";
}  if ( a % 3 == 0){
  console.log("Cyber")
  return "Cyber"
} if (a % 5 == 0 ){
  console.log("Punk");
  return "Punk";
}  else {
console.log("pas mutliple de 3 et 5")
}
}
