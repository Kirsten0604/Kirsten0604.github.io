---
layout: essay
type: essay
title: Does Green Always Mean Good?
date: 2017-08-29
labels:
  - Software Engineering
  - JavaScript
  - Learning
---

## What were your beginning thoughts on IntelliJ?

To me, IntelliJ is just another typical editor for code.  Well, that is what I originally thought.  It was a whole other story once I actually started to run the program.  Everything I typed gave me an error.  IntelliJ catches errors most other editors would let slide, such as the amount of spacing between loops and the types  of quotes for strings.  For example:

```
console.log("Hello, world!");
```

This would be considered correct by most JavaScript editors, but IntelliJ would oppose that implication, saying that the "" must be single ''.  As you can tell, IntelliJ isn't my favorite program to use when editing code, but it is good in relation to code styling.  I say this because it catches every little detail, and most future industries want programmers who can come up with clean code.  Another important fact was everything has to be redone when loading the IntelliJ environment.  The Script must be reset to 6 instead of 5.1, ES Lint must be readded, etc.  I was trying to find a way to have it automatically default to the settings I had, but failed at the attempt.

## How do you feel when you get a green checkmark?

Naturally, a green checkmark is the one symbol you want to see after you finish typing your code.  However, the journey to get to that point is quite tedious versus using another editor.

## Final Comments:

I did enjoy the Danny WOD that I attended.  It was a good practice problem for me, because it helped me prepare for the real WOD.  The TA also explained an example of a good solution promptly after the Danny WOD was finished, which helped me fix my mistakes and understand the logic better. Here is an example of the Danny WOD solution:

```
function Sharky(foods) {
  let total = 0;
  for (let food of foods) {
    if (food == 'fish') {
      total++;
      console.log("Sharky ate some fish and is happy!");
    } else if (food == 'trash') {
      console.log("Sharky ate some trash and is mad!");
    } else if (food == 'other') {
      console.log("Sharky is starving...")
    }
  }

  if (total >= 4) {
    console.log("Sharky is very satisfied");
  } else {
    console.log("Sharky is on a rampage!");
  }
};
```

JavaScript is my go-to language, and I like using it for websites and certain apps.  As long as I keep practicing and asking questions when I need help, I believe I will do fine with the WOD way of learning.
