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

**Today's Progress**: First Hackathon! Create a rock, paper, scissors game

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

**Today's Progress**: Week recap & review

**Thoughts** After a long week of learning a lot of new concepts with HTML, JavaScript and GitHub, I decided to spend today taking a bit of a break from learning anything new and instead spent the day recapping what I learnt this week before putting it into practice and attempting the remaining 3 tasks of the Hackathon. I reviewed what I learnt about objects, functions and arrays and how to create properties within objects and arrays. Also wanted to review that I fully understand how to clone down git repositorys and push/pull as that is going to be a vital part for the remainder of my School of Code course. 

### Day 7: October 2, 2022

**Today's Progress**: FCC JavaScript Basics & week recap 

**Thoughts** Today I managed to get 70% through the FreeCodeCamp course for Basics of JavaScript, this helped me so much in terms of solidifying what I've learnt this week and really making sure I fully comprehend the basics so that I can tackle the workshops next week with a better base understanding! Feel much more familiar now with create if/else if statements and different operators such as && and | |. Also learnt that there is a difference between the == (equality operator) and === (strict equlaity operator). Completed task 5/7 for the Hackathon and learnt more about math.Random and math.Floor to return random integers. 

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

**Today's Progress**: CodeWars and DOM's

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

**Today's Progress:** Mindset, Navigating Data, Presenting Research

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

**Today's Progress:** Fetch - Hackathon Fridays!! 

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

**Today's Progress:** TLC - Rest and Relax 🧖🏽‍♀️

**Thoughts:** Today for me was all about learning the importance of balance. Wanted to take a break from my screen and resume my life outside of coding. Aim was to reset and recoup myself after an intense two weeks! I spent the day instead catching up with friends & family and organising through the documents on my computer - my desktop was starting to look worse for wear with the number of screenshots

### Day 14: October 9, 2022

**Today's Progress:** Week 2 recap tasks...

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

**Today's Progress:** Week 3 commenses! Agenda: UI/UX

**Thoughts:** Worked on a !Lightening challenge with the aim of creating the Google landing page 'blindly' coded to demonstrate the importance of feedback. Given I haven't looked at HTML in depth since day 2/3 at SoC, I felt a bit underprepared for this task - unsure of the differences between ```<div> and <section>``` tags so I definitely want to spend some time revisiting this on FCC!

But, this task tied nicely into what we did for the remainder of the day - learning more about AGILE methodologies and the 4 values of AGILE: Individuals and Interactions, Working Software, Customer Collaboration, Responding to Change. Also learnt about the differences between UI and UX and that Good UI ≠ Good UX, but both are equally as important!! 