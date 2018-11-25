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

### Day 4: November 19, 2018

**Today's Progress**: I implement the auto play functionality for the computer in the tic tac toe App.

**Thoughts**: Was hard, but I coded what I thought that the program should do, it has BIG bugs but I think that runs OK for me. At the beginning I just wanted to implement the functionality for even and odd cases but then I realized that it was not going to work because I was not thinking in some cases. Then I try to use switch cases (but took me to LOT of time to change) althrough it worked I asked to some friend if I can implement the functionality without switch cases, he told me some options that blow my mind.  

**Link(s) to work**
1. [Add computer auto play in Tic Tac Toe](https://github.com/100DaysOfVue/tic-tac-toe/commit/f49624048343f9f8919fa0a945404f0f983b1ba4)

### Day 5: November 20, 2018

**Today's Progress**: I worked in simplify the computer turns functions in the tic tac toe App.

**Thoughts**: I struggled to use lookup objects instead of 'if' statement, I know that it can work (on my mind) but I still without hit. 

**Link(s) to work**

Tomorrow I add some links

### Day 6: November 21, 2018

**Today's Progress**: I Finally finished the simplification of computer turns function using lookup object in the tic tac toe App.

**Thoughts**: The main problen of yesterday was that I was picking the wrong use case of "loockup object" of the [guide used](https://www.codereadability.com/replacing-if-statements-with-object-lookups/)

**Link(s) to work**

1. [Add lookup object for simplification of checks functions](https://github.com/100DaysOfVue/tic-tac-toe/commit/aecbb02040d058b898d85444aeda78d9594464f0)

### Day 7: November 22, 2018

**Today's Progress**: I fix the overwrite bug that computer turn functions in the tic tac toe App.

**Thoughts**: I have to eliminate a lot of things but it was easy. I think that the function can be improved but that is work for tomorrow.

**Link(s) to work**

1. [Fix overwrite square bug in computer turn function](https://github.com/100DaysOfVue/tic-tac-toe/commit/22635b36d05a0c19d3a16bc0b904492c9bef8e03)

### Day 8: November 24, 2018

**Today's Progress**: I keep working in the tic tac toe App.

**Thoughts**: I easily added a random move when check lines function doesn't find a match case. And find a bug in a case. I struggled to implement a 'tie game' function but go through some errors with vue lifecycle component.

**Link(s) to work**

1. [Add random move](https://github.com/100DaysOfVue/tic-tac-toe/commit/cab6717363e1c6a0b69c4c8384d85d8b2305fb1d)
