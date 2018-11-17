# 100 Days Of Code - Log

### Day 1: November 13, 2018

**Today's Progress**: I read a lot about making unit testing with Vue and reading Vue documentation to remember how it works while I was working on tic-tac-toe game.

**Thoughts:** I really struggled with Vue unit testing (with Jest) to try to implement it but I decide to let it for a more complex app. Besides the documentation that I read was a little bit old.

**Link to work:** [Tic Tac Toe](https://github.com/100DaysOfVue/tic-tac-toe/commit/5da4662a18a405a543d044eee565ddcc4476a3b8)

### Day 2: November 14, 2018

**Today's Progress**: Add the component functionality to change props from a child component to his parent.

**Thoughts**: Was a great fight figure out how to implement this functionality because I was trying to change the array of the vue data assigning it directly a value with his index `arr[i]="x"` and for that vuejs has [certain methods to detect the change of an array with v-for directive](https://vuejs.org/v2/guide/list.html#Array-Change-Detection). BTW I was conscious that if want change some properties through the child component I have to use the method $emit but the methods mentioned above took me sorpresibly.

**Link(s) to work**: [Tic Tac Toe commit](https://github.com/100DaysOfVue/tic-tac-toe/commit/504ba6a6741767040da1a05aed4ca13faf298472)


### Day 3: November 16, 2018

**Today's Progress**: I continued developing the tic tac toe. I made 2 changes. One for Change player. The other for pick a winner.

**Thoughts** Looping with vue is really easy, but I spare some time because I did a bad assingment in the for loop of function `theWinnerIs`. I need careful

**Link(s) to work**
1. [Player Change Functionaly commit](https://www.freecodecamp.com/challenges/find-the-longest-word-in-a-string)
2. [Winner Functionality commit](https://github.com/100DaysOfVue/tic-tac-toe/commit/d2c7cae003caa99beed1b8d2ea25eebd4193d4b3)
