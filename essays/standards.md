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
Recently, I have been following the [Airbnb JavaScript Style Guide](https://github.com/airbnb/javascript) to style my JavaScript code, and checking for errors using ESLint. Here are my thoughts. Coding standards in general are really valuable in ensuring that anyone can understand your code, but people often overlook how coding standards can reinforce good habits and actually teach you about the language.
<br>
## Reinforcement
The biggest thing that I've noticed while using ESLint was how it reinforces good coding habits. I admit that without something to check my code, I sometimes get lazy and don't format my code appropriately. For example, I might write something like `arr[i+1]` instead of the more readable `arr[i + 1]`, which is something I find myself doing a lot if I'm helping a friend or testing something out, and it ends up leaking into code that I will submit. However, with ESLint, seeing the red underline annoys you enough that you are willing to go back and rewrite your code for the small gratification of the red line going away. Then, when you finally fix all the little errors in your code and see the green checkmark in the top right, you get the feeling of relief now that you know that you are finally done. This reinforces the habit of making sure your code is nice and presentable.
## Learning
Another thing that I noticed is that learning the popular coding standard actually helps you learn how to write code in that language. Say that you already know a language like Python, and then you learn a different language, say JavaScript. I find that you tend to think about how to convert Python code to JavaScript, rather than how to code in JavaScript, similar to how a non-native speaker will convert from their native language. While this is completely fine and still leads to working code, it causes you to overlook some features of the language that really make it beautiful. For example, coming into JavaScript, arrow functions were something completely alien to me and I tried to avoid using them. However, ESLint enforces the use of arrow functions when making anonymous functions, which forced me to learn how to write them, and now I understand how much cleaner they can make code look. Another thing was the difference between `let` and `const`, which was something I didn't take the time to fully understand until ESLint reminded me to use `const` vs `let` in certain scenarios and vice versa. Without ESLint catching all of this, I never would have put the effort in to learn all these details about JavaScript, and this has made me appreciate it a lot more.
