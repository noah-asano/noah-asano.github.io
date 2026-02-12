---
layout: essay
type: essay
title: "The Red Squiggle of Shame: How ESLint Made me Code Cleaner"
# All dates must be YYYY-MM-DD format!
date: 2026-02-11
published: true
labels:
---

## The Red Squiggle of Shame

In the assignment description for this essay, a claim was made that coding standards were supposedly the most important software engineering technique for improving quality. Upon hearing that, I was skeptical. More important than testing? More important than version control? More important than actually understanding what your code does? It seemed like a bold claim. But after spending my first week wrestling with ESLint in VSCode, watching those red squiggly lines multiply every time I thought I was done, I'm starting to see the point. Coding standards make your code look pretty but they also train your brain to think in patterns that actually work.
My initial reaction to ESLint was "Is this really necessary. I am very annoyed right now". I'd write what I thought was perfectly functional code—code that worked only to see my editor light up with errors. "trailing comma required." "Variable unchanged, use const instead of let." "Expected '===' and instead saw '=='." It felt nitpicky, like when you're doing something in front of your dad and making so many mistakes that you think about just letting him take over. I found myself thinking, "Who cares if I use 'let' instead of 'const' if the variable never changes? The computer doesn't care!"
But here's the thing I started noticing after a few days: the computer might not care, but my future self definitely does. ESLint was making me think before I typed, rather than just throwing code at the wall and seeing what sticks.

## Learning Through Enforcement

There's something to the idea that coding standards can actually teach you a programming language, and I'm experiencing it firsthand with TypeScript. 
When I was working in JavaScript, I didn’t think much about edge cases like undefined values or accidentally passing around loosely typed data. 
Since everything was dynamic, I could write code quickly and only fix issues when something broke at runtime. But once I started using TypeScript with ESLint enabled, I began getting warnings about things like implicit any types, unsafe member access, and missing null checks.
At first it felt restrictive, but it forced me to really understand what my data looked like and how functions were being used. I had to learn when to use things like union types. Over time, that discipline changed the way I write code. Now I naturally think about edge cases and type safety up front instead of relying on runtime debugging.
The coding standard didn't just make my code look better, it genuinely expanded my understanding of the language.

## Painful, Useful, or Both?

So is getting rid of ESLint errors painful or useful? Honestly, it's both, and that's probably the point. It's like going to the gym. It sucks while you're doing it, and you question why you're putting yourself through this, but afterward you feel better and you're genuinely stronger. The pain is the mechanism of improvement.

## The Social Contract of Code

Another useful part about coding standards is that they are basically a social contract. When everyone on a team follows the same standards, code becomes more readable and maintainable not because of some abstract principle, but because you're not constantly switching between different styles. If everyone indents with two spaces, uses single quotes for strings, and puts their curly braces in the same place, then reading someone else's code feels like reading your own.
Having a standard that says "use arrow functions for callbacks and traditional functions for methods" might seem arbitrary, but it creates a shared vocabulary. When you see an arrow function, you immediately know certain things about it. The standard creates meaning through consistency.

## Beyond the Trivial

So do I agree that coding standards are the most important software engineering technique? I'm not sure I'd go that far. I still have to learn more about the other parts to make a decision. But I no longer think coding standards are trivial. They're not just about indentation and brace placement, though those things matter more than I thought. They're about internalizing best practices, creating shared understanding, and building habits that lead to better code by default.
The real value of ESLint isn't that it catches errors. It's that it trains you to not make those errors in the first place. It's like having a really picky but knowledgeable mentor looking over your shoulder, pointing out every little thing you could do better. Annoying? Yes. Valuable? Also yes. If learning a language means internalizing its idioms and best practices until they become second nature, then yeah, coding standards can definitely help you learn a programming language. They're not everything, but they're a lot more than I gave them credit for.
