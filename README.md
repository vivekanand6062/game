🍬 Candy Crush JavaScript Game

A simple Candy Crush–style puzzle game built using HTML, CSS, and JavaScript.
This project includes drag-and-drop candy swapping, match detection, scoring, candy falling logic, and multiple game modes (Endless & Timed).

🎮 Features
✔ Drag & Drop

Swap two adjacent candies using mouse drag.

✔ Match Detection

The game automatically checks for:

Match-3 (row & column)

Match-4 (row & column)

Every match clears the candies and increases your score.

✔ Gravity System

When candies are cleared, upper candies fall down and empty spaces are refilled with new candies.

✔ Two Game Modes

Endless Mode – Play without time limit

Timed Mode – Timer starts from 120 seconds

✔ Mode Switching

Switch modes anytime using the Change Mode button.

🧠 How the Game Works
1. Board Creation

An 8×8 grid is generated. Each square gets a random candy image.

2. Game Loop

Runs every 100ms:

Finds matches

Clears matched candies

Updates score

Drops candies down

Refills top row

3. Drag & Drop Validation

Only adjacent swaps are allowed:

Left

Right

Up

Down

Invalid swaps are automatically reverted.

4. Timed Mode

Timer counts down from 120 seconds.
When 0 → game stops and shows final score.
