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
 
**Link to work:**: https://www.freecodecamp.org/fccc2498d63-cfb8-47dc-9a8a-e4da663cd78c
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