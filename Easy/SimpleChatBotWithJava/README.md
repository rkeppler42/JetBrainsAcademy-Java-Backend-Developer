# 🤖 Simple Chat Bot with Java

A console chatbot built as part of the **Hyperskill Java Backend Developer (Spring Boot) course**.

The project starts as a bot that can only introduce itself and grows into an interactive assistant that talks to the user and helps with studying programming.

---

## 🚀 Project Progress

- [x] **Stage 1** — Meet Your Chat Bot
- [x] **Stage 2** — Introduce Yourself
- [ ] **Stage 3** — _Not Started_
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
