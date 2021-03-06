# About Me

Name: Alex Rusin

Email: arusin@udel.edu

Repository: [Link](https://github.com/aerusin/portfolio.github.io)

# Portfolio
Read [this](https://marksheet.io/) tutorial which went over the basics of HTML and CSS and created this [website](https://aerusin.github.io/website/). The source code of the website is [here](https://github.com/aerusin/website/blob/main/index.html). 

Watched a beginner website tutorial on youtube linked [here](https://www.youtube.com/watch?v=FazgJVnrVuI&t=1575s&ab_channel=BrianDesign). I followed the guide a bit and created a [this](https://aerusin.github.io/website2/) website. The source code is [here](https://github.com/aerusin/website2/blob/main/index.html).

Made a game of tic-tac-toe from the react tutorial [here](https://reactjs.org/tutorial/tutorial.html). The [website](https://aerusin.github.io/reactTic-Tac-Toe/) is only showing the readme when pushed to github and published. I had another student have the issue as well.

Watched Dr.Barts video and tried to create my own cardgame [here](https://aerusin.github.io/reactcardgame/) with the source code [here](https://github.com/aerusin/reactcardgame). The goal of the game is suppose to be like a flashcard math quiz where a question would pop up and you answer and you get an output of whether its correct or not. I wanted it to be somewhat like [this](https://www.factmonster.com/math/flashcard?op[0]=addition&level=1) in terms of looks but spent alot more time then I probably should have on the actually functionality. A big problem I had was trying to get the input and use that input to check the actual value. It sounds easy but I didnt realize how many little things can get in the way such as the textbox not clearing on entry, the types being different etc etc which would essentially just break the code. The 2nd thing that ended up taking most of my time was the change cardKind function as the process of finding out where to put everything was a pain. I tried to orginionally all the buttons and functions in ControlPanel which ended up not working too well. Dr. Bart ended up giving me a great advice to make a radio button as it looks cleaner and helps out organinizing alot. I would say this was alot more difficult than I expected as the overall syntax and layout of everything was just very hard to wrap my head round at first and am still learning. This is my frist time very doing any web development so I am very happy so far. 



# Changelog
## Week 1
* Added an image of my cat from my local directory.
* Created a list of groceries with the website embedded in the name.
* Made a background gradient, centered the image as well as rounding the edges to make it feel a bit more clean.
* Fiddled with an input text box where I wanted it to be able to change the color of text on screen based on what color was entered. Ended up deleting it as I swapped to a different idea which I will list below.
* After attending Dr. Barts lecture today, I tried to implement some javascript to change the color of the button when clicking on it but had some difficulty.
* Tried to create an animation based on a tutorial I found [here](https://www.w3schools.com/css/css3_animations.asp) but had a bit of difficulty making the square go in a diamond shape which I origonally intended.
## Week 2
* Fixed one of my TODO tasks from last week which was to fix my button so that it is able to change colors whenever it clicks. Read through [this](https://www.w3schools.com/js/) tutorial as well as I watched [this](https://www.youtube.com/watch?v=_GTMOmRrqkU&t=1516s&ab_channel=devdojo) on javascript which helped me grasp a better understanding on how javascript works.
* Deleted the animated square as it messed up the screen whenever opened but will mess around with it later on in the portfolio to try and add some cool effect potentially.
* Created a calculator in my origonal website which takes in two numbers from two different input boxes that adds/subtracts/multiplies/ or divides depending on the math symbol you choose in the dropdown box. It then computes the answer placing it in another box. I originally used document.write to display the answer but it would constantly refresh to a new page with the answer. I looked online for a bit of help and found [this](https://www.tutorialspoint.com/how-to-output-javascript-into-a-textbox) guide which helped me output my javascript to a textbox.
* Tried to create a page with full functionality of a dropdown menu box from a hamburger button but got a bit confused along the way with the process of everything merging together. I did learn a couple things from the tutorial such as a css selector called hover which can do things such as change the color of elements when hovered over.
* Followed the tutorial to create tic-tac-toe in react from the guide listed above and learned about the overall process of react and the idea of props as well as componenet states which allows a componenet to remember things such as being clicked
* Read this [guide](https://www.freecodecamp.org/news/learn-the-bootstrap-4-grid-system-in-10-minutes-e83bfae115da/) that a student linked me as I was having a bit of trouble understanding the functionality of bootstrap and learned how much time bootstrap saves you and helps in terms of styling and overall layout.
* Started the inital creation of my calculator with function buttons and the ability to calculate many different numbers instead of just two. The idea is to make the math problems look like [this](https://apps.apple.com/us/app/math-drills-math-flash-cards/id1498107670).
## Week 3
* Created a basic outline of a calculator function but ended up deleting it after I had alot of trouble mapping out the inital idea.
* Created a react app with a flashcard where whenever you click enter, it gives you a random element in the list. This is only temporary to make it work for now until I figure out how to setup the buttons properly so that only problems of a certian type will be given based on user input.
* Watched Dr.Barts video and spent many many hours creating my own card game but had many issues. A big issue I had was how to extract the data from the input and compare it to the actual answer. I tried everything from input boxes, buttons etc and had a bit of trouble implementing it.
## Week 4
* Added a function called handleKeyPress which would check if the entered value was correct compared to the cards actual value.
* Updated the function so that it was able to go to the next card after a correct answer was submitted.
* Updated handleKeyPress by setting the value of the textbox to a state variable called student answer so that whenever you submit an answer, it would clear the textbox for you as the values would never go away causing the answer after the first problem to constantly fail. After many hours of headaches, I figured out that I had to get the value of the keypress as an HTMLInputElement as there were errors with the types.
* Changed the textarea to a textbox as the textarea was too big.
* Added 4 functions called setCardAdd, ....Sub, ...Mul,...Div as I wanted to be able to call these after grabbing a number value from a button click which would trigger one of these functions changing the cardKind.
* Ended up creating a new component called CardKindSelector where it updates the state of a variable called cardKind which represents the current kind of card that is meant to be displayed. I then passed this into the displayCard function where it will then get a random card of that cardkind after entering the correct answer. This was made up of radio buttons instead as the other plan of making four buttons and coding them individually was kind of a mess.
# TODO
## Week 1
* ~~Need to work on my function changeColor on click so that the color of the button will change once clicked.~~
* ~~Need to fix the animation so that it doesnt break and goes in a diamond shape then proceedes to go back in the opposite direction with the colors going in reverse as well infinitely looping.~~
* ~~I would like to try and soon work on making a calculator as well as a pig latin translator. A calculator is something ive always wanted to try and recreate so I could understand the fundamentals so I am excited to work on that.~~
## Week 2
* Plan on upscaling my calculator from two text box inputs to an actual clickable calculator that can calculate many different numbers. Will also work on making it look like an actual calculator in terms of structure, shape and colors. Really want to also add the ability to click a button and have window open where the calculator will also take in written problems instead of just entered through pushing buttons.
* Implementing bootstrap into my calculator to help the overall layout making it clean and organized.
* Potentially try and implement a simple version of black jack.
## Week 
* Find out how to make the math problems look like [this](https://apps.apple.com/us/app/math-drills-math-flash-cards/id1498107670) in terms of layout with one number on top of the symbol which is on top of the last number. Will most likely use [this](https://www.youtube.com/watch?v=F2JCjVSZlG0&t=1999s&ab_channel=freeCodeCamp.org) tutorial and make it into 4 choices as an input comparision is a bit hard at first 
