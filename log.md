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
1. [Player Change Functionaly commit](https://github.com/100DaysOfVue/tic-tac-toe/commit/af9de92b62a98ae830b369fd9ccd5396a0862fdc)
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

### Day 9: November 26, 2018

**Today's Progress**: I add a tie game functionality in the tic tac toe App.

**Thoughts**: Since 24 I was trying to applied this functionality. I begun trying with some functions in lifecycle hooks of vue, but when the functions triggered the data was not reactive. So instead I decided (the more logical. But in that time I wasn't logical) add a condition in `theWinneris` function.

**Link(s) to work**

1. [Add Tie Game functionality](https://github.com/100DaysOfVue/tic-tac-toe/commit/1c7707be22bb4f32ba790e68471cf412f979a2f5)

### Day 10: November 27, 2018

**Today's Progress**: Finally the Tic Tac Toe App is finished. Yay! :tada::tada::tada:

**Thoughts**: This day I added the styles and animations. Struggle a little with [Vuejs animations](https://vuejs.org/v2/guide/transitions.html) but for the rest was a little easy. Even add the reset functionality was.

**Link(s) to work**

1. [Add styles](https://github.com/100DaysOfVue/tic-tac-toe/commit/8ce442391ee68267d23e6f44e2dbb83384e3b966)
2. [Reset functionality](https://github.com/100DaysOfVue/tic-tac-toe/commit/4a23aad00ed24ece4dba08ff5cdaad1825b3c2ae)
3. [Add animations](https://github.com/100DaysOfVue/tic-tac-toe/commit/69407bfedf7bd1e904d8b92f4182735b822f0583)

### Day 11: November 28, 2018

**Today's Progress**: Deploy the tic tac toe with [Netlify](https://www.netlify.com/)

**Thoughts**: I fought to try to deploy the app with github pages but at the end I finished using Netlify. I follow the [deployment guide in Vue CLI 3](https://cli.vuejs.org/guide/deployment.html#github-pages) and doesn't work.

**Link(s) to work**

1. [Tic Tac Toe App](100daysofcode-tic-tac-toe.netlify.com)

### Day 12: December 03, 2018

**Today's Progress**: I started to build 'Show The Local Weather' page.

**Thoughts**: I Designed a mockup, before to start, for more speed in building the page. Tried to use a tool like [figma](https://figma.com), but it took me so much time so I stopped. The curious thing was I enjoyed. :relaxed:

I start to use the BEM methodology for CSS. I don't get used yet, but I like the descriptive.

**Link(s) to work**

1. [Add modal component](https://github.com/100DaysOfVue/show-local-weather/commit/650d44bf2f00f4ea7c0cc2230e22071b637707fb)
2. [Add weather component](https://github.com/100DaysOfVue/show-local-weather/commit/edfa26a9c6ed0f9e10ecd63902af54462ae2daa0)

### Day 13: December 04, 2018

**Today's Progress**: I worked to build a functionality to change between components in 'Show The Local Weather' page.

**Thoughts**: I discovered that only the components/tags that are called directly within other components are the only ones that can be use the <style scoped> in the template.

**Link(s) to work**

1. [Add search component](https://github.com/100DaysOfVue/show-local-weather/commit/c19577d9333039ecdcfe89f27659ea843c39ed1d)
2. [Add functionality to change between components](https://github.com/100DaysOfVue/show-local-weather/commit/d4e934ee8849b14a6fbcf4c254173383c06c6ed2)

### Day 14: December 05, 2018

**Today's Progress**: I try to use the [Open Weather Map API](https://Openweathermap.org) in 'Show The Local Weather' page but I couldn't.

**Thoughts**: I think that can be a problem with the headers in the fetch method. Even if is a response 200 it throw the error `TypeError: 'caller', 'callee', and 'arguments' properties may not be accessed on strict mode functions or the arguments objects for calls to them at Function.remote` And I don't know what that means.

### Day 15: December 07, 2018

**Today's Progress**: Finally I could make a [Open Weather Map API](https://Openweathermap.org) API call in 'Show The Local Weather' page.

**Thoughts**: I could not make the call before because I was using an incorrect API endpoint.

I was using a filter method to show the API temperature in degrees Celsius or Fahrenheit depending on another property, but I realized that the filter methods do not link the vue instance, it just takes the value to change

**Link(s) to work**

1. [Add API call](https://github.com/100DaysOfVue/show-local-weather/commit/57a7d26e9db74086488cdf3cd2033ceedabe3cb9)
2. [Add weather props to weather component](https://github.com/100DaysOfVue/show-local-weather/commit/c98c85582500b9006488be26db53057c952a467b)
