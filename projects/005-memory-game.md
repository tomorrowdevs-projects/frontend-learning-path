# Memory Game

## Project Objective

The goal of this project is to create a classic Memory game where players flip cards to find matching pairs. This game will help you practice DOM manipulation by dynamically updating the game board and event handling to respond to player actions.

## Project Overview

In the Memory game, players see a grid of facedown cards. Each card has a matching pair hidden somewhere in the grid. Players can click on two cards to reveal them. If the cards match, they stay face up. If not, they turn back over. The game continues until all pairs are matched.

### Requirements

1. **Game Board Setup (DOM Manipulation)**
   - Create a grid layout of cards using HTML and CSS.
   - Randomly assign pairs of matching symbols or images to the cards.

2. **Card Flipping (Event Handling)**
   - Add an event listener to each card to handle the flip when it is clicked.
   - Use JavaScript to toggle the visibility of each card's content on click.

3. **Match Checking**
   - Track the two cards that are clicked in each turn.
   - If the two cards match, leave them face up.
   - If they don’t match, flip them back over after a short delay.

4. **Winning Condition**
   - Display a “You Win!” message when all pairs are matched.

### Suggested Structure

1. **HTML Structure**
   - A container for the game grid.
   - Cards as individual elements inside the container, each with a hidden symbol or image.

2. **CSS Styling**
   - Style the cards to have a front (facedown) and back (revealed) view.
   - Use CSS to position the cards in a grid layout.

3. **JavaScript Functionality**
   - Shuffle and distribute matching pairs of symbols/images to the cards.
   - Track the player’s selections and check for matches.
   - Display the "You Win!" message when all pairs are found.
