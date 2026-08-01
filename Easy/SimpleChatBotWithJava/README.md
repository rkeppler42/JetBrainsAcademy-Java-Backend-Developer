# 🤖 Simple Chat Bot with Java

A console chatbot built as part of the **Hyperskill Java Backend Developer (Spring Boot) course**.

The project starts as a bot that can only introduce itself and grows into an interactive assistant that talks to the user and helps with studying programming.

---

## 🚀 Project Progress

- [x] **Stage 1** — Meet Your Chat Bot
- [x] **Stage 2** — Introduce Yourself
- [x] **Stage 3** — Let the Chat Bot Guess Your Age
- [ ] **Stage 4** — _Not Started_
- [ ] **Stage 5** — _Not Started_

---

## 📚 About the Stages

The application is developed incrementally. Each stage builds upon the previous implementation, adding new requirements and gradually transforming a basic console program into a complete chatbot.

---

<details>
<summary><strong>📌 Stage 1 — Meet Your Chat Bot</strong></summary>

### 📝 Description

Digital assistants are, in a simplified way, programs you can hold a conversation with — and this project builds one from the ground up.

The first version does nothing but introduce itself. There is no user input and no logic yet: the bot simply states who it is and when it came to life, setting the tone for everything that comes next.

### 🎯 Objectives

1. Print a greeting followed by the name chosen for the bot;
2. Print the year the bot was created, using four digits;
3. Keep the output limited to exactly two lines, respecting the required wording and punctuation.

### 💡 Expected Output

```text
Hello! My name is Aid.
I was created in 2026.
```

The name and the year are up to you — only the shape of the two lines is fixed.

</details>

---

<details>
<summary><strong>📌 Stage 2 — Introduce Yourself</strong></summary>

### 📝 Description

A bot that only talks about itself isn't much of a conversation partner. This version takes the first step towards an actual dialogue.

After the introduction, the bot asks who it is speaking to, waits for the answer and then replies using the name it was given — a small change that makes the interaction feel personal.

### 🎯 Objectives

1. Keep the introduction lines from the previous stage;
2. Ask the user for their name;
3. Read the name typed in the standard input;
4. Compliment the user by name, following the required wording.

### 💡 Expected Output

> Lines starting with `>` mark what the user types.
> The symbol is only a visual separator — the program never prints it.

```text
Hello! My name is Aid.
I was created in 2026.
Please, remind me your name.
> Max
What a great name you have, Max!
```

</details>

---

<details>
<summary><strong>📌 Stage 3 — Let the Chat Bot Guess Your Age</strong></summary>

### 📝 Description

With the introductions out of the way, the bot gains its first real skill: a guessing game.

Rather than asking for the age directly, it asks for three remainders and reconstructs the original number from them. The trick relies on the Chinese Remainder Theorem — knowing the remainders of a division by 3, 5 and 7 is enough to identify any number between 0 and 104, which comfortably covers a human lifespan.

### 🧮 The Formula

```text
age = (remainder3 * 70 + remainder5 * 21 + remainder7 * 15) % 105
```

Where `remainder3`, `remainder5` and `remainder7` are the leftovers of dividing the age by 3, 5 and 7 respectively.

### 🎯 Objectives

1. Keep the greeting and the personalised compliment from the previous stages;
2. Announce the guessing game and ask for the three remainders;
3. Read the three values from the standard input, each one on its own line;
4. Apply the formula to determine the age;
5. Reveal the result using the required wording.

### 💡 Expected Output

> Lines starting with `>` mark what the user types.
> The symbol is only a visual separator — the program never prints it.

```text
Hello! My name is Aid.
I was created in 2026.
Please, remind me your name.
> Max
What a great name you have, Max!
Let me guess your age.
Enter remainders of dividing your age by 3, 5 and 7.
> 1
> 2
> 1
Your age is 22; that's a good time to start programming!
```

</details>

---

## ▶️ How to Run

Make sure a Java Development Kit is installed.

Compile the program:

```bash
javac Main.java
```

Run the compiled program:

```bash
java Main
```
