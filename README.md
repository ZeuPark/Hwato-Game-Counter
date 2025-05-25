# Player Round Tracker 🎲

A simple HTML + JavaScript web application to track financial changes across multiple players round by round in a game.  
This tool is especially useful when playing traditional games like **Hwato (화투)**, where it's critical to ensure each round’s total sum equals zero — especially when real money is on the line.

---

## 🧭 Why This Exists

This project started during a real-life game of Hwato(화투) with friends.

We ran into a familiar problem:
> ❓ “How much did A win just now?”  
> ❓ “Wait, shouldn’t B and C pay differently?”  
> ❓ “Something’s off. This doesn’t add up.”

There was no intuitive or lightweight way to track each round’s results and keep everyone honest. So this app was created to:
- Clearly record round-by-round cash flow
- Auto-calculate missing values
- Help friends enjoy the game without arguments about money

---

## ✅ Features

- Editable player names
- Add new players dynamically
- Add rounds and track amount gained/lost per player
- Automatically calculates the missing value if one player's input is left empty (to ensure round total is zero)
- Validates that each round’s sum equals zero
- Shows running totals per player (positive/negative colored)
- Line graph to visualize progression
- Delete individual rounds
- Reset the entire game
- Save to `.json` file with timestamp
- Load previous sessions from `.json`

---

## 🚀 Usage

1. **Edit Player Names**  
   Modify the default player names (A, B, C) using the input fields and click **“이름 수정”**.

2. **Add a Player**  
   Click **“유저 추가”** to dynamically add a new player with a custom name.

3. **Add a Round**  
   Input scores in units of 100 (e.g., `2` means `200`). Leave **one field empty** and it will be auto-filled to balance the round.

4. **Validate the Round**  
   The app checks that the round totals exactly zero. Otherwise, you’ll get a warning.

5. **Remove a Round**  
   Click the **“삭제”** button next to a round to delete it and update all totals.

6. **Reset the Game**  
   Click **“게임 리셋”** to clear all rounds and totals.

7. **Save & Load**  
   - Save current game state as `.json` file with timestamp  
   - Load previous games from file using the input field

---

## ⚠️ Constraints

- At most **one blank input per round** (auto-completed)
- **Total of all inputs per round must equal 0**
- Input unit is **100**

---

## 📈 Technologies

- HTML
- JavaScript (Vanilla)
- CSS (minimal)
- Chart.js for visual graph

---

## 🧪 How to Run

Simply open `index.html` in any modern browser — no installation or backend required.

---

## 📂 File Structure

├── index.html # Main application
├── gameData_*.json # Saved game sessions (manual download)

---

## ✍️ Author

Built by [ZeuPark](https://github.com/ZeuPark) to solve a real problem in a real game.  
Because in 화투, keeping track of money should be part of the fun — not the fight.