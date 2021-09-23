---
layout: essay
type: essay
title: Green Checkmark
# All dates must be YYYY-MM-DD format!
date: 2021-09-22
labels:
  - Software Engineering
  - Coding Standards
  - Javascript
---

<img class="ui medium left circular floated image" src="../images/eslint.png">
Recently I have been following the [Airbnb JavaScript Style Guide](https://github.com/airbnb/javascript) to style my Javascript code, and checking for errors using ESLint. Here are my thoughts.
## Reinforcement
The biggest thing that I've noticed while using ESLint was how it reinforces good coding habits. I admit that without something to check my code I sometimes get lazy and don't format my code appropriately. For example, I might write something like `arr[i+1]` instead of the more readable `arr[i + 1]`, which is something I find myself doing a lot if I'm helping a friend or testing something out, and it ends up leaking into code that I will submit. However with ESLint, seeing the red underline annoys you enough that you are willing to go back and rewrite your code for the small gratification of the red line going away. Then when you finally fix all the little errors in your code and see the green checkmark in the top right, you get the feeling of relief know that you are finally done. This reinforces the habit of making sure your code is nice and presentable.
## Learning
Another thing that I noticed is that learning the popular coding standard actually helps you learn how to write code in that language. Say that you already know a language like Python, and then youlearn a different language, say JavaScript. I find that you tend to think about how to convert Python code to JavaScript, rather than how to code in JavaScript, similar to how a non-native speaker will convert from their native language. While this is completely fine and still leads to working code, it causes you to overlook some of the features of the language that really make it beautiful. For example, coming into JavaScript, arrow functions were something completely alien to me and I tried to avoid using them. However ESLint enforces the use of arrow functions when making anonomyous functions, which forced me to learn how to write them, and now I understand how much cleaner they can make code look. Another thing was the difference between `let` and `const`, which was something I didn't take the time to fully understand until ESLint reminded me to use `const` vs `let` in certain scenarios and vice versa.
