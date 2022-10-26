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

**Thoughts:** Today I managed to get 70% through the FreeCodeCamp course for Basics of JavaScript, this helped me so much in terms of solidifying what I've learnt this week and really making sure I fully comprehend the basics so that I can tackle the workshops next week with a better base understanding! Feel much more familiar now with create if/else if statements and different operators such as ```&&``` and ```| |```. Also learnt that there is a difference between the == (equality operator) and === (strict equlaity operator). Completed task 5/7 for the Hackathon and learnt more about math.Random and math.Floor to return random integers. 

**Code Snippet:**
```
let player2 = Math.floor(Math.random() * 3) 
    if (player2===0) {
        player2="rock"
    } 
 // repeated with if statements for outcome of scissors and paper

**Link to work**: https://www.freecodecamp.org/fccc2498d63-cfb8-47dc-9a8a-e4da663cd78c
```
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

**Thoughts:** Worked on a !Lightening challenge with the aim of creating the Google landing page 'blindly' coded to demonstrate the importance of feedback. Given I haven't looked at HTML in depth since day 2/3 at SoC, I felt a bit underprepared for this task - unsure of the differences between ```<div> and <section>``` tags so I definitely want to spend some time revisiting this on FCC!

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

Also spent some time in the afternoon researching UX tools such as empathy and journeys maps,  user interviews and information architechture (but user persona for my team specifically). Had a guest talk from Paavan over at AND Digital and presented our findings to the other teammates - slowly but surely starting to feel a bit more comfortable with public speaking 

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

**Today's Progress:** Week 3 Recap Task... Backend & API Routes ✅  

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