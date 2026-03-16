# 💭 Reflection: Game Glitch Investigator

Answer each question in 3 to 5 sentences. Be specific and honest about what actually happened while you worked. This is about your process, not trying to sound perfect.

## 1. What was broken when you started?


- What did the game look like the first time you ran it? just a normal guessing game. 

The Submit Hint button does not work as expected. After selecting a difficulty level (Easy, Medium, or Hard) and clicking New Game, the system immediately displays the message “You already won. Start a new game to play again.” even though a new game should have started.

The hint logic is reversed. For example, when the secret number is 10 and a player enters 12, the game displays “Higher” instead of “Lower.” Since 12 is greater than the secret number, the correct hint should be “Lower.” The same issue happens in reverse situations as well.

After entering a guess, pressing the Enter key should submit the guess just like clicking the Submit Guess button. Currently, the Enter key does not trigger the guess submission, so the user is forced to click the button.

---

## 2. How did you use AI as a teammate?

- Which AI tools did you use on this project (for example: ChatGPT, Gemini, Copilot)?
Gemini
- Give one example of an AI suggestion that was correct (including what the AI suggested and how you verified the result).
- Give one example of an AI suggestion that was incorrect or misleading (including what the AI suggested and how you verified the result).

---

## 3. Debugging and testing your fixes

- How did you decide whether a bug was really fixed?
- Describe at least one test you ran (manual or using pytest)  
  and what it showed you about your code.
- Did AI help you design or understand any tests? How?

---

## 4. What did you learn about Streamlit and state?

- In your own words, explain why the secret number kept changing in the original app.
- How would you explain Streamlit "reruns" and session state to a friend who has never used Streamlit?
- What change did you make that finally gave the game a stable secret number?

---

## 5. Looking ahead: your developer habits

- What is one habit or strategy from this project that you want to reuse in future labs or projects?
  - This could be a testing habit, a prompting strategy, or a way you used Git.
- What is one thing you would do differently next time you work with AI on a coding task?
- In one or two sentences, describe how this project changed the way you think about AI generated code.
