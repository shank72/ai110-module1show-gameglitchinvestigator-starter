# 💭 Reflection: Game Glitch Investigator

Answer each question in 3 to 5 sentences. Be specific and honest about what actually happened while you worked. This is about your process, not trying to sound perfect.

## 1. What was broken when you started?

- What did the game look like the first time you ran it?

THe game looked okay at first, but the hint messgages were completely misleading. I was following the hints to get to a certain number, but the actual number I was supposed to guess was something completely different.

- List at least two concrete bugs you noticed at the start  
  (for example: "the secret number kept changing" or "the hints were backwards").

One error was the hints: when the number was higher than the guess, it would tell the user to go higher & if the humber was lower than the guess, it would tell the user to go lower.

Another error was when I finished my current round of the game, the new game button did not do anything, so I needed to refresh the page to play again.
---

## 2. How did you use AI as a teammate?

- Which AI tools did you use on this project (for example: ChatGPT, Gemini, Copilot)?

I used the built-in CLaude to help with the project.

- Give one example of an AI suggestion that was correct (including what the AI suggested and how you verified the result).

I asked Claude about a line that could be a potential error and asked it to confirm if my thinking was correct. I verified the result by applying the suggested change manually and re-running the game to see if it was fixed.

- Give one example of an AI suggestion that was incorrect or misleading (including what the AI suggested and how you verified the result).

I honestly did not get an incorrect AI suggestion.

---

## 3. Debugging and testing your fixes

- How did you decide whether a bug was really fixed?

I decided if a bug was fixed or not by playtesting the game several times.

- Describe at least one test you ran (manual or using pytest)  
  and what it showed you about your code.

One test I ran was with the higher and lower messages. Originally it would display the opposite message than what was needed (if guess>secret it would tell me to go higher). I 

- Did AI help you design or understand any tests? How?

AI did not make any tests and I would not work with this program. Since the secret changes every game, the test would need to change with the secret. At that point, I just manually played the game.

---

## 4. What did you learn about Streamlit and state?

- In your own words, explain why the secret number kept changing in the original app.

I never saw that issue or did not notice that issue when I was playing the original, so I am not sure.

- How would you explain Streamlit "reruns" and session state to a friend who has never used Streamlit?



- What change did you make that finally gave the game a stable secret number?

---

## 5. Looking ahead: your developer habits

- What is one habit or strategy from this project that you want to reuse in future labs or projects?
  - This could be a testing habit, a prompting strategy, or a way you used Git.
- What is one thing you would do differently next time you work with AI on a coding task?
- In one or two sentences, describe how this project changed the way you think about AI generated code.
