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

### Day 16: December 08, 2018

**Today's Progress**: I completed all the API calls (through coordinates and by city name) in Local Weather Page. I also did some refactorization for simplicity.

**Thoughts**: For the API call by city name I had to do a refactorization of components that allow me to pass me the data more efficiently. 

**Link(s) to work**

1. [API call by city in search component](https://github.com/100DaysOfVue/show-local-weather/commit/f2c4e39098ff2fa94c1877ce7f97c965913ea0dc)
2. [Delete modal component](https://github.com/100DaysOfVue/show-local-weather/commit/14a8f523646842dfd45ea1bf6a12f3cb14fdf339)
3. [Add search weather by city name in App component](https://github.com/100DaysOfVue/show-local-weather/commit/b0b05aab38a2dc5c8a426862297d031b36e87be7)

### Day 17: December 09, 2018

**Today's Progress**: I did some changes to the styles of search component. And work in the design of some icons for local weather app.

**Thoughts**: Today I realised that for a feature in search functions I need to do some backend, so I decided to implement later with GraphQL.

**Link(s) to work**

1. [Change the styles of search component](https://github.com/100DaysOfVue/show-local-weather/commit/1a30b57079175f77e0cfae8ac16dfd5cf8275c17)

### Day 18-19: December 10-11, 2018

**Today's Progress**: Work all two days creating the svg icons for the local weather app.

**Thoughts**: I was a real challenge to create that. First of all, I did not know how to use a design program, I try gravit design and vectr (Inkscape to but I felt a little overwhelmed due it interface). Mainly I used gravit design until get used to how that kind of programs work, then I changed to vectr because I liked more.

Second. When I exported the design was a real problem because I did not know much about svg. So I be forced to learn more about it.

I learned that in paths of svg tags can be defined inside a tag call "*defs*" but, to be shown,  it needs to be used with a tag call "*use*".

Also the paths can be grouped in "*g*" tags for apply styles to all "*paths*" elements inside the group.

### Day 20: December 14, 2018

**Today's Progress**: I Finally added the svg assets to the weather app and use dynamic url import in local weather app.

**Thoughts**: After add the lookup object for the url svg icons I wanted to use it dynamically, without use conditionals like:

```
<img src="icon1" v-if="weatherIcon == icon1" />
< img src="icon2" v-else-if="weatherIcon == icon2" />
...
```

I want to use some like: `<img :src="iconX" />` and add the url through the lookup object but reading in some issue in vuejs github  I can use ```require(`~assets/${iconX}.svg`)``` in a function or computed propertie and used in the src attribute as `<img :src="svgPath(iconX)" />` and it worked :tada:

**Link(s) to work**

1. [Add dynamic import of icons](https://github.com/100DaysOfVue/show-local-weather/commit/a00b902b2fc9ca12c63c5a7b6c420d7df00bfa75)
2. [Add lookup objects cases](https://github.com/100DaysOfVue/show-local-weather/commit/b63dd3f0547d660a6ff49d88797412343f794aab)

### Day 21: December 15, 2018

**Today's Progress**: I add svg icons components for better animation in local weather app.

**Thoughts**: I go through all knowledge acquired about svg (defs, groups, use) to open every single svg elements and turn it into a vue component. Was painful but I enjoyed it.


**Link(s) to work**

1. [Add icons components](https://github.com/100DaysOfVue/show-local-weather/commit/d3d9a0e4cf087522626d6df277a204602a8f5490)

### Day 22: December 17, 2018

**Today's Progress**: Add the dynamic import of svg components also implement the svg animation in local weather app.

**Thoughts**: I used the [Dynamic Components](https://vuejs.org/v2/guide/components.html#Dynamic-Components) feature of vue.js. The problem with that feature is that I had to import and register all the components before using it and I just want to import just one component.

Doing some research I find an [interesting article](https://medium.com/scrumpy/dynamic-component-templates-with-vue-js-d9236ab183bb) that solved my problem using the [dynamic import from webpack](https://medium.com/front-end-weekly/webpack-and-dynamic-imports-doing-it-right-72549ff49234) (with import('url') function).

For svg animation, I used the fill, opacity to animate the icons. For backgrounds with linear gradient I used the tag "animate" of svg. To guide me and understand how animate linear gradients in svg I used this [article](https://designmodo.com/animate-svg-gradients/).

**Link(s) to work**

1. [Add dynamic import of icon component](https://github.com/100DaysOfVue/show-local-weather/commit/9d04ed16273363eb88b996ad8d0c722d4dd0b9eb)
2. [Add full svg animation to icon components](https://github.com/100DaysOfVue/show-local-weather/commit/25b8d53535e9a89756c56b0e55df03df7dd20298)

### Day 23: January 03, 2019

**Today's Progress**: Add styles to weather in local weather app.

**Thoughts**: I only did CSS today. Although it was simple, I struggled a bit to decide if I was using the flexbox or grid system. I learn to use the sup tag and read others that call my attention. 

**Link(s) to work**

1. [Add styles to weather results](https://github.com/100DaysOfVue/show-local-weather/commit/17dd1d158ca249fa72a6f1f761eed773b0dfda71)

### Day 24: January 04, 2019

**Today's Progress**: Add animations to weather results in local weather app.

**Thoughts**: I worked with animations vue using [transition tag](https://vuejs.org/v2/guide/transitions.html). I struggled a bit to use it with 2 main tags because I need to use the [transition mode](https://vuejs.org/v2/guide/transitions.html#Transitioning-Between-Components) transition between components Also, I discovered that for nest animations (for example, a div that has some animation to render it but inside it has elements that need animation) I need to use a transition group tag (which I have not done yet) or just use the CSS animation.

I also created a data reset feature for proper animation when a search is performed.

**Link(s) to work**

1. [Add animation to weather results](https://github.com/100DaysOfVue/show-local-weather/commit/a0316337043625836938fe83c61d697723379262)
2. [Add reset data into search by city name function](https://github.com/100DaysOfVue/show-local-weather/commit/0e55017eda4e9747fef7f658e9ba109b89e3da3b)

### Day 25: January 06, 2019

**Today's Progress**: Add css variables in local weather app.

**Thoughts**: For an easy way to implement responsive design I applied css variable. At the beginning I don't know where to put the :root rules in CSS code, but doing some research I found it.

**Link(s) to work**

1. [Add css variables](https://github.com/100DaysOfVue/show-local-weather/commit/6b9625746c4638369cd605cdc9284fc419aef388)

### Day 26: January 07, 2019

**Today's Progress**: Add media queries properties in local weather app.

**Thoughts**: I fought for the breakpoints I needed to use. There are many media breakpoints on the web, but the ones I found do not work on my page, so I decided to reduce the screen and observe the changes that occurred and decide which breakpoints I would use.

**Link(s) to work**

1. [Add media queries](https://github.com/100DaysOfVue/show-local-weather/commit/55dce84371f32398745d08fbf798bdb6b93329c9)

### Day 27: January 08, 2019

**Today's Progress**: Add error management funcionality on API call in local weather app.

**Thoughts**: I really fought to implement this functionality. Searching in vue cookbook section's [using axes to consume apis](https://vuejs.org/v2/cookbook/using-axios-to-consume-apis.html) I found a way to implement error management. My problem was that I was not using axios (I was using fetch), so I took the main idea of that publication and used it to implement it my way.

**Link(s) to work**

1. [Add error management to function search weather by name](https://github.com/100DaysOfVue/show-local-weather/commit/08adb98b1883343ce74d997a59b63ab373b27f77)
2. [Fix transitions durations in weather component](https://github.com/100DaysOfVue/show-local-weather/commit/861fd4ae66c3e3a2214545fd83fb43b8e4b925da)
3. [Add error messages](https://github.com/100DaysOfVue/show-local-weather/commit/e23e39e038ebcb0a68de3836e02612129fcfdf18)

### Day 28: January 09, 2019

**Today's Progress**: Add footer components to local weather app.

**Thoughts**: This component was very easy to implement, because this is just for information. The only that I fought was to match the right height that the component needed, but with css variables wasn't so hard.

**Link(s) to work**

1. [Add footer comp](https://github.com/100DaysOfVue/show-local-weather/commit/b7564e88a6bd01e5dcffd64d048f52cdefb1c87d)
2. [Add footer styles](https://github.com/100DaysOfVue/show-local-weather/commit/b7564e88a6bd01e5dcffd64d048f52cdefb1c87d)

### Day 29: January 10, 2019

**Today's Progress**: Add mist icons component to local weather app.

**Thoughts**: This was something that I was forecasting a little, But in order to stop it I just add the icon without any animation.

**Link(s) to work**

1. [Add mist comp](https://github.com/100DaysOfVue/show-local-weather/commit/28c4c1f6a678e74176741c3e5c1ef1758897bf5c)
2. [Add mist icon case](https://github.com/100DaysOfVue/show-local-weather/commit/52ff886cff473474044c42f6cdbbb95641aa6f9d)

### Day 30: January 11, 2019

**Today's Progress**: Add font-family and color to local weather app.

**Thoughts**: font-family and color always are my most difficult part. For font-family I follow this [spanish article](https://platzi.com/blog/tipografia/) and for color I used [Coolors App](https://coolors.co/) and [this article](https://platzi.com/blog/color-en-interfaces/).

**Link(s) to work**

1. [Add colors](https://github.com/100DaysOfVue/show-local-weather/commit/34723ccbfe7ba1606023fe30c2cd687ed59cd76c)
2. [Add fonts](https://github.com/100DaysOfVue/show-local-weather/commit/632d5b0a56e0f28a519b82aa2193ae555f6359b6)

### Day 31: January 12, 2019

**Today's Progress**: Fix all bugs to deploy local weather app.

**Thoughts**: Today was the day to fix everything to deploy the application. The most difficult thing was to fix the css properties of the search component so that they work correctly in both chrome and mozilla.

For fix that I have to reset the default propertie that navegator apply, for that I have to do some research and find a [reset styles article](http://meyerweb.com/eric/thoughts/2007/05/01/reset-reloaded/) that I just apply to `form, button and input`.

**Link(s) to work**

1. [Fix search responsive properties](https://github.com/100DaysOfVue/show-local-weather/commit/ad5736f52efa8133a8a88253d10c5738376ff7c9)
2. [Fix mobile footer properties](https://github.com/100DaysOfVue/show-local-weather/commit/ecaaeeffe04678d75cdace3e532612223b675d9a)
3. [Fix icon animations](https://github.com/100DaysOfVue/show-local-weather/commit/109137663aca5c4fc21ea41ed8cd9bb4b138bdf4)

### Day 32: January 14, 2019

**Today's Progress**: Deploy local weather app with netlify. :tada::tada::tada:

**Thoughts**: Was a real pain try to deploy to github pages (well, my error was really stupid :sweat_smile:). Following the [vue cli deployment section](https://cli.vuejs.org/guide/deployment.html#github-pages) where says that I have to create a `vue.config.js` file and edit the `publicPath` but the problem is that `publicPath` option going to use in future vue-cli version (v3.3 exactly) but my own was in 3.0 and I need to edit `baseUrl` instead.

Moreover, when I finish to understand that, the another problem was pick the right github url. This problem I will try to solve it in the next project.

**Link(s) to work**

1. [show local weather app](https://https://100daysofcode-tic-tac-toe.netlify.com)

### Day 33: January 23, 2019

**Today's Progress**: Design the interface and refactor default components of [random quote machine](https://github.com/100DaysOfVue/random-quote-machine)

**Thoughts**: I went through the design process using [figma](https://www.figma.com) and took out two possible approach. I'm still deciding which one to use. Also a did a little of refactorization of the default components provided by vue-cli

**Link(s) to work**

1. [Delete default styles](https://github.com/100DaysOfVue/random-quote-machine/commit/53de88853c649af8afe2adc1f30d14998003d98d)
2. [Delete default components](https://github.com/100DaysOfVue/random-quote-machine/commit/b30926d5951f443919a5c7c2ea03830ff0c6ed37)

### Day 34: January 26, 2019

**Today's Progress**: Added [axios](https://github.com/axios/axios) and did the API call in  [random quote machine](https://github.com/100DaysOfVue/random-quote-machine)

**Thoughts**: I did a little of research about how use axios, but it was easy to use.

**Link(s) to work**

1. [API call](https://github.com/100DaysOfVue/random-quote-machine/commit/b173b093be210aeb96154b9b6157472c07634913)

### Day 35: January 27, 2019

**Today's Progress**: Added styles to quote component in  [random quote machine](https://github.com/100DaysOfVue/random-quote-machine)

**Thoughts**: I prepared everything to add the tweet button. I also did some change of class name that, I've to admit, they could be in a separte commit. 

**Link(s) to work**

1. [styles to quote](https://github.com/100DaysOfVue/random-quote-machine/commit/d4b933bbe2a51bd1ac751bc428bc38d4c06088a6)

### Day 36: February 01, 2019

**Today's Progress**: I added the twitter button in [random quote machine](https://github.com/100DaysOfVue/random-quote-machine)

**Thoughts**: It was little hard because I just wanted use the SVG using an `anchor` tag, so for that I learn how to use a svg as background with css. In that order I need to apply some padding because I'm not adding any content inside the tag.

**Link(s) to work**

1. [twitter button](https://github.com/100DaysOfVue/random-quote-machine/commit/cd8d3d3bb452222af630f4b785501fd042dabcaf)

### Day 37: February 05, 2019

**Today's Progress**: I added many animations in [random quote machine](https://github.com/100DaysOfVue/random-quote-machine)

**Thoughts**: In order to add this animations (for title and buttons) I used javascript to add it. But I don't figure out how to implement the twitter button animation at the moment.

**Link(s) to work**

1. [title animation](https://github.com/100DaysOfVue/random-quote-machine/commit/77c4fe6c3f111af26051135d7fc367c8438e14fc)
2. [button animation](https://github.com/100DaysOfVue/random-quote-machine/commit/10391e5227ed61202e9d043481c80c288f4795ee)
1. [button container animation](https://github.com/100DaysOfVue/random-quote-machine/commit/9a4cfea0bfbfdec0c9c74b554231c54cfe531e60)

### Day 38: February 21, 2019

**Today's Progress**: I added twitter animation and fix the number of pixel that the title translate [random quote machine](https://github.com/100DaysOfVue/random-quote-machine)

**Thoughts**: I figured out that using CSS animations was the best options to implement twitter button animation. I even thinking on change the other animations to CSS. I need to refactor my HTML, looks like a spaghetti code (I think :disappointed:)

**Link(s) to work**

1. [refac title animation](https://github.com/100DaysOfVue/random-quote-machine/commit/5a4d9f4ceb7621fb2ddb375c1334a56c79c828b0)
