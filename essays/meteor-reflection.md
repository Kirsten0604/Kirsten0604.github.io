---
layout: essay
type: essay
title: When Meteor Crashes Your Brain
date: 2017-10-26
labels:
  - Software Engineering
  - Meteor
---

## What did you find easy about Meteor?

I am not even sure how to begin answering this question.  Like I said before, Meteor was by far the hardest programming area compared to all the other sections we have covered.  To me, the easiest part in Meteor was completed after I did the same task once previously.  Although this is a rhetorical statement, I say this because all the formatting was the same in relation to the starting instruction.  For example, the WOD this week was to add an event that works like a delete button.  In one of the homework WODs, we had already done the same thing, except it was a function to update an account.  We had this line:

```
Contacts.update(FlowRouter.getParam('_id'));
```

All we needed was to switch the word "update" to "remove" in the digits WOD:

```
Contacts.remove(FlowRouter.getParam('_id'));
```

## What did you find hard about Meteor?

If a meteor hits the Earth, many people would be injured.

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
