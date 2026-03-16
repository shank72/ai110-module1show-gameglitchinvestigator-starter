# 🎮 Game Glitch Investigator: The Impossible Guesser

## 🚨 The Situation

You asked an AI to build a simple "Number Guessing Game" using Streamlit.
It wrote the code, ran away, and now the game is unplayable. 

- You can't win.
- The hints lie to you.
- The secret number seems to have commitment issues.

## 🛠️ Setup

1. Install dependencies: `pip install -r requirements.txt`
2. Run the broken app: `python -m streamlit run app.py`

## 🕵️‍♂️ Your Mission

1. **Play the game.** Open the "Developer Debug Info" tab in the app to see the secret number. Try to win.
2. **Find the State Bug.** Why does the secret number change every time you click "Submit"? Ask ChatGPT: *"How do I keep a variable from resetting in Streamlit when I click a button?"*
3. **Fix the Logic.** The hints ("Higher/Lower") are wrong. Fix them.
4. **Refactor & Test.** - Move the logic into `logic_utils.py`.
   - Run `pytest` in your terminal.
   - Keep fixing until all tests pass!

## 📝 Document Your Experience

- [ To be a guessing game with varying levels of difficulty.] Describe the game's purpose.
- [ One error was the hints: when the number was higher than the guess, it would tell the user to go higher & if the humber was lower than the guess, it would tell the user to go lower.

Another error was when I finished my current round of the game, the new game button did not do anything, so I needed to refresh the page to play again.] Detail which bugs you found.
- [ For the hints, I just switched the hint messages. To fix the new game error, I added code that set "session_state.status" to playing. ] Explain what fixes you applied.

## 📸 Demo

- [![winning game screenshot](image.png) ] [Insert a screenshot of your fixed, winning game here]

## 🚀 Stretch Features

- [ ] [If you choose to complete Challenge 4, insert a screenshot of your Enhanced Game UI here]
