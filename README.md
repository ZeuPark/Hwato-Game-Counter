# Player Round Tracker

A simple HTML + JavaScript web application to track financial changes across multiple players round by round in a game. This tool is useful for tracking how much each player has gained or lost in every round, ensuring the total balance for each round sums to zero.

## Features

✅ Editable player names  
✅ Add new players dynamically  
✅ Add rounds and track amount gained/lost per player  
✅ Automatically calculates the missing value if one player's input is left empty (to ensure round total is zero)  
✅ Validates that each round’s sum equals zero  
✅ Shows running totals per player  
✅ Delete individual rounds  
✅ Reset the game (clears all data)  

## Usage

1. **Edit Player Names**  
   Modify the default player names (A, B, C) using the text inputs at the top and click **“이름 수정”**.

2. **Add a Player**  
   Click **“유저 추가”** to dynamically add a new player with a custom name.

3. **Add a Round**  
   Enter the amount each player gained or lost. If one input is left empty, it will automatically be calculated to ensure the round totals zero.

4. **Remove a Round**  
   Click the **“삭제”** button next to a round to delete it and update totals.

5. **Reset Game**  
   Click **“게임 리셋”** to clear all rounds and reset totals.

## Constraints

- You can leave one player input empty per round, and it will be auto-calculated.
- The total of all players' inputs for a round must equal 0.
- At most one input per round can be left blank.

## Technologies

- HTML
- JavaScript
- CSS (minimal)

## How to Run

Just open the HTML file in any modern web browser.

