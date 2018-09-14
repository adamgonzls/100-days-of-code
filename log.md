# 100 Days Of Code - Log

### Day 1: May 09, 2018

**Today's Progress:** Forked the 100 days of code branch, this took much longer than it should have.

**Thoughts:** I was pretty frustrated that it took me longer than I expected to do this routine task. Ultimately, I was able to get the fork done using the link below.

**Today's link:** 
1. [Syncing a fork](https://help.github.com/articles/syncing-a-fork/)

### Day 2: May 10, 2018
##### Regular Expressions and D3

**Today's Progress**: 
1. Studied Regular Expressions (45mins)
2. D3.js (15mins)
3. Studied Regular Expressions (47mins)

**Thoughts**: Today I was trying to solve the FreeCodeCamp "Check for Palindromes" task and ended up spending time reviewing Regular Expressions. I've used them a few times and every time I've used them in production, I've been glad that I went that route. This time I decided I wanted to spend a little more time studying them. I will spend more time on RegexOne later. I finished up "Learn D3.js for free" today, I'll need to get more practice to really do anything with this library.

**Today's links:** 
1. [RegexOne](https://regexone.com/lesson/matching_characters?)
2. [FreeCodeCamp - Check for Palinodromes](https://www.freecodecamp.org/challenges/check-for-palindromes)
3. [Learn D3.js for free](https://scrimba.com/g/gd3js)


### Day 3: May 11, 2018

**Today's Progress**:
1. More Regular Expressions (35mins)

**Thoughts** 
I went through more exercises about regular expressions, now know more about what all the different special characters mean: \d means any digit, . (period) means any character, \w means any alphanumeric character and ? means an optional character.

**Today's Links:**
1. [RegExOne](https://regexone.com/lesson/misc_meta_characters?)

### Day 4: May 12, 2018

**Today's Progress**:
1. Regular Expressions (20mins)
2. FreeCodeCamp (40mins)
3. CSS Grid (20mins)

**Thoughts** 
A few more exercises on Regular Expressions. Finished a few more algorithm problems on FreeCodeCamp. Got a little time doing some CSS grid. I'll try to apply it to a real project tomorrow.

**Today's Links:**
1. [RegExOne](https://regexone.com/problem/matching_decimal_numbers)
2. [Scrimba - Learn CSS Grid for Free](https://scrimba.com/g/gR8PTE)

# Day 5: May 13, 2018

**Today's Progress**:
1. CSS Grid (20mins)
2. CSS Grid (55mins)
3. CSS Grid (25mins)

**Thoughts** 
Finished the Grid tutorial, I found the [An Awesome Image Grid](https://scrimba.com/p/pWqLHa/cBq3PsP) lesson as one of the most interesting. I think I might try it on a production site. There are so many new properties and values for CSS Grid. Spent some more time playing with a layout using CSS grid.
## Grid Properties and Values Examples ##
1. `display: grid;`
2. `grid-template-columns: repeat(4, 1fr);`
3. `grid-template-rows: repeat(3, minmax(100px, max-content));`
4. `grid-column: column-start / column-end;`
5. `grid-row: row-start / row-end;`
6. ```grid-area: row-start / column-start / row-end / column-end; <!--(this is short-hand for #5 and #6 above, not my favorite syntax ATM)-->```

**Today's Links:**
1. [Scrimba - Learn CSS Grid for Free](https://scrimba.com/g/gR8PTE)
2. [CSS Grid Layout-crossed sections](https://medium.com/deemaze-software/css-grid-layout-crossed-sections-fca9e956e725)

# Day 6: May 14, 2018

**Today's Progress**:
1. Basic Algorithm (55mins)
2. CSS Grid (70mins)

**Thoughts** 
Spent time working on basica algorithms to search through arrays. Will most likely work on CSS Grid later. Started doing Wes Bos' course on CSS Grid. I think I can finish this one in a day or two. How in the world is tomorrow Day 7 of this challenge? It's gone by so quickly.

**Today's Links:**
1. [CSS Grid.](https://cssgrid.io/)

# Day 7: May 15, 2018

**Today's Progress**:
1. CSS Grid (30mins)

**Thoughts** 
Watched more of Wes Bos' course on CSS Grid. I'm at lesson 11 of 25, I should have this finished by Sunday. Today at the office I was busy with HTML emails, adding a few products to the site, and a emergency CSS fix.

**Today's Links:**
1. [CSS Grid.](https://cssgrid.io/)

# Day 8: May 16, 2018

**Today's Progress**:
1. Basic Algorithm (35mins)
2. CSS Grid (70mins)
3. Basic Algorithm (15mins)

**Thoughts** 
Worked on some algorithms on FreeCodeCamp during lunch. I used the substr method to resolve the issue. I was making this one too complicated for myself as I thought I had to return the matched string instead of returning true or false. I worked on the CSS Grid course some more and I solved Wes Bos' "grid cardio" exercises. I was pretty proud of that. I also solved an algorithm challenge using an ES6 method.

**Today's Links:**
1. [Confirm the Ending](https://www.freecodecamp.org/challenges/confirm-the-ending)
2. [MDN - substr()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/substr)

# Day 9: May 17, 2018

**Today's Progress**:
1. CSS Grid (60mins)
2. Basic Algorithms (40mins)
3. CSS Grid (35mins)

**Thoughts** 
Put the first CSS grid element on the work website today. It's the first step in using CSS grid more regularly. I also started creating some BEM components on the website as well. I hope this will allow other people to move things around without breaking my design. I solved another algorithm today. Today's exercise was to truncate a string (first argument) if the string was longer than the second argument. Also, if the 2nd argument was less than a certain amount append "..." to the string otherwise, append "..." but subtract the characters that would occupy "..." from the string. I also made progress on Wes Bos' CSS Grid course.

**Today's Links:**
1. [Confirm the Ending](https://www.freecodecamp.org/challenges/confirm-the-ending)
2. [MDN - substr()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/substr)
3. [CSS Grid](https://cssgrid.io/)

# Day 10: May 19, 2018

**Today's Progress**:
1. CSS Grid (40mins)

**Thoughts** 
Worked on CSS Grid some more today. The property `grid-auto-flow` with value `dense` can be used to help fill the gaps automatically if the grid has different sized elements within it.

**Today's Links:**
1. [CSS Grid](https://cssgrid.io/)

# Day 11: May 20, 2018

**Today's Progress**:
1. CSS Grid (65mins)
2. Basic Algorithms (15mins)

**Thoughts** 
In the CSS grid exercise today, I created an image gallery. In this lesson I was able to use `display: grid` on both the grid container was well as the children `.item`. This was used to make it easier to get the image to fill up the entire container as well as the overlay. I think the transition I used on the overlay in this example could meet my needs for the customer service / tech support form on the production website. 
```
transition: 0.2s;
transform: translateY(100%);
```
I also did one basic JavaScript algorithm. I used .push() as well as .slice() to resolve it although, I found another method that seemed simpler that used only .splice().

**Today's Links:**
1. [CSS Grid](https://cssgrid.io/)

# Day 12: May 21, 2018

**Today's Progress**:
1. Basic Algorithms (5mins)
2. CSS Grid (60mins)

**Thoughts** 
Solved today's algorithm super quick. Basically, I had to return an array after removing x amount of items from the beginning. I used .splice() on this exercise.
Later, I did more of the CSS grid course, this time re-creating the codepen layout. That exercise took longer than expected and was the most complex css grid layout I've done yet. Tomorrow, I will learn more about css variables in [Learn CSS Variables for free](https://scrimba.com/g/gcssvariables)

**Today's Links:**
1. [CSS Grid](https://cssgrid.io/)

# Day 13: May 22, 2018

**Today's Progress**:
1. CSS Grid (90mins)

**Thoughts** 
Today, I did the 2nd to last lesson in Wes Bos' CSS grid course. After completing the work, I noticed that the "responsive" part of the grid wasn't working properly. After messing around and resorting to copying the HTML and CSS from the source files, it still wasn't working properly. I finally decided to turn off the "Overlay Grid" in Firefox and the behavior stopped.

**Today's Links:**
1. [CSS Grid](https://cssgrid.io/)

# Day 14: May 23, 2018

**Today's Progress**:
1. CSS Grid (50mins)

**Thoughts** 
Finished the CSS Grid course and then started another course that talks about new features in CSS in general *variables*, for example. I also found another JavaScript course in my email. It seems pretty short so I'm going to knock it out too. It's an intro so everything should be super quick. Then, I'm going to go through the intro to ES6. Again, I can knock these out real quick. Lastly, I found this article that showcased some cool web developer portfolios. I'll have to take a look and see how mine measures up.

**Today's Links:**
1. [CSS Grid](https://cssgrid.io/)
2. [Introduction to JavaScript](https://scrimba.com/g/gintrotojavascript)
3. [Introduction to ES6+](https://scrimba.com/g/gintrotoes6)
4. [10 Awesome Web Developer Portfolios](https://codeburst.io/10-awesome-web-developer-portfolios-d266b32e6154)

# Day 15: May 24, 2018

**Today's Progress**:
1. JavaScript (20mins)

**Thoughts** 
Started the ES6 intro. Got reaquainted with string interpolation.
```
let firstName = "adam";
let lastName = "gonz";
console.log(`${firstName} ${lastName}`);
// adam gonz
```
I think this intro will be a good refresher. I'm at 5 out of 24 lessons.

**Today's Links:**
1. [Introduction to JavaScript](https://scrimba.com/g/gintrotojavascript)

# Day 16: May 25, 2018

**Today's Progress**:
1. JavaScript (30mins)

**Thoughts** 
Continued to work on the Introduction to JavaScript. Lots of what is being taught in this course are things I'm already familiar with in JS. Going to finish this course for the commitment and it's a good refresher.

**Today's Links:**
1. [Introduction to JavaScript](https://scrimba.com/g/gintrotojavascript)

# Day 17: May 26, 2018

**Today's Progress**:
1. JavaScript (60mins)

**Thoughts** 
Finished the Intro to JavaScript today. It was a good and brief refresher. Now, on to the Introduction to ES6+. 

**Today's Links:**
1. [Introduction to JavaScript](https://scrimba.com/g/gintrotojavascript)
2. [Introduction to ES6+](https://scrimba.com/g/gintrotoes6)

# Day 18: May 27, 2018

**Today's Progress**:
1. JavaScript (40mins)

**Thoughts** 
Working on the Intro to ES6, I used template literals. Among other things, template literals allow you to format text as it appears in your code so you don't have to concatenate variables (`word + ' ' + word2`).
```
const fullName = `${word1} ${word2}`;
```
I also learned about destructuring. In the example below, I was able to rename the `firstName` and `lastName` properties and then write them to the console using template literals.
```
const personalInformation = {
  firstName: 'Adam',
  lastName: 'Gonz',
  city: 'Chandler',
  state: 'AZ',
  zipcode: 85225
};

const {firstName: fn, lastName: ln} = personalInformation;

console.log(`${fn} ${ln}`);
```


**Today's Links:**
1. [Introduction to ES6+](https://scrimba.com/g/gintrotoes6)

# Day 19: May 29, 2018

**Today's Progress**:
1. MySQL (30mins)
2. JavaScript (110mins)

**Thoughts** 
This afternoon I was trying to work on my local WordPress environment and I was getting `error establishing a database connection`. I started looking around and I figured out that my MySQL password on my localhost expired by adding a file to the WordPress root folder. I reset the password and set the user to never expire the password again. Local environment is working again.

I spent some time working on JS algorithms. I need to think about what is the  simplest answer. I came close to getting the answers but both times, I wrote the code the hard way. For example, I could have tested for -1 and returned false on my main test but instead I tested for >= 0 and returned true which got me into 'when something is true, and I continue, how do I return true without exiting that iteration completely. If I had just returned false if the first test failed, returning true would have been 1 line of code after the false checks. I did use some string interpolation in my console.logs 😀

Continuing with the `Introduction to ES6`, I learned about the for of loop:
```javascript
// iterate through string
let fullName = "Dylan Coding God of Israel";
for (const char of fullName) {
  console.log(char)
}

// iterate through array
let money = [10, 20, 30]
let total = 0;

for (const amt of money) {
  total += amt;
}
console.log(total);
```
I also used the spread operator `...` and the rest operator, which looks just like the spread operator.
Lastly, I touched on arrow functions which, I will use a ton of, I'm sure:
```javascript
// arrow functions allow you to reduce the amount of code (the functions below are the same function)
// Pre-ES6:
function add(...nums) {
  let total = nums.reduce(function (x, y) {
    return x + y;
  })
  console.log(total);
}
// ES6:
function add(...nums) {
  let total = nums.reduce((x, y) =>  x + y);
  console.log(total);
}

add(4, 5, 7, 8, 12);

```
Stopped on lesson 12.

**Today's Links:**
1. [Checking Database Username and Password](https://www.wpkube.com/how-to-fix-error-establishing-database-connection-in-wordpress/)
2. [Reset MySQL Password](https://stackoverflow.com/questions/33467337/reset-mysql-root-password-using-alter-user-statement-after-install-on-mac)
3. [Password Management](https://dev.mysql.com/doc/refman/5.7/en/password-management.html)
4. [Introduction to ES6+](https://scrimba.com/g/gintrotoes6)
5. [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
6. [Creating and highlighting code blocks](https://help.github.com/articles/creating-and-highlighting-code-blocks/)

# Day 20: May 30, 2018

**Today's Progress**:
1. JavaScript (40mins)

**Thoughts** 
Further work on the Intro to ES6+. Covered `let` and `const` also worked on Import & Export as well as Classes.

**Today's Links:**
1. [Introduction to ES6+](https://scrimba.com/g/gintrotoes6)

# Day 21: May 31, 2018

**Today's Progress**:
1. JavaScript (15mins)
2. Git (30mins)

**Thoughts** 
Finished the Intro to ES6+. Lessons covered trailing commas which basically will prevent you from getting an error where previously you would get an error if you had a comma (like after the last property of an object), also did some async/await and sets.
I started reading through Shopify's guide "A Beginner's Git Guide with Shopify". So far, I already know the material covered but I saved this email some time ago and I wanted to go through the material just to see if I can pick up a new tip or two. 

**Today's Links:**
1. [Introduction to ES6+](https://scrimba.com/g/gintrotoes6)
2. [A Beginner's Git Guide with Shopify](https://www.shopify.com/partners/blog/git-guide)

# Day 22: June 1, 2018

**Today's Progress**:
1. Git (30mins)
2. CSS Grid (90mins)

**Thoughts** 
Finished the 3rd of 3 posts from the Beginner's Git Guide. Feel pretty good as I'm comfortable with most of the concepts covered in the posts.
I just finished a CSS Grid course. I appreciate the effort but the teacher was using inches as his values for the grid column width and oother things where that isn't used. I finished the screencast though so I can move on to other things tomorrow.

**Today's Links:**
1. [A Beginner's Git Guide with Shopify](https://www.shopify.com/partners/blog/git-guide)
2. [How to Build a Beautiful Blog](https://scrimba.com/g/gbuildablog)

# Day 23: June 5, 2018

**Today's Progress**:
1. ES6 (60mins)

**Thoughts** 
Got back into ES6 for Everyone. The first lesson where I left off was on destructuring objects. This allows you to access nested data easier.
```javascript
//destructuring an object
const wes = {
  first: 'Wes',
  last: 'Bos',
  links: {
    social: {
      twitter: 'https://twitter.com/wesbos',
      facebook: 'https://facebook.com/wesbos.developer',
    },
    web: {
      blog: 'https://wesbos.com'
    }
  }
}

const twitter = wes.links.social.twitter // old way
const facebook = wes.links.social.facebook // old way again

const { twitter, facebook:fb } = wes.links.social; // renamed facebook to 'fb'
console.log(fb);
console.log(twitter);
```
You can also destructure arrays:
```javascript
// destructuring arrays
const details = ['Wes Bos', 123, 'wesbos.com'];
// const name = details[0]; old way
// const id   = details[1]; old way
const [name, id, website] = details; // when destructuring an array, you use square brackets
console.log(name, id, website);

const data = 'Basketball,Sports,90210,23,wes,bos,cool';
const [itemName, category, sku, inventory] = data.split(',') // split and destructure
console.log(itemName, category, sku, inventory);

const team = ['Wes', 'Harry', 'Sarah', 'Keegan', 'Riker'];
const [captain, assistant, ...players] = team; // the ... is the rest operator
```
I also read an article on how to deal with browsers that don't support grid. In this article they suggest using floats, `display:table-cell`, and feature queries. This is interesting and I may need to start testing these methods out.
**Today's Links:**
1. [ES6 for Everyone](https://es6.io/)
2. [Using CSS Grid: Supporting Browsers Without Grid](https://www.smashingmagazine.com/2017/11/css-grid-supporting-browsers-without-grid/)
3. [How to Make a Chart Using AJAX & REST API's](https://blog.zingchart.com/2017/11/16/how-to-make-a-chart-using-ajax-rest-apis/)

# Day 24: June 6, 2018

**Today's Progress**:
1. CSS Article (15mins)
2. ES6 (40mins)

**Thoughts** 
Article about linting HTML using CSS was an interesting way of adding visual cues to validate CSS. One of the commenters added that build tools could be used for this purpose too, I'll probably investigate both solutions. Did some more lessons from ES6 for Everyone. I have surpassed how far I got in my previous attempts on this course.

**Today's Links:**
1. [Linting HTML using CSS](https://bitsofco.de/linting-html-using-css/)
2. [ES6 for Everyone](https://es6.io/)

# Day 25: June 8, 2018

**Today's Progress**:
1. freeCodeCamp (40mins)

**Thoughts** 
The freeCodeCamp curriculum changed in the last few days. So I've decided to work my way back to where I was when I was solving the JS algorithm problems. I'm working my way through "Applied Visual Design". I'm excited about the next chapter, "Applied Accessibility". I'm hoping I'll learn some things there I can start applying immediately.

# Day 26: June 9, 2018

**Today's Progress**:
1. freeCodeCamp (30mins)
2. freeCodeCamp (35mins)

**Thoughts** 
Working through the applied Visual Design tasks. I had the opportunity to bump-up my understanding of `HSL()`. 
>If you picture a spectrum of colors starting with red on the left, moving through green in the middle, and blue on right, the hue is where a color fits along this line. 

>In hsl() Saturation is the amount of gray in a color. A fully saturated color has no gray in it, and a minimally saturated color is almost completely gray. This is given as a percentage with 100% being fully saturated.

>Lightness is the amount of white or black in a color. A percentage is given ranging from 0% (black) to 100% (white), where 50% is the normal color.
red hsl(0, 100%, 50%), green  hsl(120, 100%, 50%), blue hsl(240, 100%, 50%)

>Mixing white with a pure hue creates a tint of that color, and adding black will make a shade. Alternatively, a tone is produced by adding gray or by both tinting and shading. Recall that the 's' and 'l' of hsl() stand for saturation and lightness, respectively. The saturation percent changes the amount of gray and the lightness percent determines how much white or black is in the color. This is useful when you have a base hue you like, but need different variations of it.

Another good lesson today was on CSS @keyframes and animations. I've done these before but I've had trouble making sense of them. This lesson made me feel silly because it taught how to use the animation properties and the @keyframes rule and how simple it is to use. Maybe when I start applying more complex animations, it'll seem like the more challenging task I remember.
```css
#anim {
  animation-name: colorful;
  animation-duration: 3s;
}
@keyframes colorful {
  0% {
    background-color: blue;
  }
  100% {
    background-color: yellow;
  }
}
```


**Today's Links:**
1. [ES6 for Everyone](https://es6.io/)
2. [Applied Visual Design: Learn How the CSS @keyframes and animation Properties Work](https://learn.freecodecamp.org/responsive-web-design/applied-visual-design/learn-how-the-css-keyframes-and-animation-properties-work)

# Day 27: June 10, 2018

**Today's Progress**:
1. freeCodeCamp (30mins)

**Thoughts** 
Today, my goal is to finish working through the applied Visual Design tasks. Another property that can be used with animation is `animation-iteration-count`. This property can be set to the amount of times you would like an animation to loop or, it can be set to `infinite` as well. Another property `animation-timing-function`, is one that I've used in the past that I could use a better understanding of the different keywords including:
+`ease` - starts slow, speeds up in the middle, then slows down again.
+`ease-out` - quick in the beginning, then slows down
+`ease-in` - slow in the beginning, then speeds up at the end
+`linear` - applies a constant animation speed throughout.
+`cubic-bezier` - the shape of the curve represents how the animation plays out. The x-axis is the duration of the animation (think of it as a time scale), the y-axis is the change in the animation.
```css
animation-timing-function: cubic-bezier(0.25, 0.25, 0.75, 0.75);
```

**Today's Links:**
1. [Reactive UI Animations with CSS Variables](https://www.shopify.com/partners/blog/ui-animation)

# Day 28: June 11, 2018

**Today's Progress**:
1. freeCodeCamp (110mins)

**Thoughts** 
In the Applied Accessibility section I was reminded of the time element with the datetime attribute that can be used to standardize times. The datetime attribute is used to set a valid format of the date - this is the value accessed by assitive devices.
```html
<time datetime="2016-09-15">Thursday, September 15<sup>th</sup></time>
```
Also, I don't think I've used this in production yet, but the audio element can be used to wrap sound in markup. The `controls` attribute shows the browser default play, pause, and other controls.
```html
<audio id="meowClip" controls>
  <source src="audio/meow.mp3" type="audio/mpeg" />
  <source src="audio/meow.ogg" type="audio/ogg" />
</audio>
```
CSS can be used to improve accessibility when you want to visually hide content meant only for screen readers (for example, when something visual like a chart needs an alternative presentation for screen readers - like a table).
The following type of rule could accomplish this:
```css
.sr-only {
position: absolute;
left: -10000px;
width: 1px;
height: 1px;
top: auto;
overflow: hidden;
}
```
**Do not** use `display: none` or `visibility: hidden` as this hides content from everyone, including screen readers. While using zero values for pixels such as `width: 0; height: 0` will remove the document from flow, meaning screen readers will ignore it.
The Web Content Accessibility Guidelines (WCAG) recommend at least a 4.5 to 1 contrast ratio for normal text. 1:1 would be the ratio for the same color (no contrast) to 21:1 for white against black (the strongest contrast).
I was introduced to the `accesskey` attribute which can be used to specify a shortcut key to activate or bring focus to an element. This attribute can be used on any element but is particularly useful when it's used with interactive ones including links, buttons, and form controls.
```html
<button accesskey="b">Important Button</button>
```

# Day 29: June 13, 2018

**Today's Progress**:
1. freeCodeCamp (50mins)
2. Slack Bot Research (70mins)

**Thoughts** 
Today I spent 50 mins working through freeCodeCamp's responsive and flexbox sections. Most of the information covered was pretty basic. I did find the explanation for the `flex` and `flex-basis` properties to be helpful. `flex-basis` specifies the initial size of an item before CSS makes adjustments with `flex-shrink` or `flex-grow`. `flex` is a shorthand property that sets `flex-grow`, `flex-shrink`, and `flex-basis` ex: `flex: 1 0 10px`. 

**Today's Links:**
1. [What does flex: 1 mean?](https://stackoverflow.com/questions/37386244/what-does-flex-1-mean/37386525)
2. [Build a "Serverless" Slack Bot in 9 Minutes with Node.js and StdLib](https://medium.com/slack-developer-blog/build-a-serverless-slack-bot-in-9-minutes-with-node-js-and-stdlib-b993cfa15358)

# Day 30: June 14, 2018

**Today's Progress**:
1. ES6 (40mins)
2. freeCodeCamp (30mins)

**Thoughts** 
An object's properties are not iterable. In order to iterate over all properties, something like `for in` could be used:
```javascript
const apple = {
  color: 'red',
  size: 'Medium',
  weight: 50,
  sugar: 10
};

for (const prop in apple) {
  const value = apple[prop];
  console.log(value);
}
```
I spent some time working on freeCodeCamp. I went through all the CSS grid exercises. Now, I am ready to work on the different "Responsive Web Design Projects".

**Today's Links:**
1. [ES6 for Everyone](https://es6.io/)

# Day 31: June 16, 2018

**Today's Progress**:
1. Tooling (40mins)
2. Tooling (40mins)

**Thoughts** 
This morning I started working on my development environment for my next [project](https://github.com/adamgonzls/tribute-invader). I noticed some warning for npm so I also updated npm and the packages as well. I spent some time configuring the tooling implementing some of the configuration from past projects and adding some from current projects. I'm almost ready to start coding!

**Today's Links:**
1. [Try the latest stable version of npm](https://docs.npmjs.com/troubleshooting/try-the-latest-stable-version-of-npm)
2. [Tribute to Invader](https://github.com/adamgonzls/tribute-invader)
3. [ES6 for Everyone](https://es6.io/)

# Day 32: June 17, 2018

**Today's Progress**:
1. Tooling (55mins)
2. es6 (30mins)

**Thoughts** 
I continued to configure my tooling today and I copied the content from my [existing](https://codepen.io/adamgonzls/pen/aNYzxB) tribute project. I'll need to update some of the containers to be more semantic and add some id's to meet the project requirements. I'll also spend a little time updating the content a little bit.
In ES6 for everyone, one of the exercises was to make a cool animation using .querySelector, .spread, and .map. I enjoyed this lesson and liked that it included template literals to go from the letters of the text to html surrounding each letter.

![A CSS demonstration on the word 'Spreads!' ](/images/spreads-demo.gif)
```javascript
// .querySelector, .spread, .map
const heading = document.querySelector(".jump");
heading.innerHTML = sparanWrap(heading.textContent);

function sparanWrap(word) {
  return [...word].map(letter => `<span>${letter}</span>`).join('');
}
```

**Today's Links:**
1. [Tribute to Invader](https://github.com/adamgonzls/tribute-invader)
2. [ES6 for Everyone](https://es6.io/)

# Day 33: June 18, 2018

**Today's Progress**:
1. es6 (20mins)

**Thoughts** 
Today, I worked through some spread operator examples.
I also worked on one of the responsive web design projects. I had completed the project previously but since then, the requirements have changed and testing has been implemented. I modified the content to fit the requirements.

**Today's Links:**
1. [Using CSS Transitions on Auto Dimensions](https://css-tricks.com/using-css-transitions-auto-dimensions/)
2. [ES6 for Everyone](https://es6.io/)

# Day 34: June 19, 2018

**Today's Progress**:
1. es6 (40mins)
2. Tribute to Invader (30mins)

**Thoughts** 
Today, I covered The rest parameter `...` (which looks like the spread operator but does the opposite) and used it with destructuring:
```javascript
const team = ['kait', 'wes', 'john', 'lux', 'sheena']; 
# destructuring to assign captain and assitant variables, then rest to assign the 'rest' of the players to variable
const [captain, assistant, ...players] = team;
console.log(captain, assistant, players); #
```
Later, I worked some more on the Invader Tribute. I was updating some content and I decided to add some recent CSS features (css variables).

**Today's Links:**
1. [ES6 for Everyone](https://es6.io/)
2. [404 pages from popular sites - Design Inspiration](https://medium.muz.li/404-pages-from-popular-sites-design-inspiration-26e84e9aa174)
3. [Touching up blemishes on Sephora's UI](https://uxdesign.cc/touching-up-blemishes-on-sephoras-ui-c37ea572abbb)
4. [Tribute to Invader](https://github.com/adamgonzls/tribute-invader)

# Day 35: June 29, 2018

**Today's Progress**:
1. es6 (40mins)
2. Tribute to Invader 

**Thoughts** 
(writing this note on July 11th)
I spent time working on the command line and wrote a script to help me parse .csv files. 

**Today's Links:**
1. [Shell Scripting Tutorial](https://www.shellscript.sh/)
2. [How to Write AWK Commands and Scripts](https://www.lifewire.com/write-awk-commands-and-scripts-2200573)
3. [Grep, Awk, and Sed in bash on OSX](http://techslides.com/grep-awk-and-sed-in-bash-on-osx)
4. [Selecting rows in a CSV file based on column value](https://unix.stackexchange.com/questions/80471/selecting-rows-in-a-csv-file-based-on-column-value)

# Day 36: July 11, 2018

**Today's Progress**:
1. WordPress (110mins)

**Thoughts** 
Today, I worked on fine-tuning a page for work. I modified a plugin that displays software titles and descriptions to render h3 tags for the title and I chose to use the content that would be added on the backend with all the appropriate tags as opposed to how I added the h3's. I decided on this because the content added on the backend could have countless elements such as `<li>`, `<p>`, `<a>` and it would be hard to predict what could be added and have it render properly (not to mention it would depend on default CSS).
I also added the helpful link below which I have referenced numerous times when trying to remember how to include a subject in an `<a>`.

**Today's Links:**
1. [Mailto Links](https://css-tricks.com/snippets/html/mailto-links/)

# Day 37: July 17, 2018

**Today's Progress**:
1. Dev Environment / Gulp 4 (80mins)

**Thoughts** 
Today I decided to create a little dev environment that I could have available when needed. I could always use http-server but this environment is more comprehensive - I included gulp-sass and browsersync. Speaking of Gulp, I tried to upgrade to Gulp 4 but ran into errors. I tried to resolve them but I think that I need to re-create my entire Gulp file and I don't really want to do that right now. I'd rather focus on learning other things at the moment. I started reading through their [documentation](https://github.com/gulpjs/gulp) but it still appears to be geared toward the older version. I checked another senior developers gulpfile and he was still using 3.9 so, I reverted. Tomorrow, I'd like to get back to learning. Also, while wrapping up my Invader tribute page, I wanted to use a transition for an effect when rolling over some text. It made me think back to using the @keyframes and I have added the FreeCodeCamp lesson that talked about that so I may update the effect to use that instead (so I can add infinite duration).

**Today's Links:**
1. [Playground](https://github.com/adamgonzls/playground)
2. [Introduction to JavaScript](https://sabe.io/classes/javascript/introduction)
3. [Applied Visual Design: Learn How the CSS @keyframes and animation Properties Work](https://learn.freecodecamp.org/responsive-web-design/applied-visual-design/learn-how-the-css-keyframes-and-animation-properties-work)

# Day 38: July 19, 2018

**Today's Progress**:
1. JavaScript (40mins)

**Thoughts** 
I worked a little on my playground - so glad I decided this method for development. Not having to constantly manually refresh the page is so much more convenient.
I also went through a few JavaScript lessons on (sabe.io)[https://sabe.io]. The lessons I did were pretty basic to me, which is good. I also covered some ES6 methods.

**Today's Links:**
1. [Playground](https://github.com/adamgonzls/playground)
2. [Introduction to JavaScript](https://sabe.io/classes/javascript/introduction)

# Day 39: July 22, 2018

**Today's Progress**:
1. JavaScript (80mins)

**Thoughts** 
In the intro to JavaScript, I was introduced to some JS methods I haven't used yet such as `Math.pow()`
```javascript
let number = Math.pow(3, 2); // 9
```
I've used random before but I want to make note of it here *(you'd make your own function that uses Math.random() in order to get any number outside of the scope of 0 - 1)*:
```javascript
let rando = Math.random(); // some random number between 0 and 1
```
Continuing with the Intro to JavaScript, I found a [good reminder](https://sabe.io/classes/javascript/loops) of a `for in` loop.
```javascript
const person = {
  name: "Max",
  weight: "180",
  age: 28
};
for (const property in person) {
  console.log("This person's " + property + " is " + person[property] + ".");
}
```

**Today's Links:**
1. [Playground](https://github.com/adamgonzls/playground)
2. [Introduction to JavaScript](https://sabe.io/classes/javascript/introduction)

# Day 38: July 23, 2018

**Today's Progress**:
1. git (60mins)

**Thoughts** 
Silly, today I spent way too much time trying to figure out why when I cloned a repo on my other computer, it was cloning the repo into a directory with the projects name. This was a rookie mistake.
I cloned using `git clone nameofrepo` and I should have typed `git clone nameofrepo .`.

**Today's Links:**
1. [Git clone without project folder](https://stackoverflow.com/questions/17581379/git-clone-without-project-folder)

# Day 39: July 24, 2018

**Today's Progress**:
1. JavaScript (30mins)
2. JavaScript (30mins)
3. Bash (15mins)

**Thoughts** 
Pretty basic lesson on arrays and array methods.
Later I worked on automating the process of deploying to Gh-Pages using Gulp. I used this on my tribute to Invader. The next Codecademy project is the [survey form](https://learn.freecodecamp.org/responsive-web-design/responsive-web-design-projects/build-a-survey-form). I'll probably use my playground repo as my base for new projects or, I may clean it up and create a new repo called "scaffolding".
I also watched a tutorial on Bash.I learned that with `cat` I could view the contents of a file. I could append to an existing file by using the `>>` such as `echo 'hello world' >> file.txt` I also learned that I could create nested directories using `mkdir -p a/b/c`.

**Today's Links:**
1. [Introduction to JavaScript](https://sabe.io/classes/javascript/arrays)
2. [Deploying to GitHub Pages with Gulp](https://medium.com/superhighfives/deploying-to-github-pages-with-gulp-c06efc527de8)
3. [Invader](https://adamgonzls.github.io/tribute-invader/)
4. [Build a Survey Form](https://learn.freecodecamp.org/responsive-web-design/responsive-web-design-projects/build-a-survey-form)

# Day 40: July 26, 2018

**Today's Progress**:
1. JavaScript (65mins)
2. Tooling (30mins)

**Thoughts** 
This evening I came up with a solution to a bug on my Random Quote Generator. Basically, when you clicked the (hidden) button to get another quote, the timer wouldn't reset. I fixed that. Then, I decided to get this site functioning similar to my Invader Tribute so I moved several files around and modified my gulp file and added the `gulp deploy` task to make pushing the site up to GitHub Pages much quicker. 

**Today's Links:**
1. [Random Quote Generator](https://adamgonzls.github.io/random-quote-generator/)

# Day 41: July 27, 2018

**Today's Progress**:
1. JavaScript (25mins)

**Thoughts** 
I worked on the objects chapter and liked the `.keys` method which will return the all of an object's keys in an array.
```javascript
console.log(Object.keys(dog));
// ["name", "age", "bark"]
```
Similarily, the `.values` method will return all the values of a JavaScript object in an array.
``` javascript
console.log(Object.values(dog));
// ["Cooper", 3, f] // the f refers to the bark method
```
Lastly, if you want both the keys and values of an object, you can use the `.entries` method.
```javascript
console.log(Object.entries(dog));
//0: ["name", "Cooper"]
//1: ["age", 3]
//2: ["bark", ƒ]
```

**Today's Links:**
1. [Sabe.io](https://sabe.io/classes/javascript/objects)

# Day 42: July 28, 2018

**Today's Progress**:
1. JavaScript (80mins)

**Thoughts** 
Worked on adding a favicon to my random quote generator and I added some quotes.
I then went through a lesson on JS classes. I enjoyed learning about the `class` keyword, `constructor` keyword, extending and `super`. I modified the tutorial code and was getting an undefined on one of my properties and then was able to figure out that my extended class wasn't using the appropriate property name established in the original class.

**Today's Links:**
1. [Sabe.io](https://sabe.io/classes/javascript/classes)

# Day 43: July 29, 2018

**Today's Progress**:
1. JavaScript (90mins)

**Thoughts** 
**Sets** are an object type that let you create a collection of values that must be unique.
```javascript
var social = new Set();

social.add("Facebook");
social.add("Twitter");
social.add("LinkedIn");

console.log(social);
// {"Facebook", "Twitter", "LinkedIn"}
```
**Maps** are an object type that allow you to store collections in key-value pairs. An analogy would be a dictionary - if you want to know the definition of a word (the value), you only need to locate the word (the key).
```javascript
var map = new Map();

map.set("red", "apple");
map.set("blue", "blueberry");
map.set("green", "pear");

console.log(map);
// {"red" => "apple"}
// {"blue" => "blueberry"}
// {"green" => "pear"}
```
**setTimeout** runs a function after a certain amount of time has elapsed. **setInterval** can be used to make the same code repeat over and over, with a set amount ot time in between.
The **Date** object abstracts away a lot of the behind-the-scenes work of getting dates directly.
```javascript
let date = new Date();
console.log(date);
// Sun Jul 29 2018 18:33:58 GMT-0700 (Mountain Standard Time)
```
**Single elements** can be located and manipulated in the DOM by using the `querySelector` method on the `document` object. This method requires a string which can be an ID, class, or tag name of an element.
```javascript
var apples = document.querySelector("#apple");
var pears = document.querySelector(".pears");
var oranges = document.querySelector("span");

console.log(apples);
console.log(pears);
console.log(oranges);
//<div id="apple">Apples taste good.</div>
//<div class="pears">Pears also taste good.</div>
//<span>Same goes with oranges.</span>
```
`querySelectorAll` can be used to get back a list of **Multiple elements**. 
```javascript
var fruits = document.querySelectorAll(".fruit");
console.log(fruits);
//(3) [div.fruit, div.fruit, div.fruit]
```
The JavaScript `classList` property can be used to easily **add**, **remove**, or check if a element **contains** a class or not.
**Add**
```javascript
var fruit = document.querySelector(".apple");
fruit.classList.add("tasty");
// <div class="apple tasty">Apples are tasty.</div>
```
**Remove**
```javascript
var fruit = document.querySelector(".apple");
fruit.classList.remove("tasty");
// <div>Apples are tasty.</div>
```
**Contains**
```javascript
var fruit = document.querySelector(".apple");
fruit.classList.add("tasty");

if (fruit.classList.contains("tasty")) {
  console.log("This fruit is tasty!");
} else {
  console.log("This fruit is not tasty!");
}
// This fruit is tasty
```
After going through a few sections on sabe.io, I started looking for an article that I've seen a few times on how to use pixels at root and rems for the rest of the site- except they said to use 100% at root and use SCSS mixins to better calculate the sizes of fonts - the reasoning was that by setting the font size at root to 10px, you are defeating what you are hoping to accomplish by using rems- which is accessibility. Using 10px at root, overrides what the user has their browser set to - I liked the reasoning and I was looking to implement this in my playground or invader tribute page to see how to implement this.

**Today's Links:**
1. [Sabe.io](https://sabe.io/classes/javascript/sets)

# Day 43: July 30, 2018

**Today's Progress**:
1. SCSS (60mins)
2. JavaScript (35mins)

**Thoughts** 
I found the article I was looking for yesterday regarding [EM vs REM vs PX](https://engageinteractive.co.uk/blog/em-vs-rem-vs-px), I'll research it further tonight. I implemented this idea with help from [Easy-Peasy REM Conversion with SASS](http://www.stubbornella.org/content/2013/07/01/easy-peasy-rem-conversion-with-sass/). I'm not sure if I like it yet and I'm not sure if I should continue to use pixels for margins and padding. Looking at [CSS-Tricks](https://css-tricks.com), it looks like they use REMs. Blast. Which makes me think my fontSize mixin may not work well. I need a function where I can input a pixel unit and it will convert it to rems. I'm thinking this article will be my next resource for this [Using pure Sass functions to make reusable logic more useful](http://thesassway.com/advanced/pure-sass-functions) In this article, (and using methods from Easy-Peasy REM Convertion), I found how to write a simple function to return a value:
```scss
@function calculateMargin($size) {
  $remSize: $size / 16px;
  @return #{$remSize}rem;
}
```

**Today's Links:**
1. [REM vs EM vs PX](https://engageinteractive.co.uk/blog/em-vs-rem-vs-px)
2. [Easy-Peasy REM Conversion with SASS](http://www.stubbornella.org/content/2013/07/01/easy-peasy-rem-conversion-with-sass/)
3. [Using pure Sass functions to make reusable logic more useful](http://thesassway.com/advanced/pure-sass-functions)
4. [Sabe.io](https://sabe.io/classes/javascript/localstorage-sessionstorage)

# Day 44: July 31, 2018

**Today's Progress**:
1. JavaScript (30mins)
2. PHP (75mins)

**Thoughts** 
Started with a lesson on regular expressions. It was a pretty good refresher. Will probably go back and try my hand at that website I previously used which had regular expression exercises.
Later I attempted to write a "share to twitter" button code in PHP. I got it to work but, I am getting warnings and errors in chrome... I'm not sure if I need to clear those errors and warnings or if I can ignore them.

**Today's Links:**
1. [Sabe.io](https://sabe.io/classes/javascript/regular-expressions)

# Day 45: August 8, 2018

**Today's Progress**:
1. JavaScript (15mins)
2. React (60mins)

**Thoughts** 
Finished the Sabe.io [JavaScript for the Web](https://sabe.io/classes/javascript) course. Pretty good course.
Later I started Wes Bos' [React for Beginners](https://reactforbeginners.com/) course. I already have Node but since I haven't updated I looked up how to [update Node via the command line](http://blog.teamtreehouse.com/install-node-js-npm-mac) (it's been a long time). 
I got through the first video, unfortunately, my node version was quite old ~6 and the recommended version for this series is ~9. Of course `brew upgrade node` resulted in node  v~10, a version with known issues dealing with the dependencies. I may end up installing `nvm` so I can switch node versions at will. This sitepoint [article](https://www.sitepoint.com/quick-tip-multiple-versions-node-nvm/) seems like a good resource.

**Today's Links:**
1. [Sabe.io](https://sabe.io/classes/javascript/errors-exceptions-debugging)
2. [How to Install Node.js and NPM on a Mac
](http://blog.teamtreehouse.com/install-node-js-npm-mac)
3. [Installing Multiple Versions of Node.js Using nvm
](https://www.sitepoint.com/quick-tip-multiple-versions-node-nvm)

# Day 46: August 10, 2018

**Today's Progress**:
1. Dev Environment (50mins)
2. React (35mins)

**Thoughts** 
Due to the issues with the installed node version yesterday, I decided to uninstall Node and install NVM. So far, I'm optimistic- the installation seems to have gone through well. I'll just have to check other projects and see if I need to delete the node_modules folder and re-install. I might take this a step further and install [AVN](https://www.npmjs.com/package/avn) - I felt that I want to have something that would be able to tell nvm what version of node a particular project requires. 
With all that done, I moved on from the first video (tooling) in Wes Bos' [React for Beginners](https://reactforbeginners.com/) course to create my first component.

**Today's Links:**
1. [Remove Node and NPM on OSX](https://gist.github.com/bradwestfall/2ca354323e30924c9099)
2. [The Best Way to Install Node.js](https://yoember.com/nodejs/the-best-way-to-install-node-js/)
3. [NVM](https://github.com/creationix/nvm#install-script)
4. [React for Beginners](https://reactforbeginners.com/)

# Day 47: August 11, 2018

**Today's Progress**:
1. React (35mins)
2. React (40mins)

**Thoughts** 
I worked on React for Beginners some more. I spent some time getting Emmet to work "better" with React JSX. Basically, when I was in "Reactland", Emmet was not autocompleting when I wrote a p + tab in order to create an opening and closing `<p></p>` tag. Additionally, if I typed storePicker.open, it wouldn't create a storePicker element with class (className) `<storePicker className='open'></storepicker>`. I figured this would have me deviate from what Wes was doing and additionally slow me down so, I researched this and got it resolved. Additionally, I added the [Scope Hunter](https://github.com/facelessuser/ScopeHunter) plugin to ST3 to help with this implementation (basically, without this if I wanted to add a variable or something outside of the scope, and hit tab, it would have created an opening and closing tag using that variable's name.)

**Today's Links:**
1. [React for Beginners](https://reactforbeginners.com/)
2. [Emmet expansions and className in React JSX](https://wesbos.com/emmet-react-jsx-sublime/)
3. [How to properly get a TAB trigger working with Emmet inside of JSX](https://gist.github.com/wesbos/2bb4a6998635df97c748)
3. [Scope Hunter]https://github.com/facelessuser/ScopeHunter

# Day 48: August 13, 2018

**Today's Progress**:
1. React (50mins)

**Thoughts** 
I re-started Wes Bos' React for Beginners course again today mostly so I could fork the repo and save the changes to my own repo.

**Today's Links:**
1. [React for Beginners](https://reactforbeginners.com/)

# Day 49: August 14, 2018

**Today's Progress**:
1. React (45mins)

**Thoughts** 
I am now caught up to where I was before I re-started the *React for Beginners* course. The basic building block for a component is as follows: 
```javascript
import React from 'react';

class ComponentName extends React.Component {
  render() {
    return (

    )
  }
}

export default ComponentName;
```
I spent some time researching how to create React snippets in Sublime. I haven't figured that out yet.

**Today's Links:**
1. [React for Beginners](https://reactforbeginners.com/)

# Day 50: August 15, 2018

**Today's Progress**:
1. Dev Environment (45mins)
2. React (30mins)

**Thoughts** 
I updated my node environment at work to use nvm. Going through the process a 2nd time still took some digging 🤓
In React for Beginners, I covered *Stateless Functional Components* (syntax below). Basically, if all your React Component does is get rendered, a Stateless functional component should be used instead.
```javascript
import React from 'react';

const Header = props => (
  <header className="top">
    <h1>Catch
    <span className="ofThe">
      <span className="of">of</span>
      <span className="the">the</span>
    </span>
    Day</h1>
    <h3 className="tagline">
      <span>{props.tagline}</span>
    </h3>
  </header>
);

export default Header;
```

**Today's Links:**
1. [Remove Node and NPM on OSX](https://gist.github.com/bradwestfall/2ca354323e30924c9099)
2. [The Best Way to Install Node.js](https://yoember.com/nodejs/the-best-way-to-install-node-js/)
3. [nvm](https://github.com/creationix/nvm#install-script)
4. [Set default node version with NVM](https://eric.blog/2016/08/23/set-default-node-version-with-nvm/)
5. [React for Beginners](https://reactforbeginners.com/)

# Day 51: August 19, 2018

**Today's Progress**:
1. Dev Environment (120mins)

**Thoughts** 
Today I worked on my dev environment to restart Wes Bos' [ES6 For Everyone](https://es6.io). I decided that last time I took this course, I overwrote a lot of useful examples. I also spent a lot of time saving, switching to chrome, and refreshing the page. I decided to incorporate BrowserSync to make development faster and I also learned a little more about BrowserSync to make switching directories and files quicker.
```javascript
gulp.task('serve', ['sass'], function() {
  browserSync.init({
    server: {
      directory: true,
      baseDir: "./"
    },
    files: "styles.css",
  });

  gulp.watch("./scss/*.scss", ['sass']);
  gulp.watch("./*/*.js").on('change', browserSync.reload);
  gulp.watch("./*/*.html").on('change', browserSync.reload);
});
```
I'll concurrently work on this course and the React course.

**Today's Links:**
1. [ES6 For Everyone!](https://es6.io)
2. [BrowserSync - Server](https://browsersync.io/docs/options#option-server)

# Day 52: August 21, 2018

**Today's Progress**:
1. ES6 (55mins)
2. React (25mins)

**Thoughts** 
In ES6 for Everyone, I got through section 1 (again). Basically this one covers `var`, `let`, and `const`. Wes talks about two different ways to deal with variables in ES6 and I think I agree with his version to use `const` by default and `let` when necessary, `var` is not used in this method. `const` is not about immutability as evidenced from the example below, object values can be updated.
```javascript
const person = {
  name: 'West',
  age: 28
}
console.log(person);

person.name = "Wesley";

console.log(person);
```
In React for Beginners, I worked on adding the router and adding routes. Also, I imported a helper function. 
Overall, I feel pretty good with the material I covered today. I feel pretty comfortable with using ES6 syntax and I felt that I was able to import some things into React before Wes mentioned them. Still a beginner but at least I'm comprehending what I need to do.

**Today's Links:**
1. [ES6 For Everyone!](https://es6.io)
2. [React for Beginners](https://reactforbeginners.com/)

**Today's Progress**:
1. React (44mins)
2. Git (10mins)

**Thoughts** 
Today in React for Beginners I added a property to the StorePicker which would use the value from the form input to route us to the specific store's url. I had to add a `ref` to the input in order to get the value from the input.

**Today's Links:**
1. [React for Beginners](https://reactforbeginners.com/)

# Day 52: September 2, 2018

**Today's Progress**:
1. React (65mins)
2. ES6 (10mins)

**Thoughts** 
Today, I worked on setting state in React. I also used props.
In ES6 for Everyone, I created HTML using Template Literals.
In the example below, I have basic information about a song in the variable `song` and I display that information using the information in `songMarkup`. I set up a ternary operator to display the text for a featured artist when that data is available. Lastly, I apply that content to the body.
```javascript
const song = {
  name: 'Dying to Live',
  artist: 'Tupac',
  featuring: 'Biggie Smalls'
}

const songMarkup = `
  <div class="song">
    <p>
      ${song.name} - ${song.artist}
      ${song.featuring ? `(Featuring ${song.featuring})` : ""}
    </p>
  </div>
`;

document.body.innerHTML = songMarkup;
```

**Today's Links:**
1. [ES6 For Everyone!](https://es6.io)
2. [React for Beginners](https://reactforbeginners.com/)

# Day 53: September 5, 2018

**Today's Progress**:
1. Project (45mins)

**Thoughts** 
Today I started working on one of the Free Code Camp [projects](https://learn.freecodecamp.org/responsive-web-design/responsive-web-design-projects/build-a-survey-form). I'll continue to work on my tutorials but I also wanted to get going on some actual projects. I'll continue to knock these out as I learn via the React and ES6 courses.

**Today's Links:**
1. [FCC-Survey](https://github.com/adamgonzls/fcc-survey)

# Day 54: September 12, 2018

**Today's Progress**:
1. Project (75mins)

**Thoughts** 
I continued to work on my survey project. I will most likely finish this project this week, then I can move onto another project. I updated the markup and styles for the inputs. I could keep this project very basic but I wanted to add something so this is something I'm still proud to show off. I also added sourcemaps to this project. Other than helping me track my SCSS, I think this will be useful as a boilerplate for future projects.

**Today's Links:**
1. [FCC-Survey](https://github.com/adamgonzls/fcc-survey)

# Day 55: September 13, 2018

**Today's Progress**:
1. ES6 (60mins)
2. Project (25mins)

**Thoughts** 
Worked through some videos on template strings and tagged templates.
I worked on completing the user stories on my survey project. I still feel like the page looks a little ugly for my taste but style is not the goal of this project. I will complete this project this weekend.

**Today's Links:**
1. [ES6 For Everyone!](https://es6.io)
2. [FCC-Survey](https://github.com/adamgonzls/fcc-survey)
