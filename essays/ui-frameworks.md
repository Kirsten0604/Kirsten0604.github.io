---
layout: essay
type: essay
title: Why UI Semantics Makes Me Cry
date: 2017-10-5
labels:
  - Software Engineering
  - Learning
  - HTML
  - CSS
  - UI
---

## What was your first opinion on Semantic UI?

I am a person who doesn't always like change.  I had used Bootstrap in the past, and I was used to the way it was styled.  When Semantic UI was introduced, I was automatically terrified.  I did want to learn something new, but at the same time I was afraid I would have a hard time figuring out the language (it took me about a month to get used to Bootstrap, and I still have some issues with it).  It also constantly confuses me to wrap many elements within each other.  If I miss even one closing tag in a nested div:

```<div class ="footer-background">
  <div class="ui centered fixed horizontal list">
    <div class="item">
      <div class="content">
        <div class="header">Pro</div>
      </div>
    </div>

    <div class="item">
      <div class="content">
        <div class="header">|</div>
      </div>
    </div>
</div>
```

I already know I will either struggle and consume time trying to figure out where the last tag goes, or I will give up because I know it is a lost cause.  However, one thing I like about Semantic UI is that you can automatically say the direction you want a certain element to go in (i.e., insert "right", "left", etc. in the div class).

## How can you compare raw HTML and CSS to Semantic UI?

Naturally, hard-coding in HTML is a lot faster than CSS and Semantic UI in general.  Adding the CSS is just a simple step further, but Semantic UI is an entirely separate condition.  With Semantic UI, you have to be specific when targeting certain classes.  For example, you can use generalities for basic HTML and CSS connections (div, span, p, etc.).  For Semantic UI, you must be specific, and may end up with many words between the "." to define the classes.  Also, Semantic UI is a lot more complicated than HTML, considering the fact that each part of the website you work on is separated by specific types of UI classes (topmenu, middlemenu, footer).  However, I would prefer not to be on a time restraint when it comes to Semantic UI, because there are a lot of different ways to design a website with it, and I would like to explore (and find the easiest solution, of course) to see the various pathways.

## Final Comments:

Overall, I would prefer Semantic UI when I have a long period of time to do the project I am working on.  If it is something short, then I would rather use HTML and CSS to give the raw draft of the code (if I had more time, I would finalize it with Semantic UI editing).  However,  I would rather use hard-coding in general, because it gives me easier access individually (if I were targeting more than one div with the same class name, I would use CSS).  Semantic UI is very hard to grasp in the beginning, which is why I still struggle with it even though I practiced for days.  Therefore, I would not recommend Semantic UI for beginners.
