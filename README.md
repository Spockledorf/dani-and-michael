# Who Said It? 💍
**A Custom Wedding Reception Game for Dani & Michael**

## Overview
This repository contains a lightweight, interactive web-based game designed for Dani and Michael's wedding reception. Guests can test how well they know the couple by guessing who said a specific quote. 

## Features
* **Progressive Leveling:** Guests start with a quick 5-question round and can unlock 10-question and 15-question levels by scoring at least 40%.
* **Dynamic Quote Pool:** Quotes are randomized for every session and drawn from a master list, ensuring no two playthroughs are exactly the same.
* **Session History:** At the end of each round, players can review the quotes they just answered and see the correct attributions. 
* **Custom Wedding Theme:** The UI is fully styled in the couple's wedding palette (lavender, white, and gray).

## File Structure
* `index.html`: The core game logic and structural markup. Contains the `CONFIG` object to set the names of Partner A and Partner B.
* `styles.css`: All visual styling, including the custom color variables, fonts, and responsive layouts[cite: 3].
* `quotes.js`: The master database of quotes. 

## How to Add Quotes
To add or modify quotes, simply open `quotes.js` and follow this format[cite: 1]:

```javascript
const QUOTES = [
  { text: "I'm not saying I'd fight a goose, I'm saying I wouldn't lose.", answer: "A" },
  { text: "Can we get a dog before we get a table? Priorities.", answer: "B" },
];