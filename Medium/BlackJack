"use strict";
const ps = require("prompt-sync");
const prompt = ps();
let first_card = parseInt(prompt('Draw the First card: '));
let second_card = parseInt(prompt('Draw the second card: '));
let hasBlackJack = false;
let sum = first_card + second_card;

function fun1() {
    if (sum < 21) {
        console.log("Do you want to draw a new card? 🤔");

    } else if (sum === 21) {
        console.log("Wohoo! You've got BlackJack! 😍");
        hasBlackJack = true;
        console.log(hasBlackJack);
    } else {
        console.log("You'are out of the game! 🤨");
    }
}
fun1();
