DevLang Documentation

Welcome to the official documentation for DevLang, a lightweight, beginner-friendly scripting language designed for making small games, utilities, and interactive programs.


---

1. Introduction

DevLang is a simple interpreted language with readable syntax. It is inspired by BASIC-like structures and focuses on quick scripting with minimal setup.

Example snippet:

say("Hello, world!")


---

2. Syntax Overview

2.1 Variables

Variables are declared simply by assigning a value:

number = 7
name = "Dev"

2.2 Functions

DevLang uses built-in functions such as:

say(text) — prints text to the screen.

Other functions can be added by the interpreter.


2.3 Loops

while attempts != 0
    say("Attempts left: " + attempts)
    attempts = attempts - 1
end

2.4 Conditions

if guess == number
    say("Correct!")
else
    say("Wrong!")
end


---

3. Built-in Features

3.1 Output

say(text) displays text.

3.2 String Handling

Strings can be joined using +.

3.3 Comments

Comments use #:

# This is a comment


---

4. DevLang Game Example

say("Welcome to DevLang Game!")

number = 7
guess = 0
attempts = 3

say("Try to guess the secret number between 1 and 10.")

while attempts != 0
    say("You have " + attempts + " attempts left.")
    attempts = attempts - 1
end


---

5. Interpreter

DevLang includes a custom interpreter capable of reading .dev files, parsing lines, and executing logic sequentially.

(Interpreter code to be added when provided.)


---

6. GUI Support

DevLang supports Windows GUI extensions using the DevLang GUI API (planned).

Example:

gui.window("My App", 400, 300)
gui.label("Hello from DevLang GUI!", 10, 10)


---

7. Future Plans

GUI API

Bytecode compiler

Optimized interpreter

DevLang Standard Library



---

8. Credits

Created by Infinityinquire.
