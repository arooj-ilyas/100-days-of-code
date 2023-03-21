# 100 Days Of Code - Log

For the next 16 weeks I will be taking a course with the School of Code 5 days a week to become a full-stack software developer. In this log I am going to track concepts I will be learning, as well as writing down workshops I will be partaking in and code snippets/links to show my days work!

### Day 1: September 26, 2022

**Today's Progress**: Computational Thinking and Pair Programming

**Thoughts:** Worked on a CSS Diner task to play with the idea of Pair Programming and understand how selectors and attritubes work. I feel like I am slowly getting better at it and understanding how CSS works. I have never come across pair programming before and CSS is still very new for me, but I managed to recall some of what I had learnt in the introduction session with School of Code last week and applied it to the task.

**Link to work:** https://flukeout.github.io/

### Day 2: September 27, 2022

**Today's Progress**: Git Rhythm

**Thoughts**: I understood the functionality of GitHub better than I did before and became familiar with the idea of using git functions such as init, add, commit, status, log. I did struggle with using the git clone, push and pull but I think with practice I will get better at it. I feel quite good about using IDE's like VS Code and have managed to correctly set up bash on my mac.

**Link(s) to work**: https://github.com/arooj-ilyas/bc13_git_demo/commits/main

### Day 3: September 28, 2022

**Today's Progress**: Introduction to JavaScript

**Thoughts** Today I finally became much more familiar and used to the idea of Git Pull --> Git Add --> Git Commit --> Git Push. I was introduced to the basics of JavaScript, how it was formed and the 5 pillars of programming in JS. Worked in Pair Programming to link HTML and JS files in VS Code, then went on to complete workshops tackling creating variables, if and else-if loops. Found this quite hard and took quite a while to get my head around, definitely need further practice here.

**Code Snippet:**

```
let userPassword=prompt("please enter password");

if (userPassword === "myPassword1!") {
    console.log (userPassword);
    alert("I'm secretly an alien");
}

else if (userPassword !== "myPassword1!") {
    alert("WRONG! Try again");
    count = count + 1;
 }
```

### Day 4: September 29, 2022

**Today's Progress**: JavaScript (Objects & Arrays)

**Thoughts** We began the day with recapping what we learnt yesterday about JS variables and functions. Then we went on to learn further about objects and arrays. Learnt how to select properties within objects and how to create, select and update arrays. Memorised that the correct formulation of a for loop is Declaration, Condition, Updater. Definitely still need more practice with creating for and while loops with arrays and objects inside.

**Code Snippet:**let index=0

```
while(index<englishNumbers.length){
     console.log(englishNumbers[index])
     index++;
}

let index=0
 for (index=0;
     index<englishNumbers.length;
     index++){
         console.log(englishNumbers[index])
}
```

### Day 5: September 30, 2022

**Today's Progress**: 💥 Rock, paper, scissors game - Hackathon Friday!!

**Thoughts** Today was a tough one! We had 7 tasks to work through to create a rock paper and scissors game with an user input function against a computer. The tasks included using Logic, creating a function with if statements, adding user input, prompts, alerts, using a Math.random() function for the computer player, creating a game loop with a while function to confirm it works and getting the player to input their name using a prompt. I only managed to complete 4/7 tasks but very proud of my efforts and ability to get that far considering I would not have even been able to write a single line of code last week!

**Code Snippet:**

```
let player2="paper"
let player1=prompt ("rock, paper or scissors")

function getWinner(player1, player2) {
    if (player1 === "rock" && player2 === "paper"){
    alert("Player2 wins!");
    return -1;
}

// lots of other if statements of all possible outcomes

let result = getWinner(player1, player2)
  console.log(result)
```

### Day 6: October 1, 2022

**Today's Progress**: Week 1 recap & review... ✅

**Thoughts** After a long week of learning a lot of new concepts with HTML, JavaScript and GitHub, I decided to spend today taking a bit of a break from learning anything new and instead spent the day recapping what I learnt this week before putting it into practice and attempting the remaining 3 tasks of the Hackathon. I reviewed what I learnt about objects, functions and arrays and how to create properties within objects and arrays. Also wanted to review that I fully understand how to clone down git repositorys and push/pull as that is going to be a vital part for the remainder of my School of Code course.

### Day 7: October 2, 2022

**Today's Progress:** FCC JavaScript Basics & week recap

**Thoughts:** Today I managed to get 70% through the FreeCodeCamp course for Basics of JavaScript, this helped me so much in terms of solidifying what I've learnt this week and really making sure I fully comprehend the basics so that I can tackle the workshops next week with a better base understanding! Feel much more familiar now with create if/else if statements and different AND/OR operators. Also learnt that there is a difference between the == (equality operator) and === (strict equlaity operator). Completed task 5/7 for the Hackathon and learnt more about math.Random and math.Floor to return random integers.

**Code Snippet:**

```
let player2 = Math.floor(Math.random() * 3)
    if (player2===0) {
        player2="rock"
    }
 // repeated with if statements for outcome of scissors and paper
```

**Link to work**: https://www.freecodecamp.org/fccc2498d63-cfb8-47dc-9a8a-e4da663cd78c

### Day 8: October 3, 2022

**Today's Progress**: CodeWars and DOM's ⚔️

**Thoughts** Start of Week 2 with the School Of Code - began the day reflecting on last week with some retrospective feedback on pair programming using the 'Stop, Start, Continue' feedback format. Signed up for CodeWars and completed 2 Level 8 Kata's! Then went on to learn all abot DOM's and how to use JavaScript to manipulate a pages CSS and HTML. Familirised myself more with for loops and learnt about querySelector, querySelectorAll, .textContent, .appendChild and .removeChild

**Code Snippet:**

```
let tips = [
  "Keep your pennies is a glass jar",
  "Save money buy not eating!",
  "Don't let your partner know...",
];

//Task 4 - create an element
// select the tips list, this is called "tips"
    // create a variable for the existing list
    // create a variable for the newTips which we will add onto the existing list
// create a for loop to loop through the array of tips
// add extra tips to the existing #tips-list using .textContent
// append using .appendChild

let ul = document.querySelector('#tips-list');
let newTips = document.createElement('li');

for (let i=0; i<tips.length; i++); {
newTips.textContent = tips;
ul.appendChild (newTips);
}
```

**Link to CodeWars profile**: https://www.codewars.com/users/arooj-ilyas

### Day 9: October 4, 2022

**Today's Progress**: DOM's - Event Listeners and Refactoring

**Thoughts:** Worked on building on yesterday's knowledge of DOM's using querySelector to add an event listener ontop of specific commands - e.g. clicking a specific button to trigger a new textContent. Grasped this pretty well and was able to work through a workshop involving addEventListener with the relative callback to various events ("keyup", "click", "shiftKey"). In the afternoon, worked on refactoring our rock, paper, scissors console application from Friday's hackathon and turn it into an interactive HTML page. This was a lot more difficult and time constraints meant I was unable to complete it. However, my partner and I worked really well in pair programming to break down and devise a plan for how to tackle the task. We managed to create variables with buttons using querySelector and functions for buttons with click eventListeners and handleClick callbacks for task 1.

**Code Snippet:**

```
const button = document.querySelector("#click-me");
button.addEventListener("click", handleClick);

//TASK 1 - created an if statement with event.shiftKey
//Order of everything matters!

function handleClick(event) {
  // If clicked, console log you clicked me!
  // If shift key pressed, change the inner text of the button to be NAILED IT
  console.log("You clicked me!")
  if (event.shiftKey) {
    button.textContent = ("NAILED IT!!!");
  }
}
```

### Day 10: October 5, 2022

**Today's Progress:** Async functions, setTimeout, setInterval, API's

**Thoughts:** Focused on the difference between async and sync functions! It was so interesting today integrating what we learnt about asynchronisity with API's - a phrase I had always heard of but never truly knew what it entailed. Learning that an API is the connection between two compute rprogrammes and that fetch() is how we can access this resource from the internet. This fetch() command will send out a request and return a promise which is why we must always await a promise!! We can't know how long this will take so a setInterval won't't work, we must wrap it in an async function for it to be true.

**Code Snippet:**

```
async function getquote() {
    let response = await fetch ("https://www.boredapi.com/api/activity");
    let data = await response.json();
    console.log(data);
    h1.textContent = data.activity;
    console.log(h1.textContent);
    let h2 = document.querySelector("#type")
    h2.textContent = data.type;
}
```

### Day 11: October 6, 2022

**Today's Progress:** 🧠 Mindset Thursday, Navigating Data, Presenting Research

**Thoughts:** Today was a mindset day, I took a personality test the night before and spoke amongst my peers of how various personality types can work together and potentially clash in working environments. Understanding these different personalities better, as well as understanding which category I fall into, will aid me in being able a better team player where I can allow my strength to shine in a working culture and also know when to ask for help. Completed a small workshop on navigating data and solidifed my understanding of selecting specific objects, properties and arrays from large data sets in DOM. Worked thereafter in a small group of 4 on individually researching the various devTools and presenting this in a short 4 minute presetnation. I definitely need to brush up on my public speaking skills but found the task a good way to bring me out of my comfort zone and learn something new.

**Code Snippet:**

```
// Task 1
// Complete the function so it returns Liz Rios' favourite fruit

function lizRiosFavFruit() {
  return SOCBook.data.people[10].favoriteFruit;
}
```

### Day 12: October 7, 2022

**Today's Progress:** 💥 Fetch - Hackathon Fridays!!

**Thoughts:** Today we worked in pair programming on a Fetch Hackathon where my partner and I selected a trivia API to create our very own game! We created a plan of what functionalities it to include and filtered the API link to match this - e.g. a true/false quiz on the category of music at a medium difficulty level. We broke down what we wanted to do, made a checklist and then began coding. Within the code we utilised async functions, fetch, await, JSON, selecting and updating properties in an object such as textContent/innerHTML, eventListeners, callback functions, if statements and much more. We also went on to use our limited existing CSS knowledge to spruce up the look of the game after lots of googling. Definitely want to focus more on learning to clean code and still so many more JS functions to learn but really proud of how far I've come so far :)

**Code Snippet:**

```
//fetch the API from the internet
let h2Question = document.querySelector("#TrivQuestion");
let data

//create an async function with a fetch() and JSON (make sure to await)
async function getQuestion() {
    const response = await fetch ("https://opentdb.com/api.php?amount=10&category=12&difficulty=medium&type=boolean");
    data = await response.json();
    // console.log(data);
    let results = (data.results[0].question);
    // console.log(results)
    h2Question.innerHTML = results
    return data
    //console.log(h2Question.textContent);
}

//create a function for the buttons made which would have event listeners attached
function handleClick(move) {
    let correctAnswer = data.results[0].correct_answer;

    if (move === correctAnswer) {
        p.textContent = "Correct Answer!!"
    } else
        p.textContent = "Incorrect Answer!!"
}
```

### Day 13: October 8, 2022

**Today's Progress:** Saturday - Rest and Relax 🧖🏽‍♀️

**Thoughts:** Today for me was all about learning the importance of balance. Wanted to take a break from my screen and resume my life outside of coding. Aim was to reset and recoup myself after an intense two weeks! I spent the day instead catching up with friends & family and organising through the documents on my computer - my desktop was starting to look worse for wear with the number of screenshots

### Day 14: October 9, 2022

**Today's Progress:** Week 2 recap tasks... API's ✅

**Thoughts:** Given 3 tasks to complete summarising what we went through in week 2 at the School of Code. Task 1 jogged my memory on creating functions and for loops - I found that I have still not fully grasped the concept of the different types of for loops and for loops in an array so definitely need to spend some extra time revising this. Task 2 and 3 went through using setInterval, fetching API's and manipulating the DOM with buttons and add eventListeners.

**Code Snippet:**

```
for (let celeb of celebs) {
  if ((celeb[0].startsWith('A')) || (celeb[0].startsWith('E')) || (celeb[0].startsWith('I')) || (celeb[0].startsWith('O')) || (celeb[0].startsWith('U'))) {
    vowelCelebs.push(celeb)

    console.log(vowelCelebs)
  }
}
```

### Day 15: October 10, 2022

**Today's Progress:** 🏃🏽‍♀️ Week 3 commenses! Agenda: UI/UX

**Thoughts:** Worked on a !Lightening challenge with the aim of creating the Google landing page 'blindly' coded to demonstrate the importance of feedback. Given I haven't looked at HTML in depth since day 2/3 at SoC, I felt a bit underprepared for this task - unsure of the differences between `<div> and <section>` tags so I definitely want to spend some time revisiting this on FCC!

But, this task tied nicely into what we did for the remainder of the day - learning more about AGILE methodologies and the 4 values of AGILE: Individuals and Interactions, Working Software, Customer Collaboration, Responding to Change. Also learnt about the differences between UI and UX and that Good UI ≠ Good UX, but both are equally as important!!

### Day 16: October 11, 2022

**Today's Progress:** 5 Princples of Design Thinking & Intro to CSS

**Thoughts:** Learnt about the 5 pillars of Design Thinking today including Disney's Ideation Method for step 3 Ideate - dreamer, realist and critic. Began to understand that design is never a linear process. It is based on User Centred Design (USD) and thought of as an iterative process. We worked in our pairs to create our very own bootcamp idea and the UX jounrney we'd like our users to go through in the 'application' process.

In the afternoon, we went on to link what we learnt about UX and Design Thinking to play around with some CSS. Fun workshop where we reassigned existing CSS variables in the global scope using the :root Selector. After, we used our existing knowledge of manipulating DOM in JS to create a button function which could toggle a page to a 'dark-mode' when clicked. Then worked on some more level 8 kata's in CodeWars in my spare time where I learnt about the charAt() method.

**Code Snippet:**

```
:root {
  --primary-colour: rgb(197,231,147);
  --secondary-colour: antiquewhite;
  --text-colour: black;
  --header-size: 24px;
  --main-text-size: 18px;
  --border-radius: 10px;
}
```

### Day 17: October 12, 2022

**Today's Progress:** UI Design & CSS Organisation/Specificity

**Thoughts:** Today we covered different principles and elements of UI Design; delved into colour theory and tools that exist to support UI developers with this such as Coolors and Palletton. Also looked into some other UI prototyping tools for wireframing such as Figma. Using the bootcamp my pair and I brainstormed in yesterday's UX session, we progressed to the UI stage and created low and high fidelity wireframes!

Learnt further about how CSS plays a vital role in UI and looked into CSS specificity and the specificity hierarchy.

### Day 18: October 13, 2022

**Today's Progress:** 🧠 Mindset Thursday, CSS Flex, UX Tools!

**Thoughts:** Started the day with a nice mindset session on the types of listeners that exist and which one I am. Covered the 'Flex' propterty in CSS as well as learning some new commands like justify-content allign-items, gap and flex direction. I still struggle with CSS and do not fully understanding all the possibilities. I will probably spend some time covering this myself in FreeCodeCamp.

Also spent some time in the afternoon researching UX tools such as empathy and journeys maps, user interviews and information architechture (but user persona for my team specifically). Had a guest talk from Paavan over at AND Digital and presented our findings to the other teammates - slowly but surely starting to feel a bit more comfortable with public speaking

**Code Snippet:**

```
// CSS
main {
	display: flex;
	flex-direction: column;
	justify-content: center;
	align-itens: center;
	background-color: brown;
	height: 100vh;
}

main > div {
	background-color: yellow;
	heigh: 50px;
	width: 50px;
	border: 1px solid;
}

main > div.button {
	display: flex;
	justify-content: center;
	allign-items: center;
}
```

### Day 19: October 14, 2022

**Today's Progress:** 💥 Design - Hackathon Fridays!!

**Thoughts:** Worked on a day-long Hackathon task of using the bootcamp idea my partner and I brainstormed earlier this week to go through the UI UX process of bringing the idea to fruition. We began with reviewing what we learnt this week and making a plan. The focus of this task was on planning, wireframing, designing and iterating before building the MVP in HTML and CSS.

My partner and I were able to gather some of the tasks we completed earlier in the week and finalise them. By the end of the day we were able to present a brainstorming session in Miro, 2 user personas and user stories, chose a colour scheme, created a logo, finished the low-fidelity and high-fidelity wireframes of the landing page and user journey navigating through the page in Figma. We were also able to make a start to creating our landing page in HTML and CSS but kept the focus of the day on designing. We were able to Google and create the NavBar in CSS and use some of the CSS variable and specificity law's we learnt earlier in the week and apply it to our page. This is definitely a project I will continue to develop on the side as I progress through the course.

**Code Snippet:**

```
:root {
    --primary-color: #3E6896;
    --secondary-color: #5F2C82;
    --background-color: white;
    --font-type: "Roboto",sans-serif;
    --third-color: #D9D9D9;
}

.navbar {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 20px;
    background-color:var(--background-color);
    color: var(--primary-color);
    font-family: var(--font-type);
```

### Day 20: October 15, 2022

**Today's Progress:** Saturday - Rest and Relax 🧖🏽‍♀️

**Thoughts:** Taking a break from my screen and focusing on life otuside of code... although I did attempt 1 code war and levelled up to Level 7 KYU!

**Code Snippet:**

```
//8 kyu - The Feast of Many Beasts
function feast(beast, dish) {
  let beastFirstLetter = beast.charAt(0);
  let beastLastLetter = beast.charAt(beast.length-1);
  let dishFirstLetter = dish.charAt(0);
  let dishLastLetter = dish.charAt(dish.length-1);

  if (beastFirstLetter===dishFirstLetter && beastLastLetter===dishLastLetter) {
    return true
    } else
      return false
}
```

### Day 21: October 16, 2022

**Today's Progress:** Week 3 Recap Task... Design ✅

**Thoughts:** Worked on a recap task today where I was asked to create the user persona, story and journey for individuals browsing my Portfolio site - then do some lo-fi and hi-fi wireframing! Really enjoyed exploring Figma some more, I can really see how powerful of a tool this could be in UX.

In prep for next week where we tackle Node.Js, I read a 'Clean Code Guide' written by School of Code to familiarise myself with why coding practices are important, why formatting my code is important, and how I can achieve well formatted, easy to understand code.

**Code Snippet:**

```
//Difference between 'Clean' and 'Messy' code

//Messy
let someStuff = ["Bananas", "Bread", "Cheese", "Crisps", "Milk"];

//Clean
let shoppingList = ["Bananas", "Bread", "Cheese", "Crisps", "Milk"];
```

### Day 22: October 17, 2022

**Today's Progress:** 🔙🔚 Backend Week - Debugging, CJS in Node.js and Local Modules

**Thoughts:** Starting off the week going through the common practices when debugging, how to approach it and why readable code is so important. Then went on to learn about Node.JS and why we use it. Learnt about the v8 JavaSCript Engine,what modules are and the different systems that exist (CJS-Common JS and ESM-ECMA Script Module). Finished the day with a light workshop where we practiced importing and exporting modules in CJS. This is all still very new to me so definitely will require a lot more hands-on practice and additional research in my own time before I understand node.js and modules better!

On a side note, I am still really struggling to get to grips with the difference between for... of and for... in loops, but hoping my mentor, some FreeCodeCamp practice and codewars can help me with this.

**Code Snippet:**

```
//in bootcamper.json seperate files has an array with bootcamper info
//in bootcamper.js file, create the pickRandomBootcamper variable to select a random bootcamper

function pickRandomBootcamper(bootcamperData) {
const random = Math.floor(Math.random()*2);
  // console.log("test", bootcamperData);

const user = bootcamperData[random];
  // console.log(user);

if (user.hasPets === false) {
  return `Hi, my name is ${user.firstName} ${user.lastName}. I'm ${user.age} years old and I have no pets.`
  }else{
  return `Hi, my name is ${user.firstName} ${user.lastName}. I'm ${user.age} years old and I'm a pet owner.`
};

module.exports = {pickRandomBootcamper};

//in app.js file, require the export
const {pickRandomBootcamper} = require("./bootcamper.js");
```

### Day 23: October 18, 2022

**Today's Progress:** 🔙🔚 Node.js Core Modules and Third Party Modules

**Thoughts:** Covered destructuing and how that can help when working in node.js. Afterwards I went on to learn more about the different types of modules that exist in node.js: Local, Core and Third Party. One workshop on Core Modules taught me how to Read and write to files using the fs module, use uuid (a third-party package) to generate unique ids and serialize/deserialize data using the JSON.parse and JSON.stringify methods. Second workshop on Third Party Modules gave us an intro to Express, use NPM init and set up our own local server!

On the side I am continuing to work on my Portfolio wireframes I created in Figma over the weekend and testing various designs before settling!

**Code Snippet:**

```
const fs = require("node:fs/promises");
const path = require("node:path");
const { v4: uuidv4 } = require("uuid");
const fileName = "quotes.json";
const filePath = path.resolve(__dirname, fileName);
// console.log(filePath);

  //Task: Add and save a new quote
	//take in quote text
  //create a quote object
  //assign unique id to object
  //save the quote object to quotes.json at the end of the array
  //return newly created object

async function addQuote(quote) {
  quote = {
    id: uuidv4(),
    quoteText: quote
  };
  const JSONquote = await fs.readFile(filePath);
  const quotes = JSON.parse(JSONquote);
  quotes.push(quote);
  const JSONData = JSON.stringify(quotes);
  await fs.writeFile(filePath, JSONData);
  return quote;
};
```

### Day 24: October 19, 2022

**Today's Progress:** 🔙🔚 Node Express, CRUD & PostMan!

**Thoughts:** Today I was introduced to CRUD operations, HTTP verbs and Postman for the first time all in one day! By the end of the day I was able to successfully build a REST API using Node.js and Express, create API endpoints allowing the user to create, read, update and delete a resource AND use Postman to make HTTP requests to test API endpoints! All new concepts to me I had never heard of at the start of the week and today is only Wednesday.

Definitely need to spend some further time cementing in everything I learnt but the mystical world of backend is slowly but surely starting to make more sense... 💭

**Code Snippet:**

```
const express = require("express");
const app = express();
const port = 3000;

const {
  getQuotes,
  addQuote,
  getRandomQuote,
  editQuote,
  deleteQuote,
} = require("./quote.js");

//create a get route handler with path api/quotes
//await the async function
//add an if statement, if the type in the request is ?=random then return getRandomQuote()
//to select type use req.query.type

app.get("/api/quotes", async function (req, res) {
  //const JSONquote = require("getQuotes")
  if (req.query.type === "random"){
    res.json(await getRandomQuote());
  }else{
    res.json(await getQuotes());
  }
});

//create a patch route handler with path /api/quotes/:id

app.patch("/api/quotes/:id", async function (req, res) {
  // call the updateQuote function with the values that are passed in the PATCH json data
  let obj = await editQuote(req.params.id, req.body.quoteText);
  res.status(201).json(obj);
});
```

### Day 25: October 20, 2022

**Today's Progress:** 🧠 Mindset Thursday, 🔙🔚 Middleware, Routes & Models and Linking Backend to Frontend!

**Thoughts:** Started the day with another mindset session with discussion on Inner Critics and Inner Champions! Learning to retrain my mind to use my perfectionist inner critic as a voice of encoragement and motivation. Shortly after, focus shifted to learning about middleware and why backend developers model and route their codes. We then put this into practice using the RESTful API workshop we completed earlier in the week and worked on routing and modeling the existing data into seperate files. Also worked on understanding how backend connects to front end and using the express.static middleware to link our models and routes to the static HTML, JS and CSS files. Challenging day, lots of information - I struggled a lot with understanding the purpose of middleware, routes and models but practice makes perfect!

**Code Snippet:**

```
const express = require("express");
const morgan = require("morgan");
const app = express();
const port = 3000;

app.use(express.json());

//use morgan (third party module)
app.use(morgan("dev"));

//tell express to serve static files
app.use(express.static("./public"));

//add middleware before app.get request handler
app.use(function(req, res, next) {
  console.log("This is my middleware");
  next();
});

//Middleware, system time
app.use(function (req, res, next) {
  req.requestTime = new Date().toLocaleString();
  console.log(req.requestTime);
  next();
});
```

### Day 26: October 21, 2022

**Today's Progress:** 💥 Build a Back End - Hackathon Friday!!

**Thoughts:** Put together everything we learnt throughout the week. Finally stating to feel a bit more comfortable with creating async funcitions, if statements and for loops. We were tasked with creating a server that functions as an API to display various recipes! Goal was to get all the CRUD routes up for GET, POST, PATCH and DELETE running in the router so that the server listens for requests and serves test/example responses. Also required was to create functions which interact with the recipe collection such as getRecipes, getRecipesByID, createRecipe, updateRecipByID and deleteRecipeByID. By the end of the day, in pair programming, my partner and I succesfully got half way through and were able to pull get and post requests from our server! I definitely struggled this week understanding everything that was going on but a lot of information has been asborbed and I will continue to work on my recipes API until all requests from the HTTP methods can be made!

**Code Snippet:**

```
// UPDATE A RECIPE BY ID
async function updateRecipeByID(id, updatedRecipe) {
  const recipeJSON = await fs.readFile (filePath);
  const recipe = JSON.parse(recipeJSON);
  // console.log(`uR: ${updatedRecipe}, id: ${id}`);

  for(let i=0; i < recipe.length; i++) {
    // console.log(`this is the recipe ${recipe[i]}`)
    // console.log(`ID here -> ${recipe[i].id}`);
    if(id === recipe[i].id){
      recipe[i] = updatedRecipe;
      return updatedRecipe;
    }
  }
}
```

### Day 27: October 22, 2022

**Today's Progress:** Saturday - Rest and Relax 🧖🏽‍♀️

**Thoughts:** Spent the day away from the screen as has been my tradition for the last 4 weeks! Can't believe I am already a month into my coding journey. I realise that as important as the theoretical and practical side of practicing code is for my journey, so is this side where I can summarise my knowledge and articulate it in a journal. Sometimes with the hussle and bussle of the week I tend to forget to update my 100daysofcode logs but weekends are the time I take out to reflect back on what I learnt this week and write down my thoughts and new knowledge here :)

### Day 28: October 23, 2022

**Today's Progress:** Week 4 Recap Task... Backend & API Routes ✅

**Thoughts:** The jigsaw puzzle that is backend is slowly starting to be build and things are slowly starting to make more sense. This weeks recap task wanted us to create some API CRUD routes using the HTTP methods we covered earlier in the week; get, post, patch and delete. I coded each route handler in the routes/users.js file and each helper function in the models/users.js file, then tested it in postman with the correct URL path for the function to make sure it's all performing as told! I still find the 'patch' handler a bit difficult and will need to spend more time going over this but feeling a lot more confident than I did earlier in the week and this will onlu continue as time goes on!

One thing I am really happy about is that for of and for in loops are starting to make MUCH more sense to me. I can see why we use them and where and was even able to write one in my API without any help! A very proud moment for me as I struggled with this a LOT at the start of the course :)

**Code Snippet:**

```
async function updateUserByID(id, updatedUser) {
  const users = await getUsers();
  for (user of users) {
    if (user.id === id) {
      if (updatedUser.first_name) user.first_name = updatedUser.first_name;
      if (updatedUser.last_name) user.last_name = updatedUser.last_name;
      if (updatedUser.email) user.email = updatedUser.email;
      if (updatedUser.catchphrase) user.catchphrase = updatedUser.catchphrase;
      await fs.writeFile(filePath, JSON.stringify(user));
      return user;
    }
}
}
```

### Day 29: October 24, 2022

**Today's Progress:** Introduction to Databases and SQL

**Thoughts:** Learning another new language to build on our Backend knowledge - this time, SQL! Today we covered what a database is, how it can be stored and the different types. We covered relational vs non-relational and what a 'query' actually symbolises. We dived further into relational databases and completed an Intro to SQL lesson on db.fiddle. From there, we pair programmed to play around with using the CRUD operations in SQL with the select query, where clause, insert into statements, update and delete! This was my first ever time hearing and learning about SQL so it was a lot of new information for me. We also briefly covered Schema for SQL and experimented making our own.

**Link to work:** https://www.db-fiddle.com/f/dg2RJvBX1aZda3ECwQUSoe/81

**Code Snippet:**

```
CREATE TABLE users (
  user_id INT GENERATED ALWAYS AS IDENTITY PRIMARY KEY,
	//INT means 'integer', aka type (number)
	//GENERATED ALWAYS... automatically assigns a unique number to a column and errors if you try to update yourself

  name TEXT,
  email TEXT,
  username TEXT
);

INSERT INTO
  users (name, email, username)
VALUES
(
  'Ben',
  'ben@ben.com',
  'MrBenBot'
),
(
  'Chris',
  'chris@chris.com',
  'TheBoss'
)

INSERT INTO users (name, email, username) VALUES (’Tao’, ‘tao@tao.com’, BegoniaFan’);
SELECT * FROM users;

UPDATE users SET username = 'Ta-yoyo- WHERE user_id = 2
RETURNING username;
SELECT * FROM users;
```

### Day 30: October 25, 2022

**Today's Progress:** SQL Joins & Murder Mystery Game! 🕵🏽🔍

**Thoughts:** Today was probably one of the most fun days I've had on the course! Started off the day with an amazing talk by a SoC Alumni on using our time here to learn how to learn, value the power of teamwork and embrace pair programming as it will come in handy when entering the workspace also! From there we continued to learn more about SQL, this time the different types of 'Joins'. We put what we learnt into practice with the PostgreSQL Joins and SubQueries Exercises and SQL Murder Mystery Game. Came across so many new concepts whilst completeing these, including but not limited to: SELECT DISTINCT, (AND, OR, NOT, BETWEEN) CONDITIONS, ORDER BY, LIKE, ALIASES, CASE WHERE

**Code Snippet:**

```
SELECT firstname || ' ' || surname AS member, name AS facility,
CASE
	WHEN cd.bookings.memid = 0 THEN (guestcost*slots)
	WHEN cd.bookings.memid > 0 THEN (membercost*slots)
	END AS cost
FROM cd.members

JOIN cd.bookings ON cd.bookings.memid = cd.members.memid
JOIN cd.facilities ON cd.facilities.facid = cd.bookings.facid

WHERE  cd.bookings.starttime BETWEEN '2012-09-14 00:00:00' AND '2012-09-14 23:59:59' AND
(
	(cd.bookings.memid = 0 and cd.bookings.slots*guestcost > 30) or
	(cd.bookings.memid != 0 and cd.bookings.slots*membercost > 30)
)

ORDER BY cost DESC;
```

**Link to exercises completed:** https://pgexercises.com/questions/joins/, https://mystery.knightlab.com/index.html#experienced

### Day 31: October 26, 2022

**Today's Progress:** First SQL Database with ElephantSQL 🐘 and Connection Pools 🏊🏽‍♀️

**Thoughts:** Huge milestone today and a LOT of learning! Today I was able to set up a connection pool between a database created in ElephantSQL on books & authors and a rest API's through utilising node-postgres to interface with the PostgreSQL database. With a combination of; npm packages, requiring and exporting modules, async funtions, plenty of awaiting (pun intended) and environmental variables, I was able to use my understanding of SQL queries from this week to create a model function for 'GetBooks()' and 'searchBooksByAuthor()'! Today was incredibly challenging and I learnt a lot of new concepts which I definitely need to build my understanding on, but I feel positive that I am on the right track. I'm excited to learn more about this powerful concept and put together the final puzzle pieces that are the jigsaw of Backend. My mentor and pair programming partner have been my biggest supporters this week and I am feeling very grateful for them both. 🫶🏽

Side notes: it was really interesting today to learn about the reason we use environmetal variables and the essential layer of security they add, definitely something I knew nothing about prior to today and want to read up on! Also, I spoke with my mentor and made a mental plan to spend the new few weeks working on building my portfolio and finding a side project 🤓

**Code Snippet:**

```
async function searchBooksByAuthor(searchTerm) {
  // Query the database and return all books that have an author name matching the searchTerm
	// Use the query function to filter books with author name (last name for now)
	// Await!
	// Collect what query returns in the variable (variable: result)
	// Console.log and return the relevant part of the result

  let result = await query (
  `SELECT *
  FROM books
  INNER JOIN authors
  ON books.author_id = authors.id
  WHERE last_name = $1;`, [searchTerm]);
  //console.log (result);
  let bookByAuthor = result.rows[0];
  return bookByAuthor;
}
```

### Day 32: October 27, 2022

**Today's Progress:** 🧠 Mindset Thursday, Parameterised Queries & Group Presentations

**Thoughts:** Mindset session in the morning all about values and making decisions in groups and why we should not focus on just finding the right answer, but rather on how to work as a group. Spent most of the day finishing up yesterdays workshop - starting to feel more comfortable with the concept of creating environmental variables & connection strings, async functions with SQL queries & parameterised statements, exporting these request models and creating routes for the response. Finished the day with giving a group presentation on Arrow Functions - I think I understand these better now!!

I definitely need more practice on creating routes in my API but I assume tomorrow's hackathon will help me with that 🫣

**Code Snippet:**

```
//.env file
PORT = 3000
POSTGRES_CONNECTION_URL=postgres://jcizuxho:bjUejFIM_queeRz3gG9OudvP1-x2AGP4@lucky.db.elephantsql.com/jcizuxho

//db index.js file
const { Pool } = require('pg')
const pool = new Pool({ connectionString: process.env.POSTGRES_CONNECTION_URL, });

module.exports = {
    query: function(text, params) {
        return pool.query(text, params)
    }
}

//model routes file
const { query } = require("../db/index.js");
```

### Day 33: October 28, 2022

**Today's Progress:** 💥 Build a REST API with Node.js, Express & PostgreSQL - Hackathon Friday!!

**Thoughts:** Big one today! My partner and I worked on creating a database of plants and sepearting it into 3 different tables; 'Plants', 'Owners' and 'Plants Owned'. The first SQL table would generate an ID for the plant, list the name of the plant, its height and light/water level requirements. The second table would generate an ID for the owner and their name, and the third table would pull these two together with the Plant_id and Owner_id to find which owner owns which plants. We created the connection string using the URL from our ElephantSQL database in the hidden .env file, created models and routes for 21 different requests covering all 4 CRUD operations! 🥳

I am starting to feel much more confident with SQL and I've found what works best for me is running the SQL query in ElephantSQL first to ensure my function will carry out the query I want without crashing the code or returning the wrong result! Made many syntax and typos along the way that caused errors but found that my partner and I worked really well with error messages, debugging and console.logging to find the root cause of the error without external help 💪🏼

I still need to work on connecting backend to frontend as we weren't able to get far enough in our hackathon timeframe to complete that but will be my goal for next week!

**Code Snippet:**

```
//async function in models - updateOwnedPlant ✅
async function updateOwnedPlant(id, updated) {
    let result = await query(
    `UPDATE owned_plants
    SET owner_id = $1, plant_id = $2, plant_nickname = $3
    WHERE owned_plant_id = $4
    RETURNING *;`, [updated.owner_id, updated.plant_id, updated.plant_nickname, id]);
    let updatedOwnedPlant = result.rows;
    return updatedOwnedPlant;
}


//create request response in route - updateOwnedPlant ✅
router.patch("/:id", async function (req,res) {
    const updatedOwnedPlant = await updateOwnedPlant(req.params.id, req.body);
    return res.json( { success: true, payload: updatedOwnedPlant});
});


//require route from routes folder and tell the app to use it
const ownedPlantsRouter = require("./routes/owned_plants.js");
app.use("/api/owned_Plants", ownedPlantsRouter);
```

### Day 34: October 29, 2022

**Today's Progress:** Saturday - Rest and Relax 🧖🏽‍♀️

**Thoughts:** Following my saturday tradition so far and spent the day away from the screen! I did spend half an hour or so putting into practice what I learnt on Thursday to refactor some of my old codewars with regular functions into arrow functions. I feel comfortbale with doing it when theres only one argument and one statement but I want to work on trying this with more arguments and if statements/loops in the statements.

**Code Snippet:**

```
//CodeWar - given the year, return what century it is

//Regular Function
function century (year) {
	let answer = math.ceil(year/100);
	return answer;
}

//Arrow Function
const century = year => math.ceil(year/100);
```

### Day 35: October 30, 2022

**Today's Progress:** Week 5 Recap Task... CommonJS (CJS) vs ECMAScript modules (ESM) ✅

**Thoughts:** Now that we have spent the last 2 weeks covering writing REST API's in CSJ, next week we will work on refactoring this into ESM. I spent some time today reading resources which go through the differences between the two and refactoring parts of my friday's hackathon from CJS to ESM. I am feeling good about achieving the goals of the recap task which were; be able to import modules using ESM, export modules using ESM and create/convert an existing API to ESM and test the code works. A YouTube video titled 'JavaScript Modules: From IIFEs to CommonJS to ES6 Modules' really helped me understand the differences and refactor my API!

**Resources:** https://www.youtube.com/watch?v=qJWALEoGge4

### Day 36: October 31, 2022

**Today's Progress:** Intro to Testing; Unit Testing, Pros/Cons and Jest

**Thoughts:** Started Monday off with a fantastic talk from guest speaker Nadeem Shabir (Staff Engineer) all about testing code and the key qualities a Junior Software Developer should strive to have to succeed in the industry. From there we dived further into the world of testing and looked at the Testing Pyramid. We focused only on unit testing today and covered testing in the feedback cycle, the pros/cons and why we test. We tied this in with our Node.js understanding by learning about the npm module Jest, and put it into practice with some basic testing functions.

As we have been working predominantly in CJS so far, working today in ESM was a bit different and will take some getting used to. But this reminds me of something Nadeem said today which really stood out to me. To remain successful, it is important to learn to unlearn. The world of tech changing so fast, so there is always something new being developed for us to use. Today I had a first-hand experience of that by having to move away from CJS and focus more on ESM, but I am up for the challenge!!

**Code Snippet:**

```
// scripts tag in package.json file
"scripts": {
    "test": "node --experimental-vm-modules node_modules/jest/bin/jest.js"
  }

// function in js file (in ESM)
export function sum(a, b) {
    return a + b;
  }

// test in separate js file
import { sum } from './sum';

test(
// a function that takes in a human readable string as first argument and a function as the second
// string with a specific label that shows up in the terminal and represents the test itself
    'adds 1 + 2 to equal 3', () => {
// function with testing logic of what we want to have happen
    expect(sum(1, 2)).toBe(3);
});
```

### Day 37: November 1, 2022

**Today's Progress:** E2E Testing 👩🏽‍🔬

**Thoughts:** Moved onto the top of the Testing pyramid and learned more about e2e testing! Sat in on a really insightful talk and demo from Paul Jaffre from Cypress about what e2e testing is, why we use it and how Cypress has come around to automate it. I am starting to understand the difference between the various layers of the testing pyramid a bit better but still need to spend some more time implementing TDD when writing tests. I loved the visual feedback of the tests that Cypress provided in e2e, I can definitely see how this is going to be something I use a lot in the future.

**Code Snippet:**

```
// can you get the header syntax check ✅
describe("h1 text test", () => {
it("checks h1 tag displays correct text", () => {
  cy.visit("http://localhost:3000/");
  cy.get("h1").contains("😈 Plan to take over the world:");
});
});

// can you type in the box? ✅
describe("box input test", () => {
it("input of box div can be changed", () => {
  cy.visit("http://localhost:3000/");
  cy.get("input").type("dave").should("have.value", "dave");
});
});
```

### Day 38: November 2, 2022

**Today's Progress:** Integration Testing - Supertest! 🦸🏽‍♀️

**Thoughts:** Today we looked into the final level of the Testing Pyramid to complete the picture - Integration testing! Before today I was unsure of how this really differed from unit testing but now it all makes sense. This is used to automate API testing and can simulate front end requests without needing to constantly run the API platform. The coaches taught us the best way to break down logic stpe by step when running an async get/post/patch/delete test.

A personal win of mine is that I am really starting to feel comfortable with for loops now! My next goal here is to learn different ways to refactoring for loops to make them easier to read and short in code lines.

**Code Snippet:**

```
	1. Sends a `GET /users` request to our app using Supertest
	2. Check the response's HTTP status code
  3. Checkthe response's body is an object with the structure:
			`{ success: true, payload: array }`
  4. Checks if every item in the `payload` array is an object with the structure:
			`{ id: any number, username: any string }`
```

### Day 39: November 3, 2022

**Today's Progress:** Databases and making our own CodeWar! ⚔️

**Thoughts:** Covered the differences between NoSQL and SQL databases in a really insightful seminar from guest lecturers, Couchbase. We discussed why we need databases, different types of databases and the context in which they can each be useful. Then we moved onto my favourite workshop yet - creating our own code war! This REALLY helped me understanding the red, green, refactor TDD concept better. As well as this, it allowed me to work on my problem-solving skills through doing kata's the other bootcampers created. I was able to work on my writing skills in being able to present a problem which, for the most part, got good feedback in terms of the ask for a Level 8 Kata!

My biggest challenge today and something I need to be aware of for future progression is the idea of dream big and start small! I found my pair and I would get carried away in the brainstorming stages which hindered us when it came to writing the tests and meant we had to go back and simplify the ask.

**Code Snippet:**

```
// version 1, our codewar -> Karen is over for dinner! What's her favourite meal? As top tier programmers we keep our friend's favourite meals in an array of objects! Better go do programming things to find the favourite meal!

import { people } from "./friendslist.js";

export function findTheMeal(people) {
  for (let i = 0; i < people.length; i++)
    if (people[i].name == "Karen") {
      findThePeople(people[i].favouritemeal);
      return people[i].favouritemeal;
    }
}
```

### Day 40: November 4, 2022

**Today's Progress:** 💥 Testathon - Hackathon Friday!! 🧪

**Thoughts:** A really good hackathon! We put into practice everything we learnt throughout the week and ran e2e tests in Cypress on a to-do list app, with some integration API tests with supertest/jest. Some things we had to do today were: create a database, connect it via a connection string to the port in .env files, adjust the script tags to connect tests to the .env files, install and import various testing modules, create beforeEach and afterAll hooks to reset the tables and visit the correct URL, using the eq variable in Cypress to target specific elements on a page and so much more!

The best part about today was being able to help my friends in the bootcamp when they were stuck on certain parts such as connecting the databases or explaining how/why we use eq rather than element attributes when running tests. Explaining it to others helped me to further my understanding on the topic and also just made me feel proud of myself for being able to support others when usually I am the one who is in need of support!

**Code Snippet:**

```
// Integration testing with Supertest
	// import resetAllTables function
	import { resetAllTables } from "../db/scripts/helpers.js";
	// import pool from pg modules
	import { pool } from "../db/index.js";

	//reset each test table before running
beforeEach(() => {
	  // console.log( "Hello I am the computer and I have reset everything for you! RUN NEXT TEST");
  return resetAllTables();
});

		// stops the test from running longer than 1 second
afterAll(() => {
  return pool.end();
});

```

### Day 41: November 5, 2022

**Today's Progress:** Saturday - Rest and Relax 🧖🏽‍♀️

**Thoughts:** Well deserved rest day after a very testing week! 😉 I went through my notes and revised everything I learnt on why we test and at what points we use the unit, integration and end to end testing. Ahead of next week, I spent a bit of time looking into React - I am super excited to learn more about this! I watched 'Learn React in 30mins' by WebDevSimplified on YT and downloaded a couple VSCode extentions they recommended to support me during next week!

Other than that, Saturdays are my mandatory time away from the screen days so I spent the day exploring life outside of code.

**Code Snippet:**

```
// create a function component inside of react and assign it the name of the file it is in

import React from 'react'

export default function react() {
  return (
    <div>react</div>
  )
}
```

### Day 42: November 6, 2022

**Today's Progress:** Week 6 Recap Task... Testing ✅

**Thoughts:** Completed a quick recap task consolidating everything we learnt on testing during Week 6. Very much similar to the hackathon task, but this time with a send Tweets page. I'm feeling much more comfortable with Cypress now and was able to implement TDD when writing the integration tests pretty well. I find creating a md plan file the simplest way for me to break down what functionalities I want the page to be able to perform into what tests I need to run.

I had a slight initial struggle when connecting the database to the documents where the server was listening to the port but none of the tweets in the database were shown. I was able to resolve this issue really quickly after looking back on my notes and realising after connecting the database, the first step is to `run npm db:reset` before running any tests.

**Code Snippet:**

```
describe('Input Elements', () => {
  //Can you access and type the name input box? ✅
  it("Can you type in the Name input?", () =>{
    cy.get("input").eq(0)
    .type("testing123")
    .should("have.value", "testing123")
  });
  //Can you access and type the tweet input box? ✅
  it("Can you type in the Tweet input?", () =>{
    cy.get("input").eq(1)
    .type("testing123")
    .should("have.value", "testing123")
  });
});
```

### Day 43: November 7, 2022

**Today's Progress:** Intro to React!! ⚛️

**Thoughts:** Today we began the basics of React, we looked into what it is, where it's used and why we use it. The videos I watched over the weekend really helped solidify what we were being taught today and the possibilies with React seem so exciting! We touched on writing React in its rawest form with React.element, then moved onto writing in JSX form to simplify and using Babel as a transpiler between different languages. Learnt some of the syntactic differences between JS and React (camelCase vs UpperCase function names) and then briefly touched upon 'props' and 'children' in React.

A lot of new information today that definitely has not all fully sunk in on day 1 but I am really excited for the week ahead and to be diving deeper in to front end again! 😁

**Code Snippet:**

```
<div id="root"></div>
	<script type="text/babel">
	const rootElement = document.querySelector("#root");
	const root = ReactDOM.createRoot(rootElement);

	function ListItem(props) {
		return <li >{props.text}</li>
	}

	root.render(
		[
		<ListItem text="Milk" />,
		<ListItem text="Eggs" />,
		<ListItem text="Flour" />,
		<ListItem text="Bananas" />,
		]
	);
```

### Day 44: November 8, 2022

**Today's Progress:** Array Methods and Create.React! 🗺

**Thoughts:** Today we revisited Array methods and did some exercises utilisng `.map`, `.filter`, `.some`, `.find`, `.findIndex`, `.every`, `.sort`. This was really helpful as I keep seeing Array methods come up in CodeWar solutions but found them really hard to get to grips with when researching myself! After this we moved onto learning about Create.React and its endless possibilities. Have a lot more to explore here but for now, we covered the basics of creating the building block components in isolation and then importing it into one place in App.js!! Also spoke about the importance of creating Component Tree diagrams before coding with React.

Finding it hard to get my head around 'props' and destrucuting for now, will bring this up in a meeting with my mentor tomorrow to discuss further.

**Code Snippet:**

```
// In list component index.js file
function List({ children }) {
	return <ul>{children}</ul>
}

export default List;

// In app.js file
import List from "../List";
import ListItem from "../ListItem";
import "./App.css";

function App() {
	return (
		<div className="App">
		<List>
			<ListItem text="tea" />
			<ListItem text="chocolate"/>
		</List>
		</div>
	);
}
```

### Day 45: November 9, 2022

**Today's Progress:** React Hooks and useState 🪝

**Thoughts:** Had a lot of fun today learning about States, 'Smart' vs. 'Dumb' components, State Hooks and Nested Components. I really strugged at the start of the day understanding what 'states' meant but with the right tools and support from the coaches and other bootcampers, I came a long way by the end of the day. Gives me a lot of gentle encouragement from what I learnt in a day to what I can achieve in the future. My main takeaway today was `const[state, setState] = useState(initialState)` and a state can be thought of as adding a 'brain' to your app! 🧠

**Code Snippet:**

```
import {useState} from "react";

let index = 0;

const [index, setIndex] = useState(0);

	function handleClick() {
		setIndex(index+1);
	}

// Creates a handleClick function which sets the index to the existing number + 1 and remembers this
```

### Day 46: November 10, 2022

**Today's Progress:** Spread and Slice makes things nice, and immutable! 🥪 🔪

**Thoughts:** I have continually come across ...'s and slice() when looking at solutions for CodeWar kata's but never really grasped what they did and how we use them until today. We covered the differences between immutability and mutability and why both can be useful in different scenarios. For the case with React, we mainly want to focus on immutability. I learnt about why we create components in seperate files, how we can utilising array/object methods such as spread, slice and mapping to make our app immitable when working with databases, and how to assign key props to child elements.

I struggled today with grasping how to use Spread and Slice together, but completing several worked examples helped cement this further. I look forward to taking what I leant today and applying it in React in tomorrow's hackathon!

**Code Snippet:**

```
//Combining Spread and Slice to toggle a completed item in a to do list from true incomplete to complete

export function toggleListItemCompleted(array, index) {
    // Clone the array into a new array with spread
    // Slice it at the index to access completed key
		// Create a function which will change the currect state of complete to the opposite
		// Reclone and slice it back at index+1
		// Combine both new arrays with the adjusted completed key's state

    const clonedArray = [...array]
    // console.log("original" + clonedArray[index].completed)
    const opposite = !clonedArray[index].completed
    const newArray = [...array.slice(0, index), {...array[index], completed: opposite}, ...array.slice(index+1)]

    return newArray
}
```

### Day 47: November 11, 2022

**Today's Progress:** 💥 Build a To Do List in React - Hackathon Friday!! 🧾 ✅

**Thoughts:** Probably the hardest day in my 100DaysOfCode journey so far. Up until this point I felt as though I was somewhat grasping what states, components, props, keys, children, mapping, immutablity were. But today, when trying to put everything I learnt together, I realised the hard way that that's not the case 😬. I will definitely need to spend some time this weekend revising the fundamentals and will give building a funcitoning app in React another go once I feel comfortable with the basics. My biggest takeaways for my future self today were knowing when to ask for help, take the time to plan and understand the task first, not giving up, be okay with presenting little but understanding a lot as opposed to the opposite, and give back to those around me who help pick me up when I start to feel low.

This journey is a rollercoaster but I am enjoying the ride and learning more about myself along the way!

**Code Snippet:**

```
function App() {
	// Create handleClick state for button
	// set the name of the state and what we want it to do, and what condition we want to start at
	const [todos, setTodos] = useState([]);
	const [userInput, setUserInput] = useState("");

	// This grabs what the user writes in the input tab
	function handleChange(event) {
		setUserInput(event.target.value);
	}

	// This spreads the original array and appends the new input from the user (userInput) into the new array
	function handleAdd() {
		setTodos([...todos, userInput]);
		setUserInput("");
	}

	// This should delete an item from the list
	// Go into the array which was made when the list was added and clone it
	// Slice out the text at the index it sits at and at index+1 value, combine these
	function deleteList(index) {
		setTodos([...todos.slice(0, index), ...todos.slice(index + 1)]);
		console.log("delete list called");
	}
```

### Day 48: November 12, 2022

**Today's Progress:** Saturday - R & R 🧖🏽‍♀️

**Thoughts:** After an intense week, I spent the entire day away from writing ANY code!! Only thing I did do on this day was recap over the Week 4 Progress Check we did a couple weeks back which tested our understanding in 3 topics; reading/naming functions, accessing arrays & objects with dot/bracket notation & debugging if statements with syntax errors. At the time I found this task quite difficult but going through it today I was able to work through the problems much more methodically and make better sense of it! Great sign of progress being made so I'm happy 😁

### Day 49: November 13, 2022

**Today's Progress:** Week 7 Recap Task... React (Blog Post) 🥴✅

**Thoughts:** Spent almost the entire day working through this weeks recap task building an app that displays blog posts and has an input bar allows users to add comments that are stored below the blogpost in a list with their initials on the side. Got stuck many times but spent the day on call with some lovely other bootcampers and worked through any errors/confusions as a team when stuck! This helped me SO much to better understand what was going on and avoid feeling overwhemled. Lots learnt today and lots to digest, but overall feeling a bit more confident with some of the basic React components and ready(?) for another week of React next week.

**Code Snippet:**

```
// App.js file

return (
	<div style={{width:"100%", marginLeft:"auto", marginRight:"auto", maxWidth:"400px"}}>
		<h1>Hello</h1>
		<BlogPost {...blog}/>
		<CommentList comments={comments} author={author}></CommentList>
		<CommentForm
			type='text'
			author={author}
			commentBox={commentBox}
			handleClick={handleClick}
			handleCommentChange={handleCommentChange}
			handleAuthorChange={handleAuthorChange}
			//handleAdd={(event) => handleAdd(event)}
		></CommentForm>
	</div>
	);
```

### Day 50: November 14, 2022

**Today's Progress:** Recap on REST API's & new React hooks - useEffect!

**Thoughts:** Recapped previous weeks REST API content to remind us of the bigger picture after working for an entire week in Front End!

Topics discussed:

- Recap on HTTP methods & CRUD operations
- Understanding different error codes
- Anatomy of a request
- Versions in API and types of versioining

After this, we linked this back to React and discussed useEffect with fetch requests to connect frontend to backend API's. Met my new pair programming buddy for the week and felt much more at grips with the content today. I grasped the purpose of useEffect much quicker than I did with useState last week. Spending time over the weekend solifidying my understanding of hooks over the weekend was likely the reason why.

By the end of day I was able to create an app which generates random pokemon using the ID prop to match it to the URI and display the pokemon's id, name and image URL. I even went on the play around with some in line and importing CSS for the first time in a while. End result = created a super cool hover button from a template I found on w3docs!

**Code Snippet:**

```
useEffect(() => {
		async function getPoke() {
			const response = await fetch(`https://pokeapi.co/api/v2/pokemon/${id}`, {
				headers: { accept: "application/json" },
			});
			const data = await response.json();
			console.log(data);
			setPokemon(data.name);
			console.log(data.sprites.front_default);
			setPokemonURL(data.sprites.front_default);
		}
		getPoke();
	}, [id]);
```

### Day 51: November 15, 2022

**Today's Progress:** Git Branching 🔀 & useReducer 🪝

**Thoughts:** Back to basics and discovered some other useful functions Git and GitHub provide which will come in handy during next weeks project week! We are familiar with git add/commit/push onto the main branch in turns, however I also realise this is not a likely environement when in the workspace. We covered how to create branches and the power of this when it comes to resolving conflicts much more seamlessly. I need a bit more practice here but as with anything, practice makes perfect 😌

From there, we went on to discover yet ANOTHER hook!!! This time useReducer and how it can be utilised to replace useState in a more maintainable and readable manner when working in complex apps with multiple event listeners and various components. I only just got my head around useState so it will take me some more practice before being able to use useState and useReducer interchangeably!

**Code Snippet:**

```
const initialArray = [];

function reducer(state, action) {
switch (action.type) {
	case "UPDATED_NAME":
		return [...state, action.payload];
	default:
			eturn state;
	}
}

function App() {
	const [state, dispatch] = useReducer(reducer, initialArray);

// Later in file, Input from the Input component in the function App() return
<Input
		addItem={(userInput) =>
			dispatch({ type: "UPDATED_NAME", payload: userInput })
		}
/>
```

### Day 52: November 16, 2022

**Today's Progress:** React Testing 🧪

**Thoughts:** Now that we had a good base understanding of creating components and states in React, we shifted onto Testing. We started by covering why we test and its drawbacks, then did a quick individual pair research task on what CreateReact and React Library Testing is. By the end of the day, I was able to use a React Matcher (getByRole) to write of a test which checked a page loads and displays the correct greeting message! Thoroughly enjoyed revisiting testing and learning more about different React Matchers.

**Code Snippet:**

```
import Judgement from "./Judgement.js";
import { test, expect } from "@jest/globals";
import { screen, render } from "@testing-library/react";

test("loads and displays greeting", () => {
	// ARRANGE
	render(<Judgement name="Alice" />);

	// ACT
	// Grabs the element that contains this text but is not exact, or the All Hail is not the entire obj
	const element = screen.getByText("All Hail", { exact: false });
	expect (element).toBeInDocument();

	// ASSERT
	// Select the element that contains the message
	expect(element).toHaveTextContent("All hail Alice, the attentive one!");

```

### Day 53: November 17, 2022

**Today's Progress:** Last Mindset Session 🧠 & Group Reserach Task on Story Points 👩🏽‍🏫

**Thoughts:** Today was sadly our last mindset session with Joseph Trudden. I've really enjoyed these as they've made me incredibly more self-aware of my listening, leadership skills, my inner champion & weaknesses. Beyond that, we've learnt how we can each play to our individual strengths when working in teams, voting methods to ensure everyone in the team feels heard and how to compromise.

In today's session, we discussed how the best teams share a common appreciation of culture and acknowledging that every teams goes off balance eventually - this is not a sign of failure but rather, a test to make sure you have a suitable recover plan in place.

The rest of day was spent covering testing in a bit more detail with added event listeners and userEvents, and finished with a group research task where we recapped on AGILE. My team and I gave a 5 min presentation of Story Points; What are they? Why are they better than conventional timeframes and dates? What is an example of a story point?

**Code Snippet:**

```
// Import test, jest, screen, render, userEvent and the relevant components
// GOAL #1 -> Want to test that the typing into the input works
// GOAL #2 -> Want to test that clicking the button works

test("should render an input, () => {
  // declare mock function
  const props = {handleNewName: jest.fn()}
  });

      //ARRANGE -> render the form
      render(<Form handleNewName={props.handleNewName}/>);

      //ACT -> select the input and type into it
      const input = screen.getByRole("textbox");
      userEvent.type(input, "Alice");

      //ASSERT -> is the typed value in the input?
      expect(input).toHaveValue("Alice");
```

### Day 54: November 18, 2022

**Today's Progress:** 💥 React API - Hackathon Friday!! 🌐

**Thoughts:** This hackathon was a bit different to previous ones, with a stronger focus on planning and iterating through ideas to build a basic, just functional MVP. I really enjoyed looking more on the prepping side of things and revisiting the Disney Ideation method today. I used Trello for the first time to break down tasks, prioritise and check off what has been done and what is left to do! It made project managing much more simple and I can already see how it is going to be an incredibly useful tool to utilise in Project Week!

We had a couple issues throughout the day, however my partner and I worked really well to solve majority of them and ask for help when we felt stuck. Good planning meant a larger issue, such as our API chosen not working, were not as big of a deal and were easily resolved without going too off-balance. Great day, we were able to build an MVP we were happy with and even had a bit of time to start working on one of our stretch goals - CSS'ing a nice button - and doing a Agile Retro on what went well, what we learnt and what we might do different next time.

**Code Snippet:**

```
function App() {
	const [quotes, setQuotes] = useState([]);

	async function randomQuote() {
		const response = await fetch("https://api.chucknorris.io/jokes/random", {
			headers: { accept: "application/JSON" },
		});
		const data = await response.json();

		let newArray = [...quotes, data.value];
		setQuotes(newArray);
		console.log(quotes);
	}

	useEffect(() => {
		randomQuote();
	}, []);
```

### Day 55: November 19, 2022

**Today's Progress:** Saturday - R & R 🧖🏽‍♀️

**Thoughts:** With next week being Project Week and feeling quite exhausted from the last 2 weeks, I chose today to not touch my laptop at all! I spend some time with friends and family, went to the gym and for a nice long walk to counter all the hours I have spent sitting at the desk for the last 8 weeks!

My mentor reminded me the value of not getting too carried away and remembering life outside of code, so I chose to pick up some old hobbies today 😄

### Day 56: November 20, 2022

**Today's Progress:** Catchup & Week 8 Recap Task...

**Thoughts:** I fell quite behind on updating my logs this week so spent the first half of the day updating my personal 100 Days of Code log on my Notion and also here. I really enjoy reflecting on what I learnt this week in retro and writing it down for my future-self! Next week is the big project week so took it easy this weekend to make sure I am mentally prepared for an exciting and, no doubt, intense week ahead!

### Day 57-86: November 20, 2022 - December 20, 2022

STILL TO DO

### Day 87: December 21, 2022

**Today's Progress:** The day before Christmas (holidays)! 🎄🎅🏼🎄❄️

Final day in the bootcamp before breaking until the 2nd of Jan for Christmas holidays! 🥳

**Thoughts:** Today we were given a Notion audit template which breaks down what we learnt throughout each week on the course. It was given as a starting point to set ourselves up for continuous successful learning by building the habit of analysing learning systematically and targeting efforts. The idea was we rate each topic based on:

1. How important you feel it will be for your learning to spend more time practicing with it
2. How much time you think you’ll need to gain confidence in it in advance of your final project

I spent a little bit of time reviewing this with my pair but will looking into it in further detail over the break on a personal level to determine what I need to spend more time revising ahead of project month when we start back in January! 😁

Rather than block off the next few days in my 100daysofcode challenge, I have decided it makes more sense to rather pause the challenge here and resume from day 88 after taking some time off to reflect better how I have progressed in 100 days of coding. 🫡

```

// 21/12/22-28/12/22... #100DaysOfCode Challenge PAUSED ⏸

```

### Day 88: December 29, 2022

**Today's Progress:** Dusted off the ol' computer! 🧹

After a wonderful, refreshing and MUCH needed 7 days off, we go again! 🦸🏽‍♀️

**Thoughts:** Despite initially planning to do much more over the holidays, after logging off on Wednesday 21st December and seeing loved ones around me take time off work for the holidays, I decided to follow suit and take some time off to spend with family. My eyes, back, mind and soul needed it and is thanking me for it now. With the nature of a bootcamp, it is very easy to get carried away and lose focus of the bigger picture. I will admittedly say I did spend some of the last few days feeling guilty for not doing much work but, after looking back on my journey so far, I can acknowledge now that by week 12 I began to really struggle with feeling burnt out. I fell behind on my logs, struggled with motivation to do anything past 5pm and constantly felt tired and half-present. Having this break has taught me that I need to go easier on myself, and the importance of pausing, taking a step back, reflecting and feeling proud.

Hence I spent most of today reflecting on the SoC audit given on day 87 and catching up on my logs, rather than coding. With the new year approaching, I want to start as I mean to go on. I have finally found something I feel truly passionate about and do not want to approach this with my old mindset of 'everything must be done now and everything must be perfect'. The world of tech is one that is always growing and there is ALWAYS going to be so much to learn, I'm never going to know everything and that's okay. After looking back on everything I have learnt so far, there are many things I feel like I still don't quite understand; whilst the old me would feel angry and disappointed in myself for that, I now see it as an exciting opportunity to learn more! The most powerful thing I've learnt about coding, which goes much against my Engineering background, is that we learn best by doing. So, I have made a plan that for the next few days I am going to try to build an app to solidify my understanding of React! Planning begins tomorrow 🤓

```

// 29/12/22... #100DaysOfCode Challenge PLAY ⏯

```

### Day 89: December 30, 2022

**Today's Progress:** ⚛️ Planning a Personal Project in React ➡️ Budget Tracking App 💰💸

**Thoughts:** I spent some time today looking into creating a new side project, one I had a use-case for and one which would help me to broaden my understanding of the basics in React. At this point, I am very familiar with working in pairs and groups to distribute workload and work on various areas of creating a website but I am yet to create an entire project start to finish by myself. I think doing this will really help me to solidify my understand of react concepts and build my understanding of 'Full-Stack'. I watched some tutorials and articles of good first apps to build for new developers and a budgeting app seemed to be one which cropped up multiple times. Seeing as this is something I could genuinely use myself, I think I am going to try to build this!

### Day 90: December 31, 2022

**Today's Progress:** Wireframing and Component Tree Diagrams ✏️

**Thoughts:** Spent some time working on creating a wireframe for how I want the budget tracket to look. Going for a simple look with reusable components so I can really wrap my head around components and props. I would also like to add some condiitional CSS rendering so that overbudget triggers a red background and text prompt to caution the user. I read a lot on visual aids and app UI colour theory, how different fonts, colours and text layouts can trigger different emotions in the user. I drew up the wireframes in Excalidraw first in low fidelity and breaking it down into components. I am now working on converting them into a high fidelity wireframe in Figma!

![](2023-03-17-17-12-12.png)

### Day 92 & 93: January 1 & 2, 2023

**Today's Progress:** Happy New Year! 🥳

**Thoughts:** Spent the day reflecting on my journey over the past year and that to come! Made a list of goals for the new year, many of which were career related, some including:

- Finish the School of Code Bootcamp and be proud of myself!!
- Land my first role in Tech!
- Work for a good company, make an impact and work towards creating something that makes the world better!
- Continue to track my journey and reflect

Tomorrow, School of Code commenses again and this time we will be meeting with our 4 week project groups! I am super excited, kind of nervous and feeling creative with tons of potential ideas to bring to the group 🤩

### Day 94: January 3, 2023

**Today's Progress:** Meet the Teams 🤝

**Thoughts:** The 4 week project commenses! Today we met our teams, got to know one another and made a team manifesto. We were given a brief to "create a solution to a real life problem". After reading the brief, we started with brainstorming problems that we have all encountered rather than ideas of apps. From there, we moved onto solutions to the problems, then rated the product market fit, feasability, usability and viability out of 5 for each idea.

**Progress:**

- Used dot voting throughout the day to come to a decision on team name and which ideas to take through to dreamer, realist and critic room.
- Tie between two ideas we all liked, so we took them both through to disney ideation.

* Created a Google Docs where we all contributed to create a team manifesto ➡️ https://docs.google.com/document/d/173oe0PoPwspKAp0uZScBkR_JnKM-0UhHes3qHhXdSqI/edit
* Created a Trello board for the week ➡️ https://trello.com/b/1ynRQExY/week-1-sprint-1-planning
  Decided that the best way to break down the sprints would be to complete weekly sprints, and each week create a new Trello board with the week's backlog, goals, stretch goals and assign members to each ticket. This would also be a mutual space for the team where we can do daily standups and retros to reflect on the day, how many goals we reach and if we are ahead or behind schedule.

![](2023-03-17-17-40-28.png)

### Day 95: January 4, 2023

**Today's Progress:** Team FatArrowFaction - Ideation, Wireframing, Planning🤩

**Thoughts:** Today we moved into the Disney Ideation room with two ideas - one being an app to monitor expired foods, and the second being a way to compare postage prices online through all existing postal services. In the disney rooms, we took each idea through the dreamer, realist and critic room and quickly came to the decision that the food expiry notification app was the one for us! We felt way more inspired by this idea and could see a real world audience for us to reach with it.

From here, we: - Dinished up the user journey stories for research and the low-fi wireframes

- Decided what we wanted our MVP to include
- Started exploring what tech stack to use
- Made the decision to opt for react native as this kind of app would not make sense in desktop version
- Created a Miro board for the team to collaborate and to track our daily progress: https://miro.com/app/board/uXjVP1sSrDA=/

### Day 96: January 5, 2023

**Today's Progress:** Tech Stack Debates 🤔

**Thoughts:** After finalising on an idea, here we began to look into tech stack and what our options were. We knew these four week were the perfect time to test our limits, set optimistic goals with the support network of one another and the School of Code coaches, and broaden our horizons whilst also solidifying our understanding of everything we have learnt thus far. With an idea of wanting to create a mobile first app, given the nature of a food expiry notification app not likely being a desktop app, we looked into options.

Some of which included: \* A desktop app

- A progressive mobile-first desktop app (similar to what my week 1 project was) with multiple pages
- A entirely mobile app

Knowing these were our options, we began to look into tech stacks including Next.js, TailwindCSS and React Native. We knew we wanted to go beyond just a single page CRA! We spent the day doing research into React Native, how easy it would be to learn from scratch within 4 weeks and alternative options.

### Day 97: January 6, 2023

**Today's Progress:** React Native! 💪🏼

**Thoughts:** We made the brave decision at this point to finalise on creating a mobile app using React Native, something entirely new to us to learn and build a functioining app from within 4 weeks. Ambitious, I know. But, before finalising on this decision today we all took the time to create a proof of concept app to see how easily we could grasp React Native. Despite a few bumps in the road and new tech terms to get used to, we muddled our way through as a team to create a very basic app which accesses a camera library using an image picker API! We felt confident that we could face this challenge together as a team.

We set out some ground rules and 15-15-15 rules to make sure we remain productive and help each other through every step. We made the decision to swap around people each day and try our best to work togerher in all aspects of the app as this was a new concept for us all! There was also a mutual agreement that learning React Native would be a hard enough challenge on its own, so we opted for JavaScript and CSS stylesheets to solidfy our understanding of everything we had learnt up until this point. We are so excited for the road ahead and can't wait to create an EPIC React Native app!! 💪🏼🚀

### Day 98 & 99: January 7 & 8, 2023

**Today's Progress:** Week 1/4, in the bag ✅

**Thoughts:** I spent the weekend planning the next 3 weeks ahead and creating a game plan for how we are going to take on this React Native Challenge. After setting up the Trello board for Sprint 2, I looked further into creating Navbar's in React Native. This was something we struggled on as a team in the Proof of Concept app purely due to time contraints so I wanted to spend my weekend looking further into this and reporting back to the team on Monday.

I watched some tutorials on how to create a navbar in react native
[](https://www.youtube.com/watch?v=AnjyzruZ36E)

While it does feel like we are being ambitious, I am genuinely excited and curious for the journey ahead. I just want to learn and I look forward to challenging myself. It can be easy to feel overwhelmed but so important to remember this is not a race, we are not competing. This is my journey and I am part of an amazing team, we will take things one step at a time and make sure everyone is involved and remember to stay proud of celebrate every team & personal accomplishement along the way! 🥰

### Day 💯: January 9, 2023

**Today's Progress:** We did it!!!! Heres to the next 100 🚀🥂

**Thoughts:** Back in September I was chosen out of 1000’s of applications to embark on a new journey. I had never understood a line of JavaScript in my life, no idea how HTML or React work and, to be honest, had a very vague idea of what a ‘developer’ actually was. 16 weeks later, I now proudly leave School Of Code with the title of a Full-Stack Developer. 👩🏽‍💻

Read the rest of my LinkedIn post here where I reflect on everything I have learnt up until this point, my achievements and accredit all the beautiful people who have stood by my side along this jounrey!
[] https://www.linkedin.com/posts/arooj-ilyas_learntocode-schoolofcode-schoolofcode-activity-7025525502467596288-RsAt?utm_source=share&utm_medium=member_desktop
