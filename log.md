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